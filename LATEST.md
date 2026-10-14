# Winjit Daily TI Digest — 2026-10-14

_Auto-generated. Window: last ~24h. Fetched at 2026-10-14T08:34:01.326203+00:00Z_

**At a glance:** 2 new KEV · 211 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-104935 | Ivanti | Connect Secure | Ivanti Connect Secure Authentication Bypass by Spoofing Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-96951 | Microsoft | Windows | Microsoft Windows Command Injection Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-109109 | 10.0 | 0.6% | A vulnerability was detected in Wavlink WL-WN530BE1-A 251117. This vulnerability affects the function strcpy of the file /cgi-bin/ExportAllSettings.cgi of the component Settings Export CGI. Performing |
| CVE-2026-109110 | 10.0 | 2.0% | A flaw has been found in Wavlink WL-WN592AX6 250422. This issue affects the function system of the component wmapd Daemon. Executing a manipulation can lead to os command injection. It is possible to  |
| CVE-2026-103849 | 10.0 | n/a | Adobe Commerce is affected by an Improper Neutralization of Special Elements Used in a Template Engine vulnerability that could result in arbitrary code execution in the context of the current user, p |
| CVE-2026-110130 | 10.0 | n/a | Dockhand before 1.0.45 contains an authentication bypass in which the global auth hook skips authentication for any path ending in a static-asset extension such as .js, including /api/* routes, and th |
| CVE-2026-48382 | 10.0 | n/a | Adobe Experience Manager is affected by an Incorrect Authorization vulnerability that could result in arbitrary code execution in the context of the current user, potentially gaining elevated access o |
| CVE-2026-48383 | 10.0 | n/a | Adobe Experience Manager is affected by an Incorrect Authorization vulnerability that could result in arbitrary code execution in the context of the current user, potentially gaining elevated access o |
| CVE-2026-109108 | 9.9 | 2.3% | A security vulnerability has been detected in Wavlink WL-WN530BE1-A 251117. This affects the function popen of the file /cgi-bin/uploadVpn.cgi. Such manipulation of the argument Type leads to os comma |
| CVE-2026-109157 | 9.9 | n/a | A vulnerability was found in TRENDnet TEW-432BRP 3.10B20. Affected by this vulnerability is the function formTcpipSetup of the file /goform/formTcpipSetup. Performing a manipulation of the argument Na |
| CVE-2026-92909 | 9.8 | n/a | Adobe Commerce is affected by an Incorrect Authorization vulnerability that could result in arbitrary code execution in the context of the current user. An attacker could exploit this vulnerability to |
| CVE-2026-63146 | 9.8 | n/a | Omnispace Agora Project before 26.10.0 contains a code injection vulnerability where unescaped, attacker-controlled values are written into the config.inc.php configuration file during installation th |
| CVE-2026-49950 | 9.8 | n/a | Xorbits Xoscar through 0.11.2 contains an unauthenticated deserialization vulnerability that allows remote attackers to execute arbitrary code by sending crafted data over the actor-pool TCP channel.  |
| CVE-2026-93388 | 9.8 | n/a | The Printcart Store (PCDesigner / NB Designer) plugin for WooCommerce is vulnerable to unauthenticated arbitrary file upload leading to remote code execution in all versions up to, and including, 2.9. |
| CVE-2026-110002 | 9.8 | n/a | The Snazzy Social Media Feed plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 2.5 via the (file scope) function. This is due to missing WordPress boots |
| CVE-2026-97657 | 9.8 | n/a | The Abandoned Cart Pro for WooCommerce plugin for WordPress is vulnerable to Authentication Bypass via Malleable Encryption and Bypassable HMAC in all versions up to, and including, 10.8.0. This is du |
| CVE-2026-97668 | 9.8 | n/a | The Abandoned Cart Pro for WooCommerce plugin for WordPress is vulnerable to SQL Injection via the guest cart persistent meta_value in all versions up to, and including, 10.8.0 due to insufficient esc |
| CVE-2026-104800 | 9.8 | n/a | The AGE-GATE plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 1.0 via the 'width (and height)' parameter parameter. This is due to missing authenticati |
| CVE-2026-87855 | 9.8 | n/a | The JTL-Connector for WooCommerce plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 2.4.3 via the saveImage() function. This is due to the startSession( |
| CVE-2026-104748 | 9.8 | n/a | The SimpleForm – Form Maker to Chat Apps with Quiz, Poll and Multi Lead Notifications plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 3.10.0 This is du |
| CVE-2026-108971 | 9.6 | 0.2% | A flaw has been found in D-Link DCS-930L B1.08B4. This impacts the function mpfd_decode of the file bootloader_region.bin of the component Emergency HTTP Recovery Server. Executing a manipulation of t |
| CVE-2026-63353 | 9.6 | n/a | Affected devices do not properly sanitize comment fields contained in imported trace files before rendering them on the Trace page.

This could allow an attacker to social engineer an authorized use |
| CVE-2026-63354 | 9.6 | n/a | Affected devices do not properly validate and sanitize visual marker data contained in imported CSV trace files before rendering it on the Trace page.

This could allow an attacker to social enginee |
| CVE-2026-106620 | 9.6 | n/a | ColdFusion is affected by an Incorrect Authorization vulnerability that could result in a Security feature bypass. A low-privileged attacker could leverage this vulnerability to bypass security measur |
| CVE-2026-100133 | 9.3 | n/a | Adobe Commerce is affected by a stored Cross-Site Scripting (XSS) vulnerability that could be abused by an attacker to inject malicious scripts into vulnerable form fields. Malicious JavaScript may be |
| CVE-2026-91013 | 9.3 | n/a | Adobe Commerce is affected by a stored Cross-Site Scripting (XSS) vulnerability that could be abused by an attacker to inject malicious scripts into vulnerable form fields. Malicious JavaScript may be |
| CVE-2026-106629 | 9.3 | n/a | Adobe Experience Manager is affected by a stored Cross-Site Scripting (XSS) vulnerability that could be abused by an attacker to inject malicious scripts into vulnerable form fields. Malicious JavaScr |
| CVE-2026-106630 | 9.3 | n/a | Adobe Experience Manager is affected by a stored Cross-Site Scripting (XSS) vulnerability that could be abused by an attacker to inject malicious scripts into vulnerable form fields. Malicious JavaScr |
| CVE-2026-83662 | 9.3 | n/a | Adobe Experience Manager is affected by a reflected Cross-Site Scripting (XSS) vulnerability. An attacker could exploit this vulnerability to inject malicious scripts into a web page, potentially gain |
| CVE-2026-90530 | 9.3 | n/a | ColdFusion RDS is affected by an Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal') vulnerability that could lead to arbitrary file system read. An attacker could exploit t |
| CVE-2026-44415 | 9.1 | n/a | Affected systems do not properly restrict access to internal APIs and paths for authenticated users. This could allow an authenticated remote attacker to access sensitive internal information, which i |
| CVE-2026-74040 | 9.1 | n/a | Wazuh versions from 3.9.0 before 4.14.8 contain an arbitrary file overwrite vulnerability in MasterHandler.process_files_from_worker allowing a cluster worker to overwrite protected master files. Atta |
| CVE-2026-74041 | 9.1 | n/a | Wazuh 4.14.3 before 4.14.8 contains a case-sensitivity mismatch between the ossec.conf validator and wazuh-logcollector that bypasses remote-command validation. Authenticated users with manager:update |
| CVE-2026-92464 | 9.1 | n/a | Adobe Commerce is affected by an Improper Input Validation vulnerability that could result in arbitrary code execution in the context of the current user. An attacker with high privileges could exploi |
| CVE-2026-93895 | 9.1 | n/a | IBM WebSphere Application Server - Liberty 20.0.0.12 through 26.0.0.10 could allow an unauthenticated remote attacker to bypass access controls configured on gRPC service methods. |
| CVE-2026-93909 | 9.1 | n/a | IBM WebSphere Application Server - Liberty 17.0.0.3 through 26.0.0.10 is vulnerable by an authentication bypass vulnerability when samlWeb-2.0 feature is enabled. |
| CVE-2026-92097 | 9.1 | n/a | The Click to Chat for WhatsApp plugin for WordPress is vulnerable to Arbitrary Shortcode Execution in versions up to, and including, 4.44 This is due to the greetings_dialog() function building the {u |
| CVE-2026-59241 | 8.8 | n/a | A vulnerability has been identified in SIMATIC WinCC V7.5 (All versions), SIMATIC WinCC V8.0 (All versions < V8.0 Update 11), SIMATIC WinCC V8.1 (All versions < V8.1 Update 7). The affected applicatio |
| CVE-2026-89196 | 8.8 | n/a | A vulnerability has been identified in RUGGEDCOM CROSSBOW (All versions < V6.0). Affected devices do not properly validate or sanitize input in facility names processed during the Bulk Import/Export w |
| CVE-2026-89197 | 8.8 | n/a | A vulnerability has been identified in RUGGEDCOM CROSSBOW (All versions < V6.0). Affected devices do not properly validate or sanitize input in the Value field of notification conditions processed dur |
| CVE-2026-109520 | 8.8 | n/a | A flaw has been found in Colorful iGameCenter 2.0.0.82. Affected by this vulnerability is the function MmMapIoSpace in the library AMDRyzenMasterDriver.sys of the component Dispatch Handler. This mani |
| CVE-2026-109676 | 8.8 | n/a | FreeRDP from 3.0.0-beta1 before 3.32.0 contains a use-after-free vulnerability in smartcard handling that allows attackers to access a freed smartcard handle object after an invalid connect operation. |
| CVE-2026-104085 | 8.8 | n/a | odt2spip plugin for SPIP before 4.4.0 contains an OS command injection vulnerability that allows authenticated authors to execute arbitrary commands by uploading a document with a maliciously crafted  |
| CVE-2026-100220 | 8.8 | n/a | Heap-based buffer overflow in Windows Media Video Decoder allows an unauthorized attacker to execute code over a network. |
| CVE-2026-109428 | 8.8 | n/a | Mistral Vibe before 2.25.5 contains a permission validation bypass vulnerability that allows attackers to execute unauthorized commands by exploiting a parsing discrepancy between tree-sitter-bash and |
| CVE-2026-109429 | 8.8 | n/a | Mistral Vibe before 2.25.4 contains a command permission gate bypass vulnerability that allows attackers to execute arbitrary commands by hiding a command substitution inside a single-quoted variable  |
| CVE-2026-110202 | 8.8 | n/a | Roo Code through 3.54.0 contains a command approval bypass vulnerability in getCommandDecision() that allows attackers to auto-approve denied shell commands by prefixing them with a bare >& redirect.  |
| CVE-2026-110203 | 8.8 | n/a | Roo Code through 3.54.0 contains a command approval bypass vulnerability that allows attackers to auto-approve denied shell commands by abusing quote-masking regex in parseCommandLine(). Attackers can |
| CVE-2026-110205 | 8.8 | n/a | Roo Code through 3.54.0 contains a command approval bypass vulnerability in parseCommandLine() that discards command substitutions placed next to * or ? glob characters. Attackers using indirect promp |
| CVE-2026-110206 | 8.8 | n/a | Roo Code through 3.54.0 contains a command approval bypass vulnerability in parseCommandLine() that allows attackers to auto-approve arbitrary shell commands by placing a command substitution in comma |
| CVE-2026-110207 | 8.8 | n/a | Wukong AICRM through 20260610 contains a missing authorization vulnerability that allows any authenticated user to call user, role, department and agent administration APIs because no administrator ch |
| CVE-2026-110215 | 8.8 | n/a | youlai-boot through 2.21.1 contains a missing authorization vulnerability that allows authenticated users to assign arbitrary menu and button permissions to roles via PUT /api/v1/roles/{roleId}/menus. |
| CVE-2026-110238 | 8.8 | n/a | Rapyd Admin from 9.0.0 before 9.20.0 contains an authorization bypass vulnerability that allows authenticated company members with the default customer role to modify or delete arbitrary user accounts |
| CVE-2026-70580 | 8.8 | n/a | Missing authentication for critical function in Windows Credential Guard allows an authorized attacker to perform spoofing locally. |
| CVE-2026-63154 | 8.8 | n/a | Omnispace Agora Project before 26.10.0 contains a SQL identifier injection vulnerability that allows a space administrator to escalate privileges by supplying caller-controlled agoraFields[] names as  |
| CVE-2026-63161 | 8.8 | n/a | Omnispace Agora Project before 26.10.0 contains a session fixation vulnerability that allows remote attackers to hijack authenticated sessions by planting a known session identifier in a victim's brow |
| CVE-2026-63162 | 8.8 | n/a | Omnispace Agora Project before 26.10.0 contains a path traversal vulnerability that allows attackers to write arbitrary files outside the intended temporary directory by supplying an unanchored tmpFol |
| CVE-2026-110444 | 8.8 | n/a | TeamPlus Messenger developed by Teamplus Technology has a Code Injection vulnerability. Unauthenticated remote attackers can trick users into opening a crafted link to inject and execute arbitrary Jav |
| CVE-2026-110445 | 8.8 | n/a | TeamPlus Messenger developed by Teamplus Technology has a Code Injection vulnerability. Unauthenticated remote attackers can trick users into interacting with crafted content to inject and execute arb |
| CVE-2026-92911 | 8.7 | n/a | Adobe Commerce is affected by a stored Cross-Site Scripting (XSS) vulnerability that could be abused by a low-privileged attacker to inject malicious scripts into vulnerable form fields. Malicious Jav |
| CVE-2026-95631 | 8.7 | n/a | Adobe Commerce is affected by an Improper Input Validation vulnerability that could result in arbitrary code execution in the context of the current user. An attacker with high privileges could exploi |
| CVE-2026-101294 | 8.7 | n/a | IBM WebSphere Application Server - Liberty 17.0.0.3 through 26.0.0.10 and IBM WebSphere Application Server 8.5, and 9.0 could allow a remote attacker to bypass cryptographic signature verification due |
| CVE-2026-13138 | 8.6 | 0.2% | Client-Side Enforcement of Server-Side Security vulnerability in Divasoft Software and E-Commerce Inc. Biletiva Ticketing Platform allows Manipulating State.

This issue affects Biletiva Ticketing Pla |
| CVE-2026-106616 | 8.6 | n/a | ColdFusion is affected by an Improper Restriction of XML External Entity Reference ('XXE') vulnerability that could lead to arbitrary file system read. An attacker could exploit this vulnerability to  |
| CVE-2026-95634 | 8.6 | n/a | CAI Content Credentials is affected by a Server-Side Request Forgery (SSRF) vulnerability that could result in privilege escalation. Exploitation of this issue does not require user interaction. Scope |
| CVE-2026-109961 | 8.5 | n/a | Froxlor 0.10.0 before 2.3.14 contains a newline injection vulnerability that allows authenticated customers to inject arbitrary entries into the root-owned NSS group database via the unvalidated addit |
| CVE-2026-71385 | 8.4 | n/a | ColdFusion is affected by an Incorrect Authorization vulnerability that could result in arbitrary code execution in the context of the current user. An attacker with high privileges could exploit this |
| CVE-2026-75995 | 8.4 | n/a | ColdFusion is affected by an Improper Input Validation vulnerability that could result in arbitrary code execution in the context of the current user. An attacker with high privileges could exploit th |
| CVE-2026-109519 | 8.3 | n/a | A vulnerability was detected in YouTransfer up to 0.0.7/1.0.6/1.1.0. Affected is an unknown function of the file /settings/template of the component Template Rendering. The manipulation results in pat |
| CVE-2026-92908 | 8.3 | n/a | Adobe Commerce is affected by an Incorrect Authorization vulnerability that could result in a Security feature bypass. A low-privileged attacker could leverage this vulnerability to bypass security me |
| CVE-2026-102073 | 8.2 | n/a | A vulnerability has been identified in APOGEE MBC (PPC) (BACnet) (All versions), APOGEE MBC (PPC) (P2 Ethernet) (All versions), APOGEE MEC (PPC) (BACnet) (All versions), APOGEE MEC (PPC) (P2 Ethernet) |
| CVE-2026-105443 | 8.2 | n/a | IBM WebSphere Application Server - Liberty 17.0.0.3 through 26.0.0.10 has insufficient isolation between servers sharing an install. |
| CVE-2026-105898 | 8.2 | n/a | ColdFusion is affected by an Incorrect Authorization vulnerability that could result in arbitrary code execution in the context of the current user. A low-privileged attacker could exploit this vulner |
| CVE-2026-93905 | 8.2 | n/a | IBM WebSphere Application Server - Liberty 17.0.0.3 through 26.0.0.10 could allow an unauthenticated remote attacker to corrupt the persisted status of batch job instances. |
| CVE-2026-110097 | 8.1 | n/a | Ikaros 1.2.0 through 1.2.5 contains an authentication bypass vulnerability that allows attackers with a valid password to skip TOTP verification by reusing the login temp token. Attackers can present  |
| CVE-2026-110108 | 8.1 | n/a | MateCloud through 5.0.8 contains a missing authorization vulnerability that allows any authenticated user to manage object storage by calling the unprotected /api/v1/admin/storage endpoints in Storage |
| CVE-2026-110124 | 8.1 | n/a | FastBee through 2.1.0 contains an insecure direct object reference vulnerability in DeviceController that allows authenticated low-privilege users to read and modify other tenants' devices by supplyin |
| CVE-2026-110112 | 8.1 | n/a | Dockhand before 1.0.50 contains a privilege escalation vulnerability that allows users from another tenant to gain admin access because OIDC iss, aud, nonce and exp claims are not validated. Attackers |
| CVE-2026-110211 | 8.1 | n/a | iFlytek SkillHub through 0.2.22 contains a missing authorization vulnerability that allows any authenticated user to permanently delete other users' skills via DELETE /api/cli/v1/skills/{namespace}/{s |
| CVE-2026-92922 | 8.1 | n/a | Adobe Commerce is affected by a stored Cross-Site Scripting (XSS) vulnerability that could be abused by a high-privileged attacker to inject malicious scripts into vulnerable form fields. Malicious Ja |
| CVE-2026-63152 | 8.1 | n/a | Omnispace Agora Project before 26.10.0 contains a second-order SQL injection vulnerability that allows authenticated attackers to inject malicious SQL via the _idCategoryFilter parameter, which is per |
| CVE-2026-63153 | 8.1 | n/a | Omnispace Agora Project before 26.10.0 contains a broken access control vulnerability in setAffectations() that allows authenticated attackers to insert access-right records for a caller-supplied targ |
| CVE-2026-63165 | 8.1 | n/a | Omnispace Agora Project before 26.10.0 contains a SQL injection vulnerability in the calendar functionality that allows attackers to inject malicious SQL by manipulating the sortEvents parameter, whic |
| CVE-2026-63174 | 8.1 | n/a | Omnispace Agora Project before 26.10.0 contains a broken access control vulnerability that allows a space administrator to assign users into spaces outside their authority because the spaceAffectList  |
| CVE-2026-104995 | 8.1 | n/a | The BP Profile Search plugin for WordPress is vulnerable to Local File Inclusion in versions up to, and including, 5.9 via the 'ajax_template' value parsed from the client-controlled 'bps_directory' c |
| CVE-2026-17092 | 8.1 | n/a | The Directorist: AI-Powered Business Directory, Listings & Classified Ads plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 8.10.2.1. This is due to the  |
| CVE-2026-103367 | 8.1 | n/a | The ShopMagic – email automation for WordPress plugin for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 4.9.0 via the 'billing_address.first_name' parameter par |
| CVE-2026-104909 | 8.1 | n/a | The Mang Board plugin for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 2.4.3 via the '<mode>_type (e.g. foo_type)' parameter parameter. This makes it possible  |
| CVE-2026-35001 | 7.8 | 0.2% | OpenS100 through commit daa35b contains an integer overflow vulnerability in the S-102 Bathymetric Surface parser that allows remote attackers to cause a heap-based buffer overflow by opening a crafte |
| CVE-2026-102233 | 7.8 | n/a | Missing authorization in Visual Studio Code allows an unauthorized attacker to bypass a security feature locally. |
| CVE-2026-110233 | 7.8 | n/a | Rovr through 0.10.3 on Windows contains an OS command injection vulnerability that allows attackers to execute commands by crafting malicious file names. Attackers can deliver a file named with shell  |
| CVE-2026-103830 | 7.8 | n/a | Substance3D - Stager is affected by a Stack-based Buffer Overflow vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires us |
| CVE-2026-103832 | 7.8 | n/a | Substance3D - Stager is affected by an out-of-bounds write vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires user inte |
| CVE-2026-103833 | 7.8 | n/a | Substance3D - Stager is affected by an out-of-bounds write vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires user inte |
| CVE-2026-103834 | 7.8 | n/a | Substance3D - Stager is affected by an out-of-bounds write vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires user inte |
| CVE-2026-103835 | 7.8 | n/a | Substance3D - Stager is affected by an out-of-bounds write vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires user inte |
| CVE-2026-103836 | 7.8 | n/a | Substance3D - Stager is affected by an out-of-bounds write vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires user inte |
| CVE-2026-103837 | 7.8 | n/a | Substance3D - Stager is affected by an out-of-bounds write vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires user inte |
| CVE-2026-103838 | 7.8 | n/a | Substance3D - Stager is affected by an out-of-bounds write vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires user inte |
| CVE-2026-103839 | 7.8 | n/a | Substance3D - Stager is affected by an out-of-bounds write vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires user inte |
| CVE-2026-103840 | 7.8 | n/a | Substance3D - Stager is affected by an out-of-bounds read vulnerability when parsing a crafted file, which could result in a read past the end of an allocated memory structure. An attacker could lever |
| CVE-2026-103851 | 7.8 | n/a | Substance3D - Stager is affected by a Stack-based Buffer Overflow vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires us |
| CVE-2026-106614 | 7.8 | n/a | ColdFusion is affected by an Incorrect Authorization vulnerability that could result in arbitrary code execution in the context of the current user. A low-privileged attacker could exploit this vulner |
| CVE-2026-83965 | 7.8 | n/a | Substance3D - Sampler is affected by a Stack-based Buffer Overflow vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires u |
| CVE-2026-83966 | 7.8 | n/a | Substance3D - Sampler is affected by an out-of-bounds write vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires user int |
| CVE-2026-95641 | 7.8 | n/a | Photoshop Desktop is affected by an out-of-bounds write vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires user interac |
| CVE-2026-72895 | 7.7 | n/a | A vulnerability has been identified in SIMATIC IPC BX-21A (All versions < V31.01.13), SIMATIC IPC RW-543A (All versions < V1.1.4), SIMATIC IPC227G / IPC277G / IPC277G PRO / IPC327G / IPC377G (All vers |
| CVE-2026-109960 | 7.7 | n/a | Froxlor 2.0.0 before 2.3.14 contains a stored cross-site scripting vulnerability that allows authenticated customers to inject HTML and JavaScript by setting a malicious theme value via customer_index |
| CVE-2026-102231 | 7.7 | n/a | Improper resolution of path equivalence in Visual Studio Code allows an unauthorized attacker to bypass a security feature locally. |
| CVE-2026-106634 | 7.7 | n/a | Adobe Experience Manager is affected by an Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal') vulnerability that could result in arbitrary file system write. A low-privileg |
| CVE-2026-105994 | 7.7 | n/a | ColdFusion is affected by an Incorrect Authorization vulnerability that could result in a Security feature bypass. A low-privileged attacker could leverage this vulnerability to bypass security measur |
| CVE-2026-34633 | 7.7 | n/a | ColdFusion is affected by a Server-Side Request Forgery (SSRF) vulnerability that could result in privilege escalation. A low-privileged attacker could exploit this vulnerability to gain elevated acce |
| CVE-2026-75748 | 7.6 | n/a | ColdFusion is affected by a Server-Side Request Forgery (SSRF) vulnerability that could result in privilege escalation. An attacker with high privileges could exploit this vulnerability to gain elevat |
| CVE-2026-85114 | 7.5 | n/a | A vulnerability has been identified in .NET Client Library for SIMATIC S7 Webserver API (All versions < V3.3.61). Affected applications do not properly validate filenames received from remote servers  |
| CVE-2026-89201 | 7.5 | n/a | A vulnerability has been identified in RUGGEDCOM CROSSBOW (All versions < V6.0). Affected devices do not properly validate or sanitize input in device group or facility names processed during the Bulk |
| CVE-2026-109967 | 7.5 | n/a | yt-dlp-web-ui through 4.0.0 contains a NULL pointer dereference vulnerability in the Service.Formats JSON-RPC method that allows remote unauthenticated attackers to crash the server. Attackers can sen |
| CVE-2026-74034 | 7.5 | n/a | Wazuh from 4.1.0 before 4.14.8 contains a missing origin check in wm_agent_upgrade that allows enrolled agents to issue upgrade_custom commands with attacker-controlled file_path. Attackers can inject |
| CVE-2026-110102 | 7.5 | n/a | Powerlevel10k through 1.20.0 contains an insecure download vulnerability in the gitstatus/install script that disables TLS certificate verification with curl -k and skips integrity checks when no SHA- |
| CVE-2026-110115 | 7.5 | n/a | Risesoft Digital-Infrastructure 9.6.5 through 9.6.11 contains a path traversal vulnerability in the fileManager Y9FileController.retrieveFileStream handler that allows unauthenticated attackers to rea |
| CVE-2026-110128 | 7.5 | n/a | fuint through commit 4c4bc8a contains a missing authentication vulnerability that allows unauthenticated attackers to retrieve any member's order details via the /clientApi/order/detail endpoint. Atta |
| CVE-2026-110111 | 7.5 | n/a | Xen Orchestra before 6.9.0 contains an improper access control vulnerability that allows any authenticated user to become global administrator by abusing the unprotected vm.importFromEsxi and vm.impor |
| CVE-2026-105442 | 7.5 | n/a | IBM WebSphere Application Server 8.5, and 9.0 and IBM WebSphere Application Server - Liberty 17.0.0.3 through 26.0.0.10 Liberty could allow a remote attacker to cause a denial of service caused by an  |
| CVE-2026-105900 | 7.5 | n/a | ColdFusion is affected by an Improper Input Validation vulnerability that could result in an application denial-of-service. An attacker could exploit this vulnerability to crash the application, leadi |
| CVE-2026-106623 | 7.5 | n/a | ColdFusion is affected by an Incorrect Authorization vulnerability that could lead to disclosure of sensitive memory. An attacker could leverage this vulnerability to disclose sensitive information. E |
| CVE-2026-75996 | 7.5 | n/a | ColdFusion is affected by an Uncontrolled Resource Consumption vulnerability that could lead to application denial-of-service. An attacker could exploit this vulnerability to exhaust system resources, |
| CVE-2026-100113 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Input Validation vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability to bypass security measu |
| CVE-2026-100114 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Access Control vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability to bypass security measure |
| CVE-2026-100115 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Access Control vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability to bypass security measure |
| CVE-2026-100117 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Input Validation vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability to bypass security measu |
| CVE-2026-100118 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Certificate Validation vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability to bypass security |
| CVE-2026-100119 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Input Validation vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability to bypass security measu |
| CVE-2026-100120 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Input Validation vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability to bypass security measu |
| CVE-2026-100121 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Certificate Validation vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability to bypass security |
| CVE-2026-100122 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Certificate Validation vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability to bypass security |
| CVE-2026-100123 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Certificate Validation vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability to bypass security |
| CVE-2026-100124 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Input Validation vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability to bypass security measu |
| CVE-2026-100135 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Input Validation vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability to bypass security measu |
| CVE-2026-100136 | 7.5 | n/a | CAI Content Credentials is affected by an Integer Overflow or Wraparound vulnerability that could result in an application denial-of-service. An attacker could exploit this vulnerability to crash the  |
| CVE-2026-100137 | 7.5 | n/a | CAI Content Credentials is affected by an Uncontrolled Resource Consumption vulnerability that could lead to application denial-of-service. An attacker could exploit this vulnerability to exhaust syst |
| CVE-2026-100138 | 7.5 | n/a | CAI Content Credentials is affected by an Uncontrolled Resource Consumption vulnerability that could lead to application denial-of-service. An attacker could exploit this vulnerability to exhaust syst |
| CVE-2026-100139 | 7.5 | n/a | CAI Content Credentials is affected by an Uncontrolled Resource Consumption vulnerability that could lead to application denial-of-service. An attacker could exploit this vulnerability to exhaust syst |
| CVE-2026-103296 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Verification of Cryptographic Signature vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability t |
| CVE-2026-103297 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Verification of Cryptographic Signature vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability t |
| CVE-2026-104345 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Input Validation vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability to bypass security measu |
| CVE-2026-105902 | 7.5 | n/a | CAI Content Credentials is affected by an Uncontrolled Resource Consumption vulnerability that could lead to application denial-of-service. An attacker could exploit this vulnerability to exhaust syst |
| CVE-2026-106627 | 7.5 | n/a | CAI Content Credentials is affected by an Uncontrolled Resource Consumption vulnerability that could lead to application denial-of-service. An attacker could exploit this vulnerability to exhaust syst |
| CVE-2026-95632 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Verification of Cryptographic Signature vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability t |
| CVE-2026-95633 | 7.5 | n/a | CAI Content Credentials is affected by an Improper Verification of Cryptographic Signature vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability t |
| CVE-2026-103423 | 7.5 | n/a | The Booking Package plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 1.7.29 This is due to the plugin not properly verifying that a user is authorized t |
| CVE-2026-104749 | 7.5 | n/a | The Bit integrations – Form Integration, Webhook, Spreadsheets, CRM, LMS & Email Automation plugin for WordPress is vulnerable to Privilege Escalation via Log Re-execution in all versions up to, and i |
| CVE-2026-104767 | 7.5 | n/a | The Membership & User Roles for WooCommerce (Automatic Role Changer) plugin for WordPress is vulnerable to Privilege Escalation in versions up to, and including, 20260828. This is due to the `maybe_ad |
| CVE-2026-102251 | 7.5 | n/a | The Abandoned Cart Pro for WooCommerce plugin for WordPress is vulnerable to generic SQL Injection via the 'validate' parameter in all versions up to, and including, 10.8.0 due to insufficient escapin |
| CVE-2026-78193 | 7.5 | n/a | The JTL-Connector for WooCommerce plugin for WordPress is vulnerable to time-based SQL Injection via 'product.push' Identity Endpoint in all versions up to, and including, 2.4.3 due to insufficient es |
| CVE-2026-95808 | 7.5 | n/a | The Form Maker by 10Web – Mobile-Friendly Drag & Drop Contact Form Builder plugin for WordPress is vulnerable to blind SQL Injection via the 'inputs' parameter in all versions up to, and including, 1. |
| CVE-2026-96661 | 7.5 | n/a | The Gmedia Photo Gallery plugin for WordPress is vulnerable to time-based SQL Injection via the 'gmedia__in' parameter in all versions up to, and including, 1.25.1 due to insufficient escaping on the  |
| CVE-2026-103366 | 7.5 | n/a | The Appointment Booking Plugin – LatePoint | Calendar & Scheduling for WordPress plugin for WordPress is vulnerable to Insecure Direct Object Reference in versions up to, and including, 5.7.3 via the  |
| CVE-2026-110284 | 7.5 | n/a | The LifterLMS – WP LMS for eLearning, Online Courses, & Quizzes plugin for WordPress is vulnerable to Local File Inclusion in versions up to, and including, 10.3.1 via attacker-controlled attributes o |
| CVE-2026-78556 | 7.4 | n/a | A vulnerability has been identified in Industrial Edge App Publisher (All versions < V1.27.9). The affected software does not properly validate the server certificate when initiating a TLS connection. |
| CVE-2026-63149 | 7.4 | n/a | Omnispace Agora Project before 26.10.0 contains an insecure randomness vulnerability that allows attackers to predict temporary or default account passwords generated by Txt::defaultPassword() using P |
| CVE-2026-63158 | 7.4 | n/a | Omnispace Agora Project before 26.10.0 contains an authentication bypass vulnerability that allows attackers possessing a user's stored bcrypt password hash to authenticate as that user without knowin |
| CVE-2026-63160 | 7.4 | n/a | Omnispace Agora Project before 26.10.0 contains a vulnerability where the persistent remember-me token is stored verbatim server-side, making the stored value identical to the bearer credential held i |
| CVE-2026-95695 | 7.4 | n/a | IBM WebSphere Application Server - Liberty 20.0.0.12 through 26.0.0.10 could allow a remote attacker to bypass security restrictions due to incorrect authorization. |
| CVE-2026-100163 | 7.4 | n/a | The Appointment Booking Plugin – LatePoint | Calendar & Scheduling for WordPress plugin for WordPress is vulnerable to Authentication Bypass in versions up to, and including, 5.7.2 via the OsCustomerH |
| CVE-2026-108964 | 7.3 | 0.4% | A vulnerability was found in SourceCodester Performance Indicator System 1.0. This affects an unknown part of the file /opils/admin/addproduct.php. Performing a manipulation of the argument prodcatego |
| CVE-2026-108966 | 7.3 | 0.4% | A vulnerability was identified in SourceCodester Performance Indicator System 1.0. This issue affects some unknown processing of the file /opils/staff/product.php. The manipulation of the argument Cat |
| CVE-2026-108967 | 7.3 | 0.4% | A security flaw has been discovered in SourceCodester Performance Indicator System 1.0. Impacted is an unknown function of the file /opils/staff/edit_credit.php. The manipulation of the argument credi |
| CVE-2026-108968 | 7.3 | 0.4% | A weakness has been identified in SourceCodester Performance Indicator System 1.0. The affected element is an unknown function of the file /opils/staff/sales_history.php. This manipulation of the argu |
| CVE-2026-108970 | 7.3 | 0.4% | A vulnerability was detected in itsmeravitejak Online-Examination-System up to e6208e630b14657999bbfe4c9912302d2a1e2449. This affects the function MySQLDB::addNewUser of the file include/database.php  |
| CVE-2026-108972 | 7.3 | 0.7% | A vulnerability was found in SourceCodester Human Resource Management System 1.0. Affected by this vulnerability is the function session_start of the file controller/employee.php of the component Empl |
| CVE-2026-108974 | 7.3 | 0.3% | A vulnerability was identified in SourceCodester E-Learning System 1.0. This affects the function save_users of the file /classes/Users.php?f=save. Such manipulation of the argument img leads to unres |
| CVE-2026-108975 | 7.3 | 0.3% | A security flaw has been discovered in SourceCodester Library Management System 1.0. This vulnerability affects the function move_uploaded_file of the file admin/add_admin.php. Performing a manipulati |
| CVE-2026-109115 | 7.3 | 0.3% | A vulnerability was found in AdithyaYelloju Restaurant-Management-System up to 7f0e7e84255e8fcfd488e83f8f91451bbbff6b9c. This issue affects some unknown processing of the file User/forgot3.php of the  |
| CVE-2026-109116 | 7.3 | 0.3% | A vulnerability was determined in AdithyaYelloju Restaurant-Management-System up to 7f0e7e84255e8fcfd488e83f8f91451bbbff6b9c. Impacted is the function mysqli_query of the component Order Management. E |
| CVE-2026-109403 | 7.3 | n/a | A vulnerability was determined in conductor-oss conductor up to 3.32.5. Affected by this vulnerability is the function A2AService.getAgentCard of the file ai/src/main/java/org/conductoross/conductor/a |
| CVE-2026-109405 | 7.3 | n/a | A security flaw has been discovered in conductor-oss conductor up to 3.33.0-rc10. This affects the function KafkaPublishTask.start of the file kafka/src/main/java/com/netflix/conductor/contribs/tasks/ |
| CVE-2026-109522 | 7.3 | n/a | A vulnerability has been found in girishsaraf Online-Appointment-Booking-System up to f427b4757128ca253d33d0cc4e87bbb9c999a4d5. Affected is an unknown function of the file Admin/deleteclinic.php of th |
| CVE-2026-109523 | 7.3 | n/a | A vulnerability was found in girishsaraf Online-Appointment-Booking-System up to f427b4757128ca253d33d0cc4e87bbb9c999a4d5. Affected by this vulnerability is an unknown functionality of the file Admin/ |
| CVE-2026-109525 | 7.3 | n/a | A vulnerability was identified in girishsaraf Online-Appointment-Booking-System up to f427b4757128ca253d33d0cc4e87bbb9c999a4d5. This affects an unknown part of the file changebookingstatus.php of the  |
| CVE-2026-109605 | 7.3 | n/a | A security vulnerability has been detected in SourceCodester Simple Cafe Billing System 1.0. This affects the function Action::save_user of the file admin_class.php of the component User Management. T |
| CVE-2026-110025 | 7.3 | n/a | A flaw has been found in slackero phpwcms up to 1.9.49/1.12.3. This issue affects some unknown processing of the file include/inc_front/content/cnt23.article.inc.php of the component Extension Check.  |
| CVE-2026-109607 | 7.3 | n/a | A flaw has been found in SourceCodester Online Exam System 1.0. Affected is an unknown function of the file adminpanel/admin/query/loginExe.php of the component Login Endpoint. This manipulation of th |
| CVE-2026-109620 | 7.3 | n/a | A vulnerability has been found in SourceCodester Online Reviewer System 1.0. Affected by this vulnerability is the function PDO::prepare of the file login/index.php. Such manipulation of the argument  |
| CVE-2026-110237 | 7.3 | n/a | Vifm 0.8.1-beta through 0.14.4 reuses a pre-existing IPC FIFO in the shared temporary directory without checking ownership, allowing local users to execute commands as another user. Attackers can pre- |
| CVE-2026-88204 | 7.3 | n/a | Improper neutralization of input during web page generation ('cross-site scripting') in Microsoft Office SharePoint allows an authorized attacker to perform spoofing over a network. |
| CVE-2026-102007 | 7.2 | 0.2% | The Bit integrations – Form Integration, Webhook, Spreadsheets, CRM, LMS & Email Automation plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'field mapped to notification_cont |
| CVE-2026-102562 | 7.2 | 0.2% | The AcyMailing plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the customField[] parameter of the public frontusers::subscribe endpoint in versions up to, and including, 11.1.0.  |
| CVE-2026-74036 | 7.2 | n/a | Wazuh from 4.3.0 before 4.14.8 contains a remote code execution vulnerability where SCA policy trust is determined by file path rather than configuration source. Attackers controlling a manager can wr |
| CVE-2026-74037 | 7.2 | n/a | Wazuh 4.0.0 before 4.14.8 fails to invalidate issued tokens for run_as users with zero static roles, because check_token never consults the blacklist. Attackers with revoked administrator grants can c |
| CVE-2026-92910 | 7.2 | n/a | Adobe Commerce is affected by an Incorrect Authorization vulnerability that could result in a Security feature bypass. An attacker could leverage this vulnerability to bypass security measures and gai |
| CVE-2026-103422 | 7.2 | n/a | The AnyComment plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'email' parameter in versions up to, and including, 0.3.6. This is due to insufficient input sanitization on th |
| CVE-2026-100153 | 7.2 | n/a | The NewStatPress plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'QUERY_STRING / REQUEST_URI' parameter in all versions up to, and including, 1.4.5 due to insufficient input  |
| CVE-2026-77114 | 7.2 | n/a | The Document Gallery plugin for WordPress is vulnerable to Stored Cross-Site Scripting via 'dg_thumber_webhook' Action Request Body in all versions up to, and including, 5.1.1 due to insufficient inpu |
| CVE-2026-83592 | 7.2 | n/a | The Contact Form DB for Enfold plugin for WordPress is vulnerable to Stored Cross-Site Scripting via Contact Form Field Values in all versions up to, and including, 2.0.2 due to insufficient input san |
| CVE-2026-93885 | 7.2 | n/a | The Cryptocurrency Donation Box – Bitcoin & Crypto Donations plugin for WordPress is vulnerable to Stored Cross-Site Scripting via data_object Parameter in all versions up to, and including, 2.2.13 du |
| CVE-2026-94377 | 7.2 | n/a | The Verified Reviews (Avis Vérifiés) plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'moderation' parameter in all versions up to, and including, 2.4.6 due to insufficient in |
| CVE-2026-95816 | 7.2 | n/a | The Smart Forms – when you need more than just a contact form plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'formString' parameter in all versions up to, and including, 2.6 |
| CVE-2026-97398 | 7.2 | n/a | The FV Flowplayer Video Player plugin for WordPress is vulnerable to Stored Cross-Site Scripting via 'synopsis' Shortcode Attribute in all versions up to, and including, 7.5.54.7212 due to insufficien |
| CVE-2026-101924 | 7.2 | n/a | The NewStatPress plugin for WordPress is vulnerable to Stored Cross-Site Scripting in versions up to, and including, 1.4.5 via the 'Last referrers' meta box on the plugin's Overview admin page. This i |
| CVE-2026-104764 | 7.2 | n/a | The Post Export Import with Media plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 1.17.1 via deserialization of untrusted input . This makes it possibl |
| CVE-2026-107631 | 7.2 | n/a | The Record of Consent Extension for Complianz plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'uid' parameter in all versions up to, and including, 2.5 due to insufficient in |
| CVE-2026-107751 | 7.2 | n/a | The Mang Board plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'user_name' parameter in all versions up to, and including, 2.4.3 due to insufficient input sanitization and ou |
| CVE-2026-74045 | 7.1 | n/a | Wazuh from 3.12.0 before 4.14.8 contains a heap buffer overflow in fim_generate_alert() where full_log is sized from input but written bounded by OS_MAXSTR. An enrolled agent can send a crafted FIM sy |
| CVE-2026-110119 | 7.1 | n/a | Yshopmall through 2.0.0 contains an insecure direct object reference vulnerability in the member address API that allows authenticated members to read, overwrite and delete other members' shipping add |
| CVE-2026-110123 | 7.1 | n/a | Makunet maku-boot 4.3.0 through 5.0.0 contains a missing authorization vulnerability that allows authenticated users to read mail and SMS configurations by calling /sys/mail/config/list and /sys/sms/c |
| CVE-2026-110208 | 7.1 | n/a | Wukong AICRM through 20260610 contains a missing authorization vulnerability in the /systemConfig controller that allows any authenticated user to read the stored AI provider API key. Attackers can re |
| CVE-2026-110216 | 7.1 | n/a | youlai-boot through 2.21.1 contains a missing authorization vulnerability that allows any authenticated user to enable or disable accounts because the updateUserStatus handler lacks a @PreAuthorize ch |
| CVE-2026-110220 | 7.1 | n/a | Kubeflow Model Registry through 0.3.17 contains a server-side request forgery vulnerability that allows namespace users to steal the controller ServiceAccount token via the modelregistry.kubeflow.org/ |
| CVE-2026-110083 | 7.1 | n/a | Adobe Experience Manager is affected by an Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability that could result in a Security feature bypass. A low-priv |
| CVE-2026-110084 | 7.1 | n/a | Adobe Experience Manager is affected by an XML Injection (aka Blind XPath Injection) vulnerability that could result in a Security feature bypass. A low-privileged attacker could leverage this vulnera |
| CVE-2026-63172 | 7.1 | n/a | Omnispace Agora Project before 26.10.0 contains a broken access control vulnerability that allows a regular, non-administrative member to create user accounts by invoking the user-edit action without  |
| CVE-2026-76001 | 7.1 | n/a | ColdFusion is affected by a Server-Side Request Forgery (SSRF) vulnerability that could result in privilege escalation. A low-privileged attacker could exploit this vulnerability to gain elevated acce |
| CVE-2026-109956 | 7.0 | n/a | NLTK through 3.10.3 contains a path traversal vulnerability in WekaClassifier that allows attackers to bypass nltk.pathsec containment by supplying unvalidated model paths. Attackers controlling the m |
| CVE-2026-110236 | 7.0 | n/a | KDE Dolphin 24.08.0 through 26.08.2 contains an OS command injection vulnerability that allows attackers to execute commands by supplying crafted folder names substituted into the {path} placeholder.  |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-jpj7-7jv5-rp9j | CVE-2026-50218 | high | Akamai GPA (Guardicore Platform Agent) client on all platforms before 7.4 improperly validates... |
| GHSA-p8p9-vpf5-3ff3 | CVE-2026-50217 | medium | A use-after-free vulnerability in the Windows WFP callout driver of Akamai Guardicore Platform... |
| GHSA-vcv3-3vwp-2j63 | CVE-2026-94370 | medium | A defect in the Qt for MCUs core string handling causes heap memory corruption. When an... |
| GHSA-898m-6rc6-jhvx | CVE-2026-110457 | low | A malicious actor with access to the network and under certain conditions could exploit a Path... |
| GHSA-426c-439h-xj38 | CVE-2026-50216 | medium | An integer underflow exists in the DNS proxy component of the macOS NetworkExtension system... |
| GHSA-f7f5-358j-wfqf | CVE-2026-110459 | high | A malicious actor with access to the network could exploit an Improper Access Control... |
| GHSA-3x44-5jjf-v9pv | CVE-2026-110458 | low | A malicious actor with access to the network and under certain conditions could exploit a Path... |
| GHSA-5h53-jg3j-22gg | CVE-2026-110451 | medium | Nix before 2.35.3 and Lix before 2.95.4 on macOS allow a Seatbelt sandbox escape (for an... |
| GHSA-fg3c-hmr6-8f64 | CVE-2026-46449 | medium | The Akamai Guardicore Platform Agent (GPA) before 7.4 for macOS is affected by a local privilege... |
| GHSA-jwj4-v94m-jmqj | CVE-2026-107153 | high | Multiple smartphones provided by Rakuten Mobile, Inc. utilize AOSP test keys for their Android... |
| GHSA-f25v-4rwp-3j2q | CVE-2026-110454 | medium | A malicious actor with access to the network could exploit an Improper Access Control... |
| GHSA-x26r-fvrg-hwcw | CVE-2026-110456 | medium | A malicious actor with access to the network and under certain conditions could exploit an... |
| GHSA-3r9g-vjqw-7p76 | CVE-2026-110455 | high | A malicious actor with access to the network and under certain conditions could exploit an... |
| GHSA-q8wq-wq6x-g2wv | CVE-2026-50215 | medium | A use-after-free exists in the Windows WFP packet-capture driver shipped with Akamai Guardicore... |
| GHSA-rhmj-5mp2-rq7c | CVE-2026-106931 | high | SiteGuard Server Edition contains an OS command injection vulnerability, which may allow an... |
| GHSA-cm63-px87-wf8p | CVE-2026-110453 | medium | Nix before 2.35.3, when unsandboxed on macOS or FreeBSD, incorrectly allows connections made by... |
| GHSA-ggvw-xgw8-9cc9 | CVE-2026-110452 | medium | The multi-user installer in Nix before 2.35.3 sets the ownership of store contents to the user ... |
| GHSA-phrv-gmvx-w547 | CVE-2026-110450 | high | Nix before 2.35.3 and Lix before 2.95.4 allow privilege escalation via a repair operation because... |
| GHSA-p6r6-rxwv-wpv9 | CVE-2026-101926 | medium | The Hyyan WooCommerce Polylang Integration plugin for WordPress is vulnerable to SQL Injection... |
| GHSA-6f5c-93fp-5pqh | CVE-2026-95808 | high | The Form Maker by 10Web – Mobile-Friendly Drag & Drop Contact Form Builder plugin for WordPress... |
| GHSA-4cfq-96xx-p72v | CVE-2026-96661 | high | The Gmedia Photo Gallery plugin for WordPress is vulnerable to time-based SQL Injection via the ... |
| GHSA-wvww-4x5h-8gg3 | CVE-2026-95816 | high | The Smart Forms – when you need more than just a contact form plugin for WordPress is vulnerable... |
| GHSA-jm7p-g52m-8c6g | CVE-2026-97398 | high | The FV Flowplayer Video Player plugin for WordPress is vulnerable to Stored Cross-Site Scripting... |
| GHSA-v5gx-mchj-c82r | CVE-2026-101924 | high | The NewStatPress plugin for WordPress is vulnerable to Stored Cross-Site Scripting in versions up... |
| GHSA-848q-gjxc-xwwm | CVE-2026-93885 | high | The Cryptocurrency Donation Box – Bitcoin & Crypto Donations plugin for WordPress is vulnerable... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Lane Equipment | dragonforce | US | 2026-10-14T00:30:19.672653+00:00 |
| Company #65 | N0n | BR | 2026-10-13T23:22:05.398765+00:00 |
| The Golden Legacy Financing | qilin |  | 2026-10-13T21:13:07.350042+00:00 |
| Lambertinum Seniorenwohnanlage | Wallstreet | DE | 2026-10-13T16:52:00.329570+00:00 |
| Mantum Holding AB | Wallstreet | SE | 2026-10-13T16:52:20.476963+00:00 |
| Brunnberg & Forshed Arkitektkontor | Wallstreet | SE | 2026-10-13T16:52:39.530059+00:00 |
| Danvikshem (Stiftelsen Danviks Hospital) | Wallstreet | SE | 2026-10-13T16:52:58.465220+00:00 |
| Briab Group AB | Wallstreet | SE | 2026-10-13T16:53:19.390364+00:00 |
| Byrån för Arkitektur och Urbanism | Wallstreet | SE | 2026-10-13T16:53:38.295886+00:00 |
| Fab Support AB | Wallstreet | SE | 2026-10-13T16:53:57.244489+00:00 |
| Vendus Sweden AB | Wallstreet | SE | 2026-10-13T16:54:16.341573+00:00 |
| Spectrum Arkitekter AB | Wallstreet | SE | 2026-10-13T16:54:35.335859+00:00 |
| Englunds Konsultbyrå AB | Wallstreet | SE | 2026-10-13T16:54:56.622140+00:00 |
| Ahlqvist & Almqvist Arkitekter AB | Wallstreet | SE | 2026-10-13T16:55:15.562612+00:00 |
| KVH | everest | US | 2026-10-13T16:03:50.492992+00:00 |
| Laerdal | everest | NO | 2026-10-13T16:03:09.970747+00:00 |
| Topcon Healthcare | everest | JP | 2026-10-13T16:02:33.309308+00:00 |
| victim | sarcoma |  | 2026-10-13T15:38:22.416094+00:00 |
| Iliff, Meredith, Wildberger & Brennan, P.C | qilin | US | 2026-10-13T15:15:49.612296+00:00 |
| Company #63 | N0n |  | 2026-10-13T14:55:31.267967+00:00 |

## IOCs
### ThreatFox (recent, abuse.ch)
| Indicator | Type | Malware |
|---|---|---|
| https://fz.777wins.org/v5 | url | win.vidar |
| bbab66169a3718001fba30bb464bf48571bd82205b0e10c32ad1e78a92890838 | sha256_hash | osx.amos |
| 0056cc09cf81211b753d79839e3399935a2aa6dd0217232a294f3953b9a7fc26 | sha256_hash | unknown |
| 00d21a53eb286b90ed853b7a8c1da493905aa2318686c9c3f3f3af6175832177 | sha256_hash | unknown |
| 107a9bfb3d0bb71a33ae17a9eac844a7a7562270a09b5ccce608a78316df0222 | sha256_hash | unknown |
| https://fz.777wins.org/mh/ | url | win.vidar |
| 139.59.140.128:8443 | ip:port | elf.aisuru |
| https://fz.777wins.org/mh | url | win.vidar |
| https://fz.777wins.org/zw | url | win.vidar |
| https://fz.777wins.org/ie/ | url | win.vidar |
| https://fz.777wins.org/ie | url | win.vidar |
| https://fz.777wins.org/hy | url | win.vidar |
| 93.94.51.131:3344 | ip:port | win.remcos |
| https://fz.777wins.org/f5/ | url | win.vidar |
| https://fz.777wins.org/f5 | url | win.vidar |
| 74.201.173.193:19750 | ip:port | win.remcos |
| 155.103.71.231:4040 | ip:port | win.remcos |
| https://fz.777wins.org/o | url | win.vidar |
| https://fz.777wins.org/b | url | win.vidar |
| https://fz.777wins.org/i0/ | url | win.vidar |

### URLhaus (recent malicious URLs, abuse.ch)
| URL | Threat | Status |
|---|---|---|
| https://up.sb/lyaON/1.tar.gz | malware_download | offline |
| https://software.security-analyze.ltd/InstallAutostart.ps1 | malware_download | online |
| https://cosmical2049.com/lom3/0ad7a0bdad0aa13d | malware_download | offline |
| https://software.security-analyze.ltd/faceitAnalyze.ps1 | malware_download | online |
| https://software.security-analyze.ltd/game_library.dll | malware_download | online |
| http://175.165.86.197:60658/i | malware_download | online |
| http://42.85.165.214:60329/bin.sh | malware_download | online |
| http://42.87.170.153:57273/i | malware_download | online |
| http://62.60.226.140/files/2145124153/4qNNRF8.exe | malware_download | offline |
| http://45.198.224.158/arm6 | malware_download | online |
| http://45.198.224.158/spc | malware_download | online |
| http://175.165.86.197:60658/bin.sh | malware_download | online |
| http://125.44.32.214:49579/i | malware_download | online |
| https://software.security-analyze.ltd/dsound.dll | malware_download | online |
| http://185.113.10.26:8080/grid-master | malware_download | online |
| http://185.113.10.26:8080/grid-bot | malware_download | online |
| http://185.113.10.26:8080/bot | malware_download | online |
| http://185.113.10.26:8080/bot-armv5 | malware_download | online |
| http://185.113.10.26:8080/bot-mips | malware_download | online |
| http://185.113.10.26:8080/bot-armv7 | malware_download | online |

### MalwareBazaar (recent samples, abuse.ch)
| SHA256 | File type | Signature |
|---|---|---|
| 263a188fc5e675a5530b57c4f48a47c745240f17238cecdf657bc724bfba9832 | abuse_ch | n/a |
| 3267f01be506f81885881ac048702223ddfca3e17cf5cb4257e816fa76f05477 | c4ffeine | n/a |
| 2c7aa6ff95e09f20a1a7421abdeec3019cdb8e66ca93100e8ae9dbca919d7c08 | abuse_ch | Mirai |
| 8788eb6c4032051af3e72ac6ec3cdf0e40297a3975b6169814ce5059216de35b | abuse_ch | Mirai |
| 57e78c8fa077b2f2d31e2f7eb8c54c2275235444ff50e0df0f898b4e99dbdf6c | abuse_ch | n/a |
| 5dd792a340957190674b37ef22d48bf2ccc81748e4840a1218fd834a68899446 | abuse_ch | NanoCore |
| 2893ece9d6aadcc501dcd72c71abc49dea77f7a6ae384e749133de16ede8c0ea | lowmal3 | RemcosRAT |
| a59059bd70635bdcc42fa68254d829a44b65bd0b1f73610899c62d299c96ff4d | lowmal3 | n/a |
| 14658b46ae5b769b56c884305deda0bd18d053b46a00820de7e7c66a67732810 | lowmal3 | n/a |
| a2e7be4e9fc4f875fea6899087c59b53c9a59a3e68a3dc7779c6e22142760489 | lowmal3 | n/a |
| 3c4e63d70f2394d2d7cd9519b9aeeaec11db12fd5977160444d377ff77dc7290 | lowmal3 | n/a |
| 70d629ad65716277ecdb508170d397cbed77e40a4845c23ec6589808cd2b4811 | anonymous | Vidar |
| 62cf3226cf293b464eb9d01ea63b62a6b3a3635f17fc30cea77c78f36b1def87 | anonymous | Vidar |
| 271e142c9bcda8eea69a5f9b734003efa32a74046a356477f352d661dffb831c | abuse_ch | n/a |
| 747368ec46304ae98c8fbea3b3ccaa022edd58a9fb108f9b04c5e21968b8e8fb | dash | Formbook |
| 19e34346b27132cbb085359b34e3978117810af8332d7058f421cb49845b087e | Darkfibr | n/a |
| 1355a1de74bb2b3d4d9f1d371cedb7dda2c6c413269574f711271e69bc2d0b1b | rc4 | n/a |
| 59ceb7b47ebb9ed5189afe1afe79a80c854bb2ddec62a23ec2c380465a9598a8 | koluke | n/a |
| 0d04c452ff96b79c20cfa41d2ac09906d6653ad5201c2ad93b1e86abaedfc605 | FXOLabs | n/a |
| 2dc1de602d1af859042d787ac993d9db89e294d2c7461c5a5af178b7322085ff | c4ffeine | AMOS |

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
| 45.148.10.240 | 11 |
| 77.90.185.20 | 11 |
| 2.57.122.238 | 10 |
| 45.43.60.98 | 10 |
| 144.225.6.182 | 10 |
| 45.148.10.151 | 9 |
| 66.132.172.139 | 9 |
| 66.132.172.184 | 9 |
| 66.132.186.182 | 9 |
| 66.132.195.53 | 9 |
| 66.132.195.56 | 9 |
| 66.132.195.93 | 9 |
| 94.154.43.57 | 9 |
| 94.154.43.223 | 9 |
| 103.159.2.113 | 9 |
| 120.48.90.166 | 9 |
| 152.32.225.117 | 9 |
| 167.94.146.50 | 9 |
| 167.94.146.52 | 9 |
| 167.94.146.55 | 9 |

### OpenPhish (live phishing URLs)
- https://handel.mobile.fahrzeuge.details.83477383.wm.sjqgvy.com/anfrangen/fahrzeug/
- http://cp188.xyz/ww/
- http://notaria11medellin.com/chulo/index.html
- https://sk.yndssh.com/auth/
- https://crownhillconsults.com/rfq
- https://seeker-snake-burn-influences.trycloudflare.com/apps/pubgmobile/?i=322701
- http://bermexa-vrk-belxavi-p9t5fc68.pages.dev/
- https://recompensasexclusivasparamiembros25.ink/E7cE3mR9w
- https://bucolic-faun-45e170.netlify.app/
- http://security-server-landing-page--vanguardmusk.replit.app/
- https://facebooksecure.blogspot.com/
- https://amazon-ui-clone-green.vercel.app/
- https://metamask-docs-ldkp21iks-consensys-ddffed67.vercel.app/
- https://shifatsb.github.io/Attack/
- https://servicioenlineadeayuda--solucionesec.replit.app/
- https://satyamkumar9304.github.io/Spotify-clone/
- https://ecuador--aumento203.replit.app/
- https://crediplus--credi0.replit.app/
- https://get-acrobat-adobe.pages.dev/favicon.ico
- https://solisita-ya.vercel.app/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=ASKXGp0_nbFzdHoBsG_d6znGlWE063OUXUJ-liVgQNfJJB3wA_mip4wV6In-9Cchxtm7MSHwtubxoQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SS2KCe5jNmM9T_aWTaJU1pBv_G-9NnUY7qRIR_VcoOMfkdu7NMPs0TTrzoIjCvF0jC_Bdl4&dsh=S-719601785%3A1791966668097739 |
| N/A | https://away.vk.ru/away.php?rh=9e0bcad1-56ba-4c4d-a1e9-a1226af80e14 |
| N/A | https://postafnkv.weebly.com/ |
| N/A | https://ersfilter-my.sharepoint.com/personal/nradonich_ersfilter_com/_layouts/15/doc.aspx?guestaccesstoken=t6T%2FHN1dKbYHlYX%2BeIMbaZufA43rrGZ6%2FaAAewNocDI%3D&docid=1_18168db23429e45f29fdf2e7be120efc4&wdFormId=%7BB9970F62-44C3-4D09-9929-6E1EB652DA57%7D&action=formsubmit&CID=cb649895-7ddf-4ba2-8444-733ac19dc0b4 |
| N/A | https://pagamento-mlsr49.publish.render.ai/ |
| N/A | https://pageseuc1.actmkt.com/(S(wa2xn22eqdze1vdtiavkacx3))/l/c5X8MfZz6j9Y7Fto3LAd |
| N/A | http://43.156.0.130/v3/signin/identifier?amp;continue=https://accounts.google.com/&amp;followup=https://accounts.google.com&passive=1209600&flowName=GlifWebSignIn&flowEntry=ServiceLogin&dsh=S959304876:1791965498907074 |
| N/A | https://postapp.wpenginepowered.com/wphtts/hreef.php |
| N/A | https://fixbetresmi.vip/ |
| 5 | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AQMjQ7TPKu6R4w93VRXMPKeD3zeOl4EoNrOdcsDBPMv7m30JK47iKcBvHB2Y608BaGxX8bX4kwt6sA&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SRCZ4pcRXOqnqnsWtJivRlR3YlROZxxYjsem6hJBRvEioYrw-gW4iaaS_gj3QKtWU4VI5_mMA&dsh=S287392881%3A1791957307319984 |
| N/A | https://yandex.ru/showcaptcha?cc=1&form-fb-hint=2.1&mt=0667FD44CFAAEAE551FABD5667A0628395827695C181B082FF56806D28C57DFFD5340C5D2E8FEE2A622959FD437C1D5BA1D9C7DE446A2CAC42C8CB536D61FE84B6A2C2FA718B2E15FD6E5CE082C5D669722882456E1A2C8B1BD73D70D3FED83AA15D7D9D99F5A91B45C02429177ED0BD20A88A6D2B4C5A3728A6493830E9CE02793F373ACE193A6213&retpath=aHR0cHM6Ly95YW5kZXgucnUvc2VhcmNoP3RleHQ9MjExNjg3MTc%2C_9e32ea590f1152ceb4677b92f96f1e0c&t=2%252F1791957268%252F2d54c158320a9246e2e17cd278ccf8c9&u=9575752175676042056&s=9a745c30c0b28a5e2d7a09fde4f69e37 |
| N/A | https://diners-corporate.lovable.app/ |
| N/A | https://pageseuc1.actmkt.com/(S(33if1a4ohjebfcsj5213z1op))/l/c5X8MfZz6j9Y7Fto3LAd |
| 3.1 | https://away.vk.ru/away.php?rh=2cd9d662-2bc4-4b86-8b94-40543bbf4d0a |
| 6.7 | http://www.allegrolokalne.8078794.cc/ |
| 8.9 | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=ASKXGp0_nbFzdHoBsG_d6znGlWE063OUXUJ-liVgQNfJJB3wA_mip4wV6In-9Cchxtm7MSHwtubxoQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06STuVtJaPXFAcVkzkgC_kOHZKRrfzPKm0bl6XEOPjtBWDS8iKLUPk5teeIMaiJxv7bGCrNeY&dsh=S-620263761%3A1791955323174139 |
| 6.4 | http://loanfairfield.com/ |
| N/A | https://pv-abonnement-renouv.com/ |
| N/A | https://id.superhuman.com/signin?oauth_client_type=MEDIATED_WEB&correlation_id=32bk7Wv69YPbByGbJExynA&version=v4&client_id=superhumanDocs |
| N/A | https://carly6386.wixsite.com/my-site-1 |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| 09545cca9c36c76f4982c4b648041a1606799b53 | Vidar C&C |
| d333c0b7e380afd2f156555b8110c00177b62e5d | Vidar C&C |
| e6c0468f46efe40f3127d33641bfc3df8b2e5c7d | PureLogsStealer C&C |
| 4664c47d412c00bf067a325ffa9790db75efbe75 | PureLogsStealer C&C |
| b3c1e060a727e4db1cf6131f1eb6e9bcca2ffb5d | PureRAT C&C |
| 11cfb1e85c316e9b9785c6778bc077bb04093dfd | PureLogsStealer C&C |
| c389945d4fc75250b291953e0abad0662dd9ce7d | Vidar C&C |
| 24ec954313877b212b522682aef606180ff6f343 | OffLoader C&C |
| 515574d4dc4957fbd0043d3a4269485384e504e7 | Vidar C&C |
| 51f9d6339bfdb9321630392913941e04d921cf7d | Vidar C&C |
| 9d4574e66ed485ca617fe78078a7dba674937bb3 | Vidar C&C |
| 629700c6fb58a48ce5c34e9e830225fad3e62634 | DCAgentRMM C&C |
| 6ae4974b641caa8b6aae8d3392e7fb4f8c7e3577 | DCAgentRMM C&C |
| 245f189a60a8b20a5dc562134b3d55d6539ac186 | Vidar C&C |
| ab1d61a4f4692b105daa345a7185119f0d29cb79 | Vidar C&C |
| 9769dce57ee77a6da94da9c824cd923cb9599892 | Vidar C&C |
| d621cfc19f287afe3b53ee95f4463732d2de342f | Malware C&C |
| 929b3729b42dabeb68077b03b2802e5b53ceade7 | ConnectWise C&C |
| 1c14689e58ebc09098f7c23eec08a314eb17ec76 | OffLoader C&C |
| 4a0c5885230b991333569023a767f7cc3a773baf | PureRAT C&C |

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
- 5.175.189.0/24
- 5.183.60.0/22
- 5.188.236.0/23

### blocklist.de (recent SSH/mail/web attack sources)
- 1.0.164.165
- 1.14.240.247
- 1.15.221.192
- 1.159.54.33
- 1.178.138.99
- 1.188.168.41
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.227.228.131
- 1.235.14.41
- 1.235.183.146
- 1.237.155.150
- 1.238.106.229
- 1.247.245.61
- 1.250.67.114
- 1.250.67.190
- 1.32.25.19
- 1.42.171.164

### CINS Army (poorly-rated IPs)
- 1.192.129.106
- 1.192.216.192
- 1.20.173.155
- 1.213.214.233
- 1.215.138.43
- 1.223.11.69
- 1.24.16.101
- 1.24.16.102
- 1.24.16.106
- 1.24.16.108
- 1.24.16.111
- 1.24.16.139
- 1.24.16.151
- 1.24.16.157
- 1.24.16.166
- 1.24.16.167
- 1.24.16.172
- 1.24.16.176
- 1.24.16.18
- 1.24.16.184

## News (last ~36h, across outlets)
### The Hacker News
- [Four-Byte Write and Timing Bug Let Researchers Run Code in Windows SmartScreen Enclave](https://thehackernews.com/2026/10/four-byte-write-and-timing-bug-let.html)
- [Microsoft Patches Record 1,413 Flaws, Including Exploited Windows Shell Bug](https://thehackernews.com/2026/10/microsoft-patches-record-1413-flaws.html)
- [OpenAI Employee Arrested for Allegedly Planting Hidden Recorder in Executive Conference Room](https://thehackernews.com/2026/10/openai-employee-arrested-for-allegedly.html)
- [Anthropic Warns Small AI Models Could Soon Form Self-Propagating IoT Botnets](https://thehackernews.com/2026/10/anthropic-warns-small-ai-models-could.html)
- [Docker Fixes Critical Two-Year-Old Hub Flaw That Let One User Push Images as Another](https://thehackernews.com/2026/10/docker-fixes-critical-two-year-old-hub.html)
- [Attacker Chains Three Ivanti Connect Secure Zero-Days for Root Access, Only Two Patched So Far](https://thehackernews.com/2026/10/attacker-chains-three-ivanti-connect.html)
- [SAP Discloses Critical CVSS 10 Flaw in Cloud SDK for Python Allowing OAuth2 Credential Theft](https://thehackernews.com/2026/10/sap-discloses-critical-cvss-10-flaw-in.html)
- [GitHub Tightens npm Publishing After Flaw Left 1,500+ Packages Vulnerable to Hijacking](https://thehackernews.com/2026/10/github-tightens-npm-publishing-after.html)
- [Xandr Fined a Record €8.6 Million for Relaying Grindr Data Revealing Sexual Orientation](https://thehackernews.com/2026/10/xandr-fined-record-86-million-for.html)
- [[Webinar] How to Stop AI-Driven Privilege Escalation With Runtime Identity Controls](https://thehackernews.com/2026/10/webinar-how-to-stop-ai-driven-privilege.html)
- [LG Smart TVs Vulnerable to Pre-Auth Root Takeover From Local Network](https://thehackernews.com/2026/10/lg-smart-tvs-vulnerable-to-pre-auth.html)
- [Product Walkthrough: Bitdefender AI Visibility and Control](https://thehackernews.com/2026/10/product-walkthrough-bitdefender-ai.html)
- [Attackers Heat French Supermarket Fridges Up to 50°C by Hijacking Danfoss Controllers](https://thehackernews.com/2026/10/attackers-heat-french-supermarket.html)
- [Two Critical MarkLogic Flaws Could Give Delegated Managers Persistent Admin Control](https://thehackernews.com/2026/10/two-critical-marklogic-flaws-could-give.html)
- [GitLab Patches CVSS 10.0 Flaw That Could Let Unauthenticated Users Run Server Code](https://thehackernews.com/2026/10/gitlab-patches-cvss-100-flaw-that-could.html)

### BleepingComputer
- [OpenAI engineer arrested for allegedly planting spy device in office](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-engineer-arrested-for-allegedly-planting-spy-device-in-office/)
- [Ghostscript flaw lets hackers hijack servers via PDF uploads](https://www.bleepingcomputer.com/news/security/ghostscript-flaw-lets-hackers-hijack-servers-via-pdf-uploads/)
- [Anthropic warns self-replicating AI could spread to your smart devices](https://www.bleepingcomputer.com/news/security/anthropic-warns-self-replicating-ai-could-spread-to-your-smart-devices/)
- [Microsoft October 2026 Patch Tuesday fixes 1,411 flaws, 3 zero-days](https://www.bleepingcomputer.com/news/microsoft/microsoft-october-2026-patch-tuesday-fixes-1-411-flaws-3-zero-days/)
- [Microsoft releases Windows 10 KB5126657 extended security update](https://www.bleepingcomputer.com/news/microsoft/microsoft-releases-windows-10-kb5126657-extended-security-update/)
- [Microsoft: Windows 11 24H2 Home and Pro reached end of support](https://www.bleepingcomputer.com/news/microsoft/microsoft-windows-11-24h2-home-and-pro-reached-end-of-support/)
- [UK Housing Ombudsman Service investigates 'security incident'](https://www.bleepingcomputer.com/news/security/uk-housing-ombudsman-service-investigates-security-incident/)
- [Windows 11 KB5127648 & KB5126653 cumulative updates released](https://www.bleepingcomputer.com/news/microsoft/windows-11-kb5127648-and-kb5126653-cumulative-updates-released/)
- [TFG London cyberattack disrupts systems at Hobbs and Whistles retailers](https://www.bleepingcomputer.com/news/security/tfg-london-cyberattack-disrupts-systems-at-hobbs-and-whistles-retailers/)
- [Ivanti warns of Connect Secure zero-day exploited in attacks](https://www.bleepingcomputer.com/news/security/ivanti-warns-of-connect-secure-zero-day-exploited-in-attacks/)
- [Docker Hub flaw let attackers impersonate users, tamper with images](https://www.bleepingcomputer.com/news/security/docker-hub-flaw-let-attackers-impersonate-users-tamper-with-images/)
- [The MFA Gaps Attackers are Still Exploiting](https://www.bleepingcomputer.com/news/security/the-mfa-gaps-attackers-are-still-exploiting/)
- [SAP warns of maximum severity OAuth2 SSRF security flaw](https://www.bleepingcomputer.com/news/security/sap-warns-of-maximum-severity-oauth2-ssrf-security-flaw/)

### Krebs on Security
- [Microsoft Patches More Than 1,400 Security Flaws](https://krebsonsecurity.com/2026/10/microsoft-patches-more-than-1400-security-flaws/)

### Dark Reading
- [Ransomware Gangs Embrace Physical Threats, Family Stalking?](https://www.darkreading.com/cybersecurity-analytics/ransomware-gangs-physical-threats-family-stalking)
- [Zero-Days Lurk in Microsoft's Overgrown October Patch Tuesday](https://www.darkreading.com/vulnerabilities-threats/zero-days-microsoft-october-patch-tuesday)
- [North Korea Phishes Ukrainians for War Intel](https://www.darkreading.com/cyberattacks-data-breaches/north-korea-phishes-ukrainians-war-intel)
- [Anthropic Finds Ingredients for Future AI Worms](https://www.darkreading.com/perimeter/anthropic-ingredients-future-ai-worms)
- [Maximum-Severity SSRF Flaw in SonicWall SMA Devices Under Attack](https://www.darkreading.com/vulnerabilities-threats/max-severity-ssrf-flaw-sonicwall-sma-devices-under-attack)

### SecurityWeek
- [Chrome, Firefox Updates Patch 114 Flaws as Mozilla Unveils Firefox Enterprise](https://www.securityweek.com/chrome-firefox-updates-patch-114-flaws-as-mozilla-unveils-firefox-enterprise/)
- [Citrix, Fortinet, Ivanti Patch 29 Vulnerabilities Across Their Products](https://www.securityweek.com/citrix-fortinet-ivanti-patch-29-vulnerabilities-across-their-products/)
- [Microsoft Patches Record 1,413 Vulnerabilities, Including Exploited Windows Zero-Day](https://www.securityweek.com/microsoft-patches-record-1413-vulnerabilities-including-exploited-windows-zero-day/)
- [SAP Patches Critical NetWeaver, S/4HANA Vulnerabilities](https://www.securityweek.com/sap-patches-critical-netweaver-s-4hana-vulnerabilities/)
- [Employee Arrested After Listening Device Found in OpenAI Conference Room, FBI and the Company Say](https://www.securityweek.com/employee-arrested-after-listening-device-found-in-openai-conference-room-fbi-and-the-company-say/)
- [Ivanti Zero-Day Chain Gave Attackers Root Access to Fully Patched VPN](https://www.securityweek.com/ivanti-zero-day-chain-gave-attackers-root-access-to-fully-patched-vpn/)
- [Adobe Patches 176 Vulnerabilities Across 11 Products](https://www.securityweek.com/adobe-patches-140-vulnerabilities-across-10-products/)
- [Google Partially Reverses Chrome Bug Bounty Cuts](https://www.securityweek.com/google-partially-reverses-chrome-bug-bounty-cuts/)
- [Meta Says Hackers Took Code, Personal Data of 1,500 in GitHub Breach](https://www.securityweek.com/meta-says-hackers-took-code-personal-data-of-1500-in-github-breach/)
- [Small AI Models Could Soon Self-Replicate on IoT Devices, Anthropic Warns](https://www.securityweek.com/small-ai-models-may-soon-be-able-to-self-replicate-on-iot-devices-anthropic-warns/)

### The Record
- [Two arrested as DOJ takes down laptop farms responsible for $3 million in North Korean revenue](https://therecord.media/north-korea-laptop-farms-worker-scams-doj-raids-texas)
- [FTC: Company netted at least $60 million charging sextortion victims for help it didn’t provide](https://therecord.media/sextortion-assistance-company-alleged-fraud-ftc-complaint)
- [Sandbox vulnerability gives rogue AI agents a path to escape and leak data, research says](https://therecord.media/sandbox-vulnerability-gives-rogue-ai-agents-path-out)
- [West African scam compounds raided, more than 100 suspected trafficking victims ‘rescued’](https://therecord.media/ghana-nigeria-scam-centers-raided-uk-us)
- [North Korean hackers target Ukrainian experts for possible intelligence on Russia's war](https://therecord.media/north-korea-hackers-russia-ukraine)

### Infosecurity Magazine
- [Billion-Dollar Companies Twice as Likely to Leave Critical Vulnerabilities Unpatched](https://www.infosecurity-magazine.com/news/companies-leave-critical/)
- [European Retail Firms Confirm Cyber Incidents](https://www.infosecurity-magazine.com/news/retail-firms-confirm-cyber/)
- [Defenders Reluctant to Deploy Agentic AI as a Cybersecurity Tool](https://www.infosecurity-magazine.com/news/defenders-skeptical-agentic-ai/)
- [UK Government Announces Sweeping New AI Security Plans](https://www.infosecurity-magazine.com/news/uk-government-sweeping-ai-security/)
- [Fifth of CISOs Take Time Off to Avoid Patch Tuesday](https://www.infosecurity-magazine.com/news/fifth-cisos-take-time-off-avoid/)

### CyberScoop
- [Ivanti misses opportunity to fix vulnerability before attackers got to work and made it a zero-day](https://cyberscoop.com/ivanti-connect-secure-zero-day-actively-exploited/)
- [DOJ charges 14 over a sprawling North Korean remote work scheme](https://cyberscoop.com/doj-north-korea-remote-work-laptop-farms/)
- [FTC says ‘sextortion’ protection companies deceived customers about services](https://cyberscoop.com/ftc-lawsuit-dmitry-belkin-sextortion-fraud/)
- [West African scammers targeted in joint international government-industry operation](https://cyberscoop.com/west-african-scammers-international-scam-crackdown-joint-disruption-week/)
- [Flock can now issue CVEs for its own products. Should we trust it?](https://cyberscoop.com/flock-cve-numbering-authority-cna/)

### Cisco Talos
- [Microsoft Patch Tuesday for October 2026 — Snort rules and prominent vulnerabilities](https://blog.talosintelligence.com/microsoft-patch-tuesday-for-october-2026/)

### Unit 42 (Palo Alto)
- [The Noise Inside the Network: How an Unsophisticated Attack Exposed a Third-Party Risk](https://unit42.paloaltonetworks.com/noise-inside-network-third-party-risk/)

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [Orphaned VBA Projects Inside DWG Files, (Wed, Oct 14th)](https://isc.sans.edu/diary/rss/33420)
- [ISC Stormcast For Wednesday, October 14th, 2026 https://isc.sans.edu/podcastdetail/10136, (Wed, Oct 14th)](https://isc.sans.edu/diary/rss/33424)
- [October 2026 Microsoft Patch Tuesday, (Tue, Oct 13th)](https://isc.sans.edu/diary/rss/33422)
- [ISC Stormcast For Tuesday, October 13th, 2026 https://isc.sans.edu/podcastdetail/10134, (Tue, Oct 13th)](https://isc.sans.edu/diary/rss/33418)

### Securelist (Kaspersky)
_No new items / feed unavailable this run._

### CrowdStrike Blog
- [U.S. Government Disrupts FAMOUS CHOLLIMA Operation with CrowdStrike Assistance](https://www.crowdstrike.com/en-us/blog/fbi-disrupts-famous-chollima-operation-with-crowdstrike-assistance/)
- [October 2026 Patch Tuesday: 1,413 CVEs Include Three Zero-Days and 75 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-october-2026/)
- [CrowdStrike and Anthropic Give Critical Infrastructure Defenders the AI Advantage](https://www.crowdstrike.com/en-us/blog/crowdstrike-anthropic-critical-infrastructure-defense-program/)
- [Solving the Continuous Authorization Conundrum](https://www.crowdstrike.com/en-us/blog/solving-the-continuous-authorization-conundrum/)
- [Unknown Threat Actor Uses AI-Driven ARTEX to Target South Korean Finance](https://www.crowdstrike.com/en-us/blog/unknown-threat-actor-uses-artex-to-target-south-korean-finance/)
- [CrowdStrike Named a Leader in the 2026 IDC MarketScape for Worldwide Modern Endpoint Security for Enterprises Vendor Assessment](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-idc-marketscape-worldwide-modern-endpoint-security-for-enterprises/)
- [Request, Aggregate, Bypass: How Attackers Can Evade LLM Safety Classifiers](https://www.crowdstrike.com/en-us/blog/how-attackers-can-bypass-llm-safety-classifiers/)
- [Falcon Data Security for SaaS Secures Sensitive Data in Microsoft 365](https://www.crowdstrike.com/en-us/blog/falcon-data-security-for-saas-secures-sensitive-data/)
- [New in Falcon Cloud Security: Third-Party App Insights and AI-Enhanced Remediation](https://www.crowdstrike.com/en-us/blog/falcon-cloud-security-third-party-app-insights-ai-enhanced-remedation/)
- [CrowdStrike Expands Federal SOC Modernization Through CISA-Funded SIEMaaS](https://www.crowdstrike.com/en-us/blog/crowdstrike-expands-federal-soc-modernization-via-cisa-siemaas/)

### FortiGuard Threat Signal
_No new items / feed unavailable this run._

## Fetch issues this run
- Securelist (Kaspersky) RSS -> malformed/unparseable feed (<urlopen error [Errno 110] Connection timed out>)

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal