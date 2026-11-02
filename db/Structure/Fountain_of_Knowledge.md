---
desc:
  behavior: "One of five colored fountains in the Ancient Archive and Sanctum. The Archive Switch powers it; activating it lets a player obtain Distilled Knowledge, which grants a color-specific blueprint when used to solve the Ancient Orchestrina puzzle."
identity:
  title: Yellow Fountain of Knowledge
  wikiPage: Fountain of Knowledge
info:
  description: "Initially inactive. Powered by the Archive Switch; interaction awards Distilled Knowledge. The yellow fountain's Distilled Knowledge unlocks the Terra Firma Tamper or Ancient Stonework blueprint through the Ancient Orchestrina puzzle."
  source: Ancient Archive biome
  spawnCode: archive_lockbox_dispencer; build override archive_knowledge_dispensary_a
roles:
  roles:
  - DST-Specific Pages
  - Return of Them
  - Structures
  - Ancient Archives
  - Naturally Spawning Objects
STRUCTURE_ACTIVATED_BY_STRUCTURE:
- Structure/Archive_Switch
STRUCTURE_AWARDS_ITEM:
- Item/Distilled_Knowledge
STRUCTURE_HAS_VARIANT:
- Structure/Blue_Fountain_of_Knowledge
- Structure/Red_Fountain_of_Knowledge
- Structure/Green_Fountain_of_Knowledge
- Structure/Orange_Fountain_of_Knowledge
---

# Structure/Fountain_of_Knowledge
