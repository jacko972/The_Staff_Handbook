# Ngineered Data Protection

## 5.1 Policy and Procedure

### Introduction

The Company, its staff and others who process or use any personal information must ensure that they follow the data protection principles set out in the Data Protection Act 1998. These are that personal data shall:

 - Be obtained and processed fairly and lawfully
 - Be obtained for a specified and lawful purpose and shall not be processed in any manner incompatible with that purpose
 - Be adequate, relevant and not excessive for those purposes
 - Be accurate and kept up to date
 - Not be kept longer than is necessary for that purpose
 - Be processed in accordance with the data subject rights
 - Be kept safe from unauthorised access, accidental loss or destruction
 - Not be transferred to a country outside the European Economic area, unless that country has equivalent levels of protection for personal data

The Company will not release staff or customer data to third parties except to relevant statutory bodies. In all other circumstances the company will obtain the consent of the individuals concerned before releasing personal data.

### Responsibility

The directors of the company are responsible for the oversight and implementation of this policy.

It will be the responsibility of the directors and senior managers of the company to ensure compliance with the policy and for communicating the policy to all staff.

All staff are responsible for ensuring that any personal data which they hold is kept securely, and personal information is not disclosed in any way and to any unauthorised third party.

### Compliance

Failure to comply with the data protection policy and procedure could result in disciplinary action.

### Review

This policy and related procedures will be reviewed and issued on at least an annual basis

### General Guidelines

 - The only people who should be able to access data covered by this policy are those who need it for their work.
 - Data should not be shared informally. Any confidential information should be requested from your line manager.
 - Employees should keep all data secure by taking sensible precautions and by following the guidelines below.
 - Personal data should not be disclosed to unauthorised people, either within the company, or externally.
 - Data should be regularly reviewed and updated. If out of date, it should be destroyed.
 - Data should only be stored or processed on customer or company owned hardware/systems.

### Data Storage Guidelines

This section describes how and where data should be stored. If you have any questions about this, please contact your line manager.

If data is stored on paper, it should be kept in a place where unauthorised people cannot see it. This includes:

 - keeping files in a locked drawer or filing cabinet
 - making sure paper and printouts are not left in a place where unauthorised people could see them
 - destroying the paper when it is no longer required

When it is stored electronically, data must be protected from unauthorised access, accidental deletion and malicious hacking attempts:

 - data should be protected by strong passwords that are changed regularly and are never shared 
 - if data is stored on removable media (like USB stick), they should be locked away when not used
 - data should only be stored on designated drives and servers and should only be uploaded to an approved cloud computing service
 - servers containing personal data should be sited in a secure location, away from general office space
 - data should be backed-up frequently
 - all servers and computers containing data should be protected by approved software and a firewall
 - Systems holding personal data should conform to company password/key policy. 
 - transmission of username password details should be encrypted where possible and not transmitted together. For example, email the username but send the password via text message.

### Data Use Guidelines

When working with data, staff should ensure:

 - the screens of their computers are always locked when unattended
 - no data is shared informally
 - data is encrypted before being transferred electronically
 - personal data is not transferred outside the European Economic Area
 - employees should not save copies of personal data to their own computer

### Data Accuracy

Staff must take reasonable steps to ensure data is kept accurate and up-to date. Data should be held in as few places as necessary, and updated at every opportunity.

### Subject Access Requests

All individuals who are subject of personal data held by Ngineered are entitled to ask what information the company holds about them and why. If an individual contacts the company requesting this information, this is called a subject access request. These should be made by email, addressed to matt@ngineered.co.uk.

### Disclosing Data for Other Reasons

In certain circumstances, the Data Protection Act allows personal data to be disclosed to law enforcement agencies without the consent of the data subject. Under these circumstances, Ngineered will disclose data, but will ensure that the request is legitimate, seeking assistance from legal advisers where necessary. The default policy is not to hand over data and we will fight this where possible.

## 5.2 Ngineered Password Policy and Procedure

### Introduction

When accessing systems and setting up new accounts for users, all Ngineered staff should conform to the password policy and procedures.
Policies

### Password Strength
Passwords should be:

 - A minimum of 12 characters
 - Be based on large entropy rather than forced character requirements. For example:
 - correcthorsebatterystaple is a more secure password that HArd2Rememb3r!

### MFA
Where possible MultiFactor Authentication should be enabled, this can be:

 - Yubikey
 - Google authentication application on a company owned mobile device
 - Gemalto cards for AWS Root accounts issued by Ric Harvey

### Password Safes
The only password safe software to be used is LastPass and this should be in conjunction with your Ngineered email account.

No plain text copies of passwords either typed or handwritten should ever be made.

### Procedures

#### Sending passwords to external users

When transmitting passwords to external users you should never transmit usernames and passwords over the same medium. For example if you send a user their username over email then the password should be confirmed over the phone or via text message. In the event this is not possible due to timezones or other factors, the user must be forced by the system to change their password immediately after login on. You should always advise customers to enable MultiFactor Authentication where possible.

#### Password Rotation

Staff are expected to rotate their system passwords regularly. Our recommendation is every 3 months.

#### Reporting compromised or suspected compromised Passwords

If you believe that your password may have become compromised you should report this immediately to your line manager. Your line manager will then report this directly to the directors so action can be taken to secure your accounts and ensure no systems have been effected.

## 5.3 Accessing Systems

### Introduction

This section will set out the basic security principles for accessing internal and customer systems.

### Procedures

#### Accessing Internal Systems

Internal systems should be accessed either via teh VyperVPN service in AWS or over HTTPS/SSH usinf public/provate key where appropriate. If systems need a password then MFA should be enabled. Internal systems include:

 - Gitlab
 - Slack
 - Gmail (mail,contacts and calendar)
 - Rota
 - SLA
 - Contact
 - All systems in our AWS account

#### Accessing Customer systems

Customer systems should be connected to according to their information security policy. Where this is undefined we should limit our system access SSH/RDP etc. to a single IP ingress into their platform. This IP is our VPN endpoint in AWS:

 - 52.49.150.14 (vpn.ngd.io)

This is an OpenVPN service and password auth is done via vyperVPN/Goldenfrog.

## Sections

* [1.0 Introduction](./README.md)
* [2.0 Absence](./2-Absence.md)
* [3.0 Pay & Benefits](./3-Pay_+_Benefits.md)
* [4.0 Policies](./4-Policies.md)
* [5.0 Information Security](./5-Information_Security.md)

