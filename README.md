# nginx docker image



## Info

* Based on nginx official image [nginx](https://hub.docker.com/_/nginx/)

        

## Build


	git clone git@github.com:camilb/docker-nginx.git
	cd ./docker-nginx
	docker build --rm -t camil/nginx .

## Basic usage

	docker pull camil/nginx
	docker run --rm -d -p 80:80 -p 443:443 camil/nginx


