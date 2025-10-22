# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
class Rectangle:
    def __init__(self, length, width):
        self.__length = length  # Private variable
        self.__width = width    # Private variable
    
    # Method to print private variables
    def print_values(self):
        print(self.__length)
        print(self.__width)

# Create an object of Rectangle class
rect = Rectangle(5, 3)

# Print private values using the method within the class
rect.print_values()

# Attempt to print private values outside the class (will raise an AttributeError)
## Output
<img width="1268" height="299" alt="Screenshot 2025-10-22 210755" src="https://github.com/user-attachments/assets/a3e70da5-72e2-47e7-90d1-c5ee04fbb5ca" />

## Result
thus the progrem runs successfully
