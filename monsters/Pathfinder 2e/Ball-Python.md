---
noteType: pf2eMonster
tags: 
  - pf2e/creature/type/animal
  - pf2e/creature/level/1
statblock: true
statblock-link: "#Ball Python"
name: "Ball Python"
hp: 20
ac: 16
modifier: 6
level: 1
---
### Ball Python
```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B1"
name: "Ball Python"
level: "Creature 1"
alignment: "N"
size: "Medium"
trait_03: "Animal"
perception:
  - name: "Perception"
    desc: "Perception +6; __low-light vision__, __imprecise scent 30__;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +6 (1d20+6); __Athletics__: +6 (1d20+6); __Stealth__: +6 (1d20+6); __Survival__: +4 (1d20+4); "
abilityMods: [3, 3, 3, -4, 1, -2]

abilities_mid:
  - name: "Tighten Coils"
    desc: "⬲ __Trigger__ A creature [[grabbed|grabbed]] or [[restrained|restrained]] by the ball python attempts to [[Escape]]. __Effect__  The DC of the [[Escape]] check is increased by 2."
abilities_bot:
  - name: "Constrict"
    desc: "⬻  1 (1d8) bludgeoning, DC 17."
  - name: "Wrap in Coils"
    desc: "⬻ __Requirements__ A Medium or smaller creature is [[grabbed|grabbed]] or [[restrained|restrained]] in the ball python's jaws.  __Effect__  The ball python moves the creature into its coils, freeing its jaws to make attacks, then uses Constrict against the creature. The ball python's coils can hold one creature."

speed: 20 feet, climb 20 feet, swim 20 feet

ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__: +8 (1d20+8); __Ref__: +10 (1d20+10); __Will__: +4 (1d20+4);"
health:
  - name: HP
    desc: "20; "


attacks:
  - name: Melee
    desc: "⬻ jaws +8 __Damage__ 1 (1d8+3) piercing plus Grab"

sourcebook: "_Bestiary_, page 302."
```

### Encounter
```encounter-table
name: Ball Python
creatures:
  - 1: Ball Python
```