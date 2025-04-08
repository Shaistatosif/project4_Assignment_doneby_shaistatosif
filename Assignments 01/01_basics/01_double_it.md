def main():
    print("Delete this line and write your code here! :)")


# This provided line is required at the end of
# Python file to call the main() function.
if __name__ == '__main__':
    main()


    # Solution

    def main():
    # Ask the user to enter a number
    num = int(input("Enter a number: "))
    
    # Initialize curr_value with the entered number
    curr_value = num
    
    # Loop until curr_value is less than 100
    while curr_value < 100:
        # Double the current value
        curr_value = curr_value * 2
        # Print the new value (without newline and with space)
        print(curr_value, end=' ')
    
    # Print a newline at the end
    print()

if __name__ == '__main__':
    main()