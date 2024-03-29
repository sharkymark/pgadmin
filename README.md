# Postgresql & PgAdmin powered by compose


## Requirements:
* docker
* docker-compose

## Quick Start
* If using Coder, have a workspace with a CVM ( has docker included )
* Clone or download this repository
* Go inside of directory,  `cd compose-postgres`
* Run this command `docker-compose up`
* If using Coder, create a Dev URL with port 5050


## Environments
This Compose file contains the following environment variables:

* `POSTGRES_USER` the default value is **postgres**
* `POSTGRES_PASSWORD` the default value is **postgres**
* `PGADMIN_PORT` the default value is **5050**
* `PGADMIN_DEFAULT_EMAIL` the default value is **pgadmin@pgadmin.org**
* `PGADMIN_DEFAULT_PASSWORD` the default value is **pgadmin**

## Access to postgres: 
* `localhost:5432`
* **Username:** postgres (as a default)
* **Password:** postgres (as a default)

## Access to PgAdmin: 
* **URL:** `http://localhost:5050`
* **Username:** `pgadmin@pgadmin.org`
* **Password:** `pgadmin`

## Add a new server in PgAdmin:
* **Host name/address** `postgres`
* **Port** `5432`
* **Username** as `POSTGRES_USER` `postgres`
* **Password** as `POSTGRES_PASSWORD` `postgres`