# SportStar Bot ⭐

Telegram bot (Khmer): famous athletes by sport + a guess-the-athlete game.

- **⭐ ស្គាល់កីឡាករ** — browse ⚽ 🏀 🥊 🏅 athletes and their profiles
- **🎯 ទាយកីឡាករ** — guess from hints (3 / 2 / 1 points)
- **🏆 ពិន្ទុរបស់ខ្ញុំ** — your total score

## Run
```bash
cp .env.example .env        # paste your token from @BotFather
python3 -m venv .venv
.venv/bin/pip install -r requirements.txt
.venv/bin/python bot.py
```

Edit athletes in `stars.py` (3 facts + 3 hints each).
