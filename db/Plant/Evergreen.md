---
desc:
  behavior: "A common conifer that can spawn naturally outside Rockyland and Savanna, and can be planted in any biome with a Pine Cone. It cycles through small, medium, large, and aged stages over roughly 0.3–4.4 in-game days per stage. A planted Pine Cone becomes a Sapling, which grows into a small tree in 2.5–5 minutes. Stumps do not regrow after being dug, so new trees must be planted. Chopping trees can summon a nearby Treeguard. Trees burn quickly and can ignite nearby plants; a burnt tree can be chopped for Charcoal."
identity:
  title: Evergreen
  wikiPage: Evergreen
info:
  biome: Most common in Forests and Grasslands; natural generation excludes Rockyland and Savanna
  canBeBurned: Can be Burned
  renew: Yes
  resources: "Tall: 3 Logs and 2 Pine Cones; Medium: 2 Logs and 1 Pine Cone; Small: 1 Log; Old: 1 Pine Cone; Stump: 1 Log; Sapling: 1 Twig; digging a stump yields an additional Log"
  spawnCode: evergreen_tall; evergreen_normal; evergreen_short; evergreen_stump
  tool: Can be Chopped with an Axe; Stumps can be Dug with a Shovel
roles:
  roles:
  - Plants
  - Trees
  - Naturally Spawning Objects
  - Flammable Objects
  - Resources
  - Mob Spawning Entities
PLANT_HAS_VARIANT:
- Plant/Lumpy_Evergreen
PLANT_PRODUCES:
- Item/Log
- Item/Pine_Cone
- Item/Twigs
PLANT_SPAWNS:
- Animal/Treeguard
---

# Plant/Evergreen
