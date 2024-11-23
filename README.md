# Sentiment Analysis Project

A machine learning project focused on sentiment analysis using product reviews data. The project compares the performance of different models across varying dataset sizes.

## Overview

This project implements sentiment analysis on product reviews to classify customer sentiment. It includes:

- Data preprocessing and analysis of product reviews
- Multiple model implementations for comparison
- Performance evaluation across different dataset sizes (500, 950, and 1400 samples)
- Visualization of model accuracy comparisons

## Model Performance

Three different models were evaluated:

| Dataset Size | Model 1 | Model 2 | Proposed Model |
|-------------|---------|---------|----------------|
| 500         | 74%     | 65%     | 78%           |
| 950         | 74%     | 76%     | 81%           |
| 1400        | 79%     | 76%     | 85%           |

The proposed model shows consistently better performance across all dataset sizes, with highest accuracy of 85% on the 1400-sample dataset.

## Dataset Features

The dataset includes:
- Review text
- Overall rating
- Review time
- Helpful votes
- Additional metadata

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- Google Colab (for notebook execution)

## Usage

1. Open the `AI_Project.ipynb` notebook in Google Colab
2. Mount your Google Drive
3. Run the cells sequentially to:
   - Load and preprocess the data
   - Train the models
   - Visualize the results



