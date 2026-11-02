---
desc:
  behavior: "A neutral mob that lives in Pig Houses. Pigs attack Monster mobs and are hostile toward Webber, Wortox, and Wurt. Feeding meat makes a Pig follow for up to 2.5 days. Eating vegetables, fruit, or Petals produces Manure every 15 seconds."
identity:
  title: Pig
  wikiPage: Pig/DST
mob:
  attackPeriod: "3"
  attackRange: "3"
  damage: "33"
  diet: "Meat, Veggie, Seeds, Generic, Goodies, Horrible, Raw; will eat nearby dropped food"
  drops: "75% Meat or 25% Pig Skin; 1% extra Pig Skin"
  health: "250"
  mobSanity: +25/min when allied
  naughtiness: "3"
  runSpeed: "5"
  spawnCode: pigman
  spawnFrom: Pig House; respawns 4 days after death
  specialAbility: Can be befriended with meat; attacks Monster mobs; turns into a Werepig after eating 4 Monster Meat or during Full Moon outdoors
  walkSpeed: "3"
roles:
  roles:
  - Animals
  - Neutral Creatures
  - Innocents
  - Surface Creatures
  - Mob Housing
ACCEPTS:
- Item/Meat
- Item/Pig_Skin
ANIMAL_DROPS:
- Item/Meat
- Item/Pig_Skin
ANIMAL_HAS_VARIANT:
- Animal/Werepig
ANIMAL_SPAWNS_ITEM:
- Item/Manure
ANIMAL_SPAWNS_STRUCTURE:
- Structure/Pig_House
ANIMAL_TRANSFORMS_INTO_ANIMAL:
- Animal/Werepig
EATS:
- Item/Meat
- Item/Monster_Meat
- Item/Egg
- Item/Pig_Skin
- Item/Mandrake
- Item/Cooked_Mandrake
---

# Animal/Pig
