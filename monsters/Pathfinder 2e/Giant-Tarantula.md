---
noteType: pf2eMonster
tags: 
  - pf2e/creature/type/animal
  - pf2e/creature/level/6
statblock: true
statblock-link: "#Giant Tarantula"
name: "Giant Tarantula"
hp: 135
ac: 21
modifier: 14
level: 6
---
### Giant Tarantula
```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B1"
name: "Giant Tarantula"
level: "Creature 6"
alignment: "N"
size: "Large"
trait_03: "Animal"
perception:
  - name: "Perception"
    desc: "Perception +14; __darkvision__;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +9 (1d20+9); __Athletics__: +16 (1d20+16); __Stealth__: +11 (1d20+11); "
abilityMods: [6, 1, 5, -5, 2, -4]

abilities_bot:
  - name: "Hair Barrage"
    desc: "⬺  The tarantula flicks its legs, flinging spiky hairs in a 15-foot cone. This deals 1 (4d6) piercing damage with a DC 25 basic Reflex save."
  - name: "Giant Tarantula Venom"
    desc: " ([[poison]]);  __Saving Throw__ DC 23 Fortitude. __Maximum Duration__ 8 rounds __Stage 1__ 1 (1d6) poison (1 round) __Stage 2__ 1 (1d6) poison, [[flat-footed|flat-footed]], and [[clumsy|clumsy 1]] (1 round) __Stage 3__ 1 (1d6) poison, [[flat-footed|flat-footed]], and [[clumsy|clumsy 2]] (null) __Stage 4__ 1 (1d6) poison and [[paralyzed|paralyzed]]. (1 round)"

speed: 30 feet, climb 30 feet

ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__: +15 (1d20+15); __Ref__: +13 (1d20+13); __Will__: +10 (1d20+10);"
health:
  - name: HP
    desc: "135; "


attacks:
  - name: Melee
    desc: "⬻ fangs +17 __Damage__ 1 (2d8+8) piercing plus giant tarantula venom"
  - name: Melee
    desc: "⬻ leg +17 ([[reach|reach 10 feet]]); __Damage__ 1 (1d12+8) bludgeoning plus Knockdown"

sourcebook: "_Bestiary_, page 307."
```

### Encounter
```encounter-table
name: Giant Tarantula
creatures:
  - 1: Giant Tarantula
```