DOCKER_COMPOSE=$(shell which docker-compose)

up:
	$(DOCKER_COMPOSE) up

build:
	$(DOCKER_COMPOSE) build

clean:
	$(DOCKER_COMPOSE) stop
	$(DOCKER_COMPOSE) rm -f

