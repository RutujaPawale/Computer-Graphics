Write a C++ program using the graphics.h library to draw a Hilbert Curve of recursion level 'n'. Your program should:

1. Accept the recursion depth n from the user.

2. Use a recursive approach to draw the Hilbert curve.

3. Define a move() function that draws a line in the specified direction (up, right, down, left).

4. Define a hilbert() recursive function that:

    -Draws the Hilbert pattern based on four directional arguments (r, d, l, u),
    -Takes recursion depth i, step size h, and current coordinates x, y as input,
    -Makes recursive calls to draw the pattern in each quadrant.

5. Initialize the graphics window using initwindow() with custom resolution.

6. Use moveto() and lineto() to perform graphical movement and drawing.

7. Display the output for at least 10 seconds and then close the window.
