# Evaluation Metrics for the Classification Problem
## Types of Prediction Errors
- False Positive (FP)
- False Negative (FN)
- True Positive (TP)
- True Negative (TN)

<img src = "Images/d1.png" alt = "d1" width = "600"/>

## Accuracy

$$\Huge \text{Accuracy} = \frac{\text{number of correct predictions}}{\text{number of correct predictions}}$$

- Useful when the number of samples is balanced

<img src = "Images/d4.png" alt = "d4" width = "600"/>

## Confusion Matrix

A table that helps to visualize the performance of a classification algorithm

<img src = "Images/d5.png" alt = "d5" width = "600"/>

## Precision and Recall

Precision and Recall metrics are relatively much more appropriate (especially compared to accuracy) when dealing with imbalanced classes.

$$\Huge \text{Precision} = \frac{TP}{TP+FP}$$

<img src = "Images/d2.png" alt = "d2" width = "600"/>

$$\Huge \text{Recall} = \frac{TP}{TP+FN}$$

<img src = "Images/d3.png" alt = "d3" width = "600"/>

## F1 Score

Weighted average of the precision and recall.

$$\Huge F1 \text{ score} = 2 \frac{\text{Precision} \times \text{Recall}}{\text{Precision} + \text{Recall}}$$

F1 Score = Harmonic mean of Precision and Recall
