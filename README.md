# Sentiment-Analysis-on-Amazon-Product-Reviews
This Project focuses on analyzing customer sentiment in Amazon product reviews using Natural Language Processing (NLP) and Machine Learning techniques.
🎯 Objectives
To identify common themes in positive and negative reviews.
To explore the relationship between review length and sentiment.
To examine whether review length correlates with product ratings.

🧰 Languages & Tools Used
Python
Libraries: scikit-learn, NLTK, VADER Sentiment Lexicon, TF-IDF Vectorizer
Visualization: WordCloud, Matplotlib, Seaborn

🔍 Methodology
Data sourced from Kaggle's Amazon Product Review dataset (1,465 rows).
Sentiment classification using:
Logistic Regression
Random Forest
Support Vector Machine (SVM)

📈 Results
All models achieved ~91–92% accuracy, performing best on positive sentiment.
Models struggled to classify neutral and negative sentiments due to data imbalance.
Positive reviews were generally longer, and a weak positive correlation (r=0.0787) was found between review length and rating.

💡 Business Implications
Supports product refinement and targeted marketing strategies.
Highlights the importance of balanced datasets for accurate sentiment detection.
