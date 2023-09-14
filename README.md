# PostgreSQL + pgAdmin4
## Description
This is a docker-compose file to run a PostgreSQL database and pgAdmin4 in separated containers.

## How to use
1. Clone this repository
2. Run `docker-compose up -d`
3. Open your browser and go to `http://localhost:8888`
4. Login with the default credentials:
    - Username: `root`
    - Password: `root`
5. Add a new server with the following credentials:
6. - Host name/address: `postgres`
    - Port: `5432`
    - Username: `root`
    - Password: `root`