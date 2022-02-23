# Ass-1-23-2-2022
max and min value in list 




l=[]
n=int(input('enter n'))
for i in range(n):
   c=int(input())
   l.append(c)
min=l[0]
for i in range(1,n):
   if l[i]<min:
     min=l[i]
max=l[0]
for i in range(1,n):
   if l[i]>max:
     max=l[i] 
print(min) 
print(max)

o/p:
enter n:3
10
20
30

10
30
