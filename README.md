# DataModelling
This project involves the analysis of the dvdrental dataset available at the PostgreSQL website, downloading and loading the data to postgreSQL.

Post that we use psycopg2 to connect python to postgreSQL and re-design the data model into STAR Schema and make the data ready to load into the data warehouse/staging area/.

-----
-> Select a Dataset
-> Design data model (I have used relational modeling)
-> Use psycopg2 (PostgreSQL Python Connector)
    - Initialize the connection
    - Create DataBase
    - Initialize the cursor to do operations on the database and execute queries
    - execute queries
    - close cursor and close connection
