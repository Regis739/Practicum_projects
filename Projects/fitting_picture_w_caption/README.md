# Задача

Целью проекта было предсказать лучшую картинку для заданной подписи. Для этого, используя имеющиеся данные, мы векторизовали картинки с помощью ResNet18, а подпись — с помощью BERT.

Целевым признаком были оценки, сделанные группой избирателей. Параллельно мы также экспериментировали с использованием оценки BERT в качестве цели, чтобы посмотреть, может ли это дать лучшие результаты.

# Итоги

Наша лучшая модель — SVR, однако наша метрика MAE была не так уж далека от метрики DummyRegressor. Тестирование нашей модели показало, что она не очень хорошо угадывала правильную картинку для заданного запроса с оценками избирателей и оценкой BERT.

Таким образом, мы можем предположить, что способ построения модели — векторизация картинок и подписей + оценки человека в качестве цели — не было оптимальным. Напротив, использование косинусных сходств с библиотекой CLIP дало нам лучший результат.

# Технический стек

+ Python
+ Pandas
+ Matplotlib/Seaborn
+ Scikit-learn
+ ResNet18
+ BERT
+ CLIP

<br/><br/>

# Tasks

The goal of the project was to predict the best picture, for a given caption. To do so, using the data available, we have vectorized the pictures with ResNet18 and the caption with BERT. The target feature was evaluations made by a group of voters. 

In parallel, we have also experimented using BERT score as a target to see if this could give a better result.

# Results

Our best model was SVR, however our MAE metric was not far from the one from the DummyRegressor. The testing of our model shows that it was not very good at guessing the right picture for a given query, with the voter's evaluations and the BERT score.

Thus we can suppose that the way of how the model was built, vectorization of pictures and captions using human's evaluations as a target, was not optimal. On the contrary using cosine similarities with the library CLIP gave us a better result. 

# Tech stack

+ Python
+ Pandas
+ Matplotlib/Seaborn
+ Scikit-learn
+ ResNet18
+ BERT
+ CLIP


