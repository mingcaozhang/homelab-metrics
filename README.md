# homelab-metrics

A simple Prometheus + Grafana stack with a custom [pwrstat exporter](https://github.com/mingcaozhang/pwrstat-exporter).

![Dashboard](grafana_screenshot.png)

## Prerequisites

The `pwrstat-exporter` image is not on dockerhub yet, so you will need to [build it yourself](https://github.com/mingcaozhang/pwrstat-exporter#Install).

## Install

```bash
git clone https://github.com/mingcaozhang/homelab-metrics.git 
cd homelab-metrics 
docker-compose up -d
```
