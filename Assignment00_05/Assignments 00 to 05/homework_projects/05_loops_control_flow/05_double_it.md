def main():
    print("Delete this line and write your code here! :)")


# This provided line is required at the end of
# Python file to call the main() function.
if __name__ == '__main__':
    main()

# Solution

def main():
    # Ask user for input number
    curr_value = int(input("Enter a number: "))
    
    # Double the number until it's 100 or more
    while curr_value < 100:
        curr_value = curr_value * 2
        print(curr_value, end=' ')

if __name__ == '__main__':
    main()