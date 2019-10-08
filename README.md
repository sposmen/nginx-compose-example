# README

To run with docker-compose:

`docker-compose up web`

To run it as daemon:

`docker-compose up -d web`

To stop when daemon

`docker-compose stop web`


This nginx will share through `8080` port if want another port set it in the `docker-compose.yml` file

## Static HTML

Just add the new files to the `html` folder. And refresh the browser (no nginx restart required)

## New configs

Add them in `conf.d`
