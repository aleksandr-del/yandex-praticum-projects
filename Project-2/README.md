# Описание [проекта](https://github.com/aleksandr-del/yandex-praticum-projects/blob/main/Project-2/yandex_practicum_final_project.ipynb)

Чтобы оптимизировать производственные расходы, металлургический комбинат решил уменьшить потребление электроэнергии на этапе обработки стали. В настоящем проекте нам предстоит построить модель, которая предскажет температуру стали.

# Навыки и инструменты

- Pandas
- Numpy
- Matplotlib
- Sklearn.model_selection train_test_split, GridSearchCV, KFold
- Sklearn.metrics r2_score, mean_absolute_error, make_scorer
- Sklearn.pipeline make_pipeline, Pipeline
- Sklearn.preprocessing StandardScaler
- Sklearn.compose ColumnTransformer
- Sklearn.linear_model Lasso
- Sklearn.tree DecisionTreeRegressor

# Общий вывод

В ходе работы над проектом было сделано следующее:

1. изучены данные и распределения признаков;
2. предобработали данные из таблиц;
3. обучили алгоритм линейной регрессии с регуляризацией с помощью кросс-валидации;
4. создали класс градиентного бустинга с методами fit и predict и с помощью кросс-валидации обучили алгоритм.
