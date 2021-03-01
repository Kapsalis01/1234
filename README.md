# ask2
while True:
  k=input("dose enan oro:")
  k=int(k)
  if(k>3):
        arF=[0,1,2]
        break
  else:
       print("oi arithmoi 0,1,2 einai protoi")
print("o k egine akeraios arithmos",k)
import random
for i in range(3,k):
     arF.append(arF[i-2]+arF[i-1])
x=len(arF)-1
p=0
print(arF[x])
for i in range(20):
     randomvalue=random.randint(1,100)
     if ((randomvalue ** arF[x]) % arF[x] == randomvalue %  arF[x]):
          p += 1
if(p==20):
     print("o arithmos", arF[x],"einai protos")
else:
     print("o aritmos", arF[x],"den einai protos")
