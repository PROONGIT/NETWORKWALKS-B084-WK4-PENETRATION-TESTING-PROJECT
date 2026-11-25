<div align="center">

# 🔐 Cybersecurity Lab - PENETRATION TESTING REPORT

**Real-world Penetration Testing Project**

</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.3-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  
  <img src="https://img.shields.io/badge/Skill-Reconnaissance%20&%20Footprinting-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Skill-Scanning%20&%20Network%20Discovery-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Zenmap%20v7.99-0070C0?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  
  
  
  <img src="https://img.shields.io/badge/Ver-John%20The%20Ripper%20v1.9-0070C0?style=flat-square&labelColor=000000" />
  
  <img src="https://img.shields.io/badge/Ver-Johnny%20v2.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Skill-Password%20Hacking-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Skill-Dictionary%20Attacks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Skill-Capture%20The%20Flag-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Skill-Hash%20Cracking-404040?style=flat-square&labelColor=C00000" />
  
  
  <img src="https://img.shields.io/badge/Networkwalks%20Tool-Hash%20Calculator-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Networkwalks%20Tool-Password%20Hacker-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/AZIAGBEDO%20KOKOU%20SODJINE%20-%20CCEP-C00000?style=flat-square" />
</p>

---

## 📌 Project Overview

This project is a real-world Penetration Testing Project structured in four milestonese (M1, M2, M3 and M4).

👉 M1 - Initial Access : Attack of the website and retrieval of 3 confidential patient PDF lab reports.

👉 M2 - Data Extraction : Cracking the encryption on all 3 retrieved files.

👉 M3 - Attack (cracking) : Finding staff salaries and shareholder details of the hospital.

👉 M4 - Pentest Report : Writing a professional penetration testing report for the client.

The project has a timeline of 5 days.

The client has provided written authorisation to conduct security testing on their web infrastructure.

---

##  ⚖️ Liability Disclaimer

This project is conducted in a controlled environment for educational purposes only. The target has been authorised for security testing by Networkwalks. These techniques must never be applied to any system without explicit written permission from the owner.

Do not use anything from here to break the law. The instructor, the authors and Networkwalks are not responsible for what you do with this knowledge. Every action you take is your own responsibility. Misuse can lead to criminal charges, heavy fines, loss of your job and a permanent record. In most countries unauthorised access is a crime even when nothing is damaged.

---

# 📘Penetration Testing Report

---

# 1. 🎯 Executive Summary

In the context of the Mediroza Hospital’s website `https://medirozahospital.com` security audit, we conducted a  security assessment to evaluate its security posture on November 23rd, 2026. The vulnerabilities assessment revealed security flaws that could expose sensitive information to unauthorized persons. We identified identified several significant weaknesses affecting the protection of sensitive business and patient information. 

The assessment demonstrated that confidential organizational data and protected patient health records are currently exposed. Multiple weaknesses across authentication controls and document protection mechanisms collectively increase the likelihood of unauthorized disclosure of sensitive information. The web platform's security posture is critically weak: independent vulnerabilities were each exploited in practice, and together they give full access to sensitive personal, medical and financial data. This puts the company’s business at risk, as well as its compliance with standards and regulations regarding personal and health data.

We recommend the immediate implementation of the following measures: 

Priority 1: Urgently (in 0–48 hours) ask developpers team to fix and enhance authentication mechanisms, remove public access to the database backup and treat all credentials in the backup as compromised. Rotate database, application, API and admin passwords and keys.

Priority 2: In a short term (1-2 weeks), strenghten the encryption of patient reports, delete the backup from the web root and store it in encrypted storage with restricted access or even offline, block the path at the web server level, review access logs for the backup, login endpoints and any anomalous queries to determine whether data was accessed by anyone other than authorized persons and audit team, activate the incident response and legal process, assess breach notification obligations to the data protection authority and affected individuals.

Priority 3: In a medium term (3-5 weeks), ensure authentication is hardened with CAPTCHA, multi-factor authentication, log and alert on repeated failures, implement system and data monitoring.

Priority 4: Ongoing schedule a full penetration test and re-test after remediation to validate fixes, run periodic vulnerability scans and annual security audits, maintain an incident response plan and conduct awareness training for staff.

Ultimately, the current website security does not meet the standards expected within an Information Security Management System (ISMS), especially in the health industry. Urgent corrective actions are essential to protect the company’s assets and significantly reduce data breach risks, in accordance with ISO 27001 regulatory standards.

---

# 2. 💎 Scope and Methodology

## 2.1 Project details

| Field | Detail |
|---|---|
|**Project Type** | Penetration Testing & Vulnerability Assessment|
|**Client Name**| Mediroza General Hospital|
|**Target**| `https://medirozahospital.com`|
|**Scope** |Full black-box penetration test. Identify vulnerabilities, exploit them to demonstrate real impact, and document all findings in a professional report.|
|**Rules**| Testing limited to the target domain only. No social engineering. No denial of service. No testing outside agreed scope.|
|**Authorization**| The client has provided written authorisation to conduct security testing on their web infrastructure.|
|**Timeline**| 5 days. Work independently.|

---

## 2.2 Report details

| Field | Detail |
|---|---|
| **Date** | 23 November 2026 |
| **Version** | 1.0.0 |
| **Author (Cybersecurity Professional)** | **AZIAGBEDO KOKOU SODJINE** |
| **Classification** | CONFIDENTIAL|
| **Reference standards** | Compliant with ISO 27001:2022 and PASSI reference standard (ANSSI)|
| **Client company** |Mediroza General Hospital|

---

## 2.3 Methodology

We demonstrated the impact of vulnerabilities in a concrete way, using a structured penetration testing methodology (PTES – Penetration Testing Execution Standard).

````text
Reconnaissance
      ↓
Enumeration
      ↓
Vulnerability Identification
      ↓
Manual Validation
      ↓
Controlled Exploitation
      ↓
Impact Assessment
      ↓
Evidence Collection
      ↓
Risk Rating
      ↓
Remediation
````

---

## 2.4 Tools Used

The table below lists each tool used in this report and its purpose.

| Tool | Purpose |
|---|---|
| Kali Linux  | Operating system used to perform the penetration testing activities|
| whois                | Find domain registration details (owner, dates, name servers).   |
| whatweb              | Fingerprint web technologies (server, CMS, plugins, IP).         |
| nslookup             | Resolve the domain name to its IP address using DNS.             |
| curl              | Read the HTTP response headers of the website & website.xml, robots.txt. |
| wafw00f              | Detect whether a Web Application Firewall protects the site.     |
| dnsrecon             | Enumerate all DNS records (NS, MX, SPF, TXT, SRV).               |
| nmap     | Scan the local subnet to find live hosts, IPs and MAC addresses. |
| Networkwalks Hash Calculator | Get the hash values of files  |
| Networkwalks Password Cracker | Crack password of files  |

---

# 3.  💎 Findings and Proof of Exploitation

---

## 3.1 Milestone 1 - Attack and patients reports getting

---

### 🫆 Footprinting & Reconnaissance

I performed reconnaissance against the `https://medirozahospital.com` website using Kali Linux tools: **Whois, WhatWeb, Nslookup, Curl, Wafw00f and DNSRecon**. Each tool was used to collect a different type of information about the target.

First, I used **WHOIS** to obtain publicly available registration information. The results provided no valuable information. 

---

![whois.png](/screenshots/whois.png)

---

I then used **WhatWeb** to identify technologies used by the website. The results identified **HTML5**, **LiteSpeed** and the IP address **199.188.201.16**. No versions of software exposed here.

Using **Nslookup**, I resolved the website name to its IP address. The provided result identified **199.188.201.16**.

I used **Curl** with the `-I` option to inspect the HTTP response headers. This provided **LiteSpeed** as server. No REST API endpoint exposed.

---

![whatweb.png](/screenshots/whatweb.png)

---

Next, I used **Wafw00f** to determine whether a Web Application Firewall was protecting the website. The result identified **LiteSpeed (LiteSpeed Technologies)**.

---

![wafw00f.png](/screenshots/wafw00f.png)

---

Finally, I used **DNSRecon** to enumerate DNS records. The results provided information relating to name servers and TXT records.

---

![dnsrecon.png](/screenshots/dnsrecon.png)

---

The outputs of all the above commands were saved in a txt file available at **`/output_files/footprinting.txt`**.

---

### 🔍 Ports Scanning with Nmap

I used **nmap** from my Kali Linux terminal to perform ports scanning on the target. The website's IP address is **`199.188.201.16`**). 

I scanned with the command : 

````bash
nmap -sV -sC 199.188.201.16
````

The results identified twelve active ports.

---

![scan_short_1.png](/screenshots/scan_short_1.png)

---

![scan_short_2.png](/screenshots/scan_short_2.png)

---

![scan_short_3.png](/screenshots/scan_short_3.png)

---

![scan_short_4.png](/screenshots/scan_short_4.png)

---

The output of this first scan is saved in a txt file available at **`/output_files/scan_short.txt`**.

---

I also full scanned with the command : 

````bash
nmap -A -p- -T4 199.188.201.16 -oN scan_full.txt 
````

The results identified twelve active ports.

---

![scan_full_1.png](/screenshots/scan_full_1.png)

---

![scan_full_2.png](/screenshots/scan_full_2.png)

---

The output of this second scan is saved in a txt file available at **`/outputs_files/scan_full.txt`**.

---

### Enumeration

I used `curl` to perform enumeration on the target with the following commands:

````bash
curl -s https://medirozahospital.com | grep -Eo 'href="[^"]+"' | sort -u
````

````bash
curl https://medirozahospital.com/sitemap.xml 
````

````bash
curl https://medirozahospital.com/robots.txt
````

---

![enumeration.png](/screenshots/enumeration.png)

---

The outputs of the commands used for enumeration were saved in a txt file that is available at **`/output_files/enumeration.txt`**.

I remarked information disclosure via **`robots.txt`**: paths that were not visible through normal navigation on the website had showed up. 

They were 3 key paths:

````text
https://medirozahospital.com/patient/
https://medirozahospital.com/staff/
https://medirozahospital.com/old/
````

Those are exposed entry points.

I entered them one by one in the browser.

---

#### /patient/

![patient.png](/screenshots/patient.png)

---

#### /staff/

![staff.png](/screenshots/staff.png)

---

#### /old/

![old.png](/screenshots/old.png)

---

The presence of a folder **/patient/reports** indicated that there would patient reports files in the **Patient Portal**.

I tried to gain the access with common usernames and passwords. I analyzed the behaviour of the authentication mechanisms.

---

#### wrong username error message

![username_wrong.png](/screenshots/username_wrong.png)

---

A trial with the default username `admin` got **Incorrect password**.

---

![admin.png](/screenshots/admin.png)

---

#### correct username error message

![username_correct.png](/screenshots/username_correct.png)

---

That behaviour lets guess which one of the credentials is wrong and helps a correct username even if the entered password is wrong.

Having a valid username could make the attack easier.

As many common passwords were failing, I opted for SQL injection.

Here again the behaviour of the authentication mechanisms was indiscreet. The error messages indicated the position of the wrong syntax in the SQL requests.

---

![sql_error_1.png](/screenshots/sql_error_1.png)

---

![sql_error_2.png](/screenshots/sql_error_2.png)

---

I gained the access by commenting the password requirement with the SQL injection.

---

![sql_correct.png](/screenshots/sql_correct.png)

---

![portal_accessed.png](/screenshots/portal_accessed.png)

---

I downloaded the 3 reports by clicking on the `download` buttons.

---

![reports_download.png](/screenshots/reports_download.png)

---

The downloaded encrypted reports PDF files are : **`patient_report_1.pdf`**, **`patient_report_2.pdf`** and **`patient_report_3.pdf`**. They are available in the folder **`/download/`**.

---

## 3.2 Milestone 2 - Cracking the encrypted files

---

### Calculating hash values

I analyzed the  encryption of the locked reports PDF files.

I used Networkwalks Hash Calculator and uploaded the files turn by turn. A crackable hash had been extracted in pdf2john or hashcat compatible format.

The hash values of each file were saved and are available in the **`/output_files/`** : **`patient_report_1.hash.txt`**, **`patient_report_2.hash.txt`** and **`patient_report_3.hash.txt`**.

---

![pdf1_hash.png](/screenshots/pdf1_hash.png)

---

![pdf2_hash.png](/screenshots/pdf2_hash.png)

---

![pdf3_hash.png](/screenshots/pdf3_hash.png)

---

### Cracking the passwords

I used Networkwalks Password Cracker over the 3 hash values.

---

![pdf1_crack.png](/screenshots/pdf1_crack.png)

---

![pdf2_crack.png](/screenshots/pdf2_crack.png)

---

![pdf3_crack_1.png](/screenshots/pdf3_crack_1.png)

---

The password cracking was not successful for the **`patient_report_3.hash.txt`** using the native wordlist of 100 words integrated to the Networkwalks tool.

I uploaded the Kali Linux wordlist of 14,344,379 words into the Networkwalks tool. I run the cracking again and that was successful.

---

![pdf3_crack.png](/screenshots/pdf3_crack.png)

---

### Contents recovering

I launched each of the encrypted reports PDF files. I entered the cracked passwords and validated. 

---

![pdf1_gap.png](/screenshots/pdf1_gap.png)

---

![pdf2_gap.png](/screenshots/pdf2_gap.png)

---

![pdf3_gap.png](/screenshots/pdf3_gap.png)

---

![pdf1_filled.png](/screenshots/pdf1_filled.png)

---

![pdf2_filled.png](/screenshots/pdf2_filled.png)

---

![pdf3_filled.png](/screenshots/pdf3_filled.png)

---

![pdf1_open.png](/screenshots/pdf1_open.png)

---

![pdf2_open.png](/screenshots/pdf2_open.png)

---

![pdf3_open.png](/screenshots/pdf3_open.png)

---

All the PDF files opened and their contents were recovered successfully.

---

## 3.3 Milestone 3 - Critical data exposure on the client server

---

I conducted a thorough analysis of everything retrieved so far. 

I tried to exploit /staff/ and /old/ found paths via enumeration.

### Exploiting /staff/ enumerated path

I entered common credentials in the fields of /staff/login.php. I also entered SQL injection requests.

No valuable result was found via the /staff/ revealed path.

---

![staff.png](/screenshots/staff.png)

---

![staff_login.png](/screenshots/staff_login.png)

---

### Exploiting /old/ enumerated path

I clicked and opened the file **`mediroza_db_backup_2019.sql`**.

![old.png](/screenshots/old.png)

---

The opened page showed the company's database backup data.

---

![backup_1.png](/screenshots/backup_1.png)

---

![backup_2.png](/screenshots/backup_2.png)

---

![backup_3.png](/screenshots/backup_3.png)

---

The exposed details were critical and sensitive data. They were business financial data and staff sensitive personal data. 

Specifically, the database details (name: **`mediroza_hr`**), confidential staff and shareholder records were clearly exposed.

I extracted  the salaries of all hospital employees and the shareholder details of the hospital.

I made a readable summary of the confidential data uncovered.

---

### Database and technical details

|Element|Details|
|----|----|
|Backup date: |2019-08-27 02:14:03|
|Backup name:|mediroza_db_backup_2019.sql|
|Backup type:|internal database backup|
|Contents:| confidential staff and shareholder records |
|Host: | localhost |
|Database name: | mediroza_hr|
|Company:| Mediroza General Hospital |
|Generated by: | Mediroza CMS 1.4.2 backup module|


---

### Salaries

ID (`id`)|Full Name (`full_name`)|Job Title (`job_title`)|Department (`department`)|Salary in ZAR (`monthly_salary_zar`)|Date Joined (`date_joined`)|
----|-------|-----------|--------|-----------|------------|
1|Dr. Rajesh Naidoo|Chief Pathologist|Diagnostics Lab|138000|2009-03-16|
2|Sarah Botha|Chief Financial Officer|Finance|152000|2011-07-01|
3|Dr. Johan van der Merwe|Medical Director|Management|160000|2007-01-22|
4|Dr. Anita Naicker|Consultant Cardiologist|Cardiology|132000|2012-09-10|
5|Dr. Ahmed Kara|Consultant Physician|Internal Medicine|128000|2013-02-18|
6|Dr. Yusuf Cassim|Senior Registrar|Emergency & Trauma|74000|2018-05-04|
7|Michael Roberts|HR Director|Human Resources|96000|2010-11-15|
8|Susan Pretorius|HR Officer|Human Resources|32000|2016-08-23|
9|Jameel Malik|IT Systems Administrator|IT|58000|2015-04-12|
10|Thabo Molefe|Network Engineer|IT|46000|2017-10-02|
11|Nomvula Khumalo|Registered Nurse|Emergency & Trauma|34000|2016-01-19|
12|Lerato Mokoena|Registered Nurse|Pediatrics|33000|2017-06-07|
13|Bongani Ndlovu|Registered Nurse|Cardiology|35000|2015-12-01|
14|Zanele Mahlangu|Nursing Sister|Theatre|42000|2013-03-25|
15|Kagiso Sithole|Pharmacist|Pharmacy|61000|2014-09-08|
16|Naledi Zulu|Pharmacy Assistant|Pharmacy|26000|2019-02-14|
17|Themba Nkosi|Radiographer|Radiology|44000|2016-07-30|
18|Palesa Radebe|Radiographer|Radiology|43000|2017-04-11|
19|Deepak Pillay|Lab Technologist|Diagnostics Lab|41000|2015-05-20|
20|Kavitha Govender|Lab Technician|Diagnostics Lab|35000|2018-08-06|
21|Dr. Suresh Moodley|Consultant Radiologist|Radiology|130000|2012-02-28|
22|Dr. Fatima Patel|Pediatrician|Pediatrics|118000|2013-10-17|
23|Nisha Singh|Physiotherapist|Rehabilitation|48000|2016-11-09|
24|Dr. Vikram Chetty|Anaesthetist|Theatre|135000|2011-06-13|
25|David Smith|Facilities Manager|Operations|52000|2014-01-27|
26|Karen O'Connor|Billing Administrator|Finance|29000|2018-03-19|
27|James Wilson|Security Supervisor|Operations|27000|2019-09-02|
28|Linda Fourie|Receptionist|Front Office|19000|2020-02-10|
29|Peter van Wyk|Procurement Officer|Supply Chain|38000|2015-08-24|
30|Andile Mbeki|Ward Clerk|Administration|21000|2019-11-05|

---

### Shareholders

|ID (`id`)|Shareholder Name (`shareholder_name`)|Share Percent (`share_percent`)|Shares Held (`shares_held`)|Share Class (`share_class`)|
-----|-------------------|------------------|---------|---------|
1|Dr. Rajesh Naidoo|18.0|180000|Ordinary|
2|Cedar Health Holdings (Pty) Ltd|15.0|150000|Ordinary|
3|Dr. Johan van der Merwe|12.0|120000|Ordinary|
4|Reddy Family Trust|11.0|110000|Ordinary|
5|Thabo Molefe|10.0|100000|Ordinary|
6|Sarah Botha|9.0|90000|Ordinary|
7|Dr. Ahmed Kara|8.0|80000|Preferential|
8|Naledi Zulu|7.0|70000|Ordinary|
9|Michael Roberts|6.0|60000|Ordinary|
10|Dr. Vikram Chetty|4.0|40000|Preferential|


---

# 4. 💎 Risk Rating

Based on the information collected during the penetration testing activities, I identified the following potential risks.

FIRST (Forum of Incident Response and Security Teams)
OWASP Top 10 - 2025

| # | Finding | Audit severity | CVSS v3.1 base score | OWASP Top 10:2021 | Impact |
| --- | --- | --- | --- | --- | --- |
| 1 | **Sensitive database backup exposed.** `robots.txt` discloses the `/old` path, which publicly serves a database backup containing personal data and the company's economic and financial status. | Critical | 7.5 (High) `CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N` | A05:2021 Security Misconfiguration; A01:2021 Broken Access Control | Direct, unauthenticated data breach. No exploitation skill needed. |
| 2 | **SQL injection and weak authentication on the patient portal.** The login is vulnerable to SQL injection. Error messages leak information on each failed attempt, and there is no limit on login attempts (no lockout or rate limiting). | Critical | 7.5 (High) `CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N` | A03:2021 Injection; A07:2021 Identification and Authentication Failures | Authentication bypass and unauthorized access to confidential patient reports. Brute-force and enumeration attacks are possible. |
| 3 | **Weak passwords protecting encrypted health reports.** Reports are encrypted, but protected by trivial passwords (`123456`, `password`) and a third password found in the public `rockyou.txt` wordlist. Hashes were recovered and cracked with a simple dictionary attack using online tools. | High | 7.5 (High) `CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N` | A02:2021 Cryptographic Failures; A07:2021 Identification and Authentication Failures | Encryption is ineffective in practice. Report contents were fully readable. |



| **\#** | **Risk / Finding**                           | **Evidence / Observation**                                  | **Potential Impact**                                                                                            | **Risk Level** |
|--------|----------------------------------------------|-------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|----------------|
| 1      | Web technology information exposed           | WhatWeb identified WordPress and WP Download Manager        | Attackers may use exposed technology/version information to identify software requiring further security review | **🟠 Medium**   |
| 2      | Server IP address identifiable               | Nslookup resolved the domain to `192.232.216.135`           | Provides information about the network location of the web service                                              | **🟡 Low**      |
| 3      | HTTP technical information exposed           | Curl returned HTTP response headers and exposed `/wp-json/` | May assist technology fingerprinting and further enumeration                                                    | **🟡 Low**      |
| 4      | WAF technology identifiable                  | Wafw00f identified ModSecurity (SpiderLabs)                 | Reveals information about the web application’s security architecture                                           | **🟡 Low**      |
| 5      | DNS infrastructure information exposed       | DNSRecon identified DNS, mail and service-related records   | DNS information can help build a broader infrastructure profile                                                 | **🟠 Medium**   |
| 6      | Multiple live hosts visible on local network | Zenmap identified three live hosts in the example network    | Unknown or unauthorized devices may potentially be present on a network                                         | **🟠 Medium**   |

**Risk level key:** 🔴 Critical 🟠 Medium 🟡 Low

The risks above are observations from the footprinting and scanning exercises, not confirmed vulnerabilities.

The practical exercises primarily involved information gathering and host discovery. No exploitation or vulnerability validation was performed as part of these two modules.

Therefore, the presence of information such as a software version, IP address or DNS record does not by itself mean that the system is vulnerable. Further authorized security testing would be required to confirm any actual vulnerability.

---

# 5. 💎 Recommendations and Remediation

Based on the observations from these activities, I recommend the following security improvements:

1.  **Review publicly exposed technology information**  
    Organizations should regularly review what information about their web technologies, CMS is publicly visible.

2.  **Keep software updated**  
    CMS platforms, plugins and other web technologies should be regularly updated and reviewed against current security advisories.

3.  **Review HTTP headers**  
    HTTP response headers should be reviewed to determine whether unnecessary technical information is being exposed.

4.  **Review DNS records regularly**  
    DNS records should be checked periodically to ensure that only required information and services are publicly exposed.

5.  **Properly configure and monitor the WAF**  
    Keep the WAF (ModSecurity) enabled and tuned, since it already blocks naive attacks.

6.  **Perform regular internal network discovery**  
    Organizations should periodically scan their own networks to identify active devices.

7.  **Investigate unknown devices**  
    Any unexpected device discovered during network scanning should be investigated and verified.

8.  **Maintain network documentation**  
    Network topology and device information should be documented and updated regularly.

9.  **Perform security testing with authorization**  
    Reconnaissance and scanning should only be performed against systems and networks where appropriate authorization has been provided.

---

# 6. Conclusion

During Week 2 of my Cybersecurity & Ethical Hacking internship, I completed practical activities covering footprinting, reconnaissance and network scanning.

In the footprinting activity, I used six Kali Linux tools to collect information about the target domain. I demonstrated how WHOIS can provide domain information, WhatWeb can identify web technologies, Nslookup can resolve domain names, Curl can inspect HTTP headers, Wafw00f can identify a WAF, and DNSRecon can provide additional DNS information.

In the network scanning activity, I used Zenmap to identify my local network configuration and discover active hosts. I also collected IP and MAC address information and created a network topology.

The exercises showed that information gathering is an important part of cybersecurity. Even before attempting to exploit a system, a security professional can gather a significant amount of information on an environment by carefully analyzing publicly available information and network responses.

I also demonsrated that technical findings should be documented clearly. A good cybersecurity report should explain what was performed, what was discovered, what the observation means, what risk it may create, and what can be done to reduce that risk.

Finally, I demonstrated that reconnaissance and scanning must always be performed within an authorized scope. These activities were completed as part of the Networkwalks Cybersecurity internsgip program.

---

# 7. Evidences Collected

---

## 📄Used commands and collected files

*The outputs of executed commands are saved in files and screenshots are collected as evidences during the activities.*

The outputs files and screenshots are respectively stored in the **`/output_files/`** and **`/screenshots/`** folders.

| Command | Screenshot | Output File| Comments |
|----------|-------|-------|--------|
|  | ├ 📂screenshots|├ 📂output_files|Folders|
| `whois www.medirozahospital.com` | ├─ [whois.png](/screenshots/whois.png)| ├─ [footprinting.txt](/output_files/footprinting.txt)  |  Looked for registration details  
|  `whatweb www.medirozahospital.com`|├─ [whatweb.png](/screenshots/whatweb.png) | ├─ [footprinting.txt](/output_files/footprinting.txt) | Inspected used technologies | 
|   `nslookup www.medirozahospital.com` | ├─ [whatweb.png](/screenshots/whatweb.png)| ├─ [footprinting.txt](/output_files/footprinting.txt) | Resolved the website name to its IP address    |
| `curl -I www.medirozahospital.com`|├─ [whatweb.png](/screenshots/whatweb.png) | ├─ [footprinting.txt](/output_files/footprinting.txt) | Inspected HTTP response headers  |                 
| `wafw00f www.medirozahospital.com` |├─ [wafw00f.png](/screenshots/wafw00f.png) | ├─ [footprinting.txt](/output_files/footprinting.txt)  | Determined Web Application Firewall    |              
| `dnsrecon -d www.medirozahospital.com`|├─ [dnsrecon.png](/screenshots/dnsrecon.png) | ├─ [footprinting.txt](/output_files/footprinting.txt) | Enumerated DNS records|              
|  `nmap -sV -sC 199.188.201.16` |├─ [scan_short_1.png](/screenshots/scan_short_1.png) | ├─ [scan_short.txt](/output_files/scan_short.txt) | Scanned ports |
|  `nmap -A -p- -T4 199.188.201.16 -oN scan_full.txt` |├─ [scan_full_1.png](/screenshots/scan_full_1.png) | ├─ [scan_full.txt](/output_files/scan_full.txt) | Scanned ports fully and saved output in scan_full.txt |
| `curl -s https://medirozahospital.com ...`|├─ [enumeration.png](/screenshots/enumeration.png)| ├─ [enumeration.txt](/output_files/enumeration.txt) | Discovered publicly referenced application routes  | 
| `curl https://medirozahospital.com/sitemap.xml`|├─ [enumeration.png](/screenshots/enumeration.png)| ├─ [enumeration.txt](/output_files/enumeration.txt) | Discovered indexed pages  | 
| `curl https://medirozahospital.com/robots.txt`|├─ [enumeration.png](/screenshots/enumeration.png) | ├─ [enumeration.txt](/output_files/enumeration.txt) | Discovered hidden directories | 

---

## 🪧 Milestones and delivrables

|Milestone|Delivrables|
|---------|---------|
|M1|[portal_accessed.png](/screenshots/portal_accessed.png), [patient_report_1.pdf](/download/patient_report_1.pdf), [patient_report_2.pdf](/download/patient_report_2.pdf), [patient_report_3.pdf](/download/patient_report_3.pdf)|
|M2|[pdf1_crack.png](/screenshots/pdf1_crack.png), [pdf1_open.png](/screenshots/pdf1_open.png), [pdf2_crack.png](/screenshots/pdf2_crack.png), [pdf2_open.png](/screenshots/pdf2_open.png), [pdf3_crack.png](/screenshots/pdf3_crack.png), [pdf3_open.png](/screenshots/pdf3_open.png)|
|M3|[backup_1.png](/screenshots/backup_1.png), [backup_2.png](/screenshots/backup_2.png), [backup_3.png](/screenshots/backup_3.png), [Database and technical details](#database-and-technical-details), [Salaries](#salaries), [Shareholders](#shareholders)|

---

## Project Short Video

We recorded a short video of the project completion.

https://github.com/user-attachments/assets/11905e7e-e119-48e9-9f67-ddfa2a335e24

---

-End-

---

# 👤 Author

**AZIAGBEDO KOKOU SODJINE**\
Cybersecurity Professional B084

LinkedIn: https://www.linkedin.com/in/kokou-sodjin%C3%A8-aziagbedo-434b2949

---

## 📌 Project Information

**Program Name:** Cybersecurity at Networkwalks | **Week:** 04 | **Project:** Real-world Penetration Testing - Mediroza Hospital | **Repository:** GitHub

