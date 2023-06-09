# Simulation and Stochastic Models Group Project

## Project Information

### Project Title

Modelling the Phone Queueing System of a Real World Service

### Authors

John Taniguchi, Sharna Granwal, Leo Gaynor, Will Doherty, Duncan Bennie, Samuel Non

### Contact

Will Doherty (email: [dohertwill@myvuw.ac.nz](mailto:dohertwill@myvuw.ac.nz))

### Summary

We modelled the phone queueing system of a service who wished to remain anonymous.

### Project start date

23/03/2023

### Project state

Completed on 09/06/2023

### Information about computational platform

The data is stored in an Excel file. R was used to read this file and perform model fitting on the interarrival and service times. Python was used to simulate the queueing system.

## Instructions for Running the Code

To run the R code that fits statistical distributions to the observed interarrival and service times:

  1) Open R markdown file for model fitting (we used RStudio for this).
  2) Install packages when prompted.
  3) Read in the data (line 33). You will need to change the file name and address.
  4) Run the portion of the code you are interested in. Each section is clearly labelled within the file.

To run the python code that simulates the queueing system:

  1) Open Final Model Simulations.ipynb (we used Juypter notebook for this).
  2) Run the first two cells import the required packages and define a function that calculates confidence intervals.
  3) Run the two cells for the model you are interested in. The second cell for each model prints the results of the simulation. Note that for the simulation using empirical data, you will need to change the file address to read in the data.
