# Summary of 25_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.5
- **min_samples_split**: 20
- **max_depth**: 4
- **eval_metric_name**: f1
- **explain_level**: 0

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.9
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
f1

## Training time

18.5 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.361178 | nan         |
| auc       | 0.92211  | nan         |
| f1        | 0.8344   |   0.500414  |
| accuracy  | 0.849859 |   0.500414  |
| precision | 0.980392 |   0.901457  |
| recall    | 1        |   0.0047191 |
| mcc       | 0.704    |   0.500414  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.361178 |  nan        |
| auc       | 0.92211  |  nan        |
| f1        | 0.8344   |    0.500414 |
| accuracy  | 0.849859 |    0.500414 |
| precision | 0.780006 |    0.500414 |
| recall    | 0.896949 |    0.500414 |
| mcc       | 0.704    |    0.500414 |


## Confusion matrix (at threshold=0.500414)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |             3006 |              680 |
| Labeled as 1 |              277 |             2411 |

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
