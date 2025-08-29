# 🪢 Hangman Game (Python)

A simple **command-line Hangman game** built in Python. The player has 6 lives to guess the hidden word before the stickman is hanged!

---

## 📂 Project Structure
hangman/
│── hangman.py # Main game logic
│── hangman_words.py # Word list
│── hangman_art.py # ASCII art for stages and logo
│── README.md # Project documentation

yaml
Copy
Edit

---

## 🎮 How to Play
1. Run the game:
   ```bash
   python hangman.py
A random word will be chosen.

Guess one letter at a time.

If the letter is correct, it will appear in the word.

If the letter is wrong, you lose a life.

The game ends when:

You guess all the letters → 🎉 You Win!

You run out of lives → ❌ You Lose!

✨ Features
ASCII art for the hangman stages.

Word list imported from hangman_words.py.

Keeps track of guessed letters.

Displays how many lives are left.

Informs you if you already guessed a letter.

📸 Example Gameplay
r
Copy
Edit
 _                                             
| |                                            
| |__   __ _ _ __   __ _ _ __ ___   __ _ _ __  
| '_ \ / _` | '_ \ / _` | '_ ` _ \ / _` | '_ \ 
| | | | (_| | | | | (_| | | | | | | (_| | | | |
|_| |_|\__,_|_| |_|\__, |_| |_| |_|\__,_|_| |_|
                    __/ |                      
                   |___/                       

Word to guess: _ _ _ _ _

6/6 LIVES LEFT
Guess a letter: a
You guessed a, that's not in the word. You lose a life.
🚀 Requirements
Python 3.x

No external libraries are needed.

🛠️ Setup
Clone the repo:

bash
Copy
Edit
git clone https://github.com/yourusername/hangman.git
cd hangman
python hangman.py

📜 License
This project is open source and free to use.
