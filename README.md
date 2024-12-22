# 📊 Fake News Detector - Data Science Project  

---

## 🌟 Project Overview  

![Overview Image](https://tse1.mm.bing.net/th?id=OIP.2lshbSH90RR3rPVLen0Z_gHaEK&pid=Api&P=0&h=180)  

The **Fake News Detector** is a Data Science project that uses machine learning algorithms to identify whether a news article is **Fake** or **Real**. By leveraging Natural Language Processing (NLP) techniques and a Naive Bayes classifier, this tool automates the detection of misinformation in real-time.  

---

## 🛠️ Technologies & Tools  

- **Python**: Primary language for data manipulation and machine learning.  
- **Scikit-learn**: For building the classification model using Multinomial Naive Bayes.  
- **NLTK**: For text preprocessing (stopword removal, tokenization, etc.).  
- **Flask**: Web framework to deploy the model as a real-time application.  
- **HTML/CSS**: For creating a user-friendly interface.  
- **Jupyter Notebooks**: For exploratory data analysis and model prototyping.  

---

## 🧠 How It Works  

![Workflow Image](https://tse4.mm.bing.net/th?id=OIP.mzstZIs3SXyM5yg2YVimvwHaD_&pid=Api&P=0&h=180)  

1. **Data Collection**:  
   - A dataset containing labeled news articles (*Fake* and *Real*) is used to train the model.  

2. **Text Preprocessing**:  
   - **Tokenization**: Breaking text into words or tokens.  
   - **Stopwords Removal**: Removing common words like “the”, “is”, etc., that do not contribute to the meaning.  
   - **Lemmatization**: Reducing words to their base forms (e.g., “running” → “run”).  

3. **Feature Extraction**:  
   - **TF-IDF Vectorizer**: Converts the text into numerical features (importance of words in the article).  

4. **Model Training**:  
   - A Multinomial Naive Bayes classifier is trained on the processed text data to classify articles as *Fake* or *Real*.  

5. **Real-Time Prediction**:  
   - Users can paste news articles into the web app, and the model will classify them instantly based on the trained data.  

---




