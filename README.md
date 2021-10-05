## $f(X)=9+3.5⋅cos[(x−30)/(12)]$
## n_all=450, n_all=400, n_all=350


## Вывод к Задаче 1 

Наилучшим числом степеней свободы для данной модели является "6", так при нём достигается минимальная ошибка MSE на тестовой выборке (ошибки на обучающей и тестовой выборках составили 1.110859 и 1.475303 соответсвенно).


## Вывод к Задаче 2
Данные для анализа: 

Для n_all = 450: 

Ошибки на обучающей и тестовой выборках:
MSE Train = 1.06
MSE Test = 0.93

Наименьший показатель MSE: 
число степеней свободы: 15
MSE Train = 1.139117
MSE Test = 0.853463

Для n_all = 400: 

Ошибки на обучающей и тестовой выборках:
MSE Train = 0.99
MSE Test = 0.84

Наименьший показатель MSE:
число степеней свободы: 7
MSE Train = 1.177642
MSE Test = 19.478629

Для n_all = 300: 

Ошибки на обучающей и тестовой выборках:
MSE Train = 0.90
MSE Test = 0.68

Наименьший показатель MSE:
число степеней свободы: 15
MSE Train = 0.981223
MSE Test = 0.625849

Выводы:
При уменьшении значения n_all ошибки на тестовой выборке уменьшаются.
Лучшую модель следуют выбирать по минимуму на кривой MSE на тестовой выборке, поэтому если выбирать из этих трех моделей, то лучшая при n_all = 300, т.к. в ней ошибка на тестовой выборке минимальна.
