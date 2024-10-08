# Описание проекта

**Задача проекта**: Разработать решение для интернет-магазина «В один клик» с целью удержания постоянных клиентов с помощью персонализированных предложений. Основная цель — предсказать вероятность снижения покупательской активности и сегментировать клиентов для создания целевых предложений.

## Постановка задачи:
1. Построить модель для предсказания вероятности снижения покупательской активности клиентов.
2. Сегментировать клиентов на основе вероятности снижения активности и прибыльности для разработки персонализированных маркетинговых стратегий.

## Используемые модели:
- `LogisticRegression` в качестве Baseline
- `KNeighborsClassifier`
- `DecisionTreeClassifier`
- `SVC`

Модели были обучены с использованием пайплайна, который включает обработку количественных и категориальных признаков. Для подбора гиперпараметров использовалась метрика Recall

## Результаты:
На основе метрики выбрана наилучшая модель - KNeighborsClassifier. Далее выполнена сегментация клиентов по вероятности снижения активности и их прибыльности для компании. Для каждого сегмента были разработаны предложения по повышению покупательской активности на основе данных моделирования.
