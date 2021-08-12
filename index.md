# OWASP Top 10 Desktop Application Security Risks | Quick Reference Table  

<br/><br/>

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

 &nbsp;  &nbsp; 
Note: These Top10 have been created keeping in mind Windows, *Nix platforms and using commonly available CVE, exploits, writeups.  

 &nbsp;  &nbsp; 
## [OWASP Top 10 Desktop Application Security Risks | Detailed Description](tab_detailed_DesktopTop10.md/#t2)

 &nbsp; 

