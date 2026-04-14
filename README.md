
Sentiment Analysis of Social Media Tweets
(1) Problem Statement
Social media platforms generate massive amounts of unstructured text data. Understanding the public sentiment (Positive, Negative, or Neutral) towards emerging technologies like Generative AI is crucial for businesses and researchers to gauge public perception and concerns.

(2) Objective
To build a Machine Learning pipeline that can automatically classify tweets into three categories: Positive, Negative, and Neutral.

To compare the performance of Naive Bayes and Support Vector Machine (SVM) classifiers.

(3) Dataset
Source: Manually curated dataset of tweets related to Generative AI and ChatGPT.

Features: Tweet_Text (Raw text) and Sentiment (Target label).

Size: 100 unique labeled tweets.

(4) Methodology
Data Preprocessing: Converted text to lowercase, removed special characters, and filtered out English stopwords using NLTK.

EDA: Analyzed the distribution of sentiments to ensure a balanced dataset (approx. 33% each).

Model Building: Used TF-IDF Vectorization for feature extraction and implemented Multinomial Naive Bayes and Linear SVM models.

Evaluation: Split data into 80% training and 20% testing sets. Evaluated models using Precision, Recall, and F1-Score.

(5) Results
Naive Bayes: Achieved 90% accuracy on the test set.

SVM: Achieved 100% accuracy on the test set.

Insight: SVM performed exceptionally well on this dataset, showing perfect classification for all three sentiment classes.


(6) How to Run
# 1. Clone the repository
git clone https://github.com/kaifreshamwala-a11y/rollno_name_assignment2

# 2. Open the .ipynb file in Google Colab or Jupyter Notebook
# 3. Ensure 'tweets_data.csv' is in the same directory
# 4. Run all cells to see the classification report
(7) Conclusion
The project successfully demonstrates that Machine Learning models, specifically SVM, can highly accurately classify sentiments in short text data like tweets. Preprocessing (cleaning) and Vectorization (TF-IDF) are key steps in achieving high performance in Natural Language Processing (NLP) tasks.

(8) AI Ethics & Responsible Usage Declaration
I used Google Gemini as an AI assistant to debug the code and structure the documentation.

The dataset used is for academic purposes and contains no private or sensitive information.

(9) Student's details
Name: RESHAMWALA MOHAMMED KAIF SAMEER

Roll No: 47

UIN: 221A007

YEAR: TE-AIDS (2025-26)
