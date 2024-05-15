# Credit Risk Modeling using Deep Learning

This project aims to develop a Credit Risk Modeling system using deep learning techniques to predict the creditworthiness of loan applicants. The model utilizes neural networks to analyze various features of loan applicants and predict whether they are likely to default on their loans.

## Problem Statement
Lending institutions face the challenge of assessing the credit risk associated with loan applicants. Traditional methods of credit risk assessment may not capture the complexities and nuances of borrower profiles. This project seeks to leverage deep learning algorithms to improve the accuracy and efficiency of credit risk assessment.

## Dataset
The project utilizes a publicly available dataset from [loan_data_2007_2014]([link_to_dataset](https://drive.google.com/drive/folders/1mzS2wgML6A-FRg07iGreWLFM0vcWamme?usp=sharing)). The dataset contains a wide range of features.
## Approach
1. **Data Understanding**: Gain a comprehensive understanding of the dataset such as understanding data structures, detect the missing value, etc.
2. **Data Preprocessing**: The dataset undergoes preprocessing steps such as handling missing values, encoding categorical variables, normalizes huge numeric value, etc.
3. **Exploratory Data Analysis**: understand the structure, patterns and relationships in the data we have before carrying out further analysis or building models.
4. **Model Building**: A deep learning model is constructed using TensorFlow/Keras, consisting of multiple dense layers with activation functions like ReLU and Sigmoid.
5. **Training**: The preprocessed dataset that has been split, feeded to the model for training.
6. **Evaluation**: The model's performance is evaluated using metrics such as accuracy, confusion matrix, precision, recall and F1-score.

## Requirements
- Python 3.10
- TensorFlow
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn
- Shutil

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/albanisyahrill/Credit-risk-modeling.git
