# Winjit Daily TI Digest — 2026-11-21

_Auto-generated. Window: last ~24h. Fetched at 2026-11-21T10:48:02.079633+00:00Z_

**At a glance:** 4 new KEV · 38 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-129448 | Apache | Roller | Apache Roller Deserialization of Untrusted Data Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-123890 | Broadcom | VMware vCenter | VMWare vCenter Authentication Bypass Using an Alternate Path or Channel Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines |
| CVE-2025-42884 | SAP | NetWeaver | SAP NetWeaver Improper Neutralization of Special Elements in Data Query Logic Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-76466 | Cisco | Expressway Series | Cisco Expressway Series Use of Hard-coded Credentials Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-133680 | 9.9 | n/a | A vulnerability was found in D-Link DCS-935L 1.10.01. This affects the function loginRouter of the file web/cgi-bin/localrecording/setconf.cgi of the component Local Recording CGI. Performing a manipu |
| CVE-2026-120539 | 9.8 | n/a | The Restrictions for BuddyPress plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 1.5.4 This is due to the plugin splicing the attacker-controlled reque |
| CVE-2026-133500 | 9.1 | 3.7% | A vulnerability was identified in Gladys Assistant up to 4.71.0. This affects an unknown function of the file gateway.downloadBackup.js of the component Backup Restore Endpoint. The manipulation of th |
| CVE-2026-19793 | 8.8 | n/a | The WP Import Export Lite plugin for WordPress is vulnerable to Limited Code Injection in all versions up to, and including, 3.9.32 via the 'comment' parameter. This is due to a two-stage shortcode ch |
| CVE-2026-129220 | 8.8 | n/a | The Everest Forms – Contact Form, Payment Form, Quiz, Survey & Custom Form Builder with AI plugin for WordPress is vulnerable to Missing Authorization in all versions up to, and including, 3.6.4 This  |
| CVE-2026-133528 | 8.6 | 0.1% | BeamNG.drive before 0.40.6 contains an out-of-bounds write vulnerability because JIT-compiled LuaJIT traces omit FFI array bounds checks, letting untrusted Lua escape the sandbox. Attackers supplying  |
| CVE-2026-133874 | 8.1 | n/a | Iceburg CRM through 5.0.0 contains an incorrect authorization vulnerability in Module::saveRecord() that allows authenticated users to write to unauthorized modules by prefixing request body keys with |
| CVE-2026-123086 | 8.1 | n/a | The PublishPress Revisions: Duplicate Posts, Submit, Approve and Schedule Content Changes plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 4.3.4 This is |
| CVE-2026-118049 | 8.1 | n/a | The Tutor LMS – eLearning and online course solution plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 4.2.0 This is due to the plugin not properly verif |
| CVE-2026-133708 | 7.8 | n/a | diffpy.structure before 3.5.1 contains a code execution vulnerability that allows attackers to run Python code by supplying crafted CIF symmetry operations passed to eval() in get_symop(). Attackers c |
| CVE-2026-134172 | 7.8 | n/a | audio-separator before 0.47.2 contains an insecure deserialization vulnerability that allows attackers to execute code by supplying malicious Demucs .th model files loaded via torch.load with weights_ |
| CVE-2026-134164 | 7.5 | n/a | probe-image-size before 7.5.0 contains an algorithmic-complexity denial of service vulnerability in lib/exif_utils.js that allows remote unauthenticated attackers to exhaust CPU by supplying self-refe |
| CVE-2026-134167 | 7.5 | n/a | devpi-web before 5.2.0 contains an unauthenticated path traversal vulnerability in the +doc documentation route because docs_file_exists and docs_file_path in doczip.py never confine relpath to the do |
| CVE-2026-134169 | 7.5 | n/a | Qwik City before 1.20.3 (@builder.io/qwik-city) and @qwik.dev/router before 2.0.0-rc.4 contain an improperly controlled object modification vulnerability in formToObj that allows unauthenticated attac |
| CVE-2026-119114 | 7.4 | n/a | The WP Fastest Cache – WordPress Cache Plugin plugin for WordPress is vulnerable to arbitrary directory deletion due to insufficient file path validation in the singleDeleteCache function in all versi |
| CVE-2026-133415 | 7.3 | 0.3% | A vulnerability has been found in sumiie24 School-Management-System up to d946d649c7c95e101fc5679ecd91999533bb10d7. The affected element is an unknown function of the file parent_Registration.php. Suc |
| CVE-2026-133578 | 7.3 | n/a | A vulnerability was detected in itsourcecode Banking Management System 1.0. This impacts an unknown function of the file manage_donation.php of the component Donor Management. The manipulation of the  |
| CVE-2026-133835 | 7.3 | n/a | A flaw has been found in hankcs HanLP up to 2.1.6. Impacted is the function uncompress of the file hanlp/utils/io_util.py of the component TAR Archive Extraction Handler. This manipulation causes path |
| CVE-2026-107713 | 7.2 | n/a | The Flutterwave Payments plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'form_id' parameter in all versions up to, and including, 1.0.7 due to insufficient input sanitizatio |
| CVE-2026-116619 | 7.2 | n/a | The MetForm – Contact Form, Survey, Quiz, Conditional Forms, Form Templates & Custom Form Builder for Elementor plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'mf-te (the fo |
| CVE-2026-119632 | 7.2 | n/a | The Forminator Forms – Contact Form, Payment Form & Custom Form Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'textarea-N (rich-text draft value, saved as Save-and- |
| CVE-2026-120485 | 7.2 | n/a | The Admin Columns plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'url' parameter in all versions up to, and including, 7.1.8 due to insufficient input sanitization and outpu |
| CVE-2026-120529 | 7.2 | n/a | The Admin Columns plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'HTTP_USER_AGENT' parameter in all versions up to, and including, 7.1.7 due to insufficient input sanitizati |
| CVE-2026-120676 | 7.2 | n/a | The Forminator Forms – Contact Form, Payment Form & Custom Form Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'upload-1 (the File Upload field's element_id)' parame |
| CVE-2026-125039 | 7.2 | n/a | The EZ SQL Reports Shortcode Widget and DB Backup plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'User-Agent header (stored to comment_agent)' parameter in all versions up t |
| CVE-2026-126011 | 7.2 | n/a | The Photo Gallery, Sliders, Proofing and Themes – NextGEN Gallery plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 4. |
| CVE-2026-131822 | 7.2 | n/a | The Contact Form to Any API plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'your-message (any CF7 form field)' parameter in all versions up to, and including, 3.0.7 due to i |
| CVE-2026-132620 | 7.2 | n/a | The WPBot – AI ChatBot for WordPress & Growth Suite: SEO, AI Writer, Email Marketing, Social Media plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'text' parameter in all ver |
| CVE-2026-133361 | 7.2 | n/a | The BlockStrap Page Builder – Bootstrap Blocks plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 0.1.65 due to insuffi |
| CVE-2026-96991 | 7.2 | n/a | The SchemaEngine AI – AI Schema Markup, Reviews & Rich Snippets for SEO plugin for WordPress is vulnerable to Stored Cross-Site Scripting via Comment Content via WebPage JSON-LD Description in all ver |
| CVE-2026-125054 | 7.2 | n/a | The SiteOrigin CSS plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via the 'class' parameter in all versions up to, and including, 1.6.9 due to insufficient input sanitizat |
| CVE-2026-107632 | 7.2 | n/a | The Unbounce Landing Pages plugin for WordPress is vulnerable to Stored Cross-Site Scripting in versions up to, and including, 1.1.6. This is due to insufficient input sanitization and output escaping |
| CVE-2026-118061 | 7.2 | n/a | The VikBooking Hotel Booking Engine & PMS plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'inquiry (array keys)' parameter in all versions up to, and including, 1.8.20 due to |
| CVE-2026-119061 | 7.2 | n/a | The VikBooking Hotel Booking Engine & PMS plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'vbf<field_id>' parameter in all versions up to, and including, 1.8.20 due to insuff |
| CVE-2026-120526 | 7.2 | n/a | The WCFM Membership – WooCommerce Memberships for Multivendor Marketplace plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'wcfm_membership_registration_form[store_name]' para |
| CVE-2026-122230 | 7.2 | n/a | The Thim Kit for Elementor – Pre-built Templates & Widgets for Elementor plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via the 'comment' parameter in all versions up to,  |
| CVE-2026-131609 | 7.2 | n/a | The Germanized for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'billing_address.first_name (Store API checkout) → stored on parent order; withdrawal get_first |
| CVE-2026-133367 | 7.2 | n/a | The WPC Frequently Bought Together for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'variation' parameter in all versions up to, and including, 8.0.2 due to in |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-qj3g-mrg9-wx86 | CVE-2026-133361 | high | The BlockStrap Page Builder – Bootstrap Blocks plugin for WordPress is vulnerable to Stored Cross... |
| GHSA-5m35-h3xr-fqw2 | CVE-2026-96991 | high | The SchemaEngine AI – AI Schema Markup, Reviews & Rich Snippets for SEO plugin for WordPress is... |
| GHSA-vm9p-468r-5w98 | CVE-2026-133963 | medium | A vulnerability was determined in MaysWind AriaNg-Native up to 1.3.14. Affected by this issue is... |
| GHSA-4ch3-9vrf-mfmq | CVE-2026-133369 | medium | The CodePeople Post Map for Google Maps plugin for WordPress is vulnerable to Stored Cross-Site... |
| GHSA-hc58-c2qw-mg6w | CVE-2026-131822 | high | The Contact Form to Any API plugin for WordPress is vulnerable to Stored Cross-Site Scripting via... |
| GHSA-2gfh-q7f2-qrp2 | CVE-2026-107713 | high | The Flutterwave Payments plugin for WordPress is vulnerable to Stored Cross-Site Scripting via... |
| GHSA-c5g4-9gp2-cr69 | CVE-2026-119632 | high | The Forminator Forms – Contact Form, Payment Form & Custom Form Builder plugin for WordPress is... |
| GHSA-5p2v-34wc-jxfq | CVE-2026-116619 | high | The MetForm – Contact Form, Survey, Quiz, Conditional Forms, Form Templates & Custom Form Builder... |
| GHSA-mf66-xcv4-gghr | CVE-2026-125054 | high | The SiteOrigin CSS plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting... |
| GHSA-gqjv-c6rv-g4mm | CVE-2026-120738 | medium | The Organize Media Folder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via... |
| GHSA-g62x-87gv-5qwj | CVE-2026-132620 | high | The WPBot – AI ChatBot for WordPress & Growth Suite: SEO, AI Writer, Email Marketing, Social... |
| GHSA-9228-62vg-2553 | CVE-2026-125039 | high | The EZ SQL Reports Shortcode Widget and DB Backup plugin for WordPress is vulnerable to Stored... |
| GHSA-mrm6-w4r7-73xh | CVE-2026-126011 | high | The Photo Gallery, Sliders, Proofing and Themes – NextGEN Gallery plugin for WordPress is... |
| GHSA-rc6q-v3f6-r25f | CVE-2026-130150 | medium | The Product Import Export for WooCommerce – CSV Product Importer & Exporter plugin for WordPress... |
| GHSA-3p8g-9fq8-rf59 | CVE-2026-120486 | medium | The ShortPixel Image Optimizer – Optimize Images, Convert WebP & AVIF plugin for WordPress is... |
| GHSA-mx2q-gj4w-4rrj | CVE-2026-118059 | medium | The MailerLite – Signup forms (official) plugin for WordPress is vulnerable to Stored Cross-Site... |
| GHSA-4fhm-2cpm-xrr9 | CVE-2026-120529 | high | The Admin Columns plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the ... |
| GHSA-2f24-3jmv-624x | CVE-2026-120679 | medium | The Redux Framework plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the '... |
| GHSA-3626-3j4c-895g | CVE-2026-120676 | high | The Forminator Forms – Contact Form, Payment Form & Custom Form Builder plugin for WordPress is... |
| GHSA-75x3-74m8-qmgp | CVE-2026-120485 | high | The Admin Columns plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'url'... |
| GHSA-9hgx-rj9x-5c2f | CVE-2026-104904 | medium | The Shortcodes Ultimate plugin for WordPress is vulnerable to Local File Inclusion in versions up... |
| GHSA-wrg4-68qg-q388 | CVE-2026-131577 | medium | The WSMS (formerly WP SMS): SMS Notifications, OTP Login and WooCommerce SMS plugin for WordPress... |
| GHSA-6853-j238-r87f | CVE-2026-126701 | medium | The Themify Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the ... |
| GHSA-x7v9-6hrr-5537 | CVE-2026-129096 | medium | The Themify Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the ... |
| GHSA-6jgm-h689-j9cf | CVE-2026-123086 | high | The PublishPress Revisions: Duplicate Posts, Submit, Approve and Schedule Content Changes plugin... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Lucid Motors | Inception | US | 2026-11-21T02:51:53.714936+00:00 |
| MT5 algo-trading farm (OneFunded funded account, WINSERVER) | PixelLeaks |  | 2026-11-20T22:54:54.318905+00:00 |
| bastion.internal domain controller (GCP, GRATEFUL-V1) | PixelLeaks |  | 2026-11-20T22:54:34.550842+00:00 |
| Aixia Group AB (Nasdaq-listed AI/IT, Sweden) | PixelLeaks | SE | 2026-11-20T22:54:13.528875+00:00 |
| Kingsport Cargo (logistics, Laravel intranet) | PixelLeaks |  | 2026-11-20T22:53:53.828949+00:00 |
| Arab Software Computer / ASCON (Oracle ERP hosting, Alexandria) | PixelLeaks | EG | 2026-11-20T22:53:33.817534+00:00 |
| Lee Memorial Health System | medusalocker | US | 2026-11-20T22:35:47.096012+00:00 |
| FAST ČR | everest | CZ | 2026-11-20T22:04:10.955887+00:00 |
| Alla France | everest | FR | 2026-11-20T22:03:33.625170+00:00 |
| ABL Bio | everest |  | 2026-11-20T22:02:57.555361+00:00 |
| Vizrt | everest | NO | 2026-11-20T22:02:21.373593+00:00 |
| ALKF | everest |  | 2026-11-20T22:01:44.629352+00:00 |
| VanMor | Dark Project | CA | 2026-11-20T20:51:19.650070+00:00 |
| Rays Power Infra | everest | IN | 2026-11-20T20:31:59.393560+00:00 |
| Geesol | everest |  | 2026-11-20T21:37:08.045741+00:00 |
| My American Alliance | everest |  | 2026-11-20T21:36:31.626246+00:00 |
| Accuver | everest |  | 2026-11-20T21:35:54.832299+00:00 |
| BK Law Group LLC | rhysida | US | 2026-11-20T19:30:55.914976+00:00 |
| KOWA | everest | JP | 2026-11-20T20:32:35.470538+00:00 |
| Jones Walker | SilentRansomGroup | US | 2026-11-20T18:10:29.260445+00:00 |

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
| 138.226.239.233 | 11 |
| 138.226.239.234 | 11 |
| 193.32.162.15 | 10 |
| 45.148.10.61 | 9 |
| 62.60.130.148 | 9 |
| 3.129.187.38 | 8 |
| 18.116.101.220 | 8 |
| 18.218.118.203 | 8 |
| 45.148.10.141 | 8 |
| 45.148.10.151 | 8 |
| 66.132.172.41 | 8 |
| 66.132.172.99 | 8 |
| 66.132.172.133 | 8 |
| 66.132.172.193 | 8 |
| 66.132.172.207 | 8 |
| 66.132.186.195 | 8 |
| 66.132.195.66 | 8 |
| 66.132.195.96 | 8 |
| 74.225.156.91 | 8 |
| 77.239.124.252 | 8 |

### OpenPhish (live phishing URLs)
- https://att-10page42.weeblysite.com/
- https://metamzkloge.gitbook.io/us
- http://metamzkloge.gitbook.io/
- http://k5q9x2m-16073842-vn4p1z-87.pages.dev/
- http://sp25ct11-zavmilo-biz-nerzaku.pages.dev/
- https://sk-facebook.blogspot.com/
- https://www.sk-facebook.blogspot.com/
- https://www.facebook-official-page.blogspot.com/
- https://www.fake-facebook.blogspot.com/
- https://kcnlgn10.gitbook.io/
- https://att-currently-2-8-2025.weeblysite.com/
- https://shopeejkt-78.blogspot.com/
- https://facebook-official-page.blogspot.com/
- https://facebookmail-facebook.blogspot.com/
- https://hadiah-resmi1577.blogspot.com/
- https://www.facebookmail-facebook.blogspot.com/
- https://facebook-www.blogspot.com/
- https://facebook-carol.blogspot.com/
- https://statroblox.com/roblox-game-stats
- https://instagramsupportverify.blogspot.com/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://tra.com/fresh-start-signup2?_ef_transaction_id=888c18d349c24dbf9a6f18c2b15df963&source_id=&affid=5&sub1=ac0f81e0a91a41eea714dc5ef6c8713a&sub2=427035&sub3=taaax21&sub4=&sub5=&oid=44 |
| N/A | https://yandex.ru/showcaptcha?cc=1&form-fb-hint=2.1.4bdb8fafcfce19433cbb4dae57a039eca57795d3868265ff35423eada5b1dce75db84b96a48374aa1a87b21af07bebf38981c5aa81a888d0f4bbc248&mt=AD1153E67EAE057B466CE40247E2AE03BE945C373292A564B1D2BC97C7CAAD3910BF3E8B4A98C8DC147ADBB3FEC55FCD56C83F6A9A92FBCDE5738E0D8A9073583CCD999495C60E5D77382F3D249E6979E92DED410AC2E5EB81974BA0408617EF55D8C111C91FDF71851546A9C126EC32CAE0AE260DBF897525CB74E6269EDD79A93DF4DEFAD64124BE633B66424319E6404DE5E597FABB34D06341&retpath=aHR0cHM6Ly95YW5kZXgucnUvc2VhcmNoP3RleHQ9MjExNjg3MTc%2C_f0325a4ec22f8996ab6de6db92598599&t=2%252F1795255610%252Fb8d8c153b55f6802e699bfc9542d7f14&u=9797100180310852319&s=c8bcb71e9b17b4ae09cec799210ec170 |
| N/A | https://solicitar-beneficiosbcp.sbs/home |
| N/A | https://b8376mghi5d.jp.larksuite.com/share/base/form/shrjpMwk5KEz3wmsdPQjPPcLjqh?auth_token=U7CK1RF-d63i3582-a8f0-4efc-9e3e-33ba9aod1bh8-NN5W4 |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AaSxoQyQEeCdGiNQploah5nAij7vrMqrlVIHby1Q4v_ARx9kttGkmffM4ARVCnkvjXQyGpUqW4kQNA&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBglctNMAXhKB9nTff_uW3Ah32LRlUvCTixraTNI7yd8Xx9leYAT-HONwrgXOze6PN9OO2w2Jw3w&dsh=S453297431%3A1795255302676704 |
| N/A | http://away.vk.ru/away.php?rh=d758c3f6-c13c-45e7-b523-f89cd2fa4abe |
| N/A | http://nourishbeyondlife.info/ |
| N/A | https://flat-bread-04ca.cloudflareaccess.com/cdn-cgi/access/login/vertiv-command-center.pages.dev?kid=617efb6eb0445e77d08421b7c2075c08ed7302463271c62a28d702c82772462a&meta=eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiIsImtpZCI6IjEyY2U5NjlmMDk3YjUyNjliNjllZjA0N2EwMjBiZGI2NGMwMTc5NjMwNzE3MzJhMWJjODg2NjJiNGUxYzJjY2IifQ.eyJ0eXBlIjoibWV0YSIsImF1ZCI6IjYxN2VmYjZlYjA0NDVlNzdkMDg0MjFiN2MyMDc1YzA4ZWQ3MzAyNDYzMjcxYzYyYTI4ZDcwMmM4Mjc3MjQ2MmEiLCJob3N0bmFtZSI6InZlcnRpdi1jb21tYW5kLWNlbnRlci5wYWdlcy5kZXYiLCJyZWRpcmVjdF91cmwiOiIvIiwic2VydmljZV90b2tlbl9zdGF0dXMiOmZhbHNlLCJpc193YXJwIjpmYWxzZSwiaXNfZ2F0ZXdheSI6ZmFsc2UsImV4cCI6MTc5NTI1NTI4MiwibmJmIjoxNzk1MjU0OTgyLCJpYXQiOjE3OTUyNTQ5ODIsImF1dGhfc3RhdHVzIjoiTk9ORSIsIm10bHNfYXV0aCI6eyJjZXJ0X2lzc3Vlcl9kbiI6IiIsImNlcnRfc2VyaWFsIjoiIiwiY2VydF9pc3N1ZXJfc2tpIjoiIiwiY2VydF9wcmVzZW50ZWQiOmZhbHNlLCJjb21tb25fbmFtZSI6IiIsImF1dGhfc3RhdHVzIjoiTk9ORSJ9LCJyZWFsX2NvdW50cnkiOiJVUyIsImFwcF9zZXNzaW9uX2hhc2giOiIwODAxNDU3ZGU3Y2NjMjg2OWY5MGIyMGRjMTcxMzQ4MjAyMTE1Zjg4ZDVlOGJkNGY4MThhNTBlZmZjNTU0NTQ3In0.M9sAy4NW5UXuSXxEeDaCRJDSpcs4l6SseB0RHcSQgoUyYgAurDc3wEHzvsX0BooGdjac-PHg90tP-N36DUXAZPOOCQLVm7NkaorOuasA6OejGUPEvSul3BoxxyMyfGZ2CLsGoorTrqsTHAlxjMKfCA10Nhj0xeFEm9CG-I8nay_twREKEB-DqtkKSKI1_ErnTJC7TMaqgkKw5GwrEak60IrTZJHjAffykjjcbLduVFcW9xosa0DYTlSH0wZJ9mFvaD0LNMwZIPQCM6cq5pIAdWVpY53CqbUjPcApKob55HODWYl8S4kXEgrbVHBt7vg8PSf8GFt7_G9hCbtd4DJ-Hg&redirect_url=%2F |
| N/A | https://away.vk.ru/away.php?rh=36354f07-e4a6-4e41-a148-b611a8a822d5 |
| N/A | https://away.vk.ru/away.php?rh=6ec0a73a-13d3-41ed-8967-5358f82e7ad0 |
| N/A | https://www.cdiscount.com?source_id=&sub1=dc0mha60fgns73akad10&adv1=&adv2= |
| N/A | https://away.vk.ru/away.php?rh=d4f15ab7-82b5-4deb-b149-72689adf9645 |
| N/A | https://auto.trovit.be/ |
| N/A | https://thebenefitsaccessguide.com/?c=25066&sid1=540190&sid2=17b-4244600-17917102-251851-11442-&sid3=608296490&sid4=&sid5=&transaction_id=0a79fa214eb24e2598c95b19c2ecbb36&campaignid=564&first_name=&last_name=&email=&address1=&address2=&city=&state=&zip=&phone=&gender=&dob=&token= |
| N/A | https://maxis-ms.biz.id/max |
| N/A | https://away.vk.ru/away.php?rh=9db0f3bb-5151-4310-bb8c-39e2c3626f3b |
| N/A | https://achaofertasdalu.vercel.app/ |
| N/A | https://tra.com/fresh-start-signup2?_ef_transaction_id=48da4eb74606490497f657a604a6db5b&source_id=&affid=5&sub1=c1afa19a1f8d446bbbed767eae723356&sub2=427035&sub3=taxrlfadvct&sub4=&sub5=&oid=44 |
| N/A | https://pageseuc1.actmkt.com/(S(jyqvy4qdegfd2zugmjwhun03))/l/c5X8MfZz6j9Y7Fto3LAd |
| N/A | https://away.vk.ru/away.php?rh=f7b3a2e7-5e9e-4ee1-bf9f-109aa222a4ea |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| 8602c6e50940880e8f3ba1d9f53ad97b481c1617 | Malware distribution |
| d66a7599fc875b9ca6633470adadfa8cc5b9c04f | Malware C&C |
| 391c96cd00389c4b285f60567adb3a3531009fc9 | Malware C&C |
| b80e467af83941a4aa1ebfd18d737059e6ade74f | Malware C&C |
| c333a3d828305b2a8f6d4f5646774ee30f0be065 | OffLoader C&C |
| c3c9181f153a966d5e57ac0da2caa02ee0268451 | Vidar C&C |
| d07fefbb493d25b4e602bd75a5f847a76ce8817a | Vidar C&C |
| 162ae181924c0382ac8c4d1b59bd2a5ab71d68f2 | Malware distribution |
| 6e5c85d2f880211cfc2b36d1e5140890c1a26399 | PureLogsStealer C&C |
| 09d1e05f957a313204823679e8b23199ddfd85d1 | Vidar C&C |
| 311d90972082954ffd0a2da52a40209f4ded4de8 | RemusStealer C&C |
| d41dff333ce19bcd2d80a26d9df47718e65e421a | RemusStealer C&C |
| 3978f94a567a7ef1f78b59b404b3794a724bd7da | RemusStealer C&C |
| 46cd17fe66d9e90a333b3d8544ad6e1ac3ced580 | FunStealer C&C |
| 1fcc1376b18842bcd8ce9078371843dc9b55ea2b | FunStealer C&C |
| 47f4d9c4606c19ddd4c053e84b27e76965058fe8 | FunStealer C&C |
| 58af3cc8f1ab7b9b4d02c23b5ac169d498cbddbc | SheetRAT C&C |
| ede2b62ea65aa4d5b6751f6fdb3702f7f55f730a | Malware C&C |
| 70e1fb9b59e223a1d2e45d12b8dbb7f4dd28d1ac | RevStealer C&C |
| ffd76c5a5ab1a81486a34ea5532ba2d5acef9995 | RevStealer C&C |

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
- 1.10.160.82
- 1.12.234.27
- 1.12.252.163
- 1.13.79.149
- 1.14.240.247
- 1.164.194.127
- 1.183.196.24
- 1.192.216.175
- 1.209.148.143
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.234.21.73
- 1.234.27.159
- 1.234.5.148
- 1.234.53.65
- 1.234.80.94
- 1.235.183.146

### CINS Army (poorly-rated IPs)
- 1.14.137.147
- 1.14.3.170
- 1.145.16.243
- 1.170.200.20
- 1.177.162.2
- 1.189.146.9
- 1.189.41.213
- 1.20.151.114
- 1.24.16.106
- 1.24.16.110
- 1.24.16.114
- 1.24.16.122
- 1.24.16.129
- 1.24.16.131
- 1.24.16.140
- 1.24.16.150
- 1.24.16.152
- 1.24.16.161
- 1.24.16.174
- 1.24.16.182

## News (last ~36h, across outlets)
### The Hacker News
- [Signal Blocks AI Agents From Reading Private Chats via Screenshots on Android and iOS](https://thehackernews.com/2026/11/signal-blocks-ai-agents-from-reading.html)
- [Hackers Exploit Critical VMware, Cisco, and Apache Flaws as Espionage Attacks Emerge](https://thehackernews.com/2026/11/hackers-exploit-critical-vmware-cisco.html)
- [WhatsApp Patches 3 Security Flaws, Including Android Bug Suspected of Use in Scams](https://thehackernews.com/2026/11/whatsapp-patches-3-security-flaws.html)
- [Bazuka Android Malware Uses Fake Screen Overlays to Hide Credential Theft and Device Control](https://thehackernews.com/2026/11/bazuka-android-malware-uses-fake-screen.html)
- [Linux KVM Flaw CVE-2026-99312 Lets Guest VMs Access Host Memory on AMD Hosts](https://thehackernews.com/2026/11/new-linux-kvm-flaw-cve-2026-99312-lets.html)
- [The Path to AI Autonomy in the SOC](https://thehackernews.com/2026/11/the-path-to-ai-autonomy-in-soc.html)
- [SonicWall Warns Gen 6 Firewalls Won't Get Security Patches, Even for Critical Flaws](https://thehackernews.com/2026/11/sonicwall-warns-gen-6-firewalls-wont.html)
- [Hackers Exploit Critical Cisco Expressway Flaw, Breach Four Devices and Reach Internal Network](https://thehackernews.com/2026/11/hackers-exploit-critical-cisco.html)
- [China-Linked Hackers Exploit Critical VMware vCenter Zero-Day to Gain Admin Access and Steal Data](https://thehackernews.com/2026/11/china-linked-hackers-exploit-critical.html)
- [ROMULUS ClickFix Attacks Deliver RAT That Can Spy on Users and Control PCs](https://thehackernews.com/2026/11/romulus-clickfix-attacks-deliver-rat.html)
- [New Unpatched Windows 0-Day FastUnlock Lets Someone Holding a Locked PC Run Programs on It](https://thehackernews.com/2026/11/new-unpatched-windows-0-day-fastunlock.html)

### BleepingComputer
- [Bell Canada says 'agentic' hacker stole enterprise customer data](https://www.bleepingcomputer.com/news/security/bell-canada-says-agentic-hacker-stole-enterprise-customer-data/)
- [Hackers use autonomous AI tool Cairn to find zero-day, take over server](https://www.bleepingcomputer.com/news/security/hackers-use-autonomous-ai-tool-cairn-to-find-zero-day-take-over-server/)
- [Vendor data breach exposes Chase, Visa, Mastercard customer info](https://www.bleepingcomputer.com/news/security/vendor-data-breach-exposes-chase-visa-mastercard-customer-info/)
- [Still tracking company passwords in spreadsheets? You’re flying blind.](https://www.bleepingcomputer.com/news/security/still-tracking-company-passwords-in-spreadsheets-youre-flying-blind/)
- [N-able says recent security breach led to major service outage](https://www.bleepingcomputer.com/news/microsoft/n-able-says-recent-security-breach-led-to-major-service-outage/)
- [Microsoft now automatically installs Windows 11 26H2 on unmanaged devices](https://www.bleepingcomputer.com/news/microsoft/microsoft-now-automatically-installs-windows-11-26h2-on-personal-and-unmanaged-pcs/)
- [F5 releases emergency patches for critical BIG-IP RCE flaws](https://www.bleepingcomputer.com/news/security/f5-releases-emergency-patches-for-critical-big-ip-rce-flaws/)
- [Windows 11 KB5132057 update released with 28 changes and fixes](https://www.bleepingcomputer.com/news/microsoft/windows-11-kb5132057-update-released-with-28-changes-and-fixes/)
- [VMware patches vCenter zero-day exploited in attacks since September](https://www.bleepingcomputer.com/news/security/vmware-patches-vcenter-zero-day-exploited-in-attacks-since-september/)

### Krebs on Security
- [CTO of ‘RansomwareHelp’ Indicted for Wire Fraud](https://krebsonsecurity.com/2026/11/cto-of-ransomwarehelp-indicted-for-wire-fraud/)

### Dark Reading
- [China's 'Armory Castle' Lays Siege to VMware vCenter Zero-Day](https://www.darkreading.com/cyberattacks-data-breaches/china-armory-castle-vmware-vcenter-zero-day)
- [In Security, Words Matter as Much as Tools, Maybe More](https://www.darkreading.com/cybersecurity-operations/security-words-matter)
- [What We Missed: Nvidia CEO Scandal Rocks AI Industry](https://www.darkreading.com/cyber-risk/what-we-missed-nvidia-ceo-scandal-rocks-ai-industry)

### SecurityWeek
- [WhatsApp Fixes Flaw Uncovered While Disrupting Scam Campaign](https://www.securityweek.com/whatsapp-fixes-flaw-uncovered-while-disrupting-scam-campaign/)
- [In Other News: Norwegian Energy Firm Cyberattacks, Supercomputer Hack, New Nightmare Eclipse Exploit](https://www.securityweek.com/in-other-news-norwegian-energy-firm-cyberattacks-supercomputer-hack-new-nightmare-eclipse-exploit/)
- [Industry Reactions to Major Outages and AI Patching Debate: Feedback Friday](https://www.securityweek.com/industry-reactions-to-major-outages-and-ai-patching-questions-feedback-friday/)
- [SBC Medical Group Data Breach Impacts Over 2 Million](https://www.securityweek.com/sbc-medical-group-data-breach-impacts-over-2-million/)
- [European Commission Confirms AI-Assisted Cyberattack Disrupted Services](https://www.securityweek.com/european-commission-confirms-ai-assisted-cyberattack-disrupted-services/)
- [Ruby Patches Ruby2Shell Vulnerability That Could Lead to RCE](https://www.securityweek.com/ruby-patches-ruby2shell-vulnerability-that-could-lead-to-rce/)
- [N-able Blames Service Disruption on Cyberattack](https://www.securityweek.com/n-able-blames-service-disruption-on-cyberattack/)
- [JPMorgan, Visa, Mastercard Cite Third-Party Incidents Amid Data Leak](https://www.securityweek.com/jpmorgan-visa-mastercard-cite-third-party-incidents-amid-data-leak/)

### The Record
- [West Virginia Legislature hit with cyber incident affecting IT systems](https://therecord.media/west-virginia-legislature-cyberattack)
- [US companies’ use of Chinese open weight AI draws rebuke from House chairmen](https://therecord.media/chinese-open-weight-AI-use-by-US-companies-house-investigation)
- [Container Store restores systems after cyberattack](https://therecord.media/container-store-restores-systems-cyberattack)
- [Amazon says Chinese hackers used Cairn AI tool to discover apparent zero-day during attack on university](https://therecord.media/amazon-research-cairn-ai-university-attacks-possible-zero-day)
- [NSA resumes normal operations following internal network disruptions](https://therecord.media/nsa-resumes-normal-operations-following-internal-disruptions)

### Infosecurity Magazine
- [JPMorgan Confirms Customer Data Breach Following Third-Party Compromise](https://www.infosecurity-magazine.com/news/jpmorgan-data-breach-third-party/)
- [Ransomware Recovery Takes 20 Days for the Typical Victim, Report Finds](https://www.infosecurity-magazine.com/news/ransomware-recovery-20-days/)
- [Mail Bombing Attacks Fuel IT Helpdesk Impersonation Scams](https://www.infosecurity-magazine.com/news/mail-bombing-attacks-it-helpdesk/)
- [Suspected North Korea-Aligned Group Hides C2 on Solana Blockchain](https://www.infosecurity-magazine.com/news/overlord-rat-solana-blockchain-c2/)

### CyberScoop
- [Signal blocks Apple, Google AI screenshotting in response to ‘existential threat’ to privacy app](https://cyberscoop.com/signal-blocks-apple-google-ai-screenshots/)
- [Sean Cairncross out as national cyber director](https://cyberscoop.com/sean-cairncross-out-national-cyber-director/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
- [Dialing for Data: Inside the Com’s High-Profile Heists](https://unit42.paloaltonetworks.com/com-affiliate-vishing-attacks/)

### Microsoft Security Blog
- [Microsoft named a Leader in the 2026 Gartner® Magic Quadrant™ for SIEM](https://www.microsoft.com/en-us/security/blog/2026/11/20/microsoft-named-a-leader-in-the-2026-gartner-magic-quadrant-for-siem/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Friday, November 20th, 2026 https://isc.sans.edu/podcastdetail/10188, (Fri, Nov 20th)](https://isc.sans.edu/diary/rss/33538)

### Securelist (Kaspersky)
_No new items / feed unavailable this run._

### CrowdStrike Blog
- [Java4Shell (CVE-2026-114938): CrowdStrike Detects Exposure and Post-Exploitation Activity](https://www.crowdstrike.com/en-us/blog/crowdstrike-helps-protect-against-java4shell-cve-2026-114938/)
- [NGINX2Root: Identify and Protect with the CrowdStrike Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-helps-protect-against-nginx2root-cve-2026-123007/)
- [CrowdStrike Brings the Human Advantage to AI Detection and Response](https://www.crowdstrike.com/en-us/blog/crowdstrike-brings-human-advantage-aidr/)
- [CrowdStrike Is Building the Engine of the Agentic SOC with Falcon Next-Gen SIEM](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-gartner-mq-siem/)
- [Hidden in the Weights: Supply Chain Risk from Backdoored LoRA Models](https://www.crowdstrike.com/en-us/blog/supply-chain-risk-from-backdoored-lora-models/)
- [Inside Falcon AI Gateway: One Control Point for AI Traffic](https://www.crowdstrike.com/en-us/blog/falcon-ai-gateway-one-control-point-for-ai-traffic/)
- [CrowdStrike Named a Leader in the 2026 IDC MarketScape for Worldwide Augmented Identity Security Solutions](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-idc-marketscape-worldwide-augmented-identity-security-solutions/)
- [November 2026 Patch Tuesday: 1,252 CVEs Include One Zero-Day and 68 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-november-2026/)
- [How Adversaries Are Turning the Vulnerability Ecosystem Against Defenders](https://www.crowdstrike.com/en-us/blog/adversaries-turn-vulnerability-ecosystem-against-defenders/)
- [CrowdStrike Extends the Agentic SOC to Detect and Stop Agent Insider Threats](https://www.crowdstrike.com/en-us/blog/crowdstrike-detects-and-stops-agent-insider-threats/)

### FortiGuard Threat Signal
- [Armory Castle Attack](https://fortiguard.fortinet.com/threat-signal-report/6678)
- [Java4Shell](https://fortiguard.fortinet.com/threat-signal-report/6668)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal