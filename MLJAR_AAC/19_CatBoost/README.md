# Summary of 19_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.2
- **depth**: 8
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

13.2 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.243198 | nan           |
| auc       | 0.962087 | nan           |
| f1        | 0.879707 |   0.502923    |
| accuracy  | 0.896768 |   0.502923    |
| precision | 1        |   0.992741    |
| recall    | 1        |   8.14095e-07 |
| mcc       | 0.789702 |   0.502923    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.243198 |  nan        |
| auc       | 0.962087 |  nan        |
| f1        | 0.879707 |    0.502923 |
| accuracy  | 0.896768 |    0.502923 |
| precision | 0.864845 |    0.502923 |
| recall    | 0.895089 |    0.502923 |
| mcc       | 0.789702 |    0.502923 |


## Confusion matrix (at threshold=0.502923)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3310 |              376 |
| Labeled as 1 |              282 |             2406 |

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
