# python-sum-ofn-natural-no-using-dictionaries

d={}
n=int(input())
for i in range(1,n+1):
  res=0
  for j in range(1,i+1):
    res=res+j 
  d[i]=res
print(d)  


#product of n natural number values
d={}
n=int(input())
for i in range(1,n+1):
  res=1
  for j in range(1,i+1):
    res=res*j 
  d[i]=res
print(d)  
