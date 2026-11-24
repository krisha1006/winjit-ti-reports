# Winjit Daily TI Digest — 2026-11-24

_Auto-generated. Window: last ~24h. Fetched at 2026-11-24T13:26:34.615327+00:00Z_

**At a glance:** 2 new KEV · 66 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-133968 | Project MONAI | MONAI Label | Project MONAI MONAI Label Path Traversal Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-134624 | N-able | MailAssure | N-able MailAssure (SpamExperts) Server-Side Request Forgery (SSRF) Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-134882 | 10.0 | 2.5% | A weakness has been identified in TOTOLINK A7100RU 7.4cu.2313_B20191024. This issue affects the function exportOvpn of the file /cgi-bin/cstecgi.cgi of the component CGI Handler. This manipulation of  |
| CVE-2026-62841 | 10.0 | n/a | Improper authentication in Azure Event Grid allows an unauthorized attacker to elevate privileges over a network. |
| CVE-2026-50691 | 9.9 | n/a | Improper authorization in M365 Copilot allows an authorized attacker to elevate privileges over a network. |
| CVE-2026-70193 | 9.9 | n/a | Improper limitation of a pathname to a restricted directory ('path traversal') in Microsoft Office SharePoint allows an authorized attacker to execute code over a network. |
| CVE-2026-120382 | 9.8 | 1.2% | An improper neutralization of argument delimiters in a command vulnerability in the OAuth API in Synology DiskStation Manager (DSM) before 7.1.1-42962-10, 7.2.1-69057-14, 7.2.2-72806-11, 7.3.2-86009-6 |
| CVE-2026-135208 | 9.8 | n/a | Kerberos Agent before 3.14.4 contains an authentication bypass vulnerability that allows unauthenticated attackers to forge administrator tokens because JWTMiddleWare() falls back to the hard-coded ke |
| CVE-2026-135202 | 9.8 | n/a | Several plugins for WordPress published by WP connect (Orders Sync to Airtable for WooCommerce, Add-On for Contact Form 7 to Notion, WP Sync for Notion – Notion to WordPress, Add-On for Contact Form 7 |
| CVE-2026-119582 | 9.8 | n/a | Improper neutralization of special elements used in an SQL command ('SQL injection') vulnerability in ITG Bilgisayar Teknoloji Grubu Tic. Ltd. Şti. VSRM allows SQL Injection.

This issue affects vSRM: |
| CVE-2026-109480 | 9.6 | n/a | Server-side request forgery in Profile Data Roaming Service (PDRS) allows an authorized attacker to elevate privileges over a network. |
| CVE-2026-118285 | 9.6 | n/a | Server-side request forgery in Azure Machine Learning allows an authorized attacker to elevate privileges over a network. |
| CVE-2026-70305 | 9.6 | n/a | Improper neutralization of input during web page generation ('cross-site scripting') in Azure Portal allows an unauthorized attacker to perform spoofing over a network. |
| CVE-2026-109490 | 9.3 | n/a | Improper neutralization of input during web page generation ('cross-site scripting') in Authentication Methods Portal Extension allows an unauthorized attacker to elevate privileges over a network. |
| CVE-2026-113824 | 9.1 | n/a | Authorization bypass through user-controlled key in Microsoft Clarity allows an unauthorized attacker to elevate privileges over a network. |
| CVE-2026-118286 | 9.1 | n/a | Improper access control in Azure Site Recovery allows an unauthorized attacker to elevate privileges over a network. |
| CVE-2026-69899 | 9.1 | n/a | Authentication bypass by spoofing in Azure DevTest Labs allows an unauthorized attacker to perform spoofing over a network. |
| CVE-2026-117593 | 9.1 | n/a | Weak Password Recovery Mechanism for Forgotten Password vulnerability in ITG Bilgisayar Teknoloji Grubu Tic. Ltd. Şti. VSRM allows Password Recovery Exploitation.

This issue affects vSRM: from v14.08 |
| CVE-2026-135436 | 8.8 | n/a | KindleEar 3.0.0 through 3.5.3 contains a remote code execution vulnerability that allows authenticated non-admin users to run Python code by uploading malicious recipes. Attackers can submit crafted r |
| CVE-2026-101862 | 8.8 | n/a | EUSurvey through 1.6, prior to commit 0669a36, contains a path traversal vulnerability in the survey import function that allows authenticated attackers with the Form Manager role to execute arbitrary |
| CVE-2026-101863 | 8.8 | n/a | EUSurvey 1.5.5 through 1.6, prior to commit d5295d5, contains a missing authorization vulnerability in the POST /forms/bulkchange endpoint that allows any authenticated user to take over or delete oth |
| CVE-2026-135691 | 8.8 | n/a | Open5GS WebUI through 2.8.0 contains an incorrect authorization vulnerability in webui/server/routes/db.js that allows authenticated user-role accounts to modify the Account model. Attackers can send  |
| CVE-2026-135692 | 8.8 | n/a | rConfig Core 8.0.0 before 8.2.17 and rConfig Pro before 8.4.0 contain a PHP object injection vulnerability in app/Casts/EncryptStringCast.php that unserializes decrypted attributes without class restr |
| CVE-2026-135695 | 8.8 | n/a | rConfig Core 8.0.0 before 8.2.13 and rConfig Pro before 8.4.0 contain an authorization bypass vulnerability in the users API that allows authenticated users to modify other accounts. Attackers can sen |
| CVE-2026-121016 | 8.8 | n/a | The affected products insufficiently restrict runtime-supplied visualization data, allowing local program execution on the engineering workstation, if a user is both logged in to a CODESYS Control run |
| CVE-2026-121018 | 8.8 | n/a | The affected products insufficiently restrict runtime-supplied visualization commands, allowing local functionality on the engineering workstation to be invoked, if a user is both logged in to a CODES |
| CVE-2026-119543 | 8.8 | n/a | Authorization bypass through User-Controlled key vulnerability in ITG Bilgisayar Teknoloji Grubu Tic. Ltd. Şti. VSRM allows Accessing Functionality Not Properly Constrained by ACLs.

This issue affect |
| CVE-2026-135693 | 8.7 | n/a | rConfig Core 8.0.0 before 8.2.17 and rConfig Pro before 8.4.0 contain a stored cross-site scripting vulnerability in the Config Search View Matches dialog, which renders configuration context via v-ht |
| CVE-2026-136128 | 8.7 | n/a | WPC Linked Variation plugin for WordPress, all versions before 4.6.1, contain a stored cross-site scripting vulnerability that allows authenticated attackers with Contributor-level access to inject ar |
| CVE-2026-69437 | 8.6 | n/a | Missing authorization in Azure AI Foundry allows an unauthorized attacker to disclose information over a network. |
| CVE-2026-81962 | 8.6 | n/a | Incorrect authorization in Azure Machine Learning allows an unauthorized attacker to disclose information over a network. |
| CVE-2026-65817 | 8.3 | n/a | Improper neutralization of special elements used in an os command ('os command injection') in Azure Managed Instance for Apache Cassandra allows an unauthorized attacker to execute code over an adjace |
| CVE-2026-101866 | 8.2 | n/a | EUSurvey through 1.6, prior to commit 118facd, contains an authorization bypass vulnerability in the public POST /runner/draft/runner endpoint that allows unauthenticated attackers to overwrite anothe |
| CVE-2026-135157 | 8.1 | n/a | Future AGI before 1.51.0 contains an authentication bypass vulnerability in ACSView.post that allows authenticated members of any organization to take over accounts in other organizations by asserting |
| CVE-2026-135171 | 8.1 | n/a | Wing FTP Server before 8.2.8 contains a predictable session identifier vulnerability that allows unauthenticated attackers to hijack administrator sessions by deriving identifiers from process, time,  |
| CVE-2026-135175 | 8.1 | n/a | ZITADEL 4.19.5 before 4.20.3 contains a host header injection vulnerability that allows unauthenticated attackers to redirect notification links by placing a trusted host in the userinfo portion of th |
| CVE-2026-135211 | 8.1 | n/a | BISHENG before 3.0.0 contains a missing authentication vulnerability in the /api/v2/workflow/invoke and /api/v2/workflow/stop routes that allows unauthenticated attackers to run workflows as the admin |
| CVE-2026-101867 | 8.1 | n/a | EUSurvey through 1.6, prior to commit edb5021, contains an incorrect authorization vulnerability in the GET /settings/shareEdit/{shareId} and POST /settings/shares handlers that allows any authenticat |
| CVE-2026-135689 | 8.1 | n/a | Community Store for Concrete CMS before 2.8.0 contains a stored cross-site scripting vulnerability that allows unauthenticated attackers to inject script via the order email in single_pages/dashboard/ |
| CVE-2026-135743 | 8.1 | n/a | FFmpeg 4.3 before 9.1 contains a heap out-of-bounds read and write vulnerability in the dynaudnorm filter because cqueue_resize() miscalculates gain history queue element counts when gausssize changes |
| CVE-2026-136120 | 8.1 | n/a | Ziit 1.3.2 contains a cross-site request forgery vulnerability in the /api/auth/epilogue/callback handler that accepts requests lacking the OAuth state parameter. Attackers can lure a signed-in victim |
| CVE-2026-136126 | 8.1 | n/a | c-icap-server through 0.5.15 and 0.6.5 contains an out-of-bounds write in process_encapsulated() that allows unauthenticated attackers to corrupt heap memory by sending six Encapsulated entities. Atta |
| CVE-2026-135722 | 7.8 | n/a | FFmpeg before 9.1 contains a heap-based buffer overflow vulnerability in peak_init_writer() and wav_write_packet() in libavformat/wavenc.c that allows attackers to corrupt heap memory by supplying aud |
| CVE-2026-135725 | 7.8 | n/a | FFmpeg before 9.1 contains a stack-based buffer overflow vulnerability in ff_rtmp_packet_write() in libavformat/rtmppkt.c that allows malicious RTMP servers to overflow a 16-byte header buffer. Attack |
| CVE-2026-135734 | 7.8 | n/a | FFmpeg before 9.1 contains a heap out-of-bounds write vulnerability in the deflicker filter that lets attackers corrupt heap memory via unclamped high bit depth luma samples. Attackers can supply craf |
| CVE-2026-135737 | 7.8 | n/a | FFmpeg before 9.1 contains a heap out-of-bounds write and read vulnerability in the tmidequalizer filter that allows attackers to corrupt memory by supplying high bit depth samples exceeding the nomin |
| CVE-2026-135738 | 7.8 | n/a | FFmpeg before 9.1 contains a heap out-of-bounds write vulnerability in libavfilter/vf_signalstats.c that allows attackers to corrupt heap memory by supplying high bit depth samples exceeding the nomin |
| CVE-2026-135740 | 7.8 | n/a | FFmpeg before 9.1 contains a heap out-of-bounds write vulnerability in libavfilter/vf_readeia608.c because build_histogram() does not clamp high bit depth luma samples to the nominal maximum. Attacker |
| CVE-2026-101864 | 7.7 | n/a | EUSurvey through 1.6, prior to commit a4161a9, contains a weak password recovery mechanism that allows attackers who obtain a still-valid password-reset link to take over accounts that use a local EUS |
| CVE-2026-120787 | 7.5 | n/a | Improper certificate validation in Microsoft Office PowerPoint allows an unauthorized attacker to execute code over a network. |
| CVE-2026-129837 | 7.5 | n/a | A flaw was found in rsyslog. A remote, unauthenticated attacker can cause a Denial of Service (DoS) by sending a specially crafted log message with an unusual timestamp. When the service processes thi |
| CVE-2026-101868 | 7.5 | n/a | EUSurvey through 1.6, prior to commit 4bf95a3, contains an authorization bypass vulnerability in the GET /preparepublishedcontribution/{id} endpoint that allows unauthenticated attackers to read priva |
| CVE-2026-101869 | 7.5 | n/a | EUSurvey 1.4.4.6738 through 1.6, prior to commit de1145c, contains an SQL injection vulnerability in the public results page GET /publication/{shortname} that allows unauthenticated attackers to infer |
| CVE-2026-101870 | 7.5 | n/a | EUSurvey through 1.6, prior to commit de1145c, contains an authorization bypass vulnerability in the public POST /editcontribution/{code} endpoint that allows unauthenticated attackers to overwrite an |
| CVE-2026-101871 | 7.5 | n/a | EUSurvey 1.5.2 through 1.6, prior to commit ffd5da7, contains a missing authorization vulnerability in the public POST /runner/delphiUpdate endpoint that allows unauthenticated attackers to submit res |
| CVE-2026-135696 | 7.5 | n/a | rConfig Core 8.2.19 before 8.2.22 contains a server-side request forgery vulnerability that allows authenticated users to bypass the DeviceIpIsValid loopback guard by supplying unresolved hostnames. A |
| CVE-2026-135742 | 7.5 | n/a | FFmpeg before 9.1 contains a heap buffer overflow vulnerability in recv_msg() of the zmq and azmq filters that allows unauthenticated network attackers to corrupt memory by sending oversized command m |
| CVE-2026-136123 | 7.5 | n/a | Friendica through 2026.05-1 contains an improper validation vulnerability in APContact::compactProfile() that allows remote actors to overwrite a local user's stored inbox and public key by declaring  |
| CVE-2026-82216 | 7.5 | n/a | Server-Side request forgery (SSRF) vulnerability in ITG Bilgisayar Teknolojileri Grubu Ltd. Şti. VSRM allows Server Side Request Forgery.

This issue affects vSRM: from 14.08.1 before 14.08.3. |
| CVE-2026-135300 | 7.4 | n/a | Pomerium from 0.30.0 before 0.34.0 contains an authentication bypass vulnerability in the MCP token endpoint that skips client secret verification for client_secret_basic clients. Attackers holding an |
| CVE-2026-135686 | 7.4 | n/a | Trilium through 0.107.0 contains an sql injection vulnerability in updateNormalEntity() that allows malicious sync partners to inject SQL by supplying crafted entity names and column keys. Attackers c |
| CVE-2026-134850 | 7.3 | 0.5% | A security vulnerability has been detected in aceberg WatchYourLAN up to 2.1.4. Affected by this issue is the function getPortState of the file backend/internal/api/api-network.go of the component Web |
| CVE-2026-134891 | 7.3 | n/a | A weakness has been identified in osCommerce 4.14.63493. This affects the function actionGiftCard of the file lib/frontend/controllers/CatalogController.php of the component Virtual Gift Card Basket.  |
| CVE-2026-127224 | 7.2 | n/a | GFI HelpDesk before 4.99.13 contains an SQL injection vulnerability in the archiver export feature that allows authenticated attackers with administrator privileges to execute arbitrary SQL queries by |
| CVE-2026-135298 | 7.1 | n/a | Convoy before 26.6.0 contains an insecure direct object reference vulnerability in /portal-api single-resource handlers that allows portal link token holders to access other tenants' resources by ID.  |
| CVE-2026-49965 | 7.1 | n/a | DreameHome cloud API before 2026-11-19 contained an insecure direct object reference vulnerability in the POST /smart-app/meari-cloud/bindDevice endpoint that allows authenticated attackers to reassig |
| CVE-2026-120777 | 7.1 | n/a | Incorrect authorization in Azure Managed Service Identity allows an authorized attacker to elevate privileges over a network. |
| CVE-2026-135706 | 7.0 | n/a | FFmpeg before 9.1 contains a heap buffer overflow vulnerability in modplug_read_header() in libavformat/libmodplug.c that allocates the buffer using max_size instead of sz. When max_size is set to 0,  |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-g6rg-px7f-4p6c | CVE-2026-96438 | medium | Unrestricted upload of file with dangerous type vulnerability in ITG Bilgisayar Teknolojileri... |
| GHSA-jccx-w4q3-2824 | CVE-2026-97198 | medium | Authorization bypass through User-Controlled key vulnerability in ITG Bilgisayar Teknolojileri... |
| GHSA-jp2q-3hxx-j4hr | CVE-2026-62269 | medium | Improper Encoding or Escaping of Output vulnerability in ex_aws (S3 request URL construction).
... |
| GHSA-ffjf-q82h-mx96 | CVE-2026-94365 | medium | Improper neutralization of input during web page generation ('cross-site scripting')... |
| GHSA-8fhr-rcgh-cpgh | CVE-2026-59698 | high | Relative path traversal in ex_aws allows an attacker who controls an S3 object key to escape the... |
| GHSA-vx85-vcmw-ph24 | CVE-2026-59697 | high | Server-Side Request Forgery (SSRF) vulnerability in ex_aws (instance metadata token provider).
... |
| GHSA-p7pj-vwgw-498c | CVE-2026-84785 | unknown | Issue summary: A QUIC peer that sends many small out-of-order STREAM fragments
while withholding... |
| GHSA-mw39-5h46-r93w | CVE-2026-128420 | low | A heap buffer overflow issue exists in the rms_mqtt daemon on Teltonika Networks devices. An... |
| GHSA-26q3-233j-qq25 | CVE-2026-13137 | high | A stack-based buffer overflow vulnerability exists in multiple parsers of RTU500 components of... |
| GHSA-cfvh-qwg2-xc3f | CVE-2026-126605 | medium | Authentication bypass in the Face ID app lock in Proton Pass for iOS before v. 1.21.1 allows an... |
| GHSA-wcm2-c3vj-8vxc | CVE-2026-135747 | unknown | Apache IoTDB MCP Server logs the IoTDB connection password in plaintext during startup, allowing... |
| GHSA-f7xc-rwc7-44v4 | CVE-2026-134858 | unknown | In Apache Pinot 0.7.1 through 1.5.1, a caller who can submit URI ingestion jobs can select local... |
| GHSA-43g7-wq45-pprh | CVE-2026-135660 | unknown | Improper Neutralization of Script-Related HTML Tags in a Web Page (Basic XSS) vulnerability in... |
| GHSA-fc7j-qcmq-x5qj | CVE-2026-125735 | high | SQL injection in the CabinPaq manual code entry module, versions v.1.2.94 and v.1.2.136. The... |
| GHSA-8w8v-44rf-m9p6 | CVE-2026-119582 | critical | Improper neutralization of special elements used in an SQL command ('SQL injection')... |
| GHSA-6m72-2j2p-pv4f | CVE-2026-121375 | high | Reflected cross-site scripting in the versioned REST API documentation page in Checkmk versions 2... |
| GHSA-22hg-j3v4-93jj | CVE-2026-119543 | high | Authorization bypass through User-Controlled key vulnerability in ITG Bilgisayar Teknoloji Grubu... |
| GHSA-459r-ccpp-765c | CVE-2026-111600 | unknown | UNIX symbolic link (symlink) following vulnerability in Apache BuildStream allows source plugins... |
| GHSA-2rfc-q4p8-2qxf | CVE-2026-117593 | critical | Weak Password Recovery Mechanism for Forgotten Password vulnerability in ITG Bilgisayar Teknoloji... |
| GHSA-hrff-34ph-wwp7 | CVE-2026-10765 | high | RTU500 contains a denial-of-service vulnerability in its IEC 61850 MMS server implementation. A... |
| GHSA-c4qg-wwp4-x4w8 | CVE-2026-96354 | unknown | Missing Authorization vulnerability in the public project REST API of Apache Texera (incubating).... |
| GHSA-77v4-pqm9-52r4 | CVE-2026-103756 | medium | Improper neutralization of input during web page generation ('cross-site scripting')... |
| GHSA-29m3-5v5v-q8qg | CVE-2026-103333 | high | Improper input validation in some SPARQL functions available in Apache Jena ARQ allows users to... |
| GHSA-cfp8-gm59-83cv | CVE-2026-97893 | medium | A Denial of Service (DoS) vulnerability exists in the ARQ SPARQL Query Optimiser in Apache Jena... |
| GHSA-q5x5-6357-rv4c | CVE-2026-96353 | unknown | Missing Authorization vulnerability in the project REST API of Apache Texera (incubating).



The... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Coneco Engineers & Scientists | Aoqin | US | 2026-11-24T07:50:30.375719+00:00 |
| IIM Raipur perimeter (Indian Institute of Management) | PixelLeaks | IN | 2026-11-24T06:59:26.632053+00:00 |
| NKN Delhi PoP (National Knowledge Network / NIC / MeitY, India) | PixelLeaks | IN | 2026-11-24T06:59:06.825766+00:00 |
| kneron.com | safepay | US | 2026-11-24T06:24:21.274984+00:00 |
| A government website for a county in a U.S. state | SoulGroup | US | 2026-11-24T02:56:45.833076+00:00 |
| VHV Company | anubis | DE | 2026-11-24T00:03:34.846680+00:00 |
| Home Instead | anubis | US | 2026-11-24T00:02:29.052243+00:00 |
| Mayerhofer Hoch-, Tief- und Ingenieurbau GmbH | qilin | DE | 2026-11-24T08:39:50.868094+00:00 |
| Nationwide IT Services, Inc. | rhysida | US | 2026-11-23T23:23:41.837057+00:00 |
| Yahoo | medusalocker | BR | 2026-11-23T23:21:20.950015+00:00 |
| Golden State Baptist College | Dark Project | US | 2026-11-23T19:51:14.107311+00:00 |
| Lowell Foods | incransom | US | 2026-11-23T16:11:48.234686+00:00 |
| Demas Schaefer Family Lawyers | rhysida |  | 2026-11-23T12:24:58.573914+00:00 |
| traconelectric.com | safepay | RO | 2026-11-23T11:23:40.395942+00:00 |
| sinagpawnshop.com | safepay | PH | 2026-11-23T11:23:07.278813+00:00 |
| bienefeld-gmbh.de | safepay | DE | 2026-11-23T11:22:33.909394+00:00 |
| elsanj.org | safepay | US | 2026-11-23T11:22:01.345875+00:00 |
| jcatkinson.co.uk | safepay | GB | 2026-11-23T11:21:27.398419+00:00 |
| hlbtropical.com | safepay | DE | 2026-11-23T11:20:54.145396+00:00 |
| spiegelberg.com | safepay | DE | 2026-11-23T11:20:20.582387+00:00 |

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
| 18.218.118.203 | 8 |
| 35.206.151.191 | 8 |
| 62.60.130.148 | 8 |
| 64.62.197.48 | 8 |
| 64.62.197.122 | 8 |
| 65.49.20.66 | 8 |
| 66.132.186.167 | 8 |
| 77.239.124.181 | 8 |
| 77.239.124.252 | 8 |
| 93.174.95.106 | 8 |
| 102.220.45.186 | 8 |
| 102.220.161.171 | 8 |
| 119.204.122.94 | 8 |
| 125.130.102.172 | 8 |
| 167.94.146.48 | 8 |
| 167.94.146.53 | 8 |
| 193.24.211.206 | 8 |
| 3.129.187.38 | 7 |
| 27.102.116.43 | 7 |
| 35.206.163.19 | 7 |

### OpenPhish (live phishing URLs)
- https://www.belepes-telekom-hu.vh22325.vh.net.pl/
- https://belepes-telekom-hu.vh22325.vh.net.pl/
- http://id2140.business-support-partner.com/
- http://dan-san2006.github.io/Netflix_gt
- https://ephemeral-squirrel-f84ee4.netlify.app/
- https://www.instagramloginpassword.blogspot.com/
- http://id2138.business-support-partner.com/
- http://hotelbs.websiteseguro.com/css/outl0ok/true/login/aces.php
- https://sso-auth.com/E.bGYjM2SvWMNs4g?/facebook_secure_account?id=759347502378427672987349826578129038123807394
- https://www.madethis.website/s/35ejwgy8/#tanum@f96bf19569d402cd21ad3f3e989b16c183b7.com
- http://raeward-mymidasbuy.de5.net/
- http://ifps62-458rn4tdu-arcadawebapps2.vercel.app/
- http://netflix-clonepractice.vercel.app/
- http://c1t77f-kehr8a7q8-arcadawebapps2.vercel.app/
- https://www.notflix-azure.vercel.app/
- http://ifps62-ag1rcrr19-arcadawebapps2.vercel.app/
- http://netflix-clone-update-brown.vercel.app/
- https://www.b35r.com/fish/61
- http://squeeth-uniswap.netlify.app/
- http://facebook-ic.blogspot.com/?m=1

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://scanned.page/4hrvN4 |
| N/A | https://www.brt-ra.eu.cc/it/ |
| N/A | https://www.brt-ws.eu.cc/it/ |
| N/A | https://www.brt-wa.eu.cc/it/ |
| N/A | https://www.brt-wx.eu.cc/it/ |
| N/A | https://www.brt-ta.eu.cc/it/ |
| N/A | https://www.brt-wz.eu.cc/it/ |
| N/A | https://www.brt-va.eu.cc/it/ |
| N/A | https://www.brt-wt.eu.cc/it/ |
| N/A | https://qlw.dnx.mybluehost.me/Rinova/badova/ |
| N/A | https://www.brt-wv.eu.cc/it/ |
| N/A | http://allegrolokalnie.pl-id-offer-3983-742-5712.sbs/playstation-5-ps5-1tb-z-2-kontro/ly9qr9t |
| N/A | https://www.brt-wr.eu.cc/it/ |
| N/A | https://www.brt-we.eu.cc/it/ |
| N/A | https://www.brt-wc.eu.cc/it/ |
| N/A | https://particuliers.sg.fr.8574839.com/f57c3778 |
| 8.1 | https://group-brt.top/it/ |
| 8.3 | https://microsoftsignin.azurewebsites.net/ |
| 7.2 | https://elster-datenerneuerung.cc/ |
| 8.2 | https://hameem.net/adobe.pw/index.html |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| 853c7cbd33c41f2a4651942d34a733403c89910b | FunStealer C&C |
| cfaeecab0d464737b0c8132f0302b4a2b5bbd149 | FunStealer C&C |
| 4da3273d01b7073f7218b69acadf32b0c57f35de | FunStealer C&C |
| 5d534c73e1fcbaad51fe510e822619d91e173e52 | FunStealer C&C |
| 85fcf32f16ea72d1c6327ab295a9bcbbfd08a644 | DCRat C&C |
| a51757af2edfa00116ada88c46d530474b3eea07 | Malware C&C |
| ccc7b03dc0841123fac4c5a518b74953711d8362 | PureLogsStealer C&C |
| c350ba2b9f3aeeb536476c111de25f3ccb5bb84e | PureLogsStealer C&C |
| 4d53fbd3a15b5220d7b092c0738564e7e6b8d00a | Malware C&C |
| b26fb89c001f599795543e012bb7c9314f2223ae | PureLogsStealer C&C |
| 2e6c34df036674422a595d391f1baedb3fb39027 | OffLoader C&C |
| bf3205fa0b555799dac3790a69a124777b6ef00d | Vidar C&C |
| c3cff7f03d5d7568c2d309491b88e1e8cb357fa6 | Vidar C&C |
| 48b0dec6d012b2281e6a23ea563f86e3bfe9f7ac | RatonRAT C&C |
| 5dbf16080b42e16892a7e78809ee51ce2c488570 | Vidar C&C |
| 0facb1061f06b727fa4ae203c7995b491c5b9720 | PureLogsStealer C&C |
| 42192f0ce811787f0916f65c01d526af6bf5ae76 | PureLogsStealer C&C |
| eba4b82e9109fe20877835378d6f4c3613a0d72e | PureRAT C&C |
| 2ff2de39746ccae87d18ddfc5a2131a079ec1a91 | Vidar C&C |
| 035fe40eafae762af44451fc432afb6ddc816b87 | Vidar C&C |

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
- 1.117.72.220
- 1.12.55.80
- 1.13.79.149
- 1.14.140.218
- 1.14.64.225
- 1.161.133.251
- 1.162.242.67
- 1.183.197.192
- 1.183.25.86
- 1.192.216.175
- 1.194.211.36
- 1.203.149.250
- 1.212.225.99
- 1.214.204.138
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.222.80.212
- 1.234.27.159

### CINS Army (poorly-rated IPs)
- 1.14.3.170
- 1.170.200.20
- 1.170.243.169
- 1.181.101.207
- 1.189.41.213
- 1.193.100.138
- 1.20.151.114
- 1.208.108.242
- 1.213.214.233
- 1.24.16.100
- 1.24.16.109
- 1.24.16.110
- 1.24.16.112
- 1.24.16.113
- 1.24.16.114
- 1.24.16.115
- 1.24.16.116
- 1.24.16.120
- 1.24.16.125
- 1.24.16.142

## News (last ~36h, across outlets)
### The Hacker News
- [Hackers Found a Way Around GitHub SHA Pinning. This Webinar Explains How to Close the Gap](https://thehackernews.com/2026/11/hackers-found-way-around-github-sha.html)
- [Google Researcher Shows How a Single Bit Change in .NET Files Bypassed Windows Code Integrity](https://thehackernews.com/2026/11/google-researcher-shows-how-single-bit.html)
- [2027 SOC Budget Reset: 5 Priorities to Cut Costs and Reduce Cyber Risk](https://thehackernews.com/2026/11/2027-soc-budget-reset-5-priorities-to.html)
- [Microsoft Fixes Azure API Management Classic Flaw as Actor Targets Customer Secrets](https://thehackernews.com/2026/11/microsoft-fixes-azure-api-management.html)
- [WHMCS SQL Injection Could Expose Customer Data and Admin Password Hashes without Login](https://thehackernews.com/2026/11/whmcs-sql-injection-flaw-could-expose.html)
- [OpenAI and Cisco Unveil AI-Assisted Linux Security Tool to Block Exploits Before Patching](https://thehackernews.com/2026/11/openai-and-cisco-unveil-ai-assisted.html)
- [Hackers Exploit N-able MailAssure Flaw While AI Agents Exploit MONAI Label Zero-Day](https://thehackernews.com/2026/11/hackers-exploit-n-able-mailassure-flaw.html)
- [Webworm Suspected of Modifying SoftEther VPN to Evade Detection and Hide Remote Access](https://thehackernews.com/2026/11/webworm-suspected-of-modifying.html)
- [⚡ Weekly Recap: VMware 0-Day, Java4Shell, NGINX2Root, Ruby2Shell, and a Whole Lot of Shell Trouble](https://thehackernews.com/2026/11/weekly-recap-vmware-0-day-java4shell.html)
- [Critical binary-parser Flaw Enables JavaScript Injection via Malicious Parser Definitions](https://thehackernews.com/2026/11/critical-binary-parser-flaw-enables.html)
- [Hackers Exploit Critical ScreenConnect Flaw to Hijack MSP Technician PCs Without Warning](https://thehackernews.com/2026/11/hackers-exploit-critical-screenconnect.html)
- [N-able Discloses Critical Mail Assure Vulnerability Found During Breach Investigation](https://thehackernews.com/2026/11/n-able-discloses-critical-mail-assure.html)
- [Hackers Exploit Critical ASP.NET Anti-CSRF Library Flaw Allowing Unauthenticated RCE](https://thehackernews.com/2026/11/hackers-exploit-critical-aspnet-anti.html)
- [Hackers Exploited GL.iNet Cloud Flaw to Install Malware on Routers and KVM Devices](https://thehackernews.com/2026/11/hackers-exploited-glinet-cloud-flaw-to.html)
- [AI-Assisted Cyber Attacks Trigger Unauthorized Payments at Indian Banks and Fintech Firms](https://thehackernews.com/2026/11/ai-assisted-cyberattacks-trigger.html)

### BleepingComputer
- [South Korea’s power giant KEPCO confirms data breach impacting 1.5 million](https://www.bleepingcomputer.com/news/security/south-koreas-power-giant-kepco-confirms-data-breach-impacting-15-million/)
- [OpenRouter drops AI providers over leaked prompts and secrets](https://www.bleepingcomputer.com/news/security/openrouter-drops-ai-providers-over-leaked-prompts-and-secrets/)
- [Microsoft Azure flaw exploited to steal customers' API credentials](https://www.bleepingcomputer.com/news/security/microsoft-azure-flaw-exploited-to-steal-customers-api-credentials/)
- [Spanish LaLiga confirms hackers stole soccer fans’ personal data](https://www.bleepingcomputer.com/news/security/spanish-laliga-confirms-hackers-stole-soccer-fans-personal-data/)
- [GlobeTopper loses $2.5 million after hackers steal $70k in gift cards](https://www.bleepingcomputer.com/news/security/globetopper-loses-25-million-after-hackers-steal-70k-in-gift-cards/)
- [AI Agents Are Creating a Shared Responsibility Gap](https://www.bleepingcomputer.com/news/security/ai-agents-are-creating-a-shared-responsibility-gap/)
- [Microsoft testing fix for Windows 11 Bluetooth audio quality drops](https://www.bleepingcomputer.com/news/microsoft/microsoft-testing-fix-for-windows-11-bluetooth-audio-quality-drops/)
- [Call center operator gets 8 years for helping scam 30,000 Americans](https://www.bleepingcomputer.com/news/security/call-center-operator-gets-8-years-for-helping-scam-30-000-americans/)
- [Microsoft confirms Windows printing issues affecting Forcepoint users](https://www.bleepingcomputer.com/news/microsoft/microsoft-confirms-printing-issues-after-kb5132043-windows-hotpatch/)
- [CISA flags critical Cisco RCE flaw as actively exploited in attacks](https://www.bleepingcomputer.com/news/security/cisa-flags-critical-cisco-expressway-rce-flaw-as-actively-exploited/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [Industrial Serial Gateways Broadcast That They're Insecure](https://www.darkreading.com/ics-ot-security/industrial-serial-gateways-broadcast-insecure)
- [CrowdStrike Makes AI Security Push With Blockbuster Zscaler Deal](https://www.darkreading.com/endpoint-security/crowdstrike-ai-security-push-zscaler-deal)
- [US Cyber Director Pick Signals Shift Toward Expertise](https://www.darkreading.com/cybersecurity-operations/us-cyber-director-pick-signals-shift-toward-expertise)
- [Behind the Alias: How One Researcher Unmasked a Decade of Ransomware Actors](https://www.darkreading.com/cybersecurity-operations/alias-researcher-unmasked-ransomware-actors)
- [AI Agents Zip From Flaw Discovery to Root Access in 11 Minutes](https://www.darkreading.com/cyberattacks-data-breaches/ai-agents-flaw-discovery-root-access-11-minutes)

### SecurityWeek
- [OpenAI, Cisco Unveil Open Source Tool to Shield Unpatched Linux Systems](https://www.securityweek.com/openai-cisco-unveil-open-source-tool-to-shield-unpatched-linux-systems/)
- [1.5 Million Impacted by Data Breach at South Korean Electric Company KEPCO](https://www.securityweek.com/1-5-million-impacted-by-data-breach-at-south-korean-electric-company-kepco/)
- [Elecbrakes Bluetooth Vulnerabilities Expose Trailers to Forced Braking](https://www.securityweek.com/elecbrakes-bluetooth-vulnerabilities-expose-trailers-to-forced-braking/)
- [Peninsula Energy Halts Trading After Cyber Incident Hits US Uranium Mine](https://www.securityweek.com/peninsula-energy-halts-trading-after-cyber-incident-hits-us-uranium-mine/)
- [Azure Flaw Exploited to Target Secrets at Norwegian Energy Firms](https://www.securityweek.com/azure-flaw-exploited-to-target-secrets-at-norwegian-energy-firms/)
- [N-able Patches Critical Flaw Discovered After Mail Assure Cyberattack](https://www.securityweek.com/n-able-patches-critical-flaw-disclosed-after-mail-assure-cyberattack/)
- [phpAfterShell Vulnerability Revives PHP2Shell’s Attack Path](https://www.securityweek.com/phpaftershell-vulnerability-revives-php2shells-attack-path/)
- [GL.iNet Routers, KVMs Compromised via Remote Management Service Flaw](https://www.securityweek.com/gl-inet-routers-kvms-compromised-via-remote-management-service-flaw/)
- [AI Inference Providers Failed to Detect Hacking and Prompt Theft, Says Dragos](https://www.securityweek.com/ai-inference-providers-failed-to-detect-hacking-and-prompt-theft-says-dragos/)
- [BadBox 3.0 Ad Fraud Operation Generating 40 Billion Daily Bid Requests Disrupted](https://www.securityweek.com/badbox-3-0-ad-fraud-operation-generating-40-billion-daily-bid-requests-disrupted/)

### The Record
- [McDonald’s Japan discloses breach exposing customer purchase and location data](https://therecord.media/japan-mcdonalds-cyberattack-breach)
- [LaLiga hacked: Spain’s top football league confirms theft of fans’ personal data](https://therecord.media/laliga-hacked-spain-top-professional-league-confirms-cyber-incident)
- [‘Grand Theft Auto VI’ hacker sentenced to seven years, released the same day](https://therecord.media/gta-vi-hacker-arion-kurtaj-released-on-license)
- [Hackers breach Austrian Foreign Ministry website, access diplomats' contact details](https://therecord.media/austrian-foreign-ministry-says-website-hacked)
- [Signal blocks screenshots by Apple, Google operating systems to protect data from AI agents](https://therecord.media/signal-no-screenshots-by-apple-google-operating-systems)

### Infosecurity Magazine
- [Chinese Open-Weight AI Models Top Closed Ones at Vulnerability Discovery in New Test](https://www.infosecurity-magazine.com/news/chinese-ai-models-top/)
- [OpenAI and Cisco Release Open-Source Tool to Shield Unpatched Linux Systems](https://www.infosecurity-magazine.com/news/openai-cisco-shirudo-linux-shields/)
- [LaLiga Says Football Fans’ Personal Data Stolen](https://www.infosecurity-magazine.com/news/la-liga-says-football-fans/)
- [Researchers Find a New AI Attack Path: Agent Instructions](https://www.infosecurity-magazine.com/news/researchers-new-ai-attack-path/)
- [Bots Hide Behind AI Agent Names to Hunt for Secrets](https://www.infosecurity-magazine.com/news/secrethunting-trafficai-agent/)
- [CrowdStrike to Acquire Zscaler in Record $44 Billion Deal](https://www.infosecurity-magazine.com/news/crowdstrike-to-acquire-zscaler/)
- [Signal Moves to Block  iOS and Android AI Agents From Reading Chats](https://www.infosecurity-magazine.com/news/signal-blocks-ai-agents-reading/)
- [US Lawmakers Propose CISA Board to Review Major Cyber Incidents](https://www.infosecurity-magazine.com/news/us-lawmakers-bill-cisa-review/)
- [Cleverbridge Confirms Customers’ Payment Card Data Breached](https://www.infosecurity-magazine.com/news/cleverbridge-payment-card-breached/)
- [Critical Cisco Expressway Flaw Exploited in Attacks](https://www.infosecurity-magazine.com/news/critical-cisco-expressway-flaw/)
- [Badbox Returns to Spread Ad Fraud and Proxyjacking Payloads](https://www.infosecurity-magazine.com/news/badbox-spread-ad-fraud/)

### CyberScoop
- [Tomorrow’s quantum threat is today’s open door](https://cyberscoop.com/ot-security-post-quantum-cryptography-op-ed/)
- [Virginia, Oregon hit SpaceX with fresh lawsuits over Grok-created CSAM](https://cyberscoop.com/virginia-oregon-sue-spacex-grok-deepfakes/)
- [Indicted Kosovo credit card theft suspect extradited to US](https://cyberscoop.com/hektor-avdyli-kosovo-credit-card-fraud-extradition/)
- [Kirsten Davies to become national cyber director nominee, Jay Clayton takes acting director job](https://cyberscoop.com/kirsten-davies-jay-clayton-national-cyber-director/)
- [CrowdStrike agrees to buy Zscaler for $43.9 billion in network security expansion](https://cyberscoop.com/crowdstrike-to-acquire-zscaler/)
- [I’ve never hunted for a software vulnerability before. AI helped me find one in six hours.](https://cyberscoop.com/finding-software-vulnerability-with-ai-wordpress-patchstack/)
- [WPIDE ≤ 3.6.4 — CSRF Nonce Bypass Leading to Unauthenticated RCE (CVE-2026-124251)](https://cyberscoop.com/wpide-csrf-vulnerability-cve-2026-124251/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [Scanning from Subnet 109.160.32.0/24, (Mon, Nov 23rd)](https://isc.sans.edu/diary/rss/33550)
- [ISC Stormcast For Tuesday, November 24th, 2026 https://isc.sans.edu/podcastdetail/10192, (Tue, Nov 24th)](https://isc.sans.edu/diary/rss/33552)
- [ISC Stormcast For Monday, November 23rd, 2026 https://isc.sans.edu/podcastdetail/10190, (Mon, Nov 23rd)](https://isc.sans.edu/diary/rss/33548)

### Securelist (Kaspersky)
- [Black Friday, red flags: too-good-to-be-true deals hiding real threats](https://securelist.com/black-friday-threat-report-2026/122061/)

### CrowdStrike Blog
- [Java4Shell (CVE-2026-114938): CrowdStrike Detects Exposure and Post-Exploitation Activity](https://www.crowdstrike.com/en-us/blog/crowdstrike-helps-protect-against-java4shell-cve-2026-114938/)
- [NGINX2Root: Identify and Protect with the CrowdStrike Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-helps-protect-against-nginx2root-cve-2026-123007/)
- [CrowdStrike Is Building the Engine of the Agentic SOC with Falcon Next-Gen SIEM](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-gartner-mq-siem/)
- [CrowdStrike Brings the Human Advantage to AI Detection and Response](https://www.crowdstrike.com/en-us/blog/crowdstrike-brings-human-advantage-aidr/)
- [Hidden in the Weights: Supply Chain Risk from Backdoored LoRA Models](https://www.crowdstrike.com/en-us/blog/supply-chain-risk-from-backdoored-lora-models/)
- [Inside Falcon AI Gateway: One Control Point for AI Traffic](https://www.crowdstrike.com/en-us/blog/falcon-ai-gateway-one-control-point-for-ai-traffic/)
- [CrowdStrike Named a Leader in the 2026 IDC MarketScape for Worldwide Augmented Identity Security Solutions](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-idc-marketscape-worldwide-augmented-identity-security-solutions/)
- [November 2026 Patch Tuesday: 1,252 CVEs Include One Zero-Day and 68 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-november-2026/)
- [How Adversaries Are Turning the Vulnerability Ecosystem Against Defenders](https://www.crowdstrike.com/en-us/blog/adversaries-turn-vulnerability-ecosystem-against-defenders/)
- [CrowdStrike Extends the Agentic SOC to Detect and Stop Agent Insider Threats](https://www.crowdstrike.com/en-us/blog/crowdstrike-detects-and-stops-agent-insider-threats/)

### FortiGuard Threat Signal
_No new items / feed unavailable this run._

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal