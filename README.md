# Game Of Generals

## Summary

This repository holds code that will be used to build a Game of Generals board game application.

## Game of Generals Rules

### Objective of the game:

The objective of the game is to eliminate or capture the flag of your opponent. You may also win by successfully maneuvering your own flag to the opposite end of the board.

### Pieces

The player's set of pieces or soldiers with the corresponding ranks and functions consists of the following 12 pieces:

| Pieces             | No. of Pieces | Functions                                                                                                                                                                                          |
| ------------------ | ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Five-Star General  | 1             | Eliminates any lower ranking officer, the private, & the flag                                                                                                                                      |
| Four-Star General  | 1             | Eliminates any lower ranking officer, the private, & the flag                                                                                                                                      |
| Three-Star General | 1             | Eliminates any lower ranking officer, the private, & the flag                                                                                                                                      |
| Two-Star General   | 1             | Eliminates any lower ranking officer, the private, & the flag                                                                                                                                      |
| One-Star General   | 1             | Eliminates any lower ranking officer, the private, & the flag                                                                                                                                      |
| Colonel            | 1             | Eliminates any lower ranking officer, the private, & the flag                                                                                                                                      |
| Lt. Colonel        | 1             | Eliminates any lower ranking officer, the private, & the flag                                                                                                                                      |
| Major              | 1             | Eliminates any lower ranking officer, the private, & the flag                                                                                                                                      |
| Captain            | 1             | Eliminates any lower ranking officer, the private, & the flag                                                                                                                                      |
| 1st Lieutenant     | 1             | Eliminates any lower ranking officer, the private, & the flag                                                                                                                                      |
| 2nd Lieutenant     | 1             | Eliminates any lower ranking officer, the private, & the flag                                                                                                                                      |
| Sergeant           | 1             | Eliminates the private, & the flag                                                                                                                                                                 |
| Spy                | 2             | Eliminates any officer & the flag                                                                                                                                                                  |
| Private            | 6             | Eliminates the spy & the flag                                                                                                                                                                      |
| Flag               | 1             | The flag can be eliminated by any piece including the opposing flag. A flag eliminates the opposing flag when it takes aggressive action by moving into the same square occupied by the other flag |

_Note: If both soldiers are of equal rank, both are eliminated_

### Preparing For Battle

Spread out the board in a 9x8 grid. Arrange your respective sets of pieces on the first 3 rows on your end of the board with the printed sides facing you. There is no predetermined place for any piece. You are therefore free to arrange the pieces according to your strategy of style of play. Note that as you arrange your pieces on the first 3 rows, you will find 6 vacant squares. This is to allow for maneuvering and freedom of movement when play begins.

### Movement

1. Any player makes the first move. Players move alternately (turn-based)
2. A player is allowed to move only one piece at a time
3. A move consists of pushing a piece to an adjacent square, either forward, backward or sideward. A diagonal move or a move of more than one square is illegal

### Challenging

1. As the game progresses, challenges are made resulting in the elimination of soldiers. A "challenge" is made when a soldier moves into the same square occupied by an opposing soldier. When a challenge is made the following rules of elimination apply:
   - A higher ranked soldier eliminates from the board a lower ranked soldier
   - If both soldiers are of equal rank, both are eliminated
   - A spy eliminates any officer starting with the rank of 5-star general down to the sergeant
   - The flag can be eliminated or captured by any piece including the opponent's flag
   - Only a private can eliminate the spy
   - The flag that moves into the same square occupied by the other flag wins the game
2. For maximum interest and suspense, a neutral part (arbiter) is present to preside over a challenge for both players. As arbiter, he is not allowed to reveal to either player the ranks of any piece whether engaged in challenges or not. In case of a challenge, the arbiter quietly removes the outranked piece and gives it back to the player who has lost it. Care must be made that the eliminated piece is not shown to the opponent.
3. When playing without an arbiter, every time there is a challenge both players must declare the ranks of the two opposing pieces concerned. After which, the outranked player removes his piece from the board.

### How the Game Ends

The game ends:
1. When the flag is eliminated or captured
2. When a flag reaches the opposite end of the board
3. When a player resigns
4. When both players agree on a drawn position

A flag reaching the opposite end of the board may still be eliminated by an opposing piece occupying a square adjacent to the one reached by the flag. In order to win, the flag should at least be two squares away from any opposing piece