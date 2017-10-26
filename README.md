# Iris Data Set

## Emerging Technologies - Problem Sheet 3

This repository contains solutions to a series of problems relating to the famous *Iris* data set. The data set
contains samples of 3 different types of *Iris* plant.

- Setosa
- Versicolor
- Virginica

The data samples contain 50 samples for each of the different types of species. Each sample is composed of 4 distinct
features of the plants including:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The original Problem Set can be found [HERE!](https://emerging-technologies.github.io/problems/jupyter.html)

All of the Python code relating to the Problem Set linked above can be found in the juptyer notebook housed in this
repository, which also contains some markdown cells relevant to the tasks being carried out.

## Problem Set

### 1. Get and load the data
Search online for Fisher’s iris data set, find a copy of the data, download it and save it to your repository. If it is
not in CSV format, use whatever means (Excel, notepad++, visual studio code, python) to convert it to CSV and save the
CSV version to your repository also. Open your Jupyter notebook for this problem sheet, creating a new one if needed,
and load the CSV file into a numpy array.

### 2. Write a note about the data set
In a markdown cell at the start of your notebook, write a short description of the iris data set, complete with
references.

### 3. Create a simple plot
The dataset contains five variables: sepal length, sepal width, petal length, petal width, and species. Use pyplot to
create a scatter plot of sepal length on the x-axis versus sepal width on the y-axis. Add axis labels and a title to the
plot.

### 4. Create a more complex plot
Re-create the above plot, but this time plot the setosa data points in red, the versicolor data point in green, and the
virginica data points in blue. Setosa, versicolor, and virginica are the three possible values of the species variable.
Add a legend to the plot showing which species is in which colour.

### 5. Use Seaborn
Use the [seaborn](https://seaborn.pydata.org/) library to create a scatterplot matrix of all five variables.

### 6. Fit a line
Fit a straight line to the variables petal length and petal width for the whole data set. Plot the data points in a
scatter plot with the best fit line shown.

### 7. Calculate the R-Squared value
Calculate the R-squared value for your line above.

### 8. Fit another line
Use numpy to select only the data points where species is setosa. Fit a straight line to the variables petal length and
petal width. Plot the data points in a scatter plot with the best fit line shown.

### 9. Calculate the R-Squared value
Calculate the R-squared value for your line above.

### 10. Use Gradient Descent
Use gradient descent to approximate the best fit line for the petal length and petal width setosa values. Compare the
outputs to your calculations above.




