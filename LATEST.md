# Winjit Daily TI Digest — 2026-10-19

_Auto-generated. Window: last ~24h. Fetched at 2026-10-19T08:39:00.013730+00:00Z_

**At a glance:** 0 new KEV · 17 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-111998 | 9.8 | n/a | Vanus 0.8.0 through 0.9.0 contains a default credentials vulnerability that allows unauthenticated remote attackers to gain cluster-admin access by using the hardcoded admin token. Attackers can send  |
| CVE-2026-16487 | 8.1 | n/a | A flaw was found in bootc when operating with the default containers signature policy. Automatic or manual upgrades of a mutable image tag may apply unsigned content for registries that fall through t |
| CVE-2026-112005 | 7.7 | n/a | WhoDB 0.104.0 before 0.135.0 contains a path traversal vulnerability that allows remote attackers to read and write arbitrary host files by running DuckDB filesystem functions through the query editor |
| CVE-2026-112000 | 7.6 | n/a | Vanus 0.8.0 through 0.9.0 contains a missing authorization vulnerability in the gateway that allows any authenticated user to call Subscribe, Ack, and unregistered methods without permission checks. A |
| CVE-2026-111999 | 7.5 | n/a | Vanus 0.8.0 through 0.9.0 contains a missing authentication vulnerability that allows unauthenticated remote attackers to publish events to any eventbus through the gateway CloudEvents HTTP receiver.  |
| CVE-2026-112021 | 7.5 | n/a | snac2 before 2.93 contains a heap-based buffer overflow vulnerability in _xs_json_load_lexer() that allows unauthenticated remote attackers to corrupt heap memory by sending JSON strings containing a  |
| CVE-2026-112082 | 7.5 | n/a | A vulnerability was identified in sgl-project SGLang up to 0.5.19. This impacts the function Scheduler.expert_distribution_handle of the file python/sglang/srt/eplb/expert_distribution.py of the compo |
| CVE-2026-16460 | 7.4 | n/a | A flaw was found in bootc and ostree. Already-staged deployments are finalized without revalidating the deployment's container image against the current containers signature policy. Unsigned OS conten |
| CVE-2026-111866 | 7.3 | 0.4% | A weakness has been identified in nemoTyrant manong up to 7c9e5228e133b9267ad3a415833bc9bb53193bb4. This impacts the function cache/del_cache/arr2sql of the file func.php. This manipulation causes sql |
| CVE-2026-111871 | 7.3 | 0.3% | A weakness has been identified in itsmeravitejak Online-Examination-System up to e6208e630b14657999bbfe4c9912302d2a1e2449. The impacted element is an unknown function of the file qsdb/usersdb/brandb/t |
| CVE-2026-111872 | 7.3 | 0.3% | A security vulnerability has been detected in itsmeravitejak Online-Examination-System up to e6208e630b14657999bbfe4c9912302d2a1e2449. This affects the function MySQLDB::valid/MySQLDB::getresults/MySQ |
| CVE-2026-111873 | 7.3 | 0.3% | A vulnerability was detected in itsmeravitejak Online-Examination-System up to e6208e630b14657999bbfe4c9912302d2a1e2449. This impacts the function MySQLDB::topicslist of the file exammanger.php of the |
| CVE-2026-111990 | 7.3 | n/a | A weakness has been identified in kishan0725 Hospital Management System up to 777fda46b77a820977a5ba616283dbfbc40bf7e1. This affects the function mysqli_query of the file admin-panel.php of the compon |
| CVE-2026-112025 | 7.3 | n/a | A weakness has been identified in light0011 cms c774dce31c6df0055568a8d5c53d964d99be199d/f72cf46f601efb2a0618c3814cc2f61380b38930. This impacts an unknown function of the file App/Home/Controller/User |
| CVE-2026-112044 | 7.3 | n/a | A security vulnerability has been detected in dotnet eShop up to 913acea66708a59595351174cee9b29f37179d29. The affected element is the function AddApplicationServices of the file src/Catalog.API/Exten |
| CVE-2026-112001 | 7.2 | n/a | ProjectSend 2.0.0 before 2.7.0 contains an incorrect authorization vulnerability that allows restricted API token holders to change the token owner's credentials via PATCH /api/v1/users/{user}. Attack |
| CVE-2026-112018 | 7.0 | n/a | cgltf through 1.15 contains a heap out-of-bounds write vulnerability in cgltf_accessor_unpack_floats() that allows attackers to write outside the output buffer via unchecked sparse accessor indices. A |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-5ch2-2phm-jp6x | CVE-2026-91046 | unknown | The ElementsReady Addons for Elementor WordPress plugin through 6.7.2 does not perform... |
| GHSA-3mqp-qxqh-qqq6 | CVE-2026-89286 | unknown | The FormFlow for GoHighLevel (GHL)  WordPress plugin through 1.0.0 does not restrict access to a... |
| GHSA-9cr7-6wq5-54c2 | CVE-2026-91047 | unknown | The ElementsReady Addons for Elementor WordPress plugin through 6.7.2 does not properly restrict... |
| GHSA-qrcf-6rx9-2mwc | CVE-2026-94273 | unknown | The Snap Finance WordPress plugin through 3.11.0 does not verify that the payment provider's... |
| GHSA-g4wc-qgxw-hw24 | CVE-2026-112081 | low | A vulnerability was determined in hankcs HanLP up to 2.1.0-beta.64. This affects the function... |
| GHSA-hqw5-mw82-chh2 | CVE-2026-112083 | medium | A security flaw has been discovered in sgl-project SGLang up to 0.5.19. Affected is the function... |
| GHSA-4pfr-64r8-wffh | CVE-2026-76739 | medium | A potential security vulnerability in HPE Compute Scale-up Server 3200 and 3250 platforms and... |
| GHSA-j823-x22q-54wf | CVE-2026-112082 | high | A vulnerability was identified in sgl-project SGLang up to 0.5.19. This impacts the function... |
| GHSA-753r-w3pv-4492 | CVE-2026-106933 | unknown | The Blaze Demo Importer WordPress plugin before 1.0.17 does not sanitize uploaded SVG files and... |
| GHSA-v5q2-hr9p-q4jv | CVE-2026-112086 | low | A vulnerability was found in ESPnet up to 202610.post2. This affects the function build_model of... |
| GHSA-66j5-6c8v-q8pj | CVE-2026-16487 | high | A flaw was found in bootc when operating with the default containers signature policy. Automatic... |
| GHSA-3mcp-jg87-j7wj | CVE-2026-106028 | unknown | The ActiveTrail for WooCommerce WordPress plugin through 1.2.6 does not perform any authorization... |
| GHSA-x2f6-pg54-586w | CVE-2026-112077 | medium | A vulnerability was detected in radareorg radare2 6.2.0/6.2.2. This issue affects the function... |
| GHSA-2pfr-4hx7-3p8p | CVE-2026-108121 | medium | Brian Mariani from DigitalCanion SA has discovered a  vulnerability in the domain creation... |
| GHSA-4573-j266-gqm9 | CVE-2026-106014 | unknown | The Gateway for Vantiv on WC WordPress plugin through 1.0.1 does not verify the authenticity of... |
| GHSA-fmj9-5fq7-mvjg | CVE-2026-112075 | low | A weakness has been identified in unslothai unsloth up to 0.1.501-beta. This affects the function... |
| GHSA-wj5h-2j88-93vj | CVE-2026-108120 | high | Brian Mariani from DigitalCanion SA has discovered a path traversal vulnerability in the View... |
| GHSA-g899-4284-8gqj | CVE-2026-112076 | low | A security vulnerability has been detected in alexta69 MeTube up to 2026.09.28. This... |
| GHSA-2p28-j54x-gv38 | CVE-2026-112080 | low | A vulnerability was found in LlamaChinese Llama-Chinese up to... |
| GHSA-q7j8-9vmr-j8qv | CVE-2026-112079 | low | A vulnerability has been found in hankcs HanLP up to 2.1.0-beta.64. The affected element is the... |
| GHSA-mgjw-qc2q-q7rc | CVE-2026-112078 | low | A flaw has been found in RVC-Project Retrieval-based-Voice-Conversion-WebUI up to 2.3.260718.... |
| GHSA-8m72-m8r9-85xc | CVE-2026-112074 | low | A security flaw has been discovered in Tencent ncnn up to... |
| GHSA-65cq-6v82-827q | CVE-2026-112045 | low | A vulnerability was detected in donetick up to 0.1.82. The impacted element is the function... |
| GHSA-fx59-v8wm-992x | CVE-2026-112073 | low | A vulnerability was identified in Tencent ncnn up to 44b02dabdcf97499281a4692ebd65bad73dcf8b6.... |
| GHSA-4fmq-r5rm-vvmw | CVE-2026-111440 | high | 在 openGauss-connector-jdbc 的 pgjdbc/src/main/java/org/postgresql/log/LogFactory.java 中，LogFactory... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| American Campus | Helix | US | 2026-10-19T02:23:57.872260+00:00 |
| Finzly Corp | N0n | US | 2026-10-19T01:23:07.372995+00:00 |
| Company #93 | N0n | US | 2026-10-19T00:22:49.507679+00:00 |
| Amagi Media Labs | N0n | US | 2026-10-18T22:24:38.779390+00:00 |
| Belcorp | qilin | PE | 2026-10-18T21:05:22.505062+00:00 |
| Company #92 | N0n | KR | 2026-10-18T20:25:29.647385+00:00 |
| ********rta.ch | cloak | CH | 2026-10-18T19:06:57.588367+00:00 |
| dac********er.de | cloak | DE | 2026-10-18T19:06:17.465564+00:00 |
| Telecom Egypt | N0n | EG | 2026-10-18T17:29:31.228669+00:00 |
| All Business Technologies (Fox Hill bookkeeping and tax practice) | N0n |  | 2026-10-18T17:28:49.429792+00:00 |
| SMIC US Company (Sunnyvale, CA — US arm of Semiconductor Manufacturing International Corpo... | N0n | US | 2026-10-18T16:27:05.221579+00:00 |
| Llano Independent School District | qilin | US | 2026-10-18T13:49:38.734560+00:00 |
| mckenneys | iah6477 | US | 2026-10-18T12:37:04.785040+00:00 |
| Pengurusan Aset Air Berhad | qilin | MY | 2026-10-18T09:47:41.943906+00:00 |
| Company #91 | N0n | US | 2026-10-18T08:54:33.702640+00:00 |
| Southwire | Helix | US | 2026-10-18T07:51:55.572286+00:00 |
| Luzco Ilumination | emperador |  | 2026-10-18T06:52:23.198824+00:00 |
| Company #90 | N0n | US | 2026-10-18T05:53:23.391515+00:00 |
| Company #89 | N0n | US | 2026-10-18T05:52:48.574994+00:00 |
| Quikrete | Helix | US | 2026-10-18T02:51:45.862874+00:00 |

## IOCs
### ThreatFox (recent, abuse.ch)
| Indicator | Type | Malware |
|---|---|---|
| f0924944e502148d001e043b96981c621a65f0d4ea0c68cef26355936ae48340 | sha256_hash | osx.amos |
| 8c0137506ab7d5fc2ab411acdbc8f729399027568c5fc892371e5d89edb6897d | sha256_hash | osx.amos |
| c77e8254819e19bf277948537724fdd2fa90f45fbc81d342c688432228282b89 | sha256_hash | osx.amos |
| 2aba880c132444d0a53e56ea03bdeede3aec3272d233cb33497a1f556a52cbe5 | sha256_hash | osx.amos |
| 23.132.164.15:14641 | ip:port | win.remcos |
| ceec6321dc3dbf2e1515bb53602bc278afa47b472f260f9bcdd109c5ad0052d4 | sha256_hash | osx.amos |
| google-proxy-66-249-88-66.google.com | domain | php.shin_webshell |
| e0f6754b62b957cda8188934366f173aa9bb8ed2beda8f3d668f9c881835a5e8 | sha256_hash | osx.amos |
| 9f9260dee736434e780d2fa6b6651c3c057b3df5 | sha1_hash | win.quasar_rat |
| 155553264e98d58b0eaa075b1c3087f6 | md5_hash | win.quasar_rat |
| 6163e1ca729d7127b4aa03d14ae02a8002da7aad | sha1_hash | osx.electro_rat |
| 1cf92442d8c4a6cc5535f8b450cf988f | md5_hash | osx.electro_rat |
| 8a442fc7e166b0af2eb74fad903cfb85151c5b8f86e994c037692a7b5b298049 | sha256_hash | win.quasar_rat |
| 6042742e42d85ca13bbd59fbab8837decc03bf2e | sha1_hash | win.quantloader |
| 1469bd018fe2f6a6cd975ba9c5e071e4 | md5_hash | win.quantloader |
| 63a58a8d5cce2d17a2818f47e8c23ac080b6d4314369b56f31f2ad65f09384cf | sha256_hash | osx.electro_rat |
| 983ae998708cc2fe3c553d09cd79cbf9c6b47ad5 | sha1_hash | elf.elevator |
| be5be4192d2df4114d39001d35f7c11f | md5_hash | elf.elevator |
| 0059a3866d1902467dd4fe64108aefd5c7fd2856a794a251c2b28004a92257b9 | sha256_hash | win.quantloader |
| 81202b83f9feb76cb7923c1a70a3da35 | md5_hash | win.quantloader |

### URLhaus (recent malicious URLs, abuse.ch)
| URL | Threat | Status |
|---|---|---|
| http://115.62.156.114:34880/i | malware_download | online |
| http://110.186.231.245:41695/i | malware_download | online |
| http://103.210.144.11/jireyrsdnf/bestwegot.sh | malware_download | offline |
| http://110.186.231.245:41695/bin.sh | malware_download | online |
| http://59.96.136.108:46282/bin.sh | malware_download | online |
| http://182.119.199.112:45841/i | malware_download | online |
| http://182.113.195.83:60679/i | malware_download | online |
| http://42.5.58.30:49850/i | malware_download | online |
| http://42.233.211.139:32917/i | malware_download | online |
| http://103.171.168.74:45242/i | malware_download | online |
| http://115.53.209.120:41356/bin.sh | malware_download | online |
| http://125.43.125.69:42510/i | malware_download | online |
| http://115.48.151.23:49308/bin.sh | malware_download | online |
| http://23.160.56.123/1531 | malware_download | offline |
| http://27.216.174.183:52609/bin.sh | malware_download | online |
| http://23.160.56.223/p.sh | malware_download | offline |
| http://27.216.174.183:52609/i | malware_download | online |
| http://123.4.251.57:35535/i | malware_download | online |
| http://42.55.63.35:56286/i | malware_download | offline |
| http://42.58.166.36:55052/i | malware_download | online |

### MalwareBazaar (recent samples, abuse.ch)
| SHA256 | File type | Signature |
|---|---|---|
| 3db1e114a5585f371b675171657d6d4fcb7c0fe78ee1ce7e8af8819b34516dcd | adrian__luca | AgentTesla |
| 52f1da7d0119637e2e62f336bae62b192fdd1a35b6c3001f8d1beec47d035920 | abuse_ch | Mirai |
| 964f99b5118c28d52119909a3d803dd61c8634b1703d817e0b66829839d65990 | abuse_ch | Mirai |
| 757aa87619f7780f889b7fb0b5b03498d34db882d792c7ac92e597ec578efcc9 | abuse_ch | Mirai |
| 565cc01c993cdf753154593f16c104e5729f436243649237d1a36cf2100a74e2 | abuse_ch | Mirai |
| 191c0859e16a94f0188276105ba5d1c07d3db578a994da12f4f876a66dc150b8 | abuse_ch | Mirai |
| 5286d2946cd32d3901b683496ee882a3970ae6ad5d63c14d36a148b6c03aeaf9 | abuse_ch | Mirai |
| 642f8c1786ad5ad90542790446775c890afccdd5978847713c414bb2bae167b7 | abuse_ch | Mirai |
| 8350c2b1da86f0169b4287b2d218554861da87de82a364032526ec2fc1f30691 | abuse_ch | Mirai |
| 3c29dd311a4332e0c03a0b7bc8cd0435b18c6638bf84017760140a5ac7dfda93 | abuse_ch | Mirai |
| 000764ec08dd7412613a6335337696010bdd7026ef61b26dd19ea5ac6cb7d7e4 | abuse_ch | Mirai |
| 03533af22a257dfcfe0794b6dbe677ad2a256a51c78fb68f7cc5621b8a18617d | abuse_ch | Mirai |
| f499984e4bf2f7786856f6a9626b44aed69556a0fd9a770b16284838968140fa | abuse_ch | Mirai |
| b95cc683d9ce6c0d07d80f43de9759166c82953f609441295d0e5eeaaacdd05a | abuse_ch | Mirai |
| e6a15e5f010724f81d9aa69acfac0b276b9d6c86559015e0ef728dbeb064cd58 | lowmal3 | n/a |
| 6fa54d4dc7eb1d7cf034498613f23e670d19a2e02f813fccdda65f41d84a9860 | smica83 | n/a |
| d2a09961631b1cddfc8a6295039d59ec4d322ccced724f26fcc7b81a7fc2fc4b | adrian__luca | n/a |
| 630446fe1613b6ae61d515d35bc9dee937f454d3e8ee27bb5802982160812936 | adrian__luca | n/a |
| 98077e229b4f5b475383f5d30217423d72c35427dd83d95d3ac5ad9dd7e95664 | adrian__luca | Formbook |
| 151355d4e162afc65c8f9569e78c02fa071d84041cc0253cfaf98ad5a9e96435 | adrian__luca | AgentTesla |

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
| 45.148.10.240 | 10 |
| 107.150.123.48 | 10 |
| 196.189.236.67 | 10 |
| 2.57.122.238 | 9 |
| 3.129.187.38 | 9 |
| 18.218.118.203 | 9 |
| 45.148.10.152 | 9 |
| 45.153.34.117 | 9 |
| 46.151.178.14 | 9 |
| 66.132.172.43 | 9 |
| 66.132.172.142 | 9 |
| 66.132.172.182 | 9 |
| 66.132.195.115 | 9 |
| 66.132.224.233 | 9 |
| 80.82.77.33 | 9 |
| 93.152.221.37 | 9 |
| 94.154.43.223 | 9 |
| 119.28.84.193 | 9 |
| 130.12.182.223 | 9 |
| 144.225.6.182 | 9 |

### OpenPhish (live phishing URLs)
- http://andresh155.github.io/exzamen
- http://sd-hope.org/wpp
- http://delta-root49.pages.dev/
- http://menuuu-aktivasi.kruer.web.id/
- http://sp10ct10-evarnak-biz-qavero.pages.dev/
- http://sp10ct10-ravvek-biz-lureni.pages.dev/
- http://sp10ct10-rulvek-biz-qavari.pages.dev/
- http://sp10ct10-gurvak-biz-rumeko.pages.dev/
- http://sp10ct10-murvek-biz-rumeni.pages.dev/
- http://sp10ct10-sarnak-biz-rumaro.pages.dev/
- https://meramaskloginyc.gitbook.io/
- https://lnk.ink/R4OsW
- https://www.roblox.com.et/users/8294879321/profile
- http://mum.lxf.temporary.site/pdolf/fg
- https://zd.lc/n5hsB
- http://goo.su/emQzHd
- https://helpus-treiozor.gitbook.io/
- https://naman-gudhka-1912.github.io/amazon-clone/checkout.html
- http://australianvouchers-ks502.ink/qLm7Ra
- https://www.roblox.com.pt/games/114574503491412/Anime-Zero-SOLAR-RADIANCE?privateServerLinkCode=33904598587074146790476626474920&game_id=114574503491412&game_name=Anime-Zero-SOLAR-RADIANCE

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://b8376mghi5d.jp.larksuite.com/share/base/form/shrjpMwk5KEz3wmsdPQjPPcLjqh?auth_token=U7CK1RF-adbr2d53-7534-4db6-ad01-37d4cfkil49j-NN5W4 |
| N/A | https://portal-kucoin-login-info.typedream.app/ |
| N/A | https://away.vk.ru/away.php?rh=94f413f2-1658-47b1-afed-91a809537933 |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=ASKXGp0_nbFzdHoBsG_d6znGlWE063OUXUJ-liVgQNfJJB3wA_mip4wV6In-9Cchxtm7MSHwtubxoQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SQqhMajONZP3qlWoFudyHWj1IpuSU41f-xF_5wj_QQwPgy_Rdh89_e-9EQmoY1k8SYEMcUeAw&dsh=S-1189047650%3A1792398408883554 |
| N/A | https://allegro-lokalnie.zoomarea.sbs/ |
| N/A | http://49.51.43.12/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AQMjQ7QyROPzn0qaqnYvX4_aw7qH8RajahyDV4UI8mo2Mw7SaNi-z6QQG4MH4pDlzJ2gDPTt_nm2&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06STlw3UgxTqZm9fFdYyeEw4FIqMMph10ib-e0t61d71VDBWTTkAvDqvwwxNEpiMndS29gZpwFg&dsh=S-181863207%3A1792398112573013 |
| N/A | https://morojames1789900170014.0690011.misitiohostgator.com/t1/page/index.php |
| N/A | https://allegro.covevictory286.sbs/ |
| N/A | https://away.vk.ru/away.php?rh=5fc898c2-c69c-4e36-92e3-dcc06805b0aa |
| N/A | https://allegro.agjab.sbs/ |
| N/A | https://skinsmonkey.com?referrer=pid%3D1%26af_tranid%3DMTQ1NDI4MDMyMzI3NzE5MTUyNDA%3D |
| N/A | https://away.vk.ru/away.php?rh=fa7fc048-cb42-4bfc-82cb-764f1b0a9c71 |
| N/A | https://vercel.com/login?next=%2Fsso-api%3Furl%3Dhttps%253A%252F%252Finterface-uniswap.vercel.app%252F%26nonce%3D8de762e0c0ae94f2f927be192e3384aa52b4c9eb9704c6e7b9b62f4bc8ad246c |
| N/A | https://www.att.com/activearmorapp?_branch_match_id=1640634546218058340&utm_source=AT%26T%20App&_branch_referrer=H4sIAAAAAAAAA8soKSkottLXT0wuySxLTSzKzS%2FSzS%2FKTM%2FM00ssKdFLzs%2FV9wtL8U6KLCzzMUqyrytKTUstKsrMS49PKsovL04tsnXOKMrPTQUAZUf3KkgAAAA%3D |
| N/A | https://qhqgcy.com |
| N/A | https://yandex.ru/showcaptcha?cc=1&form-fb-hint=2.1&mt=E80A620491D52BA3C83729885D4DA85536DB2CE75AE9999EB04BF8E2F16F835832CF59A4C858D1B32DAA8F3B8B8240B9D8217897F1685E720D14248DDB1FFF5050023540F3BED6C3C2C43146FA00553921227AD0F2A1F896BD1A32E73B6793CE30E2116B72E9A3166E5B925B081EB714A422961C7DB8A97D7A4E674E6FB4D0673491A6785DFC77D5D2&retpath=aHR0cHM6Ly95YW5kZXgucnUvc2VhcmNoP3RleHQ9MjExNjg3MTc%2C_9e32ea590f1152ceb4677b92f96f1e0c&t=2%252F1792395133%252Fd406100f3f90c9cc9643fbc89da9c4f4&u=9605136785862044437&s=c00272df8d88e2aab95431d6261dc46e |
| N/A | https://theprintking.co.za/index.php/ |
| 8.1 | http://49.51.43.12/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=AWnogHe_pDujLaO-hl3d_3DQFjS6PW6JGM3LRrD13mxmiaQWTJuHz9b6nwmaSIh76M5SMOelnJex7g&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SRSHW0G5WguGK8-r2occD8usZKN-Rc72eTQO5eKIwvT5eJA8w-_-sOwIzjIcG5LdU6GKRxrvg&dsh=S1394160346%3A1792394898707282 |
| N/A | https://login.ksszxmy.com/verify/3e4e234f?host=login.ksszxmy.com&redirect=%2F%3FNH3nYUfgFMgr3QQ122VVx9Pe |
| N/A | https://away.vk.ru/away.php?rh=e2578df2-d117-4da7-99bd-a3e3985ecb83 |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| 38151a6b2438b2b645a27a891e1e15786f11a783 | PureLogsStealer C&C |
| eaefd82da94ee8839666b2a42d24dcc412d7de3c | Malware C&C |
| e2234aa66c80b118b69211f6e8f4efbd578a7587 | PureLogsStealer C&C |
| e2dbc11a546d739d12e547c38cdb4fd6cfacd4c4 | PureLogsStealer C&C |
| b97f1ae860fce04e1aae480e10b884da9826b17b | PureLogsStealer C&C |
| 97001686e56437dda319c71d5b0deeb8647de6e3 | QuasarRAT C&C |
| ad71014e839f794407e155508ce8ba98bf9556f7 | PureRAT C&C |
| 565ad03c4f04a685db081954cc9e5b1b210849e9 | OffLoader C&C |
| 3aa254a14d2bfefa3f3645be8f87a814edcf3109 | OffLoader C&C |
| a1fe9a509cdbfa8cc81db2a1f2216a96b32b2e55 | ACRStealer C&C |
| d4c2969ae8a878031ece0d67457d419eab16358f | ACRStealer C&C |
| 20e506ba84f2b1e681674fed4f44d72024f18cb2 | WARDENStealer C&C |
| 5758a152f5bc1f96581c6530488f830766c45c96 | QuasarRAT C&C |
| b6e98fa780d26472b70284be1abf84e7cf2bb152 | Malware C&C |
| 6dc0b07b0666b932f43af624460a79c98d5d17bb | ConnectWise C&C |
| 28c47a169d83c0017b5db95a0ae29973cf21d13b | ConnectWise C&C |
| a36fb193d41fdff5259ef4902ef4b33de38f768b | DCAgentRMM C&C |
| c7a0310a47eec71976fbd7a4ac1dbd0aa4b7a7c1 | PureRAT C&C |
| ff59f65a5b8f0f847ed3c0ac1f140dc28de2f720 | OffLoader C&C |
| 4fcc8c0172b376ebfc85d644c5f64f7cd60321a5 | Vidar C&C |

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
- 1.10.176.3
- 1.14.240.247
- 1.178.216.211
- 1.179.209.26
- 1.187.76.29
- 1.20.172.244
- 1.20.230.31
- 1.20.88.78
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.227.228.131
- 1.234.21.73
- 1.234.23.83
- 1.235.14.41
- 1.235.183.146
- 1.237.155.150
- 1.238.106.229
- 1.242.33.13

### CINS Army (poorly-rated IPs)
- 1.117.61.172
- 1.117.68.141
- 1.14.149.30
- 1.15.14.29
- 1.214.29.155
- 1.215.138.43
- 1.221.65.174
- 1.24.16.150
- 1.24.16.154
- 1.24.16.166
- 1.24.16.17
- 1.24.16.179
- 1.24.16.183
- 1.24.16.2
- 1.24.16.42
- 1.24.16.5
- 1.24.16.53
- 1.24.16.6
- 1.24.16.61
- 1.24.16.74

## News (last ~36h, across outlets)
### The Hacker News
- [Unpatched Broadcom Wi-Fi Flaw Lets Attackers in Range Run Code as Root on Routers](https://thehackernews.com/2026/10/unpatched-broadcom-wi-fi-flaw-lets.html)
- [OpenCode Console Breach May Have Exposed OpenAI, Anthropic, and Google API Keys](https://thehackernews.com/2026/10/opencode-console-breach-may-have.html)
- [ConnectWise Suspends Cloud Backup After Attackers Compromise Microsoft 365 Tenants](https://thehackernews.com/2026/10/connectwise-suspends-cloud-backup-after.html)

### BleepingComputer
- [Hackers exploit SiteGuard WAF flaw to run commands as admins](https://www.bleepingcomputer.com/news/security/hackers-exploit-siteguard-waf-flaw-to-run-commands-as-system-root/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
_No new items / feed unavailable this run._

### SecurityWeek
- [Anthropic Acquires Confidential AI Startup Opaque Systems](https://www.securityweek.com/anthropic-acquires-confidential-ai-startup-opaque-systems/)
- [US Cybersecurity Job Postings Fall 26% as AI Security Engineer Demand Soars](https://www.securityweek.com/us-cybersecurity-job-postings-fall-26-as-ai-security-engineer-demand-soars/)

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
- [Orphaned VBA Projects Inside DWG Files: YARA Rule, (Sun, Oct 18th)](https://isc.sans.edu/diary/rss/33434)

### Securelist (Kaspersky)
_No new items / feed unavailable this run._

### CrowdStrike Blog
- [October 2026 Patch Tuesday: 1,413 CVEs Include Three Zero-Days and 75 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-october-2026/)
- [U.S. Government Disrupts FAMOUS CHOLLIMA Operation with CrowdStrike Assistance](https://www.crowdstrike.com/en-us/blog/fbi-disrupts-famous-chollima-operation-with-crowdstrike-assistance/)
- [CrowdStrike and Anthropic Give Critical Infrastructure Defenders the AI Advantage](https://www.crowdstrike.com/en-us/blog/crowdstrike-anthropic-critical-infrastructure-defense-program/)
- [Solving the Continuous Authorization Conundrum](https://www.crowdstrike.com/en-us/blog/solving-the-continuous-authorization-conundrum/)
- [Unknown Threat Actor Uses AI-Driven ARTEX to Target South Korean Finance](https://www.crowdstrike.com/en-us/blog/unknown-threat-actor-uses-artex-to-target-south-korean-finance/)
- [CrowdStrike Named a Leader in the 2026 IDC MarketScape for Worldwide Modern Endpoint Security for Enterprises Vendor Assessment](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-idc-marketscape-worldwide-modern-endpoint-security-for-enterprises/)
- [Request, Aggregate, Bypass: How Attackers Can Evade LLM Safety Classifiers](https://www.crowdstrike.com/en-us/blog/how-attackers-can-bypass-llm-safety-classifiers/)
- [Falcon Data Security for SaaS Secures Sensitive Data in Microsoft 365](https://www.crowdstrike.com/en-us/blog/falcon-data-security-for-saas-secures-sensitive-data/)
- [New in Falcon Cloud Security: Third-Party App Insights and AI-Enhanced Remediation](https://www.crowdstrike.com/en-us/blog/falcon-cloud-security-third-party-app-insights-ai-enhanced-remedation/)
- [CrowdStrike Expands Federal SOC Modernization Through CISA-Funded SIEMaaS](https://www.crowdstrike.com/en-us/blog/crowdstrike-expands-federal-soc-modernization-via-cisa-siemaas/)

### FortiGuard Threat Signal
_No new items / feed unavailable this run._

## Fetch issues this run
_None — all sources responded._

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal