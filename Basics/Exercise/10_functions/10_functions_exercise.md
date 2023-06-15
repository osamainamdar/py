# Exercise: Functions in python
1. Write a function called calculate_area that takes base and height as an input and returns and area of a triangle. Equation of an area of a triangle is,

def area(height,base):
  area = (1/2)*base*height
  return area
print("Area of the Triangle is:",area)


2. Modify above function to take third parameter shape type. It can be either "triangle" or "rectangle". Based on shape type it will calculate area. Equation of rectangle's area is, If no shape is supplied then it should take triangle as a default shape
   
'''Here h is height & b is base and n is the number of sides of the shape'''  
def Area(h,b,n=3): 
  area = ((n-2)*b*h)/2
  return area
if n=3:
  print("Area of Triangel is:",area)
elif n=4:
  print("Area of Rectangle is:",area)
else:
  print("pass the appropriate n value")
  

3. Write a function called print_pattern that takes integer number as an argument and prints following pattern if input number is 3,
```
*
**
***
```
if input is 4 then it should print
```
*
**
***
****
```
Basically number of lines it prints is equal to that number. (Hint: you need to use two for loops)

def print_pattern(n):
  for i in range(1, n+1):
    print('*' * i)
    
[Solution](https://github.com/codebasics/py/blob/master/Basics/Exercise/10_functions/10_functions_exercise.py)
