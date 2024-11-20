# review-classifier-nlp
A hands-on project exploring Natural Language Processing (NLP) techniques to classify Yelp reviews. This project leverages data preprocessing, feature engineering, and a machine learning pipeline to analyze and categorize reviews into 1-star or 5-star ratings. A step toward mastering NLP for practical applications.

# Review Classifier with NLP

This project delves into text classification using **Natural Language Processing (NLP)** techniques. The task involves analyzing Yelp reviews and predicting whether a review is **1-star** or **5-star** based on its content.

## Project Goal
The primary objective is to build a model that can effectively classify reviews into two categories (1-star or 5-star) by:
- Cleaning and processing textual data.
- Extracting meaningful features using vectorization methods.
- Applying a robust machine learning pipeline for classification.

## Data Insights
We use the **Yelp Review Dataset** from Kaggle, which contains:
- Reviews written by users about various businesses.
- Ratings (1 to 5 stars) reflecting the user's experience.

We focus on binary classification by isolating **1-star** and **5-star** reviews.

## Techniques Used
1. **Text Preprocessing**: 
   - Removed noise, punctuation, and stopwords.
   - Tokenized text for structured analysis.
2. **Feature Engineering**:
   - Used `CountVectorizer` and `TF-IDF` to convert text into numerical features.
3. **Machine Learning Pipeline**:
   - Built an end-to-end pipeline integrating preprocessing and classification (`Naive Bayes`).
4. **Model Evaluation**:
   - Assessed the performance using accuracy, precision, and recall.
   - Visualized word frequency distributions and dataset sparsity.

## Project Workflow
1. Data cleaning and preparation.
2. Feature extraction using vectorization methods.
3. Classification with `Multinomial Naive Bayes`.
4. Model evaluation and result interpretation.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/GovindaTak/review-classifier-nlp.git
