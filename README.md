# 📱 SMS Spam Detection using Machine Learning

This project builds a machine learning model to classify SMS messages as **spam** or **ham** (not spam). It uses standard NLP preprocessing, vectorization with `CountVectorizer`, and classifiers like **Multinomial Naive Bayes** and **XGBoost** to achieve high accuracy.

---

## 📂 Dataset

The dataset used is a CSV file (`spam.csv`) containing:

- `v1`: The label (`spam` or `ham`)
- `v2`: The SMS message text

The labels are encoded as:
- `1` = Spam  
- `0` = Ham (Not spam)

---

## ⚙️ Tools & Technologies

- Python  
- Pandas & NumPy  
- Scikit-learn  
- XGBoost  
- CountVectorizer  
- Jupyter Notebook  

---

## 🧼 Text Preprocessing

- Selected relevant columns and renamed them  
- Encoded target labels (spam = 1, ham = 0)  
- Converted text to lowercase  
- Applied `CountVectorizer` to convert text into numeric vectors

---

## 🧪 Models Trained

| Model                    | Accuracy  | Notes                               |
|-------------------------|-----------|--------------------------------------|
| Multinomial Naive Bayes | ~98.3%    | Performed best on this dataset       |
| XGBoost Classifier      | ~96.8%    | Powerful but slightly lower accuracy |

---

## 📈 Evaluation

Model performance was evaluated using:
- **Accuracy**
- `accuracy_score` from `sklearn.metrics`

---

## 🚀 How to Run

1. Clone this repository  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
