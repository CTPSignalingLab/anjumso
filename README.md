# anjumso
Annotated Jupyter Modelling Software

Welcome to **ANJUMSO** - Annotated Jupyter Modelling Software.

In order to run the code, please, install Anaconda 3.8: https://www.anaconda.com/products/individual

After the installation, download the given repository and unpack it on your PC. In the folder you will find the
following files:

1. ANJUMSO.ipynb - JuPyTer notebook, that includes model and auxiliary functions
2. Model Parameters.xlsx - Parameters of the model and model initial conditions that are stored as the Excel file.
You can edit it and this will result in the parameter change in the model. Each module of the model has its own
parameters and they are stored on the corresponding sheets of the Excel file
3. Exp_data.xlsx - ANJUMSO can read and display experimental data for the comparison with the modeling results

Excel files are to be stored in the same folder as the model.

The example model is the model of platelet collagen receptor GPVI and is based on the models from:
Martyanov *et. al.* The Biophys. J. 2020; Garzon Dasgupta *et. al.* Life 2020; Sveshnikova *et. al.* JTH 2016.
Model validation data were taken from: Dunster *et. al.* PLOS Comp. Biol. 2015; Poulter *et. al.* JTH 2017.

To run the model - execute all of the code cells. You can change the parameters of the model dynamically
by passing the model the name of the module, the name of the parameter and the range of the parameter variation.
You can also change the variables that are displayed in the plots by changing of the corresponding variable number.
The instructions for these are given in the corresponding code parts.

Parameter and variable description is given in the excel files.

The model is solved using Python Scipy solve_ivp method, that utilizes LSODA.

Enjoy!