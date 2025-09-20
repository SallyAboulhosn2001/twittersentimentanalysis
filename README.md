# Twitter Sentiment Analysis

This project implements a **machine learning pipeline to classify tweets** into four categories: **Positive, Negative, Neutral, and Irrelevant**. It showcases text preprocessing, feature engineering, multiple machine learning models, and evaluation metrics.

## **Project Overview**

Social media platforms like Twitter generate massive amounts of text data every day. Understanding the sentiment of these messages can provide valuable insights for businesses, researchers, and AI engineers.  

In this project, I trained and evaluated models to automatically classify the sentiment of tweets, demonstrating an end-to-end AI workflow.

## **Dataset**

- **Source:**Downloaded from Kaggle, provided CSV files (`twitter_training.csv` and `twitter_validation.csv`)  
- **Structure:** Each tweet has a text and a corresponding sentiment label (Positive, Negative, Neutral, Irrelevant)  
- **Preprocessing Steps:**  
  - Removed URLs, mentions, hashtags, and punctuation  
  - Converted text to lowercase  
  - Removed extra spaces and normalized text  

## **Methods**

1. **Feature Engineering:**  
   - TF-IDF vectorization to convert text into numerical features  

2. **Machine Learning Models:**  
   - **Naive Bayes**  
   - **Logistic Regression**  
   - **Random Forest**

3. **Evaluation:**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion matrix to analyze misclassifications  
   - Word clouds to visualize frequent words per sentiment class  

## **Results**

- Random Forest was the **best-performing model**  
- Confusion matrices highlighted where models misclassified sentiments  
- Word clouds provided insights into common terms for each sentiment  

## **Skills Gained**

- Data cleaning and preprocessing with **pandas**  
- Text vectorization using **TF-IDF**  
- Model training and evaluation with **scikit-learn**  
- Visualizing data and results using **matplotlib**, **seaborn**, and **wordcloud**  
- End-to-end AI project workflow from raw data to insights  


## **Visualizations**

- Class distribution chart (Positive / Negative / Neutral / Irrelevant)  
- Word clouds for each sentiment  
- Confusion matrix heatmaps  
- Model comparison bar charts  


## **How to Run**

1. Clone the repository:
git clone https://github.com/SallyAboulhosn2001/twittersentimentanalysis.git

2.you can run the project on any program supporting Python language.
