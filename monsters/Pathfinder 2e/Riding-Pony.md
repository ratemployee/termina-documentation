---
noteType: pf2eMonster
tags: 
  - pf2e/creature/type/animal
  - pf2e/creature/level/0
statblock: true
statblock-link: "#Riding Pony"
name: "Riding Pony"
hp: 16
ac: 14
modifier: 4
level: 0
---
### Riding Pony
```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B1"
name: "Riding Pony"
level: "Creature 0"
alignment: "N"
size: "Medium"
trait_03: "Animal"
perception:
  - name: "Perception"
    desc: "Perception +4; __low-light vision__, __imprecise scent 30__;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +4 (1d20+4); __Athletics__: +7 (1d20+7); "
abilityMods: [3, 2, 3, -4, 2, 0]

abilities_mid:
  - name: "Buck"
    desc: "⬲  DC 15."
abilities_bot:
  - name: "Gallop"
    desc: "⬺  The riding pony [[Stride|Strides]] twice. It has a +10-foot circumstance bonus to its Speed during these [[Stride|Strides]]."

speed: 35 feet

ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__: +7 (1d20+7); __Ref__: +4 (1d20+4); __Will__: +4 (1d20+4);"
health:
  - name: HP
    desc: "16; "


attacks:
  - name: Melee
    desc: "⬻ hoof +5 __Damage__ 1 (1d4+3) bludgeoning"

sourcebook: "_Bestiary_, page 209."
```

### Encounter
```encounter-table
name: Riding Pony
creatures:
  - 1: Riding Pony
```