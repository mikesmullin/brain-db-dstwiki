---
desc:
  behavior: "A Map Scroll records the crafting player's map at creation time. Reading it adds the recorded exploration knowledge to the reader's map. A surface scroll transfers only surface data; a Cave scroll transfers only Cave data. It can be examined to see who drew it and on which day."
identity:
  title: Map Scroll
  wikiPage: Map Scroll
item:
  burnTime: 15 sec
  canBeBurned: Can be Burned
  crafting: "1 Feather Pencil + 1 Papyrus at a Cartographer's Desk; cannot be prototyped"
  description: "A craftable DST item introduced in A New Reign. Stores its creator's map data at the time it is made; another player can read it to add that exploration knowledge to their own map. Surface and Cave map data transfer separately."
  perk: "Transfers map exploration progress to another player's map when read; can be used once"
  spawnCode: mapscroll
  stack: Does not stack
  tab: Cartography
  tier: "Cartographer's Desk"
  uses: 1 use
roles:
  roles:
  - Items
  - Map Items
  - Multiplayer
  - DST-Specific Pages
CRAFTED_FROM:
- Item/Feather_Pencil
- Item/Papyrus
ITEM_CRAFTED_AT_STRUCTURE:
- Structure/Cartographers_Desk
---

# Item/Map_Scroll
