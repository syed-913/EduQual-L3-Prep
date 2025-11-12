# Safeguarding Government Data: A Framework for Protecting Cloud Systems with SSAE 16 Type II, ISO 27001 & Major Cloud Providers.
#### Slide 1: Securing Sensitive Data in the Cloud

- The objective is to secure government data in the cloud.
	- Now, What is the objective? The objective of this presentation is to secure sensitive government data in the cloud environment through a layered approach.
    
- Protection of this data is a national security imperative.
	- So, why the protection of this government data takes place? See, if a breach has happened in a government sector, it can cause severe disruptions to critical infrastructure such as Power-Grids, Water supplies etc. As well as it can compromise the national security and the nation-wide trust.
    
- We'll explore a layered approach: governance, assurance, and technical controls.
	- I'll guide you through a layered security approach to defend cloud systems against advanced cyber threats by combining assurance, governance, and technical tools.
    
- This strategy protects data and builds trust.
	- So, this strategy does not only protect's data, but it also build's trust, which is crucial for maintaining a good relationship between user entity and its cloud providers. As the first principle of Zero Trust Model state's "Never trust, always verify". So this defence in depth strategy, help's user entities in verifying their cloud provider's security posture.
    
- This presentation will guide you through this holistic security model.
#### Slide 2: What is SSAE 16 Type II?

- An auditing standard for service organizations by AICPA.
	- Our First layer is... Assurance.
		
		Now, what is SSAE 16? SSAE 16 or Statement on Standard for Attestation Engagements No. 16, is an auditing standard proposed by American Institute of Certified Public Accountants. It was a succession of SAS 70, which is also an auditing standard but it had some limitations which SSAE 16 fulfilled.
    
- It is an attestation standard and applies only to SOC 1 reports.
	- It is an attestation standard and applies only to SOC 1 reports. Now, What is SOC or Security Organization Controls report? A SOC report is an outcome of an attestation engagement performed during an audit. There are mainly 3 kinds of SOC reporting framework, SOC-1, SOC-2 and SOC-3. The reason why SSAE 16 is limited to SOC 1 is its scope. It was not limited, although in modern times its termed as a "limitation", but in reality SSAE 16 was intentionally or specifically, developed to fulfil the scope of SOC 1 reporting framework, to eliminate any misinterpretation and misconception proposed by SAS 70.
    
- The primary focus is on controls over financial reporting (ICFR).
	- The primary focus of SSAE 16 is to ensure that whether the internal controls relevant to financial reporting are being implemented or not. The principle of Internal Controls over Financial Reporting is a set of policies and procedures through which a government entity can get assurance, specifically, for the protection of their financial information from their cloud providers. So, SSAE 16 only attest these internal controls relevant to financial reporting, whereas it was first introduced by COSO framework.
    
- A Type II report attests to the operational effectiveness of controls.
	- As I've already stated that there are 3 kinds of SOC reporting frameworks, each one is divided into 2 Types, named as Type I and Type II. So, Type I address's the quality of the presentation of service organization and the suitability of the design of internal controls on a specific point in time, while the Type II does the same, by addressing quality of presentation and design of controls, but it also includes the attestation of operational effectiveness of the internal controls over specified period of time. For example, Type I is like a snapshot of the controls being implemented currently, while Type II is a video recording of those controls being implemented over a specified period of time. This time period consist of like 6-12 months, so its not a one-time operation but a continuous cycle. The reason, why our scope specifically discuss Type II is that it is more efficient and relevant than Type !. A government entity must require a Type II report for responsible assurance from their cloud providers.
    
- These reports are critical for financial auditors.
	- Now, specifically this SSAE 16 Type II report which attest controls relevant to financial reporting is highly critical for financial auditors.
#### Slide 3: From SSAE 16 to SSAE 18

- SSAE 18 succeeded SSAE 16 with a broader scope.
	- As I've already mentioned that SSAE 16 was limited in the context of scope, which was ICFR. To overcome that limitation, AICPA decided to introduce an updated version of SSAE 16 with a broader scope and termed it as SSAE 18. The fact that it was updated is that the requirements. User entities, who are not much concerned about the assurance of ICFR, lacks trust in their service organization.
    
- It places greater emphasis on monitoring sub-service organizations.
	- Now what were the major changes introduced in SSAE 18? It emphasize service organization to monitor their sub-service organization and conduct risk assessment to protect their cloud infrastructure against cyber threats, or specifically supply chain attacks. To illustrate this, let's think back to an incident that shook the entire cybersecurity world: the SolarWinds attack.
		
		While SolarWinds wasn't a cloud-native incident, its core lesson is universally applicable. A trusted vendor—a sub-service organization—was compromised, and that single point of failure became a launchpad for attacks against thousands of their customers, including multiple government entities.
    
- The standard enhances the value of the report for due diligence.
	- So, SSAE 18 has no limitations, because of its broader scope. Its uniquely flexible, and it can align with SOC 2 report. A SOC 2 report focus's on controls relevant to _security_, _availability_, _processing integrity_, _confidentiality_, and _privacy_, in simple terms, Trust Services Criteria. So, this standard, SSAE 18, enhance value of the report for due diligence by addressing the controls relevant to security rather than being limited to asserting controls over financial reporting.
    
- It aligns more closely with other international standards.
	- This is one of the advantageous benefit of SSAE 18, that it aligns with international auditing standards like ISAE 3402 and Sarbanes Oxley, a compliance standard, directly. It also aligns with international compliance standards like ISO 27001, GDPR, HIPPA and others, indirectly. By the word "align", I mean that when a service organization prepare's for an external audit of SSAE 18, they implement controls. So, these implemented controls are already required by some compliance standards, which could potentially benefit a service organization, if they're planning to achieve any compliance certificate after SSAE 18.
    
- This makes SSAE 18 a more robust and relevant standard for government agencies.
	- Just like I've said earlier, that a government agency must consider a SOC 2 report over SOC 1, because only a SOC 2 report can provide assurance for the overall security of a cloud provider and SSAE 18 can make it possible. So, a government entity cannot rely on an ICFR assurance from their cloud providers because they prioritize assurance for the overall protection of their data rather being ensure only for the security of their financial information.

#### Slide 4: The Benefit of SSAE 16 Type II

- A SOC 1 Type II report provides a critical layer of assurance.
	- However, SOC 1 report is limited to the attestation of internal controls over financial reporting. But, it plays a critical role in its own boundary of assurance for the protection of financial information from frauds and errors, and it also maintains accuracy, either we choose SSAE 16 or 18 as an audit standard. So, those user entities who are only concerned about the security of their financial data can rely on SOC 1 Type II, but in case of a government entity, this is a pretty bad idea.
    
- It reduces the audit burden on the government agency's own auditors.
	- Now, this is one of the complimentary advantage from an SSAE 16 Type II audit, that it reduce's burden of due diligence from the user entity's own auditors and provide a clear statement for assertion. Also the service organization conducting SOC 1 Type II audit, put itself ahead of the curve and become more reliable among its competitors.
    
- The report enhances trust and credibility in the cloud provider.
	- So, from the perspective of cloud provider, the core focus or the main reason to achieve a successful audit is to gain trust of their user entities by ensuring that their controls align with the requirements of the user entity. 
		
		In simple terms, the objective behind the enhancement of trust and credibility is to enable business. The more user entities trust their cloud provider, the more their business grow.
    
- This assurance confirms that financial data is handled with due care.
	- Like I've mentioned earlier, that this assurance of SOC 1 Type II verifies that the cloud provider guarantee's their responsibility in the protection of its user entity's financial data. Because they handled this data with due-care  by maintaining security of the cloud.
    
- However, it does not provide comprehensive security assurance for the entire environment.
	- The sole purpose of these standards like SSAE 16 or 18 is assurance and they do not provide a clear view for the whole security posture of a cloud provider. In simple terms, they do not ensure what controls are being implemented, except from its scope, although the reports of these standards confirm's that the controls are in place and being implemented but it does not answer the questions of "why?", "how?", "when?", "where?" the controls are being implemented. 
		
		This is where a full fledged security management system is required for enhanced and modern security practices. So, this leads us to our next layer of defense...

#### Slide 5: The ISO 27001 Framework

- ISO 27001 is the international standard for an Information Security Management System (ISMS).
	- Governance.
		
		ISO 27001 is an international compliance standard for establishing, implementing, maintaining and continually improving Information Security Management System or ISMS. It provides a baseline of controls, divided into four fundamental areas for establishment, named as, Organizational Controls, Technical Controls, Physical Controls and People-Related Controls.
    
- It provides a systematic framework for information security.
	- See, ISO 27001 is not just a framework, its a system. And the reason why it is the most widely known security standard is that it is flexible. It can be tailored based on requirements. The ISO itself does not encourage to implement all the controls listed in their framework, but it says implement those which are relevant to protection of your systems. It is because if any organization started implementing all the controls listed in ISO 27001 standard, then the business will be impacted negatively.
    
- The framework is based on a Plan-Do-Check-Act (PDCA) cycle.
	- ISO 27001 is not a checklist of controls like PCI DSS, rather it propose a cycle of Plan-Do-Check-Act or PDCA, which require's improvement of information security controls, upon each completion. This cycle maintains the quality of controls by updating the security posture to defend against modern cyber threats.
    
- ISO 27002 provides the companion guidance on control implementation.
	- Now, ISO 27001 defines the requirements, like it explains the "what" should be done or "what" controls to implement in order to establish and improve information security, but it does not tell "how?". ISO 27002 is the supporting document of ISO 27001 which explains the process behind the implementation of controls so that an organization can learn and and take guidance from it, to fulfill the requirements of ISO 27001. For example, ISO 27001 state's that "implement an access control policy to prevent unauthorized access to information systems", so 27001 completed its job by mentioning what should be done. Now, ISO 27002 guide's on how access control should be implemented by mentioning best practices like MFA, PAM, RBAC etc. 
    
- This is a risk-based, rather than a checklist, approach to security.
	- As I've mentioned earlier its not a checklist like PCI DSS or NIST. So, this is another aspect of ISO 27001 which makes it unique in the most logical way possible. The risk based approach.
#### Slide 6: A Risk-Driven Approach

- ISO 27001 requires a comprehensive risk management process.
	- Now, do you remember, that in the previously slide, I stated that ISO 27001 is flexible and it can be tailored? This risk management process is what makes it adaptable and unique in wide range of industries. It forces a company to think critically about its specific risks and implement the most effective controls to manage them. This process is divided into two stages, named as, Risk Assessment and Risk Treatment.
    
- This process includes risk identification, analysis, and evaluation.
	- The process of risk assessment mostly includes identification, this is because it defines the scope and I read this line somewhere in articles that "you cannot protect what you can't measure"; So this includes identification of assets, vulnerabilities related to those assets and threats exploiting those vulnerabilities and then the evaluation takes place. The evaluation phase involves a decision of whether the risk require's treatment or not.
    
- It mandates a structured approach to treating or mitigating identified risks.
	- So, when the risk assessment is done and it is evaluated that the risk require's treatment, then we can look up to the four most probable treatment procedures; Mitigation, Avoidance, Transference and Acceptance. There is no fundamentally practical way to treat risk except for the four ISO 27001 mention's.
    
- This approach aligns security decisions with the organization's business objectives.
	- Now, where does the risk management process stands in the context of enabling business or assisting in achieving business objectives? See, information security procedures or policies must enable business, either passively or actively, other it has no point to exist in an organization. So, risk management process can enhance decision making focused on achieving business objectives by tailoring only the required controls to implement. For example, if an organization follows a checklist and implement all the controls on that checklist, they can leave a blind spot in their information security management system, and it can also be extremely expensive, on the other hand, a risk driven approach can lead to the removal of unwanted controls based on the organization's scope and can reduce overall expense which means its a good decision rather than throwing money at the implementation of controls which, realistically, an organization don't even require.
    
- The process culminates in a Statement of Applicability (SoA) document.
	- At last, specially after the initial implementation of ISMS or after each completion of PDCA cycle, a Statement is put forward. This document includes the justification for the inclusions and exclusions of controls. This document is named as Statement of Applicability. To understand it better, let me give you an example, if a role based access control is implemented to maintain the principle of least privilege, then it should be included to Statement of Applicability with its justification, like restricting unauthorized personnel to access database with higher privileges.

#### Slide 7: The Value of ISO 27001

- ISO 27001 certification proves an operational and auditable ISMS.
	- Now, the most important question, what are the benefits proposed by ISO 27001? for both user entity and a cloud provider. if a cloud provider holds an ISO 27001 certification, then it proves that their information security management system is continually improving to defend against modern threats and their controls are operationally effective. Also...
    
- It provides assurance in the overall security posture "of the cloud."
	- So, it verifies that a cloud provider is completing the Shared Responsibility Model by maintaining security of the cloud from their side. Now, what is Shared Responsibility Model? This model divide's the responsibility between the user entity and its cloud provider, by holding cloud provider responsible for the security of the cloud and holding user entity for the security in the cloud. For example, in a broader perspective, cloud provider is responsible for securing physical assets from physical threats like securing their data centers, while user entity is responsible for securing digital assets like the data stored in the cloud environments.
    
- This certification adds another layer of trust and credibility for the agency.
	- So, following the assurance layer, the governance layer enhance's trust and credibility of their services to user entity. If a cloud provider possess both, SSAE 18 Type II report and a certification of ISO 27001, then a government entity should consider its cloud provider among others who doesn't have any or only possess one assurance.
    
- The Statement of Applicability is a key document for review.
	- Now, A statement of applicability document should be reviewed by government entity's own auditors for better clarity on the ISMS of their cloud provider. Its not just a one time review, whenever the Statement of Applicability is updated, it should be reviewed by auditors of government entity.
    
- But it does not specify the technical tools for implementing controls.
	- But it does not specify the technical tools for implementing controls. Although, it does provide guidance on "how" the controls should be implemented through ISO 27002 but it does not mention any tools to put those controls in place, specifically the technical controls. And that is where our third and final layer Technical Controls comes in.

#### Slide 8: Cloud-Native Security Tools

- Cloud-native tools fulfill the Shared Responsibility Model.
	- So far, we've discussed the security of the cloud which covers the cloud provider's part of Shared Responsibility Model. So, the cloud native tools assist government entity to fulfil their part of Shared Responsibility Model because...
    
- They are utilized to establish security _in_ the cloud environment.
	- these tools are utilized to establish security _in_ the cloud environment. So, in the scope of my presentation, I'll be considering two major cloud providers, GCP and Azure.
    
- GCP Security Command Center provides Cloud Security Posture Management (CSPM).
	- GCP provides an extremely efficient security tool, named Security Command Center. It provides Cloud Security Posture Management or CSPM, it is a security function which helps in continuous identification and remediation of security misconfigurations. Security Command Center is not just a single tool, but it consist of several components, utilized for different purposes. For example, Security Health Analytics, which is the engine of CSPM, while Event Threat Detection component is utilized to detect malicious activities. These tools are extremely efficient in their workings because they're employed by the best security experts in the world. Also, now they've integrated artificial intelligence in these tools to reduce false positives.
    
- Microsoft Defender for Cloud offers both CSPM and Cloud Workload Protection.
	- Similarly, Microsoft Azure provide Microsoft Defender for Cloud, formerly known as Azure Security Center. It also offers CSPM and Cloud Workload Protection, this new security function provide threat detection and protect every workload on the cloud environments such as containers, storage's, serverless functions, and more.
    
- These tools create data silos, lacking a unified view across platforms.
	- Now, there is fundamental issue which is faced by every user entity working with multi-cloud environments, that is lack of centralized view. In simple terms, there is no way to manage security of different systems running on multiple cloud platforms through a unified cloud approach. For that purpose, let me introduce...

#### Slide 9: SIEM and Centralized Logging

- A Security Information and Event Management (SIEM) platform is used for threat detection.
	- A SIEM or Security Information and Event Management is the philosophy of a tool which provide a single pane of glass for the purpose of better monitoring and enhanced analysis. A SIEM tool consist of several functionalities centered towards logs such as logs correlation, aggregation and normalization.
    
- Wazuh is a powerful open-source SIEM with Host IDS and FIM capabilities.
	- Now, Wazuh is a powerful and open-source SIEM software, widely known for its Host Intrusion Detection and File Integrity Monitoring capabilities. It consist of a server and agents, a server is where everything is managed, while agents are deployed on every endpoint to forward logs to its respective server. Wazuh is not just a SIEM, its also a threat detection software which makes it a highly versatile EDR but its threat detection functionality require's expertise from its user for installing, configuring, maintaining and scaling purposes. So, to overcome that Wazuh recently introduced their Cloud version, which is pre-built and AI integrated. But this functionality does not align with centralized SIEM, ironically its not even a good choice for threat detection purposes in multi-cloud environments because a GCP's ETD is maintained by some of the worlds best security experts. But its a really good option as a...
    
- It provides a centralized platform for aggregating and correlating logs.
	- a centralized platform for aggregating and correlating logs. 
    
- A SIEM aggregates logs from on-premise and multi-cloud environments.
	- Wazuh is not a proprietary software so it avoids vendor lock-in, like if a user entity is using different cloud services from multiple providers then its easy to centralize all the log data to one Wazuh server, where it can be monitored.
    
- This provides a single, customizable dashboard of the entire security posture.

#### Slide 10: Tools in Practice

- Cloud-native tools implement controls from our ISMS.
	- Now, you'll be asking that how does this technical layer align with our previous layer of Governance? So, to put those controls in action, which are defined by ISO 27001, these tools are required, because neither ISO 27001 nor its supporting document ISO 27002 address the tools to fulfill their requirements.
    
- They generate a constant stream of security telemetry and logs.
	- Now, As I mentioned earlier that GCP Security Command Center is way better than a third party software in the context of threat intelligence. So, these cloud-native tools generate a constant stream of telemetry and logs. But, when there's a need of logs correlation in multi cloud environment, then a user entity hit a wall of vendor lock-in.
    
- A SIEM aggregates data from all platforms into a single view.
	- To overcome that a SIEM like Wazuh is utilized to aggregate and correlate logs to achieve a centralized picture for the security posture of a user entity.
    
- This provides the visibility required for real-time monitoring and incident response.
	- Now, for example, On the Google side, Security Command Center (our CSPM tool) identifies a critical misconfiguration: a public-facing storage bucket containing sensitive data. At the exact same time, on the Azure side, Microsoft Defender for Cloud (our CWP tool) detects a suspicious, unsigned process attempting to run on a virtual machine. 
		
	    Now, Both of these alerts—from the misconfigured bucket in GCP and the suspicious process in Azure—are automatically ingested and correlated by our centralized Wazuh SIEM. Wazuh provides the missing link, pulling these seemingly unrelated events from two different cloud providers and presenting them as a single, prioritized security incident on a unified dashboard. It might also show that the suspicious process in Azure was attempting to access the very bucket that was misconfigured in Google Cloud.
	
- This technical layer proves the operational effectiveness of our security program.

#### Slide 11: Summary and Final Thought

- Securing government data requires a robust, layered defense.
	- In conclusion, safeguarding government data is a national priority that requires a robust, 'Defense-in-Depth' strategy.
    
- This defense begins with the assurance of standards like SSAE 16/18.
	- We've seen that it begins with the assurance provided by standards like SSAE 18, which gives us an audited layer of trust.
    
- It is then guided by the comprehensive governance of ISO 27001.
	- This entire process is guided by the governance of a comprehensive framework like ISO 27001, which gives us a systematic way to manage our security.
    
- The strategy is implemented and measured using cloud-native and SIEM tools.
	- Finally, this strategy is put into practice and validated using modern technical tools like cloud-native security suites and SIEM platforms.
    
- Ultimately, this holistic model builds a foundation of trust and resilience.
	- This holistic, layered approach is how a government agency can build a solid foundation of trust and resilience in the cloud. It moves us from a reactive to a proactive state—because, as the great security expert Bruce Schneier once said, 'Security is not a product, but a process.' Thank you.