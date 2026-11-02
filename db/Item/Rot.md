---
desc:
  behavior: "Produced when Food items other than Eggs spoil. Used as fertilizer, fuel, and a single-use fishing lure."
  tips: "As fertilizer, it adds nutrients to Farm Soil and can fertilize replanted Grass Tufts and Berry Bushes."
identity:
  title: Rot
  wikiPage: Rot/DST
item:
  bonusRange: "+2"
  burnTime: 15 sec
  canBeBurned: Can be Burned
  crafting: Wilson can transmute 6 Rot into Manure
  droppedBy: "Most perishable items (×1; 75% in Winter)"
  foodType: Generic
  heal: "-1 when eaten; Wormwood heals +4 over 4 seconds when fertilizing"
  hunger: "-10"
  lureCharm: "0.1"
  lureRadius: "2"
  perk: Fertilizer and Fuel
  sanity: "0"
  spawnCode: "\"spoiled_food\""
  stack: "40"
roles:
  roles:
  - Most perishable items
  - Fertilizer
  - Fuel
  - Flammable Objects
  - Health Loss
ANIMAL_DROPPED_BY:
- Animal/Possessed_Varg
HEALS:
- Character/Wormwood
USED_IN:
- Item/Manure
- Item/Compost_Wrap
---

# Item/Rot
