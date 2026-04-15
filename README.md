**Introduction**

Obesity is a growing global health concern influenced by a combination of dietary habits, lifestyle behaviors, and physical conditions. Understanding these factors is essential for assessing obesity risk and designing effective interventions. This project uses the Estimation of Obesity Levels Based on Eating Habits and Physical Condition dataset from the UCI Machine Learning Repository to analyze how eating patterns and physical activity relate to different obesity categories. Using data-processing techniques, we aim to explore relationships among variables and prepare the dataset for predictive modeling.

**Dataset Description**

The dataset contains 2,111 records and 17 attributes, collected from individuals in Mexico, Peru, and Colombia. About 23% of the instances were gathered through a survey, while 77% were synthetically generated to balance class distribution. The dataset includes demographic information, eating habits, physical activity, and lifestyle factors. The target variable categorizes individuals into seven obesity levels, ranging from underweight to obesity type III. No missing values are reported.

| **Feature**                    | **Type**        | **Description**                           |
| ------------------------------ | --------------- | ----------------------------------------- |
| Gender                         | Categorical     | Male or Female                            |
| Age                            | Numerical       | Age in years                              |
| Height                         | Numerical       | Height in meters                          |
| Weight                         | Numerical       | Weight in kilograms                       |
| family_history_with_overweight | Categorical     | Whether close relatives are overweight    |
| FAVC                           | Categorical     | Frequent consumption of high-calorie food |
| FCVC                           | Numerical (1–3) | Frequency of vegetable consumption        |
| NCP                            | Numerical (1–4) | Number of main meals per day              |
| CAEC                           | Categorical     | Frequency of eating between meals         |
| SMOKE                          | Categorical     | Smoking status                            |
| CH2O                           | Numerical (1–3) | Daily water intake                        |
| SCC                            | Categorical     | Monitoring of daily calorie consumption   |
| FAF                            | Numerical (0–3) | Weekly physical activity frequency        |
| TUE                            | Numerical (0–2) | Daily time using electronic devices       |
| CALC                           | Categorical     | Alcohol consumption frequency             |
| MTRANS                         | Categorical     | Mode of transportation used               |
| **NObesity (Target)**          | Categorical     | 7-level obesity classification            |
