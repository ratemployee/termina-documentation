---
noteType: pf2eMonster
tags: 
  - pf2e/creature/type/animal
  - pf2e/creature/level/1
statblock: true
statblock-link: "#Wolf"
name: "Wolf"
hp: 24
ac: 15
modifier: 7
level: 1
---
### Wolf
```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B1"
name: "Wolf"
level: "Creature 1"
alignment: "N"
size: "Medium"
trait_03: "Animal"
perception:
  - name: "Perception"
    desc: "Perception +7; __low-light vision__, __imprecise scent 30__;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +7 (1d20+7); __Athletics__: +5 (1d20+5); __Stealth__: +7 (1d20+7); __Survival__: +7 (1d20+7); "
abilityMods: [2, 4, 1, -4, 2, -2]

abilities_bot:
  - name: "Pack Attack"
    desc: "  The wolf's [[Strike|Strikes]] deal 1 (1d4) extra damage to creatures within reach of at least two of the wolf's allies."

speed: 35 feet

ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__: +6 (1d20+6); __Ref__: +9 (1d20+9); __Will__: +5 (1d20+5);"
health:
  - name: HP
    desc: "24; "


attacks:
  - name: Melee
    desc: "⬻ jaws +9 __Damage__ 1 (1d6+2) piercing plus Knockdown"

sourcebook: "_Bestiary_, page 334."
```

### Encounter
```encounter-table
name: Wolf
creatures:
  - 1: Wolf
```