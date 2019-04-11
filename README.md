

Animated dots that become transparent on collision.

Collision detection algorithm:

In the draw function,

1) For each circle, collisions with 40 other circles are detected when the cartesian distance between them is less than the sum of their Radii.
2) The "opacity" of each of the colliding circle is set of 0.5
2) A simple counter is incremented when the current circle is colliding with any other circle.

Updating the current circle:
4) If the value of the counter is greater than 0, then the opacity of the current circle is set to 0.5
5) Otherwise, the value of the current circle is set to 1
