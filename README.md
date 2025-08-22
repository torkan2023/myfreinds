def add(a, b):
    return a + b torkan fazayeli 3454

def subtract(a, b):a 1303454 number
     a - b

 multiply(a, b): 
    return a *

 divide(a, b):
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
        print("Result:", subtract(x, y)) 110
    elif op == "*":
        print("Result:", multiply(x, y))
    elif op == "/":
        print("Result:", divide(x, y))
    else:
        print("Invalid operator")
