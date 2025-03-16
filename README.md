# Basic-calculator
This calculator took a while to create. Just addition and subtraction.

print("Select operation to perform")

print("1. Add")
print("2. Subtract")

operation = input()

if operation == "1": 
    # Getting user input for operation
    num1 = input("Enter the first number: ")
    num2 = input("Enter the second number: ")
    print("The sum is: " + str(int(num1) + int(num2)))

elif operation == "2":
    # User input for subtraction.
    num1 = input("Enter the first number: ")
    num2 = input("Enter the second number: ")
    print("The difference is: " + str(int(num1) - int(num2)))
    
else:
    print("Invalid input")

