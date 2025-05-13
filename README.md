# Python-assignment1-
try:
    a = int(input("Enter numerator: "))
    b = int(input("Enter denominator: "))
    result = a / b
    print("Result:", result)
except ZeroDivisionError as e:
    print("Error:", e)

try:
    print(undeclared_variable)
except NameError as e:
    print("Error:", e)
    
