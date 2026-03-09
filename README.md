# configuring-basic-switch-management

## Objective
The objective of this lab is to configure and manage the basic administrative settings of a network switch. The lab demonstrates how to establish console access and secure console management, enable remote management access, configure essential switch parameters, and verify connectivity to ensure proper operation within a local area network environment.

## Skills learned
- Configuring basic switch settings such as hostname and management interface
- Configuring and securing console access for local switch management
- Assigning an IP address to a switch for remote management
- Configuring default gateway settings for switch management
- Accessing and configuring the switch through the CLI
- Verifying network connectivity using basic troubleshooting commands
  
## Tools used
- Cisco Packet Tracer
- Cisco switch command-line interface (CLI)
- Console cable for local switch configuration
- Layer 2 switching technologies
- Network simulation environment

## Commands Practiced
- enable
- configure terminal
- hostname
- interface vlan 1
- ip address
- no shutdown
- ip default-gateway
- show running-config
- show ip interface brief

## Lab Topology
<img width="600" alt="image" src="https://github.com/user-attachments/assets/0a412a08-7cf7-4204-b590-6f14e9a0b5ff" />

In this LAB, PC0 on the right is connected to the switch using a console cable providing direct CLI access for initial configuration. This out-of-band connection allows administrators to configure the switch even before a management IP address is assigned.

PC1 however is connected to the switch through an Ethernet interface, allowing it to communicate within the LAN. After the switch management interface is configured, PC1 can remotely access the switch using VTY lines, demonstrating in-band management.

## Securing user mode privileged mode with simple passwords
<img width="600" alt="image" src="https://github.com/user-attachments/assets/a52a8bb7-31c3-4ce8-b8ac-78d2bdb21889" />

<img width="600" alt="image" src="https://github.com/user-attachments/assets/d3f3292e-9eb9-4004-a735-ef501b347332" />

<img width="600" alt="image" src="https://github.com/user-attachments/assets/7e8fa98c-e9fe-4a99-ba78-9024fc7600da" />

<img width="600" alt="image" src="https://github.com/user-attachments/assets/facbbd94-5d3c-493f-9ccb-35d8de51d2ea" />

<img width="600" alt="image" src="https://github.com/user-attachments/assets/18845435-7ee5-4e3e-be46-db0424572e52" />

## Securing user mode access with local usernames
<img width="600" alt="image" src="https://github.com/user-attachments/assets/262b332b-2c38-423d-9964-268c4b24d93f" />
<img width="600" alt="image" src="https://github.com/user-attachments/assets/460804ef-7eb0-48fc-bf5f-a9b3a4ad8c86" />


## Securing user mode access with external authentication servers

## Securing remote access with Secure Shell (SSH)

## Verification
