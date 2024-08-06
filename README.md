
# IRIS FLOWER CLASSIFICATION

### A. Description:

This project focuses on classifying iris flowers into three species (Iris-setosa, Iris-versicolor, and Iris-virginica) based on their sepal and petal measurements. The project involves data preprocessing, exploratory data analysis (EDA), and building a machine learning model to accurately predict the species of iris flowers.

### B. Questions Addressed:

    1. How accurately can we classify iris flowers into their respective species based on sepal and petal measurements?
    2. What are the important features that influence the classification?
    3. How does the model perform on the testing data?


### C. Dataset Description:
The Iris dataset contains 150 samples, each with four features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
The target variable is the species of the iris flower, which can be one of three categories:
- Iris-setosa
- Iris-versicolor
- Iris-virginica
We will be using the following dataset:
- Iris.csv


### D. Tasks Performed:

### 1. Data Preprocessing
- Loaded the dataset into a pandas DataFrame.
- Checked for missing values and handled any anomalies.
- Encoded the categorical target variable (species) using Label Encoding.
- Split the dataset into training and testing sets.

### 2. Exploratory Data Analysis (EDA)
- Displayed the first few rows, shape, and information about the dataset.
- Generated a statistical summary of the dataset.
- Visualized the data using pair plots to explore relationships between features and the target variable.

### 3. Model Building
- Implemented a K-Nearest Neighbors (KNN) classifier for predicting the species of iris flowers.
- Trained the model using the training dataset.
- Made predictions on the testing dataset.

### 4. Model Evaluation
- Evaluated the model's performance using metrics such as accuracy, precision, recall, and F1-score.
- Generated a classification report and confusion matrix to summarize the model's performance.
- Calculated the accuracy score of the model.


### E. Results:
- The KNN classifier achieved an accuracy score of 1.0 (100%) on the testing dataset, demonstrating its effectiveness in classifying iris flowers. The detailed classification report and confusion matrix are provided below.
