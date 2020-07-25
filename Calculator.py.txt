#Simple calculator in python with error handling
first = float(input("Enter first number: "))
second = float(input("Enter second number: "))
symb = input("Choose symbol +, -, , *, /, //, % : ")
if symb == "+":
    result = first + second
elif symb == "-":
    result = first - second
elif symb == "*":
    result = first * second
elif symb == "**":
    result = first ** second
elif symb == "/":
    result = first / second
elif symb == "//":
    result = first // second
elif symb == "%":
    result = first % second
else:
    print("Wrong symbol input try again...")
    exit()
print("Result is %.2f" %result)