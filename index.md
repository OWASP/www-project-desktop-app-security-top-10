---

layout: col-sidebar
title: OWASP Desktop App Security Top 10
tags: example-tag
level: 2
type: 
pitch: A very brief, one-line description of your project

---

This is an example of a Project or Chapter Page.  Please change these items to indicate the actual information you wish to present.  In addition to this information, the 'front-matter' above this text should be modified to reflect your actual information.  An explanation of each of the front-matter items is below:

layout: This is the layout used by project and chapter pages.  You should leave this value as col-sidebar

title: This is the title of your project or chapter page, usually the name.  For example, OWASP Zed Attack Proxy or OWASP Baltimore

tags: This is a space-delimited list of tags you associate with your project or chapter.  If you are using tabs, at least one of these tags should be unique in order to be used in the tabs files (an example tab is included in this repo) 

level: For projects, this is your project level (2 - Incubator, 3 - Lab, 4 - Flagship)

type: code, tool, documentation, or other
# Top 10 Desktop Application Security Risks

[DA1](#a)

| OWASP Top 10 Desktop App | Examples |
|---|---|
| DA1 - Injections | SQLi, LDAP, XML, OS Command |
| DA2 - Broken Authentication | OS / Desktop app account authentication & Session, Auth. for Import / Export with external drive, Auth. for Network Shared Drives or other Peripheral devices |
| DA3 - Sensitive Data Exposure | Data in Memory post logout, Logs with sensitive info., Hardcoded secrets in files, missing data at rest |
| DA4 - Insufficient Cryptography | Usage of outdated cryptographic algirithms or weak keys, inappropriate usage of cryptographic functions, reuse of cryptographic values across all installations, Improper usage of cryptography for integrity check |
| DA5 - Improper Authorization | Weak folder/file permission per user role, missing principle of least privilege principle, improper user role |
| DA6 - Security Misconfiguration | weak OS hardening, misconfigured group policies or regedit or firewall rules, missing file type check for file processing apps, usage of outdated Wnidows services, misconfigured named-pipes, etc. |
| DA7 - Insecure Communication | Usage of weak TLS or DTLS Cipher-suites, Weak TLS or DTLS Protocols, Absent Encrypted DB Queries, Absent Encrypted custom protocol communication |
| DA8 - Poor Code Quality | Missing code signing and verification for file integrity, Missing code Obfuscation, dll-preloading or injection,   |
| DA9 - Using Components with Known Vulnerabilities | Usage of outdated softwares |
| DA10 - Insufficient Logging & Monitoring | Missing  or inappropriate logging of operations and regular monitoring to detect abuse |
