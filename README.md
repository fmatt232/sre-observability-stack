# Project 4 — SRE Observability Stack

A local observability lab using Prometheus and Grafana to monitor service health and practice SRE concepts.

## Skills demonstrated
SRE • Prometheus • Grafana • Monitoring • SLIs/SLOs • Docker Compose • Incident Readiness

## Example SRE model
- Availability SLI: successful requests / total valid requests
- Latency SLI: p95 request duration
- Error-rate SLI: 5xx responses / total requests
- Example SLO: 99.9% monthly availability

The SLO is a lab target, not a claim about a production service.

## Start
```bash
docker compose up -d
```
Prometheus: port 9090  
Grafana: port 3000

Change default lab credentials before using this outside an isolated development environment.
