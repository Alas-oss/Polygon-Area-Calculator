# Polygon-Area-Calculator
This Python program defines two classes, Rectangle and Square, which represent basic geometric shapes. The Rectangle class provides functionality to calculate various properties of a rectangle, such as area, perimeter, diagonal, and more. The Square class inherits from Rectangle, with adjustments specific to squares, ensuring that width and height remain equal.

## Features
### Rectangle Class
The Rectangle class is designed to model a rectangle and provides several methods for interacting with the shape's properties.

### Attributes:

- width: The width of the rectangle.
- height: The height of the rectangle.

### Methods:

- set_width(width): Sets the width of the rectangle.
- set_height(height): Sets the height of the rectangle.
- get_area(): Calculates and returns the area of the rectangle (width * height).
- get_perimeter(): Calculates and returns the perimeter of the rectangle (2 * width + 2 * height).
- get_diagonal(): Calculates and returns the diagonal of the rectangle using the Pythagorean theorem.
- get_picture(): Returns a text-based representation (drawing) of the rectangle using * characters. If the rectangle is too large (greater than 50 units in width or height), 
- it returns "Too big for picture."
- get_amount_inside(shape): Calculates how many smaller shapes (e.g., another rectangle or square) can fit inside the current rectangle.
### Square Class (Inherits from Rectangle)
The Square class inherits from Rectangle and modifies its behavior to ensure both sides are equal, as squares have equal width and height.

### Methods:
- set_side(side): Sets both width and height to the same value, ensuring the shape is a square.
- set_width(width): Overrides the Rectangle method to set both sides to the same width.
- set_height(height): Overrides the Rectangle method to set both sides to the same height.
- __str__(): Returns a string representation of the square (Square(side=x)).
