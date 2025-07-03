 🎵 SQL Music Store Analysis (MySQL Project)

This project explores and analyzes a fictional digital music store database using MySQL. It includes a full relational schema with customer, invoice, artist, track, and genre data, and uses SQL to answer real-world business questions—from beginner to advanced levels.

---

 📌 Project Objectives

- Analyze sales and customer behavior across different countries and genres
- Identify top-performing artists, cities, and customers
- Practice SQL fundamentals as well as advanced analytical techniques
- Simulate a real-world analytics case using a music retail dataset

---

 🛠️ Tools & Technologies

- Database: MySQL (tested on MySQL 8+)
- Interface: MySQL Workbench, DBeaver, or any SQL client
- Key SQL Concepts Used:
  - Joins (`INNER`, `LEFT`)
  - Aggregations (`SUM`, `COUNT`, `AVG`)
  - Subqueries & Correlated Subqueries
  - Window Functions (`ROW_NUMBER`)
  - CTEs (Common Table Expressions)
  - Recursive Queries
  - Grouping and Filtering (`GROUP BY`, `HAVING`)

---

 📚 Question Sets Covered

 ✅ Set 1 – Easy

- Who is the senior-most employee?
- Which countries have the most invoices?
- Top 3 invoice totals
- Which city has the best customers?
- Who is the best customer?

 ⚙️ Set 2 – Moderate

- Which customers listen to Rock music?
- Top 10 Rock artists by song count
- Tracks longer than the average length

 🔍 Set 3 – Advanced

- How much has each customer spent on the best-selling artist?
- Most popular genre by country
- Highest-spending customer per country (including ties)

---

 📁 Files Included

 📊 Queries & Questions
- `Music_Store_Query.sql` – Main SQL file with all query sets
- `SQL Music Questions2.docx` – Detailed business questions
- `Music Store Analysis-Questions.pdf` – Summary version of questions

 🗄️ Database & Schema
- `Music_Store_database.sql` – Full SQL dump of database (schema + data)
- `Music Store- Create Tables Query.txt` – Table creation queries
- `schema_diagram.png` / `MusicDatabaseSchema.png` – Entity Relationship Diagram

 📂 CSV Data Files
- `album.csv`
- `artist.csv`
- `customer.csv`
- `employee.csv`
- `genre.csv`
- `invoice.csv`
- `invoice_line.csv`
- `media_type.csv`
- `playlist.csv`
- `playlist_track.csv`
- `track.csv`

---

 📈 Sample Insights

- Rock is the most globally preferred genre.
- A small group of customers drives a large portion of sales.
- Cities like Prague and Paris show higher average invoice values.
- Top artists can be identified to drive targeted promotions.

---

 🚀 How to Use

1. Install MySQL (version 8+ recommended).
2. Import the database:
   - Option 1: Use `Music_Store_database.sql` to create schema and insert data.
   - Option 2: Use `Create Tables Query.txt` and `.csv` files to load manually.
3. Open `Music_Store_Query.sql` and run it to explore business insights.

---

 🧠 Skills Practiced

- Translating business needs into SQL queries
- Multi-table joins and filtering
- Analytical query structuring using CTEs
- Ranking and segmentation using window functions
- Clean code organization and documentation

---


