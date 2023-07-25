1-Write the INNER JOIN query, where we can see the names of the city (city) and country (country) in the city table and the country table together. 
```sql
                          SELECT city,country FROM city 
                          INNER JOIN country ON city.country_id = country.country_id ;
```

2-Type the INNER JOIN query, where we can see the customer table and the payment_id in the payment table and the first_name and last_name names in the customer table together.
```sql
                          SELECT payment.payment_id, customer.first_name, customer.last_name FROM payment
                          INNER JOIN customer ON payment.customer_id = customer.customer_id ; 
```
3-Type the INNER JOIN query, where we can see the rental_id in the customer table and the rental table, as well as the first_name and last_name names in the customer table together.
```sql
                          SELECT rental.rental_id, customer.first_name, customer.last_name FROM rental
                          INNER JOIN customer ON rental.rental_id = customer.customer_id;
```
