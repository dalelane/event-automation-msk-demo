FROM registry.access.redhat.com/ubi8/ubi-minimal:latest

COPY ca.crt /certs/eem/ca.pem
COPY tls.crt /certs/eem/client.pem
COPY tls.key /certs/eem/client.key
COPY tls.crt /certs/eem/egwclient.pem
COPY tls.key /certs/eem/egwclient-key.pem

VOLUME ["/certs"]