Pashnina Alyona Konstantinovna
ПМИ_3-1

16 вариант:
f(X) = 25 + 0.02x − 0.003(x − 45)^2 + 0.00006(x - 54)^3
train_percent = 0.3, 0.25, 0.2

Вывод к 1 задаче:

Наилучшее число степеней свободы для данной модели - 2, поскольку при нем достигается минимальная ошибка на тестовой выборке.

Вывод к 2 задаче:

Для train_percent = 0.3:
Ошибки на обучающей и тестовой выборках:
* MSE Train = 0.53
* MSE Test = 335.02

Наименьший показатель MSE достигается при числе степеней свободы равном 2:
* MSE Train = 3.372475    
* MSE Test = 8.657168

Для train_percent = 0.25:
Ошибки на обучающей и тестовой выборках:
* MSE Train = 1.19
* MSE Test = 753.79

Наименьший показатель MSE достигается при числе степеней свободы равном 2:
* MSE Train = 7.588069    
* MSE Test = 19.478629

Для train_percent = 0.2:
Ошибки на обучающей и тестовой выборках:
* MSE Train = 2.12
* MSE Test = 1340.07

Наименьший показатель MSE достигается при числе степеней свободы равном 2:
* MSE Train = 13.489901    
* MSE Test = 34.628673

Выводы:
* При увеличении значения sigma, увеличиваются ошибки как на тренировочной выборке, так и на тестовой (примерно в 2 раза).
* С ростом числа степеней свободы, ошибки на тестовых выборках моделей увеличиваются, происходит переобучение.
* Если выбирать из этих трех моделей, то лучшая при sigma = 2, т.к. в ней ошибка на тестовой выборке минимальна (а если учитывать при sigma = 1 из задачи 1, то наилучшей будет она, там ошибка еще меньше).
