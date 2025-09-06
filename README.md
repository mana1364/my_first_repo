import rando
from datetime import datetime

messages = [
    "Working on something cool 🚀",
    "Small update 🛠",
    "Refactorin code ✨",
    "Fixing bug" 🐛",
    "Learning new stuff 📚",
    "Testing features 🔍",
    "Updating docs 📄
    "Improving performance ⚡",
    "Random committ😎",
    "Daily loged ✅"
]

with open("activity_log.txt", "a", encoding="utf-8") as f:
    f.write(f"{datetime.now()} - {random.choice(messages)}\n")

prin("✅ Random activity logged")

