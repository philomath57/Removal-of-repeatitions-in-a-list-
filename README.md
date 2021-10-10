# Removal-of-repeatitions-in-a-list
l=[1,1,2,2,3,3,4,4,5,5]
r=[]
for i in l:
  if i not in r:
    r.append(i)
print(r)



l= list(set(l))
print(l)
