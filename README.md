# Fake Jobs Prediction

## Description
Fake job prediction notebook contains exploratory data analysis of fakejobs datasets and supervised-learning model comparisons for accracy, precision, recall, and F1 Score.

## Why it was created
The 2020 Pandemic saw an increase in online job applications, but some of such jobs were fake. We wanted to determine the best supervised learning models for labeling jobs as real or fake based on the job description words vector. 

## Pre requisites
Anaconda Python 3.0 or higher distribution
Jupyter Notebook 6.0 or higher
Required Python Packages

### Or

Google Colab online

## How to setup and use
After installing the python distribution with anaconda, add the anaconda program path to the environment variable. Next, open a command prompt or terminal and type "jupyter notebook". Navigate to the path of your local repo and open the source notebook. 

To install the packages, you may do it inside the notebook using ``` ! pip install <package name>``` or in your command prompt type ``` conda install <package name> ```.

### Or

You can open the notebook in Google Colab and install the packages internally via ``` ! pip install <package name>```.

## Results Summary
We trained classification models on TFIDF and Bag of Words vectorization of job descriptions with the job labels as the target vector. Then the models were applied on the validation and testing data set. 

Out of the 6 classifer models **KNN, Logistic Regression, MLP, hard ensemble voting, and soft ensemble voting**, the top 3 were picked. These 3 for TFIDF had [**% accuracy, %precision, %recall, %f1-score**] as follows Random Forest [99,99,99,99], Soft Voting [97,97,98,97], and Hard Voting [98,98,98,98].   

## Permissions
You may edit the cloned scripts, but you must give credit to Gaurav Shinde and Vasudha Jhasthi for using the files and code in this repository.

