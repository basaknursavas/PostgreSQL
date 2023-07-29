1-Let's sort all the data for the first_name columns in the actor and customer tables. 
```sql
                      (SELECT first_name FROM actor
                      UNION 
                      SELECT first_name FROM customer);                                   
```
2-Let's sort the intersecting data for the first_name columns in the actor and customer tables. 
```sql
                      (SELECT first_name FROM actor
                      INTERSECT
                      SELECT first_name FROM customer);                                  
```
3-For the first_name columns in the actor and customer tables, let's sort the data that is in the first table, but not in the second table. 
```sql
                      (SELECT first_name FROM actor
                      EXCEPT
                      SELECT first_name FROM customer);                                   
```
4-Let's also do it for the data that repeats the first 3 queries.
```sql
                      (SELECT first_name FROM actor
                      UNION ALL
                      SELECT first_name FROM customer);                                         
```
```sql

                      (SELECT first_name FROM actor
                      INTERSECT ALL
                      SELECT first_name FROM customer);   
```
```sql
                      (SELECT first_name FROM actor
                      EXCEPT ALL
                      SELECT first_name FROM customer);  
```








