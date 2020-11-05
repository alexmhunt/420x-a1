## CS/IMGD 420x: Assignment 1

[Video (on Youtube)](https://youtu.be/igcMmIat9TU)

For this assignment, I made a ~1 minute long animation of a dancing, rounded cube using The Force. Aesthetically, my main inspiration was music: as I was experimenting with The Force and shaping functions, I was listening to Perturbator, a synthwave musician. His song [Miami Disco](https://youtu.be/xAM6mG6BWjw) from the Hotline Miami OST inspired me to go with a Hotline Miami, 1980s-esque color scheme full of bright blues, purples, and neon pinks. My vision was to have a single square in the center that seems to dance to the beat, expanding, contracting, and emitting waves of color. That way, I could stick to simple shapes while still being able to play with color and animation. 

Technically, I found myself drawn to the idea of distance mapping, as it allowed me to create multiple outlines of a single shape with a hollow center. I started out with a hollow square made using a simple distance map and smoothstep(), then attached the square’s bounds to time to allow the shape to expand and contract with the passage of time. I also created a distance map with several outlines for the animation’s second stage, and then used rotate() to map the canvas’s rotated coordinates to the amount of red in the render. This resulted in a pulsing square in the center that emitted spirals of blue and pink, which I was quite happy with.

![Example Render](https://github.com/alexmhunt/420x-a1/blob/gh-pages/the_force_2020_10_5_15_12_39.png)
