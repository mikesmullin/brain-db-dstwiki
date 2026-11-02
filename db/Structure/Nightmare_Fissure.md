---
desc:
  behavior: Nightmare Fissures change their light with the Nightmare Cycle and are strong locations for farming Nightmare Fuel. The Ancient Archives can cause fissures and Nightmare Ramparts to emerge at the Lunar Grotto entrance.
identity:
  title: Nightmare Fissure
  wikiPage: Nightmare Fissure/DST
info:
  description: "Acts like a Nightmare Light and can spawn one Shadow Creature at a time during Nightmare Phase: Terrorbeak, Crawling Horror, or Lurking Nightmare. Attacking one makes nearby Shadow Creatures attack together; closing the fissure despawns its spawned creatures. During an active Shadow Rift, approaching an eligible fissure can create a Miasma-surrounded Dreadstone Outcrop if none is active and none has been destroyed in the past three days; Ink Blights also spawn nearby. Lunar Grotto entrance fissures do not create outcrops or spawn Ink Blights."
  renew: Cannot be destroyed; naturally occurring fissures return at their locations
  source: Ruins and rarely in Caves on Stalagmite Terrain; several appear at the Lunar Grotto entrance after Archive Switch activation
  spawnCode: fissure (Stalagmite Terrain); fissure_lower (Ruins); fissure_grottowar (Lunar Grotto)
roles:
  roles:
  - DST-Specific Pages
  - Light Sources
  - Mob Spawning Entities
  - Nightmare State Indicator
  - Sanity Loss
  - Indestructible Object
  - Non-Flammable
  - Naturally Spawning Objects
STRUCTURE_SPAWNS_ANIMAL:
- Animal/Terrorbeak
- Animal/Crawling_Horror
- Animal/Lurking_Nightmare
- Animal/Ink_Blight
STRUCTURE_SPAWNS_WEATHER:
- Weather/Miasma
STRUCTURE_TRANSFORMS_INTO_STRUCTURE:
- Structure/Dreadstone_Outcrop
---

# Structure/Nightmare_Fissure
