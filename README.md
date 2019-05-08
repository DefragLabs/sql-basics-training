### SQL Basics Training part 1

**Assumptions:**

- Docker is installed
- Docker Compose is installed


**Running the project**

- Run the command `docker-compose up -d`. This will start a container called `my_postgres` running in port `5432`. 
- To SSH into the container, run `docker exec -it my_postgres psql -U postgres`. This command uses the default `postgres` user to log into the default database `postgres`.



**Basic Commands**
1. Create a new database `create database my_database`
2. List all databases `\l`
3. Connect to a particular database : `\c my_database`
4. Exit shell `\q`

