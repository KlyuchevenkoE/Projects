# Предсказание температуры стали

[ipynb](https://github.com/KlyuchevenkoE/yandex_praktikum/blob/master/notebooks/14_final_project__industry/final_project__industry.ipynb)

## Описание проекта

Необходимо построить, и выбрать лучшую, исходя из требования MAE не ниже 8, модель предсказания температуры стали. Для обучения модели будут использованы предобработанные данныье из семи выгрузок, содержащих измерения о протекании процессов во время плавления стали.
## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **contextlib**
- **re**
- **nltk**
- **spacy**

- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.linear_model.**LogisticRegression**
- sklearn.dummy.**DummyClassifier**
- sklearn.ensemble.**RandomForestClassifier**
- sklearn.pipeline.**Pipeline**
- sklearn.model_selection.**RandomizedSearchCV**
- sklearn.metrics **f1_score**

- **lightgbm**

## 

В рамках проекта были рассмотрены f1-меры результатов работы трех моделей. Для каждой модели пыл подобран оптимальный набор гиперпараметров. Наилучший результат показал модель логистической регресси с f1 равной 0,77 на тренировочной выборке и аналогичным значенеим на тестовой

# Steel temperature prediction

[ipynb](https://github.com/KlyuchevenkoE/yandex_praktikum/blob/master/notebooks/12_ml_text__toxic_comments/ml_text__toxic_comments.ipynb)

## Project Description
It is necessary to build and select the best, based on the requirement of MAE not lower than 8, a steel temperature prediction model. To train the model, preprocessed data from seven downloads will be used, containing measurements of the processes occurring during steel melting.
## Stack

- **python**
- **pandas**
- **numpy**
- **contextlib**
- **re**
- **nltk**
- **spacy**

- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.linear_model.**LogisticRegression**
- sklearn.dummy.**DummyClassifier**
- sklearn.ensemble.**RandomForestClassifier**
- sklearn.pipeline.**Pipeline**
- sklearn.model_selection.**RandomizedSearchCV**
- sklearn.metrics **f1_score**

- **lightgbm**

## 
As part of the project, f1-measures of the performance results of three models were considered. For each dust model, an optimal set of hyperparameters was selected. The best result was shown by the logistic regression model with f1 equal to 0.77 on the training set and a similar value on the test set
