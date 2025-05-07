# Kaggle-Learning-and-Competition-Model-Practices
This repository documents my learning journey on the Kaggle platform, including model study notes and implementations of models actually used in various competitions. 

## Playground
### 1. Predict Calorie Expenditure

Your goal is to predict how many calories were burned during a workout.

本次比赛的评估指标是**均方根对数误差**（Root Mean Squared Logarithmic Error）。

RMSLE 的计算公式如下：

$$
\text{RMSLE} = \left( \frac{1}{n} \sum_{i=1}^{n} \left( \log(1 + \hat{y}_i) - \log(1 + y_i) \right) \right)^{\frac{1}{2}}
$$

其中：

- $ n $ 是测试集中观测值的总数，
- $ \hat{y}_i $ 是目标实例 $ i$ 的预测值，
- $ y_i $ 是目标实例 $ i $ 的实际值，以及
- $ \log $ 是自然对数。

对于测试集中的每一行 `id`，你必须预测连续目标 `Calories`。文件应包含一个标题，并具有以下格式：

```
id,Calories
750000,93.2
750001,27.42
750002,103.8
等等。
```



