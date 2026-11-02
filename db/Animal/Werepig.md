---
desc:
  behavior: "A hostile Pig form that attacks nearby creatures, including other Pigs. It stops to eat ground food and transforms back to a Pig after about 4 game hours or at the start of the next day."
identity:
  title: Werepig
  wikiPage: Werepig/DST
mob:
  attackPeriod: "2"
  attackRange: "3"
  damage: "40"
  diet: "Meat, Veggie, Seeds, Generic, Goodies, Horrible, Raw; eats ground food and raw Mandrakes"
  drops: 2 Meat and 1 Pig Skin
  health: "525"
  iceStaff: "2"
  mobSanity: "-100"
  runSpeed: "7"
  sleepDart: "3"
  spawnCode: werepig
  spawnFrom: Pig or Guardian Pig during Full Moon or after eating 4 meat-based Monster Foods; Ghost haunting; Moon Stone event
  specialAbility: Hostile to nearby targets; produces Manure after eating Fruits or Vegetables; transforms back after about 4 game hours or at next day
  walkSpeed: "3"
roles:
  roles:
  - Animals
  - Hostile Creatures
  - Monsters
  - Surface Creatures
  - Full Moon
ANIMAL_DROPS:
- Item/Meat
- Item/Pig_Skin
ANIMAL_TRANSFORMS_INTO_ANIMAL:
- Animal/Pig
ANIMAL_VARIANT_OF:
- Animal/Pig
EATS:
- Item/Meat
- Item/Monster_Meat
- Item/Pig_Skin
- Item/Red_Cap
---

# Animal/Werepig
