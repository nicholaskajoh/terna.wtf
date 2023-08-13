# terna.io
Monitoring server for home lab.

## Config
Start Tailscale with:
```sh
tailscale up --accept-dns=false --accept-routes
```

## Apps
- Prometheus
- Grafana
- Plausible Analytics

## Prometheus
Reload config:

```sh
curl -X POST -u username:password https://prometheus.terna.io/-/reload
```
