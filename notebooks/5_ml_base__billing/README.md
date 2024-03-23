# Обучение модели предсказания тарифов мобильной связи с применением базовых техник ml.

[ipynb](https://github.com/KlyuchevenkoE/yandex_praktikum/blob/master/notebooks/5_ml_base__billing/ml_base__billing.ipynb)

## Описание проекта

Цлью проекта является построение модели с наилучшим значением Accuracy, то есть модель, которая будет наилучим образом предсказывать какой тариф предложить имеющемуся абоненту - обладателю устаревшего тарифного плана. 

## Навыки и инструменты

- **python**
- **pandas**
- **pandas_profiling**
- **seaborn**

- sklearn.model_selection.**RandomizedSearchCV**
- sklearn.model_selection.**GridSearchCV**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.ensemble.**RandomForestClassifier**
- sklearn.linear_model **LogisticRegression**
- sklearn.dummy **DummyClassifier**
- sklearn.model_selection **KFold**
- sklearn.metrics.**accuracy_score**

- *CatBoost*

## 

В рамках проекта нам удалось обучить модель с итоговой accuracy 83% на тестовой и 90% на валидационной выборках, соответственно. Такую модель вполне можно использовать для рекомендаций тарифного плана. Модель была выбрана путем сравнения итоговых accuracy для логистической регрессии, дерева решений, CatBoost и случайного леса, который показал себя лучше всех. Дополнительные проверки на адекватность показали что базовая модель показывает accuracy ниже (менее 70%). Также, дополнительно, были праверены результаты работы модели при исключении корреклирующих величин, в результате, результат оказался хуже, что говорит о вероятном отсутствии существенного вклада мультиколлинеарности в качество модели.
