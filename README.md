# Text_Sentiment_Analysis_IMDB
# IMDB Movie Review Sentiment Analysis 🎬📊

This project performs **sentiment analysis** on IMDB movie reviews using **Natural Language Processing (NLP)** and **Machine Learning**. It classifies each review as **Positive ** or **Negative ** using logistic regression and TF-IDF features.

---

Key Features

Data cleaning and preprocessing (NLTK)
 TF-IDF feature extraction
 Logistic Regression model for binary classification
 Real-time user input sentiment prediction
 Evaluation using precision, recall, and F1-score



 Dataset

- **Source**: [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **Structure**:
  - `review`: Text of the movie review
  - `sentiment`: Label (positive/negative)

---

 Libraries Used

```bash
pandas
numpy
nltk
scikit-learn
How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/yourusername/imdb-sentiment-analysis.git
cd imdb-sentiment-analysis
Place the IMDB Dataset.csv file in the project directory.

Run the script:

bash
Copy
Edit
python sentiment_analysis.py
Enter a custom movie review when prompted to get the predicted sentiment.

Sample Output
plaintext
Copy
Edit
Enter a movie review to analyze sentiment: This movie was absolutely fantastic with brilliant acting!

Sentiment: Positive 

