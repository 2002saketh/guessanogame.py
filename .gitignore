import random
guess_taken=0
print("Hey! What is your name")
name=input()
number=random.randint(1,100)
print("OK {}, I am thinking a number between 1 and 100".format(name))
while guess_taken<8:
    print("Take a Guess")
    guess=int(input())
    guess_taken+=1
    if guess<number:
        print("Your number is too low")
    if(guess>number):
        print("Your guess is too high")
    if guess==number:
        break
if guess==number:
    guess_taken=str(guess_taken)
    print("Congrats,{} you you guessed my number in {} guesses!".format(name,guess_taken))
if guess!=number:
    number=str(number)
    print("Nope.The number I was thinking of was {}".format(number))
