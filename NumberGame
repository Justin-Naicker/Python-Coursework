import random

number_random = random.randint(1,10)
minimum_number = 0
maximum_number = 11
input_rules = """
---Rules---
You shall select a number between 1-10. 
The computer will select a random number between 1-10! 
Use "yes" or "no" when answering questions. 
Remember, answers are case sensitive.
If the computer gets the correct number, you win! 
If the computer gets an incorrect number, you lose!
"""

print(input_rules)
input_number = input("Enter in a number from 1 - 10: ")
input_bool = input("Is " + input_number  + " your number?: ")
print(number_random)

if input_number.isdigit() == False:
  print("Please enter a numeric value! Please restart the program!")
  exit()

if int(input_number) <= minimum_number and input_bool == "yes":
  print("The number you have selected is equal to or less than 0! Please restart the program!")
  exit()
if int(input_number) >= maximum_number and input_bool == "yes":
  print("The number you have selected is equal or greater than 11! Please restart the program!")
  exit()

if int(input_number) <= minimum_number and input_bool == "no" :
  print("Please restart the program!")
  exit()
if int(input_number) >= maximum_number and input_bool == "no": 
  print("Please restart the program!")
  exit()

if int(input_number) < maximum_number and int(input_number) > minimum_number and input_bool == "yes":
  print("Your number is valid!")
if int(input_number) < maximum_number and int(input_number) > minimum_number and input_bool == "no":
  print("Please restart the program!")
  exit()


input_continue = input("Would you like to continue? : ")

if input_continue == "yes" and number_random == int(input_number):
  print("You won!")
  exit()
elif input_continue == "yes" and number_random != int(input_number):
  print("The number was " + str(number_random) + "!" + " You lost!")
  exit()

if input_continue == "no":
  print("Please restart the program!")
  exit()

