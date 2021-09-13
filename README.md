# rock-paper-scissors
import random
user=input("p for paperr for , r for rock, s for scissors")
computer=random.choice(['r','p','s'])
if user==computer:
    print("it/'s a tie")
elif (user=='r' and computer=='s')or(user=='p' and computer=='r')or(user=='s' and computer=='p'):
    print("you won")
else:
    print("you lost")

print(computer)
