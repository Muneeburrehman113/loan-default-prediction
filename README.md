# loan-default-prediction
Machine learning project using Random Forest to predict loan defaults with high accuracy. Includes preprocessing, model training, evaluation, and saved predictions.

# Loan Default Prediction using Random Forest

## 📌 Project Overview
This project predicts whether a loan applicant is likely to default based on their financial and demographic information.  
We use a **Random Forest Classifier** to classify loan status as either **0 (No Default)** or **1 (Default)**.

The project is created for learning and practice purposes to demonstrate a complete ML workflow — from data preprocessing to evaluation and saving predictions.

---

## 📂 Project Files
- **loan_default_prediction.ipynb** → Jupyter Notebook with complete code and steps.
- **predictions.csv** → CSV file containing predicted classes and probabilities for the test set.
- **ROC.PNG** → ROC curve plot showing model performance.
- **README.md** → Project documentation.

---

## 📊 Dataset
The dataset contains various borrower features such as:
- Credit history
- Loan amount
- Employment type
- Loan purpose
- Income level  
(Feature names may vary based on the source dataset.)

---

## 🔍 Methodology
1. **Data Loading & Cleaning**  
   - Handle missing values
   - Encode categorical variables
   - Feature scaling if required

2. **Model Selection**  
   - Used **Random Forest Classifier**
   - Tuned hyperparameters for better accuracy

3. **Evaluation**  
   - Classification Report  
   - Confusion Matrix  
   - ROC Curve & AUC Score (0.94)  

4. **Saving Predictions**  
   - Saved predicted class labels and probabilities to `predictions.csv`

---

## 📈 Model Performance
- **Accuracy:** 95%
- **Precision (Class 1):** 85%
- **Recall (Class 1):** 75%
- **AUC Score:** 0.9419

---

## 📷 ROC Curve
![ROC Curve](ROC.PNG)

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/loan-default-prediction.git
