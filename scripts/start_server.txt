#!/bin/bash
docker rm suzan-nginx
sudo docker run --name suzan-nginx -it -d -p 8080:80 nginx