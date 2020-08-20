# Breast-Cancer-Detection-using-Random-Forest-Classification-
Breast Cancer Detection using Random Forest Classification:

Workflow: 
1.	Firstly, the dataset was imported as usual (downloaded the dataset from Kaggle). There were 569 rows and 33 columns i.e. 32 Independent variables(features) and 1 Dependent variable. It can be seen that there one column named ‘Unnamed: 32’ that contains NaN values.
2.	The dataset is then checked for any further abnormalities and there was none.
3.	Next step is to split the dataset into Dependent (‘diagnosis’ column) and Independent variables.
4.	As the ‘diagnosis’ column contains Categorical Data, Label Encoding is used to make them 1 and 0. It converts M to 1 and B to 0.
5.	Then the dataset is split into Training and Test set with 80:20 ratio.
6.	Now, as it can be seen that, the features (Independent Variables) have values with various types of ranges. To normalize the data, Feature Scaling (StandardScaler) is applied. Then fit_transform method is applied to training data set and only transform method to test dataset.
7.	Now is the time to implement the Random Forest Classifier and fit the training sets.
8.	Next, it’s time to predict and test set and comparing results.
9.	Confusion Matrix is created to check the false positive and false negative predictions and also Accuracy is calculated.
10.	For this classification 97.4 percent accuracy is achieved.    
