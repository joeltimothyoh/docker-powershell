ARG IMAGE
FROM $IMAGE

RUN apt-get update \
    && apt-get install -y \
    git \
    && rm -rf /var/lib/apt/lists/*

CMD ["pwsh"]