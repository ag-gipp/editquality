# Model tuning report
- Revscoring version: 2.1.0
- Features: editquality.feature_lists.huwiki.goodfaith
- Date: 2018-03-19T05:25:47.374460
- Observations: 39674
- Labels: [true, false]
- Statistic: roc_auc.labels.true (maximize)
- Folds: 5

# Top scoring configurations
| model                  |   roc_auc.labels.true | params                                                                        |
|:-----------------------|----------------------:|:------------------------------------------------------------------------------|
| GradientBoosting       |                0.9841 | learning_rate=0.1, max_features="log2", n_estimators=700, max_depth=7         |
| GradientBoosting       |                0.9829 | learning_rate=0.5, max_features="log2", n_estimators=500, max_depth=5         |
| GradientBoosting       |                0.9819 | learning_rate=0.5, max_features="log2", n_estimators=300, max_depth=7         |
| GradientBoosting       |                0.9814 | learning_rate=0.5, max_features="log2", n_estimators=700, max_depth=7         |
| GradientBoosting       |                0.9814 | learning_rate=0.1, max_features="log2", n_estimators=500, max_depth=7         |
| GradientBoosting       |                0.9809 | learning_rate=0.5, max_features="log2", n_estimators=700, max_depth=5         |
| GradientBoosting       |                0.9807 | learning_rate=0.5, max_features="log2", n_estimators=300, max_depth=5         |
| GradientBoosting       |                0.9806 | learning_rate=0.5, max_features="log2", n_estimators=100, max_depth=7         |
| RandomForestClassifier |                0.9722 | max_features="log2", criterion="entropy", n_estimators=10, min_samples_leaf=1 |
| RandomForestClassifier |                0.9708 | max_features="log2", criterion="gini", n_estimators=10, min_samples_leaf=1    |

# Models
## GaussianNB
| roc_auc.labels.true   | params   |
||

## GradientBoosting
|   roc_auc.labels.true | params                                                                 |
|----------------------:|:-----------------------------------------------------------------------|
|                0.9841 | learning_rate=0.1, max_features="log2", n_estimators=700, max_depth=7  |
|                0.9829 | learning_rate=0.5, max_features="log2", n_estimators=500, max_depth=5  |
|                0.9819 | learning_rate=0.5, max_features="log2", n_estimators=300, max_depth=7  |
|                0.9814 | learning_rate=0.5, max_features="log2", n_estimators=700, max_depth=7  |
|                0.9814 | learning_rate=0.1, max_features="log2", n_estimators=500, max_depth=7  |
|                0.9809 | learning_rate=0.5, max_features="log2", n_estimators=700, max_depth=5  |
|                0.9807 | learning_rate=0.5, max_features="log2", n_estimators=300, max_depth=5  |
|                0.9806 | learning_rate=0.5, max_features="log2", n_estimators=100, max_depth=7  |
|                0.9666 | learning_rate=0.5, max_features="log2", n_estimators=700, max_depth=3  |
|                0.9654 | learning_rate=0.1, max_features="log2", n_estimators=300, max_depth=7  |
|                0.9575 | learning_rate=0.1, max_features="log2", n_estimators=700, max_depth=5  |
|                0.9504 | learning_rate=0.5, max_features="log2", n_estimators=500, max_depth=3  |
|                0.9495 | learning_rate=1, max_features="log2", n_estimators=700, max_depth=3    |
|                0.9483 | learning_rate=0.5, max_features="log2", n_estimators=500, max_depth=7  |
|                0.9432 | learning_rate=0.5, max_features="log2", n_estimators=100, max_depth=5  |
|                0.94   | learning_rate=0.1, max_features="log2", n_estimators=500, max_depth=5  |
|                0.932  | learning_rate=0.1, max_features="log2", n_estimators=500, max_depth=1  |
|                0.9319 | learning_rate=0.1, max_features="log2", n_estimators=700, max_depth=1  |
|                0.931  | learning_rate=1, max_features="log2", n_estimators=100, max_depth=7    |
|                0.9293 | learning_rate=0.01, max_features="log2", n_estimators=700, max_depth=5 |
|                0.9292 | learning_rate=0.1, max_features="log2", n_estimators=300, max_depth=1  |
|                0.9288 | learning_rate=0.1, max_features="log2", n_estimators=100, max_depth=3  |
|                0.9282 | learning_rate=0.01, max_features="log2", n_estimators=700, max_depth=3 |
|                0.9273 | learning_rate=0.01, max_features="log2", n_estimators=500, max_depth=5 |
|                0.9257 | learning_rate=0.5, max_features="log2", n_estimators=300, max_depth=1  |
|                0.9255 | learning_rate=0.01, max_features="log2", n_estimators=500, max_depth=3 |
|                0.9255 | learning_rate=0.5, max_features="log2", n_estimators=300, max_depth=3  |
|                0.9252 | learning_rate=0.01, max_features="log2", n_estimators=500, max_depth=7 |
|                0.9241 | learning_rate=0.01, max_features="log2", n_estimators=300, max_depth=5 |
|                0.9236 | learning_rate=0.01, max_features="log2", n_estimators=700, max_depth=7 |
|                0.9226 | learning_rate=0.1, max_features="log2", n_estimators=300, max_depth=3  |
|                0.9226 | learning_rate=0.01, max_features="log2", n_estimators=300, max_depth=3 |
|                0.9225 | learning_rate=0.5, max_features="log2", n_estimators=500, max_depth=1  |
|                0.9221 | learning_rate=0.01, max_features="log2", n_estimators=300, max_depth=7 |
|                0.922  | learning_rate=0.5, max_features="log2", n_estimators=100, max_depth=1  |
|                0.9209 | learning_rate=0.1, max_features="log2", n_estimators=100, max_depth=1  |
|                0.9209 | learning_rate=0.1, max_features="log2", n_estimators=100, max_depth=5  |
|                0.9207 | learning_rate=0.01, max_features="log2", n_estimators=100, max_depth=7 |
|                0.9188 | learning_rate=0.5, max_features="log2", n_estimators=700, max_depth=1  |
|                0.9186 | learning_rate=0.1, max_features="log2", n_estimators=500, max_depth=3  |
|                0.9181 | learning_rate=0.1, max_features="log2", n_estimators=300, max_depth=5  |
|                0.9168 | learning_rate=0.01, max_features="log2", n_estimators=100, max_depth=5 |
|                0.9166 | learning_rate=0.01, max_features="log2", n_estimators=700, max_depth=1 |
|                0.9154 | learning_rate=0.1, max_features="log2", n_estimators=700, max_depth=3  |
|                0.9151 | learning_rate=0.01, max_features="log2", n_estimators=100, max_depth=3 |
|                0.9131 | learning_rate=0.01, max_features="log2", n_estimators=500, max_depth=1 |
|                0.9122 | learning_rate=1, max_features="log2", n_estimators=300, max_depth=1    |
|                0.9102 | learning_rate=0.01, max_features="log2", n_estimators=300, max_depth=1 |
|                0.906  | learning_rate=0.1, max_features="log2", n_estimators=100, max_depth=7  |
|                0.9045 | learning_rate=1, max_features="log2", n_estimators=700, max_depth=5    |
|                0.9025 | learning_rate=0.01, max_features="log2", n_estimators=100, max_depth=1 |
|                0.8926 | learning_rate=0.5, max_features="log2", n_estimators=100, max_depth=3  |
|                0.878  | learning_rate=1, max_features="log2", n_estimators=100, max_depth=5    |
|                0.8756 | learning_rate=1, max_features="log2", n_estimators=300, max_depth=7    |
|                0.8736 | learning_rate=1, max_features="log2", n_estimators=700, max_depth=7    |
|                0.8734 | learning_rate=1, max_features="log2", n_estimators=100, max_depth=1    |
|                0.866  | learning_rate=1, max_features="log2", n_estimators=300, max_depth=3    |
|                0.8558 | learning_rate=1, max_features="log2", n_estimators=500, max_depth=3    |
|                0.8511 | learning_rate=1, max_features="log2", n_estimators=500, max_depth=7    |
|                0.844  | learning_rate=1, max_features="log2", n_estimators=100, max_depth=3    |
|                0.8325 | learning_rate=1, max_features="log2", n_estimators=500, max_depth=5    |
|                0.8114 | learning_rate=1, max_features="log2", n_estimators=300, max_depth=5    |
|                0.7612 | learning_rate=1, max_features="log2", n_estimators=500, max_depth=1    |
|                0.6645 | learning_rate=1, max_features="log2", n_estimators=700, max_depth=1    |

## BernoulliNB
|   roc_auc.labels.true | params   |
|----------------------:|:---------|
|                0.8735 |          |

## RandomForestClassifier
|   roc_auc.labels.true | params                                                                          |
|----------------------:|:--------------------------------------------------------------------------------|
|                0.9722 | max_features="log2", criterion="entropy", n_estimators=10, min_samples_leaf=1   |
|                0.9708 | max_features="log2", criterion="gini", n_estimators=10, min_samples_leaf=1      |
|                0.9626 | max_features="log2", criterion="gini", n_estimators=20, min_samples_leaf=1      |
|                0.9623 | max_features="log2", criterion="entropy", n_estimators=20, min_samples_leaf=1   |
|                0.9536 | max_features="log2", criterion="entropy", n_estimators=10, min_samples_leaf=3   |
|                0.9534 | max_features="log2", criterion="entropy", n_estimators=40, min_samples_leaf=1   |
|                0.9507 | max_features="log2", criterion="gini", n_estimators=40, min_samples_leaf=1      |
|                0.9487 | max_features="log2", criterion="gini", n_estimators=10, min_samples_leaf=3      |
|                0.9466 | max_features="log2", criterion="entropy", n_estimators=80, min_samples_leaf=1   |
|                0.945  | max_features="log2", criterion="entropy", n_estimators=20, min_samples_leaf=3   |
|                0.9447 | max_features="log2", criterion="gini", n_estimators=80, min_samples_leaf=1      |
|                0.9439 | max_features="log2", criterion="entropy", n_estimators=160, min_samples_leaf=1  |
|                0.9432 | max_features="log2", criterion="entropy", n_estimators=10, min_samples_leaf=7   |
|                0.9412 | max_features="log2", criterion="entropy", n_estimators=10, min_samples_leaf=5   |
|                0.9404 | max_features="log2", criterion="gini", n_estimators=20, min_samples_leaf=3      |
|                0.9399 | max_features="log2", criterion="entropy", n_estimators=20, min_samples_leaf=5   |
|                0.9392 | max_features="log2", criterion="gini", n_estimators=10, min_samples_leaf=7      |
|                0.9389 | max_features="log2", criterion="gini", n_estimators=10, min_samples_leaf=5      |
|                0.9365 | max_features="log2", criterion="gini", n_estimators=160, min_samples_leaf=1     |
|                0.9346 | max_features="log2", criterion="entropy", n_estimators=40, min_samples_leaf=3   |
|                0.9333 | max_features="log2", criterion="entropy", n_estimators=10, min_samples_leaf=13  |
|                0.932  | max_features="log2", criterion="gini", n_estimators=20, min_samples_leaf=5      |
|                0.9317 | max_features="log2", criterion="entropy", n_estimators=320, min_samples_leaf=1  |
|                0.9297 | max_features="log2", criterion="gini", n_estimators=40, min_samples_leaf=3      |
|                0.9296 | max_features="log2", criterion="entropy", n_estimators=20, min_samples_leaf=7   |
|                0.9288 | max_features="log2", criterion="entropy", n_estimators=40, min_samples_leaf=7   |
|                0.9283 | max_features="log2", criterion="gini", n_estimators=80, min_samples_leaf=3      |
|                0.9283 | max_features="log2", criterion="entropy", n_estimators=40, min_samples_leaf=5   |
|                0.9279 | max_features="log2", criterion="gini", n_estimators=20, min_samples_leaf=7      |
|                0.9272 | max_features="log2", criterion="gini", n_estimators=10, min_samples_leaf=13     |
|                0.9271 | max_features="log2", criterion="entropy", n_estimators=640, min_samples_leaf=1  |
|                0.9265 | max_features="log2", criterion="entropy", n_estimators=80, min_samples_leaf=3   |
|                0.9258 | max_features="log2", criterion="gini", n_estimators=320, min_samples_leaf=1     |
|                0.924  | max_features="log2", criterion="entropy", n_estimators=640, min_samples_leaf=13 |
|                0.9235 | max_features="log2", criterion="entropy", n_estimators=160, min_samples_leaf=3  |
|                0.9234 | max_features="log2", criterion="gini", n_estimators=640, min_samples_leaf=1     |
|                0.9232 | max_features="log2", criterion="entropy", n_estimators=80, min_samples_leaf=7   |
|                0.9228 | max_features="log2", criterion="gini", n_estimators=640, min_samples_leaf=7     |
|                0.9222 | max_features="log2", criterion="entropy", n_estimators=320, min_samples_leaf=5  |
|                0.9221 | max_features="log2", criterion="gini", n_estimators=160, min_samples_leaf=3     |
|                0.922  | max_features="log2", criterion="gini", n_estimators=160, min_samples_leaf=13    |
|                0.9216 | max_features="log2", criterion="entropy", n_estimators=640, min_samples_leaf=7  |
|                0.9214 | max_features="log2", criterion="entropy", n_estimators=320, min_samples_leaf=3  |
|                0.9213 | max_features="log2", criterion="entropy", n_estimators=160, min_samples_leaf=7  |
|                0.9212 | max_features="log2", criterion="entropy", n_estimators=160, min_samples_leaf=13 |
|                0.9211 | max_features="log2", criterion="gini", n_estimators=40, min_samples_leaf=13     |
|                0.9211 | max_features="log2", criterion="entropy", n_estimators=320, min_samples_leaf=13 |
|                0.9211 | max_features="log2", criterion="entropy", n_estimators=80, min_samples_leaf=13  |
|                0.9209 | max_features="log2", criterion="gini", n_estimators=80, min_samples_leaf=5      |
|                0.9209 | max_features="log2", criterion="gini", n_estimators=320, min_samples_leaf=3     |
|                0.9208 | max_features="log2", criterion="gini", n_estimators=40, min_samples_leaf=7      |
|                0.9206 | max_features="log2", criterion="gini", n_estimators=320, min_samples_leaf=13    |
|                0.9204 | max_features="log2", criterion="gini", n_estimators=640, min_samples_leaf=13    |
|                0.9204 | max_features="log2", criterion="entropy", n_estimators=40, min_samples_leaf=13  |
|                0.9203 | max_features="log2", criterion="gini", n_estimators=40, min_samples_leaf=5      |
|                0.9203 | max_features="log2", criterion="entropy", n_estimators=640, min_samples_leaf=5  |
|                0.9198 | max_features="log2", criterion="gini", n_estimators=80, min_samples_leaf=13     |
|                0.9198 | max_features="log2", criterion="entropy", n_estimators=80, min_samples_leaf=5   |
|                0.9197 | max_features="log2", criterion="entropy", n_estimators=20, min_samples_leaf=13  |
|                0.9195 | max_features="log2", criterion="entropy", n_estimators=160, min_samples_leaf=5  |
|                0.9191 | max_features="log2", criterion="gini", n_estimators=320, min_samples_leaf=5     |
|                0.9189 | max_features="log2", criterion="gini", n_estimators=320, min_samples_leaf=7     |
|                0.9188 | max_features="log2", criterion="gini", n_estimators=640, min_samples_leaf=5     |
|                0.9184 | max_features="log2", criterion="entropy", n_estimators=320, min_samples_leaf=7  |
|                0.9181 | max_features="log2", criterion="entropy", n_estimators=640, min_samples_leaf=3  |
|                0.918  | max_features="log2", criterion="gini", n_estimators=20, min_samples_leaf=13     |
|                0.9177 | max_features="log2", criterion="gini", n_estimators=160, min_samples_leaf=7     |
|                0.9164 | max_features="log2", criterion="gini", n_estimators=80, min_samples_leaf=7      |
|                0.914  | max_features="log2", criterion="gini", n_estimators=640, min_samples_leaf=3     |
|                0.9101 | max_features="log2", criterion="gini", n_estimators=160, min_samples_leaf=5     |

## LogisticRegression
|   roc_auc.labels.true | params              |
|----------------------:|:--------------------|
|                0.9361 | C=10, penalty="l1"  |
|                0.9342 | C=1, penalty="l1"   |
|                0.9257 | C=0.1, penalty="l1" |
|                0.779  | C=1, penalty="l2"   |
|                0.7338 | C=0.1, penalty="l2" |
|                0.7293 | C=10, penalty="l2"  |

