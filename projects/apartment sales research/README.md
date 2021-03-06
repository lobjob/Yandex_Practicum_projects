# Проект: Исследование объявлений по продаже квартир

**Описание проекта**

Мы получили данные сервиса "СПБ-Недвижимость" (название вымышленное). В них содержится информация по продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. В этих данных надо определить рыночную стоимость недвижимости и установить параметры, а так-же необходимо проанализировать данные и сделать выводы по ряду показателей. Это поможет создать автоматизированную систему, которая отследит аномалии и мошенническую деятельность. Часть этих данных внесены пользователями, а часть получена автоматически на основании картографических данных. 

**Краткое содержание проекта**

1. Открытие файла с данными и изучение общей информации
2. Предобработка данных
3. Подсчёт необходимых метрик и добавление их в таблицу
4. Проведение исследовательского анализа данных и выполнение инструкций
5. Общий вывод

**Описание данных**

Файл с данными по продаже квартир: `real_estate_data.csv`

Таблица имеет колонки:
- `airports_nearest` — расстояние до ближайшего аэропорта в метрах (м)
- `balcony` — число балконов
- `ceiling_height` — высота потолков (м)
- `cityCenters_nearest` — расстояние до центра города (м)
- `days_exposition` — сколько дней было размещено объявление (от публикации до снятия)
- `first_day_exposition` — дата публикации
- `floor` — этаж
- `floors_total` — всего этажей в доме
- `is_apartment` — апартаменты (булев тип)
- `kitchen_area` — площадь кухни в квадратных метрах (м²)
- `last_price` — цена на момент снятия с публикации
- `living_area` — жилая площадь в квадратных метрах(м²)
- `locality_name` — название населённого пункта
- `open_plan` — свободная планировка (булев тип)
- `parks_around3000` — число парков в радиусе 3 км
- `parks_nearest` — расстояние до ближайшего парка (м)
- `ponds_around3000` — число водоёмов в радиусе 3 км
- `ponds_nearest` — расстояние до ближайшего водоёма (м)
- `rooms` — число комнат
- `studio` — квартира-студия (булев тип)
- `total_area` — площадь квартиры в квадратных метрах (м²)
- `total_images` — число фотографий квартиры в объявлении


**Использованные библиотеки**

В проекте использовались следующие библиотеки:
- pandas
- numpy
- re
- matplotlib
- seaborn
