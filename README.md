# _-and-numbers
count1=0
count2=0
count3=0
for i in range(1,11):
    x = int(input())
    if x<0:
        count1= count1+1
    elif x>0:
        count2=count2+1
    elif x==0:
        count3=count3+1
print("positive numbers are:",count2)
print("negative numbers are:",count1)
print("zero are:",count3)
