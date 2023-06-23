# Отток клиентов.
[HTML ipynb](https://github.com/viktor-kuzmin-28/practicum_yandex/blob/main/Отток%20клиентов/Отток%20клиентов.ipynb)

## Описание проекта

Из «Бета-Банка» стали уходить клиенты. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Нам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. Нужно построить модель с F1-мерой больше 0.59. Дополнительно нужно измерять AUC-ROC.

## Навыки и инструменты

- pandas
- numpy
- sklearn.metrics.f1_score
- sklearn.metrics.roc_auc_score
- from sklearn.shuffle
- sklearn.preprocessing.StandardScaler
- sklearn.linear_model.DecisionTreeClassifier
- sklearn.linear_model.LogisticRegression 
- sklearn.ensemble.RandomForestClassifier
- sklearn.model_selection.train_test_split

## Вывод по итогам исследования
Из предоставленных данных мы отобрали признаки для создания моделей. Обработали обнаруженные пропуски. В процессе работы данные были сбалансированы техникой upsampled. Категориальные данные были обработаны техникой OHE. Количественные признаки были масштабированы. Наиболее эффективной с точки зрения F1 меры получилась модель Случайный лес.
