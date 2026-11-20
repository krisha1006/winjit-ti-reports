# Winjit Daily TI Digest — 2026-11-20

_Auto-generated. Window: last ~24h. Fetched at 2026-11-20T11:08:05.123274+00:00Z_

**At a glance:** 0 new KEV · 65 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-133493 | 10.0 | n/a | A vulnerability was identified in D-Link DIR-600L 2.17b02. Affected is the function genacgi_main of the file gena.cgi of the component GENA Handler. Such manipulation leads to os command injection. Th |
| CVE-2026-14492 | 9.8 | 2.4% | The WP Duplicate – WordPress Migration Plugin plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 1.1.11 via the save_single_batch_file function. This is  |
| CVE-2026-76536 | 9.4 | n/a | In Splunk Enterprise versions below 10.4.5, 10.2.9, 10.0.12, and 9.4.17, an unauthenticated user could use an empty clustering shared secret to read and modify clustering configuration through the clu |
| CVE-2026-133500 | 9.1 | n/a | A vulnerability was identified in Gladys Assistant up to 4.71.0. This affects an unknown function of the file gateway.downloadBackup.js of the component Backup Restore Endpoint. The manipulation of th |
| CVE-2026-120681 | 9.1 | n/a | The Mang Board plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 2.4.7. This is due to the plugin not properly verifying that a user is authorized to per |
| CVE-2026-133501 | 9.0 | n/a | A security flaw has been discovered in Gladys Assistant up to 4.71.0. This impacts an unknown function of the file server/lib/gateway/gateway.downloadBackup.js of the component Backup Restore Handler. |
| CVE-2026-133172 | 8.8 | n/a | Cozy Cloud cozy-stack 1.6.62 before 1.6.69 contains an authorization bypass vulnerability in the shared-drive move handler that allows authenticated users to access other instances' files. Attackers o |
| CVE-2026-133307 | 8.8 | n/a | ClassiCube before 1.4.0 contains a heap-based out-of-bounds write vulnerability in Png_Decode in src/Bitmap.c that allows malicious servers to corrupt client memory by sending a PNG with a duplicate I |
| CVE-2026-131236 | 8.8 | n/a | In Splunk Enterprise Security versions below 8.7.0, an unauthenticated user who can influence indexed event data could store attacker-controlled values in event fields. If another authenticated user w |
| CVE-2026-131271 | 8.8 | n/a | In Splunk SOAR versions below 8.8.0, an authenticated user with permission to view and edit containers for one label could use a slash command through the Representational State Transfer (REST) API to |
| CVE-2026-125085 | 8.8 | n/a | The Nexter Extension – Security, Performance, Code Snippets & Site Toolkit plugin for WordPress is vulnerable to Privilege Escalation in versions up to, and including, 4.9.0 This is due to the role_sw |
| CVE-2026-131258 | 8.7 | n/a | In Splunk SOAR versions below 8.8.0, a user with edit permission for a container or workbook task could store attacker-controlled Hypertext Markup Language (HTML) in a note. When another user with vie |
| CVE-2026-131260 | 8.7 | n/a | In Splunk SOAR versions below 8.8.0, a user with the containers:edit permission could import a container that includes a malicious Hypertext Markup Language (HTML) note. When another user views the im |
| CVE-2026-133528 | 8.6 | n/a | BeamNG.drive before 0.40.6 contains an out-of-bounds write vulnerability because JIT-compiled LuaJIT traces omit FFI array bounds checks, letting untrusted Lua escape the sandbox. Attackers supplying  |
| CVE-2026-131203 | 8.3 | n/a | In Splunk Enterprise Security versions below 8.7.0, a user who holds the "ess_analyst" Splunk Enterprise Security role could modify a search macro associated with risk exclusions. Scheduled Risk data  |
| CVE-2026-131215 | 8.3 | n/a | In Splunk Enterprise Security versions below 8.7.0, a user that holds a role with the ueba_finding_exclusion_edit capability could store attacker-controlled values in a User and Entity Behavior Analyt |
| CVE-2026-131218 | 8.3 | n/a | In Splunk Enterprise Security versions below 8.7.0, a user that holds a role with the mc_investigation_read capability could inject arbitrary Search Processing Language (SPL) into Mission Control dash |
| CVE-2026-131200 | 8.1 | n/a | In Splunk Enterprise Security versions below 8.7.0, a user who holds the "ess_analyst" Splunk Enterprise Security role could create an attacker-controlled saved search. Threat intelligence lookup gene |
| CVE-2026-131210 | 8.1 | n/a | In Splunk Enterprise Security versions below 8.7.0, a user that holds a role with the ueba_finding_exclusion_edit capability could create a finding exclusion rule that references an attacker-controlle |
| CVE-2026-84273 | 8.1 | n/a | IBM Guardium Data Protection 12.2 is vulnerable to path traversal in the datasource functionality. An authenticated attacker could exploit this vulnerability to delete arbitrary files on the appliance |
| CVE-2026-120556 | 8.1 | n/a | The Toocheke Companion plugin for WordPress is vulnerable to Missing Authorization leading to arbitrary post and attachment deletion in versions up to, and including, 2.38. This is due to a missing ob |
| CVE-2026-89095 | 8.1 | n/a | The Shortcodes and extra features for Phlox theme plugin for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 2.17.22 via the 'extra_template_path' parameter param |
| CVE-2026-118522 | 8.1 | n/a | The Video & Photo Gallery for Ultimate Member plugin for WordPress is vulnerable to Arbitrary File Deletion in versions up to, and including, 1.1.4 This is due to the um_gallery_add_videos() AJAX hand |
| CVE-2026-130010 | 8.1 | n/a | The Chatterbug Forms – Fast, Flexible WordPress Form Builder plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation in the cbforms_delete_uploaded_files |
| CVE-2026-126716 | 8.1 | n/a | The Mega Forms – Drag & Drop Form Builder with Multi-Step & Conditional Logic plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation in the delete_entry |
| CVE-2026-133168 | 7.8 | n/a | OFFIS DCMTK 3.7.1 contains a heap buffer overflow vulnerability in togglePlanarConfiguration8 and togglePlanarConfiguration16 in djcodece.cc, which compute row offsets using rows instead of columns. A |
| CVE-2026-131266 | 7.7 | n/a | In Splunk SOAR versions below 8.8.0, a user that holds a role with the System Settings edit permission could cause Splunk SOAR to send a stored Elasticsearch password to a host that the user controls. |
| CVE-2026-133577 | 7.7 | n/a | A flaw was found in the Kuadrant WebAssembly (WASM) shim shipped in Red Hat Connectivity Link 1.5. When a TokenRateLimitPolicy is attached to an HTTPRoute that also has an AuthPolicy - or when a RateL |
| CVE-2026-131243 | 7.6 | n/a | In Splunk SOAR versions below 8.8.0, an authenticated user with permission to view an affected container could query the Representational State Transfer (REST) API for approvals to retrieve a live ext |
| CVE-2026-131190 | 7.5 | n/a | In Splunk Enterprise versions below 10.4.5, 10.2.9, 10.0.12, and 9.4.17, an unauthenticated user could access RapidDiag process metadata and log file inventory information through the Representational |
| CVE-2026-131192 | 7.5 | n/a | In Splunk Enterprise versions below 10.6.1, 10.4.5, 10.2.9, 10.0.12, and 9.4.17, an unauthenticated user could access live event data from the indexing pipeline through the Representational State Tran |
| CVE-2026-131196 | 7.5 | n/a | In Splunk Enterprise versions below 10.4.5, 10.2.9, 10.0.12, and 9.4.17, an unauthenticated user who can connect to a Splunk-to-Splunk (S2S) data forwarding receiver could cause the Splunk daemon to t |
| CVE-2026-133201 | 7.5 | n/a | A vulnerability was determined in smartalock wireguard-lwip up to cfba91666590e86bd67842c71cedf9a423be823a. Impacted is the function mul of the file src/crypto/refc/x25519.c of the component X25519 La |
| CVE-2026-133534 | 7.5 | n/a | PowerLink developed by Neotroni Lighting has a SQL Injection vulnerability, allowing unauthenticated remote attackers to inject arbitrary SQL commands to read database contents. |
| CVE-2026-104927 | 7.5 | n/a | The King Addons for Elementor – 100+ Elementor Widgets, 4 000+ Elementor Templates, WooCommerce Builder, Mega Menu, Popup Builder plugin for WordPress is vulnerable to authorization bypass in all vers |
| CVE-2026-128102 | 7.5 | n/a | The rtMedia for WordPress, BuddyPress and bbPress plugin for WordPress is vulnerable to generic SQL Injection via the 'custom_fields' parameter in all versions up to, and including, 4.7.17 due to insu |
| CVE-2026-130055 | 7.5 | n/a | The VidShop for WooCommerce plugin for WordPress is vulnerable to Sensitive Information Exposure in versions up to, and including, 1.10.0 via the /vsfw/v1/products/{id} REST API endpoint. This is due  |
| CVE-2026-125059 | 7.5 | n/a | The Mang Board plugin for WordPress is vulnerable to Arbitrary File Deletion via Path Traversal in versions up to, and including, 2.4.8 via the `file_path` column handled by the `mbw_board_files_api_b |
| CVE-2026-132286 | 7.3 | 0.4% | A security vulnerability has been detected in yangzongzhuan RuoYi up to 4.8.3. The impacted element is an unknown function of the file ruoyi-admin/src/main/java/com/ruoyi/web/controller/system/SysLogi |
| CVE-2026-132611 | 7.3 | 0.4% | A security vulnerability has been detected in SourceCodester Simple Form Builder Web App 1.0. This impacts the function save_response of the file /classes/Forms.php. The manipulation of the argument q |
| CVE-2026-132626 | 7.3 | 0.3% | A vulnerability was identified in SourceCodester Modern Ticket Reservation System 1.0. Affected by this vulnerability is an unknown functionality of the file /booking/validate.php. The manipulation of |
| CVE-2026-131211 | 7.3 | n/a | In Splunk App for Payment Card Industry Compliance versions below 8.7.0, a user who holds the "ess_user" Splunk Enterprise Security role could add attacker-controlled values to lookup data used by the |
| CVE-2026-133415 | 7.3 | n/a | A vulnerability has been found in sumiie24 School-Management-System up to d946d649c7c95e101fc5679ecd91999533bb10d7. The affected element is an unknown function of the file parent_Registration.php. Suc |
| CVE-2026-133478 | 7.3 | n/a | A security vulnerability has been detected in rajesh2211 Doctor-Appointment-System up to ee974dcf4c50da85e6ea026e27f4370e9468b3cc. Affected is an unknown function of the file AppointmentSystem/Appoint |
| CVE-2026-133502 | 7.3 | n/a | A weakness has been identified in blinkospace blinko up to 1.8.8. Affected is an unknown function of the file /api/auth/verify-2fa of the component 2FA Endpoint. This manipulation of the argument user |
| CVE-2026-123972 | 7.2 | n/a | The WP-Slimbox2 Plugin plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 1.1.3.1 due to insufficient input sanitizatio |
| CVE-2026-120508 | 7.2 | n/a | The Charitable – Donation & Fundraising Platform (Donation Forms, Recurring Donations & Fundraising Campaigns) plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'stripe_payment |
| CVE-2026-129327 | 7.2 | n/a | The Apaczka.pl WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the '_apaczka[<id>][error_messages] (and sibling subkeys inside _apaczka[])' parameter in all versions  |
| CVE-2026-131582 | 7.2 | n/a | The PagBank / PagSeguro e Vindi para WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'customer.name' parameter in all versions up to, and including, 5.1.6 due to  |
| CVE-2026-131645 | 7.2 | n/a | The Kognetiks Chatbot plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 2.5.9 due to insufficient input sani |
| CVE-2026-121985 | 7.2 | n/a | The FV Flowplayer Video Player plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 7.5.57.7212 due to insufficient input |
| CVE-2026-127112 | 7.2 | n/a | The Events Made Easy plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'event[event_notes]' parameter in all versions up to, and including, 3.3.8 due to insufficient input sani |
| CVE-2026-109387 | 7.2 | n/a | The Photo Gallery, Sliders, Proofing and Themes – NextGEN Gallery plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'IPTC 2#120 (caption) / 2#005 (title) inside the image file' |
| CVE-2026-116550 | 7.2 | n/a | The Photo Gallery, Sliders, Proofing and Themes – NextGEN Gallery plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 4. |
| CVE-2026-119611 | 7.2 | n/a | The NextGEN Gallery plugin for WordPress is vulnerable to Stored Cross-Site Scripting in versions up to, and including, 4.5.5 via the 'ajax_pagination_referrer' request parameter used on the /ngg_tag/ |
| CVE-2026-121790 | 7.2 | n/a | The CWILL (Formerly ParcelPanel) – Shipment Tracking, Tracking & Order Tracking for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'data[].courier_code, data[].t |
| CVE-2026-96771 | 7.2 | n/a | The Hydrogen Calendar Embeds plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via ICS Feed Event Fields (SUMMARY/DESCRIPTION/LOCATION) in all versions up to, and including,  |
| CVE-2026-126631 | 7.1 | n/a | A flaw was found in OpenSCAP. This vulnerability allows for information disclosure when performing offline scans of untrusted filesystem images, such as container images or virtual machine (VM) disks. |
| CVE-2026-131177 | 7.1 | n/a | In Splunk Enterprise versions below 10.4.4, 10.2.9, 10.0.12, and 9.4.16, a user who does not hold the "admin" or "power" Splunk roles could run arbitrary Search Processing Language (SPL) searches with |
| CVE-2026-131181 | 7.1 | n/a | In Splunk Enterprise versions below 10.4.5, 10.2.9, 10.0.12, and 9.4.16, a user who does not hold the "admin" or "power" Splunk roles could use Data Model Acceleration to run malicious Search Processi |
| CVE-2026-131198 | 7.1 | n/a | In Splunk Enterprise Security versions below 8.7.0, a user that holds a role with the mc_view_im_data capability could cause the Mission Control incident mapping Representational State Transfer (REST) |
| CVE-2026-131245 | 7.1 | n/a | In Splunk SOAR versions below 8.8.0, a user with edit permission for the container label of a pending external prompt could obtain the external prompt link through the Representational State Transfer  |
| CVE-2026-131262 | 7.1 | n/a | In Splunk SOAR versions below 8.8.0, an authenticated user who can view and edit containers in at least one container label could create artifacts with parent relationships to containers and artifacts |
| CVE-2026-131303 | 7.1 | n/a | In Splunk AI Assistant versions below 2.0.0, a user who does not hold the "admin" or "power" Splunk roles could obtain limited information about indexes and data sources outside their authorized scope |
| CVE-2026-133306 | 7.0 | n/a | VideoLAN libaacs 0.7.0 through 0.12.0 on non-macOS, non-Windows builds contains stack-based buffer overflows in aacs_resolve_path() in src/file/path.c from length checks against the wrong buffer. Loca |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-w3jh-xm4q-8vq6 | CVE-2026-133624 | medium | SCTP protocol dissector heap disclosure in 4.6.0 to 4.6.9 and 4.4.0 to 4.4.19 might enable denial... |
| GHSA-8fpf-7482-h8rm | CVE-2026-131712 | medium | Improper Neutralization of Script-Related HTML Tags in a Web Page (Basic XSS) vulnerability in... |
| GHSA-c87q-r995-wcp4 | CVE-2026-133503 | low | A security vulnerability has been detected in ModelCloud GPTQModel up to 7.6.0. Affected by this... |
| GHSA-575f-w94v-9fwf | CVE-2026-133500 | high | A vulnerability was identified in Gladys Assistant up to 4.71.0. This affects an unknown function... |
| GHSA-37mf-jx94-7vmr | CVE-2026-133626 | high | FlowIntel contains a resource exhaustion vulnerability in its file-to-note conversion feature.... |
| GHSA-r356-43w5-vp7v | CVE-2026-131769 | medium | Missing Authorization vulnerability in Liquid Web / StellarWP The Events Calendar the-events... |
| GHSA-fwgc-xcgm-2j42 | CVE-2026-133501 | high | A security flaw has been discovered in Gladys Assistant up to 4.71.0. This impacts an unknown... |
| GHSA-p75g-wrqq-wfp3 | CVE-2026-131757 | medium | Insertion of Sensitive Information Into Sent Data vulnerability in WProyal Royal Elementor Addons... |
| GHSA-9rhx-m7g8-6q4v | CVE-2026-133531 | medium | A flaw was found in cluster-network-operator. The OVN IPsec certificate signer does not verify... |
| GHSA-fjc9-gw6c-7x47 | CVE-2026-131711 | medium | Missing Authorization vulnerability in ThemeGrill Masteriyo - LMS learning-management-system... |
| GHSA-6mrc-mrq8-m7rf | CVE-2026-133622 | low | A flaw was found in certmonger. This vulnerability allows a malicious certificate authority or an... |
| GHSA-6fc8-jqpq-w5pf | CVE-2026-131723 | medium | Missing Authorization vulnerability in Liquid Web / StellarWP Event Tickets event-tickets allows... |
| GHSA-fwrf-j2gw-rwcp | CVE-2026-133625 | medium | iLBC audio codec crash in 4.6.0 to 4.6.9 and 4.4.0 to 4.4.19 allows denial of service |
| GHSA-cm4f-9839-5qrh | CVE-2026-131770 | medium | Missing Authorization vulnerability in Liquid Web / StellarWP The Events Calendar the-events... |
| GHSA-86xr-29wc-78m6 | CVE-2026-133627 | medium | flowintel contains a log injection vulnerability in its case history (audit log) subsystem. The... |
| GHSA-w77q-w4mp-w2vx | CVE-2026-133502 | medium | A weakness has been identified in blinkospace blinko up to 1.8.8. Affected is an unknown function... |
| GHSA-cq92-qw9v-jqq2 | CVE-2026-133620 | medium | Flowintel's template repository subsystem did not adequately constrain file access to the... |
| GHSA-3726-953v-6597 | CVE-2026-131768 | medium | Improper Neutralization of Script-Related HTML Tags in a Web Page (Basic XSS) vulnerability in... |
| GHSA-2g8g-q5c4-w9c6 | CVE-2026-131710 | medium | Missing Authorization vulnerability in ThemeGrill Masteriyo - LMS learning-management-system... |
| GHSA-mgw9-cq76-7wp3 | CVE-2026-131717 | medium | Missing Authorization vulnerability in Liquid Web / StellarWP Event Tickets event-tickets allows... |
| GHSA-7248-gw96-fj36 | CVE-2026-131734 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-cq3v-hr8c-mff4 | CVE-2026-131725 | medium | Missing Authorization vulnerability in ExpressTech Quiz And Survey Master quiz-master-next allows... |
| GHSA-fh24-w4w2-4ghq | CVE-2026-131716 | medium | Cross-Site Request Forgery (CSRF) vulnerability in Awesomemotive Charitable charitable allows... |
| GHSA-v8g3-xvv4-fp23 | CVE-2026-131713 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-vh25-7mpx-mx66 | CVE-2026-131764 | medium | Missing Authorization vulnerability in Brainstorm Force SureCart surecart allows Exploiting... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| wakao.co.jp | blackout | JP | 2026-11-20T05:35:29.384945+00:00 |
| Inlandboatmen’s Union of the Pacific — Marine Division of the ILWU | spacebears | US | 2026-11-20T03:55:59.679700+00:00 |
| SDJ Design Engineering Limited | spacebears | GB | 2026-11-20T03:55:17.506791+00:00 |
| Rise | A Community Service Partnership (also known as NJ Rise) | spacebears | US | 2026-11-20T03:54:35.732189+00:00 |
| Epoch Residential | spacebears | US | 2026-11-20T03:53:54.262478+00:00 |
| Boeing | incransom | US | 2026-11-20T03:46:28.600219+00:00 |
| FIFA (Fédération Internationale de Football Association) | Handsome Boy Hacking Club | CH | 2026-11-20T01:22:03.955012+00:00 |
| Rudolph F. Jass, Jr., PLLC | rhysida | US | 2026-11-19T22:18:36.758069+00:00 |
| J... W... | SilentRansomGroup |  | 2026-11-19T22:03:16.629357+00:00 |
| AutoZone, Inc. | Inception | US | 2026-11-19T21:52:49.672867+00:00 |
| Kutak Rock LLP | SilentRansomGroup | US | 2026-11-19T17:56:03.824084+00:00 |
| UCHealth | Handsome Boy Hacking Club | US | 2026-11-19T17:17:48.710775+00:00 |
| Smith & Wesson | Handsome Boy Hacking Club | US | 2026-11-19T17:17:11.704733+00:00 |
| MedMira Inc | Deadlock | CA | 2026-11-19T14:51:13.702848+00:00 |
| Rober & Phillips | rhysida |  | 2026-11-19T14:22:55.397840+00:00 |
| SHOPBOT TOOLS, INC. | SoulGroup | US | 2026-11-19T14:15:17.233872+00:00 |
| Noble Inc. | SoulGroup | US | 2026-11-19T14:14:31.663533+00:00 |
| United Medical Doctors | SoulGroup | US | 2026-11-19T14:13:46.595227+00:00 |
| METO Systems | SoulGroup | US | 2026-11-19T14:13:00.227553+00:00 |
| Nephrology Associates | SoulGroup | US | 2026-11-19T14:12:14.726197+00:00 |

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
| 62.60.130.148 | 10 |
| 18.218.118.203 | 9 |
| 77.239.124.252 | 9 |
| 2.57.121.25 | 8 |
| 2.57.121.112 | 8 |
| 3.129.187.38 | 8 |
| 35.210.1.5 | 8 |
| 45.148.10.5 | 8 |
| 45.148.10.141 | 8 |
| 45.148.10.151 | 8 |
| 45.156.87.189 | 8 |
| 62.60.130.219 | 8 |
| 64.62.197.32 | 8 |
| 64.62.197.137 | 8 |
| 66.132.172.41 | 8 |
| 66.132.172.97 | 8 |
| 66.132.172.128 | 8 |
| 66.132.172.137 | 8 |

### OpenPhish (live phishing URLs)
- https://argocts.com/wwa/pplch/index.php
- https://ozanguner.com/BinasaIndustial/Access/
- https://mydpd.pmsml.cc/track-ch
- https://mydpd.mzqdp.xyz/track-ch
- https://mydpd.hwtrd.top/track-ch
- https://info-recap-2.kimi.page/
- https://mydpd.kiaxf.xyz/track-ch
- https://jardinsdubandiat-onmicrosoft.click/
- https://dhyehdhje.jimdofree.com/
- http://hiremedicals.com/contact/login.php
- https://upgov.net/images/z1dpeth/-/louwhan1/pages/login.php
- http://chipper-profiterole-06b105.netlify.app/
- https://bas.api.usps.zda.com/
- https://f005.backblazeb2.com/file/olaxxx/bellwebmailcadch4se.html
- http://akarshagrahari143.github.io/web-clg-Amazon
- https://vinted.id653655.shop/219249488
- https://drumhilldentalcom.qusteto-document-qpr-39948589.workers.dev/
- http://login-att-verification-page.weeblysite.com/
- https://cn.81mbetx.com/home/register/
- https://aaa-105662.square.site/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://vercel.com/login?next=%2Fsso-api%3Furl%3Dhttps%253A%252F%252Finterface-uniswap.vercel.app%252F%26nonce%3Da8ed82915c06f6adeb36722c45ada3fd7ff571729ed20066f928a0c3e60b9313 |
| N/A | https://thitheohuuco.com/ |
| N/A | https://away.vk.ru/away.php?rh=78ce9d78-4b7c-4aa2-b072-ea32dafc6b07 |
| N/A | https://site-wio9d341m.godaddysites.com/ |
| N/A | https://better.com.np/wp-login.php |
| N/A | https://away.vk.ru/away.php?rh=aa265f8b-d559-404e-ab44-083297dcd772 |
| N/A | http://43.156.0.130/v3/signin/identifier?amp;continue=https://accounts.google.com/&amp;followup=https://accounts.google.com&passive=1209600&flowName=GlifWebSignIn&flowEntry=ServiceLogin&dsh=S1461334172:1795169330700610 |
| N/A | https://away.vk.ru/away.php?rh=72b07dde-04b2-440c-b735-616d67137fc9 |
| N/A | https://away.vk.ru/away.php?rh=8fa549b7-d09d-447b-8645-6a997396c28b |
| N/A | https://pageseuc1.actmkt.com/(S(rgnp5i4d5q11hel42c3m0vcw))/l/c5X8MfZz6j9Y7Fto3LAd |
| N/A | https://itsme-nlfr.myvnc.com/ |
| N/A | https://away.vk.ru/away.php?rh=28ef0053-1dec-4d63-be76-6a0a2b46f051 |
| N/A | https://away.vk.ru/away.php?rh=b6ffa34d-2bea-4c22-a539-e91ab3e31442 |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AaSxoQyQ_ZSuXpSvue0UfKrOXnU6mQAuN0RcLmvWGTqSCzhKlOsPyDT7wQQH6ra2Rhdw1PE87iTB&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBglc5ueXLbDmstsh_I0f7XRvVffn2umwZTFGioYpLBVhObEZW7YAHQUo5XjB-poq_j8JruSg0&dsh=S1462304809%3A1795168043190204 |
| N/A | https://away.vk.ru/away.php?rh=958cbfb4-26bb-48e5-9993-c2e877500369 |
| N/A | https://flat-bread-04ca.cloudflareaccess.com/cdn-cgi/access/login/vertiv-command-center.pages.dev?kid=617efb6eb0445e77d08421b7c2075c08ed7302463271c62a28d702c82772462a&meta=eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiIsImtpZCI6IjEyY2U5NjlmMDk3YjUyNjliNjllZjA0N2EwMjBiZGI2NGMwMTc5NjMwNzE3MzJhMWJjODg2NjJiNGUxYzJjY2IifQ.eyJ0eXBlIjoibWV0YSIsImF1ZCI6IjYxN2VmYjZlYjA0NDVlNzdkMDg0MjFiN2MyMDc1YzA4ZWQ3MzAyNDYzMjcxYzYyYTI4ZDcwMmM4Mjc3MjQ2MmEiLCJob3N0bmFtZSI6InZlcnRpdi1jb21tYW5kLWNlbnRlci5wYWdlcy5kZXYiLCJyZWRpcmVjdF91cmwiOiIvIiwic2VydmljZV90b2tlbl9zdGF0dXMiOmZhbHNlLCJpc193YXJwIjpmYWxzZSwiaXNfZ2F0ZXdheSI6ZmFsc2UsImV4cCI6MTc5NTE2ODEzNSwibmJmIjoxNzk1MTY3ODM1LCJpYXQiOjE3OTUxNjc4MzUsImF1dGhfc3RhdHVzIjoiTk9ORSIsIm10bHNfYXV0aCI6eyJjZXJ0X2lzc3Vlcl9kbiI6IiIsImNlcnRfc2VyaWFsIjoiIiwiY2VydF9pc3N1ZXJfc2tpIjoiIiwiY2VydF9wcmVzZW50ZWQiOmZhbHNlLCJjb21tb25fbmFtZSI6IiIsImF1dGhfc3RhdHVzIjoiTk9ORSJ9LCJyZWFsX2NvdW50cnkiOiJVUyIsImFwcF9zZXNzaW9uX2hhc2giOiIxNDlkZDc1MDc1YzJlNjE0MmFjMzlkMTU4MjRkNGQyYWY5MTM1NjQ3ZTI4YzI1MGYyN2FlYWEzZWE5NjQ1ZGUzIn0.maO337e5Znu8s3pTvApxHhoeCcQp-y7KwvxfHuC9jsLX5Hg6FLYDe8kyoGPIRNxgnXT4taaQUhk_nlhkokqucgFKBs_XEOQbLjm2h98dKkLXddD9BW_FYZs0fQfXWtamsun6yg__9kWP3kpp7JSEBCNL9MS88S37drfOOVgnVEeqOGFJ0-kluBISwVQKLWAQUfoTwaQ9P3QrGy5-c0wymUrqpBUTSxwjpH9HhZGJ6Cq77az8Tn49sJgfmY-qPhuExFUVIlaEA9w4O64DGy94Cl72qvMlVozEBSl1wbjyyNoqRHCGlp50qe5JJfR1H71ziGLXyfVTBZOYmz8YHMGYtw&redirect_url=%2F |
| N/A | https://gfc.snd-esolutions.com/redirect/?username=redacted@abuse.ionos.com |
| N/A | https://www.instagram-login.desireblueuniforms.com/ |
| N/A | https://away.vk.ru/away.php?rh=e41a6f43-6705-4a14-8b59-fb13181a37d7 |
| N/A | https://away.vk.ru/away.php?rh=7ede16d7-3a61-460f-a0bd-f44084acab9d |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
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
| 4815c51736189179ad892b69abe7f44560919e45 | RevStealer C&C |

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
- 1.12.234.27
- 1.12.252.163
- 1.13.22.101
- 1.13.79.149
- 1.14.240.247
- 1.164.194.127
- 1.178.213.254
- 1.183.196.24
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
- 1.12.229.231
- 1.14.3.170
- 1.15.14.29
- 1.189.41.213
- 1.20.151.114
- 1.20.174.201
- 1.208.108.242
- 1.213.214.233
- 1.214.29.155
- 1.224.163.125
- 1.24.16.10
- 1.24.16.100
- 1.24.16.101
- 1.24.16.11
- 1.24.16.114
- 1.24.16.116
- 1.24.16.125
- 1.24.16.128
- 1.24.16.131
- 1.24.16.140

## News (last ~36h, across outlets)
### The Hacker News
- [China-Linked Hackers Exploit Critical VMware vCenter Zero-Day to Gain Admin Access and Steal Data](https://thehackernews.com/2026/11/china-linked-hackers-exploit-critical.html)
- [ROMULUS ClickFix Attacks Deliver RAT That Can Spy on Users and Control PCs](https://thehackernews.com/2026/11/romulus-clickfix-attacks-deliver-rat.html)
- [New Unpatched Windows 0-Day FastUnlock Lets Someone Holding a Locked PC Run Programs on It](https://thehackernews.com/2026/11/new-unpatched-windows-0-day-fastunlock.html)
- [ThreatsDay: GPT-6.2 Jailbreak Flaws, BubbleLoader PNG Malware, $500M Ransom Demands + 17 More Stories](https://thehackernews.com/2026/11/threatsday-gpt-62-jailbreak-flaws.html)
- [phpAfterShell Explained: How Hackers Could Turn a PHP Session Flaw Into Code Execution](https://thehackernews.com/2026/11/phpaftershell-explained-how-hackers.html)
- [PHP Fixes 7 Critical Flaws, Including Bugs That Could Allow Remote Code Execution](https://thehackernews.com/2026/11/php-fixes-7-critical-flaws-including.html)
- [Critical VMware vCenter Zero-Day Flaw Lets Network Attackers Bypass Authentication](https://thehackernews.com/2026/11/critical-vmware-vcenter-flaw-cvss-98.html)
- [Drupal Patches Critical Installer Flaw That Could Give Unauthenticated Attackers Control of Sites](https://thehackernews.com/2026/11/drupal-patches-critical-installer-flaw.html)
- [Everything Is a Web Application, Including Your Firewall](https://thehackernews.com/2026/11/everything-is-web-application-including.html)
- [Hackers Breach N-able Cloud Server, Disrupting Email Security Management Across 3 Regions](https://thehackernews.com/2026/11/n-able-confirms-hackers-accessed-cloud.html)
- [Ruby Ships Fixes for 7 Flaws, Including Critical Ruby2Shell, Said to Hit Default Rails Apps Pre-Auth](https://thehackernews.com/2026/11/ruby-releases-fixes-for-7-regex-and.html)
- [Researcher Demonstrates Database RCE Exploits Affecting PostgreSQL, MySQL and Oracle](https://thehackernews.com/2026/11/researcher-demonstrates-database-rce.html)
- [CISA Warns of 4 Exploited Flaws Linked to Ransomware, Cryptomining, and LLMjacking Attacks](https://thehackernews.com/2026/11/cisa-warns-of-4-exploited-flaws-linked.html)
- [PHP Warns of Critical Security Flaws Affecting All Supported Versions, Fixes Coming November 19](https://thehackernews.com/2026/11/php-warns-of-critical-security-flaws.html)

### BleepingComputer
- [F5 releases emergency patches for critical BIG-IP RCE flaws](https://www.bleepingcomputer.com/news/security/f5-releases-emergency-patches-for-critical-big-ip-rce-flaws/)
- [Windows 11 KB5132057 update released with 28 changes and fixes](https://www.bleepingcomputer.com/news/microsoft/windows-11-kb5132057-update-released-with-28-changes-and-fixes/)
- [VMware patches vCenter zero-day exploited in attacks since September](https://www.bleepingcomputer.com/news/security/vmware-patches-vcenter-zero-day-exploited-in-attacks-since-september/)
- [Hackers steal data of 1.6 million SBC Medical Group customers](https://www.bleepingcomputer.com/news/security/hackers-steal-data-of-16-million-sbc-medical-group-customers/)
- [ASUS warns of critical hard-coded key flaw in Control Center Express](https://www.bleepingcomputer.com/news/security/asus-warns-of-critical-hard-coded-key-flaw-in-control-center-express/)
- [Transport for London breach exposes 265,000 Oyster card users' data](https://www.bleepingcomputer.com/news/security/transport-for-london-breach-exposes-265-000-oyster-card-users-data/)
- [PHP security updates fix 18 flaws, including critical RCE bugs](https://www.bleepingcomputer.com/news/security/php-security-updates-fix-18-flaws-including-critical-rce-bugs/)
- [Five warning signs of ransomware breach before encryption or data theft](https://www.bleepingcomputer.com/news/security/five-warning-signs-of-ransomware-breach-before-encryption-or-data-theft/)
- [Critical NGINX ‘NGINX2Root’ bugs let attackers hijack servers](https://www.bleepingcomputer.com/news/security/critical-nginx-nginx2root-bugs-let-attackers-hijack-servers/)
- [Drupal patches critical RCE flaw, warns exploits may surface quickly](https://www.bleepingcomputer.com/news/security/drupal-patches-critical-rce-flaw-warns-exploits-may-surface-quickly/)
- [Microsoft tests new Edge Lockdown Mode that disables GPU APIs](https://www.bleepingcomputer.com/news/microsoft/microsoft-tests-new-edge-lockdown-mode-that-disables-gpu-apis/)
- [Microsoft confirms app installation, launch issues after hotpatch](https://www.bleepingcomputer.com/news/microsoft/microsoft-confirms-app-installation-launch-issues-after-hotpatch/)
- [NVIDIA investigating Gentlemen ransomware breach claims](https://www.bleepingcomputer.com/news/security/nvidia-investigating-gentlemen-ransomware-breach-claims/)
- [Ukraine, FBI arrest ransomware gang members tied to $40M in ransoms](https://www.bleepingcomputer.com/news/security/ukraine-fbi-arrest-ransomware-gang-members-tied-to-40m-in-ransoms/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [Qwen Incidents Show Self-Hosted AI Models Need Stronger Steering](https://www.darkreading.com/cyber-risk/qwen-incidents-self-hosted-ai-models-stronger-steering)
- [Second Norwegian Energy Company Breached in Two Days](https://www.darkreading.com/cyberattacks-data-breaches/second-norwegian-energy-company-breached)
- [Critical PHP Flaws Allow Code Execution, But Don't Panic 'PHP2Shell'-Style](https://www.darkreading.com/application-security/critical-php-flaws-code-execution-panic-php2shell)
- [Navigating Vulnerability Hysteria in the AI Era](https://www.darkreading.com/vulnerabilities-threats/navigating-vulnerability-hysteria-ai-era)
- [Why Holiday Security Can't Wait for Black Friday](https://www.darkreading.com/cybersecurity-operations/why-holiday-security-cant-wait-black-friday)
- [Africa Retakes Top Spot as Most Attacked Region, Led by Nigeria Surge](https://www.darkreading.com/threat-intelligence/africa-top-spot-most-attacked-region-nigeria-surge)

### SecurityWeek
- [European Commission Confirms AI-Assisted Cyberattack Disrupted Services](https://www.securityweek.com/european-commission-confirms-ai-assisted-cyberattack-disrupted-services/)
- [Ruby Patches Ruby2Shell Vulnerability That Could Lead to RCE](https://www.securityweek.com/ruby-patches-ruby2shell-vulnerability-that-could-lead-to-rce/)
- [N-able Blames Service Disruption on Cyberattack](https://www.securityweek.com/n-able-blames-service-disruption-on-cyberattack/)
- [JPMorgan, Visa, Mastercard Cite Third-Party Incidents Amid Data Leak](https://www.securityweek.com/jpmorgan-visa-mastercard-cite-third-party-incidents-amid-data-leak/)
- [Newly Patched VMware vCenter Flaw Exploited as Zero-Day by Chinese APT](https://www.securityweek.com/newly-patched-vmware-vcenter-flaw-exploited-as-zero-day-by-chinese-apt/)
- [PHP Patches Seven Critical RCE Vulnerabilities](https://www.securityweek.com/php-patches-seven-critical-rce-vulnerabilities/)
- [Nvidia Responds to Gentlemen Ransomware Claim](https://www.securityweek.com/nvidia-responds-to-gentlemen-ransomware-claim/)
- [Hackers Exploit Cisco Expressway Vulnerability Soon After PoC Release](https://www.securityweek.com/hackers-exploit-cisco-expressway-vulnerability-soon-after-poc-release/)
- [StepSecurity Secures $20 Million to Expand Supply Chain Protection](https://www.securityweek.com/stepsecurity-secures-20-million-to-expand-supply-chain-protection/)
- [Critical Apache Roller, Axis Vulnerabilities Exploited in Attacks](https://www.securityweek.com/critical-apache-roller-axis-vulnerabilities-exploited-in-attacks/)

### The Record
- [Lawmakers launch new AI safety caucus amid rising security concerns](https://therecord.media/lawmakers-launch-new-ai-safety-caucus)
- [DOJ, DHS partner on new unit tackling scams and cybercrime](https://therecord.media/doj-dhs-partner-on-new-unit-tackling-scams-cybercrime)
- [CISA nominee LoSapio vows to bolster cyber defenses while denying Jan. 6 Capitol attack](https://therecord.media/cisa-losapio-nomination-trump)
- [UK court confirms British government served Apple with secret encryption notice](https://therecord.media/apple-uk-encryption-notice)
- [European Commission confirms cyberattack, says hackers used AI tool](https://therecord.media/european-commission-confirms-cyberattack-using-ai)

### Infosecurity Magazine
- [Suspected North Korea-Aligned Group Hides C2 on Solana Blockchain](https://www.infosecurity-magazine.com/news/overlord-rat-solana-blockchain-c2/)
- [CyberPower PowerPanel Exploited to Run Malicious Code on Domain Controller](https://www.infosecurity-magazine.com/news/ups-software-abused-domain/)
- [PHP Releases Patches to Fix 18 Vulnerabilities](https://www.infosecurity-magazine.com/news/php-releases-patches-fix-18/)
- [European Commission Confirms AI-Driven Cyber-Attack Took Systems Offline](https://www.infosecurity-magazine.com/news/commission-ai-attack-systems/)
- [TfL Warns 265,000 Photocard Customers May Have Had Personal Data Exposed](https://www.infosecurity-magazine.com/news/tfl-customers-personal-data-exposed/)
- [A Fifth of UK Employees Share Passwords with AI](https://www.infosecurity-magazine.com/news/fifth-uk-employees-share-passwords/)
- [Rakuten Securities Breach Could Impact 15 Million Customers](https://www.infosecurity-magazine.com/news/rakuten-securities-breach-15/)

### CyberScoop
- [Sean Cairncross out as national cyber director](https://cyberscoop.com/sean-cairncross-out-national-cyber-director/)
- [Dems call CISA nominee ‘disqualified’ after nomination hearing](https://cyberscoop.com/michael-losapio-cisa-confirmation-hearing/)

### Cisco Talos
- [The internet needs a nap (and you do, too)](https://blog.talosintelligence.com/the-internet-needs-a-nap-and-you-do-too/)

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
- [ARMORY CASTLE Exploits vSphere](https://cloud.google.com/blog/topics/threat-intelligence/armory-castle-exploits-vsphere/)

### SANS Internet Storm Center
- [ISC Stormcast For Friday, November 20th, 2026 https://isc.sans.edu/podcastdetail/10188, (Fri, Nov 20th)](https://isc.sans.edu/diary/rss/33538)
- [ISC Stormcast For Thursday, November 19th, 2026 https://isc.sans.edu/podcastdetail/10186, (Thu, Nov 19th)](https://isc.sans.edu/diary/rss/33536)
- [Treat Your Honeypot Analysis Like Code: Git, Pull Requests and a Human Gate for AI &#x5b;Guest Diary&#x5d;, (Wed, Nov 18th)](https://isc.sans.edu/diary/rss/33534)

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
- [Java4Shell](https://fortiguard.fortinet.com/threat-signal-report/6668)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal