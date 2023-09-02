About: ThermoSolver is a python program capable of simulating and computing key properties and values for various thermodynamic cycles, using either steam or a perfect gas as the working fluid. It is an ipynb file and hence needs Jupyter Notebook support to run.

Instructions for use:
-Enter the number of end states (variable: numberofstates) and fluid type (variable: fluid) in the Initialiser.ipynb file. As for now, the fluids supported are: Water, or any ideal perfect gas  (Air, Hydrogen, Nitrogen etc)
-Save the Initialiser.ipynb file. Now, in the plotinfo.ipynb file, Enter any information about properties, isentropic efficiencies or heat and work that may be required to solve the cycle. Examples are given as test cases in the repository.
-Save the plotinfo.ipynb file. Open the launch_program.ipynb file and run it. 
-The output, i.e the cycle, shall now open in form of a web page in your default browser.


DESCRIPTION OF EACH FILE (FOR CONTEXT):
-Functions.ipynb contains all the key functions that have been employed to write the main code that computes and displays the cycle. The user need not open and/ or edit this file.
-Initialiser.ipynb assigns default or initial values to important variables and lists. The user must use this file to assign the fluid that needs to be used in the cycle, and  also assign the number of states in the cycle.
-plotinfo.ipynb is a file that the user must use to pre-assign values to properties, heat/ work transfers etc that are needed to further solve the cycle. Basically, feeding in the information from the thermodynamics question.
-satlines.ipynb is a file that I had used to create the saturation lines for each of h-s, T-s and P-v plots. It is now kept mostly for backup purposes and the user need not open this file.
-main_gases.ipynb and main_steam.ipynb contain the main body of code written to solve gas cycles and steam cycles respectively. The user must NOT edit any information in these two files and does not need to open them.

(IMP)
-launch_program.ipynb is used to launch the program. After entering relevant info in the two files Initialiser.ipynb and plotinfo.ipynb, the user must run this file to launch the app.
