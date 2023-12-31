# [Исследования рынка общепита в Москве для принятия решения об открытии нового заведения](moscow_cafe_project.ipynb)

## Описание проекта

В данной работе нам предстоит проанализировать рынок общественного питания в Москве с целью выявить особенности рынка и ответить на поставленные вопросы:
* Какие категории заведений преобладают в Москве?
* Какие категории заведений чаще являются сетевыми? 
* Какие сети самые популярные в Москве?
* В каких районах Москвы самый высокий средний чек?
и другие.

## Описание данных:

* `name` — название заведения;
* `address` — адрес заведения;
* `category` — категория заведения;
* `hours` — информация о днях и часах работы;
* `lat` — широта географической точки, в которой находится заведение;
* `lng` — долгота географической точки, в которой находится заведение;
* `rating` — рейтинг заведения по оценкам пользователей в Яндекс Картах;
* `price` — категория цен в заведении;
* `avg_bill` — средняя стоимость заказа в виде диапазона;
* `middle_avg_bill` — число с оценкой среднего чека, которое указано только для значений из столбца `avg_bill`;
* `middle_coffee_cup` — число с оценкой одной чашки капучино, которое указано только для значений из столбца `avg_bill`;
* `chain` — является ли заведение сетевым;
* `district` — административный район, в котором находится заведение;
* `seats` — количество посадочных мест.

## Используемые навыки и инструменты

`pandas` `seaborn` `plotly` `folium` `Визуализация данных`
