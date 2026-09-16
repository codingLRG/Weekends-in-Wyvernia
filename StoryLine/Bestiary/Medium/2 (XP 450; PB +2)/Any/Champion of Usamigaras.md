---
Source: "QftIS"
Size: "Medium"
Type: "Humanoid"
Alignment: "chaotic neutral"
AC: "12 (15 with mage armor)"
HP: "33 (6d8 + 6)"
Strength: 10
Dexterity: 14
Constitution: 12
Intelligence: 17
Wisdom: 14
Charisma: 15
Damage Vulnerabilities: 
Damage Resistances: 
Damage Immunities: 
Condition Immunities: 
Languages: "Common"
CR: "2 (XP 450; PB +2)"
Environment: "Any"
---

# Champion of Usamigaras - 2 (XP 450; PB +2)
```mermaid
flowchart TD
	castedMadness{{Have you casted Crown of Madness?}} -->|yes|multiAttack{{Have you multiattacked?}}
	castedMadness -->|no|castMad[[Cast Crown of Madness]]
	castMad --> multiAttack
	multiAttack -->|yes|exit[[End turn]]
	multiAttack -->|no|spells{{Have you casted a spell per turn?}}
	spells -->|no|cast[[Cast one]]
	cast --> multiAttack
	spells -->|yes|aB[[Arcane burst]]
	aB --> multiAttack
```
