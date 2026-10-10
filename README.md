# Vehicle Service Center Management

**Course:** CS1M02 — Principles of Database Systems  
**Project:** Mini Project (Task 3 & Task 4)  
**Database:** MySQL

## What this project models

The report describes a vehicle service center database with customers, customer phone numbers, vehicles, mechanics, mechanic phone numbers, services, spare parts, service-part usage, suppliers, supplier phone numbers, purchases, and bills.

## Files

- `schema.sql` — reconstructed table definitions.
- `queries.sql` — reconstructed Task 4 analytical queries.
- `SOURCE_NOTES.md` — important recovery limitations.

## Run

1. Install MySQL Server / MySQL Workbench.
2. Open `schema.sql` in MySQL Workbench and execute it.
3. Open `queries.sql` and execute queries after loading your own compatible sample data.

The original report includes sample-data screenshots, but no original `.sql` attachments. This reconstruction does not include a verified full data dump, so queries may return empty results until you populate the tables.

## Important

These files are reconstructed from screenshots embedded in the submitted PDF. They are **not guaranteed to be byte-for-byte copies of the original SQL**. Review table definitions and query semantics before using this repository as a portfolio project. In particular, check the service/bill relationships and the monthly revenue calculation against the original screenshots.
