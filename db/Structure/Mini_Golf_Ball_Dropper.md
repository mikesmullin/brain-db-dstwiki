---
identity:
  title: Mini-Golf Ball Dropper
  wikiPage: Mini Golf
info:
  description: "Starts a mini-golf round when given one Cawnival Token; drops a Golf Ball and Putter, emits light during play, and awards Prize Tickets according to score when the ball reaches a Mini-Golf Flaghole. Beginner, Standard, and Expert courses award base totals of 5, 10, and 15 tickets. At one stroke the payout is 2.5× base; under par it is floor(base × [1 + 0.75 × (par − strokes)/(par − 2)]); at par it is base; over par it is floor(base^(0.80^(strokes − par))). Custom courses award no tickets and refund the token; if the ball is not sunk before timeout, no tickets are awarded."
  spawnCode: carnivalgame_golf_tee
roles:
  roles:
  - Cawnival Games
  - Special Event
  - Structures
STRUCTURE_ACCEPTS_ITEM:
- Item/Cawnival_Token
STRUCTURE_AWARDS_ITEM:
- Item/Prize_Ticket
STRUCTURE_DROPS:
- Item/Golf_Ball
- Item/Putter
---

# Structure/Mini_Golf_Ball_Dropper
