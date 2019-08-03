# Docker

To maintain multiple container use docker-compose. They will connected trought a default network

#### Up
1. - `$ docker-compose up`
1. - `$ docker-compose up -d` // with background up

#### Down
1. - `$ docker-compose down`
  Stop a removing all the containers.

#### Restart Vocabulary
1. - "no" >> Never restar a container was failed.
1. - always >> Restar a container, not matter what has failed.
1. - on-failure >> Only restart if a container stop for an error code.
1. - unless-stopped >> Always restart unless we forcibly stop it.

