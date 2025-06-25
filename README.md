# Task 2: Data Insertion and Handling Nulls (SQL)

## 📌 Objective
Practice core SQL operations including `INSERT`, `UPDATE`, and `DELETE`, while handling missing (`NULL`) values and default constraints.

---

## 🛠️ Tools Used
- DB Fiddle (MySQL mode)  
- SQLiteStudio (alternative)  
- MySQL 5.7+

---

## 📂 File Included

| File Name                 | Description                                          |
|--------------------------|------------------------------------------------------|
| `task2_data_handling.sql` | SQL script for creating a table, inserting data, updating records, handling NULLs/defaults, and deleting rows |

---

## 💡 Features Covered

- Table creation with constraints
- Inserting complete and partial data using `NULL` and `DEFAULT`
- Updating records using `UPDATE ... WHERE`
- Deleting specific rows using `DELETE ... WHERE`
- Viewing the final clean dataset with `SELECT *`

---

## 🧪 Sample Table Schema: `Students`

```sql
CREATE TABLE Students (
    student_id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100) NOT NULL,
    age INT,
    email VARCHAR(100),
    grade VARCHAR(20) DEFAULT 'Not Assigned'
);
