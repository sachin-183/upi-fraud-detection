#  UPI Fraud Detection using Machine Learning

This project aims to **detect fraudulent UPI (Unified Payments Interface) transactions** using data analysis and machine learning techniques.  
The model identifies suspicious activities in online payment systems based on transaction patterns and user behavior.

---

##  Why This Project
- With the rapid growth of digital payment systems, **UPI fraud** has become a major concern.  
- Detecting fraudulent transactions in real-time helps:
  - Prevent financial losses.
  - Improve customer trust.
  - Enhance the security of payment networks.  
- This project demonstrates how data science and ML can help identify **fraud patterns** effectively.

---

## ⚙️ How It Works
1. **Data Collection** – Load and explore the UPI transaction dataset.  
2. **Data Preprocessing**  
   - Handle missing values.  
   - Encode categorical variables (like transaction type, device, etc.).  
   - Normalize numerical features.  
3. **Exploratory Data Analysis (EDA)**  
   - Visualize transaction patterns.  
   - Identify correlations between features.  
4. **Model Training**  
   - Use classification algorithms (e.g., Logistic Regression, Random Forest, XGBoost).  
   - Train the model to distinguish between **fraudulent** and **legitimate** transactions.  
5. **Model Evaluation**  
   - Evaluate with **accuracy**, **precision**, **recall**, **F1-score**, and **ROC-AUC**.  
   - Analyze confusion matrix for classification performance.  
6. **Prediction** – Predict whether a transaction is fraudulent based on new input data.

---

## 📂 Dataset
- **File:** `upi_fraud_dataset.csv` *(or loaded directly in the notebook)*  
- Contains transactional details like:
  | Feature | Description |
  |----------|-------------|
  | `TransactionID` | Unique ID of each transaction |
  | `Amount` | Transaction amount |
  | `TransactionType` | Type of UPI transfer (P2P, Merchant, etc.) |
  | `DeviceType` | Device used for the transaction |
  | `IsFraud` | Target variable (1 = Fraudulent, 0 = Legitimate) |

---

## 🛠️ Technologies & Libraries
- Python 3.x  
- [pandas](https://pandas.pydata.org/) – Data handling  
- [numpy](https://numpy.org/) – Numerical computations  
- [matplotlib](https://matplotlib.org/) – Visualization  
- [seaborn](https://seaborn.pydata.org/) – Advanced statistical plots  
- [scikit-learn](https://scikit-learn.org/stable/) – ML algorithms and evaluation metrics  
- [xgboost](https://xgboost.readthedocs.io/) – Gradient boosting classifier (if used)

---

## 📊 Project Workflow
1. Import necessary libraries.  
2. Load and explore the dataset.  
3. Perform data preprocessing and feature engineering.  
4. Train ML models on labeled transaction data.  
5. Evaluate model using standard metrics.  
6. Visualize key insights and performance results.  
7. Predict fraud probability for new transactions.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/upi-fraud-detection.git
   cd upi-fraud-detection
