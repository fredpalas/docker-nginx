# nginx docker image



## Info
* Based on Camil nginx files https://hub.docker.com/r/camil/nginx/
* Based on nginx official image [nginx](https://hub.docker.com/_/nginx/)

        

## Build


	git clone git@github.com:fredpalas/docker-nginx.git
	cd ./docker-nginx
	docker build --rm -t fredpalas/nginx .

## Basic usage

	docker pull fredpalas/nginx
	docker run --rm -d -p 80:80 -p 443:443 fredpalas/nginx


