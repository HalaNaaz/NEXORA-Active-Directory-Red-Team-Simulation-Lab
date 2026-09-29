# NEXORA AD RED TEAM SIMULATION LAB

## Project Status

Phase: Environment Preparation
Status: In Progress

## Lab Purpose

A controlled Active Directory red-team simulation environment for practicing
enterprise identity security, enumeration, attack simulation, detection,
hardening, and incident investigation.

## Host Systems

### Primary Lab Host
- ASUS TUF Gaming A15
- Windows 11
- 16 GB RAM
- RTX 3050 4 GB
- 512 GB SSD

### Secondary Security Workstation
- Lenovo G50
- 8 GB RAM
- 256 GB SSD
- Parrot OS

The Lenovo remains separate from the core AD lab unless explicitly required.

## Virtualization

- VMware Workstation
- Kali Linux VM

## Lab Network

Network: 192.168.56.0/24
VMnet: VMnet2
Network Type: Host-only
DHCP: Disabled

## Current Kali Configuration

- eth0: NAT
- eth1: 192.168.56.50/24
- Default route: eth0

## Planned Core Lab

- DC01 — Domain Controller
- APP01 — Application/Server workload
- WS-HR01 — HR workstation
- WS-DEV01 — Developer workstation
- Kali — Red-team workstation

## Safety Boundary

The Active Directory lab is isolated from the normal host network and
Internet-facing infrastructure. Testing is restricted to the controlled
lab environment.

## Evidence

Screenshots, logs, command output, findings, configurations, and reports
will be stored under the EVIDENCE directory.

