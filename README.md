# GPN Intelligence Cup

Исходные данные:
1. Данные о транзакциях. (transaction_df.parquet)
2. Данные о ценах конкурентов. (df_competitors.parquet)
3. Данные о погоде. (weather_df.parquet)
4. Данные о себестоимости. (df_cost.parquet)

Задача

Составить расписание цен для 5 городов, 3 продуктов на 90 дней в соответствии с
правилами, описанными ранее. Результат отправляется в формате .parquet.
Всего должно быть 1350 строчек (5*3*15).

GPN (1).ipynb - решение <br>
df_baseline.parquet - бэйзлайн <br>
df_predict_price.parquet - предсказанные цены <br>
