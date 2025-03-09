Описание
Этот проект направлен на создание модели машинного обучения для прогнозирования продаж Coca Cola по регионам на основе исторических данных. Для прогнозирования использовалась модель случайного леса (RandomForestRegressor), которая предсказывает количество проданных единиц продукции по часам в разных регионах. Проект включает агрегацию данных, обработку признаков, обучение модели и визуализацию прогнозов.

Задачи проекта:
Прогнозирование продаж Coca Cola по регионам на следующие сутки.
Оценка качества модели для каждого региона (с помощью метрик MAE и RMSE).
Визуализация прогнозов по каждому региону для отображения ожидаемых продаж по часам.
Используемые технологии:
Python: Основной язык для разработки.
Pandas: Для обработки и агрегации данных.
Scikit-learn: Для обучения модели машинного обучения (RandomForestRegressor).
Matplotlib и Seaborn: Для визуализации результатов.
Numpy: Для математических операций и работы с массивами данных.
Структура данных:
sales_data.csv: Исходный CSV-файл с данными о продажах. Данные включают следующие столбцы:
barcode: Штрихкод продукта.
quantity: Количество проданных единиц.
local_date: Дата и время продажи.
region: Регион продажи.
