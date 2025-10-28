# TSQL2012-PostgreSQL

This repository contains SQL script from the book **Microsoft SQL Server** (TSQL2012) converted from SQL Server (T-SQL) syntax to **PostgreSQL**.  
The goal is to make the original educational examples executable and testable in PostgreSQL environments.

---

## 📘 About

The book [*T-SQL Fundamentals (2012)* by Itzik Ben-Gan](https://www.microsoftpressstore.com/store/microsoft-sql-server-2012-t-sql-fundamentals-9780735658141) provides a comprehensive introduction to Transact-SQL using Microsoft SQL Server.  
This project contains a **PostgreSQL-compatible port** of those example scripts.

During the conversion process:
- SQL Server-specific statements like `IDENTITY`, `TOP`, and `GO` were replaced with PostgreSQL equivalents (`SERIAL`, `LIMIT`, `;`).
- System functions such as `GETDATE()` were replaced with `CURRENT_TIMESTAMP`.
- SQL Server data types were mapped to PostgreSQL-compatible types.
- Optional schema `"TSQL2012"` is used to preserve logical structure.

---

## 🗂️ Repository Structure

