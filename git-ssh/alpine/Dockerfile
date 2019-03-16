ARG BASE_IMAGE
FROM $BASE_IMAGE

RUN apk update \
    && apk add --no-cache \
        git \
        openssh \
    && rm -rf /var/cache/apk/*

CMD ["pwsh"]