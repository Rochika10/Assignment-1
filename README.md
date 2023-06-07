# Assignment-1
L = [11,12,13,14]
L2 = [50,60]
print(L + L2)

del L[0]
del L[1]
print(L)

L = [11,12,13,14]
L.sort()
print(L)

L.reverse()
print(L)

L = [11,12,13,14]
print(13 in L)
if(13 in L) == True:
  print("Present in list")
else:
  print("Not present")

print(len(L))
print(sum(L))

def solve(L):
   return sum([i for i in L if i % 2 == 1])
print(solve(L))

def solve(L):
   return sum([i for i in L if i % 2 == 0])
print(solve(L))

def solve(L):
   return sum([i for i in L if i % 2 == 1])
print(solve(L))

L.clear()
print(L)

del(L)
