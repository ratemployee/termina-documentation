---
noteType: pf2eMonster
tags: 
  - pf2e/creature/type/elemental
  - pf2e/creature/level/7
statblock: true
statblock-link: "#Salamander"
name: "Salamander"
hp: 125
ac: 26
modifier: 15
level: 7
---
### Salamander
```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B1"
name: "Salamander"
level: "Creature 7"
alignment: "CE"
size: "Medium"
trait_03: "Elemental"
trait_04: "Fire"
perception:
  - name: "Perception"
    desc: "Perception +15; __darkvision__;"
languages: "Common, Ignan; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +12 (1d20+12); __Athletics__: +17 (1d20+17); __Crafting__: +15 (1d20+15), (Crafting: +17 (1d20+17) for blacksmithing); __Deception__: +12 (1d20+12); __Intimidation__: +14 (1d20+14); __Society__: +13 (1d20+13); "
abilityMods: [4, 3, 4, 2, 2, 1]

abilities_mid:
  - name: "Attack of Opportunity"
    desc: "⬲ "
abilities_top:
  - name: Items
    desc: "+1 ranseur;"
abilities_bot:
  - name: "Armor of Flames"
    desc: "⬻  The salamander stokes its internal flames. Until the start of its next turn, it gains a +2 circumstance bonus to AC, and when an adjacent creature touches it or hits it with a physical attack, that creature takes 1 (2d6) [[persistent damage|persistent fire damage]] unless it succeeds at a DC 25 Reflex save."
  - name: "Constrict"
    desc: "⬻  1 (1d8+4) bludgeoning plus 1 (1d6) fire, DC 25."

speed: 20 feet

ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__: +15 (1d20+15); __Ref__: +16 (1d20+16); __Will__: +13 (1d20+13);"
health:
  - name: HP
    desc: "125;  __Immunities__ bleed, fire, poison, paralyzed, sleep; __Weaknesses__ cold 10;"


attacks:
  - name: Melee
    desc: "⬻ ranseur +18 ([[disarm]], [[magical]], [[reach|reach 10 feet]]); __Damage__ 1 (2d10+7) piercing"
  - name: Melee
    desc: "⬻ tail +17 ([[agile]], [[reach|reach 10 feet]]); __Damage__ 1 (1d8+7) bludgeoning plus 1 (1d6) fire and Grab"

sourcebook: "_Bestiary_, page 148."
```

### Encounter
```encounter-table
name: Salamander
creatures:
  - 1: Salamander
```