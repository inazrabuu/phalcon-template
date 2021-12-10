# phalcon-template
A Docker template for Phalcon based application.

#Steps to run
- clone this repository
- `docker compose up -d`
- `docker compose exec app composer init`
- `docker compose exec app composer require --dev phalcon/devtools
- `docker compose exec app ./vendor/bin/phalcon project application simple`
- Open localhost:7000

Note: This template use port 7000 to run the application and `app` as its application name. Please change the running port & name if 7000 & `app` are not the desired one.
