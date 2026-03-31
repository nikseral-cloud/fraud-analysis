# fraud-analysis
Fraud detection analysis using synthetic transaction data (Python, pandas)
# Fraud Detection Analysis

## Описание
Анализ транзакций с целью выявления мошеннических операций.

## Данные
Сгенерированный датасет с транзакциями пользователей:
- user_id
- timestamp
- amount
- ip
- country
- device_id
- status

## Что сделано
- Найдены пользователи с аномальной активностью
- Выявлены фрод-паттерны:
  - частые транзакции (bruteforce)
  - смена стран
  - смена устройств и IP-адресов
  - рост сумм
  - нетипичная активность за час
- Разработаны правила (if-then логика)

## Технологии
- Python (pandas)
- Jupyter Notebook

## Результат
Сформированы правила детекции мошенничества и проведён анализ данных.
