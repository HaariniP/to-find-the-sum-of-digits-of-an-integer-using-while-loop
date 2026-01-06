# to-find-the-sum-of-digits-of-an-integer-using-while-loop
sum=0
number=int(input("Enter an integer:"))
while(number!=0):
    digit=number%10
    sum=sum+digit
    number=number//10
    print("Sum of digits is:",sum)
output
Enter an integer:65
Sum of digits is: 5
Sum of digits is: 11
