# SQL-9
1. SELECT city.city_id, city.city, city.last_update, country.country, country.last_update FROM city
INNER JOIN country ON city.country_id = country.country_id;
2. SELECT payment.payment_id, customer.first_name, customer.last_name FROM customer
INNER JOIN payment ON customer.customer_id = payment.customer_id;
3. SELECT rental.rental_id, customer.first_name, customer.last_name FROM customer
INNER JOIN rental ON customer.customer_id = rental.customer_id;
