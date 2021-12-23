# PYTHON
#LEAP YEAR 
n=input("please enter year =")
year=int(n)
if ((year%400==0)or((year%4==0)and (year%100!=0))):
    print(n+ " is a leap year")
else:
    print(n+ " is not a leap year")
