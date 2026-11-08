ZStore is a desktop store management system built on a relational SQLite database, with a Tkinter GUI and secure admin login.
ZStore: Database-Driven Store Management System

ZStore is a DBMS project that uses a relational database for the structured storage, management and querying of store data. It comes with a desktop interface built in Python, and access is restricted to admin users.

Key Features

Relational Database: Stores data in SQLite tables (such as Employee) and retrieves it with SQL queries.
Admin Authentication: Login checks credentials against the database using parameterized SQL queries, which protects against SQL injection.
Role-Based Access: Only users with the Admin user type can open the dashboard.
Desktop GUI: A Tkinter interface with a branded login screen, a show/hide password toggle and error feedback.
Dashboard: After login, admins reach a central dashboard for managing the system.

Tech Stack
SQL, SQLite, Python, Tkinter, Pillow

Getting Started

bash
pip install pillow
python ZSTORE.py

Make sure zstore.db and the Images/ folder are in the project directory.
