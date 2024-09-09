# Video-Advertisement-Classifier-using-LLM

## Project Overview
This project involves the development of a classifier to analyze video advertisements and answer 21 binary (yes/no) questions related to the content, such as calls to action, emotional impact, and product mentions. The goal is to replicate human annotations using a machine learning classifier, with a focus on maximizing performance metrics such as agreement percentage, F1 score, precision, and recall.

## Dataset
# Videos:
150 video advertisements from various companies and of varying durations.
**Textual Data:**
Ad campaign descriptions and transcriptions of the videos.
**Ground Truth:**
Human-annotated answers to 21 yes/no questions.

## Methodology
# Data Preprocessing:
Textual data was cleaned and preprocessed to remove noise and irrelevant information.
The video descriptions were aligned with human annotations using a majority voting mechanism to resolve conflicts.
Categorical data was encoded for model training purposes.

# Model Selection:
DistilBERT and ALBERT models were chosen for their efficiency with textual data.
The model was trained on the preprocessed data, with hyperparameters such as learning rate and batch size fine-tuned for optimal performance.

## Evaluation Metrics:
**Agreement Percentage:** Measures the overall match between the classifier's results and the ground-truth annotations.
**Precision**: The proportion of true positives among all positive predictions.
**Recall:** The proportion of true positives among all actual positives.
**F1 Score:** The harmonic mean of precision and recall.

## Results
The classifier was able to replicate human annotations with moderate accuracy.
Some questions, particularly those requiring nuanced understanding of video content, posed greater challenges for the model.
Future improvements could involve fine-tuning the model for better handling of implicit and complex video content.

# Agreement Percentage
Precision
Recall
F1 Score

## Executive Summary
Detailed insights about the classifier's performance, key challenges, and areas for improvement are available in the executive summary.
