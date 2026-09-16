Project Workflow
1. Loading and Preprocessing (3 marks)
Steps performed:

Loaded dataset using pandas.

Cleaned text: lowercasing, regex removal of punctuation/numbers.

Tokenized text into words.

Removed stopwords to reduce noise.

Impact: These steps improve model performance by focusing on meaningful features and reducing irrelevant tokens.

2. Feature Extraction (2 marks)
Used TF‑IDF Vectorizer to convert text into numerical features.

Why TF‑IDF?

Captures both frequency and importance of words.

Produces a sparse matrix suitable for machine learning models.

3. Model Development (2 marks)
Trained two models:

Naive Bayes (MultinomialNB) – efficient for text classification, assumes independence between features.

Support Vector Machine (SVM) – effective in high‑dimensional spaces, finds optimal decision boundaries.

4. Model Comparison (2 marks)
Evaluation Metrics: Accuracy and F1‑score.

Results:

Naive Bayes → Accuracy: 91.16%, F1‑score: 91.14%

SVM → Accuracy: 94.02%, F1‑score: 94.03%

Conclusion:  
While Naive Bayes is simple and efficient, SVM achieved higher accuracy and F1‑score, making it more suitable for emotion classification in this dataset.

5. Timely Submission (1 mark)
Notebook saved as Sentiment_Analysis.ipynb.

Submitted via GitHub link.

📊 Final Results
Model	Accuracy	F1‑score
Naive Bayes	91.16%	91.14%
SVM	94.02%	94.03%
