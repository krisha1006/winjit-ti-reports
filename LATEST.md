# Winjit Daily TI Digest — 2026-10-31

_Auto-generated. Window: last ~24h. Fetched at 2026-10-31T09:26:07.282264+00:00Z_

**At a glance:** 2 new KEV · 63 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-118527 | Ivanti | Connect Secure | Ivanti Connect Secure Generation of Predictable Numbers or Identifiers Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-111357 | Ivanti | Connect Secure | Ivanti Connect Secure Missing Authentication for Critical Function Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-119597 | 9.8 | n/a | OpenDeepWiki through 2.0.6 contains a hard-coded JWT signing key vulnerability that allows unauthenticated attackers to forge administrator tokens using the publicly known Jwt:SecretKey in appsettings |
| CVE-2026-119660 | 9.8 | n/a | MuseBot before 2.0.0 contains an authentication bypass vulnerability that allows unauthenticated attackers to forge admin sessions by using the hard-coded default session_key 'muse_bot_session_key'. A |
| CVE-2026-119706 | 9.8 | n/a | InternLM LMDeploy 0.9.0 through 0.18.0 contains an unauthenticated remote code execution vulnerability that allows remote attackers to run OS commands by sending pickled data to the /update_weights en |
| CVE-2026-109220 | 9.8 | n/a | The PDF Invoice for WooCommerce + Drag and Drop Template Builder plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 7.1.1 via the 'customer_note' paramete |
| CVE-2026-116512 | 9.8 | n/a | The Project Manager – AI Powered Project Management, Task Management, Kanban Board & Time Tracker plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 4.1. |
| CVE-2026-119096 | 9.8 | n/a | The Uncanny Toolkit for LearnDash plugin for WordPress is vulnerable to Authentication Bypass in versions up to, and including, 3.8.2 via the `email` parameter of the `uo_login_action()` function. Thi |
| CVE-2026-118235 | 9.8 | n/a | The SimpleForm – Form Maker to Chat Apps with Quiz, Poll and Multi Lead Notifications plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 3.10.2 via the h |
| CVE-2026-116557 | 9.1 | n/a | The WP Booking System - Booking Calendar plugin for WordPress is vulnerable to unauthorized modification of data due to a missing capability check on the wpbs_action_ajax_calendar_remove_note() functi |
| CVE-2026-89270 | 9.1 | n/a | The Popup Builder – Create highly converting, mobile friendly marketing popups. plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 4.4.5 This is due to th |
| CVE-2026-103882 | 9.1 | n/a | The Acadlix LMS – AI Quiz Maker, Online Exam & Course Plugin for WordPress plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation in the post_delete_ass |
| CVE-2026-119408 | 8.8 | n/a | n8n before 2.42.6, 2.43.x before 2.43.3, and 3.x before 3.0.1 contains a remote code execution vulnerability via deprecated Function, Function Item, and LangChain Code nodes running outside task runne |
| CVE-2026-119420 | 8.8 | n/a | Lago through 1.55.0 contains an authentication bypass vulnerability that allows organization administrators to obtain session tokens for existing accounts via the acceptInvite mutation without a passw |
| CVE-2026-104012 | 8.8 | n/a | The Rox Appointment Booking – Appointment Booking Scheduling Solution plugin for WordPress is vulnerable to Privilege Escalation via Mass Assignment in all versions up to, and including, 1.3.1 This is |
| CVE-2026-120070 | 8.8 | n/a | The User Frontend – Membership, User Registration, User Profile, User Directory & Content Restriction with Frontend Post Submission plugin for WordPress is vulnerable to Privilege Escalation in all ve |
| CVE-2026-116086 | 8.8 | n/a | A flaw was found in konflux-ci. An attacker with permission to trigger automated workflow runs can cause an information disclosure by providing crafted issue titles to workflow scripts. The affected s |
| CVE-2026-119572 | 8.7 | n/a | Traefik from 3.7.0-ea.1 before 3.7.15 contains an authentication bypass vulnerability in the Kubernetes Ingress NGINX provider that silently disables mTLS configured via the auth-tls-secret annotation |
| CVE-2026-114217 | 8.6 | n/a | A flaw was found in konflux-ci. Continuous Integration (CI) automation scripts store sensitive GitHub access tokens in plaintext on the runner without cleaning them up after execution. A local attacke |
| CVE-2026-119978 | 8.5 | n/a | Flowise through 3.1.4 contains a sandbox escape vulnerability that allows authenticated users to execute OS commands by abusing allowlisted langchain and mammoth modules when ALLOW_BUILTIN_DEP=true. A |
| CVE-2026-116964 | 8.4 | n/a | A flaw was found in konflux-ci. An attacker with repository write access can achieve arbitrary code execution within the Continuous Integration and Continuous Delivery (CI/CD) workflow environment. By |
| CVE-2026-119419 | 8.1 | n/a | CakePHP through 5.4.3 contains an sql injection vulnerability that allows attackers to inject SQL by supplying unvalidated collation values to StringExpression and IdentifierExpression. Attackers cont |
| CVE-2026-119716 | 8.1 | n/a | pybars3 through 0.9.7 contains a code injection vulnerability in pybars/_compiler.py that allows template authors to execute Python code via unescaped bracketed path segments. Attackers can supply Han |
| CVE-2026-119977 | 8.1 | n/a | WordPress Core is vulnerable to Remote Code Execution in versions 4.7 through 7.1.3. This is due to predictable, web-accessible staging paths used during full-package core upgrades. This makes it poss |
| CVE-2026-103898 | 8.1 | n/a | The Wp Social Login and Register Social Counter plugin for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 3.2.2. This is due to the social login REST callback r |
| CVE-2026-117681 | 8.0 | n/a | A flaw was found in konflux-ci. This vulnerability allows privilege escalation when the user interface proxy automatically disables Transport Layer Security (TLS) certificate verification for connecti |
| CVE-2026-119373 | 7.8 | n/a | SQLite before 3.54.0 built with FTS5 contains a heap buffer overflow in fts5MergeRowidLists() that undersizes the output buffer when merging detail=none prefix doclists. Attackers who can populate a d |
| CVE-2026-119578 | 7.8 | n/a | MONAI from 1.6.0 before 1.6.1 contains a remote code execution vulnerability in Auto3DSeg algo_from_json() that allows attackers to run Python code via a crafted work directory's algo_object.json. Att |
| CVE-2026-104061 | 7.8 | n/a | Scribus before 1.6.7 contains a heap out-of-bounds write vulnerability in the scimgdataloader_psd loader that uses unchecked PSD file values as lookup array indexes. Attackers can convince users to pl |
| CVE-2026-104064 | 7.8 | n/a | Scribus before 1.6.7 contains an integer overflow vulnerability in the scimgdataloader_tiff TIFF loader that allows attackers to trigger a heap overflow via crafted tile dimensions. Attackers can supp |
| CVE-2026-104065 | 7.8 | n/a | Scribus before 1.6.7 contains an out-of-bounds write vulnerability in the importdrw Micrografx Draw plugin that uses an unvalidated y offset to select image scanlines. Attackers can craft a DRW file t |
| CVE-2026-104067 | 7.8 | n/a | Scribus before 1.6.7 contains an out-of-bounds memory access vulnerability in the importsvm plugin that fails to verify bitmap and transparency mask dimensions match. Attackers can supply a crafted SV |
| CVE-2026-119718 | 7.8 | n/a | Blender before 4.5.15 and 5.x before 5.2.3 contains a heap buffer overflow vulnerability caused by integer overflow in ptcache_data_alloc() when reading point cache files. Attackers can supply a craft |
| CVE-2026-119719 | 7.8 | n/a | Blender before 4.5.15 and 5.x before 5.2.3 contains a heap buffer overflow vulnerability in the blend file thumbnail extractor caused by 32-bit integer overflow in thumb_data_vertical_flip(). Attacker |
| CVE-2026-119722 | 7.8 | n/a | Blender before 4.5.15 and 5.x before 5.2.3 contains a heap out-of-bounds access vulnerability in read_struct() that skips size validation when a .blend file's SDNA struct layout compares equal. Attack |
| CVE-2026-112347 | 7.6 | n/a | Kirki plugin for WordPress before 6.4.1 contains a broken object-level access control vulnerability in its page REST API, where the PUT /wp-json/kirki/v1/pages/{page_id} route and the save_page_data,  |
| CVE-2026-103963 | 7.5 | 0.3% | A flaw was found in glib-networking. When establishing connections using Transport Layer Security (TLS) version 1.3, the client-side session cache does not limit the number of session tickets retained |
| CVE-2026-119655 | 7.5 | n/a | CoreShop through 1.5.5 contains an unauthenticated sql injection vulnerability in the api/Good/GetGoodsPageList endpoint via the unvalidated order parameter appended to ORDER BY. Attackers can inject  |
| CVE-2026-119656 | 7.5 | n/a | CoreShop by CoreUnion through 1.5.5 contains an unauthenticated sql injection vulnerability in the api/Agent/GetGoodsPageList endpoint via the order parameter appended to an ORDER BY clause. Anonymous |
| CVE-2026-107630 | 7.5 | n/a | The Email Templates Customizer and Designer for WordPress and WooCommerce plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 1.5.14 This is due to the plu |
| CVE-2026-119760 | 7.5 | n/a | sniproxy through 0.7.0 contains a NULL pointer dereference vulnerability in resolv_cancel() that allows remote unauthenticated attackers to crash the daemon by sending overlong hostnames. Attackers ca |
| CVE-2026-119163 | 7.5 | n/a | The FunnelKit Automations – Email Marketing Automation and CRM for WordPress & WooCommerce plugin for WordPress is vulnerable to time-based SQL Injection via the 'bwfan_cart_id' parameter in all versi |
| CVE-2026-120040 | 7.5 | n/a | The Mail logging & Catcher plugin for WordPress is vulnerable to Sensitive Information Exposure in all versions up to, and including, 2.2.0 via the 'message' parameter. This makes it possible for auth |
| CVE-2026-119619 | 7.3 | n/a | A vulnerability was found in 37954679 cak-filemanagement-system up to 5e6433246475e66462e1fea980688de96a049297. This affects the function mysqli_query of the file admin/save_student.php. Performing a  |
| CVE-2026-109234 | 7.2 | n/a | The Meow Lightbox plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'post_content (bbPress reply body)' parameter in all versions up to, and including, 5.6.4 due to insufficien |
| CVE-2026-109997 | 7.2 | n/a | The Ninja Forms – Contact Form Builder with Calculators, Quizzes, Signatures & AI Form Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'formData.extra' parameter in a |
| CVE-2026-116520 | 7.2 | n/a | The PPWP – Password Protect Pages plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment / shortcode attribute desc_below_form (and placeholder as the marker-smuggling help |
| CVE-2026-107653 | 7.2 | n/a | The SureCart – Ecommerce Made Easy For Selling Physical Products, Digital Downloads, Subscriptions, Donations, & Payments plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'com |
| CVE-2026-107750 | 7.2 | n/a | The PDF Invoices & Packing Slips for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'billing_address.first_name / last_name / company, customer_note' parameter i |
| CVE-2026-111254 | 7.2 | n/a | The W3 Total Cache plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 2.10.7 due to insufficient input sanitization and |
| CVE-2026-115840 | 7.2 | n/a | The VikRentCar Car Rental Management System plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'poplink' parameter in all versions up to, and including, 1.4.9 due to insufficien |
| CVE-2026-116522 | 7.2 | n/a | The Relevanssi – A Better Search plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 4.28.5 due to insufficient input sa |
| CVE-2026-116548 | 7.2 | n/a | The VikRentCar Car Rental Management System plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'optionals' parameter in all versions up to, and including, 1.4.10 due to insuffic |
| CVE-2026-118070 | 7.2 | n/a | The Welcart e-Commerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'gid' parameter in all versions up to, and including, 2.12.5 due to insufficient input sanitization and |
| CVE-2026-119065 | 7.2 | n/a | The Shipping Zones by Drawing for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'szbd-picked' checkout parameter in versions up to, and including, 3.3.0 The szb |
| CVE-2026-119089 | 7.2 | n/a | The ThirstyAffiliates – Affiliate Links, Link Branding, Link Tracking & Marketing Plugin plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions u |
| CVE-2026-119162 | 7.2 | n/a | The User Submitted Posts – Enable Users to Submit Posts from the Front End plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via the 'user-submitted-content' parameter in all |
| CVE-2026-107759 | 7.2 | n/a | The WPO365 | MICROSOFT 365 GRAPH MAILER plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'Subject (via wp_mail/PHPMailer, e.g. CF7 your-subject)' parameter in all versions up  |
| CVE-2026-118057 | 7.2 | n/a | The Shield Security – Smart Bot Blocking, Brute-Force Login Protection & File Scanning plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'REQUEST_URI' parameter in all versions |
| CVE-2026-110530 | 7.2 | n/a | The FeedWordPress plugin for WordPress is vulnerable to Stored Cross-Site Scripting in versions up to, and including, 2026.0517 via syndicated RSS/Atom feed content. The plugin's SyndicatedPost::sanit |
| CVE-2026-120075 | 7.2 | n/a | The WP Activity Log plugin for WordPress is vulnerable to Stored Cross-Site Scripting in all versions up to, and including, 5.6.1 due to insufficient input sanitization and output escaping. This makes |
| CVE-2026-119407 | 7.1 | n/a | Element Web and Element Desktop before 1.12.32 accept guest credentials from URL fragment parameters in loadSession, allowing remote unauthenticated attackers to log out users and clear local stores.  |
| CVE-2026-86715 | 7.1 | n/a | Plaintext storage of a password vulnerability in Crypttech Crypto and Informatics Technologies Industry and Trade Inc. Vatos DLP allows Use of Known Domain Credentials.

This issue affects Vatos DLP:  |
| CVE-2026-119707 | 7.1 | n/a | SonicJS through 3.0.0 contains a missing authorization vulnerability in the /api/:collection and /api/content write routes that only check coarse role labels. Authenticated authors or editors can use  |
| CVE-2026-119710 | 7.1 | n/a | PipesHub 0.3.0 before 0.10.0 contains an event type injection vulnerability that allows authenticated users with only the crawl:write scope to delete connectors by injecting into the :connector path s |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-2mm6-8x3p-cx55 | CVE-2026-92294 | medium | The Spectra Gutenberg Blocks – Website Builder for the Block Editor plugin for WordPress is... |
| GHSA-p6jj-qrp3-7m4g | CVE-2026-119977 | high | WordPress Core is vulnerable to Remote Code Execution in versions 4.7 through 7.1.3. This is due... |
| GHSA-x7hw-7xvr-75fq | CVE-2026-94361 | unknown | The Payable Payment Gateway for WooCommerce WordPress plugin before 1.3.1 does not verify the... |
| GHSA-8883-4cxp-cmxm | CVE-2026-82214 | unknown | The Quick Event Manager WordPress plugin before 9.19 does not verify the status or type of the... |
| GHSA-gwmh-v933-p43v | CVE-2026-118638 | unknown | The Mapster WP Maps WordPress plugin before 2.0.6 does not perform any authorization check on a... |
| GHSA-59cf-vpf5-j3cx | CVE-2026-118629 | unknown | The All-in-One Video Gallery  WordPress plugin before 5.0.0 does not check a video's publication... |
| GHSA-7x9h-cjm5-x9fc | CVE-2026-116520 | high | The PPWP – Password Protect Pages plugin for WordPress is vulnerable to Stored Cross-Site... |
| GHSA-mmc9-9v24-7pg8 | CVE-2026-116563 | medium | The Photo Gallery, Sliders, Proofing and Themes – NextGEN Gallery plugin for WordPress is... |
| GHSA-wm86-p7cw-7wvq | CVE-2026-118438 | unknown | The Firelight Lightbox WordPress plugin before 2.3.24 does not properly escape image attribute... |
| GHSA-9wr6-gc4g-7v5m | CVE-2026-118185 | unknown | The Security Optimizer  WordPress plugin before 1.6.9 does not limit the number of two-factor... |
| GHSA-jmxw-pjw9-552f | CVE-2026-118184 | unknown | The Premium Packages  WordPress plugin before 7.2.2 does not prevent unauthenticated visitors... |
| GHSA-999r-c647-2rx8 | CVE-2026-110042 | unknown | The Payment Forms for Paystack WordPress plugin before 4.0.6 does not properly restrict access to... |
| GHSA-8m6g-3645-wc49 | CVE-2026-118437 | unknown | The BuddyForms WordPress plugin before 2.10.1 does not properly verify ownership before deleting... |
| GHSA-g69p-96gc-gv86 | CVE-2026-110808 | unknown | The Essential Addons for Elementor  WordPress plugin before 6.8.8 does not correctly restrict who... |
| GHSA-fxjq-44vq-hwjg | CVE-2026-118043 | unknown | The Bulk Media Register WordPress plugin before 2.01 does not properly validate a user-supplied... |
| GHSA-6x82-24xh-w634 | CVE-2026-109997 | high | The Ninja Forms – Contact Form Builder with Calculators, Quizzes, Signatures & AI Form Builder... |
| GHSA-vv6j-8xxc-xhcc | CVE-2026-109234 | high | The Meow Lightbox plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the ... |
| GHSA-wqc3-pwvg-9wvc | CVE-2026-101326 | medium | The The Ninja Forms – Contact Form Builder with Calculators, Quizzes, Signatures & AI Form... |
| GHSA-pqjx-p6p5-mv3f | CVE-2026-100155 | medium | The The Ninja Forms – Contact Form Builder with Calculators, Quizzes, Signatures & AI Form... |
| GHSA-wc74-vwp5-gqfv | CVE-2026-110176 | high | The File Force Download module for Drupal 7 implements hook_file_download() to add a Content... |
| GHSA-qhpq-4pf4-cqxv | CVE-2026-116755 | high | Improper Neutralization of Special Elements used in a Command ('Command Injection') in the... |
| GHSA-f2vh-vxfq-92pj | CVE-2026-77152 | medium | Improper Authorization vulnerability in Drupal Field Collection for Drupal 7 allows a user with... |
| GHSA-4742-xp59-83w9 | CVE-2026-111477 | unknown | Rejected reason: This CVE ID has been rejected or withdrawn by its CVE Numbering Authority. |
| GHSA-cgc3-662q-qmrc | CVE-2026-16760 | high | In Trail of Bits fickling through 0.1.12, the _process_import() method in fickle.py adds an... |
| GHSA-xq56-qcfx-62xr | CVE-2026-111578 | high | The PDF Invoices & Packing Slips for WooCommerce WordPress plugin from 5.16.2 before 5.16.5 does... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| sp*****g.com | everstake |  | 2026-10-30T23:55:36.898357+00:00 |
| ArentFox Schiff | SilentRansomGroup | US | 2026-10-30T23:39:46.923961+00:00 |
| chicagolawyer.com | incransom | US | 2026-10-31T00:01:20.224552+00:00 |
| Studio Stelitano e Associati | emperador | IT | 2026-10-30T23:27:04.311896+00:00 |
| Moritt Hock & Hamroff LLP | SilentRansomGroup | US | 2026-10-30T21:37:51.868979+00:00 |
| P... | SilentRansomGroup |  | 2026-10-30T21:37:30.043766+00:00 |
| M... H... | SilentRansomGroup |  | 2026-10-30T20:30:49.244228+00:00 |
| KTU Shipyard | Whitearmor | PH | 2026-10-30T21:38:47.312703+00:00 |
| Suburban Orthopaedics | Wallstreet | US | 2026-10-30T20:31:26.331640+00:00 |
| Cipsa Industrias Sa De Cv | rhysida | MX | 2026-10-30T18:43:09.038702+00:00 |
| A... F... | SilentRansomGroup |  | 2026-10-30T17:09:36.433302+00:00 |
| A***** T****** | Doommageddon |  | 2026-10-30T09:22:24.263212+00:00 |
| INTI International University & Colleges | rhysida | MY | 2026-10-30T06:33:09.094021+00:00 |
| Minutes Quick Services | N0n | AE | 2026-10-30T05:53:58.343512+00:00 |
| spencers.com | Scarlettgroup | US | 2026-10-31T03:34:17.691492+00:00 |
| Susman Godfrey LLP | SilentRansomGroup | US | 2026-10-30T00:02:22.816559+00:00 |
| Acclaim Companies / JCJ Investment | genesis | US | 2026-10-30T22:02:08.362270+00:00 |
| Gilliam & Associates, P.C | genesis | US | 2026-10-30T22:01:30.190012+00:00 |
| Facts N Figures | genesis | US | 2026-10-30T22:00:51.148039+00:00 |
| Illinois Work Injury Resource Center (IWIRC) | genesis | US | 2026-10-30T22:00:10.790170+00:00 |

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
| 138.226.239.234 | 10 |
| 2.57.122.238 | 9 |
| 14.34.249.175 | 9 |
| 77.90.185.20 | 9 |
| 103.159.2.113 | 9 |
| 138.226.239.233 | 9 |
| 167.94.146.48 | 9 |
| 167.94.146.49 | 9 |
| 167.94.146.52 | 9 |
| 167.94.146.58 | 9 |
| 167.94.146.59 | 9 |
| 167.94.146.62 | 9 |
| 167.94.146.63 | 9 |
| 190.171.189.85 | 9 |
| 220.80.223.144 | 9 |
| 2.57.121.112 | 8 |
| 3.129.187.38 | 8 |
| 3.130.168.2 | 8 |
| 16.5.0.204 | 8 |
| 18.116.101.220 | 8 |

### OpenPhish (live phishing URLs)
- http://jkstr12wsed-htpmqskr-8m4h7g-jks91c378.pages.dev/
- http://skrab-zflon-vstyk-3b82fc-yjbw-vlasco.pages.dev/
- https://admin-suport-update-com.weebly.com/
- http://www.admin-suport-update-com.weebly.com/
- https://client.tkchost.com/
- https://umairali69.github.io/FB_page/
- https://xdigitalxflnltyappsute-web.vercel.app/
- http://shopeeakhirtahun172.blogspot.com/
- https://pomarosahotel.com/Adobe_Installer.html
- https://midas-shops.ww-event.com/
- https://0authac9-common-authyclientemailprotection-ac9a8c0.live-document-m365092.workers.dev/
- https://secureprofiles2026-indol.vercel.app/required.html
- https://basar-saint-ave.fr/ar//
- https://isupport-locationet.com/1GI5S2
- https://datum-ingenier-a.p-m1p9u16n.workers.dev/
- https://s3.us-east-1.amazonaws.com/violet.omega.logic/index.html
- http://l.shortlink.es/l/1cdbce272119e87371798f8ceb20a0c3cf059b97/
- https://8u2m4c-qw644c24y-1k9z8p2m4s-qwxk.pages.dev/send_appeal_request
- https://s4w.in/www-roblox-com-Anime-AdventuresprivateServerLinkCode=4460350768291503441077018644550
- http://s.team-zm.com/lp/kma-mhc/foofvybf/

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
- 1.12.55.42
- 1.13.181.113
- 1.14.240.247
- 1.14.64.144
- 1.15.221.192
- 1.15.42.91
- 1.159.54.33
- 1.162.226.183
- 1.201.146.109
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.234.27.159
- 1.234.80.94
- 1.235.183.146
- 1.238.106.229
- 1.247.245.61
- 1.250.67.114
- 1.250.67.190

### CINS Army (poorly-rated IPs)
- 1.14.64.144
- 1.179.240.27
- 1.2.252.192
- 1.215.138.43
- 1.24.16.120
- 1.24.16.162
- 1.24.16.176
- 1.24.16.178
- 1.24.16.190
- 1.24.16.20
- 1.24.16.31
- 1.24.16.44
- 1.24.16.73
- 1.24.16.8
- 1.24.16.82
- 1.24.16.83
- 1.24.16.93
- 1.24.16.94
- 1.24.229.200
- 1.25.19.202

## News (last ~36h, across outlets)
### The Hacker News
- [Attackers Chain Three Ivanti Connect Secure Flaws to Gain Unauthenticated Root Access](https://thehackernews.com/2026/10/attackers-chain-three-ivanti-connect.html)
- [A Shared ChatGPT Link Could Run Attacker Code in Your Session and Read Private Chats](https://thehackernews.com/2026/10/a-shared-chatgpt-link-could-run.html)
- [Cloudflare Reports 18.2 Million Network-Layer DDoS Attacks in Q3, Up 38%](https://thehackernews.com/2026/10/cloudflare-reports-182-million-network.html)
- [Chinese Hackers Use AI-Powered ARTEX to Target Over 200 Organizations Worldwide](https://thehackernews.com/2026/10/chinese-hackers-use-ai-powered-artex-to.html)
- [TeamViewer Flaw Lets Remote Computers Attack Users Who Connect to Control Them](https://thehackernews.com/2026/10/teamviewer-flaw-lets-remote-computers.html)
- [WordPress RCE Flaw Draws Nearly 63,000 Attack Attempts in Just 24 Hours](https://thehackernews.com/2026/10/wordpress-rce-flaw-draws-nearly-63000.html)
- [Trezor Warns of Suspected Hardware Implant in One of Its Wallets Sold by CryptoBilis](https://thehackernews.com/2026/10/trezor-warns-of-suspected-hardware.html)
- [Why Urgent Security Fixes Aren't Fixed. Observe, Prove, Act, Confirm Gets Them Moving](https://thehackernews.com/2026/10/why-urgent-security-fixes-arent-fixed.html)
- [Syrian Hacker Behind Fake Tweet That Triggered $136 Billion Market Drop Gets 42 Months in Prison](https://thehackernews.com/2026/10/syrian-hacker-behind-fake-tweet-that.html)
- [Official Claude Code Extension on Cursor Marketplace Trojanized with Persistent SSH Backdoor](https://thehackernews.com/2026/10/official-claude-code-vs-code-extension.html)
- [Hackers Actively Exploit Highly Critical Drupal Commerce Core Authorization Bypass Flaw](https://thehackernews.com/2026/10/hackers-actively-exploit-highly.html)
- [CISA Adds Actively Exploited GitLab RCE and Cisco Firewall DoS Flaws to KEV](https://thehackernews.com/2026/10/cisa-adds-actively-exploited-gitlab-rce.html)
- [Binance Suffers Security Breach Affecting $6.3 Billion in Assets, Nearly $3 Billion Frozen](https://thehackernews.com/2026/10/binance-suffers-security-breach.html)

### BleepingComputer
- [Critical Linux kernel flaw allows remote root attacks on MPTCP servers](https://www.bleepingcomputer.com/news/security/critical-linux-kernel-flaw-allows-remote-root-attacks-on-mptcp-servers/)
- [Trezor warns of suspected crypto-theft implant in hardware wallet](https://www.bleepingcomputer.com/news/security/trezor-warns-of-suspected-crypto-theft-implant-in-hardware-wallet/)
- [Malicious Claude Code extension on Cursor planted SSH backdoors](https://www.bleepingcomputer.com/news/security/malicious-claude-code-extension-on-cursor-planted-ssh-backdoors/)
- [SS7 and Diameter Attacks: How Signaling Flaws Expose Your Phone](https://www.bleepingcomputer.com/news/security/ss7-and-diameter-attacks-how-signaling-flaws-expose-your-phone/)
- [CISA says max severity GitLab flaw now exploited in the wild](https://www.bleepingcomputer.com/news/security/hackers-now-exploiting-max-severity-gitlab-flaw-in-attacks/)
- [Microsoft finally fixes VPN issues caused by September updates](https://www.bleepingcomputer.com/news/microsoft/microsoft-finally-fixes-vpn-issues-caused-by-september-updates/)
- [Drupal warns of critical Commerce Core flaw exploited in attacks](https://www.bleepingcomputer.com/news/security/drupal-warns-of-critical-commerce-core-flaw-exploited-in-attacks/)
- [Binance links $6.3 billion crypto theft to compromised DevOps laptop](https://www.bleepingcomputer.com/news/security/binance-links-63-billion-crypto-theft-to-compromised-devops-laptop/)
- [OpenAI doubles ChatGPT Pro usage limits after backlash over planned 50% cut](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-doubles-chatgpt-pro-usage-limits-after-backlash-over-planned-50-percent-cut/)
- [Binance probes potential $5.8 billion crypto-theft hack](https://www.bleepingcomputer.com/news/security/binance-probes-potential-58-billion-crypto-theft-hack/)
- [Hugging Face malware campaign returns to hijack GPUs for crypto mining](https://www.bleepingcomputer.com/news/security/hugging-face-malware-campaign-returns-to-hijack-gpus-for-crypto-mining/)
- [Japan Airlines suffers third-party data breach exposing passenger info](https://www.bleepingcomputer.com/news/security/japan-airlines-suffers-third-party-data-breach-exposing-passenger-info/)
- [Polymarket halts trading after crypto-draining script breach, $2.5M traced](https://www.bleepingcomputer.com/news/security/polymarket-halts-trading-after-crypto-draining-script-breach-25m-traced/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [Devs Hit by Trojanized Claude Code Extension for Cursor](https://www.darkreading.com/cyberattacks-data-breaches/devs-trojanized-claude-code-extension-cursor)
- [Behind the Scenes of How Operation Blackout Went Down](https://www.darkreading.com/cybersecurity-operations/behind-the-scenes-how-operation-blackout-went-down)
- [L’Italia è afflitta da vulnerabilità informatiche, senza una causa chiara](https://www.darkreading.com/cybersecurity-analytics/cyber-vulnerabilities-besiege-italy-italian)
- [Undead Software Projects Continue to Raise Security Risks](https://www.darkreading.com/application-security/undead-software-projects-raise-security-risks)
- [As Russia's Cyberwar Evolves, Belarus Steps Forward](https://www.darkreading.com/physical-security/russia-cyber-war-belarus-steps-forward)

### SecurityWeek
- [PHP2Shell Attacks Root Palo Alto Firewalls but Fail Against WordPress](https://www.securityweek.com/php2shell-attacks-root-palo-alto-firewalls-but-fail-against-wordpress/)
- [In Other News: Anthropic Breach Dispute, UEFI Flaw Hits Most Servers, Cloudflare AI Data Leak](https://www.securityweek.com/in-other-news-anthropic-breach-dispute-uefi-flaw-hits-most-servers-cloudflare-ai-data-leak/)
- [Passkeys Are Better Than Passwords. But They Are Not Enough.](https://www.securityweek.com/passkeys-are-better-than-passwords-but-they-are-not-enough/)
- [Bulletproof Host Virtualine Loses Its Domain to FBI Seizure](https://www.securityweek.com/bulletproof-host-virtualine-loses-its-domain-to-fbi-seizure/)
- [Fresh WordPress Vulnerability in Attackers’ Crosshairs](https://www.securityweek.com/fresh-wordpress-vulnerability-in-attackers-crosshairs/)
- [Drupal Commerce Core Vulnerability Exploited Against Online Stores](https://www.securityweek.com/drupal-commerce-core-vulnerability-exploited-against-online-stores/)
- [$2 Million+ Drained From Polymarket Traders in New Supply Chain Attack](https://www.securityweek.com/2-million-drained-from-polymarket-traders-in-new-supply-chain-attack/)
- [Max-Severity GitLab Vulnerability Exploited Against Alpine Linux](https://www.securityweek.com/max-severity-gitlab-vulnerability-exploited-against-alpine-linux/)
- [TeamViewer Flaw Could Let Malicious Hosts Take Over Support Technicians’ Machines](https://www.securityweek.com/teamviewer-flaw-could-let-malicious-hosts-take-over-support-technicians-machines/)
- [$6 Billion Binance Hack Bears Hallmarks of North Korea’s TraderTraitor](https://www.securityweek.com/6-billion-binance-hack-bears-hallmarks-of-north-koreas-tradertraitor/)

### The Record
- [DOJ raises privacy concerns over potential sale of Character.AI chats](https://therecord.media/doj-raises-privacy-concerns-over-character-ai-sale)
- [Fashion retailer Resolve says hackers stole payment card information](https://therecord.media/resolve-fashion-retailer-data-breach-payment-cards)
- [Florida warns that 4.9 million people had Social Security numbers leaked in financial aid site breach](https://therecord.media/florida-warns-5-million-affected-financial-aid-site-breach)
- [Syrian Electronic Army hacker gets prison time for attacks on Western targets](https://therecord.media/syrian-electronic-army-hacker-sentenced-three-years)
- [British spy agency cannot account for thousands of data storage devices, watchdog says](https://therecord.media/gchq-cannot-account-for-thousands-of-data-devices)

### Infosecurity Magazine
- [New Framework Puts Ransomware Resilience for AI Systems in Focus](https://www.infosecurity-magazine.com/news/framework-ransomware-resilience-ai/)
- [Chinese Actor Compromises US Government Network Via Chained PHP2Shell Exploit](https://www.infosecurity-magazine.com/news/chinese-us-government-chained-php2/)
- [Binance Hit by Record-Breaking $6.3bn Hack in Largest Cryptocurrency Heist in History](https://www.infosecurity-magazine.com/news/binance-record-hack-crypto-heist/)

### CyberScoop
- [China-backed threat group used agentic AI pentesting tool to compromise 140 sensitive targets in 11 days](https://cyberscoop.com/china-vapor-panda-agentic-ai-artex-campaign-crowdstrike/)
- [Apple notifications alert victims in 99 countries about mercenary spyware infections](https://cyberscoop.com/apple-spyware-notifications-pall-mall-process/)
- [California officials confirm grand jury subpoenas as states, civil groups brace to protect elections from federal encroachment](https://cyberscoop.com/california-election-subpoenas-doj-voter-rolls/)
- [Defense contractor pleads guilty to aiding North Korean remote worker scheme](https://cyberscoop.com/defense-contractor-guilty-north-korea-scheme-facilitator/)
- [Syrian hacker who served Assad regime gets 42 months in US prison](https://cyberscoop.com/syrian-hacker-ahmad-umar-agha-sentenced/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
- [Inside a malicious Claude Code-branded extension and its persistent SSH backdoor](https://www.microsoft.com/en-us/security/blog/2026/10/30/inside-malicious-claude-code-branded-cursor-extension-persistent-ssh-backdoor/)
- [From help desk impersonation to AD CS abuse: Investigating ESC1 and ESC8 intrusion paths](https://www.microsoft.com/en-us/security/blog/2026/10/30/help-desk-impersonation-ad-cs-abuse-investigating-esc1-esc8-intrusion-paths/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Friday, October 30th, 2026 https://isc.sans.edu/podcastdetail/10158, (Fri, Oct 30th)](https://isc.sans.edu/diary/rss/33472)

### Securelist (Kaspersky)
- [Filter generation in practice: from algorithms to LLMs](https://securelist.com/practical-filter-generation/121697/)

### CrowdStrike Blog
- [CrowdStrike Expands Falcon Adversary OverWatch Threat Hunting Across AI and Google Cloud](https://www.crowdstrike.com/en-us/blog/crowdstrike-expands-threat-hunting-across-ai-and-google-cloud/)
- [Build an Intelligence Advantage with Falcon Next-Gen SIEM](https://www.crowdstrike.com/en-us/blog/build-intelligence-advantage-with-falcon-next-gen-siem/)
- [CrowdStrike Agent Graph Shows How Agents Act on the Endpoint](https://www.crowdstrike.com/en-us/blog/crowdstrike-agent-graph-shows-how-agents-act-on-endpoint/)
- [VAPOR PANDA Uses AI-Driven ARTEX to Scale a Global Espionage Campaign](https://www.crowdstrike.com/en-us/blog/vapor-panda-uses-artex-to-scale-global-campaign/)
- [New Prompt Injection Techniques Cover Agent-Planning Attacks](https://www.crowdstrike.com/en-us/blog/new-prompt-injection-techniques-cover-agent-planning-attacks/)
- [When AI Guardrails Expose Vulnerabilities](https://www.crowdstrike.com/en-us/blog/when-ai-guardrails-expose-vulnerabilities/)
- [CrowdStrike 2026 Legal Threat Landscape Report: eCrime Leads Attacks, China Activity Intensifies](https://www.crowdstrike.com/en-us/blog/crowdstrike-2026-legal-threat-landscape-report/)
- [Obstacles to Weaponizing PHP2Shell Likely Constrain Immediate Widespread Exploitation](https://www.crowdstrike.com/en-us/blog/obstacles-to-weaponizing-php2shell-likely-constrain-exploitation/)
- [Why Organizations Secure AI Agents with Falcon Guardian](https://www.crowdstrike.com/en-us/blog/why-organizations-secure-ai-agents-with-falcon-guardian/)
- [CrowdStrike Protects Customers from Threats Delivered via PHP2Shell](https://www.crowdstrike.com/en-us/blog/crowdstrike-protects-customers-from-php-rce-zero-days/)

### FortiGuard Threat Signal
_No new items / feed unavailable this run._

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/
- https://api.phishstats.info/api/phishing?_sort=-id&_size=30 -> 502 Server Error: Bad Gateway for url: https://api.phishstats.info/api/phishing?_sort=-id&_size=30

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal