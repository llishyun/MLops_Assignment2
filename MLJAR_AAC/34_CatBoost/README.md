# Summary of 34_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.05
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

23.0 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.243042 | nan           |
| auc       | 0.962375 | nan           |
| f1        | 0.879661 |   0.430807    |
| accuracy  | 0.895827 |   0.569461    |
| precision | 1        |   0.99199     |
| recall    | 1        |   4.36193e-06 |
| mcc       | 0.787205 |   0.430807    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.243042 |  nan        |
| auc       | 0.962375 |  nan        |
| f1        | 0.875749 |    0.569461 |
| accuracy  | 0.895827 |    0.569461 |
| precision | 0.881024 |    0.569461 |
| recall    | 0.870536 |    0.569461 |
| mcc       | 0.786115 |    0.569461 |


## Confusion matrix (at threshold=0.569461)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3370 |              316 |
| Labeled as 1 |              348 |             2340 |

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
