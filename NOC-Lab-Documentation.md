# NOC Monitoring Lab – Prometheus & Grafana

## Overview
This project demonstrates a full Network Operations Center (NOC) monitoring environment built using Prometheus and Grafana. The lab simulates real-world infrastructure monitoring, alerting, and visualization of system performance metrics.

## Architecture
Ubuntu Server (Node Exporter) → Prometheus → Grafana Dashboard → Netdata

## Tools & Technologies
- Ubuntu Server (VirtualBox)
- Prometheus
- Grafana
- Node Exporter
- Netdata

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
- Prometheus / Grafana (NOC Operational Monitoring Dashboard & NOC Alerting Dashboard)
- Netdata (Main Dashboard, System CPU, Memory Usage, Memory Cache, Memory Swap, Disk Performance)
- Python (Custom Monitoring Automation)

## Screenshots
<img width="3552" height="1199" alt="GitHub-NOC Operational Monitoring" src="https://github.com/user-attachments/assets/b8b802d1-8b43-48b7-8a8d-ab1d319b95b6" />

<img width="3710" height="1183" alt="NOC-Lab-Alerts" src="https://github.com/user-attachments/assets/4913a10d-c7ef-4269-a59a-fde997f467e3" />

<img width="3573" height="2121" alt="Netdata-1-Main" src="https://github.com/user-attachments/assets/7aafd6b7-2c40-418f-8ee8-fb53be033a14" />

<img width="3465" height="1629" alt="Netdata-2-System-CPU" src="https://github.com/user-attachments/assets/18abfe4d-468a-42f0-966b-6da9f2363f96" />

<img width="3433" height="1980" alt="Netdata-3-Memory" src="https://github.com/user-attachments/assets/fae90666-e81c-4a20-8cd8-a980cf43debb" />

<img width="2868" height="1404" alt="Netdata-4-Memory-Usage-Cache-Swap" src="https://github.com/user-attachments/assets/522432cd-affc-4a3c-b468-d0dd2a394c44" />

<img width="2868" height="1172" alt="Netdata-5-Disk Performance" src="https://github.com/user-attachments/assets/f95346ab-d9dc-4409-8bf7-1de770feadc2" />

<img width="1039" height="1251" alt="Python-Custom Monitoring Automation" src="https://github.com/user-attachments/assets/128c2af6-1a6f-44b5-938a-14902cea94c2" />



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
- Ticketing
