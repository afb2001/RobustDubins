# Robust Dubins C++ Library
Last Modified: 3-July-2019

<p align="center"> 
<img src="http://arturwolek.com/img/RobustDubins.png">
</p>

## Dependencies:
- Ubuntu 16.04
- cmake
- (Optional) Octave/MATLAB
  for generating .m files for plotting

## Build instructions:
- Run `./build.sh` to create
  a) a library in: `./lib`
  b) executables in: `./bin`

## Usage instructions:
- Either use the library in your own code, or the DubinsSolver command line program with arguments:
`DubinsSolver x0 y0 h0 x1 y1 h1 R solnFile`
- See test programs for examples of how to incorporate into your own code
- clean.sh removes all compiled files, build files, and temporary files 

## References:

1. Tang, G., Wang, Z., & Williams, A. L. (1998). On the construction of an optimal feedback control law for the shortest path problem for the Dubins car-like robot. In Proceedings of the 30th Southeastern Symposium on Systems Theory (pp. 280–284). 
https://doi.org/10.1109/SSST.1998.660075

2. Wolek, A., & Woolsey, C. (2015). Feasible Dubins Paths in Presence of Unknown, Unsteady Velocity Disturbances. Journal of Guidance, Control, and Dynamics, 38(4), 782–787. 
https://doi.org/10.2514/1.G000629

