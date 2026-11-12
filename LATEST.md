# Winjit Daily TI Digest — 2026-11-12

_Auto-generated. Window: last ~24h. Fetched at 2026-11-12T10:48:48.466827+00:00Z_

**At a glance:** 0 new KEV · 9 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-110697 | 9.9 | n/a | A flaw was found in Quay where the robot account listing function constructs a SQL LIKE pattern from user-controlled namespace names without escaping wildcard metacharacters. An attacker who creates a |
| CVE-2026-126542 | 9.8 | n/a | WWBN AVideo 6.5 through 29.7.1 contains an authentication bypass vulnerability that allows unauthenticated attackers to log in as any user via Hybridauth social login display names. Attackers can set  |
| CVE-2026-123710 | 9.8 | n/a | A flaw was found in Red Hat Quay. An unauthenticated client can obtain an anonymous registry token with an audience it controls, present that token to the service key rotation endpoint, and install it |
| CVE-2026-126768 | 9.8 | n/a | OpsTree REMS through 1.0.0 contains an authentication bypass vulnerability that allows unauthenticated attackers to obtain valid JWTs by setting the client-controlled is_local_auth field. Attackers ca |
| CVE-2026-126797 | 9.8 | n/a | NextScan 1.1.0 through 1.2.0 contains an authentication bypass vulnerability in ns-admin that allows unauthenticated attackers to forge administrator tokens using a hardcoded JWT signing key. Attacker |
| CVE-2026-126812 | 9.8 | n/a | blueprintUE Self-Hosted Edition before 4.3.7 contains an insecure default configuration in its Docker Compose examples that sets MYSQL_ALLOW_EMPTY_PASSWORD=yes in database.env and publishes MariaDB on |
| CVE-2026-76954 | 9.8 | n/a | An improper neutralization of special elements used in an SQL command vulnerability in the Auth API in Synology DiskStation Manager (DSM) before 7.2.1-69057-13, 7.2.2-72806-10, 7.3.2-86009-5, and 7.4. |
| CVE-2026-126537 | 9.1 | n/a | The Ninja Forms - File Uploads add-on for WordPress is vulnerable to Arbitrary File Deletion (and arbitrary file read via S3/Dropbox/Google Drive exfiltration) in versions up to, and including, 3.3.36 |
| CVE-2026-85632 | 9.1 | n/a | Missing authentication for critical function and Improper validation of integrity check value vulnerability in Sipay Electronic Money and Payment Services Inc. WooCommerce Virtual POS Module allows Au |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-qcx2-v78c-8gq4 | CVE-2026-90908 | critical | A vulnerability in the GenericAdminAuthenticator component of Azul Payara Server and Azul Payara... |
| GHSA-hhm3-8qg5-w88f | CVE-2026-40820 | medium | A high privileged remote attacker can exploit an unauthenticated SQL Injection vulnerability in... |
| GHSA-3pjh-ff5g-h85m | CVE-2026-82292 | low | A NULL pointer dereference vulnerability in the Qt Framework QDomDocument::setContent() XML... |
| GHSA-jg8r-mgg8-r7rx | CVE-2026-125836 | high | Cross-Site Request Forgery (CSRF) vulnerability in Nicu Micle Simple JWT Login simple-jwt-login... |
| GHSA-c92q-w8v5-r4hp | CVE-2026-126642 | medium | An incorrect authorization flaw was found in AWX, the automation controller component of Red Hat... |
| GHSA-44cp-c734-xw76 | CVE-2026-47832 | high | The vulnerability lies in the way application credentials are handled within the BOSH deployment.... |
| GHSA-43xc-9rqh-6r2g | CVE-2026-123133 | unknown | Rejected reason: This CVE ID is a duplicate of CVE-2026-116518 and was never published. Both IDs... |
| GHSA-gv3m-v36g-qfr6 | CVE-2026-110003 | critical | A vulnerability in the administration REST interface of Azul Payara allows a remote,... |
| GHSA-9xwp-mf2p-p42r | CVE-2026-118855 | high | Akaunting 3.3.0 contains a stored cross-site scripting vulnerability through invoice import. An... |
| GHSA-hqwj-c9h5-9mr4 | CVE-2026-8332 | high | A hard-coded root password in Microchip TimePictra platform installation files could allow an... |
| GHSA-2w5p-72rc-qq3c | CVE-2026-126991 | medium | The Wikidata Lookup expansion module (wiki.py) in MISP misp-modules contained a SPARQL injection... |
| GHSA-2hfc-fw5x-vjm9 | CVE-2026-8333 | critical | A stored cross-site scripting vulnerability in Microchip the TimePictra platform could allow an... |
| GHSA-5993-pcpw-x8xp | CVE-2026-8331 | high | An unrestricted upload of files with dangerous type vulnerability in the Microchip TimePictra... |
| GHSA-27h9-745x-3rgf | CVE-2026-87772 | high | Incorrect Authorization vulnerability in TÜBİTAK BİLGEM Software Technologies Research Institute... |
| GHSA-4cwf-239q-xjfq | CVE-2026-12507 | critical | Zohocorp ManageEngine AssetExplorer versions below 7860, ServiceDesk Plus versions below 15290,... |
| GHSA-64xm-x3j2-5g2g | CVE-2026-113408 | low | Path traversal in Git allows writing to arbitrary file via cloning and committing to bad repository |
| GHSA-v53h-q7r3-wr4w | CVE-2026-12591 | critical | Zohocorp ManageEngine M365 Manager Plus versions below 4818 is affected by an authenticated... |
| GHSA-gmxr-g9qg-qjhg | CVE-2026-76792 | unknown | The User Verification by PickPlugins WordPress plugin before 2.0.49 does not rate limit the... |
| GHSA-r3fv-52qm-g995 | CVE-2026-124647 | unknown | The TI WooCommerce Wishlist WordPress plugin before 2.0.7 does not sanitise and escape user input... |
| GHSA-3fmm-mc8g-m4mq | CVE-2026-124652 | unknown | The Mine CloudVod WordPress plugin before 2.6.6 does not verify that an order belongs to the... |
| GHSA-7vhp-9r7r-4h86 | CVE-2026-124648 | unknown | The TI WooCommerce Wishlist WordPress plugin before 2.13.0 does not verify that a visitor who is... |
| GHSA-4wgw-wqj3-325x | CVE-2026-101107 | high | An OS command Injection issue exists in Air Terminal 6 provided by SoftBank Corp. Arbitrary... |
| GHSA-3w5v-7rrg-h2pc | CVE-2026-118597 | high | Akaunting 3.3.0 contains a stored cross-site scripting vulnerability in custom invoice payment... |
| GHSA-xwg6-8rwf-j275 | CVE-2026-124814 | unknown | The Ultimate Addons for Elementor Forms WordPress plugin before 1.0.8 does not properly validate... |
| GHSA-v973-hgc6-wrfw | CVE-2026-123044 | unknown | The ContentPen WordPress plugin before 1.1.1 discloses its REST API key to unauthenticated users,... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Dep | medusalocker |  | 2026-11-11T22:01:37.377000+00:00 |
| Minor League Baseball | play | US | 2026-11-11T20:19:30.872886+00:00 |
| Company #213 | N0n | QA | 2026-11-11T18:00:30.349170+00:00 |
| Company #212 | N0n | ET | 2026-11-11T17:59:43.019766+00:00 |
| K**** T**** H**** B**** | Doommageddon |  | 2026-11-11T17:52:05.208975+00:00 |
| sacheminc.com | Curious Worm | CA | 2026-11-11T17:13:08.721193+00:00 |
| sbhny.org | Curious Worm | US | 2026-11-11T17:12:34.212474+00:00 |
| shannonhealth.com | Curious Worm | IE | 2026-11-11T17:11:42.163910+00:00 |
| baronandbudd.com | Curious Worm | GB | 2026-11-11T17:10:59.162735+00:00 |
| raleighortho.com | Curious Worm | US | 2026-11-11T17:10:25.738432+00:00 |
| ki*****o.com | everstake |  | 2026-11-11T17:10:25.941163+00:00 |
| lifelinescreening.com | Curious Worm | US | 2026-11-11T17:09:47.097261+00:00 |
| safcodental.com | Curious Worm | SA | 2026-11-11T17:07:16.258455+00:00 |
| marquiscompanies.com | Curious Worm | US | 2026-11-11T17:06:55.020222+00:00 |
| atlashp.com | Curious Worm |  | 2026-11-11T17:06:34.206298+00:00 |
| Tyfone | Aoqin | US | 2026-11-11T09:51:11.638383+00:00 |
| Garden Valley School Division | interlock | CA | 2026-11-11T00:43:34.761065+00:00 |
| Leware Construction Company ofFlorida | akira | US | 2026-11-11T13:42:18.353064+00:00 |
| R3 Composites | akira |  | 2026-11-11T13:41:57.674234+00:00 |
| Quality Air | akira |  | 2026-11-11T13:41:37.862954+00:00 |

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
| 45.148.10.141 | 11 |
| 45.148.10.157 | 11 |
| 138.226.239.234 | 11 |
| 45.148.10.151 | 10 |
| 138.226.239.233 | 10 |
| 3.129.187.38 | 9 |
| 18.218.118.203 | 9 |
| 35.210.160.81 | 9 |
| 45.148.10.152 | 9 |
| 64.62.197.77 | 9 |
| 66.132.186.200 | 9 |
| 66.132.195.75 | 9 |
| 103.159.2.113 | 9 |
| 167.94.146.56 | 9 |
| 185.87.121.1 | 9 |
| 2.57.121.25 | 8 |
| 2.57.121.112 | 8 |
| 3.130.168.2 | 8 |
| 18.116.101.220 | 8 |
| 35.210.19.110 | 8 |

### OpenPhish (live phishing URLs)
- http://6oktsarv.kcppg.com/
- https://www.robiox.com.py/users/198471345763/profile
- http://hadiah-shopee329.blogspot.com/
- https://www.ehay-item.pentagrafic.mx/
- https://getalphacore.com/pd/paga/IN2651/
- http://gtalphacore.shop/2651
- http://zavqelo-mpt-fenqari-r5x9pe84.pages.dev/
- https://www.voir-document.vercel.app/
- https://en-start-faqs.pages.dev/robots.txt
- https://loginservice.cloud/E.ONEXzd-JrR7_NQ?/servus-credit-union%E2%81%84threads%E2%81%84879239875%E2%81%84trk-event-com-thread-click%E2%81%84allow-app-redirect
- https://metamask-docs-ctqr7yuof-consensys-ddffed67.vercel.app/embedded-wallets/sdk/flutter
- https://metamask-docs-ctqr7yuof-consensys-ddffed67.vercel.app/embedded-wallets/
- https://aptim.us/lookslike/nd/webmail-jp/#danik1@963d793d9758331dd9e30cca0f8c571e9704.com
- https://vb.mightybaobab.com/fonts/wservices/sc.php?lid=danik1@963d793d9758331dd9e30cca0f8c571e9704.com
- https://www.24236936365.com/
- https://overview-start-trezorr.pages.dev/robots.txt
- https://start-io-en-trezr.pages.dev/robots.txt
- https://getalphacore.com/pd/paga/IN2653/
- http://gtalphacore.shop/2653
- http://2wimhy09.mwyry.com/

### PhishStats (recent phishing/malicious URLs, scored)
_No data returned this run._

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| c197cc60215219ca6d3781953e16ed060be8ed9a | ACRStealer C&C |
| 5961621983c7a3175a43032505457983fd0422f5 | ACRStealer C&C |
| 206699fd6ec97741dcdfe7d8ff2a066f1788a3f7 | ConnectWise C&C |
| 0f01c1b3f102f81f42772aed3893c2c9e0f48fb7 | ACRStealer C&C |
| 8850bca458b507876f7d39297d44bdb1634ba915 | PureLogsStealer C&C |
| 2d5618f557611ad38b3addcb60b3e7424006b79b | Vidar C&C |
| 7cf49de496a65869f8cf0c0b6a12c6fa5ab1c70f | Vidar C&C |
| d81ba5307163e9ab6460623840036fff7d856104 | Vidar C&C |
| 3c9cf61da071dea44abcb047a6290104588fb791 | Vidar C&C |
| dc26a2f39a41b1f6341aea0fb4cdbe57ff564917 | Vidar C&C |
| 2c4f45913d2f0f0869145d6eb5399d6e00a303ea | PureLogsStealer C&C |
| b60be83fabb664ff9b542c3f0f9d7d514b9c1fa3 | RatonRAT C&C |
| 25235b80d03ab6eaf4e2b0eeed5663d302ec38b1 | Vidar C&C |
| bfa41aa99aa3dcd67f178a96fd369e74277234cf | Vidar C&C |
| f04b05a8f3f341ac61c3244469516cc850edde00 | PavinLoader C&C |
| 0796ad594b2148e4fe97407cc4703c2e78ffa752 | ACRStealer C&C |
| baa0e54314fcd527db444d8782d41003a661f84d | Havoc C&C |
| 9d191436a0dcb9dd826614de108db06cfc158b57 | PureRAT C&C |
| 78fef26abba5424bfa791ced6cd78f0f87d34c1e | PureLogsStealer C&C |
| 19a8b5f296bc373c894efccb1afb9ef601b495c6 | Malware C&C |

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
- 1.14.140.218
- 1.175.131.108
- 1.180.246.242
- 1.183.196.195
- 1.2.164.171
- 1.2.252.192
- 1.203.149.250
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.226.82.243
- 1.234.21.73
- 1.234.27.159
- 1.234.53.65
- 1.235.183.146
- 1.238.106.229
- 1.247.245.61
- 1.250.67.190

### CINS Army (poorly-rated IPs)
- 1.12.229.231
- 1.169.41.52
- 1.193.56.135
- 1.193.63.131
- 1.193.63.143
- 1.193.63.198
- 1.224.163.125
- 1.24.16.104
- 1.24.16.105
- 1.24.16.112
- 1.24.16.118
- 1.24.16.121
- 1.24.16.128
- 1.24.16.13
- 1.24.16.131
- 1.24.16.140
- 1.24.16.147
- 1.24.16.154
- 1.24.16.163
- 1.24.16.169

## News (last ~36h, across outlets)
### The Hacker News
- [Critical Pre-Auth MongoDB Flaw (CVE-2026-118383) Can Crash Lagging Servers on Failover](https://thehackernews.com/2026/11/critical-pre-auth-mongodb-flaw-cve-2026.html)
- [Node.js Fixes 16 Flaws, Including HTTP/2 Bugs That Crash Servers and Leak Other Connections' Data](https://thehackernews.com/2026/11/nodejs-fixes-16-flaws-including-http2.html)
- [Attacker Used 4,837 Hijacked GitHub Accounts to Run a CI Secret Stealer in 1,806+ Repositories](https://thehackernews.com/2026/11/4837-hijacked-github-accounts-ran-ci.html)
- [Critical Apache HTTP/2 Flaw Could Let Unauthenticated Attackers Execute Code Remotely](https://thehackernews.com/2026/11/critical-apache-http2-flaw-could-let.html)
- [ScreenConnect Attacks Target at Least 288 Endpoints Across 48 Organizations With Rogue Clients](https://thehackernews.com/2026/11/screenconnect-attacks-target-at-least.html)
- [Critical Zoom Workplace Flaw Could Allow Unauthenticated Remote Privilege Escalation](https://thehackernews.com/2026/11/critical-zoom-workplace-flaw-could.html)
- [AntiFox AI Pentesting Platform Linked to Attacks That Accessed AWS Production Secrets](https://thehackernews.com/2026/11/antifox-ai-pentesting-platform-linked.html)
- [Hackers Target Qlik Sense Servers With Reverse Shells, Stage ActiveMQ and Veeam Exploits](https://thehackernews.com/2026/11/hackers-target-qlik-sense-servers-with.html)
- [Over 35,000 Grok-Built Apps Exposed Online, Some Leaking Confidential Data and Passwords](https://thehackernews.com/2026/11/over-35000-grok-built-apps-exposed.html)
- [We Built An Agent That Broke All of Our Security Rules. Here's What We Learned.](https://thehackernews.com/2026/11/we-built-agent-that-broke-all-of-our.html)
- [eMudhra Revokes 8 More CAs It Previously Declared Unaffected by Key Compromise](https://thehackernews.com/2026/11/emudhra-revokes-8-more-cas-it.html)
- [Microsoft Patches 1,259 Flaws, Including Exploited Outlook Bug That May Expose NTLMv2 Hashes](https://thehackernews.com/2026/11/microsoft-patches-1259-flaws-including.html)
- [Railway Says Stolen Customer AI Keys Led to $740,000 in Estimated Unauthorized Usage Charges](https://thehackernews.com/2026/11/railway-says-stolen-customer-ai-keys.html)
- [Microsoft Researchers Show AI Agents Can Be Backdoored by Editing Fewer Than 10 Neurons](https://thehackernews.com/2026/11/microsoft-researchers-show-ai-agents.html)
- [Cisco BroadWorks and Openwave Flaws Actively Exploited Despite Available Patches](https://thehackernews.com/2026/11/cisco-broadworks-and-openwave-flaws.html)

### BleepingComputer
- [Microsoft confirms Windows security updates installation issues](https://www.bleepingcomputer.com/news/microsoft/microsoft-confirms-kb5132061-installation-issues-0x80070306-0x800f0989-0x800f0993-errors/)
- [Hackers plant GSocket on Linux servers for persistent access](https://www.bleepingcomputer.com/news/security/hackers-plant-gsocket-on-linux-servers-for-persistent-access/)
- [Baker Tilly notifies clients of data breach at third-party provider](https://www.bleepingcomputer.com/news/security/baker-tilly-notifies-clients-of-data-breach-at-third-party-provider/)
- [Active ScreenConnect attacks breach MSPs, impact dozens of organizations](https://www.bleepingcomputer.com/news/security/active-screenconnect-attacks-breach-msps-impact-dozens-of-organizations/)
- [eMudhra revokes 8 more CA certificates after private key mishap](https://www.bleepingcomputer.com/news/security/emudhra-revokes-8-more-ca-certificates-after-private-key-mishap/)
- [Notion says Fireworks breach exposed customer AI chat transcripts](https://www.bleepingcomputer.com/news/security/notion-says-fireworks-breach-exposed-customer-ai-chat-transcripts/)
- [Maersk confirms data breach as WhiteArmor ransomware demands $5 million](https://www.bleepingcomputer.com/news/security/maersk-confirms-data-breach-as-whitearmor-ransomware-demands-5-million/)
- [Hackers use AntiFox AI agents in AWS credential-theft attacks](https://www.bleepingcomputer.com/news/security/hackers-use-antifox-ai-agents-in-aws-credential-theft-attacks/)
- [eBPF Rootkits: Why Underground Actors Are Taking Notice](https://www.bleepingcomputer.com/news/security/ebpf-rootkits-why-underground-actors-are-taking-notice/)
- [N-able releases security hotfixes for zero-day vulnerabilities](https://www.bleepingcomputer.com/news/security/n-able-releases-security-hotfixes-for-zero-day-vulnerabilities/)
- [Microsoft fixes audio issues caused by September security updates](https://www.bleepingcomputer.com/news/microsoft/microsoft-fixes-usb-audio-issues-caused-by-september-security-updates/)
- [CISA flags Cisco BroadWorks flaw as actively exploited in attacks](https://www.bleepingcomputer.com/news/security/cisa-flags-cisco-broadworks-flaw-as-actively-exploited-in-attacks/)
- [Microsoft fixes Exchange sign-ins broken by Windows Server updates](https://www.bleepingcomputer.com/news/microsoft/microsoft-fixes-exchange-sign-ins-broken-by-october-windows-server-updates/)

### Krebs on Security
- [Who Runs the Ransomware Group Qilin?](https://krebsonsecurity.com/2026/11/who-runs-the-ransomware-group-qilin/)

### Dark Reading
- [Chinese AI Project Scouts Spies in Taiwan Chip Industry](https://www.darkreading.com/threat-intelligence/chinese-ai-project-scouts-spies-taiwan-chip-industry)
- [Japan Pushes Emergency Funding for Cybersecurity as AI-Assisted Breaches Rise](https://www.darkreading.com/cybersecurity-operations/japan-emergency-funding-cybersecurity-ai-assisted-breaches)
- [Attackers Say 'Hello' to a Different Scale of Cloud Attack](https://www.darkreading.com/cloud-security/attackers-hello-scale-cloud-attack)
- [AI Raises the Stakes for Cyber Resilience](https://www.darkreading.com/cyber-risk/ai-raises-stakes-cyber-resilience)
- [N-able Takes N-central Platform Offline After Discovery of 33 Flaws](https://www.darkreading.com/endpoint-security/n-able-n-central-offline-33-flaws)

### SecurityWeek
- [Hackers Deploy Malware in Fresh ScreenConnect Campaign](https://www.securityweek.com/hackers-deploy-malware-in-fresh-screenconnect-campaign/)
- [Hackers Target N-central Zero-Days as N-able Rushes Patches](https://www.securityweek.com/hackers-target-n-central-zero-days-as-n-able-rushes-patches/)
- [Critical Red Hat Quay Vulnerability Could Expose Private Container Images](https://www.securityweek.com/critical-red-hat-quay-vulnerability-could-expose-private-container-images/)
- [Maersk Confirms Data Theft Amid $5 Million Extortion Attempt](https://www.securityweek.com/maersk-confirms-data-theft-amid-5-million-extortion-attempt/)
- [Today: CISO Forum Virtual Summit 2026 Day 2 – Join Cybersecurity Leaders Online](https://www.securityweek.com/today-ciso-forum-virtual-summit-2026-join-global-cybersecurity-leaders/)
- [Critical Xen Orchestra Flaws Exploited in Attacks](https://www.securityweek.com/critical-xen-orchestra-flaws-exploited-in-attacks/)
- [Asus, Zoom Release Security Patches](https://www.securityweek.com/asus-zoom-release-security-patches/)
- [Citrix, Ivanti Patch Critical and High-Severity Vulnerabilities](https://www.securityweek.com/citrix-ivanti-patch-critical-and-high-severity-vulnerabilities/)
- [Finite State Raises $27 Million to Secure Software and Firmware in Connected Devices](https://www.securityweek.com/finite-state-raises-27-million-to-secure-software-and-firmware-in-connected-devices/)
- [Fortinet Patches Nearly 100 Vulnerabilities](https://www.securityweek.com/fortinet-patches-nearly-100-vulnerabilities/)

### The Record
- [Iran-backed network directed London attacks over FaceTime, US prosecutors say](https://therecord.media/iran-backed-network-directed-london-attacks-over-facetime)
- [Poland shuts down government services platform ePUAP following cyberattack](https://therecord.media/poland-shuts-down-government-services-platform-cyberattack)
- [Britain, France set out first guidelines for commercial hacking firms](https://therecord.media/britain-france-set-out-guidelines-for-commercial-hacking-firms)

### Infosecurity Magazine
- [Security Teams Must Shift from Patching to Mitigation in the AI Era](https://www.infosecurity-magazine.com/news/shift-patching-mitigation-ai-era/)
- [NCSC Launches Cyber Adversary Testing to Boost Resilience](https://www.infosecurity-magazine.com/news/ncsc-cyber-adversary-testing-boost/)
- [Maersk Reveals Data Breach as Extortion Group Demands $5m](https://www.infosecurity-magazine.com/news/maersk-data-breach-extortion-group/)
- [N-able Rushes Out N-central Fixes After 33 Zero-Days Go Public](https://www.infosecurity-magazine.com/news/n-able-n-central-able2shell-0day/)
- [Anthropic's Glasswing Finds Many Vulnerabilities Yet Delivers Few Fixes, Researcher Says](https://www.infosecurity-magazine.com/news/anthropic-glasswing/)
- [Suspected Chinese Malware Supplier Tied to Three Hacking Campaigns](https://www.infosecurity-magazine.com/news/chinese-malware-tied-three-hacking/)
- [OT Incidents Hit a Third of Industrial Organizations, SANS Finds](https://www.infosecurity-magazine.com/news/ot-incidents-third-industrial/)
- [Microsoft Fixes 1235 Flaws in Another Record Patch Tuesday](https://www.infosecurity-magazine.com/news/microsoft-fixes-1235-flaws-record/)

### CyberScoop
_No new items / feed unavailable this run._

### Cisco Talos
- [Microsoft Patch Tuesday for November 2026 — Snort rules and prominent vulnerabilities](https://blog.talosintelligence.com/microsoft-patch-tuesday-for-november-2026/)

### Unit 42 (Palo Alto)
- [ARTEX and AI-Powered Red Teaming Tools: What Defenders Need to Know](https://unit42.paloaltonetworks.com/artex-and-ai-powered-red-teaming-tools/)
- [The XG Files: Falcon C2 Flying Under The (Browser) Radar](https://unit42.paloaltonetworks.com/falcon-c2-browser-compromise/)

### Microsoft Security Blog
- [The global socket: how threat actors are weaponizing GSocket for stealthy C2](https://www.microsoft.com/en-us/security/blog/2026/11/11/global-socket-how-threat-actors-weaponizing-gsocket-stealthy-c2/)
- [Lessons from 59 Linux Kernel Bug Reports](https://www.microsoft.com/en-us/security/blog/2026/11/11/lessons-from-59-linux-kernel-bug-reports/)
- [Detecting sleeper agents hiding in AI model neurons](https://www.microsoft.com/en-us/security/blog/2026/11/10/detecting-sleeper-agents-hiding-in-ai-model-neurons/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Thursday, November 12th, 2026 https://isc.sans.edu/podcastdetail/10176, (Thu, Nov 12th)](https://isc.sans.edu/diary/rss/33512)
- [Microsoft Patch Tuesday November 2026, (Tue, Nov 10th)](https://isc.sans.edu/diary/rss/33508)
- [ISC Stormcast For Wednesday, November 11th, 2026 https://isc.sans.edu/podcastdetail/10174, (Wed, Nov 11th)](https://isc.sans.edu/diary/rss/33510)

### Securelist (Kaspersky)
- [Transcending the trust boundaries: how a cloud pentest works](https://securelist.com/how-a-cloud-pentest-works/121921/)
- [Citrus Ransomware: VLESS for traffic, Sn00py for encryption, and LLMs lending a hand](https://securelist.com/citrus-ransomware/121879/)

### CrowdStrike Blog
- [November 2026 Patch Tuesday: 1,252 CVEs Include One Zero-Day and 68 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-november-2026/)
- [How Adversaries Are Turning the Vulnerability Ecosystem Against Defenders](https://www.crowdstrike.com/en-us/blog/adversaries-turn-vulnerability-ecosystem-against-defenders/)
- [CrowdStrike Brings Enterprise Browser Security to the Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-brings-enterprise-browser-security-to-falcon-platform/)
- [CrowdStrike Extends the Agentic SOC to Detect and Stop Agent Insider Threats](https://www.crowdstrike.com/en-us/blog/crowdstrike-detects-and-stops-agent-insider-threats/)
- [CrowdStrike Introduces Agentic Adversary Emulation to Counter AI-Enabled Adversaries](https://www.crowdstrike.com/en-us/blog/crowdstrike-agentic-adversary-emulation-counters-ai-enabled-adversaries/)
- [New Falcon Cloud Security Innovations Secure the Cloud AI Runs On](https://www.crowdstrike.com/en-us/blog/falcon-cloud-security-innovations-secure-cloud-ai-runs-on/)
- [CrowdStrike Advances AI Security and Safety from Endpoint to Cloud](https://www.crowdstrike.com/en-us/blog/crowdstrike-advances-ai-security-and-safety-falcon-guardian/)
- [CrowdStrike to Acquire Fiddler to Deliver Falcon Observe for AI Agent Observability](https://www.crowdstrike.com/en-us/blog/crowdstrike-to-acquire-fiddler/)
- [Introducing AI Kill Switch: Taking Control When AI Agents Go Rogue](https://www.crowdstrike.com/en-us/blog/crowdstrike-introduces-ai-kill-switch/)
- [CrowdStrike Secures AI Agents Inside Claude Cowork](https://www.crowdstrike.com/en-us/blog/crowdstrike-secures-ai-agents-inside-claude-cowork/)

### FortiGuard Threat Signal
- [WordPress Core Time-of-check Time-of-use (TOCTOU) Race Condition Vulnerability](https://fortiguard.fortinet.com/threat-signal-report/6565)
- [OT Refrigeration Control Systems Attack](https://fortiguard.fortinet.com/threat-signal-report/6553)

## Fetch issues this run
- https://services.nvd.nist.gov/rest/json/cves/2.0?pubStartDate=2026-11-11T00:00:00.000&pubEndDate=2026-11-12T10:47:43.000&cvssV3Severity=HIGH -> HTTPSConnectionPool(host='services.nvd.nist.gov', port=443): Read timed out. (read timeout=25)
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/
- https://api.phishstats.info/api/phishing?_sort=-id&_size=30 -> HTTPSConnectionPool(host='api.phishstats.info', port=443): Read timed out. (read timeout=25)

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal