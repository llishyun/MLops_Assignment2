# Summary of 50_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.1
- **depth**: 7
- **rsm**: 0.9
- **loss_function**: Logloss
- **eval_metric**: F1
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.9
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
f1

## Training time

14.6 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.244311 | nan           |
| auc       | 0.961866 | nan           |
| f1        | 0.881074 |   0.431611    |
| accuracy  | 0.895513 |   0.458382    |
| precision | 1        |   0.992657    |
| recall    | 1        |   3.95371e-06 |
| mcc       | 0.790059 |   0.458382    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.244311 |  nan        |
| auc       | 0.961866 |  nan        |
| f1        | 0.880986 |    0.458382 |
| accuracy  | 0.895513 |    0.458382 |
| precision | 0.847662 |    0.458382 |
| recall    | 0.917039 |    0.458382 |
| mcc       | 0.790059 |    0.458382 |


## Confusion matrix (at threshold=0.458382)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3243 |              443 |
| Labeled as 1 |              223 |             2465 |

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
