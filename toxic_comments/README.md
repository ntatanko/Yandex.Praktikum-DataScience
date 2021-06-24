# Yandex.Praktikum_ML_for_texts
Yandex.Praktikum ML for texts classification
## Libraries:
 - numpy
 - pandas
 - re
 - string
 - collections
 - lightgbm
 - matplotlib
 - seaborn
 - sklearn
 - nltk
 - tqdm


#  Description
The online store is planning to launch a new service so that users can edit and supplement product descriptions, offer their edits and comment on the edits of other buyers. The store needs a tool that will search for toxic comments and send them for moderation.

# Task
Speed up the moderation of comments in the community by automating the assessment of their toxicity.  
Train the model to classify comments into positive and negative. At your disposal is a data set with markup on the toxicity of edits.  
Build a model with the value of the quality metric * * F1** at least 0.75.  

# Conclusions
The analysis and lemmatization of comments was carried out using the nltk library,  LogisticRegression, RandomForestClassifier and LGBMClassifier were trained on the features extracted using CountVectorizer and TfidfVectorizer.  
Achieved f1_score=0.789. Since in this problem, in my opinion, recall is very important, it is worth paying attention to models where it is higher or changing the classification threshold, achieving a higher recall value.


# Описание
Интернет-магазин планирует запускает новый сервис, чтобы пользователи могли редактировать и дополнять описания товаров, предлагать свои правки и комментировать правки других покупателей. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. 

# Задача
Ускорить модерацию комментариев в сообществе, автоматизировав оценку их токсичности.
Обучить модель классифицировать комментарии на позитивные и негативные. В вашем распоряжении набор данных с разметкой о токсичности правок.
Постройте модель со значением метрики качества **F1** не меньше 0.75. 

#
Проведен анализ и лемматизация комментариев с помощью библиотеки nltk, обучены модели LogisticRegression, RandomForestClassifier и LGBMClassifier на признаках, извлеченных с помощью CountVectorizer и TfidfVectorizer, удалось достичь f1=0.789. Поскольку в данной задаче, по моему мнению, очень важен recall, то стоит обтатить внимание на модели у которых он выше или менять порог классификации, добиваясь более высокого значения полноты.
