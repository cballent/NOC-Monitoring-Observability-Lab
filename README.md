# NOC Monitoring Lab – Prometheus & Grafana

## Overview
This project demonstrates a full Network Operations Center (NOC) monitoring environment built using Prometheus and Grafana. The lab simulates real-world infrastructure monitoring, alerting, and visualization of system performance metrics.

## Architecture
Ubuntu Server (Node Exporter) → Prometheus → Grafana Dashboard

## Tools & Technologies
- Ubuntu Server (VirtualBox)
- Prometheus
- Grafana
- Node Exporter

## Features
- CPU Usage monitoring (time-series)
- Memory usage tracking
- Disk usage monitoring with threshold alerts
- Network traffic (receive/transmit)
- Host availability monitoring (UP/DOWN)
- System uptime tracking
- Alerting system for:
  - High CPU usage (>85%)
  - High disk usage (>85%)
  - Host down detection

## Alerts Configured
- High CPU Usage Alert
- High Disk Usage Alert
- Host Down Alert

## Dashboards
- NOC Operational Monitoring Dashboard (Grafana)
- NOC Alerting Dashboard

## Screenshots
<img width="3552" height="1199" alt="GitHub-NOC Operational Monitoring" src="https://github.com/user-attachments/assets/b8b802d1-8b43-48b7-8a8d-ab1d319b95b6" />

<img width="3710" height="1183" alt="NOC-Lab-Alerts" src="https://github.com/user-attachments/assets/4913a10d-c7ef-4269-a59a-fde997f467e3" />


## What I Learned
- How Prometheus collects system metrics
- How Node Exporter exposes host-level data
- How Grafana visualizes infrastructure metrics
- How to build alerting rules for system monitoring
- Basics of NOC operations and observability

## Future Improvements
- Add Wazuh SIEM integration
- Add log-based alerting
- Centralized SOC dashboard
