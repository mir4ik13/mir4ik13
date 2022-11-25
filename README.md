import math
print ("Input a,x,K,b")
a=float(input())
x=float(input())
K=float(input())
b=float(input())
if ((a != 0) and ((K*math.pow((((b * x) / a) + 1), 2) != 0))):
    L = ((b * x) / a) + 1
    M = (((a * math.pow(x, 2)) + math.sin(math.pow(x, 3)) + math.exp(x) - math.sqrt(math.fabs(a + x))) / (K * math.pow(L, 2)))
    print ("M=",M)
else:
    print ("error")
    
