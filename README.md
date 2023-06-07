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

D = {1:5.6, 2:7.8, 3:6.6, 4:8.7, 5:7.7}
D[8] = 8.8
print ("After Adding (8) --> ", D)

del D[2]
print ("After Deleting (2) --> ", D)

print(6 in D)
print(len(D))
print(sum(D))
D[3] = 7.1
print ("After Updating (3) --> ", D)

D.clear()
print ("After Clear --> ", D)

S1= set([10, 20, 30, 40, 50, 60])
S2= set([40, 50, 60, 70, 80, 90])
S1.add(55)
S1.add(66)
print(S1)
S1.remove(10)
S1.remove(30)
print(S1)

print(40 in S1)

S1= set([10, 20, 30, 40, 50, 60])
S2= set([40, 50, 60, 70, 80, 90])
print(S1.union(S2))
print(S1.intersection(S2))
print(S1 - S2)

import random as r
import random
import string as s
a = random.randint(6,8)
for i in range(0,101):
 passwd=r.sample(s.ascii_letters, a)
 print (passwd)

lower = 600
upper = 800
print("Prime numbers between", lower, "and", upper, "are:")
for num in range(lower, upper + 1):
   if num > 1:
       for i in range(2, num):
           if (num % i) == 0:
               break
       else:
           print(num)
print("Numbers that are divisible by 7 and 9:")
begin 	= 100
end 	= 1000
for i in range(begin, end+1):
	if( i%7==0 and i%9==0 ):
		print(i)
    
    import random
for i in range(0,2):
  randomlist = random.sample(range(10, 30), 10)
  print(randomlist)
