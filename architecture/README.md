## Architecture

This directory contains network topology diagrams and infrastructure schemes.

### Current Design

The infrastructure is deployed on a virtualized environment using Oracle VirtualBox with the following specifications:

* **CPU:** 8 cores
* **RAM:** 8 GB
* **Storage:** 150 GB (SATA)

### Components

* **Linux Server**

  * Acts as the central node of the infrastructure
  * Provides user management, access control, and core services

* **Network Configuration**

  * Bridged network interface for external connectivity
  * Internal network interface for isolated communication

* **Security Layer**

  * The server acts as a **gateway** and **firewall**, controlling traffic between networks

### Diagram

See the **HMCI Overview** diagram for a high-level view of the infrastructure.
