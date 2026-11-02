---
desc:
  behavior: "A dangerous Caves weather event that occurs only after the Shadow Rift opens. It does not increase Wetness but damages players, spoils carried food, and degrades equipped Water Resistant armor and clothing. Protect with 100% Water Resistance; an Umbrella fully protects and repairs itself while held, and can be placed to provide area protection."
identity:
  title: Acid Rain
  wikiPage: Acid Rain
info:
  animalEffects:
  - "Damaged Bishops, Rooks, Knights, Splumonkeys, Baby Tentacles, Treeguards, Bunnymen, and Royal Rabbit Enforcers: attack damage -15%, physical damage taken +25%, movement speed -15%"
  - "Fugu Hutch, Spiders, Spider Warriors, Cave Spiders, Spitters, Dangling Depth Dwellers, Shattered Spiders, Sea Striders, and Nurse Spiders: attack damage +50%, physical damage taken -25%, movement speed +15%"
  - "Depths Worms, Shadow Splumonkeys, Tentacles, and Batilisks: attack damage +50%, physical damage taken +25%, movement speed +25%"
  - "Batilisks also move 25% faster and drop Batilisk Wing (50%), Guano (30%), Monster Meat (20%), and Nitre (20%); they raid players carrying Nitre every half day"
  - "Rock Lobsters shrink and become weaker when damaged, then slowly return to normal after the rain"
  biome: Caves except the Lunar Grotto and Ancient Archive
  characterEffects:
  - "Deals up to 3 damage per 1.5 seconds; fully resisted by 100% Water Resistance"
  - "Removes 0.07% freshness from carried perishables unless protected by Water Resistance or stored in a container"
  - Reduces durability of equipped Water Resistant armor by 3 HP and clothing by 3 seconds per tick; does not cause Wetness
  damage: Up to 3 health
  damagePeriod: Every 1.5 seconds
  introduced: Terrors Below update
  plantEffects:
  - Mushtrees accumulate acid on their caps; mushrooms falling from them are slightly spoiled
  protection: "100% Water Resistance negates player damage and perishables spoilage; the Umbralla provides full protection and regenerates its durability while equipped during Acid Rain"
  trigger: Replaces normal rainfall in the Caves while the Shadow Rift is active
  worldEffects:
  - "Forms Nitre Formations on underground Ponds, preventing fishing until mined"
  - Acid accumulates on Mushtree caps and mushrooms that fall from them are slightly spoiled
  - Replaces ordinary rain while the Shadow Rift is active
roles:
  roles:
  - Weather
  - Rift Content
  - Gameplay Mechanics
  - Caves
  - Environmental Hazards
  - From Beyond
WEATHER_AFFECTS_ANIMAL:
- Animal/Splumonkey
- Animal/Baby_Tentacle
- Animal/Treeguard
- Animal/Spider
- Animal/Spider_Warrior
- Animal/Sea_Strider
- Animal/Nurse_Spider
- Animal/Shadow_Splumonkey
- Animal/Tentacle
- Animal/Batilisk
- Animal/Rock_Lobster
- Animal/Rock_Master
WEATHER_DEGRADES_ITEM:
- Item/Rain_Coat
WEATHER_EMPOWERS_ANIMAL:
- Animal/Batilisk
- Animal/Hound_Batilisk
- Animal/Acid_Hound_Batilisk
- Animal/Shadow_Splumonkey
WEATHER_FORMS_STRUCTURE:
- Structure/Nitre_Formation
WEATHER_REPAIRS_ITEM:
- Item/Umbralla
---

# Weather/Acid_Rain
