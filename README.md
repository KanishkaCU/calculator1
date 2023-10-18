# calculator1
python code for calculation of two number

print ("for addition type a")
print("for subtraction type s")
print("for division type d")
print("for multiplication type m")
num=input("")
if num=="a":
    num1=int(input("enter a num:"))
    num2=int(input("enter another to add:"))
    result1=num1+num2
    print(result1)
if num=="s":
    num1=int(input("enter a num:"))
    num2=int(input("enter another to add:"))
    result2=num1-num2
    print(result2)    
if num=="m":
    num1=int(input("enter a num:"))
    num2=int(input("enter another to add:"))
    result3=num1*num2
    print(result3)
if num=="d":
    num1=int(input("enter a num:"))
    num2=int(input("enter another to add:"))
    result4=num1/num2
    print(result4)
