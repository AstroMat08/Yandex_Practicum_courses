# Яндекс.Практикум
Здесь представлены завершенные проекты, которые были выполнены в рамках обучения на программе Data Scientist (Practicum by Yandex) https://practicum.yandex.com <br>
Проекты разделены на блоки: условно DA (первичная работа с данными) и DS (работа с данными + применение алгоритмов DS, работа с моделями)

## DA

Номер| Название проекта| Содержание файла | Навыки, библиотеки и инструменты
----------------|----------------|----------------------|----------------------
1 | [Исследование надёжности заёмщиков - финтех](https://github.com/AstroMat08/Yandex_Practicum_courses/tree/main/Data_preprocessing)   | На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок  | EDA, предобработка данных, Python, Pandas, pivot-tables
2 | [Недвижимость](https://github.com/AstroMat08/Yandex_Practicum_courses/tree/main/Sale_of_flats_in%20_StPetersburg)  | Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости. На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. | EDA, предобработка данных, Python, Pandas, pivot-tables, matplotlib
3 | [Поиск наиболее успешной платформы для игр](https://github.com/AstroMat08/Yandex_Practicum_courses/tree/main/Games)   | Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры | EDA, предобработка данных, Python, Pandas, pivot-tables, matplotlib, numpy, scipy, stats, критерии значимости, проверка null-гипотез (сравнение выборок)


## DS

Номер| Название проекта| Содержание файла | Стек
----------------|----------------|----------------------|----------------------
4 | [Тариф - телеком](https://github.com/AstroMat08/Yandex_Practicum_courses/tree/main/Determining_tariff)     | Разработать модель DS, которая бы предложила новый оптимальный тарифный план для каждого клиента оператора телеком. многие из его абонентов пользуются устаревшими тарифными планами. Они хотят разработать модель, которая будет анализировать поведение абонентов и рекомендовать один из новых тарифных планов Megaline: Smart или Ultra.  | EDA, предобработка данных, Python, Pandas, sklearn, DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, accuracy
5 | [Отток клиентов банка](https://github.com/AstroMat08/Yandex_Practicum_courses/tree/main/Forecasting_customer_churn)      | Из банка стали уходить клиенты каждый месяц. Спрогнозирована вероятность ухода клиента из банка в ближайшее время.  | EDA, предобработка данных, Python, Pandas, numpy, seaborn, matplotlib, sklearn, OHE, get_dummies, DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, best parameters, accuracy, precision, recall, f1, roc_auc
6 | [Нефтяное месторождение](https://github.com/AstroMat08/Yandex_Practicum_courses/tree/main/Oil_production_region)      | Выбрать один из трёх регионов для разработки нового нефтяного месторождения. Построена модель для предсказания объёма запасов в новых скважинах. Выбраны скважины с самыми высокими оценками значений. Определены регионы с максимальной суммарной прибылью отобранных скважин. Построена модель для определения региона, где добыча принесёт наибольшую прибыль. Проанализирована возможная прибыль и риски.   | EDA, предобработка данных, Python, Pandas, numpy, matplotlib, scipy.stats, LinearRegression, RandomForestRegressor, mean_squared_error, оценка рисков через доверительный интервал 
7 | [Оптимизация добычи золота](https://github.com/AstroMat08/Yandex_Practicum_courses/tree/main/Gold_refining_study)  | Компания разрабатывает решения для эффективной работы золотодобывающей отрасли. Построена модель, предсказывающая коэффициент восстановления золота из золотосодержащей руды. Проанализированы данные с параметрами добычи и очистки. Построена и обучена модель, помогающая оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.   | EDA, предобработка данных, Python, Pandas, numpy, matplotlib, LinearRegression, RandomForestRegressor, DummyRegressor, cross_val_score, mean_absolute_error, mean_squared_error
8 | [Cтрахование - поиск похожих клиентов](https://github.com/AstroMat08/Yandex_Practicum_courses/tree/main/Protecting_customer_data)     | Для защиты данных клиентов страховой компании разработаны методы преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Была проведена предобработка данных. Произведена проверка работы алгоритма модели линейной регрессии при перемножении на обратимую матрицу.   | Python, Pandas, numpy, matplotlib, seaborn, NearestNeighbors, KNeighborsClassifier
9 | [Цена авто](https://github.com/AstroMat08/Yandex_Practicum_courses/tree/main/Determining_value_of_a_car)    | Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. Проанализированы данные: технические характеристики, комплектации и цены автомобилей. Построена модель для определения стоимости автомобиля с пробегом. Использованы численные методы, приближённые вычисления, оценка сложности алгоритма, градиентный спуск.   | Python, Pandas, matplotlib, LinearRegression, RandomForestRegressor, CatBoostRegressor, lgbm
10 | [Прогноз заказов такси](https://github.com/AstroMat08/Yandex_Practicum_courses/tree/main/Forecasting_taxi_orders)     | Проанализированы исторические данные о заказах такси в аэропортах. Спрогнозировано количество заказов такси на следующий час, чтобы привлекать больше водителей в период пиковой нагрузки. Построена модель для такого предсказания.   | Python, Pandas, matplotlib, LinearRegression, RandomForestRegressor, CatBoostRegressor, временные ряды (statsmodels.tsa.seasonal)
11 | [Определение возраста покупателей](https://github.com/AstroMat08/Yandex_Practicum_courses/tree/main/Photo_processing)      | Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы: 1) Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы; 2) Контролировать добросовестность кассиров при продаже алкоголя.  | Pandas, atplotlib, numpy, seaborn, keras


## Стек технологий/инструменты/подходы:
- Bootstrap
- CatBoost
- LightGBM
- math
- Matplotlib
- NLTK
- numpy
- Pandas
- Python
- SciKitLearn
- SciPy
- Seaborn
- sklearn
- SQL
- StatsModels
- визуализация данных
- исследовательский анализ данных
- исследовательский анализ данных
- лемматизация
- машинное обучение
- описательная статистика
- предобработка данных
- проверка статистических гипотез

   
