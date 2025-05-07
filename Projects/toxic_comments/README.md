# Задача

Целью этого проекта было создание модели, способной определять, являются ли комментарии из вики токсичными или нет. Перед обучением нашей модели мы подготовили наши данные с помощью библиотеки «re», чтобы иметь возможность векторизовать наши комментарии с помощью TFIDFvectorizer из библиотеки sklearn.

# Итоги

В результате, нашей лучшей моделью стала LogisticRegression, которая дала нам оценку F1 82% на нашем тестовом наборе данных.

# Технический стек

+ Python (re)
+ Pandas
+ Matplotlib/Seaborn
+ NLTK
+ Scikit-learn (TFIDFvectorizer, RandomizedSearchCV, f1_score)

<br/><br/>

# Task

The goal of this project was to create a model capable to determine if comments from wiki were toxic or not. Prior to training our model, we prepared our data with the 're' library, in order to be able to vectorized our comments with TFIDFvectorizer from the library sklearn.

# Results

As a result, our best model was LogisticRegression which gave us a F1 score of 82% on our test dataset.

# Tech stack

+ Python (re)
+ Pandas
+ Matplotlib/Seaborn
+ NLTK
+ Scikit-learn (TFIDFvectorizer, RandomizedSearchCV, f1_score)

