# Named Entity Recognition (NER) and Article Engagement Prediction

This project analyzes news articles using Named Entity Recognition (NER) to identify important entities and their correlation with article popularity. The goal is to predict news article engagement based on extracted named entities and other relevant features.

## Project Structure

- **data/**: Contains the dataset files (e.g., `politifact_fake.csv`, `politifact_real.csv`).
- **notebooks/**: Jupyter notebooks for data preprocessing, feature engineering, and model training.
- **models/**: Saved model files and model evaluation scripts.
- **visualizations/**: Visualizations (graphs, charts) showing entity frequency, model performance, etc.
- **src/**: Source code for data preprocessing, NER, feature engineering, and model training.
- **requirements.txt**: List of Python dependencies needed to run the project.

## Features

- **Data Preprocessing**: Text cleaning, tokenization, and removal of stop words.
- **Named Entity Recognition**: Extracts entities such as organizations, people, and locations from articles.
- **Feature Engineering**: Derives features like article length, sentiment scores, and entity counts.
- **Predictive Modeling**: Trains a Random Forest model to predict article engagement using extracted features.
- **Visualizations**: Includes precision-recall curves, confusion matrices, and feature correlations.

## Requirements

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - spaCy
  - TextBlob
  - VADER
  - matplotlib
  - seaborn
  - scikit-learn
