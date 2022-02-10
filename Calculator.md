#I am a bigginer in python i made this code on my own, i did'nt used ANY module its fully self built . 
#Thanks

# Basic-Calculatior
num1 = int(input("First number")) #it asks for number 1 and then operation like = +,-,/,*  . then asks for number 2
Operation = input("Operation")
num2 = int(input("Second number"))

#num = number

multiply = ("*")
subtract =("-")
divide =("/")
add = ("+")
#set value for these "*" is for muliply,'/' is for divide, '+' is for add, '-' is for subraction 


if Operation == add:      #this checks if your operation is = add,multiple,divide or subract. 
    print(num1+num2)
elif Operation == multiply:
    print(num1*num2)
elif Operation == subtract:
    print(num1-num2)
elif Operation == divide:
    print(num1/num2)
else:
    print("Incorrect Operation")

#format for inputing charecters is as follow:-
#q+b,p*s,x/y,i-h
