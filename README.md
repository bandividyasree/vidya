# vidya
#question 1
#solution 1
a,b=input().split()
if b in a:
    print("True")
else:
    print("False")
#solution 2
a,b=input().split()
a=int(a)
b=int(b)
m=-1
while(a!=0):
    c=a%10
    a=a//10
    if(b==c):
        m=1
if(m==1):
    print("True")
else:
    print("False")
    
