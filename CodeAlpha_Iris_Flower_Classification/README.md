# CodeAlpha_Iris-Flower-Classification

**Overview**
This project is developed as part of the **CodeAlpha Data Science Internship**.  
The goal is to predict the species of an iris flower: **Setosa**, **Versicolor**, or **Virginica** using a Machine Learning model. based on it's : sepal length, sepal width, petal length, petal width from given dataset


**Tools & Libraries Used**
- Python
- Pandas
- Scikit-learn
- RandomForestClassifier


**Dataset**
 1. Source: [Kaggle - Iris Flower Dataset](https://www.kaggle.com/datasets/saurabh00007/iriscsv)
 2. Description: The dataset contains 150 samples of Iris flowers with 4 numeric features and 1 categorical label (species).
 3. Feature Description : 

     -SepalLengthCm-  Sepal length in cm 
     -SepalWidthCm- Sepal width in cm 
     -PetalLengthCm- Petal length in cm 
     -PetalWidthCm- Petal width in cm 
     -Species- Type of Iris flower (Setosa, Versicolor, Virginica) 

**Project Workflow:**

   1. Data Loading & Exploration- Loaded the Iris dataset and explored its structure
   2. Data Preprocessing- Encoded species labels into numeric form. (0,1,2)
   3. Train-Test Split- Divided dataset into 80% training and 20% testing sets.
   4. Model Building- Trained a RandomForestClassifier model on the training data.
   5. Evaluation- Evaluated accuracy, confusion matrix, and classification report.
   6. Prediction- Tested model with a new unseen flower sample.


**Results:**
- **Accuracy:** ~99%
- The model effectively classifies all three species of Iris flowers with near-perfect performance.


**Learnings:**
  1. Basics of data preprocessing and encoding
  2. Splitting data into training and testing sets
  3. Training and evaluating classification models
  4. Understanding classification metrics


# Internship Information

- Internship Domain: Data Science
- Organization: CodeAlpha
- Task Name: Task 1 — Iris Flower Classification  


# Acknowledgment
Grateful to **CodeAlpha** for this amazing learning opportunity to apply and strengthen my machine learning skills.

