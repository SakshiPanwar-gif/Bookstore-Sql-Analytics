# 📚 Online Bookstore Data & Business Analytics Project
## 🔍 Project Overview
This project demonstrates end-to-end data analysis and database management for an **Online Bookstore** using **MySQL**. It includes relational database schema design, data insertion for books, customers, and orders, and a comprehensive set of exploratory and advanced SQL queries to extract valuable business insights.
## 🛠️ Folder Structure & File Description
* **`schema/`**
  * `MySQL_BOOKSTORE.sql`: Contains the DDL statements to create the database and tables (`books`, `customers`, `orders`) along with foreign key constraints.
* **`data/`**
  * `Books_data.sql`: Insert statements containing book inventory records.
  * `Customers_data.sql`: Insert statements containing customer demographics and location details.
  * `Orders_data.sql`: Insert statements tracking customer transaction history.
* **`queries/`**
  * `SQL_Queries.sql`: Includes basic exploratory queries (filtering, aggregation) and advanced analytical queries (joins, group by, subqueries, revenue analysis).
## 💡 Key Business Questions Addressed
1. **Inventory & Product Analytics:** Retrieving books by genre, identifying high/low stock levels, and locating the most expensive items.
2. **Customer Insights:** Finding customers from specific countries/cities, tracking frequent buyers, and analyzing top spenders.
3. **Sales & Revenue Performance:** Calculating total revenue, determining total books sold per genre/author, and tracking remaining stock after fulfilling orders.
## 🚀 How to Run the Project
1. Clone this repository or download the files.
2. Open your MySQL client (e.g., MySQL Workbench, DBeaver, or terminal).
3. Execute `schema/MySQL_BOOKSTORE.sql` to set up the database and tables.
4. Run the data insertion scripts inside the `data/` folder (`Books_data.sql`, `Customers_data.sql`, `Orders_data.sql`).
5. Run the scripts in `queries/SQL_Queries.sql` to explore the business analytics findings.
