# 04-03-2022-assignment-1
n=int(input('enter the no of values you want: '))
l=[]
c=0
for i in range(n):
    x=int(input())
    l.append(x)
dup=[]
for i in l:
    if i not in dup:
        dup.append(i)
    else:
        c=c+1
print('after removing duplicate values: ',dup)
print('no of duplicate values: ',c)
