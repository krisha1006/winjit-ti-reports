# Winjit Daily TI Digest — 2026-11-23

_Auto-generated. Window: last ~24h. Fetched at 2026-11-23T12:02:02.280901+00:00Z_

**At a glance:** 0 new KEV · 35 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-134882 | 10.0 | n/a | A weakness has been identified in TOTOLINK A7100RU 7.4cu.2313_B20191024. This issue affects the function exportOvpn of the file /cgi-bin/cstecgi.cgi of the component CGI Handler. This manipulation of  |
| CVE-2026-120382 | 9.8 | n/a | An improper neutralization of argument delimiters in a command vulnerability in the OAuth API in Synology DiskStation Manager (DSM) before 7.1.1-42962-10, 7.2.1-69057-14, 7.2.2-72806-11, 7.3.2-86009-6 |
| CVE-2026-121613 | 9.8 | n/a | Missing authentication and authorization on an exposed interface allows an unauthenticated remote attacker to send arbitrary commands to the affected component, which can force a device reboot or let  |
| CVE-2026-134804 | 8.8 | n/a | Portainer 2.39.0 before 2.39.9, 2.40.0 before 2.45.4, and 3.0.0 before 3.1.0 contains an authorization bypass vulnerability that allows Standard users to access other users' containers via the WebSock |
| CVE-2026-80466 | 8.8 | n/a | A vulnerability in the Web-Based Management (WBM) routing configuration allows a low-privileged remote attacker to inject shell commands into routing parameters. Due to insufficient input validation,  |
| CVE-2026-134654 | 8.1 | 0.5% | Mailflare before 48957fb contains a host header injection vulnerability in the password-reset request handler that allows unauthenticated attackers to poison reset links when APP_URL is unset. Attacke |
| CVE-2026-134803 | 8.1 | n/a | DBHub before 1.7.0 contains a read-only mode bypass vulnerability that allows MCP clients restricted to readonly execute_sql to run write and DDL statements via backslash-escaped quotes. Attackers can |
| CVE-2026-134814 | 8.1 | n/a | binary-parser before 2.3.1 contains a code injection vulnerability that allows attackers controlling parser definitions to inject JavaScript through string-typed options passed unvalidated by Context. |
| CVE-2026-134815 | 8.1 | n/a | simple-git before 4.1.0 contains an argument injection vulnerability that allows attackers to bypass the allowUnsafePack guard by supplying the --exec option to non-push git operations. Attackers who  |
| CVE-2026-134836 | 8.1 | n/a | Dashy 4.0.0 before 4.9.12 contains a credential disclosure vulnerability in isLocalRequest that attaches user credentials to lookalike hosts due to prefix-only origin checks. Attackers can lure logged |
| CVE-2026-88850 | 8.1 | n/a | The Web-Based Management (WBM) authorization model does not properly enforce permissions for all PROFIBUS configuration operations. A low-privileged remote attacker can abuse an exposed configuration  |
| CVE-2026-135055 | 8.0 | n/a | A flaw was found in the GLib DMA-BUF path of WebKitGTK. The UIProcess trusted fds.size() as the DMA-BUF plane count when handling AcceleratedBackingStore::DidCreateDMABufBuffer and copied offsets and  |
| CVE-2026-134694 | 7.8 | 0.3% | Gammapy through 2.1 contains a code injection vulnerability in WcsGeom.from_header() that passes the WCSSHAPE FITS header card to eval(). Attackers can supply a crafted .fits file with a Python expres |
| CVE-2026-134704 | 7.8 | 0.3% | OpenShot Video Editor (openshot-qt) through 4.1.1 contains an unsafe deserialization vulnerability in ProjectDataStore.load() and read_legacy_project_file() that passes non-JSON project files to pickl |
| CVE-2026-134793 | 7.8 | n/a | Electerm before 5.9.0 on Windows contains an OS command injection vulnerability that allows attackers to execute PowerShell code via crafted file or folder names containing Unicode quote characters. A |
| CVE-2026-134765 | 7.7 | n/a | Kirby 5.0.0 before 5.6.4 contains a race condition in Kirby\Api\Upload::processChunk() that allows authenticated users with upload permission to bypass SVG sanitization. Attackers can race concurrent  |
| CVE-2026-134827 | 7.7 | n/a | Lightdash before 3.212.0 contains an insufficiently protected credentials vulnerability in getGitlabInstallationRepoReadAccess that sends the organization GitLab app token to unverified hosts. Project |
| CVE-2026-134679 | 7.5 | 0.5% | WeddingShare through 1.8.2 contains a missing authorization vulnerability in the anonymous MediaViewerController.GalleryItem action that allows unauthenticated attackers to retrieve item upload paths  |
| CVE-2026-134808 | 7.5 | n/a | Gogs before 0.14.4 on Windows contains a path equivalence vulnerability in isRepositoryGitPath that allows authenticated users with write access to bypass .git directory protection using NTFS aliases. |
| CVE-2026-134812 | 7.5 | n/a | msgpackr before 2.1.4 contains an inefficient algorithmic complexity vulnerability that allows remote attackers to cause denial of service by repeatedly re-decoding buffered incomplete values. Attacke |
| CVE-2026-134813 | 7.5 | n/a | Faye websocket-driver 0.5.0 before 0.8.0, permessage-deflate before 0.2.0, and websocket-extensions before 0.2.0 contain a decompression bomb vulnerability because messages are fully inflated before m |
| CVE-2026-134821 | 7.5 | n/a | Gunicorn 25.2.0 before 27.0.0 contains a memory exhaustion vulnerability in the pure-Python ASGI HTTP/1 parser that buffers protocol lines without size limits. Unauthenticated remote attackers can sen |
| CVE-2026-134830 | 7.5 | n/a | Casdoor before 4.27.1 contains an uncontrolled resource consumption vulnerability in decodeSamlMessage that allows unauthenticated attackers to exhaust memory by sending unbounded DEFLATE-compressed S |
| CVE-2026-134838 | 7.4 | n/a | Weblate before 2026.11 contains an account takeover vulnerability in the reset_password view that allows unauthenticated attackers to reset victim passwords by abusing case-insensitive Unicode e-mail  |
| CVE-2026-134541 | 7.3 | 0.4% | A vulnerability was detected in Surya2Developer Online Shopping System 1.0. This impacts an unknown function of the file product.php of the component GET Parameter Handler. Performing a manipulation o |
| CVE-2026-134623 | 7.3 | 0.6% | A flaw has been found in Microweber up to 2.0.20. This impacts the function UserManager::make_logged of the file src/MicroweberPackages/App/Http/Controllers/ApiController.php of the component Generic  |
| CVE-2026-134826 | 7.3 | n/a | erxes before 3.4.14 contains a missing authentication vulnerability in the insurance_api plugin that allows unauthenticated attackers to create, overwrite or delete contract templates via GraphQL muta |
| CVE-2026-134789 | 7.3 | n/a | A weakness has been identified in DumbWareio DumbAssets up to 1.0.11. Affected by this vulnerability is an unknown functionality of the file server.js of the component Settings API. Executing a manipu |
| CVE-2026-134850 | 7.3 | n/a | A security vulnerability has been detected in aceberg WatchYourLAN up to 2.1.4. Affected by this issue is the function getPortState of the file backend/internal/api/api-network.go of the component Web |
| CVE-2026-134851 | 7.3 | n/a | A vulnerability was detected in leonkhoo123 self-hosting-file-uploader up to 473e38ff8fba494f33a485730c6d95c5d8c536ea. This affects an unknown part of the file routes/generator.js of the component Adm |
| CVE-2026-134885 | 7.3 | n/a | A flaw has been found in osCommerce up to 4.14.63493. The impacted element is the function actionSuccess of the file lib/frontend/controllers/MultisafeController.php of the component MultiSafepay Paym |
| CVE-2026-134887 | 7.3 | n/a | A vulnerability was found in osCommerce 4.14.63493. This impacts the function get_address_book_data of the file lib/common/helpers/Customer.php of the component Account Address List Widget. The manipu |
| CVE-2026-134543 | 7.1 | 1.4% | A flaw has been found in jprocms up to 1.7.7. Affected is the function StrUtil.format of the component Database Backup Module. Executing a manipulation of the argument host/port/username/password/dbNa |
| CVE-2026-134817 | 7.1 | n/a | mcp-server-kubernetes before 4.2.0 contains an argument injection vulnerability that allows remote MCP clients to inject kubectl flags by supplying dash-prefixed values as positional operands in tools |
| CVE-2026-134753 | 7.0 | n/a | dsniff through 2.5a2 contains an integer underflow in decode_sniffer() in decode_sniffer.c that allows unauthenticated remote attackers to write past the global obuf buffer. Attackers can send a UDP d |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-f586-4fpx-57j5 | CVE-2026-93584 | high | An SQL injection vulnerability in OTRS versions 2024.3.1 through 2026.8.1 allows unauthenticated... |
| GHSA-fc2r-pmxp-5649 | CVE-2026-134882 | critical | A weakness has been identified in TOTOLINK A7100RU 7.4cu.2313_B20191024. This issue affects the... |
| GHSA-gwgx-vvmw-r849 | CVE-2026-115903 | high | An authenticated attacker must reach the Edge file APIs through the Leader or directly on an Edge... |
| GHSA-qj57-385p-pjwm | CVE-2026-115901 | high | Exploitation requires an identity admitted to a configured trusted IdP application, control of... |
| GHSA-q3gv-f294-5h8g | CVE-2026-115900 | high | An attacker must possess a valid Worker distribution credential, reach the Leader distribution... |
| GHSA-64cr-3c3r-jwwg | CVE-2026-115899 | critical | An attacker must control pagination data returned by an upstream API or service queried by an... |
| GHSA-wmj6-rqhf-hx9q | CVE-2026-115873 | high | A remote attacker must authenticate with Read Only (GroupRead) access to at least one Worker... |
| GHSA-4p88-4hgh-4356 | CVE-2026-134935 | high | The dell-xps-touchpad-haptics package before 1.0.0-4 for Omarchy allows local users to change... |
| GHSA-8jpj-fc6r-3gp2 | CVE-2026-121456 | medium | A privilege escalation vulnerability in the Axivion Suite ApiToken permission restriction for... |
| GHSA-3fp6-8qqh-qxxv | CVE-2026-118887 | medium | ZTE Z80 Ultra is affected by an unauthorized access vulnerability. Successful exploitation of... |
| GHSA-q23h-g4w3-g629 | CVE-2026-120382 | critical | An improper neutralization of argument delimiters in a command vulnerability in the OAuth API in... |
| GHSA-c6fv-g5m5-h65q | CVE-2026-115232 | low | In iceoryx2 versions from 0.6.0 to 0.10.0, The C API getters that copy a service's hash into a... |
| GHSA-89cx-257v-m5h7 | CVE-2026-134881 | low | A security flaw has been discovered in HuLaSpark HuLa up to 3.0.9. This vulnerability affects the... |
| GHSA-65v7-5m96-v7xg | CVE-2026-134856 | low | A vulnerability was identified in Snes9x up to 1.63. The impacted element is the function... |
| GHSA-qch6-gxwx-xj8h | CVE-2026-121480 | medium | Insufficient authorization in personal notification rules in Checkmk <2.5.0p20, <2.4.0p41 and 2.3... |
| GHSA-w6mx-hmm2-pqqr | CVE-2026-134855 | medium | A vulnerability was determined in kchapelier qoijs 1.0.0. The affected element is the function... |
| GHSA-8252-hc65-7rfp | CVE-2026-134853 | medium | A vulnerability has been found in vthibault tga-js up to 1.1.1. This issue affects the function... |
| GHSA-wr2v-vp5g-4qx7 | CVE-2026-134852 | medium | A flaw has been found in shaozilee bmp-js up to 0.1.0. This vulnerability affects the function... |
| GHSA-j5mc-v362-2pvq | CVE-2026-134854 | medium | A vulnerability was found in andreasgal node-wav up to 0.0.2. Impacted is the function decode of... |
| GHSA-c2hp-546m-qfw8 | CVE-2026-134851 | medium | A vulnerability was detected in leonkhoo123 self-hosting-file-uploader up to... |
| GHSA-8h9j-ccm7-xgpv | CVE-2026-134850 | medium | A security vulnerability has been detected in aceberg WatchYourLAN up to 2.1.4. Affected by this... |
| GHSA-9xpw-fv9v-23qj | CVE-2026-134788 | medium | A security flaw has been discovered in warpdesign pcx-js up to 1.1.1. Affected is the function... |
| GHSA-c2p3-59hh-mw67 | CVE-2026-134789 | medium | A weakness has been identified in DumbWareio DumbAssets up to 1.0.11. Affected by this... |
| GHSA-9rm3-rg57-8xwc | CVE-2026-134784 | medium | A vulnerability was found in DumbWareio DumbDrop up to ff8f813f493e89c7da056e7a3101ce2ef48e3960.... |
| GHSA-6jqh-jhgv-944q | CVE-2026-134785 | medium | A vulnerability was identified in Bagisto MangoPay Payment Gateway up to... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| University Medical Imaging | Aoqin | US | 2026-11-23T06:51:04.406635+00:00 |
| Corrigan Moving Systems | Aoqin | US | 2026-11-23T06:50:30.750172+00:00 |
| kinkisharyo.com | everstake | JP | 2026-11-23T06:29:20.178264+00:00 |
| MASTER RESULT SOLUÇÕES CONTÁBEIS LTDA | spacebears | BR | 2026-11-23T04:44:15.092794+00:00 |
| Digital Instruments & Control Systems (DICS) | spacebears |  | 2026-11-23T04:43:36.606324+00:00 |
| Staufen Baumaschinen GmbH | spacebears | DE | 2026-11-23T04:42:57.027196+00:00 |
| www.suzlon.com | blackout | IN | 2026-11-23T04:24:56.437133+00:00 |
| Company #268 | N0n | US | 2026-11-23T04:11:39.875512+00:00 |
| Company #267 | N0n | GB | 2026-11-23T04:11:00.467617+00:00 |
| Company #266 | N0n | US | 2026-11-23T04:10:21.021055+00:00 |
| Company #265 | N0n | FR | 2026-11-23T04:09:41.281286+00:00 |
| Company #264 | N0n | US | 2026-11-23T04:09:02.519022+00:00 |
| Company #263 | N0n | US | 2026-11-23T04:08:23.163824+00:00 |
| Company #262 | N0n | DK | 2026-11-23T04:07:44.552976+00:00 |
| Company #261 | N0n | US | 2026-11-23T04:07:05.547549+00:00 |
| Company #260 | N0n |  | 2026-11-23T04:06:26.023343+00:00 |
| Company #259 | N0n | IL | 2026-11-23T04:05:46.438009+00:00 |
| Company #258 | N0n | US | 2026-11-23T04:05:02.693159+00:00 |
| Company #257 | N0n |  | 2026-11-23T04:04:24.179543+00:00 |
| Company #256 | N0n | US | 2026-11-23T04:03:44.623317+00:00 |

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
| 18.218.118.203 | 9 |
| 45.148.10.61 | 9 |
| 62.60.130.148 | 9 |
| 77.239.124.181 | 9 |
| 77.239.124.252 | 9 |
| 193.32.162.15 | 9 |
| 193.187.110.158 | 9 |
| 3.129.187.38 | 8 |
| 35.210.88.112 | 8 |
| 46.151.178.14 | 8 |
| 62.60.130.219 | 8 |
| 64.62.197.17 | 8 |
| 64.62.197.92 | 8 |
| 64.62.197.197 | 8 |
| 66.132.172.217 | 8 |
| 66.132.186.204 | 8 |
| 66.132.195.48 | 8 |
| 66.132.195.107 | 8 |
| 66.132.195.210 | 8 |
| 66.132.224.229 | 8 |

### OpenPhish (live phishing URLs)
- http://www.shopeeid79.blogspot.com/
- http://www.facebook-source.blogspot.com/
- https://melodious-figolla-db551d.netlify.app/
- http://infinix02882.square.site/
- https://facebook-247-support.blogspot.com/
- https://steamconmmunity.life/profile/7655462238669691
- http://sp28ct11-rumvani-biz-zemkaro.pages.dev/
- https://php-code2000.info/lum
- http://centerproxc.xyz/
- https://jlu.evgom.shop/
- https://mid6gg.eventzones.de/
- https://aprovesecenter.com/
- https://www.facebooklogin01.blogspot.com/
- http://www.88ehs.tenantid472384782.sbs/
- https://mercadolivre-mobile.217-77-5-150.sslip.io/
- https://badenwuerttemberg.info/
- https://www.jlgenfekjlfnvtgpegkwr.xyz/
- https://www.noticeofpleadings.net/amadey/domainseizurenotice.htm
- http://www.ultimateamplifier.world/
- https://spf66.com/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://a1b4f5c5c5.mktsuporte.com/conviteaeternum.html?MKT-adielmachado@icloud.com |
| N/A | https://secure-xserver-28110-paymentlink.horschamp.info/ |
| N/A | https://maxis-ly.biz.id/max |
| N/A | https://secure-xserver-55751-paymentlink.horschamp.info/ |
| N/A | https://streamingsprimes.com/captcha |
| N/A | https://secure-xserver-95587-paymentlink.horschamp.info/ |
| N/A | https://seguro.portalfinanceiro.org/ |
| N/A | https://dash.lbpiaccessmobile.com/ |
| 7.3 | https://brt.pics/it/ |
| 6.9 | https://group-brt.cc/it/ |
| 7.2 | https://matsui-ousy.cfd/review/j7E2CqUO |
| 6.6 | https://62d71531.shuangtoushe.net/ab5ff490 |
| 7.5 | https://allegrolokalnie.pl-ogloszenie483926047.cfd |
| 7.7 | http://allegrolokalnie.postoffer.cyou/ |
| 7.7 | http://allegrolokalnie.oferta38be29o8bwg38.cfd/ |
| 7.8 | https://f3c670e0.guangtui.net/db4e0255 |
| 7.2 | https://matsui-drua.cfd/review/alAqi17u |
| 7.2 | https://matsui-cpld.cfd/review/LtRuy1VJ |
| 6 | https://tplzb.com |
| 8.3 | https://recarga-jogo-garena-rho.vercel.app/ |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| ab8211e3a654f89353a344533a5ca66b1a60cf1c | Vidar C&C |
| 0d0d5cce18a498f7bd05f3b585fb73eacb1cf86b | Vidar C&C |
| ada4baf8f036019aaa197a7a8caa41f48d263490 | Malware C&C |
| 1f2d77381dd6a71a09ca621790b98506cd065667 | Malware C&C |
| fcff16dcbf0ee69046510e2701339fd1bcf80743 | ACRStealer C&C |
| 0e4d5b46dd2f307b6826ee0e1810aa4bc3dffda4 | Vidar C&C |
| 6104164ecfcc61a632111609af160f303f81f94b | OffLoader C&C |
| 079fa441563a8de8d3ed486126a310418e3b1846 | Vidar C&C |
| fccef6bf642cf2cf648562817b24f7eadc89bd08 | ACRStealer C&C |
| df20056c51a28bd1401b9108edbddb7120cee489 | Vidar C&C |
| d58ed8869a314b2d52697142cc8d9d3762318190 | Vidar C&C |
| 7b300d4e1d68c65b07fecb53031c40f91f965a0f | WARDENStealer C&C |
| c8daa804756c213ecc0d8f48e4231765ad1914f4 | Vidar C&C |
| 963ff7dc4fd9d851ba7c7a3da113a1091a9582b3 | Vidar C&C |
| e8fd09728405f4135a200e7adf15303dfa8cbf35 | Vidar C&C |
| 8602c6e50940880e8f3ba1d9f53ad97b481c1617 | Malware distribution |
| d66a7599fc875b9ca6633470adadfa8cc5b9c04f | Malware C&C |
| 391c96cd00389c4b285f60567adb3a3531009fc9 | Malware C&C |
| b80e467af83941a4aa1ebfd18d737059e6ade74f | Malware C&C |
| c333a3d828305b2a8f6d4f5646774ee30f0be065 | OffLoader C&C |

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
- 1.13.79.149
- 1.14.140.218
- 1.146.113.188
- 1.162.242.67
- 1.192.216.175
- 1.194.211.36
- 1.203.149.250
- 1.209.148.143
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.234.27.159
- 1.235.183.146
- 1.235.192.214
- 1.238.106.229
- 1.247.245.61
- 1.250.67.114
- 1.250.67.190

### CINS Army (poorly-rated IPs)
- 1.14.3.170
- 1.15.14.29
- 1.170.200.20
- 1.177.162.2
- 1.189.41.213
- 1.192.129.106
- 1.193.100.138
- 1.197.248.101
- 1.20.151.114
- 1.204.35.156
- 1.208.108.242
- 1.24.16.102
- 1.24.16.113
- 1.24.16.116
- 1.24.16.136
- 1.24.16.151
- 1.24.16.157
- 1.24.16.167
- 1.24.16.170
- 1.24.16.173

## News (last ~36h, across outlets)
### The Hacker News
- [Hackers Exploit Critical ASP.NET Anti-CSRF Library Flaw Allowing Unauthenticated RCE](https://thehackernews.com/2026/11/hackers-exploit-critical-aspnet-anti.html)
- [Hackers Exploited GL.iNet Cloud Flaw to Install Malware on Routers and KVM Devices](https://thehackernews.com/2026/11/hackers-exploited-glinet-cloud-flaw-to.html)
- [AI-Assisted Cyberattacks Trigger Unauthorized Payments at Indian Banks and Fintech Firms](https://thehackernews.com/2026/11/ai-assisted-cyberattacks-trigger.html)
- [OpenRouter Drops 3 Providers After Researchers Catch Months of Prompt Theft at AI Hosting Firms](https://thehackernews.com/2026/11/openrouter-drops-3-providers-after.html)
- [Researchers Demonstrate Ghostscript Sandbox-Escape RCE via Crafted File Uploads in Popular Apps](https://thehackernews.com/2026/11/researchers-demonstrate-ghostscript.html)

### BleepingComputer
- [Microsoft confirms Windows printing issues affecting Forcepoint users](https://www.bleepingcomputer.com/news/microsoft/microsoft-confirms-printing-issues-after-kb5132043-windows-hotpatch/)
- [CISA flags critical Cisco RCE flaw as actively exploited in attacks](https://www.bleepingcomputer.com/news/security/cisa-flags-critical-cisco-expressway-rce-flaw-as-actively-exploited/)
- [Hackers exploit GL.iNet cloud flaw to infect routers, KVM devices](https://www.bleepingcomputer.com/news/security/hackers-exploit-glinet-cloud-flaw-to-infect-routers-kvm-devices/)
- [Cleverbridge warns hackers stole credit card numbers, CVVs in data breach](https://www.bleepingcomputer.com/news/security/cleverbridge-warns-hackers-stole-credit-card-numbers-cvvs-in-data-breach/)
- [Signal to block Siri, Gemini AI from capturing chats on iOS, Android](https://www.bleepingcomputer.com/news/security/signal-to-block-siri-gemini-ai-from-capturing-chats-on-ios-android/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
_No new items / feed unavailable this run._

### SecurityWeek
- [BadBox 3.0 Ad Fraud Operation Generating 40 Billion Daily Bid Requests Disrupted](https://www.securityweek.com/badbox-3-0-ad-fraud-operation-generating-40-billion-daily-bid-requests-disrupted/)
- [SAP NetWeaver, Cisco Expressway Flaws Exploited in Attacks](https://www.securityweek.com/sap-netweaver-cisco-expressway-flaws-exploited-in-attacks/)
- [CrowdStrike to Acquire Zscaler in $43.9 Billion Deal](https://www.securityweek.com/crowdstrike-to-acquire-zscaler-in-43-9-billion-deal/)
- [FBI Investigating Apparent Hack of Its Key National Criminal Justice Database, AP Source Says](https://www.securityweek.com/fbi-investigating-apparent-hack-of-its-key-national-criminal-justice-database-ap-source-says/)

### The Record
_No new items / feed unavailable this run._

### Infosecurity Magazine
- [Cleverbridge Confirms Customers’ Payment Card Data Breached](https://www.infosecurity-magazine.com/news/cleverbridge-payment-card-breached/)
- [Critical Cisco Expressway Flaw Exploited in Attacks](https://www.infosecurity-magazine.com/news/critical-cisco-expressway-flaw/)
- [Badbox Returns to Spread Ad Fraud and Proxyjacking Payloads](https://www.infosecurity-magazine.com/news/badbox-spread-ad-fraud/)

### CyberScoop
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
- [ISC Stormcast For Monday, November 23rd, 2026 https://isc.sans.edu/podcastdetail/10190, (Mon, Nov 23rd)](https://isc.sans.edu/diary/rss/33548)
- [A brief history of syslog timestamps, (Sun, Nov 22nd)](https://isc.sans.edu/diary/rss/33530)

### Securelist (Kaspersky)
- [Black Friday, red flags: too-good-to-be-true deals hiding real threats](https://securelist.com/black-friday-threat-report-2026/122061/)

### CrowdStrike Blog
- [Java4Shell (CVE-2026-114938): CrowdStrike Detects Exposure and Post-Exploitation Activity](https://www.crowdstrike.com/en-us/blog/crowdstrike-helps-protect-against-java4shell-cve-2026-114938/)
- [NGINX2Root: Identify and Protect with the CrowdStrike Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-helps-protect-against-nginx2root-cve-2026-123007/)
- [CrowdStrike Brings the Human Advantage to AI Detection and Response](https://www.crowdstrike.com/en-us/blog/crowdstrike-brings-human-advantage-aidr/)
- [CrowdStrike Is Building the Engine of the Agentic SOC with Falcon Next-Gen SIEM](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-gartner-mq-siem/)
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