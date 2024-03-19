# Определение стоимости автомобилей. Применение численных методов 

[ipynb]([notebooks/10_numerical_methods__cars/numerical_methods__cars.ipynb](https://github.com/KlyuchevenkoE/yandex_praktikum/blob/master/notebooks/10_numerical_methods__cars/numerical_methods__cars.ipynb))

## Описание проекта

Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В нашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Нам нужно построить модель для определения стоимости.

Важны будут следующие хзарактеристрики:

качество предсказания;
скорость предсказания;
время обучения.


## Навыки и инструменты

- **python**
- **pandas**
- **seaborn**
- **numpy**
- **scipy**
- sklearn.model_selection.**RandomizedSearchCV**
- sklearn.model_selection.**cross_val_score**
- sklearn.model_selection.**RepeatedKFold**
- sklearn.metrics.**mean_squared_error**
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.preprocessing.**StandardScaler**
- sklearn.preprocessing.**OrdinalEncoder**
- sklearn.preprocessing.**OneHotEncoder**
- sklearn.dummy **DummyRegressor**

- **lightgbm**
- **catboost**


## 

## Общий вывод

В результате LGBM дал лучший результат на тренировочно датасете как по времени обучения, так и по качеству RMSE. На тестовой выборке подобранная модель LGBM показала почти идентичный результат RMSE в 1671, что ниже граничного достаточного 2500. Рекордное время обучение у случайного леса, но перебор гиперпараметров здесь занимает очень много времени. Результаты сведены в таблицу.
