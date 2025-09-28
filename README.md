# Loan-Approval-prediction

This project predicts whether a loan application will be approved or rejected using machine learning techniques. It demonstrates data preprocessing, exploratory data analysis (EDA), feature engineering, and model training to solve a real-world classification problem.

##  Project Overview

Banks and financial institutions need to automate loan approval processes to make decisions faster and more consistent. This project builds a machine learning pipeline to predict loan approval status based on applicant details.

##  Dataset

* Source: Publicly available loan dataset (e.g., Kaggle or UCI repository).
* Features: Applicant income, loan amount, credit history, education, gender, marital status, etc.
* Target: Loan Status (Approved / Not Approved).

##  Tech Stack

* **Programming Language:** Python
* **Libraries & Tools:**

  * pandas, numpy (data manipulation)
  * matplotlib, seaborn (visualization)
  * scikit-learn (machine learning models & evaluation)
  * Jupyter Notebook (development environment)

## Steps in the Project

1. **Data Preprocessing**

   * Handling missing values
   * Encoding categorical variables
   * Feature scaling

2. **Exploratory Data Analysis (EDA)**

   * Visualizing feature distributions
   * Correlation analysis

3. **Model Building**

   * Logistic Regression
   * Decision Tree
   * Random Forest
   * Support Vector Machine (SVM)
   * Comparing models based on accuracy and other metrics

4. **Model Evaluation**

   * Accuracy Score
   * Confusion Matrix
   * Classification Report

##  Results

* Best model achieved **XX% accuracy**.
* Insights: Credit history and applicant income strongly influence loan approval chances.

##  How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/loan-approval-prediction.git
   cd loan-approval-prediction
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook and run:

   ```bash
   jupyter notebook loan_Approval_prediction.ipynb
   ```

##  Future Improvements

* Deploy the model as a web app (Flask / Streamlit).
* Test on larger, real-world datasets.
* Optimize hyperparameters using GridSearchCV.

