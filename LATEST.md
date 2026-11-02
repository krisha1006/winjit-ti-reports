# Winjit Daily TI Digest — 2026-11-02

_Auto-generated. Window: last ~24h. Fetched at 2026-11-02T10:45:41.226562+00:00Z_

**At a glance:** 0 new KEV · 41 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-120189 | 10.0 | 1.3% | A vulnerability was identified in D-Link DIR-505 1.10B02. Affected is the function save_upload_file/mp_upload_file of the file /usr/bin/tftpd of the component TFTP Upload Filename Handler. The manipul |
| CVE-2026-120195 | 10.0 | 2.1% | A security vulnerability has been detected in WAVLINK WL-WN579A3-A 2026-03-10-94f93d4. The impacted element is the function set_wzdgwMesh of the file /cgi-bin/adm.cgi of the component Initial Setup Wi |
| CVE-2026-120198 | 10.0 | 2.1% | A vulnerability has been found in WAVLINK WL-WN530BE1-A V251117. Affected is the function con_check_read_finish of the file /protocol.csp. Such manipulation of the argument group_name/IP-FROM leads to |
| CVE-2026-120276 | 10.0 | n/a | A weakness has been identified in WAVLINK WN536AX6-A V260507_2.0.0. This vulnerability affects the function sub_416760 of the file /bin/ioos of the component Web Management Interface. This manipulatio |
| CVE-2026-120277 | 10.0 | n/a | A security vulnerability has been detected in WAVLINK WN536AX6-A V260507_2.0.0. This issue affects the function sub_41a1d8 of the file /bin/ioos of the component WireGuard CLI Group Handler. Such mani |
| CVE-2026-120279 | 10.0 | n/a | A flaw has been found in WAVLINK WN536AX6-A V260507. The affected element is an unknown function of the file /protocol.csp of the component openvpn_cli Handler. Executing a manipulation of the argumen |
| CVE-2026-120280 | 10.0 | n/a | A vulnerability has been found in WAVLINK WN536AX6-A V260507. The impacted element is the function wireguard_cli_group handler of the file /protocol.csp of the component WireGuard. The manipulation of |
| CVE-2026-120281 | 10.0 | n/a | A vulnerability was found in WAVLINK WN536AX6-A V260507. This affects the function strcpy of the file /protocol.csp of the component OpenVPN Handler. The manipulation of the argument openvpn_ip result |
| CVE-2026-120283 | 10.0 | n/a | A vulnerability was identified in Linksys E8450 1.2.00.360516. Affected is the function strcpy of the file /www/cgi-bin/portal.cgi. Such manipulation of the argument hidden_timezone leads to stack-bas |
| CVE-2026-120344 | 10.0 | n/a | A vulnerability has been found in WAVLINK WN551X3-A M51X3_V251020-WO-182e965. This affects the function system of the file /bin/ioos of the component WireGuard CLI Group Handler. Such manipulation of  |
| CVE-2026-120345 | 10.0 | n/a | A vulnerability was found in WAVLINK WN551X3-A M51X3_V251020-WO-182e965. This impacts the function sub_41a430 of the file /bin/ioos of the component DNS Resolution Handler. Performing a manipulation o |
| CVE-2026-120196 | 9.9 | 1.7% | A vulnerability was detected in WAVLINK WN579X3-D V250402. This affects the function port_forward of the file /cgi-bin/wapi.cgi. The manipulation of the argument Name results in os command injection.  |
| CVE-2026-120197 | 9.9 | 1.7% | A flaw has been found in WAVLINK WL-WN530HG4B M_V260724. This impacts the function port_forward of the file /cgi-bin/wapi.cgi. This manipulation of the argument Name causes os command injection. It is |
| CVE-2026-120224 | 9.9 | n/a | A security flaw has been discovered in Oray Pugongying X5 Pro up to 7.6.1. Affected is the function run_apis_by_json/run_async_task of the component API Authorization. The manipulation results in impr |
| CVE-2026-120227 | 9.9 | n/a | A vulnerability was detected in WAVLINK WN701AE M01AE_V260105. This affects the function del_staticrule of the file static_route_setting.sh of the component ioos Web Backend. Performing a manipulation |
| CVE-2026-120228 | 9.9 | n/a | A flaw has been found in WAVLINK WN553X1-B V260403_2.0.0. This vulnerability affects the function sub_416D88 of the file /bin/ioos of the component ioos Service. Executing a manipulation of the argume |
| CVE-2026-120230 | 9.9 | n/a | A vulnerability was found in WAVLINK WN701AE 260105. Impacted is the function del_vlan_group of the component ioos Web Backend. The manipulation of the argument vlan_name results in os command injecti |
| CVE-2026-120231 | 9.9 | n/a | A vulnerability was determined in WAVLINK WN553X1-B V260403_2.0.0. The affected element is the function sub_416568 of the file /bin/ioos of the component OpenVPN CLI Handler. This manipulation of the  |
| CVE-2026-120238 | 9.9 | n/a | A vulnerability has been found in WAVLINK WN553X1-B 260403_2.0.0. This affects the function sub_4162A8 of the file /bin/ioos of the component ovpn_file Handler. Such manipulation of the argument file_ |
| CVE-2026-120239 | 9.9 | n/a | A vulnerability was found in WAVLINK WN553X1-B V260403_2.0.0. This vulnerability affects the function sub_419DA8 of the file /bin/ioos of the component WireGuard CLI Handler. Performing a manipulation |
| CVE-2026-120240 | 9.9 | n/a | A vulnerability was determined in WAVLINK WN553X1-B V260403_2.0.0. This issue affects the function sub_41A748 of the file /bin/ioos of the component WireGuard CLI Group Handler. Executing a manipulati |
| CVE-2026-120282 | 9.9 | n/a | A vulnerability was determined in WAVLINK WN536AX6-A V260507. This impacts the function host_black of the file /protocol.csp. This manipulation of the argument mac causes os command injection. Remote  |
| CVE-2026-120322 | 9.9 | n/a | A vulnerability was identified in Termix-SSH Termix up to 2.9.2. This issue affects some unknown processing of the file /plugin-api/file-manager/transferToHost. The manipulation of the argument destPa |
| CVE-2026-120225 | 9.1 | n/a | A weakness has been identified in Oray Pugongying X5 Pro up to 7.6.1. Affected by this vulnerability is the function config_restore_ex of the file /etc/openwrt_release. This manipulation of the argume |
| CVE-2026-120229 | 9.1 | n/a | A vulnerability has been found in WAVLINK WN553X1-B 260403_2.0.0. This issue affects the function sub_416B50 of the file /bin/ioos. The manipulation of the argument file_id leads to os command injecti |
| CVE-2026-120232 | 8.8 | n/a | A vulnerability was identified in Horizon DataSys Reboot Restore Standard up to 13.2. The impacted element is the function sub_23908 in the library shield.sys of the component Kernel Driver. Such mani |
| CVE-2026-120311 | 8.8 | n/a | Network-AI from 5.13.4 before 5.15.5 contains a path traversal vulnerability in FileJobStore that allows attackers to read or delete arbitrary .json files by supplying traversal sequences in the job i |
| CVE-2026-120312 | 8.8 | n/a | Network-AI from 5.13.4 before 5.15.5 contains a path traversal vulnerability in AgentVCR that allows attackers controlling the cassette name to read or write arbitrary .json files. Attackers can pass  |
| CVE-2026-120315 | 8.8 | n/a | LobeHub Chat from 1.84.26 before 2.1.49 contains a path traversal vulnerability that allows authenticated users to write arbitrary files by supplying unsanitized file names to writeTempFile(). Attacke |
| CVE-2026-120324 | 8.3 | n/a | A weakness has been identified in Aklivity Zilla up to 1.3.4/2.4.7/2.5.0-rc2. The affected element is the function Path.resolve of the file FileSystemServerFactory of the component http-filesystem Bin |
| CVE-2026-120241 | 7.5 | n/a | A vulnerability was identified in Ruijie RG-ES205GC, RG-ES206GC-P, RG-ES208GC, RG-ES210GC-LP and RG-ES210GS-P ESW_1.0(1)B1P48. Impacted is an unknown function of the file httpupg.cgi of the component  |
| CVE-2026-120313 | 7.5 | n/a | Network-AI before 5.15.5 contains a path traversal vulnerability in InputSanitizer.sanitizePath() that allows attackers to escape the base directory using sibling-directory paths. Attackers can supply |
| CVE-2026-120191 | 7.3 | 0.8% | A weakness has been identified in Presenton up to 0.9.11-beta. Affected by this issue is some unknown functionality of the component API. This manipulation causes missing authentication. It is possibl |
| CVE-2026-120314 | 7.3 | n/a | Network-AI from 5.14.0 before 5.15.5 contains a missing authentication vulnerability in the A2AServer class that allows unauthenticated attackers to access task operations when no secret is configured |
| CVE-2026-120336 | 7.3 | n/a | A vulnerability was found in VStarcam O-KAM Client 1.3.3.32. Affected by this vulnerability is the function FUN_10003EA0 in the library DevDll_925.dll. The manipulation results in stack-based buffer o |
| CVE-2026-120337 | 7.3 | n/a | A vulnerability was determined in VStarcam O-KAM SuperIPCam 1.3.3.32. Affected by this issue is the function FUN_005a2d44 of the file SuperIPCam.exe of the component P2P Session Teardown. This manipul |
| CVE-2026-120341 | 7.3 | n/a | A security vulnerability has been detected in mathurvishal CloudClassroom-PHP-Project. Impacted is an unknown function of the file studentdetails.php. The manipulation leads to execution after redirec |
| CVE-2026-120342 | 7.3 | n/a | A vulnerability was detected in mathurvishal CloudClassroom-PHP-Project. The affected element is an unknown function of the file viewquery.php. The manipulation of the argument eid results in sql inje |
| CVE-2026-120347 | 7.3 | n/a | A vulnerability was determined in dayrui XunRuiCMS up to 4.7.4. Affected is the function View of the file dayrui/Fcms/Core/View.php of the component Member Module. Executing a manipulation of the argu |
| CVE-2026-120348 | 7.3 | n/a | A vulnerability was identified in dayrui XunRuiCMS up to 4.7.4. Affected by this vulnerability is the function _get_tpl_content of the file dayrui/Fcms/Library/Notice.php of the component Email Templa |
| CVE-2026-120349 | 7.3 | n/a | A security flaw has been discovered in dayrui XunRuiCMS up to 4.7.4. Affected by this issue is the function str_replace of the file /var/www/html/zzmob/index.php of the component Mobile Site Directory |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-fpcc-wxm7-87wc | CVE-2026-103310 | medium | The PayHere Payment Gateway WordPress plugin from 2.4.0 through 2.4.5 does not verify the... |
| GHSA-h86x-mppv-hp46 | CVE-2026-101184 | medium | Permission control vulnerability in the Bluetooth module.
Impact: Successful exploitation of this... |
| GHSA-g94w-7rpc-xf8m | CVE-2026-107457 | low | A memory corruption vulnerability in the QMqttClient class of the Qt MQTT module. Under certain... |
| GHSA-fm4c-g4r5-j629 | CVE-2026-101180 | medium | DoS vulnerability in the file parsing module.
Impact: Successful exploitation of this... |
| GHSA-rq78-9fpp-qr4m | CVE-2026-18199 | high | Zohocorp ManageEngine Password Manager Pro versions before 13236 and PAM360 versions before 8601... |
| GHSA-xh7r-qp3f-cv4q | CVE-2026-101186 | high | DoS vulnerability in the window module.
Impact: Successful exploitation of this vulnerability may... |
| GHSA-9qv8-r69g-p4f5 | CVE-2026-101178 | medium | Permission control vulnerability in the autofill service module.
Impact: Successful exploitation... |
| GHSA-5r35-w63q-rcr8 | CVE-2026-120349 | medium | A security flaw has been discovered in dayrui XunRuiCMS up to 4.7.4. Affected by this issue is... |
| GHSA-h394-89r9-c5qx | CVE-2026-101185 | medium | OOB read vulnerability in the peripheral module.
Impact: Successful exploitation of this... |
| GHSA-739x-rmv6-xg4v | CVE-2026-101181 | medium | Permission control vulnerability in the WLAN module. 
Impact: Successful exploitation of this... |
| GHSA-gxpw-w695-578r | CVE-2026-101183 | medium | UAF vulnerability in the location service module.
Impact: Successful exploitation of this... |
| GHSA-279j-x223-5hhm | CVE-2026-101182 | medium | Race condition vulnerability in the location service module.
Impact: Successful exploitation of... |
| GHSA-23rc-cmmh-2cx7 | CVE-2026-101177 | low | Permission control vulnerability in the Optimizer module.
Impact: Successful exploitation of this... |
| GHSA-g3r9-w8pr-mh8r | CVE-2026-101179 | medium | Buffer overflow vulnerability in the file preview module.
Impact: Successful exploitation of this... |
| GHSA-9fx2-fwgq-ffh5 | CVE-2026-101175 | medium | Null pointer dereference vulnerability in the ArkWeb module.
Impact: Successful exploitation of... |
| GHSA-v3hg-q936-w95m | CVE-2026-101174 | medium | DoS vulnerability in the DSoftBus module.
Impact: Successful exploitation of this vulnerability... |
| GHSA-q78w-j37r-f5hr | CVE-2026-101171 | low | Permission control vulnerability in the background task management module.
Impact: Successful... |
| GHSA-738v-h225-334f | CVE-2026-101172 | medium | Permission control vulnerability in the graphics module. Impact: Successful exploitation of this... |
| GHSA-chm4-2g7h-7hq4 | CVE-2026-101176 | high | Permission control vulnerability in the event notification management module.
Impact: Successful... |
| GHSA-xx2c-j6fh-rr7q | CVE-2026-101173 | medium | DoS vulnerability in the DSoftBus module.
Impact: Successful exploitation of this vulnerability... |
| GHSA-h9qf-xvw8-pmr6 | CVE-2026-101170 | medium | DoS vulnerability in the file parsing module.
Impact: Successful exploitation of this... |
| GHSA-r9m4-crch-98pw | CVE-2026-120348 | medium | A vulnerability was identified in dayrui XunRuiCMS up to 4.7.4. Affected by this vulnerability is... |
| GHSA-rq2r-g99g-gxmf | CVE-2026-120347 | medium | A vulnerability was determined in dayrui XunRuiCMS up to 4.7.4. Affected is the function View of... |
| GHSA-p4rq-q6fh-965p | CVE-2025-11969 | critical | The System REST APIs do not correctly enforce access control mechanisms, allowing users with... |
| GHSA-5m3x-rp28-cf8g | CVE-2026-120345 | critical | A vulnerability was found in WAVLINK WN551X3-A M51X3_V251020-WO-182e965. This impacts the... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Company #117 | N0n | US | 2026-11-02T04:54:25.042516+00:00 |
| Company #116 | N0n | US | 2026-11-02T04:53:50.031605+00:00 |
| Company #115 | N0n | US | 2026-11-02T04:53:17.413944+00:00 |
| Company #114 | N0n | US | 2026-11-02T04:52:43.227614+00:00 |
| Company #113 | N0n | US | 2026-11-02T04:52:10.564040+00:00 |
| Tema Hwt | Shiba | DE | 2026-11-01T18:03:35.740611+00:00 |
| synergy.co.id | lockbit5 | ID | 2026-11-01T19:27:52.959212+00:00 |
| AmplifAI (GoDaddy instance) | Whitearmor | US | 2026-11-01T13:58:21.336343+00:00 |
| My Cloud Grocer | direwolf | GB | 2026-11-01T13:06:49.688974+00:00 |
| hitech group | HYFLOCK | US | 2026-11-01T12:51:59.138258+00:00 |
| EVINOKS | Barracuda | TR | 2026-11-01T01:50:47.238640+00:00 |
| Michigan State University | BYOD | US | 2026-11-02T03:50:23.325193+00:00 |
| fzmb GmbH, Forschungszentrum für Medizintechnik und Biotechnologie | qilin | DE | 2026-11-01T17:33:12.469171+00:00 |
| Global Holding | qilin |  | 2026-11-01T15:29:16.445863+00:00 |
| Shibata Co., Ltd. | qilin | JP | 2026-11-01T12:25:55.065188+00:00 |
| Meshbesher & Spence | qilin | US | 2026-11-01T12:25:32.835938+00:00 |
| BKV Vasúti Jármjavító Kft | qilin | HU | 2026-11-01T12:24:51.104823+00:00 |
| Forum | qilin | AT | 2026-11-01T12:24:09.617902+00:00 |
| Select Community Management | qilin | US | 2026-11-01T11:25:59.119232+00:00 |
| CMD Naturkosmetik | qilin | DE | 2026-11-01T11:25:13.392406+00:00 |

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
| 18.218.118.203 | 9 |
| 45.148.10.141 | 9 |
| 45.148.10.240 | 9 |
| 51.159.4.12 | 9 |
| 77.239.124.2 | 9 |
| 80.94.95.116 | 9 |
| 103.159.2.113 | 9 |
| 119.28.84.193 | 9 |
| 167.94.146.58 | 9 |
| 179.43.153.10 | 9 |
| 196.189.236.67 | 9 |
| 199.165.159.89 | 9 |
| 220.80.223.144 | 9 |
| 2.57.121.25 | 8 |
| 2.57.121.112 | 8 |
| 3.129.187.38 | 8 |

### OpenPhish (live phishing URLs)
- https://www.instagramcom-weld.vercel.app/
- https://www.roblox.com.ml/users/438014914332/profile
- https://skylanai.com/
- https://internationaldatasystems.ca/speed/
- http://connect.mytonwallet.org/
- http://vpn.spheremama.com/index.html
- http://jacog60r.spheremama.com/index.html
- https://vendors.spheremama.com/index.html
- https://operator.zh5-app-ayxsports.com/index.html
- https://qtlm.spheremama.com/index.html
- http://6tg19ha5.sanpinjia.com/
- http://231mbutu5udwntnq.spheremama.com/
- https://z28ae00t218otkz2.spheremama.com/index.html
- http://567787.spheremama.com/
- https://promo.sanpinjia.com/index.html
- http://e8y3qufn.sanpinjia.com/
- https://file.spheremama.com/
- https://www.roblox.rw/users/696317506556/profile
- https://g5.lu/zdnwx
- https://etransfer-accept.duckdns.org/captcha.php

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://brt.tramite.us.cc/it/ |
| N/A | https://plucky-goals-083021.framer.app/ |
| N/A | https://brt.clienti.us.cc/it/#/index |
| N/A | https://amazoncheckout.netlify.app/ |
| N/A | https://away.vk.ru/away.php?rh=f026caf7-3137-4cfc-a332-33c211e6f207 |
| N/A | https://brt.fallire.us.cc/it/ |
| N/A | https://brtits.click/check/ |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bffgf=1&amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=Af_xneGpinflONH_c3iB5WwVV1C6BSPwAwpudWnjxe8BcKRMcZLFgAnlzpjtHVk0QMFIUm6AcMYv&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBgleB92Lxb0UN9qu9y5VUEuWPHNPUWR8HRlBCc_fl_yYMKaTFkjxhJ0vqt1Cytc33jx_SsGCcJw&dsh=S1377931304%3A1793615410773370 |
| N/A | https://ersfilter-my.sharepoint.com/personal/nradonich_ersfilter_com/_layouts/15/doc.aspx?guestaccesstoken=t6T%2FHN1dKbYHlYX%2BeIMbaZufA43rrGZ6%2FaAAewNocDI%3D&docid=1_18168db23429e45f29fdf2e7be120efc4&wdFormId=%7BB9970F62-44C3-4D09-9929-6E1EB652DA57%7D&action=formsubmit&CID=4cf5b47b-91c2-4889-b258-3cfe0c53d189 |
| N/A | https://brtitv.click/check/ |
| N/A | https://away.vk.ru/away.php?rh=7581bcbc-52c5-41bf-a5f8-59fdd83d23df |
| N/A | https://www.daxibuyi.com/page/qhxozfpeys |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AaSxoQyQ_ZSuXpSvue0UfKrOXnU6mQAuN0RcLmvWGTqSCzhKlOsPyDT7wQQH6ra2Rhdw1PE87iTB&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBgleQt7uVv6ZW3pnZj19KpxLIMcwX7E5X21KcYCKCcq8FUxD5Bzf3oJFdgkn0Uldq6S1qWaiw-Q&dsh=S1829914282%3A1793614680307612 |
| N/A | https://id.superhuman.com/signin?oauth_client_type=MEDIATED_WEB&correlation_id=re6HQHpme_FufFeYlY7zaQ&version=v4&client_id=superhumanDocs |
| N/A | https://annulationrapide.services-instructions-abonnements.com/ |
| N/A | https://annulation.services-instructions-abonnements.com/ |
| N/A | https://brt.civico.us.cc/it/ |
| N/A | https://pageseuc1.actmkt.com/(S(2xlukpfmzlvm5cqagu42e2dr))/l/c5X8MfZz6j9Y7Fto3LAd |
| N/A | https://www.cdiscount.com?source_id=&sub1=dbk637u0fgns738cij60&adv1=&adv2= |
| N/A | https://support-service-portal.vercel.app/accounts-center |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
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
| 3b1a9b1ca40319bdd405d0dd09923c58d250baa0 | ACRStealer C&C |
| 44c6ec85d52ecb270148701bc655e2af697e010f | ACRStealer malware distribution |

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
- 1.117.73.220
- 1.12.55.80
- 1.14.192.95
- 1.14.240.247
- 1.15.221.192
- 1.159.54.33
- 1.162.226.183
- 1.173.231.52
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.220.198.126
- 1.222.42.237
- 1.234.80.94
- 1.235.183.146
- 1.238.106.229
- 1.245.161.206
- 1.247.245.61
- 1.250.67.114

### CINS Army (poorly-rated IPs)
- 1.0.235.78
- 1.145.89.105
- 1.170.196.186
- 1.192.129.106
- 1.193.59.243
- 1.193.63.167
- 1.197.255.180
- 1.24.16.106
- 1.24.16.132
- 1.24.16.136
- 1.24.16.146
- 1.24.16.148
- 1.24.16.153
- 1.24.16.186
- 1.24.16.32
- 1.24.16.73
- 1.24.16.83
- 1.24.16.89
- 1.24.18.131
- 1.24.229.200

## News (last ~36h, across outlets)
### The Hacker News
- [New VOLTA Infostealer Uses Claude, Gemini, and Kimi AI to Rank Victims by Financial Value](https://thehackernews.com/2026/11/new-volta-infostealer-uses-claude.html)
- [CVSS 10.0 LXD, MicroCloud Flaw Lets Attackers Impersonate Trusted Clients Without a Private Key](https://thehackernews.com/2026/11/critical-lxd-and-microcloud-flaw-cvss.html)
- [Hackers Steal About $2.7 Million From Polymarket Traders via Hijacked DebugBear Script](https://thehackernews.com/2026/11/hackers-steal-about-27-million-from.html)
- [FBI Links North Korea's TraderTraitor to Record $6.43 Billion Binance Crypto Heist](https://thehackernews.com/2026/11/fbi-links-north-koreas-tradertraitor-to.html)
- [NetamLoader Malware Targets Government Windows 10 Systems in Asia via .NET Injection](https://thehackernews.com/2026/11/netamloader-malware-targets-government.html)

### BleepingComputer
- [Ivanti patches two more Connect Secure zero-days chained in attacks](https://www.bleepingcomputer.com/news/security/ivanti-patches-two-more-connect-secure-zero-days-chained-in-attacks/)
- [FBI links $6.3 billion Binance crypto heist to North Korean hackers](https://www.bleepingcomputer.com/news/security/fbi-links-63-billion-binance-crypto-heist-to-north-korean-hackers/)
- [Alpine Linux rebuilds GitLab after attempted RCE attack](https://www.bleepingcomputer.com/news/security/alpine-linux-rebuilds-gitlab-after-attempted-rce-attack/)
- [OpenAI says it's doubling Pro usage limits and bringing Work features to Chat](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-says-its-doubling-pro-usage-limits-and-bringing-work-features-to-chat/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
_No new items / feed unavailable this run._

### SecurityWeek
- [Chainalysis Discloses Data Breach Following AI-Driven Cyberattack](https://www.securityweek.com/chainalysis-discloses-data-breach-following-ai-driven-cyberattack/)
- [Polymarket Returns $3.9 Million to Traders as DebugBear Cites DNS Hijack](https://www.securityweek.com/polymarket-returns-3-9-million-to-traders-as-debugbear-cites-dns-hijack/)
- [FBI Flags Over 600 Addresses Tied to North Korea’s Binance Heist](https://www.securityweek.com/fbi-flags-over-600-addresses-tied-to-north-koreas-binance-heist/)
- [Ivanti Patches Two More Zero-Days Exploited in Connect Secure Attack Chain](https://www.securityweek.com/ivanti-patches-two-more-zero-days-exploited-in-connect-secure-attack-chain/)
- [Northstar Security Exits Stealth With $7M to Expose Toxic Risk Combinations](https://www.securityweek.com/northstar-security-exits-stealth-with-7m-to-expose-toxic-risk-combinations/)

### The Record
- [FBI blames N. Korea’s TraderTraitor for Binance theft, urges crypto industry to block transactions](https://therecord.media/fbi-blames-tradertraitor-for-binance-hack)

### Infosecurity Magazine
- [FBI Attributes Binance Heist to North Korea’s TraderTraitor](https://www.infosecurity-magazine.com/news/fbi-attributes-binance-north/)
- [Chainalysis Warns Customers After “Offensive Agentic” Security Incident](https://www.infosecurity-magazine.com/news/chainalysis-customers-offensive/)

### CyberScoop
- [Federal court tosses Trump lawsuit challenging Alaska Senate certification](https://cyberscoop.com/judge-dismisses-alaska-senate-lawsuit-peltola-sullivan/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Monday, November 2nd, 2026 https://isc.sans.edu/podcastdetail/10160, (Mon, Nov 2nd)](https://isc.sans.edu/diary/rss/33480)
- [OneNote File Extraction, (Sun, Nov 1st)](https://isc.sans.edu/diary/rss/33478)

### Securelist (Kaspersky)
- [CyberStrikeAI in the wild: the use of AI in real-world attacks on organizations](https://securelist.com/tr/cyberstrikeai-attacks/121715/)

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