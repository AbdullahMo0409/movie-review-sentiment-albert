# Movie Review Sentiment Classifier using ALBERT

This project is a sentiment analysis system that classifies movie reviews as either positive or negative using an ALBERT transformer model.

The goal of the project was to apply transformer-based NLP to understand review text and predict the overall sentiment behind it. The model returns the predicted sentiment with a confidence score, and the project also includes brief explanation support to make the prediction easier to understand.

---

## Overview

Movie reviews often contain subjective language, mixed emotions, and different writing styles. This makes sentiment classification a useful NLP task for understanding how people express opinions in text.

In this project, an ALBERT-based transformer model was used to classify review sentiment. The project focuses on:

- Text classification
- Transformer-based NLP
- Model training and evaluation
- Sentiment prediction
- Confidence-based output

---

## Features

- Classifies movie reviews as positive or negative
- Uses an ALBERT transformer model
- Provides prediction confidence
- Includes brief explanation support for the model decision
- Includes machine learning and transformer-related project files
- Uses an external dataset link instead of uploading large data files directly

---

## Model

The main model used in this project is **ALBERT**, a lightweight transformer architecture designed for natural language understanding tasks.

ALBERT was used because it provides strong NLP performance while being more parameter-efficient compared to larger transformer models.

**Approximate performance:** 94% accuracy

---

## Repository Structure

```text
movie-review-sentiment-albert/
├── data/              # Dataset notes and external dataset link
├── machine-learning/  # Related ML files or model experiments
├── transformers/      # ALBERT transformer source/model files
├── .gitignore
└── README.md
