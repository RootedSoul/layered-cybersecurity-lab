# 🛡️ From Chaos to Configuration: A 7-Layer Cybersecurity Home Lab Framework

In cybersecurity, as in the world we live in, security is built in **layers**: gradually, deliberately, and with purpose.

I built my own home lab not just to sharpen technical skills, but to understand **what needs protecting** and **how protection truly works**.

My background in the **Cyber Operations degree program** at the University of Arizona gave me the essentials to start this project.

This repository documents the evolution of my thinking and lab implementation. I hope it serves others walking a similar path.

---

## 🔐 The 7-Stage Cybersecurity Framework

To frame my approach, I structured cybersecurity into seven interdependent stages.  
Each stage builds on the last and reflects a progression from awareness to ethical reflection.
It works best as a flexible guiding framework rather than a rigid, step-by-step checklist.

### 1. **Asset Visibility & Awareness of Inventory**  
 – Know what exists: systems, ports, processes, identities.

### 2. **Network Segmentation & Boundary Control**  
 – Define zones: who talks to whom, what stays isolated.

### 3. **System Hardening & Policy Enforcement**  
 – Lock down defaults, enforce configurations, reduce surface.

### 4. **Detection, Telemetry & Log Correlation**  
 – Observe patterns, trigger alerts, analyze events.

### 5. **Behavioral Modeling & Threat Simulation**  
 – Emulate attackers, understand users, predict misuse.

### 6. **Privilege & Access Management**  
 – Control privilege boundaries: limit escalation, assign roles.

### 7. **Containment, Forensics & Reflective Oversight**  
 – Response, recovery, ethical lessons, and future posture.

---

## 📊 Lab Implementation Overview


Each of the 7 layers includes purpose, tools, and metrics.

---

<details>
<summary><strong>1. Inventory — Visibility & Awareness</strong></summary>

**Purpose:**  
Identify systems, ports, processes, users, and assets.

**Tools Used:**  
VirtualBox, Ubuntu, Kali, Windows 10, `nmap`, `ping`, `ip a`

**Metrics / Indicators:**  
Asset list, IP map, open port chart

</details>

---

<details>
<summary><strong>2. Segmentation — Trust Zones & Boundary Control</strong></summary>

**Purpose:**  
Define trust zones and communication boundaries.

**Tools Used:**  
VirtualBox NAT / Host-only networking

**Metrics / Indicators:**  
Network map, isolation tests, firewall rule validation

</details>

---

<details>
<summary><strong>3. Hardening — System Lockdown & Policy Enforcement</strong></summary>

**Purpose:**  
Remove insecure defaults, enforce system and network policies.

**Tools Used:**  
`secpol.msc`, Group Policy Editor, `netsh`, Windows Firewall

**Metrics / Indicators:**  
Disabled services, denied access attempts, config baselines

</details>

---

<details>
<summary><strong>4. Detection — Logging & Correlation</strong></summary>

**Purpose:**  
Collect logs, observe patterns, detect anomalies.

**Tools Used:**  
Wireshark, `pwndbg` (for memory access during exploit testing)

**Metrics / Indicators:**  
Packet captures, alert logs, memory access timelines

</details>

---

<details>
<summary><strong>5. Simulation — Threat Emulation & Behavioral Modeling</strong></summary>

**Purpose:**  
Simulate adversaries, test system and user response.

**Tools Used:**  
Manual reverse shell (`bash`), staged payloads

**Metrics / Indicators:**  
Shell access logs, listener connection records

</details>

---

<details>
<summary><strong>6. Privilege — Access Control & Escalation Management</strong></summary>

**Purpose:**  
Control and audit privilege boundaries and escalation vectors.

**Tools Used:**  
`sudo`, `whoami`, `chmod`, UAC settings

**Metrics / Indicators:**  
Escalation attempts, permission audits

</details>

---

<details>
<summary><strong>7. Reflection — Forensics & Posture Revision</strong></summary>

**Purpose:**  
Analyze incidents, adapt posture, document evolution.

**Tools Used:**  
GitHub repo, markdown logs, version control

**Metrics / Indicators:**  
Change logs, forensics records, lessons learned

</details>


---

## 🧠 Why This Structure?

This structure is more than technical, it's symbolic.  
Inspired by system design, military doctrine, and spiritual ascent traditions, it trains **intuition alongside technical skill**.

Each layer doesn’t just harden a system, it disciplines the mind toward clarity, response, and resilience.

This is both a cybersecurity discipline and a personal methodology for aligning technical precision with clarity of mind.

---

## 🚧 Coming Soon

**Offensive Simulation:**
- Reverse shell attack write-up
- Apache webserver setup and exploitation

**Network Architecture:**
- Virtual network segmentation walkthrough
- Home lab system diagram

**Detection & Response:**
- Forensic memory capture and analysis
- Framework mapping (MITRE ATT&CK + NIST CSF)

---

## 🗂️ Repository Structure

```markdown
To be updated soon

“Feel free to fork this repo, use the framework, or share your adaptations.”
