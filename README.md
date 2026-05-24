# SOC Home Lab – SSH Brute Force Detection

## Project Overview
This project demonstrates a beginner SOC Analyst home lab where an SSH brute-force attack was simulated using Kali Linux against an Ubuntu Server. The attack traffic was captured and analyzed using Wireshark, and authentication logs were investigated to identify malicious login attempts.

---

## Objectives
- Build a SOC home lab
- Simulate SSH brute-force attacks
- Analyze SSH traffic
- Investigate authentication logs
- Understand SOC Analyst workflow

---

## Lab Architecture

Kali Linux (Attacker)
        ↓
Ubuntu Server (Victim)
        ↓
Wireshark 

---

## Tools Used
- Kali Linux
- Ubuntu Server
- Wireshark
- Hydra
- OpenSSH

---

## Attack Simulation

### SSH Connection
```bash
ssh victim@192.168.x.x
