

## K-Nearest Neighbors (KNN) Project

### Overview

This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm using Python and the Scikit-learn library. The goal is to classify data points by analyzing the closest neighboring data samples.

### Dataset

The dataset used in this project is KNN_Project_Data, which includes several features that help in predicting the target class.

### Project Workflow

#### 1. Importing Libraries

The project relies on the following libraries:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

#### 2. Exploratory Data Analysis (EDA)

* Preview the dataset using head()
* Explore relationships between variables using pairplot

#### 3. Data Preprocessing

* Split the data into features (X) and target variable (y)
* Normalize the data using StandardScaler to improve model performance

#### 4. Splitting the Data

The dataset is divided into training and testing sets to assess how well the model performs on unseen data.

#### 5. Building the Model

The KNN model is created using:

* KNeighborsClassifier

#### 6. Evaluating the Model

Model performance is measured using:

* Confusion Matrix
* Classification Report

#### 7. Selecting the Optimal K Value

* Apply the Elbow Method to determine the most suitable K value
* Plot the error rate against different values of K


### Results

The model shows better performance after selecting the optimal K value based on the error rate analysis.

### How to Run the Project

1. Install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn

2. Launch Jupyter Notebook:

jupyter notebook

3. Open the file:

Lab8.ipynb

### Notes

* Feature scaling plays a critical role in improving KNN accuracy
* Choosing the right value of K has a strong impact on the model results
