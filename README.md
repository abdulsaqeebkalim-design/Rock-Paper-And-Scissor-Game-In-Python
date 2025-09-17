# Rock-Paper-And-Scissor-Game-In-Python
'''This is the first project(Rock, Paper and Scissor Game) that I build in python as a new first year student of BTECH in AIML''' 
''' project 1 : Rock, Paper and Scissor
rock = -1
paper = 0
scissor = 1

rock vs paper = paper wins
rock vs scissor = rock wins
paper vs scissor = scissor wins

same = draw

'''
import random

computer = random.choice([-1, 0, 1])
print("NOTE :")
print(" Enter 'r' for Rock")
print(" Enter 'p' for Paper")
print(" Enter 's' for Scissor")

youstr = input(" Enter your choice : ")
youdict = { "r": -1, "p": 0, "s": 1}
you = youdict[youstr]

reversedict = {-1 : "rock", 0 : "paper", 1 : "scissor" }
print(f" Your choice is {reversedict[you]}")
print(f" Computer's choice is {reversedict[computer]}")




if ( computer == you ):
    print(" its a draw! ")
    
else :
    if (computer == -1 and you == 0):
        print(" You wins !")
        
    elif (computer == -1 and you == 1):
       print(" Computer wins !")
        
    elif (computer == 1 and you == 0):
       print(" Computer wins !")
       
    elif (computer == 1 and you == -1):
       print(" You wins !")
       
    elif (computer == 0 and you == 1):
       print(" You wins !")
       
    elif (computer == 0 and you == -1):
       print(" Computer wins !")
       
    else:
           print("Something went wrong!")
