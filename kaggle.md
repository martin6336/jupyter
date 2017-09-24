# kaggle方法
## bagging
放回重复抽样，一种防止过拟合的方法。bagging methods work best with **strong and complex** models (e.g., fully developed decision trees), in contrast with boosting methods which usually work best with **weak models (e.g., shallow decision trees).**
## random forest
对于every tree，样本都是一个random sample drawn from the training set。split一个node的时候，并不考虑全部feature，而是一个subset of features。
## extremly randomized trees(extra trees)
比random forest的随机性更近一步，每次split node 的时候不考虑最佳的threshold,对于每个feature都是随机挑选一个threshold，谁表现最好就选谁了。降低方差，但是增加了bias。
## adaboost
改变权重，逐步改进weak model的预测能力

