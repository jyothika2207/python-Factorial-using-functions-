# python-Factorial-using-functions-

fact= 1
def factorial(n):
    global fact
    fact= 1
    for i in range(1,n+1):
        fact *=i
    return fact
        
num= int(input("enter a number"))
if num<0:
    print("cannot derive fact for -ve numbers")
else:
    factorial(num)
    print(f" Factorial of {num} is",fact)


    =========OUTPUT=============
    enter a number 5
   Factorial of 5 is 120
