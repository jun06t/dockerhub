REGISTRY_DOMAIN := jun06t
DOCKER_REPOSITORY := bigtable-emulator
TAG := latest

.PHONY: build
build:
	docker build -f Dockerfile -t ${REGISTRY_DOMAIN}/${DOCKER_REPOSITORY}:${TAG} .

.PHONY: push
push:
	docker push ${REGISTRY_DOMAIN}/${DOCKER_REPOSITORY}:${TAG}

