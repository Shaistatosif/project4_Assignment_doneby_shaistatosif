def main():
    print("Delete this line and write your code here! :)")


# This provided line is required at the end of
# Python file to call the main() function.
if __name__ == '__main__':
    main()

    
Solution
AFFIRMATION : str = "I am capable of doing anything I put my mind to."

def main():
    print("Please type the following affirmation: " + AFFIRMATION)

    user_feedback = input()  # Get user's input
    while user_feedback != AFFIRMATION:  # While the user's input isn't the affirmation
        # Tell the user that they did not type the affirmation correctly
        print("That was not the affirmation.")

        # Ask the user to type the affirmation again!
        print("Please type the following affirmation: " + AFFIRMATION)
        user_feedback = input()

    print("That's right! :)")


# There is no need to edit code beyond this point

if __name__ == '__main__':
    main()