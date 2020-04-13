ARG BASE_CONTAINER=jupyter/scipy-notebook
FROM $BASE_CONTAINER

LABEL maintainer="Amit Jain <amitjayn@apple.com>"

USER root

RUN apt-get update && \
    apt-get install -y openssh-server

# USER $NB_UID # Start as root

