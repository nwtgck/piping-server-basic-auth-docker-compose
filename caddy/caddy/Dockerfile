FROM alpine:3.13.4

LABEL maintainer="Ryo Ota <nwtgck@gmail.com>"

RUN apk add --no-cache curl
RUN cd /usr/local/bin && curl -L https://github.com/caddyserver/caddy/releases/download/v1.0.4/caddy_v1.0.4_linux_amd64.tar.gz | tar zxf -

ENTRYPOINT [ "/usr/local/bin/caddy" ]
