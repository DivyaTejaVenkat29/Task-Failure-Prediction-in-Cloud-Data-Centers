# Task-Failure-Prediction-in-Cloud-Data-Centers

## Objective:
The objective of this project is to enhance the accuracy of predicting task and job failures in cloud data centers by analyzing past system message logs. This project aims to build on previous machine learning and deep learning-based methods to improve failure prediction models. The ultimate goal is to accurately predict whether tasks and jobs will fail or complete, thereby improving the reliability and availability of cloud services.

## Implementation:
 ### Package Importation:
o	Imported libraries: Numpy, Pandas, Matplotlib, Seaborn, sklearn, TensorFlow, Keras, Plotly.
 ### Dataset Exploration:
o	Loaded and explored the dataset to understand its structure and content.
 ### Data Processing:
o	Cleaned and preprocessed data, encoded categorical variables, and normalized numerical features.
 ### Data Visualization:
o	Used Seaborn and Matplotlib to visualize data distributions and patterns.
 ### Data Splitting:
o	Split the dataset into training and testing sets.
 ### Handling Imbalance with SMOTE:
o	Applied SMOTE to address class imbalance in the training dataset.
 ### Model Building:
o	Developed CNN, LSTM, Bi-LSTM, and Bagging Classifier models.
 ### Model Training:
o	Trained models, tuning hyperparameters and using techniques to prevent overfitting.
 ### Model Evaluation:
o	Evaluated models using accuracy, precision, recall, and F1-score.
 ### Final Model Selection:
o	Chose Bagging Classifier for its superior performance.
 ### Result Interpretation:
o	Analyzed results to gain insights into factors causing task and job failures.
