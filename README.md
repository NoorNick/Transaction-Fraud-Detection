# 💳 Fraud Detection using Local Outlier Factor (LOF)

This project implements a simple yet effective fraud detection system using the **Local Outlier Factor (LOF)** algorithm from `scikit-learn`. The model is trained to detect anomalous (potentially fraudulent) transactions based on transaction features like amount, time, and location.

---

## 🧠 What’s Inside

- A `FraudDetector` class that wraps `LocalOutlierFactor`
- Detection of potential fraud based on transaction outlier scores
- Detailed analysis of suspicious transactions
- Visualization of normal vs. fraudulent activity

---

## 📊 Features Used

| Feature     | Description                     |
|-------------|---------------------------------|
| Amount      | Transaction value in currency   |
| Time        | Time stamp (arbitrary unit)     |
| Location ID | Numeric location identifier     |

---

## 📦 Installation

1. Clone the repository:

```
git clone https://https://github.com/NoorNick/Transaction-Fraud-Detection.git
cd Transaction-Fraud-Detection
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:

```
jupyter notebook
```
Then open Fraud_Detection.ipynb to explore, run the code, and visualize results.

---
## 🕵️‍♀️ Example Output
```
Potential fraud cases:
Transaction 10: Score 2.01
Transaction 12: Score 1.95
Transaction 5: Score 1.85
...
```
---
## 📈 Visualization
The notebook includes a scatter plot that shows:

- 🟢 Normal transactions (green)

- 🔴 Detected fraud cases (red)

Axes:

- X-axis: Amount

- Y-axis: Time
---
Detect smarter. Save faster. 💼🛡️💳



