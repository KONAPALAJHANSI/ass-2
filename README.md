n=1000000
pf=[0]*(n+1)
for i in range(1,n):
    pf[i]=pf[i-1]+1
m=int(input())
print(pf[m])
