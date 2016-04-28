# CTR
CTR prediction using all kind of models
# Dada set
kaggle competition **Display Advertising Challenge** [competition link](https://www.kaggle.com/c/criteo-display-ad-challenge "Title")
# model Result
|model|Regularization|demension|alpha_rate | train_logLoss | test_logLoss | public_logLoss | ranking|run time|memory|
|-----|--------------|----------|----------|------------|------------|--------------|----------------|------|-------|
|Logistic Regression| None| 2^20 |  0.1    |0.463058    | 0.366173  |0.46881         |   265 | 33min | 32M |
|Logistic Regression| None| 2^20 + 17|0.1  | 0.459353|0.369167 | 0.46506 | 210 | 54min | 73M |
