# Web-network-penetration-testing

##  owasp-zap-dast

## 
The OWASP ZAP DAST lab where I performed Dynamic Application Security Testing against live web applications to identify OWASP Top 10 vulnerabilities. Used automated scanning, manual exploration, and active attack techniques to discover SQL injection, XSS, authentication bypass, and broken access control issues.

------------------------------------------------------------------------------------------------------
## Skills Learned :- 

Dynamic Application Security Testing (DAST) against running web applications

OWASP Top 10 vulnerability identification and exploitation

Automated spidering, active scanning, and manual request interception

Risk rating using OWASP Risk Rating Methodology

Professional web application security reporting for development teams
------------------------------------------------------------------------------------------------------
## Tools Used

OWASP ZAP - Open-source DAST proxy and web vulnerability scanner

ZAP Spider - Automated web application crawling and discovery

Active Scanner - Automated vulnerability exploitation engine

Manual Request/Response Editor - Custom payload testing

HTML/JSON Reports - Professional vulnerability documentation
-----------------------------------------------------------------------------------------------------
## Steps taken :
the target : dvwa.structureality.com
1. as startup i launched zap in kali which lead me into main page
 <img width="1268" height="825" alt="image" src="https://github.com/user-attachments/assets/844d1ff0-89b9-4d21-8864-412fb98cd097" />
 for this task im gonna use Automated Scan and this is the result :
<img width="1266" height="870" alt="image" src="https://github.com/user-attachments/assets/152075d8-4746-41d8-9b5d-5f6b605c2750" />
there is too much details but im gonna use random ones

1. path traversal  <img width="757" height="316" alt="image" src="https://github.com/user-attachments/assets/31c3259e-5cee-48b8-a9e1-2b7031cb4485" />
 as we can see we have Risk level  : high,  CWE ID :22 and WASC ID : 33

2. Content security policy (CSP) Headernot set : <img width="743" height="272" alt="image" src="https://github.com/user-attachments/assets/396fb055-e906-403f-b37a-d9aeabc95a25" />
Risk Level : medium CWE ID :693 WASC ID : 15

-----------------------------------------------------------------------------------------------------
# nikto-wapiti-scanning

## 
The Nikto + Wapiti web vulnerability scanning lab where I performed comprehensive server-side and application-layer security testing. Used Nikto for web server misconfigurations and outdated software detection, combined with Wapiti's black-box injection testing to identify SQLi, XSS, file disclosure, and other OWASP Top 10 vulnerabilities.

------------------------------------------------------------------------------------------------------
## Skills Learned :- 

Web server vulnerability scanning (outdated software, misconfigurations)

Black-box application testing (SQL injection, XSS, file disclosure, SSRF)

Server fingerprinting and version-specific vulnerability detection

Multi-tool correlation for vulnerability validation

Web security assessment reporting combining server + application findings
------------------------------------------------------------------------------------------------------
## Tools Used

Nikto - Web server scanner for 6,700+ known vulnerabilities and misconfigurations

Wapiti - Black-box web vulnerability scanner for injection flaws and file issues

Combined reporting - Server + application vulnerability correlation

Kali Linux - Testing environment with pre-installed scanning tools
-----------------------------------------------------------------------------------------------------
## Steps taken : 


