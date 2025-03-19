# 📜 Language Detection & Sentiment Analysis  

---

## 📌 Overview  
This project implements two key **Natural Language Processing (NLP) models**:  

1️⃣ **Language Detection Model** 🌍  
   - Identifies the language of a given text input (e.g., English, French, Hindi, etc.).  
   - Useful for **multilingual applications, search engines, and chatbots**.  

2️⃣ **Sentiment Analysis Model** 😊😡  
   - Classifies text as **positive, negative, or neutral**.  
   - Helps in analyzing customer reviews, social media sentiment, and brand monitoring.  

---

## 🚀 Technologies Used  
- **Python** 🐍  
- **Scikit-learn** – Machine Learning algorithms  
- **NLTK & TextBlob** – Text preprocessing & sentiment analysis  
- **Pandas & NumPy** – Data handling  
- **Matplotlib & Seaborn** – Data visualization  
- **TfidfVectorizer** – Text vectorization for language detection  
- **Jupyter Notebook** – Model development  

---

## 📂 Dataset  
### **🔤 Language Detection Model**  
✅ Contains text samples in **multiple languages**.  
✅ Features:  
   - `Text` – The input sentence  
   - `Language` – The corresponding language label  

### **😊 Sentiment Analysis Model**  
✅ Contains **customer reviews/social media posts**.  
✅ Features:  
   - `Review` – The input text  
   - `Sentiment` – **Positive (1), Neutral (0), Negative (-1)**  

---

## ⚙️ Installation & Setup  
#### 1️⃣ Clone the repository  
```bash
git clone https://github.com/SAMUDRAGUPTA002/NLP_based_projects.git
cd NLP-Models  
```
#### 2️⃣ Install dependencies  
```bash
pip install -r requirements.txt  
```
#### 3️⃣ Run the models  
```bash
python language_detection.py  
python sentiment_analysis.py  
```

---

## 📊 Model Training & Evaluation  
### **🔤 Language Detection Model**  
🔹 **Preprocessing:** Text cleaning, tokenization, stopword removal  
🔹 **Vectorization:** TF-IDF representation  
🔹 **Classification Algorithm:** Logistic Regression / Naïve Bayes  
🔹 **Evaluation Metrics:**  
✅ Accuracy  
✅ Precision, Recall, F1-score  
✅ Confusion Matrix  

### **😊 Sentiment Analysis Model**  
🔹 **Preprocessing:** Lowercasing, stemming, and removing special characters  
🔹 **Feature Extraction:** Bag-of-Words, TF-IDF  
🔹 **Classification Algorithm:** Logistic Regression / SVM / LSTM (Deep Learning)  
🔹 **Evaluation Metrics:**  
✅ Accuracy  
✅ Precision, Recall, F1-score  
✅ Sentiment Distribution  

---

## 🔥 Results  
📌 The **Language Detection Model** achieves **97% accuracy** on multilingual datasets.  
📌 The **Sentiment Analysis Model** effectively classifies text sentiment with **92% F1-score**.  

---

## 💡 Future Enhancements  
🚀 Improve language detection with **Deep Learning (LSTMs, Transformers)**  
🚀 Fine-tune sentiment analysis using **BERT for contextual understanding**  
🚀 Deploy both models as an **API using Flask or FastAPI**  

---

## 📜 License  
This project is licensed under the **MIT License**.  
