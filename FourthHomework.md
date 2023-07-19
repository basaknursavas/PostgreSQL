1-Sort the different values in the replacement_cost column in the movie table. 
```sql
                        SELECT DISTINCT replacement_cost FROM film;  
```

2-How many different data are there in the replacement_cost column in the movie table? 
```sql
                        SELECT COUNT (DISTINCT replacement_cost) FROM film;  
```

3-How many of the movie names (titles) found in the movie table start with the character T and also have a rating equal to 'G'? 
```sql
                        SELECT COUNT (title) FROM film
                        WHERE title LIKE 'T%' AND rating='G';  
```

4-How many of the country names (country) in the country table consist of 5 characters? 
```sql
                        SELECT COUNT (country) FROM country
                        WHERE country LIKE '_____';

```

5-How many of the city names in the city table end with the character 'R' or r? 
```sql
                        SELECT COUNT (city) FROM city
                        WHERE city ILIKE '%R';
```

