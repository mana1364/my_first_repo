from datetime import datetime


with open("activity_log.txt", "a", encoding="utf-8") as f:
    f.write(f"Activity at {datetime.now()}\n")

print("Activity logge ✅")

