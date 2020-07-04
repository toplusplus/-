## How Data Types affect what you can do? 

- Affects space used and processing efficiency. 

- Affect the types of operations that can be performed. 

```
❌ Int       01012018
❌ String    January 1st two thousand eighteen
✅ Date      2018-01-01
```

## How to choose the best Data Type? 

- **Accuracy**. Data has to fit well with the **format** and **lenght** of the Data Type picked. 

- **Organization**. Notice that your you will wanting your data organized by name, date, a number or something. 

- **Relation**. It's easier to connect and filter data that shares the same Data Type. 

## Tools: MySQL Workbench vs phpMyAdmin

- **phpMyAdmin** is intended to handle the administration of MySQL over the Web. **Supports: managing databases, tables, columns, relations, indexes, users, permissions, etc.**

- **MySQL Workbench** is a tool for database architects, developers, and DBAs. **Provides data modeling, SQL development, and administration tools for server configuration, user administration, backup, etc.**

- MySQL Workbench is a desktop app while phpMyAdmin is a web app. 

- phpMyAdmin is easier to use. 

- MySQL Workbench has functionalities as **server administration** and **database modeling**.

```
🤓 What does Collation means? It is the character set that your database will use in its text types.
```

## Principles of Table Design

1. Avoid redundant data.

2. Provide access to other tables via keys.

3. Accomodate your processing and reporting needs. 

## Users and Permissions

```
 👉 Different users do different things
 ```
 Set **permissions per action**: Read, Write, Update and Delete. 

```
 👉 Different users can access different information
 ```
 Set **permissions per table**. 

```
 👉 Different data can be accessed from different locations
```
Set **permissions by user specific location**. 

## Queries 

Queries are a **set of instructions** written in a *language* (SQL) that can be understood by a *data base system* (MySQL).

Queries have three basic parts:

```
1️⃣ ACTION. The purpose of the query. 
```
**Select**, **Insert**, **Update**, and **Delete**. 

```
2️⃣ LOCATION. Where the action will be performed on.
```
**From** *table_name*.

```
3️⃣ RESTRICTIONS. Conditions under data will be affected. 
```
**Where** *set_of_restrictions*






