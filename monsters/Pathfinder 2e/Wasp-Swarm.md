---
noteType: pf2eMonster
tags: 
  - pf2e/creature/type/animal
  - pf2e/creature/level/4
statblock: true
statblock-link: "#Wasp Swarm"
name: "Wasp Swarm"
hp: 45
ac: 18
modifier: 10
level: 4
---
### Wasp Swarm
```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B1"
name: "Wasp Swarm"
level: "Creature 4"
alignment: "N"
size: "Large"
trait_03: "Animal"
trait_04: "Swarm"
perception:
  - name: "Perception"
    desc: "Perception +10; __darkvision__;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +12 (1d20+12); "
abilityMods: [-4, 4, 2, -5, 2, -1]

abilities_bot:
  - name: "Swarming Stings"
    desc: "⬻  Each enemy in the swarm's space takes 1 (2d8) piercing damage (DC 21 basic Reflex save) and is exposed to wasp venom. A successful save negates the poison exposure."
  - name: "Wasp Venom"
    desc: " ([[poison]]);  __Saving Throw__ DC 21 Fortitude. __Maximum Duration__ 6 rounds __Stage 1__ 1 (1d6) poison (1 round) __Stage 2__ 1 (2d6) poison and [[clumsy|clumsy 2]] (2 rounds)"

speed: 20 feet, fly 40 feet

ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__: +10 (1d20+10); __Ref__: +12 (1d20+12); __Will__: +8 (1d20+8);"
health:
  - name: HP
    desc: "45;  __Immunities__ precision, swarm mind; __Weaknesses__ area damage 5, splash damage 5;"


attacks:

sourcebook: "_Bestiary_, page 324."
```

### Encounter
```encounter-table
name: Wasp Swarm
creatures:
  - 1: Wasp Swarm
```