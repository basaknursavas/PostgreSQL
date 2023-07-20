1- List the 5 longest (length) movies in the movie table and the movie name (title) ends with the 'n' character.
```sql
                                  SELECT * FROM film 
                                  WHERE title LIKE '%n'
                                  ORDER BY length DESC 
                                  LIMIT 5;                        
```
2-Sort the 5 movies(6,7,8,9,10) in the movie table and the second shortest (length) ending with the movie name (title) 'n' character(6,7,8,9,10). 
```sql
                                  SELECT * FROM film 
                                  WHERE title LIKE '%n'
                                  ORDER BY length ASC 
                                  OFFSET 5 
                                  LIMIT 5;                         
```
3-In the descending order according to the last_name column in the customer table, sort the first 4 data, provided that store_id is 1. 
```sql
                                  SELECT * FROM customer
                                  WHERE store_id = 1
                                  ORDER BY last_name DESC 
                                  LIMIT 4;
                         
```
