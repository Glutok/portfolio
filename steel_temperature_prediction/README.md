# Оптимизация производственных расходов металлургического комбината

## Описание проекта

Чтобы оптимизировать производственные расходы, металлургический комбинат «Стальная птица» решил уменьшить потребление электроэнергии на этапе обработки стали. Задача проекта — построить модель, которая будет предсказывать температуру этого сплава.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib.pyplot**
- **sklearn**
  - sklearn.model_selection.**cross_val_score**
  - sklearn.model_selection.**train_test_split**
  - sklearn.metrics.**mean_absolute_error**
  - sklearn.preprocessing.**StandardScaler**
  - sklearn.linear_model **LinearRegression**
  - sklearn.linear_model **Lasso**
  - sklearn.tree **DecisionTreeRegressor**

## Общий вывод

Были обучены три модели, подобраны их гиперпаметры; проведена проверка на тестовом наборе данных, выбрана одна для запуска в работу
