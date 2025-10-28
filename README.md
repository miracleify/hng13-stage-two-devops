# HNG Stage 2 DevOps – Blue/Green Deployment with Nginx

## Overview

This project demonstrates a **Blue/Green deployment** of a Node.js application using **Docker Compose** and **Nginx**.  
- Blue is the **active** application.  
- Green is the **backup** application.  
- Nginx handles traffic routing and **automatic failover** when the active app fails.  

The setup also supports **chaos testing** via special endpoints to simulate downtime.

---
