# Summary of 23_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.1
- **depth**: 7
- **rsm**: 0.8
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

13.2 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.243814 | nan           |
| auc       | 0.96205  | nan           |
| f1        | 0.879557 |   0.464918    |
| accuracy  | 0.895356 |   0.495364    |
| precision | 0.996923 |   0.983607    |
| recall    | 1        |   5.69061e-06 |
| mcc       | 0.788126 |   0.495364    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.243814 |  nan        |
| auc       | 0.96205  |  nan        |
| f1        | 0.879451 |    0.495364 |
| accuracy  | 0.895356 |    0.495364 |
| precision | 0.855185 |    0.495364 |
| recall    | 0.905134 |    0.495364 |
| mcc       | 0.788126 |    0.495364 |


## Confusion matrix (at threshold=0.495364)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3274 |              412 |
| Labeled as 1 |              255 |             2433 |

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
