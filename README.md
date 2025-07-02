Project Description: Hangman Game in Python
This is a simple text-based Hangman game built in Python. The player tries to guess a randomly chosen word, one letter at a time, within a limited number of lives. For each wrong guess, a part of the hangman is drawn. The game ends when the player either guesses the word completely or uses up all their chances.

🎯 Features
🎲 Random word selection from a predefined list

🎨 ASCII art for hangman drawing (7 stages)

🧠 Tracks correct and incorrect guesses

🔁 Prevents duplicate guesses

✅ Win or lose feedback

🛡️ Input validation for single alphabet characters

⚙️ How It Works
A random word is selected using Python’s random module.

The word is hidden with underscores (_), and the user guesses one letter at a time.

The game keeps track of:

Letters already guessed

Remaining lives (starts with 6)

The current state of the word

Each incorrect guess decreases the player’s life by 1 and updates the hangman drawing.

The player wins if they guess the full word before lives run out.

📌 Technologies Used
Python 3

random module

ASCII art for visuals
* Example Output
yaml
Copy
Edit
WELCOME TO HANGMAN!

WORD: _ _ _ _ _ _
LIVES LEFT: 6
+----+
|    |
     |
     |
     |
     |
==============
USED LETTERS: a, e, i
GUESS A LETTER:
