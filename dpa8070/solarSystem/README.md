# Digital Production Arts
#### DPA 6830 Digital Scultpting in Z Brush
#### By: Benjamin B. Warner

[Back to the main page](https://benwarnerdigitalarts.github.io/3Dworks/)

## Project 2: Solar System Animation
### Date: Spetember 2nd, 2020

### Objective:
Construct a solar system out of basic shapes and animate orbits with moons.

### Solution:
Arranging the spheres and assigning colors was simple enough, but the real challenge came in creating believable orbits and recording the resulting animation.

Obviously, realistic orbits were unreasonable to implement (Earth would complete about 165 rotations before Neptune could do 1), so the next best thing is to rank the orbits very linearly.  This menas that Mercury completes 9 rotations when Venus completes 8 and so on until... Neptune completes 2. As if there was a 9th planet at some point.  Strange.

Moons were determined to orbit each planet in a very similar way, carefully avoiding placing any in the same exact orbit.  This was done by placing them in up to 4 distinct orbital layers and up to 5 distinct angular offets to allow for up to 20 moons on any planet with distinct orbits.

Finally, the orbits are all set in a way to create a perfectly looping gif.  This results in a periodic "alignment of the spheres", which is associated with some sort of supernatural phenomena.  Maybe it's Cthulhu?

![Solar System gif](https://benwarnerdigitalarts.github.io/3Dworks/dpa8070/movies/solarSystem.gif)
