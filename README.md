# calculator
calculator using Python

first_number = int(input("Enter first number :"))
op = input("Enter operator :")

second_number = int(input("Enter second number :"))
if op == "+":
    print(first_number + second_number)
elif op == "-":
    print(first_number-second_number)
elif op == "*":
    print(first_number * second_number)
elif op == "/":
    print(first_number / second_number)
else:
    print("invalid operator")
