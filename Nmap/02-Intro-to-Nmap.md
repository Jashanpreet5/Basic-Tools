# Nmap Complete Notes (Network Enumeration)

Nmap (Network Mapper) is an open-source network analysis and security auditing tool used for reconnaissance and enumeration in cybersecurity.

It helps identify:
- Active hosts on a network
- Open ports
- Running services and versions
- Operating system details
- Firewall and IDS configurations

---

## Basic Nmap Syntax

```bash
nmap <scan types> <options> <target>
```

## Nmap Architecture

Nmap scanning is divided into the following main phases:

- **Host Discovery**  
  Identifies which hosts are alive on the network.

- **Port Scanning**  
  Determines which ports are open on the target system.

- **Service Enumeration and Detection**  
  Detects running services and their versions on open ports.

- **OS Detection**  
  Identifies the operating system and its version.

- **Scriptable Interaction (Nmap Scripting Engine - NSE)**  
  Uses scripts to interact with services, detect vulnerabilities, and gather deeper information.


