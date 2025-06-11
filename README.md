# How to Play the Mini Hangman Game (Step-by-Step)

1. Start the Game
- When me run the program (python main.py), the game picks a random word from words.txt.

2. View the Hidden Word
- The word is shown as blanks (e.g., _ _ _ _), one underscore per letter.
- You also see a stickman figure, which builds up as you make wrong guesses.

3. Enter Guesses
- Type a single letter and press Enter.
- Example: e

4. Game Logic
- If the letter is in the word:
  - All occurrences of that letter are revealed.
- If the letter is not in the word:
  - One part of the hangman is drawn.
  - You lose one chance.

5. Repeating
- You continue guessing letters until:
  - You guess the full word (You Win!)  
  - OR  
  - You run out of chances (6 wrong guesses) (You Lose!)

6. Keys Used
- Any alphabet letter (a–z): to guess.
- No special keys are needed.

7. End Game
- Once you win or lose, the full word is shown.
- You can then exit or restart (if coded to repeat).
  #Libraries Used in Your Python Code (External or Standard Libraries):

# Library Used:

- import random – This is a standard library in Python.  
  It is used to select a random word from the list using the random.choice() method.

Conclusion:  
Only the standard library random is used in this code. No external libraries are used.

# Input/Output Format & Sample Usage for the Hangman Game

Input Format:
- The player inputs a single lowercase alphabet letter per guess.
- Input is typed into the terminal/console when prompted.

Output Format:
- The console displays:
  - A visual ASCII representation of the hangman depending on wrong guesses.
  - The current state of the word (with unguessed letters as _).
  - Messages like:
    - "Invalid input" if input is not a single letter.
    - "YOU WIN!" if the word is fully guessed.
    - "YOU LOSE!" if maximum attempts are reached.

Sample Usage:

Console Example:

   (empty hangman art)
_ _ _ _ _

Enter a letter: a  
Wrong guesses left: 5  
a is already guessed  

o  
|  
(ASCII hangman art updates)

_ a _ _ _

Enter a letter: b  
YOU WIN! 

Note: To run this, you must define a words list (e.g., words = ["apple", "table", "chair"]) before main() or load from a file. Also, fix if name == "main" to if name == "main":.


