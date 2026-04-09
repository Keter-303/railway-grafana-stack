# Grafana + Prometheus on Railway

This repository contains a minimal Grafana + Prometheus stack for Railway.

## Services
- Grafana
- Prometheus

## Deploy
Create two Railway services and set the root directory:
- Grafana: `grafana`
- Prometheus: `prometheus`

## Prometheus
Update `prometheus/prom.yml` to scrape your public `/metrics` endpoint.
