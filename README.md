# Karpov_Courses

# Проект e-commerce
Исследуемый набор данных: таблица с уникальными идентификаторами пользователей, таблица заказов, таблица с товарными позициями, входящими в заказы.

Суть проекта: этом проекте я проанализировала совершенные покупки, сделала когортный анализ и выяви когорту с самым высоким retention на 3й месяц. Для качественного анализа аудитории выполнила RFM-анализ.
Используемые библиотеки: pandas, seaborn, matplotlib, numpy, pandahouse, requests, urlencode.

# Проект my_final_project:
Исследуемый набор данных: таблица с информацией о принадлежности пользователей к контройльной или экспериментальной группе, файл с информацией о пользователях, которые зашли на платформу в дни проведения эксперимента, файл с информацией об оплатах пользователей в дни проведения эксперимента

Суть проекта: 
1. В ходе тестирования одной гипотезы целевой группе была предложена новая механика оплаты услуг на сайте, у контрольной группы оставалась базовая механика. Я проанализировала итоги эксперимента и сделала вывод, стоит ли запускать новую механику оплаты на всех пользователей.
- для анализа итогов эксперимента выбраны две метрики: средний чек (средняя стоимость одной покупки) и конверсия в покупку
- чтобы оценить успешность эксперимента были проведены тесты: bootsrap и хи-квадрат
2. Напиcала оптимальный запрос в ClickHouse, который подсчитаывает следующие метрики:
- ARPU 
- ARPAU 
- CR в покупку 
- СR активного пользователя в покупку 
- CR пользователя из активности по математике (subject = ’math’) в покупку курса по математике
3. Реализовала функцию, которая автоматически подгружает информацию из дополнительного файла groups_add.csv и на основании дополнительных параметров пересчитывает метрики и строит графики
Используемые библиотеки: pandas, numpy, scipy.stats, matplotlib, pandahouse, requests, urlencode

