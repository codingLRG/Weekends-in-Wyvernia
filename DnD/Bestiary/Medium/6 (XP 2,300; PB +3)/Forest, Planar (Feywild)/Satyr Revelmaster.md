---
Source: "MM'25"
Size: "Medium"
Type: "Fey"
Alignment: "chaotic neutral"
AC: 17
HP: "82 (15d8 + 15)"
Strength: 12
Dexterity: 18
Constitution: 12
Intelligence: 12
Wisdom: 14
Charisma: 17
Damage Vulnerabilities: 
Damage Resistances: 
Damage Immunities: 
Condition Immunities: 
Languages: "Common, Elvish, Sylvan"
CR: "6 (XP 2,300; PB +3)"
Environment: "Forest, Planar (Feywild)"
---

# Satyr Revelmaster - 6 (XP 2,300; PB +3)
```mermaid
flowchart TD
	bigBad{{Concerning high damage threat?}} -->|yes|FMF[Fey Melody - Frightening]
	bigBad -->|no|inMelee{{Can you hit a melee attack?}}
		inMelee -->|yes|multiMelee{{Can you hit up to 3 dif units?}}
			multiMelee -->|yes|HM[Hit Multiple]
			multiMelee -->|no|HS[Punchy]
		inMelee -->|no|FMC[Fey Melody - Charm]
```
