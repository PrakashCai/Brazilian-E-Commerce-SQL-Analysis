# Brazilian E-Commerce SQL Analysis

## Project Overview

This project explores an e-commerce marketplace dataset using SQL to generate business insights.

The goal of the project was to simulate how a data analyst works with a relational database to analyze customer activity, sales performance, and product trends.

The analysis was performed using SQL queries on multiple related tables representing customers, orders, products, and payments.

---

## Dataset

This project uses the **Olist Brazilian E-Commerce Dataset** from Kaggle.

The dataset represents a real-world e-commerce marketplace and contains transactional data such as:

* Customer information
* Order details
* Product information
* Payment records

---

## Tools Used

* SQL
* MySQL Workbench
* Kaggle Dataset
* GitHub

---

## Database Creation

The tables for this project were created manually using SQL commands.

Initially, importing CSV files through MySQL Workbench was very slow on my system. To solve this, I created the tables manually and loaded the data using SQL commands, which significantly improved the loading process.

This helped me better understand how databases are structured and how raw CSV data can be converted into relational tables.

---

## Database Schema

The database contains multiple tables including:

* customers
* orders
* order_items
* products
* payments

While creating the tables, foreign keys were not defined initially. Because of this, when generating the ER diagram using MySQL Workbench, relationships between tables were not automatically detected.

To understand the structure of the database, relationships between tables were identified manually using common fields such as:

* `customer_id`
* `order_id`
* `product_id`

These relationships were then manually defined while reverse engineering the database schema.

---

## SQL Concepts Used

This project demonstrates several important SQL concepts including:

* SELECT
* WHERE
* GROUP BY
* ORDER BY
* JOIN
* COUNT
* SUM
* DISTINCT

These concepts were used to analyze the data and answer business questions.

---

## Business Questions Answered

Some of the analysis performed in this project includes:

* Total number of orders placed
* Number of unique customers
* Total revenue generated
* Top performing products
* Sales performance across categories

---

## Key Learnings

Through this project I learned:

* How to create database tables from raw CSV data
* How relational databases work
* How to join multiple tables for analysis
* How to use SQL to answer business questions
* How to document a data analysis project for GitHub

---

## Repository Contents

This repository includes:

* SQL queries used for the analysis
* ER diagram
* Analysis

