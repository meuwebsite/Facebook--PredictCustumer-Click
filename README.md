### Machine Learning - Logistic Regression

# Facebook--PredictCustumer-Click

![fb](images/fb9.png)


# Background

Running a targetted marketing ads on facebook. The company wants to anaylze customer behaviour by predicting which customer clicks on the advertisement. Customer data is as follows:

Inputs:

* Name
* e-mail
* Country
* Time on Facebook
* Estimated Salary (derived from other parameters)


# Goals

* Split the data in Train and Test
* Train and Test the model in the data set
* Visualize
* Predict Click on the ad


# How to run 

Open Google Colab https://colab.research.google.com/
* File
* Upload Notebook
* Run the Cells


# Proccess

Import the data set and visualize the data

* With Scatter plot
#  
![fb](images/fb1.png)

* With Box plot
#  
![fb](images/fb2.png)

* With Histogram
#  
![fb](images/fb4.png)

Transforming the data and Executing a training Test 
#  
![fb](images/fb5.png)

With Confusion Matrix, checking on the accuracy
#  
![fb](images/fb6.png)

ploting the boundary using the trained classifier
* Run the classifier to predict the outcome on all pixels with resolution of 0.01
* Colouring the pixels with 0 or 1
* If classified as 0 it will be magenta, and if it is classified as 1 it will be shown in blue 
#  
![fb](images/fb7.png)

Ploting all the actual training points
#  
![fb](images/fb8.png)

Visualising the Training set results for Tran and Test
#  
![fb](images/fb9.png)
