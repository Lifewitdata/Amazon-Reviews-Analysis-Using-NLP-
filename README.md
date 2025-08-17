# 📊 Amazon Reviews Analysis Using NLP  

## 📌 Project Overview  
This project analyzes **Amazon product reviews** using **Natural Language Processing (NLP)** to understand customer sentiment, highlight key themes, and build predictive models.  

The analysis covers **EDA, text preprocessing, word cloud visualization, and sentiment classification** using a Naive Bayes model.  

---

## 📂 Dataset  
- **Total Reviews:** 3,149  
- **Features:**  
  - `verified_reviews` → Review text  
  - `feedback` → Target (1 = Positive, 0 = Negative)  
  - `rating` → Customer rating (1–5 stars)  
  - `variation` → Product variation  

---

## 🔧 Methodology  
1. **Data Preprocessing**  
   - Cleaned text (removed stopwords, punctuation, lowercase).  
   - Dropped missing values.  
   - Created `cleaned_reviews` column.  

2. **EDA**  
   - Rating distribution skewed toward **4 & 5 stars**.  
   - Majority of reviews positive → class imbalance.  
   - Variation-wise analysis showed inconsistent satisfaction levels.  

3. **Feature Engineering**  
   - Used **CountVectorizer** → Generated **4,381 unique terms**.  

4. **Modeling**  
   - **Multinomial Naive Bayes Classifier** trained with 80/20 split.  
   - Evaluated with **accuracy score** and **classification report**.  

---

## 📊 Results  

- **Model Accuracy:** 🎯 **91.6%**  
- **Classification Report:** High precision & recall for positive sentiment.  
- **Word Cloud (Top Positive Words):** *love, great, easy, good, product*  

**Key Insights:**  
- Reviews are overwhelmingly positive.  
- Strong correlation between **ratings** and **feedback**.  
- Certain product variations received relatively more negative feedback.  

---

## 📷 Visualizations  

🔹 **Word Cloud** – most frequent words in customer reviews.  
🔹 **Ratings Distribution Plot** – skewed towards 4 & 5 stars.  
🔹 **Feedback by Product Variation** – highlighted areas with negative sentiment.  


---

## 🛠 Tech Stack  
- **Languages/Libs:** Python, pandas, NumPy  
- **NLP Tools:** CountVectorizer, text cleaning  
- **ML Models:** Naive Bayes Classifier  
- **Visualization:** Matplotlib, Seaborn, WordCloud  

---

## 🚀 Next Steps  
- Apply **TF-IDF Vectorization** to improve text representation.  
- Test with **SVM & Deep Learning models** for better performance.  
- Use **SMOTE/weights** to handle class imbalance.  

---

## 📌 Key Takeaways  
✔ Built an **NLP pipeline** for Amazon review analysis.  
✔ Achieved **91.6% sentiment classification accuracy**.  
✔ Identified **top positive keywords** and product variations needing improvement.  

---

👩‍💻 **Author:** *Isfaque Ansari*  

