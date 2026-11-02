---
desc:
  behavior: "A Lumpy Evergreen form of the Treeguard. It has the same combat behavior and size-scaled stats as a normal Treeguard, but has a distinct appearance."
identity:
  title: Lumpy Treeguard
  wikiPage: Treeguard
mob:
  attackPeriod: "3"
  attackRange: 2.1 / 3.0 / 3.75 by size
  damage: 35 / 50 / 62 to players; 105 / 150 / 186 to mobs by size
  drops: 1 Monster Meat and 6 Living Logs
  health: 1400 / 2000 / 2500 by size
  iceStaff: 4 blasts
  mobSanity: "-100/min while fighting; -40/min otherwise"
  sleepDart: Sleep Darts; Pan Flute
  spawnCode: leif_sparse
  spawnFrom: Chance to appear when a Lumpy Evergreen is chopped; otherwise behaves like a normal Treeguard
  walkSpeed: 0.735 / 1.5 / 2.34375 by size
roles:
  roles:
  - Animals
  - Boss Monsters
  - Monsters
  - Neutral Creatures
  - Hostile Creatures
  - Surface Creatures
  - Lumpy Evergreen Variant
ANIMAL_DROPS:
- Item/Monster_Meat
- Item/Living_Log
ANIMAL_VARIANT_OF:
- Animal/Treeguard
SPAWNED_FROM_PLANT:
- Plant/Lumpy_Evergreen
---

# Animal/Lumpy_Treeguard
