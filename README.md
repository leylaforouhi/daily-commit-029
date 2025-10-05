import random

def guess_number():
    number = random.randint(1, 10)
    guess = 5
    return guess == number, number

if __name__ == "__main__":
    result, number = guess_number()
    if result:
        print(f"Correct! The number was {number}.")
    else:
        print(f"Wrong! The number was {number}.")
