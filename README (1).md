# 🕵️ Forensic Data Analytics – Fraud Detection  

## 📌 Business Summary  
Fraudulent transactions pose a major challenge to financial institutions, leading to revenue loss, reputational damage, and regulatory risks. Detecting fraud in real-time is difficult because fraudulent transactions are rare (<1% of all transactions) and often mimic normal customer behavior.  

This project applies **Forensic Data Analytics** techniques to detect fraud using transaction data. By analyzing spending patterns, transaction amounts, and timing, we build machine learning models that help investigators quickly identify suspicious activity.  

The detection strategy includes:  
- **Exploratory Data Analysis (EDA):** Understanding fraud vs. normal transaction behavior.  
- **Data Preprocessing:** Handling class imbalance and scaling features.  
- **Fraud Analysis:** Investigating fraud by transaction amount and time.  
- **Modeling:** Training Logistic Regression and Random Forest models.  
- **Evaluation:** Comparing models with precision, recall, F1-score, and ROC curve.  

🔑 **Key Findings:**  
- Fraudulent transactions are significantly fewer than normal ones (<1%).  
- Many fraud cases involve higher-than-normal transaction amounts.  
- Fraudulent transactions often occur at unusual hours.  
- Random Forest outperforms Logistic Regression in detecting fraud.  

This analysis can **support internal investigations** by identifying red flags early and providing interpretable evidence for compliance and risk management teams.  

---

## 📂 Project Structure  
```
fraud-detection/
│
├── data/                        # Dataset (not uploaded for confidentiality)
├── fraud_detection_notebook.ipynb   # Jupyter Notebook (full analysis)
├── plots/                       # Exported plots for README & Power BI
│   ├── class_distribution.png
│   ├── transaction_amount.png
│   ├── fraud_vs_normal.png
│   ├── roc_curve.png
│
├── dashboard/                   # Power BI dashboard file (optional)
├── README.md                    # Project documentation
```

---

## 📊 Visualizations  

### Class Distribution  
![Class Distribution](plots/class_distribution.png)  

### Transaction Amount Distribution  
![Transaction Amounts](plots/transaction_amount.png)  

### Fraud vs Normal Transactions  
![Fraud vs Normal](plots/fraud_vs_normal.png)  

### ROC Curve (Model Performance)  
![ROC Curve](plots/roc_curve.png)  

---

## ⚙️ Methodology  

1. **Load & Explore Data**  
   - Imported CSV dataset  
   - Inspected first rows, columns, and null values  

2. **Data Preprocessing**  
   - Scaled features  
   - Addressed class imbalance using SMOTE  

3. **Fraud Analysis**  
   - Analyzed fraud by transaction amount and time  

4. **Modeling**  
   - Logistic Regression  
   - Random Forest  

5. **Evaluation**  
   - Compared Accuracy, Precision, Recall, F1-score  
   - Plotted ROC curve  

---

## 📈 Power BI Dashboard (Optional)  
An interactive Power BI dashboard was built to visualize:  
- Fraud vs normal transactions  
- Transaction patterns by time & amount  
- Model performance metrics  

Recruiters and investigators can use this dashboard for **real-time monitoring**.  

---

## 🚀 How to Run  

1. Clone repository:  
   ```bash
   git clone https://github.com/yourusername/fraud-detection.git
   cd fraud-detection
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. Run Jupyter Notebook:  
   ```bash
   jupyter notebook fraud_detection_notebook.ipynb
   ```

---

## 🏦 Business Relevance  
This project demonstrates how forensic data analytics can help a **leading financial institution**:  
- Detect fraudulent activity early  
- Reduce financial losses  
- Support compliance investigations  
- Strengthen internal risk management frameworks  

---

## 👨‍💻 Author  
Developed by AMON ASWEGE MWASYOGE 
📧 Email: amonaswege426@gmail.com 
📞 Phone: +255 619 867 946
🎓 Data Science Graduate | Forensic Data Analytics Enthusiast  
