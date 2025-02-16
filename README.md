# Toxic_comment_classification-NLP-PROJECT-




![Screenshot 2025-02-15 192624](https://github.com/user-attachments/assets/60f46bcd-4221-4eaf-a446-8a10dadd62f1)









This project focuses on classifying whether a comment is toxic or not using machine learning techniques. The preprocessing steps involve removing special characters and numbers using the re module, eliminating common stopwords with the NLTK library, and applying lemmatization using WordNetLemmatizer to standardize words. The implementation relies on various modules, including pandas for structured data handling, matplotlib for visualizing trends, nltk.corpus for accessing linguistic datasets like stopwords and WordNet, re for text cleaning, and sklearn.metrics for evaluating model performance. After preprocessing, each word is converted into a numerical vector, which serves as a feature for classification. Initially, Naïve Bayes was used for prediction, leveraging word probabilities to determine toxicity; however, Logistic Regression was ultimately chosen due to its improved accuracy in classifying toxic comments. This repository provides a complete pipeline for preprocessing, feature extraction, and classification to identify toxic comments effectively.

