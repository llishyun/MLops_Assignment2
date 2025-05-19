# Summary of 1_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: gini
- **max_depth**: 3
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.9
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
f1

## Training time

4.1 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.392128 | nan          |
| auc       | 0.883808 | nan          |
| f1        | 0.808078 |   0.298161   |
| accuracy  | 0.810637 |   0.298161   |
| precision | 0.811137 |   0.598013   |
| recall    | 1        |   0.00587886 |
| mcc       | 0.655177 |   0.298161   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.392128 |  nan        |
| auc       | 0.883808 |  nan        |
| f1        | 0.808078 |    0.298161 |
| accuracy  | 0.810637 |    0.298161 |
| precision | 0.705637 |    0.298161 |
| recall    | 0.945312 |    0.298161 |
| mcc       | 0.655177 |    0.298161 |


## Confusion matrix (at threshold=0.298161)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             2626 |             1060 |
| Labeled as 1 |              147 |             2541 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
