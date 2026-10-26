# Winjit Daily TI Digest — 2026-10-26

_Auto-generated. Window: last ~24h. Fetched at 2026-10-26T08:41:20.153418+00:00Z_

**At a glance:** 0 new KEV · 33 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-116231 | 9.9 | n/a | A security flaw has been discovered in Oray Pugongying X5 Pro 7.6.1. The impacted element is an unknown function of the component Ser2net. Performing a manipulation of the argument regmsg results in c |
| CVE-2026-116232 | 9.9 | n/a | A weakness has been identified in Oray Pugongying X5 Pro 7.6.1. This affects the function snmp_set of the component SNMP Handler. Executing a manipulation of the argument info.community can lead to cr |
| CVE-2026-116207 | 9.1 | n/a | YesWiki 4.6.0 before 4.7.0 and 5.0.0-alpha1 before 5.0.0-alpha4 contains an unauthenticated SQL injection vulnerability in SearchManager::prepareSearchRequest(). Field names from the query and searchf |
| CVE-2026-116068 | 8.8 | n/a | Dokploy through 0.30.10 contains an authorization bypass vulnerability that allows owners or admins of any organization to control other tenants' applications by supplying foreign applicationId values |
| CVE-2026-116201 | 8.8 | n/a | Snipe-IT before 8.5.0 contains a SAML assertion replay vulnerability that allows attackers to reuse captured assertions by exploiting a non-atomic nonce check in the SAML acs handler. Attackers can se |
| CVE-2026-116067 | 8.2 | n/a | Paisa before 0.7.8 contains a path traversal vulnerability in the GetFile, GetSheet, DeleteBackups, and DeleteSheetBackups handlers that lets unauthenticated attackers read files and delete backups th |
| CVE-2026-116176 | 8.2 | n/a | vLLM from 0.9.2 before 0.24.0 contains a server-side request forgery vulnerability that allows API callers to force outbound connections by embedding a decode address in the X-Request-Id header. Attac |
| CVE-2026-116211 | 8.2 | n/a | YesWiki 4.5.0 before 4.7.0 contains an SQL injection vulnerability in PageManager::save(), where the date_maj_fiche field of a Bazar entry-creation request is concatenated unescaped into an INSERT sta |
| CVE-2026-116116 | 8.2 | n/a | A vulnerability was detected in Yoosee GM8135S Camera 21.00.01.36. Affected is an unknown function of the component Secure Boot. Performing a manipulation results in improper verification of cryptogra |
| CVE-2026-116149 | 8.1 | n/a | ImageMagick before 6.9.13-58 and 7.x before 7.1.2-33 contains a stack-based buffer overflow in the handling of bzip2 compressed images. Attackers can supply a crafted image using bzip2 compression to  |
| CVE-2026-116199 | 8.1 | n/a | Snipe-IT before 8.6.3 contains an authentication bypass in GoogleAuthController::handleGoogleCallback, which logs in the user whose username matches the Google account email without enforcing the acti |
| CVE-2026-116204 | 8.1 | n/a | YesWiki before 4.7.0 contains a cross-site request forgery vulnerability in the despam action (tools/security/actions/despam.php) that lets unauthenticated attackers delete or restore pages through an |
| CVE-2026-116208 | 8.1 | n/a | YesWiki from 4.6.2 before 4.7.0 contains a missing authorization vulnerability in ActivityPubService::syncActorPosts that lets malicious ActivityPub servers manipulate other actors' mirrored entries.  |
| CVE-2026-116180 | 7.7 | n/a | vLLM from 0.8.5 before 0.31.0 has a denial of service flaw. LogprobsTensors.empty_cpu() in vllm/v1/outputs.py allocates an uninitialized int32 tensor, and the V1 model runner leaves prompt positions r |
| CVE-2026-116177 | 7.5 | n/a | vLLM from 0.10.2 before 0.25.0 contains an uncontrolled resource consumption vulnerability that allows unauthenticated attackers to exhaust memory because the Nemotron-VL processors globally set Image |
| CVE-2026-116179 | 7.5 | n/a | vLLM from 0.18.0 before 0.31.0 contains a resource exhaustion vulnerability that allows API clients to bypass the video/jpeg frame-count cap by overriding num_frames through media_io_kwargs. Attackers |
| CVE-2026-116183 | 7.5 | n/a | phpMyFAQ before 4.1.10 contains an object-level authorization bypass vulnerability that allows unauthenticated attackers to modify or delete any visitor question by supplying an arbitrary openQuestion |
| CVE-2026-116189 | 7.5 | n/a | rclone from 1.55.0 before 1.75.2 contains a signature verification bypass in stable selfupdate that trusts checksums from unsigned bytes preceding the PGP-clearsigned SHA256SUMS block. Attackers contr |
| CVE-2026-116191 | 7.5 | n/a | Rclone before 1.75.2 contains a path traversal vulnerability in serve webdav that allows unauthenticated attackers to write above the served root by sending an unvalidated '..' path component. Attacke |
| CVE-2026-116163 | 7.4 | n/a | Parse Server before 8.6.102 and 9.0.0 before 9.10.5-alpha.2 contains an authentication bypass because the validateSetUp, validateLogin, and validateUpdate methods of custom adapters subclassing AuthAd |
| CVE-2026-115999 | 7.3 | 0.3% | A vulnerability has been found in mansi-k Restaurant_IMS d7ad49f61ab7cc1ec6eb359ac2b5378bdbde0694. Affected is the function mysqli_connect of the file lsmodal.php. The manipulation of the argument log |
| CVE-2026-116000 | 7.3 | 0.3% | A security flaw has been discovered in Zylon PrivateGPT 1.0.0/1.0.1. This vulnerability affects the function load_file_from_uri of the file private_gpt/server/ingest/uri_loader.py of the component URI |
| CVE-2026-116006 | 7.3 | 0.4% | A vulnerability was detected in YunaiV/zhijiantianya ruoyi-vue-pro up to 2026.09. The affected element is an unknown function of the file AuthController.java of the component SMS Code Verification. Th |
| CVE-2026-116048 | 7.3 | 0.3% | A vulnerability was detected in krupalshah EmployeeRecruitmentSystem up to 922ff6d208278282e7c8e36d70d9ae356adec9fe. Affected by this vulnerability is the function mysql_query of the file /source/regi |
| CVE-2026-116049 | 7.3 | 0.3% | A flaw has been found in krupalshah EmployeeRecruitmentSystem up to 922ff6d208278282e7c8e36d70d9ae356adec9fe. Affected by this issue is the function mysql_query of the file /source/registerform2.php o |
| CVE-2026-116050 | 7.3 | 0.3% | A vulnerability has been found in krupalshah Employee Recruitment System up to 922ff6d208278282e7c8e36d70d9ae356adec9fe. This affects an unknown part of the file /source/registerform3.php of the compo |
| CVE-2026-116060 | 7.3 | n/a | A vulnerability was determined in SourceCodester Performance Indicator System 1.0. This affects an unknown part of the file /opils/staff/adddealer.php. Executing a manipulation of the argument Contact |
| CVE-2026-116061 | 7.3 | n/a | A vulnerability was identified in SourceCodester Performance Indicator System 1.0. This vulnerability affects unknown code of the file /opils/staff/edit_dealer.php. The manipulation of the argument Co |
| CVE-2026-116062 | 7.3 | n/a | A security flaw has been discovered in SourceCodester Performance Indicator System 1.0. This issue affects some unknown processing of the file /opils/staff/save_profile.php. The manipulation of the ar |
| CVE-2026-116094 | 7.3 | n/a | A vulnerability was determined in EyouCMS up to 1.8.3. This impacts the function remote_file_to_local of the file application/function.php. Executing a manipulation can lead to server-side request for |
| CVE-2026-116110 | 7.3 | n/a | A vulnerability was found in GiantappMan LiveWallPaper 2.6.8.0 on Windows. This issue affects some unknown processing of the file /LiveWallpaper/UploadFile of the component SignalR Hub. Performing a m |
| CVE-2026-116112 | 7.3 | n/a | A vulnerability was identified in HashenUdara edoc-doctor-appointment-system up to cc258425b915d1af9e298777ccd26d160493e68d. The affected element is an unknown function of the file admin/add-new.php.  |
| CVE-2026-116117 | 7.3 | n/a | A flaw has been found in halo-dev halo up to 2.27.0-beta.1. Affected by this vulnerability is the function run.halo.app.theme.DefaultViewNameResolver.resolveViewNameOrDefault of the file application/s |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-vcp6-2j22-77rj | CVE-2026-116119 | medium | A vulnerability was found in NocoDB up to 2026.08.0. This affects an unknown part of the file... |
| GHSA-xfjr-cjmw-vhcw | CVE-2026-116120 | medium | A vulnerability was determined in NocoDB up to 2026.07.0. This vulnerability affects the function... |
| GHSA-qw65-38gx-3749 | CVE-2026-116121 | medium | A vulnerability was identified in NocoDB up to 2026.08.0. This issue affects some unknown... |
| GHSA-r6jf-7rr9-67p9 | CVE-2026-116123 | medium | A weakness has been identified in NocoDB up to 2026.07.0. The affected element is the function... |
| GHSA-cwjw-4x7p-f6xv | CVE-2026-116122 | medium | A security flaw has been discovered in NocoDB up to 2026.07.0. Impacted is the function... |
| GHSA-8hgg-w6j7-2qjj | CVE-2026-116116 | high | A vulnerability was detected in Yoosee GM8135S Camera 21.00.01.36. Affected is an unknown... |
| GHSA-jxv2-266f-6xgq | CVE-2026-116117 | medium | A flaw has been found in halo-dev halo up to 2.27.0-beta.1. Affected by this vulnerability is the... |
| GHSA-4946-g74f-xm3x | CVE-2026-116115 | low | A security vulnerability has been detected in Yoosee GM8135S Camera 21.00.01.36. This impacts an... |
| GHSA-wm54-r5pw-gm93 | CVE-2026-116118 | low | A vulnerability has been found in Z.ai Zcode up to 3.14.3/3.15.1. Affected by this issue is some... |
| GHSA-g3v3-vrcf-hj62 | CVE-2026-116114 | low | A weakness has been identified in Yoosee GM8135S Camera 21.00.01.36. This affects an unknown... |
| GHSA-jxj3-4fgr-8483 | CVE-2026-116113 | low | A security flaw has been discovered in GouGuOA up to 6.1.2. The impacted element is the function... |
| GHSA-r6vq-m3xv-fg74 | CVE-2026-113345 | high | Electronic delivery item Inspection Support System provided by Japan's Ministry of Land,... |
| GHSA-r6h4-5497-c694 | CVE-2026-116112 | medium | A vulnerability was identified in HashenUdara edoc-doctor-appointment-system up to... |
| GHSA-qqv4-567f-4g4p | CVE-2026-116111 | low | A vulnerability was determined in 2K Games Civilization V 1.0.3.144. Impacted is the function... |
| GHSA-5r9h-jfp8-wfxv | CVE-2026-116107 | low | A vulnerability was detected in Datafeedr Product Sets Plugin up to 1.3.24 on WordPress. Affected... |
| GHSA-3cxv-6mgc-j7c4 | CVE-2026-116109 | low | A vulnerability has been found in continuedev Continue 2.0.0. This vulnerability affects the... |
| GHSA-vg35-77c3-m29x | CVE-2026-116101 | low | A vulnerability was found in itsourcecode Online Cake Ordering System 1.0. The affected element... |
| GHSA-gcgv-3j6w-p5vj | CVE-2026-116106 | medium | A security vulnerability has been detected in HeyCyan App 1.0.103 on Android. Affected by this... |
| GHSA-9wwg-c5q6-j74r | CVE-2026-116100 | low | A vulnerability has been found in gougucms up to 4.08.18. Impacted is the function Add of the... |
| GHSA-c33q-pqr3-xjv6 | CVE-2026-116103 | low | A vulnerability was identified in Sony Neural Network Libraries up to 1.39.0. This affects the... |
| GHSA-7mj2-6mxg-wcx9 | CVE-2026-116102 | medium | A vulnerability was determined in QuantGeekDev docker-mcp 0.1.0/0.2.0. The impacted element is... |
| GHSA-6qxx-xgg9-2xr8 | CVE-2026-116105 | medium | A weakness has been identified in HeyCyan App 1.0.103 on Android. Affected is an unknown function... |
| GHSA-q96p-8xmw-x2vw | CVE-2026-116110 | medium | A vulnerability was found in GiantappMan LiveWallPaper 2.6.8.0 on Windows. This issue affects... |
| GHSA-hcm7-9pjr-2755 | CVE-2026-116108 | low | A flaw has been found in openbq-org OpenBB up to 4.7.2/5.0.0. This affects an unknown part of the... |
| GHSA-4vrm-q3gq-97hp | CVE-2026-116104 | low | A security flaw has been discovered in Sony Neural Network Libraries up to 1.39.0. This impacts... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| LoveSac | Whitearmor | US | 2026-10-26T02:57:17.650976+00:00 |
| Glückauf-Vermessung GmbH | payload | DE | 2026-10-26T00:24:26.372363+00:00 |
| Miletic GmbH | payload | DE | 2026-10-26T00:23:12.630470+00:00 |
| Edelstahl-Mechanik GmbH | payload | DE | 2026-10-26T00:21:58.628410+00:00 |
| J.B Hunt | Whitearmor | US | 2026-10-26T00:00:24.383724+00:00 |
| White & Case | qilin | US | 2026-10-25T17:18:17.976366+00:00 |
| Partido Liberal | Whitearmor | AR | 2026-10-25T16:56:33.851704+00:00 |
| Weitz & Luxenberg | Falcon | US | 2026-10-25T15:52:01.178008+00:00 |
| Astrana Health | Falcon | US | 2026-10-25T14:53:02.969183+00:00 |
| A-RMS | emperador |  | 2026-10-25T14:52:33.011354+00:00 |
| Yodingenierie | Panzer | BJ | 2026-10-25T17:55:57.455931+00:00 |
| Aesthetic Dental Designs, P.A | HYFLOCK | US | 2026-10-25T11:53:17.559073+00:00 |
| AyT COMPUTERS SRL | emperador |  | 2026-10-25T09:52:04.948881+00:00 |
| ETO | qilin | DE | 2026-10-25T07:24:50.523326+00:00 |
| TOPLIVO AD | N0n | BG | 2026-10-25T06:56:34.098354+00:00 |
| Technoleads Services Inc. | N0n |  | 2026-10-25T06:56:05.946039+00:00 |
| Pure Grow Diamonds Inc. | N0n |  | 2026-10-25T06:55:37.623219+00:00 |
| Mach Law APC (San Diego family law and divorce practice) | N0n | US | 2026-10-25T06:55:09.342572+00:00 |
| Keidel Supply Company Incorporated | N0n | US | 2026-10-25T06:54:40.120560+00:00 |
| Andrews Advisory Group LLC | N0n | US | 2026-10-25T06:54:11.761633+00:00 |

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
| 138.226.239.233 | 10 |
| 138.226.239.234 | 10 |
| 144.225.6.184 | 10 |
| 193.24.211.219 | 10 |
| 36.255.97.242 | 9 |
| 38.148.20.75 | 9 |
| 45.148.10.141 | 9 |
| 45.148.10.152 | 9 |
| 50.114.236.142 | 9 |
| 66.132.195.123 | 9 |
| 66.132.195.124 | 9 |
| 102.220.161.170 | 9 |
| 103.159.2.113 | 9 |
| 121.6.96.149 | 9 |
| 147.185.132.51 | 9 |
| 152.32.225.117 | 9 |
| 179.43.153.2 | 9 |

### OpenPhish (live phishing URLs)
- https://s4w.in/jZlxQ
- http://xfinityhelplogin.weebly.com/
- https://www.roblox.rw/games/88738945340571/Would-You-Rather-Countryball-Tower?privateServerLinkCode=11040290185766545005746312904812&game_id=88738945340571&game_name=Would-You-Rather-Countryball-Tower
- https://www.roblox.rw/games/84107034759866/UPD-Countryball-Simulator?privateServerLinkCode=11040290185766545005746312904812&game_id=84107034759866&game_name=UPD-Countryball-Simulator
- https://www.roblox.rw/games/9391468976/HIRED-KILLER-Jujutsu-Shenanigans?privateServerLinkCode=11040290185766545005746312904812&game_id=9391468976&game_name=HIRED-KILLER-Jujutsu-Shenanigans
- https://www.roblox.rw/games/107778070777162/Steal-An-Egg?privateServerLinkCode=11040290185766545005746312904812&game_id=107778070777162&game_name=Steal-An-Egg
- https://www.roblox.rw/games/15269951959/SHINJI-Legends-Battlegrounds?privateServerLinkCode=11040290185766545005746312904812&game_id=15269951959&game_name=SHINJI-Legends-Battlegrounds
- https://www.roblox.rw/games/13076380114/Heroes-Battlegrounds?privateServerLinkCode=11040290185766545005746312904812&game_id=13076380114&game_name=Heroes-Battlegrounds
- http://conncast.vercel.app/
- http://494145-coinbase.com/
- https://cont17ct-davuri-biz-kelom-ravta.pages.dev/
- https://www.dashboard.adobeexperience.com.br/
- https://www.instagarm.vercel.app/
- https://www.roblox.rw/games/77182599101794/-4nn1s-place?privateServerLinkCode=29443536713818717471407919220012
- https://lsdryfg-xgbjsrdtgh.pages.dev/index.htm
- https://ppss123.shop/
- http://www.newhorizonsrehab.ke/arm/amnd/
- https://suite.zapier.app/
- https://netflix-ui-clone-vikas.vercel.app/login
- https://elettrotecnica-branchi-s-r-l-s.p-s9bbs8qw.workers.dev/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://xml-v4.pushub.net/click?i=i94RKTq92Zc_0 |
| N/A | https://away.vk.ru/away.php?rh=e4739204-4a5b-421c-b5e0-3ea5e9c364c5 |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AaSxoQyQEeCdGiNQploah5nAij7vrMqrlVIHby1Q4v_ARx9kttGkmffM4ARVCnkvjXQyGpUqW4kQNA&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06STGsNF8VPrtJfKj3qidG9aja4ebPwbb3p9TiXusftYSxkZeudKTKZ_ASPNRMww1GRCrQl0CJw&dsh=S3138052%3A1793003440887002 |
| N/A | http://49.51.43.12/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=ASKXGp36_CB8HzfrpuLLHTVjXxiUGDwO6Tj8yz4QrsaGyc3I4H4G7NxTTQJtpw0j07g9O5T5Tx4uyQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06STPQdGYg0_bAp1vgDCsmPl9zePttLYij4pL6WTfQfCeVAq7bm7ObfU2dHAQeM6IRcVCC29PRA&dsh=S1227769386%3A1793002703926386 |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AQMjQ7TPKu6R4w93VRXMPKeD3zeOl4EoNrOdcsDBPMv7m30JK47iKcBvHB2Y608BaGxX8bX4kwt6sA&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06STKcoZ-bAV5cvS1H6OsVKHrNoD83vtIfHAauWs9o1m1twKy04fSeELTc2CSPFOd_MNRMmy5&dsh=S-1945138564%3A1793002547198923 |
| N/A | https://skinsmonkey.com?referrer=pid%3D1%26af_tranid%3DMTYxODc3MjM0ODIxMTkyODY3NzA%3D |
| N/A | https://away.vk.ru/away.php?rh=6d649ba7-9603-4044-9b7d-fbd9893c602d |
| N/A | https://gotodaddymarketplace.weebly.com/ |
| N/A | https://away.vk.ru/away.php?rh=2caa0bb4-f1aa-44b0-b12d-bbe44f17aeee |
| N/A | https://www.att.com/activearmorapp?_branch_match_id=1643176099519264772&utm_source=AT%26T%20App&_branch_referrer=H4sIAAAAAAAAA8soKSkottLXT0wuySxLTSzKzS%2FSzS%2FKTM%2FM00ssKdFLzs%2FV9wtL8U6KLCzzMUqyrytKTUstKsrMS49PKsovL04tsnXOKMrPTQUAZUf3KkgAAAA%3D |
| N/A | https://away.vk.ru/away.php?rh=645a20cb-0058-45ee-a88f-fe705edac568 |
| N/A | https://away.vk.ru/away.php?rh=8b330677-d612-4599-9a12-b8c53bf43948 |
| N/A | https://buffaloorthopaedic.com/content/apwfdmwdim |
| 8.9 | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=ASKXGp0_nbFzdHoBsG_d6znGlWE063OUXUJ-liVgQNfJJB3wA_mip4wV6In-9Cchxtm7MSHwtubxoQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SS30EwxBuil5CEa56D7iGMFG02DVTSKVKB7DVySOjrwu9zp3NZxZPyoRekYJ1qQ2S7Y_bVSCg&dsh=S842072358%3A1793000846811410 |
| N/A | https://flat-bread-04ca.cloudflareaccess.com/cdn-cgi/access/login/vertiv-command-center.pages.dev?kid=617efb6eb0445e77d08421b7c2075c08ed7302463271c62a28d702c82772462a&meta=eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiIsImtpZCI6IjEyY2U5NjlmMDk3YjUyNjliNjllZjA0N2EwMjBiZGI2NGMwMTc5NjMwNzE3MzJhMWJjODg2NjJiNGUxYzJjY2IifQ.eyJ0eXBlIjoibWV0YSIsImF1ZCI6IjYxN2VmYjZlYjA0NDVlNzdkMDg0MjFiN2MyMDc1YzA4ZWQ3MzAyNDYzMjcxYzYyYTI4ZDcwMmM4Mjc3MjQ2MmEiLCJob3N0bmFtZSI6InZlcnRpdi1jb21tYW5kLWNlbnRlci5wYWdlcy5kZXYiLCJyZWRpcmVjdF91cmwiOiIvIiwic2VydmljZV90b2tlbl9zdGF0dXMiOmZhbHNlLCJpc193YXJwIjpmYWxzZSwiaXNfZ2F0ZXdheSI6ZmFsc2UsImV4cCI6MTc5MzAwMTA5NywibmJmIjoxNzkzMDAwNzk3LCJpYXQiOjE3OTMwMDA3OTcsImF1dGhfc3RhdHVzIjoiTk9ORSIsIm10bHNfYXV0aCI6eyJjZXJ0X2lzc3Vlcl9kbiI6IiIsImNlcnRfc2VyaWFsIjoiIiwiY2VydF9pc3N1ZXJfc2tpIjoiIiwiY2VydF9wcmVzZW50ZWQiOmZhbHNlLCJjb21tb25fbmFtZSI6IiIsImF1dGhfc3RhdHVzIjoiTk9ORSJ9LCJyZWFsX2NvdW50cnkiOiJVUyIsImFwcF9zZXNzaW9uX2hhc2giOiJjZTA0ZTIzM2VlODE2MzlkNDA3N2UxYzlkMjI0YWU4ODNjMmEzMDQyNGMyNGRjNmEwYWY5MDJmMzEzOWU1MTZjIn0.YMLF13Erh2-z3rYhKs0ngbh3ymda5pdHOLPLXYarTVoKcJm9oarfJ7B3F1dd6Pn-1_yiI4BkrxPhNfUcIIZSbCazHBX1kLE-L__KvZSoAhUyQGD4Vxte2w9xaj6o6lNSRV3_ls4MRq9zbEO1reK611OXs5jKcHzCCC3u-5XmydlxA6rx8hn2XyW2AVNgKJxZFijxedBlLRuGzPf-FIKOjlCbX2a6CbTk8KivBy0cv1lQUP3jDZRMig2kID0vre5Z0AGINYjJ7e7yRou5da4WvjS5J7Q3E0_4hEZ7XRvE_KddP741EASPKgTv5Jf-Ipe9qM-uUj-00pnuOw85O7a_YA&redirect_url=%2F |
| N/A | https://away.vk.ru/away.php?rh=08faed4d-f748-4193-9aa2-6e01145d921e |
| N/A | https://away.vk.ru/away.php?rh=7dee3de9-af06-4ff1-b204-3f784e1ed34a |
| N/A | https://away.vk.ru/away.php?rh=b672ef3a-65af-40b7-9390-d7570a5aa9d7 |
| N/A | https://away.vk.ru/away.php?rh=2ef0e42a-f4f1-48e1-956f-8bcf79392769 |
| N/A | https://ersfilter-my.sharepoint.com/personal/nradonich_ersfilter_com/_layouts/15/doc.aspx?guestaccesstoken=t6T%2FHN1dKbYHlYX%2BeIMbaZufA43rrGZ6%2FaAAewNocDI%3D&docid=1_18168db23429e45f29fdf2e7be120efc4&wdFormId=%7BB9970F62-44C3-4D09-9929-6E1EB652DA57%7D&action=formsubmit&CID=af1bfbe8-224b-476f-a438-c4b75da21924 |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| bd8eb13b5f944ac4c4a03a22d8c1b574bd02ee4f | QuasarRAT C&C |
| a41e8528d9b464b9620f4cc5900c444f291366e7 | BridgeAgent C&C |
| e6500b535b03160f06f2ca5c663ae180275dbb3b | Vidar C&C |
| 52c7bf8fd5f6312e161c6fe20c68edfa90e137eb | Vidar C&C |
| 6f373dd650805f118832ae3c618d10f0402ea6fe | Vidar C&C |
| f6f18a9147a66682618c0255dd3d376ccbcfed94 | Vidar C&C |
| 882b92d7a268237df18813ca7349fd2092f47618 | DCRat C&C |
| 6d96859790e57d9a9d1acb20ff920a508eb96e1c | PureRAT C&C |
| a331a0dfcaaab84fb90dce85c86841a80db29e88 | PureRAT C&C |
| aa538a850650cd9657359dd49a50229103e3f3dc | Vidar C&C |
| e22f91a1cca032454ef45d769cd9b3374283b2a2 | QuasarRAT C&C |
| cfac3216fbbc990e5c606fa5b6b513f2773df7ab | nullRAT C&C |
| 35661619ef7eb0f46354d9b8a6354a1115e338eb | Vidar C&C |
| f74cfb538bdbd89cd3fbfccd91e6530561d87310 | WARDENStealer C&C |
| f1943fdd37320ad09ea8985e9b86ae33aee4525d | RevStealer C&C |
| 842b7c6b2ac561e7155bfdae757689f50ff6c634 | NetSupport RAT malware distribution |
| 84abb61ca68f4b6b4a7f421516b188dae0516d0f | Vidar C&C |
| 49ee355c74a19712c68535feccf60156ff4055f3 | Vidar C&C |
| f8ac3547b3ec163234ebcb90d325eec86069a42f | Vidar C&C |
| 3c99c5d67f2afafad06b3da29af5d1ab97bf5273 | PureLogsStealer C&C |

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
- 1.10.248.226
- 1.117.73.220
- 1.12.55.80
- 1.14.240.247
- 1.15.106.134
- 1.159.54.33
- 1.162.216.37
- 1.187.214.31
- 1.20.172.162
- 1.203.149.250
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.234.80.94
- 1.235.183.146
- 1.238.106.229
- 1.247.245.61
- 1.250.67.114
- 1.250.67.190

### CINS Army (poorly-rated IPs)
- 1.15.14.29
- 1.177.162.4
- 1.192.129.106
- 1.193.57.144
- 1.221.65.174
- 1.236.221.173
- 1.236.254.202
- 1.24.16.144
- 1.24.16.159
- 1.24.16.172
- 1.24.16.187
- 1.24.16.39
- 1.24.16.46
- 1.24.16.98
- 1.244.184.137
- 1.28.125.52
- 1.30.28.182
- 1.30.80.145
- 1.31.32.6
- 1.32.57.245

## News (last ~36h, across outlets)
### The Hacker News
- [Malicious File in Downloads Folder Tries to Trick AI Coding Agent Into Installing Malware](https://thehackernews.com/2026/10/malicious-file-in-downloads-folder.html)
- [Unpatched Tailscale SSH Flaws Could Let a Hacked Device Reach Root on Other Servers](https://thehackernews.com/2026/10/unpatched-tailscale-ssh-flaws-could-let.html)
- [PHP2Shell Exploitation Attempts Continue Amid Suspected N. Korea Global Scanning Activity](https://thehackernews.com/2026/10/php2shell-exploitation-hits-government.html)
- [OpenAI AI Agents Demonstrate VM Escapes and Secret Cross-Sandbox Communication](https://thehackernews.com/2026/10/openai-ai-agents-demonstrate-vm-escapes.html)

### BleepingComputer
- [AI coding agents hijacked using AGENTS.md file in Downloads folder](https://www.bleepingcomputer.com/news/security/ai-coding-agents-hijacked-using-agentsmd-file-in-downloads-folder/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
_No new items / feed unavailable this run._

### SecurityWeek
- [Former Unit 8200 Officers Raise $34 Million for Agentic SecOps Startup Mave](https://www.securityweek.com/former-unit-8200-officers-raise-34-million-for-agentic-secops-startup-mave/)

### The Record
_No new items / feed unavailable this run._

### Infosecurity Magazine
_No new items / feed unavailable this run._

### CyberScoop
_No new items / feed unavailable this run._

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Monday, October 26th, 2026 https://isc.sans.edu/podcastdetail/10150, (Mon, Oct 26th)](https://isc.sans.edu/diary/rss/33456)
- [YARA-X 1.22.0 Release, (Sun, Oct 25th)](https://isc.sans.edu/diary/rss/33454)

### Securelist (Kaspersky)
_No new items / feed unavailable this run._

### CrowdStrike Blog
- [Obstacles to Weaponizing PHP2Shell Likely Constrain Immediate Widespread Exploitation](https://www.crowdstrike.com/en-us/blog/obstacles-to-weaponizing-php2shell-likely-constrain-exploitation/)
- [Why Organizations Secure AI Agents with Falcon Guardian](https://www.crowdstrike.com/en-us/blog/why-organizations-secure-ai-agents-with-falcon-guardian/)
- [CrowdStrike Protects Customers from Threats Delivered via PHP2Shell](https://www.crowdstrike.com/en-us/blog/crowdstrike-protects-customers-from-php-rce-zero-days/)
- [CrowdStrike Uncovers New Agentic AI Campaigns](https://www.crowdstrike.com/en-us/blog/crowdstrike-uncovers-new-agentic-ai-campaigns/)
- [CrowdStrike Achieves NCSC CIR Enhanced Level Assurance](https://www.crowdstrike.com/en-us/blog/crowdstrike-achieves-uk-ncsc-cir-enhanced-level-assurance/)
- [U.S. Government Disrupts FAMOUS CHOLLIMA Operation with CrowdStrike Assistance](https://www.crowdstrike.com/en-us/blog/fbi-disrupts-famous-chollima-operation-with-crowdstrike-assistance/)
- [October 2026 Patch Tuesday: 1,413 CVEs Include Three Zero-Days and 75 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-october-2026/)
- [CrowdStrike and Anthropic Give Critical Infrastructure Defenders the AI Advantage](https://www.crowdstrike.com/en-us/blog/crowdstrike-anthropic-critical-infrastructure-defense-program/)
- [Solving the Continuous Authorization Conundrum](https://www.crowdstrike.com/en-us/blog/solving-the-continuous-authorization-conundrum/)
- [Unknown Threat Actor Uses AI-Driven ARTEX to Target South Korean Finance](https://www.crowdstrike.com/en-us/blog/unknown-threat-actor-uses-artex-to-target-south-korean-finance/)

### FortiGuard Threat Signal
_No new items / feed unavailable this run._

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal