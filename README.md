# Eight-Ball-Pool-Physics-Simulator
The Eight-Ball Pool Physics Simulator is a program written in MATLAB which accurately simulates the physics of pool shots. The program accounts for elasticity of collisions, ball to ball friction, ball to table friction, ball to wall friction along with accurate directions. The final positions of all balls are accurate up to +- 1.0 units. 
The general architecture of the program:
1)	Initial positions and velocities of all balls are given
2)	All ball positions are updated according to their velocities and frictions over a small-time increment (0.001s used)
3)	Program checks for any collision
4)	If collision detected, program updates velocity vectors
5)	Cycle repeats until all ball speeds are zero
6)	Animation is generated using positions stored in arrays
To run program, set time increment, coefficients of restitution, coefficients of friction, initial ball positions and initial velocities. 
