REVIEW: binarySearch, fibonacciSequence, code-alongs in class, homeworkAssignments, etcs.

Memory Storage:

data goes into the memory address(variables, primitive, etc.), this then determines the memory storage that the code uses.
1 byte = 8 bits
EXAMPLE: int var = 5, contains 5 bytes of storage.

SAV means:
Save - Creating inputs and outputs to test
Action - Feed inputs to the function tested
Verify - Compare actual outputs with expected outputs

Object Oriented Programming is helpful to keeping group related information together.

Class: Is a template
Object: Concrete object

A class has behaviors or variables in which the class follows and has. Class methods are really actions of the object of the class.

Inheritance: best used when multiple classes have duplicated variables that are the same within those classes.

-The base class is what is made to help reduce the duplicated variables found within the subclasses.
-base classes has its base class constructors and possibly functions as well.

To summarize inheritance it is a...
-base class and its subclasses or derived classes
-can use super to access the base class
-DOES NOT support inheritance from multiple classes though

Override vs Overload:

Override:
Re-implement a function in derived class from base class with the...
-same name
-same signature
EXAMPLES: equal() and toString() functions are overrided

Overload:
Re-implement a function in the same class...
-same name
-different signatures

Polymorphism:
The ability of a class to provide different implementations of a method, depending on the type of object that is passed to the method.

OOP:

Encapsulation
-class vs object/instance vs reference
-default access
-private memeber vs public method (setter/getter)

Inheritance
-base class and derived class
-calling base class copy constructor
-override vs overload

Polymorphism ("many form")
-accesssing derived class object using base class reference

Abstract class: helps provide the function played but unique to each class or subclass.

Interface class: implements actions that are found in the inherited class or for classes that have the same function.

NOTE*
java is always pass by value
-the value of a primitive type is its value
-the value of an object type is its reference("memory address")

Complexity is cost of time and resources:
-CPU
-Disk
-network
-Power

LESS TIME = LESS MEMORY

1-pass is each element used one time

"Big O" notation is space, and execution time. "O" reads as "order of".
-speed grows as elements increase.

EXAMPLE VIA CHATGPT:
Time complexity example:
Suppose we have an unsorted list of n integers and we want to find the maximum value. A simple algorithm to do this would be to iterate through the list, comparing each value to a running maximum and updating the maximum if we find a larger value. The time complexity of this algorithm would be O(n), because in the worst case we would need to compare every value in the list.

Space complexity example:
Suppose we have an array of n elements and we want to create a new array that contains only the even elements from the original array. One way to do this would be to iterate through the original array, checking each element to see if it is even and adding it to the new array if it is. The space complexity of this algorithm would be O(n), because in the worst case the new array would need to contain all n elements of the original array.

