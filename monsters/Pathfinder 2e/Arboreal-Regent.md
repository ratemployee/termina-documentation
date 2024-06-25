---
noteType: pf2eMonster
tags: 
  - pf2e/creature/type/plant
  - pf2e/creature/level/8
statblock: true
statblock-link: "#Arboreal Regent"
name: "Arboreal Regent"
hp: 150
ac: 26
modifier: 18
level: 8
---
### Arboreal Regent
```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B1"
name: "Arboreal Regent"
level: "Creature 8"
alignment: "NG"
size: "Huge"
trait_03: "Plant"
perception:
  - name: "Perception"
    desc: "Perception +18; __low-light vision__;"
languages: "Arboreal, Common, Sylvan;  speak with plants;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +19 (1d20+19); __Diplomacy__: +16 (1d20+16); __Intimidation__: +16 (1d20+16); __Nature__: +18 (1d20+18); __Stealth__: +11 (1d20+11), (Stealth: +21 (1d20+21) in forests); "
abilityMods: [7, -1, 6, 1, 4, 2]

abilities_mid:
  - name: "Axe Vulnerability"
    desc: "  The arboreal regent takes 5 additional damage from axes."
abilities_bot:
  - name: "Awaken Tree"
    desc: "⬺ ([[concentrate]], [[primal]]);  The arboreal regent causes a tree within 180 feet to uproot itself and fight as a minion using the statistics for an awakened tree. The arboreal regent can control up to two awakened trees at a time, and it can issue commands to both trees as a single action, which has the [[concentrate]] and [[auditory]] traits."
  - name: "Sunder Objects"
    desc: "  When an arboreal regent damages an item or structure, it deals an additional 1 (2d10) damage to that item or structure."
  - name: "Throw Rock"
    desc: "⬻ "

speed: 25 feet

ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__: +20 (1d20+20); __Ref__: +11 (1d20+11); __Will__: +16 (1d20+16);"
health:
  - name: HP
    desc: "150;  __Weaknesses__ axe vulnerability , fire 10; __Resistances__ bludgeoning 5, piercing 5"


attacks:
  - name: Melee
    desc: "⬻ branch +19 ([[reach|reach 15 feet]]); __Damage__ 1 (2d12+7) bludgeoning"
  - name: Melee
    desc: "⬻ root +19 ([[trip]]); __Damage__ 1 (2d8+7) bludgeoning"
  - name: Ranged
    desc: "⬻ rock +19 ([[brutal]], [[range increment|range increment 120 feet]]); __Damage__ 1 (2d10+7) bludgeoning"

spellcasting:
  - name: "Primal Innate Spells"
    desc: "DC 26; __Constant__ ;"
sourcebook: "_Bestiary_, page 25."
```

### Encounter
```encounter-table
name: Arboreal Regent
creatures:
  - 1: Arboreal Regent
```