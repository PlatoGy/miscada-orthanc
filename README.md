# miscada-orthanc

## Directory Structure
- config/：Orthanc configuration
- logs/：Logs
- volumes/：Persistent data storage directory
- docker-compose.yml：One-click deployment configuration file

## Quick Start

1. Clone this repository:
   ```sh
   git clone <your-repo-url>
   cd Orthanc
   ```

2. Start the service:
   ```sh
   docker-compose up -d
   ```

3. Access the Orthanc Web interface:
   ```sh
   http://localhost:8042
   ```