# Simple-python-calculator
operator = input("Enter your operator (+ - * /): ")
a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

if operator == "+":
    result = a + b
    print(round(result, 3))
elif operator == "-":
    result = a - b
    print(round(result, 3))
elif operator == "*":
    result = a * b
    print(round(result, 3))
elif operator == "/":
    if b != 0:  
        result = a / b
        print(round(result, 3))
    else:
        print("Error: Division by zero is not allowed.")
else:
    print("Invalid operator")

