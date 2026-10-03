# Network-Security-Virtual-SOC-Lab-VMWARE-
Virtualized lab simulating a segmented enterprise network protected by a FortiGate firewall and monitored with IDS/IPS and SIEM tools.
- Built a segmented network in VMware with separate Sales and IT LANs behind a FortiGate firewall with IPS enabled
- Deployed Suricata as a network IDS on a mirrored traffic segment and Snort on a Sales LAN host to detect malicious activity
- Integrated Wazuh SIEM for centralized log collection, alerting, and monitoring
- Simulated attacks (e.g., [Nmap scan, brute force]) and investigated the resulting alerts
- Documented the topology, ports, and traffic flow in a diagram
