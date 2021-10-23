
import time as t
import random
import os
os.system("clear")
print("This is a guessing game")
t.sleep(1)
os.system("clear")
t.sleep(2)
print(""" PYTHON GUESS GAME
""")
print("""Public copyright by algoni.No maintainace of code should be altered.
""")
x = random.randrange(1, 20)
print("This is a guessing game")
print("Type a digit of Number.")
num = int(input("ENTER YOUR INPUT: "))
t.sleep(3)
print("Checking input...")
t.sleep(3)
print("Comparing...")
t.sleep(3)
print("scanning result...")
t.sleep(3)
print('scan complete')
os.system("clear")
if num == x:
  print("CORRECT,YOU WON ✓")
elif num > x:
  print("Your guess is wrong❌")
elif num < x:
  print("Your guess is wrong❌")
elif num != x:
  print("Your guess is wrong❌")
print("Your Guess is", num, "The Correct answer is", x)
