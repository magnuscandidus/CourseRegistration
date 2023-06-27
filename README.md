# CourseRegistration
t=int(input())
while t:
    n,m,k=map(int,input().split())
    if((m-k)>=n):
        print("YES")
    else:
        print("NO")
    t-=1
