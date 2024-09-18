# Casino Game

A simple command-line-based slot machine game built in Python. The user can deposit money, place bets on multiple lines, and spin the slot machine to potentially win rewards. The game continues until the player decides to quit or runs out of money.

## How It Works

The game simulates a slot machine where the player can:
- Deposit money to their balance.
- Place bets on up to 3 lines.
- Spin the slot machine and win based on the result.
- The player can win based on matching symbols across the lines they bet on.

### My Approach

The game has been designed with a focus on simplicity and ease of use, featuring:
- **Symbol Frequency and Value**: Different symbols have varying frequencies and payout values, making the game both engaging and unpredictable.
- **Real-time Feedback**: After every spin, the slot machine will show whether the player won or lost, and their updated balance.
- **Simple Betting Mechanism**: Players can bet on 1 to 3 lines and adjust their betting amount within a given range.

The game keeps track of the player’s balance, bets, and winnings throughout the session.

## Instructions

1. **Deposit Money**: 
   - Upon starting the game, you’ll be prompted to deposit an amount of money. This amount will serve as your balance.
   
2. **Place Your Bet**: 
   - Choose the number of lines (1 to 3) on which you want to place your bets.
   - Enter the amount you wish to bet on each line. The total bet is calculated based on the number of lines multiplied by your bet per line.
   
3. **Spin the Slot Machine**: 
   - After placing your bet, the slot machine will spin. If the symbols on a line match, you’ll win according to the symbol's payout value. Your winnings will be added to your balance.
   - The game will show the total amount you’ve won, along with the lines that resulted in a win.

4. **End the Game**:
   - You can continue playing as long as you have money. If you wish to stop, enter `q` when prompted.

## Example Gameplay

- **Symbols**: The slot machine has four symbols, each with a different payout value and frequency.
  - 'A' appears 2 times and has a payout of 5x.
  - 'B' appears 4 times and has a payout of 4x.
  - 'C' appears 6 times and has a payout of 3x.
  - 'D' appears 8 times and has a payout of 2x.

- If you match three symbols on a line, you win the payout multiplied by your bet on that line.

## Requirements

- **Python 3.x** is required to run the game. No additional libraries are needed.

## Running the Game

1. Clone or download the repository.
   ```bash
   git clone https://github.com/your-username/casino-slot-machine.git
