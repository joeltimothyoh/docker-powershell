ARG BASE_IMAGE
FROM $BASE_IMAGE

RUN apt-get update \
    && apt-get install -y \
        git \
        openssh-client \
        openssh-server \
    && rm -rf /var/lib/apt/lists/*

CMD ["pwsh"]