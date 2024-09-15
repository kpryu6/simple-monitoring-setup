# Monitoring System with Prometheus, Grafana, cAdvisor, and Node Exporter

This project provides a complete setup for monitoring Docker containers and the host system using **Prometheus**, **Grafana**, **cAdvisor**, and **Node Exporter**. The system collects metrics from both containers and the host machine, visualizes the data in Grafana, and allows alerting based on predefined conditions.

## Overview

This setup uses:
- **Prometheus** to scrape metrics from cAdvisor (for containers) and Node Exporter (for host machine).
- **cAdvisor** to monitor container resource usage (CPU, memory, disk I/O, network traffic, etc.).
- **Node Exporter** to monitor the host machine's metrics (CPU, memory, disk, etc.).
- **Grafana** to visualize the collected data and set up alerts for critical metrics.

## Features
- Real-time monitoring of Docker containers and host system.
- Visualize CPU, memory, disk usage, and network traffic in Grafana dashboards.
- Alerts configured for CPU and memory thresholds to notify when a resource exceeds a set limit.
- Scalable and customizable monitoring setup.

## Prerequisites
- Docker and Docker Compose installed on your system.
- Basic understanding of Docker and containerized environments.

## Access the Services

- Grafana: Available at http://localhost:3000. Default username/password: admin/admin.
- Prometheus: Available at http://localhost:9090.
- cAdvisor: Available at http://localhost:8080. This provides a web interface for container metrics.
- Node Exporter: Runs in the background and exposes host system metrics on port 9100.

## Setup
[Monitoring Notion Page](https://gelatinous-inch-9e4.notion.site/Prometheus-Grafana-1d7adb59f33e4f60a7c66ea11b25e7ce)
