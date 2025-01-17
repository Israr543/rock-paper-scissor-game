# rock-paper-scissor-game
import random

computer=random.choice(["s","p","r"])

user=input("Enter your choice--------S R P ")

if(computer==user):
    print("Draw")
else:
    if(computer=="r" and user=="p"):
        print("You win..........")
    
    elif(computer=="p" and user=="s"):
        print("You won.....")
    
    elif(computer=="s" and user=="r"):
        print("You won.....")

    elif(computer=="p" and user=="r"):
        print("You Loooooseeeee.....")
    
    elif(computer=="s" and user=="p"):
        print("You Loooooseeeee.....")

    elif(computer=="r" and user=="s"):
        print("You Loooooseeeee.....")

    else:
        print("Invalid......")
