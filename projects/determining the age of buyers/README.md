# Проект: Определение возраста покупателей


**Описание проекта**

Сетевой супермаркет «Хлеб-Соль» (название вымышленное) внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:

- Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
- Контролировать добросовестность кассиров при продаже алкоголя.

Необходимо построить модель, которая по фотографии определит приблизительный возраст человека. В моём распоряжении набор фотографий людей с указанием возраста.

Изучим имеющиеся данные и попытаемся построить модель компьютерного зрения для решения поставленной задачи.

Задачи:
- Провести исследовательский анализ набора фотографий.
- Подготовить данные к обучению.
- Обучить нейронную сеть и рассчитать её качество.
- Значение метрики **MAE** не должно быть выше значения: 8.

*Примечание:* Обучение нейронной сети выполнялось на GPU-процессорах. В тетради продемонстрирован код сборки нейронной сети, процесс и результаты обучения.

**Краткое содержание проекта**

1. Исследовательский анализ данных
2. Обучение модели
3. Анализ обученной модели

**Описание данных**

Данные взяты с сайта [ChaLearn Looking at People](http://chalearnlap.cvc.uab.es/dataset/26/description/).
В моём распоряжении папка с изображениями. И csv-файл: `labels.csv`, с двумя колонками: `file_name` и `real_age`. 

**Использованные библиотеки**

В проекте использовались следующие библиотеки:
- pandas
- numpy
- matplotlib
- PIL
- keras