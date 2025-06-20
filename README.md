Я проанализировала данные о преступлениях в Чикаго с 2001 года по настоящее время. Использовала библиотеки Pandas, Matplotlib и PySpark.

Этапы работы
1. Предобработка данных
Удалила строки с пропущенными значениями в важных столбцах (например, Location Description, Arrest, Domestic, и т.д.).
Преобразовала столбец Date в формат даты.
Преобразовала столбцы Arrest и Domestic в булев тип (True/False).
Проверила данные на пропуски и посмотрела основные статистики (describe()).

2. Визуализация
С помощью matplotlib построила графики:
Распределение преступлений по годам
Частота типов преступлений
Частота описаний мест, где происходили преступления (top-20)

3. Работа с PySpark
Установила и настроила PySpark
Загрузила CSV-файл с преступлениями
Создала временную таблицу и с помощью SQL-запроса посчитала количество преступлений по типу

Результат запроса: чаще всего встречаются такие преступления, как THEFT(кража), BATTERY(нападение), CRIMINAL DAMAGE(повреждение имущества).

Crimes_-_2001_to_Present.csv — набор данных из открытых источников Чикаго.
