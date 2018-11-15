"""
Guessing Game
This program guesses the number in your mind until it gets it
Nov 10, 2018
"""

import random

# Initial guess
number = random.randint(0,100)
max_num = 100
min_num = 0

initial_guess = False
tries = 0


while initial_guess == False:
    
    print("is the number ", number)
    input_text = input("Type 'y' if correct or 'n': ")
    
    if  input_text == 'y':
        
        print("YES I GOT IT!!")
        print("Tries: ", tries, " times")
        initial_guess = True
        
    elif input_text =='n':     
  
        high_low = input("If it's too high, type 'h', if it's low, type 'l': ")

        if high_low == 'h':
            max_num = number-1

        elif high_low =='l':
            min_num = number+1

        else:
            print("invalid input")    
        
        if max_num <= min_num or min_num < 0 or max_num > 100:
            print("Invalid input. Please try again.")
            break 

        number = random.randint(min_num, max_num)
        tries += 1

    else:
        print("invalid input")
    
  

