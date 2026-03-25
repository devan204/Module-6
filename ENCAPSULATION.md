# Exp.No:30  
## IMPLEMENTATION OF ABSTRACT BASE CLASS USING POLYMORPHISM IN SHAPE SUBCLASSES

---

### AIM  
To create an abstract base class named Polygon with an abstract method sides(), and implement this method in its subclasses Triangle, Square, Pentagon, and Hexagon. Then, create objects of each subclass and call the sides() method to display the number of sides for each polygon.

---

### ALGORITHM

Import Required Module:

Import ABC and abstractmethod from the abc module.

Define the Abstract Base Class:

Create a class named Polygon that inherits from ABC.

Define an abstract method sides() using the @abstractmethod decorator.

Define Subclasses:

Create classes Triangle, Square, Pentagon, and Hexagon that inherit from Polygon.

In each subclass, override and implement the sides() method to display the number of sides for that polygon.

Driver Code:

Create objects of each subclass.

Call the sides() method for each object.

---

### PROGRAM

```
from abc import ABC,abstractmethod  
  
class Polygon(ABC):   
  
   @abstractmethod   
   def sides(self):   
      pass  
  
class Triangle(Polygon):
    def sides(self):
        print("Triangle has 3 sides")   
  
class Pentagon(Polygon): 
    def sides(self):
        print("Pentagon has 5 sides")
  
     
   #Add code here
class Hexagon(Polygon):
    def sides(self):
        print("Hexagon has 6 sides")
  
   #Add your code
class square(Polygon):
    def sides(self):
        print("I have 4 sides")   
  
# Driver code   
t = Triangle()
t.sides()
 
  
s = square()
s.sides()
  
  
p = Pentagon() 
p.sides()

  
k = Hexagon()
k.sides()
```

### OUTPUT
![Screenshot (252)](https://github.com/user-attachments/assets/18bf4bf8-0ccf-4a8d-83c3-0aa693034f29)


### RESULT
Thus the python program was initialised and executed successfully.
