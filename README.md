# sql-afternoon


/* create table person (
	id integer primary key autoincrement,
  	name,
  	age,
  	height,
  	city,
  	favoritecolor
); */
 
/* select * from person;  */

/* insert into person(name, age, height, city, favoritecolor)
values ( 'josh', 30, 180, 'atlanta', 'blue' ),
		('courtney', 27, 160, 'fort worth', 'green'),
        ('kyle', 30, 150, 'richland hills', 'brown'),
        ('sam', 31, 155, 'watauga', 'black'),
        ('clay', 29, 140, 'denton', 'red'); */
      
      
/* select * from person order by height desc; */

/* select * from person order by height asc; */

/* select * from person order by age desc; */

/* select * from person where age > 20; */

/* select * from person where age = 18; */

/* select * from person where age < 20 or age > 30; */

/* select * from person where age != 27; */

/* select * from person where favoritecolor != 'red'; */

/* select * from person where favoritecolor not in ('red', 'blue'); */

/* select * from person where favoritecolor in ('orange', 'green') */

/* select * from person where favoritecolor in ('orange', 'green', 'blue'); */

/* select * from person where favoritecolor in ('yellow', 'purple'); */

/* create table orders(
  personid integer primary key autoincrement,
  ProductName,
  ProductPrice,
  Quantity
  ); */

/* insert into orders(ProductName, ProductPrice, Quantity)
values
  ('fish', 10, 1),
  ('steak', 50, 2),
  ('waffles', 2, 3)
 */

/* select * from orders; */
/* select sum(quantity) from orders; */
/* select sum(productprice * quantity) from orders; */
/* select sum(productprice * quantity) from orders where personid = 2; */


/* insert into artist(name)
values
	('josh'),
    ('sam'),
    ('kyle')
     */

/* select * from artist order by name desc limit 10; */

/* select * from artist order by name asc limit 5; */

/* select * from artist where name like 'black%'; */

/* select * from artist where name like '%black%'; */


/* select firstname, lastname from employee where city like 'calgary'; */

/* select firstname, lastname, birthdate from employee order by birthdate desc limit 1; */
/* select firstname, lastname, birthdate from employee order by birthdate asc limit 1; */
/* select * from employee */

/* select * from employee where reportsto = 2 */

/* select count(*) from employee where city like 'lethbridge'; */

/* select count(*) from invoice where billingcountry = 'USA'; */

/* select * from invoice order by total desc limit 1 */

/* select * from invoice order by total asc limit 1 */

/* select * from invoice where total > 5  */

/* select * from invoice where total < 5*/

/* select count(*) from invoice where billingstate in ('CA', 'TX', 'AZ') */

/* select avg(total) from invoice; */

/* select sum(total) from invoice; */
