# Прогноз спроса на такси

[ipynb](https://github.com/KlyuchevenkoE/yandex_praktikum/blob/master/notebooks/11_time_series__taxi/time_series__taxi.ipynb)

## Описание проекта

У нас есть исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Наша задача подобрать модель, которая наилучшим образом спрогнозирует спрос на такси в следующий час. Значение метрики RMSE на тестовой выборке должно быть не больше 48.
## Навыки и инструменты

- **python**
- **pandas**
- **pandas_profiling**
- **matplotlib**
- **seaborn**
- **numpy**

- statsmodels.tsa.seasonal.**seasonal_decompose**

- sklearn.model_selection.**cross_val_score**
- sklearn.model_selection.**TimeSeriesSplit**
- sklearn.model_selection.**RandomizedSearchCV**
- sklearn.model_selection.**GridSearchCV**
- sklearn.linear_model.**LinearRegression**
- sklearn.linear_**model.Lasso**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.metrics.**mean_squared_error**

- **lightgbm**
- **catboost** 

**pickle**

## 

В результате работы удалось дотичь нужного значения метрики RMSE при прогонозе спроса на такси в следующий час. В нашем проекте это значение на тестовой выборке составило 46,3 для выбранной модели случайного леса с подобранными гиперпараметрами, которая показала себя на тестововй выборке лучше LGBM и Линейная регрессия. Также, на первых этапах работы был проведен анализ данных, в рамках которого выявлен тренд к росту спроса на таки на всем датасете и явная сезонность связанная с ростом спровс в ночные часы, спадом в утренние и средним значением днем.
