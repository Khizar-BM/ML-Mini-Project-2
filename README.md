# Twitter Sentiment Analysis

## Overview
This project implements various machine learning models to perform sentiment analysis on Twitter data. The goal is to classify tweets as positive or negative based on their content. Multiple approaches are compared, including traditional machine learning models and deep learning techniques with transformer-based models.

## Dataset
The project uses the Sentiment140 dataset, which contains 160,000 tweets with sentiment labels:
- Label 0: Negative sentiment
- Label 1: Positive sentiment

The dataset is perfectly balanced with equal numbers of positive and negative samples (80,000 each).

## Models Implemented
The project experiments with and compares multiple approaches:

1. **Traditional Machine Learning**
   - Random Forest Classifier
   - Support Vector Machine (SVM)
   - Logistic Regression

2. **Deep Learning**
   - DistilBERT - A smaller, faster version of BERT that retains most of BERT's performance

## Preprocessing Techniques
- Text cleaning (removing URLs, usernames, special characters)
- Tokenization
- Stemming
- Stop word removal
- TF-IDF vectorization for traditional ML models

## Results
The models were evaluated using accuracy and classification metrics. The transformer-based model (DistilBERT) achieved the best performance compared to traditional machine learning approaches.

## Project Structure
- `ml_mp_2.ipynb`: Jupyter notebook containing all code for data preprocessing, model training, and evaluation
- `Sentiment Analysis on Twitter Data.pdf`: Complete report on the project methodology and findings
- `trained_weights.zip`: Saved model weights for future use or inference

## Requirements
- Python 3.x
- TensorFlow
- Transformers (Hugging Face)
- NLTK
- scikit-learn
- pandas
- numpy
- matplotlib

## Usage
1. Clone the repository:
   ```
   git clone https://github.com/Khizar-BM/ML-Mini-Project-2.git
   ```
2. Install the required dependencies
3. Run the Jupyter notebook to see the complete workflow

## Future Work
- Experiment with larger transformer models (BERT, RoBERTa)
- Implement ensemble methods combining traditional ML and deep learning approaches
- Expand to multi-class sentiment classification
- Test the models on different social media datasets

## Author
- Khizar Baig Mohammed

## License
This project is available for educational and research purposes. 