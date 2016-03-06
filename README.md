# potato-kagglers
:watermelon: Conquering Kaggle in collaboration

## План действий

1. Собираем команду желающих. Голосованием выбираем Kaggle competition, который будем с особым цинизмом пинать в данной итерации;
1. В течение `1-2 дней` смотрим на данные, делаем EDA, обсуждаем, у кого какие мысли и что с этим делать.
1. Скидываем ссылки на свое добро. `Кто-то`, кхм, их заботливо собирает их в один постик.
<!--Потом можно будет поделиться самыми яркими переживаниями.-->
1. В течение `нескольких дней` знакомимся с чужим кодом и результатами его исполнения. По идее, такой коллективный разум даст точку опоры для фича-инжиниринга и последующего возвращения к EDA.
1. Генерируем идеи: 1-3 предварительных варианта решения; или того, какие фичи построить; или что еще с этим сделать. Сперва пробуем самостоятельно, каждый сам по себе, а затем обмениваемся опытом.
1. Параллельно тестируем новые признаки. Анализируем их пользу и результат EDA в целом.

Уточнить/согласовать детали:
* `кто-то` → @demidovakatya,
* `несколько дней` → ???,
* `1-2 дня` → ???

## Exploratory data analyses

#### Итерация первая.
Разбираем [SF Crime](https://www.kaggle.com/c/sf-crime).

* https://github.com/tyz910/sf-crime-model/blob/master/02_model_tests.ipynb
* https://github.com/movb/kaggle/blob/master/sf-crime/gradienboost.ipynb
* https://github.com/kiote/kaggle/blob/master/sf-crime/basemodel.ipynb
* https://github.com/Jinxal/ML-Scripts/blob/master/sf_crime_sk.ipynb
* https://tyz910.github.io/sf-crime-map/ (on Kaggle: https://www.kaggle.com/tyz910/sf-crime/yet-another-map)
* http://rpubs.com/yurkai/SFCrimeEDA
* https://github.com/letfoolsdie/kaggle-SFCrime/blob/master/somewhatEDA.ipynb
* https://github.com/re9ulus/data_science_snippets/blob/master/eda/Crime_SF_EDA_by_re9ulus.ipynb

## План действий (с 03.03)

* загрузили данные;
* соорудили супер-модель;
* разбили кросс-валидацией данные;
* посчитали метрику кросс-валидации.

Для определенности:

```
метрика: логлосс
КФолд: 5
random_state: 42
```

Набросок ноутбука для дальнейшей работы («скелета»): https://github.com/yurkai/SFCrime/blob/master/template.ipynb
