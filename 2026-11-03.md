# Winjit Daily TI Digest — 2026-11-03

_Auto-generated. Window: last ~24h. Fetched at 2026-11-03T10:37:37.182284+00:00Z_

**At a glance:** 0 new KEV · 53 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-120276 | 10.0 | n/a | A weakness has been identified in WAVLINK WN536AX6-A V260507_2.0.0. This vulnerability affects the function sub_416760 of the file /bin/ioos of the component Web Management Interface. This manipulatio |
| CVE-2026-120277 | 10.0 | n/a | A security vulnerability has been detected in WAVLINK WN536AX6-A V260507_2.0.0. This issue affects the function sub_41a1d8 of the file /bin/ioos of the component WireGuard CLI Group Handler. Such mani |
| CVE-2026-120280 | 10.0 | n/a | A vulnerability has been found in WAVLINK WN536AX6-A V260507. The impacted element is the function wireguard_cli_group handler of the file /protocol.csp of the component WireGuard. The manipulation of |
| CVE-2026-120281 | 10.0 | n/a | A vulnerability was found in WAVLINK WN536AX6-A V260507. This affects the function strcpy of the file /protocol.csp of the component OpenVPN Handler. The manipulation of the argument openvpn_ip result |
| CVE-2026-120345 | 10.0 | n/a | A vulnerability was found in WAVLINK WN551X3-A M51X3_V251020-WO-182e965. This impacts the function sub_41a430 of the file /bin/ioos of the component DNS Resolution Handler. Performing a manipulation o |
| CVE-2026-120442 | 9.8 | n/a | ape-volo-admin before 3.6.1 contains an authentication bypass vulnerability that allows unauthenticated attackers to forge administrator tokens using a hardcoded JWT signing key in appsettings.json. A |
| CVE-2026-77876 | 9.8 | n/a | Control Web Panel (CWP) before webpanel_version 1.16 contains an OS command injection vulnerability in the protected_directory user panel module that allows attackers to execute arbitrary commands by  |
| CVE-2026-102435 | 9.8 | n/a | The Ultra Addons for Contact Form 7 plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation in the _getObjAttr function in all versions up to, and includ |
| CVE-2026-86596 | 9.8 | n/a | The s2Member plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, <= 260927 via the 'item_name' parameter parameter. This is due to insufficient sanitizati |
| CVE-2026-120534 | 9.8 | n/a | The Advanced Custom Fields: Extended PRO plugin for WordPress is vulnerable to Limited Code Injection in all versions up to, and including, 0.9.2.6 via the render_field function. This is due to insuff |
| CVE-2026-120446 | 9.4 | n/a | madong-admin-saas through 5.1.4 contains a missing authentication vulnerability in the platform tenant management API because the 'platformapi' middleware key never matches the 'platform' application. |
| CVE-2026-120518 | 9.1 | n/a | The BuddyPress XProfile Image Field plugin for WordPress is vulnerable to arbitrary file deletion in all versions up to, and including, 3.1.0. This is due to bpxp_image_field_update_on_user_activation |
| CVE-2026-120311 | 8.8 | n/a | Network-AI from 5.13.4 before 5.15.5 contains a path traversal vulnerability in FileJobStore that allows attackers to read or delete arbitrary .json files by supplying traversal sequences in the job i |
| CVE-2026-120315 | 8.8 | n/a | LobeHub Chat from 1.84.26 before 2.1.49 contains a path traversal vulnerability that allows authenticated users to write arbitrary files by supplying unsanitized file names to writeTempFile(). Attacke |
| CVE-2026-73695 | 8.8 | n/a | Control Web Panel (CWP) before webpanel_version 1.16 contains a path traversal vulnerability in services/users/index.php that allows attackers to include arbitrary local PHP files by supplying an unsa |
| CVE-2026-73697 | 8.8 | n/a | Control Web Panel (CWP) before webpanel_version 1.16 contains an arbitrary file write and OS command injection vulnerability in the phpini_editor user panel module that allows attackers with access to |
| CVE-2026-29508 | 8.8 | n/a | ReadyMedia (formerly MiniDLNA) versions 1.3.0 through 1.3.3 contain a stack-based buffer overflow vulnerability that allows remote attackers to corrupt stack memory by crafting a malicious DFF audio f |
| CVE-2026-107441 | 8.8 | n/a | An out-of-bounds write vulnerability in the CGI program of Zyxel GS1900-24E firmware versions through 2.90(AAHK.2)C0 could allow an unauthenticated adjacent attacker  to exploit the flaw and potential |
| CVE-2026-76955 | 8.8 | n/a | A buffer overflow vulnerability in the zdp_wtp binary in Zyxel NWA110AX firmware versions through 7.12(ABTG.0)C0 could allow a LAN-based attacker to escalate privileges on an affected device. |
| CVE-2026-104080 | 8.4 | n/a | Control Web Panel (CWP) before webpanel_version 1.30 contains an OS command injection vulnerability in the loopback API /valid_token/ route that allows unauthenticated attackers to execute arbitrary c |
| CVE-2026-77878 | 8.4 | n/a | Control Web Panel (CWP) before webpanel_version 1.30 contains an OS command injection vulnerability in the loopback API database restore route /v1/restoredatabase/, where the restoreDBBackup() handler |
| CVE-2026-77880 | 8.4 | n/a | Control Web Panel (CWP) before webpanel_version 1.16 contains an OS command injection vulnerability in the loopback API password change route /newpass/, which runs as root. An attacker can inject arbi |
| CVE-2026-120324 | 8.3 | n/a | A weakness has been identified in Aklivity Zilla up to 1.3.4/2.4.7/2.5.0-rc2. The affected element is the function Path.resolve of the file FileSystemServerFactory of the component http-filesystem Bin |
| CVE-2026-119736 | 8.2 | n/a | Attendo (formerly Petpooja Payroll) Admin Android application version 3.0.13 and earlier contains a hard-coded credentials vulnerability that allows attackers to extract production MQTT broker credent |
| CVE-2026-120538 | 8.1 | n/a | The Easy Digital Downloads plugin for WordPress is vulnerable to authentication bypass leading to administrator account takeover in all versions up to, and including, 3.7.2. During a PayPal guest chec |
| CVE-2026-120574 | 8.1 | n/a | The SureCart plugin for WordPress is vulnerable to unauthenticated account takeover in all versions up to, and including, 4.9.5. The passwordless one-time-code login REST route (VerificationCodeContro |
| CVE-2026-120577 | 8.1 | n/a | The FluentCart A New Era of eCommerce – Faster, Lighter, and Simpler plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation in the deleteFile function i |
| CVE-2026-120431 | 7.8 | n/a | Netpbm before 10.86.51, 11.x before 11.02.29, and 11.03 before 11.15.07 contains a heap-based buffer overflow in sgitopnm's readChannels() function when processing RLE-compressed SGI images. Attackers |
| CVE-2026-120434 | 7.8 | n/a | Netpbm before 10.86.51, 11.x before 11.02.30, and 11.03 before 11.15.08 contains a stack-based buffer overflow in picttoppm's scanPoly() function in converter/ppm/picttoppm.c. Attackers can supply a c |
| CVE-2026-120435 | 7.8 | n/a | Netpbm before 10.86.51, 11.x before 11.02.30, and 11.03 before 11.15.08 contains a heap buffer overflow in xpmtoppm caused by an unvalidated characters-per-pixel value in the XPM header. Attackers can |
| CVE-2026-120438 | 7.8 | n/a | QuickJS-NG before 0.16.0 contains an integer overflow in js_proxy_get_own_property_names() in quickjs.c that causes a heap buffer overflow on 32-bit hosts. Attackers running JavaScript can return a la |
| CVE-2026-120833 | 7.8 | n/a | labbench before 0.46.1 contains a deserialization of untrusted data vulnerability in read() and read_relational() that passes any file with a .p or .pickle extension to pandas.read_pickle based on the |
| CVE-2026-77879 | 7.7 | n/a | Control Web Panel (CWP) before webpanel_version 1.16 contains a SQL injection vulnerability in the loopback API authentication gate access_token(), which connects to MySQL as root and interpolates att |
| CVE-2026-120426 | 7.5 | n/a | OpenCSG CSGHub through v2.6.0-ce contains an authorization bypass vulnerability in the unauthenticated file resolve route that allows remote attackers to read private repository files. Attackers can i |
| CVE-2026-119731 | 7.5 | n/a | Munshi (by Petpooja) before 2026-06-30 contained a payment bypass vulnerability in its subscription payment webhook at POST /api/payment/order/webhook, which lacks webhook authentication, cryptographi |
| CVE-2026-120752 | 7.5 | n/a | PyMuPDF 1.25.3 before 2.0 contains a stack-based buffer overflow vulnerability in JM_set_annot_callout_line() that copies a caller-supplied number of callout points into a fixed three-element stack ar |
| CVE-2026-120559 | 7.5 | n/a | The Contact Form Extender for Divi Builder plugin for WordPress is vulnerable to Arbitrary File Deletion due to insufficient file path validation in the cfefd_remove_uploaded_file() function in all ve |
| CVE-2026-120459 | 7.4 | n/a | python-jose through 3.5.0 contains an authentication bypass vulnerability that allows unauthenticated attackers to forge JWTs because HMACKey and CryptographyHMACKey accept zero-length HMAC secrets. W |
| CVE-2026-120314 | 7.3 | n/a | Network-AI from 5.14.0 before 5.15.5 contains a missing authentication vulnerability in the A2AServer class that allows unauthenticated attackers to access task operations when no secret is configured |
| CVE-2026-120336 | 7.3 | n/a | A vulnerability was found in VStarcam O-KAM Client 1.3.3.32. Affected by this vulnerability is the function FUN_10003EA0 in the library DevDll_925.dll. The manipulation results in stack-based buffer o |
| CVE-2026-120337 | 7.3 | n/a | A vulnerability was determined in VStarcam O-KAM SuperIPCam 1.3.3.32. Affected by this issue is the function FUN_005a2d44 of the file SuperIPCam.exe of the component P2P Session Teardown. This manipul |
| CVE-2026-120341 | 7.3 | n/a | A security vulnerability has been detected in mathurvishal CloudClassroom-PHP-Project. Impacted is an unknown function of the file studentdetails.php. The manipulation leads to execution after redirec |
| CVE-2026-120342 | 7.3 | n/a | A vulnerability was detected in mathurvishal CloudClassroom-PHP-Project. The affected element is an unknown function of the file viewquery.php. The manipulation of the argument eid results in sql inje |
| CVE-2026-120347 | 7.3 | n/a | A vulnerability was determined in dayrui XunRuiCMS up to 4.7.4. Affected is the function View of the file dayrui/Fcms/Core/View.php of the component Member Module. Executing a manipulation of the argu |
| CVE-2026-120487 | 7.2 | n/a | LaraDashboard before 1.4.5 contains an incorrect authorization vulnerability in SettingPolicy::manageCoreUpgrades() that allows non-Superadmin administrators with settings.edit to access Superadmin-on |
| CVE-2026-120558 | 7.2 | n/a | The Advanced Shipment Tracking for WooCommerce plugin for WordPress is vulnerable to SQL Injection via the `tracking_provider` parameter of the `POST /wp-json/wc-ast/v3/orders/<order_id>/shipment-trac |
| CVE-2026-105978 | 7.2 | n/a | Improper input validation in management control functions may allow a remote attacker with high privileges to inject operating system commands and execute them with root privileges. |
| CVE-2026-105979 | 7.2 | n/a | Improper input validation in the ZeroTier VPN function may allow a remote attacker with high privileges to inject system commands and execute them with root privileges. |
| CVE-2026-105980 | 7.2 | n/a | Improper input validation in the WireGuard VPN function may allow a remote attacker with high privileges to inject system commands and execute them with root privileges. |
| CVE-2026-105981 | 7.2 | n/a | Improper input validation in the Digital I/O function may allow a remote attacker with high privileges to inject operating system commands and execute them with root privileges. |
| CVE-2026-105982 | 7.2 | n/a | Improper input validation in the IPsec VPN function may allow a remote attacker with high privileges to inject system commands and execute them with root privileges. |
| CVE-2026-120439 | 7.0 | n/a | QuickJS-NG before 0.16.0 contains an integer overflow in js_typed_array_sort() in quickjs.c that allows attackers to cause a heap buffer overflow on 32-bit hosts. Attackers who can run JavaScript can  |
| CVE-2026-91909 | 4.6 | n/a | Dell OpenManage Enterprise, versions prior to 4.8.0, contains an Improper Neutralization of Argument Delimiters in a Command ('Argument Injection') vulnerability. A low privileged attacker with adjace |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-cmmf-wccr-xrrh | CVE-2026-92610 | unknown | In esmf-sdk-py-aspect-model-loader versions 2.1.2 to 2.2.1, the Aspect Model loader resolves... |
| GHSA-g2hh-vxh7-5vwh | CVE-2026-91075 | medium | The Eupago Gateway For Woocommerce WordPress plugin from 4.5.0 through 4.7.5 does not verify the... |
| GHSA-c35r-j59w-5p7f | CVE-2026-121022 | critical | Use of Default Password (CWE-1393) in the web client in AxxonSoft Axxon One before 3.0.0 on... |
| GHSA-9w8f-4c2r-vh34 | CVE-2026-118448 | medium | A use of uninitialized memory vulnerability in the pybddisasm Python bindings affects nd_to_text.... |
| GHSA-87vx-w47q-9fj9 | CVE-2026-121023 | medium | Insertion of Sensitive Information into Log File (CWE-532) in the ARP Agent component in... |
| GHSA-j27f-gvg7-cxpv | CVE-2026-121020 | medium | Exposure of Sensitive Information to an Unauthorized Actor (CWE-200) in the security... |
| GHSA-wqpq-pvq4-433g | CVE-2026-118446 | medium | A use-after-free vulnerability in the pybddisasm Python bindings affects array-valued members of... |
| GHSA-jmww-h2pp-r5r5 | CVE-2026-121024 | medium | Incorrect Authorization (CWE-863) in the Health Monitoring service in AxxonSoft AxxonNet before 3... |
| GHSA-qm9j-xr9g-5hqr | CVE-2026-118447 | medium | A use of uninitialized memory vulnerability in the pybddisasm Python bindings may disclose... |
| GHSA-8mvm-3gqr-9wc8 | CVE-2026-105982 | high | Improper input validation in the IPsec VPN function may allow a remote attacker with high... |
| GHSA-g5h3-rrm5-w5mh | CVE-2026-109161 | medium | Insufficient bounds checking in the Digital I/O function may allow a remote attacker with high... |
| GHSA-xm87-hrrj-pq46 | CVE-2026-118445 | medium | A use-after-free vulnerability in the pybddisasm Python bindings affects structure-valued members... |
| GHSA-73r7-q94j-p98r | CVE-2026-121021 | medium | Plaintext Storage of a Password (CWE-256) in the SecurityManager shared configuration in... |
| GHSA-j6cj-3pf4-988r | CVE-2026-105981 | high | Improper input validation in the Digital I/O function may allow a remote attacker with high... |
| GHSA-2fpm-24vf-wgg4 | CVE-2026-105980 | high | Improper input validation in the WireGuard VPN function may allow a remote attacker with high... |
| GHSA-5hc8-wr2r-5gjx | CVE-2026-105979 | high | Improper input validation in the ZeroTier VPN function may allow a remote attacker with high... |
| GHSA-p5f7-36qg-83fr | CVE-2026-118444 | medium | Out-of-bounds read vulnerabilities in the pybddisasm Python bindings may disclose adjacent... |
| GHSA-g9ph-g78p-5m7h | CVE-2026-105978 | high | Improper input validation in management control functions may allow a remote attacker with high... |
| GHSA-xpq3-q6vx-4qg3 | CVE-2026-103327 | medium | The CryptoCloud WordPress plugin from 3.0.0 through 3.0.1 does not verify the authenticity of the... |
| GHSA-p4f5-m8h6-x7p5 | CVE-2026-74846 | unknown | Catalyst::Plugin::Authentication versions before 0.10029 for Perl allow timing attacks on stored... |
| GHSA-w63q-qmf7-22jw | CVE-2026-4052 | critical | This issue only impacts deployments where WSO2 Identity Server is configured as a Resident Key... |
| GHSA-r4p6-57j4-fc8p | CVE-2026-16900 | high | Zohocorp ManageEngine Log360 and EventLog Analyzer versions 13071 and below are vulnerable to an... |
| GHSA-q9rp-676h-9hq2 | CVE-2026-13594 | critical | Zoho Corporation's ManageEngine Log360 and EventLog Analyzer versions 13062 and below are... |
| GHSA-qwgf-vfr8-c8w3 | CVE-2026-120988 | unknown | billboard.js before 4.1.3 allows an attacker to execute malicious JavaScript due to improper... |
| GHSA-j9pm-jfh5-ph9p | CVE-2025-5769 | medium | The authentication endpoint does not properly encode user-supplied input before rendering it... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Stahlbau Mann GmbH | payload | DE | 2026-11-03T04:06:32.600616+00:00 |
| Company #122 | N0n | US | 2026-11-03T03:28:32.480345+00:00 |
| Company #121 | N0n | US | 2026-11-03T03:27:56.666766+00:00 |
| Company #120 | N0n | US | 2026-11-03T03:27:20.759448+00:00 |
| Company #119 | N0n |  | 2026-11-03T03:26:45.106476+00:00 |
| Company #118 | N0n | AE | 2026-11-03T03:26:08.243467+00:00 |
| S... G... | SilentRansomGroup |  | 2026-11-02T21:00:34.267356+00:00 |
| da*****t.com | everstake |  | 2026-11-02T16:17:21.248292+00:00 |
| ra*****g.com | everstake |  | 2026-11-02T16:16:43.107808+00:00 |
| Holland & Knight | Redact | US | 2026-11-02T16:00:11.224717+00:00 |
| deom.be | safepay | BE | 2026-11-02T11:22:51.643089+00:00 |
| Neiman & Company, Inc. | pear | US | 2026-11-02T10:22:54.143039+00:00 |
| Ateşsan Ambalaj | HYFLOCK | TR | 2026-11-02T10:52:11.020018+00:00 |
| Company #117 | N0n | US | 2026-11-02T04:54:25.042516+00:00 |
| Company #116 | N0n | US | 2026-11-02T04:53:50.031605+00:00 |
| Company #115 | N0n | US | 2026-11-02T04:53:17.413944+00:00 |
| Company #114 | N0n | US | 2026-11-02T04:52:43.227614+00:00 |
| Company #113 | N0n | US | 2026-11-02T04:52:10.564040+00:00 |
| Isapre Consalud | qilin | CL | 2026-11-02T20:21:50.112374+00:00 |
| Harry's International | Orova | SG | 2026-11-02T16:54:24.558218+00:00 |

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
| 14.34.249.175 | 10 |
| 138.226.239.233 | 10 |
| 138.226.239.234 | 10 |
| 3.129.187.38 | 9 |
| 18.218.118.203 | 9 |
| 45.148.10.121 | 9 |
| 51.159.4.12 | 9 |
| 64.62.197.77 | 9 |
| 167.94.146.48 | 9 |
| 167.94.146.53 | 9 |
| 167.94.146.55 | 9 |
| 167.94.146.56 | 9 |
| 167.94.146.59 | 9 |
| 220.80.223.144 | 9 |
| 2.57.121.25 | 8 |
| 2.57.121.112 | 8 |
| 2.57.122.238 | 8 |
| 3.130.168.2 | 8 |
| 45.148.10.141 | 8 |
| 45.148.10.151 | 8 |

### OpenPhish (live phishing URLs)
- https://www.roblox.com.et/users/7280036217/profile
- https://s4w.in/recwU
- https://www.roblox.com.et/users/2977314015/profile
- https://s4w.in/gHboQ
- https://www.robiox.com.gr/users/8070655915/profile
- https://yukoncloud.cloud/Adobe_Installer.html
- https://compositura.com/js/indexe.html#lawrence
- https://robloxr.com.es/users/775450188/profile
- https://steomcomnmunity.ru/765678242749772
- https://is.gd/steamcommunity765678242749772
- http://app.shopledgerapp.com/
- http://wquie-eiiow201113.pages.dev/help/contact/292730103411180appeals/submit-appeal-form/return
- https://platform-policy-help-phi.vercel.app/required.html/
- https://qr-codes.io/j8aWFr
- http://www.coastalrealtyconnections.com/wp-content/uploads/2026/10/bible-readings-1.html#lorixpro@532a50b8bfb6dfe5bd534e5def05c5e17816.com
- https://www.roblox.com.et/users/643208279/profile
- https://s4w.in/www-roblox-com-users-64208279-profile
- https://yhgwyqom.elementor.cloud/1/es/SPAIN/es/arg/Aa/A/ES/argentina/ar/ES9D303ESS/ESS4Z3499SES/82CFGU2554/index.html
- https://mplays.topup-diamonds.com/
- https://aliferlopess.site/new/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://b8376mghi5d.jp.larksuite.com/share/base/form/shrjpMwk5KEz3wmsdPQjPPcLjqh?auth_token=U7CK1RF-737h19e2-db33-4b35-860b-f7744ema65h1-NN5W4 |
| N/A | https://ipkobznzs.sviluppo.host/ |
| N/A | https://away.vk.ru/away.php?rh=0015ef35-1477-4171-8153-08c3e02317c4 |
| N/A | https://45-77-67-89.cpanel.site/eu/date.php |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AWnogHfrcMjMJOA5-x4JjU2A_H62FL5Ipip8qUn0FfsVqhu1vrUBPxBl4JpnqCjPGKNrTfaShVnNJQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBglf-ncNsOY-PuFAbA8FGO0skPdUBzyiSNAEhg0tQmP7KPYUaiayjesHk6wnw_1cBRz0X3jVg&dsh=S1124736358%3A1793700948239880 |
| N/A | https://away.vk.ru/away.php?rh=a4f5fa80-8b39-480a-87ff-ea4206cc8e30 |
| N/A | https://away.vk.ru/away.php?rh=24013749-2bba-4ad9-89fb-2eb7c33b632f |
| N/A | http://43.156.0.130/v3/signin/identifier?amp;continue=https://accounts.google.com/&amp;followup=https://accounts.google.com&passive=1209600&flowName=GlifWebSignIn&flowEntry=ServiceLogin&dsh=S-1624549647:1793700507813766 |
| N/A | https://forsale.dynadot.com/forsale/tepcojp.co |
| N/A | https://fischliamsee.ch/hutarchitecturedocs |
| N/A | https://matscarlux.fr/ |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AaSxoQyQEeCdGiNQploah5nAij7vrMqrlVIHby1Q4v_ARx9kttGkmffM4ARVCnkvjXQyGpUqW4kQNA&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBglfvV382v4anZO0TttpkjuTQCRktdMzTjZfOuonOKK9SYBsfZru-_sOvbNfqvq__zw4CYEKH&dsh=S-199408681%3A1793699800059833 |
| N/A | https://away.vk.ru/away.php?rh=4778e2c3-9a1b-4b4f-ab49-fa684f1de9a9 |
| N/A | https://skinsmonkey.com?referrer=pid%3D1%26af_tranid%3DMTcyMzU1MDYyMTAzNTY0NDA0MDU%3D |
| N/A | https://away.vk.ru/away.php?rh=046b7f41-dacd-497a-ae42-ad32a340af2d |
| N/A | https://away.vk.ru/away.php?rh=96edf07c-77ca-4fb3-8876-0b42fa683ee8 |
| N/A | https://fischliamsee.ch/hutarchitecture/11.php |
| N/A | https://www.barracudabar-pattaya.com/ |
| N/A | https://yandex.ru/showcaptcha?cc=1&form-fb-hint=2.1&mt=C16ADD57E6B9210D064A3C2E346F120FF3890FD47E0CD06D4EABE8077E7A0A3F6D7F81933090DA70284FEC4F4C45DE0CFE67E699A0BB9222202AB93EF9761DE4D7D1AF93F6423859774D40E1B563CD2C766081FDBEDFC5D93AD41949A2DBEBB298E8FA7DCDF064DFE5C1DA943E12B4F7C4A0837A08031C3BD5C9E0D30A87D5634D209ACF9F6E930A0C&retpath=aHR0cHM6Ly95YW5kZXgucnUvc2VhcmNoP3RleHQ9MjExNjg3MTc%2C_9e32ea590f1152ceb4677b92f96f1e0c&t=2%252F1793698481%252F7161889d27fad7c681ca1c17837d3ce9&u=9692603016315147480&s=e88ab4db2b3e7c46bb2fc07e28956c26 |
| N/A | https://pageseuc1.actmkt.com/(S(m2p4ib4ps2csz3n0chrgbw1e))/l/c5X8MfZz6j9Y7Fto3LAd |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| 66c657533cb5d25c1cef98a173f26b69536b67d6 | ResolverRAT C&C |
| 1b2f2ca48067d909791338a6c32cf2e0104f6a7f | Malware C&C |
| 2c8903399677fe6022cab030e0049bcfff538bdd | OffLoader C&C |
| 589654a4ecbbc484056cc1bfeea1fcdc7ecc7d81 | Vidar C&C |
| 4f63e391bda319474161cb4a2506c40acc8fca7a | ACRStealer malware distribution |
| 39addcc32a42a6e5e02bc47df50ae4382f7985ea | Malware C&C |
| 937b0696c1b45add349c0bb80ccb2c5bf1b45e8d | QuasarRAT C&C |
| 7971c98d08ecbd1c681c9b7e24d9c051b2cab4d5 | PureRAT C&C |
| ea4723a7e20c5d7a484f1839bbdeb7264e390b67 | PureRAT C&C |
| 557e284271700e2d215ccfd45928ca26e7010195 | PureRAT C&C |
| 939dee92e7a71c659a53d1080e2eedf80c447b5b | ACRStealer malware distribution |
| b9dfaffdab120dab2356b97d90d45c5f48065887 | AdaptixC2 C&C |
| ec9a883b6bc64865d35acff1bb2ef03b88aa5e41 | PavinLoader C&C |
| c7661472410f15e671d6f85acba76f5b54e12b42 | PureRAT C&C |
| 4dcd0af12d82ecc86eb1bb0425ec59fa08122e19 | Malware C&C |
| afd4e0dbe6138ee5718f9bf93aa72943c3be5336 | PureRAT C&C |
| 47faf6aded8419d9517d9dbd5646a435d51cb210 | Vidar C&C |
| e84ebc6b9b7ac39785254a0ef0caddd96f51aa99 | Vidar C&C |
| eb3a71b4803774f788e85831b9e5821c6c62ada1 | Vidar C&C |
| f9542c3038dc3632d71c1e3735408c8577e8568a | PureRAT C&C |

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
- 1.117.73.220
- 1.12.55.80
- 1.14.192.95
- 1.14.240.247
- 1.159.54.33
- 1.162.226.183
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.234.80.94
- 1.235.183.146
- 1.238.106.229
- 1.245.161.206
- 1.247.245.61
- 1.250.67.114
- 1.250.67.190
- 1.39.156.115
- 1.85.42.195
- 1.9.47.19

### CINS Army (poorly-rated IPs)
- 1.14.64.144
- 1.15.14.29
- 1.172.202.65
- 1.192.129.106
- 1.193.63.167
- 1.24.16.109
- 1.24.16.110
- 1.24.16.126
- 1.24.16.127
- 1.24.16.172
- 1.24.16.190
- 1.24.16.194
- 1.24.16.22
- 1.24.16.31
- 1.24.16.62
- 1.24.16.71
- 1.24.16.9
- 1.24.16.92
- 1.24.16.93
- 1.24.16.98

## News (last ~36h, across outlets)
### The Hacker News
- [Hackers Exploit BTCPay Server Flaw to Steal Bitcoin and Litecoin From Hot Wallets](https://thehackernews.com/2026/11/hackers-exploit-btcpay-server-flaw-to.html)
- [Synology NAS Devices Targeted in Ransomware Attacks Exploiting Patched DSM Flaw](https://thehackernews.com/2026/11/synology-nas-devices-targeted-in.html)
- [New Wave of Refrigeration Cyberattacks Hits Supermarkets Across Europe, Forcing Stores to Pull Food](https://thehackernews.com/2026/11/second-wave-of-cyberattacks-hits.html)
- [Attackers Exploit Critical Siemens IoT2050 Flaw to Plant Remote Command Backdoors](https://thehackernews.com/2026/11/attackers-exploit-critical-siemens.html)
- [Attackers Target Unpatched CryptoPayment Gateway Flaw That Can Expose Wallet Credentials](https://thehackernews.com/2026/11/attackers-target-unpatched.html)
- [⚡ Weekly Recap: Critical CVEs, Linux DDoS Botnet, Device-Code Phishing, Android Spyware and More](https://thehackernews.com/2026/11/weekly-recap-critical-cves-linux-ddos.html)
- [Google Disrupts 1.3 Million-Device Android Botnet, Says TV Box Maker Sold Criminal Access](https://thehackernews.com/2026/11/google-disrupts-13-million-device.html)
- [DarkBlinders Compromises Israeli Target and Iraqi Kurdish Government Cloud Environment](https://thehackernews.com/2026/11/darkblinders-compromises-israeli-target.html)
- [Critical Langflow Flaws Could Let Unauthenticated Attackers Run Code on Servers](https://thehackernews.com/2026/11/critical-langflow-flaws-could-let.html)
- [Is Your SOC Ready for AI Agents? A Maturity Check Before You Deploy](https://thehackernews.com/2026/11/is-your-soc-ready-for-ai-agents.html)
- [Attackers Pose as IT Support on Microsoft Teams, Abuse AD CS to Steal Company Data](https://thehackernews.com/2026/11/attackers-pose-as-it-support-on.html)
- [Government Linux Servers Targeted With SysGoRAT and Suspected AI-Generated Scripts](https://thehackernews.com/2026/11/government-linux-servers-targeted-with.html)
- [New VOLTA Infostealer Uses Claude, Gemini, and Kimi AI to Rank Victims by Financial Value](https://thehackernews.com/2026/11/new-volta-infostealer-uses-claude.html)

### BleepingComputer
- [Chinese hackers use ARTEX AI in automated attacks against 200 orgs](https://www.bleepingcomputer.com/news/security/chinese-hackers-use-artex-ai-in-automated-attacks-against-200-orgs/)
- [Fintech platform Sageworks taken offline after suspected cyberattack](https://www.bleepingcomputer.com/news/security/fintech-platform-sageworks-taken-offline-after-suspected-cyberattack/)
- [Google disrupts million-device XCPE Android malware botnet, bans TV box maker](https://www.bleepingcomputer.com/news/security/google-disrupts-million-device-xcpe-android-malware-botnet-bans-tv-box-maker/)
- [BTCPay Server warns of hot wallet crypto thefts on outdated instances](https://www.bleepingcomputer.com/news/security/btcpay-server-warns-of-hot-wallet-thefts-targeting-outdated-instances/)
- [Your Mobile Carrier Stores Your Call Logs for Years](https://www.bleepingcomputer.com/news/security/your-mobile-carrier-stores-your-call-logs-for-years/)
- [Hackers disrupt refrigeration systems at European supermarkets](https://www.bleepingcomputer.com/news/security/hackers-disrupt-refrigeration-systems-at-european-supermarkets/)
- [Microsoft fixes Smart App Control broken by October Windows update](https://www.bleepingcomputer.com/news/microsoft/microsoft-fixes-smart-app-control-broken-by-october-windows-update/)
- [Over 1,000 GitLab servers vulnerable to ongoing RCE attacks](https://www.bleepingcomputer.com/news/security/over-1-000-gitlab-servers-vulnerable-to-code-execution-attacks/)
- [Synology warns of C3RB3R ransomware attacks targeting NAS devices](https://www.bleepingcomputer.com/news/security/synology-warns-customers-of-ongoing-c3rb3r-ransomware-attacks/)
- [Ivanti patches two more Connect Secure zero-days chained in attacks](https://www.bleepingcomputer.com/news/security/ivanti-patches-two-more-connect-secure-zero-days-chained-in-attacks/)

### Krebs on Security
- [Tech Firms Dismantle Botnet That Turned 1.3M TV Boxes Into Proxies](https://krebsonsecurity.com/2026/11/tech-firms-dismantle-botnet-that-turned-1-3m-tv-boxes-into-proxies/)

### Dark Reading
- [One Compromised Laptop, Billions Lost: The Binance Attack-Path Warning](https://www.darkreading.com/cyberattacks-data-breaches/binance-hack-test-attack-paths)
- [Microsoft's AI Risk Report Misses This Key Detail](https://www.darkreading.com/cyberattacks-data-breaches/microsoft-ai-cyber-risk-report-miss)
- [PapRAT Cyber-Espionage Campaign Leaves a 'Bitter' Taste in South Asia](https://www.darkreading.com/cyberattacks-data-breaches/paprat-cyberespionage-campaign-bitter-south-asia)

### SecurityWeek
- [UK Cyber Chief Says the UK Will Face AI Cyberattacks on Critical Infrastructure by 2028](https://www.securityweek.com/uk-cyber-chief-says-the-uk-will-face-ai-cyberattacks-on-critical-infrastructure-by-2028/)
- [Google Dismantles XCPE Botnet of 1.3 Million Android Devices](https://www.securityweek.com/google-dismantles-xcpe-botnet-of-1-3-million-android-devices/)
- [NATO’s Crossed Swords Exercise Brings AI Agents Into Cyber Operations Training](https://www.securityweek.com/natos-crossed-swords-exercise-brings-ai-agents-into-cyber-operations-training/)
- [Over 100 European Stores Hit as Supermarket Fridge Attacks Return](https://www.securityweek.com/over-100-european-stores-hit-as-supermarket-fridge-attacks-resume/)
- [Cybersecurity M&A Roundup: 37 Deals Announced in October 2026](https://www.securityweek.com/cybersecurity-ma-roundup-37-deals-announced-in-october-2026/)
- [Florida Student Aid Website Hack Puts Data of 4.9 Million People at Risk](https://www.securityweek.com/florida-student-aid-website-hack-puts-data-of-4-9-million-people-at-risk/)
- [Revolve Data Breach Impacts at Least 200,000 People](https://www.securityweek.com/revolve-data-breach-impacts-at-least-180000-people/)
- [Google Introduces $250,000 Root-in-Cloud Bug Bounty Reward](https://www.securityweek.com/google-introduces-250000-root-in-cloud-bug-bounty-reward/)
- [Malicious Claude Code Extension Served in Cursor Supply Chain Attack](https://www.securityweek.com/malicious-claude-code-extension-served-in-cursor-supply-chain-attack/)
- [Chainalysis Discloses Data Breach Following AI-Driven Cyberattack](https://www.securityweek.com/chainalysis-discloses-data-breach-following-ai-driven-cyberattack/)

### The Record
- [UK faces ‘unprecedented rise’ in cyberattacks in coming months, warns cyber chief](https://therecord.media/uk-ncsc-predicts-rise-cyberattacks-coming-months)
- [Largest crypto exchange in Brazil confirms cyberattack as millions flow out of platform](https://therecord.media/mercado-bitcoin-brazil-cryptocurrency-heist)
- [Michigan State cyber incident claimed by ransomware gang behind recent hospital attack](https://therecord.media/michigan-state-university-byod-gang-cyber-incident)
- [Polymarket pledges to give $3.9 million back to victims after site compromise](https://therecord.media/polymarket-returning-funds-to-customers-after-site-compromise)
- [Russia's statistics agency confirms cyberattack claimed by Belarusian and Ukrainian hackers](https://therecord.media/hackers-ukraine-belarus-russia)

### Infosecurity Magazine
- [Police and Tech Firms Team Up to Dismantle XCPE Botnet](https://www.infosecurity-magazine.com/news/police-tech-firms-team-up-to/)
- [Armadin Tests Find 88% of Severe Flaws Outside Vendor Advisories](https://www.infosecurity-magazine.com/news/armadin-severe-exposures-missed/)
- [Bitter Deploys PapRAT in Asian Cyber-Espionage Campaign](https://www.infosecurity-magazine.com/news/paprat-bitter-cyberespionage/)
- [FBI Attributes Binance Heist to North Korea’s TraderTraitor](https://www.infosecurity-magazine.com/news/fbi-attributes-binance-north/)
- [Chainalysis Warns Customers After “Offensive Agentic” Security Incident](https://www.infosecurity-magazine.com/news/chainalysis-customers-offensive/)

### CyberScoop
- [Google shuts down global botnet running on certified Android devices](https://cyberscoop.com/google-disrupts-xcpe-botnet-videostrong-android-devices/)
- [Business groups mount fresh campaign for long-term renewal of information sharing law](https://cyberscoop.com/business-groups-cisa-2015-renewal-ndaa-cybersecurity/)
- [Could Nick Andersen’s leadership outlast the clock on his acting role?](https://cyberscoop.com/nick-andersen-cisa-acting-director-nomination/)
- [Federal court tosses Trump lawsuit challenging Alaska Senate certification](https://cyberscoop.com/judge-dismisses-alaska-senate-lawsuit-peltola-sullivan/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
- [Unit 42 Threat Intelligence Highlights - Nov. 2, 2026](https://unit42.paloaltonetworks.com/u42-threat-intelligence-highlights-oct-2026/)

### Microsoft Security Blog
- [What exploited vulnerabilities have in common: A data-driven analysis of real-world attacks](https://www.microsoft.com/en-us/security/blog/2026/11/02/exploited-vulnerabilities-common-data-driven-analysis-real-world-attacks/)

### Google Cloud Threat Intel
- [Shutting the Door on the XCPE Botnet](https://cloud.google.com/blog/topics/threat-intelligence/shutting-the-door-on-the-xcpe-botnet/)
- [The Rise of LLMJacking: How Threat Actors Monetize Compromised Cloud and Model Resources](https://cloud.google.com/blog/topics/threat-intelligence/llmjacking-monetizing-compromised-cloud-models/)

### SANS Internet Storm Center
- [ISC Stormcast For Tuesday, November 3rd, 2026 https://isc.sans.edu/podcastdetail/10162, (Tue, Nov 3rd)](https://isc.sans.edu/diary/rss/33484)
- [Mutipath TCP: Use and Detection, (Mon, Nov 2nd)](https://isc.sans.edu/diary/rss/33482)
- [ISC Stormcast For Monday, November 2nd, 2026 https://isc.sans.edu/podcastdetail/10160, (Mon, Nov 2nd)](https://isc.sans.edu/diary/rss/33480)

### Securelist (Kaspersky)
- [MLEP in KICS for Networks 5.0: how machine learning helps track network behavior of OT devices](https://securelist.com/tr/machine-learning-event-processor-in-kics-for-networks/121794/)
- [CyberStrikeAI in the wild: the use of AI in real-world attacks on organizations](https://securelist.com/tr/cyberstrikeai-attacks/121715/)

### CrowdStrike Blog
- [Introducing AI Kill Switch: Taking Control When AI Agents Go Rogue](https://www.crowdstrike.com/en-us/blog/crowdstrike-introduces-ai-kill-switch/)
- [CrowdStrike Advances AI Security and Safety from Endpoint to Cloud](https://www.crowdstrike.com/en-us/blog/crowdstrike-advances-ai-security-and-safety-falcon-guardian/)
- [CrowdStrike to Acquire Dreadnode to Bring Automated AI Security Testing to the Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-to-acquire-dreadnode/)
- [CrowdStrike to Acquire Fiddler to Deliver Falcon Observe for AI Agent Observability](https://www.crowdstrike.com/en-us/blog/crowdstrike-to-acquire-fiddler/)
- [CrowdStrike Secures AI Agents Inside Claude Cowork](https://www.crowdstrike.com/en-us/blog/crowdstrike-secures-ai-agents-inside-claude-cowork/)
- [What Makes a Good Security Agent? 5 Lessons from the AgentWorks Hackathon](https://www.crowdstrike.com/en-us/blog/five-lessons-from-agentworks-hackathon/)
- [CrowdStrike Expands Falcon Adversary OverWatch Threat Hunting Across AI and Google Cloud](https://www.crowdstrike.com/en-us/blog/crowdstrike-expands-threat-hunting-across-ai-and-google-cloud/)
- [Build an Intelligence Advantage with Falcon Next-Gen SIEM](https://www.crowdstrike.com/en-us/blog/build-intelligence-advantage-with-falcon-next-gen-siem/)
- [CrowdStrike Agent Graph Shows How Agents Act on the Endpoint](https://www.crowdstrike.com/en-us/blog/crowdstrike-agent-graph-shows-how-agents-act-on-endpoint/)
- [VAPOR PANDA Uses AI-Driven ARTEX to Scale a Global Espionage Campaign](https://www.crowdstrike.com/en-us/blog/vapor-panda-uses-artex-to-scale-global-campaign/)

### FortiGuard Threat Signal
- [OT Refrigeration Control Systems Attack](https://fortiguard.fortinet.com/threat-signal-report/6553)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal