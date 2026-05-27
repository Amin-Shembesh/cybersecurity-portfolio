# Technical Portfolio: Cybersecurity Infrastructure & Assessment

Welcome! This repository centralizes the technical case studies, architectural briefs, and implementation write-ups for my hands-on cybersecurity projects. 

---

## 💻 Featured Technical Projects

### 1. Enterprise-Grade IDS/IPS & SIEM Pipeline Integration
*Architected and deployed a multi-tier network defense architecture to centralize log management and engineer custom detection logic.*

👉 **[Click Here to View the Full Engineering Brief & Architecture Logs (PDF)](./Enterprise_Grade_IDS_IPS_SIEM_Pipeline_Integration.pdf)**

#### Key Implementations & Technical Milestones:
* **Architecture:** Architected a production-ready, three-tier SOC defense stack connecting a pfSense perimeter gateway to a centralized Wazuh SIEM manager through a fully instrumented log ingestion pipeline.
* **Custom XML Decoder Engineering:** Designed and scripted custom XML decoder logic to safely coexist with native Wazuh rule signatures, resolving local logging conflicts and achieving granular, zero-loss log visibility across all monitored endpoints.
* **Suricata IDS/IPS Optimization:** Diagnosed and resolved virtual network packet-drop anomalies by bypassing checksum validation constraints via targeted configuration overrides, enabling Suricata to accurately inspect, classify, and drop malicious edge traffic.
* **Log Transport & Normalization:** Configured rsyslog pipelines and user group permissions to allow the Wazuh Agent to seamlessly consume raw Suricata alert payloads; resolved critical YAML/JSON serialization errors to deliver clean, structured, searchable data arrays to the Kibana visualization layer.
* **Validation & Attack Simulation:** Verified full-stack detection efficacy by executing live Path Traversal attack simulations and injecting custom HTTP request headers (e.g., "BlackSun" User-Agent triggers) to confirm strict detection and blocking rule enforcement end-to-end.

---

### 2. Web Application & WAF Vulnerability Assessment (Independent Security Research)
*Conducted an independent, real-world penetration test and security evaluation of Web Application Firewall configurations and production web application attack surfaces.*

👉 **[Click Here to View the Full Assessment & Mitigation Report (PDF)](./Web_Application_WAF_Vulnerability_Assessment.pdf)**

#### Key Implementations & Technical Milestones:
* **Vulnerability Assessment:** Conducted an independent, deep-dive security evaluation and penetration test of Web Application Firewall configurations and modern web application attack surfaces.
* **Threat Mapping & Defenses:** Mapped active threat sequences against the OWASP Top 10 matrix and systematically analyzed WAF bypass mechanisms to identify architectural gaps, document vulnerabilities, and formulate production-grade hardening defenses.

---

## 🛠️ Summary of Core Technical Competencies
* **SIEM & Log Operations:** Log transport pipelines, rsyslog, JSON/YAML data serialization, and custom XML decoder development.
* **Network Security Engineering:** Perimeter gateway firewalls (pfSense), IDS/IPS fine-tuning (Suricata), traffic inspection, and network architecture design.
* **Application Security & Pen Testing:** Independent security research, vulnerability assessments, OWASP Top 10 mapping, WAF bypass analysis, and active threat emulation.

---
*Note: The projects represented above consist of a locally architected security engineering lab and an independent web application penetration testing assessment. Full structural proofs, configurations, and research logs are preserved in the briefs above.*
