---
desc:
  behavior: "Neutral herd animal from Savannas and Mandrake Forests. Each herd has up to 12 members, wanders by day and bunches together at dusk and night. In heat it attacks nearby creatures and produces calves. Beefalo drop 4 Meat and 3 Beefalo Wool on death, with a 33% chance of a Beefalo Horn; they also produce Manure periodically."
  tips: "Mounted Beefalo buck riders after a timer that scales from 50 seconds at 0% Domestication to 800 seconds at 100%; it is shorter while untamed, shaved, or in heat. Brushing speeds domestication. Herd heat lasts all Spring and follows a 20-day rest/3-day heat cycle outside Spring; calves spawn every 1–2 days while the herd is heated and no player is nearby. Beefalo can be shaved while asleep for 3 Beefalo Wool, which regrows in 3 days."
identity:
  title: Beefalo
  wikiPage: Beefalo/DST
mob:
  attackPeriod: "4"
  attackRange: "3"
  damage: "34"
  diet: "Veggie, Roughage"
  drops: "On death: 4 Meat, 3 Beefalo Wool, and 1 Beefalo Horn (33% chance); drops Manure every 40–60 seconds; shaving while asleep yields 3 Beefalo Wool"
  heal: Regenerates 6.9 health every 10 seconds; full regeneration in 3 days
  health: "1000"
  image:
  - "File:Beefalo.png"
  naughtiness: "4"
  runSpeed: "7"
  spawnCode: "\"beefalo\""
  spawnFrom: Savanna and Mandrake Forest
  specialAbility: "Herds of up to 12 become aggressive together during Spring and periodic heat; spawn Baby Beefalo when players are off-screen. Feeding any Veggie or Roughage adds 10% Obedience; saddling requires 10% and mounting 50%. Domestication takes about 20–25 days through riding or maintaining Hunger; a Brush can shorten this by 5 days. Fully tamed Beefalo leave their herd and gain one of four tendencies."
  tool: Can be Shaved
  walkSpeed: "1.5"
roles:
  roles:
  - Animals
  - Neutral Creatures
  - Surface Creatures
  - Passive Creatures
  - Hostile Creatures
  - Follower-ish
  - Mob Spawning Entities
  - Diurnals
ANIMAL_DROPS:
- Item/Meat
- Item/Beefalo_Wool
- Item/Beefalo_Horn
- Item/Manure
ANIMAL_SPAWNS:
- Animal/Baby_Beefalo
CAN_DAMAGE:
- Animal/Butterfly
EATS:
- Item/Twigs
- Item/Cut_Grass
- Item/Beefalo_Treats
---

# Animal/Beefalo
