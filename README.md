# Docker Compose Deployment Guide

1. **Install Docker:**
   Ensure Docker is installed on your system. Follow the official Docker installation instructions for your operating system.

2. **Update Configuration:**
   Edit the **complete-deployment-compass.yaml** file with the appropriate repository links.

3. **Optional Customization:**
   Optionally, configure the **complete-deployment-compass.yaml** file according to your specific requirements.

4. **Full Deployment:**
   To deploy the entire stack, execute the following command:
   ```
   docker compose -f complete-deployment-compass.yaml up -d
   ```
   
5. **Individual Service Deployment:**
   To deploy services individually, use the following command:
   ```
   docker compose -f complete-deployment-compass.yaml up --detach --build <service-name>
   ```
