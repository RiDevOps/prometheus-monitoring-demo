# Setup Instructions

## Prerequisites
- Docker installed
- Docker Compose installed

## Running the Monitoring Stack

1. Clone this repository
2. Navigate to the project directory
3. Run the stack:
   ```bash
   docker-compose up -d
Accessing the Services
Prometheus: http://localhost:9090
Grafana: http://localhost:3000 (admin/admin)
Node Exporter: http://localhost:9100/metrics
Grafana Dashboard Setup
Login to Grafana (admin/admin)
Add Prometheus as data source (http://prometheus:9090)
Import dashboard or create custom dashboards for monitoring
Stopping the Stack
docker-compose down
