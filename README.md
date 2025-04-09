# 🎮 Hangman Game in Python

This is a simple **console-based Hangman game** written in Python. The player has to guess the correct word by suggesting letters within a limited number of chances.

---

## 📝 Features

- Random word selection from a predefined list.
- Letter guessing with feedback.
- Tracks used letters.
- 6 lives (chances) before the game is over.
- Clean and simple console output.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed on your system.

### How to Run

1. Clone this repository or download the `hangman.py` file.
2. Open your terminal or command prompt.
3. Run the script using:

```bash
python hangman.py
```

---

## 🎯 Game Rules

- The game will randomly choose a word from a list.
- You have 6 lives to guess the correct word.
- You can guess one letter at a time.
- Repeating the same guess will give a warning.
- Invalid inputs (e.g. numbers, symbols) will be rejected.

---

## 📂 Word List

Words currently included in the game:

```
apple, banana, orange, grape, watermelon, pineapple, mango
```

Feel free to modify or expand this list in the code!

---

## 📸 Example Gameplay

```
You have 6 lives left and you have used these letters:
Current word:  - - - - -
Guess a letter: A

You have 6 lives left and you have used these letters: A
Current word:  A - - - -
Guess a letter: B
Letter is not in word.
...
```

---

## 💡 Future Improvements

- Add difficulty levels.
- Read words from an external file.
- Add a simple GUI using `tkinter` or `pygame`.

---

## 🤝 Contributing

Feel free to fork this project and improve it. Pull requests are welcome!

---

## 📜 License

This project is open-source and free to use.

