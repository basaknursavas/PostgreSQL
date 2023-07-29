1-Type the LEFT JOIN query, where we can see the names of the city (city) and country (country) in the country table together with the city table.
```sql
                              SELECT city.city, country.country FROM city; 
                              LEFT JOIN country ON city.country_id = country.country_id;                                                    
```
2-Type the RIGHT JOIN query, where we can see the customer table and the payment_id in the payment table, as well as the first_name and last_name names in the customer table together.
```sql
                              SELECT customer.first_name, customer.last_name, payment.payment_id FROM customer
                              RIGHT JOIN payment ON customer.customer_id = payment.customer_id;
                                                    
```
3-Type the FULL JOIN query, where we can see the rental_id in the customer table and the rental table, as well as the first_name and last_name names in the customer table together.
```sql
                              SELECT customer.first_name, customer.last_name, rental.rental_id FROM customer
                              FULL JOIN rental ON customer.customer_id = rental.customer_id ;
                                                   
```
