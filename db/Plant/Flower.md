---
desc:
  behavior: "A small plantable flower that grows from rain (and by planting captured Butterflies). Picking it restores +5 sanity. A 50% chance that a flower becomes an Evil Flower (haunting). Densely plantable; more flowers randomize the butterfly spawn spot."
  tips: "Cultivate by catching Butterflies with a Bug Net and right-clicking them on the ground (1 butterfly = 1 flower, like planting Pine Cones). Useful for a sanity garden. Place near Bee Boxes so Bees can pollinate for honey. In a Cave a flower wilts into a Withered Flower. Variants: Rose (deals 1 damage when picked, +5 sanity; spawnCode flower_rose) and Withered Flower (caves; spawnCode flower_withered)."
identity:
  title: Flower
  wikiPage: Flower/DST
info:
  biome: "Grassland, Forest"
  canBeBurned: Can be Burned
  haunt: "50% chance to turn into an Evil Flower"
  image:
  - "File:Flower1.png"
  - "File:Flower2.png"
  - "File:Flower3.png"
  - "File:Flower4.png"
  - "File:Flower5.png"
  - "File:Flower6.png"
  - "File:Flower7.png"
  - "File:Flower8.png"
  - "File:Flower9.png"
  - "File:Flower10.png"
  objectSanity: +5 when picked
  picked: Can be picked
  renew: Yes
  spawnCode: "\"flower\""
  spawnFrom: Rain
roles:
  roles:
  - Plants
  - Structures
  - Mob Spawning Entities
  - Mob Housing
  - Naturally Spawning Objects
  - Sanity Boost
  - Flammable Objects
  - A New Reign
PLANT_HAS_VARIANT:
- Plant/Rose
- Plant/Withered_Flower
PLANT_PRODUCES:
- Item/Petals
SPAWN:
- Animal/Butterfly
---

# Plant/Flower
