OVERALL CONCLUSION :

CONCLUSION FROM NER_TAG ANALYSIS :
1. Fake news tends to use emotive, political, or nationalistic terms and vague time references to manipulate attention or stir sentiment.

2. Factual news is more statistical, structured, and detailed, using quantifiers, financial terms, and ordinal references to communicate precise information.

CONCLUSION FROM SENTIMENT ANALYSIS :
4. Fake news tends to be more negative in tone.
   Negative sentiments dominate fake news articles.
   This suggests fake news may often be crafted to provoke fear, anger, or outrage.

5. Real news has a more positive tone.
   Positive sentiment dominates real news.
   It implies that factual reporting is more balanced or optimistic, or at least less emotionally manipulative.

6. Neutral sentiment is low in both.
   Most news, whether real or fake, carries some form of polarity, either positive or negative.
   This might be due to the emotional nature of news content itself.



   ##  Features

-  **Text Preprocessing**: Cleaned and prepared news headlines and articles.
-  **NER-Based Analysis**: Identified the most common named entities in fake vs factual news using SpaCy.
-  **Data Visualization**: Compared frequency of entities across news types using Seaborn barplots.
-  **ML Classifiers**: Implemented two classifiers — Logistic Regression and SGDClassifier.
-  **Performance Metrics**: Achieved **99% accuracy** on both models.

---

##  Tech Stack

- **Python 3.9+**
- **Pandas** & **NumPy**
- **Matplotlib** & **Seaborn**
- **scikit-learn**
- **SpaCy (NER)**
- **Jupyter Notebook**

Model	                  Vectorizer	   Accuracy
Logistic Regression    	Bag-of-Words	 99%
SGDClassifier	          Bag-of-Words	 99%
