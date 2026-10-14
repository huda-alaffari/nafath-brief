Version: NAFATH-V4
Track: <one of: Software | AI | Mobile | Networking | Cybersecurity | Data>

## Overview
National service-providing institutions employ a range of technologies to deliver their services securely. These technologies must be protected against cyber-intrusions and unauthorized modifications.

Each of the six information technology domains fulfills a fundamental role. In the software domain, efforts focus on building reliable applications and validating updates. Artificial intelligence ensures the reliability of models and the data used to train them. Mobile technology protects applications and devices from unauthorized access. Networking contributes to securing internet connections and monitoring for suspicious data activity. Cybersecurity focuses on system monitoring, risk identification, and security incident management. Meanwhile, data management ensures the accuracy, confidentiality, and availability of information.

These domains are interconnected; a flaw in one can impact the others. For instance, a software breach could expose sensitive data or trigger network-level security issues. Consequently, project managers must ensure the implementation of regular security checks, engagement with trusted vendors, continuous monitoring, and the development of effective contingency plans to guarantee the continuity of secure and reliable services.

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

## Cybersecurity

## Data

## Misconception in My Track

## Open Question
