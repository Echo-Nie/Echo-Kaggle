# Kaggle Learning
This repository documents my learning journey on the Kaggle platform, including model study notes and implementations of models actually used in various competitions. 

## Getting Start
### 1. Titanic

[泰坦尼克号 - 从灾难中学习机器学习 |卡格尔 --- Titanic - Machine Learning from Disaster | Kaggle](https://www.kaggle.com/competitions/titanic)

1912 年 4 月 15 日，在她的处女航中，被广泛认为“永不沉没”的 RMS 泰坦尼克号在与冰山相撞后沉没。不幸的是，船上的每个人都没有足够的救生艇，导致 1502 名乘客和船员中有 2224 人死亡。虽然生存下来有一些运气因素，但似乎某些群体比其他人更有可能生存下来。在本次挑战赛中，我们要求您构建一个预测模型，使用乘客数据（即姓名、年龄、性别、社会经济阶层等）回答“什么样的人更有可能生存”这个问题。

Goal：你的工作是预测一名乘客是否在泰坦尼克号沉没后幸存下来。对于测试集中的每个值，您必须预测变量的 0 或 1 值，您的分数是您正确预测的乘客百分比，这称为[准确性 ](https://en.wikipedia.org/wiki/Accuracy_and_precision#In_binary_classification)。
$$
Accuracy = \frac{TP + TN}{TP + TN + FP + FN}
$$




## Playground
### 1. Predict Calorie Expenditure

[预测卡路里消耗 |卡格尔 --- Predict Calorie Expenditure | Kaggle](https://www.kaggle.com/competitions/playground-series-s5e5)

Your goal is to predict how many calories were burned during a workout.

本次比赛的评估指标是**均方根对数误差**（Root Mean Squared Logarithmic Error）。

RMSLE 的计算公式如下：

$$
\text{RMSLE} = \left( \frac{1}{n} \sum_{i=1}^{n} \left( \log(1 + \hat{y}_i) - \log(1 + y_i) \right) \right)^{\frac{1}{2}}
$$

其中：

- $n$ 是测试集中观测值的总数
- $\hat{y}_i$ 是目标实例 $i$ 的预测值
- $y_i$ 是目标实例 $i$ 的实际值
- $\log$ 是自然对数

对于测试集中的每一行 `id`，你必须预测连续目标 `Calories`。文件应包含一个标题，并具有以下格式：

```
id,Calories
750000,93.2
750001,27.42
750002,103.8
等等。
```



## Competition

