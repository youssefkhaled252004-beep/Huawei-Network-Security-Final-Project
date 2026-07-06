# Enterprise Network Security Infrastructure

Multi-site enterprise network security design built in Huawei eNSP, simulating a real-world secure corporate network.

![Network Topology](./topology-diagram.png)

## Overview
Connected two sites via three VPN types (GRE, IPSec, L2TP), with Master/Backup 
firewall high-availability via HRP, zone-based security policy (Trust/DMZ/Untrust), 
source & server NAT, and an integrated wireless network (AC/AP).

## Requirements Implemented
1. Physical & IP addressing schema
2. Full security infosec policy with security zones
3. Source NAT & server NAT
4. WLAN deployment
5. HRP (firewall redundancy)
6. VPN tunnels: GRE, IPSec, L2TP
7. End-to-end connectivity verified via sec-client

## Tech Stack
Huawei VRP · eNSP Simulator · Firewall (USG) · HRP · GRE · IPSec · L2TP · NAT · WLAN/AC-AP