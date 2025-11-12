# Objective
​**Monitor security and compliance** using _Azure Security Center_, _GCP Security Command Center,_ and open-source tools like _Wazuh_.
___
#### What is SIEM and Wazuh?
- **Security Information and Event Management:**
	- SIEM is any kind of software which collect's and utilize logs from various assets of organization, such as servers, agents, containers, network devices etc. A SIEM analyze these collected logs and detect (or some times prevent) the security threats such as intrusion detection, unauthorized access, unusual network traffic etc.
- **Wazuh:**
	- Wazuh is an open source SIEM software which is rich in features such as EDR, FIM Regulatory Compliance, Reporting etc. It's mostly known for Host Intrusion Detection System (HIDS). Wazuh can detect as well as prevent intrusions and its highly flexible and scalable.

#### What are the advantages and detriments of Wazuh?
- **Benefits:**
	- It can eliminate the risk of data exposure to any third parties (like cloud providers). It can be downloaded and run locally in internal network and avoid any kind of log data exposure.
	- Wazuh is not a proprietary software so it avoids vendor lock-in, like if a user entity is using different cloud services from multiple providers and its easy to centralize all the log data to one Wazuh server, where it can be monitored.
	- Wazuh is highly flexible and can be customized personally, like if the user entity require advanced rules for detecting unauthorized access, then the rules can be tweaked accordingly.
	- For cloud, Wazuh is not free but it can reduce other cost effective areas and make it tolerable in sense of business.
- **Detriments:**
	- It can be extremely complex to setup a SIEM manually as it requires advanced experience to handle and work with thousands of agents simultaneously.
	- It require's require's extreme operational work to develop, maintain, scale, patch and tune.
	- As compared to cloud security monitoring and management systems, it is quite low in performance like cloud security systems are managed hundreds of well trained professional looking after their clients protection while Wazuh have to be setup and maintain locally by user entity's own staff which is quite non beneficial.
#### How does GCP SCC compliment Wazuh?
- GCP Security Command Center is better than Wazuh in sense of performance because SCC is managed by Google's own global threat intelligence, which makes it more faster and unique in sense of finding vulnerabilities or misconfigurations in systems. Also it continuously assess the security posture against the well known security benchmarks like CIS or NIST.
- While Wazuh overtake SCC in context of HIDS and FIM as well as Wazuh can be customized as per the requirements and it can also interact with multiple cloud security software's for centralized monitoring.
- Wazuh and GCP Security Command Center both compliment each other. GCP SCC detect latest threats while Wazuh centralize logs for better detection and prevention. Like first detecting newly emerged threats using GCP SCC then setting custom rules based on the threat in Wazuh for better detection and prevention.
#### What is Azure Security Center?
- Microsoft Defender for Cloud formerly known as Azure Security Center is a suite of tools to detect and respond to threats and maintain a healthy security posture all over the organization's digital assets. There three components of Azure Security Center:
- **Development Security Operations:** Defender for Cloud enables security from the start of Development life-cycle and follow the *security by design* idea. It integrates security into the across multi-pipeline environment.
- **Cloud Security Posture Management:** This is all about prevention. It continuously scans your Azure environment for misconfigurations and security vulnerabilities. For a government agency, this is invaluable for ensuring compliance with standards like ISO 27001.
- **Cloud Workload Protection Platform:** This is the "detect and respond" component. Defender for Cloud provides advanced, intelligent threat protection for various workloads across a government agency's environment, including servers, containers, databases, storage etc,
Simply, Azure Security Center is a central hub for the whole security of Azure's Cloud.

#### What's the difference between GCP Security Command Center and Azure Security Center?
- The core difference between **GCP Security Command Center (SCC)** and **Microsoft Defender for Cloud (MDC)** is primarily **scope and integration method**. **GCP SCC** acts as a **centralized risk and security findings aggregator**, consolidating data from _other_ Google Cloud security services (like Event Threat Detection or Web Security Scanner) into one dashboard, making it primarily a **single pane of glass for posture management and risk assessment** within GCP. In contrast, **Microsoft Defender for Cloud (MDC)** is a more **comprehensive, integrated suite** that not only offers **Cloud Security Posture Management (CSPM)** but also includes **Cloud Workload Protection (CWP)** features like runtime protection, server protection, and container scanning _directly_ within its service tiers, making it a more expansive security _tool_ that manages and protects workloads across Azure and hybrid environments.
#### GCP Security Command Center (SCC) Components

GCP Security Command Center (SCC) is a unified security and risk management platform for Google Cloud. It's a suite of services designed to help you prevent, detect, and respond to threats. While it is one service, it's composed of several powerful modules.

1. **Security Health Analytics (SHA):**
    
    - **What it is:** This is the **Cloud Security Posture Management (CSPM)** engine of SCC.
        
    - **How it's utilized:** SHA continuously scans your GCP environment for misconfigurations and security vulnerabilities. It checks your configurations against security benchmarks like the CIS (Center for Internet Security) Foundations Benchmark. For example, it can detect if a storage bucket is publicly exposed, an SSH port is open to the internet, or a service account has overly broad permissions. The findings are categorized by severity.
        
2. **Event Threat Detection (ETD):**
    
    - **What it is:** This is the real-time **threat detection** service.
        
    - **How it's utilized:** ETD analyzes log data from sources like Cloud Logging for signs of malicious activity. It uses machine learning to identify specific threats such as crypto-mining activity, exfiltration of sensitive data, or a compromised service account being used for unauthorized activity.
        
3. **Web Security Scanner:**
    
    - **What it is:** A vulnerability scanner specifically for your web applications running on Google Cloud.
        
    - **How it's utilized:** You can schedule or run on-demand scans to check for common web vulnerabilities like Cross-Site Scripting (XSS), outdated libraries, or mixed content. This helps you find flaws in your applications before an attacker can exploit them.
        
4. **Container Threat Detection:**
    
    - **What it is:** A service for detecting threats within your container environments, particularly during runtime.
        
    - **How it's utilized:** It monitors container activity for malicious behaviors, such as attempts to run malicious scripts, binary authorization bypasses, or unexpected process execution within the container.
        

#### Microsoft Defender for Cloud Suite/Tools

Microsoft Defender for Cloud is more of a unified management suite than a single tool. It provides security posture management and threat protection across Azure, on-premises, and other cloud providers (multi-cloud). It's broken down into two main pillars:

1. **Cloud Security Posture Management (CSPM):**
    
    - **What it is:** This is the core function of Defender for Cloud. It helps you prevent security misconfigurations.
        
    - **How it's utilized:** The CSPM dashboard gives you a **Secure Score**, which is a single metric that represents your overall security posture. It provides actionable recommendations to improve this score, such as "Enable Multi-Factor Authentication" or "Encrypt all virtual machines." This directly helps an organization follow best practices and align with security frameworks like ISO 27001.
        
2. **Cloud Workload Protection (CWP):**
    
    - **What it is:** This is the **threat detection and protection** side of the platform. It provides specialized security for different types of workloads.
        
    - **How it's utilized:** You can enable specific "Defender plans" for different workloads. For example:
        
        - **Defender for Servers:** Provides threat detection and vulnerability management for your Azure VMs and on-premises servers.
            
        - **Defender for Containers:** Protects your Kubernetes clusters by detecting vulnerabilities and runtime threats.
            
        - **Defender for SQL:** Provides security for your SQL databases by detecting potential threats and vulnerabilities.
            
        - **Defender for Storage:** Detects unusual and potentially harmful activity in your storage accounts.
            

##### The Key Distinction

The most critical point to remember, which you can use to show a deeper understanding, is how these tools relate to your presentation.

- **Cloud-Native Tools are the "How":** They are the specific technical mechanisms that implement the controls required by your **ISO 27001 ISMS**. For instance, the ISO 27001 framework might require a control for "vulnerability management," and your organization would use **Web Security Scanner** in GCP or **Defender for Servers** in Azure to fulfill that control.
    
- **Centralized Visibility:** You can explain that while these tools provide security within their specific cloud (which is a limitation), they provide the data necessary for a centralized **SIEM** (like Wazuh) to provide a unified view across _all_ of your environments. This proves you understand not just what the tools are, but how they fit into a complete, end-to-end security program.

___
