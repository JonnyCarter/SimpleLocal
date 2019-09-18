# Notes

This is just a simple container - two simple containers  for testing out some code, and trying some stuff.
Its not designed for production use. Its just a place to try stuff

from the command line travel to the  root directory of this project and run this `docker-compose up -d`
This will bring up a basic docker container on local host that also has a database should you need to use one.

```
    environment:
      - MYSQL_ROOT_PASSWORD=docker
      - MYSQL_DATABASE=db_runwaytest

```

You can change these to adjust the DB name when you set it up.



