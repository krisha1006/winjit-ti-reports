# Winjit Daily TI Digest — 2026-10-20

_Auto-generated. Window: last ~24h. Fetched at 2026-10-20T08:20:10.599989+00:00Z_

**At a glance:** 0 new KEV · 52 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-112370 | 9.9 | n/a | A vulnerability was found in H3C Magic NX15 100R017. This issue affects the function sub_416874 of the file /usr/bin/usrlist. Performing a manipulation results in os command injection. Remote exploita |
| CVE-2026-112371 | 9.9 | n/a | A vulnerability was determined in H3C Magic NX15 NX15V100R017. Impacted is the function write of the file /api/esps of the component RPC Interface. Executing a manipulation of the argument path can le |
| CVE-2026-111862 | 9.8 | n/a | Rank Math SEO PRO for WordPress is affected by a supply-chain compromise in a subset of version 3.0.123 packages downloaded or updated between October 15, 2026 at 20:02 UTC and October 16, 2026 at 07: |
| CVE-2026-109437 | 9.8 | n/a | Cognition before 0.13.0 contains an unauthenticated remote code execution vulnerability due to defaulting its agent sandbox backend to local execution and shipping no authentication on its REST/SSE AP |
| CVE-2026-112776 | 9.8 | n/a | Craft CMS from 5.0.0 before 5.11.0 contains an authorization bypass vulnerability that allows site-scoped GraphQL tokens to mutate other sites' content because requireAllowedSite() is not enforced. At |
| CVE-2026-112779 | 9.8 | n/a | Grav API plugin (grav-plugin-api) 1.0.40 before 1.0.42 caches a full translation dictionary for every well-formed language code sent to the unauthenticated GET /api/v1/translations/{lang} endpoint, an |
| CVE-2026-109442 | 9.8 | n/a | piflow 2.0.0 through 2.0.1 contains a remote code execution vulnerability in its DeepAgents chat agent, whose POST /chat and POST /chat/stream endpoints lack authentication. Attackers can instruct the |
| CVE-2026-75128 | 9.8 | n/a | Langchain-Chatchat through 0.3.1.3 exposes a POST /tools/call API endpoint that invokes any registered tool by name without authentication, leaving the always-registered shell tool callable. Remote at |
| CVE-2026-77932 | 9.8 | n/a | DB-GPT through 0.8.2 contains an unauthenticated remote code execution vulnerability because the /api/v1/chat/react-agent endpoint relies on a mock get_user_from_headers function that grants every cal |
| CVE-2026-77933 | 9.8 | n/a | DB-GPT through 0.8.2 contains a hardcoded credentials vulnerability in its default docker-compose.yml that sets a static MYSQL_ROOT_PASSWORD and publishes port 3306 on all interfaces. Attackers reachi |
| CVE-2026-77936 | 9.8 | n/a | Letta through 0.16.8 ships a compose.yaml that does not enable LETTA_SERVER_SECURE, so the password middleware is never added and all API routes are unauthenticated, and it exposes a superuser Postgre |
| CVE-2026-109395 | 9.1 | n/a | Ning compress-lzf before 1.2.0 contains an out-of-bounds memory access vulnerability in the sun.misc.Unsafe based UnsafeChunkDecoder that fails to validate back-references and literal runs. Attackers  |
| CVE-2026-112770 | 8.8 | n/a | Craft CMS 4.x before 4.18.8 and 5.x before 5.11.0 contains a remote code execution vulnerability in the Twig group filter, which invokes non-string arrow arguments as callables without the checkArrow  |
| CVE-2026-112772 | 8.8 | n/a | Craft CMS from 5.0.0 before 5.11.0 contains a remote code execution vulnerability that allows authenticated Control Panel users to escape the Twig sandbox via Asset::getMimeType transforms. Attackers  |
| CVE-2026-112780 | 8.8 | n/a | Grav from 2.0.15 before 2.2.2 contains an allowlist bypass vulnerability that allows page editors to call arbitrary public static methods by renaming Flex form fields with replace-name@. Attackers wit |
| CVE-2026-107400 | 8.8 | n/a | IBM TRIRIGA Application Platform 5.0.0 through 5.0.8 could allow a remote authenticated attacker to execute arbitrary code due to improper authentication. |
| CVE-2026-109126 | 8.8 | n/a | IBM Verify Identity Access 11.0.3.1 and IBM Security Verify Access 10.0.9.3 Appliance could allow a physically proximate attacker to gain elevated privileges due to the use of hard-coded credentials. |
| CVE-2026-109443 | 8.8 | n/a | JoySafeter through 1.0.0 contains a remote code execution vulnerability that allows authenticated users to run operating system commands via an unsandboxed execute tool in Copilot standard mode. Attac |
| CVE-2026-109444 | 8.8 | n/a | OpenSRE through 0.1.2026.10.19 contains an approval gate bypass vulnerability that allows attackers to execute shell_run commands without confirmation because the headless presenter's execution_allowe |
| CVE-2026-77926 | 8.8 | n/a | Aix-DB 1.2.4 contains a remote code execution vulnerability that allows authenticated non-admin users to run operating system commands through the ChatBI common agent's ungated deepagents execute tool |
| CVE-2026-77930 | 8.8 | n/a | EvoScientist 0.1.0 before 0.2.5 contains an approval bypass vulnerability that allows attackers to run host shell commands by delegating them to async sub-agents lacking an interrupt_on gate. Attacker |
| CVE-2026-77934 | 8.8 | n/a | Coze Studio before 0.5.0 contains an insecure default configuration that allows any registered user to execute commands by running workflow code nodes in an unsandboxed python3 subprocess. Attackers c |
| CVE-2026-113404 | 8.8 | n/a | WebITR developed by Uniong has a Insecure Deserialization vulnerability. Authenticated remote attackers can use the hard-coded cryptographic key to craft and submit malicious serialized data, thereby  |
| CVE-2026-113405 | 8.8 | n/a | BA-Workflow developed by YS-infoware has a SQL Injection vulnerability. Authenticated remote attackers can inject arbitrary SQL statements to read, modify, and delete database contents. |
| CVE-2026-113406 | 8.8 | n/a | BA-Workflow developed by YS-infoware has a SQL Injection vulnerability. Authenticated remote attackers can inject arbitrary SQL statements to read, modify, and delete database contents. |
| CVE-2026-113407 | 8.8 | n/a | BA-Workflow developed by YS-infoware has a SQL Injection vulnerability. Authenticated remote attackers can inject arbitrary SQL statements to read, modify, and delete database contents. |
| CVE-2026-105453 | 8.4 | n/a | IBM Sterling Connect Direct for Unix 6.3.0.0 through 6.3.0.7 and 6.4.0.0 through 6.4.0.6 could allow a local attacker to gain elevated privileges due to improper privilege management. |
| CVE-2026-107366 | 8.3 | n/a | IBM Langflow OSS 1.0.0 through 1.12.4 contains three message endpoints that perform no ownership verification. Any authenticated user can bulk-delete another user's messages, overwrite message content |
| CVE-2026-77935 | 8.3 | n/a | Coze Studio through 0.5.1 contains an insecure direct object reference vulnerability in workflow.go that allows authenticated users to access other spaces' workflows by supplying foreign workflowIDs.  |
| CVE-2026-53995 | 8.2 | n/a | MLflow 3.17.1 and earlier contains a path traversal vulnerability in the FileStore tracking backend that allows unauthenticated attackers to control filesystem paths by submitting a crafted trace ID c |
| CVE-2026-16487 | 8.1 | 0.2% | A flaw was found in bootc when operating with the default containers signature policy. Automatic or manual upgrades of a mutable image tag may apply unsigned content for registries that fall through t |
| CVE-2026-109440 | 8.1 | n/a | LangAlpha through 2026.09.07 contains an indirect prompt injection vulnerability that allows remote attackers to execute shell commands or Python by planting instructions in web content retrieved by t |
| CVE-2026-77937 | 8.1 | n/a | Letta through 0.16.8 contains an authentication bypass vulnerability that allows API callers to impersonate other users by supplying a self-asserted user_id HTTP header. Attackers can set user_id to a |
| CVE-2026-112360 | 8.0 | n/a | A security vulnerability has been detected in Netis EAP930 1.250905.115454. This issue affects the function return200 of the file /cgi-bin/debug of the component CGI Endpoint. The manipulation of the  |
| CVE-2026-112263 | 7.8 | n/a | Television (tv) 0.15.0 through 0.15.9 contains an OS command injection vulnerability that allows attackers to run shell commands through improperly escaped single quotes in format_command. Attackers c |
| CVE-2026-112257 | 7.8 | n/a | A flaw was found in GIMP. The PSD thumbnail resource loader performs a BGR-to-RGB channel swap with a fixed 3-byte stride and does not verify that the JPEG thumbnail is RGB. A crafted grayscale PSD th |
| CVE-2026-112258 | 7.8 | n/a | A flaw was found in GIMP. The XCF loader can leave a dangling pointer in the linked-channels list when a linked channel is later destroyed via a selection property. Opening a crafted XCF file can caus |
| CVE-2026-112261 | 7.8 | n/a | A flaw was found in GIMP. Opening a crafted XCF that selects a path and then fails to load that path can cause a use-after-free in the main process, leading to a crash and potentially arbitrary code e |
| CVE-2026-112304 | 7.5 | n/a | docTR through 1.1.0 contains an unsafe deserialization vulnerability in load_pretrained_params() that loads checkpoints with torch.load without weights_only=True. Attackers who control a local or URL- |
| CVE-2026-112309 | 7.5 | n/a | @rvf/set-get before 7.0.4 contains a prototype pollution vulnerability in setPath that allows unauthenticated attackers to overwrite properties of shared built-in functions via inherited Object.protot |
| CVE-2026-112775 | 7.5 | n/a | Craft CMS from 5.0.0 before 5.11.0 contains an authentication bypass vulnerability that allows attackers to reuse verification codes because users/verify-email does not invalidate them for active user |
| CVE-2026-112782 | 7.5 | n/a | Grav 1.7.53 before 1.7.53.5 and 2.0.0-rc.8 before 2.2.2 contains a resource exhaustion vulnerability that allows anonymous visitors to bypass the system.images.max_pixels limit when system.images.url_ |
| CVE-2026-93300 | 7.5 | n/a | The EventON - Subscriber plugin for WordPress is vulnerable to generic SQL Injection via the 'email' parameter in all versions up to, and including, 1.4.5 due to insufficient escaping on the user supp |
| CVE-2026-112377 | 7.4 | n/a | CCC Attestation SIG attested-tls-poc through commit 731ca82 fails to bind early attestation Evidence to the TLS connection, allowing attackers to relay valid Evidence from a genuine attester. Attacker |
| CVE-2026-112104 | 7.3 | n/a | A flaw has been found in eremef bandcamp-player up to 1.8.33-beta. The impacted element is an unknown function of the file database.ts of the component Remote Control Server. Executing a manipulation  |
| CVE-2026-112141 | 7.3 | n/a | A vulnerability was determined in satya-vinay Events-Management-System up to 437c77ceb69bf9fe2e3f4f46f7871b83f425383a. Affected is the function mysqli_query of the file doedit.php of the component Reg |
| CVE-2026-112145 | 7.3 | n/a | A security vulnerability has been detected in speaches-ai speaches up to 0.9.0-rc.3. This vulnerability affects the function PyannoteDiarizationModelManager._load_fn of the file src/speaches/executors |
| CVE-2026-112150 | 7.3 | n/a | A security flaw has been discovered in vraj404 Criminal-Management-System up to 2808d057e7ddc5295519a487365b0cacfd0ba8c4. Affected is an unknown function of the file search.php. The manipulation of th |
| CVE-2026-112252 | 7.3 | n/a | A vulnerability has been found in Wuxi Wubang Security Software Wubang Five-in-One Safety Production Management Information System up to 3.5. Affected is the function xp_cmdshell of the file /ws.asmx. |
| CVE-2026-112177 | 7.3 | n/a | A flaw was found in Ghostscript as shipped with Red Hat Enterprise Linux 8. The correction for CVE-2019-14869 was omitted during the rebase from version 9.25 to 9.27, leaving privileged .forceput oper |
| CVE-2026-112774 | 7.2 | n/a | Craft CMS from 5.8.0 before 5.11.0 contains a remote code execution vulnerability that allows authenticated administrators to inject Yii behaviors by supplying a JSON-string field layout to ContentBlo |
| CVE-2026-112777 | 7.2 | n/a | Craft CMS 4.x before 4.18.8 and 5.x before 5.11.0 contains a blocklist bypass in the Twig create() function because its class-name checks are case-sensitive while PHP class resolution is not. Attacker |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-m32q-hxxr-f9w2 | CVE-2026-96903 | unknown | The Easy Property Listings WordPress plugin before 3.5.27 does not perform authorisation checks... |
| GHSA-wvwj-r2jm-h52q | CVE-2026-97627 | high | Hidden functionality issue exists in Multiple DVRs (Digital Video Recorders) provided by Atsumi... |
| GHSA-5c63-xm6f-r368 | CVE-2026-113380 | critical | In the RingRTC library before 2.72.0 for Signal, a peer that saturates a call's FSM queue can... |
| GHSA-qwfm-hv5v-vc9r | CVE-2026-113386 | high | Roundcube Webmail before 1.6.20 and 1.7.x before 1.7.5 are affected by IMAP command injection. A... |
| GHSA-xm9h-7j4x-37fx | CVE-2026-93300 | high | The EventON - Subscriber plugin for WordPress is vulnerable to generic SQL Injection via the ... |
| GHSA-576j-vm4f-c456 | CVE-2026-96902 | unknown | The Easy Property Listings WordPress plugin before 3.5.28 does not restrict which listing fields... |
| GHSA-9p4x-ppr8-mm4w | CVE-2026-100737 | medium | Hidden functionality issue exists in Multiple DVRs (Digital Video Recorders) provided by Atsumi... |
| GHSA-q9jg-8mw4-m3mw | CVE-2026-109831 | medium | UnRTF by GNU Project is vulnerable to out-of-bounds write. If a user opens an RTF file crafted by... |
| GHSA-8vcw-r93h-qx6c | CVE-2026-75753 | medium | Missing Authentication for a Critical Function  in certain ASUS routers allows an unauthorized... |
| GHSA-c3cx-qmjc-794q | CVE-2026-12489 | medium | An incorrect authorization vulnerability in the Data Access Layer (DAL) of Zyxel EX3501-T0... |
| GHSA-8j23-4jj7-m65q | CVE-2026-17518 | high | Buffer Copy without Checking Size of Input in certain ASUS router models allows an adjacent... |
| GHSA-r9g2-75m7-w9wg | CVE-2026-105299 | high | Summary



Before version 0.9.0, the HTTP/1 upstream path in pingora-proxy passed the downstream... |
| GHSA-2738-4g2m-64cv | CVE-2026-86467 | unknown | Apache Airflow Amazon provider: the AWS auth manager's SAML login flow does not bind the... |
| GHSA-978r-3cgq-4j3w | CVE-2026-102438 | high | An uncontrolled search path element vulnerability in ASUS Armoury Crate allows local users to... |
| GHSA-mcq2-6h3f-3vf3 | CVE-2026-86957 | unknown | An out-of-bounds read was addressed with improved bounds checking. This issue is fixed in iOS 26... |
| GHSA-c46j-mwhw-r25p | CVE-2026-86979 | unknown | A privacy issue was addressed with improved checks. This issue is fixed in macOS Golden Gate 27.... |
| GHSA-jh3m-g6w6-xjp4 | CVE-2026-86928 | unknown | A path handling issue was addressed with improved validation. This issue is fixed in macOS Golden... |
| GHSA-5c43-29q9-8fc4 | CVE-2026-86932 | unknown | An authorization issue was addressed with improved state management. This issue is fixed in macOS... |
| GHSA-pf5v-xx6f-ccgf | CVE-2026-86977 | unknown | An authorization issue was addressed with improved network restrictions. This issue is fixed in... |
| GHSA-hqp4-33rx-h858 | CVE-2026-86975 | unknown | An out-of-bounds read was addressed with improved bounds checking. This issue is fixed in iOS 27... |
| GHSA-pqq2-646c-p785 | CVE-2026-86976 | unknown | An authorization issue was addressed with improved state management. This issue is fixed in iOS... |
| GHSA-3hf6-q2c8-cwvf | CVE-2026-86953 | unknown | An out-of-bounds write issue was addressed with improved bounds checking. This issue is fixed in... |
| GHSA-hmv8-g358-v6hx | CVE-2026-86962 | unknown | A double free issue was addressed with improved memory management. This issue is fixed in iOS 26... |
| GHSA-79mp-j3j2-g5p4 | CVE-2026-86948 | unknown | This issue was addressed by enforcing library validation on the affected binaries. This issue is... |
| GHSA-qhj5-j72v-q72x | CVE-2026-86961 | unknown | A race condition was addressed with additional validation. This issue is fixed in iOS 27 and... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Fisher59 | anubis |  | 2026-10-20T03:57:32.679892+00:00 |
| BW Office World | payload |  | 2026-10-20T00:08:36.598547+00:00 |
| Brüninghoff Group | payload | DE | 2026-10-20T00:07:26.154443+00:00 |
| Rosenberg & Pittinsky | Global Secret Group | US | 2026-10-19T22:23:20.831665+00:00 |
| Toyota Canarias | qilin | ES | 2026-10-19T21:39:49.714008+00:00 |
| Baker Donelson | Redact | US | 2026-10-19T20:55:00.112730+00:00 |
| Vormittag Associates Inc | N0n | US | 2026-10-19T20:53:43.606863+00:00 |
| Seminole Schools | Global Secret Group | US | 2026-10-19T20:52:13.758169+00:00 |
| chooseultimate.com | lockbit5 | US | 2026-10-19T21:31:17.353307+00:00 |
| Froggys Fog | N0n | US | 2026-10-19T19:22:56.788259+00:00 |
| WalkingTree Technologies | qilin | IN | 2026-10-19T15:59:19.631587+00:00 |
| SkyWorld Air Cargo | qilin | AE | 2026-10-19T15:58:41.146838+00:00 |
| Johnson & Pace | qilin | GB | 2026-10-19T15:58:00.416336+00:00 |
| Dental Team FL | qilin | US | 2026-10-19T15:57:18.608289+00:00 |
| Grupo Cronica | qilin | AR | 2026-10-19T14:53:29.161722+00:00 |
| Salauno | qilin | MX | 2026-10-19T14:52:46.048800+00:00 |
| PingCAP / TiDB Cloud | fulcrumsec | CN | 2026-10-19T13:50:46.421007+00:00 |
| Latham & Watkins | SilentRansomGroup | US | 2026-10-19T13:25:56.448207+00:00 |
| Hotel DuPont | N0n | US | 2026-10-19T13:24:13.858059+00:00 |
| Kingwood Endoscopy | N0n | US | 2026-10-19T13:23:34.643309+00:00 |

## IOCs
### ThreatFox (recent, abuse.ch)
| Indicator | Type | Malware |
|---|---|---|
| hi0cx4lq.bulkcompressimages.com | domain | js.clearfake |
| https://z01.abangempayer.org/c6/ | url | win.vidar |
| 6048e045bbbafcfd5f594e31e0cece86fe5ffa1c94a563fddd1fca8183ce9061 | sha256_hash | osx.amos |
| 159.89.160.29:3278 | ip:port | win.remus |
| f000b4e228b5210bcbf558478cf19e477393248f10b37f62893372e5faccb975 | sha256_hash | osx.amos |
| https://z01.abangempayer.org/tz/ | url | win.vidar |
| 47.129.52.27:80 | ip:port | win.vshell |
| 60.205.221.206:8081 | ip:port | win.vshell |
| 1.94.100.198:22 | ip:port | win.cobalt_strike |
| 45.32.29.179:8084 | ip:port | win.vshell |
| 8.216.63.147:60000 | ip:port | unknown |
| a60322f3d0333bce984463be9109bd2c94912bf2b62e0eff0ff9d47e1cbc840c | sha256_hash | osx.amos |
| eb5f3dd2a5053e750d10b4c520b0fea07f306b717598a8828b9fa953e406d212 | sha256_hash | osx.amos |
| https://wh.abangempayer.org/m0/ | url | win.vidar |
| 7eef1f1775b28c8f597140a058cf0f06ed012b7a241e62093a427d666faac926 | sha256_hash | osx.amos |
| d83076b8ee5c4ce88d582c4ec96fe3ceef6ac9ab | sha1_hash | win.asyncrat |
| 0a4456ee28ab88126b0fbe9c977ada79 | md5_hash | win.asyncrat |
| 3ea2a81a288fe047cca8d1f19e291eff | md5_hash | win.formbook |
| a027801b9481b5e24c8773efaa7957dd67a69384 | sha1_hash | jar.crossrat |
| 42e3b99c78c70551642b4e7a568c3898 | md5_hash | jar.crossrat |

### URLhaus (recent malicious URLs, abuse.ch)
| URL | Threat | Status |
|---|---|---|
| http://182.127.178.64:45042/bin.sh | malware_download | online |
| http://27.215.143.87:33433/bin.sh | malware_download | online |
| http://176.65.139.148/bins/arm5 | malware_download | online |
| http://42.228.32.100:37587/bin.sh | malware_download | online |
| http://183.35.50.224:38590/bin.sh | malware_download | online |
| http://42.225.69.1:56329/bin.sh | malware_download | online |
| http://118.251.13.202:40966/bin.sh | malware_download | online |
| http://123.11.4.67:51620/i | malware_download | online |
| http://112.248.81.145:57433/i | malware_download | offline |
| http://123.11.4.67:51620/bin.sh | malware_download | online |
| http://42.230.30.10:51216/i | malware_download | online |
| http://182.116.23.184:38135/i | malware_download | online |
| http://101.59.79.119:48386/bin.sh | malware_download | online |
| http://61.52.169.211:52510/i | malware_download | online |
| http://119.189.146.15:56459/bin.sh | malware_download | online |
| https://github.com/ashdirectorband33/DiscordObhod/releases/download/1.10.2/zapret-discord-youtube-1.10.2.rar | malware_download | online |
| https://github.com/vicedetectivepack38/zapret-discord-youtube-2026/releases/download/v1.1.1/zapret-discord-youtube-1.10.3.zip | malware_download | online |
| https://github.com/TerminusWizard/youtubezapret/releases/download/1.9.9c/zapret-discord-youtube-1.9.9c.zip | malware_download | online |
| https://github.com/Restrictionergrid/DiscordFix-Windows/releases/download/1.11.1-New/zapret-discord-youtube-1.10.3.rar | malware_download | online |
| https://github.com/FreighterDeflate/DiscordObhod-New/releases/download/1.10.7/zapret-discord-youtube-1.10.2.rar | malware_download | online |

### MalwareBazaar (recent samples, abuse.ch)
| SHA256 | File type | Signature |
|---|---|---|
| d5e98b7761678d242eb513f58396ec636581f4b39ed7dec9af5272159e5a132f | whack_sh | n/a |
| 7fec3c5196460fbb3f9d484f4c15bc0c63ea627479abc9865cd74428b53521c3 | akudryk007 | n/a |
| bb6b28283b4c1c6d5946c5e2e9dda1824d0b828bd079a477678a8389c20ee2f9 | abuse_ch | PureLogsStealer |
| d63bb93f2f8d94a3f27b19252e8dd0907537a5a1241e45d5e01747aff03b5756 | abuse_ch | Mirai |
| a36b8ba545b0ebe6f3abed5c8edccfdec59d8b889112810f0a46fb0d26a79fb8 | threatcat_ch | n/a |
| c85467e8ed3b35ea22acfa2174ec18dd0332eae01bf239248dcffbca7a643e04 | Bitsight | n/a |
| 198659cc46b0cccf45c63324d3f25192095757a7df2ab6bb2e28e74f1d8d2dd4 | Bitsight | n/a |
| 1e98a36b2c40441a1bf33060bad8b52bf74ee659472aa15d3463bd51b118725f | whack_sh | AsyncRAT |
| a45c6dfff64bf285aa4c5a5bb70f95c43c077825606031629e307d82346f9eec | whack_sh | Mirai |
| bc0bde5dd5ca313436bc7119c5f603d9f4fb99dcbb09b2eaa5fd7ccda2c33794 | c4ffeine | AMOS |
| 50dcb100a03e3715615ab4dc04f6cedaa3e3c00c919367cda523b96b5d60ca0c | abuse_ch | SalatStealer |
| b34fe4cb9678e1ef5325277632f20603cf224e27e19e686e630429d3780aa319 | whack_sh | SalatStealer |
| e7455555251208365e3efc756a056b356419de8705ee6ae21731c9c5a4d4e6db | lowmal3 | AgentTesla |
| 64fea69abc1cd238b0c19501c1d9066d630a5ce91f5255c4317461646dabf7e6 | lowmal3 | n/a |
| ffc9adcdec20e97438ec1a46c7f08e76dbaa90b0a4b7de03291d90b791885583 | Bitsight | n/a |
| a235d7366d71f58f27b6f262a263211e76153648408e1f8e78d00b68dfac55e8 | abuse_ch | Mirai |
| 44a7cba81a611e798624ffab187b137725a5b7c0b80e53160f32839f01c7093f | Bitsight | Formbook |
| 22bfc182f4c190dbb875c15b344a8e24bc9d670533163f84e5f8dd3d36effe36 | abuse_ch | Mirai |
| 2a9e9064a532d8f386a73d63248e235fb6141445557f955059bd3b2d8a86a671 | abuse_ch | Mirai |
| 791163aa1825717ca9f53e15165e49a75e431094bb8de709f71ea02ad5b0babd | abuse_ch | Mirai |

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
| 77.90.185.20 | 12 |
| 2.57.122.238 | 10 |
| 45.148.10.240 | 10 |
| 46.151.178.14 | 10 |
| 130.12.180.32 | 10 |
| 152.32.225.117 | 10 |
| 64.62.197.167 | 9 |
| 64.62.197.227 | 9 |
| 66.132.172.136 | 9 |
| 66.132.172.142 | 9 |
| 66.132.186.180 | 9 |
| 66.132.195.55 | 9 |
| 66.132.224.87 | 9 |
| 71.6.199.23 | 9 |
| 85.217.149.22 | 9 |
| 85.217.149.38 | 9 |
| 103.159.2.113 | 9 |
| 167.94.146.49 | 9 |
| 167.94.146.51 | 9 |
| 167.94.146.62 | 9 |

### OpenPhish (live phishing URLs)
- http://faq-start-ledgercom-eng.typedream.app/
- http://hotelhautbuyeg.click/
- https://f005.backblazeb2.com/file/using1sg/mtsprofilesg.html
- https://www.amazonklantenservicenederland.com/
- http://shrabana-56.github.io/shrabana-project
- https://sky.money.irish/
- http://pub-6dc1b0514c16443f996ab97f41fbd0f7.r2.dev/3737848789.html
- http://www.hadiahshopee63.blogspot.com/
- https://security-server-page--tonyciresi.replit.app/
- http://celoechaore.pages.dev/
- https://www.roblox.ly/communities/8224279362/AuroraHub#!/about
- https://www.roblox.com.am/users/464414580239/profile
- http://merry-tanuki-99d39f.netlify.app/
- https://www.ledgerupdate.org/
- https://botsea.club/76etfl/g5eg
- http://www-mfacebook.com.vn/9x8q1ays3gb?z9B&9bK
- https://todayaccess.authofflog.com/
- https://crm.hips-warehouse.com/
- http://docs--trezor---login--io-cdn.typedream.app/
- https://www.roblox.rw/games/17625359962/-RIVALS?privateServerLinkCode=82052717502923663570920842920144

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | http://43.156.0.130/v3/signin/identifier?amp;continue=https://accounts.google.com/&amp;followup=https://accounts.google.com&passive=1209600&flowName=GlifWebSignIn&flowEntry=ServiceLogin&dsh=S-1807984436:1792484257382980 |
| N/A | https://lexigap.com/internet-banking.dbs.com.sg/ |
| N/A | https://ipc.cv/ |
| N/A | https://shuldo.wixsite.com/homepage1 |
| N/A | https://pageseuc1.actmkt.com/(S(3cycfo4mt4ghvrvioj2temyc))/l/c5X8MfZz6j9Y7Fto3LAd |
| N/A | https://away.vk.ru/away.php?rh=e5e4b1af-2c20-47f5-98f9-ca6afbf4b41c |
| N/A | https://www.att.com/activearmorapp?_branch_match_id=1640958071337501134&utm_source=AT%26T%20App&_branch_referrer=H4sIAAAAAAAAA8soKSkottLXT0wuySxLTSzKzS%2FSzS%2FKTM%2FM00ssKdFLzs%2FV9wtL8U6KLCzzMUqyrytKTUstKsrMS49PKsovL04tsnXOKMrPTQUAZUf3KkgAAAA%3D |
| 9.1 | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AWnogHfrcMjMJOA5-x4JjU2A_H62FL5Ipip8qUn0FfsVqhu1vrUBPxBl4JpnqCjPGKNrTfaShVnNJQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SSYcEVebGY3PhWQmzbDU96ugspD4fAxn4V7BMXCmZMdF_VytaBof8jDz7Eehdj2WamaUcOsww&dsh=S1392840665%3A1792472929863777 |
| 8.7 | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AQMjQ7TPKu6R4w93VRXMPKeD3zeOl4EoNrOdcsDBPMv7m30JK47iKcBvHB2Y608BaGxX8bX4kwt6sA&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SSvNkTebds4-lI4lVSE2oukTwtBFxDQoh1N7vOxpApa4rJCBnvZDFscXROBA45LA12K-3HLpg&dsh=S1394021595%3A1792472635840161 |
| 9.1 | http://43.156.0.130/v3/signin/identifier?amp%3Bffgf=1&amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=Af_xneGpinflONH_c3iB5WwVV1C6BSPwAwpudWnjxe8BcKRMcZLFgAnlzpjtHVk0QMFIUm6AcMYv&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SQ7OjYAvEBbEuPqVcJdeTZScYX4lvRFNg-_-rpSnwVyRMSjkheHP-yz58dzC5dTjIc01V5Adg&dsh=S1645585994%3A1792471894727877 |
| N/A | https://correoscostarica.cyou/5-vx_sgv6rvbtdv/VYb-5Vh6EvNTv_T5G5-RFY/user-936598//formulario-envio.php |
| 5 | http://49.51.43.12/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=ASKXGp36_CB8HzfrpuLLHTVjXxiUGDwO6Tj8yz4QrsaGyc3I4H4G7NxTTQJtpw0j07g9O5T5Tx4uyQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06ST7RJznfmMzMERp-CfFGEtgkrJ7qpwHh1HChJx1S7T4TQGp-7YFv_W3M4tRWPRknMjMwI-e&dsh=S1714296807%3A1792471320216340 |
| N/A | https://away.vk.ru/away.php?rh=f1744246-41f8-4271-a74c-795ca8160360 |
| N/A | https://b8376mghi5d.jp.larksuite.com/share/base/form/shrjpMwk5KEz3wmsdPQjPPcLjqh?auth_token=U7CK1RF-427g33e4-d42b-4643-9ae8-896fc5osr50q-NN5W4 |
| N/A | https://away.vk.ru/away.php?rh=7dfbda96-23f7-41e6-b03c-a8157fb1f6b6 |
| N/A | https://pageseuc1.actmkt.com/(S(kuxsopqtxca2lzmaj2fkh5yf))/l/c5X8MfZz6j9Y7Fto3LAd |
| N/A | https://kervinox.cfd/saisoncard |
| 9.2 | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AaSxoQyQEeCdGiNQploah5nAij7vrMqrlVIHby1Q4v_ARx9kttGkmffM4ARVCnkvjXQyGpUqW4kQNA&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SRNgWovd1lVPVOVpIb5Jaj66boseBNK7_J4yn2zZ4UuBFgtDzhRuSG7Oyks6H6eipK_4sOh&dsh=S-770617869%3A1792469693060569 |
| 8.8 | http://43.156.0.130/v3/signin/identifier?amp;continue=https://accounts.google.com/&amp;followup=https://accounts.google.com&passive=1209600&flowName=GlifWebSignIn&flowEntry=ServiceLogin&dsh=S1463380334:1792469162424150 |
| N/A | https://bankcheckdata-card.jp/ |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| 59fb8a90649cac57e345fbd3af9f76d6a73fac12 | OffLoader C&C |
| 9a2205a15c886d6278d9e0d60747e8ad287b6c7b | PureLogsStealer C&C |
| 9061737b3e3cb6dae0a02abe33346d72ccd27af4 | RatonRAT C&C |
| 75964711a6e10849d232b5df09f428a4eaa48a68 | PureRAT C&C |
| 9001ac2344ddd1b2e32f5d25b5e56b323e6fc862 | Vidar C&C |
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
- 1.117.73.220
- 1.12.36.175
- 1.12.55.80
- 1.12.70.212
- 1.14.110.231
- 1.14.240.247
- 1.14.94.193
- 1.14.97.120
- 1.15.106.134
- 1.15.14.87
- 1.15.221.192
- 1.159.54.33
- 1.162.208.58
- 1.179.209.26
- 1.187.169.38
- 1.187.76.29
- 1.20.104.8
- 1.20.172.244
- 1.212.225.99

### CINS Army (poorly-rated IPs)
- 1.14.149.30
- 1.15.14.29
- 1.177.162.2
- 1.192.129.106
- 1.193.63.62
- 1.215.43.201
- 1.221.65.174
- 1.24.16.107
- 1.24.16.131
- 1.24.16.165
- 1.24.16.167
- 1.24.16.180
- 1.24.16.188
- 1.24.16.23
- 1.24.16.24
- 1.24.16.3
- 1.24.16.37
- 1.24.16.4
- 1.24.16.40
- 1.24.16.41

## News (last ~36h, across outlets)
### The Hacker News
- [ClickFix Attackers Exploit Siemens Software Center Flaw to Deploy Remote Access Trojan](https://thehackernews.com/2026/10/clickfix-attackers-exploit-siemens.html)
- [Ex-OpenAI Engineer Detained in Spy Device Case as Saudi Royal Contacts Emerge](https://thehackernews.com/2026/10/ex-openai-engineer-detained-in-spy.html)
- [Hackers Use New ROMULUS ClickFix Platform to Deliver LegionLoader and Other Malware](https://thehackernews.com/2026/10/romulus-clickfix-platform-tricks-users.html)
- [Hackers Exploit Plex2Shell Flaws to Install Crypto Miners and Linux Proxy Backdoor](https://thehackernews.com/2026/10/hackers-exploit-plex2shell-flaws-to.html)
- [Popular WordPress SEO Plugin Rank Math PRO Hijacked to Deliver Self-Restoring Backdoor](https://thehackernews.com/2026/10/popular-wordpress-seo-plugin-rank-math.html)
- [⚡ Weekly Recap: 98 Zero-Days, Rogue AI Agents, $100M Crypto Theft, 700 Supermarkets Hit and More](https://thehackernews.com/2026/10/weekly-recap-98-zero-days-rogue-ai.html)
- [GhostAction Attackers Plant Credential Stealer Disguised as Font in 94 GitHub Repositories](https://thehackernews.com/2026/10/ghostaction-attackers-plant-credential.html)
- [From Email-to-Case to the Boardroom: How Inherited Agents Break Governance Built for Software](https://thehackernews.com/2026/10/from-email-to-case-to-boardroom-how.html)
- [Fake Web3 Accelerator Uses npm Packages to Spread Malware and Hijack AI Agent Traffic](https://thehackernews.com/2026/10/fake-web3-accelerator-uses-npm-packages.html)
- [Unpatched Broadcom Wi-Fi Flaw Lets Attackers in Range Run Code as Root on Routers](https://thehackernews.com/2026/10/unpatched-broadcom-wi-fi-flaw-lets.html)
- [OpenCode Console Breach May Have Exposed OpenAI, Anthropic, and Google API Keys](https://thehackernews.com/2026/10/opencode-console-breach-may-have.html)

### BleepingComputer
- [Nikkei discloses third data breach in a month, 1.8M records exposed](https://www.bleepingcomputer.com/news/security/nikkei-discloses-third-data-breach-in-a-month-18m-records-exposed/)
- [WordPress SEO plugin Rank Math compromised to backdoor websites](https://www.bleepingcomputer.com/news/security/wordpress-seo-plugin-rank-math-compromised-to-backdoor-websites/)
- [Hackers hijack AOMEI update servers to secretly spread malware](https://www.bleepingcomputer.com/news/security/hackers-hijack-aomei-update-servers-to-secretly-spread-malware/)
- [Bullhorn takes staffing platform offline to contain cyberattack](https://www.bleepingcomputer.com/news/security/bullhorn-takes-staffing-platform-offline-to-contain-cyberattack/)
- [OpenCode hack exposes API keys amid AI distillation attacks](https://www.bleepingcomputer.com/news/security/opencode-hack-exposes-api-keys-amid-ai-distillation-attacks/)
- [Microsoft fixes game, app crashes caused by recent Windows update](https://www.bleepingcomputer.com/news/microsoft/microsoft-fixes-game-app-crashes-caused-by-windows-kb5124010-preview-update/)
- [Inside the Underground Market for Know Your Client Services](https://www.bleepingcomputer.com/news/security/inside-the-underground-market-for-know-your-client-services/)
- [F5 releases out-of-band patches for critical NGINX vulnerabilities](https://www.bleepingcomputer.com/news/security/f5-releases-out-of-band-patches-for-critical-nginx-vulnerabilities/)
- [Microsoft fixes classic Outlook bug that hid Copilot buttons](https://www.bleepingcomputer.com/news/microsoft/microsoft-fixes-bug-that-hid-copilot-buttons-in-classic-outlook/)
- [Microsoft: October Windows Server updates break Exchange sign-in, mail flow](https://www.bleepingcomputer.com/news/microsoft/microsoft-october-windows-server-updates-cause-exchange-issues/)

### Krebs on Security
- [Feds Suspect Ransom Negotiator Ran ShinyHunters Extortion Site](https://krebsonsecurity.com/2026/10/feds-suspect-ransom-negotiator-ran-shinyhunters-extortion-site/)

### Dark Reading
- [Researchers Infiltrate Microsoft Tech Support Scam Operation](https://www.darkreading.com/threat-intelligence/microsoft-tech-support-scam-operation)
- ['AdFection' Turns Ad Impressions Into Zero-Click Spyware Delivery](https://www.darkreading.com/data-privacy/adfection-online-ads-spyware-delivery)
- [ConnectWise Disables Cloud Backups Amid Concerns for Downstream MSPs](https://www.darkreading.com/identity-access-management-security/connectwise-disables-cloud-backups-downstream-msps)
- [OnlyFans Copyright Takedowns Expose Compromised Websites](https://www.darkreading.com/vulnerabilities-threats/onlyfans-copyright-takedowns-expose-compromised-websites)
- [The Evolving Cybersecurity Lexicon: Vulnerability Discovery to Resilience](https://www.darkreading.com/vulnerabilities-threats/cybersecurity-lexicon-vulnerability-discovery-resilience)

### SecurityWeek
- [Siemens Software Center Vulnerability Exploited in ClickFix Malware Attacks](https://www.securityweek.com/siemens-software-center-vulnerability-exploited-in-clickfix-malware-attacks/)
- [Drupal Warns of Fast Exploitation Risk for Critical Core RCE Flaw](https://www.securityweek.com/drupal-warns-of-fast-exploitation-risk-for-critical-core-rce-flaw/)
- [Rank Math PRO WordPress Plugin Compromised in Supply Chain Attack](https://www.securityweek.com/rank-math-pro-wordpress-plugin-compromised-in-supply-chain-attack/)
- [ConnectWise Suspends Cloud Services in Response to Cyberattack](https://www.securityweek.com/connectwise-suspends-cloud-services-in-response-to-cyberattack/)
- [Plex2Shell Exploit Chain Weaponized Against Plex Servers Hours After Disclosure](https://www.securityweek.com/plex2shell-exploit-chain-weaponized-against-plex-servers-hours-after-disclosure/)
- [One Compromised Login Exposed Millions of California Students’ Records](https://www.securityweek.com/one-compromised-login-exposed-millions-of-california-students-records/)
- [Exploited Fortinet Bug Linked to Stealthy FortiGate Implant in Telecom Hack](https://www.securityweek.com/exploited-fortinet-bug-linked-to-stealthy-fortigate-implant-in-telecom-hack/)
- [MITRE ATT&CK v20 Catalogs AI Abuse, MFA Bypass, Water Utility Attacks](https://www.securityweek.com/mitre-attck-v20-catalogs-ai-abuse-mfa-bypass-water-utility-attacks/)
- [Anthropic Acquires Confidential AI Startup Opaque Systems](https://www.securityweek.com/anthropic-acquires-confidential-ai-startup-opaque-systems/)

### The Record
- [Judge denies WhatsApp’s bid to hold spyware maker in contempt for allegedly targeting users](https://therecord.media/whatsapp-denied-appeal-alleged-nso-group-violation-injunction)
- [ConnectWise suspends Cloud Backup service after supply chain attack](https://therecord.media/connectwise-suspends-cloud-backup-service-supply-chain-attack)
- [Two more Serbian opposition figures targeted with spyware, researchers say](https://therecord.media/serbia-spyware-pegasus-elections)
- [Ahold Delhaize confirms 'malicious actions' behind cyber outages affecting grocery brands](https://therecord.media/ahold-delhaize-cyberattack-grocery)
- [Russian social media giant VK faces disruptions after data center drone strike](https://therecord.media/russian-social-media-giant-vk-faces-disruptions-drone-strike-data-center)

### Infosecurity Magazine
- [Exploited Vulnerabilities Typically Take Three Months to Patch, Moody’s Finds](https://www.infosecurity-magazine.com/news/exploited-vulnerabilities-three/)
- [Conduent Agrees to Pay $80m to Settle Data Breach Class Action](https://www.infosecurity-magazine.com/news/conduent-settle-data-breach-action/)
- [OpenCode Breach Could Affect OpenAI, Anthropic and Google](https://www.infosecurity-magazine.com/news/opencode-breach-openai-anthropic/)
- [ConnectWise Shuts Off Cloud Services After ‘Unauthorized Access’ to Microsoft 365 Tenants](https://www.infosecurity-magazine.com/news/connectwise-shuts-off-cloud/)
- [US Cybersecurity Job Postings Fall 26%, Hitting Four Year Low](https://www.infosecurity-magazine.com/news/cybersecurity-job-postings-fall/)

### CyberScoop
- [Wyden seeks adoption of encryption tech at hundreds of federal agencies to protect visitors’ sensitive traffic](https://cyberscoop.com/wyden-urges-federal-adoption-encrypted-client-hello/)
- [DHS to ban DeepSeek from federal civilian agencies](https://cyberscoop.com/dhs-bans-deepseek-federal-agencies/)
- [Spyware found on devices belonging to prominent Serbian critics as elections loom](https://cyberscoop.com/pegasus-spyware-serbia-critics-elections/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
- [Threat Brief: Active Exploitation of PAN-OS CVE-2026-0257 (Updated October 19)](https://unit42.paloaltonetworks.com/active-exploitation-of-pan-os-cve-2026-0257/)

### Microsoft Security Blog
- [Agents are your newest insiders. Security must move at their speed.](https://www.microsoft.com/en-us/security/blog/2026/10/19/agents-are-your-newest-insiders-security-must-move-at-their-speed/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Tuesday, October 20th, 2026 https://isc.sans.edu/podcastdetail/10142, (Tue, Oct 20th)](https://isc.sans.edu/diary/rss/33436)

### Securelist (Kaspersky)
- [The journey of a paper unicorn: adventures inside a modern warehouse](https://securelist.com/paper-unicorn-warehouse-security/121537/)

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
- [Atlassian Arbitrary File Access Vulnerability](https://fortiguard.fortinet.com/threat-signal-report/6548)

## Fetch issues this run
_None — all sources responded._

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal