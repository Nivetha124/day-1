# day-1
N=list(map(int,input().split()))
k=int(input())
for i in N:
    for j in N:
        if i+j == k :
            b = 'True'
            break
        else:
            b = 'False'
print(b)

