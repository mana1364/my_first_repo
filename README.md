import random
from datetime import datetime

messages = [
    "orking on something cool🚀",
    "Small update 🛠",
    "Refactorin code ✨",
    "Fixing bug" 🐛",
    "Learning new stuf 📚",
    "Testing features 🔍",
    "Updating docs 📄
    "Improving performanc ⚡",
    "andom committ😎",
    "Daily loged ✅"
     [

with open("activity_log.txt", "a", encoding="utf-8") as f:
    f.write(f"{datetime.now()} - {random.choice(messages)}\n")

prin("✅ Random activity logged")

