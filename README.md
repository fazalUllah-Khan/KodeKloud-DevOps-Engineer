# KodeKloud-DevOps-Engineer
This is collection of all my tasks as DevOps Engineer working in Project Nautilus a subdivision of the xFusionCorp Industries.

# Project Nautilus¶

# Overview¶

Project Nautilus is the Naval subdivision of the xFusionCorp Industries. Nautilus Application helps the Naval forces to make smart procurement decisions of their manned or unmanned maritime systems while ensuring that the operational requirements are met. It also aims to provide the best-in-class operational support, improving the safety and life extension of existing machines and reducing the cost of ownership.

# Current Repertoire¶

Sonar Technology and Systems
LUSV - Large Unmanned Surface Vehicles
Autonomous Unmanned Undersea Pods
Nuclear Submarines
Laser Guidance Systems

# Application Architecture¶

Nautilus deployment architecture can be viewed here

The Nautilus is a three-tier application and is deployed in the Stratos Datacenter in the North America Region.

# Data Tier: 
The Data tier is the layer that stores data with the retrieval storage and execution methods made by the application layer. We are making use of MariaDB which is one of the most popular open source relational databases.

# Application Tier: 
Makes use of a LAMP which is a stack of open-source software that can be used to create web applications. LAMP is an acronym that usually consists of the Linux OS, the Apache HTTP Server, a MySQL relational DBMS (like MariaDB), and PHP.

# Client Tier: 
The application client which in this case is a web browser software that processes and displays HTML resources, issues HTTP requests for resources, and processes HTTP responses.

# Load Balancer: 
Nginx is used for HTTP Load Balancing to distribute requests through multiple application servers.

<img width="1171" alt="image" src="https://github.com/fazalUllah-Khan/KodeKloud-DevOps-Engineer/assets/148821704/4f05bd3d-8b76-48ab-a408-a99b5346e70b">

# Shared Services¶

* Storage Filer: A NAS (Network Attached Storage) filer is used to provide reliable and stable external storage for the application tier servers.
* SFTP Server: SFTP, which stands for SSH File Transfer Protocol is used to transfer data amongst two remote systems.
* Backup Server: A staging backup system used for short term archival.
* Jump Server: The intermediary host or an SSH gateway to a remote network hosting the Nautilus application.

# Infrastructure Details¶

<img width="776" alt="image" src="https://github.com/fazalUllah-Khan/KodeKloud-DevOps-Engineer/assets/148821704/a02b27d0-2f9e-4e06-b096-d88761eb8320">

