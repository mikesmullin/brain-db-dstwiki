---
desc:
  behavior: "A Wurt-exclusive King born on a Royal Tapestry. When killed, summoned Loyal Merm Guards regenerate after 1 day. It accepts Freshwater Fish, Live Eel, or Ocean Fishes from Wurt or a Clever Disguise and gives resources; Ocean Fishes also yield Gold Nuggets."
identity:
  title: King of the Merms
  wikiPage: King of the Merms
mob:
  damage: Immune; cannot attack or move
  diet: Foods Wurt can eat; accepts food only from Wurt or a player wearing Clever Disguise
  heal: Regenerates 2 Health per second
  health: "1000"
  hunger: Starts at 50; maximum 200; drains 25 per day; dies after Hunger is empty for 2 days
  spawnCode: mermking
  spawnFrom: Merm gains 50 Hunger while on Royal Tapestry
  specialAbility: "Boosts all Merms while alive; neutralizes them toward all creatures and players; summons up to 4 Loyal Merm Guards when health falls below 75%; trades accepted fish for resources"
roles:
  roles:
  - Animals
  - Wurt Exclusive
  - Invulnerable (combat)
  - Merm King
ACCEPTS:
- Item/Fish
ANIMAL_BUFFS_ANIMAL:
- Animal/Merm
ANIMAL_SPAWNS:
- Animal/Loyal_Merm_Guard
ANIMAL_SPAWNS_ITEM:
- Item/Gold_Nugget
SPAWNED_FROM_STRUCTURE:
- Structure/Royal_Tapestry
---

# Animal/King_of_the_Merms
