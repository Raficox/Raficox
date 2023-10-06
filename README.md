import random

Result=random.randint(1,100)
Number=0

while Number!=Result:
    Number=int(input("Enter a Number="))
    if Number>Result:
        print("Guessing Lower Number")
    elif Number<Result:
        print("Guessing Higher Number")
    else:
        print("You are won.your guess is Right ")
