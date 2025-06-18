# CODEALPHA_HANGMAN
HANGMAN GAME
Use a small list of 5 predefined words (no need to use a file or API).
● Limit incorrect guesses to 6.
● Basic console input/output — no graphics or audio.
Key Concepts Used: random, while loop, if-else, strings, lists.
Brief Explanation of Hangman Game
Hangman is a classic word-guessing game where one player thinks of a word, and the other player tries to guess it by suggesting letters within a limited number of attempts.

🔸 How the Game Works:
Secret Word:
A word is selected randomly (or by one player) and kept hidden.

Blank Representation:
The word is shown as underscores or dashes representing each letter (e.g., __A__A for “GUAVA”).

Guessing Letters:
The player guesses one letter at a time:

If the letter is correct, it is revealed in the word.

If the letter is wrong, a part of a "hangman" figure is drawn (head, body, arms, legs, etc.).

Winning:

The player wins if they guess the complete word before reaching the maximum number of wrong guesses.

Losing:

The player loses if the entire hangman figure is drawn before the word is guessed.

🔸 Objective:
To guess the correct word with as few incorrect guesses as possible.

