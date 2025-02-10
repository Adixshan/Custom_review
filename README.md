#📂 Project 2: Sentiment Analysis on Customer Reviews
###📝 Overview
This project builds a Machine Learning model to classify customer reviews as positive or negative.

✨ Features
-✔️ Text Cleaning (Removing special characters, stopwords, digits)
-✔️ Feature Extraction (TF-IDF Vectorization)
-✔️ Model Training (Logistic Regression / Naïve Bayes / SVM)
-✔️ Hyperparameter Tuning (Optimizing model performance)
-✔️ Model Saving (For future predictions)
-✔️ Real-time Sentiment Prediction

📦 Requirements
Python 3.x
pandas, numpy (for data handling)
nltk (for text preprocessing)
sklearn (for ML model training & evaluation)
⚙️ Setup Instructions
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/Adixshan/Custom_review.git
cd Sentiment-Analysis
2️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the Jupyter Notebook
bash
Copy
Edit
jupyter notebook Sentiment_Analysis.ipynb
4️⃣ Test the Model with Custom Reviews
python
Copy
Edit
review = input("Enter your review: ")
predict_sentiment(review)
💡 The model will classify it as Positive 😊 or Negative 😡
