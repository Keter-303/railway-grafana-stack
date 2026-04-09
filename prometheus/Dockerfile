ARG VERSION=v3.2.1

FROM prom/prometheus:${VERSION}

COPY prometheus.yml /etc/prometheus/prometheus.yml

CMD ["--config.file=/etc/prometheus/prometheus.yml", "--storage.tsdb.path=/prometheus"]
