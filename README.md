# Lorenz-Ransomware



**MITRE ATT&CK Techniques:**

**1. Initial Access**

Phishing
Valid Accounts
Trusted Relationship

**2. Lateral Movement**

Taint Shared Content
Remote File Copy

**3. Execution**

Command and Scripting Interpreter: PowerShell
Scheduled Task/Job
Windows Management Instrumentation

**4. Defense Evasion**

Masquerading

**5. Credential Access**

Credentials from Password Stores

**6. Discovery**

Account Discovery
System Information Discovery
File and Directory Discovery

**7. Collection**

Data from Local System

**8. Impact**

Data Encrypted for Impact
Inhibit System Recovery

**Indicators of Compromise:**

SHA-256:

8ea6a6d4578029c7b2dbbfb525ec88b2cb309901ec5a987847471b6101f0de41

971f0a32094b8ac10712503305ac6789048d190a209c436839e2e6b0acb016f3

cef17b9289ba18c979b704648c0f2b736f65f9f9158b471bc2486b6c14e14a4d

edc2070fd8116f1df5c8d419189331ec606d10062818c5f3de865cd0f7d6db84

a0ccb9019b90716c8ee1bc0829e0e04cf7166be2f25987abbc8987e65cef2e6f

1264b40feaa824d5ba31cef3c8a4ede230c61ef71c8a7994875deefe32bd8b3d

40ff1ab8ac09057421079dae83fb675d7a2a3da6c7d0cd6400a0d720c5b0f58c

a9fdbc6d20b780ca42660ad4803f391308fa0243fbc515fd3c1acf935dd43c1e

7275034886da11ca6d828547f15cab259e22ba624c5f5762afd237aa686455dd

5b03b861884cb3e14a8b888c7dee2ee0d494933df863d504882345fa278d1ea5

71cdbbc62e10983db183ca60ab964c1a3dab0d279c5326b2e920522480780956

4b1170f7774acfdc5517fbe1c911f2bd9f1af498f3c3d25078f05c95701cc999

c0c99b141b014c8e2a5c586586ae9dc01fd634ea977e2714fbef62d7626eb3fb

**C2 IPs:**

162[.]33[.]179[.]45

172[.]86[.]75[.]63

65[.]21[.]187[.]237

167[.]99[.]186[.]156

157[.]90[.]147[.]28

143[.]198[.]117[.]43 

45[.]61[.]139[.]150


**Recommendation:**

1.	Create rules to detect and block IOCs mentioned above in applicable security solutions - SIEM, EDR, Firewall, Proxy etc. to secure the network and Search for existing signs of the indicated IOCs in your environment.

2.	Upgrade software and operating systems, applications, and firmware on network assets in a timely manner for prevention. 

3.	Kindly ensure that your Endpoint Security and Perimeter security products are updated with latest signatures to detect these threats.

4.	Enforce least privilege: Remove admin rights for users and reduce application and machine privileges to the minimum required. Just-in-time access should also be implemented to reduce persistent or standing privileges

5.	Maintain offline (i.e., physically disconnected) backups of data, and regularly test 

6.	backup and restoration.

7.	Protect cloud storage by backing up to multiple locations, requiring MFA for access and encrypting data in the cloud.

8.	Collect telemetry from cloud environments. Ensure that telemetry from cloud environments including the network telemetry (e.g., virtual private cloud [VPC] flow logs), identity telemetry (e.g., account sign-on, token usage, federation configuration changes) and application telemetry (e.g., file downloads, cross-organization sharing) is retained and visible to the security team.

9.	Ensure all backup data is encrypted.

10.	For Linux users, we recommend that use a Linux security module (such as SELinux, AppArmor, or SecComp) for defense in depth.

11.	Remind users not to visit un-trusted websites or follow links provided by unknown or un-trusted sources.

12.	Inform and educate users regarding the threats posed by hypertext links contained in emails or attachments especially from un-trusted sources.

**Reference**

https://www.cybereason.com/blog/cybereason-vs.-lorenz-ransomware
https://securityaffairs.co/wordpress/126738/malware/lorenz-ransomware-hit-hensoldt.html
https://www.cybertalk.org/the-worst-outcomes-lorenz-ransomware-a-new-double-extortion-strategy/ https://www.bleepingcomputer.com/news/security/defense-contractor-hensoldt-confirms-lorenz-ransomware-attack/
https://www.tesorion.nl/en/posts/lorenz-ransomware-rebound-corruption-and-irrecoverable-files/
https://research.checkpoint.com/2022/17th-january-threat-intelligence-report/
