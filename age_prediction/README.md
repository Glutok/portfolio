# Определение возраста покупателей

## Описание проекта

Требуется обучить нейронную сеть, которая должна определить возраст человека по фотографии

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **tensorflow**
  - **tensorflow.keras.models Sequential**
  - **tensorflow.keras.optimizers Adam**
  - **tensorflow.keras.layers GlobalAveragePooling2D, Dense**
  - **tensorflow.keras.preprocessing.image.ImageDataGenerator**
  - **tensorflow.keras.applications.resnet.ResNet50**

## Общий вывод

Было проведено обучение импортированной нейронной сети архитектуры ResNet. Проведена проверка на тестово наборе данных. За 5 эпох MAE на тестовой выборке составило 6.5
