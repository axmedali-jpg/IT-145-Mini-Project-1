# IT-145-Mini-Project-1
This piece of Python code was constructed solely for a class assignment. This piece of Python code highlights a guess the number gam and its played through the terminal and only ends when the right number is guessed successfully. This projects serves a great purpose.
import random
numbers = list(range(1,21))
secret_number = 13
while True:
	message = input("Lets play a Game called Guess the number! ")
	message = int(message)
	if message == secret_number:
		print("Congratulations, That is the right number thanks for playing!")
		break
	elif message > secret_number:
		print("That number is higher. Try again!")
	elif message < secret_number:
		print("That number is lower. Try again!")
	else:
		print("Number is way off. Try Again!")
