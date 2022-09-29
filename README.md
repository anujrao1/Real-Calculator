# Real-Calculator

def add(a,b):
    addition = a+b
    print("The sum of ",a,"and",b,"is",addition)
    return addition
  
def sub(a,b):
    subtraction= a-b
    print("The subtraction of ",a,"and",b,"is",subtraction)
    return subtraction
    
def mul(a,b):
    multipication = a*b
    print("The multipication of ",a,"and",b,"is",multipication)
    return multipication
    
def div(a,b):
    division = a/b
    print("The  of ",a,"and",b,"is",division)
    return division

number1 , operator , number2 = map(str,input("Enter the Equation:").split())=8/9
number1 = int(number1)
number2 = int(number2)

if operator =="+":
    add(number1,number2)
    
elif operator=="-":
    sub(number1,number2)
    
elif operator=="*":
    mul(number1,number2)
    
elif operator=="/":
    div(number1,number2)
     
else :
         print("invalid no. type something else")
