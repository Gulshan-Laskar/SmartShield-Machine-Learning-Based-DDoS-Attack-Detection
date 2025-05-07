# 🚨 SmartShield: Machine Learning-Based DDoS Attack Detection

An end-to-end data science project that leverages statistical techniques and machine learning to detect Distributed Denial of Service (DDoS) attacks from network traffic logs. It combines exploratory data analysis (EDA), dimensionality reduction using PCA, and classification via supervised and unsupervised models to build a robust cybersecurity solution.

---

## 📌 Project Objectives
- Analyze large-scale network traffic data for anomalies.
- Detect DDoS attacks with high accuracy using machine learning models.
- Minimize false positives and computational cost.
- Explore traffic trends across time and protocol types.

---

## 🧰 Tools & Technologies
- **Programming**: Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Models**: Logistic Regression, Random Forest, Isolation Forest
- **Techniques**: PCA (Principal Component Analysis), GridSearchCV
- **Concepts**: Anomaly Detection, EDA, Feature Engineering, Time Series Segmentation

---

## 📊 Exploratory Data Analysis Highlights
- **Label Distribution**: Nearly balanced dataset (Benign: 49.4%, DDoS: 50.6%)
- **Traffic Patterns**: DDoS traffic showed prolonged flows with large forward packet counts.
- **Protocol Use**: TCP is the primary protocol used in attacks; UDP and unknown types are rare.
- **Time-Based Trends**: DDoS attacks peaked during 6 PM–12 AM, indicating strategic attack timing.

---

## 🧪 Model Performance
| Model               | Accuracy | Precision | Recall | F1-Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression | ~98.0%   | 0.97–0.99 | 0.97–0.99 | 0.98 |
| Random Forest       | **99.75%** | **1.00** | **1.00** | **1.00** |
| Isolation Forest (Unsupervised) | 65.6% | 0.62 | 0.85 | 0.72 |

---

## 🔍 Dimensionality Reduction with PCA
- Reduced feature space from 82 to 26 components.
- Retained 95% of total variance.
- Enhanced model interpretability and performance.
  
---
