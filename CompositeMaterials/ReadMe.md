# Прогнозирование конечных свойств новых материалов (композиционных материалов). Подбор лучшей модели.

## Статус проекта 
Проект выполнен в полном объеме. Завершен.

## Данные

Представлены данные о начальных свойствах компонентов композиционных материалов (количество связующего, наполнителя, температурный режим отверждения и т.д.).

## Задача

Цель: спрогнозировать ряд конечных свойств получаемых композиционных материалов.

Необходимо: выбрать лучшую модель для определения конечных свойств композиционных материалов.

## Выводы 

С целью прогнозирования пяти характеристик будущего композитного материала на основе его составляющих и методов формирования были рассмотрены 4 модели: модель линейной регерссии, случайного леса, градиентного бустинга и нейронной сети.

В ходе рассмотрения наиболее точной себя проявила модель нйронной сети, однако на таком объеме данных она работает нестабильно и не каждый раз дает точные предстказания.

Следующая по точности себя проявила модель линейной регрессии. К тому же, при проверке на тестовой выборке модель линейной регрессии показывает значительно лучшие результаты, чем модель нейронной сети.

В связи с описанным выше, можно сделать вывод о том, что в работу следует принимать модель линейной регрессии.

## Используемые библиотеки

*Pandas*
*Keras*
*lightgbm*
*Matplotlib*
*sklearn*

## Используемые модели: 

*LinearRegression*
*RandomForestRegressor*
*LGBMRegressor*
*Sequential*