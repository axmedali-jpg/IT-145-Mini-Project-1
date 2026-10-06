# IT-145-Mini-Project-1
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
