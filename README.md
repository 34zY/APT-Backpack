# APT-Backpack
Most common used CVE's by APT, legitimate RAT and other tools used by adversary

## CVE's

- CVE-2019-11510 (Pulse Connect Secure 8.2 8.3 9.0)          **Unauth file read**          
- CVE-2019-19781 (Citrix ADC & Gateway)                      **Directory Traversal**
- CVE-2020-5902  (F5 Big IP)                                 **RCE**
- CVE-2021-1497  (Cisco HyperFlex HX)                        **Unauth Command injection**
- CVE-2021-20090 (Buffalo WSR-2533DHP2 WSR-2533DHP3)         **Unauth RCE**
- CVE-2021-22006 (Vmware vCenter Server)                     **Authentication bypass**
- CVE-2021-22205 (GitLab CE/EE)                              **RCE**
- CVE-2021-26084 (Atlassian Confluence)                      **Unauth RCE**
- CVE-2021-26855 (Microsoft Exchange Server)                 **RCE**
- CVE-2021-26857 (Microsoft Exchange Server)                 **RCE**
- CVE-2021-26858 (Microsoft Exchange Server)                 **RCE**
- CVE-2021-26865 (Microsoft Exchange Server)                 **RCE**
- CVE-2021-36260 (Hikvision)                                 **Command Injection**
- CVE-2021-40539 (ManageEngine ADSelfService Plus)           **API Auth bypass** -> **RCE** 
- CVE-2021-41773 (Apache HTTP Server 2.4.49)                 **Path Traversal**
- CVE-2021-42237 (Sitecore XP 7.5)                           **Deserialisation** -> **RCE**
- CVE-2021-44228 (Apache Log4j)                              **RCE**
- CVE-2021-40444 (Microsoft Office)                          **RCE**
- CVE-2022-1388  (F5 BIG-IP)                                 **RCE**
- CVE-2022-24112 (Apache APISIX 2.12.1)                      **RCE**
- CVE-2022-26134 (Atlassian Confluence)                      **RCE**

## Legitimate RAT (Remote Administration Tools) & Servers sockets

- Ammyy admin client v3 (windows) (This is caught by many defenses)
- Ngrok client (windows/linux)

## Exploitation 

- Mimikatz (Source code)
- Sysinternals suite
- PSTools

## Exfiltration

- XXD static (windows)

## Phishing

- Office document with warnings (enable content)

## Reverse shell

- Ncat OPENBSD (Not caught by Microsoft Defender EDR)

*Use it rightly, i'm not resposible about any bad use of this pack*
