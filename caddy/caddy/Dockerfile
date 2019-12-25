FROM alpine:3.11

LABEL maintainer="Ryo Ota <nwtgck@gmail.com>"

RUN apk add --no-cache curl
RUN cd /usr/local/bin && curl -L https://github.com/mholt/caddy/releases/download/v0.11.5/caddy_v0.11.5_linux_amd64.tar.gz | tar zxf -

ENTRYPOINT [ "/usr/local/bin/caddy" ]
