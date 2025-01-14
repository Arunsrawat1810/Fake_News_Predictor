# Fake News Prediction

This project involves a machine learning model designed to predict whether a news article is real or fake using natural language processing (NLP) techniques. The model is trained on a dataset containing diverse news articles to enhance its generalization capability.

## Dataset Description

The dataset used in this project contains the following columns:

- `id`: Unique identifier for a news article
- `title`: The title of the news article
- `author`: The author of the news article
- `text`: The text of the article (may be incomplete)
- `label`: A label marking whether the news article is real or fake (1: Fake news, 0: Real news)

## Dependencies

To run this project, you need the following Python packages:
- numpy
- pandas
- re
- nltk
- scikit-learn

## Installation

Install the required packages using pip:
```bash
pip install numpy pandas nltk scikit-learn
