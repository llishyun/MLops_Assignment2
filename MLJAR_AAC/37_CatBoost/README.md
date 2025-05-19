# Summary of 37_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.05
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

20.4 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.247341 | nan           |
| auc       | 0.961123 | nan           |
| f1        | 0.876833 |   0.421449    |
| accuracy  | 0.892846 |   0.480127    |
| precision | 0.996183 |   0.983377    |
| recall    | 1        |   1.32269e-05 |
| mcc       | 0.783013 |   0.480127    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.247341 |  nan        |
| auc       | 0.961123 |  nan        |
| f1        | 0.876559 |    0.480127 |
| accuracy  | 0.892846 |    0.480127 |
| precision | 0.852373 |    0.480127 |
| recall    | 0.902158 |    0.480127 |
| mcc       | 0.783013 |    0.480127 |


## Confusion matrix (at threshold=0.480127)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3266 |              420 |
| Labeled as 1 |              263 |             2425 |

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
