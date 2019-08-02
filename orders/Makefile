build-image:
	docker build -t nameko/nameko-example-orders:$(TAG) .;

docker-tag:
	docker tag nameko/nameko-example-orders:$(FROM_TAG) \
	$(DOCKER_REG)/$(DOCKER_NAMESPACE)/nameko-example-orders:$(TAG)

push-image:
	docker push $(DOCKER_REG)/$(DOCKER_NAMESPACE)/nameko-example-orders:$(TAG)
