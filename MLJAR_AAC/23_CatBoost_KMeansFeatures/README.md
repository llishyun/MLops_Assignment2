# Summary of 23_CatBoost_KMeansFeatures

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

17.2 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.24367  | nan          |
| auc       | 0.962198 | nan          |
| f1        | 0.879199 |   0.461578   |
| accuracy  | 0.895042 |   0.489409   |
| precision | 0.996923 |   0.985198   |
| recall    | 1        |   4.4245e-06 |
| mcc       | 0.787487 |   0.489409   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.24367  |  nan        |
| auc       | 0.962198 |  nan        |
| f1        | 0.879089 |    0.489409 |
| accuracy  | 0.895042 |    0.489409 |
| precision | 0.854833 |    0.489409 |
| recall    | 0.904762 |    0.489409 |
| mcc       | 0.787487 |    0.489409 |


## Confusion matrix (at threshold=0.489409)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3273 |              413 |
| Labeled as 1 |              256 |             2432 |

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
