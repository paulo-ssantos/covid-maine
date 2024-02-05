# Maine Covid-Economy | MySQL Relational Database Modeling

## Project Description

This repository contains files related to the conversion of data from CSV to a MySQL database. The primary focus is on ensuring security, standardization, and data integrity throughout the process.

## Converted CSV Tables

1. **size_codes**
2. **qcew_Maine_all_areas**
3. **ownership_codes**
4. **industry_lookup**
5. **fips_lookup**
6. **agg_level_codes**

## Conversion Process

The CSV files were manually analyzed, and based on the fields and data types found in the CSV files, corresponding tables were created. Subsequently, the data from the CSV files were imported into the MySQL database.
- Source of CSV files: https://data.world/darrenfishell/covid-economy

## Key Points of Attention

### Security

To enhance security, UUIDs (Universally Unique Identifiers) were used instead of sequential numbers as primary keys in the tables.

### Standardization

All table and column names adhere to a consistent naming convention:
- Tables: `TAB_table`
- Columns: `tab_column`

### Data Integrity

Ensuring data integrity is a top priority. Foreign keys have been employed to establish proper relationships between different tables, creating a robust and interconnected database structure.
