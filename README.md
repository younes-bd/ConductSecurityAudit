<h1> Conduct a security audit </h1>

<h2>Description</h2>
Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location. However, its online presence has grown, attracting customers in the U.S. and abroad. Their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, and completing a risk assessment. The goal of the audit is to provide an overview of the risks the company might experience due to the current state of their security posture. The IT manager wants to use the audit findings as evidence to obtain approval to expand his department. 

Your task is to review the IT manager’s scope, goals, and risk assessment. Then, perform an internal audit to complete a controls assessment and compliance checklist.
<br />

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>
<p align="center">
analyze the audit scope, goals, and risk assessment : <br/>
  
You receive the following email from your IT manager:
Hello!
I have completed the audit scope and goals, as well as a risk assessment. At a high level, the main goals and risks are as follows:
Goals:
Improve Botium Toys’ current security posture by aligning to industry best practices (e.g., adhere to the NIST CSF, implement concept of least permissions)
Provide mitigation recommendations (i.e., controls, policies, documentation), based on current risks
Identify compliance regulations Botium Toys must adhere to, primarily based on where we conduct business and how we accept payments
To review the full report, read the Botium Toys: Audit scope and goals document

Risks:
Inadequate management of assets
Proper controls are not in place
May not be compliant with U.S. and international regulations and guidelines
Current risk score is 8/10 (high), due to a lack of controls and adherence to compliance regulations and standards
To review the complete list of assets and risks, read the Botium Toys: Risk assessment document 

Thank you,
Botium Toys IT Manager

After you review the audit scope, goals, and risk assessment, consider the following questions:
What are the biggest risks to the organization?
Which controls are most essential to implement immediately versus in the future?
Which compliance regulations does Botium Toys need to adhere to, to ensure the company keeps customer and vendor data safe, avoids fines, etc.?
Then, move on to the next step. 

<p align="center">
conduct the audit: controls assessment <br/>

Controls assessment 

To review control categories, types, and the purposes of each, read the control categories document.
Current assets
Assets managed by the IT Department include: 
●	On-premises equipment for in-office business needs  
●	Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
●	Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
●	Internet access
●	Internal network
●	Vendor access management
●	Data center hosting services  
●	Data retention and storage
●	Badge readers
●	Legacy system maintenance: end-of-life systems that require human monitoring 


Administrative Controls
Control Name	Control type and explanation

	Needs to be implemented (X)	Priority

Least Privilege	Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs	X	High
Disaster recovery plans	Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration	X	High
Password policies	Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques	X	High
Access control policies	Preventative; increase confidentiality and integrity of data	X	High
Account management policies	Preventative; reduce attack surface and limit overall impact from disgruntled/former employees	X	High/
Medium
Separation of duties	Preventative; ensure no one has so much access that they can abuse the system for personal gain	X	High





Technical Controls
Control Name	Control type and explanation
	Needs to be implemented
(X)	Priority

Firewall
	Preventative; firewalls are already in place to filter unwanted/malicious traffic from entering internal network	NA	NA
Intrusion Detection System (IDS)	Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly	X	High
Encryption
	Deterrent; makes confidential information/data more secure (e.g., website payment transactions)	X	High/
Medium
Backups	Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan	X	High
Password management system	Corrective; password recovery, reset, lock out notifications	X	High/
Medium
Antivirus (AV) software	Corrective; detect and quarantine known threats	X	High
Manual monitoring, maintenance, and intervention	Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities	X	High






Physical Controls
Control Name	Control type and explanation
	Needs to be implemented
(X)	Priority

Time-controlled safe	Deterrent; reduce attack surface/impact of physical threats	X	Medium/
Low
Adequate lighting	Deterrent; limit “hiding” places to deter threats	X	Medium/
Low
Closed-circuit television (CCTV) surveillance	Preventative/detective; can reduce risk of certain events; can be used after event for investigation	X	High/
Medium
Locking cabinets (for network gear) 	Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear	X	Medium
Signage indicating alarm service provider	Deterrent; makes the likelihood of a successful attack seem low	X	Low
Locks	Preventative; physical and digital assets are more secure	X	High
Fire detection and prevention (fire alarm, sprinkler system, etc.)	Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc.	X	Medium/
Low




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
