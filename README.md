# Salary Prediction Using BERT

This project demonstrates how to use BERT (Bidirectional Encoder Representations from Transformers) for predicting salary ranges based on job descriptions. The model leverages the power of BERT's contextual language understanding to generate more accurate predictions from job-related text.

## Overview

The salary prediction model aims to understand job descriptions to predict appropriate salary ranges. It uses BERT to extract meaningful patterns and features from the text, improving the relevance and accuracy of predictions.

## Requirements

```bash
pip install torch transformers pandas scikit-learn
```

### Main Dependencies

- **Python 3.7+**
- **Transformers**: For working with BERT and other transformer models.
- **PyTorch**: Provides the deep learning backend for model training.
- **Pandas**: Used for data handling and manipulation.
- **Scikit-learn**: Supplies tools for model evaluation and metrics.

## Data Preparation

Ensure you have a dataset containing job descriptions and associated salary ranges. In the notebook:

- Job descriptions are cleaned and tokenized using the BERT tokenizer.
- Data is split for training and evaluation.

## Model Training and Evaluation

The notebook includes code to:

- Preprocess and tokenize job descriptions.
- Fine-tune BERT for salary prediction tasks.
- Evaluate the model using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).