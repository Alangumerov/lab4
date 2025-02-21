1)import math
def degree_to_radian(a):
 b=a*(math.pi/180)
 return b
a=int(input())
b=degree_to_radian(a)
print(b)

2)import math
def trapezoid(base1, base2, height):
  area=0.5*(base1+base2)*height
  return area
height=int(input())
base1=int(input())
base2=int(input())
area2=trapezoid(base1, base2, height)
print(area2)

3)import math
def polygon(n,a):
 if n==4:
     area=a**2
     return area
 else: 
     area=(n* s**2)/(4*math.tan(math.pi/n))
     return area
n=int(input())
a=int(input())
area=polygon(n,a)
print(area)

4)import math
def parallelogramm(h,a):
     area=h*a
     return area
h=int(input())
a=int(input())
area=parallelogramm(h,a)
print(area)

