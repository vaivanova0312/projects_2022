# projects_2022

Этот репозиторий в основном предназначен для проектов, которые я сделала во время обучения на аналитика данных в Яндекс.Практикум.

В течение обучения я научилась проводить обработку данных, проводить исследовательский и статистический анализ, выявлять закономерности, проводить А/В-тестирование, разбираться в юнит-экономике, использовать машинное обучение и на основании полученной информации делать обоснованные выводы. Также создавать дашборды, презентации и использовать SQL-запросы. 

Рекомендации: для корректной работы с моими проектами необходимо установить основные библиотеки Python (numpy, pandas, scipy, scikit-learn, matplotlib, seaborn, plotly, math).

##  1. Статистический анализ данных

### Название проекта

Определение выгодного тарифа для телеком компании

### Цель проекта

На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа

### Описание проекта

Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка данных, их анализ.Проверены гипотезы о различии выручки абонентов разных тарифов и
различии выручки абонентов из Москвы и других регионов.

##  2. Сборный проект_1

### Название проекта

Выявление закономерностей, определяющих успешность игры для интернет-магазина компьютерных игр

### Цель проекта

Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры 

### Описание проекта

Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовал критерий Стьюдента для независимых выборок.

##  3. Анализ бизнес-показателей

### Название проекта

Анализ бизнес-показателей развлекательного приложения Procrastinate Pro+

### Цель проекта

Задача для маркетингового аналитика развлекательного приложения Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Необходимо разобраться в причинах и помочь компании выйти в плюс.

### Описание проекта

Проведен анализ данных от ProcrastinatePRO+. Рассчитаны различные метрики, использован когортный анализ: LTV, CAC, ROI, Retention rate и т.д. Использованы уже написанные ранее функции расчёта метрик. Сделаны правильные выводы по полученным данным.

##  4. Принятие решений в бизнесе

### Название проекта

Проверка гипотез по увеличению выручки в интернет-магазине - оценить результаты A/B теста

### Цель проекта

Используя данные интернет-магазина приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами

### Описание проекта

Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем проведен анализ результатов A/B-теста, построены графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитана статистическая значимость различий конверсий
и средних чеков по сырым и очищенным данным. На основании анализа было принято решение о нецелесообразности дальнейшего проведения теста.

##  5. Сборный проект — 2 

### Название проекта

Изучение поведения пользователей мобильного приложения продажи продуктов питания

### Цель проекта

На основе данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж, а также оценить результаты A/A/B-тестирования

### Описание проекта

Были изучены принципы событийной аналитики. Построена
воронка продаж, исследован путь пользователей до покупки. Проанализированы результаты A/B-теста введения новых шрифтов. Произведено сравнение 2 контрольных группы между собой, убедились в правильном разделении трафика, а затем сравнили с тестовой группой. Выявлено, что новый шрифт значительно не повлияет на поведение пользователей.

##  6. Основы машинного обучения

### Название проекта

Анализ и план действий по удержанию клиентов сети фитнес-центров

### Цель проекта

На основе данных о посетителях сети фитнес-центров спрогнозировать вероятность оттока для каждого клиента в следующем месяце, сформировать с помощью кластеризации портреты пользователей

### Описание проекта

В данном проекте использовано машинное обучение. Спрогнозирована вероятность оттока (на уровне следующего месяца) для каждого клиента; сформированы типичные портреты пользователей: выделены наиболее яркие группы, охарактеризованы их основные свойства; проанализированы основные признаки, наиболее сильно влияющие
на отток.

##  7. Выпускной проект_моб.приложение

### Название проекта

Выделение групп на основе поведения пользователей мобильного приложения продажи ненужных вещей

### Цель проекта

На основании поведения пользователей определить: кто склонен возвращаться в мобильное приложение (Retention Rate); кто часто совершает целевое действие (просмотр контактов) и как различается время между распространенными событиями пользователей.

### Описание проекта

Проведено изучение метрик вовлеченности пользователей (DAU, WAU, средняя продолжительность сессии, трекинг событий, конверсия в целевое действие). Проведено сегментирование пользователей на 2 группы на основе действий. Для каждой группы было выявлено кто склонен возвращаться, просматривать контакты и как различается время между распространенными событиями пользователей. Проведена проверка  2гипотез: конверсия в просмотры контактов пользователей, установивших приложение по ссылке из yandex и google различаются; конверсия в просмотры контактов пользователей, кликнувших рекомендованные объявления и добавивших объявление в избранное различаются. Были сделаны выводы, что повысит эффективность приложения и даны рекомендации. Также по
результатам была подготовлена презентация с полученными графиками и дашборд распределения количества событий по типу с фильтрами.

##  8. SQL

### Название проекта

Анализ базы данных электронных книг

### Цель проекта

Анализ базы данных c информацией о книгах, издательствах, авторах, а также пользовательские обзоры книг для дальнейшего формирования ценностного предложения для нового продукта.

### Описание проекта

С помощью SQL-запросов были получены ответы на основные вопросы:
    - сколько книг вышло после 1 января 2000 года;
    - какое количество обзоров и какая средняя оценка для каждой книги;
    - какое издательство выпустило наибольшее число книг толще 50 страниц;
    - какой автор с самой высокой средней оценкой книг;
    - какое среднее количество обзоров от пользователей, которые поставили больше 50 оценок.
