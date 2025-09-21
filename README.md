# Multilingual Binary Text Classification with XLM-RoBERTa
This project implements a binary text classification model using XLM-RoBERTa, capable of handling paired text inputs and imbalanced datasets. It is designed for multilingual data, making it suitable for applications where inputs are in multiple languages.
## Overview
The model predicts a binary label (0 or 1) based on two input text fields: origin_query and category_path. It uses transformer-based embeddings from XLM-RoBERTa and fine-tunes them on the training dataset. The code also manages missing values gracefully and ensures proper tokenization, padding, and truncation.
# Key Features
1)Paired input handling: Combines information from two text columns to improve prediction.
2)Multilingual support: Leverages XLM-RoBERTa’s ability to understand multiple languages.
3)Class imbalance handling: Computes weights from training labels and uses weighted cross-entropy loss during training.
4)Evaluation metrics: Tracks both accuracy and F1 score for the positive class, ensuring balanced performance on minority classes.
5)GPU acceleration: Supports CUDA with mixed-precision training for faster execution.
# Results
The model achieves an F1 score of 0.77 on the positive class for the test set.

The Project repo entails 

