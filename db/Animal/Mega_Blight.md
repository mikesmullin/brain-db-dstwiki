---
desc:
  behavior: "A giant passive, two-headed shadow centipede that appears in the Caves after a Shadow Rift opens. It wanders rather than pursuing targets, grows by eating Miasma, and destroys objects in its path. It cannot be harmed while upright; a falling Boulderbough boulder flips it onto its back and makes it vulnerable for about 7 seconds. Each segment drains sanity, and every segment drops loot when it is defeated. A player with Shadow Affinity sees its alternate name, Ripple."
  tips: A running player can outrun its walking speed. Lure it under a Boulderbough and chop the tree to flip it; it takes a fresh boulder for each vulnerability window.
identity:
  title: Mega Blight
  wikiPage: Mega Blight
mob:
  damage: 75 to players; 150 to mobs
  diet: "Miasma; each head eats 5 clouds to grow a segment, with a 60-second cooldown per head"
  drops: "Per segment: 1 Dreadstone with 66% chance of a second and 34% chance of a third; 2 Pure Horror with 25% chance of a third; 2 Nightmare Fuel with 50% chance of a third and 25% each for a fourth and fifth. Average per segment: 2 Dreadstone, 2.25 Pure Horror, 3 Nightmare Fuel."
  health: 2000 shared by all segments
  mobSanity: "-40/min per segment at point-blank range; scales with distance and each segment contributes"
  planarDamage: "50"
  planarEntityProtection: Yes
  runSpeed: 10 (unused by its AI)
  spawnCode: shadowthrall_centipede_controller
  spawnFrom: Centipede Nest set piece in the Fumarole Biome while a Shadow Rift is active; only appears while the spawner is unloaded
  specialAbility: "Spawns with 7 segments (two heads and five body segments) and grows to at most 20. Wanders without pursuing or attacking on purpose; it can move through the world without a home or leash. Each head seeks Miasma within 10 units; eating does not heal it. Contact destroys chop-, mine-, hammer-, and dig-able objects and deals 150 physical + 50 planar damage to living targets (players take half physical damage); Shadow entities are immune. All segments are invulnerable while upright. A Boulderbough boulder flips it for about 7 seconds, exposing a shared 2000-health pool. Only one exists at a time. Spawn and despawn checks happen while the Centipede Nest spawner is unloaded; it is removed when no Shadow Rift remains, subject to the area's load state."
  walkSpeed: "5"
roles:
  roles:
  - Shadow Rift
  - Shadow Thralls
  - Mobs
  - DST Exclusive
  - Shadow Aligned
  - Passive Creatures
ANIMAL_DROPS:
- Item/Dreadstone
- Item/Pure_Horror
- Item/Nightmare_Fuel
---

# Animal/Mega_Blight
