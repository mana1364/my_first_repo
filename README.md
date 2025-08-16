import random
from datetime import datetime

messages = [
    "Working on something cool 🚀",
    "Smal update 🛠",
    "Refactorin code ✨",
    "Fixing bugs 🐛",
    "Learning new stuff 📚",
    "Testing features 🔍",
    "Updating docs 📄",
    "Improving performance ⚡",
    "Random commit 😎",
    "Daily log ✅"
]

with open("activity_log.txt", "a", encoding="utf-8") as f:
    f.write(f"{datetime.now()} - {random.choice(messages)}\n")

print("✅ Random activity logged")

