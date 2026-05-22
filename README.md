<!-- Anchor for 'Back to top' link -->
<a name="readme-top"></a>

<div align="center">

# 🎮 Python Hangman 

<!-- Interactive Badges -->
![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

A classic, text-based implementation of the Hangman game written in Python.

**[🚀 Features](#-features) • [💻 How to Run](#-how-to-run) • [🕹️ How to Play](#️-how-to-play)**

</div>

---

## 🚀 Features
*Interactive Task List showing current and future features:*
- [x] **Randomized Words:** Selects a random secret word for every game.
- [x] **Attempt Tracking:** Players have 6 incorrect attempts before the game ends.
- [x] **Input Validation:** Ensures players enter valid characters and prevents duplicate guesses.
- [ ] *Future Update: Add ASCII Stick-figure graphics.*
- [ ] *Future Update: Add difficulty levels.*

---

<!-- Collapsible Section for Code Logic -->
<details>
<summary><b>🧠 Click to reveal: How the Code Works</b></summary>
<br>
Here is a simplified breakdown of the game's logic:

1. **Setup:** Imports the `random` module to pick a secret word and initializes variables like the `guessed_letters` list and `attempts_left`.
2. **Game Loop:** Uses a `while` loop that keeps the game running as long as the player has attempts remaining.
3. **Input Validation:** Prompts the user for a letter, checking that it is a single alphabetical character and hasn't been guessed already.
4. **Checking Guesses:** Compares the input against the secret word. If correct, the letter is revealed; if wrong, 1 attempt is subtracted.
5. **Win/Loss States:** The game immediately stops if all letters are revealed (Win). If the loop finishes because attempts hit 0, the `else` block triggers the Game Over message (Loss).
</details>

---

## 💻 How to Run

<!-- Collapsible Section for Instructions -->
<details>
<summary><b>🛠️ Click to expand installation instructions</b></summary>
<br>

1. Clone the repository or download the python script.
2. Open your terminal or command prompt.
3. Navigate to the directory containing the file.
4. Run the script using the following command:
   
```bash
   python hangman.py
