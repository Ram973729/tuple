# Remove even numbers
n=int(input())
l=[]
l=list(map(int,input().split()))
for i in l:
    if i%2==0:
        l.remove(i)
print(l)        
