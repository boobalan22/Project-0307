FROM ubuntu:22.04

# Install Docker & basic tools
RUN apt-get update && apt-get install -y \
  docker.io \
  docker-compose \
  curl \
  git \
  openjdk-11-jdk \
  maven \
  && apt-get clean

# Allow Docker in container
RUN usermod -aG docker root
