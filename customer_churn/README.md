# Отток клиентов банка

## Задача

Проанализировать исторические данные о поведении клиентов и спрогнозировать уйдёт ли клиент из банка в ближайшее время или нет.

В рамках исследования использованы: DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, а также Upsampling и Downsampling для борьбы с дисбалансом классов.

## Что было выполнено:

- Спрогнозирована вероятность ухода клиента из банка в ближайшее время.
- Построена модель с предельно большим значением F1-меры с последующей проверкой на тестовой выборке. Доведена метрика до 0.59. 
- Дополнительно измерен AUC-ROC, соотнесен с F1-мерой

## Библиотеки

*pandas*, *numpy*, *Matplotlib*, *sklearn*
