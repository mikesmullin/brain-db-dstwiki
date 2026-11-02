---
desc:
  behavior: "A naturally generated entrance to the Caves. Opening a plugged Sinkhole reveals a staircase and spawns up to six Batilisks quickly at Dusk; killed Batilisks respawn at one per minute until the limit is reached. Default worlds have 10 Sinkholes, each paired with one Cave Stair. The Sinkhole cannot be destroyed."
identity:
  title: Sinkhole
  wikiPage: Sinkhole/DST
info:
  biome: "Forest, Mosaic, Marsh; also several guaranteed world-generation biomes"
  renew: No
  resources: Mining the plugged cover gives Flint and Rocks
  spawnCode: "cave_entrance; opened: cave_entrance_open"
  tool: Can be Mined; 6 Pickaxe hits to open
roles:
  roles:
  - Mineable Objects
  - Naturally Spawning Objects
  - Resources
  - Non-Renewable
  - Mob Spawning Entities
  - Mob Housing
  - Portal
SPAWNS:
- Animal/Batilisk
STRUCTURE_DROPS:
- Item/Flint
- Item/Rocks
STRUCTURE_PAIRED_WITH:
- Structure/Stairs
---

# Structure/Sinkhole
