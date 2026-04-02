Traffic Simulator using a cellular automata.

For each clock tick do the following:
I. Accelerate: if the velocity v of a vehicle is lower than vmax and if the distance to the
next car ahead is larger than v + 1, the speed is advanced by one,  let v = v + 1
2. Slowing down (due to other cars): if a vehicle at site I sees the next vehicle at site I + j (with j < v), it reduces its speed to, let v = j - 1
3. Randomization: with probability p (0.10 out of 1.0), the velocity of each vehicle (if greater than zero) is decreased by one, let v = v - 1
4.  Car motion: each vehicle is advanced v sites.

Treat the road as a series of rectangles, some filled with cars, and some empty.
Leave enough space between rectangles so two cars are not touching each other.

Make the car rectangles large enough that you can easily see them (vertically and horizontally).
Randomly initialize the simulated road with cars and their simulated velocity v <= vmax
Try to create a traffic jam in the middle of the screen.  In other words, back to back cars in a jam.

The program should be written in a single HTML file, containing HTML, CSS, JavaScript, and graphics.
It should fit in a typical laptop browser without scroll bars.
The color scheme should have a gray background and the cars should have random soft colors.
There should be start, pause, and reset buttons.
If the user clicks on an empty cell, a car should be added.
Traffic should flow fro left to right,






