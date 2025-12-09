import random
import datetime

messages = [
    "Today is a great day to learn something new!",
    "Keep going — you're closer than you think.",
    "Small steps every day lead to big results.",
    "Consistency beats intensity.",
    "Write code, make progress, repeat.",
    "Your future self will thank you for today's effort.",
    "One line of code is still progress."
]

today = datetime.date.today()
random.seed(today.toordinal())

print(f"Date: {today}")
print("Daily Message:", random.choice(messages))
