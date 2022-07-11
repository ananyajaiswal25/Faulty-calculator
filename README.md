# Faulty-calculator
It's a calculator which calculates everything for you! But i have added different values that will give you wrong values i.e., faulty values!

HERE IS THE CODE!!

val1 = int(input("Enter your first input: "))
val2 = int(input("Enter your second input:"))
operator = input("Select your operator among *,+,-,/ :")

if operator == "+":
    if val1 == 56 and val2 == 9:
        print("77")
    else:
        print("Sum is:",val1 + val2)
if operator == "-":
    print("Substract is:",val1-val2)
if operator == "*":
    if val1 == 45 and val2 == 3:
        print("555")
    else:
        print("Multiply is :",val1*val2)
if operator == "/":
    if val1 ==56 and val2 == 6:
        print("4")
    else:
        print("Divide is:",float(val1/val2))
