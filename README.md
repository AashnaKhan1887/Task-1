# Task-1
Python scripts for Task 1 and Task 2 assignments

# Basic Math Operations Program

# Taking input from the user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Performing operations
addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 * num2

# Handling division safely 
if num2 != 0:
    division = num1 / num2
else:
    division = "Undefined (can't divide by zero 😬)"

# Displaying results
print("\n📊 Results:")
print(f"➕ Addition: {addition}")
print(f"➖ Subtraction: {subtraction}")
print(f"✖️ Multiplication: {multiplication}")
print(f"➗ Division: {division}")
