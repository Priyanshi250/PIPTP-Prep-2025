# Week1 - Day 1

## Problems
- Problem 1
 ```python
 def fun(w,x):
 y=0
 if((x%w == 0) or (w%x) == 0):
 y= y+1;
 else:
 y= y+10
 print(y)
 print(fun(40,4))
```
## Aproach
In this question we use % operator and or operator to solve the question in the first if condition true then the value of y updated and reach the answer.
## Final Answer
1
- Problem 2
```python
 Integer a
 Set a = 1
 while(a<5)
 a = a+2;
 end while
 print a
 ```
  ## Aproach
  for this question we use simple while loop condition and if it true updtae the value.
## Final Answer
5
## Problem - 3
``` python
def fun(a,b):
if(a and b and(a+b)>0):
return a+ fun(a-2,b-2)+b
return a^b
res = fun(8,8)
print (res)
```
## Approach
Here for this we use ^ is the bitwise  XOR the compare the value of two number in such way that same bit  will be 0 and different bit should be 1 and then return the function.

## Final Answer
40

## Problem - 4
```python
Integer a,b
Set a=3, b= 3
a=b
if(1^1)
a=1
Else
b=2
End if
Print a+b
```
## Approach
Here for this we use ^ is the bitwise  XOR the compare the value of two number in such way that same bit  will be 0 and different bit should be 1 for this if condition false the value of b updated to 2 then a= 3 and b= 2 then the result will be 5.
## Final Anser
5

## problem 4
```python
def fun(a,b):
for c in range (2,5):
if((a%2) <(b%3)):
a = 4%3
if(5%3 >b):
a= b
b=1
return (a+b)
print(fun(7,5))
```
##Approach
here for this question we apply loop from 2 to 5 in which apply % operation and using if condition it and return the function for a = 7 and b =5 .
## Final Answer
2

