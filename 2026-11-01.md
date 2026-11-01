# Winjit Daily TI Digest — 2026-11-01

_Auto-generated. Window: last ~24h. Fetched at 2026-11-01T10:15:21.537844+00:00Z_

**At a glance:** 0 new KEV · 51 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-120189 | 10.0 | n/a | A vulnerability was identified in D-Link DIR-505 1.10B02. Affected is the function save_upload_file/mp_upload_file of the file /usr/bin/tftpd of the component TFTP Upload Filename Handler. The manipul |
| CVE-2026-120195 | 10.0 | n/a | A security vulnerability has been detected in WAVLINK WL-WN579A3-A 2026-03-10-94f93d4. The impacted element is the function set_wzdgwMesh of the file /cgi-bin/adm.cgi of the component Initial Setup Wi |
| CVE-2026-120198 | 10.0 | n/a | A vulnerability has been found in WAVLINK WL-WN530BE1-A V251117. Affected is the function con_check_read_finish of the file /protocol.csp. Such manipulation of the argument group_name/IP-FROM leads to |
| CVE-2026-120196 | 9.9 | n/a | A vulnerability was detected in WAVLINK WN579X3-D V250402. This affects the function port_forward of the file /cgi-bin/wapi.cgi. The manipulation of the argument Name results in os command injection.  |
| CVE-2026-120197 | 9.9 | n/a | A flaw has been found in WAVLINK WL-WN530HG4B M_V260724. This impacts the function port_forward of the file /cgi-bin/wapi.cgi. This manipulation of the argument Name causes os command injection. It is |
| CVE-2026-109220 | 9.8 | 0.5% | The PDF Invoice for WooCommerce + Drag and Drop Template Builder plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 7.1.1 via the 'customer_note' paramete |
| CVE-2026-116512 | 9.8 | 0.6% | The Project Manager – AI Powered Project Management, Task Management, Kanban Board & Time Tracker plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 4.1. |
| CVE-2026-119096 | 9.8 | 0.5% | The Uncanny Toolkit for LearnDash plugin for WordPress is vulnerable to Authentication Bypass in versions up to, and including, 3.8.2 via the `email` parameter of the `uo_login_action()` function. Thi |
| CVE-2026-118235 | 9.8 | 0.7% | The SimpleForm – Form Maker to Chat Apps with Quiz, Poll and Multi Lead Notifications plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 3.10.2 via the h |
| CVE-2026-120201 | 9.8 | n/a | Jpom 2.10.0 through 2.11.12 contains an authentication bypass vulnerability that allows unauthenticated attackers to gain super-administrator access by injecting query conditions into the JPOM-USER-TO |
| CVE-2026-120209 | 9.8 | n/a | AJ-Report through 1.7.1 signs share tokens with a hard-coded JWT secret, allowing attackers to forge valid Share-Tokens offline. Attackers can mint a token with reportCode 'dataSet' to access the test |
| CVE-2026-116557 | 9.1 | 0.3% | The WP Booking System - Booking Calendar plugin for WordPress is vulnerable to unauthorized modification of data due to a missing capability check on the wpbs_action_ajax_calendar_remove_note() functi |
| CVE-2026-89270 | 9.1 | 0.4% | The Popup Builder – Create highly converting, mobile friendly marketing popups. plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 4.4.5 This is due to th |
| CVE-2026-103882 | 9.1 | 0.8% | The Acadlix LMS – AI Quiz Maker, Online Exam & Course Plugin for WordPress plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation in the post_delete_ass |
| CVE-2026-104012 | 8.8 | 0.3% | The Rox Appointment Booking – Appointment Booking Scheduling Solution plugin for WordPress is vulnerable to Privilege Escalation via Mass Assignment in all versions up to, and including, 1.3.1 This is |
| CVE-2026-120070 | 8.8 | 0.3% | The User Frontend – Membership, User Registration, User Profile, User Directory & Content Restriction with Frontend Post Submission plugin for WordPress is vulnerable to Privilege Escalation in all ve |
| CVE-2026-116086 | 8.8 | 0.3% | A flaw was found in konflux-ci. An attacker with permission to trigger automated workflow runs can cause an information disclosure by providing crafted issue titles to workflow scripts. The affected s |
| CVE-2026-76010 | 8.8 | 1.1% | The Photo Gallery, Sliders, Proofing and Themes – NextGEN Gallery plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 4.4.1 via the render_image function. |
| CVE-2026-120203 | 8.8 | n/a | ShowDoc 2.8.14 before 3.9.6 contains a code injection vulnerability in its Mock feature that allows authenticated users to execute shell commands through mockjs templates. Attackers can store a templa |
| CVE-2026-114217 | 8.6 | 0.1% | A flaw was found in konflux-ci. Continuous Integration (CI) automation scripts store sensitive GitHub access tokens in plaintext on the runner without cleaning them up after execution. A local attacke |
| CVE-2026-116964 | 8.4 | 0.3% | A flaw was found in konflux-ci. An attacker with repository write access can achieve arbitrary code execution within the Continuous Integration and Continuous Delivery (CI/CD) workflow environment. By |
| CVE-2026-119977 | 8.1 | 0.6% | WordPress Core is vulnerable to Remote Code Execution in versions 4.7 through 7.1.3. This is due to predictable, web-accessible staging paths used during full-package core upgrades. This makes it poss |
| CVE-2026-103898 | 8.1 | 0.4% | The Wp Social Login and Register Social Counter plugin for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 3.2.2. This is due to the social login REST callback r |
| CVE-2026-117681 | 8.0 | 0.1% | A flaw was found in konflux-ci. This vulnerability allows privilege escalation when the user interface proxy automatically disables Transport Layer Security (TLS) certificate verification for connecti |
| CVE-2026-120205 | 8.0 | n/a | Thelia before 3.1.0 contains a stored cross-site scripting vulnerability in ForSomeCustomers::getSummary() that allows unauthenticated attackers to inject scripts via unescaped customer names. Attacke |
| CVE-2026-119163 | 7.5 | 0.3% | The FunnelKit Automations – Email Marketing Automation and CRM for WordPress & WooCommerce plugin for WordPress is vulnerable to time-based SQL Injection via the 'bwfan_cart_id' parameter in all versi |
| CVE-2026-120040 | 7.5 | 0.3% | The Mail logging & Catcher plugin for WordPress is vulnerable to Sensitive Information Exposure in all versions up to, and including, 2.2.0 via the 'message' parameter. This makes it possible for auth |
| CVE-2026-109197 | 7.5 | 0.5% | The WP Directory Kit plugin for WordPress is vulnerable to generic SQL Injection via the 'idfield' parameter in all versions up to, and including, 1.6.0 due to insufficient escaping on the user suppli |
| CVE-2026-120194 | 7.5 | n/a | A flaw was found in json-glib. The JSONPath slice evaluator used by json_path_query() can enter an infinite loop when given a slice expression with a negative step. An application that evaluates attac |
| CVE-2026-120208 | 7.5 | n/a | libheif 1.18.0 before 1.23.3 contains a heap-based buffer overflow vulnerability in unc_decoder_mixed_interleave::processTile() that allows attackers to write out of bounds by supplying chroma compone |
| CVE-2026-118147 | 7.4 | n/a | Improper certificate validation in Visual Studio allows an unauthorized attacker to perform spoofing over a network. |
| CVE-2026-120191 | 7.3 | n/a | A weakness has been identified in Presenton up to 0.9.11-beta. Affected by this issue is some unknown functionality of the component API. This manipulation causes missing authentication. It is possibl |
| CVE-2026-109234 | 7.2 | 0.4% | The Meow Lightbox plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'post_content (bbPress reply body)' parameter in all versions up to, and including, 5.6.4 due to insufficien |
| CVE-2026-109997 | 7.2 | 0.4% | The Ninja Forms – Contact Form Builder with Calculators, Quizzes, Signatures & AI Form Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'formData.extra' parameter in a |
| CVE-2026-116520 | 7.2 | 0.4% | The PPWP – Password Protect Pages plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment / shortcode attribute desc_below_form (and placeholder as the marker-smuggling help |
| CVE-2026-107653 | 7.2 | 0.3% | The SureCart – Ecommerce Made Easy For Selling Physical Products, Digital Downloads, Subscriptions, Donations, & Payments plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'com |
| CVE-2026-107750 | 7.2 | 0.3% | The PDF Invoices & Packing Slips for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'billing_address.first_name / last_name / company, customer_note' parameter i |
| CVE-2026-111254 | 7.2 | 0.3% | The W3 Total Cache plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 2.10.7 due to insufficient input sanitization and |
| CVE-2026-115840 | 7.2 | 0.2% | The VikRentCar Car Rental Management System plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'poplink' parameter in all versions up to, and including, 1.4.9 due to insufficien |
| CVE-2026-116522 | 7.2 | 0.2% | The Relevanssi – A Better Search plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 4.28.5 due to insufficient input sa |
| CVE-2026-116548 | 7.2 | 0.2% | The VikRentCar Car Rental Management System plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'optionals' parameter in all versions up to, and including, 1.4.10 due to insuffic |
| CVE-2026-118070 | 7.2 | 0.2% | The Welcart e-Commerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'gid' parameter in all versions up to, and including, 2.12.5 due to insufficient input sanitization and |
| CVE-2026-119065 | 7.2 | 0.2% | The Shipping Zones by Drawing for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'szbd-picked' checkout parameter in versions up to, and including, 3.3.0 The szb |
| CVE-2026-119089 | 7.2 | 0.2% | The ThirstyAffiliates – Affiliate Links, Link Branding, Link Tracking & Marketing Plugin plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions u |
| CVE-2026-119162 | 7.2 | 0.2% | The User Submitted Posts – Enable Users to Submit Posts from the Front End plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via the 'user-submitted-content' parameter in all |
| CVE-2026-107759 | 7.2 | 0.3% | The WPO365 | MICROSOFT 365 GRAPH MAILER plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'Subject (via wp_mail/PHPMailer, e.g. CF7 your-subject)' parameter in all versions up  |
| CVE-2026-118057 | 7.2 | 0.2% | The Shield Security – Smart Bot Blocking, Brute-Force Login Protection & File Scanning plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'REQUEST_URI' parameter in all versions |
| CVE-2026-110530 | 7.2 | 0.2% | The FeedWordPress plugin for WordPress is vulnerable to Stored Cross-Site Scripting in versions up to, and including, 2026.0517 via syndicated RSS/Atom feed content. The plugin's SyndicatedPost::sanit |
| CVE-2026-120075 | 7.2 | 0.2% | The WP Activity Log plugin for WordPress is vulnerable to Stored Cross-Site Scripting in all versions up to, and including, 5.6.1 due to insufficient input sanitization and output escaping. This makes |
| CVE-2026-120114 | 7.2 | 0.4% | The Debug Log Manager – Conveniently Monitor and Inspect Errors plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'message (and pageUrl)' parameter in all versions up to, and i |
| CVE-2026-120207 | 7.1 | n/a | Thelia Page Module before 2.0.4 contains a cross-site request forgery vulnerability that allows remote attackers to delete page tags, documents and images by abusing back-office delete routes lacking  |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-wh4p-gf4j-mjqc | CVE-2026-120218 | low | A flaw has been found in Typemill up to 2.26.0. The impacted element is the function... |
| GHSA-h6r7-8xvv-hr33 | CVE-2026-120217 | low | A vulnerability was detected in Delgan loguru 0.7.3. The affected element is the function... |
| GHSA-cq8m-m2p5-jxxm | CVE-2026-120198 | critical | A vulnerability has been found in WAVLINK WL-WN530BE1-A V251117. Affected is the function... |
| GHSA-wfgm-582m-23r9 | CVE-2026-118168 | unknown | The MapPress  WordPress plugin before 2.97.15 does not restrict which user's data its front-end... |
| GHSA-r3f9-h5m2-87ch | CVE-2026-107343 | unknown | The Kali Forms — Contact Form & Drag-and-Drop Builder WordPress plugin before 2.4.30 does not... |
| GHSA-hqj9-3pgq-546r | CVE-2026-113481 | unknown | The Media Library Assistant WordPress plugin before 3.44 does not check that the requesting user... |
| GHSA-3h5r-7p7q-xv68 | CVE-2026-107342 | unknown | The Kali Forms — Contact Form & Drag-and-Drop Builder WordPress plugin before 2.4.30 does not... |
| GHSA-894j-4953-62g7 | CVE-2026-113482 | unknown | The Media Library Assistant WordPress plugin before 3.44 does not escape one of its shortcode... |
| GHSA-jq5g-pp5w-q8h6 | CVE-2026-120197 | high | A flaw has been found in WAVLINK WL-WN530HG4B M_V260724. This impacts the function port_forward... |
| GHSA-fmc2-w58f-qqpv | CVE-2026-120196 | high | A vulnerability was detected in WAVLINK WN579X3-D V250402. This affects the function port_forward... |
| GHSA-3wx6-ffgj-fwjg | CVE-2026-120195 | critical | A security vulnerability has been detected in WAVLINK WL-WN579A3-A 2026-03-10-94f93d4. The... |
| GHSA-89vm-wj4q-hr3r | CVE-2026-120252 | medium | imagecodecs 2023.1.23 through 2026.10.10 contains a stack-based buffer overflow vulnerability in... |
| GHSA-j736-6c4x-7rx7 | CVE-2026-120251 | medium | imagecodecs 2026.3.6 through 2026.10.10 contains an infinite loop vulnerability in... |
| GHSA-j499-8gjf-h2jf | CVE-2026-120249 | medium | Thelia Back-office Default Twig Template before 1.1.1 contains a cross-site request forgery... |
| GHSA-pxjx-g7g8-jwq6 | CVE-2026-120250 | medium | OpenAlgo 1.0.0.29 before 2.0.3.1 contains an improper certificate validation vulnerability in... |
| GHSA-rgjm-77r7-28xg | CVE-2026-120192 | medium | A security vulnerability has been detected in Presenton up to 0.9.11-beta. This affects an... |
| GHSA-ggpr-cj64-vcq3 | CVE-2026-120190 | low | A security flaw has been discovered in PostyBirb Plus up to 3.1.75. Affected by this... |
| GHSA-6hg3-f9xg-2hg4 | CVE-2026-120244 | medium | FFmpeg 2.1 through 9.0.2 contains a use of uninitialized resource vulnerability in the PCX... |
| GHSA-76cq-jhfp-r489 | CVE-2026-120246 | medium | FFmpeg 4.4 through 9.0.2 contains a use of uninitialized variable vulnerability in the CDXL... |
| GHSA-xxr4-v6q3-9x28 | CVE-2026-120248 | medium | Thelia before 3.1.1 contains a stored cross-site scripting vulnerability that allows... |
| GHSA-rp9m-mw76-ppmp | CVE-2026-120247 | medium | FFmpeg 2.3 through 9.0.2 contains a use of uninitialized resource vulnerability in the Huffyuv... |
| GHSA-c346-mwjq-88hv | CVE-2026-120245 | medium | FFmpeg 0.10 through 9.0.2 contains a use of uninitialized resource vulnerability in... |
| GHSA-hcx6-ffr8-ff2w | CVE-2026-120243 | medium | FFmpeg 2.0 through 9.0.2 contains a use of uninitialized variable vulnerability in the Go2Meeting... |
| GHSA-jxrg-fcrf-gm4j | CVE-2026-120191 | medium | A weakness has been identified in Presenton up to 0.9.11-beta. Affected by this issue is some... |
| GHSA-2j25-rfrh-cphw | CVE-2026-120189 | critical | A vulnerability was identified in D-Link DIR-505 1.10B02. Affected is the function... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| EVINOKS | Barracuda | TR | 2026-11-01T01:50:47.238640+00:00 |
| Danser | qilin | US | 2026-11-01T00:39:08.118503+00:00 |
| JHAMF Group | Vexy Ransomware | BD | 2026-10-31T19:04:20.888985+00:00 |
| System Soft | Vexy Ransomware | BG | 2026-10-31T19:04:42.079141+00:00 |
| Straze Garden Center | payload |  | 2026-10-31T14:31:26.317572+00:00 |
| Kraft Lernen | payload | DE | 2026-10-31T14:30:05.303563+00:00 |
| SALEG (Sachsen-Anhaltische Landesentwicklungsgesellschaft mbH) | payload | DE | 2026-10-31T14:28:42.041214+00:00 |
| Phoenix Charter Academy | rhysida | US | 2026-10-31T12:35:39.959568+00:00 |
| Ivan Smith Furniture | sarcoma | PH | 2026-10-31T10:31:38.535322+00:00 |
| Gamdom V2 | Whitearmor |  | 2026-10-31T10:30:39.069282+00:00 |
| Holcim | emperador | CH | 2026-10-31T09:53:09.832637+00:00 |
| quevedo-ponce.com | safepay | EC | 2026-10-31T08:04:05.227635+00:00 |
| mars-semi.com.tw | safepay | TW | 2026-10-31T08:03:30.155489+00:00 |
| Rood Trucking | safepay | US | 2026-10-31T08:02:56.729937+00:00 |
| grifosespinoza.com | safepay | PE | 2026-10-31T08:02:23.894723+00:00 |
| jumonji-u.ac.jp | safepay | JP | 2026-10-31T08:01:50.416318+00:00 |
| everon.com.ar | safepay | AR | 2026-10-31T08:01:16.169020+00:00 |
| goldencrops.com.tw | safepay | TW | 2026-10-31T08:00:42.784467+00:00 |
| layam.com | safepay | IL | 2026-10-31T08:00:09.488761+00:00 |
| uaa.mx | safepay | MX | 2026-10-31T07:59:35.931824+00:00 |

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
| 138.226.239.233 | 12 |
| 138.226.239.234 | 12 |
| 14.34.249.175 | 10 |
| 2.57.122.238 | 9 |
| 64.62.197.167 | 9 |
| 77.90.185.20 | 9 |
| 103.159.2.113 | 9 |
| 167.94.146.54 | 9 |
| 196.189.236.67 | 9 |
| 199.165.159.89 | 9 |
| 3.129.187.38 | 8 |
| 3.130.168.2 | 8 |
| 12.156.67.18 | 8 |
| 18.218.118.203 | 8 |
| 35.202.9.133 | 8 |
| 45.148.10.152 | 8 |
| 45.148.10.240 | 8 |
| 46.151.178.14 | 8 |
| 51.75.253.68 | 8 |
| 64.62.197.77 | 8 |

### OpenPhish (live phishing URLs)
- http://ta.gdffuy.xyz/
- https://sharemyhtml.com/p/M1yBCNzLRG
- https://cl.realizarconsultaco.com/
- https://jisooooo0201.github.io/Instagram.html
- https://start-re-trresezer.gitbook.io/
- https://knkddkmlmeaedd.weebly.com/
- https://elaf.com.eg/adobe-document.co/
- http://gopayy-indonesiaz.resmi-wsl2.my.id/
- https://s.team-yr.com/admin
- https://s.team-yr.com/
- http://oosoftlms.weebly.com/
- https://www.roblox.com.ss/users/8795648614/profile
- https://apenasate-hoje2026.lol/
- https://mydpd.cyobn.help/track-ch
- https://fighterzone.github.io/Fb/
- https://8s1q2g-qw999agreg-mbtz1m8p9z2-fsgc12.pages.dev/welcome_aboard?welcome=10009568686956300&token248=10009568686956300&name_token136=Espumas%20Chaideappeals%2Fsubmit-appeal-form%2Freturn%2F
- https://account-verify-system.netlify.app/
- https://store.communityartsection.com/workshop/AWP-AncientHeritage/
- https://uv-bitli-compo.pages.dev/help/contact/477657948684314
- https://uv-bitli-compo.pages.dev/help/contact/201235025373238appeals/submit-appeal-form/return/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://knkddkmlmeaedd.weebly.com/ |
| N/A | https://elaborate-medovik-506f14.netlify.app/ |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AaSxoQyQEeCdGiNQploah5nAij7vrMqrlVIHby1Q4v_ARx9kttGkmffM4ARVCnkvjXQyGpUqW4kQNA&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBgld4pMwBUwvx5GozazmV_LthslA-Wc6yemNHyuT8fVV_HdXHGToupkagQnAYk_QkC52XBbh7Jw&dsh=S2016068275%3A1793527793705371 |
| N/A | https://ipkobznzs.sviluppo.host/index.php?sid=034b54662253e0b4ab27e170fc1e9a35 |
| N/A | https://58596767.com/jzwKLSAquo.jp.net |
| N/A | https://pageseuc1.actmkt.com/(S(00zn4ujdsqo5hyt5ukj3v15u))/l/c5X8MfZz6j9Y7Fto3LAd |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=ASKXGp0_nbFzdHoBsG_d6znGlWE063OUXUJ-liVgQNfJJB3wA_mip4wV6In-9Cchxtm7MSHwtubxoQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBgldVdFMggvqqpam4Smb9As9jyeBEqUndo6-jGD6uUzXbqC7mB8v_WLHqKP6dnzaeRu61YbbVTg&dsh=S37364240%3A1793523908338550 |
| N/A | https://secure-xdomain-74372.w-group.shop/ |
| N/A | https://www.att.com/activearmorapp?_branch_match_id=1645364390017666208&utm_source=AT%26T%20App&_branch_referrer=H4sIAAAAAAAAA8soKSkottLXT0wuySxLTSzKzS%2FSzS%2FKTM%2FM00ssKdFLzs%2FV9wtL8U6KLCzzMUqyrytKTUstKsrMS49PKsovL04tsnXOKMrPTQUAZUf3KkgAAAA%3D |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bffgf=1&amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=Af_xneGpinflONH_c3iB5WwVV1C6BSPwAwpudWnjxe8BcKRMcZLFgAnlzpjtHVk0QMFIUm6AcMYv&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBgldB1HMhjCSd0RmyOCZnxxHhjDEqrQkreaZIQrQvjDZtbfx4f7k-7cuXErQVcMe6IQFTYhXq&dsh=S-1895047417%3A1793523524070814 |
| N/A | https://xml-v4.pushub.net/click?i=JTIicJCHwds_0 |
| N/A | https://away.vk.ru/away.php?rh=872c9548-9962-4007-a2b6-95c47fdd2df0 |
| N/A | https://away.vk.ru/away.php?rh=cf73fd62-de89-43e5-9440-c364aa98555b |
| N/A | https://checkfortnite.cc/ |
| N/A | https://away.vk.ru/away.php?rh=184acb2d-f118-493f-8f55-e6abe29184ce |
| N/A | https://away.vk.ru/away.php?rh=6ca286bb-a1fb-4877-84da-005b3c5e4caf |
| N/A | https://away.vk.ru/away.php?rh=67072ecd-dfa2-44f2-9bf2-cbe012dc5639 |
| N/A | https://skinsmonkey.com?referrer=pid%3D1%26af_tranid%3DMTc2MTI5Nzk2Nzg3ODI5MTExMjk%3D |
| N/A | http://49.51.43.12/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=AWnogHe_pDujLaO-hl3d_3DQFjS6PW6JGM3LRrD13mxmiaQWTJuHz9b6nwmaSIh76M5SMOelnJex7g&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBglejpgKH-Hf9Y1dBF1O6XtpiKT8wxSQeqD9ZQSe4lgFR7wSX6wvwT2tD3Ff8E0xBhfp1-EzmZw&dsh=S1495491951%3A1793522149343612 |
| N/A | https://away.vk.ru/away.php?rh=9a2d725c-79dc-4826-8646-d4bcfed6a31b |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| e84ebc6b9b7ac39785254a0ef0caddd96f51aa99 | Vidar C&C |
| eb3a71b4803774f788e85831b9e5821c6c62ada1 | Vidar C&C |
| f9542c3038dc3632d71c1e3735408c8577e8568a | PureRAT C&C |
| 3b1a9b1ca40319bdd405d0dd09923c58d250baa0 | ACRStealer C&C |
| 44c6ec85d52ecb270148701bc655e2af697e010f | ACRStealer malware distribution |
| 9d47db624532e58342c036323af03246682b8535 | ACRStealer malware distribution |
| d22e586d60cc68c0488c7ede7b46ebc0341cd3ce | Vidar C&C |
| cf7e51ae64c43d0e0ecf6f00bddb8899f51af644 | Vidar C&C |
| 47477bdad9212d35e0ad21867e929825d5c668a7 | OffLoader C&C |
| c66e709b5d5107c52235593e2e70293f810817e0 | PureRAT C&C |
| 7f7f0cc383cc408a31be236f521a474f9fa955bf | Vidar C&C |
| c81dfb846d72043d82cfedada7b5fbc3f1ed956d | AsyncRAT C&C |
| de045f977bb3fcb870a7c70433ec3c4055b4df56 | AokigaharaStealer C&C |
| 794a98bb8dfb1c8707541d2f1136fc7c1faa123f | Malware C&C |
| aebfe1d6a7db6458477771a467698c52ec1cd181 | Vidar C&C |
| b8b817853b031f3c2ef9ff332422a2f75cdafb14 | Vidar C&C |
| 8bc6b066cdd4399e5217c58236bb0f32971a4d49 | OffLoader C&C |
| a3e3e53c9b5eb4d1d1197181c599f07ca61b3c9e | Vidar C&C |
| d7d1025725506635e295b7a5eb61c2162f2a1f93 | Vidar C&C |
| 88dfcb0baeaaec06b4973eeb6b8bf76e7ff16315 | ConnectWise C&C |

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
- 1.10.160.127
- 1.12.55.42
- 1.13.181.113
- 1.14.240.247
- 1.14.64.144
- 1.15.221.192
- 1.15.42.91
- 1.159.54.33
- 1.162.226.183
- 1.173.231.52
- 1.201.146.109
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.220.198.126
- 1.222.42.237
- 1.234.27.159
- 1.234.80.94
- 1.235.183.146
- 1.238.106.229

### CINS Army (poorly-rated IPs)
- 1.170.196.186
- 1.193.63.167
- 1.20.151.114
- 1.2.252.192
- 1.215.138.43
- 1.24.16.10
- 1.24.16.121
- 1.24.16.129
- 1.24.16.134
- 1.24.16.135
- 1.24.16.155
- 1.24.16.189
- 1.24.16.190
- 1.24.16.191
- 1.24.16.35
- 1.24.16.48
- 1.24.16.71
- 1.24.16.8
- 1.24.18.131
- 1.24.229.200

## News (last ~36h, across outlets)
### The Hacker News
- [CVSS 10.0 LXD, MicroCloud Flaw Lets Attackers Impersonate Trusted Clients Without a Private Key](https://thehackernews.com/2026/11/critical-lxd-and-microcloud-flaw-cvss.html)
- [Hackers Steal About $2.7 Million From Polymarket Traders via Hijacked DebugBear Script](https://thehackernews.com/2026/11/hackers-steal-about-27-million-from.html)
- [FBI Links North Korea's TraderTraitor to Record $6.43 Billion Binance Crypto Heist](https://thehackernews.com/2026/11/fbi-links-north-koreas-tradertraitor-to.html)
- [NetamLoader Malware Targets Government Windows 10 Systems in Asia via .NET Injection](https://thehackernews.com/2026/11/netamloader-malware-targets-government.html)
- [Chainalysis Confirms Intrusion Into Internal Tools and Exposure of Customer Identity Data](https://thehackernews.com/2026/10/chainalysis-confirms-intrusion-into.html)
- [Attackers Chain Three Ivanti Connect Secure Flaws to Gain Unauthenticated Root Access](https://thehackernews.com/2026/10/attackers-chain-three-ivanti-connect.html)
- [A Shared ChatGPT Link Could Run Attacker Code in Your Session and Read Private Chats](https://thehackernews.com/2026/10/a-shared-chatgpt-link-could-run.html)
- [Cloudflare Reports 18.2 Million Network-Layer DDoS Attacks in Q3, Up 38%](https://thehackernews.com/2026/10/cloudflare-reports-182-million-network.html)

### BleepingComputer
- [Northflank security breach leads to abuse of customers' AI API keys](https://www.bleepingcomputer.com/news/security/northflank-security-breach-leads-to-abuse-of-customers-ai-api-keys/)
- [New Android SMS of Death exploit can remotely crash unpatched phones](https://www.bleepingcomputer.com/news/security/new-android-sms-of-death-exploit-can-remotely-crash-unpatched-phones/)
- [Reddit to lock content behind logins to fight scrapers](https://www.bleepingcomputer.com/news/security/reddit-to-lock-content-behind-logins-to-fight-scrapers/)
- [From Beginner to Bug Hunter: Learning Cybersecurity in the AI Era.](https://www.bleepingcomputer.com/news/security/from-beginner-to-bug-hunter-learning-cybersecurity-in-the-ai-era/)
- [Chainalysis discloses data breach from "offensive agentic techniques"](https://www.bleepingcomputer.com/news/security/chainalysis-discloses-data-breach-from-offensive-agentic-techniques/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
_No new items / feed unavailable this run._

### SecurityWeek
- [Syrian Hacker Gets Prison Time in US After Over a Decade on the Run](https://www.securityweek.com/syrian-hacker-gets-prison-time-in-us-after-over-a-decade-on-the-run/)

### The Record
_No new items / feed unavailable this run._

### Infosecurity Magazine
_No new items / feed unavailable this run._

### CyberScoop
_No new items / feed unavailable this run._

### Cisco Talos
- [Appraisal by AI: Model-driven victim prioritization in the VOLTA infostealer](https://blog.talosintelligence.com/appraisal-by-ai-model-driven-victim-prioritization-in-the-volta-infostealer/)

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
- [Inside a malicious Claude Code-branded extension and its persistent SSH backdoor](https://www.microsoft.com/en-us/security/blog/2026/10/30/inside-malicious-claude-code-branded-cursor-extension-persistent-ssh-backdoor/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [OneNote File Extraction, (Sun, Nov 1st)](https://isc.sans.edu/diary/rss/33478)
- [Wireshark 5.0.0rc1 Release, (Sat, Oct 31st)](https://isc.sans.edu/diary/rss/33476)
- [YARA-X 1.22.1 Release, (Sat, Oct 31st)](https://isc.sans.edu/diary/rss/33474)
- [YARA-X 1.22.0 Release, (Sun, Oct 25th)](https://isc.sans.edu/diary/rss/33454)

### Securelist (Kaspersky)
_No new items / feed unavailable this run._

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

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal