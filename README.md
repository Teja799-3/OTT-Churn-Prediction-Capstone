# OTT-Churn-Prediction-Capstone
Text, Social Media &amp; Web Analytics on OTT Platform Viewer Churn
Here is a **clean, neat, professionally structured README.md** — concise, clear, and perfect for GitHub & project evaluation.

Copy–paste directly into your repository.

---

# 📌 Viewer Churn Prediction for OTT Platforms

**Text, Social Media & Web Analytics Capstone Project**

This project builds a complete analytics pipeline to understand viewer behavior on OTT platforms (Netflix, Prime Video, Hotstar, SonyLIV) using **Text Analytics, NLP, Social Media Analytics, Web Analytics, and Machine Learning**.
The goal is to **predict churn**, identify reasons for user dissatisfaction, and recommend retention strategies.

---


 🎯 Objective

To reduce OTT subscriber churn by analyzing viewer reviews, tweets, and behavioral data using modern text analytics and machine learning techniques.

---

## 🧩 Use Cases Overview

### **1️⃣ Use Case 1: Sentiment Analysis of Viewer Reviews**

* Cleaned and processed OTT viewer reviews
* Extracted polarity, subjectivity, and sentiment labels
* 3D sentiment visualization (Polarity vs Subjectivity vs Index)
* **Key Insight:** Strong link between negative sentiment & potential churn

---

### **2️⃣ Use Case 2: Topic Modeling on Viewer Feedback**

* TF-IDF vectorization
* LDA topic modeling (5 dominant topics)
* 3D topic clustering visualization
* **Key Insight:** Churn mainly driven by subscription price, buffering, and poor recommendations

---

### **3️⃣ Use Case 3: Social Media Analytics**

* Collected/simulated tweets for OTT brands
* Performed sentiment scoring
* Visualized sentiment trend in 3D (Polarity–Subjectivity–Timeline)
* **Key Insight:** Negative spikes align with outages, app issues, or show controversies

---

### **4️⃣ Use Case 4: Churn Prediction**

* Behavioral features: watch hours, sessions/week, subscription age, sentiment score
* Models used: Logistic Regression, Random Forest
* Achieved **85–90% accuracy**
* 3D churn visualization combining behavior + sentiment
* **Key Insight:** Low engagement + low sentiment is strongest churn signal

---

### **5️⃣ Use Case 5: Web Analytics & Recommendation Engine**

* Simulated web activity logs
* K-Means clustering + PCA (4 user clusters)
* 3D viewer segmentation
* **Key Recommendations:**

  * High engagement → loyalty rewards
  * Low engagement + buffering → improve performance
  * Moderate → personalized recommendations
  * Dormant → re-engagement campaigns

---

## 🛠 Tech Stack

* **Python:** pandas, numpy, sklearn, nltk, spacy, textblob
* **Visualization:** Plotly 3D, Matplotlib
* **Database:** SQLite
* **Modeling:** TF-IDF, LDA, Random Forest, Logistic Regression, PCA, K-Means

---

## 📊 Outputs Generated

* Auto-saved visualizations (PNG + HTML)
* Complete SQLite database: `ott_sentiment.db`
* Churn predictions & clusters
* PPT presentation (5 slides)

---

## ▶️ How to Run

1. Install required libraries:

   ```sh
   pip install pandas numpy matplotlib plotly sklearn textblob nltk
   ```
2. Open the notebooks in the following order:

   1. UC1_Sentiment_Analysis.ipynb
   2. UC2_Topic_Modeling.ipynb
   3. UC3_Social_Media_Analytics.ipynb
   4. UC4_Churn_Prediction.ipynb
   5. UC5_Web_Analytics_Clustering.ipynb
3. Run all cells – charts and database outputs generate automatically.

---

## 🏁 Final Outcome

✔ Built a complete text + social media + web analytics workflow
✔ Predicted churn accurately
✔ Identified key reasons for churn
✔ Segmented user behavior
✔ Provided actionable OTT business recommendations

---


