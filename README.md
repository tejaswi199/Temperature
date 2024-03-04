#Approach 1
n=int(input())
for i in range(n):
  f=int(input())
  if(f>98):
    print("YES")
  else:
    print("NO")
#Approach 2
n=int(input())
i=0
while(n>i):
  f=int(input())
  if(f>98):
    print("YES")
  else:
    print("NO")
  i=i+1
#Approach 3
n=int(input())
while(n>0):
  f=int(input())
  if(f>98):
    print("YES")
  else:
    print("NO")
  n=n-1
