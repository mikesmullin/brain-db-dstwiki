---
desc:
  behavior: "A large tree monster that can appear from nearby Evergreens when trees are chopped. It is hostile to the woodcutter and follows its target until pacified by planting Pine Cones or enough trees nearby. It becomes neutral when pacified, sleeps at night, and has short, normal, and tall sizes whose health, damage, range, and speed scale with size."
identity:
  title: Treeguard
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
  spawnCode: leif
  spawnFrom: "Chopping an Evergreen has a 1.33% chance to spawn one from a nearby tree starting on Day 4; more can spawn as the world ages"
  walkSpeed: 0.735 / 1.5 / 2.34375 by size
roles:
  roles:
  - Animals
  - Boss Monsters
  - Monsters
  - Neutral Creatures
  - Hostile Creatures
  - Surface Creatures
ANIMAL_DROPS:
- Item/Monster_Meat
- Item/Living_Log
ANIMAL_HAS_VARIANT:
- Animal/Lumpy_Treeguard
---

# Animal/Treeguard
