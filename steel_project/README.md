# Graduation project of course DataScience Yandex.Praktikum
# Выпускной проект курса DataScience Yandex.Praktikum
## Libraries/библиотеки:
 - numpy
 - pandas
 - matplotlib
 - plotly
 - seaborn
 - sklearn
 - lightgbm
 - catboost
 - tensorflow.keras
 
 
## Description
To optimize production costs at the metallurgical plant, it is necessary to reduce the energy consumption at the steel processing stage.  
__steel_processing.ipynb__  

## Task
Build a model that predicts the final temperature of the steel based on the initial characteristics and processing stages.   

## Data Description
The data consists of files describing the different stages of steel processing. 


## Content:
 - Exploratory data analysis
 - Data preparation
 - Model training
 - Checking models on test data
 - Conclusions  

A research analysis was conducted, data distribution was studied, and outliers were identified. As a result, it is recommended to check at what stage errors in the data may occur and pay attention to the missing temperature measurements.
Models trained: linear regression, RandomForestRegressor, LGBMRegressor, CatBoostRegressor, neural network.
It was possible to achieve the accuracy of predicting the final steel temperature of 5.6 degrees on the test data.
The analysis of the importance of the features is carried out, the parameters and additives that make the main contribution to the determination of the final temperature of steel are identified.
 
## Additional task.
Study the characteristics of the steel processing.
__steel_additional_task.ipynb__  

 
 
 
## Описание
Для оптимизации производственных расходов на металлургическом комбинате надо уменьшить потребление электроэнергии на этапе обработки стали.  
__steel_processing.ipynb__  

## Задача
Построить модель, которая по начальным характеристикам и этапам обработки предскажет конечную температуру стали.


## Описание данных
Данные состоят из файлов, описывающих разные стадии процесса обработки стали.

## Содержание:
 - Исследовательский анализ данных
 - Подготовка данных
 - Обучение моделей
 - Проверка моделей на тестовых данных
 - Выводы
 
## Дополнительное задание.
Изучить характеристики процесса обработки стали.  
__steel_additional_task.ipynb__  

Проведен исследовательский анализ, изучено распределение данных и выявлены выбросы. По итогам рекомендуется проверить, на каком этапе могут возникать ошибки в данных и обратить внимание на отсутствующие измерения температуры.
Обучены модели: линейная регрессия,RandomForestRegressor, LGBMRegressor, CatBoostRegressor, нейронная сеть.
Удалось достичь точности предсказания конечной температуры стали 5,6 градусов на тестовых данных.
Проведен анализ важности признаков, выявлены параметры и добавки, вносящие основной вклад в определение конечной температуры стали.
