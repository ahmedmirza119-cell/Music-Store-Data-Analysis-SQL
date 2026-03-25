# 🎵 Music Store Data Analysis (PostgreSQL)

"A comprehensive data analysis of a digital music store using PostgreSQL to uncover business insights, customer behavior, and sales trends."

---

## 📂 Project Structure

This repository contains the following files to help you set up and analyze the music store database:

* **`schema.sql`**: Contains the DL (Data Definition Language) queries to create the database structure and tables.
* **`data.sql`**: Contains the sample records used to populate the music store database.
* **`Music_Store_Queries.sql`**: The core of the project. Contains Level 1, 2, and 3 analysis queries, covering everything from basic filtering to complex Window Functions and CTEs.

---

## 🛠️ Database and Tools
* **PostgreSQL**: The primary database engine used for analysis.
* **PgAdmin4**: Used as the GUI for writing and executing queries.

---

## 🔍 Key Analysis & Insights

In this project, I solved various business problems through SQL, including:
1.  **Employee Hierarchy**: Identifying the senior-most employee based on job titles.
2.  **Sales Performance**: Pinpointing countries and cities with the highest revenue to plan promotional events.
3.  **Customer Behavior**: Identifying top-spending customers for loyalty rewards.
4.  **Genre Trends**: Analyzing which music genres (like Rock) dominate specific markets.
5.  **Advanced Analysis**: Using **CTEs** and **Window Functions** to find the most popular music genre and the highest-spending customer for each country.

---

## 🗺️ Schema - Music Store Database

Schema- Music Store Database  
![MusicDatabaseSchema](https://user-images.githubusercontent.com/112153548/213707717-bfc9f479-52d9-407b-99e1-e94db7ae10a3.png)
---

## 🚀 How to Use
1.  Run the `schema.sql` file in your PostgreSQL environment to create the tables.
2.  Import the data using `data.sql`.
3.  Open and run `Music_Store_Queries.sql` to explore the business insights.
