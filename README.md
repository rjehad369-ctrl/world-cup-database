# ⚽ World Cup Database - freeCodeCamp Relational Database Project

A relational database project built as part of the freeCodeCamp Relational Database Certification. This project demonstrates proficiency in PostgreSQL, database design, Bash scripting, and complex SQL querying.

## 📋 Project Overview
The project manages a database containing data about FIFA World Cup matches (from 2014 onwards), including teams, match rounds, and goals scored. It involves three main parts:
1. **Database Design:** Creating a normalized relational database (`worldcup`) with `teams` and `games` tables, including proper Primary and Foreign Key constraints.
2. **Data Insertion Script (`insert_data.sh`):** A Bash script that reads from a CSV file (`games.csv`) and programmatically populates the database without hard-coding IDs.
3. **Query Script (`queries.sh`):** A collection of advanced SQL queries executed via a Bash script to extract specific insights and statistics from the database.

---

## 🛠️ Tech Stack
* **Database:** PostgreSQL
* **Scripting:** Bash, SQL
* **Environment:** Linux / VS Code / CodeRoad

---

## 📂 Project Files
* `worldcup.sql` — A full database dump containing the schema and inserted data.
* `insert_data.sh` — Bash script to parse `games.csv` and insert data into PostgreSQL.
* `queries.sh` — Bash script containing various PostgreSQL queries answering specific project prompts.
* `games.csv` — Raw dataset containing World Cup match details.

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR-USERNAME/world-cup-database.git](https://github.com/YOUR-USERNAME/world-cup-database.git)
   cd world-cup-database
