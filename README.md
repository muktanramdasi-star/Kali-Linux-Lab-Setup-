# Kali-Linux-Lab-Setup-
A dedicated network lab setup and environment configuration built inside Kali Linux
### Kali Linux Network Lab Setup

This repository contains the setup and documentation for my networking lab environment built inside Kali Linux. 

### Purpose

The main goal of this lab is to configure network interfaces, practice troubleshooting connectivity issues, and run diagnostic tools to analyze internet traffic paths. 

### Tools Used

* **Ping:** Testing basic connectivity to local gateways and public servers.
* **Traceroute / MTR:** Tracing network hops to find where slowdowns or packet loss happen.
* **NetworkManager:** Managing and resetting network interfaces.

### Quick Commands Reference

Resetting network interfaces: 

bash

sudo systemctl restart NetworkManager
sudo dhclient -r && sudo dhclient

Use code with caution.

Testing direct IP routing: 

bash

ping -c 4 8.8.8.8

