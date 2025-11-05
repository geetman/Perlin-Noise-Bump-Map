# Perlin-Noise-Bump-Map
A Bump Map Generation using Perlin Noise for Randomness 
### Part 1: Noise Generation
Random noise is generated. This is then converted into a height map.
### Part 2: Pixel measurements
The height map is then converted into a pixel grid. This pixel grid takes the distance from the mouse pointer and calculates a ***Lit*** value.
### Part 3: Rendering
The Lit valuse is then run through the renderer. The renderer calculates the reletive Lit value (Lit value based on the lit values and height values of other pixels) to create shadows. This is then printed onto the screen.
## NOW RUNS ON 240 FPS!!!!
