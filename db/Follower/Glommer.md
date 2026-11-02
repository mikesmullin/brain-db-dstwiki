---
desc:
  behavior: "A passive Full Moon companion that appears with Glommer's Flower at Glommer's Statue. When allied, it grants a nearby player +6.25 Sanity per minute and periodically produces Glommer's Goop. Killing it adds 50 Naughtiness and guarantees Krampus; it sleeps after three Sleep Darts."
identity:
  title: Glommer
  wikiPage: Glommer/DST
mob:
  attackPeriod: "3"
  damage: "2"
  drops: "Killed: 3 Monster Meat, 1 Glommer's Wings, and 2 Glommer's Goop. Periodically: 1 Glommer's Goop every 2–4 days."
  health: "100"
  mobSanity: +6.25/min when allied and very close
  naughtiness: "50"
  spawnCode: glommer
  spawnFrom: "Glommer's Statue on Full Moon; flies away at daytime if its flower remains at the statue"
  specialAbility: "Follows the holder of Glommer's Flower; waits near the dropped flower or follows Chester when the flower is stored inside. Passive; regrows on the next Full Moon after death. Lunar aligned."
roles:
  roles:
  - Followers
  - Passive Creatures
  - Light Sources
  - Lunar Aligned
DROPS:
- Item/Monster_Meat
- Item/Glommers_Wings
- Item/Glommers_Goop
FOLLOWER_SUMMONED_BY_ITEM:
- Item/Glommers_Flower
---

# Follower/Glommer
