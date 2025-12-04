# overtime-pay

ovpay=0
sum=0
for i in range(1,11):
     print("Enter Working Hours of Emp ",i,":")
     h=int(input())
if(h>40):
     extra=h-40
     ovpay=extra*12
     print("Over time pay of emp ",i,"is ",ovpay)
     sum=sum+ovpay
else:
     print("No Overtime Pay")

print("Total Overtime Pay of all employees : ", sum)

output
Enter Working Hours of Emp  1 :
45
Enter Working Hours of Emp  2 :
52
Enter Working Hours of Emp  3 :
44
Enter Working Hours of Emp  4 :
50
Enter Working Hours of Emp  5 :
60
Enter Working Hours of Emp  6 :
68
Enter Working Hours of Emp  7 :
75
Enter Working Hours of Emp  8 :
86
Enter Working Hours of Emp  9 :
90
Enter Working Hours of Emp  10 :
66
Over time pay of emp  10 is  312
Total Overtime Pay of all employees :  312
