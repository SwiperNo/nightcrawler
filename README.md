# nightcrawler
Welcome to the Interview Questions Project repository! This project aims to be a comprehensive resource for technical interviews.

## Requirements
* kubernetes cluster (k3d,minikube,etc..)
* container runtime (docker,containerd,podman)
* helm
* git
* python

## Python exercise

**API KEY**: 3b93dbe006af066f0a0db26c13d3a15c

**API DOCS**:
  https://openweathermap.org/api/geocoding-api
  https://openweathermap.org/current

1. Resolve issues with script
2. Add parse arg for unit of measurement, look at api docs for units
3. Update get_daily_weather function to return imperial measurement instead of Kelvin using units argument created above
4. Create a new function that returns a string with the following data: temp, temp_min, temp_max, wind speed, and weather description
5. Print out data above

## Docker exercise

1. Create test file with "Hello World!" in the Dockerfile within the `/nginx/files` dir
2. Build Dockerfile and tag image
3. Run docker image targetport 8080
4. Access http server on localhost

## Helm Chart exercise

1. Resolve issue with helm chart
2. Add service manifest to helm chart that will expose nginx deployment
3. Deploy helm chart and curl service

## K8s Imperative exercise
1. Create pod with name busybox in the namespace interview using image busy box
2. Check the logs of the pod


## K8s Declaritive exercise
1. Create a deployment manifest with the name httpd use the container httpd:latest
2. Add an init container to the manifest using a python container that prints `hello world`

## Git exercise
1. checkout rebase-me branch
2. rebase branch against main
3. run git log to check the commit history
