# Rock, Paper, Scissors Game

## Designing a Rock Paper Scissors Mini Game Project in Python

This project implements a simple text-based version of the classic game "Rock, Paper, Scissors" in Python. The program allows the user to play against the computer in a continuous loop until the user decides to exit.

## Features
- User-friendly interface to select options: Rock, Paper, Scissors, or Exit.
- Computer randomly selects its move from the available choices.
- Game logic determines the winner based on the rules of Rock, Paper, Scissors.
- Input validation to ensure users enter valid choices.

## Requirements
This project requires Python 3.x. No additional libraries need to be installed as it uses standard Python libraries:
- **random**: To generate random choices for the computer.
- **os**: To interact with the operating system (optional, included for future extensions).
- **re**: To validate user input using regular expressions.

## How to Play
1. Clone or download this repository.
2. Run the script in a Python interpreter.
   ```bash
   python rock_paper_scissors.py
   ```
3. Follow the on-screen instructions:
   - Enter **R** for Rock, **P** for Paper, **S** for Scissors, or **E** to Exit the game.
   - The computer will also select its move randomly.
4. The program will display the results of each round:
   - **Tie**: Both the user and computer chose the same option.
   - **Win**: The user's choice beats the computer's choice.
   - **Lose**: The computer's choice beats the user's choice.
5. Continue playing until you choose to exit by entering **E**.

## Game Logic
The winner is determined based on the following rules:
- **Rock beats Scissors**: Rock crushes Scissors.
- **Scissors beats Paper**: Scissors cut Paper.
- **Paper beats Rock**: Paper wraps Rock.
- If both players choose the same option, the round is a **Tie**.

## Example Output
```text
Rock, Paper, Scissors - Shoot!
Choose your weapon [R]ock], [P]aper, [S]cissors, [E]xit: R
You chose: R
I chose: S
You win!

Rock, Paper, Scissors - Shoot!
Choose your weapon [R]ock], [P]aper, [S]cissors, [E]xit: P
You chose: P
I chose: S
Scissors beats paper! I win!

Rock, Paper, Scissors - Shoot!
Choose your weapon [R]ock], [P]aper, [S]cissors, [E]xit: E
Exiting Game..
```

## Code Explanation
1. **Infinite Loop**:
   - The game runs in an infinite loop until the user exits by pressing **E**.

2. **User Input**:
   - The user is prompted to select an option.
   - Input validation ensures only valid options are accepted.

3. **Computer Choice**:
   - The computer selects its move randomly from the options **R**, **P**, and **S**.

4. **Game Logic**:
   - The program compares the user's choice with the computer's choice to determine the winner based on predefined rules.

5. **Exit Option**:
   - The user can exit the game anytime by entering **E**.

## References
- [Python random module](https://docs.python.org/3/library/random.html)
- [Regular Expression Operations](https://docs.python.org/3/library/re.html)

## License
This project is licensed under the MIT License. See the LICENSE file for details.


