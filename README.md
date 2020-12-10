# Курсовые работы 

1. База данных Goodreads - описана модель хранения данных популярного интернет-портала так называемой «социальной каталогизации». Сайт предоставляет свободный доступ к обширной базе данных книг, аннотаций, различных обзоров.

Требования к курсовому проекту:
1. Составить общее текстовое описание БД и решаемых ею задач;
2. минимальное количество таблиц - 10;
3. скрипты создания структуры БД (с первичными ключами, индексами, внешними ключами);
4. создать ERDiagram для БД;
5. скрипты наполнения БД данными;
6. скрипты характерных выборок (включающие группировки, JOIN'ы, вложенные таблицы);
7. представления (минимум 2);
8. хранимые процедуры / триггеры;


2.Модель для предсказания цен на недвижимость (квартиры) - Python Numpy, Pandas, Matplotlib, Scikit-learn

Требования к курсовому проекту:
Используя данные из обучающего датасета (train.csv), построить модель для предсказания цен на недвижимость.
С помощью полученной модели, предсказать цены для квартир из тестового датасета (test.csv).

Целевая переменная:
Price

Метрика качества:
R2 - коэффициент детерминации (sklearn.metrics.r2_score)

Требования к решению:
R2 > 0.6

3. Модель для прогнозирования невыполнения долговых обязательств по текущему кредиту. Выполнить прогноз для примеров из тестового датасета.

Целевая переменная
Credit Default - факт невыполнения кредитных обязательств

Метрика качества
F1-score (sklearn.metrics.f1_score)

Требования к решению
F1 > 0.5
