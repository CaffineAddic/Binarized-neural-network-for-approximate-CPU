# Binarized-neural-network-for-approximate-CPU
## This code is made for the project titled "Approximate CPU design and it's analysis using ML"
In this project we are proposing design of an approimate microprocessor CPU with approximate ALU (approx adders, multipliers etc.) and using it to process sensor data using the ability of machine learning algorithms which remain indrifferent to approximation added to the data. We are then processing the data using a pretrained shallow BNN with only 17 Binary neurons which is pretrained for the paricular data type.
In this code we are using Larq library to impliment the BNN and we are generating the random error in the code itself and we are comparing the testing accuracy with model trained with the original dataset here we are using the Banknote authenticaion dataset.
### Please note before running the code please install the following libraries tensorflow larq pandas numpy random matplotlib sklearn and well as the dataset and keep the program and the dataset in the same folder.
you can use 
##### pip install tensorflow larq pandas numpy random matplotlib sklearn 
to install the dependency in one go
