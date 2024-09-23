# docker-compose-exercise

This is a Docker compose exercise made for the Capgemini Engineering Docker workshop.

## Project structure

### Database

A MySQL database consisting of one table with some movies (see database/database.sql).

### Webapp

The webapp retrieves the movies from the database and shows them in a HTML page. This webapp is build using Flask (a Python Microframework).

## Exercise

### Creating a docker-compose.yml

Create a docker-compose.yml file to run the webapp and the database. Information on how to create such a file can be found here:

- https://docs.docker.com/compose/overview/
- https://docs.docker.com/compose/compose-file/

Once your created the docker-compose.yml file, run:

```
docker-compose up
```
