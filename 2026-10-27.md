# Winjit Daily TI Digest — 2026-10-27

_Auto-generated. Window: last ~24h. Fetched at 2026-10-27T08:47:28.968317+00:00Z_

**At a glance:** 2 new KEV · 40 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-109618 | PHP Group | PHP | PHP Memory Corruption Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-109619 | PHP Group | PHP | PHP Stale Internal Request-State Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-116508 | 10.0 | n/a | A security flaw has been discovered in TOTOLINK A950RG 4.1.2cu.5268_B20221104. Affected by this issue is the function sub_402340 of the file infostat.cgi of the component Device-Information CGI. Perfo |
| CVE-2026-116231 | 9.9 | 0.4% | A security flaw has been discovered in Oray Pugongying X5 Pro 7.6.1. The impacted element is an unknown function of the component Ser2net. Performing a manipulation of the argument regmsg results in c |
| CVE-2026-116504 | 9.9 | n/a | A vulnerability has been found in TOTOLINK A950RG 4.1.2cu.5268_B20221104. This affects the function setCloudUpgradeFW of the file lib/cste_modules/upgrade.so of the component Cloud Upgrade. The manipu |
| CVE-2026-116506 | 9.9 | n/a | A vulnerability was determined in TOTOLINK A950RG 4.1.2cu.5268_B20221104. Affected is the function apmib_set of the file firewall.so. This manipulation causes command injection. The attack may be init |
| CVE-2026-116485 | 9.8 | n/a | danmu_api before 1.21.7 contains an authentication bypass vulnerability that allows unauthenticated attackers to modify server environment configuration when the default TOKEN is used and ADMIN_TOKEN  |
| CVE-2026-112346 | 9.8 | n/a | OpenHands Software Agent SDK before 1.52.0 contains an unauthenticated remote code execution vulnerability where the DockerWorkspace and Apptainer workspace launchers bind the sandbox agent server to  |
| CVE-2026-116233 | 9.1 | 0.5% | A security vulnerability has been detected in Oray Pugongying X5 Pro 7.6.1. This impacts an unknown function of the component Dnsmasq. The manipulation of the argument rent_time leads to crlf injectio |
| CVE-2026-116234 | 9.1 | 0.5% | A vulnerability was detected in Oray Pugongying X5 Pro 7.6.1. Affected is an unknown function of the file /etc/ipsec.conf of the component IPsec Policy Handler. The manipulation of the argument secpro |
| CVE-2026-116214 | 9.1 | n/a | MacCMS v10 before 2026.1000.4054 contains an authentication bypass vulnerability that allows unauthenticated attackers to reset any member's password because check_msg() never compares msg_to. Attacke |
| CVE-2026-116505 | 9.1 | n/a | A vulnerability was found in TOTOLINK A950RG 4.1.2cu.5268_B20221104. This impacts the function getDeviceInfo of the file /var/lib/misc/udhcpd.leases of the component device-information Handler. The ma |
| CVE-2026-116738 | 8.8 | n/a | VMime through 0.9.2 contains an integer underflow in the uuEncoder::decode function that allows remote attackers to trigger a stack-based buffer overflow via crafted uuencoded MIME parts. Attackers ca |
| CVE-2026-116748 | 8.8 | n/a | Transmission 4.0.0 before 4.1.3 contains a permissive CORS vulnerability in handle_request() in rpc-server.cc that exposes the X-Transmission-Session-Id anti-CSRF token to any web origin. Malicious we |
| CVE-2026-116811 | 8.8 | n/a | OpenPanel before 3.0.0 contains a sandbox escape vulnerability in the js-runtime validator that allows a project member to bypass the AST allowlist by aliasing the Function constructor. Attackers with |
| CVE-2026-116843 | 8.8 | n/a | Mistral Vibe before 3.0.3 contains a remote code execution vulnerability that allows attackers to run commands by defining git filter drivers in an untrusted repository's .git/config. When started wit |
| CVE-2026-75891 | 8.8 | n/a | The Kirki plugin for WordPress is vulnerable to Privilege Escalation via PHP Object Injection in all versions up to, and including, 6.2.5 via deserialization of untrusted input through the 'get-single |
| CVE-2026-116819 | 8.5 | n/a | OpenPanel before 3.0.0 contains an information disclosure vulnerability that allows read-level project members to obtain plaintext integration secrets because the notification.rules query skips redact |
| CVE-2026-116237 | 8.4 | 0.7% | A vulnerability was found in Oray Pugongying X5 Pro 7.6.1. This affects an unknown part of the component Dnsmasq. Performing a manipulation results in crlf injection. Remote exploitation of the attack |
| CVE-2026-116116 | 8.2 | 0.1% | A vulnerability was detected in Yoosee GM8135S Camera 21.00.01.36. Affected is an unknown function of the component Secure Boot. Performing a manipulation results in improper verification of cryptogra |
| CVE-2026-116818 | 8.2 | n/a | OpenPanel before 3.0.0 contains an unauthenticated ClickHouse sql injection vulnerability that allows remote attackers to inject SQL through the projectId parameter of the /live/visitors/:projectId We |
| CVE-2024-58400 | 8.2 | n/a | llama.cpp before b3701 contains an out-of-bounds read vulnerability in llama_decode_internal and llama_encode_internal that allows remote unauthenticated attackers to read memory by supplying unvalida |
| CVE-2026-112343 | 8.1 | n/a | Syncplify Server! before 8.8.0 contains an access control bypass vulnerability that allows authenticated SFTP users to evade per-path permission overrides by exploiting case-insensitive filesystem pat |
| CVE-2026-116747 | 8.1 | n/a | Kener 3.0.0 before 4.1.10 contains an authentication bypass vulnerability that allows unauthenticated attackers to forge session tokens by using the hardcoded DUMMY_SECRET fallback key. When KENER_SEC |
| CVE-2026-116723 | 7.8 | n/a | FLTK through 1.4.5 contains a stack-based buffer overflow vulnerability in Fl_BMP_Image::load_bmp_() that allows attackers to corrupt stack memory by supplying an oversized BMP colors_used field. Atta |
| CVE-2026-116724 | 7.8 | n/a | FLTK through 1.4.5 contains an integer overflow vulnerability in Fl_BMP_Image::load_bmp_() that causes undersized pixel buffer allocation from file-supplied width and height. Attackers can supply a cr |
| CVE-2026-116816 | 7.8 | n/a | llama.cpp b5899 before b10261 contains a heap out-of-bounds write vulnerability in llm_tokenizer_plamo2::build that allows attackers to corrupt heap memory via crafted GGUF models. Attackers can suppl |
| CVE-2026-115717 | 7.7 | n/a | Frappe Builder versions before 1.36.1 contain a server-side request forgery vulnerability in the convert_to_webp API endpoint, which lacks the has_page_write access control applied to similar asset-in |
| CVE-2026-116218 | 7.6 | n/a | Dolibarr ERP CRM 19.0.0 before 23.0.4 contains an SQL injection vulnerability that allows authenticated API users to inject SQL via the type field of the third-party bankaccounts REST endpoint. Attack |
| CVE-2026-116489 | 7.5 | n/a | Timescale pgvectorscale before 0.9.1 contains a type confusion vulnerability that allows low-privileged database users to corrupt memory by shadowing pgvector's vector type or operators. Attackers wit |
| CVE-2026-116543 | 7.5 | n/a | Open5GS 1.3.0 through 2.8.0 contains a heap out-of-bounds write vulnerability in parse_multipart() that allows unauthenticated attackers to corrupt memory by supplying an empty multipart boundary. Att |
| CVE-2026-116110 | 7.3 | 0.4% | A vulnerability was found in GiantappMan LiveWallPaper 2.6.8.0 on Windows. This issue affects some unknown processing of the file /LiveWallpaper/UploadFile of the component SignalR Hub. Performing a m |
| CVE-2026-116112 | 7.3 | 0.3% | A vulnerability was identified in HashenUdara edoc-doctor-appointment-system up to cc258425b915d1af9e298777ccd26d160493e68d. The affected element is an unknown function of the file admin/add-new.php.  |
| CVE-2026-116257 | 7.3 | n/a | A vulnerability was determined in BillaBear up to 2025.01.03. Affected by this issue is the function processInstall of the file src/BillaBear/Controller/InstallController.php of the component Installa |
| CVE-2026-116260 | 7.3 | n/a | A weakness has been identified in libimobiledevice up to 1.4.0. This issue affects the function service_receive of the file src/afc.c of the component AFC Service. Executing a manipulation can lead to |
| CVE-2014-125135 | 7.3 | n/a | A security vulnerability has been detected in OctoPrint 1.0.0/1.1.0. Affected is an unknown function of the component Flask Secret Key Handler. Such manipulation leads to use of hard-coded cryptograph |
| CVE-2026-116620 | 7.3 | n/a | A security vulnerability has been detected in Tencent RapidJSON up to 1.1.0. This issue affects the function GenericStringStream<UTF8<char>>::Take in the library include/rapidjson/stream.h of the comp |
| CVE-2026-116623 | 7.3 | n/a | A vulnerability was detected in code-projects Simple Content Management System 1.0. Impacted is an unknown function of the file /web/admin/welcome.php of the component Admin Interface. The manipulatio |
| CVE-2026-116236 | 7.2 | 0.4% | A vulnerability has been found in Oray Pugongying X5 Pro 7.6.1. Affected by this issue is the function plugin_init of the file /tmp/upload_files of the component PPPoE WAN Setting Handler. Such manipu |
| CVE-2026-116219 | 7.2 | n/a | Dolibarr ERP CRM before 24.0.0 contains an OS command injection vulnerability in htdocs/admin/tools/export.php that lets authenticated administrators bypass the restrict_os_commands allowlist. Attacke |
| CVE-2026-116808 | 7.2 | n/a | OpenPanel before 3.0.0 contains an sql injection vulnerability that allows authenticated users to read cross-tenant data by supplying a crafted property parameter to profile.values. Attackers can inje |
| CVE-2026-111820 | 7.2 | n/a | The Analytics Insights – Google Analytics Dashboard for WordPress plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the Page Title in all versions up to, and including, 6.3.12 due  |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-jg7j-q6m4-7gq5 | CVE-2026-117469 | medium | Psono Server (CE & EE) versions 1.0.0 through 7.2.3 did not enforce the direction of file... |
| GHSA-4hh2-mhpm-69h3 | CVE-2026-117472 | medium | Psono Server CE && EE versions 4.0.33 through 7.2.3 compared the request path for the bulk-secret... |
| GHSA-897w-6p63-7p9g | CVE-2026-117468 | medium | Psono Server versions 5.3.5 through 7.2.3 used a permission class that did not enforce token... |
| GHSA-f39h-p64c-xrvv | CVE-2026-103312 | unknown | The Payment Integration Wompi WordPress plugin through 4.0.1 does not verify the authenticity of... |
| GHSA-q3ph-3gv2-g5wq | CVE-2026-117471 | medium | Psono Server CE && EE versions 0.1.0 through 7.2.3 accepted a user-controlled host when... |
| GHSA-3gq2-hx4p-69qc | CVE-2026-117470 | medium | Psono Server CE & EE versions 3.1.0 through 7.2.3 did not consume a stored WebAuthn challenge... |
| GHSA-qxp3-7pvj-q7qx | CVE-2026-103332 | unknown | The Payex Payment Gateway for Woocommerce WordPress plugin through 1.2.10 does not properly... |
| GHSA-3jq2-63r2-vgw4 | CVE-2026-111820 | high | The Analytics Insights – Google Analytics Dashboard for WordPress plugin for WordPress is... |
| GHSA-4vq8-3jwp-cxgv | CVE-2026-116640 | low | A flaw has been found in Saruf-Ratul HR-Payroll-Management-System... |
| GHSA-r2vp-5h4m-7j3c | CVE-2026-88781 | medium | Untrusted Pointer Dereference in ASUS certain motherboards firmware allows a kernel-level... |
| GHSA-2r7q-339v-2m8g | CVE-2026-116639 | low | A vulnerability was detected in MD-MAFUJUL-HASAN Online-Payroll-Management-System up to... |
| GHSA-xwx6-2mm7-g8wj | CVE-2026-116843 | high | Mistral Vibe before 3.0.3 contains a remote code execution vulnerability that allows attackers to... |
| GHSA-j2x3-vcc8-r98q | CVE-2026-116844 | medium | Fclairamb ftpserverlib through 0.32.4 contains a cleartext transmission vulnerability because... |
| GHSA-g75x-vcw6-3m3f | CVE-2026-116842 | medium | DevilutionX 1.4.0 through 1.5.5 contains a heap buffer overflow vulnerability in the bundled... |
| GHSA-f5q2-p5c3-3xqr | CVE-2026-116605 | medium | A vulnerability was found in SourceCodester Online Food Ordering System 1.0. The impacted element... |
| GHSA-w426-2r79-q458 | CVE-2026-116623 | medium | A vulnerability was detected in code-projects Simple Content Management System 1.0. Impacted is... |
| GHSA-jjjq-27hc-2q7x | CVE-2026-116838 | high | A malicious actor who lures an authenticated user to a malicious page could exploit a Cross-Site... |
| GHSA-3jhp-qv93-3428 | CVE-2026-116829 | medium | llama.cpp b10398 before b11301 contains an integer overflow vulnerability in... |
| GHSA-rff6-86qf-mmc2 | CVE-2026-97028 | unknown | Rejected reason: Maintainers determined it is not a vulnerability. |
| GHSA-hqgg-6cxc-95g7 | CVE-2026-116839 | high | A malicious actor who lures an authenticated user to a malicious page could exploit a Cross-Site... |
| GHSA-52pf-v9gp-98qj | CVE-2026-116840 | medium | llama.cpp b5854 before b11275 contains an integer overflow vulnerability in gguf_init_from_reader... |
| GHSA-xfhf-c35f-773q | CVE-2026-116620 | medium | A security vulnerability has been detected in Tencent RapidJSON up to 1.1.0. This issue affects... |
| GHSA-98hf-f439-379p | CVE-2026-116608 | low | A security vulnerability has been detected in DAMO Academy VideoLLaMA2 up to 1.1. Affected by... |
| GHSA-5c39-2376-cxh9 | CVE-2026-116836 | high | A malicious actor with access to the adjacent network and under certain conditions could exploit... |
| GHSA-4qpr-vwfh-qwp4 | CVE-2025-71439 | medium | llama.cpp before b5649 contains a heap out-of-bounds read vulnerability in llama_vocab::impl:... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| DATEM, Inc. | crypto24 | PH | 2026-10-27T04:11:17.674706+00:00 |
| Burris & MacOmber | everest |  | 2026-10-27T04:33:27.978594+00:00 |
| Energy Storage Terminal in Singapore | everest | SG | 2026-10-27T04:32:51.124991+00:00 |
| Point Robotics | everest |  | 2026-10-27T04:32:17.013209+00:00 |
| Natuzzi | everest | IT | 2026-10-27T04:31:41.695092+00:00 |
| TECNA ICE | everest | IT | 2026-10-27T04:31:06.242991+00:00 |
| MediSolution | everest |  | 2026-10-27T04:30:31.961924+00:00 |
| SleepEx LabRetriever | everest |  | 2026-10-27T04:29:56.461196+00:00 |
| gamblinglore | Whitearmor |  | 2026-10-27T04:05:36.281691+00:00 |
| Verification | Whitearmor |  | 2026-10-27T03:07:40.796568+00:00 |
| zzq-test | ULose |  | 2026-10-27T01:08:42.042582+00:00 |
| probe-011637cabbf94076- | ULose |  | 2026-10-27T01:08:22.327260+00:00 |
| Morrison Cohen | SilentRansomGroup | US | 2026-10-26T23:07:56.396007+00:00 |
| MISC Group | rhysida | MY | 2026-10-26T20:27:18.651315+00:00 |
| Afflelou | emperador | FR | 2026-10-26T21:52:29.796720+00:00 |
| Ingelectus Innovative Electrical Solutions S.L. | N0n | ES | 2026-10-26T18:57:11.389460+00:00 |
| Beasley Allen Law Firm | Falcon | US | 2026-10-26T16:54:28.340940+00:00 |
| Gamdom | Whitearmor |  | 2026-10-26T18:00:10.433408+00:00 |
| Delta Electric Power Association | qilin | US | 2026-10-26T12:03:57.071068+00:00 |
| Bangor Wholesale Laminates | qilin | GB | 2026-10-26T12:03:03.384731+00:00 |

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
| 45.148.10.121 | 9 |
| 45.148.10.157 | 9 |
| 64.62.197.48 | 9 |
| 91.92.43.221 | 9 |
| 138.226.239.90 | 9 |
| 138.226.239.233 | 9 |
| 138.226.239.234 | 9 |
| 152.32.225.117 | 9 |
| 157.245.84.42 | 9 |
| 160.250.132.238 | 9 |
| 185.136.15.80 | 9 |
| 185.136.15.81 | 9 |
| 185.136.15.110 | 9 |
| 185.136.15.111 | 9 |
| 193.47.62.69 | 9 |
| 193.187.110.159 | 9 |
| 196.189.236.67 | 9 |
| 2.57.122.238 | 8 |
| 45.148.10.5 | 8 |
| 45.148.10.141 | 8 |

### OpenPhish (live phishing URLs)
- https://www.roblox.com.et/users/4243002378/profile
- http://bofa-login.vercel.app/
- https://chatgpt0005.eu.org/blog/discord-patch-notes-february-4-2026/
- https://chatgpt0005.eu.org/blog/save-and-display-your-faves-add-discord-shop-marvel-rivals-items-to-your-profiles-wishlist/
- https://chatgpt0005.eu.org/blog/discord-is-now-on-meta-quest-reach-out-to-your-servers-while-in-vr/
- https://chatgpt0005.eu.org/blog/discord-update-december-13-2023-changelog/
- https://chatgpt0005.eu.org/category/community/
- https://www.it-supportdesk.com/signin?t=eyJhbGciOiJIUzI1NiJ9.eyJ0cmFja2luZ190b2tlbiI6ImJhNDFiOWE1LTUxMDgtNDhhZC1hN2YzLTZhNjRkNTUxNDI4OCIsImNlbGwiOiJodHRwczovLzIxZzZqZnZoeTYuZXhlY3V0ZS1hcGkudXMtZWFzdC0yLmFtYXpvbmF3cy5jb20vcHJvZC9hcGkvcGhpc2hpbmdjYW1wYWlnbiIsImNhbXBhaWduX3Rva2VuIjoiNWZmNTE3ZTItNWI4NS00ZjU3LTk4ODYtY2UwMzAzZTBiNzlhIiwidGVzdF90b2tlbiI6ZmFsc2UsImV4dGVybmFsX3RyYWluaW5nIjpmYWxzZSwiZGlyZWN0X2RlbGl2ZXJ5Ijp0cnVlLCJpYXQiOjE3OTI5NDUzMjYsImlzcyI6Imh0dHBzOi8vYXBwLnBoaXNodGhyZWF0LmNvbSIsImV4cCI6MTgwMDcyMTMyNn0.ZjE0oQrgVuD_L_gTWb-i1UIT1dFmj2B1X3BuZ2dXeUw
- https://www.id-cms.work/verify/xug2eay6d3ompbaha
- https://www.id-cms.work/
- https://www.roblox.et/users/6765120257/profile
- https://comptecaweb-001-site1.ktempurl.com/Agris-Webconnexions/
- http://www.mlnk.vn/asuar/
- https://statelawfirm.weupdaa.workers.dev/
- https://1url.at/www/robloxuser-951099195-profile
- http://pub-cf8243e496b946db82fa4374d900d030.r2.dev/30064354gs4.html
- https://www.roblox.com.et/users/4486801085/profile
- https://1kak1anzas.pages.dev/
- https://amuento-3278--aumento35.replit.app/
- https://confrmpges-pgesacct.github.io/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://centraldoacoarclrmittonline.ferrosescritorioaeroaco.workers.dev/?gad_source=1 |
| N/A | https://away.vk.ru/away.php?rh=78de4361-86b3-4aa4-b738-79513f7e0c1d |
| N/A | https://trnsace.site/oferta/l/-251586969?id=9b8b772b-1f5a-4eb1-bdd5-9817be0566e3 |
| N/A | https://app.bonificacaocliente.info/ |
| N/A | https://suportenetgerentejuridico.digital/ |
| N/A | https://acesso.appgerentepj.digital/ |
| N/A | https://away.vk.ru/away.php?rh=3b004800-697b-4fd4-83f0-c10ff6529f4d |
| N/A | https://allegrolokalnie.pl-618402.sbs/ |
| N/A | https://atualizacaonetempresas.app/ |
| N/A | https://allegrolokalnie.pl-lokalna-ofeta9xv17yj75v0.shop/ |
| N/A | https://away.vk.ru/away.php?rh=12e8a246-16ae-43e9-97c9-6dbbbe576fd1 |
| N/A | https://away.vk.ru/away.php?rh=232b0841-7d07-4888-b005-9d4917507c44 |
| N/A | https://ersfilter-my.sharepoint.com/personal/nradonich_ersfilter_com/_layouts/15/doc.aspx?guestaccesstoken=t6T%2FHN1dKbYHlYX%2BeIMbaZufA43rrGZ6%2FaAAewNocDI%3D&docid=1_18168db23429e45f29fdf2e7be120efc4&wdFormId=%7BB9970F62-44C3-4D09-9929-6E1EB652DA57%7D&action=formsubmit&CID=f877e52e-d963-44e6-a5e3-58c108a8f195 |
| N/A | https://away.vk.ru/away.php?rh=f5015da1-4b8b-420c-a558-3a7295c3e5be |
| N/A | https://bradesco.pjatualizacaosegura.live/ |
| N/A | https://allegrolokalnie.pl-bnmj5.sbs/ |
| N/A | https://sesja-3p5h-pkobiznes.pl-firma.net/-/logowanie?sid=1370668d3415fe5851d0fb125b560707 |
| N/A | https://bradesco.validacaoempresas.pro/ |
| N/A | https://app.clienteonline.shop/ |
| N/A | https://allegro.pl-hdwnd72nxiw92nr9xg3.shop/ |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| e5eefcb70e310314c73361c957aa2a1f970fbd65 | PureRAT C&C |
| a54ad395d86f7e564d4c23c150ce28359538d64d | OffLoader C&C |
| 9aa781171a4918d3e4069dd810fb846797806db7 | PureLogsStealer C&C |
| ba95841b4146ce72ee532c53be1651bc97d73388 | OffLoader C&C |
| 109f3ba748ac0f3a080d01039cfd0de392b83b30 | PureRAT C&C |
| 4500afbacb26f57137b330589027e0560957267f | PureLogsStealer C&C |
| 4d319fb9760ff822c5079e3ddbda8304de89f565 | Vidar C&C |
| 4269a895d221ce05070c61672e42fc549739137e | Vidar C&C |
| 5570df9517e8673cf294c4ae0314ff1e95e10c7a | Vidar C&C |
| b59fc9b78f8adfb12404d606d32f189309dcffdb | Vidar C&C |
| 92ebef95bba7efc76f713e8b4aa8d40d45478645 | PureRAT C&C |
| 72551f187ace5de0909186afdfea0756e9e3cd6d | XoriumStealer C&C |
| bd8eb13b5f944ac4c4a03a22d8c1b574bd02ee4f | QuasarRAT C&C |
| a41e8528d9b464b9620f4cc5900c444f291366e7 | BridgeAgent C&C |
| e6500b535b03160f06f2ca5c663ae180275dbb3b | Vidar C&C |
| 52c7bf8fd5f6312e161c6fe20c68edfa90e137eb | Vidar C&C |
| 6f373dd650805f118832ae3c618d10f0402ea6fe | Vidar C&C |
| f6f18a9147a66682618c0255dd3d376ccbcfed94 | Vidar C&C |
| 882b92d7a268237df18813ca7349fd2092f47618 | DCRat C&C |
| 6d96859790e57d9a9d1acb20ff920a508eb96e1c | PureRAT C&C |

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
- 1.10.242.248
- 1.12.55.80
- 1.12.64.109
- 1.14.105.177
- 1.14.149.30
- 1.14.192.95
- 1.14.240.247
- 1.147.62.60
- 1.15.106.134
- 1.159.54.33
- 1.162.216.37
- 1.187.165.30
- 1.187.214.31
- 1.187.238.219
- 1.192.80.17
- 1.20.172.162
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.220.198.126

### CINS Army (poorly-rated IPs)
- 1.15.14.29
- 1.193.57.144
- 1.193.63.224
- 1.220.119.115
- 1.236.254.202
- 1.24.16.117
- 1.24.16.119
- 1.24.16.145
- 1.24.16.163
- 1.24.16.54
- 1.24.16.55
- 1.24.16.91
- 1.24.16.97
- 1.244.184.137
- 1.28.125.52
- 1.30.28.182
- 1.30.80.145
- 1.32.57.245
- 1.36.198.249
- 1.83.125.149

## News (last ~36h, across outlets)
### The Hacker News
- [Attackers Hijack Dahua IP Cameras in Ukraine Using P2P Access and Auth Weaknesses](https://thehackernews.com/2026/10/attackers-hijack-dahua-ip-cameras-in.html)
- [CISA Confirms Active Exploitation of Two PHP2Shell Flaws Enabling Remote Code Execution](https://thehackernews.com/2026/10/cisa-confirms-active-exploitation-of.html)
- [Hackers Infect 953 Online Stores With Scanner-Evading JavaScript, Mostly on Magento](https://thehackernews.com/2026/10/hackers-infect-953-online-stores-with.html)
- [PHP Issues Second Windows Security Update in Five Days to Fix Brotli Code Execution Flaw](https://thehackernews.com/2026/10/php-issues-second-windows-security.html)
- [Attackers Use Microsoft Teams IT Support Scams to Deploy Malware and Ransomware](https://thehackernews.com/2026/10/attackers-use-microsoft-teams-it.html)
- [⚡ Weekly Recap: This2Shell, That2Shell, Everything's an RCE? Rogue AI, Supply Chain Chaos and More](https://thehackernews.com/2026/10/weekly-recap-this2shell-that2shell.html)
- [Two Critical Wasmtime Flaws Could Let Malicious WebAssembly Modules Escape Sandboxes](https://thehackernews.com/2026/10/two-critical-wasmtime-flaws-could-let.html)
- [Between alerts: What Attackers Do in the Spaces Ordinary Detection Misses](https://thehackernews.com/2026/10/between-alerts-what-attackers-do-in.html)
- [uCreator Android Spyware Can Steal Telegram 2FA Passwords and Clone WeChat Accounts](https://thehackernews.com/2026/10/ucreator-android-spyware-can-steal.html)
- [Microsoft 365 Token-Replay Attacks Compromise 97 Accounts at 79 Organizations](https://thehackernews.com/2026/10/microsoft-365-token-replay-attacks.html)
- [Gheist Uses Stolen GitHub Tokens to Steal Private Repository Secrets via Actions Logs](https://thehackernews.com/2026/10/gheist-uses-stolen-github-tokens-to.html)
- [Malicious File in Downloads Folder Tries to Trick AI Coding Agent Into Installing Malware](https://thehackernews.com/2026/10/malicious-file-in-downloads-folder.html)

### BleepingComputer
- [CISA confirms PHP2Shell vulnerabilities now exploited in attacks](https://www.bleepingcomputer.com/news/security/cisa-confirms-php2shell-vulnerabilities-now-exploited-in-attacks/)
- [University of Copenhagen data breach exposes data of 525,000 people](https://www.bleepingcomputer.com/news/security/university-of-copenhagen-data-breach-exposes-data-of-525-000-people/)
- [Former pentester used ARTEX AI to steal 8.2 million data records](https://www.bleepingcomputer.com/news/security/former-pentester-used-artex-ai-to-steal-82-million-data-records/)
- [OpenAI launches GPT-6.1 Terra with 3x faster AI agents, 50% lower pricing](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-launches-gpt-61-terra-with-3x-faster-ai-agents-50-percent-lower-pricing/)
- [DreamHost forces password resets in ongoing "incident"](https://www.bleepingcomputer.com/news/security/dreamhost-forces-email-ftp-sftp-password-resets-in-ongoing-incident/)
- [Critical 'HTTP2Shell' Brotli vulnerability triggers emergency patches](https://www.bleepingcomputer.com/news/security/critical-http2shell-brotli-vulnerability-triggers-emergency-patches/)
- [Microsoft releases emergency .NET patches for critical Brotli flaw](https://www.bleepingcomputer.com/news/microsoft/microsoft-releases-emergency-net-patches-for-critical-brotli-flaw/)
- [When an AI Agent Is the Incident, the Identity Record Is the Evidence](https://www.bleepingcomputer.com/news/security/when-an-ai-agent-is-the-incident-the-identity-record-is-the-evidence/)
- [Chinese man extradited for role in $36 million cryptocurrency scam](https://www.bleepingcomputer.com/news/security/chinese-man-extradited-for-role-in-36-million-cryptocurrency-scam/)
- [Kali Linux 2026.3 released with 6 new tools, desktop updates](https://www.bleepingcomputer.com/news/linux/kali-linux-20263-released-with-6-new-tools-desktop-updates/)
- [PHP2Shell security flaws now sucessfully exploited in the wild](https://www.bleepingcomputer.com/news/security/php2shell-security-flaws-now-sucessfully-exploited-in-the-wild/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [So Many AI Security Benchmarks, But None Tell the Whole Story](https://www.darkreading.com/cybersecurity-analytics/benchmarking-security-of-ai-models-poses-challenges)
- [Risks &amp; Rewards: How AI Is Redefining the CISO's Role](https://www.darkreading.com/cybersecurity-careers/risks-rewards-ai-redefining-ciso-role)
- [In-the-Wild Attack Abuses AI Agents' Trust in Markdown](https://www.darkreading.com/application-security/in-the-wild-attack-ai-agents-trust-markdown)
- ['Gheist' Weaponizes GitHub Tokens to Steal Cloud Secrets](https://www.darkreading.com/cyberattacks-data-breaches/gheist-stolen-github-tokens-cloud-secrets)
- [10 Software Security Practices Built for the Next 250 Years](https://www.darkreading.com/cyberattacks-data-breaches/10-software-security-practices-built-250-years)

### SecurityWeek
- [Maritime Coalition Launches Free Vulnerability Database for Ship and Port Systems](https://www.securityweek.com/maritime-coalition-launches-free-vulnerability-database-for-ship-and-port-systems/)
- [Cybersecurity Issue Forces a Major New Mexico Hospital to Divert Patients and Close Clinics](https://www.securityweek.com/cybersecurity-issue-forces-a-major-new-mexico-hospital-to-divert-patients-and-close-clinics/)
- [Anthropic Files for Potentially the Biggest IPO Ever as CEO Warns of Risk to Humanity From AI](https://www.securityweek.com/anthropic-files-for-potentially-the-biggest-ipo-ever-as-ceo-warns-of-risk-to-humanity-from-ai/)
- [Industrial Vendors Check Products for PHP2Shell Vulnerabilities](https://www.securityweek.com/industrial-vendors-check-products-for-php2shell-vulnerabilities/)
- [Genesys Hack Exposes Customer Data From Internal Systems](https://www.securityweek.com/genesys-hack-exposes-customer-data-from-internal-systems/)
- [Stolen AI Reasoning Could Help China Build Cheaper Rivals](https://www.securityweek.com/stolen-ai-reasoning-could-help-china-build-cheaper-rivals/)
- [PHP2Shell Exploitation Moves From Probes to Working Shells](https://www.securityweek.com/php2shell-exploitation-moves-from-probes-to-working-shells/)
- [953 Online Stores Infected in Long-Lasting Malware Campaign](https://www.securityweek.com/953-online-stores-infected-in-long-lasting-malware-campaign/)
- [Dutch Police Arrest Two Over NFC Relay Attacks That Drained $400,000+ From Bank Accounts](https://www.securityweek.com/dutch-police-arrest-two-over-nfc-relay-attacks-that-drained-400000/)
- [Node2Shell: Brotli Flaw Triggers Patching Across Microsoft, Node.js, Python Packages](https://www.securityweek.com/node2shell-brotli-flaw-triggers-patching-across-microsoft-node-js-python-packages/)

### The Record
- [Texas sues OpenAI for deceiving consumers about safety, seeks sweeping reforms and fines](https://therecord.media/texas-sues-openai-deceiving-customers)
- [Serbian autocrat loses election following widespread reports of digital repression](https://therecord.media/serbia-election-spyware-vucic)
- [Ukraine disputes Musk's claims of Starlink misuse as military connectivity restored](https://therecord.media/ukraine-disputes-musk-claims-of-starlink-misuse)
- [Dutch police extradite Chinese national accused of laundering Cambodian investment scam funds](https://therecord.media/dutch-police-extradite-chinese-national-money-laundering-scams)
- [Ukraine warns hackers are exploiting Chinese-made Dahua surveillance cameras](https://therecord.media/ukraine-cert-ua-warning-chinese-dahua-cameras-hacked)

### Infosecurity Magazine
- [CISA 2030 Sets Out ‘Aggressive, Anticipatory’ Cyber Defense Strategy for Critical Infrastructure](https://www.infosecurity-magazine.com/news/cisa-aggressive-strategy-critical/)
- [Gheist Attackers Stumble in Attempt to Abuse GitHub Tokens](https://www.infosecurity-magazine.com/news/gheist-attackers-abuse-stolen/)
- [Linux Flaws Exposed Before Fixes as Root Exploit Goes Public](https://www.infosecurity-magazine.com/news/linux-flaws-exposed-before-fixes/)
- [Microsoft Issues Emergency Patch Update for Critical .NET Buffer Overflow Flaw](https://www.infosecurity-magazine.com/news/microsoft-patch-update-net-flaw/)
- [Blue Initiative Offers Maritime Sector Dedicated Vulnerability Database](https://www.infosecurity-magazine.com/news/blue-initiative-maritime/)
- [PHP Publishes Mitigation Advice for New RCE Flaw](https://www.infosecurity-magazine.com/news/php-publishes-mitigation-advice/)

### CyberScoop
- [Experts temper emergency-level alarms over critical Brotli defect](https://cyberscoop.com/brotli-critical-vulnerability-decompression-library-node2shell-broccoli2shell/)
- [Senators, rights groups say Trump administration breaking law by withholding surveillance court opinion](https://cyberscoop.com/wyden-schiff-fisa-section-702-declassification/)
- [Authorities extradite Chinese national for alleged $37M investment scam](https://cyberscoop.com/chinese-national-extradited-investment-scam/)
- [CISA publishes strategy with eye on the next four years](https://cyberscoop.com/cisa-2030-cybersecurity-strategy/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Tuesday, October 27th, 2026 https://isc.sans.edu/podcastdetail/10152, (Tue, Oct 27th)](https://isc.sans.edu/diary/rss/33462)
- [Apple Patches for October 2026, (Mon, Oct 26th)](https://isc.sans.edu/diary/rss/33458)
- [Looking for a Language &#x5b;Guest Diary&#x5d;, (Wed, Oct 21st)](https://isc.sans.edu/diary/rss/33442)
- [ISC Stormcast For Monday, October 26th, 2026 https://isc.sans.edu/podcastdetail/10150, (Mon, Oct 26th)](https://isc.sans.edu/diary/rss/33456)

### Securelist (Kaspersky)
- [Deploying AI agents securely: how Kaspersky products mitigate AI threats](https://securelist.com/tr/how-to-secure-ai-agents/121444/)

### CrowdStrike Blog
- [Why Organizations Secure AI Agents with Falcon Guardian](https://www.crowdstrike.com/en-us/blog/why-organizations-secure-ai-agents-with-falcon-guardian/)
- [Obstacles to Weaponizing PHP2Shell Likely Constrain Immediate Widespread Exploitation](https://www.crowdstrike.com/en-us/blog/obstacles-to-weaponizing-php2shell-likely-constrain-exploitation/)
- [CrowdStrike Protects Customers from Threats Delivered via PHP2Shell](https://www.crowdstrike.com/en-us/blog/crowdstrike-protects-customers-from-php-rce-zero-days/)
- [CrowdStrike Uncovers New Agentic AI Campaigns](https://www.crowdstrike.com/en-us/blog/crowdstrike-uncovers-new-agentic-ai-campaigns/)
- [CrowdStrike Achieves NCSC CIR Enhanced Level Assurance](https://www.crowdstrike.com/en-us/blog/crowdstrike-achieves-uk-ncsc-cir-enhanced-level-assurance/)
- [U.S. Government Disrupts FAMOUS CHOLLIMA Operation with CrowdStrike Assistance](https://www.crowdstrike.com/en-us/blog/fbi-disrupts-famous-chollima-operation-with-crowdstrike-assistance/)
- [October 2026 Patch Tuesday: 1,413 CVEs Include Three Zero-Days and 75 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-october-2026/)
- [CrowdStrike and Anthropic Give Critical Infrastructure Defenders the AI Advantage](https://www.crowdstrike.com/en-us/blog/crowdstrike-anthropic-critical-infrastructure-defense-program/)
- [Solving the Continuous Authorization Conundrum](https://www.crowdstrike.com/en-us/blog/solving-the-continuous-authorization-conundrum/)
- [Unknown Threat Actor Uses AI-Driven ARTEX to Target South Korean Finance](https://www.crowdstrike.com/en-us/blog/unknown-threat-actor-uses-artex-to-target-south-korean-finance/)

### FortiGuard Threat Signal
- [Node.js Brotli Remote Code Execution (Nodel2Shell)](https://fortiguard.fortinet.com/threat-signal-report/6556)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal