# Python_Calculator
print("Please enter a operation, After you enter and operation press the enter key")
print("/ means divide")
print("* means multiply")
print("- means subtract")
print("+ means add")
op = input()
if (op == "-") or (op == "+") or (op == "*") or (op == "/"):
    print("good")
else:
    print("bruh")
    quit()

if op == "+":
    print("Enter the numbers you would like to add")
    a = int(input())
    b = int(input())
    sum = a + b
    print(sum)
elif op == "-":
    print("Enter the numbers you would like to subtract")
    a = int(input())
    b = int(input())
    diff = a - b
    print(diff) 
elif op == "*":
    print("Enter the numbers you would like to Multiply")
    a = int(input())
    b = int(input())
    product = a * b
    print(product)   
elif op == "/":
    print("Enter the numbers you would like to Divide")
    a = int(input())
    b = int(input())
    quo = a / b
    print(quo)   

