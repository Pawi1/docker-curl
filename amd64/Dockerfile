FROM scratch
ADD rootfs.tar.gz /

USER 65532

ENV PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
ENV SSL_CERT_FILE=/etc/ssl/certs/ca-certificates.crt

LABEL name="pawi1/curl"
LABEL version="0.0.1"
LABEL description="This is a Curl image, designed to minimize the size."
LABEL architecture="amd64"


ENTRYPOINT ["/usr/bin/curl"]
