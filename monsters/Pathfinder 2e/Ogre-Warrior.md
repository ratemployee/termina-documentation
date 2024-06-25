---
noteType: pf2eMonster
tags: 
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2e/creature/level/3
statblock: true
statblock-link: "#Ogre Warrior"
name: "Ogre Warrior"
hp: 50
ac: 17
modifier: 5
level: 3
---
### Ogre Warrior
```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B1"
name: "Ogre Warrior"
level: "Creature 3"
alignment: "CE"
size: "Large"
trait_03: "Giant"
trait_04: "Humanoid"
perception:
  - name: "Perception"
    desc: "Perception +5; __darkvision__;"
languages: "Jotun; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +12 (1d20+12); "
abilityMods: [5, -1, 4, -2, 0, -2]


speed: 25 feet

ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__: +11 (1d20+11); __Ref__: +6 (1d20+6); __Will__: +5 (1d20+5);"
health:
  - name: HP
    desc: "50; "


attacks:
  - name: Melee
    desc: "⬻ ogre hook +12 ([[deadly|deadly 1d10]], [[reach|reach 10 feet]], [[trip]]); __Damage__ 1 (1d10+7) piercing"
  - name: Ranged
    desc: "⬻ javelin +6 ([[thrown|thrown 30 feet]]); __Damage__ 1 (1d6+7) piercing"

sourcebook: "_Bestiary_, page 252."
```

### Encounter
```encounter-table
name: Ogre Warrior
creatures:
  - 1: Ogre Warrior
```