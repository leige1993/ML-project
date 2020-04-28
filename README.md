# ML-project
phone price prediction
手机价格预测模型
1.数据集1500，20个特征+价格类别（0，1，2，3）；
2.数据处理：数据类型转换、归一化处理；
3.特征选取
4.数据划分：从1500里分training set, cross validation set, test set
5.选择单个模型（有监督分类），集成学习模型
逻辑回归、决策树、支持向量机、神经网络、KNN，贝叶斯
集成学习模型：随机森林（bagging）、Gradient Boost Decision Tree(adaboost)、stacking
6.对每个模型调整参数，找使得validation error均值最小的参数；
7.对模型评分
评分维度：
①　错误率与准确率
②　Confusion Matrix（查准率（precision）、查全率（recall）与F1-score）
https://zhuanlan.zhihu.com/p/59862986
③　PR曲线
④　roc曲线、AUC曲线
⑤　KD曲线
