# Summary of 56_Xgboost

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.1
- **max_depth**: 8
- **min_child_weight**: 5
- **subsample**: 1.0
- **colsample_bytree**: 0.9
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

7.1 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.261419 | nan           |
| auc       | 0.956275 | nan           |
| f1        | 0.870052 |   0.498168    |
| accuracy  | 0.887198 |   0.498168    |
| precision | 0.994975 |   0.983152    |
| recall    | 1        |   0.000298326 |
| mcc       | 0.77151  |   0.498168    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.261419 |  nan        |
| auc       | 0.956275 |  nan        |
| f1        | 0.870052 |    0.498168 |
| accuracy  | 0.887198 |    0.498168 |
| precision | 0.846046 |    0.498168 |
| recall    | 0.895461 |    0.498168 |
| mcc       | 0.77151  |    0.498168 |


## Confusion matrix (at threshold=0.498168)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3248 |              438 |
| Labeled as 1 |              281 |             2407 |

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
