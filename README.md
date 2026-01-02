# Personal Loan Acceptance Prediction

##  Objective
The objective of this project is to predict which customers are most likely to accept a personal loan offer using classification techniques and to extract meaningful business insights from customer data.

---

##  Dataset
**Bank Marketing Dataset**  
Source: UCI Machine Learning Repository

The dataset contains customer demographic and financial information such as:
- `age` – Age of the customer
- `job` – Type of job
- `marital` – Marital status
- `education` – Education level
- `balance` – Account balance
- `housing` – Housing loan status
- `loan` – Personal loan status
- `y` – Target variable (yes/no for loan acceptance)

 Dataset Link:  
https://archive.ics.uci.edu/ml/datasets/bank+marketing

---

##  Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

##  Project Workflow

### 1. Data Loading & Exploration
- Loaded the Bank Marketing dataset
- Explored dataset shape, columns, and missing values

### 2. Exploratory Data Analysis (EDA)
- Analyzed customer distribution by:
  - Age
  - Job type
  - Marital status
- Visualized relationships between customer features and loan acceptance

### 3. Data Preprocessing
- Encoded categorical variables using Label Encoding
- Prepared features and target variable for modeling

### 4. Train-Test Split
- Split data into:
  - 80% training set
  - 20% testing set

### 5. Classification Modeling
- Trained a **Logistic Regression** classifier to predict loan acceptance

### 6. Model Evaluation
- Evaluated model using:
  - Accuracy score
  - Classification report
  - Confusion matrix

### 7. Business Insights Extraction
- Identified customer groups more likely to accept personal loans
- Analyzed acceptance rates across different age groups and job categories

---

## Results & Insights
- Middle-aged customers showed higher loan acceptance rates
- Certain job categories were more responsive to loan offers
- Logistic Regression provided effective and interpretable results for this business problem

---

##  How to Run the Project
1. Download the dataset from the UCI repository
2. Place `bank.csv` in the project directory
3. Open the Jupyter Notebook:
