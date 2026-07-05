# Home SOC Lab

## Overview
A self-built Security Operations Center (SOC) lab for practicing attack
detection and log analysis. Built entirely on a personal laptop using
VirtualBox — no cloud costs, fully isolated from my real network.

**Status:** 🚧 Work in progress

## Goal
Practice identifying and analyzing common attacks (port scans, brute-force
login attempts, exploitation) by generating them myself and detecting them
through a SIEM, to build hands-on skills for SOC analyst / security
analyst roles.

## Architecture
- **Attacker:** Kali Linux
- **Victim:** Metasploitable2
- **Monitoring/SIEM:** Wazuh (on Ubuntu Server)
- **Network:** All VMs on an isolated internal VirtualBox network (not
connected to my real LAN)

(Diagram coming soon)

## Tools Used
- VirtualBox
- Kali Linux
- Metasploitable2
- Wazuh

## Progress Log
- [x] Set up VirtualBox
- [x] Kali Linux installed
- [ ] Metasploitable2 installed
- [ ] Wazuh installed and configured
- [ ] Internal network configured, all VMs communicating
- [ ] First attack (port scan) run and detected
- [ ] Documentation for each attack scenario

## What I'm Learning
Notes and lessons will go here as I build — what worked, what didn't,
and what I'd do differently.
