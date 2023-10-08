---
Title:heart-attack
---

## The goal of collecting this dataset

our goal is to Identify whether the chances of of a heart attack occurrence is high or low for the patient

```         
The source of the dataset, include link\URL
```

The dataset was sourced from the kaggle website in this URL: <https://www.kaggle.com/datasets/pritsheta/heart-attack>

## General information

1- Number of Attributes: 14 2- Number of Objects: 303 3- Type of Attributes:

| Attribute name | Data type | Description                                             | possible values                                                           |
|-----------------|-----------------|---------------------|-----------------|
| age            | Numeric   | Age (in years)                                          | range between 29-77                                                       |
| sex            | Binary    | gender                                                  | 1 = male; 0 =female                                                       |
| cp             | Numeric   | Chest Pain type                                         | 1: typical angina,2: atypical angina,3: non-anginal pain ,4: asymptomatic |
| trestbps       | Numeric   | resting blood pressure                                  | range beteen 94-200                                                       |
| chol           | Numeric   | serum cholesterol in mg/dL                              | range between 126-564                                                     |
| fbs            | Binary    | fasting blood sugar \> 120 mg/dL (likely to be diabetic | 1=true,0=false                                                            |
| Restecg        | Binary    | Resting electrocardiogram                               | 0=normal,1=abnormal                                                       |
| Oldpeak        | Numeric   | ST depression                                           | range between 0-6.20                                                      |
| thalach        | Numeric   | heart rate achieved                                     | range between 71-202                                                      |
| exang          | Binary    | exercise induced angina                                 | 1 = yes; 0 = no                                                           |
| slope          | Numeric   | the slope of the peak exercise ST segment               | range between 0-2                                                         |
| Ca             | Numeric   | number of major vessels                                 | range between 0-4                                                         |
| Thal           | Numeric   | Thalassemia                                             | range between 0-3                                                         |
| Target         | Binary    | if the target has disease or not                        | 0 = no disease, 1 = disease                                               |

Class label: -target of Heart Attack accurrance -not target of Heart Attack accurrance

``` R
install.packages("readxl")
```

``` R
View(dataset)
```

```         
nrow(dataset)
```

```         
ncol(dataset)
```
