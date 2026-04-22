# 🎮 MasterMind Game (Python)

A simple terminal-based MasterMind game built with Python.

---

## 📌 Features

* Random secret code generation (4 colors)
* User guesses the code within limited tries
* Input validation for correct colors
* Feedback system (correct position vs incorrect position)
* 10 attempt limit
* Simple CLI-based gameplay
* Beginner-friendly Python logic

---

## 🛠 Built With

* Python 3
* Random module

---

## 🎮 How to Play

1. Run the program
2. The computer generates a secret code
3. Enter your guess using color letters separated by spaces

   Example: R G B Y
   
4. You will get feedback after each guess:
* ✔ Correct position
* 🔄 Correct color but wrong position

5. You have 10 tries to guess the correct code
6. Win by guessing the full correct sequence

---

## 🎨 Available Colors

| Symbol | Color   |
| ------ | ------- |
| R      | Red     |
| G      | Green   |
| B      | Blue    |
| Y      | Yellow  |
| W      | White   |
| O      | Orange  |

---

## ▶️ Run Project

python game.py

## 📷 Example Output

Welcome to MasterMind, you have 10 tries to guess the code...
The valid colors are R G B Y W O

Guess: R G B Y
correct position: 2 | incorrect position: 1

Guess: R G B W
You guessed the code in 5 tries!

## 📚 What I Learned

* Python functions
* Loops and conditionals
* Lists and dictionaries
* Random module usage
* Input validation
* Game logic building
* Problem-solving skills

## 🚀 Future Improvements

* Add difficulty levels (Easy / Medium / Hard)
* Add GUI version (Tkinter / PyGame)
* Add colorized terminal output
* Add score tracking system
* Add restart game option

## Author
Made by Sahan Asantha
