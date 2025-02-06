Data Science Project - Heart Disease Prediction using ML Algorithms

Overview:
- The aim is to predict if a person is likely to have heart disease based on certain health data.
- Predicting heart disease in advance can save patients time and effort compared to waiting for doctor appointments and multiple tests.

Why It's Important:
- Automating the heart disease prediction process can save both doctor and patient time.
- Early detection helps in timely treatment and improves outcomes.

Machine Learning Approach:
- Machine learning models can be trained to predict the likelihood of heart disease based on features like glucose levels, blood pressure, and others.
- These models use datasets to predict heart disease probability.

Data Used:
- Features include: blood pressure, chest pain type, cholesterol levels, age, and others.
- Dataset with 303 rows from Kaggle is used for the classification task.

Exploratory Data Analysis (EDA) Insights:
- Positive and negative correlations exist between different features (e.g., 'thalach' with 'slope' positively, 'age' with 'restecg' negatively).
- Some features show interesting relationships (e.g., higher cholesterol with age).

Visualizations:
- The dataset contains both numerical and categorical features.
- One-hot encoding is used to convert categorical data into numerical format.
- Correlation heatmaps and scatter plots provide insight into data trends.
- Most patients are aged 50-60 years, and there are outliers in cholesterol levels (ranging from 200-500).
- Some gender-related differences in heart disease prevalence.

Machine Learning Models Used:
- K Nearest Neighbors (KNN)
- Logistic Regression
- Naive Bayes
- Random Forest Classifier

Model Evaluation:
- Naive Bayes performed best based on F1 score, precision, recall, and accuracy for predicting heart disease.

Future Scope:
- More data from different sources can improve the prediction models.
- Additional features could help in refining the prediction process.
- The best model, Naive Bayes, can be deployed in real-time to assist doctors in diagnosing heart disease.

How to Use the Repository:
- Install Git to clone the repository.
- Use Gitbash to clone the repository from the provided link.
- Download the repository folder and open it in Anaconda.
- Open and run the .ipynb (Jupyter Notebook) files to execute the code.