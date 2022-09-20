FROM bitnami/kubectl:1.23

USER root
RUN apt-get update \
    && apt-get install openssh-client \
    && rm -rf /var/lib/apt/lists /var/cache/apt/archives
