# Homelab Network Stack
This repository contains the configuration and documentation for my personal homelab network infrastructure. It details the setup, services, and various components that make up my home network environment.

  ## Table of Contents
  * [Overview](#Overview)
  * [Components](#Components)
  * [Hardware](#Hardware)
  * [Components](#Components)
  * [Software & Services](#Software--Services)
  * [Configuration Structure](#Configuration-Structure)
  * [Network Diagrams](#Network-Diagrams)
  * [Contributing](#Contributing)

  <hr>

  ## Overview
  The homelab-network-stack repository serves as a centralised and version-controlled source for all aspects of my home network. My goal is to maintain a robust, secure, and highly available network that supports various homelab services, including virtualisation, container orchestration, media servers, and general home automation. This documentation aims to provide a clear understanding of the network's design and implementation.

  <hr>

  ## Components

  ### Hardware
  * **Router/Firewall:** Ubiquiti Dream Machine Pro (UDM-Pro)
  * **Switch(es):** Ubiquiti Networks Pro HD 24-Port PoE Layer 3 (USW-Pro-HD-24-PoE 600W)
  * **Access Point(s):** 2x Ubiquiti U7 Pro Wall (U7-Pro-Wall)
  * **Camera System (NVR):** Ubiquiti Network Video Recorder (UNVR)
  * **NAS:** Ubiquiti UNAS Pro (UNAS-Pro)
  * **Server(s) / Compute:** Supermicro (32 x Intel Xeon CPU E5-2620 v4 @ 2.10GHz 2 Sockets / 192GB RAM)
  * **IoT Devices:** Google Home, Google Play, Phillips Hue Hub and Phillips Smart Lights, security cameras, smart thermostats, smart appliances.
  * **End User Devices:** Laptops, desktops, smartphones, gaming consoles.
  * **WAN:**:  Fibre to the premise (FTTP) through Aussie Broadband - NBN Ultra-Fast 1000Mbps/50Mbps Unlimited

  ### Software & Services
  * [Software and tools]
  
  ### Operating Systems:
  * **Server:** Proxmox 8.4

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

  <hr>

  ## Configuration Structure
  
  This repository is organized to logically separate different aspects of the network configuration:

  * ./firewall/: Firewall rules, NAT configurations, and general router settings.
  * ./networking/: VLAN definitions, IP addressing schemes, and switch configurations.
  * ./dns/: DNS records, Pi-hole configurations, and custom host entries.
  * ./vpn/: VPN server and client configurations.
  * ./ansible/: Ansible playbooks for automating server and service deployments.
  * ./terraform/: Terraform configurations for infrastructure as code.
  * ./docs/: Additional documentation, notes, and troubleshooting guides.
  * ./diagrams/: Network topology diagrams (logical and physical).

  <hr>

  ## Network Diagrams
  
  Detailed network diagrams will be included in the ./diagrams/ directory. These will illustrate:

  * Logical Network Diagram: Showing VLANs, subnets, and routing paths.
  * Physical Network Diagram: Depicting hardware connections and cable runs.
  * Service Flow Diagram: Illustrating how different services interact across the network.

  ## Contributing
  
  While this is primarily a personal repository, I welcome suggestions and feedback. If you have any questions or spot an area for improvement, feel free to open an issue.
  
