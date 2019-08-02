build-image:
	docker build -t nameko/nameko-example-products:$(TAG) .;

docker-tag:
	docker tag nameko/nameko-example-products:$(FROM_TAG) \
	$(DOCKER_REG)/$(DOCKER_NAMESPACE)/nameko-example-products:$(TAG)

push-image:
	docker push $(DOCKER_REG)/$(DOCKER_NAMESPACE)/nameko-example-products:$(TAG)
