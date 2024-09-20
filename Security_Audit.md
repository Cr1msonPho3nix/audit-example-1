# Scenario

This scenario is based on a fictional company:

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide.

The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist.

## Scope and goals of the audit

### Scope

The scope is defined as the entire security program at Botium Toys. This means all assets need to be assessed alongside internal processes and procedures related to the implementation of controls and compliance best practices.

### Goals

Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices need to be implemented to improve Botium Toys’ security posture.

## Current Assets

- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring

## Risk assessment

### Risk description

Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards

### Control best practices

The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

### Risk score

On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

#### Additional comments

The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:

- Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
- Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database.
- Access controls pertaining to least privilege and separation of duties have not been implemented.
- The IT department has ensured availability and integrated controls to ensure data integrity.
- The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
- Antivirus software is installed and monitored regularly by the IT department.
- The IT department has not installed an intrusion detection system (IDS).
- There are no disaster recovery plans currently in place, and the company does not have backups of critical data.
- The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
- Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters).
- There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
- While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.
- The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.

## Controls and Compliance Checklist

Does Botium Toys currently have this control in place?
| Control | Yes or not | Why? |
| :------- | :---: | :--- |
| Least Privilege | No | All the employees have access to customer data. This has to be changed to reduce the risk of breach. |
| Disaster Recovery Plan | No | No disaster recovery plan in place. This have to be implemented to ensure business continuity. |
| Password policies | No | Password policy exists, the requirements are almost none, which could allow a threat actor to more easily access secure data. |
| Separation of duties | No | Any employee can access the data. This needs to be implemented alongside "Least Privilege" to reduce the possibility of fraud/access to critical data.|
| Firewall | Yes | Existing Firewall is set by the IT department.|
| Intrusion Detection System (IDS) | No | An IDS nneds to put in place to help identify possible intrusions by threat actors.|
| Backups | No | Backups are crucial to recover critical data in case of a lose or breach, mostly to ensure business continuity.|
| Antivirus Software | Yes | Antivirus is installed and monitored by the IT Department.|
| Manual monitoring, maintenance, and intervention for legacy systems | No | While legacy systems are monitored and maintained, there is no regular schedule for this task. Policies related to intervention needs to be clear or they will pose a risk of breach.|
| Encryption | No | Encryption is crucial to protect stored data, prodiving greater confidentiality of sensitive information.|
| Password management system | No | Introducing a password management system would improve IT department/other employee productivity in the case of password issues.|
| Locks | Yes | The store’s physical location has sufficient lock ammount.|
| Closed-circuit television (CCTV) surveillance | Yes | CCTV is installed at store’s physical location.|
| Fire detection/prevention (fire alarm, sprinkler system, etc.) | Yes | Store physical location has a functioning fire detection and prevention system.|

## Compliance Checklist

Does Botium Toys currently adhere to this compliance best practice?
<u>Payment Card Industry Data Security Standard (PCI DSS)</u>
| Best Practice | Yes or not | Why? |
| :------- | :---: | :--- |
| Only authorized users have access to customers’ credit card information. | No | Because all employees have access to the company’s internal data.|
| Credit card information is accepted, processed, transmitted, and stored internally, in a secure environment. | No | Credit card information is not encrypted and all employees, as stated before, have access to the internal data, including customer's credit card information.|
|Implement data encryption procedures to better secure credit card transaction touchpoints and data. | No | No Encryption is used in any kind of data stored, so confidentiality of costumers' financial information is at risk.|
|Adopt secure password management policies. | No | Password policies are nominal and there is no password management system used.|

<u>General Data Protection Regulation (GDPR)</u>
| Best Practice | Yes or not | Why? |
| :------- | :---: | :--- |
| E.U. customers’ data is kept private/secured. | No | No Encryption is used in any kind of data stored, so confidentiality of costumers' financial information is at risk.|
| There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. | Yes | There is a plan to notify E.U. customers within 72 hours of a data breach.|
| Ensure data is properly classified and inventoried. | No | Assets have been inventoried/listed, but not classified.|
| Enforce privacy policies, procedures, and processes to properly document and maintain data. | Yes | Privacy policies, procedures, and processes have been developed among IT team members and other employees.|

<u>System and Organizations Controls (SOC type 1, SOC type 2)</u>
| Best Practice | Yes or not | Why? |
| :------- | :---: | :--- |
| User access policies are established. | No | Some controls, as "Least Privilege" and "Separation of Duties" are not implemented, so place; all employees have access to internally stored data.|
| Sensitive data (PII/SPII) is confidential/private. | No | Encryption has to be implemented to ensure the confidentiality of PII/SPII..|
| Data integrity ensures the data is consistent, complete, accurate, and has been validated.. | Yes | Data integrity is in place.|
| Data is available to individuals authorized to access it. | No | Data is available to all employees, but authorization needs to be limited to only the individuals who need access to it to do their jobs.|

## Recommendations

After auditing Botium Toys security posture, some crucial controls have to be in place to protect the data stored, such as:

- Implement the OWASP principle of least privilege, due to all workers having access to almost any information.
- Creating backups and a recovery plan is crucial in case something happens.
- Encryption should be implemented due to the storage of personal information, which can be easily read in a leak.
- A password management system should be implemented to avoid weak passwords and easily group all passwords of a specific worker, so in case of forgetting it only the master password has to be modified.
- Password policies have to be modified in order to create stronger, more difficult to break, passwords.
- Legacy System Management should be improved in order to “Minimize the attack surface area”, mostly due to out of date equipment and security flags.
