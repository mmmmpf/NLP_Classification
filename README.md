# Emotion Classification with DistilBERT

## Overview
This project applies a pre-trained DistilBERT model to classify emotions in text data. It demonstrates binary classification (neutral vs. non-neutral) and multi-class classification (positive, neutral, negative).

## Assumptions
- The dataset (CSV file) contains a column named 'Emotion' with the target labels and a column 'text' with the input text data.

## Instructions
1. Ensure that the required libraries are installed, including `transformers`, `datasets`, and `scikit-learn`.
2. Change the CSV file location to match your local library / google.colab environment.
3. Run the code in a Python environment that supports GPU acceleration for faster training (e.g., Google Colab).


## Code Structure
- Data loading and preprocessing
- Visualization of data distribution
- Model training and evaluation
- Precision and recall calculation
- Handling imbalanced data (optional)

## Conclusion
The code provides a basic framework for emotion classification using transformers, with additional considerations for imbalanced data and evaluation metrics.
