# Newton-Raphson-method

Program:
```python3
def f(x):
return x**3-x-2
def f1(x):
return 3*x**2-1
xo=float (input ("Enter the initial approximation: "))
for i in range (1,10):
xn=xo-f(xo)/f1(xo)
xo=xn
print ("The approximate root using Newton-Raphson method is %.4f"%xn)
```
Output:
Enter the initial approximation: 1
The approximate root using Newton-Raphson method is 1.5214
