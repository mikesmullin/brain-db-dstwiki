---
desc:
  behavior: "Fertilizes Farm Soil with 8 Growth Formula nutrients and triggers Wormwood's bloom for 1 minute. Returns an Empty Bottle when used."
  tips: "Ferments over 3 days through Fermenting, Fermented, and Super stages, increasing nutrient potency."
identity:
  title: Growth Formula Starter
  wikiPage: Growth Formula Starter
item:
  crafting: 1 Empty Bottle + 1 Kelp Frond + 1 Ashes
  description: Bottled nutrients from the sea.
  fertilize: "Adds 8 Growth Formula nutrient; triggers Wormwood's bloom for 1 minute"
  perk: Fertilize Farm
  spawnCode: "\"soil_amender\""
  spoil: 3 days to ferment through all stages
  stack: Does not stack
  tab: "Food & Gardening"
  tier: Alchemy Engine
  uses: 1 use
roles:
  roles:
  - Science Tier 2
  - DST-Specific Pages
  - Craftable Items and Structures on DST
  - Fertilizer
  - "Food & Gardening Filter"
CRAFTED_FROM:
- Item/Empty_Bottle
- Item/Kelp_Fronds
- Item/Ashes
ITEM_HAS_VARIANT:
- Item/Fermenting_Growth_Formula
- Item/Fermented_Growth_Formula
- Item/Super_Growth_Formula
TRIGGERS_BLOOM:
- Character/Wormwood
---

# Item/Growth_Formula_Starter
