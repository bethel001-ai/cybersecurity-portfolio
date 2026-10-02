# Passive Footprinting & Reconnaissance Intelligence Report

An open-source intelligence (OSINT) assessment mapping the external footprint of a financial technology entity (**Miahnation Financial Group**) using an authorized practice domain (`miahnationsecurity.site`).

## 🛠️ Tools & Methodology
* **DNS Enumeration:** `dig` (A, MX, NS, TXT, PTR)
* **Attack Surface Mapping:** `subfinder`, `theHarvester`
* **Infrastructure Discovery:** `whois`, ARIN registry querying
* **Information Leakage:** Scoped Google Dorking

## 📊 Key Findings
* **Infrastructure Monolith:** Identified 26 subdomains (including high-value targets like `admin`, `secure`, and `dev`) resolving to a singular AWS infrastructure node (`35.169.115.175`).
* **Email Spoofing Risk:** Discovered a soft-fail SPF configuration (`~all`) lacking protective DKIM/DMARC frameworks.

## 📁 Deliverables
* [Full Intelligence Report (PDF)](./intelligence-report.pdf)
