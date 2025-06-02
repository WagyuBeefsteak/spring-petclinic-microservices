FROM grafana/loki:2.8.0

COPY local-config.yaml /etc/loki/local-config.yaml

ENTRYPOINT ["/usr/bin/loki", "-config.file=/etc/loki/local-config.yaml"]
