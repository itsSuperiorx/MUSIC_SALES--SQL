# Music Store Data Analysis using PostgreSQL

## Overview

This project analyzes music store data using PostgreSQL to derive insights into sales trends, customer behavior, and popular music genres. The analysis is divided into three sections: Easy, Moderate, and Advanced, each containing a set of questions to be answered using SQL queries.

## Project Structure

The project is organized as follows:

* **`sql_queries.sql`**: This file will contain the SQL queries you write to answer the questions.
* **`data/`**: This directory will hold the dataset files (e.g., CSV files) used for the analysis.
* **`README.md`**: This file (the one you're reading) provides an overview of the project and instructions.

## Getting Started

### Prerequisites

* PostgreSQL installed
* A PostgreSQL client (e.g., pgAdmin, Dbeaver)
* The dataset files (in the `data/` directory)

### Setup

1.  **Create a Database:**
    
    * Create a new database in PostgreSQL (e.g., `music_store`).
2.  **Import the Data:**
    
    * Import the data from the provided CSV files into the appropriate tables within your database.
3.  **Run SQL Queries:**
    
    * Write and execute SQL queries in the `sql_queries.sql` file to answer the questions outlined in the analysis.

## Analysis Questions

The analysis is divided into three sets of questions:

### Question Set 1 - Easy

1.  Who is the senior most employee based on job title? 
2.  Which countries have the most Invoices?
3.  What are top 3 values of total invoice? 
4.  Which city has the best customers? We would like to throw a promotional Music Festival in the city we made the most money. 
5.  Who is the best customer? 

### Question Set 2 - Moderate

1.  Write query to return the email, first name, last name, & Genre of all Rock Music listeners. Return your list ordered alphabetically by email starting with A 
2.  Let's invite the artists who have written the most rock music in our dataset. Write a query that returns the Artist name and total track count of the top 10 rock bands 
3.  Return all the track names that have a song length longer than the average song length. Return the Name and Milliseconds for each track. Order by the song length with the longest songs listed first 

### Question Set 3 - Advanced

1.  Find how much amount spent by each customer on artists? Write a query to return customer name, artist name and total spent 
2.  We want to find out the most popular music Genre for each country. We determine the most popular genre as the genre with the highest amount of purchases. Write a query that returns each country along with the top Genre. For countries where the maximum number of purchases is shared return all Genres 
3.  Write a query that determines the customer that has spent the most on music for each country. Write a query that returns the country along with the top customer and how much they spent. For countries where the top amount spent is shared, provide all customers who spent this amount 



## Contributing

Contributions are welcome!
