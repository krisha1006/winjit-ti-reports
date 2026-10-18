# Winjit Daily TI Digest — 2026-10-18

_Auto-generated. Window: last ~24h. Fetched at 2026-10-18T07:53:34.080966+00:00Z_

**At a glance:** 0 new KEV · 29 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-104736 | 9.8 | n/a | The LearnPress plugin for WordPress is vulnerable to PHP Object Injection in versions up to, and including, 4.4.10 via deserialization of untrusted input from the 'checkout-email' request parameter du |
| CVE-2026-111911 | 9.8 | n/a | phpMyFAQ 4.0.0 before 4.1.9 contains an authentication bypass vulnerability where WebAuthn registration endpoints attach credentials to any account without authentication or challenge validation. Atta |
| CVE-2026-110653 | 9.1 | n/a | The Appointment Booking Plugin – LatePoint | Calendar & Scheduling for WordPress plugin for WordPress is vulnerable to Authentication Bypass via Race Condition in all versions up to, and including, 5. |
| CVE-2026-111884 | 8.3 | n/a | phpMyFAQ before 4.1.9 and 4.2.0-alpha before 4.2.0-beta does not require the current password when changing an account e-mail in the user control panel (UserController::updateData, api/user/data/updat |
| CVE-2026-111908 | 8.3 | n/a | phpMyFAQ 4.0.0 before 4.1.9 and 4.2.0-alpha before 4.2.0-beta contains a broken object-level authorization vulnerability in the PUT /api/v3.1/faq/update endpoint, which checks only the global edit_faq |
| CVE-2026-92798 | 8.1 | n/a | The User Registration & Membership plugin for WordPress is vulnerable to Arbitrary Shortcode Execution in versions up to, and including, 5.2.8 This is due to insufficient input sanitization in the 're |
| CVE-2026-111882 | 8.1 | n/a | phpMyFAQ 3.2.0-alpha before 4.1.9 and 4.2.0-alpha before 4.2.0-beta contains an authentication bypass vulnerability that allows IdP-authenticated users to skip TOTP two-factor authentication through t |
| CVE-2026-111909 | 8.1 | n/a | phpMyFAQ before 4.1.9 contains a missing authorization vulnerability in the deleteUser() API that allows authenticated non-superadmin users with delete_user permission to delete superadmin accounts. A |
| CVE-2026-111927 | 7.7 | n/a | Coder before 2.29.20, 2.33.0 before 2.33.12, 2.34.0 before 2.34.8, and 2.35.0 before 2.35.4 contains an improper hostname validation flaw in GetWorkspaceProxyByHostname whose SIMILAR TO pattern perfor |
| CVE-2026-111881 | 7.6 | n/a | FreeRDP from 3.14.1 before 3.32.0 contains an integer underflow in the WinPR BMP writer, where a mismatched stride calculation passes SIZE_MAX - 3 to Stream_Zero for sub-byte images. A malicious RDP c |
| CVE-2026-107762 | 7.5 | n/a | The Kirki – Freeform Page Builder, Website Builder & Customizer plugin for WordPress is vulnerable to Insecure Direct Object Reference in all versions up to, and including, 6.3.2 via the 'context' par |
| CVE-2026-108123 | 7.5 | n/a | The WP Booking System – Booking Calendar plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 2.1.0.3 This is due to the plugin not properly verifying that  |
| CVE-2026-111898 | 7.5 | n/a | phpMyFAQ 4.2.0-alpha before 4.2.0-beta contains an authentication bypass vulnerability that allows Keycloak users to take over local accounts by matching preferred_username or email. Attackers control |
| CVE-2026-111901 | 7.5 | n/a | phpMyFAQ 4.2.0-alpha before 4.2.0-beta contains an uncontrolled resource consumption vulnerability in the unauthenticated faqs and search API endpoints. Attackers can send concurrent GET requests that |
| CVE-2026-111923 | 7.5 | n/a | Fleet before 4.89.0 contains an unbounded recursion vulnerability in Apple MDM enrollment property list parsing that allows unauthenticated attackers to crash the server. Attackers can send a crafted  |
| CVE-2026-111924 | 7.5 | n/a | Fleet before 4.83.0 contains a denial of service vulnerability that allows unauthenticated attackers to exhaust server memory by sending gzip-compressed request bodies. Attackers can send small, highl |
| CVE-2026-111880 | 7.4 | n/a | FreeRDP versions from 2.0.0 before 3.32.0 contain a heap out-of-bounds write in the server hash-callback NTLM path that fails to validate the MIC offset. Unauthenticated attackers can send a crafted A |
| CVE-2026-111866 | 7.3 | n/a | A weakness has been identified in nemoTyrant manong up to 7c9e5228e133b9267ad3a415833bc9bb53193bb4. This impacts the function cache/del_cache/arr2sql of the file func.php. This manipulation causes sql |
| CVE-2026-111871 | 7.3 | n/a | A weakness has been identified in itsmeravitejak Online-Examination-System up to e6208e630b14657999bbfe4c9912302d2a1e2449. The impacted element is an unknown function of the file qsdb/usersdb/brandb/t |
| CVE-2026-111872 | 7.3 | n/a | A security vulnerability has been detected in itsmeravitejak Online-Examination-System up to e6208e630b14657999bbfe4c9912302d2a1e2449. This affects the function MySQLDB::valid/MySQLDB::getresults/MySQ |
| CVE-2026-111873 | 7.3 | n/a | A vulnerability was detected in itsmeravitejak Online-Examination-System up to e6208e630b14657999bbfe4c9912302d2a1e2449. This impacts the function MySQLDB::topicslist of the file exammanger.php of the |
| CVE-2026-104734 | 7.2 | n/a | The Kirki – Freeform Page Builder, Website Builder & Customizer plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 6.3.2 via deserialization of untrusted  |
| CVE-2026-109208 | 7.2 | n/a | The LearnPress – WordPress LMS Plugin for Create and Sell Online Courses plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'quantity (REST) / order_comments (checkout)' paramet |
| CVE-2026-103899 | 7.2 | n/a | The EU VAT Assistant for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'vat_number' parameter in all versions up to, and including, 2.1.30.260413 due to insuffi |
| CVE-2026-96660 | 7.2 | n/a | The User Registration & Membership – Free & Paid Memberships, Subscriptions, Content Restriction, User Profile, Custom User Registration & Login Builder plugin for WordPress is vulnerable to Stored Cr |
| CVE-2026-100316 | 7.2 | n/a | The European VAT Compliance Assistant for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via CF-IPCountry Header in all versions up to, and including, 1.36.10 due to ins |
| CVE-2026-111110 | 7.2 | n/a | The Payment forms, Buy now buttons, and Invoicing System | GetPaid plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'mmdwqzpoxadd' parameter in all versions up to, and includi |
| CVE-2026-111897 | 7.1 | n/a | phpMyFAQ 4.2.0-alpha before 4.2.0-beta contains an authorization bypass vulnerability that allows category-restricted editors to manage attachments of FAQs outside their categories by supplying arbitr |
| CVE-2026-111907 | 7.1 | n/a | phpMyFAQ 4.0.0 before 4.1.9 contains a cross-site request forgery vulnerability in the POST /admin/api/update-database endpoint, which executes database migrations without validating a CSRF token. Att |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-cwj3-qffg-4fm2 | CVE-2026-111875 | low | A vulnerability has been found in David-Crty Databasement up to 1.8.1. Affected by this... |
| GHSA-84pv-hx2c-786x | CVE-2026-111876 | low | A vulnerability was found in alexpasmantier television up to 0.15.9. Affected by this issue is... |
| GHSA-4m5j-grw9-w64h | CVE-2026-111874 | low | A flaw has been found in OpenCATS 0.10.0. Affected is the function processLogin of the file... |
| GHSA-7q5v-v72h-cwh3 | CVE-2026-111873 | medium | A vulnerability was detected in itsmeravitejak Online-Examination-System up to... |
| GHSA-76c2-f3p3-xq8x | CVE-2026-111872 | medium | A security vulnerability has been detected in itsmeravitejak Online-Examination-System up to... |
| GHSA-xxqh-978p-7hqv | CVE-2026-111870 | medium | A security flaw has been discovered in itsmeravitejak Online-Examination-System up to... |
| GHSA-2qc2-gvjr-chrr | CVE-2026-111871 | medium | A weakness has been identified in itsmeravitejak Online-Examination-System up to... |
| GHSA-frrj-xjh4-92p7 | CVE-2026-111869 | medium | A vulnerability was identified in makeplane plane up to 1.4.2. Impacted is an unknown function of... |
| GHSA-rp78-2737-x9fc | CVE-2026-111868 | low | A vulnerability was determined in datastax pulsar-jms up to 9.0.3. This issue affects the... |
| GHSA-p3hm-x653-5rc6 | CVE-2026-111997 | medium | ip-address before 10.7.4 allows a denial of service (CPU consumption from quadratic complexity,... |
| GHSA-x58p-mp77-7rf8 | CVE-2023-1706 | unknown | Rejected reason: This candidate is unused by its CNA. |
| GHSA-mpfx-gr32-m9c9 | CVE-2022-3404 | unknown | Rejected reason: This candidate is unused by its CNA. |
| GHSA-q6ph-39c8-3p2p | CVE-2022-1550 | unknown | Rejected reason: DO NOT USE THIS CANDIDATE NUMBER. ConsultIDs: none. Reason: This candidate was... |
| GHSA-hx9m-q84f-fgfc | CVE-2022-4463 | unknown | Rejected reason: This candidate is unused by its CNA. |
| GHSA-p249-6rmc-99jm | CVE-2019-0206 | unknown | Rejected reason: DO NOT USE THIS CANDIDATE NUMBER. ConsultIDs: none. Reason: This candidate was... |
| GHSA-g93p-xr45-m7xc | CVE-2019-0208 | unknown | Rejected reason: DO NOT USE THIS CANDIDATE NUMBER. ConsultIDs: none. Reason: This candidate was... |
| GHSA-8qg7-2f9j-6cvc | CVE-2026-111866 | medium | A weakness has been identified in nemoTyrant manong up to... |
| GHSA-hq78-gpjr-752h | CVE-2026-105391 | unknown | Rejected reason: This CVE ID has been rejected or withdrawn by its CVE Numbering Authority. |
| GHSA-72hj-xr2x-9xp8 | CVE-2026-107274 | unknown | Rejected reason: This CVE ID has been rejected or withdrawn by its CVE Numbering Authority. |
| GHSA-j43p-993c-mr3f | CVE-2026-108117 | unknown | Rejected reason: This CVE ID has been rejected or withdrawn by its CVE Numbering Authority. |
| GHSA-j6g8-ff8p-ffx2 | CVE-2026-107345 | unknown | Rejected reason: This CVE ID has been rejected or withdrawn by its CVE Numbering Authority. |
| GHSA-5g4f-pq6q-922r | CVE-2026-107772 | unknown | Rejected reason: This CVE ID has been rejected or withdrawn by its CVE Numbering Authority. |
| GHSA-xh3j-g4r6-rg5h | CVE-2014-8113 | unknown | Rejected reason: DO NOT USE THIS CANDIDATE NUMBER. ConsultIDs: none. Reason: This candidate was... |
| GHSA-2f6g-93v9-pcfq | CVE-2014-7854 | unknown | Rejected reason: DO NOT USE THIS CANDIDATE NUMBER. ConsultIDs: none. Reason: This candidate was... |
| GHSA-c2cv-ghmm-xf62 | CVE-2014-3918 | unknown | Rejected reason: DO NOT USE THIS CANDIDATE NUMBER. ConsultIDs: none. Reason: This candidate was... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Quikrete | Helix | US | 2026-10-18T02:51:45.862874+00:00 |
| Solid Trading B.V. | N0n | NL | 2026-10-18T01:26:57.708293+00:00 |
| ECO USA | N0n | US | 2026-10-18T01:26:16.619915+00:00 |
| SQA Services Inc | N0n |  | 2026-10-18T01:25:36.179500+00:00 |
| Personify Health | Helix | US | 2026-10-17T22:23:45.502451+00:00 |
| Bay Alarm | Helix | US | 2026-10-17T22:23:24.581079+00:00 |
| Smith Douglas Homes | Helix | US | 2026-10-17T22:23:03.451277+00:00 |
| Company #88 | N0n | US | 2026-10-17T19:24:26.787601+00:00 |
| Rheem Global | Helix | US | 2026-10-17T18:22:04.862943+00:00 |
| Company #86 | N0n | US | 2026-10-17T06:53:37.963927+00:00 |
| Company #85 | N0n | US | 2026-10-17T05:25:56.633167+00:00 |
| Company #84 | N0n | US | 2026-10-17T05:25:20.201640+00:00 |
| Chugoku Bend | everest |  | 2026-10-17T03:07:09.380455+00:00 |
| Taekwang Network | everest | KR | 2026-10-17T03:06:33.600895+00:00 |
| Brenner Base Tunnel | everest | AT | 2026-10-17T03:05:58.919242+00:00 |
| PART2 Global AirFreight International | Eclipse | SG | 2026-10-17T22:21:40.458651+00:00 |
| First Brothers Co., Ltd | qilin | TH | 2026-10-17T20:16:07.976121+00:00 |
| Decorolala - 500 Line Sample | BYOD |  | 2026-10-17T16:52:04.161325+00:00 |
| Prafesta Ind. e Com. de Embalagens Ltda | N0n | BR | 2026-10-16T21:53:44.751763+00:00 |
| WSBI-ESBG | play | BE | 2026-10-16T20:40:40.050274+00:00 |

## IOCs
### ThreatFox (recent, abuse.ch)
| Indicator | Type | Malware |
|---|---|---|
| https://us.9nawin.org/nk/ | url | win.vidar |
| https://us.9nawin.org/ln/ | url | win.vidar |
| https://us.9nawin.org/lo/ | url | win.vidar |
| https://us.9nawin.org/yb/ | url | win.vidar |
| https://us.9nawin.org/zo/ | url | win.vidar |
| http://192.162.199.249/cf7jcx5ttx7uw21f | url | osx.amos |
| 89a25311145ada1664428064bc5b4ae16ec3e322b1399f3d4e753de8aba3ea06 | sha256_hash | osx.amos |
| https://us.9nawin.org/yo/ | url | win.vidar |
| https://us.9nawin.org/zq/ | url | win.vidar |
| https://us.9nawin.org/lq/ | url | win.vidar |
| https://us.9nawin.org/b4/ | url | win.vidar |
| xawipo.workers.dev | domain | php.shin_webshell |
| 111.170.148.132:10011 | ip:port | unknown |
| 111.170.148.132:10012 | ip:port | unknown |
| https://ba.9nawin.org/m0/ | url | win.vidar |
| https://ba.9nawin.org/xx/ | url | win.vidar |
| 47ce866bc6022d4e2a791d73cff0a71ec37fa327646dd9099d38701135c5b9b6 | sha256_hash | unknown_loader |
| 79470e722fcc76b61df510b3053dc645bdd7715ff719dbfab79e4f51511f278f | sha256_hash | elf.mirai |
| 8c934318b8a5dae64d98dbefa3a968954fc63c2f6fdff51045e1ba921407ee91 | sha256_hash | elf.mirai |
| 0efb47bf881a6a1f80ea168eef41aa7a27164072c3a6025733bc085b7b03ee13 | sha256_hash | elf.mirai |

### URLhaus (recent malicious URLs, abuse.ch)
| URL | Threat | Status |
|---|---|---|
| http://220.161.160.148:39073/i | malware_download | online |
| http://219.157.254.40:41021/i | malware_download | online |
| http://42.230.39.96:47720/bin.sh | malware_download | online |
| http://61.53.135.200:51468/bin.sh | malware_download | online |
| http://61.53.135.200:51468/i | malware_download | online |
| http://112.226.204.29:59814/i | malware_download | online |
| http://59.180.135.152:41296/i | malware_download | online |
| http://59.97.251.59:46282/i | malware_download | online |
| http://113.231.8.253:35628/i | malware_download | online |
| http://221.14.39.83:55219/bin.sh | malware_download | online |
| http://123.9.218.23:59961/i | malware_download | online |
| http://45.172.218.181:50780/i | malware_download | online |
| http://113.53.69.133:47548/i | malware_download | online |
| http://125.44.33.3:57068/i | malware_download | online |
| http://59.97.251.59:46282/bin.sh | malware_download | online |
| http://113.205.156.227:58929/i | malware_download | online |
| http://45.153.34.235:8765/bins/dlr.mpsl | malware_download | online |
| https://gitlab.com/brisslands/decode/-/raw/main/XHP3.exe | malware_download | online |
| https://gitlab.com/brisslands/decode/-/raw/main/y0Xc9Og1lghX.exe | malware_download | online |
| https://gitlab.com/brisslands/decode/-/raw/main/S8D70IPCZNAA.exe | malware_download | online |

### MalwareBazaar (recent samples, abuse.ch)
| SHA256 | File type | Signature |
|---|---|---|
| 72f9d45b38670c740f156f1db4d9b50fbf62f343e1af3f48c454be3ebea7b534 | whack_sh | n/a |
| d34ff5a34fd3e4263052ad6834fdd7389024afa35d9d731aac8c04acc0d4a317 | abuse_ch | Mirai |
| 1f7a31315c822ea415d628c73a24bae47c191b1a933e3672bc7d7eec46fdc98b | abuse_ch | Mirai |
| 599f3c673a8c330be34e6bc676fc6a8f8f98c84e43bb4875ee40e6ca29c27da4 | abuse_ch | n/a |
| 0587e8365e2d416b727d7fc274f93566ce17cd9adbf097ea69bd55ac35284620 | abuse_ch | Mirai |
| 18d46c6383ead81b7ba287f642958e6cd8341f3825d3bc498f7fbc868f26ccab | abuse_ch | Mirai |
| 99d6881553218afeef61ea5408c16598d699c958e36f56effc8827638c44d4eb | whack_sh | n/a |
| 89a25311145ada1664428064bc5b4ae16ec3e322b1399f3d4e753de8aba3ea06 | whack_sh | n/a |
| ec25ee7e4e802306ae1c9deda02b252082b10dc5cee4efdf8dc7d8f671e300de | abuse_ch | n/a |
| 4ad7a5f20c04017770ed3ab3d1df906e0c5768b8fa20eb7a7fdd43f9057a0726 | whack_sh | n/a |
| 6976c75310991d14cdb739b1d826d4dabd850cda0794a928c9b23c71bbf0f2a3 | whack_sh | n/a |
| d85508e7e10f702bd83e1baf01ff85820015666cd5da72add0802fbd30ccaff4 | Bitsight | CoinMiner |
| 83da0e8a179cf390198e2576f2c2a0046367e8f5b5bfa02835ba9cdaca50be97 | whack_sh | RustyStealer |
| 603a4b05c524e163c615ae754d3ea4cecac983e2e0226d6835c3a1526ead6e48 | abuse_ch | Mirai |
| 5e0cd322a30013dba5df58e22e1648fa79959056fc5c91daf2182cc517ecdc24 | abuse_ch | Mirai |
| 110d904351efe79beca610456380380c833cbc39289f76eb48247f29ae7e3dea | whack_sh | n/a |
| e1deea1ed7bb74a68f6fefedc1859ee7aeb8f5a0565bd6b749fe06f1f4bf8be8 | whack_sh | n/a |
| b6f944550a36ae0fd6d6e2edc8d23466badbfc2633672bca9675e67c8ccb42cb | whack_sh | n/a |
| a8b8317307adfc657c8554fca1a9c67572bba33bc7a08dbfc6e58d3ba97ab130 | abuse_ch | n/a |
| 4c3b517c1f9cfdf83b2bba8ea5fa0d756d4fe943cbbf42d2404c8328e2f9f6b9 | abuse_ch | n/a |

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
| 77.90.185.20 | 10 |
| 152.32.225.117 | 10 |
| 202.155.18.56 | 10 |
| 45.148.10.141 | 9 |
| 94.154.43.223 | 9 |
| 103.159.2.113 | 9 |
| 130.12.180.32 | 9 |
| 167.94.146.52 | 9 |
| 167.94.146.59 | 9 |
| 196.189.236.67 | 9 |
| 2.57.122.168 | 8 |
| 2.57.122.238 | 8 |
| 3.129.187.38 | 8 |
| 14.17.59.195 | 8 |
| 31.184.195.246 | 8 |
| 35.237.94.18 | 8 |
| 45.148.10.152 | 8 |
| 45.148.10.157 | 8 |
| 45.148.10.240 | 8 |
| 45.172.152.74 | 8 |

### OpenPhish (live phishing URLs)
- http://roblox.com.et/users/7999205213/profile
- http://danaid.httpz.biz.id/
- https://vinted-check.com/238874013
- https://intokken.com/
- https://rbcode.net/v/4cfdcf48ff6172d39bd47d7e28a8c7d0
- http://stone15-nest.pages.dev/
- https://www.roblox.ly/games/17625359962/RIVALS?privateServerLinkCode=92963367821158724662057277604387
- http://www.c5e2eebc14e3af5a3ec7a62e74c65e93.vercel.app/
- https://coppermingle.shop/meet/zoom/Iphone/
- https://coppermingle.shop/meet/zoom/Iphone/invite.php
- https://coppermingle.shop/meet/zoom
- http://my-robux10000.blogspot.com/
- https://www.roblox.com.ml/games/93377007303268/UPDATE-Job-Application-Tower?privateServerLinkCode=384328757637766641742433182819
- https://www.alldomainsept-two.vercel.app/
- https://trustledgeraml.vercel.app/
- http://prime-asset-recovery.com/
- http://super-duper-octo-eureka--tsccoeste.replit.app/
- https://www.roblox.com.bn/users/499206237787/profile
- http://alldomainsept-two.vercel.app/
- http://1najrn1.pages.dev/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=ASKXGp0_nbFzdHoBsG_d6znGlWE063OUXUJ-liVgQNfJJB3wA_mip4wV6In-9Cchxtm7MSHwtubxoQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SSW5RcrdFO7z4ZELZjz0PKrlwuvtAlRfXio8W00qQ8FW3hTMwEYfpMEtbjVflvZkj12v7dCHg&dsh=S-1138847246%3A1792309886707540 |
| N/A | https://flat-bread-04ca.cloudflareaccess.com/cdn-cgi/access/login/vertiv-command-center.pages.dev?kid=617efb6eb0445e77d08421b7c2075c08ed7302463271c62a28d702c82772462a&meta=eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiIsImtpZCI6IjEyY2U5NjlmMDk3YjUyNjliNjllZjA0N2EwMjBiZGI2NGMwMTc5NjMwNzE3MzJhMWJjODg2NjJiNGUxYzJjY2IifQ.eyJ0eXBlIjoibWV0YSIsImF1ZCI6IjYxN2VmYjZlYjA0NDVlNzdkMDg0MjFiN2MyMDc1YzA4ZWQ3MzAyNDYzMjcxYzYyYTI4ZDcwMmM4Mjc3MjQ2MmEiLCJob3N0bmFtZSI6InZlcnRpdi1jb21tYW5kLWNlbnRlci5wYWdlcy5kZXYiLCJyZWRpcmVjdF91cmwiOiIvIiwic2VydmljZV90b2tlbl9zdGF0dXMiOmZhbHNlLCJpc193YXJwIjpmYWxzZSwiaXNfZ2F0ZXdheSI6ZmFsc2UsImV4cCI6MTc5MjMwOTM0MywibmJmIjoxNzkyMzA5MDQzLCJpYXQiOjE3OTIzMDkwNDMsImF1dGhfc3RhdHVzIjoiTk9ORSIsIm10bHNfYXV0aCI6eyJjZXJ0X2lzc3Vlcl9kbiI6IiIsImNlcnRfc2VyaWFsIjoiIiwiY2VydF9pc3N1ZXJfc2tpIjoiIiwiY2VydF9wcmVzZW50ZWQiOmZhbHNlLCJjb21tb25fbmFtZSI6IiIsImF1dGhfc3RhdHVzIjoiTk9ORSJ9LCJyZWFsX2NvdW50cnkiOiJVUyIsImFwcF9zZXNzaW9uX2hhc2giOiJlNTIzNTBjNGU3ZTYzNmIzODQ2ZGIyZTdmOTI1ODg3YTk0MGRjNDZhYjcwMzkzZTYzYTM2ODY5MDQyNGI5MDgzIn0.DxUZeOOTvYLx8_x7iHN0tQj74VVP8cEhnO81m4ZKLy-jPTdA8KzmGiBKWy1V-h_DSfcr6tHABwtZP8WbIXHyN87tLXbNVI0XZjMOgtPQXEiwO-TfaajWn1yThCyOksftVaDRh3fMnCb3kJZqW1OZ96Z8hjFnHPp3tPYi_NK1VW_H-wO3OmrMWS-WeBzXv6IpPJkUVc9fDJ8D6S5iDkmfwii5B1lrJpF3KMg1e90x9iQDYzWeqen8I__D1qnUkS2AUtxvgXmpFQzPS_Q345EO8LDeF4qi9GNp-f5r_EOl57FbJS3Nm5gemgOLEi2E6QpYJqRMZ-Y1hXaotMlfaYhntA&redirect_url=%2F |
| N/A | https://away.vk.ru/away.php?rh=66a79829-5200-48f5-b604-0a200fd052b9 |
| N/A | http://allegro.1290h9ikk4fgj.pics/ |
| N/A | https://away.vk.ru/away.php?rh=204df661-2862-42f8-9e22-f2f62deb0f1e |
| N/A | http://49.51.43.12/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=AWnogHe_pDujLaO-hl3d_3DQFjS6PW6JGM3LRrD13mxmiaQWTJuHz9b6nwmaSIh76M5SMOelnJex7g&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06STDomFW_-7HWdWWTZKkd4M5cTrQxmYSfadvt_O2Hm17PEJi8-BT7vhLz2TkP5_b2-OSzC_LMA&dsh=S-971696013%3A1792306700530179 |
| N/A | http://away.vk.ru/away.php?rh=64d6c50f-a55f-4e93-b4c7-f29748caa049 |
| N/A | https://allegro-lokalnie.oneseekmonsoon.cfd/ |
| N/A | https://id.superhuman.com/signin?oauth_client_type=MEDIATED_WEB&correlation_id=9oAkVmfI1PQ3oUZrCtBKWg&version=v4&client_id=superhumanDocs |
| N/A | https://away.vk.ru/away.php?rh=746f3d97-3c04-4c7a-a695-4d347ff1df15 |
| N/A | https://away.vk.ru/away.php?rh=c6768d98-1016-440f-be49-800523fcdb18 |
| N/A | http://43.156.0.130/v3/signin/identifier?amp;continue=https://accounts.google.com/&amp;followup=https://accounts.google.com&passive=1209600&flowName=GlifWebSignIn&flowEntry=ServiceLogin&dsh=S-1274665134:1792305094956433 |
| N/A | https://away.vk.ru/away.php?rh=4033c2a9-7bfe-4e41-8f77-5ddd38cf7b78 |
| N/A | https://away.vk.ru/away.php?rh=2a028588-04f7-4ecf-a645-9aaab7b31aef |
| N/A | https://b8376mghi5d.jp.larksuite.com/share/base/form/shrjpMwk5KEz3wmsdPQjPPcLjqh?auth_token=U7CK1RF-bcej7fa1-4cd5-4d2d-aa82-22e60ethi0eq-NN5W4 |
| N/A | https://away.vk.ru/away.php?rh=664c4cb5-eca4-484c-9d61-4550c4df4e64 |
| N/A | https://app-cz9x.glide.page/dl/a189fc |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AaSxoQyQEeCdGiNQploah5nAij7vrMqrlVIHby1Q4v_ARx9kttGkmffM4ARVCnkvjXQyGpUqW4kQNA&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SSinG5GpchZox0SpsrMMp_JjUpMz9fOOvR-42kuFjlHPrBAoTTwP6p_m9Nb5whlvoyOfBmL&dsh=S571796493%3A1792304001008367 |
| N/A | https://www.att.com/activearmorapp?_branch_match_id=1640248425591061547&utm_source=AT%26T%20App&_branch_referrer=H4sIAAAAAAAAA8soKSkottLXT0wuySxLTSzKzS%2FSzS%2FKTM%2FM00ssKdFLzs%2FV9wtL8U6KLCzzMUqyrytKTUstKsrMS49PKsovL04tsnXOKMrPTQUAZUf3KkgAAAA%3D |
| N/A | https://away.vk.ru/away.php?rh=5005658b-374c-4adf-b38f-92ea705a80d8 |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| 7ef960d6cfa5bae388a927a5e20f9238bcb22f92 | Vidar C&C |
| 0922f0b5df139ddc07c5f43fea6d84c885ecc833 | Vidar C&C |
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
- 1.178.216.211
- 1.179.232.194
- 1.187.160.37
- 1.20.187.52
- 1.20.230.31
- 1.20.88.78
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.227.228.131
- 1.234.23.83
- 1.235.14.41
- 1.235.183.146
- 1.238.106.229
- 1.24.16.95
- 1.242.33.13

### CINS Army (poorly-rated IPs)
- 1.117.58.215
- 1.12.229.231
- 1.14.149.30
- 1.192.129.106
- 1.215.138.43
- 1.24.16.102
- 1.24.16.104
- 1.24.16.106
- 1.24.16.123
- 1.24.16.133
- 1.24.16.146
- 1.24.16.153
- 1.24.16.163
- 1.24.16.167
- 1.24.16.171
- 1.24.16.180
- 1.24.16.182
- 1.24.16.187
- 1.24.16.188
- 1.24.16.195

## News (last ~36h, across outlets)
### The Hacker News
- [MALFEX npm Package 'imgdecode' Hides Shellcode Loader in Windows Native Addon](https://thehackernews.com/2026/10/malfex-npm-package-imgdecode-hides.html)
- [Hackers Use Compromised ConnectWise Credential to Sign In to 173 Microsoft 365 Tenants](https://thehackernews.com/2026/10/hackers-use-compromised-connectwise.html)

### BleepingComputer
- [Hackers breach Microsoft 365 tenants via ConnectWise supply-chain attack](https://www.bleepingcomputer.com/news/security/hackers-breach-microsoft-365-tenants-via-connectwise-supply-chain-attack/)
- [Drupal patches critical RCE flaws, warns exploits may emerge soon](https://www.bleepingcomputer.com/news/security/drupal-patches-critical-rce-flaws-warns-exploits-may-emerge-soon/)
- [Critical BlockStrap flaw lets hackers run code on Magento servers](https://www.bleepingcomputer.com/news/security/critical-blockstrap-flaw-lets-hackers-run-code-on-magento-servers/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [BeyondTrust Remote Support Zero-Day Continues Trend of Exploited Edge Bugs](https://www.darkreading.com/endpoint-security/beyondtrust-remote-support-exploited-edge-bugs)

### SecurityWeek
- [Israeli Ad Firm Doubled as Candiru’s Zero-Click Spyware Delivery Channel](https://www.securityweek.com/israeli-ad-firm-doubled-as-candirus-zero-click-spyware-delivery-channel/)

### The Record
_No new items / feed unavailable this run._

### Infosecurity Magazine
_No new items / feed unavailable this run._

### CyberScoop
- [Federal agencies recommend cyber controls, independent testing for frontier AI systems](https://cyberscoop.com/federal-ai-agent-sandbox-security-guidance/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
_No new items / feed unavailable this run._

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
_No new items / feed unavailable this run._

## Fetch issues this run
_None — all sources responded._

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal