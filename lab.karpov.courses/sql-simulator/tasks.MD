# Решение заданий из тренажера [karpov.courses](https://lab.karpov.courses/learning/152/)
# Фильтрация данных
**Задание №1**

Напишите SQL-запрос к таблице **products** и выведите всю информацию о товарах, цена которых не превышает 100 рублей. Результат отсортируйте по возрастанию id товара.

Поля в результирующей таблице: **product_id**, **name**, **price**
```sql
SELECT product_id,
       name,
       price
FROM   products
WHERE  price <= 100
ORDER BY product_id
```
