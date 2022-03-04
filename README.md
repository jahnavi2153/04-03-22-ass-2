# 04-03-22-ass-2
#Write a program to find second runner up of the person based on given data.
n = int(input())
a=(int, input().split())
x=[]
for i in a:
    x.append(i)
    num=x[1]
y=[int(j) for j in num]
z=(sorted(y,reverse=True))
List = []
for j in z:
    if j!= max(z):
        List.append(i)

print(max(List))
