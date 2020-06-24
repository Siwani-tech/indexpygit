num=121
temp=num
sum=0


while temp>0:
    digit=temp%10
    sum=sum*10+digit
    temp//=10


if num==sum:
    print('armstrong no')

else:
    print('not')
