Анализ поведения пользователей в мобильном приложении
Задача:
Проанализируйте связь целевого события — просмотра контактов — и других действий пользователей.
Оцените, какие действия чаще совершают те пользователи, которые просматривают контакты.
Проведите исследовательский анализ данных
Проанализируйте влияние событий на совершение целевого события
Проверьте статистические гипотезы
Одни пользователи совершают действия tips_show и tips_click , другие —только tips_show . Проверьте гипотезу: конверсия в просмотры контактов различается у этих двух групп.
Сформулируйте собственную статистическую гипотезу. Дополните её нулевой и альтернативной гипотезами. Проверьте гипотезу с помощью статистического теста.
1  Описание данных:
Датасет содержит данные о событиях, совершенных в мобильном приложении "Ненужные вещи". В нем пользователи продают свои ненужные вещи, размещая их на доске объявлений.
В датасете содержатся данные пользователей, впервые совершивших действия в приложении после 7 октября 2019 года.
Декомпозиция
Цели исследования:
Управление вовлеченностью клиентов (адаптация приложения по целевой и смежной аудитории) будет актуально только на основе данных о поведении пользователей.
Получить на основе поведения пользователей гипотезы о том как можно было бы улучшить приложение с точки зрения пользовательского опыта.
Шаг 1. Открыть файлы с данными и изучите общую информацию
Шаг 2. Подготовка данных
Замена столбцов, приведение к нужному типу данных, просмотр дубликатов и пропусков, если требуется и удаление их.
Шаг 3. Проведите исследовательский анализ данных
Выбираем тайм-аут, приводя агрументы
Построить диаграмму тайм-аут, выведя выбросы и аномалии
Веделение сесиии
Поиск сценариев
Простмотр повторовяющихся событий в рамках сессии
Удаление повторяющихся событий
Проверка временного интервала
Источник перехода
Количество событий в приложении
Количество просмотров контактов по источникам
Просмотр контактов
Действия пользователя, совершивший просмотр контактов
Посчитать конверсию каждого действия в показ контактов
Рассчитать время пользования приложением каждым пользователем
Рассчитать минимальное, максимальное и среднее количество сессий на пользователя и ее длительность.
Посмотреть популярные действия пользователей, запустившие приложение
Анализ событий
Проанализируйте связь целевого события — просмотра контактов — и других действий пользователей:
В разрезе сессий отобрать сценарии\паттерны, которые приводят к просмотру контактов
Построить воронки по основным сценариям в разрезе уникальных пользователей
Как различается время между событиями map -> contacts_show и search -> contacts_show в рамках сессий?
Оцените, какие действия чаще совершают те пользователи, которые просматривают контакты:
Рассчитать частоту событий в разрезе пользователей с contacts_show и без него
Шаг 4. Проверка гипотез:
Одни пользователи совершают действия tips_show и tips_click , другие —только tips_show . Проверьте гипотезу: конверсия в просмотры контактов различается у этих двух групп.
где, tips_show — увидел рекомендованные объявления, tips_click — кликнул по рекомендованному объявлению.
Одни пользователи добавляют объявление в избранное, только, после открытия карточки advert_open, другие - без открытия карточки. Проверьте гипотезу: конверсия в просмотры контактов различаются у этих двух групп.
где, advert_open- открыл карточки объявления.
Шаг 5. Рекомендации заказчику, выводы
