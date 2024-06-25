---
noteType: pf2eMonster
tags: 
  - pf2e/creature/type/animal
  - pf2e/creature/level/5
statblock: true
statblock-link: "#Giant Moray Eel"
name: "Giant Moray Eel"
hp: 65
ac: 21
modifier: 11
level: 5
---
### Giant Moray Eel
```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B1"
name: "Giant Moray Eel"
level: "Creature 5"
alignment: "N"
size: "Large"
trait_03: "Animal"
trait_04: "Aquatic"
perception:
  - name: "Perception"
    desc: "Perception +11; __low-light vision__, __imprecise scent 30__;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +9 (1d20+9); __Athletics__: +13 (1d20+13); __Stealth__: +13 (1d20+13); "
abilityMods: [6, 2, 3, -4, 2, -1]

abilities_mid:
  - name: "Ambush"
    desc: "⬲ __Trigger__ A target creature passes within 20 feet of the giant moray eel's hiding place and has not detected the giant moray eel. __Effect__  The giant moray eel lunges out of its hiding place, Swims directly toward the triggering creature, and makes a jaws [[Strike]] against it. The target creature is [[flat-footed|flat-footed]] to this attack."
abilities_bot:
  - name: "Pharyngeal Jaws"
    desc: "⬺ __Requirements__ The giant moray eel has a creature [[grabbed|grabbed]] in its jaws.  __Effect__  The giant moray eel uses its second set of jaws to pull the prey into its gullet. The eel deals 1 (1d6+4) piercing damage to the [[grabbed|grabbed]] creature and gains a +2 circumstance bonus to its Swallow Whole attempts and to the DC for the creature to [[Escape]]. This effect ends if the target [[Escape|Escapes]] or the giant moray eel Swallows it Whole."
  - name: "Swallow Whole"
    desc: "⬻ ([[attack]]);  Small, 1 (1d6+6) bludgeoning, Rupture 12."

speed: 10 feet, swim 40 feet

ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__: +14 (1d20+14); __Ref__: +13 (1d20+13); __Will__: +9 (1d20+9);"
health:
  - name: HP
    desc: "65;  __Resistances__ bludgeoning 5, piercing 5"


attacks:
  - name: Melee
    desc: "⬻ jaws +15 ([[reach|reach 10 feet]]); __Damage__ 1 (2d6+8) piercing plus Grab"

sourcebook: "_Bestiary_, page 142."
```

### Encounter
```encounter-table
name: Giant Moray Eel
creatures:
  - 1: Giant Moray Eel
```