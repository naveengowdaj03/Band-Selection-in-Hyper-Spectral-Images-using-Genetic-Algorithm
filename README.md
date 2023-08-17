# Testing the project
To test the project, open the command prompt and drag the "interface" application from the folder to the command prompt to run it.
When the application opens, select the Hyperspectral Image Data File and the Target File To Train from the folder "Dataset" as xx_corrected.mat and xx_gt.mat respectively.
There are two sets of images present in the dataset, i.e., "xx" in the file name can be Salinas or Indian_pines.
The user may enter the number of bands they wish to select, the number of indivuals to initialize and the number of gereations to be produced before stopping the search.
We tested the program on Indian_pines dataset using the parameters:
no. of bands to select = 13
no. of individuals to initialize = 21
no. of generations to before stopping = 5
and obtained a classification accuracy of 99.78%.

# GUI
# interface.exe
This file was generated using pyinstaller. Source: https://www.geeksforgeeks.org/convert-python-script-to-exe-file/

# Code
# genetic_algo.py
This file contains the code and relevant functions for the implementation of a genetic algorithm for band selection in hyperspectral images.

# interface.py
This file contains the code for the GUI to give files and parameters as input and run the genetic algorithm and show the selected bands and the accuracy obtained by them.