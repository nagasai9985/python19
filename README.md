#swapping using arthamatic operation *,/
a= int (input("enter the value of a :"))
b= int (input("enter the value of b :"))
print('before the swap',a,b)
a=a*b
b=a/b
a=a/b
print("after swap a=", round (a),"b=",round (b))
