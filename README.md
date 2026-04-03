# Web Security Learning - SQL Injection

This repository contains my notes, payloads, and lab solutions while learning **SQL Injection**.

## What is SQL Injection?
SQL Injection (SQLi) is a web security vulnerability that allows an attacker to interfere with the queries that an application makes to its database. It generally occurs when user input is not properly sanitized.

## Platform Used
- PortSwigger Web Security Academy

## Labs Completed
- SQL injection vulnerability in WHERE clause allowing retrieval of hidden data
- SQL injection vulnerability allowing login bypass

## What I Learned
- How websites use SQL queries for login and data retrieval
- How attacker input can change the logic of SQL queries
- Login bypass technique using payloads like `' OR 1=1 --`
- Importance of input validation and prepared statements

## Next Steps
- Learn more advanced SQLi techniques
- Practice on other platforms (TryHackMe, HackTheBox, etc.)

---
Created by Chetan | Started: April 2026
