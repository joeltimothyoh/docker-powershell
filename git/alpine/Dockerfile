ARG IMAGE
FROM $IMAGE

RUN apk update \
    && apk add --no-cache \
    git \
    && rm -rf /var/cache/apk/*

CMD ["pwsh"]