#  Titanic Dataset – Data Cleaning & Preprocessing
# Objective
The goal of this project is to clean and preprocess the Titanic dataset for machine learning purposes. This includes handling missing values, encoding categorical variables, scaling features, and removing outliers to prepare the data for modeling.

# Tools & Libraries Used
-Google Colab – Coding & execution
- Python – Programming language
- Pandas – Data manipulation
- NumPy – Numerical operations
- Matplotlib & Seaborn – Data visualization
- Scikit-learn – Data preprocessing tools

# Files Included
File Name                                                           
 >Titanic-Dataset.csv           - Original dataset from Kaggle (optional)      
 >titanic_cleaned.csv          - Final cleaned dataset ready for ML modeling  
 >Titanic_Data_Cleaning.ipynb  - Google Colab notebook with step-by-step code 
               

# Step-by-Step Process

 1. Data Loading
- Loaded dataset using `pandas`  
- Inspected basic info and data types

 2. Handling Missing Values
- `Age`: Filled missing values with median  
- `Embarked`: Filled missing values with mode  
- `Cabin`: Dropped due to too many missing values

 3. Encoding Categorical Features
- `Sex`: Label encoding (`male` = 0, `female` = 1)  
- `Embarked`: One-hot encoding (`Embarked_Q`, `Embarked_S`)

 4. Feature Scaling
- Applied `StandardScaler` to `Age` and `Fare` for normalization

 5. Outlier Detection & Removal
- Visualized `Age` and `Fare` using boxplots  
- Removed outliers using the IQR method


## Results
- Final cleaned dataset contains **607 rows**  
- Data is now consistent, numerical, and scaled  
- Ready to be used in ML models such as Logistic Regression, SVM, etc.


# Dataset Source
[Kaggle: Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

## 📎 How to Run
1. Clone or download this repository.
2. Open `Titanic_Data_Cleaning.ipynb` in Google Colab or Jupyter Notebook.
3. Run each cell step-by-step.
4. Final cleaned file: `titanic_cleaned.csv`


##  Contact
For queries or feedback, feel free to reach out:  
indurisravani7@gmail.com


## ✅ Internship Task Submission
This project was completed as part of the AI & ML Internship Task 1 – Data Cleaning and Preprocessing.


