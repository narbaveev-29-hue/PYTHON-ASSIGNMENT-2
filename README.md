#  Hangman Game (Python)

## Overview

This project is a Python implementation of the classic **Hangman word guessing game**.

The program allows a user to guess a randomly selected word letter by letter. It runs in the terminal and provides interactive feedback after each guess. The game also includes an optional hint system to assist the player.

---

## Features

### Core Gameplay

* Random word selection from a word list (`words.txt`)
* User starts with **6 guesses**
* Displays:

  * Remaining guesses
  * Available letters
  * Partially guessed word using `_` for unknown letters
* Handles:

  * Correct guesses
  * Incorrect guesses
  * Repeated guesses

---

### Hint System

* Enter `*` to view possible word matches
* Suggests valid words based on current progress
* Helps improve guessing strategy

---

## Functions Used

* `is_word_guessed` → Checks if the word is fully guessed
* `get_guessed_word` → Shows current progress of the word
* `get_available_letters` → Displays unused letters
* `hangman` → Runs the main game
* `match_with_gaps` → Matches patterns with possible words
* `show_possible_matches` → Displays hint suggestions
* `hangman_with_hints` → Runs game with hint feature

---

## Project Structure

```id="o30f8k"
ps2/
├── hangman.py
├── words.txt
```

---

## How to Run

1. Make sure both files are in the same folder:

   * `hangman.py`
   * `words.txt`

2. Run the program:

```bash id="5xg53v"
python hangman.py
```

---

##  How to Play

* Enter one letter at a time
* You have **6 guesses**
* Repeated guesses will be notified
* Enter `*` to get hints (if enabled)

---

## Example

```id="r8br0z"
Welcome to Hangman!
I am thinking of a word that is 5 letters long.
-------------
You have 6 guesses left.
Available letters: abcdefghijklmnopqrstuvwxyz
Please guess a letter: a
Good guess: _ a _ _ _
```

---

## Skills Demonstrated

* Python basics (loops, conditionals, functions)
* String and list manipulation
* User input handling
* Game logic implementation

---

## License

This project is for learning and practice purposes.
