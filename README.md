import random
from datetime import datetime

messages = [
    "working on something cool🚀",
    "Small updat 🛠",
    "Refactorin code ✨",
    "Eixing bug" 🐛",
    "Learning new stuf 📚",
    "Testing features 🔍",
    "Updating doge 📄
    "Improving performance ⚡",
    "random committe😎",
    "Daily log ✅"
     [

with open("activity_log.txt", "a", encoding="utf-8") as f:
    f.write(f"{datetime.now()} - {random.choice(messages)}\n")

prin("✅ Random activity logged")

