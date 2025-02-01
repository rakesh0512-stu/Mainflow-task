# Mainflow-task
program 1
num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))
sum_result = num1 + num2
print("The sum is:", sum_result)

program 2
def odd_or_even(number):
    if number % 2 == 0:
        return "Even"
    else:
        return "Odd"
num = int(input("Enter a number: "))
print(odd_or_even(num))
program 3
def factorial(n):
    result = 1
    for i in range(1, n + 1):
        result *= i
    return result
num = int(input("Enter a number: "))
print(f"Factorial of {num} is{factorial(num)}")

program 4
def fibonacci(n):
    fib_sequence = [0, 1]
    for i in range(2, n):
        fib_sequence.append(fib_sequence[-1] + fib_sequence[-2])
    return fib_sequence[:n]
num = int(input("Enter a number: "))
print(f"First {num} Fibonacci numbers: {fibonacci(num)}")
program 5
def reverse_string(s):
    return s[::-1]
text = input("Enter a string: ")
print("Reversed string:", reverse_string(text))

program 6
def is_palindrome(s):
    return s == s[::-1]
text = input("Enter a string: ")
print("Is palindrome:", is_palindrome(text))
program 7

def is_leap_year(year):
    return (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0)
year = int(input("Enter a year: "))
print("Is leap year:", is_leap_year(year))

program 8
def is_armstrong(n):
    digits = str(n)  # Convert number to string to get digits
    power = len(digits)  # Number of digits
    total = sum(int(digit) ** power for digit in digits)  # Sum of each digit raised to the power
    return total == n  # Check if sum matches original number

num = int(input("Enter a number: "))
print("Is Armstrong number:", is_armstrong(num))











