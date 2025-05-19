# Summary of 58_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.7
- **min_samples_split**: 30
- **max_depth**: 6
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

19.2 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.322412 | nan          |
| auc       | 0.933655 | nan          |
| f1        | 0.849179 |   0.461479   |
| accuracy  | 0.861782 |   0.483669   |
| precision | 0.991903 |   0.950503   |
| recall    | 1        |   0.00204626 |
| mcc       | 0.730966 |   0.461479   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.322412 |  nan        |
| auc       | 0.933655 |  nan        |
| f1        | 0.84771  |    0.483669 |
| accuracy  | 0.861782 |    0.483669 |
| precision | 0.791734 |    0.483669 |
| recall    | 0.912202 |    0.483669 |
| mcc       | 0.728414 |    0.483669 |


## Confusion matrix (at threshold=0.483669)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3041 |              645 |
| Labeled as 1 |              236 |             2452 |

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
