---
desc:
  behavior: "A mineable cave formation with Full, Medium, and Low states. Each state has its own mineral drop table; mining lowers its appearance but retains the starting state's loot table."
identity:
  title: Stalagmite
  wikiPage: "Stalagmite/DST#Stalagmite"
info:
  biome: Caves
  renew: No
  resources: "Full: 3 Rocks, 1.6 Flint, 1.25 Gold Nugget, 0.05 Blue Gem, 0.05 Red Gem, 0.1 Fossil; Medium: 2 Rocks, 1.6 Flint, 0.5 Gold Nugget, 0.1 Fossil; Low: 1 Rock, 1.3 Flint, 0.5 Gold Nugget, 0.1 Fossil"
  spawnCode: "\"stalagmite_full\", \"stalagmite_med\", \"stalagmite_low\""
  tool: "Can be Mined with a Pickaxe, Opulent Pickaxe, or Pick/Axe"
roles:
  roles:
  - minerals
  - Structures
  - Mineable Objects
  - Naturally Spawning Objects
  - Resources
  - Non-Renewable
  - Non-Flammable
  - Caves
STRUCTURE_HAS_VARIANT:
- Structure/Tall_Stalagmite
YIELDS:
- Item/Rocks
- Item/Flint
- Item/Gold_Nugget
- Item/Blue_Gem
- Item/Red_Gem
- Item/Fossil_Fragment
---

# Structure/Stalagmite
