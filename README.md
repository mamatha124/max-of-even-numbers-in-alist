# max-of-even-numbers-in-a-list in python
# max of even numbers in a list
# approach-1
n=int(input())
a=list(map(int,input().split()))
r=0
for i in range(n):
  if a[i]%2==0 and a[i]>r:
    r=a[i]
print(r)

# approach-2
n=int(input())
a=list(map(int,input().split()))
r=0
for i in a:
  if i%2==0 and i>r:
    r=i
print(r)

# approach-3
n=int(input())
a=list(map(int,input().split()))
r=[]
for i in range(n):
  if a[i]%2==0:
    r.append(a[i])
print(max(r))

# approach-4
n=int(input())
a=list(map(int,input().split()))
r=[]
for i in a:
  if i%2==0:
    r.append(i)
print(max(r))

