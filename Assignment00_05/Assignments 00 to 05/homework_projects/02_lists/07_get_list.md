def main():
    print("Delete this line and write your code here! :)")


# This provided line is required at the end of
# Python file to call the main() function.
if __name__ == '__main__':
    main()

    
Solution
def main():
    lst = []  # Make an empty list to store things in

    val = input("Enter a value: ")  # Get an initial value
    while val:  # While the user input isn't an empty value
        lst.append(val) # Add val to list
        val = input("Enter a value: ")  # Get the next value to add

    print("Here's the list:", lst)


# There is no need to edit code beyond this point

if __name__ == '__main__':
    main()