+++
date = "2016-02-26T21:09:22-08:00"
draft = true
title = "Administrative Safeguards (164.308)"
comments=false
share=false
noauthor=true
+++

Taken directly from the wording of the Security Rule, administrative safeguards are *administrative actions, and policies and procedures, to manage the selection, development, implementation, and maintenance of security measures to protect electronic protected health information and to manage the conduct of the covered entity's workforce in relation to the protection of that information.*

There aren't specific security settings in this section, and the most important area covered is the risk assessment. The risk assessment is a fundamental process for any organization that wants to become compliant. Because Innovation Force is a division of Cambia Health Solutions some policy and compliance measures are shared with other departments of Cambia, such as the security office or disaster recovery.

## Security Management Process - 164.308(a)(1)(i)

Standard | Description
--------- | -----------
Risk Analysis (Req)  | Conduct an accurate and thorough assessment of the potential risks and vulnerabilities to the confidentiality, integrity, and availability of electronic PHI held by the covered entity.
Risk Management (Req) | Implement security measures sufficient to reduce risks and vulnerabilities to a reasonable and appropriate level to comply with Sec. 164.306(a) [Security standards: General rules; (a) General requirements].
Sanction Policy (Req) | Apply appropriate sanctions against workforce members who fail to comply with the security policies and procedures of the covered entity.
Information System Activity Review (Req) | Implement procedures to regularly review records of information system activity, such as audit logs, access reports, and security incident tracking reports.

```
Innovation Force has a risk management policy that defines the risk analysis and risk management process. This policy is operationalized with processes to conduct regularly risk assessments. Innovation Force uses NIST800-30 and 800-26 for performing risk analysis. Our policy begins with an inventory of all Innovation Force systems, mapping of where ePHI is processed, transmitted, or stored, identification of threats, risks, and likelihood, and the mitigation of risks. Policies address risk inherent within the environment and mitigating the risk to an acceptable and reasonable level.

Innovation Force has a Sanction Policy that has sanctions for employees not adhering to certain policies, and for specifically violating HIPAA rules.

Policies and procedures address the requirements of monitoring and logging system level events and actions taken by individuals within the environment. All requests into and out of the Innovation Force network are logged, as well as all system events. Innovation Force, has implemented multiple logging and monitoring solutions to track events within their environment and to monitor for certain types of behavior. Log data is regularly reviewed. Additionally, proactive alerts are enabled and triggered based on certain suspicious activity.
```

## Assigned Security Responsibility - 164.308(a)(2)

Standard | Description
--------- | -----------
Assigned Security Responsibility (Req) | Identify the security official who is responsible for the development and implementation of the policies and procedures required by this subpart for the entity.


```
Innovation Force has formally assigned and documented its security officer. Our security officer is Alexander Thorpe. He can be reached by email at alexander.thorpe [at] cambiahealth.com.
```

## Workforce Security - 164.308(a)(3)(i)

Standard | Description
--------- | -----------
Authorization and/or Supervision (A) | Implement procedures for the authorization and/or supervision of workforce members who work with electronic protected health information or in locations where it might be accessed.
Workforce Clearance Procedure (A) | Implement procedures to determine that the access of a workforce member to electronic protected health information is appropriate.
Termination Procedures (A) | Implement procedures for terminating access to electronic protected health information when the employment of a workforce member ends or as required by determinations made as specified in paragraph (a)(3)(ii)(B) [Workforce Clearance Procedures] of this section.


```
Innovation Force has policies in place that require workforce members requesting access to ePHI to submit an authorization form that is signed and acknowledges their responsibility of safeguarding ePHI. The form must also be approved by the Security Officer. Once signed and approved, then the individual will be provisioned access to systems deemed business necessary. All Access to ePHI is based on minimum necessary requirements and least privilege.

Innovation Force policies define the immediate removal of access once an employee has been terminated, with the Security Officer responsible for terminating the access. Once HR initiates the termination process the termination checklist is referenced to ensure necessary actions are taken to remove systems and facilities access.
```


## Information Access Management - 164.308(a)(4)(i)

Standard | Description
--------- | -----------
Isolating Health care Clearinghouse Function (Req) | If a health care clearinghouse is part of a larger organization, the clearinghouse must implement policies and procedures that protect the electronic protected health information of the clearinghouse from unauthorized access by the larger organization.
Access Authorization (A) | Implement policies and procedures for granting access to electronic protected health information, for example, through access to a workstation, transaction, program, process, or other mechanism.
Access Establishment and Modification (A) | Implement policies and procedures that, based upon the entity's access authorization policies, establish, document, review, and modify a user's right of access to a workstation, transaction, program, or process.


```
Innovation Force does not perform the functions of a Healthcare Clearinghouse so aspects of this section are not applicable.

The security officer determines the roles necessary for each system and application. When access is needed to Innovation Force infrastructure, a request and acknowledgement form is signed and then approved by the Security Officer.

Innovation Force has a formal process for requesting additional access to ePHI, and all Innovation Force developers must get approval for all requests concerning ePHI.
```

## Security Awareness and Training - 164.308(a)(5)(i)

Standard | Description
--------- | -----------
Security Reminders (A) | Periodic security updates to all members of Innovation Force
Protection from Malicious Software (A) | Procedures for guarding against, detecting, and reporting malicious software.
Log-in Monitoring (A) | Procedures for monitoring log-in attempts and reporting discrepancies.
Password Management (A) | Procedures for creating, changing, and safeguarding passwords.


```
Innovation Force, Inc has a Security Awareness training policy in place that requires new employees and current employees to conduct training upon hire and annually thereafter. Minimum training is done annually, with regular informal security and compliance training done at least once a month.

Innovation Force proactively assesses and tests for malicious software within their environment, both infrastructure and workstations. Members of the Innovation Force team monitor bug and vulnerability lists to assure they remain up to date.

Innovation Force is monitoring and logging successful and unsuccessful log-in attempts to the servers within its environment and policies are in place requiring audit logging, which includes login attempts.

Password configurations are set to require that passwords are a minimum of 8 character length, 90 day password expiration, account lockout after 5 invalid attempts, password history of last 4 passwords remembered, and account lockout after 15 minutes of inactivity.
```


## Security Incident Procedures - 164.308(a)(6)(i)

Standard | Description
--------- | -----------
Response and Reporting (Req) | Identify and respond to suspected or known security incidents; mitigate, to the extent practicable, harmful effects of security incidents that are known to the covered entity; and document security incidents and their outcomes.


```
Innovation Force has implemented a formal incident response plan (IRP), which discusses the procedures for identifying, responding to, and escalating suspected and confirmed security breaches. Innovation Force has implemented an incident response team for the purposes of dealing with potential security breaches. The IRP has specific types of incidents to look out for, as well as some common types of incidents that are monitored for within the environment.
```

## Contingency Plan - 164.308(a)(7)(i)

Standard | Description
--------- | -----------
Data Backup Plan (Req) | Establish and implement procedures to create and maintain retrievable exact copies of electronic protected health information.
Disaster Recovery Plan (Req) | Establish (and implement as needed) procedures to restore any loss of data.
Emergency Mode Operation Plan (Req) | Establish (and implement as needed) procedures to enable continuation of critical business processes for protection of the security of electronic PHI while operating in emergency mode.
Testing and Revision Procedure (A) | Implement procedures for periodic testing and revision of contingency plans.
Applications and Data Criticality Analysis (A) | Assess the relative criticality of specific applications and data in support of other contingency plan components.


```
Innovation Force, Inc has a formal Backup and Recovery Policy that defines the data backup strategy including: schedule, associated responsibilities, and any risk-assessed exclusion to the backup schedule.

Innovation Force has a formal Disaster Recovery plan to ensure the efficient recovery of critical business data and systems in the event of a disaster. The DR plan includes specific technical procedures necessary to reinstate the infrastructure and data to allow critical business functions to continue business operations after a disaster has occurred. Additionally, the Innovation Force DR plan includes requirements for performing annual testing of the DR plan to ensure its effectiveness.

Innovation Force has a DR plan, or a Business Continuity Plan (BCP), to aid in the efficient recovery of critical business functions after a disaster has been declared. The BCP goes into effect after facility outage of 24 hours. The BCP identifies critical information necessary to resume business operations such as: Hardware/software requirements, recovery time objectives, forms, employee/vendor contact lists, alternate working procedures, emergency access procedures, and a data and application criticality analysis. The BCP includes an Emergency Mode Operations Plan that addresses the access and protection of ePHI while operating in emergency mode.

The DR and BPC plans are reviewed and tested annually or whenever significant infrastructure changes occur.

Innovation Force has a performed an applications and data criticality analysis that details what systems and application need be recovered and their specific order in the recovery process.
```

## Evaluation - 164.308(a)(8)

Standard | Description
--------- | -----------
Evaluation (Req) | Perform a periodic technical and non-technical evaluation, based initially upon the standards implemented under this rule and subsequently, in response to environmental or operational changes affecting the security of electronic PHI that establishes the extent to which an entity's security policies and procedures meet the requirements of this subpart.


```
Innovation Force has formal internal policies and procedures for conducting periodic technical and non-technical testing. These define procedures for performing quarterly internal and external vulnerability scanning, as well as annual penetration testing. Vulnerability scanning is performed regularly on a weekly basis and with any major changes in infrastructure. Additionally, non-technical evaluations occur on an annual basis to ensure that the security posture of Innovation Force is at the defined level, approved by management, and communicated down to Innovation Force employees.
```

## Business Associate Contracts and Other Arrangement - 164.308(b)(1)

Standard | Description
--------- | -----------
Written Contract or Other Arrangement (Req) | A covered entity, in accordance with 164.306 [Security Standards: General Rules], may permit a business associate to create, receive, maintain, or transmit electronic protected health information on the covered entity's behalf only if the covered entity obtains satisfactory assurances, in accordance with 164.314(a) [Business Associate Contracts or Other Arrangements] that the business associate will appropriately safeguard the information. Document the satisfactory assurances required by paragraph (b)(1) [Business Associate Contracts and Other Arrangements] of this section through a written contract or other arrangement with the business associate that meets the applicable requirements of 164.314(a) [Business Associate Contracts or Other Arrangements].


```
Innovation Force has a formalized template, as well as policies in place regarding Business Associate Agreements and written contracts. Innovation Force has engaged a third party provider for hosting responsibilities and has written attestations of safeguarding its data. Additionally, Innovation Force performs due diligence in assuring that third party providers they select go through their due diligence process and provide services consistent with Innovation Force's security and compliance posture.
```
