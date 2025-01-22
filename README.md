# Higher or Lower Game

A fun interactive game where players guess which account has more followers on social media. This project is a Python-based console game designed to test and challenge your intuition about social media popularity!

---

## 📜 How It Works

1. Two random social media accounts are displayed with a brief description and their origin.
2. You need to guess which account has more followers by typing **'A'** or **'B'**.
3. If your guess is correct, your score increases, and the game continues.
4. The game ends when you make an incorrect guess.

---

## 🛠️ Features

- **Random Account Selection:** Fetches random accounts from the dataset.  
- **Interactive Gameplay:** Provides instant feedback on your guesses.  
- **Score Tracking:** Keeps a tally of your correct answers.  

---

## 🚀 Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/higher-lower-game.git
   cd higher-lower-game
   ```
2. Ensure you have Python installed.  
3. Install the `replit` package if not already installed:
   ```bash
   pip install replit
   ```
4. Run the game:
   ```bash
   python main.py
   ```

---

## 📂 Dataset

The game uses the `data` module to source random account information. Make sure the `game_data` module is available in your project folder.

Example structure for the `data` module:
```python
data = [
    {
        "name": "Instagram",
        "follower_count": 346,
        "description": "Social media platform",
        "country": "United States"
    },
    ...
]
```

---

## 🖥️ Demo

Here's a snapshot of the gameplay:

```
Compare A: Instagram, a Social media platform, from United States.
vs
Against B: TikTok, a Short video sharing platform, from China.
Who has more followers? Type 'A' or 'B': a
You're right! Current score: 1.
```

---

## 🛡️ Prerequisites

- Python 3.x  
- `replit` library for clearing the console.  

---



