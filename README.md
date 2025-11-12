# 🏨 Hotel Review Sentiment Analysis  

**NLP-powered hotel review analysis** that processes 250K+ real customer reviews across 10 global cities to uncover patterns in satisfaction, complaints, and neutral feedback.  
Combines **Natural Language Processing**, **Machine Learning**, and **Data Visualization** for actionable insights.

---

## ✨ Project Highlights  

✅ Consolidated 250K+ reviews from **10 cities** (Dubai, London, NYC, etc.)  
✅ Applied **VADER Sentiment Analyzer** for polarity scoring (Positive / Negative / Neutral)  
✅ Built TF-IDF-based text representations  
✅ Trained and tuned **Logistic Regression** and **Ridge Classifier** models  
✅ Achieved **~90% accuracy** with consistent class performance  
✅ Visualized trends by **hotel**, **city**, and **sentiment label** using Seaborn and Matplotlib  

---

## 🧰 Tech Stack  

| Category | Tools / Libraries |
|-----------|------------------|
| **Language** | Python 3.10 |
| **Data Handling** | Pandas, NumPy |
| **NLP** | NLTK, VADER Sentiment |
| **ML Models** | Scikit-Learn (TF-IDF, Logistic Regression, Ridge Classifier) |
| **Visualization** | Seaborn, Matplotlib |
| **Environment** | Jupyter Notebook, Conda |

---

## 🧠 Workflow  

1. **Data Preprocessing** – Combine & clean multi-city review files  
2. **Sentiment Analysis** – Compute sentiment polarity using VADER  
3. **EDA & Visualization** – Explore top hotels and sentiment distributions  
4. **Model Training** – Fit and tune ML classifiers on TF-IDF vectors  
5. **Evaluation** – Compare accuracy, precision, recall, and F1-scores  

---

## 📊 Visual Insights  

<p align="center">
  <img src="sentiment labels.png" width="75%">
  <br>
  <em>Distribution of Sentiment Labels – Positive, Neutral, Negative</em>
</p>

<p align="center">
  <img src="assets/660462f4-cb75-45b7-9a19-250b9295615d.png" width="95%">
  <br>
  <em>Top 10 Hotels by Sentiment Distribution (Sampled Data)</em>
</p>

---

## 🧮 Results  

| Model | Accuracy | Precision | F1-Score (per class) |
|--------|-----------|------------|----------------------|
| Logistic Regression | **0.8983** | 0.7859 | [0.5457 (Negative), 0.7628 (Neutral), 0.9446 (Positive)] |
| Ridge Classifier | 0.8867 | 0.7596 | 0.7736 (macro) |

✅ **Final Model:** Logistic Regression  
- High accuracy (~90%) and excellent positive sentiment recognition  
- Balanced recall across classes, suitable for large-scale review monitoring  

---

## 📈 Interpretation  

💡 **Positive reviews dominate** across all cities, reflecting generally favorable hotel experiences.  
💡 **Negative feedback** mostly relates to location, cleanliness, or service inconsistencies.  
💡 **Neutral sentiments** cluster around factual or mixed opinions.  

---

## ⚙️ How to Run  

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/hotel-review-sentiment-analysis.git
   cd hotel-review-sentiment-analysis
   pip install -r requirements.txt
   jupyter notebook Customers_Hotel_Review_Sentiment_Analysis.ipynb
