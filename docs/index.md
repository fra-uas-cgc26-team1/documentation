---
hide:
  - navigation
  - toc
---

<div align="center">
  <h1 style="font-size: 3rem; font-weight: 800; margin-bottom: 0;">Distributed AI Edge Cluster</h1>
  <p style="font-size: 1.2rem; color: #888;">An autonomous threat-detection system powered by High-Performance Computing.</p>
  <br>
  
  [System Architecture & Setup](infrastructure.md){ .md-button .md-button--primary }
  [View HPC Benchmarks](performance.md){ .md-button }
</div>

<br><br>

---

## 🎯 Executive Summary
This documentation details the development, integration, and performance analysis of an edge computing monitoring solution. The system automatically identifies individuals and detects threat situations (e.g., theft, fire, vandalism) using a highly consolidated, distributed hardware architecture.

!!! summary "System Capabilities at a Glance"
    * **High Availability:** Kubernetes (K3s) managed containerized services.
    * **Edge AI:** Real-time object detection via the Hailo-8L NPU.
    * **HPC Scalability:** Validated Amdahl's and Gustafson's Laws via MPI.
    * **Live Alerting:** Instant Telegram notifications via MQTT/REST.

## ⚙️ Core Architecture

The physical infrastructure leverages a consolidated Master-Worker cluster design to eliminate SD-card degradation and simplify OS management.

* 🧠 **Master Node:** Raspberry Pi 5 (Admin, TFTP/NFS Boot Server, K3s Control Plane)
* ⚡ **Worker Nodes:** Raspberry Pi 3 Cluster (PXE Network Booted)
* 👁️ **Vision Node:** Raspberry Pi AI Camera + AI HAT+ 

!!! tip "Navigating this Documentation"
    Use the navigation tabs at the top of the screen to explore specific subsystems, or click the **System Architecture** button above to begin with the physical deployment guides.