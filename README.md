# Sentiment Analysis — Twitter Airline Data

Machine learning project to classify tweet sentiment as positive, negative, or neutral.

**Dataset:** Twitter US Airline Sentiment (14,640 tweets)

**Tools:** Python, pandas, nltk, scikit-learn, matplotlib, seaborn, wordcloud

**Models trained:**
- Logistic Regression — 79.88% accuracy
- Naive Bayes — 73.36% accuracy

**Key Findings:**
- Logistic Regression outperformed Naive Bayes by 6.5%
- Negative sentiment dominates at 63% of all tweets (9,178 out of 14,640)
- Model performs best on negative tweets (82% precision) and struggles most with neutral (68%)
- Most common negative words: delay, cancel, service, wait, hour
