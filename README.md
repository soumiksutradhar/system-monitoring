# System Monitoring with Prometheus & Grafana

This project sets up a basic monitoring stack using Prometheus and Grafana with Docker Compose. It collects system metrics using Node Exporter and visualizes them on a Grafana dashboard.

## Features
- Prometheus metrics collection every 20 seconds
- Node Exporter to monitor system metrics
- Grafana dashboard for visualization

## Setup Instructions

1. Clone this repo:

    ```bash
    git clone https://github.com/soumiksutradhar/system-monitoring.git
    cd system-monitoring
    ```

2. Start the monitoring stack:

    ```bash
    docker-compose up -d
    ```

3. Access services:
   - Prometheus: `http://localhost:9090`
   - Grafana: `http://localhost:3000` (default login: admin/admin)
   - Node Exporter metrics: `http://localhost:9100/metrics`

## Customization

- Edit `prometheus.yml` to change scrape intervals or add more targets
- Update Grafana dashboards to visualize different metrics

---
