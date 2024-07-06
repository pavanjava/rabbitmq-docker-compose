# rabbitmq-docker-compose
This repository gives the flexibility to run the rabbitmq as a compose file


## Setup
This setup assumes you already have docker-compose and docker (using docker toolbox) installed.

- `git clone git@github.com:pavanjava/rabbitmq-docker-compose.git`

- `cd rabbitmq-docker-compose`
- `docker-compose up`
or
-`docker compose up -d`


- Open http://localhost:15672/ (or what ever IP you get when you run docker-machine ip) and use the login

- username: rabbitmqadmin
- password: rabbitmq@123
## License
GPL-3.0 license