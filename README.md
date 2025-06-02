# There are seven more codes, which will be added after 2025.10.25😘

<!-- Kaggle-Logo -->

<p align="center">
  <img src="https://github.com/user-attachments/assets/06b5dd1c-f989-4958-adf8-32fdd4cd882d" 
       style="width: 300px;" />
</p>


<!-- packages -->
<div align="center">
<img alt="Static Badge" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">&nbsp;&nbsp;
<img alt="Static Badge" src="https://img.shields.io/badge/Pytorch-EE4C2C?style=for-the-badge&logo=Pytorch&logoColor=white">&nbsp;&nbsp;
<img alt="Static Badge" src="https://img.shields.io/badge/numpy-blue?style=for-the-badge&logo=numpy&logoColor=white">&nbsp;&nbsp;
<img alt="Static Badge" src="https://img.shields.io/badge/pandas-blue?style=for-the-badge&logo=pandas&logoColor=yellow&color=%23150458">&nbsp;&nbsp;
<img alt="Static Badge" src="https://img.shields.io/badge/scikitlearn-blue?style=for-the-badge&logo=scikitlearn&logoColor=%23F7931E&color=blue">&nbsp;&nbsp;
</div>

<!-- some tags -->
<div align="center">
    <img src="https://img.shields.io/github/stars/Echo-Nie/Echo-Kaggle?style=flat&logo=GitHub&color=blue" alt="GitHub Stars"/>&nbsp;
    <img src="https://img.shields.io/badge/build-Kaggle-blue?style=flat&color=blue&logo=jupyter&label=Made%20With%20Jupyter" alt="Build with Jupyter"/>
</div>


# Kaggle Learning
This repository documents my learning journey on the Kaggle platform, including model study notes and implementations of models actually used in various competitions. 

## Getting Start
## Playground
### 2. Predict Calorie Expenditure (update 2025/5/6)

![Predict Calorie Expenditure](E:\Echo-Kaggle\assets\Predict Calorie Expenditure.png)

[Predict Calorie Expenditure | Kaggle](https://www.kaggle.com/competitions/playground-series-s5e5)

Your goal is to predict how many calories were burned during a workout.

The evaluation metric for this competition is R**oot Mean Squared Logarithmic Error** .

The **RMSLE** is calculated as:

$$
\text{RMSLE} = \left( \frac{1}{n} \sum_{i=1}^{n} \left( \log(1 + \hat{y}_i) - \log(1 + y_i) \right) \right)^{\frac{1}{2}}
$$

where:

- $n$ is the total number of observations in the test set,
- $\hat{y}_i$ is the predicted value of the target for instance (i),
- $y_i$ is the actual value of the target for instance (i), and,
- $\log$ is the natural logarithm.

For each `id` row in the test set, you must predict the continuous target, `Calories`. The file should contain a header and have the following format:

```
id,Calories
750000,93.2
750001,27.42
750002,103.8
etc。
```

### 1. Titanic (update 2024/6/1)

![Titanic](.\assets\Titanic.png)

[Titanic - Machine Learning from Disaster | Kaggle](https://www.kaggle.com/competitions/titanic)

The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

Goal：It is your job to predict if a passenger survived the sinking of the Titanic or not. For each in the test set, you must predict a 0 or 1 value for the variable. Your score is the percentage of passengers you correctly predict. This is known as [accuracy](https://en.wikipedia.org/wiki/Accuracy_and_precision#In_binary_classification). You should submit a csv file with exactly 418 entries plus a header row. Your submission will show an error if you have extra columns (beyond PassengerId and Survived) or rows.

$$
Accuracy = \frac{TP + TN}{TP + TN + FP + FN}
$$

The file should have exactly 2 columns:

- PassengerId (sorted in any order)
- Survived (contains your binary predictions: 1 for survived, 0 for deceased)

```
PassengerId,Survived
892,0
893,1
894,0
Etc.
```

## 

## Competition

