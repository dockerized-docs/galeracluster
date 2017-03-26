# dockerized-docs-galeracluster

# What is it? #
Dockerzied Galera-Cluster documentation for offline use.

# Image description #
- Base image: `python:2.7`
- The most current Galera-Cluster `master` branch is cloned and built using sphinx
- Galera-Cluster documentation directory (`/documentation/galeracluster/build/dirhtml`) is linked to httpd `DocumentRoot` (`/var/www/html`)  
# How to use this image #

```console
$ docker run -d genadipost/dockerized-docs-galeracluster

```

You can test it by visiting http://container-ip:80
