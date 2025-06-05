FROM grafana/loki:2.8.0

# Create directories

RUN mkdir -p /tmp/loki/boltdb-shipper-active \

             /tmp/loki/boltdb-shipper-cache \

             /tmp/loki/chunks \

             /tmp/loki/rules

COPY local-config.yml /etc/loki/local-config.yml

ENTRYPOINT ["/usr/bin/loki", "-config.file=/etc/loki/local-config.yml"]
