# NGINX Dynamic Upstream Loadbalancer
The purpose of this K8s HELM chart / Docker image is to create an `nginx` based image that will always check your upstream list provided via `ConfigMap` or via `.env` file that can be read directly into `bash`

# Upcoming
This project will most likely extend off the base image `nginx:latest` and also `busybox:latest` and a possible conbination of `node:latest-alpineslim`

