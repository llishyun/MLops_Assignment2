# Summary of 19_CatBoost_GoldenFeatures

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

11.4 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.244004 | nan           |
| auc       | 0.961918 | nan           |
| f1        | 0.879661 |   0.436688    |
| accuracy  | 0.894415 |   0.493405    |
| precision | 1        |   0.993837    |
| recall    | 1        |   2.93771e-06 |
| mcc       | 0.787205 |   0.436688    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.244004 |  nan        |
| auc       | 0.961918 |  nan        |
| f1        | 0.878366 |    0.493405 |
| accuracy  | 0.894415 |    0.493405 |
| precision | 0.85413  |    0.493405 |
| recall    | 0.904018 |    0.493405 |
| mcc       | 0.786208 |    0.493405 |


## Confusion matrix (at threshold=0.493405)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3271 |              415 |
| Labeled as 1 |              258 |             2430 |

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
