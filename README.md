# Random-number-guessing-game
#just a start of the projects and learning things in deeper way ,by small steps daily
#CODE
import random
number = random.randint(1, 50)
attempts=0
while True:
    guess_number= int(input("TAKE A GUESS: "))
    attempts+=1

    if guess_number < number:
        print("TOO LOW")
        
    elif guess_number > number:
        print("TOO HIGH")
       
    else:
        print(f"CONGRATULATIONS YOU HAVE GUESSED IT RIGHT in {attempts} tries")
        break
