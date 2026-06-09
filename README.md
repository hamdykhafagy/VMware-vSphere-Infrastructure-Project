# VMware Virtualization Infrastructure Project

## Project Overview
This project demonstrates the design and management of a high-availability virtualized environment using VMware ESXi and vCenter. The lab was implemented within VMware Workstation to simulate a professional data center infrastructure capable of handling mission-critical workloads.

## Core Project Requirements & Implementation
- **ESXi Deployment:** Installed and configured two ESXi hosts as virtual machines within VMware Workstation.
- **Centralized Management:** Deployed vCenter Server Virtual Appliance to manage the ESXi hosts.
- **Cluster Management:** Combined ESXi hosts into a cluster to enable advanced features: vMotion, High Availability (HA), and Distributed Resource Scheduler (DRS).
- **Virtual Machine Management:** 
    - Created virtual machines and performed lifecycle operations including cloning, snapshotting, and template creation.
    - Uploaded ISOs to a centralized content library.
    - Executed live migration of VMs between ESXi hosts.
- **Network Configuration:** Configured virtual switches (vSwitches) for management, VM Port Groups, and dedicated storage/migration traffic.
- **Storage Management:** Created and managed NFS datastores to support shared storage requirements.
- **Resilience & Fault Tolerance:** 
    - Configured HA and DRS, validating service continuity by simulating ESXi host failure.
    - Enabled Fault Tolerance (FT) on critical virtual machines for zero-downtime protection.

## Lab Architecture & Tech Stack
- **Hypervisor:** VMware Workstation (Nested Virtualization)
- **Core Components:** VMware ESXi, vCenter Server Appliance
- **Storage:** NFS Datastores
- **Management:** vSphere Web Client

---
*Project executed as part of the Information Technology Institute (ITI) System Administration track.*
