# Learned a simple setup of Azure Load Balancer 

## What is Azure Load Balancer?

Azure Load Balancer is a highly available, fully managed service that distributes incoming network traffic across multiple backend resources such as Virtual Machines (VMs) within Azure. It operates at Layer 4 (Transport Layer) of the OSI model, enabling it to handle both TCP and UDP traffic. The key goals are high availability, scalability, and resilience—ensuring that applications remain responsive and reliable even under heavy load or when individual backend servers fail.

## Key Features:

- Distributes inbound and outbound network traffic

- Supports both public (Internet-facing) and internal (private) traffic scenarios

- Provides health probes to monitor backend resource status

- Offers port forwarding and outbound NAT functionality

- Scales to millions of flows for all TCP/UDP applications

- Integration with other Azure services and security models

## Types of Azure Load Balancer

- Public - Distribute Internet traffic to VMs - Internet-facing
- Internal - (Private)	Distribute traffic within a Virtual Network (VNet) - Private only

There are also Basic and Standard SKUs, with Standard offering more features, reliability, and integration options

## Setup 

<img width="1039" height="590" alt="Screenshot 2025-07-22 at 8 54 48 PM" src="https://github.com/user-attachments/assets/d0aa8fd6-b323-4e9c-a0f9-9580504a1b19" />
