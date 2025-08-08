# ASEAN SMS Phishing Campaign - Indicators of Compromise (IOCs)

This repository provides Indicators of Compromise (IOCs) related to an active and sophisticated SMS phishing campaign targeting individuals and organizations across Thailand and the broader ASEAN region. These IOCs are shared to aid cybersecurity professionals, network defenders, and individuals in detecting, blocking, and mitigating threats posed by this campaign.

## Campaign Overview

Our analysis indicates a coordinated effort by threat actors utilizing newly registered domains to conduct widespread SMS phishing activities. The campaign impersonates various legitimate entities, including telecommunication providers, banks, and delivery services across multiple ASEAN countries.

**Key Characteristics:**
* **Impersonation:** Mimicking well-known brands (e.g., AIS, CIMB, Maybank, J&T Express, Globe, Smart, Celcom, Singtel, Telkomsel).
* **Rapid Domain Registration:** New domains are registered frequently, often using generic top-level domains (gTLDs) like `.vip`, `.bar`, `.top`, `.xyz`, `.cc`, `.ink`, `.sbs`, `.click`, `.skin`, `.site`.
* **Broad Regional Targeting:** Observed targeting in Thailand, Malaysia, Philippines, Singapore, Indonesia, and potentially other ASEAN nations.
* **Threat Actor:** A company identified as "ewew rewreb wwegf" from Hong Kong is linked to the registration of numerous malicious domains.

**Primary Objectives of the Attackers:**
1.  **Credential Harvesting:** Stealing sensitive login information for various online accounts.
2.  **Malware Distribution:** Deploying malicious software onto victim devices.
3.  **Financial Fraud:** Tricking users into unauthorized financial transactions.

## Indicators of Compromise (IOCs)

The `iocs/` directory contains various types of indicators that can be used for threat detection and prevention.

### How to Use These IOCs

These IOCs can be integrated into your security tools, such as:
* Firewalls (for IP and domain blocking)
* Intrusion Detection/Prevention Systems (IDS/IPS)
* Security Information and Event Management (SIEM) systems
* DNS filters
* Email and SMS security gateways

**Always exercise caution and verify any information before taking action based on unsolicited messages.**

## Repository Contents

* `iocs/domains.txt`: A list of malicious domain names associated with this campaign.
* `iocs/ips.txt`: A list of malicious IP addresses hosting the phishing infrastructure.
* `iocs/registrars.txt`: Information about domain registrars used by the threat actors.
* `iocs/registrants.txt`: Information about registrant companies linked to the malicious domains.
* `LICENSE`: The license under which these IOCs are shared.
* `README.md`: This file.

## Contributing

We welcome contributions from the cybersecurity community to keep this repository up-to-date and comprehensive. If you identify new IOCs related to this campaign or have additional information, please consider submitting a Pull Request.

**Submission Guidelines:**
1.  Fork the repository.
2.  Add new IOCs to the appropriate files within the `iocs/` directory. Ensure they are defanged.
3.  Provide a brief description or context for the new IOCs in your pull request.
4.  Submit a pull request for review.

## Disclaimer

The information provided in this repository is for threat intelligence and cybersecurity purposes only. While we strive for accuracy, the dynamic nature of cyber threats means that some information may become outdated. We are not responsible for any actions taken based on the information provided herein. Use these IOCs responsibly and at your own risk.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**#Cybersecurity #Phishing #SMSScam #ThreatIntelligence #ASEAN #Thailand #CERT #CyberAwareness**
