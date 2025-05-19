# Summary of 53_Xgboost

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.075
- **max_depth**: 8
- **min_child_weight**: 1
- **subsample**: 1.0
- **colsample_bytree**: 1.0
- **eval_metric**: f1
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.9
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
f1

## Training time

9.7 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.25805  | nan           |
| auc       | 0.957439 | nan           |
| f1        | 0.871137 |   0.486449    |
| accuracy  | 0.888924 |   0.514207    |
| precision | 1        |   0.98491     |
| recall    | 1        |   6.87531e-05 |
| mcc       | 0.773688 |   0.514207    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.25805  |  nan        |
| auc       | 0.957439 |  nan        |
| f1        | 0.870567 |    0.514207 |
| accuracy  | 0.888924 |    0.514207 |
| precision | 0.855859 |    0.514207 |
| recall    | 0.885789 |    0.514207 |
| mcc       | 0.773688 |    0.514207 |


## Confusion matrix (at threshold=0.514207)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3285 |              401 |
| Labeled as 1 |              307 |             2381 |

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
