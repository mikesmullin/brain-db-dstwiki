---
desc:
  behavior: "A Shadow Rift cave mob that disguises itself as a duplicate of an eligible equippable inventory item without changing the real item. Most interactions reveal it; it also reveals automatically after roughly one to two days. Containers, stackable items, heavy items, carryable small creatures, and already mimicked items are ineligible. Haunting it reveals it."
identity:
  title: Mimicreep
  wikiPage: Mimicreep
mob:
  drops: 1 Nightmare Fuel when killed after reveal; WX-78 module spawns have no loot
  health: "100"
  mobSanity: "-10 on reveal"
  runSpeed: "6"
  spawnCode: itemmimic_revealed
  spawnFrom: Nighttime in the Caves while the Shadow Rift is active; disguises itself as an eligible carried equippable item
  specialAbility: "Creates an identical nearby duplicate of an eligible item; revealing it startles the triggering player and drains 10 Sanity. Once revealed, it flees and can disguise itself again; stepping near it shortly after reveal kills it instantly. Up to 10 naturally spawned disguised Mimicreeps can exist. A socketed Possessed Shadow Atrium grants reveal immunity and periodically creates revealed, no-loot Mimicreeps."
roles:
  roles:
  - DST-Specific Pages
  - Shadow Aligned
  - Mob
ANIMAL_DROPS:
- Item/Nightmare_Fuel
---

# Animal/Mimicreep
