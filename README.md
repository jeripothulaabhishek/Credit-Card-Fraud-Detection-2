#  Credit Card Fraud Detection

This project is about detecting fraudulent credit card transactions using data analysis and machine learning. The goal is to identify suspicious transactions that may be fraud while keeping normal transactions safe.

---

##  Project Overview
- Built using **Python** in **Jupyter Notebook**
- Works on a real-world, **imbalanced dataset**
- Shows step-by-step process:
  1. Data cleaning and preprocessing  
  2. Data visualization and analysis  
  3. Handling class imbalance  
  4. Training machine learning models  
  5. Evaluating accuracy and performance  

---

##  Dataset
- Download from Kaggle: [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Contains **284,807 transactions**, of which only **492 are fraudulent** — making it highly imbalanced :contentReference[oaicite:0]{index=0}
- Features:
  - **V1–V28**: anonymized components from PCA  
  - **Time**: seconds elapsed since the first transaction  
  - **Amount**: transaction amount  
  - **Class**: target variable — `0` = normal, `1` = fraud :contentReference[oaicite:1]{index=1}

---

##  Tools & Libraries Used
- **Python**  
- **Pandas, NumPy** → Data handling  
- **Matplotlib, Seaborn** → Visualization  
- **Scikit-learn** → Machine learning models  

---

##  How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/jeripothulaabhishek/Credit-Card-Fraud-Detection-2.git
   cd Credit-Card-Fraud-Detection-2
Install required libraries:

pip install -r requirements.txt


Open the notebook:

jupyter notebook


Run credit card fraud detect.ipynb step by step.

Results

The model could detect most fraudulent transactions with good accuracy.

Balanced between catching frauds (recall) and avoiding false alarms (precision).

Future Scope

Improve results using deep learning (Neural Networks / Autoencoders)

Deploy as a web app for real-time fraud detection

Integrate into banking/finance systems for live monitoring

Author

Abhishek Goud

GitHub: jeripothulaabhishek

B.Tech – Artificial Intelligence & Data Science