# Предсказание температуры стали

[ipynb](https://github.com/KlyuchevenkoE/yandex_praktikum/blob/master/notebooks/14_final_project__industry/final_project__industry.ipynb)

## Описание проекта

Необходимо построить, и выбрать лучшую, исходя из требования MAE не ниже 8, модель предсказания температуры стали. Для обучения модели будут использованы предобработанные данныье из семи выгрузок, содержащих измерения о протекании процессов во время плавления стали.
## Навыки и инструменты

- **time**
- **pandas**
- **seaborn** 
- **matplotlib**
- **numpy** 
- **scipy** 
- **stats** 

- **pathlib**

- sklearn.model_selection.**train_test_split**
- sklearn.preprocessing.**StandardScaler**

- sklearn.pipeline.**Pipeline**
- sklearn.pipeline.**make_pipeline**
- sklearn.pipeline.**FeatureUnion**

- sklearn.decomposition.**PCA**
- sklearn.feature_selection.**SelectKBest**
- sklearn.feature_selection.**f_regression**

- sklearn.linear_model.**LinearRegression**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.linear_model.**Lasso**

- sklearn.model_selection.**RandomizedSearchCV**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**KFold**
  
- sklearn.metrics.**mean_squared_error**
- sklearn.metrics.**mean_absolute_error**

- tensorflow.**keras**
- keras.layers.**Conv2D, MaxPooling2D, Flatten, Dense**
- tensorflow.keras.models.**Sequential**
- tensorflow.keras.optimizers.**Adam**


- sklearn.dummy.**DummyRegressor**

- **tempfile**
- **shutil**
- **catboost**

## 

Проведенная работа дает основание утверждать, что прогноз значения температуры на финальных стадиях нагрева, может быть предсказан по имеющемуся набору признаков в имеющемся объеме данных. Такой прогноз вполне можно использовать для предупреждения перегрева сплава сверх необходимых температур, что приведет к сокращению энергопотребления.

# Steel temperature prediction

[ipynb](https://github.com/KlyuchevenkoE/yandex_praktikum/blob/master/notebooks/14_final_project__industry/final_project__industry.ipynb)

## Project Description
It is necessary to build and select the best, based on the requirement of MAE not lower than 8, a steel temperature prediction model. To train the model, preprocessed data from seven downloads will be used, containing measurements of the processes occurring during steel melting.
## Stack

- **time**
- **pandas**
- **seaborn** 
- **matplotlib**
- **numpy** 
- **scipy** 
- **stats** 

- **pathlib**

- sklearn.model_selection.**train_test_split**
- sklearn.preprocessing.**StandardScaler**

- sklearn.pipeline.**Pipeline**
- sklearn.pipeline.**make_pipeline**
- sklearn.pipeline.**FeatureUnion**

- sklearn.decomposition.**PCA**
- sklearn.feature_selection.**SelectKBest**
- sklearn.feature_selection.**f_regression**

- sklearn.linear_model.**LinearRegression**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.linear_model.**Lasso**

- sklearn.model_selection.**RandomizedSearchCV**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**KFold**
  
- sklearn.metrics.**mean_squared_error**
- sklearn.metrics.**mean_absolute_error**

- tensorflow.**keras**
- keras.layers.**Conv2D, MaxPooling2D, Flatten, Dense**
- tensorflow.keras.models.**Sequential**
- tensorflow.keras.optimizers.**Adam**


- sklearn.dummy.**DummyRegressor**

- **tempfile**
- **shutil**
- **catboost**


## 
The work carried out gives grounds to assert that the forecast of the temperature value at the final stages of heating can be predicted from the existing set of features in the available volume of data. Such a forecast can be used to prevent overheating of the alloy above the required temperatures, which will lead to a reduction in energy consumption.
