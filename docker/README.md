## Postgresql: How to create a user for each database?

```sql
-- create a database if you didn't create it yet
CREATE DATABASE "kt-jab-houy-db";

-- create a user with password
CREATE USER "kt-jab-houy-user" WITH ENCRYPTED PASSWORD 'password';

-- grant access the user to the database
GRANT ALL PRIVILEGES ON DATABASE "kt-jab-houy-db" TO "kt-jab-houy-user";
```