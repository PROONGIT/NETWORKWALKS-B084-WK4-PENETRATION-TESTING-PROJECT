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

| Field | Detail |
|---|---|
| **Pentester Name (Cybersecurity Professional)** | **AZIAGBEDO KOKOU SODJINE** |
| **Program/Batch** | B084-Networkwalks |
| **Date** | 23 November 2026 |
| **Modules completed** | W2-PM1 (Multiple Kali Tools)<br>W2-PM5 (Zenmap Scanning) |
| **Scope [Client/Target]** | 1. Networkwalks (secured written permission already)<br>2. My own local LAN Network |
| **Permission secured from client?** | Yes |
| **Phases covered** | **Phase 1:** Reconnaissance & Footprinting<br>**Phase 2:** Scanning & Network Discovery<br>**Phase 3-5:** In Progress |



## Tools Used

The table below lists each tool used in this report and its purpose.

| Tool | Purpose |
|---|---|
| Kali Linux & Windows | Operating systems used in the lab for footprinting and reconnaissance activities|
| WHOIS                | Find domain registration details (owner, dates, name servers).   |
| whatweb              | Fingerprint web technologies (server, CMS, plugins, IP).         |
| nslookup             | Resolve the domain name to its IP address using DNS.             |
| curl -I              | Read the HTTP response headers of the website.                   |
| wafw00f              | Detect whether a Web Application Firewall protects the site.     |
| dnsrecon             | Enumerate all DNS records (NS, MX, SPF, TXT, SRV).               |
| Zenmap (Nmap GUI)    | Scan the local subnet to find live hosts, IPs and MAC addresses. |
| Linux & Windows CMD | Local IP and MAC address identification / confirmation            |




This report covers footprinting the networkwalks.com domain using multiple Kali Linux tools (W2-PM1) and scanning my own local network with Zenmap (W2-PM5). One module covers the footprinting phase and the other covers the scanning phase, so together they show how an attacker moves from gathering public information to mapping live hosts on a network. These activities are part of the Week 2 of my internship program at Networkwalks.

All commands were run in Kali Linux (footprinting and scanning). Every step below includes the exact command used, the result I observed, a screenshot as evidence, and a short note on why the finding matters from an attacker's point of view. The commands outputs are also saved in text files that are available in "/outputs_files" as well as the zenmap topology pdf file.

---

# 3.  💎 Findings and Proof of Exploitation

## 3.1 🫆 Footprinting & 🔍 Reconnaissance

I performed reconnaissance against the `networkwalks.com` domain using six Kali Linux tools: **WHOIS, WhatWeb, Nslookup, Curl, Wafw00f and DNSRecon**. Each tool was used to collect a different type of information about the target.

First, I used **WHOIS** to obtain publicly available domain registration information and identify the domain’s name servers. The results provided information about the domain registration and hosting infrastructure.

I then used **WhatWeb** to identify technologies used by the website. The results identified **WordPress 7.1.4**, **WordPress Download Manager 3.3.76**, **Bootstrap 7.1.4** and **JQuery 3.7.1**, along with other informations exposed by the website.

Using **Nslookup**, I resolved the domain name to its IP address. The provided result identified **192.232.216.135**.

I used **Curl** with the `-I` option to inspect the HTTP response headers. This provided additional information about the web application and exposed the WordPress REST API endpoint `/wp-json/`.

Next, I used **Wafw00f** to determine whether a Web Application Firewall was protecting the website. The result identified **ModSecurity (SpiderLabs)**.

Finally, I used **DNSRecon** to enumerate DNS records. The results provided information relating to name servers, mail servers, SPF/TXT records, service records and DNS software information.

---

## 3.2 Network Scanning with Zenmap

For the second activity, I launched the GUI of **Zenmap** from my Kali Linux. I used Zenmap to perform network discovery on my local network. The practical required me to identify my local IP address and subnet, discover live hosts, identify their IP and MAC addresses, and generate a network topology.

I first used the `ifconfig -a` command on the Kali VM to identify my local IP address (**`10.0.0.2`**) and LAN subnet (**`10.0.0.0/24`**). I then entered the subnet into Zenmap and selected **`Ping Scan`** to identify active hosts. 

And I scanned with the command : 

````bash
nmap -sn 10.0.0.0/24
````

The results identified three live hosts:

- `10.0.0.1`
- `10.0.0.7`
- `10.0.0.2`

The results also included two MAC addresses.

|Live Hosts       | IP Address | MAC Address | Local VM Name |
|-----------------|------------|-------------|---------------|
|QEMU virtual NIC | 10.0.0.1 | 52:54:00:12:35:00 | Gateway |
|Oracle VirtualBox virtual NIC | 10.0.0.7| 08:00:27:CE:C9:16 | Windows7 VM |
|Zenmap Host  | 10.0.0.2 | 08:00:27:08:12:48| KALI_LINUX VM |

After completing the scan, I opened the **Topology** section in Zenmap, enabled the legend and saved the network topology in PDF format. The topology pdf file is available at /outputs_files/9_topology.pdf

---

## Salaries

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

## Shareholders

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

Based on the information collected during the footprinting and network scanning activities, I identified the following potential risks.

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
    Organizations should regularly review what information about their web technologies, CMS and plugins is publicly visible.

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

## 📄Commands and collected files

*The outputs of executed commands are saved in files and screenshots are collected as evidences during the activities.*

The outputs files and screenshots are respectively stored in the **`/outputs_files/`** and **`/screenshots/`** folders.

---

### The contents of the /outputs_files/ and /screenshots/ folders 

| Command | Screenshot | Output File| Comments |
|----------|-------|-------|--------|
|  | ├ 📂screenshots|├ 📂outputs_files|Folders|
| `whois networkwalks.com` | ├─ [1_whois.png](/screenshots/1_whois.png)| ├─ [1_whois.txt](/outputs_files/1_whois.txt)  |  Found domain registration details  
|  `whatweb networkwalks.com`|├─ [2_whatweb.png](/screenshots/2_whatweb.png) | ├─ [2_whatweb.txt](/outputs_files/2_whatweb.txt) | Identified used technologies | 
|   `nslookup networkwalks.com` | ├─ [3_nslookup.png](/screenshots/3_nslookup.png)| ├─ [3_nslookup.txt](/outputs_files/3_nslookup.txt) | Resolved the domain name to its IP address    |
| `curl -I https://networkwalks.com`|├─ [4_curl.png](/screenshots/4_curl.png) | ├─ [4_curl.txt](/outputs_files/4_curl.txt) | Inspected HTTP response headers  |                 
| `wafw00f networkwalks.com` |├─ [5_wafw00f.png](/screenshots/5_wafw00f.png) | ├─ [5_wafw00f.txt](/outputs_files/5_wafw00f.txt)  | Determined Web Application Firewall    |              
| `dnsrecon -d networkwalks.com`|├─ [6_dnsrecon.png](/screenshots/6_dnsrecon.png) | ├─ [6_dnsrecon.txt](/outputs_files/6_dnsrecon.txt) | Enumerated DNS records|              
|  `nmap -sn 10.0.0.0/24` |├─ [7_zenmap.png](/screenshots/7_zenmap.png) | ├─ [7_zenmap.txt](/outputs_files/7_zenmap.txt) | Scanned local network |
| `ifconfig -a` |├─ [8_ifconfig-a.png](/screenshots/8_ifconfig-a.png) | ├─ [8_ifconfig-a.txt](/outputs_files/8_ifconfig-a.txt) | Found local VM MAC address |   
| `Topology -> Save Graphic` |├─ [9_topology.png](/screenshots/9_topology.png) | ├─ [9_topology.pdf](/outputs_files/9_topology.pdf)  | Drew the network topology |
| `ipconfig /all` | └─ [ipconfig_all.png](/screenshots/ipconfig_all.png) | └─ [ipconfig_all.txt](/outputs_files/ipconfig_all.txt) | Confirmed Windows VM's MAC and IP addresses |   

---

## 📷Screenshots Gallery

*Screenshots collected as evidence during the activities.*

---

### whois

![whois output](/screenshots/1_whois.png)

---

### whatweb

![whatweb output](/screenshots/2_whatweb.png)

---

### nslookup

![nslookup output](/screenshots/3_nslookup.png)

---

### curl

![curl output](/screenshots/4_curl.png)

---

### wafw00f

![wafw00f output](/screenshots/5_wafw00f.png)

---

### dnsrecon

![dnsrecon output](/screenshots/6_dnsrecon.png)

---

### zenmap scan

![zenmap output](/screenshots/7_zenmap.png)

---

### ifconfig

![loacal_mac output](/screenshots/8_ifconfig-a.png)

---

### zenmap topology

![Zenmap scan and topology](/screenshots/9_topology.png)

---

### ipconfig

![windows_mac output](/screenshots/ipconfig_all.png)

---

## Project Short Video

We recorded a short video of the project completion.

https://github.com/user-attachments/assets/52be1bf5-5ebd-4a3c-bce6-dbcb8a2232c7

---

-End-

---

# 👤 Author

**AZIAGBEDO KOKOU SODJINE**\
Cybersecurity Professional B084

LinkedIn: https://www.linkedin.com/in/kokou-sodjin%C3%A8-aziagbedo-434b2949

---

## 📌 Project Information

**Program Name:** Cybersecurity at Networkwalks | **Week:** 02 | **Project:** Footprinting & Reconnaissance Attacks With Multiple KALI Tools | **Repository:** GitHub

