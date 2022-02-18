# 18-2-22-ASSIGNMENT
def isprime(n):
    for i in range(2,n):
        if n%i==0:
            return False
    return True
n=int(input())
c=0
for i in range(2,n+1):
    if isprime(i):
        c=c+1 
print(c)




OUT PUT 
NO OUT PUT IS COMING SIRRR
