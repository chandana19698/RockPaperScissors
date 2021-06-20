import random
rock = '''
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
'''

paper = '''
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''

scissors = '''
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''
Options=[rock,paper,scissors]
user_choice1=int(input("Enter 1 to choose rock, 2 for paper, 3 for scissors"))
if user_choice1==1:
  choice1=rock
elif user_choice1==2:
  choice1=paper
elif user_choice1==3:
  choice1=scissors
else:
  print("invalid choice")
  choice1="Invalid choice"


if choice1!="Invalid choice": 
  choice2=random.choice(Options)
  print(f"You chose"+choice1)
  print(f"computer chose"+choice2)

  if choice1==rock and choice2==paper:
    print("You loose")
  elif choice1==paper and choice2==rock:
    print("You win")
  elif choice1==paper and choice2==scissors:
    print("You loose")
  elif choice1==scissors and choice2==paper:
    print("You win")
  elif choice1==rock and choice1!=choice2:
    print("You win")
  elif choice2==rock and choice1!=choice2:
    print("You loose")
  else:
    print("Draw")
else:
  print("Game over")
