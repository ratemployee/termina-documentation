---
noteType: pf2eMonster
tags: 
  - pf2e/creature/type/dragon
  - pf2e/creature/level/13
statblock: true
statblock-link: "#Adult Bronze Dragon"
name: "Adult Bronze Dragon"
hp: 260
ac: 34
modifier: 23
level: 13
---
### Adult Bronze Dragon
```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B1"
name: "Adult Bronze Dragon"
level: "Creature 13"
alignment: "LG"
size: "Huge"
trait_03: "Amphibious"
trait_04: "Dragon"
trait_05: "Water"
perception:
  - name: "Perception"
    desc: "Perception +23; __darkvision__, __imprecise scent 60__;"
languages: "Aquan, Common, Draconic, Dwarven, Elven, Gnomish;  speak with animals;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +22 (1d20+22); __Arcana__: +28 (1d20+28); __Athletics__: +24 (1d20+24); __Diplomacy__: +23 (1d20+23); __Intimidation__: +23 (1d20+23); __Occultism__: +24 (1d20+24); __Stealth__: +22 (1d20+22); "
abilityMods: [7, 3, 4, 5, 4, 4]

abilities_mid:
  - name: "Electricity Aura"
    desc: " ([[aura]], [[electricity]]);  10 feet, 1 (1d12) electricity damage. The bronze dragon can turn this aura on or off using a single action, which has the [[concentrate]] trait, and it can choose to not affect allies with the aura."
  - name: "Frightful Presence"
    desc: " ([[aura]], [[emotion]], [[fear]], [[mental]]);  90 feet, DC 31."
  - name: "Attack of Opportunity"
    desc: "⬲  Jaws only."
abilities_bot:
  - name: "Breath Weapon"
    desc: "⬺  The bronze dragon breathes in one of two ways. The dragon can't use Breath Weapon again for 1 (1d4) rounds.<ul class='inner-bullet-list'><li>__Lightning__ (arcane, electricity, evocation); The dragon breathes lightning in a 80-foot line that deals 1 (8d12) electricity damage (DC 33 basic Reflex save).</li><li>__Repulsion Gas__ (abjuration, arcane, incapacitation, mental); The dragon breathes a 80-foot line of repulsive gas. Each creature in the area must succeed at a DC 33 Will save or become [[fleeing|fleeing]] from the dragon for 1 round (or 2 rounds on a critical failure).</li></ul>"
  - name: "Draconic Frenzy"
    desc: "⬺  The dragon makes two claw [[Strike|Strikes]] and one tail [[Strike]] in any order."
  - name: "Draconic Momentum"
    desc: "  When the dragon scores a critical hit with a [[Strike]], it recharges its Breath Weapon."
  - name: "Water Mastery"
    desc: " ([[arcane]], [[transmutation]], [[water]]);  For up to 60 minutes per day, the dragon, along with allied creatures and vessels within 50 feet, can move at double their normal Speed in water."

speed: 40 feet, fly 140 feet, swim 50 feet

ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__: +24 (1d20+24); __Ref__: +23 (1d20+23); __Will__: +26 (1d20+26);"
health:
  - name: HP
    desc: "260;  __Immunities__ electricity, paralyzed, sleep;"


attacks:
  - name: Melee
    desc: "⬻ jaws +28 ([[electricity]], [[magical]], [[reach|reach 15 feet]]); __Damage__ 1 (2d12+15) piercing plus 1 (1d12) electricity"
  - name: Melee
    desc: "⬻ claw +28 ([[agile]], [[magical]], [[reach|reach 10 feet]]); __Damage__ 1 (2d10+15) slashing"
  - name: Melee
    desc: "⬻ tail +26 ([[magical]], [[reach|reach 15 feet]]); __Damage__ 1 (1d10+13) bludgeoning"

spellcasting:
  - name: "Arcane Innate Spells"
    desc: "DC 33; __2nd__ [[obscuring mist]] (at will); __Constant__ __(2nd)__ [[speak with animals]];"
sourcebook: "_Bestiary_, page 120."
```

### Encounter
```encounter-table
name: Adult Bronze Dragon
creatures:
  - 1: Adult Bronze Dragon
```