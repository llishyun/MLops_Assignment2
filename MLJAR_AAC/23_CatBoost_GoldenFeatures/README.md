# Summary of 23_CatBoost_GoldenFeatures

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

17.8 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.243551 | nan           |
| auc       | 0.962286 | nan           |
| f1        | 0.880721 |   0.427574    |
| accuracy  | 0.894101 |   0.427574    |
| precision | 0.997423 |   0.982607    |
| recall    | 1        |   4.84044e-06 |
| mcc       | 0.789115 |   0.427574    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.243551 |  nan        |
| auc       | 0.962286 |  nan        |
| f1        | 0.880721 |    0.427574 |
| accuracy  | 0.894101 |    0.427574 |
| precision | 0.838775 |    0.427574 |
| recall    | 0.927083 |    0.427574 |
| mcc       | 0.789115 |    0.427574 |


## Confusion matrix (at threshold=0.427574)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3207 |              479 |
| Labeled as 1 |              196 |             2492 |

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
