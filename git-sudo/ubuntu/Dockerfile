ARG BASE_IMAGE
FROM $BASE_IMAGE

RUN apt-get update \
    && apt-get install -y \
        git \
        sudo \
    && rm -rf /var/lib/apt/lists/*

CMD ["pwsh"]