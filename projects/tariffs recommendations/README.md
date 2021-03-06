# Проект: Рекомендации тарифов


**Описание проекта**

В рамках сотрудничества с телеком компанией "Мегалайн" (название вымышленное), с которой уже проводился [анализ по определению перспективного тарифа](https://github.com/lobjob/Yandex_Practicum_projects/tree/main/projects/tariffs%20of%20a%20telecom%20company%20analysis "Перейти в папку проекта"), поступила заявка на построение модели машинного обучения для рекомендации тарифа абонентам на основе их использования связи.

Даны данные о поведении клиентов, которые уже перешли на тарифы "Смарт" и "Ультра". Нужно построить модель машинного обучения для задачи классификации, которая выберет подходящий тариф.

Нужно построить модель с максимально большим значением accuracy. Довести долю правильных ответов по крайней мере до 0.75. Проверить accuracy на тестовой выборке.


**Краткое содержание проекта**

1. Открытие и изучение данных
2. Разделение данных на выборки
3. Исследования моделей
4. Проверка моделей на тестовой выборке
5. Выводы
6. Доп.: Проверка лучшей модели на адекватность

**Описание данных**

Файл с данными: `users_behavior.csv`

Колонки в данных:
- `сalls` — количество звонков;
- `minutes` — суммарная длительность звонков в минутах;
- `messages` — количество sms-сообщений;
- `mb_used` — израсходованный интернет-трафик в Мб;
- `is_ultra` — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).

**Использованные библиотеки**

В проекте использовались следующие библиотеки:
- pandas
- sklearn