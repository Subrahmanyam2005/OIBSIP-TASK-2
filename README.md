This Java program, GuessTheNumber, is a simple number-guessing game where the user attempts to guess a randomly generated number between 1 and 100. Here's a breakdown of its functionality:

1. Random Number Generation: The program uses the Random class to generate a random number between 1 and 100. This number is stored in the variable numberToGuess.


2. User Input and Guessing: The program prompts the user to input their guess using a Scanner. The user's guess is then compared to the generated random number.


3. Attempts Counter: The number of attempts taken by the user is tracked using the attempts variable. Each time the user makes a guess, the number of attempts is incremented.


4. Feedback and Hints: Based on the user's guess:

If the guess is too low, the program outputs "Too low! Try again."

If the guess is too high, the program outputs "Too high! Try again."

If the guess is correct, the program congratulates the user and displays the number of attempts and the final score.



5. Score Calculation: The score is calculated based on the number of attempts. The user starts with 100 points, and 5 points are subtracted for each incorrect guess. The score is displayed when the user guesses the correct number.


6. Game Loop: The game continues until the user correctly guesses the number. Once the correct guess is made, the loop breaks.


7. Termination: After the game ends, the scanner is closed to release resources.



This code provides a basic interactive game that allows users to improve their guessing skills while keeping track of their score based on the number of attempts.
