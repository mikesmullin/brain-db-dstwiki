---
desc:
  behavior: "A Wurt-exclusive follower mob. Its appearance changes with the King of the Merms, gaining Health and damage while he lives. Wurt or a player wearing Clever Disguise can recruit Merms with vegetarian food or raw Fish, at 15 Hunger per day (10.3 while the King is alive). The King's Pauldron, Crown, and Trident quests can grant loyal Merms protection, a dodge, and a damage boost; guards can also make triple attacks. Lunar and shadow skills create mutated and shadow guards."
identity:
  title: Loyal Merm Guard
  wikiPage: Loyal Merm Guard
mob:
  attackPeriod: 3 seconds
  damage: 20 (50 while King of the Merms is alive)
  diet: "Veggie, Seeds, Goodies, Generic; eats Fruits and Vegetables from the ground"
  heal: "With Wurt's Sensible Swamp Fighter skill, retreats and heals after falling below 25% health"
  health: 200 (660 while King of the Merms is alive)
  runSpeed: "8"
  spawnCode: mermguard
  spawnFrom: Merm Flort-ifications while the King of the Merms is alive; King summons 4 guards when attacked
  specialAbility: "Defends the King; behaves like a befriended Merm, including chopping and mining; immune to epic screeching; cannot be haunted. King equipment quests can grant damage protection, dodge, or increased damage; Wurt's lunar and shadow skills can transform it into mutated or shadow forms."
  walkSpeed: "3"
roles:
  roles:
  - Animals
  - Merm Followers
  - Wurt Exclusive
  - Guards
ANIMAL_SPAWNS_STRUCTURE:
- Structure/Merm_Flortification
ANIMAL_TRANSFORMS_INTO_ANIMAL:
- Animal/Mutated_Merm_Guard
- Animal/Shadow_Merm_Guard
ANIMAL_VARIANT_OF:
- Animal/Merm
SPAWNED_FROM_ANIMAL:
- Animal/King_of_the_Merms
---

# Animal/Loyal_Merm_Guard
