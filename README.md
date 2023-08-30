# CORALINE Data Engineer Junior

## Introduction
This is a take home test for position Data Engineer (Junior) from Coraline company.

There are 2 assignments
>1. Create a Python script to ingest data from an Excel file into a PostgreSQL database, consolidating data from each year into a single table.
>2. Create a SQL script to build a table: "cat_reg" utilizing data from a previous  assignment.

## Material
>1. Challenge instruction - Challenge - DE (Junior).pdf
>2. Source file - de_challenge_data.xlsx
>3. Source code - Take_Home_Coraline_test.ipynb

## Requirement library
>1. Pandas - for read and cleansnig data
>2. Psycopg2 - for create connection to PostgreSQL database

## Installation

```
# install PostgreSQL
!apt install postgresql postgresql-contrib &>log

# start PostgreSQL serviecs
!service postgresql start

# Create root user
!sudo -u postgres psql -c "CREATE USER root WITH SUPERUSER"

# Create database
!sudo -u postgres createdb challenge
```


## Result
### Task 1 : Preview result from table food_sales
![image](https://github.com/patcharaponmai/Take_Home_Test_Coraline/assets/140698887/b28bd640-6b62-4c2c-a6b4-c5d44a121930)

### Task 2 : Preview result from table cat_reg
![image](https://github.com/patcharaponmai/Take_Home_Test_Coraline/assets/140698887/ed8bc43f-9580-48d8-b948-4d168183f786)
