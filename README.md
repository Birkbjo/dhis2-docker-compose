
### DHIS2 Docker

Each folder will start a docker container with the version of the folder.

Currently only `latest` will automatically download the DB. 

For versions other than `latest`, download the DB from [databases.dhis2.org](https://databases.dhis2.org/) into `./<version>/db/sierraleone/init.sql`


Start:

* `cd latest`
* `docker compose up -d`