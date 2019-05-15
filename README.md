# Master Folder for Computer Science Class
### Authors
#### Ding Yi Zhang
#### David Alexander
**Binary star ststem simulation, with possibility to simulate the N-Body problem**
We used Verlet's velocity method of numerical integration which can be found [here](https://www.compadre.org/PICUP/resources/Numerical-Integration/). The dt we used varied but was always below 1000. Acceleration was calculated using Newton's universal gravitation, and initial conditions were calculated using astrophysics equations, including Kepler's third law and derivations of Kepler's second law for velocity. 

When running the program, ensure that:
1. A correct file path has been set up for the data file
2. If you have added bodies, n should be equal to the number of bodies, and must be changed in the simulation *and* animation files
3. SkipSteps in the animation file is not zero

To change the simulation:
1. The skipSteps variable in speeds up and slows down the animation
2. If *focused* is given to animate_SEM as a command line arg, the animation will focus on Earth, and if not, it will focus on the Sun
3. To create your own system, please use the Verlet file by adding NewBody objects to the bodies[] array and changing n accordingly

Enjoy!
