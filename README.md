# 🛒 Amazon Reviews Sentiment Analysis  

## 📌 Overview  
This project analyzes **Amazon product reviews** to initially classify them as **positive** or **negative** using **Natural Language Processing (NLP)** and machine learning. The goal is to extract insights from customer feedback and improve product recommendations. 5-star base classification and emoji treatment were explored as well.  

## 🔍 Key Features  
✅ **Data Preprocessing** – Clean and tokenize text for analysis  
✅ **Exploratory Data Analysis (EDA)** – Understand trends in reviews  
✅ **Machine Learning Models** – Train classifiers for sentiment detection  
✅ **Model Evaluation** – Compare accuracy, precision, and recall  
✅ **Visualizations** – Insights through word clouds & sentiment distributions  

## 🤖 Machine Learning Models  

The top-performing models for sentiment classification:  

| Model | Accuracy (%) | F1-Score | True Positives (TP) | True Negatives (TN) | False Positives (FP) | False Negatives (FN) |  
|--------|------------|-----------|------------------|------------------|------------------|------------------|  
| **Logistic Regressor Did/Didn't Bigram** | ✅ **84.5** | ✅ **0.801** | 468 | 800 | 109 | 123 |  
| **Logistic Regressor Tokenized** | 83.9 | 0.795 | 468 | 790 | 119 | 123 |  
| **Random Forest Tokenized** | 83.0 | 0.753 | 389 | 856 | 53 | 202 |  
| **Naive Bayes ComplementNB Tokenized** | 82.8 | 0.778 | 451 | 791 | 118 | 140 |  

🛠 Tech Stack

- Languages: Python
- Libraries: SpaCy, nltk, Pandas, NumPy, scikit-learn, Matplotlib, Seaborn
- Tools: Jupyter Notebook
 
## 📬 Contact
💼 [LinkedIn](https://www.linkedin.com/in/chelsy-mena-gonzalez) | 📧 [chelsymg@gmail.com](mailto:chelsymg@gmail.com)


