# mssql-starter

Minimal starter project, create mssql container with custom database with docker-compose only.

Based on a useful and insightful project by [pm7y](https://github.com/pm7y).

Refer the following link for more details and leave a star, while doing so: [Click here to get to the github project of pm7y](https://github.com/pm7y/DockerExamples).

CAUTION: Use this for test purposes only, as for production further steps are necessary.

# Usage

Define your custom SQL statements in `mssql-init.sql`

docker-compose executes the script using a separate docker container with the necessary tools required.

```
docker compose up -d
```

To remove everything cleanly, including volumes:

```
docker compose down -v
```
