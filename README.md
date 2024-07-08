# Домашнее задание к занятию "`SQL-ЧАСТЬ 1`" - `Фёдоров Илья`
### задание 1
SELECT DISTINCT district FROM address WHERE district LIKE 'K%a' AND district NOT LIKE '% %';

### задание 2
SELECT * FROM payment WHERE payment_date BETWEEN '2005-06-15' AND '2005-06-18' AND amount > 10.00;

### задание 3
SELECT * FROM rental ORDER BY rental_date DESC LIMIT 5;

### задание 4
SELECT LOWER(REPLACE(first_name, 'LL', 'pp')) AS modified_first_name, LOWER(last_name) AS modified_last_name FROM customer WHERE active = 1 AND (first_name = 'Kelly' OR first_name = 'Willie');
