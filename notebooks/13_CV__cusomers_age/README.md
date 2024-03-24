# Определение возраста клиента по фотографии

[ipynb](https://github.com/KlyuchevenkoE/yandex_praktikum/blob/master/notebooks/13_CV__cusomers_age/CV__cusomers_age.ipynb)

## Описание проекта

Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:

* Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
* Контролировать добросовестность кассиров при продаже алкоголя. В рамках работы, построим модель, которая по фотографии определит приблизительный возраст человека.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib**

- tensorflow.keras.applications.resnet.**ResNet50**
- tensorflow.keras.preprocessing.image.**ImageDataGenerator**
- tensorflow.keras.layers.**GlobalAveragePooling2D, Dense, Flatten**
- tensorflow.keras.models.**Sequential**
- tensorflow.keras.optimizers.**Adam**


## 

* Итоговая модель с использованием Res50 показала результат с MAE ниже парогового уровня, установленного заказчиком, которая составила 6.5
* С точки зрения бизнес - задачи, если по первой части, заказчик вполне может рассчитывать на анализ по возрастным группам, то точного прогноза достижения 18ти лет(для продажи алкоголя) модель не даст и применять в таком виде ее можно толко закладывая значение ошибки в ожидаемый результат - то есть задачу, например, можно переформулировать с учетом необходимости попадания прогноза в возрастную группу и если эта группа окажется группой риска8 (16-25 лет например), а кассир не проверил документы то это будет тревожным сигналом.
# Determining customers age from photo

[ipynb](https://github.com/KlyuchevenkoE/yandex_praktikum/blob/master/notebooks/12_ml_text__toxic_comments/ml_text__toxic_comments.ipynb)

## Project Description

Photo recording in the checkout area will help determine the age of customers in order to:

* Analyze purchases and offer products that may be of interest to buyers of this age group;
* Monitor the integrity of cashiers when selling alcohol. As part of the work, we will build a model that will determine the approximate age of a person from a photograph.
## Stack

- **python**
- **pandas**
- **numpy**
- **matplotlib**

- tensorflow.keras.applications.resnet.**ResNet50**
- tensorflow.keras.preprocessing.image.**ImageDataGenerator**
- tensorflow.keras.layers.**GlobalAveragePooling2D, Dense, Flatten**
- tensorflow.keras.models.**Sequential**
- tensorflow.keras.optimizers.**Adam**

## 
* The final model using Res50 showed a result with MAE below the threshold level set by the customer, which was 6.5
* From the point of view of the business task, if in the first part, the customer can fully count on analysis by age groups, then the model will not give an accurate forecast of reaching 18 years of age (for the sale of alcohol) and it can only be used in this form by putting the error value into the expected result - that is, the task, for example, can be reformulated taking into account the need for the forecast to fall into an age group, and if this group turns out to be a risk group8 (16-25 years old, for example), and the cashier did not check the documents, then this will be an alarming signal.
