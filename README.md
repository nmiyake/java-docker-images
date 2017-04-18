java-docker-images
==================

Docker images for Java.

alpine-oracle-jdk-8
-------------------
Based on a Docker image that uses Oracle JDK 8 with the Unlimited Strength JCE policy installed.

Additionally, inclues the following:

For Gradle support:
  * `libstdc++`: required because Gradle needs 'libnative-platform.so'

For CircleCI support:
  * `bash`: required for command-line operations
  * `git`, `openssh`: required for checking out source
  * `tar`, `gzip`: required for cache restore operations
