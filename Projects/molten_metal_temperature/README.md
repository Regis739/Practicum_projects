# Задача

У нас была база данных с большим количеством таблиц, после их изучения мы проверили:
+ пропущенные значения
+ дубликаты
+ аномалии
+ выполнили некоторые features enginnering
+ выполнили EDA
+ нашли лучшую модель с помощью перекрестной проверки
+ выполнили анализ важности функций

# Итоги

Одна вещь, которую мы заметили во время EDA, — это выбросы, в основном происходящие из необычно длительных процессов очистки (около 2% набора данных). Среднее время процесса должно составлять около 45 минут, однако иногда очистка длится дольше, поскольку сталь еще не была готова (не достигла желаемых свойств). Эти выбросы определенно могут негативно повлиять на эффективность нашей модели.

В этом проекте мы предложили модель для прогнозирования этой температуры, чтобы иметь возможность улучшить использование электродов и сократить счета за электроэнергию.
Лучшая найденная оценка была: SVR с MAE 6,07 в тестовом наборе данных.

Мы также рекомендуем тщательно контролировать входную температуру и время использования электродов, чтобы оптимизировать процесс очистки в ковше.

# Технический стек

+ Python
+ SQL
+ Pandas
+ Matplotlib/Seaborn
+ Scikit-learn

<br/><br/>

# Task

We had a database with lot of tables, after studying them and have checked for :
+ missing values
+ duplicates
+ anomalies
then we have:
+ created some features enginnering
+ done EDA
+ found the best model through cross-validation
+ done a feature importance analysis


# Results

One thing we have noticed during the EDA was outliers mainly coming from unusually long refining processes (about 2% of the dataset). The average time of the process should be about 45 minutes, however sometimes the refining last longer because the steel was not ready yet (did not reach the wanted properties). These outliers can definitely impact negatively the performance of our model.

In this project we have proposed a model to predict this temperature in order to be able to improve the usage of the electrodes and reduce the electric bill.
The best estimator found was : SVR with a MAE of 6.07 on the test dataset.
We have also recommended to monitor tightly the input temperature and the usage time of the electrodes in order to optimize the process of ladle refining.

# Tech stack

+ Python
+ SQL
+ Pandas
+ Matplotlib/Seaborn
+ Scikit-learn



