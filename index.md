---

layout: col-sidebar
title: OWASP Desktop App Security Top 10
tags: example-tag
level: 2
type: 
pitch: A very brief, one-line description of your project

---

 In addition to this information, the 'front-matter' above this text should be modified to reflect your actual information.  An explanation of each of the front-matter items is below:

layout: This is the layout used by project and chapter pages.  You should leave this value as col-sidebar

title: This is the title of your project or chapter page, usually the name.  For example, OWASP Zed Attack Proxy or OWASP Baltimore

tags: This is a space-delimited list of tags you associate with your project or chapter.  If you are using tabs, at least one of these tags should be unique in order to be used in the tabs files (an example tab is included in this repo) 

level: For projects, this is your project level (2 - Incubator, 3 - Lab, 4 - Flagship)

type: documentation
# Top 10 Desktop Application Security Risks

[DA1](#a)

| OWASP Top 10 Desktop App | Examples |
|---|---|
| DA1 - Injections | SQLi, LDAP, XML, OS Command |
| DA2 - Broken Authentication | OS / DesktopApp account Authentication & Session Management, Auth. for Import / Export with external Drive, Auth. for Network Shared Drives or other Peripheral devices |
| DA3 - Sensitive Data Exposure | Data in Memory post App Logout, Logs with Sensitive Info., Hardcoded Secrets in files |
| DA4 - Insufficient Cryptography | Usage of Outdated Cryptographic Algirithms or Weak Keys, Inappropriate usage of Cryptographic Functions, Reuse of Cryptographic Parameters across all Installations, Improper usage of Cryptography for Integrity Check |
| DA5 - Improper Authorization | Weak File/Folder Permission per User Role, Missing Principle of Least Privilege approach, Improper User Roles |
| DA6 - Security Misconfiguration | Weak OS Hardening, Misconfigured Group Policies / Registry / Firewall rules etc., Missing File Type check for File Processing Apps,  Misconfigured Named-Pipes, etc. |
| DA7 - Insecure Communication | Usage of weak TLS or DTLS Cipher-suites, Weak TLS or DTLS Protocols, Absent Encrypted DB Queries, Absent Encrypted standard/custom protocol communication |
| DA8 - Poor Code Quality | Missing Code-Signing and Verification for File Integrity, Missing Code Obfuscation, Dll-Preloading or Injection, Race Conditions, #############(Overflows, Null pointers, memory corruption) etc.  |
| DA9 - Using Components with Known Vulnerabilities | Usage of Outdated Softwares, or Usage of Obsolete Components/Services of Windows/3rd Party vendors |
| DA10 - Insufficient Logging & Monitoring | Missing or Improper Logging of Activities, Missing Regular Monitoring to Detect Abuse |
