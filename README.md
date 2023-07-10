# PassingMark
# cook your dish here
t=int(input())
while t:
    a1,b1,c1,t1,a,b,c=map(int,input().split())
    if(a>=a1 and b>=b1 and c>=c1 and (a+b+c)>=t1):
        print("Yes")
    else:
        print("No")
    t-=1
