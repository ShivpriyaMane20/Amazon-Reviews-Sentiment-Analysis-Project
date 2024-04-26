# Amazon-Reviews-Sentiment-Analysis-Project

# Amazon Book Reviews Sentiment Analysis

## Team Information
- **Team 20**
- **Members**: Shivpriya Mane, Vaishnavi Bhavesh Patel

## Overview
This project conducts sentiment analysis on Amazon book reviews to extract insights from customer feedback. Utilizing Natural Language Processing (NLP) techniques, the goal is to classify sentiments into positive, negative, or neutral categories and provide aggregated sentiment scores for individual books.

## Dataset
The dataset comprises two parts: book details and corresponding reviews with ratings. It includes various attributes such as title, description, authors, user IDs, review texts, and more.

- **Source**: [Kaggle Amazon Book Reviews Dataset](https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews/data)

## Methodology
The project encompasses the following steps:
1. **Data Preprocessing**: Merging datasets, selecting relevant columns, cleaning, and sampling.
2. **Exploratory Data Analysis (EDA)**: Sentiment assignment, sentiment distribution visualization, thematic analysis using word clouds, and review length analysis.
3. **Model Selection**: Logistic Regression, Random Forest, and XGBoost models have been evaluated based on accuracy, precision, recall, ROC-AOC, confusion matrices, and F1-score.
4. **Feature Engineering**: The project uses TF-IDF vectorization for text representation and implements strategies to balance the dataset.

## Results
The analysis revealed a significant imbalance in sentiments with a prevalence of positive reviews. Detailed insights from machine learning models provide guidance for authors and publishers.

## Conclusion
Sentiment analysis using machine learning offers valuable insights into readers' emotions and preferences. XGBoost, in particular, proved to be robust in handling the challenges of text data analysis.

## References
- Kaggle Dataset: [Amazon Book Reviews](https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews/data)
- Sentiment Analysis using TF-IDF: [Medium Article](#)

---

## How to Run

Please follow the instructions in the `INFO6105_Team 20.ipynb` notebook for a step-by-step guide on how to perform sentiment analysis on the dataset.

## License
This project is open-sourced under the CC0: Public Domain License.
