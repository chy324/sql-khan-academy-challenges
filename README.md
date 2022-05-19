### Intro to SQL: Querying and Managing Data
## This GitHub repository contains the schemas, questions and solutions to 

IF OBJECT_ID('Tempdb..#Temp') IS NOT NULL
	DROP TABLE #Temp;
GO

CREATE TABLE #Temp (NORMAL_LINK VARCHAR(200),HYPERLINK XML);
GO
INSERT INTO #Temp
SELECT '[https://www.khanacademy.org/computing/computer-programming/sql]';
GO

The coursework included:

# SQL Basics

More Advanced SQL Queries

Relational Queries in SQL

Modifying Databases with SQL
