# Streamlined Wazuh SOC: Automated Detection & Response Lab

## 📌 Project Overview
An optimized, enterprise-grade Security Operations Center (SOC) lab environment. This project demonstrates sub-second threat detection and automated incident response using a lightweight, segmented architecture.

### Key Features:
* **Streamlined Architecture:** 3-node stack (Manager, Victim, Attacker) using a mix of LXC and VM for performance efficiency.
* **Automated Mitigation:** Configured Active Response to dynamically drop brute-force IPs via `iptables`.
* **Custom Visualization:** Purpose-built dashboards for real-time telemetry and "Kill Chain" tracking.
* **AI-Validated:** Leveraged AI as a technical consultant to source and validate industry-standard attack vectors for defensive testing.

## 🛠️ Tech Stack
* **SIEM:** Wazuh (Manager & Indexer)
* **Infrastructure:** Proxmox VE (LXC & KVM)
* **Networking:** Segmented VLANs, Virtual Bridges
* **Testing:** Kali Linux (Hydra, FIM testing)
