---
title: Example
layout:  null
tab: true
order: 1
tags: example-tag
---


# <a name="tab_desc" > </a>
# OWASP Top 10 Desktop Application Security Risks
<br/>


### [DA1 - Injections](#da1)

Issues such as SQL, LDAP, XML, OS command injection, etc. occur when untrusted input is passed to the interpreter as a part of a query/command. An attacker can trick interpreters to execute arbitrary commands to perform unwanted operations or gather unauthorized data.
 
### [DA2 - Broken Authentication and Session Management](#da2)

It includes issues such as insecure authentication implementation, authentication bypass, improper session, etc. An attacker can exploit insecure implementation in order to compromise user sessions, passwords and keys or to assume the identity of the user of the application.


### [DA3 - Sensitive Data Exposure](#da3)

Unintentional exposure of sensitive information such as PII, financial information, healthcare information or application keys and secrets. This may include data in memory post app logout, logs with sensitive info., hardcoded secrets in files (dll, binaries, configuration files), etc. An attacker can use this information to carry out identity frauds.


### [DA4 - Improper Cryptography Usage](#da4)

Issues such as usage of weak cryptographic algorithms, weak keys or secrets, custom cryptographic functions and insecure key management. An attacker can exploit these flaws to retrieve the sensitive information or to attack the users of the different instances of the same application.


### [DA5 - Improper Authorization](#da5)

Authorization flaws include weak file/folder permission per user role, missing principle of least privilege approach, improper user roles, unauthorized access to registry or environment variables, etc. An attacker can gain elevated privilege of the application or of the target system.

### [DA6 - Security Misconfiguration](#da6)

Flaws include misconfigured group policies / registry / firewall rules etc., missing file-content type check for file processing apps, misconfigured named-pipes, misconfigured supporting services used by the application, misconfigured third party services (SQL, AD, etc). An attacker can gain system access by exploiting these flaws.

### [DA7 - Insecure Communication](#da7)

Insecure communication issues include usage of weak TLS or DTLS cipher-suites/protocols, plaintext database connections, usage of plaintext communication protocols such as HTTP, COAP, MQTT,etc. These flaws allow an attacker to perform MiTM attacks in order to sniff and manipulate the data of an active connection.


### [DA8 - Poor Code Quality](#da8)

Issues related to absence of secure coding practices such as missing code-signing and verification of file integrity, missing code obfuscation, lack of binary protection, memory leaks, buffer overflows, etc. An attacker can reverse engineer the application in order to obtain information about the application logic, business specific proprietary logic or can exploit application processing using binary attacks like dll-preloading or injections, overflow/underflows and memory corruption. 

### [DA9 - Using Components with Known Vulnerabilities](#da9)


It includes usage of outdated softwares, obsolete components/services of OS/Third-party vendors. An attacker can exploit the vulnerable components/services to retrieve information or to compromise the target system either locally or remotely depending upon the exploit.


### [DA10 - Insufficient Logging & Monitoring](#da10)

Includes missing or insecure implementation of logs, improper parameters within audit logs, missing regular monitoring to detect abuse, etc. Centralized Logging and monitoring are used to detect/analyze an incident and to detect an active attack respectively, sometimes attackers try to manipulate this data to prevent alarms with many techniques like timestomping and many others, such issues also have to be focused.

