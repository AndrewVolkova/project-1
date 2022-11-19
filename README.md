# Проект 1. Анализ данных вакансий из сайта HeadHunter

## Оглавление  
[1. Описание проекта](https://github.com/AndrewVolkova/project-1/blob/master/README.md#Описание-проекта)  
[2. Решаемая задача?](https://github.com/AndrewVolkova/project-1/blob/master/README.md#Решаемая-задача)  
[3. Информация о данных](https://github.com/AndrewVolkova/project-1/blob/master/README.md#Информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/AndrewVolkova/project-1/blob/master/README.md#Этапы-работы-над-проектом)  
[5. Результаты](https://github.com/AndrewVolkova/project-1/blob/master/README.md#Результаты)    
[6. Выводы](https://github.com/AndrewVolkova/project-1/blob/master/README.md#Выводы)


### Описание проекта

Проект, относящийся к зачетному проекту под названием "PROJECT-1. Анализ резюме из HeadHunter" блока 1-го. Знакомство с данными. Python для анализа данных,
учебной платформы SkillFactory, Профессия Data Science.
Задача проекта показать знания в следующих областях:
  * базовый анализ структуры данных,
  * преобразование данных,
  * исследование и очистка данных,
  * построение графиков

 ### Решаемая задача

Компания HeadHunter столкнулась с проблемой, что часть соискателей не указывает желаемую заработную плату, 
когда составляет своё резюме, или же указывает некорректные цифры, такие как суммы в другой валюте, или же просто 1, 
исключительно чтобы заполнить поле с желаемой зарплатой хоть какими-то данными.
Чтобы минимизировать такие ситуации, компания HeadHunter хочет построить модель, которая бы автоматически определяла 
примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе.

[К оглавлению](#оглавление)

### Информация о данных

1. Файл dst-3.0_16_1_hh_database.csv
* Содержит базу данных резюме выгруженную с сайта ваканский hh.ru 
* Данные охватывают период с 10 Апреля 2018 по 15 Мая 2019 по всем городам РФ.<br>
* Содержит около 45К записей
* Данный файл доступен для скачивания по ссылке

2. Файл ExchangeRates.csv
* Содержит данные о всех кросс курсах валют, встречающихся в разделе ожидаемая зарплата, за весь период данных о вакансиях
* Используется в процессе преобразования данных с целью привести Зарплату к одной валюте (Руб)
* Данный файл находится в папке data
* Сгенерировать новый файл можно на сайте  [MDF.RU](https://mfd.ru)


### Этапы работы над проектом
