40031990

Raytracer Notes:

Uses Bounding Boxes around all objects to check if a ray may or may not intersect specific geometry. At the beginning of the run() function,
all geometry is sorted in a vector by its minimum Z value, to determine the closest object to the camera.

When using global illumination with area light, the program assumes a 5x5 sample grid for the area light

Has a multithreaded solution in the code, but since the Lab computers do not allow multithreading this section has been commented out