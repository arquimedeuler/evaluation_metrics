# Evaluation metrics

This repository contains a summary of the article [Evaluation Metrics](https://aman.ai/primers/ai/evaluation-metrics/) from [aman.ai](https://aman.ai/).

The structure of the course is as follows

## 1. Evaluation Metrics for the Classification Problem
In this section, we discuss the fundamental metrics for evaluating classification models.

- Types of Prediction Errors
The different types of errors that a classification model can make, such as type I (false positive) and type II (false negative) errors, are explored.

- Accuracy
Accuracy measures the proportion of correct predictions out of the total predictions. It is a basic but important metric for assessing overall model performance.

- Precision
Precision focuses on the proportion of positive predictions that were actually correct. It is particularly useful when minimizing false positives is critical.

- Recall
Recall evaluates the proportion of positive instances that the model correctly identified. It is essential when it is crucial to capture the majority of positive instances.

- Confusion Matrix
The confusion matrix provides a detailed view of the model predictions, showing true positives, false positives, true negatives and false negatives.

- F1 Score
The F1 Score combines precision and recall in a single metric, useful when seeking a balance between the two.

## 2. Evaluation Metrics for Generative Text Models
In this section, we explore specific metrics for evaluating generative text models.

- Perplexity
Perplexity measures the inconsistency or "surprise" of a generative model. Lower perplexity indicates greater model coherence and comprehensibility.

- Burstiness
Burstiness evaluates consistency in text generation. It measures how much the length of generated sequences varies.

- BLEU Score
The BLEU Score evaluates the quality of text generation by comparing it with human references. It is especially useful in machine translation.

- ROUGE Score
The ROUGE Score measures the similarity between the generated text and a reference set, being relevant in automatic summary evaluations.

## Conclusion
This repository provides a detailed overview of key evaluation metrics for classification and generative text models in the context of Deep Learning. By understanding these metrics, users can make informed decisions about the performance of their models and make adjustments to improve the efficiency and quality of predictions.

Additionally, each folder includes a dedicated theory file, named theory.md, which provides a detailed explanation of the concepts associated with evaluation metrics for classification problems or text generative models, respectively. In addition, a notebook of examples named examples.ipynb is included.
