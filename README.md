# Basic CRUD Operations in JPA

## Demonstration of Component Mapping through Code
For this I have created one Customer Entity.

One Customer Repository for performing basic CRUD opreations.

Written Test Cases for all CRUD operations.

Use MySql Database for storing customer table.

### Commands Used in MySQL Workbench -
use sys;

CREATE TABLE customer_table (
    id int PRIMARY KEY auto_increment,
    name varchar(20),
    email varchar(20)
);

select * from customer_table;
