# Winjit Daily TI Digest — 2026-10-24

_Auto-generated. Window: last ~24h. Fetched at 2026-10-24T07:59:05.711389+00:00Z_

**At a glance:** 2 new KEV · 8 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-114625 | Arista | VeloCloud Orchestrator | Arista VeloCloud Orchestrator SQL Injection Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-110447 | Collabora | Collabora Online – Built-in CODE Server | Collabora Online – Built-in CODE Server OS Command Injection Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-115806 | 9.8 | n/a | The Prime Mover – Backup and Migration plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 2.2.1 via deserialization of untrusted input in the migration se |
| CVE-2026-57845 | 8.8 | n/a | Hugging Face Datasets through 5.1.0 contains an insecure deserialization vulnerability that allows attackers to execute arbitrary Python code by crafting a malicious pickle file loaded through the dep |
| CVE-2026-115726 | 7.8 | n/a | Aider through 0.86.2 contains a command execution vulnerability that allows attackers to run shell commands by committing a malicious .aider.conf.yml that is auto-loaded without a trust prompt. Attack |
| CVE-2026-115810 | 7.7 | n/a | Tandoor Recipes before 2.7.0 contains a server-side request forgery vulnerability in the Pestle importer that allows authenticated low-privileged users to force the server to issue GET requests to arb |
| CVE-2026-115484 | 7.6 | 0.2% | A flaw was found in the iscsiuio component of open-iscsi. The DHCPv4 option parser incorrectly calculates the length of the options data, causing it to read beyond the allocated buffer into adjacent h |
| CVE-2026-115728 | 7.5 | n/a | @hapi/content from 6.0.1 before 6.0.3 contains a regular expression denial of service vulnerability in Content.disposition() caused by an incomplete fix for CVE-2026-35213. Unauthenticated remote atta |
| CVE-2026-115486 | 7.1 | 0.2% | A flaw was found in the iscsiuio component of open-iscsi. The IPv6 Neighbor Discovery handler accesses link-layer address options at a fixed offset without verifying the packet contains them. Addition |
| CVE-2026-115807 | 7.1 | n/a | The User Profile Builder – Beautiful User Registration Forms, User Profiles & User Role Editor plugin for WordPress is vulnerable to Limited Privilege Escalation in all versions up to, and including,  |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-qrph-gf2g-mv7f | CVE-2026-97352 | unknown | The News Kit Addons For Elementor WordPress plugin before 1.4.9 does not perform a capability... |
| GHSA-ghmr-rrgg-273r | CVE-2026-114429 | unknown | The WPVR  WordPress plugin before 9.0.3 does not properly sanitise and escape some of its tour... |
| GHSA-pjph-x42v-fp6x | CVE-2026-113674 | unknown | The GeoDirectory  WordPress plugin before 2.8.194 does not correctly verify ownership of listings... |
| GHSA-47rj-2gqg-xch4 | CVE-2026-113493 | unknown | The GeoDirectory  WordPress plugin before 2.8.194 does not sanitise and escape some of its map... |
| GHSA-q52q-7v6q-wrp3 | CVE-2026-112207 | unknown | The Download Monitor WordPress plugin before 5.3.4 does not properly validate that a clicked link... |
| GHSA-qw4x-6r3w-q94x | CVE-2026-97353 | unknown | The News Kit Addons For Elementor WordPress plugin through 1.4.7 does not perform capability or... |
| GHSA-3838-5p3q-5cgw | CVE-2026-110956 | unknown | The asVereinbase  WordPress plugin before 1.1.8 does not require a valid password or a genuine... |
| GHSA-jmq3-353m-7wg2 | CVE-2026-87835 | unknown | The Front End Users WordPress plugin through 3.2.35 does not restrict which account attributes a... |
| GHSA-jj25-wjr9-4f42 | CVE-2026-113492 | unknown | The GeoDirectory  WordPress plugin before 2.8.194 does not perform status, ownership or password... |
| GHSA-qmfj-rv52-jh27 | CVE-2026-113673 | unknown | The GeoDirectory  WordPress plugin before 2.8.194 does not properly escape administrator-defined... |
| GHSA-jf56-6mwc-cfqj | CVE-2026-113490 | unknown | The GeoDirectory  WordPress plugin before 2.8.194 does not perform any status or ownership check... |
| GHSA-54m2-gc24-q2f7 | CVE-2026-113491 | unknown | The GeoDirectory  WordPress plugin before 2.8.194 does not validate a user-supplied image URL... |
| GHSA-cj9g-3xc7-vgw3 | CVE-2026-113489 | unknown | The GeoDirectory  WordPress plugin before 2.8.194 does not verify that a referenced attachment... |
| GHSA-4w67-w4g6-34xj | CVE-2026-107907 | unknown | The MAS Videos WordPress plugin through 1.3.4 does not perform any capability or ownership check... |
| GHSA-q8c9-qpq5-4xhg | CVE-2026-107887 | unknown | The Advanced Twenty Seventeen WordPress plugin through 1.3.1 does not perform any capability or... |
| GHSA-w5mv-3wm8-fgrx | CVE-2026-105199 | unknown | The Pixel Tag Manager for WooCommerce  WordPress plugin before 2.2.3 does not perform a... |
| GHSA-g589-p4qg-x28q | CVE-2026-115806 | critical | The Prime Mover – Backup and Migration plugin for WordPress is vulnerable to PHP Object Injection... |
| GHSA-4c28-jc56-4ggg | CVE-2026-115807 | high | The User Profile Builder – Beautiful User Registration Forms, User Profiles & User Role Editor... |
| GHSA-r9qr-cj53-q38x | CVE-2026-115929 | high | MongoDB Compass relies on Electron, a third-party runtime that carries its own TLS root... |
| GHSA-h5r5-h782-vqvp | CVE-2026-115931 | critical | Postiz lets a signed-in user ask the backend to run a function on one of their connected channels... |
| GHSA-96vr-mq84-f8xm | CVE-2026-110814 | unknown | Rejected reason: This CVE ID has been rejected or withdrawn by its CVE Numbering Authority. |
| GHSA-gr24-8mgh-vqv4 | CVE-2026-108793 | unknown | Rejected reason: This CVE ID has been rejected or withdrawn by its CVE Numbering Authority. |
| GHSA-8pqg-7g86-mxqf | CVE-2026-115937 | high | The Mollie webhook endpoint accepts two independent, attacker-controlled parameters and never... |
| GHSA-gg4p-9c93-5hfp | CVE-2026-115938 | high | Craft CMS allows any authenticated control panel user to submit an element-search condition whose... |
| GHSA-j6hf-w48h-c9f9 | CVE-2026-115935 | high | The app/process-api-response-headers action accepts fake Craft API response headers from any... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Commonwealth Community Bank | qilin | US | 2026-10-24T03:30:27.396662+00:00 |
| Trinity Custom Homes | Deadlock | US | 2026-10-24T02:53:03.322742+00:00 |
| Family Planning Association of Pakistan | Panzer | PK | 2026-10-24T00:24:57.173779+00:00 |
| Hensel Elektrik | Deadlock | DE | 2026-10-23T21:50:47.029484+00:00 |
| Sanders Law Group | rhysida |  | 2026-10-23T20:18:08.289344+00:00 |
| von Schaewen | qilin | DE | 2026-10-23T20:16:50.993720+00:00 |
| Company #110 | N0n | ES | 2026-10-23T19:52:50.371867+00:00 |
| mickeybody.com | chaos | US | 2026-10-23T18:00:12.687155+00:00 |
| whitearmor.cc | Whitearmor |  | 2026-10-23T17:55:10.161843+00:00 |
| JS Constructor, INC | emperador | US | 2026-10-23T16:52:22.826630+00:00 |
| Labaid Cancer Hospital And Super Speciality Center | qilin | BD | 2026-10-23T16:26:27.946648+00:00 |
| Kale Balata A | qilin | TR | 2026-10-23T16:26:08.593297+00:00 |
| MaxiSeguridad | qilin | AR | 2026-10-23T16:25:48.851771+00:00 |
| zelsior.es | lockbit5 | ES | 2026-10-23T17:16:08.418238+00:00 |
| Aryza | qilin | AR | 2026-10-23T15:26:27.345102+00:00 |
| Aerotop | qilin | CL | 2026-10-23T15:26:07.900411+00:00 |
| Revi Group | qilin | MX | 2026-10-23T15:25:28.443650+00:00 |
| JB Hunt | Whitearmor | US | 2026-10-23T16:39:22.672105+00:00 |
| lidoway.com | lockbit5 | LI | 2026-10-23T17:16:47.609861+00:00 |
| mlh.com.lb | lockbit5 | LB | 2026-10-23T17:17:24.272714+00:00 |

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
| 77.90.185.20 | 11 |
| 80.94.95.115 | 11 |
| 138.226.239.233 | 11 |
| 138.226.239.234 | 11 |
| 2.57.122.238 | 10 |
| 45.148.10.240 | 10 |
| 80.94.95.116 | 10 |
| 160.250.132.238 | 10 |
| 179.43.153.2 | 10 |
| 3.129.187.38 | 9 |
| 14.34.249.175 | 9 |
| 46.151.178.14 | 9 |
| 64.62.197.122 | 9 |
| 66.132.195.101 | 9 |
| 107.150.123.48 | 9 |
| 144.225.6.184 | 9 |
| 167.94.146.55 | 9 |
| 2.57.121.112 | 8 |
| 2.57.122.209 | 8 |
| 16.5.0.160 | 8 |

### OpenPhish (live phishing URLs)
- http://app.forward-box.com/
- https://account.forward-box.com/error.aspx?e=404
- https://account.forward-box.com/login
- http://03.trendndailyinsider.com/?cid=cs60m-2134&t1=9719156&t3=b79b66b3-d579-43b0-9bc9-373268802bcb&t5=68b658c805debd001271bcfe&t6=%7Baff_sub6%7D&t7=%7Baff_sub7%7D&t8=TnDUpTo1000paypal&transaction_id=1024ff9cd082248f2585d8d6bcc983&email=%7Bemail%7D&userFname=%7Bfirst_name%7D&last=%7Blast_name%7D&userAddress=%7Baddress%7D&cityName=%7BcityName%7D&stateName=%7Bstate%7D&stateCode=%7Bstate_code%7D&zipcode=%7Bzip%7D&countryName=%7Bcountry%7D&mobile=%7Bphone%7D&dobdate=%7Bdobdate%7D&dobmonth=%7Bdobmonth%7D&dobyear=%7Bdobyear%7D&gender=%7Bgender%7D&isr=true&sessionid=dc8104bf-e4e4-4c47-8135-1ffd02e48a64&uck=d035839e-ec3d-4b1c-8fdb-fd267fbe1cd1&idr=true&prod=1&domain=03.trendndailyinsider.com&gls=1
- https://vitrineidealmagazine.shop/produto/8835998
- http://roblox.com.et/communities/904439903/JeohanXmisty
- http://zelpar-vornix-a84de5-nyhh-n2406aco.pages.dev/
- http://sp30ct10-melvuni-biz-zalero.pages.dev/
- https://nolvik-quaren-60f8d3-njybn-rg2406xma.pages.dev/
- http://8kmy-2z5ex-lde8x-213rrj-kevm1.pages.dev/
- https://sp26ct-mavko-biz-zemra-kelti.pages.dev/
- https://aup-gq3s-nf9rr-ebcuh-nx9.pages.dev/
- http://sp30ct10-nalreko-biz-murelo.pages.dev/
- http://g72e-kwifta-r5k0-4x8ujc-fs0d.pages.dev/
- http://sp30ct10-korvemi-biz-zunako.pages.dev/
- http://46tef6-322u-szg67p-97guse.pages.dev/
- https://fc4p-mob46-hr4y-8u0-9fk59t.pages.dev/
- http://sp30ct10-norlevo-biz-zumari.pages.dev/
- https://sp30ct10-kavlevo-biz-zunemi.pages.dev/
- https://sp30ct10-kelreko-biz-zunati.pages.dev/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=ASKXGp0_nbFzdHoBsG_d6znGlWE063OUXUJ-liVgQNfJJB3wA_mip4wV6In-9Cchxtm7MSHwtubxoQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SQBo7TkN3SMhflxwTHvbzbAmNvcV3RmPVUxGYylJPDNlIIaN9obW0CTgDS2qRxs47VjzScB1w&dsh=S1294179424%3A1792828472475772 |
| N/A | https://gerardo.desarrollowebalcala.es/ip/index.php?sid=f0ca86b58b34edde32b68557636398c8 |
| N/A | http://allegrolokalnie.massivefab105.cfd/449wrkywg |
| N/A | http://allegrolokalnie.massivefab105.cfd/ |
| N/A | https://xml-v4.pushub.net/click?i=4wBvSsWkxxg_0 |
| N/A | https://away.vk.ru/away.php?rh=12ba8ee3-e8de-4b6e-9ac9-1a1229a96a58 |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=ASKXGp0_nbFzdHoBsG_d6znGlWE063OUXUJ-liVgQNfJJB3wA_mip4wV6In-9Cchxtm7MSHwtubxoQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06STN5r0hdPFUaRrikHQbcmszwG_pz39fIkOmkKzKYkWrdKzl2P71Hik9bwk7t4vUI_L9MOpS9g&dsh=S557456512%3A1792826264696894 |
| N/A | https://away.vk.ru/away.php?rh=bcf7dc21-7793-4aef-b80a-80da2dd467c4 |
| N/A | https://away.vk.ru/away.php?rh=e7120e22-a343-43cf-a005-e254b4031544 |
| N/A | https://ersfilter-my.sharepoint.com/personal/nradonich_ersfilter_com/_layouts/15/doc.aspx?guestaccesstoken=t6T%2FHN1dKbYHlYX%2BeIMbaZufA43rrGZ6%2FaAAewNocDI%3D&docid=1_18168db23429e45f29fdf2e7be120efc4&wdFormId=%7BB9970F62-44C3-4D09-9929-6E1EB652DA57%7D&action=formsubmit&CID=d9592f92-8d6a-4472-a2f7-d37dcc15372e |
| N/A | http://allegro-lokalnie.partnermoss842.cfd/atnahf30dda5yy |
| N/A | http://allegro-lokalnie.agile-107.cfd/ |
| N/A | http://49.51.43.12/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=AWnogHe_pDujLaO-hl3d_3DQFjS6PW6JGM3LRrD13mxmiaQWTJuHz9b6nwmaSIh76M5SMOelnJex7g&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SRSwl9PgDLrIxFJnhl8kg-lv0lf9kGu-AoAOS_q3ibMbGGR9dLNop9PbNSuWk6pnYCIq-cqbA&dsh=S-1975765415%3A1792825337737313 |
| N/A | http://allegro-lokalnie.optimaleasy282.cfd/hi3ippjxc |
| N/A | http://43.156.0.130/v3/signin/identifier?amp;continue=https://accounts.google.com/&amp;followup=https://accounts.google.com&passive=1209600&flowName=GlifWebSignIn&flowEntry=ServiceLogin&dsh=S-1827374779:1792824772862303 |
| N/A | http://allegrolokalnie.vimphoenix131.cfd/pe3484hei7vv6 |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AaSxoQyQ_ZSuXpSvue0UfKrOXnU6mQAuN0RcLmvWGTqSCzhKlOsPyDT7wQQH6ra2Rhdw1PE87iTB&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SSelEFsbnbccBaXz_JP0F4pGEb23Ly8LpDZKFcuyt57XdMmu4T5afPBBqzgdWBMWPnwSfdyKw&dsh=S-1289400197%3A1792824563274712 |
| N/A | http://allegrolokainie.salesblack91194.cfd/24b0czb |
| N/A | https://us06webzoomus2fj2f830440905293.com/2661951713/invite.php |
| N/A | https://away.vk.ru/away.php?rh=51fd0c16-b2f7-4c94-b1b0-c81524e187eb |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| f8ac3547b3ec163234ebcb90d325eec86069a42f | Vidar C&C |
| 3c99c5d67f2afafad06b3da29af5d1ab97bf5273 | PureLogsStealer C&C |
| 4bba6041d3bd00dd1eb5d436f7d17c7e786eb5ee | PureLogsStealer C&C |
| e8e1ee53a4b01fe4d284f3edf82c0dfd5b6c63cf | CobaltStrike C&C |
| d0cbe76e7158ac0762ebaf34f37e8a357cdfb6b2 | OffLoader C&C |
| 3eba611997b2a74274fd3974dad68bd2d64a936d | Vidar C&C |
| 6f89137efd938f732c38a20125c58d0248016909 | Vidar C&C |
| fe097ea5a213100162ccf6811a78483695f0f8a5 | Vidar C&C |
| b5b9054786b6c3877c16c507e4589388e3f2d08c | Vidar C&C |
| 79928c5b3aaa3ea9d05750ba6b2af2aa6cbea154 | PureRAT C&C |
| 7a5cbff9325f0ca3de3f020b3ba02e51390807cf | Malware C&C |
| 7ed29169b508169575d0d26850aca8a93044067c | QuasarRAT C&C |
| 082cdbff4a21322dcf87bbc200976465f072ae6e | QuasarRAT C&C |
| a546ecee7425b15ec2b0b63cd012b897d627cdc9 | ConnectWise C&C |
| 815ef869856dfa28c55e7c5e07f1d0cce6a4e426 | ConnectWise C&C |
| 9eabf92b1ca6728e2a32c3a090b11c177ac686c3 | ConnectWise C&C |
| ad4757ff933072cc46f34e8c2935df4a2835905f | OffLoader C&C |
| be6dd6d95188274b338310b78e2bc1315a90f64f | PureLogsStealer C&C |
| c5dac4c5a4feb2fec8886ae4e28e8c9bb87b19e9 | Vidar C&C |
| e4c69c59c688b6b22688718fd601e7a3bc6e2c8a | OffLoader C&C |

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
- 1.10.248.238
- 1.10.248.240
- 1.117.73.220
- 1.12.48.131
- 1.12.55.42
- 1.12.55.80
- 1.12.70.212
- 1.14.240.247
- 1.14.97.120
- 1.15.106.134
- 1.15.179.199
- 1.15.221.192
- 1.159.54.33
- 1.178.212.25
- 1.183.196.144
- 1.187.174.173
- 1.203.186.47
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74

### CINS Army (poorly-rated IPs)
- 1.12.229.231
- 1.168.172.140
- 1.177.162.4
- 1.215.138.43
- 1.221.65.174
- 1.24.16.165
- 1.24.16.170
- 1.24.16.173
- 1.24.16.174
- 1.24.16.183
- 1.24.16.29
- 1.24.16.4
- 1.24.16.40
- 1.24.16.42
- 1.24.16.46
- 1.28.125.52
- 1.30.80.145
- 1.32.57.245
- 1.36.114.61
- 1.83.125.102

## News (last ~36h, across outlets)
### The Hacker News
- [CISA Flags Two Actively Exploited Critical Flaws in Collabora Online and Arista VeloCloud](https://thehackernews.com/2026/10/cisa-flags-two-actively-exploited.html)
- [BlackX UEFI Bootkit Bypasses Secure Boot on Patched Windows Systems Missing Revocations](https://thehackernews.com/2026/10/blackx-uefi-bootkit-bypasses-secure.html)
- [Ruby Fixes Three Regex Engine Bugs Responsible for Four Critical GitLab RCE Flaws](https://thehackernews.com/2026/10/ruby-fixes-three-regex-engine-bugs.html)
- [Exposed Infrastructure Reveals How Ransomware Affiliates Used AI Agents to Execute Intrusions](https://thehackernews.com/2026/10/exposed-infrastructure-reveals-how.html)
- [Hackers Breach Enterprise Firewalls and VPNs, Exposing Over 70,000 Credentials](https://thehackernews.com/2026/10/hackers-breach-enterprise-firewalls-and.html)
- [PHP Warns of Another Unpatched RCE Risk Two Days After Emergency PHP2Shell Patches](https://thehackernews.com/2026/10/urgent-php-warns-of-another-unpatched.html)
- [Russia-Linked Hackers Used New Mesh Network Backdoor in Destructive Ukraine Attack](https://thehackernews.com/2026/10/russian-linked-hackers-used-new-mesh.html)
- [Critical Flaw in Python’s Popular Pillow Image Library Allows Code Execution via a Crafted Image](https://thehackernews.com/2026/10/critical-flaw-in-pythons-popular-pillow.html)
- [Researchers Demonstrate Node2Shell RCE Exploit on Node.js Build Using Crafted Brotli Data](https://thehackernews.com/2026/10/researchers-demonstrate-node2shell-rce.html)
- [Critical x402 SDK Flaw Could Let Malicious APIs Drain AI Agents’ Token Balances](https://thehackernews.com/2026/10/critical-x402-sdk-flaw-could-let.html)
- [PHP2Shell Exploit Attempts Hit Millions as Attackers Try to Deploy Mirai Malware](https://thehackernews.com/2026/10/php2shell-exploit-attempts-hit-millions.html)

### BleepingComputer
- [Abandoned Popcorn Time app exposed millions of devices to RCE attacks](https://www.bleepingcomputer.com/news/security/abandoned-popcorn-time-app-exposed-millions-of-device-to-rce-attacks/)
- [Microsoft Teams to get AI-powered, context-aware phishing detection](https://www.bleepingcomputer.com/news/microsoft/microsoft-teams-to-get-ai-powered-context-aware-phishing-detection/)
- [Microsoft: Windows Server 2016 reaches end of support in January](https://www.bleepingcomputer.com/news/microsoft/microsoft-windows-server-2016-reaches-end-of-support-in-january/)
- [Quest Diagnostics confirms data breach exposed patient records](https://www.bleepingcomputer.com/news/security/quest-diagnostics-confirms-data-breach-exposed-patient-records/)
- [PHP shares mitigation for new RCE vulnerability with no patch](https://www.bleepingcomputer.com/news/security/php-shares-mitigation-for-new-and-unpatched-rce-vulnerability/)
- [You gave your AI agent access, but who is giving it orders?](https://www.bleepingcomputer.com/news/security/you-gave-your-ai-agent-access-but-who-is-giving-it-orders/)
- [HPE patches eight max severity RCE and auth bypass AOS flaws](https://www.bleepingcomputer.com/news/security/hpe-patches-eight-max-severity-rce-and-auth-bypass-aos-flaws/)
- [Railway warns devs to rotate secrets after potential breach](https://www.bleepingcomputer.com/news/security/railway-warns-devs-to-rotate-secrets-after-potential-breach/)
- [Capcom confirms data breach affecting 11.7 million accounts](https://www.bleepingcomputer.com/news/security/capcom-confirms-data-breach-affecting-117-million-accounts/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [Trust Is Not What It Seems — And Fraudsters Are Counting on It](https://www.darkreading.com/cyber-risk/trust-is-not-what-it-seems-and-fraudsters-are-counting-on-it)
- [Exposed to PHP2Shell? Cyber Experts Weigh in With Advice](https://www.darkreading.com/application-security/exposed-php2shell-cyber-experts-advice)
- [AI Tools Are Generating Massive Attacks for Little Cost](https://www.darkreading.com/cybersecurity-operations/ai-tools-massive-attacks-little-cost)
- [Why Caribbean Threats Cascade Into Global Cyber-Risk](https://www.darkreading.com/cyber-risk/why-caribbean-threats-cascade-global-cyber-risk)
- [Cyber Insurance's New Reality: Underwriting Isn't Enough](https://www.darkreading.com/cyber-risk/cyber-insurances-underwriting-isnt-enough)
- [AI Agents as Insider Threats: Inside Microsoft's Bet on a Unified Security Stack](https://www.darkreading.com/cybersecurity-operations/ai-agents-insider-threats-inside-microsoft-unified-security-stack)
- [State Bank of India Suffers a Customer PII Data Leak](https://www.darkreading.com/cyberattacks-data-breaches/state-bank-india-customer-pii-data-leak)
- [Microsoft Links Storm-0940 to ConnectWise Supply Chain Attack](https://www.darkreading.com/cyberattacks-data-breaches/microsoft-storm-0940-connectwise-supply-chain-attack)
- [What We Missed: Feds Lasso Texas Laptop Farms](https://www.darkreading.com/insider-threats/texas-laptop-farms-north-korean-it-workers)

### SecurityWeek
- [In Other News: Tor Exit Relays Hijacked, Banks Spot Rogue AI Agents, Self-Rebuilding macOS Ransomware](https://www.securityweek.com/in-other-news-tor-exit-relays-hijacked-banks-spot-rogue-ai-agents-self-rebuilding-macos-ransomware/)
- [Mirai Botnet Operators Join PHP2Shell Attacks as ASLR Bypass Exploits Emerge](https://www.securityweek.com/mirai-botnet-operators-join-php2shell-attacks-as-aslr-bypass-exploits-emerge/)
- [China APT Uses AI Pentest Tool Artex in ConnectWise Attacks](https://www.securityweek.com/china-apt-uses-ai-pentest-tool-artex-in-connectwise-attacks/)
- [Attackers Exploit Third Arista VCO Zero-Day in Four Months](https://www.securityweek.com/attackers-exploit-third-velocloud-orchestrator-zero-day-in-four-months/)
- [11 Million Impacted by Capcom Data Breach](https://www.securityweek.com/11-million-impacted-by-capcom-data-breach/)
- [Quest Diagnostics Data Breach Exposed ‘Certain Patient Records’](https://www.securityweek.com/quest-diagnostics-reports-cyber-breach-affecting-certain-patient-records/)
- [LiteLLM Compromised in Fresh Supply Chain Attack](https://www.securityweek.com/litellm-compromised-in-fresh-supply-chain-attack/)
- [Atlassian Patches 75 Flaws in Data Center and Server Products](https://www.securityweek.com/atlassian-patches-75-third-party-flaws-in-data-center-and-server-products/)
- [Iran’s Prince of Persia APT Hosts C&C in US for First Time Since 2016](https://www.securityweek.com/irans-prince-of-persia-apt-hosts-cc-in-us-for-first-time-since-2016/)

### The Record
- [FCC bans two devices with surveillance chips linked to Huawei](https://therecord.media/fcc-bans-devices-huawei-surveillance-chips)
- [UK proposes 14-year prison terms for undersea cable sabotage](https://therecord.media/uk-undersea-cables-sabotage-new-sentencing-guidelines)
- [Quest Diagnostics warns of potential data theft after attack on lab service system](https://therecord.media/quest-diagnostics-network-intrusion)
- [Reports of PHP bug exploitation attempts grow as experts downplay viability of exploits](https://therecord.media/php-php2shell-exploitation-attempts-pocs)
- [Toronto crime tips org freezes operations after details of data breach come to light](https://therecord.media/toronto-crime-tips-org-freezes-ops-after-breach)

### Infosecurity Magazine
- [Gaming Giant Capcom Confirms Data Breach Exposed Users’ Personal Information](https://www.infosecurity-magazine.com/news/capcom-confirms-data-breach/)
- [Widespread Token-Spraying Attacks Target Microsoft 365 Accounts For Email Compromise](https://www.infosecurity-magazine.com/news/tokenspraying-attacks-target/)
- [Attacks on Tech Firms Behind Most Third-Party Data Breach Victims](https://www.infosecurity-magazine.com/news/tech-third-party-breach-victims/)

### CyberScoop
- [Senators say targeted ads are a security risk. Ad groups say the critics are off base.](https://cyberscoop.com/targeted-ads-spyware-government-threat/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
- [Threat Brief: Critical Vulnerabilities in PHP: CVE-2026-109618, CVE-2026-109619 (Updated October 23)](https://unit42.paloaltonetworks.com/cve-2026-109618-cve-2026-109619/)

### Microsoft Security Blog
- [Inside the LiteLLM 1.107.0 supply chain compromise: Credential theft through Python startup hooks](https://www.microsoft.com/en-us/security/blog/2026/10/23/inside-the-litellm-1-107-0-supply-chain-compromise-credential-theft-through-python-startup-hooks/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [(Reliable)&#x3f; php2shell exploitability, (Fri, Oct 23rd)](https://isc.sans.edu/diary/rss/33452)
- [PHP Vulnerability Wrap-Up, (Fri, Oct 23rd)](https://isc.sans.edu/diary/rss/33450)
- [ISC Stormcast For Friday, October 23rd, 2026 https://isc.sans.edu/podcastdetail/10148, (Fri, Oct 23rd)](https://isc.sans.edu/diary/rss/33448)

### Securelist (Kaspersky)
_No new items / feed unavailable this run._

### CrowdStrike Blog
- [Why Organizations Secure AI Agents with Falcon Guardian](https://www.crowdstrike.com/en-us/blog/why-organizations-secure-ai-agents-with-falcon-guardian/)
- [Obstacles to Weaponizing PHP2Shell Likely Constrain Immediate Widespread Exploitation](https://www.crowdstrike.com/en-us/blog/obstacles-to-weaponizing-php2shell-likely-constrain-exploitation/)
- [CrowdStrike Protects Customers from Threats Delivered via PHP2Shell](https://www.crowdstrike.com/en-us/blog/crowdstrike-protects-customers-from-php-rce-zero-days/)
- [CrowdStrike Uncovers New Agentic AI Campaigns](https://www.crowdstrike.com/en-us/blog/crowdstrike-uncovers-new-agentic-ai-campaigns/)
- [CrowdStrike Achieves NCSC CIR Enhanced Level Assurance](https://www.crowdstrike.com/en-us/blog/crowdstrike-achieves-uk-ncsc-cir-enhanced-level-assurance/)
- [U.S. Government Disrupts FAMOUS CHOLLIMA Operation with CrowdStrike Assistance](https://www.crowdstrike.com/en-us/blog/fbi-disrupts-famous-chollima-operation-with-crowdstrike-assistance/)
- [October 2026 Patch Tuesday: 1,413 CVEs Include Three Zero-Days and 75 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-october-2026/)
- [CrowdStrike and Anthropic Give Critical Infrastructure Defenders the AI Advantage](https://www.crowdstrike.com/en-us/blog/crowdstrike-anthropic-critical-infrastructure-defense-program/)
- [Solving the Continuous Authorization Conundrum](https://www.crowdstrike.com/en-us/blog/solving-the-continuous-authorization-conundrum/)
- [Unknown Threat Actor Uses AI-Driven ARTEX to Target South Korean Finance](https://www.crowdstrike.com/en-us/blog/unknown-threat-actor-uses-artex-to-target-south-korean-finance/)

### FortiGuard Threat Signal
- [OT Refrigeration Control Systems Attack](https://fortiguard.fortinet.com/threat-signal-report/6553)
- [Trimble Cityworks Remote Code Execution Attack](https://fortiguard.fortinet.com/threat-signal-report/5997)
- [PHP2Shell Remote Code Execution Vulnerabilities](https://fortiguard.fortinet.com/threat-signal-report/6551)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal