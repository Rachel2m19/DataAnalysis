# models 模型

1.Linear Regression 线性回归模型

keypoint：

• 建模快速简单。

• 有直观的理解和解释。

• 线性回归对异常值非常敏感。


2.Polynomial Regression 多项式回归

keypoint：

• 模拟非线性数据;总体上更灵活，可以模拟一些相当复杂的关系。

• 完全控制要素变量的建模（要设置变量的指数）。

• 需要仔细的设计。需要一些数据的先验知识才能选择最佳指数。

• 容易过拟合。

3.Ridge Regression 岭回归

标准线性或多项式回归在特征变量之间存在很高的共线性（high collinearity）的情况下将失败。共线性是自变量之间存在近似线性关系，会对回归分析带来很大的影响。

4.Lasso回归

5.弹性网络回归（ElasticNet Regression）


Reference
1.https://www.sohu.com/a/249214202_814235
