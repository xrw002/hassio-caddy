ARG BUILD_FROM
FROM $BUILD_FROM

ENV LANG C.UTF-8

RUN apk add --no-cache caddy=0.10.14-r0 jq

ENV CADDYPATH /ssl

COPY run.sh /

CMD [ "/run.sh" ]
