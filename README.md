To maximize the utilization of satellite resources and fully optimize as many flexible payloads as possible, this work implements an optimization method for jointly optimizing the frequency band, beam, and power multi-dimensional resources, where the flexibility of the beam includes state, position, and beamwidth.

# SOFTWARE REQUIREMENTS

- MATLAB 2019b or newer version is required. The following MATLAB toolboxes are required:
	- Global Optimization toolbox
	- Parallel Computing Toolbox
	- Optimization Toolbox
	- Statistics and Machine Learning Toolbox

- Additionally, two external packages are also required, MOSEK and CVX: 

	- MOSEK ApS is a software for nonlinear convex optimization. The software requires a user license which can be obtained free of charge for researchers, students or other academic members. More information about the license can be found at https://www.mosek.com/products/academic-licenses/.  MOSEK is employed through CVX ( that is detailed below). It should be reminded to follow the steps in order as described in the guide. In particular,  Step 4  is required to detect the MOSEK licence with CVX, after placing the MOSEK license in the correct folder. 

	- CVX is a powerful and efficient solver for convex optimization problems. A user guide and installation steps can be found in http://web.cvxr.com/cvx/doc/mosek.html
       	  to install both MOSEK and CVX in MATLAB.

refer to https://github.com/tomramzp/Resource



System_Simulations19.m main program
PlotResults_CR4.m          results plotting
