# Winjit Daily TI Digest — 2026-10-17

_Auto-generated. Window: last ~24h. Fetched at 2026-10-17T07:38:08.948769+00:00Z_

**At a glance:** 2 new KEV · 33 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-102764 | BeyondTrust | Remote Support | BeyondTrust Remote Support Authentication Bypass by Spoofing Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2025-61624 | Fortinet | Multiple Products | Fortinet Multiple Products Path Traversal Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-111643 | 9.8 | n/a | Misaka Danmu Server through 2.8.9 contains an authentication bypass vulnerability that allows unauthenticated attackers to write arbitrary configuration keys via the unprotected POST /api/ui/config-hi |
| CVE-2026-111690 | 9.8 | n/a | Simple Admin Core through 1.8.7 contains an authentication bypass vulnerability that allows unauthenticated attackers to forge super administrator tokens by using the hard-coded Auth.AccessSecret in a |
| CVE-2026-111693 | 9.8 | n/a | DataBuff ai-apm-web through 0.1.10 contains a hard-coded default credentials vulnerability that allows unauthenticated attackers to gain administrator access using the built-in admin/Databuff@123 acco |
| CVE-2026-111704 | 9.8 | n/a | LangChat through commit 2a6285a contains a missing authentication vulnerability that allows unauthenticated remote attackers to access REST controllers because no Sa-Token interceptor is registered. A |
| CVE-2026-104736 | 9.8 | n/a | The LearnPress plugin for WordPress is vulnerable to PHP Object Injection in versions up to, and including, 4.4.10 via deserialization of untrusted input from the 'checkout-email' request parameter du |
| CVE-2026-110653 | 9.1 | n/a | The Appointment Booking Plugin – LatePoint | Calendar & Scheduling for WordPress plugin for WordPress is vulnerable to Authentication Bypass via Race Condition in all versions up to, and including, 5. |
| CVE-2026-111380 | 8.8 | 0.3% | FreeRDP from 3.29.0 before 3.32.0 contains an integer overflow in the Apple audin backends (audin_mac.m, audin_ios.m), which compute the audio queue buffer size as FramesPerPacket * 2 * nChannels in U |
| CVE-2026-111723 | 8.8 | n/a | LingGuo-Drama through commit 8a6924a contains a missing authorization vulnerability that allows any registered user to manage all accounts through the /admin/v1/admins API protected only by AuthAdminJ |
| CVE-2026-111633 | 8.6 | n/a | ZKEACMS through 4.4 contains an authentication bypass vulnerability that allows unauthenticated attackers to forge REST API JWT bearer tokens using a hard-coded HMAC-SHA256 signing key in JwtBearerDef |
| CVE-2026-111650 | 8.6 | n/a | ChronoFrame through 1.0.0 contains a missing authentication vulnerability in the server/api/wizard/ handlers that allows unauthenticated attackers to reconfigure already configured instances. Attacker |
| CVE-2026-111663 | 8.6 | n/a | Chaskiq through 2.0.3 contains a server-side request forgery vulnerability that allows unauthenticated attackers to fetch arbitrary URLs via the createUrlUpload GraphQL mutation. Attackers can submit  |
| CVE-2026-111680 | 8.3 | n/a | APIPark through 1.9.7-beta contains an authorization bypass vulnerability that allows authenticated team managers to access other teams' services and applications by supplying their own team id in the |
| CVE-2026-111684 | 8.3 | n/a | Magistrala through 1.0.0 contains an authorization bypass vulnerability that allows authenticated workspace members to view, issue, and revoke other tenants' device certificates by supplying foreign s |
| CVE-2026-111605 | 8.1 | n/a | Jpom through 2.11.12 contains an authorization bypass vulnerability in SshFileController that allows authenticated workspace users to access SSH hosts belonging to other workspaces by supplying foreig |
| CVE-2026-111634 | 8.1 | n/a | Helical Insight through 7.0.0 contains an sql injection vulnerability that allows authenticated viewers to inject SQL through unescaped report parameter values sent to /executeDatasource. Attackers ca |
| CVE-2026-111639 | 8.1 | n/a | bbs-go through 4.4.6 contains an authentication bypass vulnerability in the /api/login/google_one_tap endpoint that allows remote attackers to log in as other users by submitting Google ID tokens issu |
| CVE-2026-92798 | 8.1 | n/a | The User Registration & Membership plugin for WordPress is vulnerable to Arbitrary Shortcode Execution in versions up to, and including, 5.2.8 This is due to insufficient input sanitization in the 're |
| CVE-2026-111389 | 7.7 | 0.2% | Frappe HRMS 14.x before 14.38.2, 15.x before 15.64.0, and 16.x before 16.18.0 contains a SQL injection vulnerability in some endpoints caused by missing input validation. Any authenticated attacker, i |
| CVE-2026-111638 | 7.7 | n/a | sshportal through 1.19.5 contains a missing authorization vulnerability in the management shell 'key show' command that allows authenticated non-admin users to obtain decrypted backend private SSH key |
| CVE-2026-111613 | 7.5 | n/a | AllData through 0.7.1 contains an unauthenticated JDBC injection vulnerability that allows remote attackers to open arbitrary database connections by supplying jdbcUrl and jdbcDriverClass values to th |
| CVE-2026-111685 | 7.5 | n/a | IceCMS through 4.1.5 contains an unauthenticated sql injection vulnerability that allows remote attackers to inject SQL by supplying a crafted num path parameter to /WebResource/findresourcebynum. Att |
| CVE-2026-111710 | 7.5 | n/a | Netcore NR256CN through 1.5.140116 contains a NULL pointer dereference vulnerability in the Boa web server's user_auth() function that allows unauthenticated attackers to crash the server via a malfor |
| CVE-2026-107762 | 7.5 | n/a | The Kirki – Freeform Page Builder, Website Builder & Customizer plugin for WordPress is vulnerable to Insecure Direct Object Reference in all versions up to, and including, 6.3.2 via the 'context' par |
| CVE-2026-108123 | 7.5 | n/a | The WP Booking System – Booking Calendar plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 2.1.0.3 This is due to the plugin not properly verifying that  |
| CVE-2026-111675 | 7.4 | n/a | Course-tencent-cloud through 2.0.1 contains an improper restriction of authentication attempts vulnerability that allows unauthenticated attackers to brute force 6-digit SMS/email verification codes,  |
| CVE-2026-111644 | 7.3 | n/a | Misaka Danmu Server through 2.8.9 contains a missing authentication vulnerability that allows unauthenticated attackers to access audit, diagnostics, data-check, scan-index and health routes under /ap |
| CVE-2026-104734 | 7.2 | n/a | The Kirki – Freeform Page Builder, Website Builder & Customizer plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 6.3.2 via deserialization of untrusted  |
| CVE-2026-109208 | 7.2 | n/a | The LearnPress – WordPress LMS Plugin for Create and Sell Online Courses plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'quantity (REST) / order_comments (checkout)' paramet |
| CVE-2026-103899 | 7.2 | n/a | The EU VAT Assistant for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'vat_number' parameter in all versions up to, and including, 2.1.30.260413 due to insuffi |
| CVE-2026-96660 | 7.2 | n/a | The User Registration & Membership – Free & Paid Memberships, Subscriptions, Content Restriction, User Profile, Custom User Registration & Login Builder plugin for WordPress is vulnerable to Stored Cr |
| CVE-2026-111695 | 7.1 | n/a | Shaiwz data-platform-open through commit efeacd3 contains an insecure direct object reference vulnerability that allows authenticated workspace members to access other workspaces' datasources by numer |
| CVE-2026-111700 | 7.1 | n/a | WebVella ERP through 1.8.8 contains an sql injection vulnerability that allows any authenticated user to inject SQL through WHERE-clause text literals in the EQL query API. Attackers can send crafted  |
| CVE-2026-62439 | 7.0 | n/a | A flaw was found in GIMP. An integer overflow occurs in the file-pvr plug-in when calculating memory buffer sizes for image dimensions. By tricking a user into opening or previewing a specially crafte |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-52ff-p635-qf9p | CVE-2026-97314 | unknown | The ThirstyAffiliates  WordPress plugin before 3.12.1 does not check the status or type of the... |
| GHSA-vv83-mghr-rv2c | CVE-2026-92431 | unknown | The Patreon WordPress plugin before 1.10.0 does not perform an authorization check on some of its... |
| GHSA-8hhj-377x-qmw2 | CVE-2026-92432 | unknown | The Patreon WordPress plugin before 1.10.0 does not validate a user-supplied redirect destination... |
| GHSA-w3q2-34vh-jqmw | CVE-2026-92433 | unknown | The Patreon WordPress plugin before 1.10.0 does not verify a nonce when connecting the site to a... |
| GHSA-4rjp-9x4j-xqhv | CVE-2026-110268 | medium | The Post Export Import with Media plugin for WordPress is vulnerable to Directory Traversal in... |
| GHSA-3gjr-mw3r-975c | CVE-2026-109369 | medium | The WP Booking System – Booking Calendar plugin for WordPress is vulnerable to authorization... |
| GHSA-q4hg-2jqc-r6m6 | CVE-2026-109985 | medium | The xSpeed Cache: AI-Powered Performance Hub with MCP, Caching & CDN plugin for WordPress is... |
| GHSA-2wvw-mp72-5fwj | CVE-2026-108123 | high | The WP Booking System – Booking Calendar plugin for WordPress is vulnerable to authorization... |
| GHSA-cpx4-rgq2-9wvh | CVE-2026-107752 | medium | The Welcart e-Commerce plugin for WordPress is vulnerable to generic SQL Injection via the ... |
| GHSA-p8r3-cm77-gmp2 | CVE-2026-81344 | unknown | The ACF Frontend Admin by DynamiApps WordPress plugin through 3.29.13 does not restrict which PHP... |
| GHSA-93fh-f4mp-7f58 | CVE-2026-91074 | unknown | The BSK PDF Manager WordPress plugin through 3.8.1 does not properly sanitise and escape a... |
| GHSA-f5p8-wvgf-xw3f | CVE-2026-92978 | medium | The User Registration & Membership – Free & Paid Memberships, Subscriptions, Content Restriction,... |
| GHSA-5jfw-8m7v-h73m | CVE-2026-109989 | medium | The Themify Popup plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the ... |
| GHSA-mc7j-c3xf-rrxf | CVE-2026-96660 | high | The User Registration & Membership – Free & Paid Memberships, Subscriptions, Content Restriction,... |
| GHSA-fc28-r9m2-c784 | CVE-2026-92798 | high | The User Registration & Membership plugin for WordPress is vulnerable to Arbitrary Shortcode... |
| GHSA-4x57-h4wj-759x | CVE-2026-109368 | medium | The WP Booking System – Booking Calendar plugin for WordPress is vulnerable to Sensitive... |
| GHSA-3972-hwr2-mqjw | CVE-2026-92715 | medium | The Tutor LMS – eLearning and online course solution plugin for WordPress is vulnerable to... |
| GHSA-jmr2-v244-x8cp | CVE-2026-106470 | unknown | The WP Data Access  WordPress plugin before 5.5.88 does not have authorisation and CSRF checks in... |
| GHSA-c523-6gwp-mjrc | CVE-2026-111726 | medium | The Themify Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via ... |
| GHSA-pvfc-2cxg-992w | CVE-2026-103376 | unknown | The PeachPay — Payments & Express Checkout for WooCommerce (supports Stripe, PayPal, Square,... |
| GHSA-rv5m-5pv4-6hxw | CVE-2026-104122 | unknown | The Ukr-To-Lat WordPress plugin through 1.3.5 does not sanitize and escape a term name before... |
| GHSA-jjg3-qq29-rm7h | CVE-2026-81343 | unknown | The ACF Frontend Admin by DynamiApps WordPress plugin through 3.29.13 does not perform a... |
| GHSA-9vjv-8c2x-cq8c | CVE-2026-104246 | unknown | The Contact Form 7 Signature Addon WordPress plugin through 4.2.2 does not sanitize a signature... |
| GHSA-v7wr-g973-rw99 | CVE-2026-110527 | unknown | The WP User Manager  WordPress plugin before 2.9.20 does not roll back the WordPress account it... |
| GHSA-vm66-9mh3-25v8 | CVE-2026-107744 | medium | The LearnPress – WordPress LMS Plugin for Create and Sell Online Courses plugin for WordPress is... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Chugoku Bend | everest |  | 2026-10-17T03:07:09.380455+00:00 |
| Taekwang Network | everest | KR | 2026-10-17T03:06:33.600895+00:00 |
| Brenner Base Tunnel | everest | AT | 2026-10-17T03:05:58.919242+00:00 |
| Prafesta Ind. e Com. de Embalagens Ltda | N0n | BR | 2026-10-16T21:53:44.751763+00:00 |
| WSBI-ESBG | play | BE | 2026-10-16T20:40:40.050274+00:00 |
| New Tec Tool Limited | play | HK | 2026-10-16T20:40:05.254581+00:00 |
| MicroSearch Corporation | play |  | 2026-10-16T20:39:30.477410+00:00 |
| Pure Options | play |  | 2026-10-16T20:38:54.697094+00:00 |
| Kissei Shoji | everest | JP | 2026-10-17T03:07:45.468139+00:00 |
| ONEOK, Inc. | Redact | US | 2026-10-16T18:54:41.963065+00:00 |
| Company #80 | N0n |  | 2026-10-16T15:57:47.227005+00:00 |
| Company #79 | N0n | US | 2026-10-16T15:57:11.465109+00:00 |
| Company #78 | N0n |  | 2026-10-16T15:56:36.722081+00:00 |
| Company #77 | N0n | US | 2026-10-16T15:56:01.252137+00:00 |
| Company #76 | N0n | US | 2026-10-16T15:55:26.210449+00:00 |
| Company #72 | N0n |  | 2026-10-16T15:54:50.992242+00:00 |
| Company #71 | N0n | US | 2026-10-16T15:54:15.783656+00:00 |
| Parker-Hannifin Corporation | Redact | US | 2026-10-16T15:01:15.176403+00:00 |
| Company #82 | N0n | US | 2026-10-16T14:57:35.051129+00:00 |
| Company #81 | N0n |  | 2026-10-16T14:56:59.799581+00:00 |

## IOCs
### ThreatFox (recent, abuse.ch)
| Indicator | Type | Malware |
|---|---|---|
| 014696bc15b640ca3b480fd0ce1283c6f99687c9d3b45af18666de5e303e4075 | sha256_hash | osx.amos |
| fe1363f77be9a4e425487917d4b37bd0e2a31177f223520769b4922374a26f0d | sha256_hash | osx.amos |
| 86faae18773a4bc50538786f1926391a5d5faacdf4db04e52e0a76de8461ace1 | sha256_hash | osx.amos |
| sbhhe93865.workers.dev | domain | php.shin_webshell |
| 9f6a50eeb9f6b6aa918fef32639e75e4bdcf47eb7c226ec26f6075376669c6a1 | sha256_hash | osx.amos |
| d86c2497a43fceeb5841c6b84cc5611ece018529e93312d8814c3b0ba3e64ba3 | sha256_hash | osx.amos |
| r1oqxdev.abijacobs.co.uk | domain | js.clearfake |
| 103.115.57.95:8084 | ip:port | win.vshell |
| 203.91.78.218:8443 | ip:port | win.vshell |
| 43.247.135.185:64410 | ip:port | unknown |
| ac692b8c93d74858dffc9ac2b55fbdb3b729776cc29588cb3a91bebae265f47e | sha256_hash | unknown_loader |
| e0a7753a0bcd11621a102e4d0cf5e7a1b1fb7eb3dd2996ad765f00fb288b90a2 | sha256_hash | elf.mirai |
| a1e934b757fed45fd8375307543385366f53ad33d36aa3f29cc684a87077d941 | sha256_hash | elf.mirai |
| b6e45aa8120160979c6925429d837fed32a251861efed6fbd7ed7574cd431784 | sha256_hash | elf.mirai |
| 34a014f288c4f2e8f2d01d58cd84c813253d9b4f2fc4449adcb3225822303792 | sha256_hash | osx.amos |
| 0f48c6ae39ccba9c337f1b16482b946330181c58fa66bece7e89ea9ecfb0a454 | sha256_hash | osx.amos |
| 23460d9b06333ded0de5e8dd0777de591c80905d7c99c96ae485c02f8f8836d5 | sha256_hash | osx.amos |
| d62e373338fd3c2cdde6e73fd6213205f6f5f8da48a288b54d42a001bfbf74cf | sha256_hash | osx.amos |
| dc53f410a3f2483a3448066046dd955787c7a59473fa997803161525d77cf5db | sha256_hash | osx.amos |
| 92052044606935476c23d5b24733838019e916d3bec16eb9e0d22eae2b8839af | sha256_hash | osx.amos |

### URLhaus (recent malicious URLs, abuse.ch)
| URL | Threat | Status |
|---|---|---|
| http://105.184.104.188:39199/bin.sh | malware_download | online |
| http://31.56.52.6/setup.sh | malware_download | offline |
| http://31.56.52.6/xmrig-x64 | malware_download | online |
| http://31.56.52.6/xmrig-aarch64 | malware_download | online |
| http://31.56.52.6/xmrig-arm | malware_download | online |
| http://31.56.52.6/xmrig-x86 | malware_download | online |
| http://31.56.52.6/main_arm7 | malware_download | online |
| http://31.56.52.6/main_mpsl | malware_download | online |
| http://31.56.52.6/main_m68k | malware_download | online |
| http://31.56.52.6/main_arm5 | malware_download | online |
| http://31.56.52.6/main_sh4 | malware_download | online |
| http://31.56.52.6/main_mips | malware_download | online |
| http://31.56.52.6/main_arm6 | malware_download | online |
| http://31.56.52.6/main_ppc | malware_download | online |
| http://31.56.52.6/main_arm | malware_download | online |
| http://31.56.52.6/main_x86 | malware_download | online |
| http://31.56.52.6/main_x86_64 | malware_download | online |
| http://42.84.58.51:46758/i | malware_download | online |
| http://170.84.133.234:49286/i | malware_download | online |
| http://42.7.247.36:45946/i | malware_download | online |

### MalwareBazaar (recent samples, abuse.ch)
| SHA256 | File type | Signature |
|---|---|---|
| 9bbac682ae6adfcb1806c4621ca39a109134bee40503ee0ab272afbff25ae490 | abuse_ch | n/a |
| 2167821583aa8c2278c99d137a26750b62971b73879dad54150502ecf4e9e4ac | abuse_ch | Mirai |
| 4fc823a3de3e6247b6e91daee1e11377c2a96f9a5ff98fd71f715f1de1413db3 | abuse_ch | Mirai |
| 68172073e2ecbad0a6b23fe88a31fbddb4ddb965246f29cc643e7914cef01086 | abuse_ch | Mirai |
| 0456d49f1fc5ea9d3c2b980c50ef58827a28c0481c00dd145136f311d36368d6 | abuse_ch | Mirai |
| c3a1f83bbec527c0f208a1087074f1a21526a4191637d92e5e9751274e8a6313 | abuse_ch | n/a |
| 7f98634c81ada016093032eec6aca74bc1c72be595a660b2a54a8528934afa2d | abuse_ch | RemcosRAT |
| 1a378f4d7f7612272c23909b3fec3bacc25a10c03d71ad227d5975994dc7c8cc | abuse_ch | Mirai |
| 0b8cfee5ebcd43ed78cae7686cef4b384dad6c8f20715c59a4d647cb719980f1 | abuse_ch | Mirai |
| 952256513e1b4f841dab1021ba12b6d2512349d36ebe20dce6737152089ac652 | abuse_ch | Mirai |
| a4059ee50556710bd14fd82d546043926a69c6c748ddd7a06f52122be9324526 | abuse_ch | n/a |
| 1d9410fa39f88ea1d4d4c16b250c16943ac3993bdcbe10be41e5472a0d58c547 | abuse_ch | Mirai |
| 1c054df984eafd4b755d0a5e7880357178516148480b347358d7b3b9184857fd | abuse_ch | Mirai |
| c9b6d5d7d3f6cb54c654e318a7e73f8ca10eedfb471282c62e5609c7621c4d96 | abuse_ch | Mirai |
| 2b81d9ca2f0642144927f083fadf8cbb48ba42ef7869a75e1ac59254be9ec0c2 | whack_sh | n/a |
| 08d5b5614ba34e1829b8cadaaffa97fdf3aaf9ac63cf0895680532aa485f2506 | abuse_ch | Mirai |
| af008d6a9792e9b5467de98f3baa91f5ebd0fac7708a0c4befa94d8aaf6b4509 | abuse_ch | Mirai |
| 8c6f96076f5cce5d2346a9c448537e5af97e9b0b294dd9bc0f37105b789c3b11 | abuse_ch | n/a |
| 378b07cea2cbd47cd15bbeae1e62a6b4ca79a5b502a6311b6dff715da58e3dbb | abuse_ch | Mirai |
| 278e6f9e228efaf85e992443bcc57e9de2a455237769c40fabd0f0112f0ef930 | abuse_ch | Mirai |

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
| 77.90.185.20 | 11 |
| 152.32.225.117 | 10 |
| 196.189.236.67 | 10 |
| 202.155.18.56 | 10 |
| 66.132.186.191 | 9 |
| 107.150.123.48 | 9 |
| 167.94.146.51 | 9 |
| 193.24.211.219 | 9 |
| 195.178.110.227 | 9 |
| 2.57.121.25 | 8 |
| 2.57.121.112 | 8 |
| 2.57.122.238 | 8 |
| 45.120.216.232 | 8 |
| 45.148.10.61 | 8 |
| 45.148.10.141 | 8 |
| 45.148.10.151 | 8 |
| 45.148.10.152 | 8 |
| 45.148.10.157 | 8 |
| 45.148.10.240 | 8 |
| 45.156.129.80 | 8 |

### OpenPhish (live phishing URLs)
- https://wh-appqqe.com/index.html
- http://uphold.design/
- http://span1531.github.io/Spotify_Cloner
- https://location-findmy.cloud/help?IyQ
- http://location-findmy.cloud/IyQ
- https://rbcode.net/v/c461a6c5b1ea7a8466563b9fadfd988a
- http://fastadharprint.xyz/crs/verifycertificate.php
- http://tajahada1.blogspot.com/
- http://www.hadiah-shopee223.blogspot.com/
- http://ganar2026sp.vip/
- http://consultawebgov.info/home/index.html
- http://consultawebgov.info/
- https://lunahost.net/zookk/
- http://painelregularizargov.org/
- https://auth-ttreozrr-starrt.gitbook.io/
- https://f005.backblazeb2.com/file/docreviews/index.html#alanz@5f3b59fa9bfe4c4e06d65734301d49ead72c.net
- http://ask-exodus-wlt-lilyy.wasmer.app/
- http://armanrao123.github.io/amazon-website
- http://ledgerlive-us-learn.typedream.app/
- https://xelzavi-rpx-lormeta-c9x6hp81.pages.dev/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://away.vk.ru/away.php?rh=83c45122-52b5-4bb1-b428-bf1abadfd957 |
| N/A | https://away.vk.ru/away.php?rh=17c59437-aba7-45cf-810e-78b9994a6b66 |
| N/A | https://servicecreditagricolemiseajour.hosted.phplist.com/lists/ |
| N/A | https://away.vk.ru/away.php?rh=66525b70-9842-4541-9da9-bcfe5c40ae46 |
| N/A | https://bixsgrb.cn/Login/ |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AWnogHfrcMjMJOA5-x4JjU2A_H62FL5Ipip8qUn0FfsVqhu1vrUBPxBl4JpnqCjPGKNrTfaShVnNJQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SRrUfMgbz3cAQhpKM_X6d5p5y23ESUFFgLxBInfzkUDlcTWDFirbxoPaj37OhaWZZXmYSXYDw&dsh=S-821679495%3A1792221392948334 |
| N/A | https://www.att.com/activearmorapp?_branch_match_id=1639897745618510618&utm_source=AT%26T%20App&_branch_referrer=H4sIAAAAAAAAA8soKSkottLXT0wuySxLTSzKzS%2FSzS%2FKTM%2FM00ssKdFLzs%2FV9wtL8U6KLCzzMUqyrytKTUstKsrMS49PKsovL04tsnXOKMrPTQUAZUf3KkgAAAA%3D |
| N/A | https://iasteun.cn/Login/ |
| N/A | https://away.vk.ru/away.php?rh=af605fb0-6927-48a2-8aff-828906d58a89 |
| N/A | https://actualisationpasssecu-sg.com/ |
| N/A | http://away.vk.ru/away.php?rh=aed85c5e-110f-4655-af77-f547aa77c027 |
| N/A | https://away.vk.ru/away.php?rh=31cd31f6-546a-4534-b372-28a911243644 |
| N/A | http://43.156.0.130/v3/signin/identifier?amp;continue=https://accounts.google.com/&amp;followup=https://accounts.google.com&passive=1209600&flowName=GlifWebSignIn&flowEntry=ServiceLogin&dsh=S-231432583:1792218891749778 |
| N/A | https://modification-de-mon-abonnement.com/blog/blog.php |
| N/A | https://away.vk.ru/away.php?rh=aa79e2b3-a0cf-4217-bca9-80c0d975fa93 |
| N/A | https://stonetoolsblog.com/ |
| N/A | https://pageseuc1.actmkt.com/(S(qmutjlm44qw53ky5g5oa2oqt))/l/c5X8MfZz6j9Y7Fto3LAd |
| N/A | https://flat-bread-04ca.cloudflareaccess.com/cdn-cgi/access/login/vertiv-command-center.pages.dev?kid=617efb6eb0445e77d08421b7c2075c08ed7302463271c62a28d702c82772462a&meta=eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiIsImtpZCI6IjEyY2U5NjlmMDk3YjUyNjliNjllZjA0N2EwMjBiZGI2NGMwMTc5NjMwNzE3MzJhMWJjODg2NjJiNGUxYzJjY2IifQ.eyJ0eXBlIjoibWV0YSIsImF1ZCI6IjYxN2VmYjZlYjA0NDVlNzdkMDg0MjFiN2MyMDc1YzA4ZWQ3MzAyNDYzMjcxYzYyYTI4ZDcwMmM4Mjc3MjQ2MmEiLCJob3N0bmFtZSI6InZlcnRpdi1jb21tYW5kLWNlbnRlci5wYWdlcy5kZXYiLCJyZWRpcmVjdF91cmwiOiIvIiwic2VydmljZV90b2tlbl9zdGF0dXMiOmZhbHNlLCJpc193YXJwIjpmYWxzZSwiaXNfZ2F0ZXdheSI6ZmFsc2UsImV4cCI6MTc5MjIxODE3MSwibmJmIjoxNzkyMjE3ODcxLCJpYXQiOjE3OTIyMTc4NzEsImF1dGhfc3RhdHVzIjoiTk9ORSIsIm10bHNfYXV0aCI6eyJjZXJ0X2lzc3Vlcl9kbiI6IiIsImNlcnRfc2VyaWFsIjoiIiwiY2VydF9pc3N1ZXJfc2tpIjoiIiwiY2VydF9wcmVzZW50ZWQiOmZhbHNlLCJjb21tb25fbmFtZSI6IiIsImF1dGhfc3RhdHVzIjoiTk9ORSJ9LCJyZWFsX2NvdW50cnkiOiJVUyIsImFwcF9zZXNzaW9uX2hhc2giOiJmZjQ3MTExYjc5ZTQ3ZjNhYmVkYTUxNDRkY2VkZmE4ZDA2YzVlNjE3MDE3M2IwZmE0MjMyNDhkMGM1NjQ0YjY0In0.pOlOOu5BbcsUwDzRZ91pciUe2NI7nrq4xQ1lVg_AqMS0HKJjIyyceWdYgS3P0JRVcfAoOJpyStrBbn_drK7nBUMlanUJd7uPCAQFHxTMjUOQrbFH8PbHJcvAk3dnFi5gHiBiFCHELNS8GgADcVrvpqaAox7PfM-6IaOIZ7pu-jtXfRjSInw50oHqGyz9PEYr-3WN0ppsUv9IAi493T76riv0ZtaPXqsChvv3exBqHdc_ehlr0QicZaf82tvljPLZ1vdRWYmAu-x-_VRmzVYaI-DF_IFUxeSEk0h5cpjMrDL8_wRC3AQJdL8YsNwWUra0e-57er0-4y_SfMAiZqIdqA&redirect_url=%2F |
| N/A | https://p361951.pro/ |
| N/A | http://49.51.43.12/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=AWnogHe_pDujLaO-hl3d_3DQFjS6PW6JGM3LRrD13mxmiaQWTJuHz9b6nwmaSIh76M5SMOelnJex7g&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06STUswwQUWt2Uf3cYm30-xhqqAqAn4qCFz2spIYVXWpQnAZdAeI1tWCx45LBZtoP8Nw2Z4sWpA&dsh=S-971696013%3A1792217387301547 |

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
- 1.117.72.220
- 1.14.240.247
- 1.159.54.33
- 1.161.18.125
- 1.179.232.194
- 1.180.246.242
- 1.187.160.37
- 1.20.187.52
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.227.228.131
- 1.235.14.41
- 1.235.183.146
- 1.237.155.150
- 1.238.106.229
- 1.24.16.95
- 1.247.245.61
- 1.250.67.114

### CINS Army (poorly-rated IPs)
- 1.12.229.231
- 1.14.149.30
- 1.179.240.111
- 1.183.41.171
- 1.189.248.116
- 1.192.129.106
- 1.215.138.43
- 1.221.65.174
- 1.236.254.202
- 1.24.16.107
- 1.24.16.108
- 1.24.16.11
- 1.24.16.112
- 1.24.16.113
- 1.24.16.116
- 1.24.16.124
- 1.24.16.128
- 1.24.16.133
- 1.24.16.142
- 1.24.16.150

## News (last ~36h, across outlets)
### The Hacker News
- [Hackers Use Compromised ConnectWise Credential to Sign In to 173 Microsoft 365 Tenants](https://thehackernews.com/2026/10/hackers-use-compromised-connectwise.html)
- [Researchers Demonstrate OpenBSD Root Exploit Chaining 37-Year-Old Shared-Memory Bug](https://thehackernews.com/2026/10/researchers-demonstrate-openbsd-root.html)
- [Attackers Tampered with AOMEI Backupper's Update Servers for Minutes to Deliver a Backdoor](https://thehackernews.com/2026/10/attackers-tampered-with-aomei.html)
- [UAT-11985 Uses Fake Event Invites to Target Taiwan Research Affiliates With Google AitM Phishing](https://thehackernews.com/2026/10/uat-11985-uses-fake-event-invites-to.html)
- [OpenAI Research Model Spent 3rd-Party Test ETH Without Permission to Deploy Smart Contract](https://thehackernews.com/2026/10/openai-research-model-spent-3rd-party.html)
- [AI Decision Models and Their Impact on AI SOC Platforms](https://thehackernews.com/2026/10/ai-decision-models-and-their-impact-on.html)
- [China-Linked Hackers Exploited BeyondTrust Zero-Day to Take Over Remote Support Servers](https://thehackernews.com/2026/10/china-linked-hackers-exploited.html)
- [CERT-In Warns AI Agents Accessed Sensitive Data at Indian Organizations During Testing](https://thehackernews.com/2026/10/cert-in-warns-ai-agents-accessed.html)
- [PEERSTITCH Malware Deployed via FortiOS Flaw Bypasses Checks on Tagged VPN Sessions](https://thehackernews.com/2026/10/attackers-exploit-fortios-flaw-to.html)
- [Critical PwnEscape Linux Kernel Vulnerability Lets Guest VMs Read Host Memory](https://thehackernews.com/2026/10/critical-pwnescape-linux-kernel.html)

### BleepingComputer
- [Critical BlockStrap flaw lets hackers run code on Magento servers](https://www.bleepingcomputer.com/news/security/critical-blockstrap-flaw-lets-hackers-run-code-on-magento-servers/)
- [Targeted ads installed Candiru spyware in zero-click attacks](https://www.bleepingcomputer.com/news/security/zero-click-attacks-used-targeted-ads-to-deliver-candiru-spyware/)
- [Employees using personal ChatGPT at work? Here's what IT admins need to do](https://www.bleepingcomputer.com/news/security/employees-using-personal-chatgpt-at-work-heres-what-it-admins-need-to-do/)
- [Burger King Japan data breach exposes 11 million customer records](https://www.bleepingcomputer.com/news/security/burger-king-japan-data-breach-exposes-11-million-customer-records/)
- [Microsoft: October Windows update may break Smart App Control](https://www.bleepingcomputer.com/news/microsoft/kb5127648-windows-security-update-may-break-smart-app-control/)
- [BAE Systems cyberattack disrupts US federal court operations](https://www.bleepingcomputer.com/news/security/bae-systems-cyberattack-disrupts-us-federal-court-operations/)
- [BeyondTrust patches zero-day exploited in attacks since August](https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/)
- [Hackers exploit Collabora RCE flaw to backdoor Nextcloud servers](https://www.bleepingcomputer.com/news/security/hackers-exploit-collabora-rce-flaw-to-backdoor-nextcloud-servers/)
- [Android gets AI defenses against messaging scams, fake calls](https://www.bleepingcomputer.com/news/security/android-gets-ai-defenses-against-messaging-scams-fake-calls/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [BeyondTrust Remote Support Zero-Day Continues Trend of Exploited Edge Bugs](https://www.darkreading.com/endpoint-security/beyondtrust-remote-support-exploited-edge-bugs)
- [Fake Claude, ChatGPT Attacks Surge, Putting Developers at Risk](https://www.darkreading.com/application-security/fake-claude-chatgpt-attacks-developers-risk)
- [Biomemory Launches DNA Shield, First Commercial Product Built on Its Molecular IT Platform](https://www.darkreading.com/data-privacy/biomemory-launches-dna-shield)
- [Enterprise AI Enters Risk Management Phase as Security Concerns Rise](https://www.darkreading.com/cyber-risk/enterprise-ai-risk-management-phase-security-concerns-rise)
- [AI Takes Control of Robotic Arm in 16 Minutes Flat](https://www.darkreading.com/ics-ot-security/ai-takes-control-robotic-arm-16-minutes)
- [When Your Ransomware Negotiator Works for the Other Side](https://www.darkreading.com/cyber-risk/when-your-ransomware-negotiator-works-other-side)
- [When AI Agents Commit Breaches, Humans May Not Be Held Liable](https://www.darkreading.com/insider-threats/ai-agents-breaches-humans-liable)
- [SecTor 2026 Reveals a Rapidly Shifting Cybersecurity Landscape](https://www.darkreading.com/cybersecurity-operations/sector-2026-reveals-a-rapidly-shifting-cybersecurity-landscape)
- [F-Secure Launches Victim-First Scam Encyclopedia Covering 50+ Types of Consumer Fraud](https://www.darkreading.com/threat-intelligence/f-secure-launches-victim-first-scam-encyclopedia-covering-50-types-of-consumer-fraud)
- [AI Slop Isn't Just for Social Media; It's Ruining Cyberattacks, Too](https://www.darkreading.com/threat-intelligence/ai-slop-ruining-cyberattacks)

### SecurityWeek
- [In Other News: ICS-Sniper Attack, Hacking XWorm Malware Operators, $250k Chrome Exploit](https://www.securityweek.com/in-other-news-ics-sniper-attack-hacking-xworm-malware-operators-250k-chrome-exploit/)
- [BAE Systems Security Incident Stalls Notices From US Bankruptcy Courts](https://www.securityweek.com/bae-systems-security-incident-stalls-notices-from-us-bankruptcy-courts/)
- [Chinese APT Exploited BeyondTrust Vulnerability as Zero-Day](https://www.securityweek.com/chinese-apt-exploited-beyondtrust-vulnerability-as-zero-day/)
- [OpenAI Models Hacked Data Portals, Raided a Crypto Wallet to Finish Tasks](https://www.securityweek.com/openai-models-hacked-data-portals-raided-a-crypto-wallet-to-finish-tasks/)
- [F5, Juniper Networks Patch Critical Vulnerabilities](https://www.securityweek.com/f5-juniper-networks-patch-critical-vulnerabilities/)
- [Microsoft Patches Two Dozen RCE Flaws in Office](https://www.securityweek.com/microsoft-patches-two-dozen-rce-flaws-in-office/)
- [Proofpoint Inks $6.3 Billion All-Cash Deal to Acquire Varonis](https://www.securityweek.com/proofpoint-inks-6-3-billion-all-cash-deal-to-acquire-varonis/)

### The Record
- [Proofpoint lines up $6.3 billion deal for Varonis’ data security](https://therecord.media/proofpoint-varonis-cybersecurity-acquisition)
- [Moscow police detain suspected DataSuckers hackers linked to breaches in Ukraine and Russia](https://therecord.media/russia-datasuckers-hackers-arrested)
- [Baltimore suburb confirms August data breach after ransomware claims](https://therecord.media/anne-arundel-county-maryland-confirms-data-breach)
- [Suspected Chinese espionage attackers abusing BeyondTrust IT support zero-day](https://therecord.media/beyond-trust-cyberattack-china)
- [Federal bankruptcy courts dealing with outages after contractor cyberattack](https://therecord.media/federal-bankruptcy-courts-dealing-with-cyberattack-outage)

### Infosecurity Magazine
- [Ransomware Gangs Increasingly Turn to Threats of Physical Violence to Extort Payments](https://www.infosecurity-magazine.com/news/ransomware-threats-physical/)
- [China Espionage Actor Actively Targeting Critical BeyondTrust Flaw, Google Warns](https://www.infosecurity-magazine.com/news/china-actor-beyondtrust-flaw-google/)
- [Cyber Incident at BAE Systems Disrupts US Federal Bankruptcy Noticing](https://www.infosecurity-magazine.com/news/cyber-incident-bae-us-bankruptcy/)

### CyberScoop
- [Federal agencies recommend cyber controls, independent testing for frontier AI systems](https://cyberscoop.com/federal-ai-agent-sandbox-security-guidance/)
- [Prolific Chinese espionage group exploits BeyondTrust zero-day](https://cyberscoop.com/china-espionage-attacks-beyondtrust-zero-day-armory-castle/)
- [Cybersecurity incident at BAE Systems disrupts US bankruptcy court system](https://cyberscoop.com/bae-systems-cybersecurity-incident-us-bankruptcy-courts/)
- [Proofpoint to buy Varonis for $6.3 billion](https://cyberscoop.com/proofpoint-acquires-varonis-systems-data-security/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
- [Top 5 Initial Access Threat Vectors Observed by Unit 42 in September 2026](https://unit42.paloaltonetworks.com/top-5-initial-access-vectors-september-2026/)
- [AI-Powered Espionage Campaign Targets Government Linux Infrastructure](https://unit42.paloaltonetworks.com/ai-campaign-targets-linux-infrastructure/)

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Friday, October 16th, 2026 https://isc.sans.edu/podcastdetail/10140, (Fri, Oct 16th)](https://isc.sans.edu/diary/rss/33432)
- [Small Agents, Smaller Blast Radius: Controlling What AI Can Do, (Fri, Oct 16th)](https://isc.sans.edu/diary/rss/33430)
- [Panchan's Mining Island &#x5b;Guest Diary&#x5d;, (Wed, Oct 14th)](https://isc.sans.edu/diary/rss/33426)

### Securelist (Kaspersky)
_No new items / feed unavailable this run._

### CrowdStrike Blog
- [October 2026 Patch Tuesday: 1,413 CVEs Include Three Zero-Days and 75 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-october-2026/)
- [U.S. Government Disrupts FAMOUS CHOLLIMA Operation with CrowdStrike Assistance](https://www.crowdstrike.com/en-us/blog/fbi-disrupts-famous-chollima-operation-with-crowdstrike-assistance/)
- [CrowdStrike and Anthropic Give Critical Infrastructure Defenders the AI Advantage](https://www.crowdstrike.com/en-us/blog/crowdstrike-anthropic-critical-infrastructure-defense-program/)
- [Solving the Continuous Authorization Conundrum](https://www.crowdstrike.com/en-us/blog/solving-the-continuous-authorization-conundrum/)
- [Unknown Threat Actor Uses AI-Driven ARTEX to Target South Korean Finance](https://www.crowdstrike.com/en-us/blog/unknown-threat-actor-uses-artex-to-target-south-korean-finance/)
- [CrowdStrike Named a Leader in the 2026 IDC MarketScape for Worldwide Modern Endpoint Security for Enterprises Vendor Assessment](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-idc-marketscape-worldwide-modern-endpoint-security-for-enterprises/)
- [Request, Aggregate, Bypass: How Attackers Can Evade LLM Safety Classifiers](https://www.crowdstrike.com/en-us/blog/how-attackers-can-bypass-llm-safety-classifiers/)
- [Falcon Data Security for SaaS Secures Sensitive Data in Microsoft 365](https://www.crowdstrike.com/en-us/blog/falcon-data-security-for-saas-secures-sensitive-data/)
- [New in Falcon Cloud Security: Third-Party App Insights and AI-Enhanced Remediation](https://www.crowdstrike.com/en-us/blog/falcon-cloud-security-third-party-app-insights-ai-enhanced-remedation/)
- [CrowdStrike Expands Federal SOC Modernization Through CISA-Funded SIEMaaS](https://www.crowdstrike.com/en-us/blog/crowdstrike-expands-federal-soc-modernization-via-cisa-siemaas/)

### FortiGuard Threat Signal
- [Atlassian Arbitrary File Access Vulnerability](https://fortiguard.fortinet.com/threat-signal-report/6548)

## Fetch issues this run
_None — all sources responded._

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal