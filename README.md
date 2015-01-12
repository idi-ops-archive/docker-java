## Java Dockerfile


This repository is used to build Java Docker images. It is used by the [Docker automated build service](https://registry.hub.docker.com/u/inclusivedesign/java/).

Currently the following tags are used:

* `latest` (default): OpenJDK Java 7 JDK (alias to `openjdk-7`)
* `openjdk-7`: OpenJDK Java 7 JDK


### Base Docker Image

* [inclusivedesign/centos:7](https://registry.hub.docker.com/u/inclusivedesign/centos/)


### Download

    docker pull inclusivedesign/java

#### Run `java`

    docker run -it --rm inclusivedesign/java java
