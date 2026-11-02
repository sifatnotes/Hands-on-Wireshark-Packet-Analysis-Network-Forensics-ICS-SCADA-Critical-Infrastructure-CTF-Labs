# Hands-on-Wireshark-Packet-Analysis-Network-Forensics-ICS-SCADA-Critical-Infrastructure-CTF-Labs
A practical collection of cybersecurity CTF labs covering deep packet analysis (Wireshark fundamentals, display filters, DNS tunneling/leakage, TCP handshake , raw wire protocols) &amp; Operational Technology / ICS / SCADA security (substation outages, water plant intrusions, HMI zone security, industrial protocol analysis, power grid SOC drills).
# Wireshark Packet Analysis, Network Forensics & ICS/SCADA Critical Infrastructure CTF Labs

Welcome to the **Wireshark Packet Analysis, Network Forensics & ICS/SCADA Critical Infrastructure CTF Lab Collection**. This repository serves as an organized, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on deep protocol inspection, packet capture analysis, and Industrial Control Systems / Operational Technology (ICS/OT) defense—spanning **Wireshark Fundamentals & Deep Packet Forensics (Wireshark capture mechanics, complex display filters, TCP handshake anomaly tracking, protocol wire analysis)**, **DNS & TCP Network Telemetry (DNS exfiltration/leaks, TCP stream assembly, hidden payload extraction)**, **ICS/SCADA Security, HMI & Industrial Protocols (Modbus/DNP3 water plant intrusions, HMI zone security, SCADA telemetry monitoring)**, and **Critical Infrastructure Defense & Outage Incident Response (Power grid SOC drills, substation outage response, safety-instrumented system threats)**.

---

## Lab Collection Index

### 1. Wireshark Fundamentals & Packet Capture Mechanics
* **Wireshark Fundamentals: Packet Detective**  
  *Lab Link:* [https://learn.secbyte.org/ctf/wireshark-fundamentals-packet-detective](https://learn.secbyte.org/ctf/wireshark-fundamentals-packet-detective)  
  *Focus:* Core principles of Wireshark navigation, analyzing packet capture files (`.pcap`/`.pcapng`), navigating protocol tree hierarchies, and extracting exported objects.

* **Packet Capture Pursuit**  
  *Lab Link:* [https://learn.secbyte.org/ctf/packet-capture-pursuit](https://learn.secbyte.org/ctf/packet-capture-pursuit)  
  *Focus:* Live packet capture workflows using `dumpcap` and `tshark`, tuning capture buffers, configuring ring buffers, and capturing traffic across high-throughput network interfaces.

* **Display Filters: Log Sleuthing & Hidden Indicators**  
  *Lab Link:* [https://learn.secbyte.org/ctf/display-filters-log-sleuthing-hidden-indicators](https://learn.secbyte.org/ctf/display-filters-log-sleuthing-hidden-indicators)  
  *Focus:* Authoring complex Wireshark display filter expressions, leveraging boolean operators, filtering by byte offsets, and isolating subtle indicators of compromise (IoCs).

<Image src="image_agent_tag_3940253182291092428" alt="Wireshark packet analysis diagram showing network protocol header structures" caption="Wireshark Packet Capture & Protocol Header Analysis Pane" />

---

* **Protocol Analysis: Reading the Wire**  
  *Lab Link:* [https://learn.secbyte.org/ctf/protocol-analysis-reading-the-wire](https://learn.secbyte.org/ctf/protocol-analysis-reading-the-wire)  
  *Focus:* Reading raw binary protocol frames, analyzing Ethernet II headers, inspecting IPv4/IPv6 options, and dissecting Transport Layer protocol fields.

### 2. DNS & TCP Traffic Analysis
* **DNS Traffic Analysis: Hidden Names & Leaky Queries**  
  *Lab Link:* [https://learn.secbyte.org/ctf/dns-traffic-analysis-hidden-names-leaky-queries](https://learn.secbyte.org/ctf/dns-traffic-analysis-hidden-names-leaky-queries)  
  *Focus:* Detecting covert DNS tunneling exfiltration (TXT/CNAME queries), inspecting suspicious subdomains, analyzing DNS over HTTPS (DoH) traffic, and isolating internal query leaks.

* **TCP Analysis: From Handshake to Hidden Data**  
  *Lab Link:* [https://learn.secbyte.org/ctf/tcp-analysis-from-handshake-to-hidden-data](https://learn.secbyte.org/ctf/tcp-analysis-from-handshake-to-hidden-data)  
  *Focus:* Analyzing TCP 3-way handshakes (SYN, SYN-ACK, ACK), detecting TCP reset (`RST`) injection, evaluating window scaling/retransmissions, and extracting covert data embedded in TCP options.

### 3. ICS/SCADA Security & Industrial Protocols
* **Industrial Protocols: Water Plant Intrusion**  
  *Lab Link:* [https://learn.secbyte.org/ctf/industrial-protocols-water-plant-intrusion](https://learn.secbyte.org/ctf/industrial-protocols-water-plant-intrusion)  
  *Focus:* Analyzing industrial control traffic (Modbus TCP, DNP3, EtherNet/IP), identifying unauthorized register write commands (`Function Code 06/16`), and triaging water treatment plant intrusions.

* **SCADA Monitoring: From Telemetry to Incident Detection**  
  *Lab Link:* [https://learn.secbyte.org/ctf/scada-monitoring-from-telemetry-to-incident-detection](https://learn.secbyte.org/ctf/scada-monitoring-from-telemetry-to-incident-detection)  
  *Focus:* Auditing SCADA telemetry feeds, detecting anomalous polling frequencies, identifying spoofed sensor values, and configuring OT network intrusion detection rules.

* **ICS Security Assessment: From HMI to Zone Trust**  
  *Lab Link:* [https://learn.secbyte.org/ctf/ics-security-assessment-from-hmi-to-zone-trust](https://learn.secbyte.org/ctf/ics-security-assessment-from-hmi-to-zone-trust)  
  *Focus:* Auditing Human-Machine Interface (HMI) workstations, verifying Purdue Model architecture zone segmentation, and identifying unencrypted control channel trust violations.

### 4. Critical Infrastructure Defense & Outage Incident Response
* **Critical Infrastructure Defense: Power Grid SOC Drill**  
  *Lab Link:* [https://learn.secbyte.org/ctf/critical-infrastructure-defense-power-grid-soc-drill](https://learn.secbyte.org/ctf/critical-infrastructure-defense-power-grid-soc-drill)  
  *Focus:* Executing defensive SOC triage drills during simulated cyber attacks against electric power grid control networks, isolating compromised jump boxes, and restoring system visibility.

<Image src="image_agent_tag_3940253182291095373" alt="SCADA based power systems network architecture diagram including control centers and substations" caption="Power System SCADA & Substation Network Architecture" />

---

* **ICS Threats: From Recon to Safety Impact**  
  *Lab Link:* [https://learn.secbyte.org/ctf/ics-threats-from-recon-to-safety-impact](https://learn.secbyte.org/ctf/ics-threats-from-recon-to-safety-impact)  
  *Focus:* Analyzing multi-stage APT attack lifecycles targeting Industrial Control Systems—from initial OT network recon to tampering with Safety Instrumented Systems (SIS).

* **ICS Incident Response: Substation Outage**  
  *Lab Link:* [https://learn.secbyte.org/ctf/ics-incident-response-substation-outage](https://learn.secbyte.org/ctf/ics-incident-response-substation-outage)  
  *Focus:* Conducting forensic incident response for electrical substation outages, triaging malicious IEC 60870-5-104 / IEC 61850 breaker trips, and reconstructing attacker timelines.

---

## Learning Path

### Path A: Wireshark Packet Analyst & Network Forensic Examiner
1. **Packet Capture & Filters:** Start with [Wireshark Fundamentals](https://learn.secbyte.org/ctf/wireshark-fundamentals-packet-detective), [Packet Capture Pursuit](https://learn.secbyte.org/ctf/packet-capture-pursuit), and [Display Filters](https://learn.secbyte.org/ctf/display-filters-log-sleuthing-hidden-indicators).
2. **Protocol Inspection:** Master protocol mechanics in [Protocol Analysis: Reading the Wire](https://learn.secbyte.org/ctf/protocol-analysis-reading-the-wire), [DNS Traffic Analysis](https://learn.secbyte.org/ctf/dns-traffic-analysis-hidden-names-leaky-queries), and [TCP Analysis](https://learn.secbyte.org/ctf/tcp-analysis-from-handshake-to-hidden-data).

### Path B: ICS/SCADA Security & Industrial Protocol Specialist
1. **Industrial Traffic & Monitoring:** Audit OT protocols via [Industrial Protocols: Water Plant Intrusion](https://learn.secbyte.org/ctf/industrial-protocols-water-plant-intrusion) and [SCADA Monitoring](https://learn.secbyte.org/ctf/scada-monitoring-from-telemetry-to-incident-detection).
2. **HMI & Zone Trust:** Validate OT architecture in [ICS Security Assessment: From HMI to Zone Trust](https://learn.secbyte.org/ctf/ics-security-assessment-from-hmi-to-zone-trust).

### Path C: Critical Infrastructure Defender & OT Incident Responder
1. **Power Grid Defense:** Respond to SOC drills in [Critical Infrastructure Defense: Power Grid SOC Drill](https://learn.secbyte.org/ctf/critical-infrastructure-defense-power-grid-soc-drill).
2. **Threats & Substation Outages:** Investigate OT attacks in [ICS Threats: From Recon to Safety Impact](https://learn.secbyte.org/ctf/ics-threats-from-recon-to-safety-impact) and [ICS Incident Response: Substation Outage](https://learn.secbyte.org/ctf/ics-incident-response-substation-outage).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding direct link to launch the exercise environment hosted on Learn SecByte.
3. Review scenario directives, Wireshark packet captures (`.pcap`/`.pcapng`), industrial protocol logs, or OT network topology diagrams.
4. Construct advanced display filters, decode Modbus/DNP3 function codes, identify covert DNS tunneling queries, analyze TCP handshake anomalies, or triage malicious electrical breaker trip commands to capture flags.

---

## Target Audience

* **SOC Analysts & Network Forensics Examiners:** Master Wireshark display filters, analyze PCAP captures, detect DNS exfiltration, and inspect TCP stream data.
* **ICS/OT Security Engineers & SCADA Administrators:** Audit Modbus/DNP3 industrial protocols, verify Purdue Model zone segmentation, and secure HMI workstations.
* **Critical Infrastructure Incident Responders:** Investigate power grid cyber attacks, triage electrical substation outages, and analyze Safety Instrumented System (SIS) threats.
* **Cybersecurity Students:** Acquire practical hands-on experience in network packet analysis, industrial protocol mechanics, and operational technology security.

---

## Disclaimer

All lab links provided in this repository direct to official training environments hosted on Learn SecByte. All materials and exercises are provided strictly for educational purposes, defensive skill building, and authorized security research. Unauthorized packet interception, scanning, or industrial control tampering against production networks is strictly prohibited.
