# Summary of 20_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.1
- **depth**: 6
- **rsm**: 0.7
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

11.7 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.242435 | nan           |
| auc       | 0.96266  | nan           |
| f1        | 0.880272 |   0.458096    |
| accuracy  | 0.89567  |   0.482303    |
| precision | 0.996923 |   0.983912    |
| recall    | 1        |   4.31764e-06 |
| mcc       | 0.788784 |   0.458096    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.242435 |  nan        |
| auc       | 0.96266  |  nan        |
| f1        | 0.879812 |    0.482303 |
| accuracy  | 0.89567  |    0.482303 |
| precision | 0.855536 |    0.482303 |
| recall    | 0.905506 |    0.482303 |
| mcc       | 0.788765 |    0.482303 |


## Confusion matrix (at threshold=0.482303)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3275 |              411 |
| Labeled as 1 |              254 |             2434 |

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
