#CODESOFT- TASK4
# User Input: Prompt the user to choose rock, paper, or scissors.
# Computer Selection: Generate a random choice (rock, paper, or scissors)
# for the computer. Game Logic: Determine the winner
# based on the user's choice and the computer's choice.
# Rock beats scissors, scissors beat paper, and paper beats rock.
# Display Result: Show the user's choice and the computer's choice.
# Display the result, whether the user wins, loses, or it's a tie.
# Score Tracking (Optional): Keep track of the user's and
# computer's scores for multiple rounds. Play Again: Ask the user
# if they want to play another round. User Interface: Design a user-friendly
# interface with clear instructions and feedback
import random

options = ['Rock', 'Paper', 'Scissors']

userScore, computerScore = 0, 0
totalRounds = 3

for i in range(totalRounds):
    userOption = int(input('Press 1 for Rock, 2 for Paper, 3 for Scissors: '))
    userChoice = options[userOption-1]

    computerChoice = options[random.randint(0,2)]

    print(f'You chose: {userChoice}')
    print(f'Computer chose: {computerChoice}')

    result = "It's a tie!"

    if userChoice == "Rock":
        if computerChoice == "Paper":
            result = "Computer won this round!"
            computerScore += 1
        elif computerChoice == "Scissors":
            result = "You won this round!"
            userScore += 1

    elif userChoice == "Paper":
        if computerChoice == "Scissors":
            result = "Computer won this round!"
            computerScore += 1
        elif computerChoice == "Rock":
            result = "You won this round!"
            userScore += 1

    elif userChoice == "Scissors":
        if computerChoice == "Rock":
            result = "Computer won this round!"
            computerScore += 1
        elif computerChoice == "Paper":
            result = "You won this round!"
            userScore += 1
    
    print(result + '\n')

print(f'Your score: {userScore}')
print(f"Computer's score: {computerScore}")

if userScore > computerScore:
    print('You won most rounds!')
elif computerScore > userScore:
    print('Computer won most rounds!')
else: 
    print("It's a draw")
