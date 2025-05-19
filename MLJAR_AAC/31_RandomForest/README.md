# Summary of 31_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.9
- **min_samples_split**: 40
- **max_depth**: 5
- **eval_metric_name**: f1
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.9
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
f1

## Training time

27.0 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.34034  | nan          |
| auc       | 0.92469  | nan          |
| f1        | 0.836226 |   0.438025   |
| accuracy  | 0.852055 |   0.485411   |
| precision | 0.987654 |   0.934226   |
| recall    | 1        |   0.00270275 |
| mcc       | 0.70705  |   0.438025   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.34034  |  nan        |
| auc       | 0.92469  |  nan        |
| f1        | 0.833363 |    0.485411 |
| accuracy  | 0.852055 |    0.485411 |
| precision | 0.793672 |    0.485411 |
| recall    | 0.877232 |    0.485411 |
| mcc       | 0.703777 |    0.485411 |


## Confusion matrix (at threshold=0.485411)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3073 |              613 |
| Labeled as 1 |              330 |             2358 |

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
