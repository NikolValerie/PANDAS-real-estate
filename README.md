# Введение
В датасете хранятся данные о квартирах в городе Москва, данные взяты с площадки "Циан" и включают в себя разнообразную информацию о квартирах.
# Структура проекта
Датасет оформлен в виде таблице, каждая строка отображает 1 объявление на площадке, всего в датасете 19737 строк и 21 столбик.
# Работа над проектом
Нам даны данные по 23368 квартирам. Нам необходимо подготовить данные для разработчиков машинного обучения.
Для этого нам надо изучить и преобразовать данные для них. 
Они на результатах нашей работы будут учить модели предсказывать стоимость аренды квартир по Москве
Над проектом работают Токтабеков Бауржан, Николаева Валерия, Чимов Степан, Мартиросян Левон.
# Ход нашей работы 
*1*. Анализ имеющихся данных.
Для начала мы в целом оценили, какие признаки нам нужны, а какие можно убрать. Разделили фичи между собой, и сделали небольшой анализ с помощью графиков (EDA.html).
*2*. Препроцессинг данных.
Удалили ещё больше данных :) оставили самое нужное, заполнили ячейки типа NaN. Также для некоторых признаков было намешано много информации, поэтому нужно было разделить её и создать новые фичи. Все категориальные признаки заменили на числа для возможности обучения моделей.
*3*. **Финальный коммит**. 
Удилили все дубликаты и оставили признаки только типа int и float. 
Теперь можно приступать к работе с данными :)
