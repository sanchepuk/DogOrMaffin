<h1> Ошибки нейросети на тренировочной и валидационной выборки </h1>

- <b>Использование функции потери CrossEntropyLoss и оптимизатором SGD</b>\
Ошибка на тестовой выборке 3/6 = 50%. Выдаёт всегда один ответ \
![alt text](Training_with_CrossEntropyLoss_and_SGD.png "CrossEntropyLoss_and_SGD")

* <b>Использование функции потери CrossEntropyLoss и оптимизатором Adam</b>\
Ошибка на тестовой выборке 1/6 = 17%. Нестабильное обучение\
![alt text](Training_with_CrossEntropyLoss_and_Adam.png "CrossEntropyLoss_and_Adam")

- <b>Использование функции потери MSELoss и оптимизатором SGD</b>\
Ошибка на тестовой выборке 3/6 = 50%. Выдаёт всегда один ответ \
![alt text](Training_with_MSELoss_and_SGD.png "MSELoss_and_SGD")

* <b>Использование функции потери MSELoss и оптимизатором Adam</b>\
Ошибка на тестовой выборке 0/6 = 0%. Обучение нейросети в большенстве случаев одинаково. Ошибка по дельте - 28%\
![alt text](Training_with_MSELoss_and_Adam.png "MSELoss_and_Adam")