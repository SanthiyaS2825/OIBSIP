# Iris Flower Classification

## About the Project
This project is part of my Oasis Infobyte Data Science Internship.

The aim of this project is to classify iris flowers into three species using machine learning.

## Dataset
I used the Iris dataset available in Scikit-learn.

The dataset contains 150 flower samples and 4 features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The three species are Setosa, Versicolor, and Virginica.

## Data Analysis
- Checked the dataset for missing values.
- Viewed the dataset summary.
- Created a species count plot.
- Used a pairplot to compare flower measurements.
- Created a box plot for petal length.

## Machine Learning Models
I trained two classification models:
1. Logistic Regression
2. Decision Tree Classifier

The dataset was divided into 80% training data and 20% testing data.

## Results
- Logistic Regression Accuracy: 100%
- Decision Tree Accuracy: 100%

Both models correctly classified all 30 test samples in this experiment.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Conclusion
This project helped me learn the basic steps of data analysis and machine learning classification using Python.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Task 2: Unemployment Analysis with Python

### About the Project
This project explores unemployment data in India using Python. I used Pandas to clean and analyse the data and Matplotlib and Seaborn to create visualisations.

### Work Done
- Loaded and cleaned the unemployment dataset.
- Checked missing values and summary statistics.
- Compared average unemployment rates across states.
- Visualised monthly unemployment trends.
- Compared unemployment rates before and during the COVID-19 period.
- Created a correlation heatmap for selected numerical columns.
- Compared monthly unemployment rates in Tamil Nadu, Kerala and Karnataka.

### Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Conclusion
This project helped me practise data cleaning, exploratory data analysis and visualisation using Python. It also helped me explore changes in unemployment rates across different states and over time.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------



## Task 3: Car Price Prediction

### Project Overview
This project focuses on predicting the selling price of used cars using machine learning techniques. The dataset contains information about cars, including manufacturing year, present price, kilometres driven, fuel type, seller type, transmission, and previous owners.

### Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

### Work Done
- Loaded and explored the used car dataset.
- Checked missing values and removed duplicate records.
- Performed data cleaning and feature engineering.
- Created visualizations to understand car prices and their relationships with different features.
- Encoded categorical variables for machine learning.
- Split the dataset into training and testing sets.
- Trained Linear Regression and Random Forest Regressor models.
- Evaluated model performance using MAE, RMSE, and R² score.
- Analysed feature importance using the Random Forest model.

### Files
- `Car_Price_Prediction.ipynb` – Notebook containing the code and analysis.
- `car data.csv` – Dataset used for the project.

### Conclusion
This project provided practical experience in data preprocessing, exploratory data analysis, feature engineering, machine learning model training, and model evaluation for used car price prediction.

------------------------------------------------------------------------------------------------


## Task 4: Email Spam Detection with Machine Learning

### Project Description
This project uses machine learning to classify text messages as spam or ham (normal messages). The SMS Spam Collection dataset was used to train and evaluate the models.

### Tools and Technologies
- Python
- Pandas
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn

### Steps Performed
- Loaded and explored the SMS Spam Collection dataset.
- Checked missing values and the distribution of spam and normal messages.
- Preprocessed text by converting it to lowercase and removing punctuation and common stopwords.
- Used TF-IDF to convert text messages into numerical features.
- Split the dataset into training and testing sets.
- Trained Multinomial Naive Bayes and Logistic Regression models.
- Evaluated the models using accuracy, precision, recall, F1-score, and confusion matrices.

### Model Results

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Multinomial Naive Bayes | 97.31% | 99.17% | 80.54% | 88.89% |
| Logistic Regression | 96.50% | 100% | 73.83% | 84.94% |

### Conclusion
Multinomial Naive Bayes performed better overall on the test dataset, with 97.31% accuracy and 80.54% recall. This project helped me understand text preprocessing, TF-IDF feature extraction, machine learning classification, and model evaluation.


