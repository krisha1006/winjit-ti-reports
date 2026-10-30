# Winjit Daily TI Digest — 2026-10-30

_Auto-generated. Window: last ~24h. Fetched at 2026-10-30T09:46:17.293437+00:00Z_

**At a glance:** 2 new KEV · 29 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-97229 | GitLab | Community Edition and Enterprise Edition | GitLab Community Edition and Enterprise Edition Integer Overflow or Wraparound Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-76418 | Cisco | Secure Firewall ASA Software and Cisco Secure FTD Software | Cisco Secure Firewall ASA Software and Cisco Secure FTD Software Unchecked Return Value to NULL Pointer Dereference Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-103039 | 9.8 | n/a | The Gravity Forms plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 3.1.2 via a Post Custom Field whose input type is List. This is due to GFFormsModel:: |
| CVE-2026-49142 | 8.8 | n/a | OpenEMR before 8.5.0 contains an authenticated SQL injection vulnerability in the Syndromic Surveillance module that allows users with Clinician-level privileges to read and modify arbitrary database  |
| CVE-2026-119144 | 8.8 | n/a | Frappe Framework before 15.111.0 and 16.x before 16.21.0 contains a server-side template injection vulnerability because user-controlled message fields are rendered as templates without neutralization |
| CVE-2026-104368 | 8.8 | n/a | The Export and Import Users and Customers plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 2.7.5 via the plugin's own export and re-import workflow. The |
| CVE-2026-89435 | 8.8 | n/a | The Formidable Forms – WordPress Form Builder for Contact Forms, Calculators, Quizzes & More plugin for WordPress is vulnerable to Arbitrary Plugin Installation in all versions up to, and including, 6 |
| CVE-2026-9535 | 8.2 | n/a | A out-of-bounds read vulnerability exists in the vtkChacoReader InputGraph2 functionality of vtk (version(s): 9.6.1). A specially crafted chaco can lead to an out-of-bounds read. An attacker can provi |
| CVE-2026-119050 | 8.1 | n/a | Agno through 3.1.11 contains an unsafe reflection vulnerability in PandasTools that allows attackers to invoke arbitrary pandas functions by supplying model-controlled function names to getattr(). Att |
| CVE-2026-119127 | 8.1 | n/a | ZITADEL 4.0.0 before 4.19.5 contains a host header injection vulnerability in the Login V2 UI that allows unauthenticated attackers to poison password-reset, invite, and email-verification links by su |
| CVE-2026-114148 | 7.8 | n/a | Incorrect default permissions in ASP.NET Core allows an authorized attacker to elevate privileges locally. |
| CVE-2026-119049 | 7.6 | n/a | FreeMail before 5.3.2 contains an authorization bypass vulnerability that allows authenticated users to claim another user's existing mailbox via the POST /api/create endpoint. Attackers who know a vi |
| CVE-2026-119025 | 7.5 | n/a | open 7.2.0 before 11.0.0 contains an OS command injection vulnerability that allows attackers to execute PowerShell code by supplying crafted URLs on Windows and WSL. Attackers can embed $(...) subexp |
| CVE-2019-25781 | 7.5 | n/a | Python-Markdown 3.0 through 3.11.2 contains an algorithmic complexity vulnerability in inline link parsing that allows remote attackers to exhaust CPU through unmatched brackets. Attackers can submit  |
| CVE-2026-110245 | 7.5 | n/a | IBM Langflow OSS 1.0.0 through 1.12.4 could allow a remote attacker to obtain sensitive information due to improper authentication. |
| CVE-2026-119119 | 7.5 | n/a | Crawl4AI before 0.9.5 contains a denial of service vulnerability in the Docker API server where _clamp_untrusted() fails to cap the delay_before_return_html, mean_delay, and max_range fields of untrus |
| CVE-2026-119120 | 7.5 | n/a | Crawl4AI from 0.9.0 before 0.9.5 fails to filter the CosineStrategy model_name field in untrusted Docker API request bodies, allowing authenticated clients to choose which HuggingFace model the server |
| CVE-2026-41216 | 7.5 | n/a | An invalid pointer dereference vulnerability exists in the vtkPNGReader::ExecuteInformation functionality of vtk 9.6. A specially crafted .png file can lead to a denial of service. An attacker can pro |
| CVE-2026-42057 | 7.5 | n/a | An invalid pointer dereference vulnerability exists in the vtkPNGReader::vtkPNGReaderUpdate2 functionality of vtk 9.6. A specially crafted .png file can lead to a denial of service. An attacker can pr |
| CVE-2026-8822 | 7.5 | n/a | A memory corruption vulnerability exists in the vtkDEMReader ReadProfiles functionality of vtk (version(s): 9.6.1). A specially crafted USGS DEM can lead to a buffer overflow. An attacker can provide  |
| CVE-2026-8824 | 7.5 | n/a | A memory corruption vulnerability exists in the vtkBMPReader ExecuteDataWithInformation functionality of vtk (version(s): 9.6.1). A specially crafted .bmp file can lead to a buffer overflow. An attack |
| CVE-2026-9536 | 7.5 | n/a | A heap-based buffer overflow vulnerability exists in the vtkWindBladeReader FindVariableOffsets functionality of vtk (version(s): 9.6.1). A specially crafted .wind can lead to a buffer overflow. An at |
| CVE-2026-119325 | 7.5 | n/a | Bricks Theme 2.4 and before for WordPress contains an unauthenticated broken access control vulnerability in the load_popup_content REST endpoint that allows anonymous attackers to read draft and unpu |
| CVE-2026-103963 | 7.5 | n/a | A flaw was found in glib-networking. When establishing connections using Transport Layer Security (TLS) version 1.3, the client-side session cache does not limit the number of session tickets retained |
| CVE-2026-110732 | 7.5 | n/a | The AI Engine – The Chatbot, AI Framework & MCP for WordPress plugin for WordPress is vulnerable to Missing Authorization in all versions up to, and including, 3.8.6 This is due to the MCP module's OA |
| CVE-2026-114488 | 7.4 | 0.3% | A flaw was found in Wildfly. A remote attacker can bypass authentication on IIOP EJB invocations as the CSIv2 security interceptor accepts ITTPrincipalName identity assertions in the service context w |
| CVE-2026-119128 | 7.4 | n/a | ZITADEL 4.0.0 before 4.19.5 contains an authentication bypass vulnerability in the Login V2 UI that allows unauthenticated attackers to set the first credential of users lacking any authentication met |
| CVE-2026-96187 | 7.4 | n/a | Access of resource using incompatible type ('type confusion') in Microsoft Edge (Chromium-based) allows an unauthorized attacker to disclose information over a network. |
| CVE-2026-116622 | 7.2 | n/a | The Food Store – Online Food Delivery & Pickup plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'service_time' parameter in all versions up to, and including, 1.5.5 due to ins |
| CVE-2026-90437 | 7.2 | n/a | The Gravity Forms plugin for WordPress is vulnerable to Stored Cross-Site Scripting via Post Excerpt / Post Custom Field / Rich-Text Paragraph Field Values in all versions up to, and including, 3.1.1  |
| CVE-2026-97645 | 7.2 | n/a | The Gravity Forms plugin for WordPress is vulnerable to Stored Cross-Site Scripting via List Field in all versions up to, and including, 3.1.2 due to insufficient input sanitization and output escapin |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-3536-74c2-mgrr | CVE-2026-64618 | unknown | Improper Neutralization of Special Elements used in an SQL Command ("SQL Injection")... |
| GHSA-7pvg-2h32-c6jc | CVE-2026-65874 | unknown | This issue affects Apache Fineract versions up to and including 1.15.0. The Center read endpoint ... |
| GHSA-8p38-wrq5-f9qc | CVE-2026-59388 | medium | Cloud Controller (CAPI) leaks sensitive data into audit logs in multiple instances: custom... |
| GHSA-mvr6-3j94-gvw8 | CVE-2026-59385 | low | A user with SpaceDeveloper privileges could modify the URL of a space-scoped broker without... |
| GHSA-xf4x-4c6x-9xm2 | CVE-2026-59396 | medium | A denial-of-service vulnerability exists in UAA's private_key_jwt client-authentication mechanism... |
| GHSA-37xc-gw75-236w | CVE-2026-59387 | high | The Nginx routing configuration for Cloud Controller blocks unauthenticated access to /internal... |
| GHSA-4ppv-vpf6-gfrj | CVE-2026-59386 | medium | A SpaceSupporter could improperly modify an application's start command and buildpack—actions... |
| GHSA-jgwq-jmrj-p95p | CVE-2026-115455 | medium | A flaw was found in GCC libstdc++. When an application extracts data into a bitset from a wide... |
| GHSA-774g-h2fq-p98f | CVE-2026-97645 | high | The Gravity Forms plugin for WordPress is vulnerable to Stored Cross-Site Scripting via List... |
| GHSA-775q-m9j7-gg3x | CVE-2026-114691 | medium | A flaw was found in the libstdc++ component of GCC. An attacker who can provide an excessively... |
| GHSA-8wqr-r4rr-gg45 | CVE-2026-115456 | low | A flaw was found in gcc. An attacker could cause a Denial of Service (DoS) by passing a string... |
| GHSA-36h8-gj54-w3vc | CVE-2026-114690 | medium | A flaw was found in GCC. An out-of-bounds memory access vulnerability exists in the libstdc++... |
| GHSA-4v5h-x9v6-mww6 | CVE-2026-82104 | critical | In Teltonika Networks RUTOS devices running versions from 7.22 through 7.24.2 and TSWOS devices... |
| GHSA-8r7c-j2qw-g3gp | CVE-2026-90437 | high | The Gravity Forms plugin for WordPress is vulnerable to Stored Cross-Site Scripting via Post... |
| GHSA-7366-rqfr-5w7j | CVE-2026-89435 | high | The Formidable Forms – WordPress Form Builder for Contact Forms, Calculators, Quizzes & More... |
| GHSA-22w7-p44p-2gq7 | CVE-2026-110732 | high | The AI Engine – The Chatbot, AI Framework & MCP for WordPress plugin for WordPress is vulnerable... |
| GHSA-vpwg-79f7-v3cx | CVE-2026-118952 | medium | A flaw was found in the Kroxylicious ACL authorizer. Its prefix-matching logic may apply a rule... |
| GHSA-p38h-8554-v633 | CVE-2026-118593 | medium | A flaw was found in Red Hat Enterprise Linux 9 kernel builds. An incomplete backport of the CVE... |
| GHSA-v228-2jfw-f8cg | CVE-2026-116622 | high | The Food Store – Online Food Delivery & Pickup plugin for WordPress is vulnerable to Stored Cross... |
| GHSA-635p-78xg-j6w3 | CVE-2026-103039 | critical | The Gravity Forms plugin for WordPress is vulnerable to PHP Object Injection in all versions up... |
| GHSA-65m9-fpqg-cx7w | CVE-2026-119059 | medium | The Content Egg plugin for WordPress is vulnerable to unauthorized modification of data due to a... |
| GHSA-gf37-757h-m7hx | CVE-2026-118698 | medium | The JoomSport – for Sports: Team & League, Football, Hockey & more plugin for WordPress is... |
| GHSA-87rp-9h85-83hj | CVE-2026-118100 | unknown | The BuddyForms WordPress plugin before 2.10.3 does not check that the requester is allowed to... |
| GHSA-755c-vvf8-fm4g | CVE-2026-118500 | medium | The Cool FormKit Lite – Advanced Form Builder for Elementor plugin for WordPress is vulnerable to... |
| GHSA-cf3c-vhpc-r6rv | CVE-2026-114443 | unknown | The Security Plugin, Firewall & Malware Scanner with Auto Removal WordPress plugin before 2.191... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Susman Godfrey LLP | SilentRansomGroup | US | 2026-10-30T00:02:22.816559+00:00 |
| TDS Telecommunications LLC. | Global Secret Group | US | 2026-10-29T21:54:07.712704+00:00 |
| IT Foods Industries | Shiba |  | 2026-10-29T20:36:55.631822+00:00 |
| Friendly Senior Living | Shiba |  | 2026-10-29T20:36:36.107929+00:00 |
| Morgan White Group | Shiba |  | 2026-10-29T20:36:16.686785+00:00 |
| Antwerp House Dentistry | Shiba | GB | 2026-10-29T20:35:57.079262+00:00 |
| as*****g.com | everstake |  | 2026-10-29T20:25:08.497064+00:00 |
| ca*****s.com | everstake |  | 2026-10-29T20:24:31.319474+00:00 |
| in*****s.com | everstake |  | 2026-10-29T20:23:52.693713+00:00 |
| corp-smart.com | everstake |  | 2026-10-29T20:23:13.685971+00:00 |
| rolly.io | Whitearmor |  | 2026-10-29T18:04:46.117826+00:00 |
| LA PROFUMERIA SRL | emperador | IT | 2026-10-29T16:53:34.200516+00:00 |
| INTAX, Inc. | rhysida |  | 2026-10-29T14:14:29.488392+00:00 |
| www.viehhauser-kfz.at | krybit | AT | 2026-10-29T14:06:43.428858+00:00 |
| Circleville Police Department | Booba Project | US | 2026-10-29T13:21:34.206838+00:00 |
| Programs for Parents, Inc. | Booba Project | US | 2026-10-29T13:21:55.468140+00:00 |
| South Weber City | Booba Project | US | 2026-10-29T13:22:16.123980+00:00 |
| California School Boards Association | Booba Project | US | 2026-10-29T13:22:37.130896+00:00 |
| National Association of Credit Management | Booba Project | US | 2026-10-29T13:22:58.010345+00:00 |
| LifeFone | Booba Project | US | 2026-10-29T13:23:18.856891+00:00 |

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
| 77.90.185.20 | 12 |
| 138.226.239.233 | 10 |
| 138.226.239.234 | 10 |
| 167.94.146.52 | 10 |
| 196.189.236.67 | 10 |
| 2.57.122.238 | 9 |
| 14.34.249.175 | 9 |
| 37.187.35.26 | 9 |
| 45.148.10.121 | 9 |
| 45.148.10.240 | 9 |
| 64.62.197.227 | 9 |
| 66.132.172.185 | 9 |
| 77.239.124.2 | 9 |
| 80.82.77.139 | 9 |
| 103.159.2.113 | 9 |
| 167.94.146.49 | 9 |
| 167.94.146.50 | 9 |
| 167.94.146.51 | 9 |
| 167.94.146.54 | 9 |
| 167.94.146.58 | 9 |

### OpenPhish (live phishing URLs)
- https://mu.qmmafe.com/
- http://www.viewdetail2910tbnaplnw.usnicvrfauthenservices.com/public/index?ref=business-support-center-DASDFDSYUYEE43FJDSHFSDFsetting%25popup%3fclient_id=889943718806-ual26tplnot2ea8b7n5t4p77keo8eb
- http://www.viewdetail2910tbnaplnw.usnicvrfauthenservices.com/
- https://www.ukinvoibebubu.vercel.app/
- https://viewdetail2910tbnaplnw.usnicvrfauthenservices.com/public/index?ref=business-support-center-DASDFDSYUYEE43FJDSHFSDFsetting%25popup%3fclient_id=889943718806-ual26tplnot2ea8b7n5t4p77keo8eb
- https://viewdetail2910tbnaplnw.usnicvrfauthenservices.com/
- https://sharivorcanas.netlify.app/a
- https://sharivorcanas.netlify.app/a.html/
- https://tabstool.net/?os=win10
- https://https--www--roblox.com/users/1596649554/profile
- https://88888.ec.cc/
- https://www.ipkobznzs.sviluppo.host/
- https://www.robiox.com.gr/users/4890711579/profile
- https://couriersplease.addliu.com/
- https://couriersplease.addlir.com/
- https://couriersplease.addlia.com/
- http://www.buyerhub.pk/
- http://www.index2027.vercel.app/
- http://index2027.vercel.app/
- https://pwlri.cn/verification/index

### PhishStats (recent phishing/malicious URLs, scored)
_No data returned this run._

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| c81dfb846d72043d82cfedada7b5fbc3f1ed956d | AsyncRAT C&C |
| de045f977bb3fcb870a7c70433ec3c4055b4df56 | AokigaharaStealer C&C |
| 794a98bb8dfb1c8707541d2f1136fc7c1faa123f | Malware C&C |
| aebfe1d6a7db6458477771a467698c52ec1cd181 | Vidar C&C |
| b8b817853b031f3c2ef9ff332422a2f75cdafb14 | Vidar C&C |
| 8bc6b066cdd4399e5217c58236bb0f32971a4d49 | OffLoader C&C |
| a3e3e53c9b5eb4d1d1197181c599f07ca61b3c9e | Vidar C&C |
| d7d1025725506635e295b7a5eb61c2162f2a1f93 | Vidar C&C |
| 88dfcb0baeaaec06b4973eeb6b8bf76e7ff16315 | ConnectWise C&C |
| 8439a45334bfd81293cf20abb44f3e20843131db | Vidar C&C |
| 32facbb63422b11875f949b45ceb306e4673a3b7 | Malware C&C |
| db1370abc2fbcfc4d9dc332b56f0d2e91deb9d23 | PureLogsStealer C&C |
| 840910d1faf7f934326f08cd5424862ca50646d5 | OffLoader C&C |
| b843ff0bf989bbda8086054a9d9ce65e885e4845 | RevStealer C&C |
| 62ddff80b88f12d3ca6ba44eb09b5e7ba9e2f390 | RevStealer C&C |
| 4623e7174a6917c16402029733c2aaa14d2f83dd | RevStealer C&C |
| 3a2dc08faa4e47e147c1293b240d7502efa7db48 | Vidar C&C |
| be3eba6ce90c5d19ee1e986170e96323108d092d | Vidar C&C |
| 2444b1d1f72da59dc3bcc0191170509822344090 | Vidar C&C |
| 875a92bb886a52699413fb2e4370adc03c1eda37 | QuasarRAT C&C |

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
- 1.12.55.42
- 1.14.240.247
- 1.140.72.67
- 1.15.106.134
- 1.15.221.192
- 1.15.42.91
- 1.159.54.33
- 1.180.246.242
- 1.187.164.7
- 1.201.146.109
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.222.57.68
- 1.234.80.94
- 1.235.183.146
- 1.238.106.229
- 1.247.245.61
- 1.250.67.114

### CINS Army (poorly-rated IPs)
- 1.15.14.29
- 1.179.240.27
- 1.193.63.52
- 1.220.119.115
- 1.24.16.10
- 1.24.16.100
- 1.24.16.148
- 1.24.16.159
- 1.24.16.169
- 1.24.16.170
- 1.24.16.182
- 1.24.16.31
- 1.24.16.32
- 1.24.16.4
- 1.24.16.51
- 1.24.16.71
- 1.24.16.82
- 1.24.16.83
- 1.24.16.96
- 1.24.18.131

## News (last ~36h, across outlets)
### The Hacker News
- [Hackers Actively Exploit Highly Critical Drupal Commerce Core Authorization Bypass Flaw](https://thehackernews.com/2026/10/hackers-actively-exploit-highly.html)
- [CISA Adds Actively Exploited GitLab RCE and Cisco Firewall DoS Flaws to KEV](https://thehackernews.com/2026/10/cisa-adds-actively-exploited-gitlab-rce.html)
- [Binance Suffers Security Breach Affecting $6.3 Billion in Assets, Nearly $3 Billion Frozen](https://thehackernews.com/2026/10/binance-suffers-security-breach.html)
- [ThreatsDay: Critical Firewall Flaws, Banking Trojans Rented, Weaponized PDF, Token Theft + 26 More Stories](https://thehackernews.com/2026/10/threatsday-critical-firewall-flaws.html)
- [Linux Kernel TCP Flaw With 9.8 CVSS Score Affects Ubuntu, Red Hat and Other Distributions](https://thehackernews.com/2026/10/linux-kernel-tcp-flaw-with-98-cvss.html)
- [Fake ChatGPT and Claude Apps Abuse Signed Executables to Deploy Crypto Miners](https://thehackernews.com/2026/10/fake-chatgpt-and-claude-apps-abuse.html)
- [Google's Gemini 4 Carbon Leads Benchmarks for Finding, Exploiting, and Patching Vulnerabilities](https://thehackernews.com/2026/10/googles-gemini-4-carbon-leads.html)
- [Webinar: How to Build AI Threat Readiness Into Your Security Operations](https://thehackernews.com/2026/08/learn-how-to-build-security-operations.html)
- [Telegram Android Flaw Lets Attackers Run Code When Users Answer Voice Calls](https://thehackernews.com/2026/10/telegram-android-flaw-lets-attackers.html)
- [The Rise of the Threat Operator: How AI Will Redefine Security Operations and Careers](https://thehackernews.com/2026/10/the-rise-of-threat-operator-how-ai-will.html)
- [26,400 Valid Cloud and AI Credentials Found Exposed in Public Gitee Repositories](https://thehackernews.com/2026/10/26400-valid-cloud-and-ai-credentials.html)
- [Cisco Patches Actively Exploited ASA and FTD VPN Flaw That Can Crash Firewalls](https://thehackernews.com/2026/10/cisco-patches-actively-exploited-asa.html)
- [GitHub Launches npm Firewall to Block Malicious Packages Before Installation](https://thehackernews.com/2026/10/github-launches-npm-firewall-to-block.html)
- [Attacker Tried to Exploit Alpine Linux’s GitLab via CVSS 10.0 Flaw Its Ruby Left Open](https://thehackernews.com/2026/10/attacker-tried-to-exploit-alpine-linuxs.html)
- [Hackers Exploited Cisco SD-WAN Flaw to Plant Malware Built to Steal Encryption Keys](https://thehackernews.com/2026/10/hackers-exploited-cisco-sd-wan-flaw-to.html)

### BleepingComputer
- [Binance links $6.3 billion crypto theft to compromised DevOps laptop](https://www.bleepingcomputer.com/news/security/binance-links-63-billion-crypto-theft-to-compromised-devops-laptop/)
- [OpenAI doubles ChatGPT Pro usage limits after backlash over planned 50% cut](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-doubles-chatgpt-pro-usage-limits-after-backlash-over-planned-50-percent-cut/)
- [Binance probes potential $5.8 billion crypto-theft hack](https://www.bleepingcomputer.com/news/security/binance-probes-potential-58-billion-crypto-theft-hack/)
- [Hugging Face malware campaign returns to hijack GPUs for crypto mining](https://www.bleepingcomputer.com/news/security/hugging-face-malware-campaign-returns-to-hijack-gpus-for-crypto-mining/)
- [Japan Airlines suffers third-party data breach exposing passenger info](https://www.bleepingcomputer.com/news/security/japan-airlines-suffers-third-party-data-breach-exposing-passenger-info/)
- [Polymarket halts trading after crypto-draining script breach, $2.5M traced](https://www.bleepingcomputer.com/news/security/polymarket-halts-trading-after-crypto-draining-script-breach-25m-traced/)
- [Fake crypto app on Apple App Store linked to $23K wallet theft](https://www.bleepingcomputer.com/news/security/fake-crypto-app-on-apple-app-store-linked-to-23k-wallet-theft/)
- [Hackers exploit Cisco SD-WAN flaw to deploy custom KeyDrift malware](https://www.bleepingcomputer.com/news/security/hackers-exploit-cisco-sd-wan-flaw-to-deploy-custom-keydrift-malware/)
- [Chrome extensions with 13.4 million installs caught hijacking searches](https://www.bleepingcomputer.com/news/security/chrome-extensions-with-134-million-installs-caught-hijacking-searches/)
- [Microsoft fixes Remote Desktop failures caused by recent Windows updates](https://www.bleepingcomputer.com/news/microsoft/microsoft-fixes-remote-desktop-failures-caused-by-recent-windows-updates/)
- [3 Ways AI Agents Already Operate in Your Browser](https://www.bleepingcomputer.com/news/security/3-ways-ai-agents-already-operate-in-your-browser/)
- [CISA warns of Fragnesia Linux flaw chained in PHP2Shell attacks](https://www.bleepingcomputer.com/news/security/cisa-warns-of-fragnesia-linux-flaw-chained-in-php2shell-attacks/)
- [Windows 11 KB5127936 update released with 41 changes and fixes](https://www.bleepingcomputer.com/news/microsoft/windows-11-kb5127936-update-released-with-41-changes-and-fixes/)
- [New Cisco firewall zero-day exploited to crash SSL VPN devices](https://www.bleepingcomputer.com/news/security/cisco-warns-of-firewall-zero-day-exploited-to-crash-ssl-vpn-devices/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [As Russia's Cyberwar Evolves, Belarus Steps Forward](https://www.darkreading.com/physical-security/russia-cyber-war-belarus-steps-forward)
- [Anthropic-Themed Phishing Emails Bypass Top Security Tools](https://www.darkreading.com/cyberattacks-data-breaches/anthropic-phishing-emails-bypass-security-tools)
- [Rethinking Cybersecurity Awareness in the AI Era](https://www.darkreading.com/cyber-risk/rethinking-cybersecurity-awareness-ai-era)
- [Claude Model Builds Exploits Across Major Browsers &amp; OSes](https://www.darkreading.com/application-security/claude-model-exploits-major-browsers-oses)
- [Threat Modeling With 4 Simple Questions on a White Board](https://www.darkreading.com/cyber-risk/threat-modeling-4-simple-questions)
- [Shadowy AI Relay Disables OpenAI Codex, Claude Code Sandboxes](https://www.darkreading.com/threat-intelligence/ai-relay-service-openai-codex-claude-code-sandboxes)
- [Cyber Vulnerabilities Besiege Italy, Absent Clear Cause](https://www.darkreading.com/cybersecurity-analytics/cyber-vulnerabilities-besiege-italy)

### SecurityWeek
- [$2 Million+ Drained From Polymarket Traders in New Supply Chain Attack](https://www.securityweek.com/2-million-drained-from-polymarket-traders-in-new-supply-chain-attack/)
- [Max-Severity GitLab Vulnerability Exploited Against Alpine Linux](https://www.securityweek.com/max-severity-gitlab-vulnerability-exploited-against-alpine-linux/)
- [TeamViewer Flaw Could Let Malicious Hosts Take Over Support Technicians’ Machines](https://www.securityweek.com/teamviewer-flaw-could-let-malicious-hosts-take-over-support-technicians-machines/)
- [$6 Billion Binance Hack Bears Hallmarks of North Korea’s TraderTraitor](https://www.securityweek.com/6-billion-binance-hack-bears-hallmarks-of-north-koreas-tradertraitor/)
- [When Risk Becomes Personal: What Security Leaders Can Learn From a Cancer Diagnosis](https://www.securityweek.com/when-risk-becomes-personal-what-security-leaders-can-learn-from-a-cancer-diagnosis/)
- [Google Touts Powerful Cybersecurity Capabilities in Gemini 4 Carbon Model](https://www.securityweek.com/google-says-gemini-4-carbon-leads-in-finding-exploiting-and-fixing-vulnerabilities/)
- [How Secure Are US Elections? Voting Machine Risks and the Growing Threat of AI](https://www.securityweek.com/how-secure-are-us-elections-voting-machine-risks-and-the-growing-threat-of-ai/)
- [Cisco Open Sources Quarry to Catch AI Agent Attacks Hidden in Harmless Steps](https://www.securityweek.com/cisco-open-sources-quarry-to-catch-ai-agent-attacks-hidden-in-harmless-steps/)
- [Adobe, Veeam, Juniper Networks Patch Critical Vulnerabilities](https://www.securityweek.com/adobe-veeam-juniper-networks-patch-critical-vulnerabilities/)
- [BAE Says No Data Extracted in Incident Hitting Bankruptcy Courts](https://www.securityweek.com/bae-says-no-data-extracted-in-incident-hitting-bankruptcy-courts/)

### The Record
- [Limited reports of PHP bug exploitation emerge](https://therecord.media/php2shell-successful-exploitation-reports-emerge)
- [GM settles with 36 states for selling driver data, agrees to $220 million fine and reforms](https://therecord.media/general-motors-lawsuit-privacy)
- [Federal bankruptcy courts contractor says no data stolen during cyber intrusion](https://therecord.media/us-bankruptcy-courts-it-contractor-says-no-data-stolen-cyberattack)
- [FTC to probe major companies over personalized pricing and pay](https://therecord.media/ftc-rideshare-airlines-data)
- [Cyberattack disrupts Belgian tax services before filing deadline](https://therecord.media/cyberattack-disrupts-belgian-tax-services-before-deadline)

### Infosecurity Magazine
- [NIK C2 Malware Can Use Victims’ OpenAI Keys for AI Queries](https://www.infosecurity-magazine.com/news/nik-c2-malware-victims-openai-keys/)
- [CREST Urges Whole-Ecosystem Approach to Financial Cyber Resilience](https://www.infosecurity-magazine.com/news/crest-financial-cyber-resilience/)
- [Online Scam Volumes Double to Overtake Phishing](https://www.infosecurity-magazine.com/news/online-scam-volumes-double/)
- [ICO Reprimands Staffordshire Police After Domestic Abuse Breach](https://www.infosecurity-magazine.com/news/ico-reprimand-staffordshire-police/)
- [NIST Publishes Guidance to Meet Federal Post-Quantum Deadlines](https://www.infosecurity-magazine.com/news/nist-guidance-post-quantum/)
- [MR ROBOT Malware-as-a-Service Targets Indian Bank Customers](https://www.infosecurity-magazine.com/news/robot-malware-indian-bank-customers/)

### CyberScoop
- [Leaked DHS employee archive, Icepick, faces challenges to stay online](https://cyberscoop.com/dhs-employee-breach-icepick-database-takedown/)
- [Officials seize domain of top bulletproof hosting provider Virtualine](https://cyberscoop.com/virtualine-bulletproof-hosting-provider-seized/)

### Cisco Talos
- [A quiet week in infosec <.<](https://blog.talosintelligence.com/a-quiet-week-in-infosec/)
- [IR trends Q3 2026: Actors impersonate IT help desks in vishing attacks as ransomware activity increases](https://blog.talosintelligence.com/ir-trends-q3-2026/)
- [NIK C2: The new AI-enabled command-and-control framework](https://blog.talosintelligence.com/nik-c2-new-ai-enabled-framework/)

### Unit 42 (Palo Alto)
- [Threat Brief: Critical Vulnerabilities in PHP: CVE-2026-109618, CVE-2026-109619 (Updated October 29)](https://unit42.paloaltonetworks.com/cve-2026-109618-cve-2026-109619/)

### Microsoft Security Blog
- [Tracking AI adoption in North Korean threat actor tradecraft](https://www.microsoft.com/en-us/security/blog/2026/10/29/tracking-ai-adoption-in-north-korean-threat-actor-tradecraft/)
- [IDC MarketScape names Microsoft a Leader in the 2026 Worldwide Modern Endpoint Security for Enterprises Vendor Assessment](https://www.microsoft.com/en-us/security/blog/2026/10/29/idc-marketscape-names-microsoft-a-leader-in-the-2026-worldwide-modern-endpoint-security-for-enterprises-vendor-assessment/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Friday, October 30th, 2026 https://isc.sans.edu/podcastdetail/10158, (Fri, Oct 30th)](https://isc.sans.edu/diary/rss/33472)
- [Deploying a Local Ghidra Server for Your Malware Analysis Lab, (Thu, Oct 29th)](https://isc.sans.edu/diary/rss/33470)
- [ISC Stormcast For Thursday, October 29th, 2026 https://isc.sans.edu/podcastdetail/10156, (Thu, Oct 29th)](https://isc.sans.edu/diary/rss/33468)
- [Yet Another ClickFix Campaign, (Wed, Oct 28th)](https://isc.sans.edu/diary/rss/33466)

### Securelist (Kaspersky)
- [Unknown APT uses NetamLoader to attack a Win10 OS customized for governments in Asia](https://securelist.com/netamloader/121676/)

### CrowdStrike Blog
- [New Prompt Injection Techniques Cover Agent-Planning Attacks](https://www.crowdstrike.com/en-us/blog/new-prompt-injection-techniques-cover-agent-planning-attacks/)
- [VAPOR PANDA Uses AI-Driven ARTEX to Scale a Global Espionage Campaign](https://www.crowdstrike.com/en-us/blog/vapor-panda-uses-artex-to-scale-global-campaign/)
- [When AI Guardrails Expose Vulnerabilities](https://www.crowdstrike.com/en-us/blog/when-ai-guardrails-expose-vulnerabilities/)
- [CrowdStrike 2026 Legal Threat Landscape Report: eCrime Leads Attacks, China Activity Intensifies](https://www.crowdstrike.com/en-us/blog/crowdstrike-2026-legal-threat-landscape-report/)
- [Obstacles to Weaponizing PHP2Shell Likely Constrain Immediate Widespread Exploitation](https://www.crowdstrike.com/en-us/blog/obstacles-to-weaponizing-php2shell-likely-constrain-exploitation/)
- [Why Organizations Secure AI Agents with Falcon Guardian](https://www.crowdstrike.com/en-us/blog/why-organizations-secure-ai-agents-with-falcon-guardian/)
- [CrowdStrike Protects Customers from Threats Delivered via PHP2Shell](https://www.crowdstrike.com/en-us/blog/crowdstrike-protects-customers-from-php-rce-zero-days/)
- [CrowdStrike Uncovers New Agentic AI Campaigns](https://www.crowdstrike.com/en-us/blog/crowdstrike-uncovers-new-agentic-ai-campaigns/)
- [CrowdStrike Achieves NCSC CIR Enhanced Level Assurance](https://www.crowdstrike.com/en-us/blog/crowdstrike-achieves-uk-ncsc-cir-enhanced-level-assurance/)
- [U.S. Government Disrupts FAMOUS CHOLLIMA Operation with CrowdStrike Assistance](https://www.crowdstrike.com/en-us/blog/fbi-disrupts-famous-chollima-operation-with-crowdstrike-assistance/)

### FortiGuard Threat Signal
_No new items / feed unavailable this run._

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/
- https://api.phishstats.info/api/phishing?_sort=-id&_size=30 -> 502 Server Error: Bad Gateway for url: https://api.phishstats.info/api/phishing?_sort=-id&_size=30

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal