Number Guessing Game (Java)
** Overview **
This is a simple game where you guess a number using the console in Java.
The player has to guess a random number that is picked between 1 and 100.
The game consists of 3 rounds, and in each round, the player gets up to 10 tries to figure out the correct number.
The game gives you points depending on how fast you guess the number.

** Features **
A random number is picked between 1 and 100.
There are 3 rounds in total.
You get 10 attempts in each round.
You get hints like "greater than" or "less than" after each guess.
Scoring works like this:
- Round Score = Number of attempts left
- Total Score = Sum of scores from all rounds
- If you don't guess the number in 10 attempts, the number is shown to you.

** How to Play **
Open the program in your Java IDE or in the terminal.
The game starts with Round 1.
Type your guess.
After each guess, you will get a hint:
- If your guess is too low: "The number is greater than your guess."
- If your guess is too high: "The number is less than your guess."
- Guess correctly within 10 attempts to get points.
- After 3 rounds, the total score will be shown.

** Scoring **
- Score = (Maximum Attempts - Number of attempts used)
- Example: If you guess the number in 4 attempts, then your score is 10 - 4 = 6.
- If you fail to guess the number, you get 0 points for that round.

** Example Gameplay **
NUMBER GUESSING GAME
Total Number Of Rounds: 3
Attempts To Guess Number In Each Round: 10
Round 1: Guess the number between 1 and 100 in 10 attempts.
Enter your guess:
50
The number is greater than 50.
Attempts Left = 9.
Enter your guess:
75
The number is less than 75.
Attempts Left = 8.
Enter your guess:
63
Congratulations!
Number Guessed Successfully. Attempts = 3. Round Score = 7
...
Game Over.
Total Score = 15

** How to Run **
Save the file as NumberGuessingGame.java
Compile the program:
javac NumberGuessingGame.java
Run the program:
java NumberGuessingGame

** Requirements ** 
Java Development Kit (JDK) 8 or higher
Terminal/IDE (Eclipse, IntelliJ IDEA, or VS Code)

** Author **
This was created as a Java project to help improve logic building, random number generation, and handling user input.
