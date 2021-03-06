# Прогнозирование оттока клиентов (телеком)

## Задача

Создать модель для выявления клиентов, которые с наибольшей вероятностью покинут компанию: метрика AUC ROC должна оказаться не ниже 0.88.

## Что было выполнено:

- Проведен исследовательский анализ данных, который выявил самые важные признаки для дальнейшей работы
- Были обучены четыре модели LogisticRegression, XGBClassifier, LGBMClassifier и CatBoostClassifier
- По итогам первых тестов были внесены изменения в датасет - удалены мешающие признаки
- Был применен алгоритм KMean с целью перевода важной количественной переменной в категориальную

В конечно итоге удалось увеличить целевую метрику (AUC ROC) до 0.9320 c помощью CatBoostClassifier

## Библиотеки

*pandas, NumPy, Matplotlib, Seaborn, Imblearn, scikit-learn, CatBoost, LightGBM, XGBoost*
