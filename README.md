java-docker-images
==================

Docker images for Java.

alpine-oracle-jdk-8
-------------------
Based on a Docker image that uses Oracle JDK 8 with the Unlimited Strength JCE policy installed.
Additionally, includes `bash`, `libstdc++`, `git` and `openssh` to allow the image to be run in
CircleCI and to run Gradle tasks.
