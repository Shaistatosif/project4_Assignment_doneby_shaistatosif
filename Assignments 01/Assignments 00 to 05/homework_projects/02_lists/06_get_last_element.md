def main():
    print("Delete this line and write your code here! :)")


# This provided line is required at the end of
# Python file to call the main() function.
if __name__ == '__main__':
    main()

    
Solution
def get_last_element(lst): """ Prints the last element of the provided list. """

# Takes the length of the list and minuses 1 since they are zero-indexed (we start counting at 0)
print(lst[len(lst) - 1])

# The line below works too!!
# print(lst[-1]) 