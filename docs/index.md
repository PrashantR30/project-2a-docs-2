
<p align="center">
   <!-- <font size="10"><b>Project 2A</b></font><br> -->
   <img src="./assets/project-2a-lockup.svg" width="240">
</p>

# Introduction
Mirantis Project 2A is designed to provide a consistent, scalable approach to deploying and managing Kubernetes clusters.<br><br>
The project aims to offer a repeatable, secure, and efficient method to leverage existing tools within the Kubernetes ecosystem, such as Cluster API, without modifications.<br><br>
This ensures flexibility while accommodating the diverse use cases common in enterprise IT environments. For more detailed information, refer to the [introduction](./introduction.md) .

# Key Objectives
Project 2A revolves around creating standardized templates that streamline cluster deployment and lifecycle management.
The project focuses on scalability, ease of use, and consistency.

### Core Components<br>
The main components of Project 2A include:

* **Hybrid Multi-Cluster Management (HMC):**
   Provides deployment and lifecycle management for Kubernetes clusters, handling configuration, updates, and all CRUD operations.

* **Cluster State Management (SMC):**
   Manages the installation and lifecycle of beachhead services, policies, Kubernetes API configurations, and more.

* **Observability (OBS):**
   Monitors clusters and beachhead services, including event logging and management of logs.


## Supported Cloud Providers
HMC leverages the Cluster API provider ecosystem to enable seamless integration with various cloud platforms. The following cloud providers currently have validated templates, with additional support planned. Follow the Quick Setup Guide for each provider below to get started:

 * [AWS](./aws/main.md)
 * [Azure](./azure/main.md)
 * [Vsphere](./vsphere/main.md)    
<hr>
