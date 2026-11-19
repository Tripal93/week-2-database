# SQL Assignment: Retrieving and Filtering Data

**Retrieving, Filtering, Sorting, and Limiting Data in SQL**

This repository contains the SQL solutions for querying and filtering records across the `payments`, `orders`, `employees`, `offices`, and `products` tables using MySQL.

## Files

- `answers.sql` — Contains all five SQL queries for the assignment.

## Queries Included

1. **Retrieve Payment Information:** Selects `checkNumber`, `paymentDate`, and `amount` from `payments`.
2. **Find Orders in Process:** Filters `orders` where `status = 'In Process'` and sorts by `orderDate` descending.
3. **Find Sales Representatives:** Retrieves `firstName`, `lastName`, and `email` from `employees` for `Sales Rep` roles, sorted by `employeeNumber` descending.
4. **Retrieve Office Information:** Retrieves all columns and records from `offices`.
5. **Retrieve the Five Cheapest Products:** Selects `productName` and `quantityInStock` from `products`, sorted by `buyPrice` ascending and limited to 5 results.

## How to Run

1. Open MySQL Workbench or your MySQL CLI and select your database:
   ```sql
   USE classicmodels;
