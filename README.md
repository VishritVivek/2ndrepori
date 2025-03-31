a=int(input("ENTER A NUMBER : "))
b=list(range(2,1000,2))
if a in b:
    print(a," IS EVEN")
else:
    print(a," IS ODD")

a=list(range(1,51))
for x in a:
    print(x)
z=sum(a)
print("THE SUM OF ALL NUMBERS FROM 1 TO 50 AS ABOVE IS : ",z)
