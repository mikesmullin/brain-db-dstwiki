---
desc:
  behavior: "Place a Fossil Fragment on the ground and add seven more to assemble an Odd Skeleton. Its form is fixed at the fifth fragment; hammer an incorrect one to recover the pieces and begin again. Only the correct form can be revived with a Shadow Atrium. When an Atrium is nearby, the correct form always assembles."
identity:
  title: Odd Skeleton
  wikiPage: Fossils
info:
  resources: "Built from 8 Fossil Fragments; the design is determined when the fifth fragment is placed: 60% correct, 20% each incorrect form. Placement radius: 3.2 units"
  spawnCode: fossil_stalker
  tool: Can be Hammered; returns all Fossil Fragments used
roles:
  roles:
  - Structures
  - Ancient
  - Shadow
SPAWNS:
- Animal/Reanimated_Skeleton
- Animal/Forest_Reanimated_Skeleton
- Animal/Caves_Reanimated_Skeleton
STRUCTURE_CRAFTED_FROM:
- Item/Fossil_Fragment
STRUCTURE_HAS_VARIANT:
- Structure/Wrong_Odd_Skeleton_1
- Structure/Wrong_Odd_Skeleton_2
STRUCTURE_REPAIRED_BY:
- Item/Fossil_Fragment
---

# Structure/Odd_Skeleton
