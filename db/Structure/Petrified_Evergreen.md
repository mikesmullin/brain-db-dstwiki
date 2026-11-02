---
desc:
  behavior: "A petrified Evergreen variant that yields Rocks, Flint, or Nitre when mined. Petrification affects every growth stage; resource quantities depend on size. Once petrified, trees cannot be chopped with an Axe or continue growing. A random Evergreen or Lumpy Evergreen is selected as the cluster center; eligible trees within 9 tiles and no farther than 2.4 tiles from one another petrify together, provided fewer than 20% of Evergreens are already petrified."
  tips: "Characters nearby may hear a warning noise shortly before the cluster petrifies. This resource can replace Boulders, but extensive petrification can reduce the available Wood supply until regular tree regrowth replenishes it."
identity:
  title: Petrified Evergreen
  wikiPage: Petrified Tree
info:
  biome: Forest; Grassland
  renew: "Yes; some Evergreens are petrified in the starting world, then new clusters appear every 21–32 days after the first event"
  resources: "Short: 1 Rock +35% for another, 25% each Flint and Nitre. Normal: 1 Rock +75% for another, 25% Flint, 40% Nitre. Tall: 2 Rocks +35% for another, 75% Flint, 65% Nitre. Old: 0/1/2 Rocks at 25/50/25%, 75% Flint, 25% Nitre."
  spawn: "May replace Boulders or some Evergreens in the starting world; first later petrification occurs days 44–65, then every 21–32 days"
  spawnCode: rock_petrified_tree; rock_petrified_tree_short; rock_petrified_tree_tall; rock_petrified_tree_old
  tool: Can be Mined with a Pickaxe
roles:
  roles:
  - Structures
  - DST-Specific Pages
  - Trees
  - Non-Flammable
  - A New Reign
YIELDS:
- Item/Rocks
- Item/Nitre
- Item/Flint
---

# Structure/Petrified_Evergreen
