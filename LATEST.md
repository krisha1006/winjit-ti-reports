# Winjit Daily TI Digest — 2026-10-29

_Auto-generated. Window: last ~24h. Fetched at 2026-10-29T09:40:55.093375+00:00Z_

**At a glance:** 2 new KEV · 59 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-41709 | Broadcom | VMware ESX | Broadcom VMWare ESX Insufficient Logging Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-46300 | Linux | Kernel | Linux Kernel Missing Initialization of a Variable Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-103406 | 9.8 | n/a | An Improper Neutralization of Special Elements used in an OS Command vulnerability in the AutomatedProvisioner in Juniper Networks Session Smart Conductor allows a remote attacker to execute arbitrary |
| CVE-2026-103409 | 9.8 | n/a | A Missing authentication for critical function vulnerability in Juniper Networks Session Smart Router allows an unauthenticated network-based attacker to obtain administrative privileges by passing cr |
| CVE-2026-118690 | 9.8 | n/a | Signal K Server before 2.33.0 contains a missing authentication vulnerability that allows unauthenticated remote attackers to download log archives via the /skServer/ziplogs endpoint. Attackers can ex |
| CVE-2026-118579 | 9.8 | n/a | A weakness has been identified in D-Link DIR-505 1.10B02. The impacted element is the function main of the file /secmark1524.cgi of the component Web Management CGI. This manipulation of the argument  |
| CVE-2026-109516 | 9.8 | n/a | The Bot for Telegram on WooCommerce plugin for WordPress is vulnerable to Authentication Bypass leading to Account Takeover in all versions up to, and including, 1.3.0. The `/wp-json/woo-telegram/v1/m |
| CVE-2026-42922 | 9.8 | n/a | A authorization bypass vulnerability exists in the /nodered functionality of FUXA (version(s): 1.3.2-2809). A specially crafted HTTP request can lead to a arbitrary code execution. An attacker can mak |
| CVE-2026-117574 | 9.1 | n/a | A flaw was found in ai-gateway-payload-processing. An authenticated remote attacker can exploit this vulnerability by submitting a request specifying another tenant's model identifier in the request b |
| CVE-2014-125138 | 8.8 | 0.4% | C97net qEngine CMS through 6.0.0, Kemana Directory through 1.5.6, and Cart Engine through 3.0.0 contain an unrestricted file upload vulnerability in administrative image fields. Editor-role users can  |
| CVE-2015-20129 | 8.8 | 0.2% | CrushFTP before 7.3.0 contains a cross-site request forgery vulnerability that allows attackers to perform administrative actions because CSRF protection is disabled by default. Attackers can lure an  |
| CVE-2026-103401 | 8.8 | n/a | An Improper Link Resolution Before File Access ('Link Following') vulnerability in the unauthenticated web server handlers in Juniper Networks Session Smart Router and Session Smart Conductor allows a |
| CVE-2026-103402 | 8.8 | n/a | An Insufficient Verification of Data Authenticity vulnerability in PCLI in Juniper Networks Session Smart Router and Session Smart Conductor allows an attacker with write access to the model cache dir |
| CVE-2026-103403 | 8.8 | n/a | An Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability in AccessManager in Juniper Networks Session Smart Router and Session Smart Conductor allows |
| CVE-2026-103407 | 8.8 | n/a | An Improper Limitation of a Pathname to a Restricted Directory vulnerability in ConfigDirector in Juniper Networks Session Smart Router and Session Smart Conductor allows an authenticated REST user to |
| CVE-2026-103408 | 8.8 | n/a | A Stack Buffer Overflow vulnerability in the DHCP client in Juniper Networks Session Smart Router allows an unauthenticated attacker on the local network to achieve remote code execution via a malicio |
| CVE-2026-106079 | 8.8 | n/a | An Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability in AccessManager in Juniper Networks Session Smart Router and Session Smart Conductor allows |
| CVE-2026-118683 | 8.8 | n/a | MONAI from 1.2.0 before 1.6.1 contains a remote code execution vulnerability in ConfigWorkflow.__init__, which passes a bundle's configs/logging.conf to logging.config.fileConfig that eval()s handler  |
| CVE-2026-118645 | 8.7 | n/a | n8n before 1.123.85, 2.x before 2.43.5, and 2.44.x before 2.44.1 contains a filter injection vulnerability in the Quick Base node, which sends the Where filter to the Quick Base API as raw query text. |
| CVE-2026-118649 | 8.3 | n/a | n8n before 2.43.5 and 2.44.x before 2.44.1 accepts a client-supplied workflow ID and caches each workflow's owner project in memory by that ID, so a crafted ID such as __proto__ makes the Data Table p |
| CVE-2026-118643 | 8.2 | n/a | n8n before 1.123.85, 2.x before 2.43.5, and 2.44.x before 2.44.1 stores credential secrets in execution error data when operations fail in the Git, MongoDB Atlas Vector Store, and Google Cloud Storage |
| CVE-2026-118647 | 8.2 | n/a | n8n before 1.123.85, 2.x before 2.43.5, and 2.44.x before 2.44.1 saves the SeaTable Trigger node's API token in error execution data, because failed poll requests store raw request headers. Users who  |
| CVE-2026-118375 | 8.1 | 0.4% | llama.cpp b8841 before b11865 contains an out-of-bounds write vulnerability in the ggml-rpc RDMA transport rdma_recv() function that allows unauthenticated peers to overflow the rpc-server stack. Atta |
| CVE-2026-84725 | 8.1 | n/a | when EAP runs with -secmgr, the openjdk-orb's JDKBridge honours attacker-supplied CDR codebase URLs during object unmarshalling on :3528, allowing an unauthenticated attacker to load and instantiate a |
| CVE-2026-109411 | 8.1 | n/a | An access control bypass flaw was found in Samba's vfs_ceph_rgw module in it's openat() function. An authenticated user can bypass access controls to read or overwrite restricted files on shares confi |
| CVE-2026-96228 | 8.1 | n/a | SSL Wireless SMS Notification for WordPress is vulnerable to Authentication Bypass in all versions up to, and including, 3.8.1. The public final_login_ajax_action handler resolves a user and issues an |
| CVE-2026-118688 | 7.9 | n/a | wasmtime-wasi in Wasmtime before 36.0.18, 37.0.0 before 48.0.6, and 49.0.0 before 49.0.3 re-appends a trailing slash to rename source paths, causing renameat on macOS and FreeBSD hosts to follow direc |
| CVE-2026-118378 | 7.8 | 0.2% | Tabularis before 0.28.0 contains an SQL injection vulnerability in its SQLite driver that allows MCP clients to execute stacked statements by supplying a crafted table_name to the describe_table tool. |
| CVE-2026-112357 | 7.8 | n/a | GFI KerioConnect (Kerio Connect) Outlook Connector (Offline Edition), 'KOFF', before 10.0.9 Patch 2 contains a local privilege escalation vulnerability caused by weak installer permissions that leave  |
| CVE-2026-118752 | 7.8 | n/a | FreeImage (danoli3 fork) before 3.19.22 contains a heap buffer overflow vulnerability in the PBM RLE decoder of PluginIFF.cpp that lacks bounds checks on ByteRun1 runs. Attackers can supply a crafted  |
| CVE-2026-118753 | 7.8 | n/a | FreeImage (danoli3 fork) before 3.19.25 contains a heap buffer overflow vulnerability in PluginGIF.cpp that allows attackers to write past the canvas allocation via unclipped GIF frame rectangles. Att |
| CVE-2026-118644 | 7.7 | n/a | n8n before 2.41.5 and 2.42.x before 2.42.2 passes a failed workflow's full execution context, including the identity of the user who started the run, to the configured error workflow. A project editor |
| CVE-2026-13451 | 7.7 | n/a | A flaw was found in KServe. A namespace-scoped user with create/update permissions on InferenceService custom resources can exploit this vulnerability by providing a malicious `storageUri`. This Serve |
| CVE-2026-118377 | 7.5 | 0.2% | mews/pos through 2.0.0 contains an insufficient verification of data authenticity vulnerability that allows unauthenticated attackers to forge payment results by submitting unverified callbacks. Garan |
| CVE-2026-118641 | 7.5 | n/a | n8n before 1.123.85, 2.x before 2.43.5, and 2.44.x before 2.44.1 contains an OData $filter injection vulnerability in the Microsoft Outlook contact lookup and Microsoft SharePoint v1 item update nodes |
| CVE-2026-118679 | 7.5 | n/a | n8n before 1.123.83, 2.41.4, and 2.42.1 contains a server-side request forgery vulnerability in the Slack Trigger webhook that allows unauthenticated attackers to exfiltrate Slack tokens by bypassing  |
| CVE-2026-118686 | 7.5 | n/a | EspoCRM before 9.3.11 and 10.x before 10.0.8 contains a denial of service vulnerability in which the password-redaction regular expression applied during API error handling consumes excessive CPU on l |
| CVE-2026-118682 | 7.5 | n/a | KaringX ClashMi through 1.0.32.1801 disables TLS certificate validation by default in the HttpUtils helper, allowing attackers to intercept HTTPS traffic by presenting any certificate. Attackers opera |
| CVE-2026-118689 | 7.5 | n/a | OvenMediaEngine through 0.21.0 contains a denial of service vulnerability in OvtPacket::LoadHeader() that allows unauthenticated attackers to stall connections by sending payload_length values above 3 |
| CVE-2026-118694 | 7.5 | n/a | python-markdown2 through 2.5.5 contains a denial of service vulnerability that allows remote users to exhaust CPU by submitting Markdown with unclosed inline link destinations. Attackers can submit re |
| CVE-2026-118803 | 7.5 | n/a | Bricks Theme 2.4.3 and before contains an unauthenticated dynamic-data tag injection vulnerability that allows anonymous attackers to control the urlParams object in the query_result REST endpoint, ca |
| CVE-2026-118804 | 7.5 | n/a | Bricks Builder 2.4.3 and before contains a broken access control vulnerability that allows unauthenticated attackers to access restricted post content by submitting crafted post_status and post_type v |
| CVE-2026-93757 | 7.5 | n/a | The Wild Apricot Login plugin for WordPress is vulnerable to Authentication Bypass via SSO Email-Collision Account Binding in all versions up to, and including, 1.0.18. When no WildApricot contact-ID  |
| CVE-2026-93855 | 7.5 | n/a | The SendPress Newsletters plugin for WordPress is vulnerable to time-based SQL Injection via the 'subscriberid' parameter in all versions up to, and including, 1.26.1.20 due to insufficient escaping o |
| CVE-2026-93904 | 7.5 | n/a | The Social Web Suite – Social Media Auto Post, Social Media Auto Publish plugin for WordPress is vulnerable to generic SQL Injection via the 'exclude_posts' parameter in all versions up to, and includ |
| CVE-2026-114488 | 7.4 | n/a | A flaw was found in Wildfly. A remote attacker can bypass authentication on IIOP EJB invocations as the CSIv2 security interceptor accepts ITTPrincipalName identity assertions in the service context w |
| CVE-2026-15564 | 7.4 | n/a | Wildfly's IIOP listener may permit deserialization of input streams before authentication is performed. An attacker who can gain access to the IIOP port may be able to construct and send malicious obj |
| CVE-2026-118648 | 7.3 | n/a | n8n before 1.123.85, 2.x before 2.43.5, and 2.44.x before 2.44.1 contains a stored cross-site scripting vulnerability because some webhook response paths, such as error responses and responses without |
| CVE-2013-20007 | 7.2 | 2.0% | Linksys WAG200G through 1.01.06 contains an OS command injection vulnerability that allows authenticated attackers to execute commands by injecting backtick-delimited input into the timer_interval par |
| CVE-2026-117607 | 7.2 | 0.7% | Xerte Online Toolkits through 3.15.5 contains a remote code execution vulnerability that allows authenticated users with system permission to run PHP by importing a crafted language pack. Attackers ca |
| CVE-2026-118755 | 7.2 | n/a | Volmarg Personal Management System through 2.1.0 contains an OS command injection vulnerability that allows authenticated users to execute shell commands via unescaped folder paths in the storage modu |
| CVE-2026-96666 | 7.2 | n/a | The Schema App Structured Data plugin for WordPress is vulnerable to Stored Cross-Site Scripting via Comment Content via 'Remove Microdata' Output Filter in all versions up to, and including, 2.3.2 du |
| CVE-2026-96669 | 7.2 | n/a | The Food Store – Online Food Delivery & Pickup plugin for WordPress is vulnerable to Stored Cross-Site Scripting via 'service_type' Cookie in all versions up to, and including, 1.5.5 due to insufficie |
| CVE-2026-96741 | 7.2 | n/a | The DSGVO All in one for WP plugin for WordPress is vulnerable to Stored Cross-Site Scripting via Comment Content via Output Buffer Regex Corruption in all versions up to, and including, 5.0 due to in |
| CVE-2026-67187 | 7.1 | n/a | Ninja Forms plugin for WordPress before 3.15.4 contains an incomplete server-side validation vulnerability that allows unauthenticated attackers to submit arbitrary values to Checkbox List, Multi-Sele |
| CVE-2026-103411 | 7.1 | n/a | An Integer Underflow vulnerability in DhcpMessageDecoder in Juniper Networks Session Smart Router allows an attacker with local network access to cause information disclosure and a denial of service v |
| CVE-2026-118642 | 7.1 | n/a | n8n before 1.123.85, 2.43.5, and 2.44.1 contains an authorization bypass vulnerability that allows authenticated members to use inaccessible credentials through inline sub-workflow nodes with non-bool |
| CVE-2026-118675 | 7.1 | n/a | n8n before 1.123.85, 2.43.5, and 2.44.1 contains a credential guard bypass vulnerability that allows editors of shared workflows to use restricted credentials by loading sub-workflows from URLs or loc |
| CVE-2026-118676 | 7.1 | n/a | n8n before 1.123.85, 2.43.5, and 2.44.1 contains an authorization bypass vulnerability that allows member users to use credentials they cannot access by omitting default node parameters. Attackers can |
| CVE-2026-118678 | 7.1 | n/a | n8n before 2.41.4 and 2.42.x before 2.42.1 contains a prototype pollution vulnerability that allows low-privileged users to alter built-in object behaviour by saving workflows with specially named con |
| CVE-2026-118692 | 7.0 | n/a | CherryTree through 1.7.2 contains an OS command injection vulnerability in CtActions::link_clicked that allows attackers to execute commands by embedding shell metacharacters in web link URLs. When th |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-cvc4-pw4g-cgpc | CVE-2026-85498 | low | A flaw was found in polkit. When processing input that begins with a null byte, an arithmetic... |
| GHSA-ghmm-gqr3-xwc7 | CVE-2026-115303 | low | The Contact Form by Supsystic WordPress plugin before 1.11.1 does not strip CR/LF characters or... |
| GHSA-874x-f28p-552g | CVE-2026-7190 | medium | A cross-site scripting (XSS) vulnerability in the ICTBroadcast software, which affects the demo... |
| GHSA-728x-3f75-69xh | CVE-2026-117174 | unknown | Rejected reason: VUL-2026-008368 為先回報之相同問題 |
| GHSA-cgx5-hf2m-237r | CVE-2026-114358 | critical | This
vulnerability exists in the Radius
Xenia M2M Platform due to insufficient validation of user... |
| GHSA-7m89-78rx-fg5j | CVE-2025-62839 | high | An use of hard-coded cryptographic key vulnerability has been reported to affect HBS 3 Hybrid... |
| GHSA-rv3x-2h7v-368w | CVE-2025-62841 | high | An use of hard-coded cryptographic key vulnerability has been reported to affect HBS 3 Hybrid... |
| GHSA-hx7p-ffjf-vx59 | CVE-2026-118030 | medium | A flaw was found in the HOTP authentication mechanism of the keycloak-services component, which... |
| GHSA-3cf5-cf36-hfwx | CVE-2026-117859 | medium | A flaw was found in the Pushed Authorization Request PAR implementation of the keycloak-services... |
| GHSA-7q7x-f5rc-ffjj | CVE-2026-117548 | medium | A NULL pointer dereference flaw was found in 389-ds-base. This flaw occurs when a ModifyDN ... |
| GHSA-jjgf-8hh9-873m | CVE-2026-117688 | medium | A flaw was found in the client registration component of Keycloak, an open-source identity and... |
| GHSA-4mr3-gfq4-fhxv | CVE-2026-117627 | medium | A flaw was found in the JWT Authorization Grant implementation of the keycloak-services component... |
| GHSA-jvj2-6jx4-m6x8 | CVE-2026-85007 | unknown | The Video Player for YouTube  WordPress plugin before 2.1.4 does not perform a capability check... |
| GHSA-v794-5r9j-cqr4 | CVE-2026-78396 | unknown | The Link Library WordPress plugin before 7.10.0 does not verify that a requested link belongs to... |
| GHSA-57vw-f9g4-3923 | CVE-2026-78395 | unknown | The Link Library WordPress plugin before 7.10.0 does not re-check the selected library's own... |
| GHSA-jcp7-hvh9-8xxq | CVE-2026-88928 | unknown | The PAYCOMET for WooCommerce WordPress plugin before 5.46 does not verify the cryptographic... |
| GHSA-hpv3-cf4r-w5fw | CVE-2026-115302 | unknown | The Contact Form by Supsystic  WordPress plugin before 1.11.1 does not restrict access to an AJAX... |
| GHSA-w5fp-cxgp-hgxf | CVE-2026-19610 | medium | A flaw was found in the platform-mbean component of JBoss EAP, which provides management access... |
| GHSA-fg44-384v-2gf8 | CVE-2026-93293 | medium | The Password Protected plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the... |
| GHSA-55j7-9hpq-4p98 | CVE-2026-86794 | unknown | The Community Events WordPress plugin before 1.6.0 does not have authorisation or nonce checks... |
| GHSA-445v-r4g3-586w | CVE-2026-89216 | unknown | The vTables  WordPress plugin before 0.3 does not properly sanitise and escape a parameter before... |
| GHSA-89hx-fmwj-cww5 | CVE-2026-15564 | high | Wildfly's IIOP listener may permit deserialization of input streams before authentication is... |
| GHSA-cghp-w6p2-hcf7 | CVE-2026-110505 | unknown | The Enable SVG, WebP, and ICO Upload WordPress plugin before 1.1.6 does not prevent animation... |
| GHSA-cmrc-7c99-5736 | CVE-2026-113617 | unknown | The Automated Import Products to Cart WordPress plugin before 1.0.4 does not sanitize a user... |
| GHSA-xjfv-965p-5j67 | CVE-2026-113616 | unknown | The LogixFast Auth WordPress plugin before 1.0.4 does not deliver its password-reset one-time... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Santiam Hospital & Clinics | anubis | US | 2026-10-28T23:32:38.524137+00:00 |
| Lowenstein Sandler LLP | SilentRansomGroup | US | 2026-10-28T23:30:55.412982+00:00 |
| susannecerda.com | lockbit5 | MX | 2026-10-29T04:03:09.015718+00:00 |
| xspringcapital.com | lockbit5 | SG | 2026-10-29T04:03:54.440445+00:00 |
| Morrison Foerster | SilentRansomGroup | US | 2026-10-28T21:29:40.152117+00:00 |
| T... E... | SilentRansomGroup |  | 2026-10-28T21:29:20.618729+00:00 |
| S... H... | SilentRansomGroup |  | 2026-10-28T21:28:57.171470+00:00 |
| Fortrex | Wallstreet | US | 2026-10-28T21:31:10.907978+00:00 |
| The Anglican International School | Global Secret Group | IL | 2026-10-28T20:24:06.315999+00:00 |
| L... | SilentRansomGroup |  | 2026-10-28T17:34:09.834165+00:00 |
| Noelker and Hull | rhysida | US | 2026-10-28T16:59:06.260497+00:00 |
| Hauhinco | payload | DE | 2026-10-28T14:49:50.250850+00:00 |
| Marbre Design | payload | FR | 2026-10-28T14:48:35.878124+00:00 |
| Company #112 | N0n | MY | 2026-10-28T07:53:44.722544+00:00 |
| Echo.com | Whitearmor | DE | 2026-10-28T02:10:02.050465+00:00 |
| wagyu.xyz unfairness | Whitearmor |  | 2026-10-28T02:10:42.771753+00:00 |
| PQE Group | Panzer | IT | 2026-10-28T18:26:50.917009+00:00 |
| Trulife | akira |  | 2026-10-28T13:37:58.825942+00:00 |
| Roberts Consulting Services | akira |  | 2026-10-28T13:37:39.134708+00:00 |
| EWM Group | aurora | GB | 2026-10-28T13:00:09.407449+00:00 |

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
| 2.57.122.238 | 10 |
| 45.148.10.240 | 10 |
| 77.90.185.20 | 10 |
| 195.178.110.26 | 10 |
| 14.34.249.175 | 9 |
| 45.148.10.119 | 9 |
| 45.148.10.141 | 9 |
| 45.148.10.152 | 9 |
| 46.151.178.14 | 9 |
| 58.182.58.128 | 9 |
| 66.132.195.94 | 9 |
| 94.154.43.63 | 9 |
| 103.159.2.113 | 9 |
| 167.94.146.51 | 9 |
| 196.189.236.67 | 9 |
| 209.99.190.186 | 9 |
| 220.80.223.144 | 9 |
| 2.57.121.25 | 8 |
| 2.57.121.112 | 8 |
| 2.57.122.76 | 8 |

### OpenPhish (live phishing URLs)
- https://signin.broker/E.-hMc2FZ9GQs9hA
- https://rbcode.net/v/0b972db75a826160df8877b137bc6039
- https://my-aol-account.blogspot.com/
- https://www.my-aol-account.blogspot.com/
- http://constant-standard-cris.vercel.app/
- http://roblox.ss/communities/6464021279/CLOTHING
- https://mcodashop.topup-diamonds.com/
- https://zoffry.qpon/Adb/
- http://www.constant-standard-cris.vercel.app/
- https://www.roblox.ly/users/1458147996/profile
- https://portal.cod-indigenouslocalknowledge.org/adoc/
- https://www.systemtupdate.vercel.app/
- https://yhgwyqom.elementor.cloud/es/SPAIN/es/arg/Aa/A/ES/argentina/ar/ES9D303ESS/ESS4Z3499SES/82CFGU2554/index.html
- https://www.roblox.com.ss/users/2922440158/profile
- http://www.pnfp.lol/
- https://accountprotectonmicrsoftclo.silverveilvalley.de/JiOex?e=neletsys@090019cbe7396c95280cc516762413f31f2e.org
- https://www.roblox.com.kz/users/600806000/profile
- https://hameem.net/adobe.live/index.html
- https://sgplay.speciallshop.com/
- http://updatepasswrd-23l7.vercel.app/

### PhishStats (recent phishing/malicious URLs, scored)
_No data returned this run._

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| 32facbb63422b11875f949b45ceb306e4673a3b7 | Malware C&C |
| db1370abc2fbcfc4d9dc332b56f0d2e91deb9d23 | PureLogsStealer C&C |
| 840910d1faf7f934326f08cd5424862ca50646d5 | OffLoader C&C |
| b843ff0bf989bbda8086054a9d9ce65e885e4845 | RevStealer C&C |
| 62ddff80b88f12d3ca6ba44eb09b5e7ba9e2f390 | RevStealer C&C |
| 4623e7174a6917c16402029733c2aaa14d2f83dd | RevStealer C&C |
| 3a2dc08faa4e47e147c1293b240d7502efa7db48 | Vidar C&C |
| be3eba6ce90c5d19ee1e986170e96323108d092d | Vidar C&C |
| 2444b1d1f72da59dc3bcc0191170509822344090 | Vidar C&C |
| 875a92bb886a52699413fb2e4370adc03c1eda37 | QuasarRAT C&C |
| b3419f377a0765d386af3f3a61bede653db873f7 | ArvionRAT C&C |
| 891b265025da1fe909b4792dfe0f3df462694bef | ConnectWise C&C |
| d8d068667512bafa6720747c23266764f70638a9 | ConnectWise C&C |
| f7c6d6e9767952571df5b177956e71f6e664711d | ConnectWise C&C |
| 9c1e389a6cea4a7eb32b2e1d89acedfd5b7a52f9 | ConnectWise C&C |
| 8a6380c8c1857ae5e6c215fc9593e152d2350c87 | ConnectWise C&C |
| 33f97c9513d957c407b1fb86aee23c20f9145680 | ConnectWise C&C |
| b850658af6eba65201db37e5e0491bc33b8bba8e | ConnectWise C&C |
| d7ab2ab9aa49099722347f16ecdebd91097d1aa0 | ConnectWise C&C |
| bea642be1361616c46c371216f52414d41ad58d7 | ConnectWise C&C |

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
- 1.12.55.42
- 1.14.240.247
- 1.140.72.67
- 1.144.106.82
- 1.15.106.134
- 1.159.54.33
- 1.162.208.86
- 1.179.238.84
- 1.180.246.242
- 1.187.164.7
- 1.187.213.56
- 1.192.80.17
- 1.2.252.192
- 1.20.243.85
- 1.201.146.109
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.219.121.34

### CINS Army (poorly-rated IPs)
- 1.15.14.29
- 1.189.248.116
- 1.193.57.144
- 1.193.63.52
- 1.214.29.155
- 1.215.138.43
- 1.223.11.69
- 1.236.254.202
- 1.24.16.106
- 1.24.16.121
- 1.24.16.132
- 1.24.16.174
- 1.24.16.186
- 1.24.16.4
- 1.24.16.43
- 1.24.16.78
- 1.24.16.79
- 1.24.16.83
- 1.24.16.94
- 1.244.184.137

## News (last ~36h, across outlets)
### The Hacker News
- [Hackers Exploited Cisco SD-WAN Flaw to Plant Malware Built to Steal Encryption Keys](https://thehackernews.com/2026/10/hackers-exploited-cisco-sd-wan-flaw-to.html)
- [China-Linked Hackers Exploited VMware ESX Zero-Day to Reduce Audit Trail Visibility](https://thehackernews.com/2026/10/china-linked-hackers-exploited-vmware.html)
- [Attackers Exploit PHP2Shell Flaws in Internet-Exposed Palo Alto Networks Management Interfaces](https://thehackernews.com/2026/10/attackers-exploit-php2shell-flaws-in.html)
- [Volt Typhoon Used Covert Silent Train Network in Four Zero-Day Exploitation Campaigns](https://thehackernews.com/2026/10/volt-typhoon-used-covert-silent-train.html)
- [Google to Allow One-Tap Android App Installs From Approved Third-Party Stores Outside U.S.](https://thehackernews.com/2026/10/google-to-allow-one-tap-android-app.html)
- [Researcher Reveals How Logic Bugs Alone Cracked Microsoft Edge in $175,000 Pwn2Own Win](https://thehackernews.com/2026/10/researcher-reveals-how-logic-bugs-alone.html)
- [PHP2Shell Attack Roots 25 Servers, Breaches U.S. Government-Affiliated Network](https://thehackernews.com/2026/10/php2shell-attack-roots-25-servers.html)
- [Hackers Target Critical Oracle E-Business Suite RCE Flaw Days After Security Patch](https://thehackernews.com/2026/10/hackers-target-critical-oracle-e.html)
- [Critical 16-Year-Old UEFI Flaw Can Run Code Before Secure Boot on Network-Booting Servers](https://thehackernews.com/2026/10/critical-16-year-old-uefi-flaw-can-run.html)
- [Wazuh and AI for Enhanced SOC Workflows](https://thehackernews.com/2026/10/wazuh-and-ai-for-enhanced-soc-workflows.html)
- [Adobe Fixes 8 Critical Campaign Classic Flaws Allowing Code Execution and Security Bypass](https://thehackernews.com/2026/10/adobe-fixes-8-critical-campaign-classic.html)
- [American Organizations Under Attack: Skyw4lker Device Code Phishing Campaign Exposed](https://thehackernews.com/2026/10/american-organizations-under-attack.html)
- [Anthropic's Unreleased AI Model Chains Flaws Into Working Chrome, Safari, Windows and Linux Exploits](https://thehackernews.com/2026/10/anthropics-unreleased-ai-model-chains.html)
- [FBI Seizes Virtualine Domain Over Alleged Criminal Hosting and Bitcoin Money Laundering](https://thehackernews.com/2026/10/fbi-seizes-virtualine-domain-over.html)
- [Japan's GMO Offers $1 Million Bounty to Catch Hackers Behind FX Trading Cloud Breach](https://thehackernews.com/2026/10/japans-gmo-offers-1-million-bounty-to.html)

### BleepingComputer
- [Police seize Virtualine bulletproof service tied to ransowmare, cybercrime](https://www.bleepingcomputer.com/news/security/police-seize-virtualine-bulletproof-service-tied-to-ransowmare-cybercrime/)
- [Discord to let search engines index public server messages](https://www.bleepingcomputer.com/news/security/discord-to-let-search-engines-index-public-server-messages/)
- [Sony ISP subsidiary data breach exposes 2.5 million customer records](https://www.bleepingcomputer.com/news/security/sony-isp-subsidiary-data-breach-exposes-25-million-customer-records/)
- [Volt Typhoon hides zero-day attacks using 'Silent Train' framework](https://www.bleepingcomputer.com/news/security/volt-typhoon-hides-zero-day-attacks-using-silent-train-framework/)
- [Microsoft urges Entra ID admins to migrate users to passkeys](https://www.bleepingcomputer.com/news/microsoft/microsoft-reminds-entra-id-admins-to-migrate-users-to-passkeys/)
- [InfraTrust report warns of exploited flaws in critical network infrastructure](https://www.bleepingcomputer.com/news/security/infratrust-report-warns-of-exploited-flaws-in-critical-network-infrastructure/)
- [Even after PHP2Shell, blast radius matters more than a CVSS score](https://www.bleepingcomputer.com/news/security/even-after-php2shell-blast-radius-matters-more-than-a-cvss-score/)
- [Hackers now scanning systems for recently-patched Oracle flaw](https://www.bleepingcomputer.com/news/security/hackers-now-scanning-systems-for-recently-patched-oracle-flaw/)
- [CISA warns of hackers now exploiting critical Node2Shell flaw](https://www.bleepingcomputer.com/news/security/cisa-warns-of-hackers-now-exploiting-critical-node2shell-flaw/)
- [Nefilim and Hive ransomware affiliate gets 70 months in prison](https://www.bleepingcomputer.com/news/security/nefilim-and-hive-ransomware-affiliate-gets-70-months-in-prison/)
- [Japan's GMO urges customers to shut down PCs amid ransomware threat](https://www.bleepingcomputer.com/news/security/japans-gmo-urges-customers-to-shut-down-pcs-amid-ransomware-threat/)
- [OpenAI's GPT-6.1 Terra is safer overall, but shows more destructive-action flags in tests](https://www.bleepingcomputer.com/news/artificial-intelligence/openais-gpt-61-terra-is-safer-overall-but-shows-more-destructive-action-flags-in-tests/)
- [UNM Health ransomware attack disrupts patient care, surgeries](https://www.bleepingcomputer.com/news/security/unm-health-ransomware-attack-disrupts-patient-care-surgeries/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [Cyber Vulnerabilities Besiege Italy, Absent Clear Cause](https://www.darkreading.com/cybersecurity-analytics/cyber-vulnerabilities-besiege-italy)
- [GhostAction Hacking Wave Fizzles, But Attackers Lurk on in GitHub](https://www.darkreading.com/application-security/ghostaction-hacking-wave-fizzles-attackers-github)
- [Attacker Relentlessly Scans for Credentials by Impersonating AI Bots](https://www.darkreading.com/cyber-risk/attacker-impersonates-ai-bots-scans-credentials)
- [Third Serengeti Sweep Tops 1,400 Arrests as Investigations Mature](https://www.darkreading.com/cybersecurity-operations/third-serengeti-sweep-1400-arrests-investigations-mature)

### SecurityWeek
- [HHS Filing Puts iRhythm Data Breach Toll at 8.2 Million](https://www.securityweek.com/hhs-filing-puts-irhythm-data-breach-toll-at-8-2-million/)
- [Chinese Hackers Quietly Used Low-Severity ESXi Logging Flaw as Zero-Day](https://www.securityweek.com/chinese-hackers-quietly-used-low-severity-esxi-logging-flaw-as-zero-day/)
- [Ukrainian Hive and Nefilim Ransomware Affiliate Gets 70 Months in US Prison](https://www.securityweek.com/ukrainian-hive-and-nefilim-ransomware-affiliate-gets-70-months-in-us-prison/)
- [Upwind Security Raises $400 Million at $3.8 Billion Valuation](https://www.securityweek.com/upwind-security-raises-400-million-at-3-8-billion-valuation/)
- [Chrome and Firefox Updates Patch Over 200 Vulnerabilities](https://www.securityweek.com/chrome-and-firefox-updates-patch-over-200-vulnerabilities/)
- [TLS Flaws Found in GoAhead Web Server Used in Hundreds of Millions of Devices](https://www.securityweek.com/tls-flaws-found-in-goahead-web-server-used-in-hundreds-of-millions-of-devices/)
- [China-Linked Hackers Exploit PHP2Shell to Root Firewalls](https://www.securityweek.com/china-linked-hackers-exploit-php2shell-to-root-firewalls/)
- [Long-Hidden Flaws Patched in EPICS Research Facility Control Software](https://www.securityweek.com/long-hidden-flaws-patched-in-epics-research-facility-control-software/)
- [Nobody Trusts the Security Questionnaire. We Rely on It Anyway.](https://www.securityweek.com/nobody-trusts-the-security-questionnaire-we-rely-on-it-anyway/)
- [Secrets Management Firm Infisical Valued at $600 Million After $40 Million Raise](https://www.securityweek.com/secrets-management-firm-infisical-valued-at-600-million-after-40-million-raise/)

### The Record
- [Court strikes down West Virginia law barring disclosure of public officials’ personal data](https://therecord.media/west-virginia-daniels-law-struck-down-appellate-court)
- [Japan Airlines warns of data breach as country grapples with multiple cyber incidents](https://therecord.media/japan-airlines-warns-of-breach-country-grapples-with-incidents)
- [European digital rights nonprofit noyb sues Scale AI for ‘invasive’ worker surveillance](https://therecord.media/noyb-sues-scale-ai-for-worker-surveillance)
- [US sanctions Russians, North Koreans for laundering IT worker earnings](https://therecord.media/north-korea-russia-sanctions)
- [Moldova investigates possible foreign involvement in major government cyberattack](https://therecord.media/moldova-investigates-possible-foreign-involvement-cyberattacks)

### Infosecurity Magazine
- [MR ROBOT Malware-as-a-Service Targets Indian Bank Customers](https://www.infosecurity-magazine.com/news/robot-malware-indian-bank-customers/)
- [Japan’s GMO Internet Urges Customers to Disconnect PCs](https://www.infosecurity-magazine.com/news/japan-gmo-internet-disconnect/)
- [Attackers Hide Malware Behind Signed ChatGPT and Claude Binaries](https://www.infosecurity-magazine.com/news/attackers-hide-malware-behind/)
- [AI Is Turning CISOs Into Business-Risk Translators, Says Nvidia’s Head of Cyber](https://www.infosecurity-magazine.com/news/ai-is-turning-cisos-into/)
- [Energy Giant Engie Notifies Customers of Supply Chain Breach](https://www.infosecurity-magazine.com/news/energy-giant-engie-supply-chain/)

### CyberScoop
- [Officials seize domain of top bulletproof hosting provider Virtualine](https://cyberscoop.com/virtualine-bulletproof-hosting-provider-seized/)
- [Leak site publishes data on more than 41,000 DHS employees obtained by hacktivists](https://cyberscoop.com/dhs-employee-data-leak-ddosecrets/)
- [Lawsuit against Ex-Overstock CEO tied to 2020 election film falls apart over question of ‘actual malice’](https://cyberscoop.com/patrick-byrne-dominion-defamation-lawsuit-actual-malice/)
- [Researchers uncover Volt Typhoon’s covert, ephemeral network](https://cyberscoop.com/volt-typhoon-silent-train-covert-ephemeral-network-black-lotus-labs/)
- [Prosecutors charge Madagascar scammers in NFT-stealing scheme based on fake online dating profiles](https://cyberscoop.com/madagascar-nft-dating-scam-charges/)

### Cisco Talos
- [Inside KeyDrift: Analyzing historical UAT-11473 activity on Cisco SD-WAN](https://blog.talosintelligence.com/uat-11473-keydrift/)

### Unit 42 (Palo Alto)
- [Unwrapping Retail Peak Season Cyber Threats](https://unit42.paloaltonetworks.com/unwrapping-retail-cyber-threats/)

### Microsoft Security Blog
- [The CISO’s evolving role: Protecting and defending in the agentic era](https://www.microsoft.com/en-us/security/blog/2026/10/28/the-cisos-evolving-role-protecting-and-defending-in-the-agentic-era/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [Deploying a Local Ghidra Server for Your Malware Analysis Lab, (Thu, Oct 29th)](https://isc.sans.edu/diary/rss/33470)
- [ISC Stormcast For Thursday, October 29th, 2026 https://isc.sans.edu/podcastdetail/10156, (Thu, Oct 29th)](https://isc.sans.edu/diary/rss/33468)
- [Yet Another ClickFix Campaign, (Wed, Oct 28th)](https://isc.sans.edu/diary/rss/33466)
- [ISC Stormcast For Wednesday, October 28th, 2026 https://isc.sans.edu/podcastdetail/10154, (Wed, Oct 28th)](https://isc.sans.edu/diary/rss/33464)

### Securelist (Kaspersky)
- [Unknown APT uses NetamLoader to attack a Win10 OS customized for governments in Asia](https://securelist.com/netamloader/121676/)
- [Millions of security cameras at risk: DoS vulnerability in Intelbras devices](https://securelist.com/intelbras-camera-vulnerability/121131/)

### CrowdStrike Blog
- [CrowdStrike 2026 Legal Threat Landscape Report: eCrime Leads Attacks, China Activity Intensifies](https://www.crowdstrike.com/en-us/blog/crowdstrike-2026-legal-threat-landscape-report/)
- [When AI Guardrails Expose Vulnerabilities](https://www.crowdstrike.com/en-us/blog/when-ai-guardrails-expose-vulnerabilities/)
- [Why Organizations Secure AI Agents with Falcon Guardian](https://www.crowdstrike.com/en-us/blog/why-organizations-secure-ai-agents-with-falcon-guardian/)
- [Obstacles to Weaponizing PHP2Shell Likely Constrain Immediate Widespread Exploitation](https://www.crowdstrike.com/en-us/blog/obstacles-to-weaponizing-php2shell-likely-constrain-exploitation/)
- [CrowdStrike Protects Customers from Threats Delivered via PHP2Shell](https://www.crowdstrike.com/en-us/blog/crowdstrike-protects-customers-from-php-rce-zero-days/)
- [CrowdStrike Uncovers New Agentic AI Campaigns](https://www.crowdstrike.com/en-us/blog/crowdstrike-uncovers-new-agentic-ai-campaigns/)
- [CrowdStrike Achieves NCSC CIR Enhanced Level Assurance](https://www.crowdstrike.com/en-us/blog/crowdstrike-achieves-uk-ncsc-cir-enhanced-level-assurance/)
- [U.S. Government Disrupts FAMOUS CHOLLIMA Operation with CrowdStrike Assistance](https://www.crowdstrike.com/en-us/blog/fbi-disrupts-famous-chollima-operation-with-crowdstrike-assistance/)
- [October 2026 Patch Tuesday: 1,413 CVEs Include Three Zero-Days and 75 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-october-2026/)
- [CrowdStrike and Anthropic Give Critical Infrastructure Defenders the AI Advantage](https://www.crowdstrike.com/en-us/blog/crowdstrike-anthropic-critical-infrastructure-defense-program/)

### FortiGuard Threat Signal
- [Node.js Brotli Remote Code Execution (Node2Shell)](https://fortiguard.fortinet.com/threat-signal-report/6556)
- [PHP2Shell Remote Code Execution Vulnerabilities](https://fortiguard.fortinet.com/threat-signal-report/6551)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/
- https://api.phishstats.info/api/phishing?_sort=-id&_size=30 -> 502 Server Error: Bad Gateway for url: https://api.phishstats.info/api/phishing?_sort=-id&_size=30

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal