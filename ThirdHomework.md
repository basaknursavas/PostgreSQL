1-Sort the country names in the country column in the country table starting with the 'A' character and ending with the 'a' character. 
```sql
                            SELECT * FROM country 
                            WHERE country LIKE 'A%a';
```

2-Sort the country names in the country column in the country table, which consist of at least 6 characters and end with the 'n' character. 
```sql
                            SELECT * FROM country 
                            WHERE country LIKE '_____a';

```
3-List the movie names containing the 'T' character, regardless of at least 4 uppercase or lowercase letters from the movie names in the title column in the movie table. 
```sql
                            SELECT title FROM film 
                            WHERE title ILIKE '%t%t%t%t%';
```
4-From the data in all the columns in the movie table, sort the data starting with the title 'C' character and the length (length) is greater than 90 and the rental_rate is 2.99. 
```sql
                            SELECT * FROM film 
                            WHERE title LIKE 'C%' AND  length > 90 AND rental_rate = 2.99;

```



