Dockerized-monitoring-suite:
-->DevOps Monitoring Project using Docker, Prometheus, Grafana, and CI/CD with GitHub Actions. Includes a Python app with real-time metrics visualization.

 Tech Stack:
- Python (Flask)
- Docker & Docker Compose
- Prometheus
- Grafana
- GitHub Actions (CI/CD)

 Features:
- Python app exposing metrics
- Prometheus scrapes metrics
- Grafana dashboards for visualization
- Containerized setup using Docker
- CI/CD pipeline using GitHub Actions

 Project Structure: 
── app.py
── Dockerfile
── docker-compose.yml
── prometheus.yml
── requirements.txt
──.github/workflows/ci.yml

Screenshots:
App Output (/tasks)
--> Python application running inside Docker, serving API responses.
Prometheus Targets Page
--> Prometheus successfully scraping configured services and exporters.
Prometheus Graph (PromQL query)
--> Real-time metrics visualization using PromQL queries in Prometheus UI.
Grafana Dashboard
--> Interactive dashboard visualizing application metrics using Prometheus as data source.
Docker Containers (Docker Desktop)
--> All project services (app, Prometheus, Grafana) running as containers.
