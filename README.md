# Circle Metrics Calculator

## Description

This C++ program, contained in `circle.cpp` and `circle.h`, calculates various metrics of a circle based on user input for the radius. The program prompts the user to input the radius of the circle and then computes and displays its area and circumference.

## Files Included

### `circle.cpp`

This file contains the main logic of the program. Upon execution, it does the following:

- Allocates memory for a Circle object using dynamic memory allocation.
- Prompts the user to input the radius of the circle.
- Sets the user-input radius value for the Circle object.
- Calculates and displays the area and circumference of the circle based on the provided radius.

### `circle.h`

This header file defines the Circle class. It includes:

- Private member variables for the radius, area, circumference, and a constant for π (pi).
- A constructor that initializes the radius, area, and circumference pointers.
- Public member functions:
  - `set_rad(double rad)`: Sets the radius of the circle.
  - `compute_area()`: Calculates and returns the area of the circle.
  - `compute_circumference()`: Calculates and returns the circumference of the circle.
  - `check_rad(double rad)`: Checks if the radius is valid (greater than zero).
  - Destructor to release allocated memory.

## How to Use

1. **Compile and Run:**
   - Compile `circle.cpp` and link it with `circle.h` in your preferred C++ compiler.
   - Execute the compiled program.

2. **Input:**
   - Enter the radius of the circle as prompted by the program.

3. **Output:**
   - The program will display the calculated area and circumference of the circle based on the provided radius.

## Code Structure

- `circle.cpp` contains the main code to execute the program, prompt for user input, and display results.
- `circle.h` defines the Circle class with functions to perform calculations on the given radius.

## Note

- Ensure valid input for the radius (positive and non-zero) to get accurate results.
