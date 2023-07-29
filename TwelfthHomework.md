1-In the movie table, the movie length is shown in the length column. How many movies are there that have a length greater than the average movie length?
```sql
                                SELECT COUNT(*) FROM film 
                                WHERE length > 
                                (SELECT AVG(length) FROM film);                        
```
2-How many movies are there with the highest rental_rate value in the movie table?
```sql
                                SELECT COUNT(*) FROM film 
                                WHERE rental_rate = 
                                (SELECT MAX(rental_rate) FROM film);                        
```
3-In the movie table, sort the movies with the lowest rental_rate and the lowest think replacement_cost values.
```sql
                                SELECT COUNT(*) FROM film 
                                WHERE rental_rate = 
                                (SELECT MIN(rental_rate) FROM film) 
                                AND replacement_cost =
                                (SELECT MIN (replacement_cost) FROM film);                        
```
4-List the customers(customers) who have made the largest number of purchases in the payment table.
```sql
                                SELECT * FROM customer
                                INNER JOIN (SELECT COUNT(*) A, customer_id FROM payment
                                GROUP BY customer_id
                                )count_purchases
                                ON customer.customer_id = count_purchases.customer_id
                                ORDER BY A DESC
                                LIMIT 3;                        
```
