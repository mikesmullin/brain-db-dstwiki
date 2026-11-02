---
desc:
  behavior: "A seasonal Giant that seeks food and normally remains neutral until provoked. It rummages food out of Chests, Scaled Chests, and Ice Boxes without destroying them, and drops a Fur Tuft every 45 seconds while walking. Its attacks damage players and mobs and destroy structures. During Winter and Spring it sleeps; attacks wake it, while sleep effects or losing targets can return it to sleep. It does not despawn naturally and can respawn after more than 26 days if its spawn conditions are met."
identity:
  title: Bearger
  wikiPage: Bearger/DST
mob:
  attackPeriod: "3"
  attackRange: 5 melee; 6 ground pound
  damage: 87.5 to players; 175 to mobs
  diet: "Meat, Veggie, Berry, Generic; eats food on ground, from pickable plants, and from Chests, Scaled Chests, and Ice Boxes; ignores Salt Boxes and Magician's Chests"
  drops: 8 Meat + 1 Thick Fur + Bearger Figure Sketch
  health: "6000"
  mobSanity: "-400/min in combat; -100/min otherwise"
  runSpeed: "10"
  spawnCode: bearger
  spawnFrom: Only when world is over 28 days old and season is Autumn; first spawn is normally during the second Autumn if the world starts in Autumn. Warning growl plays one minute before arrival.
  specialAbility: "Drops a Fur Tuft every 45 seconds while walking. Area melee and ground-pound attacks destroy structures; ground pound may shake loose 3–5 Fur Tufts. Yawn sleeps nearby mobs for 10 seconds (24 range, 14-second cooldown). Stealing its food three times provokes it; a nearby player carrying a honeyed item then also draws aggression."
  walkSpeed: 3 casual; 6 aggressive
roles:
  roles:
  - Giants
  - Boss Monsters
  - Hostile Creatures
  - Reign of Giants
  - Autumn
ANIMAL_DROPS:
- Item/Meat
- Item/Thick_Fur
- Item/Bearger_Figure_Sketch
---

# Animal/Bearger
