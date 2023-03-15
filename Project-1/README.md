# Описание [проекта](https://github.com/aleksandr-del/yandex-praticum-projects/blob/main/Project-1/yandex_practicum_calculus_project.ipynb)

Сервис по продаже автомобилей с пробегом разрабатывает приложение, чтобы привлечь новых клиентов. В нём можно будет узнать рыночную стоимость своего автомобиля. Целью настоящего проекта являетс модель, которая умеет определять стоимость автомобиля. Заказчику важны качество предсказания, время обучения модели и время предсказания модели.

# Навыки и инструменты

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Sklearn.linear_model LinearRegression, Ridge
- Sklearn.model_selection GridSearchCV, cross_validate, train_test_split
- Sklearn.metrics r2_score, mean_squared_error, make_scorer
- Sklearn.ensemble RandomForestRegressor

# Общий вывод

Вывод

При работе над проектом были:
1. изучены и подготовлены данные;
2. пропуски в категориальных признаках заполнены новым категориальным значением; из данных удалены наблюдения с аномальными значениями;
3. с помощью кросс-валидации и подбора гипарпараметров обучены и оценены модели на тестовой выборке
