# Guess The Number Game

## Description
This is a simple number guessing game implemented in Java. The program generates a random number between 0 and 999, and the player has to guess it. After each incorrect guess, the program provides feedback on whether the guessed number is too high or too low. Once the correct number is guessed, the program displays the number of attempts taken and provides feedback based on the player's performance.

## Features
- Generates a random number within the range of 0 to 999.
- Takes user input for guessing the number.
- Provides hints whether the guessed number is too high or too low.
- Displays the number of attempts taken to guess the number.
- Gives feedback based on the player's guessing performance.

## How to Run
1. Install [Java](https://www.java.com/en/download/) if not already installed.
2. Clone this repository:
   ```sh
   git clone https://github.com/your-github-username/your-repository-name.git
   ```
3. Navigate to the project directory:
   ```sh
   cd your-repository-name
   ```
4. Compile the Java file:
   ```sh
   javac Main.java
   ```
5. Run the program:
   ```sh
   java Main
   ```

## Code Structure
- `Randomnumber` Class:
  - Generates a random number.
  - Takes user input for guessing.
  - Provides hints for the next guess.
  - Counts the number of attempts.
  - Gives performance feedback.
- `Main` Class:
  - Initializes the game.
  - Calls methods to take guesses and evaluate performance.

## Example Output
```
Enter the number (within 1000): 500
You guessed greater number.
Try smaller one.
Enter the number (within 1000): 250
You guessed smaller number.
Try larger one.
Enter the number (within 1000): 300
You guessed the number in 3rd attempt.
You are having excellent mind.
```

## Future Improvements
- Add difficulty levels (easy, medium, hard) with different number ranges.
- Implement a graphical user interface (GUI) for better user experience.
- Allow multiple rounds of play without restarting the program.

