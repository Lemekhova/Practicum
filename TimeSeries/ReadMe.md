# Прогнозирование заказов такси

## Статус проекта
Проект выполнен в полном объеме. Завершен.

## Данные

- Количество заказов

## Задача

Заказчик — Компания «Чётенькое такси».

Цель: привлекать больше водителей в период пиковой нагрузки.

Необходимо: Постройте модель для предсказания количества заказов такси на следующий час.

## Выводы
В ходе работы были рассмотрены несколько моделей.
Лучше всего на валидационных данных проявила себя модель градиентного бустинга LGBMRegressor при большем количестве признаков.
Данные были разбиты на валидационную и тестовую выборки последовательно, где тестовая выборка представлена конечной частью временного ряда.
В связи с этим, модель показала метрику RMSE на тестовой выборке хуже, чем RMSE на валидационной выборке, а график временного среднего значения количества заказов такси вконце "ползет" вверх и является менее стационарным временным рядом в отличие от более ранних показателей.

## Используемые библиотеки
*Pandas*
*Sklearn*
*statsmodels*
*Lightgbm*
*Matplotlib*

## Используемые модели
*LGBMRegressor*
*LinearRegression*
*RandomForestClassifier*