# Estate code 


## Database Setup Commands:
```bash
CREATE DATABASE estate;
CREATE USER admin WITH PASSWORD 'admin';
ALTER ROLE admin SET client_encoding TO 'utf8';
ALTER ROLE admin SET default_transaction_isolation TO 'read committed';
ALTER ROLE admin SET timezone TO 'UTC';
GRANT ALL PRIVILEGES ON DATABASE estate TO admin;
\c estate ;
GRANT ALL ON SCHEMA public to admin;
```


