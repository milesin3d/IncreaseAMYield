# Increase Additive Manufacturing Yield
3D Printing + Machine Learning = Increase Part Yield

## Background Information
This experiment includes actual (not simulated) data from a metal 3D printing machine and a thermal imaging sensor. 
10 samples were built and tested. 
From many experiences (both successes and failures), a broad understanding of physics, and a grasp of the internals of a 3D printer, there are many theories on how the "digital thread" is constructed (how one set of data affects another). 
This large unknown thread of data is problematic for companies looking to create a bussiness model around machines that have a high potential, but come with much volatility, uncertainty, and cost.

## Goals
### Business
Increase the return on investment (ROI) of the machine by increasing the yield of the 3D printed components.

### Data
1) Develop a connection between the three datasets.
2) With this understanding, control the Print Parameters, and create a boundary for the Melt Pool Metrics, so that porosity is as close to 0% as possible.

## Datasets
### Print Parameters
Inputs into the printer prior to the building process.

### Melt Pool Metrics
A thermal imaging sensor captures images of the melting process, specifically the melt pool.

### Material Properties
The material property measured was porosity or (1 - Density).

## Machine Learning
### Linear Regression
The act of fitting a line to two or more variables to show a linear relationship between them.

### Random Forest
Many decision trees are used to separate the data into groups to determine their outcomes.