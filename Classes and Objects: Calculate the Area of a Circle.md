# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

```py

class cse:
    def mech(self, r):
        area = 3.14 * r * r
        print("Area of circle is:", area)

radius = float(input())

obj = cse()
obj.mech(radius)
```
## Output
<img width="534" height="310" alt="image" src="https://github.com/user-attachments/assets/08de1243-3674-4344-b5e2-72cd9d51ecab" />


## Result
The Python program was executed successfully, and the area of the circle was calculated using a class and method based on the given radius. The result was displayed correctly.
