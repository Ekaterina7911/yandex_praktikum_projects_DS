# 7. Выбор локации для скважины (машинное обучение в бизнесе)

### Сфера деятельности
Добывающие компании 

### Цели проекта

На основе данных необходимо выбрать район, где добыча нефти принесёт наибольшую прибыль.

### Описание проекта

Изучены данные о пробах нефти из трёх регионов
- Обучена модель линейной регресси для каждого региона
- Для оценки качества моделей расчитан показатель RSME и коэффициент детерминации
- Определен безубыточный объем залежей и проведено сравнение его со средним запасом в каждом регионе
- В процессе работы использована техника Bootstrap для отбора 200 скважин из 500

### Итоги

Рекомендован регион для разработки с максимальной оценкой прибыли - это второй регион со следующими показателями: средняя прибыль 518,3 млн.руб, доверительный интервал в диапазоне от 128.0 млн.руб. до 953.6 млн.руб., риск убытков 0,3%


### Навыки и инструменты

- предобработка данных
- Python
- Pandas
- Bootstrap
- Scikit-learn