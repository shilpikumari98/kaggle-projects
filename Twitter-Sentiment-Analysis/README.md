
# 🐦 Twitter Sentiment Analysis

This project focuses on classifying tweets into **Positive**, **Negative**, **Neutral**, and **Irrelevant** sentiments using machine learning and natural language processing (NLP). The goal is to understand public sentiment, which can be applied in brand monitoring, politics, and customer service.

---

## 📁 Project Structure

* `twitter_training.csv`: Dataset containing over 74,000 labeled tweets.
* `twitter-sentiment-analysis.ipynb`: Python notebook for end-to-end sentiment classification.
* `README.md`: Project documentation.

---

## 🧠 Objective

To preprocess real-world tweet data and train machine learning models capable of accurately classifying tweet sentiment using text-based features.

---

## 📊 Dataset Overview

* **Total Tweets:** 74,682
* **Fields:**

  * `ID`: Tweet ID
  * `Entity`: Brand/Topic (e.g., Apple, Amazon, etc.)
  * `Sentiment`: One of `Positive`, `Negative`, `Neutral`, or `Irrelevant`
  * `Tweet`: The actual tweet text

---

## ⚙️ Methodology

### 1. **Data Cleaning**

* Removed nulls and duplicates
* Lowercased all text
* Stripped URLs, punctuation, hashtags, and stopwords

### 2. **Preprocessing**

* Tokenization
* Lemmatization
* Vectorization using **TF-IDF**

### 3. **Model Training**

Used two ML algorithms:

* **Logistic Regression** (TF-IDF)
* **Support Vector Machine (SVM)** (TF-IDF)

### 4. **Evaluation Metrics**

* Accuracy
* Confusion Matrix
* Classification Report

---

## 🏆 Results

| Model                  | Accuracy |
| ---------------------- | -------- |
| Logistic Regression    | 60.90%   |
| Support Vector Machine | 61.00%   |

📌 **Observation:** SVM slightly outperformed Logistic Regression on this multi-class classification task.

---

## 📈 Visualizations

* Sentiment distribution plot
* Word clouds for each sentiment class
* Confusion matrix for model evaluation

---

## 🛠 Tools & Libraries

* `pandas`, `numpy` – Data processing
* `nltk`, `re` – NLP preprocessing
* `sklearn` – Model building and evaluation
* `matplotlib`, `seaborn` – Visualizations

---

## ✅ How to Run

1. Clone this repository.
2. Install dependencies:

   ```bash
   pip install pandas numpy nltk scikit-learn matplotlib seaborn
   ```
3. Run the notebook:

   ```bash
   jupyter notebook twitter-sentiment-analysis.ipynb
   ```

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo, suggest improvements, or submit pull requests.
---
