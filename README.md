# SMS-Spam-Classifier
Title:

SMS Spam Classifier using Machine Learning

1. Problem Statement

Spam messages are a major nuisance in communication systems. They waste user time, may contain scams, and can lead to financial or personal harm. The goal of this project is to develop a machine learning model that classifies SMS messages as Spam or Ham (Not Spam).

2. Dataset

Dataset Used: SMS Spam Collection Dataset (UCI Machine Learning Repository).

Size: ~5,574 messages (4,827 ham, 747 spam).

Features: Raw text messages labeled as “ham” or “spam”.

3. Methodology

Data Preprocessing

Text cleaning (lowercasing, removing punctuation, stopwords).

Tokenization & feature extraction using TF-IDF Vectorizer.

Model Training

Algorithm: Logistic Regression (baseline).

Compared with: Naive Bayes.

Evaluation

Metrics: Accuracy, Precision, Recall, F1-score.

4. Results

Logistic Regression achieved ~97% accuracy.

Naive Bayes achieved ~95% accuracy.

Model is lightweight and works well in real-time classification.

5. Tools Used

Python, Scikit-learn, Pandas, Numpy

Google Colab for training

GitHub for project hosting

CLI (Command Line Interface) for demo

6. Learning & Conclusion

Learned text preprocessing & feature extraction.

Understood trade-offs between Logistic Regression & Naive Bayes.

Built an end-to-end ML pipeline with a simple interface.
