---
desc:
  behavior: "Houses one Bird, which can be swapped at any time. Caged Birds slowly starve after roughly 20 days depending on temperature. Feeding Seeds or Crop Seeds has a 33% chance to produce Guano; feeding farm crops yields crop seeds; feeding meat-based food produces an Egg. A dead bird becomes a fresh Morsel, then a skeleton; cleaning the cage after it becomes a skeleton yields Rot. Caged birds never drop feathers."
identity:
  title: Birdcage
  wikiPage: Birdcage/DST
info:
  capacity: 1 bird
  crafting: "6 Gold Nuggets, 2 Papyrus, and 2 Seeds; prototype at an Alchemy Engine"
  description: A happy home for your avian friends.
  spawnCode: birdcage
  tier: Alchemy Engine
roles:
  roles:
  - Structures
  - Science Tier 2
  - Craftable Items and Structures on DST
  - Science
  - "Food & Gardening Filter"
  - Birds
  - Non-Flammable
  - Mob Housing
STRUCTURE_ACCEPTS_ITEM:
- Item/Monster_Meat
- Item/Cooked_Monster_Meat
- Item/Monster_Jerky
STRUCTURE_AWARDS_ITEM:
- Item/Egg
STRUCTURE_CRAFTED_FROM:
- Item/Gold_Nugget
- Item/Papyrus
- Item/Seeds
STRUCTURE_HOUSES_ANIMAL:
- Animal/Crow
- Animal/Redbird
- Animal/Snowbird
- Animal/Canary
- Animal/Misshapen_Bird
- Animal/Moonblind_Crow
YIELDS:
- Item/Seeds
- Item/Egg
- Item/Morsel
- Item/Rot
---

# Structure/Birdcage
