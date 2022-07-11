## Heart-Disease-Prediction
<h3>Objective :</h3> 
This repository is a learning experience to:
<ul>
<li>apply fundamental concepts of Machine Learning.</li>
<li>Evaluate and interpret and justify our results and interpretation.</li>
</ul>

<h3>Problem Statement : </h3>
<h4>Given a heart disease dataset, we need to predict whether a person has the disease or not.</h4>

The analysis has been broadly divided into six sections. 
<ol>
<li>Importing Libraries and Reading the dataset</li>
<li>EDA</li>
<li>Splitting the Training and Testing data</li>
<li>Creating the model</li>
<li>Prediction</li>
<li>Accuracy and Confusion Matrix</li>
</ol>

<b><ins>Section 1:</ins> Importing Libraries and Reading the dataset<b><br>
In this section, I am importing all the necessary python libraries like numpy, pandas, matplotlib, sklearn, etc. Along with this, I am reading the dataset using read_csv method. 

<b><ins>Section 2:</ins> EDA(Exploratory Data Analysis)</b><br>
In this section, I am using the above imported libraries to understand the relation between different features in our dataset. I am using exploration techniques and visualization to get some insights from the data.

<b><ins>Section 3:</ins> Splitting the Training and Testing data</b><br>
Here I am splitting my dataset into two parts: training and testing dataset. Training DataSet will be given to the model for training and testing dataset will be used to test the model.

<b><ins>Section 4:</ins> Creating the model</b><br>
Here I am creating the model using sklearn library. While creating the model, I will be using the training dataset.

<b><ins>Section 5:</ins> Prediction</b>
In this section, the model is predicting the values of target column(Whether disease is there or not) that is 0 or 1.
0 -> no disease
1 -> disease 

<b><ins>Section 6:</ins> Accuracy and Confusion Matrix</b><br> 
Here, I am using sklearn methods to find the accuracy of my model. Accuracy of my model comes out to be <b>98.3</b>. 
  
<b>KNN Algorithm</b> ->
KNN stands for K Nearest Neighbors algorithm. It is supervised learning algorithm. K-NN algorithm assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories. K-NN algorithm can be used for Regression as well as for Classification but mostly it is used for the Classification problems.
