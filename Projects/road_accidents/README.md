# Задача

У нас была база данных, и мы использовали несколько SQL-запросов для ее изучения. Затем нам пришлось использовать SQL-запрос для извлечения датафрейм, над которым мы собирались работать. Ключевым моментом в этом проекте был правильный выбор функций для использования. Действительно, некоторые из них были результатом ДТП, и их использование привело бы к утечке данных. 

# Итоги

В результате лучшей моделью стал RandomForestClassifier. Наши метрики roc_auc составили 73%.
Наиболее важными характеристиками были стоимость страховой премии (обычно стоимость высока для категорий, склонных к авариям, например, для молодых водителей), состояние трезвости водителя, тип транспортного средства, возраст транспортного средства и физическое состояние водителя.
Вот почему система измерения состояния трезвости водителя может использоваться компанией каршеринга для предотвращения ДТП.

# Технический стек
+ Python
+ Pandas
+ Matplotlib/Seaborn
+ Scikit-learn
+ SQL
+ Shap

# Task

+ A database have been provided, and we have used some SQL queries to study it. 
+ Then we had to use a SQL query to extract the dataframe that we were going to work with.
+ The key moment in this project was to select correctly the features to use. Indeed some of them were the result of the accident and using them would have resulted in a data leakage.

# Results

As a result, our best model was RandomForestClassifier. Our roc_auc metrics was equal to 73%.
The most important features were the price of the insurance premium (usually the price is high for categories prone to have an accident like young drivers for example), the state of sobriety of the driver, the type of vehicles the age of the vehicle and the physical state of the driver.
This is why a system to measures the driver's state of sobriety could be used by the car sharing company to avoid accident.

# Tech stack

+ Python
+ Pandas
+ Matplotlib/Seaborn
+ Scikit-learn
+ SQL
+ Shap
