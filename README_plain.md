# Week 8 Assignment – Clinic Booking System

This repository also includes a version with icons and improved visual structure.  
See [README.md](./README.md) for the visually enhanced version.

---

## Table of Contents
- [Overview](#overview)
- [Objectives](#objectives)
- [Schema Overview](#schema-overview)
- [How to Run](#how-to-run)
- [Requirements](#requirements)
- [License](#license)
- [Author](#author)

---

## Overview

Relational schema design for a clinic appointment system using **MySQL**.  
Focus: normalized data structure, data integrity, and performance.

---

## Objectives

- Apply database normalization techniques: First Normal Form (1NF) and Second Normal Form (2NF)  
- Create tables with appropriate constraints: `PRIMARY KEY`, `FOREIGN KEY`, `UNIQUE`, `NOT NULL`  
- Define and enforce relationships between entities (e.g., One-to-Many)

---

## Schema Overview

The following tables are created in the `clinicDB` database:

- `specialties`: Stores medical specialty information  
- `doctors`: Profiles for each doctor, linked to a specialty  
- `patients`: Patient records with personal details  
- `appointments`: Tracks patient bookings with doctors

All tables follow normalization principles up to 2NF.

---

## How to Run

1. Open MySQL Workbench or your preferred SQL client  
2. Execute the `answers.sql` script  
3. The script will:
   - Create the `clinicDB` database  
   - Create all required tables  
   - Define all necessary constraints

---

## Requirements

- MySQL 8.x  
- Basic understanding of SQL syntax, including:
  - DDL (Data Definition Language)  
  - Common constraints such as `NOT NULL`, `PRIMARY KEY`, `FOREIGN KEY`

---

## License

This project is licensed under the MIT License.  
See the [LICENSE](LICENSE) file for more details.

---

## Author

**Augusto Mate** – mate.augusto.mz@gmail.com
