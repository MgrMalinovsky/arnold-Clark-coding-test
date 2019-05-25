import random
win = 0
player_check = 0
list1 = ["rock", "paper", "lizard","scissors","spock"]


while player_check == 0:
    player = (str(input("choose your player:")))
    for e in list1:
      if e == player:
          print('your symbol is', player)
          player_check = 1
          break
          print("incorrect symbol, type again")

opponent = random.choice(list1)
print("Opponents symbol is",opponent)

if player == "rock":
    if opponent == "lizard" or opponent == "scissors":
        win = 1
    elif opponent == "paper" or opponent == "spock":
        win = 0
    else:
        win = 2

if player == "paper":
    if opponent == "rock" or opponent == "spock":
        win = 1
    elif opponent == "scissors" or opponent == "lizard":
        win = 0
    else:
        win = 2

if player == "scissors":
    if opponent == "paper" or opponent == "lizard":
        win = 1
    elif opponent == "spock" or opponent == "rock":
        win = 0
    else:
        win = 2

if player == "scissors":
    if opponent == "paper" or opponent == "lizard":
        win = 1
    elif opponent == "spock" or opponent == "rock":
        win = 0
    else:
        win = 2

if player == "lizard":
    if opponent == "spock" or opponent == "paper":
        win = 1
    elif opponent == "rock" or opponent == "scissors":
        win = 0
    else:
        win = 2

if player == "spock":
    if opponent == "scissors" or opponent == "rock":
        win = 1
    elif opponent == "lizard" or opponent == "paper":
        win = 0
    else:
        win = 2



if win == 1:
    print("you won")
elif win == 0:
    print("you lose")
else:
    print("it's draw!")
