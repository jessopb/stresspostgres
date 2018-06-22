# stresspostgres
sandbox to insert many rows of data into a postgres db from node in a variety of ways

# Steps
0. Install postgres, nodejs, 
1. Create DB
    1. create user, password, give roles
    2. create database
    3. create 4 simple tables
2. npm install pg
3. create 4 simple js files
    1. insert using client + promises
    2. insert using pool
        - callback
        - promies
        - async/await
    3. insert using transaction
