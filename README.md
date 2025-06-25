# 🍽️ Sentiment Analysis of Restaurant Reviews

This project performs sentiment analysis on restaurant reviews using 🧠 **Natural Language Processing (NLP)** and a 🤖 **Naive Bayes classifier**. It classifies each review as **positive** ✅ or **negative** ❌ based on its content.

<br/>

## ✨ Features

- 🧹 Clean and preprocess text data  
- ❌ Remove stopwords using NLTK  
- 🌱 Apply stemming using `PorterStemmer`  
- 🧾 Extract features with `CountVectorizer`  
- 🤖 Train a `MultinomialNB` sentiment classifier  
- 📊 Evaluate model performance with a confusion matrix and accuracy score  
- 📝 Predict sentiment for a custom review  

<br/>

## 🧾 Requirements

| Symbol | Requirement (Library)                  |
|-----------|--------------------------------------------|
| 📄        | `pandas`          |
| 🔍        | `re`  |
| 📘        | `nltk`  |
| 🧾        | `sklearn.feature_extraction.text` – `CountVectorizer` |
| 🤖        | `sklearn.naive_bayes`  |
| ✂️        | `sklearn.model_selection` |
| 📊        | `sklearn.metrics` |



<br/>

## 📁 Dataset

- **File**: `Restaurant_Reviews.tsv`  


> 📌 Make sure the dataset is placed in the **same folder** as the notebook.

<br/>

## ⚙️ Workflow

1. 📥 Load dataset using `pandas`  
2. 🧹 Clean text: remove non-letter characters, convert to lowercase  
3. ❌ Remove stopwords using NLTK  
4. 🌱 Apply stemming with `PorterStemmer`  
5. 🧾 Convert text to features using `CountVectorizer`  
6. ✂️ Split data into training and testing sets  
7. 🤖 Train a Naive Bayes classifier  
8. 📊 Evaluate with confusion matrix & accuracy  
9. 🔍 Predict sentiment for a new review

<br/>

## 🚀 How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/BhagyashreeMohalkar/Sentiment-Analysis-Restaurant.git
cd Sentiment-Analysis-Restaurant
```

### 2️⃣ Install Required Libraries

```bash
pip install nltk scikit-learn pandas
```

### 3️⃣ Launch the Notebook

```bash
jupyter notebook Sentiment_Analysis_of_Restaurant_Reviews.ipynb
```

📝 Ensure that `Restaurant_Reviews.tsv` is in the **same directory**.

<br/>

## 📊 Sample Output

### 🧾 Confusion Matrix
```
[[91  9]
 [17 83]]
```

### 🎯 Accuracy Score
```
0.87
```

<br/>

## 👩‍💻 Author

**Bhagyashree Savata Mohalkar**  
🎓 Electronics & Computer Engineering  
🏫 Sanjivani College of Engineering, Kopargaon  

🔗 [LinkedIn](https://www.linkedin.com/in/bhagyashree-mohalkar-1b6861287/) | 🐙 [GitHub](https://github.com/BhagyashreeMohalkar)

<br/>

## 🌟 Support

If you found this project helpful, don’t forget to ⭐ the repository. Your support encourages more projects like this! 😊

---
