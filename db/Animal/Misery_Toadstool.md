---
desc:
  behavior: "An advanced Toadstool variant with increased health, damage, and defense. It is summoned from a Misery Toadstool Cap, created by exploding a Volatile Canary near a Toadstool Cap. Its death guarantees a Glowcap Blueprint and a Napsack Blueprint. Charge levels at 0, 1–4, 5–7, and 8+ Sporecaps give 0/25/50/99% damage reduction and 150/175/225/300 damage, with 3.5/3/2.5/2-second attacks."
identity:
  title: Misery Toadstool
  wikiPage: Toadstool
mob:
  attackPeriod: 3.5 / 3 / 2.5 / 2 by charge
  attackRange: 7; Spore Bomb targets players within 10
  damage: 150 / 175 / 225 / 300 by charge
  drops: "Guaranteed Glowcap Blueprint and Napsack Blueprint; Shroom Skin at 70%, 40%, and 20% health"
  health: "99,999"
  iceStaff: "4 casts initially; one additional cast after each thaw, up to 6"
  introduced: Bonus Update after A New Reign
  protection: "0% / 25% / 50% / 99% damage reduction by Sporecap charge"
  sleepDart: "4"
  spawnCode: toadstool_dark
  spawnFrom: Chop a Misery Toadstool Cap in the Caves
  specialAbility: Same behavior as Toadstool; spawns differently colored Boomshrooms and Sporecaps
  walkSpeed: 0.6 / 0.8 / 1.2 / 3.2 by Sporecap charge
roles:
  roles:
  - DST-Specific Pages
  - Boss Monsters
  - A New Reign
  - Cave Creatures
  - Object Destroyers
  - Earthshakers
ANIMAL_DROPS:
- Item/Shroom_Skin
- Item/Glowcap_Blueprint
- Item/Napsack_Blueprint
ANIMAL_SPAWNS_STRUCTURE:
- Structure/Boomshroom
- Structure/Sporecap
- Structure/Misery_Boomshroom
- Structure/Misery_Sporecap
ANIMAL_VARIANT_OF:
- Animal/Toadstool
---

# Animal/Misery_Toadstool
