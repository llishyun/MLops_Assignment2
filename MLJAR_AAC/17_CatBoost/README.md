# Summary of 17_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.1
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

17.8 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.241786 | nan           |
| auc       | 0.962774 | nan           |
| f1        | 0.880174 |   0.494583    |
| accuracy  | 0.895984 |   0.494583    |
| precision | 0.996923 |   0.985204    |
| recall    | 1        |   2.55569e-06 |
| mcc       | 0.789404 |   0.494583    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.241786 |  nan        |
| auc       | 0.962774 |  nan        |
| f1        | 0.880174 |    0.494583 |
| accuracy  | 0.895984 |    0.494583 |
| precision | 0.855888 |    0.494583 |
| recall    | 0.905878 |    0.494583 |
| mcc       | 0.789404 |    0.494583 |


## Confusion matrix (at threshold=0.494583)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3276 |              410 |
| Labeled as 1 |              253 |             2435 |

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
