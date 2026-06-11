# Distributed AI: Edge Computing Threat Detection

Welcome to the official documentation for our High Integrity Systems semester project. 

## Project Objective
This system is an edge computing monitoring solution designed to automatically identify people and detect threat situations such as theft, fire, or vandalism. It combines high-performance cluster computing with real-time artificial intelligence inference.

## Core Architecture
Our deployment utilizes a highly consolidated, distributed architecture:

* **Master Node:** Raspberry Pi 5 (Handling cluster administration and Kubernetes backend)
* **Worker Nodes:** Raspberry Pi 3 High-Availability Cluster
* **AI Edge Vision:** Raspberry Pi AI Camera & AI HAT+ (Hailo-8L NPU)
* **Distributed Software Stack:**
    * **HPC & Scaling:** Message Passing Interface (MPI)
    * **Cloud Infrastructure:** K3s (Kubernetes), Docker
    * **Storage:** Distributed object storage (Ceph/MinIO)
    * **Monitoring:** Prometheus & Grafana
    * **Frontend:** Vue.js / React mapped interface