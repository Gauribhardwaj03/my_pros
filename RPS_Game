import sys
import random
def play():
    choice_user=input("Do you want to play?\n'y' for yes\n'n' for no\n")
    if(choice_user=='n'):
        print("Thank You")
        sys.exit()
    while(choice_user=='y'):
         user=input("Enter your choice\n'r' for rock\n'p' for paper\n's' for scissors\n")
         computer=random.choice(['r','p','s'])
         if user==computer:
            print("It is a tie")
         if is_win(user,computer):
            print("You win")
         if is_win(computer,user):
            print("You lose")
         choice_user=input("Do you want to play further?\n'y' for yes\n'n' for no\n")
         if(choice_user=='n'):
            print("Thank You")
            sys.exit()
def is_win(player,opponent):#r>s ,p>r, s>p
    if((player=='r'and opponent=='s')or (player=='p'and opponent=='r')or(player=='s'and opponent=='p')):
        return True
    else:
        return False
play()
