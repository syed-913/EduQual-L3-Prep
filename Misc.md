Ans 1: The internal audit team should focus on the robustness of the internal controls and how effectively those controls are being implemented. Type II is important because its audit is done over a period of time and focus's on operational effectiveness.

Ans 2: The benefit here is the precise assurance of user entity like in our case government agency. In simple terms, a government agency will be ensure and relaxed about the security of their data, only if there isn't some zero day vulnerability which penetrates the cloud provider system.

Ans 3: A potential risk for that government agency is exposure of data by insider threat or lack of confidentiality. So the cloud provider doesn't seem trust worthy and the government agency must change their cloud provider as soon as possible or either they (user entity) must suggest the cloud provider to strengthen their change management process.

Ans 4: The SOC 1 Type II report does not provide or focus on risk assessment procedures effectively so relying solely on SOC 1 Type II is a potential risk for government agency's overall risk assessment. Other types of assurance may include the characteristics of SOC 2 reports like confidentiality, processing integrity, privacy, availability and overall security.  

Ans 5: Maybe the facilitation takes place by the monitoring of sub-service organization's internal controls. I really have no answer to this questions I don't know why.
___

Q1: SSAE 16 was replaced by SSAE 18, right? There were some minor differences, what are those differences?

Q2: Can you define to me, complimentary user entity controls? How does it work? What does it do?

Q3: What do you know about internal COSO internal Control framework?

Q4: If an healthcare organization fails SSAE 16 Type II or SSAE 18 audit, due to non-compliant cloud configurations. What are the four most likely root causes that results in the failure of audit?

Q5: How does the SSAE 16 type II compliance interact with HIPPA, GDPR, PCI DSS in a cloud hosted healthcare environment? 

Q6: So, if there is a 0 day vulnerability that affects the Azure Compliance Manager and GCP Compliance Monitoring System. What emergency response plan should a healthcare organization follow to maintain a SSAE 16 compliance?

Q7: What is the most important thing in every compliance or standard? Before doing anything, what's  the first step?

Q7.2: How do you design the controls which satisfies compliance requirements?

Q8: Why should the organizations follow these auditing standards? like SSAE 16 or 18. What are they demonstrating to their customers?

Q9: What role do immutable storage and blockchain base logging play in achieving SSAE 18 or 16 compliance for forensic audits?

Q10: Blockchain based hyper ledgers ensures what?

___

Ans 1: If a government agency is utilizing a public cloud on GCP, then the risk assessment done by user entity can expose that there's huge risk of unauthorized access to government's sensitive data in public cloud. To address this risk, ISO 27002 possess access and identity management, authentication and other controls which can be implemented to reduce the risk to an acceptable level, however if the risk is not reduced to an acceptable level, then better option is to move towards private cloud. Although a government agency would never store their data on "public cloud" as it possess many threats alongside unauthorization.

Ans 2: If I am an auditor of a government agency, then firstly I would be looking for the Physical Controls, People Controls and maybe Organizational Controls and their justifications in a cloud provider's ISO 27001 SoA, mostly focused on Physical because physical controls are not the responsibility of my government agency, whereas my government agency should be responsible of risks possessed by the internal systems (intangible assets like software etc), peoples, policies of my agency. I mentioned Organization and People Controls so that I may understand their policies and procedures as well as understood how well trained their employees are, it would give me more understanding of the service provider with which I'm sharing my organization's sensitive data.

Ans 3: The information security policy should be evolved in the context of physical threat, because the Shared Responsibility Model states that the "security of the cloud" is under cloud provider's responsibility which basically means the physical security, whereas the government agency is responsible for other aspects of security controls like people, organizational, technological. Physical security control is impacted the most by this evolution because of Shared Responsibility Model.

Ans 4: The continual improvement aspect of ISO 27001 is extremely important and serious because it require continuous and ongoing commitment from the organization in order to defend against latest threats, continuous risk management can deal with latest threats, whereas an ongoing internal audits and compliance reviews will aid organization in achieving their objective.

Ans 5: The reason behind the involvement of top management in order protect sensitive government data is very straight forward, the top management is responsible and accountable for any kind of inconvenience in the ISMS. Specially in cloud-based ISMS, monitoring from top management is highly important because of Shared Responsibility Model. For example, if an audit is conducted for the certification of ISO 27001, and the auditors find out that the included (in SoA) technological controls are not being implemented properly in the ISMS of government agency then the top management is accountable here, so to fulfil their responsibility upon ISMS their (top management's) involvement is necessary.

Linked QnA:

Ans 1: In cloud-based system, ISO 27001 compliment's SSAE 16 Type II by already fulfilling the requirements of SSAE 16 Type II audit, likewise Type II also indirectly compliment's ISO 27001 by ensuring that the cloud provider is handling sensitive financial data of their clients in process and at rest, its direct support is towards SOX. The government agency can review the cloud provider's SoA to understand the posture of provider's ISMS as well as the agency can ensure the operating effectiveness and the security of data related to finance. Both standards provide robust credibility to the clients of cloud provider's.

Ans 2: The gaps encountered by government agency will be of the assurance related to the sub-service organization monitoring by cloud provider's management, although if the cloud provider's ISMS is well maintained and continually improved then there is no need for the assurance of risk management. SOC 1 is limited to only assure data related to finance whereas SOC 2 can handle both assurances like risk analysis and sub-service organization monitoring. ISO's certification can ensure the efficiency of risk management but the monitoring of sub-service will be a loop hole which prevent government agency to partner with cloud provider.

Ans 3: I can't comprehend the question, the relation between change management and SOC 1 Type II or simply financial reporting, can you ask this question in a different manner?
___
Ans 1: Yes an organization can rely on one, however if we consider a service organization than SSAE 18 is a requirement not a complement likewise for service organization ISO 27001 is also a requirement because it sets the baseline of security. An ISO 27001 complements SSAE 18 by requiring the security in form of confidentiality, integrity and availability which simply fulfil's the requirements of SSAE 18 Trust Services Criteria.

Ans 2: In cloud environments, data silos can cause multiple problems and reduce operational effectiveness because its isolated and does not provide a full picture of the organization's security, this can risk in decision making for the top management because "you can't protect what you can't measure". A SIEM like Wazuh eliminates this isolation and provide a bigger picture of organization with high customization and tailoring of its logs and it also provide centralization as well as it can be an assist for incident response team for responding effectively to incidents.

Ans 3: initially I'll isolate the system then execute the incident response plan to eradicate the beacon and recover the stolen data.

Ans 4: Principle of least privilege relates to ISO 27001 in the context of role based access control, as RBAC require's least privilege for the individual role, it means the privileges an individual possess are based on their role. In cloud native tools like GCP Security Command Center, GCP IAM is utilized to implement role based access control. For example a junior system admin or an intern require root access on system for kernel tuning purposes would be restricted by GCP IAM because only a senior have that privilege.

Ans 5: Vulnerability is weakness in computer system or software which is discovered by tweaking with the code logic (most probably). Whereas, misconfiguration is done by the personnel working with the services and other components of the computer system, misconfiguration is simply a mistake done by a human in the code while configuring or tuning a service or software for their personal needs. Don't really know why to distinguish!

___
Ans 1: By monitoring their activity, we can ensure that the recommendations by GCP SHA are in practice.

Ans 2: If we talk about deletion of a database, then the deletion itself is a critically sensitive action which should be discussed with stakeholders. However, The principle of least privilege restrict's Jane from deletion using GCP IAM, the deletion should be disabled even for the admin. I don't really know which type of access control should be done here, maybe MAC.

Ans 3: The Shared Responsibility Model itself propose the concept distinction between the responsibility of security for data between service provider and user entity. According to Shared Responsibility Model, the cloud provider is responsible for security of the cloud like the physical security while government agency is responsible for the security in the cloud like the data stored in cloud storage and databases.

Ans 4: Well, the ISO 27001 is a security framework, and security enable's business passively. The business objective can be fulfilled by protecting the system from threats and reducing their impact. For instance, if an organization do not posses ISO 27001, and it got attacked or breached, is there any chance of toleration and business continuity, obviously not. So, ISO 27001 enable's business continuity and assist business objective passively.

Ans 5: I would consider it as an incident because its a False positive and it require's monitoring, if it ain't successful than its not a threat, at least for now. I would inform security team to monitor the IP actively so that they can confirm and block and monitor their login request with more attention
___
- How would you explain the difference between **confidentiality, integrity, and availability** (the CIA triad) to a non-technical manager? Can you provide a real-world example for each in the context of government data?
	- Imagine your national ID card, it must be confidential because if someone like thief achieved your id card then they can use in bad ways and you can get arrested. And it shouldn't be modified, if it is than you'll be imprisoned for violating the laws by tampering your identity. At last it should be available to you all the time, like if you were stopped by police for speeding they require your id card and if your ID card is not available to you than you'll face some legal consequences.
- What is the main challenge of implementing a SIEM like Wazuh in a multi-cloud environment, and what is one technical solution to overcome this challenge?
	- The SIEM like Wazuh require operational workforce to maintain, operate, patch and tune. in comparison to cloud-native tools, Wazuh acquire less performance not because its not capable but the security experts handling cloud-native tools in cloud provider's organization are obviously way better than the user entity's security personnel. If you want to use Wazuh for centralized dashboard, log correlation, FIM and HIDS, than it is pretty good enough but for threat detection and modeling purposes, one should look after cloud-native tools because they're specialized to developed to fulfil threat detection backed by experts.
- Scenario: Your team has been tasked with securely migrating a legacy on-premises database to a cloud environment. The database contains highly sensitive personal information. What is the single most important security action you would recommend for this migration?
	- access control policy alongside encryption, because only the authorized personnel are permissible to read/write sensitive information and if they don't know the technical workings like a top-management personnel wouldn't know about these technical work going on in my team, he just needs to maintain CIA of their information based on information classification, so to maintain CIA I must be using access control policy for limiting access to those information like restricting interns in taking part during this migration. And encryption to defend confidentiality of the data as well as to protect integrity I'll be using hash signatures. And for redundancy I got on-prem servers until the data is fully migrated.
- How does a robust governance framework like ISO 27001 help an organization manage the risks associated with third-party vendors and contractors?
	- ISO 27001 help's through its risk assessment and treatment process/policies. It require's identification of each asset in organization and the vulnerabilities associated with it, and also the threats to that vulnerabilities. Like if FireEye didn't look into the code of solar-winds then we never knew the spying has been on this much scale, what FireEye did was an absolute example of risk assessment of their third party vendor's product.
- Why is it crucial for a security professional to understand the business objectives of the organization, and how can this understanding influence their security decisions?
	- The reason for this is that every aspect of organization needs to enable business, not single one have to be an obstacle in business objectives of organization. Security professionals need to put forward their requirements to protect data based on classification, before asking for requirement, they must understand the business objective so that they can tailor their requirements and take decisions accordingly.

___
Ans 1: The best example for this is the Google's physical security of the cloud. It consist of 6 layers of protection from advanced or smart fencing to thermal cameras, to access controls inside data center, to security operation center monitoring data center 24/7, to the encryption of data at rest. This is what Defence in depth look like in action.

Ans 2: The role of data classification is to maintain the order of information based on its importance, for example, a highly sensitive information is graded as "Top Secret" and normal info like employee name is graded as "Common". It can impact the inclusion and exclusion of controls because controls are meant to protect information at each stage of classification so a control should align with the protection of information at each stage.

Ans 3: Here the principle of need to know/least privilege is applied to grant access based on the developer's needs or its role.

Ans 4: IN the context of incident reponse, containment is isolating the malware to only those systems which are already affected, basically stopping the spread of malware. While eradication is the process of removing that malware completely, containment is done in initial stages of IR while eradication is done in the last stages of IR.

Ans 5: By performing security testing practices on that application like penetrating testing or red teaming.

Short Q/A:
1. To filter web traffic
2. To manage people, process and technology under its responsibility
3. Chain of custody is to securely transmit evidence from the incident to the courtroom to comply with justice.
4. DES
5. A zero day exploit is an exploit which has no patch.
6. Continuously Trying common passwords through an automation tool.
7. To assess the security of the asset by trying to penetrate it.
8. Don't know
9. Authentication is something you have and authorization is something you are.
10. Don't know