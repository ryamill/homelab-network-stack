# Homelab Network Stack
This repository contains the configuration and documentation for my personal homelab network infrastructure. It details the setup, services, and various components that make up my home network environment.

  ## Table of Contents
  * [Overview](#Overview)
  * [Components](#Components)
  * [Hardware](#Hardware)
  * [Components](#Components)
  * [Software & Services](#Software&Services)
  * [Configuration Structure](#ConfigurationStructure)
  * [Network Diagrams](#NetworkDiagrams)
  * [Contributing](#Contributing)

  <hr>

  ## Overview
  The homelab-network-stack repository serves as a centralized and version-controlled source for all aspects of my home network. My goal is to maintain a robust, secure, and highly available network that supports various homelab services, including virtualization, container orchestration, media servers, and general home automation. This documentation aims to provide a clear understanding of the network's design and implementation.

  ## Components

  ### Hardware
  * Router/Firewall:  
  * Switch(es):
  * Access Point(s):
  * Server(s) / Compute:

  ### Software & Services
  
  ### Operating Systems:

  [OS Name, e.g., Proxmox VE, Debian, Ubuntu Server]

  ### Network Services:
  * DHCP: [Service/Tool, e.g., pfSense DHCP Server]
  * DNS: [Service/Tool, e.g., Pi-hole, Unbound]
  * VPN: [Service/Tool, e.g., OpenVPN, WireGuard]

  ### Containerization/Orchestration:
  * [Tool, e.g., Docker, Kubernetes (k3s/k8s)]

  ### Configuration Management:
  * [Tool, e.g., Ansible, Terraform]

  ### Monitoring:
  * [Tool, e.g., Prometheus, Grafana, Zabbix]
  * [Add any other relevant software/services, e.g., Plex, Home Assistant, Nextcloud]

  ## Configuration Structure
  
  This repository is organized to logically separate different aspects of the network configuration:

  ./firewall/: Firewall rules, NAT configurations, and general router settings.
  ./networking/: VLAN definitions, IP addressing schemes, and switch configurations.
  ./dns/: DNS records, Pi-hole configurations, and custom host entries.
  ./vpn/: VPN server and client configurations.
  ./ansible/: Ansible playbooks for automating server and service deployments.
  ./terraform/: Terraform configurations for infrastructure as code.
  ./docs/: Additional documentation, notes, and troubleshooting guides.
  ./diagrams/: Network topology diagrams (logical and physical).

  ## Network Diagrams
  
  Detailed network diagrams will be included in the ./diagrams/ directory. These will illustrate:

  * Logical Network Diagram: Showing VLANs, subnets, and routing paths.
  * Physical Network Diagram: Depicting hardware connections and cable runs.
  * Service Flow Diagram: Illustrating how different services interact across the network.

  ## Contributing
  
  While this is primarily a personal repository, I welcome suggestions and feedback. If you have any questions or spot an area for improvement, feel free to open an issue.
  
