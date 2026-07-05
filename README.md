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
- [x] Metasploitable2 installed
- [ ] Wazuh installed and configured
- [ ] Internal network configured, all VMs communicating
- [ ] First attack (port scan) run and detected
- [ ] Documentation for each attack scenario

## What I'm Learning
Notes and lessons will go here as I build — what worked, what didn't,
and what I'd do differently.

- I l earned the difference between a full VM package (like Kali's .vbox
file) and a plain disk image (like Metasploitable's .vmdk) — the
second one needs you to build the VM shell yourself in VirtualBox.
- I realized how easy it is to accidentally attach the wrong disk to a
new VM when both are listed in the same dropdown — now I double-check
which file is selected before clicking Finish.
- I practiced documenting as I go instead of waiting until the end —
taking screenshots right after each step so I don't forget what I did.

**Difficulties I ran into:**

- Got confused about which OS I was actually working in (Windows vs.
Ubuntu) — I had Ubuntu installed but wasn't using it, which caused
me to run Linux commands in PowerShell by mistake.
- The Kali download page layout wasn't what I expected from online
guides — had to navigate by trial and error to find the right link.
- Almost attached the wrong virtual hard disk (Kali's instead of
Metasploitable's) since both were listed in the same dropdown —
caught it before finishing by double-checking the file name.
- Had to figure out that VirtualBox's keyboard "capture" meant my
screenshot shortcut wasn't reaching Windows — needed to click
outside the VM window first.
