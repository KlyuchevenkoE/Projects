# Определение стоимости автомобилей. Применение численных методов 

[ipynb](https://github.com/KlyuchevenkoE/yandex_praktikum/blob/master/notebooks/6_ml_teacher__bank_clients_churn/ml_teacher__bank_clients_churn.ipynb)

## Описание проекта

Из банка стали уходить клиенты. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. Построим модель с предельно большим значением F1-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59. Дополнительно измерим AUC-ROC, сравнивая её значение с F1-мерой.

## Навыки и инструменты

- **python**
- **pandas**
- **pandas_profiling**
- **matplotlib**
- **seaborn**
- **numpy**

- sklearn.model_selection.**RandomizedSearchCV**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**cross_val_score**
- sklearn.model_selection.**RepeatedKFold**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.ensemble.**RandomForestClassifier**
- sklearn.linear_model **LogisticRegression**
- sklearn.dummy **DummyClassifier**
- sklearn.preprocessing.**StandardScaler**
- sklearn.preprocessing.**OrdinalEncoder**
- sklearn.preprocessing.**OneHotEncoder**
- sklearn.compose **make_column_transformer**
- sklearn.metrics.**confusion_matrix**
- sklearn.metrics.**f1_score**
- sklearn.metrics.**roc_curve**
- sklearn.metrics.**roc_auc_score**
- sklearn.utils.**shuffle**

## 

По итогам работы выбрана модель случайного леса. Модель с подобранными гиперпараметрами случайным поиском показывает наилучший результат при использовании даунсеплинга и может быть применена для прогнозирования оттока клиентов в нашей задаче.
