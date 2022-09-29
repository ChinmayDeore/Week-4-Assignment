## Chinmay D. 9/21/2022
def WorkTicketFour():
## Naming and starting the function
    x = input("Please enter an alphabet: ")
    if(x=='A'or x=='a'or x=='E'or x=='e'or x=='I' 
    or x=='i'or x=='O'or x=='o'or x=='U'or x=='u'):
# Assigning certain characters to fit the vowel parameter
        print('Your alphabet',x,'is a vowel.')
    else:
        print('Your alphabet',x, 'is not a vowel.')
# prints this statement in case the character is something else
# than a vowel
WorkTicketFour()
## Calls the function and ends the program