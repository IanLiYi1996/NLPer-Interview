# 集成学习 - GBDT

---

[TOC]

## 1. Boosting 思想

Boosting 基于串行策略， 各个基分类器之间有依赖。

1. 先从初始训练集训练一个弱学习器，初始训练集各个样本权重相同
2. 根据上一个弱学习器的表现，调整样本权重，是的分类错误的样本得到更多关注
3. 基于调整后的样本分布，训练下一个弱学习器、
4. 测试时，对各基学习器**加权**得到最终结果

## 2. GBDT

GBDT ， Gradient Boosting  Decision Tree， 叫 梯度提升决策树。

### 1. GBDT 思想



