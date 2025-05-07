# Задача

Для временных рядов задачи немного отличаются от задач для обычного набора данных. Нам нужно было проверить, был ли наш индекс монотонным, и выполнить повторную выборку с использованием суммы. Затем мы изучаем тренд и сезонность. После EDA мы:
+ выполняем некоторую разработку признаков,
+ обучаем нашу модель с помощью перекрестной проверки TimeSeriesSplit,
+ прогнозируем количество заказов за две последние недели набора данных, 
+ проверяем нашу модель с помощью базовой линии. 

# Итоги

В этом проекте feature engineering было ключевым для получения хорошего RMSE. После EDA мы увидели, что у нас есть сезонность, основанная на днях и неделях. Признаки, созданные на целой неделе, дали нам лучшую оценку RMSE (max_lag и rolling_avg_size равны 168 часам).

# Технический стек

+ Python
+ Pandas
+ Matplotlib/Seaborn
+ Statsmodels 
+ Scikit-learn

<br/><br/>

# Task

For time series, tasks are usually little bit different than for usual dataset. We had to check if our indexes were monotonic and perform resampling using the sum. We then study the trend and the seasonality. After the EDA, we :
+ perform some features engineering, 
+ trained our model with cross-validation using TimeSeriesSplit, 
+ predict the number of orders for the two last weeks of the dataset
+ check our model using a baseline

# Results

In this project, the features engineering was key to obtain a good RMSE. After the EDA, we saw that we had a seasonality based on days and on weeks. Features created on the whole week gave us a better RMSE score (max_lag and rolling_avg_size equal to 168 hours).

# Tech stack

+ Python
+ Pandas
+ Matplotlib/Seaborn
+ Statsmodels 
+ Scikit-learn


