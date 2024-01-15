#Ground state energy of hard sphere Bose gas in Elliptical HO potential by VMC methods - (2020)
### A C++ utility and paper

## How to run the program
Uncomment whatever type of run in the Main- Scope you want and make sure the others are commented out.
Make whatever changes to the hyperparameters (None should be needed) that are needed in the function body.
Compile, using CMake and x64- Release (otherwise python will look in the wrong directory for the executable).

From here, you can either compile and run the executable (with command line args to overwrite the built- in arguments),
or execute via the functions in DataHandler.py

## File explanation
Python:
DataHandler.py - Used for all plotting 
dataModule.py  - Module for all datahandling associated with the output of the c++ code including plotting

C++ :
runtype.h - function declerations for the types of runs that are set up in the Main.cpp file
Benchmark.h - Timing Class used to benchmark the program

## Compiling
The program is compiled using cmake and the executable is left where it is. Make sure to compile as "Release", or the python code will look for the executable in the wrong folder.

