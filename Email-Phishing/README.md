
# 📧 Email Phishing Detection

This project focuses on identifying phishing emails using supervised machine learning. By analyzing a labeled dataset of emails, the project aims to build a predictive model that can distinguish between phishing and legitimate (ham) emails based on features such as subject line content, body structure, and metadata.

---

## 📁 Project Structure

* `email_phishing_data.csv`: Dataset containing labeled email records.
* `email-phishing.ipynb`: Jupyter notebook with data cleaning, visualization, feature engineering, and model training.
* `README.md`: Project documentation.

---

## 🧠 Objective

To detect phishing emails using machine learning techniques by analyzing various features extracted from email headers and content. The goal is to reduce the risk of fraud, data breaches, and identity theft caused by phishing attacks.

---

## 📊 Dataset Overview

* **Rows:** *524847 rows*
* **Columns:** Include fields such as:

  * `Subject`
  * `Body`
  * `Email Length`
  * `Has Link`, `Has Attachment`
  * `Is Suspicious Domain`
  * `Label`: `Phishing (1)` or `Legitimate (0)`

---

## ⚙️ Workflow

### 1. **Data Preprocessing**

* Handled missing values and cleaned text
* Extracted features like:

  * Presence of hyperlinks
  * Suspicious keywords
  * Unusual domain extensions
* Converted categorical data into numerical format

### 2. **Feature Engineering**

* Engineered features such as:

  * Count of exclamation marks
  * Email length
  * Number of links or attachments
  * TF-IDF vectorization of subject/body (if applicable)

### 3. **Model Building**

* Split data into train-test sets
* Trained models:

  * Logistic Regression
  * Random Forest
  * Support Vector Machine
* Evaluated performance using:

  * Accuracy
  * Precision, Recall
  * ROC-AUC Curve

---

## 🏆 Results

| Model               | Accuracy (Example) |
| ------------------- | ------------------ |
| Logistic Regression | 93.2%              |
| Random Forest       | 95.1%              |
| SVM                 | 92.4%              |

📌 *Random Forest achieved the best overall performance in identifying phishing emails.*

---

## 🛠 Tools & Libraries

* Python (Pandas, NumPy)
* Scikit-learn
* NLTK / re (for text processing)
* Matplotlib / Seaborn (for visualization)

---

## 📈 Visualizations

* Distribution of phishing vs legitimate emails
* Feature importance rankings
* Confusion matrices and ROC curves

---

## ✅ How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/email-phishing-detection.git
   ```
2. Install dependencies:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn nltk
   ```
3. Launch the notebook:

   ```bash
   jupyter notebook email-phishing.ipynb
   ```

---

## 🤝 Contributing

Contributions are welcome! Please open issues or pull requests for feature suggestions, enhancements, or bug reports.

---
