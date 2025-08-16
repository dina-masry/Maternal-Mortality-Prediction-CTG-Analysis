# Maternal Mortality Prediction: CTG Analysis
## 🌟 Project Overview
This repository addresses the critical global challenge of maternal mortality by developing predictive models using Cardiotocogram (CTG) data. Maternal mortality remains a significant health concern, especially in low-resource settings, where most deaths are preventable. CTGs offer a cost-effective way to assess fetal health, and this project leverages machine learning to classify fetal health into 'Normal', 'Suspect', or 'Pathological' categories, aiming to contribute to earlier intervention and improved outcomes.

The project explores both Artificial Neural Networks (ANN) and classical Machine Learning (ML) models to identify the most effective approach for this vital classification task.

## ✨ Features

- Data Preparation: Comprehensive loading and initial preparation of the CTG dataset.

- Train-Test Split: Splitting the data into training and testing sets (75:25 ratio) for robust model evaluation.

- ANN Baseline Model: Implementation and training of a baseline Artificial Neural Network with default configurations.

- Classical ML Model: Training of a traditional machine learning model for comparative analysis.

- Model Performance Assessment: Evaluation of both ANN and classical ML models to understand their strengths and differences in predicting fetal health.


## 🛠️ Key Technologies & Libraries

- Python: The primary programming language for data science and machine learning.

- Pandas & NumPy: For efficient data manipulation and numerical operations.

- Scikit-learn: For data splitting, classical machine learning algorithms, and evaluation metrics.

- TensorFlow / Keras: For building, training, and evaluating Artificial Neural Networks.

- Matplotlib : For data visualization and presenting model results.

## 🗃️ Data Description
The dataset consists of 2126 records extracted from Cardiotocogram (CTG) examinations. Each record contains various features related to fetal heart rate (FHR), uterine contractions, and fetal movements. These records were expertly classified by three obstetricians into three distinct fetal health classes:

- Normal

- Suspect

- Pathological

The dataset provides a rich basis for developing a predictive model that can aid medical professionals.

## 🧠 Methodology

- Data Loading: The CTG dataset is loaded into a pandas DataFrame.

- Data Splitting: The dataset is split into training and testing sets using a 75:25 ratio, ensuring a fair evaluation of model performance on unseen data.

- Artificial Neural Network (ANN) Baseline: An ANN model is constructed and trained using all available features and default configurations. This serves as a foundational deep learning approach.

- Classical Machine Learning Model: A chosen classical machine learning model (Logistic Regression) is trained on the same preprocessed data.

- Model Assessment & Comparison: The performance of both the ANN and the classical ML model is assessed using appropriate classification metrics (e.g., accuracy, precision, recall, F1-score). A direct comparison highlights the strengths and weaknesses of each approach for this specific problem.

📊 Results

This project aims to deliver models capable of accurately classifying fetal health from CTG data. The results section within the Jupyter Notebook will detail:
The performance metrics (accuracy, precision, recall, F1-score) for both the ANN baseline model and the selected classical ML model.

<img width="732" height="360" alt="loss" src="https://github.com/user-attachments/assets/1c424722-f54f-4757-b0b4-57e7852ce69f" /> 
This is the loss in nueral network algorithm
<img width="627" height="537" alt="nueral-matrix" src="https://github.com/user-attachments/assets/a4a6e73f-20c7-400a-827b-0465869bf884" />
Confusion matrix of nueral network on unseen data.
 you can find all results of all models within the notebook.


## 🤝 Contributing
Contributions are welcome! If you have suggestions for improvements, new features, or find any issues, please feel free to open a pull request or submit an issue.
