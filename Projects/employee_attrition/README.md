# Задача

В этом проекте есть две части. Первая — построить регрессионную модель, способную предсказать уровень удовлетворенности сотрудников (используемая метрика была sMAPE = 13,68).

Затем мы построили модель классификации, чтобы иметь возможность предсказать, собирается ли сотрудник покинуть компанию или нет, используя результаты предыдущей регрессионной модели.  За исследованием последовала сегментация сотрудников на основе прогнозов модели. Стоит отметить, что цель была сбалансированной.

# Итоги

Используемая метрика была roc_auc, и дала нам результат 92,3% с RandomForestClassifier. 
Были даны рекомендации, чтобы помочь бизнесу сохранить своих сотрудников:
+ для молодых сотрудников, которые представляют самый большой процент увольняющихся : лучше интегрировать их, вовлекая в корпоративную жизнь компании и предоставляя качественное обучение и дальнейший карьерный рост 

+ для важних сотрудников, потеря которых представляет большой риск для компании : лучше ценить их, повышая их зарплаты (при анализе данных многие ушли, потому что не получили повышения зарплаты), предоставлять возможности карьерного роста, заботиться об их личных ценностях (например, здоровье, предлагая развернутую медицинскую страховку или оказывать финансовую помощь для учебы детей, если таковая имеется) 

# Технический стек

+ Python
+ Pandas
+ Matplotlib/Seaborn
+ Scikit-learn
+ Shap

<br/><br/>

# Task

This project was divided in two parts. The first task was to build a regression model able to predict the satisfaction rate of the employees (the metric used was sMAPE = 13.68).

Then the second task was to build a classification model to be able to predict if an employee was going to leave the company or not, using the results from the previous regression model.It worth noting that the target was balanced. The study was followed by a segmentation of the employees based on the model's predictions. 

# Results

The metric used was roc_auc, and gave us a result of 92.3% with RandomForestClassifier. 

Recommendations has been made to help the business to keep his employees:
+ for young employees, who represent the largest percentage of those leaving: better integrate them by involving them into the corporate life of the company and providing quality training and further career growth

+ for important employees, whose loss is a great risk for the company: it is better to value them by increasing their salaries (in the EDA, we saw that many left because they did not receive a raise in the previous year), providing opportunities for their career growth, taking care of them on a more personal basis  ​​(e.g. health, by offering comprehensive health insurance or providing financial assistance for children's education, if needed)

# Tech stack

+ Python
+ Scipy
+ Matplotlib/Seaborn
+ Scikit-learn
+ Shap




