# 📰 Fake News Detection Using NLP & Machine Learning

## 📌 Overview
This project aims to detect **fake news articles** using **Natural Language Processing (NLP) and Machine Learning** techniques. The model is trained on a labeled dataset of real and fake news articles and predicts whether a given news article is real or fake.

## 📂 Dataset
- Dataset: **FA-KES-Dataset 2.csv**
- Contains **804 news articles** labeled as real (1) or fake (0)
- Features used: `article_title`, `article_content`, `labels`

## 🛠️ Technologies Used
- **Python**
- **Scikit-learn** (Machine Learning models)
- **NLTK** (Text preprocessing & Sentiment Analysis)
- **Pandas & NumPy** (Data Handling)
- **Matplotlib & Seaborn** (Data Visualization)

## 🔍 Methodology
1. **Data Preprocessing:**
   - Removed duplicates & unnecessary columns
   - Text cleaning (stopwords, punctuation, stemming)
   - Combined `article_title` and `article_content`

2. **Feature Engineering:**
   - Used **TF-IDF Vectorization** to convert text into numerical form
   - Applied **Sentiment Analysis** using VADER

3. **Model Training & Evaluation:**
   - Models used: **Logistic Regression, SVM, Random Forest**
   - Best Accuracy: **~55% using SVM**

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Dhruthiii/Fake-News-Detection-using-NLP-and-ML.git
   cd Fake-News-Detection-using-NLP-and-ML
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python fake_news_detection.py
   ```

## 📈 Results & Future Improvements
✅ Basic ML models achieved ~55% accuracy.
✅ Plan to implement **Deep Learning (LSTM, BERT)** for better performance.
✅ Deploy as a **Web App using Flask/Streamlit**.

## 🤝 Contributing
Feel free to open issues or pull requests for improvements!

## 📜 License
This project is open-source under the **MIT License**.

---

⭐ If you found this project useful, please give it a **star ⭐** on GitHub!

