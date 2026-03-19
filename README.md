# Celestial Bodies Database 🌌

This is the first project of the freeCodeCamp Relational Database Certification. The objective was to design and implement a complex PostgreSQL database that models a small universe with various celestial bodies and their relationships.

## 🛠 Technologies Used
- PostgreSQL: Used to create a relational database with multiple linked tables.
- SQL: Used for schema definition, implementing constraints (Primary Keys, Foreign Keys, Unique, Not Null), and data insertion.
## 📋 Database Schema
The database, named universe, consists of the following interconnected tables:
- galaxy: Information about different galaxies.
- star: Stars linked to their respective galaxies.
- planet: Planets orbiting specific stars.
- moon: Moons belonging to planets.
- constellation: A custom table modeling groups of stars.


## 🔑 Key Features Implemented
- Relational Integrity: Each table uses appropriate Primary Keys and Foreign Keys to maintain data relationships.
- Data Types: Utilized various PostgreSQL types including INT, NUMERIC, TEXT, VARCHAR, and BOOLEAN.
- Constraints: Strict use of NOT NULL and UNIQUE constraints as per project specifications.

## 🚀 How to Run
- 1.🚀Access PostgreSQLess PostgreSQL**:
- Log into your psqRebuild the Databased the Database**:
   
- 2.**Rebuild the Database:
- Use the provided SQL script to recreate the entire structure and data:
   ```bash
   psql -U postgres < universe.sql
   ```
- 3.**Explore the Data:
- You can verify the tables by running:
```bash
\c universe
```
```bash
\dt
```

Completed as part of the freeCodeCamp Relational Database Curriculum.
