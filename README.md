# SQL
SQL Template Scripts

## Purpose
These scripts are basic template files to be modified when working with applications that require database manipulation.

## Platforms
The structure of these scripts follows Microsoft TSQL syntax, but can be refactored for other databases such as MySQL/MariaDB, PostgreSQL, Oracle, etc.

## Usage  
See the instructions below for each script.  

### *JOINS*  
Joins are useful when querying sets of data that span multiple tables. For example, in AP automation, we might need to query an Invoices table to get the InvoiceNumber and then query the Vendor table to get the VendorID to match the associated records.
