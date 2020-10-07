<h1 align="center">Introduction to Software Vulnerabilities</h1>

## Introduction
With the world becoming ever more dependent on computer systems, the need to protect data, information technology infrastructure, and business critical applications becomes increasingly more obvious. Software vulnerabilities are discovered everyday and the exploitation of these flaws are responsible for a projected six trillion dollars (USD) by 2021 (https://cybersecurityventures.com/hackerpocalypse-cybercrime-report-2016/). Education into developing software with security in mind can help reduce the massive costs of security breaches that are enabled through software faults.

## General Information
Vulnerabilities for specific software can be searched through a Common Vulnerability and Exposure (CVE) number. These numbers are in the format of CVE-Year-Number. An example would be CVE-2019-0708 which in this case was a very severe Microsoft vulnerability. CVEs can be registered here: https://cve.mitre.org/index.html. Vulnerabilities that do not have a CVE associated with them are referred to as zero-day vulnerabilities. 

## Types of Vulnerabilities
|Type | Description |
|---------|------------|
|Buffer Overflow | Buffer overflows occur when the buffer or variable is too small to handle the data that it is holding. The data is then moved to a volatile state which could crash the program or potentially execute commands. Buffer overflows are very common ways to achieve code execution on an affected application or machine. |
|OS Command Injection| As the name implies, OS Command Injection is an attack where an attacker (often remote) attempts to run arbitrary system commands on a target. |
|SQL Injection| SQL injection allows a malicious actor to inject SQL commands to a database. The attacker can dump sensitive user data, create new tables or views, and drop (delete) user data in some cases. |
|Cross Site Scripting| Server side scripts that are injected into web pages. Other users may be able to view the results of this script and potentially interact with malicious files or commands. |
|Cross Site Request Forgery| Similar to Cross Site Scripting however the attacker can send requests to outside entities. A shocking example would be sending a false request to a victims bank account to send money to the attackers. |
|URL Redirection| Redirection attacks allow an attacker to move traffic toward a specified website. This can be used to steal web traffic, deliver a malicious file, or to deny service.
|Path Traversal| One of my favorites, allows the attacker to traverse a directory that they should not have access to. For example if files are uploaded on a server in the /usr/uploads directory, a malicious actor can navigate using unsanitized input, to the /usr directory and other sub directories.|
|Unrestricted Upload of Malicious Files| If data is unsanitized a malicious actor can drop malicious code through various file-formats. If the code is run on the server it is classified as remote code execution. |


## Key Takeaways
Make sure to develop using security in mind principles. Using code reviews and vulnerability scanning (or if the resources exist, penetration testing) is vital to software engineering. Always sanitize user data as a general rule of thumb.

## Topics not Covered
- Social Engineering
- Physical Vulnerabilities
- Sandbox Escape
- VLAN hopping

## Further Reading 
If you would like more information about software vulnerabilities, please check out these links below:
- https://en.wikipedia.org/wiki/Vulnerability_(computing)
- https://www.upguard.com/blog/vulnerability
- https://www.solarwindsmsp.com/content/computer-security-vulnerabilities
