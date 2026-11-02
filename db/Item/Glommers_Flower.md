---
desc:
  behavior: "Glommer's Flower emits light. Its dead form can be used as fuel for a Fire Pit or Ice Flingomatic. The flower itself cannot be destroyed by fire."
identity:
  title: "Glommer's Flower"
  wikiPage: "Glommer's Flower/DST"
item:
  burnTime: 90 sec when dead
  description: "A flower that blooms at Glommer's Statue on a Full Moon. Picking it summons Glommer nearby; carrying it makes Glommer follow the holder. It does not stack."
  perk: "Dropping it or leaving it in a stationary container makes Glommer wait there; placing it inside Chester makes Glommer follow Chester. If Glommer dies, the linked flower dies. A new flower grows at the next Full Moon even if the statue was destroyed."
  spawnCode: glommerflower
  stack: Does not stack
roles:
  roles:
  - Items
  - Light Sources
  - Followers
  - Full Moon
  - Non-Flammable
ITEM_SUMMONS_FOLLOWER:
- Follower/Glommer
YIELDED_BY_STRUCTURE:
- Structure/Glommers_Statue
---

# Item/Glommers_Flower
