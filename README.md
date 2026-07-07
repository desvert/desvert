# Hi, I'm Nick 👋

I'm a commercial HVAC technician finishing a BS in Cybersecurity Technology, open to opportunities in OT/ICS security, systems administration, and defensive security. Coming from trade work and emergency services, I tend to think in terms of reliability, failure modes, and systems that have to work under real-world conditions.

---

## Current Focus
- OT/ICS security concepts, protocols (Modbus, BACnet), and lab environments
- Network security monitoring with Suricata and Zeek
- Python tooling for PCAP analysis and protocol parsing
- Preparing for a multi-semester digital forensics track -- disk, memory, and network forensics

---

## Selected Projects

### 🔬 otparse-mcp
**[`otparse-mcp`](https://github.com/desvert/otparse-mcp)** A containerized MCP server that parses Modbus/TCP and BACnet/IP packet captures using tshark and returns structured JSON for LLM-assisted analysis. Built to support OT/ICS traffic triage workflows.

*Focus: OT/ICS protocols, packet analysis, MCP tooling, Python*

### 🕸️ netparse
**[`netparse`](https://github.com/desvert/netparse)** A general-purpose PCAP forensics MCP server, complementing otparse-mcp's OT/ICS focus with broader network traffic analysis for LLM-assisted triage.

*Focus: Network forensics, PCAP analysis, MCP tooling, Python*

### 🧪 mcp-test-env
**[`mcp-test-env`](https://github.com/desvert/mcp-test-env)** Containerized attack simulation lab with a red team node and sensor stack, used to generate and validate traffic for otparse-mcp and netparse development.

*Focus: Docker, attack simulation, detection tuning*

### 🌡️ ot-hvac-testbed
**[`ot-hvac-testbed`](https://github.com/desvert/ot-hvac-testbed)** Microcontroller-driven HVAC control and instrumentation testbed exploring real-world OT concepts -- sensor telemetry, actuator control, serial data logging, and control logic across multiple platforms.

*Focus: OT/ICS fundamentals, embedded systems, Linux-based data logging, system reliability*

---

## Tools & Technologies

Linux (Ubuntu, Rocky) • Docker/Compose • Python • Bash • Git • tshark/pyshark • Suricata • Zeek • Modbus/TCP • BACnet/IP • TCP/IP networking • systemd

---

## Background

BS Cybersecurity Technology, UMGC (CAE-CD designated institution) -- in progress. Prior background in commercial HVAC, firefighting, and EMS. Home lab spans virtual and physical infrastructure -- dedicated NSM sensor and red team nodes, ESP32 wireless telemetry over MQTT, and Docker/Vagrant environments (currently being rebuilt post-migration) for networking and security practice.

**Technical blog:** [desvert.github.io](https://desvert.github.io)

---

*Repositories here are intentionally documented to reflect operational thinking -- small systems that recover cleanly from failure and are easy to hand off.*
