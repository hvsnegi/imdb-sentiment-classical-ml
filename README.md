# IMDB Sentiment Analysis - Classical ML

Binary sentiment classification on the IMDB 50K movie reviews dataset using TF-IDF vectorization and 5 classical ML models.

## Results

| Model | Accuracy | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | 91.75% | 97.39% |
| Linear SVM | 91.74% | 97.26% |
| Naive Bayes | 88.29% | 95.24% |
| Random Forest | 85.77% | 93.49% |
| Gradient Boosting | 84.15% | 92.57% |

## Project Structure

- IMDB_Sentiment_Analysis.ipynb — Main notebook
- requirements.txt — Dependencies
- README.md — This file

## How to Run

1. Open IMDB_Sentiment_Analysis.ipynb in Google Colab
2. Download dataset from Kaggle:
   kaggle datasets download -d lakshmi25npathi/imdb-dataset-of-50k-movie-reviews --unzip
3. Run all cells top to bottom

## Dataset
IMDB Dataset of 50K Movie Reviews — https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

## Models Used
- Logistic Regression + TF-IDF bigrams
- Linear SVM + TF-IDF bigrams
- Naive Bayes + TF-IDF bigrams
- Random Forest + TF-IDF unigrams
- Gradient Boosting + Bag-of-Words

## Pipeline
Raw Text -> Clean Text -> TF-IDF/BoW -> Classifier -> Positive/Negative
