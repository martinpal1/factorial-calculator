# factorial-calculator
chatgpt assisted code that can calculate the factorial of a number which can handle additional cases of negative numbers - task set by university

" def factorial(n):
    if n < 0:
        return "Factorial is undefined for negative numbers"
    elif n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Prompt the user for input
user_input = input("Enter a non-negative integer: ")

# Convert the user input to an integer (assuming it's a valid integer input)
try:
    num = int(user_input)
    result = factorial(num)
    print(f"The factorial of {num} is {result}")
except ValueError:
    print("Invalid input. Please enter a valid non-negative integer.") "
