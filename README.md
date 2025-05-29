# Evaluating and Improving Defenses with MITRE ATT&CK

This repository contains the ATT&CK Navigator matrices for the threats discussed in [Breakout BRKSEC-2227 "Evaluating and Improving Defenses with MITRE ATT&CK"](https://www.ciscolive.com/global/learn/session-catalog.html?search=BRKSEC-2227). This session is being delivered at Cisco Live US in San Diego June 9th, 2025.

It includes a top-level JSON that will pre-populate all of the component JSONs in 1 action. This will also include more source JSONs and the example YAML files for DeTTECT.

## Related Tools
I am also using some additional tools in the presentation that can be obtained via the following repos:
- [MITRE ATT&CK's Homepage](https://attack.mitre.org)
- [ATT&CK Parser](https://github.com/mjmcphee/attack_parser)
- [ATT&CK Rosetta](https://github.com/mjmcphee/attack-rosetta)
- [MITRE's Caldera BAS](https://github.com/mitre/caldera)
- [MITRE ATT&CK Navigator](https://github.com/mitre-attack/attack-navigator)
- [MITRE ATT&CK STIX Data](https://github.com/mitre-attack/attack-stix-data) - for when the TAXII server is down.
- [MITRE CTID's Threat Emulation Library](https://github.com/center-for-threat-informed-defense/adversary_emulation_library)
- [RaboBank's DeTTECT Tool](https://github.com/rabobank-cdc/DeTTECT)

## To use:
Clone the repo as needed for ready access to the examples worked on in BRKSEC-2227.

Specific instructions for the Related Tools are offered in each repository.

## Other Resources

### Referenced pages
- [MOVEit Transfer Breach by Cl0p (TA505) ransomware group](https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-158a)
- [VPNFilter, borrowing from BlackEnergy](https://blog.talosintelligence.com/2018/05/VPNFilter.html)
- [David Biacco's write-up on the Pyramid of Pain (our colleague from Splunk, now a Cisco Company)](https://www.eventtracker.com/blog/2015/february/the-pyramid-of-pain/)
- [MITRE's explanation of how ATT&CK was designed](https://www.mitre.org/publications/technical-papers/mitre-attack-design-and-philosophy)
- [Splunk 5 Year Perspective on TTPs](https://www.splunk.com/en_us/blog/security/macro-att-ck-2024-a-five-year-perspective.html)
- [Using Excel as your Navigator](https://cyberwardog.blogspot.com/2017/07/how-hot-is-your-hunt-team.html)
- [Cisco Secure Network Analytics ATT&CK Use Cases](https://www.cisco.com/c/dam/en/us/products/collateral/security/stealthwatch/stealthwatch-mitre-use-case.pdf)

### Blogs and How-To's
- [MITRE’s own ATT&CK materials are hard to beat](https://attack.mitre.org)
- [Getting Started Guide – useful for all 4 use cases](https://attack.mitre.org/resources/getting-started/)
- [Best blog on Medium](https://medium.com/mitre-attack/)
- [Pyramid of Pain](https://globalsecuresolutions.com/the-pyramid-of-pain/)
- [Orbital for ATT&CK](https://blogs.cisco.com/security/finding-the-malicious-needle-in-your-endpoint-haystacks)
- [Threat Grid use of ATT&CK TTPs in reports: https://blogs.cisco.com/security/black-hat-usa-2018-attck-in-the-noc](https://github.com/user-attachments/assets/26f02cae-0b69-4326-8bf6-dba38a6abefa)

### Complimentary MITRE/CTID Efforts
- [Center for Threat-Informed Defense (CTID): group in MITRE Engenuity, leads ATT&CK, D3FEND, and related](https://ctid.mitre-engenuity.org)
- [D3FEND: counter ATT&CKs TTPs by detailing how one can harden, detect, isolate, deceive, or evict the threat](https://d3fend.mitre.org)
- [Cyber Analytics Repository (CAR): validated analytical recipes for tools like Splunk, Elastic, etc. help detect TTPs in use](https://car.mitre.org/)
- [ATT&CK Flow – a tool to assist in linking TTPs into an adversary’s behavior (alchemy ;) )](https://center-for-threat-informed-defense.github.io/attack-flow/)
- [ATT&CK Powered Suit: Browser plugin to link and research TTPs](https://mitre-engenuity.org/cybersecurity/center-for-threat-informed-defense/attack-powered-suit/)
- [Common Attack Pattern Enumeration and Classification (CAPEC): Like ATT&CK, but focused on applications](https://capec.mitre.org/)
- [Malware Attribute Enumeration and Characterization (MAEC)](http://maecproject.github.io/)
- [MITRE ENGAGE](https://engage.mitre.org/)

### Additional Software and Tools
- [MITRE’s ATT&CK Workbench: allows orgs to maintain a local repo of their own ATT&CK data and keep it in synch with global feeds](https://ctid.mitre-engenuity.org/our-work/attack-workbench/)
- [Red Canary’s Atomic Red Team](https://atomicredteam.io)
- [Sigma Project for easy conversion of analytics between SIEMs](https://github.com/SigmaHQ/sigma)
- [MITRE's D3FEND Project, useful for those designing defensive tools](https://d3fend.mitre.org/)
- [CVE2CAPEC tool, mapping CVEs to CWEs to TTPs](https://galeax.github.io/CVE2CAPEC/)
- [Mappings Explorer](https://center-for-threat-informed-defense.github.io/mappings-explorer/)
- [CTID's CTI Blueprints](https://github.com/center-for-threat-informed-defense/cti-blueprints/wiki)
- [CTID's Sensor Mappings](https://center-for-threat-informed-defense.github.io/sensor-mappings-to-attack/levels/)
- [MISP (Malware Information Sharing Project)](https://www.misp-project.org/)
- [OpenCTI](https://filigran.io/solutions/open-cti/)

### CTI-related Resources
- [CIS Critical Security Controls, OS Benchmarks & Hardened Images a fantastic resource](https://www.cisecurity.org/cybersecurity-tools/)
- [OWASP Secure Software Development Lifecycle Project](https://www.owasp.org/index.php/OWASP_Secure_Software_Development_Lifecycle_Project)
- [UK National Cyber Security Centre](https://www.ncsc.gov.uk/section/advice-guidance/all-topics)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [US-CERT Resources](https://www.us-cert.gov/resources)
- [CREST Resource page](https://www.crest-approved.org/knowledge-sharing/index.html)
- [SANS Cyber Defense Reading Room](https://cyber-defense.sans.org/resources/whitepapers)
- [Awesome DeTTECT tutorial by Mohammed Alshaboti](https://medium.com/@alshaboti/getting-started-with-mitre-caldera-offensive-and-defensive-training-3ca9f693e0d7)

