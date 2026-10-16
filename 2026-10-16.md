# Winjit Daily TI Digest — 2026-10-16

_Auto-generated. Window: last ~24h. Fetched at 2026-10-16T08:00:56.123962+00:00Z_

**At a glance:** 1 new KEV · 78 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-21589 | Atlassian | Multiple Products | Atlassian Multiple Products Files or Directories Accessible to External Parties Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-110957 | 10.0 | n/a | A vulnerability has been found in Wavlink WL-WN530BE2-A up to M30BE2_V250604. The affected element is the function sub_12580 of the file api.cgi of the component Login Processing. The manipulation of  |
| CVE-2026-111281 | 9.8 | n/a | Jooan JA-A12 IP cameras with firmware 009_20171107 and 05.02.31.105 contain a remote code execution vulnerability that allows unauthenticated attackers to run root commands via hard-coded credentials. |
| CVE-2026-111322 | 9.8 | n/a | Archon 0.2.13 through 0.11.1 contains a missing authentication vulnerability that allows unauthenticated attackers to access the /api/* control API, which binds to 0.0.0.0 by default. Attackers with n |
| CVE-2026-111329 | 9.8 | n/a | JuggleIM im-server through 1.8.16 ships default administrator credentials admin/123456 that allow unauthenticated remote attackers to access the admin console on port 8090. Attackers can log in as adm |
| CVE-2026-104798 | 9.8 | n/a | The My Calendar – Accessible Event Manager plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 3.8.7. The public `mcs` GET parameter is reflected into post |
| CVE-2026-109219 | 9.8 | n/a | The Mang Board plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 2.4.4 via the mbw_file_upload function. This is due to missing file extension validatio |
| CVE-2026-109515 | 9.8 | n/a | The MailOptin – Popup, Optin Forms & Email Newsletters for Mailchimp, HubSpot, AWeber Etc. plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 1.2.78.6 Thi |
| CVE-2026-103768 | 9.8 | n/a | The ELEX WordPress HelpDesk & Customer Ticketing System plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 3.3.7 via the initMailPart function. This is d |
| CVE-2026-89079 | 9.8 | n/a | The Theme My Login plugin for WordPress is vulnerable to privilege escalation via account takeover in versions up to, and including, 7.2.1. This is due to the plugin not properly validating a user's i |
| CVE-2026-104730 | 9.8 | n/a | The Sunshine Photo Cart – Client Photo Gallery & Photo Proofing for Photographers plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 3.7.4 via deserializa |
| CVE-2026-111283 | 9.0 | n/a | BMC Helix Network Management on-prem before 26.3.01 contains an authentication bypass vulnerability that allows unauthenticated attackers to log in as the local administrator with any password when SA |
| CVE-2026-77931 | 8.8 | 1.0% | MoviePilot through 3.1.5 contains a command injection vulnerability that allows attackers to execute arbitrary OS commands by embedding malicious instructions in untrusted content processed through to |
| CVE-2026-111352 | 8.8 | n/a | ThinkCMF through 8.0.1 contains an incorrect authorization vulnerability in RestAdminBaseController that allows restricted backend administrators to call every admin REST API endpoint because Auth::ch |
| CVE-2026-111380 | 8.8 | n/a | FreeRDP from 3.29.0 before 3.32.0 contains an integer overflow in the Apple audin backends (audin_mac.m, audin_ios.m), which compute the audio queue buffer size as FramesPerPacket * 2 * nChannels in U |
| CVE-2026-111382 | 8.8 | n/a | FreeRDP before 3.32.0 contains a client-side heap out-of-bounds write vulnerability in general_LumaToYUV444 and general_ChromaV2ToYUV444 that allows malicious RDP servers to corrupt client memory. Att |
| CVE-2026-85659 | 8.8 | n/a | The PilotPress plugin for WordPress is vulnerable to Privilege Escalation via Account Takeover in all versions up to, and including, 2.0.43. The vulnerability exists because the `update_cc_details()`  |
| CVE-2026-92115 | 8.8 | n/a | The WP Photo Album Plus plugin for WordPress is vulnerable to authenticated Command Injection in all versions up to, and including, 9.3.02.002 via the `value` parameter of the `update-photo` AJAX acti |
| CVE-2026-92553 | 8.8 | n/a | The YaySMTP – WP Mail SMTP with Email Logs, Tracking & Reports plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 2.7.7 via the putFile function. This is |
| CVE-2026-111282 | 8.2 | n/a | Driftregion iso14229 before 0.10.1 contains an integer wraparound in Handle_0x38_RequestFileTransfer that lets unauthenticated attackers bypass the file path length check. Attackers can send a short R |
| CVE-2026-104745 | 8.1 | n/a | The Customer Email Verification for WooCommerce plugin for WordPress is vulnerable to Privilege Escalation via the `alg_wc_ev_verify_email` parameter in versions up to, and including, 3.3.0. The vulne |
| CVE-2026-103895 | 8.1 | n/a | The miniOrange OTP Login, Verification and SMS Notifications plugin for WordPress is vulnerable to Authentication Bypass in versions up to, and including, 5.5.8 via the `mo_by_pass_login()` function.  |
| CVE-2026-109221 | 8.1 | n/a | The Groundhogg — CRM, Newsletters, and Marketing Automation plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation in the copy_file function in all vers |
| CVE-2026-109447 | 8.1 | n/a | The User Profile Builder – Beautiful User Registration Forms, User Profiles & User Role Editor plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 4.0.3 vi |
| CVE-2026-75941 | 8.0 | n/a | A potential vulnerability was reported in the Lenovo Legion Zone application, distributed exclusively in the Chinese market, that could allow an attacker on the same logical network to execute arbitra |
| CVE-2026-93953 | 8.0 | n/a | The Backuply – Backup, Restore, Migrate and Clone plugin for WordPress is vulnerable to SQL Injection via the Biographical Info field (second-order, via restore) in all versions up to, and including,  |
| CVE-2026-104932 | 8.0 | n/a | The Search Regex plugin for WordPress is vulnerable to PHP Object Injection in version 3.5 via deserialization of untrusted input in the replace_all function. This allows authenticated attackers, with |
| CVE-2026-104715 | 7.8 | n/a | A flaw was found in cifs-utils. This flaw allows an unprivileged local user to achieve privilege escalation. When a privileged service mounts a Common Internet File System (CIFS) share using a user-co |
| CVE-2026-111312 | 7.7 | n/a | OpenHealth through 0.2.0 contains a missing authentication and authorization vulnerability in the /api/health-data/[id] GET, PATCH and DELETE handlers that query records by id without session or autho |
| CVE-2026-111389 | 7.7 | n/a | Frappe HRMS 14.x before 14.38.2, 15.x before 15.64.0, and 16.x before 16.18.0 contains a SQL injection vulnerability in some endpoints caused by missing input validation. Any authenticated attacker, i |
| CVE-2026-109430 | 7.5 | 0.3% | Ellucian WebAdvisor 3.2 contains an unauthenticated XML External Entity (XXE) injection vulnerability that allows remote attackers to submit crafted XML POST requests to the /WebAdvisor/WebAdvisor end |
| CVE-2026-111160 | 7.5 | n/a | LightLLM through 1.2.0 contains a denial of service vulnerability that allows unauthenticated attackers to crash the inference worker by supplying the internal pd_kv_trans_params field to the /generat |
| CVE-2026-111224 | 7.5 | n/a | pfSense CE through 2.9.0 contains an OS command injection vulnerability in the OpenVPN openvpn.connect_async.sh script that allows authenticated VPN users to execute commands as root via crafted usern |
| CVE-2026-111277 | 7.5 | n/a | NivoCart through 2.5.1 contains a missing authorization vulnerability in the download() action of account/order that allows unauthenticated attackers to retrieve guest order invoices by supplying an o |
| CVE-2026-111279 | 7.5 | n/a | Dragonfly through 2.0.2 contains an unbounded memory allocation vulnerability that allows unauthenticated clients to exhaust memory by passing a negative COUNT to HRANDFIELD, ZRANDMEMBER or SRANDMEMBE |
| CVE-2026-111378 | 7.5 | n/a | FreeRDP from 3.0.0 before 3.32.0 contains an uncontrolled resource consumption vulnerability in parse_nla_mode_pdu that allows unauthenticated attackers to exhaust server memory. Attackers can complet |
| CVE-2026-103525 | 7.5 | n/a | The FluentCart A New Era of eCommerce – Faster, Lighter, and Simpler plugin for WordPress is vulnerable to Insecure Direct Object Reference in all versions up to, and including, 1.7.0 via the 'order_i |
| CVE-2026-107659 | 7.5 | n/a | The Modula Image Gallery – Photo Grid & Video Gallery plugin for WordPress is vulnerable to Sensitive Information Exposure in all versions up to, and including, 3.0.11 via the 'id (post ID in /wp-json |
| CVE-2026-107746 | 7.5 | n/a | The FunnelKit – Funnel Builder for WooCommerce Checkout plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 3.16.0.6 This is due to the plugin not properly |
| CVE-2026-109400 | 7.5 | n/a | The InstaWP Connect – 1-click WP Staging & Migration plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 0.1.4.1 This is due to the plugin registering its  |
| CVE-2026-110590 | 7.5 | n/a | The Klarna for WooCommerce plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 4.13.3 This is due to the plugin not properly verifying that a user is autho |
| CVE-2026-111114 | 7.5 | n/a | The Nexter Extension – Security, Performance, Code Snippets & Site Toolkit plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 4.7.11 The vulnerability exi |
| CVE-2026-103896 | 7.5 | n/a | The 10Web Booster – Website speed optimization, Cache & Page Speed optimizer plugin for WordPress is vulnerable to a limited file write via path traversal in versions up to, and including, 2.34.5 This |
| CVE-2026-111280 | 7.4 | n/a | snap7 through 1.4.3 contains an out-of-bounds write vulnerability in TSnap7MicroClient::opReadArea() that allows malicious S7 peers to overflow client buffers via an unchecked DataLength field. Rogue  |
| CVE-2026-111356 | 7.4 | n/a | MacCMS v10 through 2026.1000.4056 does not limit attempts on the six-digit password recovery code, allowing unauthenticated attackers to take over member accounts. Attackers knowing a victim's email o |
| CVE-2026-111210 | 7.3 | n/a | A vulnerability was determined in bitcoinj up to 0.17. Affected is the function url.openConnection of the file PaymentSession.java of the component Payment Request Handler. Executing a manipulation of |
| CVE-2026-92629 | 7.3 | n/a | A potential improper authorization vulnerability was reported in Lenovo Baiying PC Client, distributed exclusively in the Chinese market, that could allow a local authenticated user to execute arbitra |
| CVE-2026-111379 | 7.3 | n/a | FreeRDP before 3.32.0 contains a heap buffer overflow vulnerability in persistent_cache_read_entry_v3 that allows local attackers to corrupt memory by supplying a crafted v3 persistent cache file. Att |
| CVE-2026-111381 | 7.3 | n/a | FreeRDP before 3.32.0 contains a heap buffer overflow vulnerability in persistent_cache_read_entry_v2 that allows local attackers to corrupt heap memory via integer wraparound in bitmap size calculati |
| CVE-2026-111214 | 7.2 | n/a | Netgate pfSense CE 2.7.0 through 2.9.0 contains an OS command injection vulnerability that allows authenticated users with QinQ edit privilege to run commands by storing an unvalidated parent interfac |
| CVE-2026-111216 | 7.2 | n/a | Netgate pfSense CE through 2.9.0 contains an OS command injection vulnerability that allows authenticated users with gateway edit privileges to execute commands as root by injecting shell metacharacte |
| CVE-2026-111217 | 7.2 | n/a | Netgate pfSense CE through 2.9.0 contains an OS command injection vulnerability that allows authenticated users with Virtual IP edit privileges to execute commands as root by storing an unvalidated CA |
| CVE-2026-111226 | 7.2 | n/a | pfSense CE 2.4.5 through 2.9.0 contains an OS command injection vulnerability that allows authenticated WebGUI users with Advanced Admin Access privilege to execute commands as root via Login Protecti |
| CVE-2026-111229 | 7.2 | n/a | pfSense CE 2.7.0 through 2.9.0 contains a command injection vulnerability in services_captiveportal_hasync.php that allows users with only the Captive Portal HA privilege to execute commands as root.  |
| CVE-2026-111231 | 7.2 | n/a | Netgate pfSense CE through 2.9.0 contains an authorization bypass vulnerability that allows read-only WebGUI users to replace config.xml because config_restore() and config_install() ignore the 'User  |
| CVE-2026-111366 | 7.2 | n/a | cool-admin-midway through 8.0.0 contains an authorization bypass vulnerability that allows department-limited admins to manage users outside their departments by supplying arbitrary user ids. Attacker |
| CVE-2026-107758 | 7.2 | n/a | The Colibri Page Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 1.0.390 due to insufficient input sanitizat |
| CVE-2026-109207 | 7.2 | n/a | The RSS Aggregator by Feedzy – Feed to Post, Autoblogging, News & YouTube Video Feeds Aggregator plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'media:thumbnail@url' paramet |
| CVE-2026-109990 | 7.2 | n/a | The Flying Scripts: Delay JavaScript to Improve Site Speed & Performance plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and includ |
| CVE-2026-97339 | 7.2 | n/a | The Complianz GDPR/CCPA Cookie Consent Banner plugin for WordPress is vulnerable to Stored Cross-Site Scripting via Comment Content via yotu-wp Cookie-Blocker Filter in all versions up to, and includi |
| CVE-2026-109998 | 7.2 | n/a | The Mang Board plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'content' parameter in all versions up to, and including, 2.4.3 due to insufficient input sanitization and outp |
| CVE-2026-100186 | 7.2 | n/a | The User Profile Builder – Beautiful User Registration Forms, User Profiles & User Role Editor plugin for WordPress is vulnerable to Stored Cross-Site Scripting via First Name Field in all versions up |
| CVE-2026-103999 | 7.2 | n/a | The Ultra Addons for Contact Form 7 plugin for WordPress is vulnerable to Stored Cross-Site Scripting via File Upload in all versions up to, and including, 3.5.54 due to insufficient input sanitizatio |
| CVE-2026-104000 | 7.2 | n/a | The Simply Schedule Appointments plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'status' parameter in all versions up to, and including, 1.6.12.35 due to insufficient input  |
| CVE-2026-107764 | 7.2 | n/a | The SiteOrigin CSS plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via the 'url (comment_author_url)' parameter in all versions up to, and including, 1.6.7 due to insuffici |
| CVE-2026-109232 | 7.2 | n/a | The Salon Booking System – Appointment Booking for Salons, Barbershops & Spas plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'sln[<checkout-field-key>]' parameter in all ver |
| CVE-2026-109513 | 7.2 | n/a | The NotificationX – FOMO, Live Sales Notification, WooCommerce Sales Popup, GDPR, Social Proof, Announcement Banner & Floating Notification Bar plugin for WordPress is vulnerable to Stored Cross-Site  |
| CVE-2026-111122 | 7.2 | n/a | The SiteOrigin CSS plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via the 'href' parameter in all versions up to, and including, 1.6.7 due to insufficient input sanitizati |
| CVE-2026-89051 | 7.2 | n/a | The WP Ghost (Hide My WP Ghost) – Security & Firewall plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'replaceHeadersAndTags' function in versions up to, and including, 7.0.1 |
| CVE-2026-95686 | 7.2 | n/a | The Opti-Behavior – Self-Hosted Heatmaps, Session Recordings, Funnels, A/B Testing & Smart Insights plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via the 'targetUrl' para |
| CVE-2026-95809 | 7.2 | n/a | The Opti-Behavior – Self-Hosted Heatmaps, Session Recordings, Funnels, A/B Testing & Smart Insights plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via 'country_name' Locat |
| CVE-2026-96570 | 7.2 | n/a | The Schema & Structured Data for WP & AMP plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'saswp_review_text' parameter in all versions up to, and including, 1.67 due to insu |
| CVE-2026-107768 | 7.2 | n/a | The TranslatePress – Translate Multilingual sites with AI Translation plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including |
| CVE-2026-109193 | 7.2 | n/a | The HivePress – Business Directory, Listings & Classified Ads Plugin plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the '<custom user attribute slug> (e.g. hp_custom_link)' para |
| CVE-2026-110701 | 7.2 | n/a | The CP Multi View Events Calendar plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'CalendarTitle' parameter in all versions up to, and including, 1.4.42 due to insufficient i |
| CVE-2026-97640 | 7.2 | n/a | The WPConsent – Cookie Banner & Cookie Consent for Privacy Compliance (GDPR / CCPA / EU Compliance Cookie Notice) plugin for WordPress is vulnerable to Stored Cross-Site Scripting via Comment Content  |
| CVE-2026-111359 | 7.1 | n/a | CRMEB 5.6.1 through 6.0.0 contains an insecure direct object reference vulnerability that allows authenticated storefront users to read and claim other users' orders via the gift-order API. Attackers  |
| CVE-2026-111369 | 7.1 | n/a | ClassroomIO through 1.0.0 contains an incorrect authorization vulnerability in the PUT and DELETE /:lessonId lesson routes that allows any course member, including students, to modify lessons. Authent |
| CVE-2026-84823 | 7.1 | n/a | A flaw was found in WildFly. A user with the `Monitor` role, which is the lowest standard Role-Based Access Control (RBAC) role, can exploit a path traversal vulnerability in the `take-snapshot` opera |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-cmj8-gm9j-p86q | CVE-2026-96570 | high | The Schema & Structured Data for WP & AMP plugin for WordPress is vulnerable to Stored Cross-Site... |
| GHSA-gc4h-w8gx-jfq5 | CVE-2026-95809 | high | The Opti-Behavior – Self-Hosted Heatmaps, Session Recordings, Funnels, A/B Testing & Smart... |
| GHSA-q46r-82q7-hj69 | CVE-2026-88963 | medium | The Tutor LMS – eLearning and online course solution plugin for WordPress is vulnerable to DOM... |
| GHSA-v32q-5f5q-9x8f | CVE-2026-89079 | critical | The Theme My Login plugin for WordPress is vulnerable to privilege escalation via account... |
| GHSA-g9x2-j2vc-fcrr | CVE-2026-109232 | high | The Salon Booking System – Appointment Booking for Salons, Barbershops & Spas plugin for... |
| GHSA-x53h-w4xx-wqx7 | CVE-2026-95686 | high | The Opti-Behavior – Self-Hosted Heatmaps, Session Recordings, Funnels, A/B Testing & Smart... |
| GHSA-px2j-96c7-vxc7 | CVE-2026-111458 | medium | The fanx_fingerprint function in ssl/sslxprint.c of ssldump allocates a heap buffer for... |
| GHSA-9q7f-9qf7-62pg | CVE-2026-93767 | medium | The Tainacan plugin for WordPress is vulnerable to Directory Traversal in all versions up to, and... |
| GHSA-ph8g-mcqh-5p98 | CVE-2026-85659 | high | The PilotPress plugin for WordPress is vulnerable to Privilege Escalation via Account Takeover in... |
| GHSA-gqmr-m2rf-7c75 | CVE-2026-109447 | high | The User Profile Builder – Beautiful User Registration Forms, User Profiles & User Role Editor... |
| GHSA-hvxm-vpq4-3qxh | CVE-2026-89051 | high | The WP Ghost (Hide My WP Ghost) – Security & Firewall plugin for WordPress is vulnerable to... |
| GHSA-7gph-gw3f-5mr5 | CVE-2026-109513 | high | The NotificationX – FOMO, Live Sales Notification, WooCommerce Sales Popup, GDPR, Social Proof,... |
| GHSA-q8wf-34g4-mm3w | CVE-2026-110017 | medium | The Quick PayPal Payments: Payment Button & Form plugin for WordPress is vulnerable to Stored... |
| GHSA-vx38-3rqc-7pgm | CVE-2026-109414 | medium | The Vitepos – Point of Sale (POS) for WooCommerce plugin for WordPress is vulnerable to blind SQL... |
| GHSA-gq9v-x5r6-qvc7 | CVE-2026-111122 | high | The SiteOrigin CSS plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting... |
| GHSA-phxf-4j8m-r2jf | CVE-2026-12272 | medium | The Lightweight Cookie Notice – Cookie Banner for Cookie Consent plugin for WordPress is... |
| GHSA-67h6-9gc5-xw7x | CVE-2026-107764 | high | The SiteOrigin CSS plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting... |
| GHSA-9rx6-fffx-55r5 | CVE-2026-100158 | medium | The SQL Chart Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the ... |
| GHSA-pg87-gj3v-m4jx | CVE-2026-104932 | high | The Search Regex plugin for WordPress is vulnerable to PHP Object Injection in version 3.5 via... |
| GHSA-q4wg-8pfx-jfgq | CVE-2026-107748 | medium | The User Profile Builder – Beautiful User Registration Forms, User Profiles & User Role Editor... |
| GHSA-6247-9gvr-43xh | CVE-2026-104001 | medium | The The Slim SEO – AI SEO Plugin, Lightweight, Fast & Automated plugin for WordPress is... |
| GHSA-x22g-vhr9-fpv2 | CVE-2026-111106 | medium | The Mail Mint plugin for WordPress is vulnerable to SQL Injection via the 'filters' parameter of... |
| GHSA-3658-jvcq-xc7g | CVE-2026-103999 | high | The Ultra Addons for Contact Form 7 plugin for WordPress is vulnerable to Stored Cross-Site... |
| GHSA-cx8v-98r8-v7fw | CVE-2026-100186 | high | The User Profile Builder – Beautiful User Registration Forms, User Profiles & User Role Editor... |
| GHSA-gpm8-99q9-v8fc | CVE-2026-103896 | high | The 10Web Booster – Website speed optimization, Cache & Page Speed optimizer plugin for WordPress... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Company #75 | N0n | US | 2026-10-16T01:23:41.272921+00:00 |
| Company #74 | N0n | US | 2026-10-16T01:23:06.889496+00:00 |
| Evolution Spine / All Labs | N0n |  | 2026-10-16T00:22:58.465900+00:00 |
| verveba.com \ www.att.com | incransom | US | 2026-10-15T22:58:44.927730+00:00 |
| fairfeelegalservices.com | incransom | US | 2026-10-15T22:59:23.132719+00:00 |
| nowaszkola.com | incransom | PL | 2026-10-15T22:03:22.348956+00:00 |
| www.coopecaja.fi.cr | incransom | CR | 2026-10-15T22:03:58.025799+00:00 |
| Keio Corporation | qilin | JP | 2026-10-15T21:04:57.648192+00:00 |
| Telcoe Federal Credit Union | qilin | US | 2026-10-15T20:03:53.217281+00:00 |
| TGM Manufacturing, Inc | Wallstreet | US | 2026-10-15T19:23:13.230279+00:00 |
| Segres Systec | qilin | ES | 2026-10-15T17:05:23.014609+00:00 |
| The Excalibur Group | qilin | US | 2026-10-15T17:04:04.304978+00:00 |
| hilmar-cheese | iah6477 | US | 2026-10-15T17:01:07.206966+00:00 |
| Company #70 | N0n | EG | 2026-10-15T16:23:34.356770+00:00 |
| Company #73 | N0n |  | 2026-10-15T16:23:00.257678+00:00 |
| KD Corp | qilin | KR | 2026-10-15T15:02:16.037759+00:00 |
| grupoabg.com | lockbit5 | MX | 2026-10-15T16:04:44.914875+00:00 |
| neweramachines.com | lockbit5 | US | 2026-10-15T16:06:43.781520+00:00 |
| lcww.com.eg | lockbit5 | EG | 2026-10-15T16:07:25.690075+00:00 |
| kidzrkooldental.com | lockbit5 | US | 2026-10-15T16:09:28.727968+00:00 |

## IOCs
### ThreatFox (recent, abuse.ch)
| Indicator | Type | Malware |
|---|---|---|
| https://vb.888idrcatchy.org/q8 | url | win.vidar |
| https://vb.888idrcatchy.org/v | url | win.vidar |
| https://vb.888idrcatchy.org/el | url | win.vidar |
| https://vb.888idrcatchy.org/el/ | url | win.vidar |
| zubyretu.workers.dev | domain | php.shin_webshell |
| https://vb.888idrcatchy.org/iv | url | win.vidar |
| https://vb.888idrcatchy.org/fi | url | win.vidar |
| https://vb.888idrcatchy.org/hp/ | url | win.vidar |
| https://browse-id-enter.codes | url | unknown |
| 3f8f34747f212b978db927ca45365ab2a416b8149ff93ba625436ece55f92ac2 | sha256_hash | osx.amos |
| a3358d45d9b172ccb27fd5b1ec076347e3226025e20ded26c319c5804171be51 | sha256_hash | osx.amos |
| a208b24088153fa3ae18314706dabcf2a87bf9fc3beb1f365e1e12e4e456cfdf | sha256_hash | osx.amos |
| faf572c1c989ca17101d5003bceb8b4796e709b93bf014f642b2a2c4b7b77fb4 | sha256_hash | osx.amos |
| https://vb.888idrcatchy.org/hp | url | win.vidar |
| https://vb.888idrcatchy.org/ilr | url | win.vidar |
| jiramora.workers.dev | domain | php.shin_webshell |
| https://vb.888idrcatchy.org/l9 | url | win.vidar |
| https://vb.888idrcatchy.org/l9/ | url | win.vidar |
| https://vb.888idrcatchy.org/j8 | url | win.vidar |
| https://vb.888idrcatchy.org/ea | url | win.vidar |

### URLhaus (recent malicious URLs, abuse.ch)
| URL | Threat | Status |
|---|---|---|
| http://119.184.8.229:39267/i | malware_download | offline |
| http://105.224.29.86:35259/i | malware_download | online |
| http://125.41.2.138:58809/bin.sh | malware_download | online |
| http://42.224.10.16:32822/i | malware_download | online |
| http://115.51.92.255:49190/i | malware_download | online |
| http://105.184.120.172:43511/i | malware_download | online |
| http://138.204.196.244:57205/i | malware_download | online |
| http://42.234.167.165:42616/bin.sh | malware_download | offline |
| http://171.213.198.0:41971/i | malware_download | offline |
| https://vtivision-fi.com/suzxwgr/afwugem/aimxfrz/1313secured_stub.ps1 | malware_download | online |
| https://vtivision-fi.com/suzxwgr/afwugem/aimxfrz/DEsecured_stub.ps1 | malware_download | online |
| https://vtivision-fi.com/suzxwgr/afwugem/aimxfrz/UGTsecured_stub.ps1 | malware_download | online |
| https://vtivision-fi.com/suzxwgr/afwugem/aimxfrz/KPsecured_stub.ps1 | malware_download | online |
| https://vtivision-fi.com/suzxwgr/afwugem/aimxfrz/DTsecured_stub.ps1 | malware_download | online |
| https://vtivision-fi.com/suzxwgr/afwugem/aimxfrz/ojsecured_stub.ps1 | malware_download | online |
| https://vtivision-fi.com/suzxwgr/afwugem/aimxfrz/secured_stub.ps1 | malware_download | online |
| https://drive.google.com/uc?export=download&id=1zejSPyWGejAr5gTQViaOKk7CxyIA7XWY | malware_download | online |
| https://drive.google.com/uc?export=download&id=10ICemtxdkr_yOgc4NZiDkbkzOwJddq22 | malware_download | online |
| http://175.165.82.203:59615/i | malware_download | offline |
| http://175.149.85.227:46495/i | malware_download | offline |

### MalwareBazaar (recent samples, abuse.ch)
| SHA256 | File type | Signature |
|---|---|---|
| 18e7bea35f43858ce0174866bcaba4ea45c51be95d32d73ed3736744c44fb6c4 | abuse_ch | n/a |
| a22f104c84e80eda41c23abcbf90ae30a953d53697b7f90c8df1197f43578115 | dash | RemcosRAT |
| b8616579d720af5c0d8a81536a34517e0be3ac886e7a459d6bf982a79d051693 | dash | n/a |
| d27e33a6766532e8a826517790932a3c90e8c12fc6cbe96d19d398eb0e2f06f5 | anonymous | Vidar |
| dfda428358139eca7b9691cef8cb2e2085faad8f158debde5eb395c185040f7e | whack_sh | n/a |
| 6b79cc7d38340106c0cf18a24499d430a6319282387fdd396d4a2f7943f8dd8e | whack_sh | ConnectWise |
| 2fcb530e9fc950da8f43f38beb90beb63b26730f53b7e954b3813fe213ccd060 | wristhulk | n/a |
| d5d1874bec53d5afa09ef36ae3e88630122e14c6f224b14752e5bd014d51fe16 | wristhulk | n/a |
| dcbe27c0161bdf1922bf060c50b086031a7ffde000bff3bf4fae3df10bbbd096 | wristhulk | n/a |
| 77d5542a5b29e500d9bb571bb191fc787074c411ed73e543eea8e1769a13105a | Bitsight | n/a |
| 2a9d70d79cf080d7037f624722d40c4f39374f2a4459d3331ed608c293b0176e | wristhulk | n/a |
| 3f1f116c327d7d35af96e73ccf68b95d2422782d904f0715834b99e27a7465b4 | wristhulk | n/a |
| 34b78a64d76e3d03455fa25dda4292eea59dea145f0c3f2c2addcb7380ff988b | Bitsight | n/a |
| e096855e3202ad914ea6ff670e1872d813f6104f3c0b4ed878d0fb376a772c5b | abuse_ch | SalatStealer |
| 93b60bb3affff182a38cfd66c956204db0509a72844a8ff69582892e16437646 | Parper | SalatStealer |
| 3180cf557014640edb8525d0029ca2ccb51ad1515288ba12a7c65fe9d872d91b | vlasovmichael | n/a |
| 3fac4942b8c7461044de38bdc07fdb7e7f21a70c51434f1248e9c5b85e657e02 | nat | AgentTesla |
| 5a417f4582f91f21f2842b170d21cf5f92b48fad39183e315d505d5a2deef5c0 | wristhulk | n/a |
| 73b0347a300e8d5b13d37ea451069999b8266093f47c9c461ddf85568e9f9245 | wristhulk | n/a |
| d172a3bd408a9a96b9e18ca3e7da896ad5c6014cedb61d827919e10df040683e | abuse_ch | n/a |

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
| 107.150.123.48 | 11 |
| 45.148.10.240 | 10 |
| 152.32.225.117 | 10 |
| 160.250.132.238 | 10 |
| 2.57.122.238 | 9 |
| 45.148.10.152 | 9 |
| 66.240.236.119 | 9 |
| 80.94.95.109 | 9 |
| 85.217.149.30 | 9 |
| 92.5.155.195 | 9 |
| 130.12.180.32 | 9 |
| 167.94.146.51 | 9 |
| 14.63.217.28 | 8 |
| 20.193.50.139 | 8 |
| 31.184.195.246 | 8 |
| 36.66.16.233 | 8 |
| 45.43.60.98 | 8 |
| 45.148.10.141 | 8 |
| 45.148.10.157 | 8 |

### OpenPhish (live phishing URLs)
- https://sp18ct10-murnek-biz-vazaro.pages.dev/
- https://2hmes.com/schwartzmfg/schwartzmfg.html
- https://sites.google.com/view/orange-secu/accueil?clckid=091a9c56
- http://clck.ru/3VdxBb
- http://en--start-ledger-com-web-sso.typedream.app/
- https://globalmoney.eu/
- https://shopee2359.blogspot.com/
- https://www.usps-server.serv00.net/
- http://start-begin-io-trezer-app.typedream.app/
- http://www.shopee1217.blogspot.com/
- http://www.inforesmi-tbk89.blogspot.com/
- http://taxwithholdingpdf-viewer.vercel.app/
- http://account-restriction-1000967754.web.app/help/contact/10045873236587345/
- https://activarprotecciones.iceiy.com/?i=1
- https://www.acur.me/l/WlJZr
- https://nag.gitbook.io/erds
- http://safegemini--log-en.webflow.io/
- http://shopee1211.blogspot.com/
- http://www.browardcourtpdf-viewer.vercel.app/
- https://chanchal7068.github.io/Amazon-Clone

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://pageseuc1.actmkt.com/(S(hy4pcr0g1u401hktv4st3miw))/l/c5X8MfZz6j9Y7Fto3LAd |
| 9.1 | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AaSxoQyQEeCdGiNQploah5nAij7vrMqrlVIHby1Q4v_ARx9kttGkmffM4ARVCnkvjXQyGpUqW4kQNA&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06STnICMdhP99k2m6VqLhptHj4J9Si5yXkqrZ1-b83W7l3PMf3PPd-30z5bfH_LJumjGTq8CKCA&dsh=S-584522676%3A1792137167437578 |
| N/A | https://away.vk.ru/away.php?rh=5882ea5b-48e7-4ce0-8f0c-a77243cd27b2 |
| N/A | https://away.vk.ru/away.php?rh=dafffc2a-e32e-4ef9-82c9-591d6af9407d |
| 5 | http://49.51.43.12/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=ASKXGp36_CB8HzfrpuLLHTVjXxiUGDwO6Tj8yz4QrsaGyc3I4H4G7NxTTQJtpw0j07g9O5T5Tx4uyQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SSE_6hJwjryDm5ylfALEE8WcWPG0sjz0-3InD8qHWFgN3lMxgXJelJpyejXaNAR2g4-0AsV&dsh=S572778931%3A1792136126117713 |
| N/A | https://vibuma.com/redirect/ads.html?checkid=87&checktime=1535032107&redirect=http://0xC117DD0E/qzmwa/q68747470733A2F2F7072657474792D736561736F6E2D65706F63682E676C697463682E6D652F3F653D/737570706F72744062726F616463617374746F6F6C732E636F6D&coid=20501&empid=37252&UniqueEmployee=0&buttontext=Click%20for%20our%20Website%20target |
| 8.6 | http://43.156.0.130/v3/signin/identifier?amp;continue=https://accounts.google.com/&amp;followup=https://accounts.google.com&passive=1209600&flowName=GlifWebSignIn&flowEntry=ServiceLogin&dsh=S-184520822:1792135712334667 |
| 9.1 | http://43.156.0.130/v3/signin/identifier?amp%3Bffgf=1&amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=Af_xneGpinflONH_c3iB5WwVV1C6BSPwAwpudWnjxe8BcKRMcZLFgAnlzpjtHVk0QMFIUm6AcMYv&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SSFasQ_Mg7L2yARW3DcU8WMA_jwQInV0eSZyQ6i0wKTWpi8YGd4z8M77ExZc-9_xav6GeRsMg&dsh=S1631093647%3A1792135564986671 |
| 3 | http://away.vk.ru/away.php?rh=51d6ab46-5f0e-4eb8-936b-e27ae8c73eb6 |
| N/A | https://fiberhost.net/gleview/ |
| N/A | https://away.vk.ru/away.php?rh=431538b0-3943-456a-82c8-0fbf5f62c822 |
| 4.5 | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AaSxoQyQ_ZSuXpSvue0UfKrOXnU6mQAuN0RcLmvWGTqSCzhKlOsPyDT7wQQH6ra2Rhdw1PE87iTB&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SQEBC7hR0ipqpJylsTxP1nKIissPJixvWYmeP3yNpseBrnQ4Z7uQh09jKTQ-J9syQ7hUhb8jw&dsh=S-216824746%3A1792134469701323 |
| N/A | https://away.vk.ru/away.php?rh=4dd9f168-c5e9-4ad0-a6fc-7adcb8ed90c7 |
| N/A | https://flat-bread-04ca.cloudflareaccess.com/cdn-cgi/access/login/vertiv-command-center.pages.dev?kid=617efb6eb0445e77d08421b7c2075c08ed7302463271c62a28d702c82772462a&meta=eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiIsImtpZCI6IjEyY2U5NjlmMDk3YjUyNjliNjllZjA0N2EwMjBiZGI2NGMwMTc5NjMwNzE3MzJhMWJjODg2NjJiNGUxYzJjY2IifQ.eyJ0eXBlIjoibWV0YSIsImF1ZCI6IjYxN2VmYjZlYjA0NDVlNzdkMDg0MjFiN2MyMDc1YzA4ZWQ3MzAyNDYzMjcxYzYyYTI4ZDcwMmM4Mjc3MjQ2MmEiLCJob3N0bmFtZSI6InZlcnRpdi1jb21tYW5kLWNlbnRlci5wYWdlcy5kZXYiLCJyZWRpcmVjdF91cmwiOiIvIiwic2VydmljZV90b2tlbl9zdGF0dXMiOmZhbHNlLCJpc193YXJwIjpmYWxzZSwiaXNfZ2F0ZXdheSI6ZmFsc2UsImV4cCI6MTc5MjEzMzcyOSwibmJmIjoxNzkyMTMzNDI5LCJpYXQiOjE3OTIxMzM0MjksImF1dGhfc3RhdHVzIjoiTk9ORSIsIm10bHNfYXV0aCI6eyJjZXJ0X2lzc3Vlcl9kbiI6IiIsImNlcnRfc2VyaWFsIjoiIiwiY2VydF9pc3N1ZXJfc2tpIjoiIiwiY2VydF9wcmVzZW50ZWQiOmZhbHNlLCJjb21tb25fbmFtZSI6IiIsImF1dGhfc3RhdHVzIjoiTk9ORSJ9LCJyZWFsX2NvdW50cnkiOiJVUyIsImFwcF9zZXNzaW9uX2hhc2giOiI4ODgwYTFiNmUxNjAzMzBiZTRkYTBhZmQ2MWNiOWI3ZTA2OTQyZDNjMTA4MzI4NjQ1YWY1MTg3ZTZhZWFiZmI4In0.d92vgFmcedxWMjxoMpDGmUWEWc3CN6LY9m9MZHTsng0aKmqZp2Vv93QQcnBxXF-yUSm29s0xo8-rESUWOIc-zrGxZhT6bXfEEPGvA6ZtuBAAtSZ_5lpm3yyyYwDnmNygKjSg5egv7HemWEB3UkZZzZoxCVocMV706vlcR2kD3T95OvNIo-DLiIRzKarjxDJ7IqhHzvLmb4nalpkimorMv3gbqlnUpi4LDDBHNbCvDC1DU__p-jVxYwYLPFWZqTMJ0QwENfUjLv-MzjHS-K2sb7-E7aOJ4QhGwWQ0Obr1LB9osqgCBK8l7-bKH1ZcqPANl7xWGpozsYVIZQHiHk9GPw&redirect_url=%2F |
| N/A | https://away.vk.ru/away.php?rh=f0b892ff-1208-4744-94a7-f58f478043f9 |
| 7.5 | http://49.51.43.12/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AQMjQ7QyROPzn0qaqnYvX4_aw7qH8RajahyDV4UI8mo2Mw7SaNi-z6QQG4MH4pDlzJ2gDPTt_nm2&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06ST_WOxBLEw03Wy3Jy6lcequjcdi4HvoujzsJp3Yea0juJfCY5EZpkZ-x67kZz55JryxMN3ZOg&dsh=S-147235752%3A1792132944379743 |
| N/A | https://yandex.ru/showcaptcha?cc=1&form-fb-hint=2.1&mt=0B65EB1197FA68034FA97E54843AB2B410D9CD093505F0C551E1A00E489521077594124DC7E0E0D09DF50A1D0AD571BE4ACAF46A0E22A0FBEE9FA23B3C4A3E200A1B158A2EF64A08B2A27E876CAF81B93866AD93FD43613A94A5865056FD593E87417C2387BFA70378C06956440C70A274BA95B2F9863F6170DC3C14D0C2840A48AE116F56F558DBDD&retpath=aHR0cHM6Ly95YW5kZXgucnUvc2VhcmNoP3RleHQ9MjExNjg3MTc%2C_9e32ea590f1152ceb4677b92f96f1e0c&t=2%252F1792132874%252Fbc2fc20a424c3d884b63d716b995c033&u=9587536911960386380&s=d108c1e4ddbe40d8e1265915176382be |
| 8.8 | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AWnogHfrcMjMJOA5-x4JjU2A_H62FL5Ipip8qUn0FfsVqhu1vrUBPxBl4JpnqCjPGKNrTfaShVnNJQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06STQortm-l2gyv06vVMWCYNwrXiRlpiqLYHphfQ42iwI6F2_FrfI_NUtFF4hZMidxn8vy_kA&dsh=S1008155422%3A1792132707113756 |
| N/A | https://www.att.com/activearmorapp?_branch_match_id=1639528536487439382&utm_source=AT%26T%20App&_branch_referrer=H4sIAAAAAAAAA8soKSkottLXT0wuySxLTSzKzS%2FSzS%2FKTM%2FM00ssKdFLzs%2FV9wtL8U6KLCzzMUqyrytKTUstKsrMS49PKsovL04tsnXOKMrPTQUAZUf3KkgAAAA%3D |
| 4.5 | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=ASKXGp0_nbFzdHoBsG_d6znGlWE063OUXUJ-liVgQNfJJB3wA_mip4wV6In-9Cchxtm7MSHwtubxoQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06STdP1bmMmh2T8lLTmBuSs0stNxAcjZ4CcuDKqiiTYgrW2Ru5VNKUuUJGk_SlEZubVvNrLJekA&dsh=S288954237%3A1792132238752613 |

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
- 1.10.247.40
- 1.14.149.30
- 1.14.240.247
- 1.159.54.33
- 1.161.18.125
- 1.179.232.194
- 1.180.246.242
- 1.20.150.168
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.220.198.126
- 1.222.42.237
- 1.227.228.131
- 1.235.14.41
- 1.235.183.146
- 1.237.155.150
- 1.238.106.229
- 1.247.245.61
- 1.250.67.190

### CINS Army (poorly-rated IPs)
- 1.14.149.30
- 1.192.129.106
- 1.192.216.192
- 1.215.138.43
- 1.24.16.110
- 1.24.16.116
- 1.24.16.117
- 1.24.16.12
- 1.24.16.134
- 1.24.16.137
- 1.24.16.142
- 1.24.16.150
- 1.24.16.151
- 1.24.16.153
- 1.24.16.166
- 1.24.16.167
- 1.24.16.172
- 1.24.16.174
- 1.24.16.177
- 1.24.16.18

## News (last ~36h, across outlets)
### The Hacker News
- [China-Linked Hackers Exploited BeyondTrust Zero-Day to Take Over Remote Support Servers](https://thehackernews.com/2026/10/china-linked-hackers-exploited.html)
- [CERT-In Warns AI Agents Accessed Sensitive Data at Indian Organizations During Testing](https://thehackernews.com/2026/10/cert-in-warns-ai-agents-accessed.html)
- [PEERSTITCH Malware Deployed via FortiOS Flaw Bypasses Checks on Tagged VPN Sessions](https://thehackernews.com/2026/10/attackers-exploit-fortios-flaw-to.html)
- [Critical PwnEscape Linux Kernel Vulnerability Lets Guest VMs Read Host Memory](https://thehackernews.com/2026/10/critical-pwnescape-linux-kernel.html)
- [ThreatsDay: Adobe RCE, DNS Wallet Theft, NVIDIA Container Escape, Self-Healing Backdoor + 23 More](https://thehackernews.com/2026/10/threatsday-adobe-rce-dns-wallet-theft.html)
- [Citizen Lab Traces Zero-Click Candiru Spyware Infections at Al Jazeera to Targeted Online Ads](https://thehackernews.com/2026/10/citizen-lab-traces-zero-click-candiru.html)
- [Silent Lynx Exploits WinRAR Flaw to Deploy Reverse Shell in CIS Government Attacks](https://thehackernews.com/2026/10/silent-lynx-exploits-winrar-flaw-to.html)
- [Help TDS Linked to Hotejka as 20,000+ Cloudflare Pages Domains Host Tech Support Scams](https://thehackernews.com/2026/10/help-tds-linked-to-hotejka-as-20000.html)
- [NGINX Fixes 5 Flaws, Including Possible RCE and a TLS Bug That May Skip Client-Cert Checks](https://thehackernews.com/2026/10/nginx-fixes-5-flaws-including-possible.html)
- [Next.js Ships Out-of-Band Patch for Two Critical RCE Flaws in Caching and SVG Processing](https://thehackernews.com/2026/10/nextjs-ships-out-of-band-patch-for-two.html)
- [Drupal Patches Critical Field UI Flaw With Unauthenticated RCE Path via Contributed Modules](https://thehackernews.com/2026/10/drupal-patches-critical-core-rce-flaw.html)
- [Fake AI Attacks Spread Across US Companies: How MSSPs Can Stop Incidents Early](https://thehackernews.com/2026/10/fake-ai-attacks-spread-across-us.html)
- [Palo Alto Networks Patches PAN-OS Authenticated RCE Flaw Amid Active Exploitation](https://thehackernews.com/2026/10/palo-alto-networks-patches-pan-os.html)
- [Why AI Confidence Is Not Validation](https://thehackernews.com/2026/10/why-ai-confidence-is-not-validation.html)
- [India Mandates Registered Caller Name Display on 4G and Newer Networks From November 1](https://thehackernews.com/2026/10/india-mandates-registered-caller-name.html)

### BleepingComputer
- [BAE Systems cyberattack disrupts US federal court operations](https://www.bleepingcomputer.com/news/security/bae-systems-cyberattack-disrupts-us-federal-court-operations/)
- [BeyondTrust patches zero-day exploited in attacks since August](https://www.bleepingcomputer.com/news/security/beyondtrust-patches-zero-day-exploited-in-attacks-since-august/)
- [Hackers exploit Collabora RCE flaw to backdoor Nextcloud servers](https://www.bleepingcomputer.com/news/security/hackers-exploit-collabora-rce-flaw-to-backdoor-nextcloud-servers/)
- [Android gets AI defenses against messaging scams, fake calls](https://www.bleepingcomputer.com/news/security/android-gets-ai-defenses-against-messaging-scams-fake-calls/)
- [Hackers hijack D-Link, Ubiquiti devices to resell your stolen bandwidth](https://www.bleepingcomputer.com/news/security/hackers-hijack-d-link-ubiquiti-devices-to-resell-your-stolen-bandwidth/)
- [Fake Arch Linux packages push malware with root privileges](https://www.bleepingcomputer.com/news/security/fake-arch-linux-packages-push-malware-with-root-privileges/)
- [Is AI pentesting as good as a human pentester?](https://www.bleepingcomputer.com/news/security/is-ai-pentesting-as-good-as-a-human-pentester/)
- [Microsoft: Windows Server 2022 reached end of mainstream support](https://www.bleepingcomputer.com/news/microsoft/microsoft-windows-server-2022-reached-end-of-mainstream-support/)
- [Police arrests 95 suspects in international CSAM crackdown action](https://www.bleepingcomputer.com/news/security/police-arrests-95-suspects-in-child-sexual-abuse-material-crackdown/)
- [Microsoft fixes bug causing Windows black screens, Explorer crashes](https://www.bleepingcomputer.com/news/microsoft/microsoft-fixes-bug-causing-windows-black-screens-explorer-crashes/)
- [UK Legal Aid Agency: Hackers stole records dating back to 1978](https://www.bleepingcomputer.com/news/security/uk-legal-aid-agency-hackers-stole-records-dating-back-to-1978/)
- [Palo Alto Networks warns of PAN-OS RCE flaw exploited in attacks](https://www.bleepingcomputer.com/news/security/palo-alto-networks-warns-of-pan-os-rce-flaw-exploited-in-attacks/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [SecTor 2026 Reveals a Rapidly Shifting Cybersecurity Landscape](https://www.darkreading.com/cybersecurity-operations/sector-2026-reveals-a-rapidly-shifting-cybersecurity-landscape)
- [F-Secure Launches Victim-First Scam Encyclopedia Covering 50+ Types of Consumer Fraud](https://www.darkreading.com/threat-intelligence/f-secure-launches-victim-first-scam-encyclopedia-covering-50-types-of-consumer-fraud)
- [AI Slop Isn't Just for Social Media; It's Ruining Cyberattacks, Too](https://www.darkreading.com/threat-intelligence/ai-slop-ruining-cyberattacks)
- [Vulnerability Management Isn't About the Score — It's About How It Applies to You](https://www.darkreading.com/cybersecurity-operations/vulnerability-management-isnt-about-the-score-its-about-how-it-applies-to-you)
- [EU Grocers Pay a Steep Price for Unpatched Fridge Firmware](https://www.darkreading.com/ics-ot-security/eu-grocers-unpatched-fridge-firmware)
- [Ivanti ICS Zero-Day Attacks Highlight Vendor Patching Hurdles](https://www.darkreading.com/vulnerabilities-threats/ivanti-ics-zero-day-attacks-vendor-patching)
- [Yam Store: The Phishing Network Behind a Billion Messages](https://www.darkreading.com/cyberattacks-data-breaches/yam-store-phishing-network-behind-billion-messages)
- [Anthropic 'SneakPeek' Flaw Is a Silent Zero-Click Threat](https://www.darkreading.com/threat-intelligence/new-anthropic-sneakpeek-silent-zero-click-threat)

### SecurityWeek
- [Microsoft Patches Two Dozen RCE Flaws in Office](https://www.securityweek.com/microsoft-patches-two-dozen-rce-flaws-in-office/)
- [Proofpoint Inks $6.3 Billion All-Cash Deal to Acquire Varonis](https://www.securityweek.com/proofpoint-inks-6-3-billion-all-cash-deal-to-acquire-varonis/)
- [Context Is King in the Fight Against Modern Cyberattacks](https://www.securityweek.com/context-is-king-in-the-fight-against-modern-cyberattacks/)
- [Watch Now: Zero Trust Strategies Summit – All Sessions Available on Demand](https://www.securityweek.com/virtual-event-today-zero-trust-strategies-summit-2/)
- [UK Legal Aid Agency Hack Scope Widens After Forensic Review](https://www.securityweek.com/uk-legal-aid-agency-hack-scope-widens-after-forensic-review/)
- [Supermarket Refrigeration Attack Widens to Copeland, Dixell Controllers](https://www.securityweek.com/supermarket-refrigeration-attack-widens-to-copeland-dixell-controllers/)
- [CikaBika Bot RAT Uses Discord for C&C](https://www.securityweek.com/cikabika-bot-rat-uses-discord-for-cc/)
- [Novel Android RAT ‘Hirudo’ Replaces Banking Apps With Trojanized Copies](https://www.securityweek.com/novel-android-banking-rat-hirudo-replaces-banking-apps-with-trojanized-copies/)
- [CenterPoint Energy Data Breach Impacts 1 Million Texans](https://www.securityweek.com/centerpoint-energy-data-breach-impacts-1-million-texans/)
- [CISO Conversations: James Robinson – Many Jobs, One Journey to Netskope CISO](https://www.securityweek.com/ciso-conversations-james-robinson-many-jobs-one-journey-to-netskope-ciso/)

### The Record
- [Federal bankruptcy courts dealing with outages after contractor cyberattack](https://therecord.media/federal-bankruptcy-courts-dealing-with-cyberattack-outage)
- [Zero-click spyware infecting devices through online ads, researchers say](https://therecord.media/spyware-citizen-lab-advertising)
- [UK Legal Aid Agency hack worse than thought, with stolen records dating back to 1978](https://therecord.media/uk-legal-aid-cyberattack-data)
- [Suspected Kazakhstan-linked hackers target governments across former Soviet states](https://therecord.media/suspected-kazakhstan-phishing-central-asia-espionage)
- [Ukraine says Elon Musk's Starshield service partially restored after restrictions disrupted drone missions](https://therecord.media/ukraine-says-starshield-working-again-after-disruption)

### Infosecurity Magazine
- [France: Internet-Exposed Danfoss Controllers Drop 71% After Cyber-Attack](https://www.infosecurity-magazine.com/news/france-expose-danfoss-controllers/)
- [New Aoki Infostealer Targets AI Coding Assistant Credentials](https://www.infosecurity-magazine.com/news/aoki-infostealer-ai-coding/)
- [Warning Over High-Risk Vulnerabilities in Widely Used LLM Gateway Tool](https://www.infosecurity-magazine.com/news/high-risk-vulnerabilities-llm-tool/)
- [Microsoft Disrupts Global Yam Store Network Behind One Billion Phishing Messages](https://www.infosecurity-magazine.com/news/microsoft-yam-store-one-billion/)
- [ICO Reprimands Met Over Third-Party Data Leak](https://www.infosecurity-magazine.com/news/ico-reprimands-met-over-thirdparty/)

### CyberScoop
- [Proofpoint to buy Varonis for $6.3 billion](https://cyberscoop.com/proofpoint-acquires-varonis-systems-data-security/)
- [The next election influence campaign will target your AI chatbot](https://cyberscoop.com/ai-chatbots-election-influence-hyperlocal-networks/)
- [AdFection: How mercenary spyware invades victims’ devices through targeted advertising](https://cyberscoop.com/adfection-zero-click-spyware-discover-tech/)
- [Authorities charge alleged OLVX cybercrime marketplace operator in North Macedonia](https://cyberscoop.com/olvx-cybercrime-marketplace-operator-charged-north-macedonia/)

### Cisco Talos
- [The Q3 Vulnerability Pulse: Discovery ≠ Exploitation](https://blog.talosintelligence.com/the-q3-vulnerability-pulse-discovery-exploitation/)

### Unit 42 (Palo Alto)
- [AI-Powered Espionage Campaign Targets Government Linux Infrastructure](https://unit42.paloaltonetworks.com/ai-campaign-targets-linux-infrastructure/)
- [Unit 42 Uncovers PEERSTITCH, a Stealthy FortiGate Implant](https://unit42.paloaltonetworks.com/fortimanager-cve-2024-47575-peerstitch-malware/)

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
- [ARMORY CASTLE Exploits BeyondTrust](https://cloud.google.com/blog/topics/threat-intelligence/armory-castle-exploits-beyondtrust/)

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
- [Atlassian Arbitrary File Access Vulnerability](https://fortiguard.fortinet.com/threat-signal-report/6548)

## Fetch issues this run
- SANS Internet Storm Center RSS -> malformed/unparseable feed (<unknown>:2:0: syntax error)

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal