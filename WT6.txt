## Chinmay D. 9/21/2022
import random 
def WorkTicketSix():
## Naming and starting the function
    log_one = [1,3,5,7,9,11,13,15,17,19,21,23,25,27,29,31,33,35]
    log_two = [2,4,6,8,10,12,14,16,18,20,22,24,26,28,30,32,34,36]
## Assigns integers to two seperate lists
    while True:
        if input("Guess a number, color or both. Enter 'stop' to end the game: ") == 'stop':
            break
        number = random.randrange(0, 37)
## Generates a random integer between the range of 0 to 36 
        print('\nNumber is: ', number)
        if number in log_one:
            print('And the color is Red')
        else:
            print('And the color is black')
WorkTicketSix()
## Calls the function and ends the program