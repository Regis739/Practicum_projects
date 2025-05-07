# Задача

Для этого исследования мы, как обычно, проверили отсутствующие значения, аномалии и дубликаты. В ходе этого исследования мы заметили, что звезды кажутся неправильно классифицированными по цвету. 

Затем мы провели эксперимент, чтобы увидеть влияние этой неправильной классификации. 

Используя пайплайн для предотвращения утечки данных, мы также тщательно масштабировали и кодировали необходимые функции перед созданием нашей нейронной сети. Также тщательно масштабировали и кодировали необходимые признаки перед построением нашей нейронной сети.

# Результаты

Неправильная классификация звезд по цвету увеличивала наши ошибки. Классифицируя их правильно, мы смогли получить удовлетворительный результат для этого исследования со среднеквадратичной погрешностью 2634 К.

Мы выяснили, что одним из ключевых признаков датасета для получения хорошего результата был цвет звезды. Однако, многие из этих звезд оказались неправильно классифицированными в наборе данных, что увеличивало нашу ошибку.

# Технический стек

+ Python
+ Pandas
+ Matplotlib/Seaborn
+ Scikit-learn
+ Pytorch

<br/><br/>

# Task

For this project we did as usual, check for :
+ missing values,
+ anomalies,
+ duplicates.

During this study, we noticed that stars appeared misclassified by their color. 

We then have experimented to see the impact of this misclassification. 

Using a pipeline to avoid data leakage, we also carefully scaled and encoded the needed features before building our neural network.

# Results

The misclassification of stars by their colors were increasing our errors. By classify them correctly we have been able to obtain a satisfactory result for this study with a RMSE of 2634 K. 

A graphic showing comparison between the true temperatures and the predicted temperatures has been plotted to show the effectiveness of our neural network. We have figured out that one of the key feature of the dataset to obtain a good result was the color of the star. 

# Tech stack

+ Python
+ Pandas
+ Matplotlib/Seaborn
+ Scikit-learn
+ Pytorch
