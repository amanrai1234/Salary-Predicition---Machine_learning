# Data-scientists-salary-predicition
In this projected I predicted the salary of the dataset using their salary dataset. In this I had to clean, encode and split the data and train it for regression.




## Dataset: 

The dataset contains the salary of people (data scientists) across united states.
Visualization and reading of dataset:

I have used pandas to read and display first five elements (dataframe.head()) as 
It’s easier to visualization compared to the NumPy. Then to get the information
of the dataset contents, I have used pandas.info(), we can use this but we should 
always check the datset manually also. But sometimes the dataset might be too 
big to open, in that case we can use these kinds of techniques to do the 
computation.

## Finding Correlations:

Here I have used the .Corr() function from the pandas that gives the correlation 
of the elements in the dataset as the output. Here we can check the correlation of 
the dataset on the single element or on the entire dataset. In the Notebook, I 
have also plotted this using seaborn library. Here to plot the normal distribution 
of the dataset I have used the histograms and plotted the distribution of all the 
features in a single block.

## Data Cleaning:

This is the most challenging part of the dataset and here I have again used
pandas to clean the data, I have searched for special characters also so that I 
could remove them and make the data less redundant. Here I removed the 
columns(features) that are having text(sentence like) because categorical 
features with only one or two unique words can be one-hot encoded. 

Here we have to note that the values that I have chosen to do cleaning are the 
ones which had a good positive or negative correlation with the target variables.
If there is close to zero correlation between features and the target values then it 
is not a wise choice to keep the feature in the training set.

## Data Division:

I have divided the data into numerical and categorical features, I did this
because we need to scale the numerical values and one hot encode the 
categorical features. After the division of data and doing One hot encoding
+Scaling(non-categorical variables), I have concatenated the dataset again and 
split it in training and testing sets.

## Linear Regression:

Now, the data cleaning part is completed, this is the time where we have to do 
linear regression. I have used Sckit-learn library of linear Regression to do this 
task.
After fitting the dataset on the data and target variable I perform the below three
tasks using the scikit learn:

1] mean square error

2] mean square absolute error

3] Root mean Square Error


















# How to run this file

TO RUN THE NOTEBOOKS JUST UPLOAD THE DATASET IN THE JUPYTER NOTEBOOK AND YOU CAN RUN IT.





















