# Winjit Daily TI Digest — 2026-11-11

_Auto-generated. Window: last ~24h. Fetched at 2026-11-11T10:33:29.199213+00:00Z_

**At a glance:** 6 new KEV · 143 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 0 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-124194 | Microsoft | Office | Microsoft Office Outlook Missing User Interaction for Potentially Unsafe Action Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-111793 | Openwave Messaging Limited | Webtop Media Transcoder | Openwave Messaging Limited Webtop Media Transcoder Incorrect Resource Transfer Between Spheres Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-20320 | Cisco | BroadWorks | Cisco BroadWorks Improper Restriction of XML External Entity Reference Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-111560 | Barracuda Networks | Multiple Products | Barracuda Networks Multiple Products OS Command Injection Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-116606 | Barracuda Networks | Barracuda Email Security Gateway (ESG) | Barracuda Networks Email Security Gateway (ESG) Authentication Bypass Using an Alternate Path or Channel Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-125350 | Google | Chromium | Google Chromium Use-After-Free Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-125086 | 10.0 | 0.6% | A vulnerability has been found in D-Link M60 1.12.B01. Impacted is the function system of the file /etc/emDaemon/mosquitto.conf of the component emDaemon MQTT Broker. Such manipulation leads to hard-c |
| CVE-2026-120002 | 9.9 | n/a | Incorrect authorization in Microsoft Office SharePoint allows an authorized attacker to elevate privileges over a network. |
| CVE-2026-125370 | 9.8 | 0.7% | Kubero 3.0.0 through 3.1.1 contains an authentication bypass vulnerability that allows unauthenticated remote attackers to forge administrative JWTs by using a hardcoded fallback signing secret when J |
| CVE-2026-125383 | 9.8 | 0.8% | INDOTALENT WHMS (Asp.Net-Core-Inventory-Order-Management-System) before 10.20261109 contains an authentication bypass vulnerability caused by a hard-coded JWT signing key, issuer and audience in appse |
| CVE-2026-89324 | 9.8 | n/a | The Basel Post Types plugin for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 1.18. The vulnerability exists because a missing-quotes coding error in the defin |
| CVE-2026-126542 | 9.8 | n/a | WWBN AVideo 6.5 through 29.7.1 contains an authentication bypass vulnerability that allows unauthenticated attackers to log in as any user via Hybridauth social login display names. Attackers can set  |
| CVE-2026-120779 | 9.6 | n/a | Improper control of generation of code ('code injection') in Visual Studio Code allows an unauthorized attacker to execute code over a network. |
| CVE-2026-121904 | 9.6 | n/a | Adobe Connect is affected by a stored Cross-Site Scripting (XSS) vulnerability that could be abused by a low-privileged attacker to inject malicious scripts into vulnerable form fields. Malicious Java |
| CVE-2026-60043 | 9.3 | 0.4% | An unauthenticated remote attacker can perform a XSS attack on a logged in backend user allowing for execution of multiple critical system actions. This could allow an attacker to shutdown the server  |
| CVE-2026-121355 | 9.1 | n/a | Adobe Connect is affected by an Incorrect Authorization vulnerability that could result in privilege escalation. An attacker could exploit this vulnerability to gain elevated access to sensitive infor |
| CVE-2026-80095 | 9.0 | n/a | Improper neutralization of input during web page generation ('cross-site scripting') in Microsoft Office SharePoint allows an authorized attacker to elevate privileges over a network. |
| CVE-2026-125406 | 8.8 | 0.2% | Ettercap through 0.8.4.1 contains a stack buffer underwrite vulnerability in the telnet dissector in src/dissectors/ec_telnet.c that decrements the output pointer on backspace without a lower bound ch |
| CVE-2026-11316 | 8.8 | n/a | A out-of-bounds write vulnerability exists in the dr_wav drwav__read_cue_to_metadata_obj functionality of dr_libs (version(s): 0.14.5). A specially crafted .wav file can lead to an out-of-bounds write |
| CVE-2026-119908 | 8.8 | n/a | Integer underflow (wrap or wraparound) in Windows Storage Spaces Controller allows an unauthorized attacker to execute code over a network. |
| CVE-2026-119916 | 8.8 | n/a | Heap-based buffer overflow in Windows Input System allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119925 | 8.8 | n/a | Out-of-bounds read in Windows Text Services Framework allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119934 | 8.8 | n/a | Double free in Remote Desktop Client allows an unauthorized attacker to execute code over a network. |
| CVE-2026-119950 | 8.8 | n/a | Heap-based buffer overflow in Windows Print Spooler Components allows an unauthorized attacker to elevate privileges over a network. |
| CVE-2026-119969 | 8.8 | n/a | Heap-based buffer overflow in Graphic Fonts allows an unauthorized attacker to execute code over a network. |
| CVE-2026-119975 | 8.8 | n/a | Improper neutralization of input during web page generation ('cross-site scripting') in Visual Studio Code allows an unauthorized attacker to execute code over a network. |
| CVE-2026-119983 | 8.8 | n/a | Server-side request forgery (ssrf) in Visual Studio Code allows an unauthorized attacker to bypass a security feature over a network. |
| CVE-2026-119986 | 8.8 | n/a | Heap-based buffer overflow in Microsoft Office Excel allows an unauthorized attacker to execute code over a network. |
| CVE-2026-120001 | 8.8 | n/a | Heap-based buffer overflow in Microsoft Office PowerPoint allows an unauthorized attacker to execute code over a network. |
| CVE-2026-120003 | 8.8 | n/a | Heap-based buffer overflow in Microsoft Office allows an unauthorized attacker to execute code over a network. |
| CVE-2026-120005 | 8.8 | n/a | Heap-based buffer overflow in Microsoft Office PowerPoint allows an unauthorized attacker to execute code over a network. |
| CVE-2026-121663 | 8.8 | n/a | Incomplete list of disallowed inputs in Visual Studio Code allows an unauthorized attacker to bypass a security feature over a network. |
| CVE-2026-121665 | 8.8 | n/a | Trust boundary violation in Visual Studio Code allows an unauthorized attacker to bypass a security feature over a network. |
| CVE-2026-85923 | 8.8 | n/a | Authorization bypass through user-controlled key in Azure DevOps Server allows an authorized attacker to elevate privileges over a network. |
| CVE-2026-88176 | 8.8 | n/a | Missing authorization in Microsoft Office SharePoint allows an authorized attacker to elevate privileges over a network. |
| CVE-2026-70003 | 8.7 | n/a | Improper verification of cryptographic signature in JDBC Driver for SQL Server allows an unauthorized attacker to bypass a security feature over a network. |
| CVE-2026-122102 | 8.7 | n/a | Adobe Connect is affected by a stored Cross-Site Scripting (XSS) vulnerability that could be abused by a low-privileged attacker to inject malicious scripts into vulnerable form fields. Malicious Java |
| CVE-2026-113557 | 8.6 | n/a | Audition is affected by an Improper Input Validation vulnerability that could result in arbitrary code execution in the context of the current user. An attacker could exploit this vulnerability to exe |
| CVE-2026-119985 | 8.3 | n/a | Incorrect authorization in Visual Studio Code allows an unauthorized attacker to execute code over a network. |
| CVE-2026-120780 | 8.3 | n/a | Improper access control in Visual Studio Code allows an unauthorized attacker to execute code over a network. |
| CVE-2026-120513 | 8.2 | 0.5% | The Everest Forms – Contact Form, Payment Form, Quiz, Survey & Custom Form Builder with AI plugin for WordPress is vulnerable to file deletion due to insufficient file path validation in the remove_cs |
| CVE-2026-109097 | 8.2 | n/a | A vulnerability has been identified in ROS# (All versions < V2.3.1). Affected systems do not properly escape text of message definition files. This could allow an attacker that is able to pass a craft |
| CVE-2026-119989 | 8.2 | n/a | Improper neutralization of special elements used in a command ('command injection') in Azure Pipelines allows an authorized attacker to execute code over a network. |
| CVE-2026-125358 | 8.1 | 0.2% | Universal-modder before commit e88f6876745427321eb755ebc98276063a962d8a contains a missing WebSocket Origin validation vulnerability in the HostLink class of its passthrough example mods that allows r |
| CVE-2026-125401 | 8.1 | 0.4% | Ettercap through 0.8.4.1 contains a heap buffer overflow vulnerability in gg_get_version() in src/dissectors/ec_gg.c that writes up to 44 bytes into a 30-byte allocation. Remote attackers can send Gad |
| CVE-2026-125402 | 8.1 | 0.3% | Ettercap through 0.8.4.1 contains a heap out-of-bounds read vulnerability in sslw_get_clienthello_sni() in src/ec_sslwrap.c that trusts the unchecked 16-bit SNI length field. Network-adjacent attacker |
| CVE-2026-125405 | 8.1 | 0.3% | Ettercap through 0.8.4.1 contains an out-of-bounds read vulnerability in Parse_NTLM_Auth() in src/dissectors/ec_http.c due to unvalidated NTLM message offsets. Attackers can send a crafted HTTP Author |
| CVE-2026-76877 | 8.1 | 0.3% | The WPML Multilingual CMS plugin for WordPress is vulnerable to Authentication Bypass via Race Condition in versions up to, and including, 4.9.7. This is due to the `process_iframe_request` function's |
| CVE-2026-119945 | 8.1 | n/a | Use after free in Windows Modern Device Management (MDM) allows an unauthorized attacker to execute code over a network. |
| CVE-2026-119951 | 8.1 | n/a | Use after free in Windows Deployment Services allows an unauthorized attacker to execute code over a network. |
| CVE-2026-119952 | 8.1 | n/a | Observable timing discrepancy in Windows Schannel allows an unauthorized attacker to execute code over a network. |
| CVE-2026-119961 | 8.1 | n/a | Concurrent execution using shared resource with improper synchronization ('race condition') in Windows Internet Information Services allows an unauthorized attacker to execute code over a network. |
| CVE-2026-119962 | 8.1 | n/a | Double free in Windows Cred SSProvider Protocol allows an unauthorized attacker to execute code over a network. |
| CVE-2026-119963 | 8.1 | n/a | Double free in Windows Message Queuing allows an unauthorized attacker to execute code over a network. |
| CVE-2026-119964 | 8.1 | n/a | Double free in Windows Message Queuing allows an unauthorized attacker to execute code over a network. |
| CVE-2026-119967 | 8.1 | n/a | Use after free in Windows Message Queuing Queue Manager allows an unauthorized attacker to execute code over a network. |
| CVE-2026-126539 | 8.1 | n/a | Directus before 12.1.0 contains an authorization bypass vulnerability that allows unauthenticated attackers to skip permission checks by sending a failed auth message on public-mode WebSocket connecti |
| CVE-2026-126541 | 8.1 | n/a | WWBN AVideo through 29.7.1 contains a missing authorization vulnerability in Live plugin restream endpoints that allows authenticated streamers to obtain other users' stream keys by supplying arbitrar |
| CVE-2026-111190 | 8.1 | n/a | The ARForms plugin for WordPress is vulnerable to arbitrary file upload in all versions up to, and including, 7.2.4 via its form file-upload handler. The name of the stored file is taken from an attac |
| CVE-2026-122164 | 8.0 | n/a | Weak authentication in Windows Kerberos allows an authorized attacker to elevate privileges over a network. |
| CVE-2026-88187 | 8.0 | n/a | Heap-based buffer overflow in Windows Bluetooth A2DP driver allows an authorized attacker to elevate privileges over an adjacent network. |
| CVE-2026-88240 | 8.0 | n/a | Heap-based buffer overflow in Windows DHCP Client allows an authorized attacker to elevate privileges over an adjacent network. |
| CVE-2026-94513 | 8.0 | n/a | Heap-based buffer overflow in SQL Server allows an authorized attacker to elevate privileges over a network. |
| CVE-2026-125742 | 7.8 | n/a | 7-Zip before 26.06 contains a heap out-of-bounds write vulnerability in the LZX decoder that lets attackers corrupt memory when a continuation CAB volume declares a smaller window. Attackers can entic |
| CVE-2026-59082 | 7.8 | n/a | A vulnerability has been identified in SIMATIC WinCC V7.5 (All versions), SIMATIC WinCC V8.0 (All versions), SIMATIC WinCC V8.1 (All versions). Affected devices implicitly execute active content when  |
| CVE-2026-121267 | 7.8 | n/a | Incorrect default permissions vulnerability in TÜBİTAK BİLGEM Software Technologies Research Institute eta-remote allows Accessing Functionality Not Properly Constrained by ACLs.

This issue affects e |
| CVE-2026-119899 | 7.8 | n/a | Improper access control in Windows Win32K allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119903 | 7.8 | n/a | Improper access control in Windows Installer allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119904 | 7.8 | n/a | Improper control of generation of code ('code injection') in Microsoft Windows Speech allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119906 | 7.8 | n/a | Improper neutralization of special elements used in an os command ('os command injection') in Windows Sandbox allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119907 | 7.8 | n/a | Untrusted pointer dereference in Windows Function Discovery Resource Publication allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119917 | 7.8 | n/a | Heap-based buffer overflow in Windows Distributed Transaction Coordinator allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119929 | 7.8 | n/a | Use after free in Windows Installer allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119933 | 7.8 | n/a | Use of uninitialized resource in Windows NTFS allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119939 | 7.8 | n/a | Improper privilege management in Windows Print Spooler Components allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119941 | 7.8 | n/a | Untrusted pointer dereference in Windows Volume Shadow Copy allows an unauthorized attacker to elevate privileges locally. |
| CVE-2026-119943 | 7.8 | n/a | Buffer over-read in Microsoft Windows Search Component allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119953 | 7.8 | n/a | Use after free in Windows DNS allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119954 | 7.8 | n/a | Absolute path traversal in Microsoft Windows Search Component allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119957 | 7.8 | n/a | Double free in Windows Remote Desktop Services allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119987 | 7.8 | n/a | Untrusted search path in Microsoft Windows App Store allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119997 | 7.8 | n/a | Heap-based buffer overflow in Microsoft Office Outlook allows an unauthorized attacker to execute code locally. |
| CVE-2026-121661 | 7.8 | n/a | Incomplete list of disallowed inputs in Visual Studio Code allows an unauthorized attacker to bypass a security feature locally. |
| CVE-2026-126497 | 7.8 | n/a | LibreCAD through 2.2.1.6 contains a heap-based out-of-bounds write vulnerability in the bundled libdxfrw dwgReader18::parseDataPage() function due to unchecked buffer size and page offsets. Attackers  |
| CVE-2026-18767 | 7.8 | n/a | A local low privileged attacker or process can access I/O ports via TcRouter.sys because of exposed IOCTL function calls resulting in a full compromise of the affected devices. |
| CVE-2026-18768 | 7.8 | n/a | A local low privileged attacker can access arbitrary physical memory or define its mapping via TcRouter.sys because of exposed IOCTL function calls resulting in a full compromise of the affected devic |
| CVE-2026-18769 | 7.8 | n/a | A local low privileged attacker can move arbitrary physical memory content via TcRouter.sys because of exposed IOCTL function calls resulting in a full compromise of the affected devices. |
| CVE-2026-121668 | 7.7 | n/a | Missing authorization in Azure Confidential Clean Rooms allows an authorized attacker to perform tampering over a network. |
| CVE-2026-121350 | 7.7 | n/a | Adobe Connect is affected by an Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability that could lead to disclosure of sensitive memory. A low-privileged a |
| CVE-2026-121890 | 7.7 | n/a | Adobe Connect is affected by an Improper Restriction of XML External Entity Reference ('XXE') vulnerability that could lead to arbitrary file system read. A low-privileged attacker could exploit this  |
| CVE-2026-126570 | 7.6 | n/a | Padloc 4.0.0 before 4.3.1 contains a prototype pollution vulnerability that allows SCIM token holders to modify Object.prototype by sending crafted SCIM PATCH paths to ScimServer._handleScimUsersPatch |
| CVE-2026-76970 | 7.5 | 0.3% | Due to a Memory Corruption vulnerability in Application Server ABAP for SAP NetWeaver and ABAP Platform, an unauthenticated attacker could send specially crafted requests to the application. If proces |
| CVE-2026-76973 | 7.5 | 0.3% | Due to a Memory Corruption vulnerability in Application Server ABAP of SAP NetWeaver and ABAP Platform, an unauthenticated attacker could send specially crafted network requests to the affected servic |
| CVE-2026-89114 | 7.5 | 0.3% | SAP NetWeaver AS Java EDM Application does not perform an authentication check for certain web service requests. An unauthenticated attacker could send a specially crafted request to retrieve sensitiv |
| CVE-2026-120012 | 7.5 | 0.3% | SAP Cloud SDK for AI (Node.js) could inadvertently include sensitive authentication credentials in error messages generated by certain internal operations under specific failure conditions. An attacke |
| CVE-2026-120013 | 7.5 | 0.4% | The agent_memory module accepts a caller-supplied tenant parameter in create_client(tenant=...). Prior to version 0.50.0, the tenant parameter was not validated before being used to construct filesyst |
| CVE-2026-60040 | 7.5 | 0.3% | An unauthenticated remote attacker can perform a DoS in the backends backup creation function. This can result in a total loss of availability. |
| CVE-2026-60044 | 7.5 | 0.3% | The backups created by the application use a weak static password allowing an unauthenticated remote attacker to access their content. This can result in a total loss of confidentiality. |
| CVE-2026-124747 | 7.5 | n/a | A flaw was found in BusyBox. When resuming a download over File Transfer Protocol (FTP), the wget utility fails to verify that the resume offset does not exceed the file size reported by the server, r |
| CVE-2026-120399 | 7.5 | n/a | A flaw was found in flightctl. A TLS handshake is performed synchronously in the HTTP server’s connection-context callback without a deadline. A network-reachable unauthenticated client can stall the  |
| CVE-2026-125759 | 7.5 | n/a | Nango before 0.71.3 contains an sql injection vulnerability that allows unauthenticated attackers to execute arbitrary SQL by supplying a crafted task group key to the orchestrator API. Attackers can  |
| CVE-2026-119932 | 7.5 | n/a | Null pointer dereference in Windows Remote Desktop allows an unauthorized attacker to deny service over a network. |
| CVE-2026-119938 | 7.5 | n/a | Heap-based buffer overflow in Windows Shell allows an unauthorized attacker to execute code over a network. |
| CVE-2026-119944 | 7.5 | n/a | Heap-based buffer overflow in Windows Mobile Device Management allows an unauthorized attacker to elevate privileges over a network. |
| CVE-2026-119947 | 7.5 | n/a | Use after free in Windows Hyper-V allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119948 | 7.5 | n/a | Stack-based buffer overflow in Windows Active Directory allows an authorized attacker to execute code over a network. |
| CVE-2026-119960 | 7.5 | n/a | Use of uninitialized resource in Windows Hyper-V allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119966 | 7.5 | n/a | Integer overflow or wraparound in Windows Graphics Kernel allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119995 | 7.5 | n/a | Heap-based buffer overflow in Microsoft Office Outlook allows an unauthorized attacker to execute code over a network. |
| CVE-2026-119996 | 7.5 | n/a | Heap-based buffer overflow in Microsoft Office Outlook allows an unauthorized attacker to execute code over a network. |
| CVE-2026-120000 | 7.5 | n/a | Deserialization of untrusted data in Microsoft Office SharePoint allows an authorized attacker to execute code over a network. |
| CVE-2026-121680 | 7.5 | n/a | Exposure of sensitive information to an unauthorized actor in Windows NTLM allows an unauthorized attacker to perform spoofing over a network. |
| CVE-2026-122169 | 7.5 | n/a | Insufficient granularity of access control in Windows IKE Extension allows an authorized attacker to perform spoofing locally. |
| CVE-2026-122177 | 7.5 | n/a | Improper link resolution before file access ('link following') in Windows iSCSI allows an unauthorized attacker to elevate privileges over a network. |
| CVE-2026-80094 | 7.5 | n/a | Use after free in Remote Desktop Gateway Service allows an authorized attacker to elevate privileges over a network. |
| CVE-2026-84010 | 7.5 | n/a | Exposed dangerous method or function in SQL Server allows an authorized attacker to elevate privileges over a network. |
| CVE-2026-115483 | 7.5 | n/a | The Everest Forms plugin for WordPress is vulnerable to Arbitrary File Read in all versions up to, and including, 3.6.3 via the attach_entry_files() function. This is due to the function attaching any |
| CVE-2026-126543 | 7.5 | n/a | WWBN AVideo through 29.7.1 contains an improper payment verification vulnerability in plugin/PayPalYPT/ipnV2.php that credits wallets from PayPal IPNs not bound to the site's merchant account. Unauthe |
| CVE-2026-124737 | 7.5 | n/a | A flaw was found in BusyBox. When the TFTP (Trivial File Transfer Protocol) client requests a custom small block size and receives a standard response, it falls back to the default block size without  |
| CVE-2026-82509 | 7.4 | n/a | V programming language standard library net.http through version 0.5.2 prior to commit 4077484 contains a TLS certificate validation bypass vulnerability that allows on-path attackers to intercept HTT |
| CVE-2026-125758 | 7.4 | n/a | Aptabase before commit 61d4c01 contains an authentication bypass vulnerability that allows unauthenticated attackers to forge sign-in links by using the publicly known example AUTH_SECRET. Attackers c |
| CVE-2026-126499 | 7.4 | n/a | Jellyfin before 12.0 contains a path traversal vulnerability in the DELETE /Library/VirtualFolders and POST /Library/VirtualFolders/Name endpoints that allows attackers to delete or move directories v |
| CVE-2026-125076 | 7.3 | 0.4% | A vulnerability was found in SourceCodester Smart Attendance System with QR Code Scanner 1.0. Affected is an unknown function of the file api/attendance_handler.php of the component JSON Endpoint. Per |
| CVE-2026-125087 | 7.3 | 0.4% | A vulnerability was found in Michael-A-Kuykendall Shimmy up to 2.6.4. The affected element is an unknown function of the file src/server.rs of the component Inference API. Performing a manipulation re |
| CVE-2026-119900 | 7.3 | n/a | Out-of-bounds read in Windows NTFS allows an authorized attacker to elevate privileges locally. |
| CVE-2026-120778 | 7.3 | n/a | Creation of temporary file in directory with insecure permissions in .NET Aspire allows an authorized attacker to elevate privileges locally. |
| CVE-2026-125382 | 7.2 | 0.5% | Map-OS 5.0.0 to before 5.2.2 contains a privilege escalation vulnerability in the REST users API that allows non-administrator operators holding the cUsuario permission to bypass permission-delegation |
| CVE-2026-93427 | 7.2 | 0.2% | The ARMember Premium – Membership Plugin, Content Restriction, Member Levels, User Profile & User signup plugin for WordPress is vulnerable to Stored Cross-Site Scripting via Registration Custom Field |
| CVE-2026-60035 | 7.2 | 0.5% | A high privileged remote attacker can perform a code injection in the backends network auth function leading to code execution. This can result in a total loss of confidentiality, integrity and availa |
| CVE-2026-60039 | 7.2 | 0.5% | A high privileged remote attacker can perform a code injection in the backends backup restore function leading to code execution. This can result in a total loss of confidentiality, integrity and avai |
| CVE-2026-12424 | 7.2 | n/a | The ARforms plugin for WordPress is vulnerable to Stored Cross-Site Scripting via Referer Header in all versions up to, and including, 7.2.4 due to insufficient input sanitization and output escaping. |
| CVE-2026-12427 | 7.2 | n/a | The ARforms plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'description' parameter in all versions up to, and including, 7.2.4 due to insufficient input sanitization and out |
| CVE-2026-125397 | 7.1 | 0.2% | NocoBase plugin-ai 2.1.0 through 2.2.41 contains an authorization bypass vulnerability in getAccessibleAIEmployee() that lets authenticated users access unassigned AI employees by overriding the role- |
| CVE-2026-125398 | 7.1 | 0.3% | Instatic before 0.0.21 contains an authorization bypass vulnerability in handleRowAuthor that allows authenticated users to skip table-level access checks by loading rows with getDataRow() instead of  |
| CVE-2026-125750 | 7.1 | n/a | Firekylin through 2.18.1 contains an improper authorization vulnerability that allows editor-role users to read administrator-only secrets because the admin API base guard permits all GET actions. Edi |
| CVE-2026-125754 | 7.1 | n/a | Dolibarr 20.0.0 through 23.0.4 and 24.x before 24.0.2 contains an insecure direct object reference vulnerability in api_expensereports.class.php payment endpoints that lets authenticated users access  |
| CVE-2026-119988 | 7.1 | n/a | Numeric truncation error in Windows SMB allows an authorized attacker to execute code over a network. |
| CVE-2026-110091 | 7.1 | n/a | Premiere Pro is affected by a Missing Authentication for Critical Function vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability to bypass securit |
| CVE-2026-126561 | 7.1 | n/a | Semantic MediaWiki 2.5.0 before 7.4.1 contains a missing authorization vulnerability that allows editors without the edit-protection right to lock pages by adding an Is edit protected annotation. Atta |
| CVE-2026-126566 | 7.1 | n/a | Semantic MediaWiki 7.3.1 before 7.4.1 contains an incorrect authorization vulnerability in EditProtectionUpdater::userMayChangeProtection() that checks protection changes against the page's latest rev |
| CVE-2026-16478 | 7.0 | n/a | Permissive list of allowed inputs vulnerability in TÜBİTAK BİLGEM Software Technologies Research Institute pardus-nvidia-installer allows Privilege Escalation.

This issue affects pardus-nvidia-instal |
| CVE-2026-119913 | 7.0 | n/a | Improper link resolution before file access ('link following') in Windows Print Spooler Components allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119919 | 7.0 | n/a | Heap-based buffer overflow in Windows Distributed Transaction Coordinator allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119921 | 7.0 | n/a | Heap-based buffer overflow in Windows Microsoft Account Sign-in Assistant allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119928 | 7.0 | n/a | Use after free in Windows PrintWorkflowUserSvc allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119931 | 7.0 | n/a | Time-of-check time-of-use (toctou) race condition in Windows Text Services Framework allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119974 | 7.0 | n/a | Time-of-check time-of-use (toctou) race condition in Windows Cloud Files Mini Filter Driver allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119981 | 7.0 | n/a | Missing authentication for critical function in Visual Studio Code allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119992 | 7.0 | n/a | Double free in Windows HTTP.sys allows an authorized attacker to elevate privileges locally. |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-874v-49pf-3wjr | CVE-2026-126626 | medium | The web services listener of Progressive Robot hMailServer 6.3.3 through 6.3.7 counts every... |
| GHSA-gxm7-28h3-vf9j | CVE-2026-126623 | high | Inefficient algorithmic complexity in the JSON reader of Progressive Robot hMailServer 6.3.6 and... |
| GHSA-6c88-88jx-2hcr | CVE-2026-18767 | high | A local low privileged attacker or process can access I/O ports via TcRouter.sys because of... |
| GHSA-q63q-8h8v-j42v | CVE-2026-126625 | medium | Incorrect default permissions in the Windows installer of Progressive Robot hMailServer 6.3.7... |
| GHSA-5vrf-r3xw-59r9 | CVE-2026-126624 | high | Unverified ownership in the Windows installer of Progressive Robot hMailServer 6.3.7 allows a... |
| GHSA-x59q-qhqr-ghwc | CVE-2026-18769 | high | A local low privileged attacker can move arbitrary physical memory content via TcRouter.sys... |
| GHSA-25c8-q942-4rxj | CVE-2026-18768 | high | A local low privileged attacker can access arbitrary physical memory or define its mapping via... |
| GHSA-2q54-5c4c-vg9w | CVE-2026-126621 | high | Progressive Robot hMailServer 6.0.0-B1 through 6.3.7 on Windows hands OpenSSL the names of its... |
| GHSA-67h5-cmp2-p9hr | CVE-2026-126615 | medium | The sign-in of Progressive Robot hMailServer 6.2.22-pre2 through 6.3.7 takes for an account names... |
| GHSA-g98g-j6w4-w22m | CVE-2026-126617 | high | SQL injection in the database layer of Progressive Robot hMailServer 6.0.0-B1 through 6.2.18,... |
| GHSA-5xgg-6cxw-qr32 | CVE-2026-126619 | medium | Misinterpretation of SQL statement text in the database layer of Progressive Robot hMailServer 6... |
| GHSA-4f2q-v3rq-2852 | CVE-2026-126616 | medium | The auto-ban of Progressive Robot hMailServer 6.2.0 through 6.3.3, with a MySQL or MariaDB... |
| GHSA-7748-8wp3-j5hq | CVE-2026-126610 | high | Progressive Robot hMailServer 6.3.4 through 6.3.7, with a MySQL or MariaDB database and TlsMode... |
| GHSA-2wjf-5hp3-227w | CVE-2026-126618 | medium | The auto-ban of Progressive Robot hMailServer 6.0.0-B1 through 6.3.7 can be kept from banning an... |
| GHSA-h7qw-3f34-rjrw | CVE-2026-93487 | high | In affected versions of Octopus Server, incorrect validation of the permissions assigned to a... |
| GHSA-45pg-vr27-cp42 | CVE-2026-126622 | high | Incorrect default permissions in the Windows installer of Progressive Robot hMailServer 6.3.7... |
| GHSA-8g5c-c364-9965 | CVE-2026-126609 | high | Progressive Robot hMailServer 6.2.25 through 6.3.7 on Windows, with a PostgreSQL database, the... |
| GHSA-8r4c-2qx7-2q6q | CVE-2026-126614 | medium | The web services listener of Progressive Robot hMailServer 6.3.3 through 6.3.7 does not apply the... |
| GHSA-332h-7rh6-hg9m | CVE-2026-126607 | high | Progressive Robot hMailServer 6.2.3 through 6.3.7 on Windows, with a MySQL or MariaDB database,... |
| GHSA-68qj-r5q8-pvm5 | CVE-2026-126613 | high | Allocation of resources without limits in the JSON reader of Progressive Robot hMailServer 6.3.2... |
| GHSA-pm2h-xjj9-fw84 | CVE-2026-126611 | high | Progressive Robot hMailServer 6.3.4 through 6.3.7, with a MySQL or MariaDB database, TlsMode... |
| GHSA-5647-98qw-xpgp | CVE-2026-15785 | medium | The Joinchat – Enhanced "click to chat" plugin for WordPress is vulnerable to Reflected Cross... |
| GHSA-hvr4-pggg-cr56 | CVE-2026-126612 | high | Improper link resolution in the Windows installer of Progressive Robot hMailServer 6.0.0 through... |
| GHSA-grj3-mv63-h3cw | CVE-2026-123659 | medium | The ProfilePress WordPress plugin before 4.17.6 does not restrict the role and user meta filters... |
| GHSA-269c-5hmm-363q | CVE-2026-12427 | high | The ARforms plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the ... |

## Ransomware — new leak-site victim postings (ransomware.live)
_No data returned this run._

## IOCs
### ThreatFox (recent, abuse.ch)
_No data returned this run._

### URLhaus (recent malicious URLs, abuse.ch)
_No data returned this run._

### MalwareBazaar (recent samples, abuse.ch)
_No data returned this run._

### Feodo Tracker (active botnet C2 IPs, abuse.ch)
| IP | Malware |
|---|---|
| 162.243.103.246 | Emotet |
| 50.16.16.211 | QakBot |
| 34.204.119.63 | QakBot |
| 178.62.3.223 | QakBot |
| 27.133.154.218 | QakBot |

### IPsum (IPs flagged by 5+ independent blocklists)
| IP | Lists flagging it |
|---|---|
| 45.148.10.151 | 10 |
| 45.148.10.152 | 10 |
| 18.116.101.220 | 9 |
| 18.218.118.203 | 9 |
| 45.148.10.141 | 9 |
| 45.148.10.157 | 9 |
| 64.62.197.77 | 9 |
| 66.132.195.75 | 9 |
| 95.188.91.101 | 9 |
| 138.226.239.233 | 9 |
| 185.87.121.1 | 9 |
| 195.178.110.227 | 9 |
| 3.131.220.121 | 8 |
| 35.210.82.106 | 8 |
| 35.210.172.21 | 8 |
| 35.210.226.156 | 8 |
| 36.66.16.233 | 8 |
| 45.156.87.78 | 8 |
| 64.62.197.2 | 8 |
| 64.62.197.32 | 8 |

### OpenPhish (live phishing URLs)
- https://www.roblox.com.et/users/9501717396/profile
- https://s4w.in/roblox-com-users-9501771396-profile
- https://security-alerters.info/we5fe123204/83eeaf9c6c0678753e5eddcc/index.php?id=bf6537fa062b87b709041adcb1d85319
- http://promogiftwinter.com/
- https://mdi6mb.eventzones.de/
- https://burungkpertu2.kamunanya.de/
- https://https--www--roblox.com/login?returnUrl=368542007
- https://macroxchowchowv5-ctfjecbdg2fde2e7.z03.azurefd.net/
- https://1011fr3-6z19umsj.4everland.app/
- https://hvabuzujvbnm.info/
- https://sharefilem3650.documentation-m3650676556.workers.dev/
- https://eonifyit.com/cart
- https://bunksatrode.hostel.town/us/
- https://objectstorage.us-phoenix-1.oraclecloud.com/n/axlnm4hhzeul/b/standard-tiered-messages-are-here/o/index7670964.htm?_kx=uEmZeXr7tHqIX1P2rNTM5TLQVJMqyYnAcEMZGx0DwT8.Xn5yTR
- https://www.roblox.com.ml/users/400925685186/profile
- https://millassllc.com/include/adobe1/adobe/download.html
- http://tzbgtm.com/
- https://csmgroup.blu-foods.com/login?method=signin&mode=secure&client_id=db30ed6-53592-41922-0d22-aaab5901c&privacy=on&sso_reload=true&redirect_urI=https%3A%2F%2Flogin.microsoftonline.com%2F
- https://csmgroup.blu-foods.com/go
- http://trustwallet.com-users.vip/

### PhishStats (recent phishing/malicious URLs, scored)
_No data returned this run._

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| b60be83fabb664ff9b542c3f0f9d7d514b9c1fa3 | RatonRAT C&C |
| 25235b80d03ab6eaf4e2b0eeed5663d302ec38b1 | Vidar C&C |
| bfa41aa99aa3dcd67f178a96fd369e74277234cf | Vidar C&C |
| f04b05a8f3f341ac61c3244469516cc850edde00 | PavinLoader C&C |
| 0796ad594b2148e4fe97407cc4703c2e78ffa752 | ACRStealer C&C |
| baa0e54314fcd527db444d8782d41003a661f84d | Havoc C&C |
| 9d191436a0dcb9dd826614de108db06cfc158b57 | PureRAT C&C |
| 78fef26abba5424bfa791ced6cd78f0f87d34c1e | PureLogsStealer C&C |
| 19a8b5f296bc373c894efccb1afb9ef601b495c6 | Malware C&C |
| b05b9b740f218f28eb17bfded00a13c2aba7798d | ACRStealer C&C |
| 1cffce18a067f905ef42108b7c833bc6d80edf89 | CobraRAT C&C |
| 6dabd1e1610022f44a5193e3f613d332b0449119 | PureLogsStealer C&C |
| 4e13fc3de8cecc9a0238827e64ed0a530912dea0 | ACRStealer C&C |
| ae4f978f970ebd6485a1c6993022a9b905f269ba | OffLoader C&C |
| 311e268a12c312f6327c3d7a7d697320793481c8 | ACRStealer C&C |
| f645b552ec56cfc6550b89e3202c53f74c2e980a | OffLoader C&C |
| 96b81644c0b65e34116351415b2bec72bf7fc5be | PureLogsStealer C&C |
| 0de85864ac1b98530883c917890196a0c99fd520 | ACRStealer C&C |
| 0d983264dd1f51176b28d44e1ab03223062c08ff | PureLogsStealer C&C |
| dea6f037aff488a491921f27b37d970d8abd1c62 | OffLoader C&C |

### Spamhaus DROP (hijacked/leased malicious netblocks)
- 1.10.16.0/20
- 1.19.0.0/16
- 1.32.128.0/18
- 2.26.75.0/24
- 2.27.5.0/24
- 2.27.62.0/24
- 2.56.192.0/22
- 2.57.122.0/24
- 2.57.232.0/23
- 2.57.234.0/23
- 2.58.56.0/24
- 2.59.152.0/24
- 2.59.153.0/24
- 5.42.92.0/24
- 5.101.86.0/24
- 5.105.220.0/24
- 5.175.169.0/24
- 5.175.182.0/24
- 5.175.189.0/24
- 5.175.253.0/24

### blocklist.de (recent SSH/mail/web attack sources)
- 1.1.220.166
- 1.13.181.113
- 1.14.140.218
- 1.161.133.214
- 1.162.217.195
- 1.172.90.41
- 1.175.131.108
- 1.180.246.242
- 1.2.164.171
- 1.2.252.192
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.220.198.126
- 1.222.42.237
- 1.226.82.243
- 1.234.27.159
- 1.234.53.65
- 1.234.80.94
- 1.235.183.146

### CINS Army (poorly-rated IPs)
- 1.12.229.231
- 1.15.14.29
- 1.169.17.240
- 1.169.3.7
- 1.192.216.192
- 1.193.56.135
- 1.220.119.115
- 1.223.11.69
- 1.224.163.125
- 1.24.16.103
- 1.24.16.107
- 1.24.16.116
- 1.24.16.118
- 1.24.16.119
- 1.24.16.120
- 1.24.16.122
- 1.24.16.123
- 1.24.16.124
- 1.24.16.130
- 1.24.16.132

## News (last ~36h, across outlets)
### The Hacker News
- [Microsoft Patches 1,259 Flaws, Including Exploited Outlook Bug That May Expose NTLMv2 Hashes](https://thehackernews.com/2026/11/microsoft-patches-1259-flaws-including.html)
- [Railway Says Stolen Customer AI Keys Led to $740,000 in Estimated Unauthorized Usage Charges](https://thehackernews.com/2026/11/railway-says-stolen-customer-ai-keys.html)
- [Microsoft Researchers Show AI Agents Can Be Backdoored by Editing Fewer Than 10 Neurons](https://thehackernews.com/2026/11/microsoft-researchers-show-ai-agents.html)
- [Cisco BroadWorks and Openwave Flaws Actively Exploited Despite Available Patches](https://thehackernews.com/2026/11/cisco-broadworks-and-openwave-flaws.html)
- [Git Patches Flaw That Lets Malicious Repositories Execute Code During Recursive Clones](https://thehackernews.com/2026/11/git-patches-flaw-that-lets-malicious.html)
- [SGLang RCE Exploit Breaches NEAR AI, Steals Data From 18 Agents and About 100 Users](https://thehackernews.com/2026/11/sglang-rce-exploit-breaches-near-ai.html)
- [Hackers Exploit Critical Xen Orchestra Auth Bypass Flaw to Gain Admin Access](https://thehackernews.com/2026/11/hackers-exploit-critical-xen-orchestra.html)
- [Three China-Nexus Espionage Campaigns Linked Through Sparrow Malware Ecosystem](https://thehackernews.com/2026/11/three-china-nexus-espionage-campaigns.html)
- [Attackers Exploit AhsayCBS Flaws to Deploy Sandbox-Evading Python Backdoor](https://thehackernews.com/2026/11/attackers-exploit-ahsaycbs-flaws-to.html)
- [Blind Eagle Uses Fake Court Notices to Deliver Remote Access Trojan Across Latin America](https://thehackernews.com/2026/11/blind-eagle-uses-fake-court-notices-to.html)
- [Fireworks AI Confirms Wider Breach Affecting Customer Datasets, Model Weights and Notion AI Chats](https://thehackernews.com/2026/11/fireworks-ai-breach-widens-to-expose.html)
- [Binance Warns of iOS Sandbox Escape That Could Expose Crypto Wallet Keys, No Fix Confirmed](https://thehackernews.com/2026/11/binance-warns-of-ios-sandbox-escape.html)
- [Beyond the Alert: The Case for Rich Network Data](https://thehackernews.com/2026/11/beyond-alert-case-for-rich-network-data.html)
- [Apple Patches iMessage Group Chat Privacy Flaws and Bluetooth Pairing Vulnerabilities](https://thehackernews.com/2026/11/apple-patches-imessage-group-chat.html)
- [Russian Turla Hackers Use New Cereal Malware to Steal Emails From Government Exchange Servers](https://thehackernews.com/2026/11/russian-turla-hackers-use-new-cereal.html)

### BleepingComputer
- [CISA flags Cisco BroadWorks flaw as actively exploited in attacks](https://www.bleepingcomputer.com/news/security/cisa-flags-cisco-broadworks-flaw-as-actively-exploited-in-attacks/)
- [Microsoft fixes Exchange sign-ins broken by Windows Server updates](https://www.bleepingcomputer.com/news/microsoft/microsoft-fixes-exchange-sign-ins-broken-by-october-windows-server-updates/)
- [Railway breach leads to $740,000 in fraudulent AI charges](https://www.bleepingcomputer.com/news/apple/railway-breach-leads-to-740-000-in-fraudulent-ai-charges/)
- [Japanese furniture giant Nitori says hackers stole 37.6M customer records](https://www.bleepingcomputer.com/news/security/japanese-furniture-giant-nitori-says-hackers-stole-376m-customer-records/)
- [Microsoft releases Windows 10 KB5131096 extended security update](https://www.bleepingcomputer.com/news/microsoft/microsoft-releases-windows-10-kb5131096-extended-security-update/)
- [Hackers exploit trusted AWS access to breach multiple cloud environments](https://www.bleepingcomputer.com/news/security/hackers-exploit-trusted-aws-access-to-breach-multiple-cloud-environments/)
- [Microsoft November 2026 Patch Tuesday fixes 1,235 flaws, Outlook zero-day](https://www.bleepingcomputer.com/news/microsoft/microsoft-november-2026-patch-tuesday-fixes-1-235-flaws-outlook-zero-day/)
- [Windows 11 KB5132061 & KB5131087 cumulative updates released](https://www.bleepingcomputer.com/news/microsoft/windows-11-kb5132061-and-kb5131087-cumulative-updates-released/)
- [Critical Xen Orchestra auth bypass flaw exploited to hijack VM servers](https://www.bleepingcomputer.com/news/security/critical-xen-orchestra-auth-bypass-flaw-exploited-to-hijack-vm-servers/)
- [Binance warns of iOS flaw that could leak crypto wallet secrets](https://www.bleepingcomputer.com/news/security/binance-warns-of-ios-flaw-that-could-leak-crypto-wallet-secrets/)
- [Ransomware recovery is now a client retention metric](https://www.bleepingcomputer.com/news/security/ransomware-recovery-is-now-a-client-retention-metric/)
- [SAP patches ICM2SHELL and PROXYGATE maximum severity flaws](https://www.bleepingcomputer.com/news/security/sap-patches-four-maximum-severity-security-vulnerabilities/)
- [Hackers now exploit critical Barracuda ESG flaws to gain root access](https://www.bleepingcomputer.com/news/security/hackers-exploit-barracuda-email-security-gateway-flaws-to-get-root-access/)
- [Turla hackers use new Cereal malware to spy on govt Exchange servers](https://www.bleepingcomputer.com/news/security/turla-hackers-use-new-ceral-malware-to-spy-on-govt-exchange-servers/)
- [Google patches eighth Chrome zero-day exploited in attacks this year](https://www.bleepingcomputer.com/news/security/google-patches-eighth-chrome-zero-day-exploited-in-attacks-this-year/)

### Krebs on Security
- [Microsoft Fixes Nearly 1,100 Security Vulnerabilities](https://krebsonsecurity.com/2026/11/microsoft-fixes-nearly-1100-security-vulnerabilities/)

### Dark Reading
- [November Patch Tuesday: An Overflowing Cornucopia of CVEs](https://www.darkreading.com/vulnerabilities-threats/november-patch-tuesday-cornucopia-cves)
- [Artex: The AI Pen-Test Tool Hackers Turned Into a Weapon](https://www.darkreading.com/cyberattacks-data-breaches/artex-ai-pen-test-tool-hackers-weapon)
- [F-Secure Identifies 26 Ways AI Can Harm Consumers, and Where to Stop Them](https://www.darkreading.com/application-security/f-secure-26-ways-ai-harm-consumers-where-to-stop-them)
- [Checkmarx Appoints Kobi Sivilya as Chief Information Security Officer](https://www.darkreading.com/cybersecurity-careers/checkmarx-appoints-kobi-sivilya-chief-information-security-officer)
- [How to Assess OT Incident Response Preparedness](https://www.darkreading.com/ics-ot-security/assess-ot-incident-response-preparedness)
- [AI Coding Agents Leak Thousands of Secrets to GitHub](https://www.darkreading.com/cyber-risk/ai-coding-agents-leak-secrets-github)
- [AI Makes Reverse Engineering Mainstream Software &amp; Malware Far Easier](https://www.darkreading.com/application-security/ai-reverse-engineering-apps)
- [People Are Getting Weird About AI](https://www.darkreading.com/cyber-risk/people-are-getting-weird-about-ai)

### SecurityWeek
- [Threat Actors Exploit Openwave, Cisco BroadWorks Vulnerabilities](https://www.securityweek.com/threat-actors-exploit-openwave-cisco-broadworks-vulnerabilities/)
- [Chipmaker Patch Tuesday: Over 200 Vulnerabilities Addressed by Intel, AMD](https://www.securityweek.com/chipmaker-patch-tuesday-over-200-vulnerabilities-addressed-by-intel-amd/)
- [Recently Patched Barracuda Vulnerabilities Exploited in Attacks](https://www.securityweek.com/recently-patched-barracuda-vulnerabilities-exploited-in-attacks/)
- [Bluetooth, AirPlay Pairing Vulnerabilities Patched Across Apple Platforms](https://www.securityweek.com/bluetooth-airplay-pairing-vulnerabilities-patched-across-apple-platforms/)
- [Exploited Outlook Zero-Day Among 1,094 Flaws Patched by Microsoft](https://www.securityweek.com/exploited-outlook-zero-day-among-1094-flaws-patched-by-microsoft/)
- [Adobe Patches 110 Vulnerabilities Across 9 Products](https://www.securityweek.com/adobe-patches-110-vulnerabilities-across-9-products/)
- [Software Transparency Is Changing: Allan Friedman on SBOM, AI BOMs and What Comes Next](https://www.securityweek.com/software-transparency-is-changing-allan-friedman-on-sbom-ai-boms-and-what-comes-next/)
- [Google Widens Gemini 4 Carbon Access After AI Agents Verify Signal Code](https://www.securityweek.com/google-widens-gemini-4-carbon-access-after-ai-agents-verify-signal-code/)
- [Today: CISO Forum Virtual Summit 2026 – Join Global Cybersecurity Leaders](https://www.securityweek.com/today-ciso-forum-virtual-summit-2026-join-global-cybersecurity-leaders/)
- [WhiteMatter Raises $20 Million in Series A Funding](https://www.securityweek.com/whitematter-raises-20-million-in-series-a-funding/)

### The Record
- [US Army member arrested in UK over allegations of spying for Russia](https://therecord.media/us-army-member-arrested-in-uk-spying-for-russia)
- [Microsoft’s Patch Tuesday surpasses 1,000 bugs for second month in a row](https://therecord.media/patch-tuesday-microsoft-1000-bugs-again)
- [AI company Fireworks says hackers stole data, billing info during October breaches](https://therecord.media/ai-company-fireworks-says-hackers-stole-data-in-oct-attacks)
- [Cybercriminals are increasingly infecting regular people with spyware](https://therecord.media/spyware-cyber-crime-iverify)
- [Palantir exec nominated to lead CISA; lame-duck Senate vote is uncertain](https://therecord.media/michael-losapio-cisa-director-nomination)

### Infosecurity Magazine
- [OT Incidents Hit a Third of Industrial Organizations, SANS Finds](https://www.infosecurity-magazine.com/news/ot-incidents-third-industrial/)
- [Microsoft Fixes 1235 Flaws in Another Record Patch Tuesday](https://www.infosecurity-magazine.com/news/microsoft-fixes-1235-flaws-record/)
- [CISA Expands Incident Reporting Form While CIRCIA Mandate Waits](https://www.infosecurity-magazine.com/news/cisa-incident-reporting-form-circia/)
- [Russia-Linked Turla Hijacks Exchange Servers to Spy on NATO and EU Emails](https://www.infosecurity-magazine.com/news/turla-cereal-exchange-email/)
- [Cloud Vulnerabilities Surge Fourfold in Less Than a Year](https://www.infosecurity-magazine.com/news/cloud-vulnerabilities-surge/)
- [Default Admin Password Let Researchers Unlock and Start Cars](https://www.infosecurity-magazine.com/news/forgerock-openidm-default-password/)
- [Vanderbilt University Takes Systems Offline After Cyber Incident](https://www.infosecurity-magazine.com/news/vanderbilt-university-cyber/)
- [France Blames Iran for Supermarket Fridge Hack, Requests International Arrest Warrants](https://www.infosecurity-magazine.com/news/france-blames-iran-supermarket/)
- [Binance Investigates ShinyHunters Breach Claims](https://www.infosecurity-magazine.com/news/binance-investigates-shinyhunters/)

### CyberScoop
- [CISA director pick already drawing concern from Hill Dems over Palantir connection](https://cyberscoop.com/michael-losapio-cisa-director-nomination-palantir-scrutiny/)
- [The US wants its quantum lead to turn into factories and supply chains](https://cyberscoop.com/us-quantum-computing-industry-manufacturing-push/)
- [Microsoft fixes over 1,000 vulnerabilities in November Patch Tuesday](https://cyberscoop.com/microsoft-patch-tuesday-november-2026/)
- [Vanderbilt University reels following ransomware attack claimed by BYOD group](https://cyberscoop.com/vanderbilt-university-ransomware-attack-byod/)
- [Spyware attacks trend toward hitting just about anyone](https://cyberscoop.com/spyware-attacks-trend-everyday-people-iverify-report/)
- [Russian Turla group used new toolset to silently pilfer emails from Kazakhstan, Romanian governments](https://cyberscoop.com/russian-turla-group-used-new-toolset-to-silently-pilfer-emails-from-kazakhstan-romanian-governments/)
- [Trump picks Palantir’s LoSapio to head CISA](https://cyberscoop.com/trump-picks-palantirs-losapio-to-head-cisa/)

### Cisco Talos
- [Microsoft Patch Tuesday for November 2026 — Snort rules and prominent vulnerabilities](https://blog.talosintelligence.com/microsoft-patch-tuesday-for-november-2026/)

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
- [Detecting sleeper agents hiding in AI model neurons](https://www.microsoft.com/en-us/security/blog/2026/11/10/detecting-sleeper-agents-hiding-in-ai-model-neurons/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Wednesday, November 11th, 2026 https://isc.sans.edu/podcastdetail/10174, (Wed, Nov 11th)](https://isc.sans.edu/diary/rss/33510)
- [Microsoft Patch Tuesday November 2027 , (Tue, Nov 10th)](https://isc.sans.edu/diary/rss/33508)
- [Apple Patches Everyting: November 2026 Edition, (Tue, Nov 10th)](https://isc.sans.edu/diary/rss/33506)
- [ISC Stormcast For Tuesday, November 10th, 2026 https://isc.sans.edu/podcastdetail/10172, (Tue, Nov 10th)](https://isc.sans.edu/diary/rss/33504)

### Securelist (Kaspersky)
- [Citrus Ransomware: VLESS for traffic, Sn00py for encryption, and LLMs lending a hand](https://securelist.com/citrus-ransomware/121879/)
- [IT threat evolution in Q3 2026. Non-mobile statistics](https://securelist.com/malware-report-q3-2026-pc-iot-statistics/121843/)
- [IT threat evolution in Q3 2026. Mobile statistics](https://securelist.com/malware-report-q3-2026-mobile-statistics/121844/)

### CrowdStrike Blog
- [November 2026 Patch Tuesday: 1,252 CVEs Include One Zero-Day and 68 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-november-2026/)
- [How Adversaries Are Turning the Vulnerability Ecosystem Against Defenders](https://www.crowdstrike.com/en-us/blog/adversaries-turn-vulnerability-ecosystem-against-defenders/)
- [CrowdStrike Introduces Agentic Adversary Emulation to Counter AI-Enabled Adversaries](https://www.crowdstrike.com/en-us/blog/crowdstrike-agentic-adversary-emulation-counters-ai-enabled-adversaries/)
- [CrowdStrike Brings Enterprise Browser Security to the Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-brings-enterprise-browser-security-to-falcon-platform/)
- [CrowdStrike Extends the Agentic SOC to Detect and Stop Agent Insider Threats](https://www.crowdstrike.com/en-us/blog/crowdstrike-detects-and-stops-agent-insider-threats/)
- [New Falcon Cloud Security Innovations Secure the Cloud AI Runs On](https://www.crowdstrike.com/en-us/blog/falcon-cloud-security-innovations-secure-cloud-ai-runs-on/)
- [CrowdStrike Advances AI Security and Safety from Endpoint to Cloud](https://www.crowdstrike.com/en-us/blog/crowdstrike-advances-ai-security-and-safety-falcon-guardian/)
- [Introducing AI Kill Switch: Taking Control When AI Agents Go Rogue](https://www.crowdstrike.com/en-us/blog/crowdstrike-introduces-ai-kill-switch/)
- [CrowdStrike Secures AI Agents Inside Claude Cowork](https://www.crowdstrike.com/en-us/blog/crowdstrike-secures-ai-agents-inside-claude-cowork/)
- [CrowdStrike to Acquire Dreadnode to Bring Automated AI Security Testing to the Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-to-acquire-dreadnode/)

### FortiGuard Threat Signal
- [WordPress Core Time-of-check Time-of-use (TOCTOU) Race Condition Vulnerability](https://fortiguard.fortinet.com/threat-signal-report/6565)
- [OT Refrigeration Control Systems Attack](https://fortiguard.fortinet.com/threat-signal-report/6553)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/
- https://api.phishstats.info/api/phishing?_sort=-id&_size=30 -> 502 Server Error: Bad Gateway for url: https://api.phishstats.info/api/phishing?_sort=-id&_size=30
- https://api.ransomware.live/v2/recentvictims -> 429 Client Error: TOO MANY REQUESTS for url: https://api.ransomware.live/v2/recentvictims

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal