1-Let's create a table in your test database with column information named employee id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100).
```sql
                              CREATE TABLE employee ( 
	                              id INTEGER,
	                              name VARCHAR(50),
	                              birthday DATE,
	                              email VARCHAR(100)
                              );                         
```
2-Let's add 50 pieces of data to the employee table we created by using the 'Mockaroo' service.
```sql
insert into employee (id, name, birthday, email) values (1, 'Franky', '2004-07-15', 'fstroband0@salon.com');
insert into employee (id, name, birthday, email) values (2, 'Zackariah', '2004-06-06', 'zgoodlake1@google.co.jp');
insert into employee (id, name, birthday, email) values (3, 'Caro', '2004-09-18', 'cmathan2@wix.com');
insert into employee (id, name, birthday, email) values (4, 'Crystie', '2003-11-06', 'ccisar3@noaa.gov');
insert into employee (id, name, birthday, email) values (5, 'Gladys', '2004-05-15', 'gbackshall4@fotki.com');
insert into employee (id, name, birthday, email) values (6, 'Elissa', '2003-12-12', 'epadley5@ucsd.edu');
insert into employee (id, name, birthday, email) values (7, 'Fidelio', '2004-04-21', 'flade6@live.com');
insert into employee (id, name, birthday, email) values (8, 'Faythe', '2004-03-22', 'flyffe7@xrea.com');
insert into employee (id, name, birthday, email) values (9, 'Margarethe', '2004-09-16', 'mwillis8@exblog.jp');
insert into employee (id, name, birthday, email) values (10, 'Tait', '2004-05-31', 'trayner9@dailymail.co.uk');
insert into employee (id, name, birthday, email) values (11, 'Lilah', '2003-10-27', 'lnottona@hugedomains.com');
insert into employee (id, name, birthday, email) values (12, 'Kata', '2004-09-02', 'kmcgowranb@nhs.uk');
insert into employee (id, name, birthday, email) values (13, 'Wilfred', '2004-05-14', 'wdebenedettic@nsw.gov.au');
insert into employee (id, name, birthday, email) values (14, 'Doralin', '2004-09-10', 'dwattishamd@cdc.gov');
insert into employee (id, name, birthday, email) values (15, 'Tim', '2004-02-04', 'tstoadee@oakley.com');
insert into employee (id, name, birthday, email) values (16, 'Desiri', '2003-11-13', 'driseboroughf@fc2.com');
insert into employee (id, name, birthday, email) values (17, 'Cris', '2003-10-29', 'ccarlesig@vimeo.com');
insert into employee (id, name, birthday, email) values (18, 'Kipp', '2004-03-30', 'kriddetth@cmu.edu');
insert into employee (id, name, birthday, email) values (19, 'Sal', '2004-04-28', 'srycei@sbwire.com');
insert into employee (id, name, birthday, email) values (20, 'Hedwig', '2004-05-08', 'hmunganj@ezinearticles.com');
insert into employee (id, name, birthday, email) values (21, 'Shannon', '2004-09-02', 'sbrounckerk@themeforest.net');
insert into employee (id, name, birthday, email) values (22, 'Tonia', '2003-12-04', 'tmaidmentl@eepurl.com');
insert into employee (id, name, birthday, email) values (23, 'Cristi', '2004-03-29', 'ckarolowskim@wsj.com');
insert into employee (id, name, birthday, email) values (24, 'Virgil', '2004-03-19', 'vclinningn@youku.com');
insert into employee (id, name, birthday, email) values (25, 'Tabbitha', '2004-03-10', 'tbrooko@weibo.com');
insert into employee (id, name, birthday, email) values (26, 'Amity', '2004-04-22', 'aauthersp@eepurl.com');
insert into employee (id, name, birthday, email) values (27, 'Mahmoud', '2003-09-22', 'mdelloq@archive.org');
insert into employee (id, name, birthday, email) values (28, 'Vladimir', '2004-01-18', 'vtynemouthr@apache.org');
insert into employee (id, name, birthday, email) values (29, 'Andreana', '2004-01-31', 'amuffs@unblog.fr');
insert into employee (id, name, birthday, email) values (30, 'Agace', '2004-07-30', 'amilmoet@myspace.com');
insert into employee (id, name, birthday, email) values (31, 'Fabiano', '2003-12-09', 'ffilipicu@loc.gov');
insert into employee (id, name, birthday, email) values (32, 'Lonni', '2003-11-17', 'lbevesv@guardian.co.uk');
insert into employee (id, name, birthday, email) values (33, 'Sharlene', '2003-11-22', 'sbaxstarew@digg.com');
insert into employee (id, name, birthday, email) values (34, 'Gard', '2004-06-27', 'gtoombsx@nytimes.com');
insert into employee (id, name, birthday, email) values (35, 'Meridith', '2004-03-14', 'mclutheramy@addtoany.com');
insert into employee (id, name, birthday, email) values (36, 'Zak', '2004-03-10', 'zcaswellz@reverbnation.com');
insert into employee (id, name, birthday, email) values (37, 'Tarrance', '2004-08-21', 'tcolvill10@wiley.com');
insert into employee (id, name, birthday, email) values (38, 'Arleta', '2003-12-10', 'aribeiro11@pcworld.com');
insert into employee (id, name, birthday, email) values (39, 'Chicky', '2003-11-20', 'cyashanov12@cloudflare.com');
insert into employee (id, name, birthday, email) values (40, 'Analise', '2003-12-20', 'aerangey13@blinklist.com');
insert into employee (id, name, birthday, email) values (41, 'Kimmi', '2003-10-27', 'kunderhill14@java.com');
insert into employee (id, name, birthday, email) values (42, 'Kerk', '2004-04-06', 'kgaither15@ftc.gov');
insert into employee (id, name, birthday, email) values (43, 'Elly', '2004-03-24', 'eminister16@google.cn');
insert into employee (id, name, birthday, email) values (44, 'Glory', '2004-08-14', 'gnern17@odnoklassniki.ru');
insert into employee (id, name, birthday, email) values (45, 'Maureene', '2004-06-25', 'mcrowder18@tripod.com');
insert into employee (id, name, birthday, email) values (46, 'Babs', '2004-03-22', 'bbere19@nps.gov');
insert into employee (id, name, birthday, email) values (47, 'Nelly', '2004-01-21', 'ngreaterex1a@examiner.com');
insert into employee (id, name, birthday, email) values (48, 'Tamara', '2003-11-22', 'tgobbett1b@admin.ch');
insert into employee (id, name, birthday, email) values (49, 'Evangeline', '2004-02-27', 'edimont1c@webmd.com');
insert into employee (id, name, birthday, email) values (50, 'Kimmie', '2004-05-16', 'kkezourec1d@ovh.net');
```

3-Let's do 5 UPDATE operations that will update the other columns according to each of the columns.
```sql
                          UPDATE employee
                          SET email = 'updated'
                          WHERE name LIKE 'C%' ;
```
4-Let's do 5 DELETE operations that will delete the corresponding row according to each of the columns. 
```sql
                          DELETE FROM employee
                          WHERE name LIKE 'A%' ;
```
