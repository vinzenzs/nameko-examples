build-image:
	docker build -t nameko/nameko-example-products:$(TAG) .;

docker-tag:
	docker tag nameko/nameko-example-products:$(FROM_TAG) \
	registry.nextpart.io:443/nextpart/nameko-example-products:$(TAG)

push-image:
	docker push registry.nextpart.io:443/nextpart/nameko-example-products:$(TAG)
