build-image:
	docker build -t nameko/nameko-example-orders:$(TAG) .;

docker-tag:
	docker tag nameko/nameko-example-orders:$(FROM_TAG) \
	registry.nextpart.io:443/nextpart/nameko-example-orders:$(TAG)

push-image:
	docker push registry.nextpart.io:443/nextpart/nameko-example-orders:$(TAG)
