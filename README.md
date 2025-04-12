# 🃏 Blackjack Game (Python CLI)

A simple and interactive command-line version of the classic **Blackjack (21)** card game, built in Python. Challenge the computer and test your luck—can you hit 21 without going bust?

---

## 🎯 Game Rules

- Try to get as close to 21 as possible without going over.
- Face cards (J, Q, K) are worth 10.
- Aces can count as 11 or 1 depending on your score.
- The dealer (computer) will draw until reaching 17 or more.
- A score of 21 with just two cards is a **Blackjack**!

---

## 📦 Requirements

- Python 3.x  
- `art` module for the ASCII logo

Install the art module with:

```bash
pip install art
```

---

## ▶️ How to Play

1. Clone the repo or download the script.
2. Run the program:

```bash
python blackjack.py
```

3. Follow the prompts in the terminal:

```plaintext
Do you want to play a game of Blackjack? Type 'y' or 'n':
```

---

## 🧠 Game Logic Breakdown

- `deal_card()` – returns a random card from the deck.
- `calculate_score(cards)` – returns the score of the current hand, adjusting Aces if necessary.
- `compare(u_score, c_score)` – compares the user and computer scores and declares the winner.
- `play_game()` – handles the game loop: deals cards, manages user decisions, and prints the outcome.

---

## 📁 Project Structure

```
blackjack/
├── blackjack.py      # Main script with game logic
└── art.py            # ASCII art logo (logo variable)
```

---

## 💡 Example Output

```plaintext
Your cards: [10, 9], current score: 19
Computer's first card: 6

Type 'y' to get another card, type 'n' to pass: n

Your final hand: [10, 9], final score: 19
Computer's final hand: [6, 10, 4], final score: 20
You lose 😤
```

---

## 🛠 Possible Enhancements

- Add betting or scoring system
- GUI version with buttons and graphics (e.g. using Tkinter or PyGame)
- Add card suits and better visual formatting
- Multiplayer mode

## 👨‍💻 Author

Crafted with ☕ and Python by Parth Koshti.
