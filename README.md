# Reverse-Number-in-python

#Reverse number simple Ways:

n=int(input("Enter the Number"))
s=0
while n!=0:
    d=n%10
    s=s*10+d
    n=n//10
print("Reverse number",s)
