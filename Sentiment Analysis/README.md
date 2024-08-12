# Sentiment Analysis on Amazon Reviews
This project focuses on performing sentiment analysis on Amazon product reviews. The primary goal is to classify customer reviews as either positive or negative using various machine learning techniques.

## Key Features:

- Data Preprocessing: The dataset is preprocessed to handle missing values, and text data is cleaned and tokenized.
- Feature Extraction: TF-IDF vectorization is employed to convert text data into numerical features.
- Modeling: Several models are built and compared, including Logistic Regression, Random Forest, and Decision Tree classifiers.
- Evaluation: Models are evaluated using accuracy, confusion matrix, and classification report to determine the best performing model.
- Visualization: The project includes visualizations such as word clouds to understand the most common words in positive and negative reviews.
## Dataset:

The dataset used for this project consists of Amazon product reviews, where each review is labeled as positive or negative.                                       
url= https://drive.google.com/file/d/1yXhMGfaElSHpjz5CXa9UxAtV7A7i14hl/view

## Libraries Used:

- pandas, numpy for data manipulation
- sklearn for machine learning models and metrics
- nltk for natural language processing tasks
- matplotlib and WordCloud for visualization
  
## How to Run:

- Clone the repository.
- Install the required libraries.
- Run the Jupyter notebook to see the analysis and model results.

## Conclusion

This sentiment analysis project successfully classified Amazon product reviews as positive or negative using various machine learning models. The LogisticRegression achieved an accuracy of 74%, indicating its effectiveness in sentiment classification.

