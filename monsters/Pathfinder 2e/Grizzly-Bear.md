---
noteType: pf2eMonster
tags: 
  - pf2e/creature/type/animal
  - pf2e/creature/level/3
statblock: true
statblock-link: "#Grizzly Bear"
name: "Grizzly Bear"
hp: 45
ac: 19
modifier: 10
level: 3
---
### Grizzly Bear
```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B1"
name: "Grizzly Bear"
level: "Creature 3"
alignment: "N"
size: "Large"
trait_03: "Animal"
perception:
  - name: "Perception"
    desc: "Perception +10; __low-light vision__, __imprecise scent 30__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +11 (1d20+11); __Survival__: +8 (1d20+8); "
abilityMods: [4, 1, 5, -4, 1, -2]

abilities_bot:
  - name: "Mauler"
    desc: "  The grizzly bear gains a +2 circumstance bonus to damage rolls against creatures it has [[grabbed|grabbed]]."
  - name: "Rush"
    desc: "⬺  The grizzly bear [[Stride|Strides]] and makes a [[Strike]] at the end of that movement. During the [[Stride]], the grizzly bear gains a +10-foot circumstance bonus to its Speed."

speed: 35 feet

ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__: +12 (1d20+12); __Ref__: +6 (1d20+6); __Will__: +8 (1d20+8);"
health:
  - name: HP
    desc: "45; "


attacks:
  - name: Melee
    desc: "⬻ jaws +11 __Damage__ 1 (2d8+4) piercing"
  - name: Melee
    desc: "⬻ claw +11 ([[agile]]); __Damage__ 1 (1d10+4) slashing plus Grab"

sourcebook: "_Bestiary_, page 40."
```

### Encounter
```encounter-table
name: Grizzly Bear
creatures:
  - 1: Grizzly Bear
```