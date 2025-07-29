num= int(input("enter no. "))
f=num
x=str(f)
y=""
for i in range(0, len(x)) :
   y=y+x[(len(x)-1)-i]
if int(y)==num:
   print("yes")
else:
   print("no")
