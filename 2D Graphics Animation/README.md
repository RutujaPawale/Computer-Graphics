Write a C++ program using the <graphics.h> library to visually simulate a sunrise and sunset animation. The program should include the following features:

1. Sun Drawing:
The sun should be represented as a yellow circle that rises from the bottom of the screen (near the horizon) during sunrise and sets back during sunset.

2. Ground and Mountains:
Draw a white ground line near the bottom of the screen.
Behind the ground, draw static dark gray mountains using the fillpoly() function to create a scenic background.

3. Shadows:
Simulate dynamic shadows that change length and direction depending on the vertical position of the sun. As the sun rises, shadows become shorter; as the sun sets, they become longer again.

4. Sunrise and Sunset Animation:
In the sunrise() function, animate the sun rising from the horizon to the top.
In the sunset() function, animate the sun setting from the top back to the horizon.
Use a for loop to animate the sun’s vertical movement, and delay() to control animation speed.
Clear and redraw the scene in each loop iteration to simulate motion.

5. Graphics Initialization:
Initialize the graphics driver using initgraph().
After the sunrise completes, add a short delay, then execute the sunset animation.
Use closegraph() to properly shut down the graphics mode.
