import random

NUM_ROUNDS = 5

def play_high_low():
    print("Welcome to the High-Low Game!")
    print("--------------------------------")
    
    score = 0
    
    for round_num in range(1, NUM_ROUNDS + 1):
        print(f"Round {round_num}")
        
        # Generate random numbers
        your_num = random.randint(1, 100)
        computer_num = random.randint(1, 100)
        
        print(f"Your number is {your_num}")
        
        # Get user input with validation
        while True:
            guess = input("Do you think your number is higher or lower than the computer's?: ").lower()
            if guess in ['higher', 'lower']:
                break
            print("Please enter either 'higher' or 'lower'")
        
        # Determine if the guess was correct
        correct = False
        if guess == 'higher' and your_num > computer_num:
            correct = True
        elif guess == 'lower' and your_num < computer_num:
            correct = True
        
        # Update score and print result
        if correct:
            score += 1
            print(f"You were right! The computer's number was {computer_num}")
        else:
            print(f"Aww, that's incorrect. The computer's number was {computer_num}")
        
        print(f"Your score is now {score}\n")
    
    # Final message based on performance
    print("Thanks for playing!")
    if score == NUM_ROUNDS:
        print("Wow! You played perfectly!")
    elif score >= NUM_ROUNDS // 2:
        print("Good job, you played really well!")
    else:
        print("Better luck next time!")

# Start the game
play_high_low()