# SMS Spam Detection with Machine Learning

This notebook demonstrates SMS spam detection using machine learning techniques. The dataset (`spam.csv`) contains SMS messages labeled as "ham" (not spam) or "spam". The workflow includes:

- **Data Preprocessing:** Loading the dataset, selecting relevant columns, and encoding labels.
- **Text Vectorization:** Converting SMS messages into numerical features using `CountVectorizer`.
- **Model Training:** Training two classifiers—XGBoost and Multinomial Naive Bayes—on the vectorized data.
- **Evaluation:** Assessing model performance using accuracy on a held-out test set.

This approach provides a simple yet effective pipeline for classifying SMS messages as spam or not spam.
