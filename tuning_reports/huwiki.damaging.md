# Model tuning report
- Revscoring version: 2.1.0
- Features: editquality.feature_lists.huwiki.damaging
- Date: 2018-03-19T05:10:29.816655
- Observations: 39674
- Labels: [true, false]
- Statistic: roc_auc.labels.true (maximize)
- Folds: 5

# Top scoring configurations
| model                  |   roc_auc.labels.true | params                                                                          |
|:-----------------------|----------------------:|:--------------------------------------------------------------------------------|
| GradientBoosting       |                0.9344 | max_depth=3, n_estimators=300, learning_rate=0.1, max_features="log2"           |
| GradientBoosting       |                0.9339 | max_depth=5, n_estimators=700, learning_rate=0.01, max_features="log2"          |
| GradientBoosting       |                0.9336 | max_depth=3, n_estimators=700, learning_rate=0.01, max_features="log2"          |
| GradientBoosting       |                0.9333 | max_depth=5, n_estimators=500, learning_rate=0.01, max_features="log2"          |
| RandomForestClassifier |                0.9327 | n_estimators=640, criterion="entropy", min_samples_leaf=13, max_features="log2" |
| GradientBoosting       |                0.9326 | max_depth=3, n_estimators=100, learning_rate=0.1, max_features="log2"           |
| GradientBoosting       |                0.9326 | max_depth=7, n_estimators=700, learning_rate=0.01, max_features="log2"          |
| GradientBoosting       |                0.9326 | max_depth=1, n_estimators=500, learning_rate=0.1, max_features="log2"           |
| GradientBoosting       |                0.9325 | max_depth=7, n_estimators=500, learning_rate=0.01, max_features="log2"          |
| GradientBoosting       |                0.9324 | max_depth=7, n_estimators=300, learning_rate=0.01, max_features="log2"          |

# Models
## BernoulliNB
|   roc_auc.labels.true | params   |
|----------------------:|:---------|
|                0.8433 |          |

## GaussianNB
| roc_auc.labels.true   | params   |
||

## RandomForestClassifier
|   roc_auc.labels.true | params                                                                          |
|----------------------:|:--------------------------------------------------------------------------------|
|                0.9327 | n_estimators=640, criterion="entropy", min_samples_leaf=13, max_features="log2" |
|                0.932  | n_estimators=320, criterion="entropy", min_samples_leaf=13, max_features="log2" |
|                0.9317 | n_estimators=160, criterion="entropy", min_samples_leaf=13, max_features="log2" |
|                0.9315 | n_estimators=80, criterion="entropy", min_samples_leaf=13, max_features="log2"  |
|                0.9312 | n_estimators=320, criterion="entropy", min_samples_leaf=5, max_features="log2"  |
|                0.9306 | n_estimators=640, criterion="entropy", min_samples_leaf=5, max_features="log2"  |
|                0.9299 | n_estimators=640, criterion="gini", min_samples_leaf=13, max_features="log2"    |
|                0.9298 | n_estimators=160, criterion="entropy", min_samples_leaf=5, max_features="log2"  |
|                0.9296 | n_estimators=640, criterion="entropy", min_samples_leaf=7, max_features="log2"  |
|                0.9292 | n_estimators=320, criterion="entropy", min_samples_leaf=7, max_features="log2"  |
|                0.9288 | n_estimators=640, criterion="gini", min_samples_leaf=5, max_features="log2"     |
|                0.9286 | n_estimators=320, criterion="gini", min_samples_leaf=7, max_features="log2"     |
|                0.9282 | n_estimators=640, criterion="entropy", min_samples_leaf=3, max_features="log2"  |
|                0.9282 | n_estimators=640, criterion="gini", min_samples_leaf=7, max_features="log2"     |
|                0.9281 | n_estimators=80, criterion="entropy", min_samples_leaf=7, max_features="log2"   |
|                0.9279 | n_estimators=640, criterion="gini", min_samples_leaf=3, max_features="log2"     |
|                0.9277 | n_estimators=160, criterion="gini", min_samples_leaf=5, max_features="log2"     |
|                0.9276 | n_estimators=40, criterion="entropy", min_samples_leaf=13, max_features="log2"  |
|                0.9275 | n_estimators=320, criterion="gini", min_samples_leaf=13, max_features="log2"    |
|                0.9273 | n_estimators=640, criterion="entropy", min_samples_leaf=1, max_features="log2"  |
|                0.9269 | n_estimators=80, criterion="gini", min_samples_leaf=13, max_features="log2"     |
|                0.9267 | n_estimators=320, criterion="gini", min_samples_leaf=5, max_features="log2"     |
|                0.9266 | n_estimators=160, criterion="gini", min_samples_leaf=13, max_features="log2"    |
|                0.926  | n_estimators=160, criterion="gini", min_samples_leaf=7, max_features="log2"     |
|                0.9255 | n_estimators=320, criterion="entropy", min_samples_leaf=3, max_features="log2"  |
|                0.9251 | n_estimators=160, criterion="gini", min_samples_leaf=3, max_features="log2"     |
|                0.9245 | n_estimators=640, criterion="gini", min_samples_leaf=1, max_features="log2"     |
|                0.9243 | n_estimators=320, criterion="gini", min_samples_leaf=3, max_features="log2"     |
|                0.9241 | n_estimators=80, criterion="entropy", min_samples_leaf=5, max_features="log2"   |
|                0.9237 | n_estimators=80, criterion="gini", min_samples_leaf=7, max_features="log2"      |
|                0.9234 | n_estimators=40, criterion="gini", min_samples_leaf=7, max_features="log2"      |
|                0.9233 | n_estimators=160, criterion="entropy", min_samples_leaf=7, max_features="log2"  |
|                0.922  | n_estimators=40, criterion="gini", min_samples_leaf=13, max_features="log2"     |
|                0.9219 | n_estimators=80, criterion="gini", min_samples_leaf=5, max_features="log2"      |
|                0.9211 | n_estimators=40, criterion="entropy", min_samples_leaf=7, max_features="log2"   |
|                0.9208 | n_estimators=160, criterion="entropy", min_samples_leaf=3, max_features="log2"  |
|                0.9198 | n_estimators=320, criterion="gini", min_samples_leaf=1, max_features="log2"     |
|                0.9194 | n_estimators=40, criterion="entropy", min_samples_leaf=5, max_features="log2"   |
|                0.9193 | n_estimators=320, criterion="entropy", min_samples_leaf=1, max_features="log2"  |
|                0.9176 | n_estimators=160, criterion="gini", min_samples_leaf=1, max_features="log2"     |
|                0.9166 | n_estimators=20, criterion="entropy", min_samples_leaf=13, max_features="log2"  |
|                0.9161 | n_estimators=80, criterion="gini", min_samples_leaf=3, max_features="log2"      |
|                0.9158 | n_estimators=80, criterion="entropy", min_samples_leaf=3, max_features="log2"   |
|                0.9137 | n_estimators=20, criterion="gini", min_samples_leaf=7, max_features="log2"      |
|                0.9113 | n_estimators=20, criterion="gini", min_samples_leaf=13, max_features="log2"     |
|                0.911  | n_estimators=20, criterion="entropy", min_samples_leaf=7, max_features="log2"   |
|                0.9093 | n_estimators=40, criterion="gini", min_samples_leaf=5, max_features="log2"      |
|                0.9088 | n_estimators=40, criterion="entropy", min_samples_leaf=3, max_features="log2"   |
|                0.9061 | n_estimators=20, criterion="entropy", min_samples_leaf=5, max_features="log2"   |
|                0.9044 | n_estimators=160, criterion="entropy", min_samples_leaf=1, max_features="log2"  |
|                0.9039 | n_estimators=10, criterion="entropy", min_samples_leaf=13, max_features="log2"  |
|                0.8978 | n_estimators=80, criterion="entropy", min_samples_leaf=1, max_features="log2"   |
|                0.8976 | n_estimators=20, criterion="gini", min_samples_leaf=5, max_features="log2"      |
|                0.8973 | n_estimators=10, criterion="gini", min_samples_leaf=13, max_features="log2"     |
|                0.8966 | n_estimators=80, criterion="gini", min_samples_leaf=1, max_features="log2"      |
|                0.8962 | n_estimators=40, criterion="gini", min_samples_leaf=3, max_features="log2"      |
|                0.8905 | n_estimators=20, criterion="gini", min_samples_leaf=3, max_features="log2"      |
|                0.889  | n_estimators=10, criterion="gini", min_samples_leaf=7, max_features="log2"      |
|                0.8888 | n_estimators=20, criterion="entropy", min_samples_leaf=3, max_features="log2"   |
|                0.8838 | n_estimators=10, criterion="entropy", min_samples_leaf=7, max_features="log2"   |
|                0.8838 | n_estimators=40, criterion="entropy", min_samples_leaf=1, max_features="log2"   |
|                0.88   | n_estimators=10, criterion="gini", min_samples_leaf=5, max_features="log2"      |
|                0.8795 | n_estimators=10, criterion="entropy", min_samples_leaf=5, max_features="log2"   |
|                0.874  | n_estimators=40, criterion="gini", min_samples_leaf=1, max_features="log2"      |
|                0.8635 | n_estimators=10, criterion="entropy", min_samples_leaf=3, max_features="log2"   |
|                0.8619 | n_estimators=10, criterion="gini", min_samples_leaf=3, max_features="log2"      |
|                0.8393 | n_estimators=20, criterion="entropy", min_samples_leaf=1, max_features="log2"   |
|                0.8318 | n_estimators=20, criterion="gini", min_samples_leaf=1, max_features="log2"      |
|                0.7806 | n_estimators=10, criterion="entropy", min_samples_leaf=1, max_features="log2"   |
|                0.7799 | n_estimators=10, criterion="gini", min_samples_leaf=1, max_features="log2"      |

## LogisticRegression
|   roc_auc.labels.true | params              |
|----------------------:|:--------------------|
|                0.9196 | C=10, penalty="l1"  |
|                0.919  | C=1, penalty="l1"   |
|                0.9168 | C=0.1, penalty="l1" |
|                0.7768 | C=1, penalty="l2"   |
|                0.774  | C=0.1, penalty="l2" |
|                0.7635 | C=10, penalty="l2"  |

## GradientBoosting
|   roc_auc.labels.true | params                                                                 |
|----------------------:|:-----------------------------------------------------------------------|
|                0.9344 | max_depth=3, n_estimators=300, learning_rate=0.1, max_features="log2"  |
|                0.9339 | max_depth=5, n_estimators=700, learning_rate=0.01, max_features="log2" |
|                0.9336 | max_depth=3, n_estimators=700, learning_rate=0.01, max_features="log2" |
|                0.9333 | max_depth=5, n_estimators=500, learning_rate=0.01, max_features="log2" |
|                0.9326 | max_depth=3, n_estimators=100, learning_rate=0.1, max_features="log2"  |
|                0.9326 | max_depth=7, n_estimators=700, learning_rate=0.01, max_features="log2" |
|                0.9326 | max_depth=1, n_estimators=500, learning_rate=0.1, max_features="log2"  |
|                0.9325 | max_depth=7, n_estimators=500, learning_rate=0.01, max_features="log2" |
|                0.9324 | max_depth=7, n_estimators=300, learning_rate=0.01, max_features="log2" |
|                0.932  | max_depth=1, n_estimators=300, learning_rate=0.1, max_features="log2"  |
|                0.9313 | max_depth=1, n_estimators=700, learning_rate=0.1, max_features="log2"  |
|                0.9312 | max_depth=3, n_estimators=500, learning_rate=0.01, max_features="log2" |
|                0.9311 | max_depth=5, n_estimators=300, learning_rate=0.01, max_features="log2" |
|                0.9293 | max_depth=1, n_estimators=300, learning_rate=0.5, max_features="log2"  |
|                0.9283 | max_depth=5, n_estimators=100, learning_rate=0.1, max_features="log2"  |
|                0.9279 | max_depth=3, n_estimators=500, learning_rate=0.1, max_features="log2"  |
|                0.9272 | max_depth=7, n_estimators=100, learning_rate=0.01, max_features="log2" |
|                0.926  | max_depth=7, n_estimators=100, learning_rate=0.1, max_features="log2"  |
|                0.9259 | max_depth=5, n_estimators=100, learning_rate=0.01, max_features="log2" |
|                0.9256 | max_depth=3, n_estimators=300, learning_rate=0.01, max_features="log2" |
|                0.9236 | max_depth=1, n_estimators=500, learning_rate=0.5, max_features="log2"  |
|                0.9233 | max_depth=1, n_estimators=100, learning_rate=0.5, max_features="log2"  |
|                0.9232 | max_depth=1, n_estimators=100, learning_rate=0.1, max_features="log2"  |
|                0.923  | max_depth=3, n_estimators=700, learning_rate=0.1, max_features="log2"  |
|                0.92   | max_depth=1, n_estimators=700, learning_rate=0.01, max_features="log2" |
|                0.9189 | max_depth=1, n_estimators=700, learning_rate=0.5, max_features="log2"  |
|                0.918  | max_depth=3, n_estimators=100, learning_rate=0.01, max_features="log2" |
|                0.9175 | max_depth=5, n_estimators=300, learning_rate=0.1, max_features="log2"  |
|                0.916  | max_depth=1, n_estimators=500, learning_rate=0.01, max_features="log2" |
|                0.9138 | max_depth=1, n_estimators=500, learning_rate=1, max_features="log2"    |
|                0.9112 | max_depth=5, n_estimators=500, learning_rate=0.1, max_features="log2"  |
|                0.9097 | max_depth=1, n_estimators=300, learning_rate=0.01, max_features="log2" |
|                0.9072 | max_depth=3, n_estimators=100, learning_rate=0.5, max_features="log2"  |
|                0.9062 | max_depth=1, n_estimators=300, learning_rate=1, max_features="log2"    |
|                0.9038 | max_depth=1, n_estimators=100, learning_rate=0.01, max_features="log2" |
|                0.8985 | max_depth=5, n_estimators=700, learning_rate=0.1, max_features="log2"  |
|                0.8985 | max_depth=7, n_estimators=300, learning_rate=0.1, max_features="log2"  |
|                0.8869 | max_depth=1, n_estimators=700, learning_rate=1, max_features="log2"    |
|                0.8821 | max_depth=3, n_estimators=300, learning_rate=0.5, max_features="log2"  |
|                0.8792 | max_depth=3, n_estimators=500, learning_rate=0.5, max_features="log2"  |
|                0.8765 | max_depth=5, n_estimators=100, learning_rate=0.5, max_features="log2"  |
|                0.8496 | max_depth=3, n_estimators=700, learning_rate=0.5, max_features="log2"  |
|                0.8395 | max_depth=7, n_estimators=500, learning_rate=0.1, max_features="log2"  |
|                0.837  | max_depth=3, n_estimators=100, learning_rate=1, max_features="log2"    |
|                0.8114 | max_depth=7, n_estimators=100, learning_rate=0.5, max_features="log2"  |
|                0.8055 | max_depth=3, n_estimators=300, learning_rate=1, max_features="log2"    |
|                0.8035 | max_depth=7, n_estimators=700, learning_rate=0.1, max_features="log2"  |
|                0.8001 | max_depth=5, n_estimators=300, learning_rate=0.5, max_features="log2"  |
|                0.7999 | max_depth=5, n_estimators=100, learning_rate=1, max_features="log2"    |
|                0.7764 | max_depth=3, n_estimators=700, learning_rate=1, max_features="log2"    |
|                0.7752 | max_depth=5, n_estimators=700, learning_rate=0.5, max_features="log2"  |
|                0.7734 | max_depth=7, n_estimators=700, learning_rate=0.5, max_features="log2"  |
|                0.7635 | max_depth=7, n_estimators=500, learning_rate=0.5, max_features="log2"  |
|                0.7404 | max_depth=5, n_estimators=300, learning_rate=1, max_features="log2"    |
|                0.7364 | max_depth=7, n_estimators=300, learning_rate=0.5, max_features="log2"  |
|                0.7073 | max_depth=7, n_estimators=100, learning_rate=1, max_features="log2"    |
|                0.6882 | max_depth=5, n_estimators=500, learning_rate=1, max_features="log2"    |
|                0.6645 | max_depth=1, n_estimators=100, learning_rate=1, max_features="log2"    |
|                0.6566 | max_depth=7, n_estimators=700, learning_rate=1, max_features="log2"    |

