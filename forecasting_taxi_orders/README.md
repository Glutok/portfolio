# Прогнозирование заказов такси

## Описание проекта

Требуется модель машинного обучения, которая должна предсказать количество заказов такси на следующий час. Модель поможет привлекать больше водителей в период пиковой нагрузки.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **statsmodels**
  - **statsmodels.tsa.seasonal.seasonal_decompose**
  - **statsmodels.graphics.tsaplots**
- **sklearn**
  - **sklearn.model_selection.train_test_split**
  - **sklearn.model_selection.TimeSeriesSplit**
  - **sklearn.model_selection.cross_val_score**
  - **sklearn.linear_model.LinearRegression**
  - **sklearn.ensemble.RandomForestRegressor**
- **keras**
  - **tensorflow.keras.models.Sequential**
  - **tensorflow.keras.layers.Dense , Dropout**
  - **tensorflow.keras.optimizers.Adam**

## Общий вывод

Были обучены модели ML, проведена проверка обученных моделей на тестовом наборе данных.
