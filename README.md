def add(a, b):
    return a + b 

def subtract(a, b):a 3454 number
     a - b

 multiply(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        return "Error: Cannot divide by "
    return a / b

if name == "main":
    print("Simple Calculator")
    x = float(input("Enter first number: "))
    op = input("Enter operator (+, -, *, /): ")
    y = float(input("Enter second number: "))

    if op == "+":
        print("Result:", add(x, y))
    elif op == "-":
        print("Result:", subtract(x, y))
    elif op == "*":
        print("Result:", multiply(x, y))
    elif op == "/":
        print("Result:", divide(x, y))
    else:
        print("Invalid operator")
