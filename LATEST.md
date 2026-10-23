# Winjit Daily TI Digest — 2026-10-23

_Auto-generated. Window: last ~24h. Fetched at 2026-10-23T08:23:31.890153+00:00Z_

**At a glance:** 0 new KEV · 72 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-114575 | 10.0 | 2.2% | A flaw has been found in TOTOLINK A950RG 4.1.2cu.5268_B20221104. Affected by this issue is the function UploadCustomModule of the file lib/cste_modules/product.so. Executing a manipulation of the argu |
| CVE-2026-83938 | 10.0 | n/a | Missing authentication for critical function in Azure Kubernetes Configuration Service allows an unauthorized attacker to elevate privileges over a network. |
| CVE-2026-97785 | 10.0 | n/a | Improper authentication in AAD App Proxy allows an unauthorized attacker to elevate privileges over a network. |
| CVE-2026-115375 | 9.9 | n/a | Incus 7.0.0 before 7.0.2 and 7.1.0 before 7.5.0 contains a path traversal vulnerability that allows clients able to create instances to write files on the host. The flaw stems from unvalidated depende |
| CVE-2026-115377 | 9.9 | n/a | Incus before 6.0.7, 6.1.0 before 7.0.2, and 7.1.0 before 7.5.0 contains an arbitrary file write vulnerability that allows malicious migration sources to write host files by planting symlinks in transf |
| CVE-2026-115384 | 9.9 | n/a | Wasmtime 39.0.0 before 48.0.4 and 49.0.0 before 49.0.2 contains a stack buffer overflow vulnerability that allows malicious guests to write ~16KB to the native stack via unvalidated async callback res |
| CVE-2021-48014 | 9.8 | n/a | FineReport 9.0 contains a path traversal vulnerability in the /WebReport/ReportServer design_save_svg operation that allows unauthenticated attackers to write arbitrary files via the filePath paramete |
| CVE-2021-48016 | 9.8 | n/a | DedeCMS through 5.8.1-beta contains a PHP code injection vulnerability in ShowMsg() where the HTTP Referer header is written into a DedeTemplate string and included. Unauthenticated attackers can send |
| CVE-2022-51026 | 9.8 | n/a | Bytebase 0.12.0 before 1.0.1 contains an authentication bypass vulnerability that allows unauthenticated attackers to log in as any user. The flaw stems from trusting client-supplied GitLab provider c |
| CVE-2022-51022 | 9.1 | n/a | YiShaAdmin 2.2 through 3.1, fixed in commit 025b062, contains an unauthenticated path traversal vulnerability in the /admin/File/DownloadFile endpoint that allows attackers to read and delete arbitrar |
| CVE-2026-114658 | 8.8 | 0.3% | Grav Login plugin from 3.6.0 before 3.9.13 contains a missing authorization vulnerability in the login.invite task that allows page authors to obtain super user accounts. Attackers can define an invit |
| CVE-2026-115328 | 8.8 | n/a | JSON-SCADA before 0.65-alpha contains an sql injection vulnerability in opcApi() in src/server_realtime_auth/index.js that allows authenticated users to inject SQL via HistoryReadRequest parameters. A |
| CVE-2026-115330 | 8.8 | n/a | Lotus through 0.10.2 contains an sql injection vulnerability that allows authenticated organization users to execute arbitrary SQL by appending stacked statements to custom metric queries. Attackers c |
| CVE-2026-115331 | 8.8 | n/a | Lotus through 0.10.2 contains an sql injection vulnerability that allows authenticated organization users to inject SQL by supplying crafted billable metric property_name or categorical filter values. |
| CVE-2026-115332 | 8.8 | n/a | Lotus through 0.10.2 contains an sql injection vulnerability that allows authenticated organization users to inject SQL by registering crafted subscription_filter_keys that bypass keyword-only validat |
| CVE-2026-114635 | 8.7 | 0.2% | Traefik before v2.11.58 and v3.7.14 contains an authentication bypass vulnerability in its SNI check, which is skipped when request TLS state is nil. Unauthenticated clients can send HTTP/2 requests w |
| CVE-2026-114636 | 8.7 | 0.3% | Traefik v3.7.13 before v3.7.14 contains an access-control bypass in the Kubernetes Ingress NGINX provider, where the HTTP router generated for ssl-passthrough Ingresses on non-TLS entry points never a |
| CVE-2026-114637 | 8.7 | 0.3% | Traefik from v3.2.0 before v3.7.14 contains an authentication bypass vulnerability in the experimental FastProxy connection pool, which fails to pin NTLM/Negotiate-authenticated backend connections to |
| CVE-2026-114638 | 8.7 | 0.2% | Traefik v3.7.0 before v3.7.14 contains an improper authentication vulnerability in the Kubernetes Ingress NGINX provider that merges client CAs when auth-tls-secret names collide after dot-to-dash nor |
| CVE-2026-114639 | 8.7 | 0.3% | Traefik 2.11.0 before 2.11.58 and 3.0.0 before 3.7.14 contains an authentication bypass because a first request preauthenticated with an Authorization: Negotiate token authenticates a socket in the gl |
| CVE-2026-114640 | 8.7 | 0.2% | Traefik from v3.7.0 before v3.7.14 contains an authentication bypass vulnerability in its Kubernetes Ingress-NGINX provider that forwards client-supplied Ssl-Client-* headers on the plaintext HTTP rou |
| CVE-2026-114642 | 8.7 | 0.2% | Traefik 2.11.0 before 2.11.58 and 3.0.0 before 3.7.14 stores its NTLM/Kerberos backend round tripper in a client-connection slot not keyed by ServersTransport, so one service's TLS client configuratio |
| CVE-2026-115513 | 8.7 | n/a | OpenCATS before 0.12.0 contains a stored cross-site scripting vulnerability that allows a low-privileged authenticated user to inject HTML/JavaScript payloads by setting a Candidate, Company, Contact, |
| CVE-2026-115353 | 8.6 | n/a | Mistune before 3.3.0 contains a path traversal vulnerability in the RST include directive that allows attackers to read arbitrary files by supplying relative or absolute paths. Attackers can submit ma |
| CVE-2026-114661 | 8.5 | 0.2% | OpenRemote 1.2.0 before 1.31.0 contains a missing authorization vulnerability in GatewayServiceResource that allows any authenticated user to start, stop and query gateway tunnels without an administr |
| CVE-2026-115372 | 8.5 | n/a | Incus from 7.3.0 before 7.5.0 contains a project restriction bypass that allows restricted project users to set block.create_options through volume update, copy, and move operations. Attackers can set |
| CVE-2026-114663 | 8.4 | 0.1% | Vyper 0.4.0b1 through 0.5.0b1 miscompiles unfoldable constants and omitted default arguments from imported modules, because parse_Name resolves their names in the using function's scope rather than at |
| CVE-2026-115325 | 8.3 | n/a | Netmaker through 1.7.0 contains an authorization bypass vulnerability in the updateExtClient handler that allows network-scoped users to modify external clients on other networks. Attackers with exter |
| CVE-2019-25778 | 8.2 | n/a | SeaCMS through 8.7 contains an unauthenticated SQL injection vulnerability that allows remote attackers to manipulate database queries by injecting SQL through the rlist[] array parameter. Attackers c |
| CVE-2022-51021 | 8.2 | n/a | NotificationX plugin for WordPress 2.0.0 before 2.3.12 contains an unauthenticated SQL injection vulnerability that allows remote attackers to manipulate database queries by supplying an array-form 'i |
| CVE-2022-51023 | 8.2 | n/a | PHPOK 4.5.000 before 5.4.081 contains an SQL injection vulnerability that allows unauthenticated attackers to manipulate ORDER BY clauses via the sort parameter. Attackers can send GET requests to /ap |
| CVE-2024-58393 | 8.2 | n/a | i-Netsolution Readymade Unilevel Ecommerce MLM (2024-03-15 build) contains an SQL injection vulnerability that allows unauthenticated attackers to manipulate database queries through the 'id' paramete |
| CVE-2025-71434 | 8.2 | n/a | Weaver E-cology 8.0, 9.0, and 10.0 prior to 10.76 contains an unauthenticated SQL injection vulnerability in the /api/doc/out/more/list endpoint via the elementmore parameter with srcType=2. Attackers |
| CVE-2026-114662 | 8.1 | 0.2% | Obot before 0.26.0 contains an authentication bypass vulnerability in the CLI login flow that allows unauthenticated attackers to steal API keys by choosing token request IDs. Attackers can create a t |
| CVE-2026-115324 | 8.1 | n/a | mem0 0.1.117 before 1.0.8 contains an sql injection vulnerability in mem0/vector_stores/databricks.py that allows attackers to inject SQL by influencing stored memory content. Attackers can supply cra |
| CVE-2026-115392 | 7.9 | n/a | Wasmtime before 24.0.13, 25.0.0 before 36.0.14, 37.0.0 before 46.0.3, and 47.0.0 before 47.0.4 allows a filesystem sandbox escape in wasmtime-wasi because its cap-std dependency mishandles symlinks wi |
| CVE-2026-115504 | 7.8 | n/a | CFITSIO through 4.7.0 contains an out-of-bounds write vulnerability in ffgcls2() in getcols.c that trusts attacker-controlled heap descriptor lengths for variable-length string columns. Attackers can  |
| CVE-2026-115376 | 7.7 | n/a | Incus 7.0.1 before 7.0.2 and 7.2.0 before 7.5.0 contains an authorization bypass vulnerability that allows project-restricted clients to copy volumes by omitting source.type. Attackers can send crafte |
| CVE-2026-108456 | 7.7 | n/a | Server-side request forgery (ssrf) in Azure AI Foundry allows an authorized attacker to elevate privileges over a network. |
| CVE-2026-115505 | 7.6 | n/a | libsmb2 before 6.3 contains integer overflow vulnerabilities in the DCE/RPC NDR decoder in lib/dcerpc.c that allow heap out-of-bounds reads and writes. A malicious SMB server or machine-in-the-middle  |
| CVE-2026-115484 | 7.6 | n/a | A flaw was found in the iscsiuio component of open-iscsi. The DHCPv4 option parser incorrectly calculates the length of the options data, causing it to read beyond the allocated buffer into adjacent h |
| CVE-2026-114656 | 7.5 | 0.2% | Traefik before 2.11.58 and 3.7.13 contains an authentication bypass vulnerability that allows unauthenticated clients to skip client-certificate checks because negated Host matchers are counted as ser |
| CVE-2017-20287 | 7.5 | n/a | Javo Spot theme for WordPress before 3.0.0 contains a path traversal vulnerability that allows unauthenticated attackers to read arbitrary files via the fn parameter of the jvfrm_spot_get_json AJAX ac |
| CVE-2017-20289 | 7.5 | n/a | Broadstreet Ad Widget plugin for WordPress 2.2.0 before 2.12.0 contains a local file inclusion vulnerability that allows authenticated users to execute attacker-chosen PHP files by passing unsanitized |
| CVE-2018-25438 | 7.5 | n/a | Intermesh Group-Office 3.3.0 before 3.5.5 contains an unauthenticated path traversal vulnerability in compress.php that allows remote attackers to read arbitrary files by manipulating the 'file' param |
| CVE-2018-25439 | 7.5 | n/a | MetInfo CMS 6.0.0 before 6.1.1 contains a path traversal vulnerability in /include/thumb.php that allows unauthenticated attackers to read arbitrary files via the dir parameter. Attackers can send cra |
| CVE-2019-25779 | 7.5 | n/a | WooThemes Diarise through 1.5.9 contains a file read vulnerability that allows unauthenticated attackers to read arbitrary files through the calendar parameter of download.php. Attackers can send GET  |
| CVE-2021-48013 | 7.5 | n/a | Weaver E-cology 8.0 contains a path traversal vulnerability that allows unauthenticated attackers to read arbitrary files through the fpath parameter of the /weaver/ln.FileDownload endpoint. Attackers |
| CVE-2021-48015 | 7.5 | n/a | JeeWMS before commit 0a610e8 contains an unauthenticated path traversal vulnerability that allows remote attackers to read arbitrary files via the dbPath parameter. Attackers can send GET requests to  |
| CVE-2021-48017 | 7.5 | n/a | OrbiTeam BSCW Server 5.x before 5.2.5 and 7.x before 7.4.4 contains an unauthenticated path traversal vulnerability in the style_name parameter of the theme operation. Attackers can send GET requests  |
| CVE-2022-51024 | 7.5 | n/a | Kavita 0.5.2 before 0.5.4.1 contains a path traversal vulnerability that allows unauthenticated attackers to read arbitrary files by supplying '../' sequences in the filename parameter. Attackers can  |
| CVE-2024-58396 | 7.5 | n/a | YouDataSum CPAS Audit Management System V4 contains a path traversal vulnerability that allows unauthenticated attackers to read arbitrary files by manipulating the fileId parameter. Attackers can sen |
| CVE-2026-115347 | 7.5 | n/a | Mistune before 3.3.0 contains an inefficient algorithmic complexity vulnerability in parse_link_text that allows remote attackers to cause denial of service through unbalanced square brackets. Attacke |
| CVE-2026-115348 | 7.5 | n/a | Mistune from 3.0.0 before 3.3.0 contains an algorithmic complexity vulnerability in the inline link parser's parse_link_text function that allows unauthenticated attackers to exhaust CPU with unbalanc |
| CVE-2026-115349 | 7.5 | n/a | Mistune from 3.0.0 before 3.3.0 contains an algorithmic complexity denial of service vulnerability in the parse_link_text function in src/mistune/helpers.py. Attackers can submit markdown with deeply  |
| CVE-2026-115352 | 7.5 | n/a | Mistune before 3.3.0 contains an algorithmic complexity vulnerability in the inline link parser that allows unauthenticated attackers to exhaust CPU by submitting long runs of unmatched '[' characters |
| CVE-2026-115355 | 7.5 | n/a | Mistune before 3.3.0 contains a path traversal vulnerability in the Include directive that allows attackers to read arbitrary files by supplying ../ sequences in include paths. Attackers can also inje |
| CVE-2026-112330 | 7.5 | n/a | Motor.NET before 0.19.0 contains a denial of service vulnerability that allows a remote attacker who can publish to a consumed queue to crash the service permanently by sending a message with crafted  |
| CVE-2026-112331 | 7.5 | n/a | Motor.NET before 0.19.0 contains a denial-of-service vulnerability that allows a remote attacker who can produce records to a consumed topic to crash the service permanently by sending a single crafte |
| CVE-2026-112332 | 7.5 | n/a | Motor.NET before 0.19.0 contains an uncaught exception vulnerability in JsonNetDeserializer.Deserialize that allows a remote attacker who can publish to a consumed queue or topic to crash the service  |
| CVE-2026-115506 | 7.5 | n/a | libexpat through 2.9.0 contains a denial of service vulnerability because billion laughs protection in accountingDiffTolerated() in xmlparse.c detects entity amplification too late. Attackers can supp |
| CVE-2026-115497 | 7.5 | n/a | The Music Store – WordPress eCommerce plugin for WordPress is vulnerable to Directory Traversal in all versions up to, and including, 1.4.7 via the 'f' parameter parameter. This makes it possible for  |
| CVE-2026-114221 | 7.4 | 0.3% | NT OneAPP developed by NewType Infortech has a Credential Disclosure vulnerability. Unauthenticated remote attackers can trigger an HTTP Basic Authentication challenge from an unvalidated source in th |
| CVE-2026-111079 | 7.4 | n/a | A flaw was found in Goose. When the terminal integration feature is enabled, the application captures shell command history and sends it verbatim without sanitization to configured Large Language Mode |
| CVE-2026-114577 | 7.3 | 0.3% | A vulnerability was found in oretnom23 php-travel-agency-system. This vulnerability affects unknown code of the file admin/insert.php of the component Insertion Handler. The manipulation of the argume |
| CVE-2026-115323 | 7.3 | n/a | EverShop 1.2.2 before 2.2.1 contains a missing authorization vulnerability in the customer address API that allows unauthenticated attackers to manage other customers' addresses. Attackers who know cu |
| CVE-2026-104068 | 7.2 | n/a | JetBackup plugin for WordPress before 3.1.24.10 contains a symlink-based arbitrary file write vulnerability that allows an authenticated WordPress administrator to write attacker-controlled file conte |
| CVE-2026-109198 | 7.2 | n/a | The Anti-Spam by CleanTalk – Spam Protection Without CAPTCHA plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'user_email' parameter in all versions up to, and including, 6.89 |
| CVE-2026-114664 | 7.1 | 0.2% | Frappe Framework before 16.33.0 contains a blind SQL injection vulnerability in the frappe.desk.doctype.event.event.get_events method, which fails to properly neutralize user-supplied input before inc |
| CVE-2026-115371 | 7.1 | n/a | Incus 6.0.3 before 6.0.7, 6.6.0 before 7.0.2, and 7.1.0 before 7.5.0 contains an improper authorization vulnerability that allows restricted TLS clients to read storage bucket keys in the default proj |
| CVE-2026-115374 | 7.1 | n/a | Incus 7.0.0 before 7.0.2 and 7.1.0 before 7.5.0 contains a signature verification flaw in its built-in S3 server that allows presigned URL holders to inject unsigned x-amz-* headers. Attackers can add |
| CVE-2026-115486 | 7.1 | n/a | A flaw was found in the iscsiuio component of open-iscsi. The IPv6 Neighbor Discovery handler accesses link-layer address options at a fixed offset without verifying the packet contains them. Addition |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-69cf-82p8-9425 | CVE-2026-94267 | unknown | The Advanced Custom Fields: Extended WordPress plugin before 0.9.2.8, Advanced Custom Fields:... |
| GHSA-5c6h-7vg8-f3f2 | CVE-2026-94268 | unknown | The Advanced Custom Fields: Extended WordPress plugin before 0.9.2.8, Advanced Custom Fields:... |
| GHSA-x437-3m7g-hfr2 | CVE-2026-94264 | unknown | The Advanced Custom Fields: Extended WordPress plugin before 0.9.2.8, Advanced Custom Fields:... |
| GHSA-vf96-8vxj-vchf | CVE-2026-113501 | unknown | The LiteSpeed Cache WordPress plugin before 7.9.2 does not perform a capability check on its... |
| GHSA-grhh-22v9-vc32 | CVE-2026-113500 | unknown | The LiteSpeed Cache WordPress plugin before 7.9.2 does not limit one of its HTML optimization... |
| GHSA-7923-x8xg-r65v | CVE-2026-112230 | unknown | The Popup Builder  WordPress plugin before 4.4.6 does not perform authorization checks before... |
| GHSA-8j7c-fxr7-7933 | CVE-2026-94262 | unknown | The Advanced Custom Fields: Extended WordPress plugin before 0.9.2.8, Advanced Custom Fields:... |
| GHSA-vm5g-h8fh-8cpp | CVE-2026-113499 | unknown | The LiteSpeed Cache WordPress plugin before 7.9.2 does not restrict one of its HTML rewriting... |
| GHSA-hhfq-xfxp-vh74 | CVE-2026-111737 | unknown | The Speed Optimizer  WordPress plugin before 7.8.5 does not sanitise or escape some of its... |
| GHSA-qgfq-45qj-365w | CVE-2026-111982 | unknown | The User Profile Builder  WordPress plugin before 4.0.5 does not verify that a user is authorized... |
| GHSA-f92x-x728-fq7r | CVE-2026-113472 | unknown | The Depicter — Popup & Slider Builder WordPress plugin before 4.8.2 does not properly validate... |
| GHSA-qx3q-4jp5-2qg8 | CVE-2026-112219 | unknown | The Download Monitor WordPress plugin before 5.3.5 does not correctly restrict management of the... |
| GHSA-rhrq-vr3g-vpch | CVE-2026-110537 | unknown | The Essential Addons for Elementor  WordPress plugin before 6.8.7 does not verify that an... |
| GHSA-vv9w-x7f3-8cfq | CVE-2026-111738 | unknown | The Speed Optimizer  WordPress plugin before 7.8.5 does not verify network-level privilege before... |
| GHSA-v2v8-j877-jpr5 | CVE-2026-109934 | unknown | The Otter Blocks  WordPress plugin before 3.2.8 does not correctly determine whether a post is... |
| GHSA-9mx2-qxwc-rp6q | CVE-2026-111966 | unknown | The User Profile Builder  WordPress plugin before 4.0.5 does not sanitise and escape one of its... |
| GHSA-282g-jjg9-h9cq | CVE-2026-110510 | unknown | The Essential Addons for Elementor  WordPress plugin before 6.8.7 does not validate the HTML tag... |
| GHSA-3jfj-x8x5-pch2 | CVE-2026-109935 | unknown | The Otter Blocks  WordPress plugin before 3.2.8 does not enforce its block visibility conditions... |
| GHSA-7hjg-79p8-hrjm | CVE-2026-109936 | unknown | The Otter Blocks  WordPress plugin before 3.2.8 does not correctly bound a pattern it uses to... |
| GHSA-655q-x6wx-x8mp | CVE-2026-109933 | unknown | The Otter Blocks  WordPress plugin before 3.2.8 does not properly sanitize and escape user... |
| GHSA-rmjv-pr48-2r29 | CVE-2026-115497 | high | The Music Store – WordPress eCommerce plugin for WordPress is vulnerable to Directory Traversal... |
| GHSA-qg8v-7rmw-27ch | CVE-2026-109198 | high | The Anti-Spam by CleanTalk – Spam Protection Without CAPTCHA plugin for WordPress is vulnerable... |
| GHSA-2pr8-78jh-mm95 | CVE-2026-107858 | high | Missing Origin Validation in WebSockets (CWE-1385) and Permissive Cross-domain Policy with... |
| GHSA-6x3j-5f9q-7h4j | CVE-2026-89419 | medium | OpenStack Ironic before 39.0.1 sometimes allows a user to change the maintenance setting on a... |
| GHSA-48wg-78rx-fcjg | CVE-2026-115638 | medium | OpenStack Ironic through 39.0.1 allows a denial of service via a configdrive that results in a... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| SEPIVER | qilin | MX | 2026-10-22T23:40:29.746474+00:00 |
| M... C... | SilentRansomGroup |  | 2026-10-22T19:30:40.239379+00:00 |
| United Restaurant Supply | qilin | US | 2026-10-22T18:41:39.974610+00:00 |
| AMSAM | bravox | FR | 2026-10-22T17:03:04.045393+00:00 |
| Barrow & Grimm | bravox | US | 2026-10-22T17:02:26.225218+00:00 |
| M...r | SilentRansomGroup |  | 2026-10-22T16:59:24.203647+00:00 |
| Kirkland & Ellis LLP | SilentRansomGroup | US | 2026-10-22T16:58:16.460174+00:00 |
| DR.SCHNELL GmbH & Co. KGaA | rhysida | DE | 2026-10-22T15:26:05.905806+00:00 |
| Airtificial | qilin |  | 2026-10-22T15:24:55.724478+00:00 |
| Bathurst RSL | qilin | AU | 2026-10-22T14:40:40.396076+00:00 |
| Creative Universe | qilin | AU | 2026-10-22T14:39:48.620508+00:00 |
| PWC | everest | GB | 2026-10-22T13:10:19.855983+00:00 |
| Performance Ford Inc | N0n | US | 2026-10-22T09:26:19.729068+00:00 |
| istanbultrading.com | lockbit5 | TR | 2026-10-22T21:30:20.484598+00:00 |
| Company #109 | N0n |  | 2026-10-22T07:29:09.063755+00:00 |
| Company #108 | N0n |  | 2026-10-22T07:28:34.272617+00:00 |
| Company #107 | N0n | BG | 2026-10-22T07:27:59.233928+00:00 |
| Company #106 | N0n |  | 2026-10-22T07:27:24.816240+00:00 |
| Company #105 | N0n |  | 2026-10-22T07:26:49.292466+00:00 |
| Company #104 | N0n |  | 2026-10-22T07:26:14.546647+00:00 |

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
| 80.94.95.115 | 11 |
| 80.94.95.116 | 11 |
| 45.148.10.240 | 10 |
| 64.62.197.122 | 10 |
| 107.150.123.48 | 10 |
| 169.239.75.138 | 10 |
| 2.57.122.238 | 9 |
| 45.148.10.152 | 9 |
| 66.132.172.43 | 9 |
| 102.220.161.170 | 9 |
| 152.32.225.117 | 9 |
| 160.250.132.238 | 9 |
| 193.24.211.219 | 9 |
| 195.178.110.26 | 9 |
| 2.57.122.209 | 8 |
| 3.129.187.38 | 8 |
| 3.130.168.2 | 8 |
| 18.116.101.220 | 8 |

### OpenPhish (live phishing URLs)
- https://system-update-account-ilpro.vercel.app/account-center-support
- https://www.roblox.com.et/users/1654175985/profile
- http://bc23.primus.rcassocies.com/W_PRIMUS_WINE_PROD/SignIn?ReturnUrl=%2FW_PRIMUS_WINE_PROD%2F
- http://accueilboitear24seconnecte77.jimdofree.com/
- https://accueilsurlespacear24-8744.jimdofree.com/
- http://webnailar24.jimdofree.com/
- http://accueil-servicear24boite7080.jimdofree.com/
- http://accueilservicear24boite9704.jimdofree.com/
- https://accueilservicear24boite97044.jimdofree.com/
- http://claud.vazbi.autos/
- https://ipana.fwh.is/?page_id=15
- http://simple-armadillo-6051f0.instawp.site/wp-content/plugins/indexDSAR24.html
- http://luiz-doc-ref.pages.dev/
- https://auth-ar24espc-web.vercel.app/
- https://allergro.shop/
- https://gringoxissff899.github.io/Nubank/
- https://soares16nascimento17-star.github.io/Nuba/
- https://soares16nascimento17-star.github.io/Nubank/
- https://ec2-3-11-243-50.eu-west-2.compute.amazonaws.com/wp-content/plugins/filester/assets/css/wells/signon.php?activity=&client_id=3%2A%24%29%23gNGZsn%2AqPVKtFh%29_MaM%5E5jbz7mr_gQL%21JNE%5EeSqsF2WiS&cmd=signon_submit&crumb=%28jE2Or2uXgruQnLxCeh%21p8Zi7bdAy%2B&done=&email=&id=efc1a9d099203246bf2c87b2caf22b78efc1a9d099203246bf2c87b2caf22b78&intl=&redirect_uri=&session=efc1a9d099203246bf2c87b2caf22b78efc1a9d099203246bf2c87b2caf22b78%3Fsrc%3Dq%2Bm7%5E7bEhz%24ykR_H1XGq
- https://mvrn80dqtwil-zktp2nnx-5o4m1e-zk477a.pages.dev/

### PhishStats (recent phishing/malicious URLs, scored)
_No data returned this run._

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
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
| c2cc28a75ec95c7f4109d6af0e02b9c1273fb774 | Vidar C&C |
| ee44c0aa609918ca30691fe0f49b87945d450bcd | Malware C&C |
| 3f00a128af6109bb4ba928f2a73caeb1820f561d | Malware C&C |
| e86dd566921f2733639879ecd1a3be715644cec6 | PureLogsStealer C&C |

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
- 1.117.73.220
- 1.12.36.175
- 1.12.48.131
- 1.12.55.42
- 1.12.55.80
- 1.12.70.212
- 1.14.240.247
- 1.14.94.193
- 1.14.97.120
- 1.15.106.134
- 1.15.221.192
- 1.15.30.237
- 1.152.109.139
- 1.159.54.33
- 1.178.212.25
- 1.183.196.144
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74

### CINS Army (poorly-rated IPs)
- 1.14.149.30
- 1.168.172.140
- 1.214.29.155
- 1.24.16.110
- 1.24.16.111
- 1.24.16.116
- 1.24.16.118
- 1.24.16.119
- 1.24.16.132
- 1.24.16.163
- 1.24.16.170
- 1.24.16.171
- 1.24.16.180
- 1.24.16.186
- 1.24.16.46
- 1.24.16.71
- 1.244.184.137
- 1.28.125.52
- 1.30.80.145
- 1.32.57.245

## News (last ~36h, across outlets)
### The Hacker News
- [Researchers Demonstrate Node2Shell RCE Exploit on Node.js Build Using Crafted Brotli Data](https://thehackernews.com/2026/10/researchers-demonstrate-node2shell-rce.html)
- [PHP2Shell Exploit Attempts Hit Millions as Attackers Try to Deploy Mirai Malware](https://thehackernews.com/2026/10/php2shell-exploit-attempts-hit-millions.html)
- [The AI Agent Nobody Owns: Watch Expert Webinar On Your Newest Insider Threat](https://thehackernews.com/2026/10/the-ai-agent-nobody-owns-watch-expert.html)
- [Arista Warns of Critical VeloCloud SQL Injection Zero-Day Exploited in Attacks](https://thehackernews.com/2026/10/arista-warns-of-critical-velocloud-sql.html)
- [eMudhra to Exit Global SSL/TLS Business After 8 Intermediate CA Keys Found Easily Guessable](https://thehackernews.com/2026/10/emudhra-to-exit-global-ssltls-business.html)
- [ThreatsDay: AI Secrets Leak, PingCAP Source Theft, Signal Hang-Up Flaw, Laravel Auth Bypass + 21 More](https://thehackernews.com/2026/10/threatsday-ai-secrets-leak-pingcap.html)
- [Two CVSS 9.0 Linux KSMBD RCE Flaws Disclosed on Public Mailing Lists Before Kernel Fixes](https://thehackernews.com/2026/10/two-cvss-90-linux-ksmbd-rce-flaws.html)
- [Meta Ordered to Pay $25 Billion After Court Finds 43 Million Privacy Violations](https://thehackernews.com/2026/10/meta-ordered-to-pay-25-billion-after.html)
- [INTERPOL Arrests 1,462 Suspects, Disrupts 10,909 Cybercrime Networks in Global Crackdown](https://thehackernews.com/2026/10/interpol-arrests-1462-suspects-disrupts.html)
- [Railway Says Intruder May Have Accessed Customer Secrets, Urges Credential Rotation](https://thehackernews.com/2026/10/railway-says-intruder-may-have-accessed.html)
- [OpenCode Flaw Lets Malicious MCP Servers Execute Code During Sign-In on Windows and WSL](https://thehackernews.com/2026/10/opencode-flaw-lets-malicious-mcp.html)
- [LiteLLM Suspects GitHub Token Leak in AI Gateway Logs Behind Malicious Package Release](https://thehackernews.com/2026/10/litellm-suspects-github-token-leak-in.html)
- [Node.js Brotli Decoder Bug Could Allow Remote Code Execution in All Supported Versions](https://thehackernews.com/2026/10/nodejs-brotli-decoder-bug-could-allow.html)
- [New QPACK Flaws Can Crash HTTP/3 Servers, Trigger Up to 4,000-Fold Memory Amplification](https://thehackernews.com/2026/10/new-qpack-flaws-can-crash-http3-servers.html)
- [Someone Tried to Exploit PHP2Shell 4 Days Before the Vulnerabilities Were Publicly Disclosed](https://thehackernews.com/2026/10/someone-tried-to-exploit-php2shell-4.html)

### BleepingComputer
- [Railway warns devs to rotate secrets after potential breach](https://www.bleepingcomputer.com/news/security/railway-warns-devs-to-rotate-secrets-after-potential-breach/)
- [Capcom confirms data breach affecting 11.7 million accounts](https://www.bleepingcomputer.com/news/security/capcom-confirms-data-breach-affecting-117-million-accounts/)
- [LiteLLM release pipeline hacked to distribute info-stealer malware](https://www.bleepingcomputer.com/news/security/litellm-release-pipeline-hacked-to-distribute-info-stealer-malware/)
- [Arista patches new VeloCloud Orchestrator zero-day exploited in attacks](https://www.bleepingcomputer.com/news/security/arista-patches-new-velocloud-orchestrator-zero-day-exploited-in-attacks/)
- [Microsoft shares how to fix broken Exchange Online EWS apps](https://www.bleepingcomputer.com/news/microsoft/microsoft-shares-how-to-fix-broken-exchange-online-ews-apps/)
- [Machine speed attacks require machine speed detection and response](https://www.bleepingcomputer.com/news/security/machine-speed-attacks-require-machine-speed-detection-and-response/)
- [Amazon says PHP2Shell exploitation began 4 days before patches](https://www.bleepingcomputer.com/news/security/amazon-says-php2shell-exploitation-began-4-days-before-patches/)
- [GitLab warns of new max severity code execution vulnerability](https://www.bleepingcomputer.com/news/security/gitlab-warns-of-new-max-severity-code-execution-vulnerability/)
- [Authorities disrupt nearly 11,000 cybercrime networks in Africa](https://www.bleepingcomputer.com/news/security/authorities-disrupt-nearly-11-000-cybercrime-networks-in-africa/)
- [Google Chrome adds Gemini-powered scam detection, warns users of ClickFix attacks](https://www.bleepingcomputer.com/news/google/google-chrome-adds-gemini-powered-scam-detection-warns-users-of-clickfix-attacks/)
- [Japan's Onamae Desktop Cloud hacked, up to 27,000 servers affected](https://www.bleepingcomputer.com/news/security/japans-onamae-desktop-cloud-hacked-up-to-27-000-servers-affected/)
- [Lazarus hackers use post-quantum cryptography for malware delivery](https://www.bleepingcomputer.com/news/security/lazarus-hackers-use-post-quantum-cryptography-for-malware-delivery/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [State Bank of India Suffers a Customer PII Data Leak](https://www.darkreading.com/cyberattacks-data-breaches/state-bank-india-customer-pii-data-leak)
- [Microsoft Links Storm-0940 to ConnectWise Supply Chain Attack](https://www.darkreading.com/cyberattacks-data-breaches/microsoft-storm-0940-connectwise-supply-chain-attack)
- [What We Missed: Feds Lasso Texas Laptop Farms](https://www.darkreading.com/insider-threats/texas-laptop-farms-north-korean-it-workers)
- [Les supermarchés de l'UE paient d'un firmware de réfrigérateur non mis à jour](https://www.darkreading.com/ics-ot-security/eu-grocers-unpatched-fridge-firmware-french)
- [UAE Transitions 50% of Gov't Services to Agentic AI](https://www.darkreading.com/cybersecurity-operations/uae-transitions-50-government-services-agentic-ai)
- [TiDB Breach Exposes Flawed Cloud Security Assumptions](https://www.darkreading.com/cloud-security/tidb-breach-flawed-cloud-security)

### SecurityWeek
- [LiteLLM Compromised in Fresh Supply Chain Attack](https://www.securityweek.com/litellm-compromised-in-fresh-supply-chain-attack/)
- [Atlassian Patches 75 Flaws in Data Center and Server Products](https://www.securityweek.com/atlassian-patches-75-third-party-flaws-in-data-center-and-server-products/)
- [Iran’s Prince of Persia APT Hosts C&C in US for First Time Since 2016](https://www.securityweek.com/irans-prince-of-persia-apt-hosts-cc-in-us-for-first-time-since-2016/)
- [Hacker Conversations: Corey Thuen and the Evil Bit](https://www.securityweek.com/hacker-conversations-corey-thuen-and-the-evil-bit/)
- [Indurex Raises $8 Million to Expand Industrial Cybersecurity Platform](https://www.securityweek.com/indurex-raises-8-million-to-expand-industrial-cybersecurity-platform/)
- [Signal Vulnerability Lets Malicious Callers Block Hang-Ups](https://www.securityweek.com/signal-vulnerability-lets-malicious-callers-block-hang-ups/)
- [Tech and Security Companies Respond to PHP2Shell Vulnerabilities](https://www.securityweek.com/tech-and-security-companies-respond-to-php2shell-vulnerabilities/)
- [Splunk, SolarWinds Release Fresh Security Updates](https://www.securityweek.com/splunk-solarwinds-release-fresh-security-updates/)
- [Cisco Patches 34 Vulnerabilities Across Multiple Products](https://www.securityweek.com/cisco-patches-34-vulnerabilities-across-multiple-products/)
- [PHP2Shell Exploitation Started Days Before Patches](https://www.securityweek.com/php2shell-exploitation-started-days-before-patches/)

### The Record
- [Toronto crime tips org freezes operations after details of data breach come to light](https://therecord.media/toronto-crime-tips-org-freezes-ops-after-breach)
- [Indian tech company eMudhra announces withdrawal from certificate business after security incident](https://therecord.media/indian-tech-company-announces-withdrawal-certificate-business-incident)
- [Microsoft blames ConnectWise attacks on Chinese state hacker using ARTEX AI agents](https://therecord.media/china-cyber-connectwise-ai)
- [Cybercrime crackdown across Africa leads to 1,462 arrests, $105 million seized](https://therecord.media/africa-cybercrime-interpol-arrests)
- [South Carolina officials offer assistance after state capital hit with cyberattack](https://therecord.media/south-carolina-officials-offer-assistance-cyber-incident)

### Infosecurity Magazine
- [EU Regulators to Investigate Booking.com Over Scam Risks](https://www.infosecurity-magazine.com/news/eu-bookingcom-scam-risks/)
- [Iranian Hacking Group Found Hosting C2 Infrastructure in the US](https://www.infosecurity-magazine.com/news/iranian-hacking-group-hosting-c2/)
- [Microsoft: Chinese State Actor Used AI to Compromise ConnectWise Tenants](https://www.infosecurity-magazine.com/news/microsoft-chinese-ai-connectwise/)
- [PHP2Shell Exploitation Attempt Detected by Amazon Four Days Before Vulnerability Disclosure](https://www.infosecurity-magazine.com/news/php2shell-exploitation-attempt/)
- [Cloud Security Maturity Lags Despite Widespread Adoption, SANS Warns](https://www.infosecurity-magazine.com/news/cloud-security-maturity-lags-sans/)

### CyberScoop
- [Exclusive: bipartisan bill would develop federal guidance for distillation attacks, convene industry on defensive cyber](https://cyberscoop.com/bipartisan-bill-combat-ai-distillation-attacks-nist/)
- [eMudhra kills its certificate business after researchers cracked its private keys in under a second](https://cyberscoop.com/emudhra-shuts-down-certificate-business-weak-private-keys/)
- [Encryption isn’t enough to protect data wherever it goes](https://cyberscoop.com/vaultless-keyless-pseudonymization-cybersecurity-policy-op-ed/)
- [Microsoft pins ConnectWise supply-chain attack to China-state aligned threat group](https://cyberscoop.com/microsoft-attributes-connectwise-supply-chain-attack-china-storm-0940/)

### Cisco Talos
- [I had plans for that second](https://blog.talosintelligence.com/i-had-plans-for-that-second/)
- [Compromised eMudhra intermediate certificates](https://blog.talosintelligence.com/compromised-intermediate-certificates/)

### Unit 42 (Palo Alto)
- [EMudhra Intermediate CA Certificates Compromised](https://unit42.paloaltonetworks.com/emudhra-certificate-compromise/)
- [The Current Landscape of OAuth Attacks](https://unit42.paloaltonetworks.com/current-landscape-oauth-attacks/)

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Thursday, October 22nd, 2026 https://isc.sans.edu/podcastdetail/10146, (Thu, Oct 22nd)](https://isc.sans.edu/diary/rss/33446)
- [Critical PHP Vulnerability (CVE-2026-109618, CVE-2026-109619) &#x5b;infocon yellow&#x5d;, (Wed, Oct 21st)](https://isc.sans.edu/diary/rss/33440)

### Securelist (Kaspersky)
- [How APT41 revived the BlackLotus bootkit to attack diplomatic organizations in Central Asia](https://securelist.com/uefi-bootkit-blackx/121539/)

### CrowdStrike Blog
- [CrowdStrike Uncovers New Agentic AI Campaigns](https://www.crowdstrike.com/en-us/blog/crowdstrike-uncovers-new-agentic-ai-campaigns/)
- [CrowdStrike Protects Customers from Threats Delivered via PHP2Shell](https://www.crowdstrike.com/en-us/blog/crowdstrike-protects-customers-from-php-rce-zero-days/)
- [CrowdStrike Achieves NCSC CIR Enhanced Level Assurance](https://www.crowdstrike.com/en-us/blog/crowdstrike-achieves-uk-ncsc-cir-enhanced-level-assurance/)
- [U.S. Government Disrupts FAMOUS CHOLLIMA Operation with CrowdStrike Assistance](https://www.crowdstrike.com/en-us/blog/fbi-disrupts-famous-chollima-operation-with-crowdstrike-assistance/)
- [October 2026 Patch Tuesday: 1,413 CVEs Include Three Zero-Days and 75 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-october-2026/)
- [CrowdStrike and Anthropic Give Critical Infrastructure Defenders the AI Advantage](https://www.crowdstrike.com/en-us/blog/crowdstrike-anthropic-critical-infrastructure-defense-program/)
- [Solving the Continuous Authorization Conundrum](https://www.crowdstrike.com/en-us/blog/solving-the-continuous-authorization-conundrum/)
- [Unknown Threat Actor Uses AI-Driven ARTEX to Target South Korean Finance](https://www.crowdstrike.com/en-us/blog/unknown-threat-actor-uses-artex-to-target-south-korean-finance/)
- [CrowdStrike Named a Leader in the 2026 IDC MarketScape for Worldwide Modern Endpoint Security for Enterprises Vendor Assessment](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-idc-marketscape-worldwide-modern-endpoint-security-for-enterprises/)
- [Request, Aggregate, Bypass: How Attackers Can Evade LLM Safety Classifiers](https://www.crowdstrike.com/en-us/blog/how-attackers-can-bypass-llm-safety-classifiers/)

### FortiGuard Threat Signal
- [PHP2Shell Remote Code Execution Vulnerabilities](https://fortiguard.fortinet.com/threat-signal-report/6551)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/
- https://api.phishstats.info/api/phishing?_sort=-id&_size=30 -> HTTPSConnectionPool(host='api.phishstats.info', port=443): Read timed out. (read timeout=25)

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal