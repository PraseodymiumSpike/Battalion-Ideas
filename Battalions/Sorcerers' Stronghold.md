# Sorcerers' Stronghold (Failed Idea)
## Preface
I once wondered if it would be interesting if you could not capture 1 King and then checkmate the other in Spartan Chess but had to actually win through Duple-Check and Mate. This concept is implemented in a weird way here to make it suitable for Titan's Battalion, and the Wizard and the Wile are both equivalents to the Kings despite only 1 of them being a Titan. If they moved like Kings and could not be captured individually, they would be too strong, so I made them weaker. I wanted to be able to balance this using Fairy-Stockfish, but it seems that won't be possible, so I'm likely not going to continue this for the time being.
## Pieces
### Wizard
This Piece is a Titan. It Moves and Captures 1 Space along Rook Lines.
### Wile
This Piece cannot be Captured. It Moves and Captures 1 Space along Rook Lines. At any point during a Turn of the Player Controlling it, its location can optionally be swapped with a Friendly Wizard's. This does not use up the Turn.
### Apprentice
This Piece Moves and Captures 1 Square Forwards along Bishop Lines. It must Promote to Mage, Steed, or Mantle when the Turn of the Player Controlling it ends while it's in the back Rank of an Opponent's Territory. 
### Mage
This Piece Moves and Captures an unlimited number of Squares along Rook Lines or to Knight Squares.
### Steed
This Piece Moves and Captures in the directions of Knight Squares and may make an unlimited number of Leaps in the same direction until it either makes a Capture or is blocked on a Space it could otherwise land on. It is identical to the piece often called "nightrider" in fairy chess problems.
### Trap
This Piece Moves and Captures to the end of a path starting 1 Square along a Rook Line and continuing outwards 1 Square along a Rook or Bishop Line. Like a xiangqi horse, it may not stop without completing its entire path, and it may not Leap over other Pieces.
```
 AAA
B a C
Bb$cC
B d C
 DDD
```
* In the above diagram, assuming it started on the space marked "$", it could Move or Capture to a Space labeled "A" through the one labeled "a", it could Move or Capture to a Space labeled "B" through the one labeled "b", or so on.
## Starting Territory
```
\********\
xAAAAAAAAx
x        x
x STWUTM x
xxxxxxxxxx
```
* In the above diagram, "U" is used for the Wile.
