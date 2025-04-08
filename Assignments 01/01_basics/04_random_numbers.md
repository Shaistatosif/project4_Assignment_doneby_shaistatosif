import random

N_NUMBERS: int = 10
MIN_VALUE: int = 1
MAX_VALUE: int = 100

def main():
    """
    You should write your code here. Make sure to delete 
    the 'pass' line before starting to write your own code.
    """
    pass

if __name__ == '__main__':
    main()

    # Solution
    import random

N_NUMBERS: int = 10
MIN_VALUE: int = 1
MAX_VALUE: int = 100

def main():
    """
    Generates and prints 10 random numbers between 1 and 100.
    Each number is separated by a space.
    """
    for i in range(N_NUMBERS):
        num = random.randint(MIN_VALUE, MAX_VALUE)
        print(num, end=' ')
    print()  # For a newline after the numbers

if __name__ == '__main__':
    main()
