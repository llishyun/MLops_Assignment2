# Summary of 7_Xgboost_categorical_mix

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: binary:logistic
- **eta**: 0.075
- **max_depth**: 8
- **min_child_weight**: 5
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

8.3 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.262023 | nan           |
| auc       | 0.956124 | nan           |
| f1        | 0.869765 |   0.444086    |
| accuracy  | 0.887669 |   0.524691    |
| precision | 0.994975 |   0.98296     |
| recall    | 1        |   0.000302613 |
| mcc       | 0.771126 |   0.524691    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.262023 |  nan        |
| auc       | 0.956124 |  nan        |
| f1        | 0.869104 |    0.524691 |
| accuracy  | 0.887669 |    0.524691 |
| precision | 0.854421 |    0.524691 |
| recall    | 0.884301 |    0.524691 |
| mcc       | 0.771126 |    0.524691 |


## Confusion matrix (at threshold=0.524691)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3281 |              405 |
| Labeled as 1 |              311 |             2377 |

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
