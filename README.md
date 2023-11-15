# Display-digit-of-a-number

num=int(input("Enter number:"))
if num!=0:
   while (num!=0):
    digit=num%10
    num=num//10
    print(digit)
