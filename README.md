
# 🎮 Hangman Game in Python

A simple and fun implementation of the classic **Hangman** game using Python. The game picks a random word from a list, and you try to guess it one letter at a time before the hangman is fully drawn.

---

## ✅ Features

- Random word selection from a list
- Visual hangman progress with stages
- Letter-by-letter guessing
- Tracks remaining attempts
- Clean and beginner-friendly code

---

## 📁 Project Files

- `hangman.py` – Main Python script to start the game
- `words.txt` – A file containing word choices (one word per line)
- `stages.txt` – ASCII hangman stages separated by `###` delimiters

---

## 🧩 How to Play

1. The program randomly selects a word from `words.txt`.
2. You guess letters one by one.
3. Correct guesses reveal their positions.
4. Incorrect guesses draw a new part of the hangman (max 6 tries).
5. Win by guessing the word, or lose if the hangman is fully drawn.

---

## 🧰 Requirements

- Python 3.x

Install Python from the official site: https://www.python.org/

---

## 🚀 Getting Started

1. **Clone or Download** the repository.
2. Ensure all files (`hangman.py`, `words.txt`, `stages.txt`) are in the same folder.
3. Run the game using:

```bash
python hangman.py
```

---

## 📌 Sample Output

```
Word: _ _ _ _ _
Guess a letter: e
Good guess!

Word: _ e _ _ _
Guess a letter: a
Wrong guess!
Attempts left: 5
```

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
