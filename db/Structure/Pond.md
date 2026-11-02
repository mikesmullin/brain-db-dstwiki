---
desc:
  behavior: "Fishing takes 4 seconds plus 4 seconds for each missing fish or eel. Ponds freeze in Winter once the temperature is low enough; frozen ponds do not spawn creatures and cannot be fished, but can be walked over. Surface ponds have 2–4 bank plants that cannot be picked, burn for Ashes, and regrow every Summer; Ruins ponds have Cave Lichen instead."
identity:
  title: Pond
  wikiPage: Pond
info:
  biome: Grasslands and Forests (common); Marsh; Ruins (Caves)
  description: "A small, naturally spawning freshwater fishing spot found in Grasslands, Forests, Marshes, and the Ruins."
  renew: Cannot be destroyed; regenerates one fish or eel every 160 seconds
  resources: Holds up to 10 Fish or Eels
  spawn: Green ponds spawn Frogs during the day; purple Marsh ponds spawn Mosquitoes at dusk and night; blue Ruins ponds contain Eels instead of Fish
  spawnCode: pond; pond_mos; pond_cave
  tool: Can be fished when not frozen
roles:
  roles:
  - Structures
  - Naturally Spawning Objects
  - Fishing
  - Water
PLANT_SPAWNS_FROM_STRUCTURE:
- Plant/Pond_Plant
SPAWNS:
- Animal/Frog
STRUCTURE_HAS_VARIANT:
- Structure/Marsh_Pond
- Structure/Cave_Pond
- Structure/Frozen_Pond
---

# Structure/Pond
