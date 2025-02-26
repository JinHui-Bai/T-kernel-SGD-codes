  The different files are labeled as the code of different parts of the manuscript, and when testing the program, 
the two columns after the iteration number are the test error of the last step and the average estimator, respectively. 
In addition, to conduct experiments with other datasets in T-kernel SGD, it is recommended to use the code in Subection 
5.3. Different data distribution and noise can be set by adjusting the fuction "construct-data", as well as the 
expression after function s return to set different optimal prediction functions. However, it is important to set X to 
be a spherical unit of type list and the number of elements should be the same as d in the class. Other formats may 
cause errors in the model.
