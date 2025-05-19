# Summary of 52_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.1
- **depth**: 7
- **rsm**: 0.9
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

15.5 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.244593 | nan           |
| auc       | 0.961869 | nan           |
| f1        | 0.877879 |   0.506126    |
| accuracy  | 0.895356 |   0.533549    |
| precision | 0.996183 |   0.985696    |
| recall    | 1        |   7.69786e-06 |
| mcc       | 0.7865   |   0.506126    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.244593 |  nan        |
| auc       | 0.961869 |  nan        |
| f1        | 0.876641 |    0.533549 |
| accuracy  | 0.895356 |    0.533549 |
| precision | 0.871644 |    0.533549 |
| recall    | 0.881696 |    0.533549 |
| mcc       | 0.785826 |    0.533549 |


## Confusion matrix (at threshold=0.533549)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3337 |              349 |
| Labeled as 1 |              318 |             2370 |

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
