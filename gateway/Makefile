build-image:
	docker build -t nameko/nameko-example-gateway:$(TAG) .;

docker-tag:
	docker tag nameko/nameko-example-gateway:$(FROM_TAG) \
	$(DOCKER_REG)/$(DOCKER_NAMESPACE)/nameko-example-gateway:$(TAG)

push-image:
	docker push $(DOCKER_REG)/$(DOCKER_NAMESPACE)/nameko-example-gateway:$(TAG)
