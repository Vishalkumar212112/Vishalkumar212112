
print("W_e~l*c(o)m[e] ")
print("python calculator")
print("Addition '+' ")
print("Subtraction '-' ")
print("Multiplication '*' ")
print("Division '/' ")


num1 = float(input("Enter the number: "))
opr = input("Enter the opertor ")
num2 = float(input("Enter the number: "))


if opr == "+":
    print("Result: ", num1 + num2)
elif opr == "-":
    print("Result: ", num1 - num2)
elif opr == "*":
    print("Result: ", num1 * num2   ) 
elif opr == "/":
    print("Result: ", num1 / num2 )


else:
    print("Invalid operator ")


