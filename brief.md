Version: NAFATH-V4
Track: <one of: Software | AI | Mobile | Networking | Cybersecurity | Data>

## Overview
National service-providing institutions employ various technologies to deliver services securely. These technologies must be protected against cyber-intrusions and unauthorized modifications.
Each of the six information technology domains plays a fundamental role. Software focuses on reliable applications and secure updates. Artificial intelligence supports reliable models and training data. Mobile technology protects applications and devices. Networking secures connections and monitors suspicious activities. Cybersecurity involves system monitoring, risk identification, and incident management, while data management ensures information accuracy, confidentiality, and availability.
These domains are interconnected, and a weakness in one can affect the others. Therefore, institutions need regular security checks, trusted vendors, continuous monitoring, and effective contingency plans to maintain secure and reliable services. Understanding potential threats is equally important, leading to the question: What are the different types of hackers, and how are they classified based on their objectives and methods of operation?

## Software
According to the Twelve-Factor App methodology, configuration and secrets, such as passwords and API keys, should be stored in environment variables instead of hardcoding them into the code. This improves security by preventing sensitive information from being exposed. It also allows the same application to run in different environments with different settings, makes updates easier without changing the code, and helps manage access to sensitive information independently.
Resource: <title: Store config in the environment> - <full [URL](https://12factor.net/config)>

## AI
The main types of adversarial attacks on machine learning are:
- Evasion attacks: Change input data to make the AI produce incorrect results.
- Poisoning attacks: Manipulate training data to teach the model wrong patterns.
- Model extraction attacks: Send many queries to copy or reproduce a model’s behavior.
- Privacy attacks: Attempt to reveal sensitive information from the model’s training data.
The main difference is that evasion targets inputs, poisoning targets training data, model extraction targets the model, and privacy attacks target confidential information.
Resource: <title: What Is an Adversarial AI Attack?> - <full [URL](https://www.paloaltonetworks.com/cyberpedia/what-are-adversarial-attacks-on-AI-Machine-Learning)>
<title: Understanding adversarial attacks against Machine Learning and AI> - <full [URL](https://www.ncsc.gov.uk/paper/understanding-adversarial-attacks-against-machine-learning-and-ai#context)>

## Mobile
The OWASP MASVS is a security framework dedicated to mobile applications, providing guidance on the testing process and vulnerability detection. The framework covers various aspects, including data storage, cryptography, authentication, network communication, and operational environment protection. 

Implementation follows these steps: 
- first, identifying the application's specific security requirements.
- second, examining the application against the relevant MASVS criteria.
- third, utilizing scanning tools and manual reviews to detect vulnerabilities.
- fourth, documenting findings and remediating identified vulnerabilities.
For instance, the tester verifies that sensitive user data is stored securely and that network communications occur over encrypted channels.
Resource: <title:OWASP MASVS> - <full[URL](https://www.appknox.com/cyber-security-jargons/masvs)>
          <title:OWASP MASVS> - <full[URL](https://mas.owasp.org/MASVS/)>
           https://github.com/OWASP/masvs/blob/master/OWASP_MASVS.yaml
## Networking
BGP Hijacking: An attack in which fraudulent BGP routes are advertised to seize IP addresses or redirect internet traffic along illegitimate paths for malicious purposes.
The Role of RPKI: It provides a verification mechanism based on digital certificates—known as Route Origin Authorizations (ROAs)—to prove that an Autonomous System (ASN) is authorized to announce specific IP prefixes. This helps prevent route hijacking and allows for the validation of BGP updates.
What does RPKI not protect against?
Manipulation of the entire AS-PATH.
Route leaks, even when the origin is valid.
Errors in BGP policies, preferences, or traffic engineering.
Comprehensive validation of all path elements; it is limited to verifying only the Origin AS.
Resource: <title:BGP Hijacking: Understanding Threats to Internet Routing> - <full[URL](https://www.kentik.com/kentipedia/bgp-hijacking/)>
<title:RPKI> - <full[URL](https://nhimg.org/glossary/rpki/)>
## Cybersecurity
Log4Shell (CVE-2021-44228): A critical Remote Code Execution (RCE) vulnerability in the Apache Log4j 2 library, which allowed attackers to execute arbitrary code remotely by exploiting the JNDI feature.
Why it is critical: 
It received the maximum CVSS score of 10.0 because it:
- Is exploitable remotely over a network.
- Requires no authentication or user interaction.
- Allows for the execution of arbitrary code on targeted systems.
- Affected a vast number of applications and services that utilize Log4j.
How it was addressed:
Apache disabled the dangerous JNDI feature by default in Log4j 2.15.0 and subsequently removed it entirely in Log4j 2.16.0 and later patched versions. It is recommended to update affected systems and implement the necessary mitigation measures.
Resource: <title:CVE-2021-44228 Detail> - <full[URL](https://nvd.nist.gov/vuln/detail/cve-2021-44228)>
## Data
A Software Bill of Materials (SBOM) is a structured, machine-readable list or "ingredients list" that enumerates all software components, open-source libraries, modules, and external dependencies utilized in the development of a software application. 
Minimum Information Requirements: As per the global recommendations from the Cybersecurity and Infrastructure Security Agency (CISA), the NSA, the FBI, and international allies, a typical SBOM is structured into metadata and component data sections. Baseline / Core Areas (Set by NTIA and revised in CISA/multinational frameworks)
• Supplier Name: The organization that developed, manufactured, or services the part.
• Component Title: The formal designation of the software package or module.
• Version: The exact release identifier of the component (essential for aligning with vulnerability records such as CVEs).
• Distinct Identifiers: Standardized codes like Package URLs (PURL), Common Platform Enumerations (CPE), or SWID tags that enable scanners to cross-reference databases of vulnerabilities automatically.
• Dependency Connections: A diagram illustrating how components interrelate, differentiating between direct dependencies and transitive (nested) ones.
• Creator of SBOM Data: The entity or application that produced the SBOM document.
• Timestamp: The date and time of the creation of the SBOM document.
Resource: <title:Software Bill of Materials (SBOM)> - <full[URL](https://www.cisa.gov/topics/information-communications-technology-supply-chain-security/sbom)>
Resource: <title:The Minimum Elements For a Software Bill of Materials (SBOM)> - <full[URL](https://www.ntia.gov/sites/default/files/publications/sbom_minimum_elements_report_0.pdf)>

## Misconception in My Track
In the past, it was commonly believed that there was only one type of hacker: an individual who sabotages systems or steals data with the intent to cause harm and threaten those whose information has been compromised. In reality, however, there are various categories of hackers—including those who are harmless, known as "ethical hackers." 

This raises the question: what are the different types of hackers, and how are they classified based on their objectives and methods of operation?

## Open Question
what are the different types of hackers, and how are they classified based on their objectives and methods of operation?
