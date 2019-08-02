build-image:
	docker build -t nameko/nameko-example-gateway:$(TAG) .;

docker-tag:
	docker tag nameko/nameko-example-gateway:$(FROM_TAG) \
	registry.nextpart.io:443/nextpart/nameko-example-gateway:$(TAG)

push-image:
	docker push registry.nextpart.io:443/nextpart/nameko-example-gateway:$(TAG)
