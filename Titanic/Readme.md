# Titanic Survival Prediction using Logistic Regression

## Overview
This project is a Machine Learning classification model built using **Logistic Regression** to predict whether a passenger survived the Titanic disaster or not.

The project includes:
- Data preprocessing
- Handling missing values
- Feature encoding
- Model training
- Model evaluation using accuracy, confusion matrix, and classification report

---

## Dataset
The dataset used in this project is the famous **Titanic Dataset**.

### Files Included
- `titanic.csv` → Dataset used for training and testing
- `titaniclogistic.ipynb` → Jupyter Notebook containing the complete implementation

---

## Technologies & Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Algorithm
- Logistic Regression

---

## Data Preprocessing Steps

The following preprocessing steps were performed:

### 1. Data Cleaning
- Checked missing values
- Filled missing values in the `Age` column using median values
- Removed unnecessary columns

### 2. Feature Engineering
- Converted categorical values into numerical format using One-Hot Encoding

### 3. Train-Test Split
- Split dataset into training and testing data using an 80:20 ratio

---

## Model Evaluation
The model performance was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## Project Workflow
1. Load Dataset  
2. Explore Data  
3. Handle Missing Values  
4. Encode Categorical Features  
5. Split Dataset  
6. Train Logistic Regression Model  
7. Predict Results  
8. Evaluate Performance  

---

## How to Run the Project

### Step 1: Clone the Repository
```bash
git clone <your-repository-link>
```

### Step 2: Install Required Libraries
```bash
pip install pandas numpy scikit-learn jupyter
```

### Step 3: Run the Notebook
```bash
jupyter notebook
```

Then open:
```bash
titaniclogistic.ipynb
```

---

## Future Improvements
- Add data visualization using Matplotlib and Seaborn
- Improve model accuracy using advanced algorithms
- Perform hyperparameter tuning
- Deploy the model using Flask or Streamlit

---

## Author
**Krish Garg**  
Machine Learning & Data Science Enthusiast
