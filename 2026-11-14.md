# Winjit Daily TI Digest — 2026-11-14

_Auto-generated. Window: last ~24h. Fetched at 2026-11-14T09:58:29.370350+00:00Z_

**At a glance:** 2 new KEV · 0 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-114713 | UnrealIRCd | UnrealIRCd | UnrealIRCd Improper Neutralization of Delimiters Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-123039 | Check Point | Multiple Products | Check Point Multiple Products Incorrect Permission Assignment for Critical Resource Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
_No new high/critical CVEs in this window (or NVD rate-limited this run)._

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-326x-6v6x-22wv | CVE-2026-126697 | unknown | The Quick Page/Post Redirect Plugin WordPress plugin before 5.2.4 was distributed with a hidden... |
| GHSA-6g8m-p68x-665h | CVE-2026-129181 | medium | A vulnerability has been found in projectworlds Visitor Management System 1.0. This issue affects... |
| GHSA-9f4m-7955-grcm | CVE-2026-18742 | medium | The Flatsome theme for WordPress is vulnerable to Stored Cross-Site Scripting via 'data-text-sec'... |
| GHSA-qjhw-rmf9-g548 | CVE-2026-124649 | unknown | The Lightbox with PhotoSwipe WordPress plugin before 5.19.0 does not properly sanitise link... |
| GHSA-2mxc-w25w-664h | CVE-2026-126640 | unknown | The WP Ultimate CSV Importer  WordPress plugin before 9.3 does not escape values from imported... |
| GHSA-vf59-qh8h-wqpf | CVE-2026-123046 | unknown | The SEOJuice WordPress plugin before 2.12.0 does not correctly restrict a REST API authentication... |
| GHSA-x76m-c6rr-jrhw | CVE-2026-118182 | unknown | The Duplicate Post WordPress plugin before 1.5.8 does not check that a user duplicating a post is... |
| GHSA-6349-73wc-mj72 | CVE-2026-118183 | unknown | The Duplicate Post WordPress plugin before 1.5.8 does not check whether a user may publish posts... |
| GHSA-92xq-fm7m-c8gr | CVE-2026-116528 | unknown | The Chargely Free Subscriptions For Woocommernce WordPress plugin through 1.0 does not perform... |
| GHSA-q7qf-q8mm-9qhq | CVE-2026-117490 | unknown | The Flatsome WordPress theme before 3.20.13 does not enforce the acting user's publish and post... |
| GHSA-g3hh-4c53-rw8m | CVE-2026-126639 | unknown | The WP Ultimate CSV Importer  WordPress plugin before 9.2, WP Ultimate CSV Importer Pro WordPress... |
| GHSA-6x39-87p4-cf54 | CVE-2026-123122 | unknown | The Checkout Files Upload for WooCommerce WordPress plugin before 2.4.1 does not verify that a... |
| GHSA-jw8h-m67w-2j3v | CVE-2026-117487 | unknown | The Flatsome WordPress theme before 3.20.13 does not perform a capability or nonce check on an... |
| GHSA-qvmw-9jwc-9q89 | CVE-2026-118181 | unknown | The Duplicate Post WordPress plugin before 1.5.8 does not perform a capability check when saving... |
| GHSA-6cgc-29gr-v9hp | CVE-2026-119258 | unknown | The Swipe WordPress plugin through 1.4 does not properly authenticate a login request before... |
| GHSA-phq8-x45p-mjm8 | CVE-2026-111034 | unknown | The Countdown, Coming Soon, Maintenance  WordPress plugin through 3.0.8 does not check that the... |
| GHSA-3rr9-7ppg-8c4r | CVE-2026-111033 | unknown | The Countdown, Coming Soon, Maintenance  WordPress plugin through 3.0.8 does not perform... |
| GHSA-rmjc-x932-v382 | CVE-2026-105984 | unknown | The Email Marketing 4Dem WordPress plugin through 2.0.5 does not perform authorization or... |
| GHSA-358q-57fj-36xj | CVE-2026-105983 | unknown | The Email Marketing 4Dem WordPress plugin through 2.0.5 does not perform authorization or... |
| GHSA-9367-hx9q-rjcg | CVE-2026-124969 | high | The Optimole – Optimize Images | Convert WebP & AVIF | CDN & Lazy Load | Image Optimization... |
| GHSA-4c36-pqmf-xhhf | CVE-2026-126173 | critical | The AutomatorWP Pro plugin for WordPress' webhook addon is vulnerable to authorization bypass in... |
| GHSA-493r-633r-g34j | CVE-2026-9821 | medium | IBM Cyber Fraud 1.0.0 through 1.1.0 could allow an unauthorized user to inject data into log... |
| GHSA-5wmw-rg9f-m66r | CVE-2026-9870 | medium | IBM Cyber Fraud 1.0.0 through 1.1.0 is vulnerable to cross-site scripting. This vulnerability... |
| GHSA-vr8h-pj9q-293w | CVE-2026-129180 | medium | A flaw has been found in projectworlds Visitor Management System 1.0. This vulnerability affects... |
| GHSA-c89q-h7hg-5gxf | CVE-2026-129173 | medium | A security flaw has been discovered in Stirling-Tools Stirling-PDF up to 3.3.0. Affected is the... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| I****** A***** | netrunner | KW | 2026-11-14T01:30:50.924965+00:00 |
| Grundbaulabor Trier GmbH | everest | DE | 2026-11-14T03:32:50.190997+00:00 |
| K&A Industries | interlock | US | 2026-11-13T22:46:01.680491+00:00 |
| Final Notice Before Publication | everest |  | 2026-11-13T22:44:12.215915+00:00 |
| i*t*r***t.com | Curious Worm |  | 2026-11-13T20:53:46.961552+00:00 |
| t**a.com | Curious Worm |  | 2026-11-13T20:53:27.907368+00:00 |
| Frey Properties of Highland LLC | play | US | 2026-11-13T20:29:46.224571+00:00 |
| ARRB Group | play | AU | 2026-11-13T20:29:10.769450+00:00 |
| The Tidewater Inn | Aoqin | US | 2026-11-13T18:21:30.277020+00:00 |
| Advantage Archives | incransom | US | 2026-11-13T20:14:47.003693+00:00 |
| Walgreen Co. | Wallstreet | US | 2026-11-13T19:03:11.758241+00:00 |
| RE/MAX Germany | Panzer | DE | 2026-11-13T21:51:51.251717+00:00 |
| sportsmansguide.com | incransom | US | 2026-11-13T20:14:27.769657+00:00 |
| World Wide Fittings | bravox | US | 2026-11-13T14:21:52.700230+00:00 |
| The CCMC | Dark Project | CA | 2026-11-13T15:55:12.125727+00:00 |
| Koray Topaç Hukuk Bürosu | Doommageddon | TR | 2026-11-13T11:22:24.878217+00:00 |
| Carsem | emperador | MY | 2026-11-13T11:23:06.967557+00:00 |
| Company #216 | N0n | BW | 2026-11-13T03:28:24.431546+00:00 |
| Galorath | akira | US | 2026-11-13T14:19:54.964178+00:00 |
| Replogle Globes | akira | US | 2026-11-13T14:19:35.288814+00:00 |

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
| 45.148.10.151 | 11 |
| 45.148.10.152 | 10 |
| 138.226.239.233 | 10 |
| 138.226.239.234 | 10 |
| 45.148.10.141 | 9 |
| 45.148.10.157 | 9 |
| 125.130.102.172 | 9 |
| 201.86.42.211 | 9 |
| 18.218.118.203 | 8 |
| 35.210.44.49 | 8 |
| 35.210.116.204 | 8 |
| 35.210.176.28 | 8 |
| 64.62.197.107 | 8 |
| 79.3.96.178 | 8 |
| 81.181.129.218 | 8 |
| 92.27.101.99 | 8 |
| 103.159.2.113 | 8 |
| 167.94.146.59 | 8 |
| 179.43.153.2 | 8 |
| 179.43.153.18 | 8 |

### OpenPhish (live phishing URLs)
- http://shopee-sale26.blogspot.com/
- http://www.program-resmi647.blogspot.com/
- https://www.hadiahshopeeday88.blogspot.com/
- https://www.shopee842.blogspot.com/
- http://www.hadiahshopee179.blogspot.com/
- https://amazonprime-network.fr/pages/login.php
- http://safefile-edocu.innovaagencia.com.co/
- https://eup-ravan.net/az/
- http://ptshopee-69.blogspot.com/
- http://undian-shopee-mart.blogspot.com/
- http://program-resmi888.blogspot.com/
- https://www.roblox.com.ss/games/13621938427/untitled-boxing-game?privateServerLinkCode=95388447005431092484134632311458
- http://shopee0927.blogspot.com/
- https://g5.lu/hg32r
- https://www.roblox.rw/users/333100482737/profile
- http://robloxv.com/games/134026357772960/Barber-Simulator?gameSetTypeId=100000003&homePageSessionInfo=5d228721-24bf-4302-a481-c1801e137b45&isAd=false&newGameEnum_analyticsData=0&numberOfLoadedTiles=34&page=homePage&placeId=134026357772960&playContext=homePage&position=1&positionInRow=1&rowOnPage=3&sortPos=2&sortSubId=&universeId=10770932189
- https://podular.site/?msclkid=11e0cc087d6c1d97b686a6ffe5234382
- https://www.etereacouture.it/aa/ubsMoula25/ubs/ubs.ch_login-id_url=9505f60ac1aaef5a5c92a2ec19b09807
- http://www.etereacouture.it/aa/ubsMoula25/ubs/ubs.ch_login-id_url=9505f60ac1aaef5a5c92a2ec19b09807/Select/login.php
- http://shopee1218.blogspot.com/

### PhishStats (recent phishing/malicious URLs, scored)
_No data returned this run._

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| c8e6fc7bb95a5fe2122679cfca61f87c7ce2875a | NativeLoader C&C |
| 0d04a50138c74a1ecfa1a7b4a3afddeb2a4be571 | QuasarRAT C&C |
| d43053e6c4c7f1b6d00e860b690cdf1b964e1afa | WARDENStealer C&C |
| 0038c1179510d131864264eb4a4a6648e8c54425 | Vidar C&C |
| c18c0c3de038ac37fee18f385a8396789ffe7867 | FunStealer C&C |
| 6627379996ae380572b3d2893ff2f2f377def6ec | FunStealer C&C |
| 262c1f81aee686adb3f6fc3a17951096265bf1b0 | FunStealer C&C |
| 9c24fe0ff6b7d2e3cd6fba2446f7ba0e4d18b737 | FunStealer C&C |
| 0799f487e606540102c11948be32f12439eee1ec | FunStealer C&C |
| 9d0751a9eab469ff9a399a086ea2531b3c22dc30 | OffLoader C&C |
| 955d88cd421ad19859f6015a6ba3ea81e07b510c | PureLogsStealer C&C |
| 45972ca5b00612d1f51e51325f7662d60cdd7860 | WARDENStealer C&C |
| adc24b6b9445798ed026d417fe423b72aa290ebc | WARDENStealer C&C |
| 041028a7248ce181b5c083d17d31ef9443364b70 | WARDENStealer C&C |
| 0335d3d009c55ea6f49e57aeb54fbdb84e5def8e | FunStealer C&C |
| d313c92a2c0c535a7b60359f758b0032db60b99b | FunStealer C&C |
| 187d60de02b8184158547240aec75f31b8e93a27 | Vidar C&C |
| e637e68e3a9cdbe38b1c1c3ca411596797a0fd66 | Vidar C&C |
| c197cc60215219ca6d3781953e16ed060be8ed9a | ACRStealer C&C |
| 5961621983c7a3175a43032505457983fd0422f5 | ACRStealer C&C |

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
- 1.10.221.161
- 1.13.79.149
- 1.14.140.218
- 1.162.194.101
- 1.164.158.192
- 1.172.102.101
- 1.179.172.45
- 1.194.211.36
- 1.2.226.61
- 1.20.178.157
- 1.201.146.109
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.22.175.131
- 1.222.42.237
- 1.226.82.243
- 1.234.27.159
- 1.234.53.65

### CINS Army (poorly-rated IPs)
- 1.12.229.231
- 1.15.14.29
- 1.168.185.245
- 1.189.248.116
- 1.192.129.106
- 1.193.56.135
- 1.193.63.143
- 1.193.63.186
- 1.193.63.198
- 1.20.151.114
- 1.204.27.246
- 1.214.29.155
- 1.224.163.125
- 1.24.16.11
- 1.24.16.114
- 1.24.16.115
- 1.24.16.116
- 1.24.16.125
- 1.24.16.129
- 1.24.16.130

## News (last ~36h, across outlets)
### The Hacker News
- [PostgreSQL Patches 52 Flaws, Including 22-Year-Old Bug Enabling Authenticated RCE](https://thehackernews.com/2026/11/postgresql-patches-52-flaws-including.html)
- [New Mior and Skyfall Attacks Let Rogue Cloud Hosts Steal Secrets From AMD SEV-SNP VMs](https://thehackernews.com/2026/11/new-mior-and-skyfall-attacks-let-rogue.html)
- [FBI Says North Korean Hackers Stole Over $400 Million in Crypto Using Deepfake Video Calls](https://thehackernews.com/2026/11/fbi-says-north-korean-hackers-stole.html)
- [Trezor Confirms Hidden Implants in CryptoBilis-Sold Wallets That Can Steal Recovery Phrases](https://thehackernews.com/2026/11/trezor-confirms-hidden-hardware.html)
- [When an AI Agent Goes Wrong, Can You Stop It?](https://thehackernews.com/2026/11/when-ai-agent-goes-wrong-can-you-stop-it.html)
- [SilentAir Hijacks Asian Telecom Networks to Intercept SMS 2FA Codes and Spy on Taiwanese Users](https://thehackernews.com/2026/11/silentair-hijacks-asian-telecom.html)
- [Operation Endgame Takes Down Gootloader, CastleRAT and StealC Servers, Seizes 6.4M Stolen Logins](https://thehackernews.com/2026/11/operation-endgame-takes-down-gootloader.html)
- [Hackers Exploit PHP2Shell Flaws in Check Point Gateways to Deploy TSGA Backdoor and Wipe ESXi Files](https://thehackernews.com/2026/11/hackers-exploit-php2shell-flaws-in.html)
- [Hackers Exploit N-central Flaws to Infect 21 Servers, Including 19 Running Hotfix 2](https://thehackernews.com/2026/11/hackers-exploit-n-central-flaws-to.html)

### BleepingComputer
- [Trezor confirms crypto-stealing implants in three wallets, releases fix](https://www.bleepingcomputer.com/news/cryptocurrency/trezor-confirms-crypto-stealing-implants-in-three-wallets-releases-fix/)
- [German military drone operations disrupted by cyberattack](https://www.bleepingcomputer.com/news/security/german-military-drone-operations-disrupted-by-cyberattack/)
- [Check Point gateways hacked via PHP2Shell to deploy VMware ESXi wiper](https://www.bleepingcomputer.com/news/security/check-point-gateways-hacked-via-php2shell-to-deploy-vmware-esxi-wiper/)
- [How one AI agent exposed five critical enterprise security gaps](https://www.bleepingcomputer.com/news/security/how-one-ai-agent-exposed-five-critical-enterprise-security-gaps/)
- [Microsoft says November security updates cause printing issues](https://www.bleepingcomputer.com/news/microsoft/microsoft-says-november-security-updates-cause-printing-issues/)
- [Check Point warns of zero-day flaw exploited for root access](https://www.bleepingcomputer.com/news/security/check-point-patches-zero-day-that-lets-hackers-get-root-access/)
- [Microsoft confirms Windows activation failures after November updates](https://www.bleepingcomputer.com/news/microsoft/microsoft-confirms-windows-activation-failures-after-november-updates/)
- [Police arrest 354 suspects in dark web cybercrime crackdown](https://www.bleepingcomputer.com/news/security/police-arrest-354-vendors-buyers-in-global-cybercrime-crackdown/)
- [New worm-like 'SCKit' malware targets MSPs in ScreenConnect attacks](https://www.bleepingcomputer.com/news/security/new-worm-like-sckit-malware-targets-msps-in-screenconnect-attacks/)
- [Hackers compromise 4,800 GitHub accounts to steal cloud credentials](https://www.bleepingcomputer.com/news/security/hackers-compromise-4-800-github-accounts-to-steal-cloud-credentials/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [ArcticRAT Cybercrime Gang Profiles Victim Finances With AI](https://www.darkreading.com/mobile-security/arcticrat-cybercrime-gang-profiles-victim-finances-ai)
- [Attackers in Binance Breach Targeted Known Weakness, Missing Controls](https://www.darkreading.com/cybersecurity-operations/attackers-binance-breach-targeted-weakness-missing-controls)
- [Getting Past the Post-Quantum Cryptography Discovery Phase](https://www.darkreading.com/cybersecurity-operations/getting-past-post-quantum-cryptography-discovery)

### SecurityWeek
- [No Signs of Hacking in FAA Ground Stop as FBI Reportedly Probes Software Update](https://www.securityweek.com/no-signs-of-hacking-in-faa-ground-stop-as-fbi-reportedly-probes-software-update/)
- [FAA Ground Stop Issued Due to ‘Extraordinary Circumstances’](https://www.securityweek.com/faa-ground-stop-issued-due-to-extraordinary-circumstances/)
- [In Other News: New CISA Director Nominee, Connected Car Hacking, Baker Tilly Data Breach](https://www.securityweek.com/in-other-news-new-cisa-director-nominee-connected-car-hacking-baker-tilly-data-breach/)
- [Microsoft Struggles to Restore Email and Other Services in a Global Outage](https://www.securityweek.com/microsoft-struggles-to-restore-email-and-other-services-in-a-global-outage/)
- [Apify Confirms Customer Data Accessed in Cyberattack](https://www.securityweek.com/apify-confirms-customer-data-accessed-in-cyberattack/)
- [SilentAir Hackers Intercept Calls, SMS From Inside Mobile Networks](https://www.securityweek.com/silentair-hackers-intercept-calls-sms-from-inside-mobile-networks/)
- [Law Enforcement Disrupts Gootloader, CastleRAT, and StealC Infrastructure](https://www.securityweek.com/law-enforcement-disrupts-gootloader-castlerat-and-stealc-infrastructure/)
- [Citrix Patches 10 Critical NetScaler Vulnerabilities](https://www.securityweek.com/citrix-patches-10-critical-netscaler-vulnerabilities/)
- [OpenAI Unveils Daybreak Red Team, Defense Factory Security Tools](https://www.securityweek.com/openai-unveils-daybreak-red-team-defense-factory-security-tools/)
- [Nightmare Eclipse Drops Windows Zero-Day Exploit ‘SignDrop’](https://www.securityweek.com/nightmare-eclipse-drops-windows-zero-day-exploit-signdrop/)

### The Record
- [FBI flash alert says Artex tool automating cyberattacks at ‘machine speed’](https://therecord.media/artex-ai-tool-fbi-flash-alert)
- [City of Osaka warns of data breach impacting 1 million as Japan reels from dozens of cyber incidents](https://therecord.media/city-of-osaka-japan-email-data-breach)
- [NYC to bar surveillance pricing as momentum for bans grows nationwide](https://therecord.media/nyc-council-passes-bill-ban-surveillance-pricing)
- [University of Texas at Arlington warns personal information stolen during cyberattack](https://therecord.media/university-of-texas-arlington-warns-data-breach)
- [German parliament passes law giving spy agencies hacking, sabotage powers](https://therecord.media/german-parliament-passes-law-giving-spy-agencies-hacking-power)

### Infosecurity Magazine
- [Hackers' Overreliance on AI Can Result in Weaker Cyber-Attacks, Proofpoint Researcher Says](https://www.infosecurity-magazine.com/news/hackers-ai-weaker-cyber-attacks/)
- [Microsoft 365 Outage Set to Ramp up Security Risks to Organizations](https://www.infosecurity-magazine.com/news/microsoft-365-outage-security/)
- [Phishing Rises Three Times Faster in Europe Than Globally, Proofpoint Finds](https://www.infosecurity-magazine.com/news/phishing-rises-faster-europe/)
- [AI Set to Revolutionize Ransomware Following “Stagnant” Few Years](https://www.infosecurity-magazine.com/news/ai-revolutionize-ransomware/)

### CyberScoop
- [Researchers continue to find serious vulnerabilities in internet connected refrigerators](https://cyberscoop.com/copeland-dixell-refrigeration-vulnerabilities/)
- [Industry guidelines for offensive cyber tools unveiled through international Pall Mall Process](https://cyberscoop.com/pall-mall-process-commercial-spyware-guidelines/)
- [US seizes North Korean hacking infrastructure, $1.2 billion in cryptocurrency stolen from Binance](https://cyberscoop.com/us-seizes-north-korea-hacking-infrastructure-binance/)

### Cisco Talos
- [ARTEX and beyond: AI-enabled penetration testing platforms](https://blog.talosintelligence.com/artex-and-beyond/)

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
- [SCKit abuses ScreenConnect to deploy remote access and target technician sessions](https://www.microsoft.com/en-us/security/blog/2026/11/13/sckit-abuses-screenconnect-deploy-remote-access-target-technician-sessions/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [Macfinger ClickFix campaign sends DownTheDRAIN infostealer for macOS, (Fri, Nov 13th)](https://isc.sans.edu/diary/rss/33518)
- [ISC Stormcast For Friday, November 13th, 2026 https://isc.sans.edu/podcastdetail/10178, (Fri, Nov 13th)](https://isc.sans.edu/diary/rss/33516)

### Securelist (Kaspersky)
- [Ransomware at the hypervisor layer: how attackers use ESXi and vCenter features for malicious purposes](https://securelist.com/esxi-ransomware/121959/)

### CrowdStrike Blog
- [Inside Falcon AI Gateway: One Control Point for AI Traffic](https://www.crowdstrike.com/en-us/blog/falcon-ai-gateway-one-control-point-for-ai-traffic/)
- [CrowdStrike Named a Leader in the 2026 IDC MarketScape for Worldwide Augmented Identity Security Solutions](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-idc-marketscape-worldwide-augmented-identity-security-solutions/)
- [November 2026 Patch Tuesday: 1,252 CVEs Include One Zero-Day and 68 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-november-2026/)
- [How Adversaries Are Turning the Vulnerability Ecosystem Against Defenders](https://www.crowdstrike.com/en-us/blog/adversaries-turn-vulnerability-ecosystem-against-defenders/)
- [CrowdStrike Extends the Agentic SOC to Detect and Stop Agent Insider Threats](https://www.crowdstrike.com/en-us/blog/crowdstrike-detects-and-stops-agent-insider-threats/)
- [CrowdStrike Introduces Agentic Adversary Emulation to Counter AI-Enabled Adversaries](https://www.crowdstrike.com/en-us/blog/crowdstrike-agentic-adversary-emulation-counters-ai-enabled-adversaries/)
- [New Falcon Cloud Security Innovations Secure the Cloud AI Runs On](https://www.crowdstrike.com/en-us/blog/falcon-cloud-security-innovations-secure-cloud-ai-runs-on/)
- [CrowdStrike Brings Enterprise Browser Security to the Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-brings-enterprise-browser-security-to-falcon-platform/)
- [CrowdStrike Advances AI Security and Safety from Endpoint to Cloud](https://www.crowdstrike.com/en-us/blog/crowdstrike-advances-ai-security-and-safety-falcon-guardian/)
- [CrowdStrike to Acquire Fiddler to Deliver Falcon Observe for AI Agent Observability](https://www.crowdstrike.com/en-us/blog/crowdstrike-to-acquire-fiddler/)

### FortiGuard Threat Signal
- [Apache HTTP/2 RCE](https://fortiguard.fortinet.com/threat-signal-report/6665)

## Fetch issues this run
- https://services.nvd.nist.gov/rest/json/cves/2.0?pubStartDate=2026-11-13T00:00:00.000&pubEndDate=2026-11-14T09:57:26.000&cvssV3Severity=HIGH -> HTTPSConnectionPool(host='services.nvd.nist.gov', port=443): Read timed out. (read timeout=25)
- https://services.nvd.nist.gov/rest/json/cves/2.0?pubStartDate=2026-11-13T00:00:00.000&pubEndDate=2026-11-14T09:57:26.000&cvssV3Severity=CRITICAL -> 503 Server Error: Service Unavailable for url: https://services.nvd.nist.gov/rest/json/cves/2.0?pubStartDate=2026-11-13T00:00:00.000&pubEndDate=2026-11-14T09:57:26.000&cvssV3Severity=CRITICAL
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/
- https://api.phishstats.info/api/phishing?_sort=-id&_size=30 -> HTTPSConnectionPool(host='api.phishstats.info', port=443): Read timed out. (read timeout=25)

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal