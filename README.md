# Slot Machine Game

This Python script simulates a simple slot machine game, where players can deposit money, bet on multiple lines, spin the slot machine, and win or lose money based on the outcome of the spin.

## Game Configuration

- `MAX_LINES`: The maximum number of lines that can be bet on.
- `MAX_BET`: The maximum bet amount allowed.
- `MIN_BET`: The minimum bet amount allowed.
- `ROWS` and `COLS`: The number of rows and columns in the slot machine.

Two dictionaries are used to define the symbols and their characteristics:

- `symbol_count`: Contains the number of each symbol (A, B, C, D) in the slot machine.
- `symbol_value`: Contains the values associated with each symbol when calculating winnings.

## How to Play

1. Run the script, and it will prompt you to make an initial deposit.

2. Enter the amount you want to deposit. It must be a positive number.

3. The game will start, and you can choose to spin the slot machine by pressing Enter or quit by entering 'q' at any time.

4. After each spin, you will see the outcome, including the result of the spin and any winnings on specific lines.

5. The game continues until you decide to quit.

## Functions

### check_winnings(columns, lines, bet, values)

Checks if there are any winning combinations in the slot machine spin and calculates the winnings. It returns the total winnings and the winning lines.

### get_slot_machine_spin(rows, cols, symbols)

Generates a random slot machine spin with the specified number of rows and columns using the provided symbols and their counts.

### print_slot_machine(columns)

Prints the current state of the slot machine for visualization.

### deposit()

Allows the player to deposit an initial amount of money. It prompts for the deposit amount and validates it.

### get_number_of_lines()

Prompts the player to select the number of lines to bet on, ensuring the input is within the allowed range.

### get_bet()

Asks the player to choose the bet amount for each line, with a validation check to ensure it falls within the allowed range.

### spin(balance)

Handles the main game logic. It takes the player's balance as input and prompts the player to bet on lines. It generates a slot machine spin, checks for winnings, and updates the player's balance accordingly. It returns the net result of the spin (winnings - total bet).

## Main Game Loop

The `main()` function is the entry point of the game. It starts by asking the player for an initial deposit and then enters a loop where the player can choose to spin the slot machine or quit the game. The player's balance is updated after each spin, and the game continues until the player chooses to quit. The final balance is displayed when the game ends.

## Contact Information

For questions or feedback, please feel free to contact the developer:

## Meta

Akif Özcelik – [@akifzclk](https://twitter.com/akifzclk) – akifozcelik.de@gmail.com

Distributed under the MIT license. See `LICENSE` for more information.

[https://github.com/AkifOzcelik/python-slot-machine](https://github.com/AkifOzcelik/)

Enjoy playing the slot machine game!
