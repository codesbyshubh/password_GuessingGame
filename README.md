# password_GuessingGame
started learning python and build mini project to enhance my skill and get some practical knowladge


WORD GUESSING GAME: PROJECT SUMMARY


This document outlines the core concepts, functionality, and pseudocode for a word guessing game program.

🎮 How the Game Works

The game follows a simple, step-by-step process:

1. Secret Word Selection: The program first selects a secret word (e.g., "banana").

2. Initial Clue: The user is told how many letters the secret word has.

3. Guessing Loop: The program prompts the user to guess the word.
      
      • Win Condition: If the       user's guess is correct, they win, and the program shows the total number of attempts taken.

Hint: If the guess is incorrect, the program provides a hint (e.g., "2 letters are correct and in the right place").

4. Game End: The game continues until the user guesses the word correctly.



PSEUDOCODE STRUCTURE 

The program execution is structured as follows:


1. START the program.

2. SHOW a welcome message and the rules.

3. LET the user choose a difficulty level.

4. Based on the level, SET a list of possible secret words.

5. RANDOMLY select the secret word from the chosen list.

6. TELL the user the number of letters in the secret word.

7. SET the attempt counter to 0.

8. WHILE the user hasn't guessed the word:

   a. ASK the user to enter a guess.
   b. INCREMENT the attempt counter.
   c. IF the guess equals the secret word: i. PRINT "Congratulations!" and show attempts. ii. BREAK the loop.      d. ELSE (if the guess is wrong): i. COMPARE each letter in the guess to the secret word. ii. COUNT how many        letters are correct and in the correct place (to give a hint).
