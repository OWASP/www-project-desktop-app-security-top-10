---

layout: col-sidebar
title: OWASP Desktop App Security Top 10
tags: OWASP-Desktop-App-Security-Top-10
level: 2
type: documentation
pitch: Desktop App Security top 10 documents vulnerabilities for all major platform derived from publicaly known exploits, CVEs etc.

---


The OWASP Desktop App. Security Top 10 is a standard awareness document for developers, product owners and security engineers. It represents a broad consensus about the most critical security risks to Desktop applications.

Globally recognized by developers as the first step towards more secure coding.

Companies should adopt this document and start the process of ensuring that their desktop applications minimize these risks. Using the OWASP Top 10 is perhaps the most effective first step towards changing the software development culture within your organization into one that produces more secure code.




# OWASP Top 10 Desktop Application Security Risks | Quick Reference Table  


| OWASP Top 10 Desktop App | Examples |
|---|---|
| DA1 - Injections | SQLi, LDAP, XML, OS Command, etc. |
| DA2 - Broken Authentication & Session Management | OS / DesktopApp account Authentication & Session Management, Auth. for Import / Export with external Drive, Auth. for Network Shared Drives or other Peripheral devices |
| DA3 - Sensitive Data Exposure | Data in Memory post App Logout, Logs with Sensitive Info., Hardcoded Secrets in files, etc. |
| DA4 - Improper Cryptography Usage | Weak Keys or Usage of Outdated Cryptographic Algirithms, Inappropriate usage of Cryptographic Functions, reuse of Cryptographic Parameters across all Installations, Improper usage of Cryptography for Integrity check |
| DA5 - Improper Authorization | Weak File/Folder Permission per User Role, Missing Principle of Least Privilege approach, Improper User Roles |
| DA6 - Security Misconfiguration | Weak OS Hardening, Misconfigured Group Policies / Registry / Firewall rules etc., Missing File Type check for File Processing Apps,  Misconfigured Named-Pipes, misconfigured 3rd party services, etc. |
| DA7 - Insecure Communication | Usage of weak TLS or DTLS Cipher-suites or Protocols, Unencrypted DB Queries in Transit, Absent Encrypted standard/custom protocol communication like HTTP, MQTT, COAP, etc. |
| DA8 - Poor Code Quality | Missing Code-Signing and Verification for File Integrity, Missing Code Obfuscation, Dll-Preloading or Injection, Race Conditions, lack of binary protection (Overflows, Null pointers, memory corruption) etc.  |
| DA9 - Using Components with Known Vulnerabilities | Usage of Outdated Softwares, or Usage of Obsolete Components/Services of Windows/3rd Party vendors |
| DA10 - Insufficient Logging & Monitoring | Missing or Improper Logging of Activities, Missing Regular Monitoring to Detect Abuse |  


Note: These Top10 have been created keeping in mind Windows, *Nix platforms and using commonly available CVE, exploits, writeups.


