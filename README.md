# Assignment-5


Employee Payroll Management System
This is a Java application that allows you to manage employee payroll information. You can add, edit, and delete employee records, and the system will automatically calculate their monthly salaries based on the inputs you provide.

Employee and BonusEmployee. Employee is an abstract class that serves as a superclass for BonusEmployee. The BonusEmployee class extends the Employee class and adds a monthly bonus percentage field and a method to calculate the monthly salary including the bonus.

The calculateMonthlySalary method in the BonusEmployee class calculates the monthly salary including the bonus by overriding the calculateMonthlySalary method of the Employee class. The method calculates the basic wage, HRA, EPF, ESI, and other allowances for the BonusEmployee and then calculates the total earnings, total deductions, and net salary including the bonus.

The Employee class contains fields for name, address, gross wage, total working days, and paid working days. It also includes getters and setters for name, address, and gross wage.




Shapes
This program implements a simple Shape interface that allows the user to create and calculate the area and perimeter of different shapes, including Circle, Rectangle, Square, and Triangle.

To use this program, you can create a new instance of any of the classes mentioned above, passing the appropriate parameters in the constructor. Then, you can call the calculateArea() and calculatePerimeter() methods to calculate the area and perimeter of the shape, respectively. Finally, you can call the toString() method to get a string representation of the shape and its properties.

Here is a brief overview of each shape class and its properties:

Circle: Represents a circle shape, with a radius (rad) property. Calculates the area and perimeter of the circle using the formulae pi * rad^2 and 2 * pi * rad, respectively.
Rectangle: Represents a rectangle shape, with a length (length) and breadth (breadth) property. Calculates the area and perimeter of the rectangle using the formulae length * breadth and 2 * (length + breadth), respectively.
Square: Represents a square shape, with a side (side) property. Calculates the area and perimeter of the square using the formulae side * side and 4 * side, respectively.
Triangle: Represents a triangle shape, with three sides (side1, side2, and side3) properties. Calculates the area and perimeter of the triangle using the formulae 0.5 * side1 * side2 and side1 + side2 + side3, respectively.
In the Shape interface, we have also defined a constant pi to use in the area and perimeter calculations of the circle shape.

In the Demo class, we have provided an example of how to use each of the shape classes. We create an instance of each shape class, calculate its area and perimeter, and then print out its properties using the toString() method.
