# 📰 Fake News Detection using Machine Learning

> 🚀 ML project demonstrating an end-to-end NLP classification pipeline with scope for real-world deployment

---

## 📌 Project Overview

This project focuses on building a machine learning model to classify news articles as **Fake** or **Real** based on textual content.

The system uses Natural Language Processing (NLP) techniques and supervised learning algorithms to detect patterns in news data and make predictions.

---

## 📊 Dataset

* Source: Kaggle Fake and Real News Dataset
* Contains labeled news articles:

  * **Fake = 1**
  * **Real = 0**

---

## ⚙️ Workflow

1. Data Loading and Merging
2. Data Preprocessing
3. Label Encoding
4. Train-Test Split
5. Text Vectorization using TF-IDF
6. Model Training
7. Model Evaluation

---

## 🤖 Models Used

* Logistic Regression
* Multinomial Naive Bayes
* Random Forest Classifier

---

## 📈 Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Precision, Recall, F1-score

---

## 🏆 Final Result

Random Forest Classifier achieved the best performance with an accuracy of approximately **99%** on the test dataset.

---

## 🔍 Sample Prediction

**Input:**
"Breaking: Government announces new policy reforms to boost the economy..."

**Output:**
Prediction: Real News
Confidence: 0.94

---

## 🧠 Key Learnings

* Built an end-to-end NLP pipeline using TF-IDF
* Compared multiple machine learning models
* Evaluated model performance using standard metrics
* Gained understanding of text classification challenges

---

## ⚠️ Limitations

* Model is trained on a static dataset
* May not generalize well to real-time or unseen news sources
* The model performs classification based on linguistic patterns learned from labeled data and does not verify facts from live sources

---

## 🚀 Production-Level Enhancements (Planned)

The current implementation focuses on model development. The following improvements can be implemented to make the system production-ready:

* Convert the model into an API using FastAPI or Flask
* Deploy the system using Docker for scalability
* Integrate real-time news verification using external APIs (e.g., news aggregation services)
* Add source credibility checks and domain validation
* Implement logging and monitoring for predictions
* Improve generalization using advanced NLP models like BERT

> Note: Real-time verification APIs often involve usage costs and rate limits, so they are not integrated in this version.

---

## 📁 Project Structure

fake-news-detection/
│
├── fake_news_detection.ipynb
├── README.md

---

## ▶️ How to Run

1. Clone the repository
2. Open the notebook (`.ipynb` file)
3. Run all cells sequentially

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib / Seaborn

---

## 👩‍💻 Author

**Harshita**
