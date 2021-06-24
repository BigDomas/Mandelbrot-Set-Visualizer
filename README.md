# Mandelbrot-Set-Visualizer
Application built in Processing 3 that renders the Mandelbrot Set.

Load both files into Processing 3. 

================= MOVEMENT =================

Click any point on the window to render a new image centered around that point.
Scroll up or down to change the zoom level, then click to render a new image zoomed-in to that point.

================= COLORING =================

When each pixel is iterated, it will return a double: -1 if the point is calculated to be in the set, or a number >= 0 (in the area near the origin) that approaches infinity as the point gets closer to the edge of the set.
A few coloring functions are given in the colorAlgorithm method
