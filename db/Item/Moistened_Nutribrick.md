---
desc:
  behavior: "Wetting a Nutribrick creates this form; it spoils while wet and reverts to dry Nutribrick if it dries. A Watering Can can moisten it. Wormwood cannot eat it, but using it as fertilizer heals Wormwood."
identity:
  title: Moistened Nutribrick
  wikiPage: Nutribrick
item:
  burnTime: 1.5 minutes
  canBeBurned: Can be Burned
  description: "A wet, edible Nutribrick. It can be used as Crock Pot filler or fertilizer; Wormwood cannot eat it but receives healing from it."
  fertilize: Nutrients for Farm Soil; heals Wormwood by up to 32 Health over 32 seconds
  foodType: Generic
  heal: "1; Wormwood: 32 over 32 seconds"
  hunger: "18.75"
  sanity: "0"
  spawnCode: wx78_foodbrick
  spoil: 1 day
  stack: "40"
roles:
  roles:
  - Items
  - DST-Specific Pages
  - Food
  - Perishables
  - Fertilizer
ITEM_AFFECTS_CHARACTER:
- Character/Wormwood
ITEM_TRANSFORMS_INTO_ITEM:
- Item/Nutribrick
---

# Item/Moistened_Nutribrick
