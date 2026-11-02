---
desc:
  behavior: "An aggressive Caves boss that also attacks other creatures, including other Toadstools. Three Toadstool holes generate in the Caves, each surrounded by three ponds; one contains a Toadstool Cap. The boss burrows back into its hole if players leave the fight, and a replacement cap appears in a random hole 20 days after it is killed. A Spore Bomb attaches to a nearby player, emits light for 3.5 seconds, then explodes; its cloud lasts one minute, damages players and spoils perishables by 7% per second. Below 40% health it hops twice, attacks nearby players and mobs, and causes earthquakes. Sporecaps buff its speed, damage, attack rate, damage reduction, hit recovery, and Boomshroom spawn rate; chopping them lowers its charge. Charge levels at 0, 1–4, 5–7, and 8+ Sporecaps raise damage reduction to 0/20/40/80%, damage to 100/120/150/250, and attack rate to 3.5/3/2.5/2 seconds."
identity:
  title: Toadstool
  wikiPage: Toadstool
mob:
  attackPeriod: 3.5 / 3 / 2.5 / 2 by charge
  attackRange: 7; Spore Bomb targets players within 10
  damage: 100 / 120 / 150 / 250 by charge
  drops: "1 Frog Legs; one Red, Green, and Blue Cap, each with a 33% chance of an extra; 3–5 Meat; 1 Shroom Skin plus another at 70% and 40% health; 2 Rare Blueprints (one of three Funcap blueprints and either a Glowcap Blueprint at 33% or Mushlight Blueprint at 67%)"
  health: "52,500"
  iceStaff: "4 casts initially; one additional cast after each thaw, up to 6"
  introduced: Warts and All update
  protection: "0% / 20% / 40% / 80% damage reduction by Sporecap charge"
  sleepDart: "4"
  spawnCode: toadstool
  spawnFrom: Chop a Toadstool Cap in the Caves
  specialAbility: "Spawns Boomshrooms and Sporecaps; attaches a light-emitting Spore Bomb to a player, which explodes after 3.5 seconds into a damaging cloud lasting 1 minute; causes earthquakes below 40% health"
  walkSpeed: 0.6 / 0.8 / 1.2 / 3.2 by Sporecap charge
roles:
  roles:
  - DST-Specific Pages
  - Boss Monsters
  - A New Reign
  - Cave Creatures
  - Object Destroyers
  - Earthshakers
ANIMAL_DROPS:
- Item/Frog_Legs
- Item/Meat
- Item/Shroom_Skin
- Item/Red_Cap
- Item/Green_Cap
- Item/Blue_Cap
- Item/Red_Funcap_Blueprint
- Item/Green_Funcap_Blueprint
- Item/Blue_Funcap_Blueprint
- Item/Glowcap_Blueprint
- Item/Mushlight_Blueprint
ANIMAL_HAS_VARIANT:
- Animal/Misery_Toadstool
ANIMAL_SPAWNS_STRUCTURE:
- Structure/Boomshroom
- Structure/Sporecap
---

# Animal/Toadstool
