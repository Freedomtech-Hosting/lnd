FROM alpine

RUN apk add --no-cache tor

COPY torrc /etc/tor/torrc

RUN chown 10000 /var/lib/tor

ENTRYPOINT ["tor"]