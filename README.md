Mini-Calculator using python

# Mini-Calculator
print("                  *** MINI CALCULATOR ***")
print("Enter the 1st number")
a=int(input())
print("Enter the 2nd number")
b=int(input())
print("Enter the calculate operators you want- Choose any of this operator (+,-,*,/)")
c=input()
if c=="+":
    print("Result is:", a+b)
elif c=="-":
    print("Result is:", a-b)
elif c=="*":
    print("Result is:", a*b)
elif c=="/":
    print("Result is:", a/b)
else:
    print("Invalid numbers or operator to perform it - Please try again!")
