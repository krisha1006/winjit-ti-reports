# Winjit Daily TI Digest — 2026-11-04

_Auto-generated. Window: last ~24h. Fetched at 2026-11-04T10:41:05.500883+00:00Z_

**At a glance:** 1 new KEV · 42 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-119977 | WordPress | WordPress Core | WordPress WordPress Core Time-of-check Time-of-use (TOCTOU) Race Condition Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-121606 | 10.0 | n/a | A vulnerability has been found in Qihoo 360 D621-2, D603-2, D600-2, D619, D606-6 and D706 up to 6.4.9. Affected by this issue is the function verify_sign of the file fs2/bin/iscm of the component Firm |
| CVE-2026-121607 | 10.0 | n/a | A vulnerability was found in Qihoo 360 D603-2, D600-2, D606-6 and D706 up to 6.4.9. This affects the function testspeed_command of the file /fs2/bin/iscm. Performing a manipulation of the argument hos |
| CVE-2026-121609 | 10.0 | n/a | A vulnerability was identified in Qihoo 360 Whole Home Router M5 4.0.17.1566. This issue affects the function Home of the file /etc/init.d/mpt of the component Boot Script. The manipulation leads to h |
| CVE-2026-121615 | 10.0 | n/a | A vulnerability was determined in Linksys E5600 1.1.0.26. Affected is an unknown function of the file /cgi-bin/mesh_login.cgi of the component Login Handler. Executing a manipulation can lead to impro |
| CVE-2026-121597 | 9.9 | n/a | A weakness has been identified in TOTOLINK A950RG 4.1.2cu.5268_B20221104. This affects the function setAppEasyWizardConfig of the file /cgi-bin/cstecgi.cgi of the component Easy Setup Wizard Handler.  |
| CVE-2026-121598 | 9.9 | n/a | A security vulnerability has been detected in TOTOLINK A950RG 4.1.2cu.5268_B20221104. This impacts the function strcpy of the file /cgi-bin/cstecgi.cgi of the component Basic Wireless Configuration Ha |
| CVE-2026-121599 | 9.9 | n/a | A vulnerability was detected in TOTOLINK A950RG 4.1.2cu.5268_B20221104. Affected is the function setWiFiMultipleConfig/delWiFiMultipleConfig of the file /cgi-bin/cstecgi.cgi of the component Multi-SSI |
| CVE-2026-121600 | 9.9 | n/a | A flaw has been found in TOTOLINK A950RG 4.1.2cu.5268_B20221104. Affected by this vulnerability is the function setMacFilterRules of the file /cgi-bin/cstecgi.cgi of the component MAC Filter Handler.  |
| CVE-2026-112354 | 9.8 | n/a | Etrel INCH AC charging station management web interface prior to firmware versions 7.1.2 and 8.0.1 contains a hard-coded default credentials vulnerability that allows remote attackers to gain full Adm |
| CVE-2026-120518 | 9.1 | 0.8% | The BuddyPress XProfile Image Field plugin for WordPress is vulnerable to arbitrary file deletion in all versions up to, and including, 3.1.0. This is due to bpxp_image_field_update_on_user_activation |
| CVE-2026-76124 | 8.8 | n/a | The BuddyBoss App plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 3.2.1 via the send_feedback function. This is due to insufficient file type validati |
| CVE-2026-121451 | 8.8 | n/a | AB Download Manager before 1.11.2 contains a cross-site request forgery vulnerability in its unauthenticated browser-integration API that allows remote attackers to write attacker-chosen files to arbi |
| CVE-2026-121621 | 8.8 | n/a | A command injection vulnerability was found in Argo CD Image Updater, where a proxy URL configured on an SSH Git repository is passed unsanitized into a shell-interpreted SSH command. An attacker able |
| CVE-2026-121731 | 8.8 | n/a | RosarioSIS before 12.9 contains a sql injection vulnerability that allows authenticated non-student users, including parents, to inject SQL via the unquoted period_id parameter in StudentSummary.php.  |
| CVE-2026-121816 | 8.8 | n/a | Herowatch Mini developed by About Time Technologies has a Missing Authentication vulnerability. Unauthenticated remote attackers can connect to the affected device's ADB service and obtain an ADB shel |
| CVE-2026-120554 | 8.8 | n/a | The Import and export users and customers plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 2.5.11 This is due to a non-atomic multi-option write sequenc |
| CVE-2026-110022 | 8.4 | n/a | The PFI plugin framework deploys executable assemblies (DLLs) from a signed plugin package into the local plugin repository and loads them via reflection, but the deployment routine processes archive  |
| CVE-2026-110935 | 8.4 | n/a | The PFI plugin framework deployment routine does not validate path components when extracting archive entries to the local plugin repository. Archive entries containing relative path segments such as  |
| CVE-2026-121729 | 8.3 | n/a | emailflare before commit cf31f33 contains a missing authorization vulnerability in the inbox service /api/keys routes that allows any authenticated member to list, create and revoke API keys. Attacker |
| CVE-2026-120538 | 8.1 | 0.4% | The Easy Digital Downloads plugin for WordPress is vulnerable to authentication bypass leading to administrator account takeover in all versions up to, and including, 3.7.2. During a PayPal guest chec |
| CVE-2026-120577 | 8.1 | 0.6% | The FluentCart A New Era of eCommerce – Faster, Lighter, and Simpler plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation in the deleteFile function i |
| CVE-2026-121419 | 8.1 | n/a | SurrealDB from 3.1.0 before 3.3.0 contains an improper authentication vulnerability where the MCP BoundSubject fingerprint uses the access method name instead of per-user identity for JWT/Bearer acces |
| CVE-2026-120833 | 7.8 | 0.1% | labbench before 0.46.1 contains a deserialization of untrusted data vulnerability in read() and read_relational() that passes any file with a .p or .pickle extension to pandas.read_pickle based on the |
| CVE-2026-121818 | 7.8 | n/a | Herowatch Mini developed by About Time Technologies has a system signing vulnerability. Authenticated local attackers can exploit a publicly available test key to sign malicious programs, allowing the |
| CVE-2026-121561 | 7.7 | n/a | Label Studio before 1.23.2 (label-studio-sdk before 2.1.2) contains a server-side request forgery vulnerability that allows authenticated users to read internal URLs through image-bearing export forma |
| CVE-2026-120559 | 7.5 | 0.7% | The Contact Form Extender for Divi Builder plugin for WordPress is vulnerable to Arbitrary File Deletion due to insufficient file path validation in the cfefd_remove_uploaded_file() function in all ve |
| CVE-2026-121386 | 7.5 | n/a | FreeRDP before 3.32.2 contains a denial of service vulnerability in WinPR's winpr_read_png_from_buffer() and winpr_convert_from_jpeg(), which lack libpng/libjpeg error handling. A malicious RDP server |
| CVE-2026-121427 | 7.5 | n/a | AzuraCast through 0.23.8 fails to remove frontend_config.custom_config in PUT /station/{id}/profile/edit for users lacking the Manage station broadcasting permission, and the stored JSON is written ve |
| CVE-2026-121450 | 7.5 | n/a | CFNext before 3.1.0 contains a weak cryptographic derivation vulnerability that allows subscription link holders to recover the admin password because the subscription UUID is an MD5 of the password w |
| CVE-2026-121727 | 7.5 | n/a | Kore before 4.3.0 contains an integer underflow vulnerability in HTTP request body handling that allows unauthenticated attackers to bypass http_body_max by sending more body bytes than declared. Atta |
| CVE-2026-121617 | 7.5 | n/a | A security flaw has been discovered in Linksys E5600 1.1.0.26. Affected by this issue is the function init_multipart of the file /cgi-bin/upload_fw.cgi of the component Header Parser. The manipulation |
| CVE-2026-121817 | 7.5 | n/a | Herowatch Go Server developed by About Time Technologies has a Insecure Direct Object Reference vulnerability. Authenticated remote attackers can modify specific parameters to access or operate other  |
| CVE-2026-121502 | 7.3 | n/a | A vulnerability was identified in mathurvishal CloudClassroom-PHP-Project. The impacted element is an unknown function of the file facultydetails.php. The manipulation of the argument deleteid leads t |
| CVE-2026-121524 | 7.3 | n/a | A flaw has been found in sumiie24 School-Management-System up to d946d649c7c95e101fc5679ecd91999533bb10d7. Affected by this issue is some unknown functionality of the file parent_Login.php of the comp |
| CVE-2026-121608 | 7.3 | n/a | A vulnerability was determined in Qihoo 360 D603-2, D600-2 and D606-6 up to 6.3.2. This vulnerability affects the function on_push_message of the file /fs2/bin/iscm of the component Timezone Push Hand |
| CVE-2026-121610 | 7.3 | n/a | A security flaw has been discovered in funadmin 7.1.0. Impacted is the function Curd::selectList of the file /frontend/ajax/index of the component Frontend List Endpoint. The manipulation of the argum |
| CVE-2026-105978 | 7.2 | 0.4% | Improper input validation in management control functions may allow a remote attacker with high privileges to inject operating system commands and execute them with root privileges. |
| CVE-2026-105979 | 7.2 | 0.4% | Improper input validation in the ZeroTier VPN function may allow a remote attacker with high privileges to inject system commands and execute them with root privileges. |
| CVE-2026-105981 | 7.2 | 0.4% | Improper input validation in the Digital I/O function may allow a remote attacker with high privileges to inject operating system commands and execute them with root privileges. |
| CVE-2026-115498 | 7.2 | n/a | The Slim Jetpack plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'g<PAGE_ID>-website (Website contact-field)' parameter in all versions up to, and including, 2.7.0.1 due to i |
| CVE-2026-120757 | 7.1 | n/a | HDF5 through 2.2.0 contains a heap buffer over-read vulnerability in H5L__extern_traverse() in src/H5Lexternal.c, the default traversal callback for external links. The callback locates the target fil |
| CVE-2026-82976 | 7.1 | n/a | A flaw was found in the image-customization-controller used in OpenShift's bare metal provisioning stack. The controller registers an HTTP file server on port 8084 with no authentication. The custom i |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-x4c3-5562-wh3h | CVE-2026-62007 | high | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-3hf5-9fwq-fwv2 | CVE-2026-114426 | high | SEPPmail Secure Email Gateway before 15.1.1 processes and writes v1 file-interface upload data... |
| GHSA-cgwj-vcgg-qcjc | CVE-2026-19731 | low | Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal') vulnerability in... |
| GHSA-3c43-m234-72qw | CVE-2026-114424 | critical | SEPPmail Secure Email Gateway before 15.1.1 can evaluate attacker-influenced replacement text as... |
| GHSA-83v7-h64g-wr4c | CVE-2026-114425 | critical | SEPPmail Secure Email Gateway before 15.1.1 trusts a file path supplied in externally provided... |
| GHSA-hggc-fwq7-pw8h | CVE-2026-19721 | low | Improper restriction of XML external entity reference vulnerability in TÜBİTAK BİLGEM Software... |
| GHSA-x255-6rhg-mx7j | CVE-2026-114421 | high | SEPPmail Secure Email Gateway before 15.1.1 permits password recovery for a created but... |
| GHSA-vf28-m39r-7xjf | CVE-2026-114420 | medium | SEPPmail Secure Email Gateway before 15.1.1 does not neutralize LDAP metacharacters in an... |
| GHSA-q866-82pg-8qrm | CVE-2026-62126 | high | Allocation of Resources Without Limits or Throttling vulnerability in miniOrange SAML SP Single... |
| GHSA-hfp9-jwcf-cfg7 | CVE-2026-57666 | high | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-2rjp-mrq2-jh6r | CVE-2026-56065 | high | Insertion of Sensitive Information into Externally-Accessible File or Directory vulnerability in... |
| GHSA-r5h5-pm99-m3rh | CVE-2026-57775 | medium | Authentication Bypass Using an Alternate Path or Channel vulnerability in RelyWP Simple... |
| GHSA-jjgm-fqmr-3vwc | CVE-2026-57639 | high | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-h4pw-ggq7-3wp8 | CVE-2026-54861 | high | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-q45c-9cwx-46jr | CVE-2026-119477 | high | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-pgwx-rp76-jv29 | CVE-2026-62000 | high | Missing Authorization vulnerability in WC Lovers WCFM Marketplace wc-multivendor-marketplace... |
| GHSA-q58p-cmmq-f3q2 | CVE-2026-119366 | high | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-9w3c-qrp7-jvc2 | CVE-2026-110944 | low | Resource exhaustion vulnerability in the HTTP request handling of the QHttpServer component of Qt... |
| GHSA-54r8-946x-g5g5 | CVE-2026-121818 | high | Herowatch Mini developed by About Time Technologies has a system signing vulnerability.... |
| GHSA-g88g-cww8-g52p | CVE-2026-121816 | high | Herowatch Mini developed by About Time Technologies has a Missing Authentication vulnerability.... |
| GHSA-33f3-4jq2-r259 | CVE-2026-121817 | high | Herowatch Go Server developed by About Time Technologies has a Insecure Direct Object Reference... |
| GHSA-q5pq-qhgc-v7vf | CVE-2026-54851 | high | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-2qrc-pgx3-p26j | CVE-2026-77690 | high | ZohoCorp ManageEngine Key Manager Plus versions before 7151 were vulnerable to a Command... |
| GHSA-c5gr-wpjp-5jrv | CVE-2026-77779 | high | ManageEngine Key Manager Plus versions before 7151 were vulnerable to an Improper Access Control... |
| GHSA-v2q9-hw4w-2v6m | CVE-2026-112244 | unknown | The Duplicator  WordPress plugin before 5.1.0, duplicator-pro WordPress plugin before 5.1.0 does... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| SILIKO d.o.o. | Aoqin | SI | 2026-11-04T00:54:26.315826+00:00 |
| Petroshahd(Enap Sipetrol International - Egypt Branch) | Aoqin | CL | 2026-11-04T00:53:54.779184+00:00 |
| Nextron Technology | Aoqin | CN | 2026-11-04T00:53:18.747649+00:00 |
| Goldsmith & Hull | Aoqin | US | 2026-11-04T00:52:42.935237+00:00 |
| bliss1041.com | incransom | US | 2026-11-03T23:06:49.455458+00:00 |
| innovativedriven.com | incransom | US | 2026-11-03T23:07:14.439113+00:00 |
| butler.legal | incransom | US | 2026-11-03T23:07:38.745515+00:00 |
| roundglass.com | incransom | US | 2026-11-03T23:08:02.132893+00:00 |
| fidepartners.com | incransom | ES | 2026-11-03T23:08:29.322474+00:00 |
| darrequipment.com | chaos | US | 2026-11-03T21:44:06.006241+00:00 |
| Buchanan Ingersoll & Rooney PC | Falcon | US | 2026-11-03T20:21:16.784607+00:00 |
| Project Trojan Horse | Whitearmor |  | 2026-11-03T20:28:58.460193+00:00 |
| G... R... | SilentRansomGroup |  | 2026-11-03T12:54:26.532228+00:00 |
| DROUIN SAS | Booba Project | FR | 2026-11-03T12:20:41.591331+00:00 |
| City of Edgewater | Booba Project | US | 2026-11-03T12:21:02.640429+00:00 |
| Vetstoria | Booba Project | SE | 2026-11-03T12:21:25.106844+00:00 |
| Boardman Park | Booba Project | GB | 2026-11-03T12:21:46.008311+00:00 |
| Company #127 | N0n | SA | 2026-11-03T10:56:26.162139+00:00 |
| Company #126 | N0n |  | 2026-11-03T10:55:51.256181+00:00 |
| Company #125 | N0n | US | 2026-11-03T10:55:14.713880+00:00 |

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
| 103.159.2.113 | 10 |
| 3.129.187.38 | 9 |
| 51.159.4.12 | 9 |
| 64.62.197.77 | 9 |
| 167.94.146.48 | 9 |
| 167.94.146.57 | 9 |
| 167.94.146.63 | 9 |
| 170.231.236.98 | 9 |
| 193.24.211.219 | 9 |
| 196.189.236.67 | 9 |
| 199.165.159.9 | 9 |
| 209.99.190.186 | 9 |
| 216.36.112.159 | 9 |
| 2.57.122.238 | 8 |
| 3.130.168.2 | 8 |
| 18.218.118.203 | 8 |
| 35.210.188.215 | 8 |
| 45.148.10.151 | 8 |
| 58.182.58.128 | 8 |
| 64.62.197.152 | 8 |

### OpenPhish (live phishing URLs)
- https://digitalinv.aeronationaviation.com/method1/email.html
- https://microsoft09-one.vercel.app/
- http://www.microsoft09-one.vercel.app/
- http://www.nextwhatsapp.blogspot.com/
- https://kerijansenlawgroupcom.weupdaa.workers.dev/
- https://ventira.life/css/doc/download.html
- http://facebook24-facebook.blogspot.com/
- https://www.roblovx.com.es/share?code=54408925083919342413887764625210&type=Profile&source=ProfileShare&gameid=8304191830
- https://www.interbank.correctcertificate.com/
- http://roblox.com.ss/communities/838487772/SHOTERKETU-GIVEAWAYS
- https://apenasate-hoje2026.lat/
- https://www.facebookprofilelinks.blogspot.com/
- https://myfamilyprime-espace.com/
- https://fqg.pap.temporary.site/tricolors/seguro.html
- https://www.xf.gdmaoka.com/
- https://yrpkw7grzgo-msvlsi-5z4x8b-yrpks45c.pages.dev/welcome_aboard?welcome=1009568686956370&token248=1009568686956370&name_token136=Trollh%C3%A4ttan%20Classic%20Garage%20AB
- https://kxlrq08hwu-wptjn36fyn-3y1x8g-yr200c.pages.dev/appeals/submit-appeal-form/return/
- https://yrpkw866lkw-msvwur-5w4x9b-yrpks19p.pages.dev/send_appeal_request
- https://yrpkw7grzgo-msvlsi-5z4x8b-yrpks45c.pages.dev/send_appeal_request
- https://kxlrq08hwu-wptjn36fyn-3y1x8g-yr200c.pages.dev/send_appeal_request

### PhishStats (recent phishing/malicious URLs, scored)
_No data returned this run._

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
_No data returned this run._

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
- 1.14.192.95
- 1.14.240.247
- 1.159.54.33
- 1.162.226.183
- 1.20.191.150
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.234.80.94
- 1.235.183.146
- 1.238.106.229
- 1.247.245.61
- 1.250.67.114
- 1.250.67.190
- 1.27.251.252
- 1.55.44.10
- 1.9.47.19
- 1.92.114.88
- 1.94.62.64

### CINS Army (poorly-rated IPs)
- 1.15.14.29
- 1.168.190.191
- 1.192.129.106
- 1.193.59.243
- 1.20.151.114
- 1.204.29.139
- 1.24.16.11
- 1.24.16.141
- 1.24.16.147
- 1.24.16.188
- 1.24.16.27
- 1.24.16.44
- 1.24.16.6
- 1.24.16.63
- 1.24.16.77
- 1.24.16.78
- 1.24.16.92
- 1.24.16.94
- 1.24.16.96
- 1.24.16.99

## News (last ~36h, across outlets)
### The Hacker News
- [Russian Police Arrest 3 Suspected VasyGrek Hackers, Dismantle Criminal Infrastructure](https://thehackernews.com/2026/11/russian-police-arrest-3-suspected.html)
- [Google Issues Patches for Critical Android Flaw That Could Allow RCE Without User Interaction](https://thehackernews.com/2026/11/google-patches-critical-android-flaw.html)
- [CISA Confirms Hackers Exploiting WordPress Core Flaw During Software Upgrades](https://thehackernews.com/2026/11/cisa-confirms-hackers-exploiting.html)
- [mSecure Warns Users to Change Passwords, Reset 2FA and Passkeys After Suspicious Activity](https://thehackernews.com/2026/11/msecure-warns-users-to-change-passwords.html)
- [Chainstack Reports Production Systems Breach Exposing Customer Data and Password Hashes](https://thehackernews.com/2026/11/chainstack-reports-production-systems.html)
- [Binance Reveals How Fake Job Interviews and AI Tool Abuse Led to $6.43 Billion Theft](https://thehackernews.com/2026/11/binance-reveals-how-fake-job-interviews.html)
- [Barracuda Flaws Could Be Chained to Bypass Authorization and Gain Root Access](https://thehackernews.com/2026/11/barracuda-flaws-could-be-chained-to.html)
- [Google Warns LLMjacking Attacks Are Costing Some Enterprises Up to $1 Million in Cloud Charges](https://thehackernews.com/2026/11/google-warns-llmjacking-attacks-are.html)
- [cPGuard Update Channel Hijacked to Backdoor Linux Servers and Collect Password Hashes](https://thehackernews.com/2026/11/cpguard-update-channel-hijacked-to.html)
- [Red Hat Patches 9.8-Rated Linux TCP RCE Flaw While Ubuntu Releases Fixes for Testing](https://thehackernews.com/2026/11/red-hat-patches-98-rated-linux-tcp-rce.html)
- [The 4 Elements of Exposure Prioritization and How to Operationalize Them](https://thehackernews.com/2026/11/the-4-elements-of-exposure.html)
- [Russia-Aligned Gorbag Hackers Exploit WinRAR Flaw to Deploy Data-Stealing Malware](https://thehackernews.com/2026/11/russia-aligned-gorbag-hackers-exploit.html)
- [Hackers Exploit BTCPay Server Flaw to Steal Bitcoin and Litecoin From Hot Wallets](https://thehackernews.com/2026/11/hackers-exploit-btcpay-server-flaw-to.html)
- [Synology NAS Devices Targeted in Ransomware Attacks Exploiting Patched DSM Flaw](https://thehackernews.com/2026/11/synology-nas-devices-targeted-in.html)
- [New Wave of Refrigeration Cyberattacks Hits Supermarkets Across Europe, Forcing Stores to Pull Food](https://thehackernews.com/2026/11/second-wave-of-cyberattacks-hits.html)

### BleepingComputer
- [Hackers use n-day exploits in zero-click attacks on iOS, Android devices](https://www.bleepingcomputer.com/news/security/hackers-use-n-day-exploits-in-zero-click-attacks-on-ios-android-devices/)
- [Hackers hijack cPGuard autoupdate to deploy backdoor, steal data](https://www.bleepingcomputer.com/news/security/hackers-hijack-cpguard-autoupdate-to-deploy-backdoor-steal-data/)
- [WorkOS says attacker used ARTEX AI to breach internal sales app](https://www.bleepingcomputer.com/news/security/workos-says-attacker-used-artex-ai-to-breach-internal-sales-app/)
- [Binance says fake job interview led to $6.3 billion crypto heist](https://www.bleepingcomputer.com/news/security/binance-says-fake-job-interview-led-to-63-billion-crypto-heist/)
- [Google: LLMjacking attacks rack up $1 million in cloud AI charges](https://www.bleepingcomputer.com/news/security/google-llmjacking-attacks-rack-up-1-million-in-cloud-ai-charges/)
- [Barracuda warns of critical flaws allowing root access to devices](https://www.bleepingcomputer.com/news/security/barracuda-warns-of-critical-flaws-allowing-root-access-to-devices/)
- [Gartner Predicts SOCs Will Have 50% More Engineers Than Analysts by 2028](https://www.bleepingcomputer.com/news/security/gartner-predicts-socs-will-have-50-percent-more-engineers-than-analysts-by-2028/)
- [UK school estate hit by 3AM ransomware in suspected AI-assisted attack](https://www.bleepingcomputer.com/news/security/uk-school-estate-hit-by-3am-ransomware-in-suspected-ai-assisted-attack/)
- [Police seizes over 100 servers in investment scam crackdown](https://www.bleepingcomputer.com/news/security/police-seizes-over-100-servers-in-investment-scam-crackdown/)
- [Google adds new $250,000 Cloud VRP reward for Root-in-Cloud bugs](https://www.bleepingcomputer.com/news/google/google-adds-new-250-000-cloud-vrp-reward-for-root-in-cloud-bugs/)
- [Harvard University data breach exposed info of 851,000 accounts](https://www.bleepingcomputer.com/news/security/harvard-university-data-breach-exposed-info-of-851-000-accounts/)

### Krebs on Security
- [Tech Firms Dismantle Botnet That Turned 1.3M TV Boxes Into Proxies](https://krebsonsecurity.com/2026/11/tech-firms-dismantle-botnet-that-turned-1-3m-tv-boxes-into-proxies/)

### Dark Reading
- [Philippine Migrant Worker Data Likely Leaked in 69GB Government Breach](https://www.darkreading.com/cyberattacks-data-breaches/philippine-migrant-worker-data-69gb-government-breach)
- [Fresh European Fridge Attacks Put Cold-Chain Security in Focus](https://www.darkreading.com/ics-ot-security/fresh-european-fridge-attacks-cold-chain-security)
- [Germany Busts 'Crime-as-a-Service' Investment Fraud Outfit](https://www.darkreading.com/cybersecurity-operations/germany-crime-service-investment-fraud)
- [9 Cyber Awareness Tips That Actually Match Today's Maze of Threats](https://www.darkreading.com/cyber-risk/9-cyber-awareness-tips-todays-maze-threats)
- [LLMjacking Emerges as Thriving Cybercriminal Enterprise](https://www.darkreading.com/cloud-security/llmjacking-thriving-cybercriminal-enterprise)
- [3AM Affiliate Embraces AI-Like Loops in European School Attack](https://www.darkreading.com/data-privacy/3am-affiliate-ai-loops-european-school-attack)

### SecurityWeek
- [North Korea Launches Missiles Toward the Sea as Pyongyang Protests Against US Claims on Binance Hack](https://www.securityweek.com/north-korea-launches-missiles-toward-the-sea-as-pyongyang-protests-against-us-claims-on-binance-hack/)
- [Meta Shares Top Muse Bug Bounty Findings as Payouts Reach $1.2 Million](https://www.securityweek.com/meta-shares-top-muse-bug-bounty-findings-as-payouts-reach-1-2-million/)
- [Frontline Education Data Breach Impacts Over 1.3 Million](https://www.securityweek.com/frontline-education-data-breach-impacts-over-1-3-million/)
- [CrowdStrike Reportedly Paying $495 Million for AI Security Firms Fiddler, Dreadnode](https://www.securityweek.com/crowdstrike-reportedly-paying-495-million-for-ai-security-firms-fiddler-dreadnode/)
- [Android’s November 2026 Updates Patch Over 200 Vulnerabilities](https://www.securityweek.com/androids-november-2026-updates-patch-over-200-vulnerabilities/)
- [Critical Node-RED Flaw Exploited in Attacks](https://www.securityweek.com/critical-node-red-flaw-exploited-in-attacks/)
- [UK Cyber Chief Says the UK Will Face AI Cyberattacks on Critical Infrastructure by 2028](https://www.securityweek.com/uk-cyber-chief-says-the-uk-will-face-ai-cyberattacks-on-critical-infrastructure-by-2028/)
- [Google Dismantles XCPE Botnet of 1.3 Million Android Devices](https://www.securityweek.com/google-dismantles-xcpe-botnet-of-1-3-million-android-devices/)
- [NATO’s Crossed Swords Exercise Brings AI Agents Into Cyber Operations Training](https://www.securityweek.com/natos-crossed-swords-exercise-brings-ai-agents-into-cyber-operations-training/)
- [Over 100 European Stores Hit as Supermarket Fridge Attacks Return](https://www.securityweek.com/over-100-european-stores-hit-as-supermarket-fridge-attacks-resume/)

### The Record
- [Google dismantles massive botnet hidden in Android TV boxes](https://therecord.media/google-dismantles-botnet-hidden-android-tv-boxes)
- [Several German lawmakers and foreign policy staff received Apple warnings on spyware](https://therecord.media/german-officials-among-apple-spyware-warning-recipients)
- [British businesses caught in Europe-wide supermarket fridge attacks](https://therecord.media/british-businesses-caught-in-europe-wide-supermarket-fridge-attacks)
- [Binance CEO says ‘months-long campaign’ led to $6.3 billion theft as N. Korea denies responsibility](https://therecord.media/binance-cryptocurrency-theft-months-long-campaign-nkorea)
- [Russia dismantles infrastructure of VasyGrek cybercrime group, detains three suspects](https://therecord.media/russia-dismantles-vasygrek-infrastructure-detains-three)

### Infosecurity Magazine
- [Fake Interview of Software Engineer Led to Binance Mega-Heist](https://www.infosecurity-magazine.com/news/fake-interview-software-engineer/)
- [Russia-Aligned Gorbag Targets Ukraine for Intelligence](https://www.infosecurity-magazine.com/news/russia-gorbag-targets-ukraine/)
- [Hackers Exploit BTCPay Server Flaw to Steal Cryptocurrency](https://www.infosecurity-magazine.com/news/btcpay-server-flaw-cryptocurrency/)
- [Cyber-Attack on Refrigeration Systems Hits Supermarkets Across Europe](https://www.infosecurity-magazine.com/news/cyber-refrigeration-supermarkets/)
- [NCSC Chief Warns of Imminent AI Ransomware Threat to UK Critical Infrastructure](https://www.infosecurity-magazine.com/news/ncsc-ai-ransomware-threat-uk-cni/)
- [LLMJacking is Costing Some Businesses Up to $1m, Warns Google](https://www.infosecurity-magazine.com/news/llmjacking-cost-business-1m-warns/)
- [Police and Tech Firms Team Up to Dismantle XCPE Botnet](https://www.infosecurity-magazine.com/news/police-tech-firms-team-up-to/)

### CyberScoop
- [Defense and aerospace firm settles with government over allegedly failing to meet cybersecurity contract requirements](https://cyberscoop.com/ilc-dover-cybersecurity-settlement-false-claims-act/)
- [Oklahoma man charged with mailing threats, substances to election officials nationwide](https://cyberscoop.com/oklahoma-man-charged-white-powder-letters-election-officials/)
- [Europol dismantles investment scheme that impacted potential victims in 50 countries](https://cyberscoop.com/europol-investment-scam-takedown/)
- [Ballot scanner malfunctions, flurry of federal legal actions test election officials on final day of voting](https://cyberscoop.com/westchester-ballot-scanner-malfunctions-disinformation/)
- [CrowdStrike moves to acquire Fiddler and Dreadnode, adding AI observability and testing to its security platform](https://cyberscoop.com/crowdstrike-acquires-fiddler-dreadnode-ai-security/)
- [CISA’s new strategy runs into America’s blind trust problem](https://cyberscoop.com/cisa-2030-strategy-operational-technology-blind-trust-op-ed/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
- [Unit 42 Threat Intelligence Highlights - Nov. 2, 2026](https://unit42.paloaltonetworks.com/u42-threat-intelligence-highlights-oct-2026/)

### Microsoft Security Blog
- [Fake-download campaign uses trojanized installers to deliver monetization payloads](https://www.microsoft.com/en-us/security/blog/2026/11/03/fake-download-campaign-uses-trojanized-installers-deliver-monetization-payloads/)
- [Microsoft named a Leader in the 2026 Gartner® Magic Quadrant™ for AI Agent Management Platforms](https://www.microsoft.com/en-us/security/blog/2026/11/03/microsoft-named-a-leader-in-the-2026-gartner-magic-quadrant-for-ai-agent-management-platforms/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Wednesday, November 4th, 2026 https://isc.sans.edu/podcastdetail/10164, (Wed, Nov 4th)](https://isc.sans.edu/diary/rss/33486)
- [ISC Stormcast For Tuesday, November 3rd, 2026 https://isc.sans.edu/podcastdetail/10162, (Tue, Nov 3rd)](https://isc.sans.edu/diary/rss/33484)

### Securelist (Kaspersky)
- [MLEP in KICS for Networks 5.0: how machine learning helps track network behavior of OT devices](https://securelist.com/tr/machine-learning-event-processor-in-kics-for-networks/121794/)

### CrowdStrike Blog
- [CrowdStrike Extends the Agentic SOC to Detect and Stop Agent Insider Threats](https://www.crowdstrike.com/en-us/blog/crowdstrike-detects-and-stops-agent-insider-threats/)
- [CrowdStrike Introduces Agentic Adversary Emulation to Counter AI-Enabled Adversaries](https://www.crowdstrike.com/en-us/blog/crowdstrike-agentic-adversary-emulation-counters-ai-enabled-adversaries/)
- [CrowdStrike Brings Enterprise Browser Security to the Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-brings-enterprise-browser-security-to-falcon-platform/)
- [New Falcon Cloud Security Innovations Secure the Cloud AI Runs On](https://www.crowdstrike.com/en-us/blog/falcon-cloud-security-innovations-secure-cloud-ai-runs-on/)
- [CrowdStrike Advances AI Security and Safety from Endpoint to Cloud](https://www.crowdstrike.com/en-us/blog/crowdstrike-advances-ai-security-and-safety-falcon-guardian/)
- [Introducing AI Kill Switch: Taking Control When AI Agents Go Rogue](https://www.crowdstrike.com/en-us/blog/crowdstrike-introduces-ai-kill-switch/)
- [CrowdStrike Secures AI Agents Inside Claude Cowork](https://www.crowdstrike.com/en-us/blog/crowdstrike-secures-ai-agents-inside-claude-cowork/)
- [CrowdStrike to Acquire Dreadnode to Bring Automated AI Security Testing to the Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-to-acquire-dreadnode/)
- [CrowdStrike to Acquire Fiddler to Deliver Falcon Observe for AI Agent Observability](https://www.crowdstrike.com/en-us/blog/crowdstrike-to-acquire-fiddler/)
- [What Makes a Good Security Agent? 5 Lessons from the AgentWorks Hackathon](https://www.crowdstrike.com/en-us/blog/five-lessons-from-agentworks-hackathon/)

### FortiGuard Threat Signal
- [Linux Kernel Remote Code Execution](https://fortiguard.fortinet.com/threat-signal-report/6564)
- [Ivanti Connect Secure Zero-Day Exploitation](https://fortiguard.fortinet.com/threat-signal-report/6563)
- [OT Refrigeration Control Systems Attack](https://fortiguard.fortinet.com/threat-signal-report/6553)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/
- https://sslbl.abuse.ch/blacklist/sslblacklist.csv -> HTTPSConnectionPool(host='sslbl.abuse.ch', port=443): Read timed out. (read timeout=25)
- https://api.phishstats.info/api/phishing?_sort=-id&_size=30 -> 502 Server Error: Bad Gateway for url: https://api.phishstats.info/api/phishing?_sort=-id&_size=30

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal