# Rock-Paper-Scissors Game

This is a simple Rock-Paper-Scissors game written in C++. The player competes against the computer by selecting either Rock (`r`), Paper (`p`), or Scissors (`s`). The computer's move is randomly generated, and the game determines the winner based on standard rules.

## Features

- Allows the player to input a move (`r` for Rock, `p` for Paper, `s` for Scissors).
- The computer randomly generates its move.
- The game displays the result (win, loss, or draw) and both the player's and computer's moves.

## How to Play

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/rock-paper-scissors-game.git
   cd rock-paper-scissors-game



2. Compile:
```bash
g++ rock_paper_scissors.cpp -o rps_game

```
3. Run the game:
```bash
./rps_game

```
4. Enter your move when prompted (r for Rock, p for Paper, s for Scissors). The computer will also choose a move, and the result will be displayed


## Example

```rust
Welcome to Stone Paper Scissor Game

Enter r for ROCK, p for PAPER, and s for SCISSOR: r

Game Draw!

Your Move: r
Computer's Move: r

```



## RULES
- Rock (r) beats Scissors (s).
- Scissors (s) beats Paper (p).
- Paper (p) beats Rock (r).
- If both player and computer choose the same move, the game is a draw.
## REQUIREMENTS
- C++ compiler
