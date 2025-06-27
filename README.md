# Hangman Game (C++)

> A fun word-guessing game with categories, difficulty levels, and a 10-second timer per guess.

---

## 🧠 Overview

This C++ project is a console-based Hangman game where the player:
- Selects a category (Animals, Fruits, or Countries)
- Chooses a difficulty (Easy, Medium, or Hard)
- Guesses the hidden word one letter at a time
- Has 10 seconds to guess each letter
- Can use built-in hints to help identify the word

Great for practicing:
- Randomization
- Timers with `chrono` and `thread`
- String manipulation
- Basic game loops and user input

---

## 🎮 Features

- **Multiple Categories**: Choose between Animals, Fruits, and Countries
- **Difficulty Settings**: Easy (10 tries), Medium (7), Hard (5)
- **Timed Input**: Players must guess within 10 seconds
- **Hint System**: Each word has a hint shown at the start
- **Clean Interface**: Dynamic word display with underscores and correct letters revealed

---

## 🛠️ Requirements

- C++11 or higher
- Works on any OS with a standard C++ compiler

---

## ▶️ How to Run

1. **Compile the game:**
```bash
g++ hangman.cpp -o hangman
```

2. **Run it:**
```bash
./hangman
```

---

## 🗂️ Project Structure

```
hangman_game/
├─ hangman.cpp         # Main game file
├─ README_Hangman.md   # Project README
```

---

## 🙏 Acknowledgements

This project was built by Christopher Jung with help from **ChatGPT** for structuring the README and refining the game logic.

---

## 📜 License

This project is open-source and free to use.

---

*Made by Christopher Jung — March 25, 2025*
