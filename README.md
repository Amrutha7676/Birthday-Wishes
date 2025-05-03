# Birthday-Wishes
import time
import sys

def type_print(text, delay=0.04):
    for char in text:
        sys.stdout.write(char)
        sys.stdout.flush()
        time.sleep(delay)
    print()

# Input the name
name = input("Enter the birthday person's name: ")

# Build the message
message = f"""
🎉🎉🎉 SURPRISE! 🎉🎉🎉

🎂 Happy Birthday, {name}! 🎂
Wishing you a day full of happiness, joy, and lots of cake! 🎈🎁
May this year bring you success, love, and all your heart's desires. 🥳
"""

# Add some suspense
print("\nPreparing your birthday surprise...")
time.sleep(1.5)
print("3...")
time.sleep(1)
print("2...")
time.sleep(1)
print("1...")
time.sleep(0.8)
print()

# Show the message with typing effect
type_print(message)
