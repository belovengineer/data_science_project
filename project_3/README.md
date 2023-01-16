# Проект 2. Прогнозирование оттока клиентов банка

![plot](/data/PS-21121-Appellate-Court-Opens-Door-for-New-Complaint-Against-Georgetown-530578254-web.jpg)

## Оглавление  
[1. Описание проекта](https://github.com/belovengineer/data_science_learn/tree/main/project_3/README.md#Описание-проекта)  
[2. Какой кейс решаем?](https://github.com/belovengineer/data_science_learn/tree/main/project_3/README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](https://github.com/belovengineer/data_science_learn/tree/main/project_3/README.md#Краткая-информация-о-данных)   
[4. Выводы](https://github.com/belovengineer/data_science_learn/tree/main/project_3/README.md#Выводы) 

### Описание проекта   
  
Создаем модель прогнозирования оттока клиентов из банка.

<b>Стэк-технологии:</b>
* Математические функции - NumPy   
* Обработка и анализ данных - Pandas  
* Визуализация данных - Matplotlib, Seaborn, Plotly  
* Машинное обучение - Scikit-learn  
  
:arrow_up: [К оглавлению](https://github.com/belovengineer/data_science_learn/tree/main/project_3/README.md#Оглавление)


### Какой кейс решаем?  
  
Спрогнозировать, перестанет ли клиент пользоваться услугами банка.
  
### Краткая информация о данных
  
<b>Напомним значения столбцов:</b>  
  
* RowNumber — номер строки таблицы;  
* CustomerId — идентификатор клиента;   
* Surname — фамилия клиента;  
* CreditScore — кредитный рейтинг клиента (чем он выше, тем больше клиент брал кредитов и возвращал их);  
* Geography — страна проживания клиента (банк межнациональный);  
* Gender — пол клиента;  
* Age — возраст клиента;  
* Tenure — сколько лет клиент пользуется банком;  
* Balance — сколько у клиента денег на счетах в банке;  
* NumOfProduct — число услуг банка, которые приобрёл клиент;  
* HasCrCard — есть ли у клиента кредитная карта (1 — да, 0 — нет);  
* IsActiveMember — есть ли у клиента статус активного участника банка (1 — да, 0 — нет);  
* EstimatedSalary — предполагаемая заработная плата клиента;  
* Exited — статус ушедшего (1 — ушедший клиент, 0 — лояльный клиент).   
    
:arrow_up: [К оглавлению](https://github.com/belovengineer/data_science_learn/tree/main/project_3/README.md#Оглавление)

### Выводы:  
* Для нашей задачи лучшая подобранная модель - RandomForest  
* Парамметры, которые дают лучший результат: n_estimators=500, max_depth=8, criterion='entropy'  
* Лучший показатель метрики F1 - 0.83

:arrow_up: [К оглавлению](https://github.com/belovengineer/data_science_learn/tree/main/project_3/README.md#Оглавление)


Если проект показался для Вас интересным - я буду очень рад, если Вы отметите репозиторий и профиль ⭐️