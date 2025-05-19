# Summary of 18_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.1
- **depth**: 7
- **rsm**: 1.0
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

18.2 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.24038  | nan           |
| auc       | 0.96312  | nan           |
| f1        | 0.880368 |   0.414093    |
| accuracy  | 0.895199 |   0.515357    |
| precision | 0.997783 |   0.979608    |
| recall    | 1        |   2.01071e-06 |
| mcc       | 0.788784 |   0.450792    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.24038  |  nan        |
| auc       | 0.96312  |  nan        |
| f1        | 0.877879 |    0.515357 |
| accuracy  | 0.895199 |    0.515357 |
| precision | 0.863048 |    0.515357 |
| recall    | 0.893229 |    0.515357 |
| mcc       | 0.7865   |    0.515357 |


## Confusion matrix (at threshold=0.515357)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3305 |              381 |
| Labeled as 1 |              287 |             2401 |

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
