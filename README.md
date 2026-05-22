# Hangman Game 🎮

A classic, text-based implementation of the Hangman game written in Python.

## 🚀 Features
* **Randomized Words:** Selects a random secret word from a predefined list for every game.
* **Attempt Tracking:** Players have 6 incorrect attempts before the game ends.
* **Input Validation:** Ensures players enter valid, single alphabetical characters and prevents guessing the same letter twice.
* **Real-time Status:** Displays the current state of the word, remaining attempts, and previously guessed letters.

## 🧠 How the Code Works
Here is a simplified breakdown of the game's logic:
* **1. Setup:** Imports the `random` module to pick a secret word and initializes variables like the `guessed_letters` list and `attempts_left`.
* **2. Game Loop:** Uses a `while` loop that keeps the game running as long as the player has attempts remaining.
* **3. Input Validation:** Prompts the user for a letter, checking that it is a single alphabetical character and hasn't been guessed already.
* **4. Checking Guesses:** Compares the input against the secret word. If correct, the letter is revealed; if wrong, 1 attempt is subtracted.
* **5. Win/Loss States:** The game immediately stops if all letters are revealed (Win). If the loop finishes because attempts hit 0, the `else` block triggers the Game Over message (Loss).

## 🛠️ Prerequisites
* Python 3.x installed on your machine.

## 💻 How to Run
1. Clone the repository or download the python script.
2. Open your terminal or command prompt.
3. Navigate to the directory containing the file.
4. Run the script using the following command:
   
```bash
   python hangman.py
