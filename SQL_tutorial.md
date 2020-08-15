### [1. Select Statement](#1-Select-Statement)

### [2. Select Distinct Syntax](#2-Select-Distinct)

### [3. WHERE Clause](#3-WHERE-Clause)

### 1. Select Statement

> ```JS script
> SELECT *
> FROM table_name;
> ```

> ```JS script
> SELECT column1, column2, ...
> FROM table_name;
> ```

### 2. Select Distinct

> List the different (distinct) values.
>
> ```JS script
> SELECT DISTINCT column1, column2, ...
> FROM table_name;
> ```

> Lists the number of different (distinct) customer countries.
>
> ```JS script
> SELECT COUNT(DISTINCT Country)
> FROM Customers;
> ```

### 3. WHERE Clause

> The **WHERE** clause is used to filter records.
>
> ```JS script
> SELECT column1, column2, ...
> FROM table_name
> WHERE condition;
> ```

> ```JS script
> SELECT *
> FROM Customers
> WHERE Country='Mexico';
> ```
