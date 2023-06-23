# Выпускной проект: Промышленность.
[HTML ipynb](https://github.com/viktor-kuzmin-28/practicum_yandex/blob/main/Промышленность/Промышленность.ipynb)

## Описание проекта

Чтобы оптимизировать производственные расходы, металлургический комбинат ООО «Так закаляем сталь» решил уменьшить потребление электроэнергии на этапе обработки стали. Нам предстоит построить модель, которая предскажет температуру стали.

## Навыки и инструменты

- pandas
- numpy
- seaborn
- matplotlib.pyplot
- tqdm
- sklearn.metrics.mean_squared_error
- sklearn.preprocessing.StandardScaler
- sklearn.linear_model.LinearRegression
- sklearn.ensemble.RandomForestRegressor
- catboost.CatBoostRegressor
- sklearn.model_selection.train_test_split
- sklearn.model_selection.RandomizedSearchCV

## Вывод по итогам исследования
Данные были обработаны от артефактов (согласованных с заказчиком). Была собрана общая таблица признаков, исключены признаки с высокой корреляцией друг с другом. После данные были разделены на выборки и проведено масштабирование. На основе данных нами были созданы три модели регрессии с подбором гиперпараметров. Все модели показали результат превосходящий значение метрики поставленной заказчиком. Лучшей же моделью на этапе разработки оказалась модель CatBoostRegressor. 
