
# Rock-Paper-Scissors Game in C

This repository contains a simple command-line implementation of the classic "Rock-Paper-Scissors" game in C. Play against the computer and see if you can predict its choices!

## Features

- **Single-player mode**: Play against the computer.
- **Randomized outcomes**: The computer randomly selects its option each round.
- **Instant feedback**: Displays the result of each round (win, loss, or draw).

## Getting Started

### Prerequisites

- A C compiler, such as GCC

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/rock-paper-scissors.git
   cd rock-paper-scissors
   ```

2. Compile the code:
   ```bash
   gcc rock-paper.c -o rock-paper-scissors
   ```

3. Run the game:
   ```bash
   ./rock-paper-scissors
   ```

## How to Play

- Players choose one option: Rock, Paper, or Scissors.
- The computer randomly selects its option as well.
- The outcome is based on the following rules:
  - Rock crushes Scissors -> Rock wins
  - Scissors cut Paper -> Scissors win
  - Paper covers Rock -> Paper wins
- If both the player and the computer choose the same option, it’s a draw.

## Example Gameplay

```plaintext
Choose your option (1 for Rock, 2 for Paper, 3 for Scissors): 1
You chose Rock
Computer chose Scissors
You win! Rock crushes Scissors.
```

## Code Structure

- **rock-paper.c**: Contains the full code logic for the game, including:
  - Taking user input
  - Randomly selecting the computer’s choice
  - Comparing choices and determining the outcome

## License

This project is open-source and available under the [MIT License](LICENSE).
