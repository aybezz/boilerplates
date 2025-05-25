# Prometheus-Grafana Boilerplate

This folder provides a ready-to-use Docker Compose setup for running Prometheus and Grafana for monitoring and visualization.

## Features
- **Prometheus**: Collects and stores metrics.
- **Grafana**: Visualizes metrics from Prometheus.
- Pre-configured to scrape metrics from **Node Exporter** and **cAdvisor** using example Prometheus job configurations.

## Usage
1. Review and update `config/prometheus.yml` as needed.
2. Start the stack:
   ```sh
   docker compose -f compose.yml up -d
   ```
3. Access Grafana at [http://localhost:3000](http://localhost:3000)
4. Access Prometheus at [http://localhost:9090](http://localhost:9090)

## Folder Structure
- `compose.yml`: Docker Compose file to start services.
- `config/prometheus.yml`: Prometheus configuration.

---

This setup is ideal for local development and testing of monitoring solutions.
