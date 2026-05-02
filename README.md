# 📧 Spam Mail Prediction using Machine Learning

## 👨‍💻 Author
**Vikram Singh Kushwaha**

---

## 📌 Project Overview
This project is a Machine Learning-based **Spam Mail Prediction System** built using Python and Natural Language Processing (NLP) techniques. The goal is to classify emails as **Spam** or **Ham (Not Spam)** by learning patterns from textual data.

The project demonstrates a complete end-to-end ML workflow including text preprocessing, feature extraction, model training, evaluation, and visualization.

---

## 🎯 Objectives
- Detect spam emails using machine learning
- Apply NLP techniques to real-world text data
- Build a reliable and efficient classification model
- Understand feature extraction using TF-IDF

---

## 🛠️ Tech Stack
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## 🧠 Key Concepts Used
- Text Preprocessing (Cleaning, Lowercasing, Removing Stopwords)
- Feature Extraction using **TF-IDF Vectorizer**
- Supervised Learning (Classification)
- Model Evaluation using Accuracy Score

---

## ⚙️ Machine Learning Workflow

### 1. 📥 Data Collection
- Dataset containing labeled emails (Spam / Ham)

### 2. 🧹 Data Preprocessing
- Removing punctuation
- Converting text to lowercase
- Removing stopwords
- Tokenization

### 3. 🔢 Feature Extraction
- Used **TF-IDF Vectorizer** to convert text into numerical vectors

### 4. 🔀 Train-Test Split
- Split dataset using `train_test_split`

### 5. 🤖 Model Building
- Implemented **Logistic Regression** classifier

### 6. 📊 Model Evaluation
- Evaluated using **accuracy_score**

---


---

## 📈 Model Performance
- **Accuracy Score:** 95.33%

Optional metrics you can include:
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 📊 Features
- Classifies emails as Spam or Ham
- Uses NLP techniques for text processing
- Efficient and lightweight model (Logistic Regression)
- Clear and structured ML pipeline

---

## ▶️ How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
```

### 2. Navigate to the project directory
```bash
cd your-repo-name
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the script
```bash
python spam_mail_prediction.py
```

---

## 📁 Project Structure
```
├── spam_mail_prediction.py
├── dataset.csv
├── images/
│   ├── spam_distribution.png
│   ├── word_frequency.png
│   └── tfidf_visual.png
├── requirements.txt
└── README.md
```

---

## 📌 Example Usage
Input:
```
"Congratulations! You have won a free lottery ticket. Click here now!"
```

Output:
```
Spam
```

---

## 🚀 Future Improvements
- Use advanced NLP models (LSTM, BERT)
- Improve preprocessing with stemming/lemmatization
- Deploy as a web application using Flask/FastAPI
- Add real-time email classification

---

## 💡 Key Learnings
- Hands-on experience with NLP pipelines
- Understanding TF-IDF and text vectorization
- Building classification models on text data
- Importance of preprocessing in NLP tasks

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📬 Contact
Feel free to connect with me for feedback or collaboration opportunities.

---

⭐ If you like this project, don’t forget to give it a star!

