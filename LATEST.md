# Winjit Daily TI Digest — 2026-10-22

_Auto-generated. Window: last ~24h. Fetched at 2026-10-22T08:26:31.775631+00:00Z_

**At a glance:** 0 new KEV · 103 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-113744 | 10.0 | 0.6% | A security vulnerability has been detected in Tenda AC19 16.03.10.07. The impacted element is the function formSetFirewallCfg of the file /goform/SetFirewallCfg of the component httpd Web Management S |
| CVE-2026-114382 | 10.0 | n/a | A security flaw has been discovered in TOTOLINK EX200 5.2.3c.7200. This affects the function setStaticDhcpConfig of the file /cgi-bin/cstecgi.cgi of the component lan.so. The manipulation of the argum |
| CVE-2026-114383 | 10.0 | n/a | A weakness has been identified in TOTOLINK EX200 5.2.3c.7200. This impacts the function setWiFiAclAddConfig of the file /cgi-bin/cstecgi.cgi of the component wireless.so. This manipulation of the argu |
| CVE-2026-114575 | 10.0 | n/a | A flaw has been found in TOTOLINK A950RG 4.1.2cu.5268_B20221104. Affected by this issue is the function UploadCustomModule of the file lib/cste_modules/product.so. Executing a manipulation of the argu |
| CVE-2026-114268 | 9.9 | n/a | A flaw has been found in Tenda BE3L Pro 16.03.60.62. Affected by this vulnerability is the function formWifiBasicSet of the file /goform/WifiBasicSet. This manipulation of the argument security_5g cau |
| CVE-2026-113736 | 9.8 | 0.9% | A vulnerability has been found in D-Link DHP-W610AV 1.02EUb03. The impacted element is the function login_prepare_hnap of the file etc/defnodes/defaultvalue.xml of the component HNAP Login. The manipu |
| CVE-2026-114108 | 9.8 | 0.4% | HKUDS Vibe-Trading from 0.1.0 before 0.1.7 contains a missing authentication vulnerability that allows unauthenticated attackers to access the FastAPI surface because require_auth() returns early when |
| CVE-2026-114119 | 9.8 | 0.4% | Best Practice Software Bp Premier before 1.14.1.1128 uses a hardcoded Microsoft SQL Server administrative password that is shared across all installations and cannot be changed without breaking the ap |
| CVE-2026-109618 | 9.8 | n/a | PHP uses longjmp() for out-of-memory (OOM) errors to exit the current context and abort handling of the request. Some contexts may not properly account for this scenario and leave request memory in an |
| CVE-2026-109619 | 9.8 | n/a | PHP has various global state that temporarily points into request memory. In some scenarios, global state may not be correctly reset, or may be repopulated after being reset. The global state may then |
| CVE-2026-76473 | 9.8 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, engineering teams for Cisco Emergency Responder, Cisco Prime Collaboration Deployment, Cisco Unified Communications Man |
| CVE-2026-76474 | 9.8 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, engineering teams for Cisco Emergency Responder, Cisco Prime Collaboration Deployment, Cisco Unified Communications Man |
| CVE-2026-76475 | 9.3 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, engineering teams for Cisco Emergency Responder, Cisco Prime Collaboration Deployment, Cisco Unified Communications Man |
| CVE-2026-91403 | 9.1 | n/a | Vulnerability in the Oracle Java SE, Oracle GraalVM for JDK, Oracle GraalVM Enterprise Edition product of Oracle Java SE (component: JSSE).  Supported versions that are affected are Oracle Java SE: 8u |
| CVE-2026-114220 | 9.1 | n/a | NT OneAPP developed by NewType Infortech has an Improper Certificate Validation vulnerability. Unauthenticated network-adjacent attackers can perform a man-in-the-middle attack by failing to validate  |
| CVE-2026-20043 | 9.0 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, the Cisco owned Open Source Snort 3 Software engineering team has conducted a comprehensive internal security review. T |
| CVE-2026-114089 | 8.8 | 0.1% | Trigger.dev before 4.5.2 contains a cross-site request forgery vulnerability in the CLI authorization-code flow because loading /account/authorization-code/<code> mints a Personal Access Token without |
| CVE-2026-114094 | 8.8 | 0.7% | Dulwich before 1.2.9 fails to validate DOS drive letter prefixes in Git tree path elements on Windows, allowing arbitrary file write. Attackers can craft a malicious repository with a tree entry named |
| CVE-2026-114107 | 8.8 | 0.5% | HKUDS Vibe-Trading from 0.1.0 before 0.1.7 contains an indirect prompt injection vulnerability that allows remote attackers to execute shell commands as root by planting instructions in documents or w |
| CVE-2026-114109 | 8.8 | 0.4% | uv before 0.11.15 contains a path traversal vulnerability that allows malicious wheels to write files outside the scripts directory via crafted console_scripts or gui_scripts entry point names. Attack |
| CVE-2026-82814 | 8.8 | 0.5% | The Duplicator and Duplicator Pro plugins for WordPress are vulnerable to PHP Object Injection in all versions up to, and including, 1.5.17 and 4.6.10, respectively, via deserialization of untrusted d |
| CVE-2026-114387 | 8.8 | n/a | Shopper from 2.0.0 before 2.6.0 contains a missing authorization vulnerability that allows admin-panel users holding only access_dashboard to create administrators and grant permissions. Attackers can |
| CVE-2026-76476 | 8.8 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, engineering teams for Cisco Emergency Responder, Cisco Prime Collaboration Deployment, Cisco Unified Communications Man |
| CVE-2026-76477 | 8.8 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, engineering teams for Cisco Emergency Responder, Cisco Prime Collaboration Deployment, Cisco Unified Communications Man |
| CVE-2026-76478 | 8.8 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, engineering teams for Cisco Emergency Responder, Cisco Prime Collaboration Deployment, Cisco Unified Communications Man |
| CVE-2026-76291 | 8.8 | n/a | In Splunk Enterprise versions below 10.4.4, 10.2.8, 10.0.11, and 9.4.16, a user that holds a role with the schedule_search capability could bypass the expected safeguards in the scheduled search workf |
| CVE-2026-76298 | 8.8 | n/a | In Splunk Enterprise versions below 10.4.4 and 10.2.8, a user who does not hold the "admin" or "power" Splunk roles could derive the PostgreSQL sidecar database superuser password and run arbitrary op |
| CVE-2026-114658 | 8.8 | n/a | Grav Login plugin from 3.6.0 before 3.9.13 contains a missing authorization vulnerability in the login.invite task that allows page authors to obtain super user accounts. Attackers can define an invit |
| CVE-2026-114635 | 8.7 | n/a | Traefik before v2.11.58 and v3.7.14 contains an authentication bypass vulnerability in its SNI check, which is skipped when request TLS state is nil. Unauthenticated clients can send HTTP/2 requests w |
| CVE-2026-114636 | 8.7 | n/a | Traefik v3.7.13 before v3.7.14 contains an access-control bypass in the Kubernetes Ingress NGINX provider, where the HTTP router generated for ssl-passthrough Ingresses on non-TLS entry points never a |
| CVE-2026-114637 | 8.7 | n/a | Traefik from v3.2.0 before v3.7.14 contains an authentication bypass vulnerability in the experimental FastProxy connection pool, which fails to pin NTLM/Negotiate-authenticated backend connections to |
| CVE-2026-114638 | 8.7 | n/a | Traefik v3.7.0 before v3.7.14 contains an improper authentication vulnerability in the Kubernetes Ingress NGINX provider that merges client CAs when auth-tls-secret names collide after dot-to-dash nor |
| CVE-2026-114639 | 8.7 | n/a | Traefik 2.11.0 before 2.11.58 and 3.0.0 before 3.7.14 contains an authentication bypass because a first request preauthenticated with an Authorization: Negotiate token authenticates a socket in the gl |
| CVE-2026-114640 | 8.7 | n/a | Traefik from v3.7.0 before v3.7.14 contains an authentication bypass vulnerability in its Kubernetes Ingress-NGINX provider that forwards client-supplied Ssl-Client-* headers on the plaintext HTTP rou |
| CVE-2026-114642 | 8.7 | n/a | Traefik 2.11.0 before 2.11.58 and 3.0.0 before 3.7.14 stores its NTLM/Kerberos backend round tripper in a client-connection slot not keyed by ServersTransport, so one service's TLS client configuratio |
| CVE-2026-76490 | 8.6 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, the Cisco Expressway Series software engineering team has conducted a comprehensive internal security review. This revi |
| CVE-2026-114661 | 8.5 | n/a | OpenRemote 1.2.0 before 1.31.0 contains a missing authorization vulnerability in GatewayServiceResource that allows any authenticated user to start, stop and query gateway tunnels without an administr |
| CVE-2026-114663 | 8.4 | n/a | Vyper 0.4.0b1 through 0.5.0b1 miscompiles unfoldable constants and omitted default arguments from imported modules, because parse_Name resolves their names in the using function's scope rather than at |
| CVE-2026-114068 | 8.3 | 0.3% | Trigger.dev before 4.6.0 contains a missing authorization vulnerability in the waitpoint token wait endpoint that allows authenticated attackers to block runs belonging to other organizations. Attacke |
| CVE-2026-114053 | 8.1 | 0.5% | vLLM from 0.7.3 before 0.31.0 forwards the request-supplied mm_processor_kwargs.code_revision to Transformers AutoProcessor.from_pretrained, letting clients select which revision of a model's dynamic  |
| CVE-2026-114066 | 8.1 | 0.3% | Trigger.dev before 4.7.0 contains a missing authorization vulnerability that allows holders of unrestricted environment API keys to block runs they do not own by supplying a foreign parentRunId to bat |
| CVE-2026-114069 | 8.1 | 0.3% | Trigger.dev before 4.6.0 contains an improper authorization vulnerability in the GET /api/v1/projects/:projectRef/envvars endpoint, which returns the environment's root API key as TRIGGER_SECRET_KEY f |
| CVE-2026-114078 | 8.1 | 0.3% | Trigger.dev before 4.5.6 contains an authorization bypass vulnerability in DeleteTaskScheduleService and SetActiveOnTaskScheduleService that allows authenticated users to delete or disable other organ |
| CVE-2026-114082 | 8.1 | 0.3% | Trigger.dev before 4.6.2 contains an authorization vulnerability that allows public-token holders with session write access to obtain environment-wide S2 stream credentials via session input initializ |
| CVE-2026-114083 | 8.1 | 0.4% | Trigger.dev before 4.5.0-rc.3 contains a path traversal vulnerability in the api/v1/packets and api/v2/packets endpoints that allows authenticated tenants to escape their object key prefix through an  |
| CVE-2026-114087 | 8.1 | 0.3% | Trigger.dev before 4.5.6 self-hosted Docker Compose deployments using the default secrets from hosting/docker/.env.example allow authentication bypass because the hardcoded MAGIC_LINK_SECRET lets anyo |
| CVE-2026-114403 | 8.1 | n/a | PHPOffice PHPPresentation through 1.2.0 contains an insecure deserialization vulnerability that allows attackers to instantiate arbitrary PHP objects by supplying a crafted presentation file. Attacker |
| CVE-2026-114662 | 8.1 | n/a | Obot before 0.26.0 contains an authentication bypass vulnerability in the CLI login flow that allows unauthenticated attackers to steal API keys by choosing token request IDs. Attackers can create a t |
| CVE-2026-114096 | 7.8 | 0.2% | Dulwich from 0.24.0 before 1.2.8 contains a symlink following vulnerability in porcelain.checkout(paths=[...]) that allows attackers to write arbitrary files by abusing raw os.open without O_NOFOLLOW. |
| CVE-2026-114097 | 7.8 | 0.2% | Dulwich from 0.23.1 before 1.2.8 contains a path traversal vulnerability in CommitFilter._apply_index_filter() that allows attackers to write files outside the working directory via symlinks persistin |
| CVE-2026-114098 | 7.8 | 0.2% | Dulwich from 0.22.5 before 1.2.8 contains a path traversal vulnerability in stash.py pop() that allows attackers to write arbitrary files outside the worktree through intermediate directory symlinks.  |
| CVE-2026-20291 | 7.8 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, the Cisco owned Open Source Snort 3 Software engineering team has conducted a comprehensive internal security review. T |
| CVE-2026-76479 | 7.8 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, engineering teams for Cisco Emergency Responder, Cisco Prime Collaboration Deployment, Cisco Unified Communications Man |
| CVE-2026-76494 | 7.8 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, the Cisco Expressway Series software engineering team has conducted a comprehensive internal security review. This revi |
| CVE-2026-76495 | 7.8 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, the Cisco Expressway Series software engineering team has conducted a comprehensive internal security review. This revi |
| CVE-2026-76524 | 7.8 | n/a | A vulnerability in the control channel socket implementation of&nbsp;Open Source Snort 3 could allow an authenticated, local attacker with low privileges to execute arbitrary commands as the Snort 3 p |
| CVE-2026-114081 | 7.7 | 0.3% | Trigger.dev before 4.5.6 contains an SQL injection vulnerability in the TSQL query compiler, which concatenates window-function names into generated ClickHouse SQL without allowlisting or escaping. Au |
| CVE-2026-114084 | 7.7 | 0.3% | Trigger.dev before 4.5.6 contains an SQL injection vulnerability in the /realtime/v1/runs endpoint, which concatenates the unescaped tags query parameter into the ElectricSQL shape where clause and de |
| CVE-2026-114051 | 7.5 | 0.4% | vLLM before 0.31.0 skips the min_tokens <= max_tokens check for /inference/v1/generate requests with a null max_tokens, so the EngineCore input thread later dies on an uncaught VLLMValidationError whi |
| CVE-2026-114052 | 7.5 | 0.4% | vLLM after 0.24.0 and before 0.31.0 contains a memory exhaustion vulnerability in MOSS-Audio model serving that caches a processor for every distinct request-controlled mm_processor_kwargs value in an |
| CVE-2026-114059 | 7.5 | 0.4% | ArcadeDB before 26.10.1 contains a remote code execution vulnerability that allows authenticated users, including read-only reader role holders, to execute Groovy code because GremlinQueryEngine.comma |
| CVE-2026-114063 | 7.5 | 0.4% | SvelteKit (@sveltejs/kit) from 2.10.0 before 3.0.0 contains a path traversal vulnerability in the vite preview server on Windows that allows unauthenticated attackers to read files outside the prerend |
| CVE-2026-114102 | 7.5 | 0.3% | adm-zip before 0.6.1 contains a denial of service vulnerability that allows unauthenticated attackers to crash the Node.js process via a malformed ZIP file, because inflateAsync in methods/inflater.js |
| CVE-2026-114106 | 7.5 | 0.4% | HKUDS Vibe-Trading from 0.1.0 before 0.1.7 contains a path traversal vulnerability that allows remote attackers to read sensitive server files through LLM agent file-read tools. Attackers can prompt t |
| CVE-2026-20236 | 7.5 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, the Cisco owned Open Source Snort 3 Software engineering team has conducted a comprehensive internal security review. T |
| CVE-2026-20356 | 7.5 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, the Cisco owned Open Source Snort 3 Software engineering team has conducted a comprehensive internal security review. T |
| CVE-2026-76491 | 7.5 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, the Cisco Expressway Series software engineering team has conducted a comprehensive internal security review. This revi |
| CVE-2026-76492 | 7.5 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, the Cisco Expressway Series software engineering team has conducted a comprehensive internal security review. This revi |
| CVE-2026-76493 | 7.5 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, the Cisco Expressway Series software engineering team has conducted a comprehensive internal security review. This revi |
| CVE-2026-76505 | 7.5 | n/a | A vulnerability in the IPv4 packet processing functionality of Cisco IOS XR Software that affects Cisco ASR 9000 and 9900 Series Aggregation Services Routers as well as Cisco ASR 9902 and 9903 Compact |
| CVE-2026-76288 | 7.5 | n/a | In Splunk Enterprise versions below 10.4.4, 10.2.8, 10.0.11, and 9.4.16, an unauthenticated user could send a single crafted request to the Splunk Web JavaScript logger endpoint and cause Splunk Web t |
| CVE-2026-76290 | 7.5 | n/a | In Splunk Enterprise versions below 10.4.4, 10.2.8, and 10.0.11, an unauthenticated user could send repeated requests to the Edge Processor package download endpoint in the Splunk Pipeline Builders ap |
| CVE-2026-76306 | 7.5 | n/a | In Splunk SOAR versions below 8.7.0, a user that has the "Observer" role could use query filters in the Representational State Transfer (REST) API to infer password hashes and authorization tokens for |
| CVE-2026-114656 | 7.5 | n/a | Traefik before 2.11.58 and 3.7.13 contains an authentication bypass vulnerability that allows unauthenticated clients to skip client-certificate checks because negated Host matchers are counted as ser |
| CVE-2021-48018 | 7.4 | 0.3% | Vyper from 0.2.13 before 0.2.15 allocates storage slots for @nonreentrant reentrancy locks at the same locations as contract storage variables. When a function using @nonreentrant is called, setting t |
| CVE-2026-114397 | 7.4 | n/a | Trudesk through 1.2.11 contains a missing authentication vulnerability in debug routes enabled whenever NODE_ENV is unset, letting unauthenticated attackers invoke them remotely. Attackers can call /d |
| CVE-2026-89035 | 7.4 | n/a | MikroTik RouterOS through 7.24.5 contains a session token replay vulnerability in the WebFig interface that allows attackers to bypass authentication by replaying captured session tokens across new EC |
| CVE-2026-114219 | 7.4 | n/a | NT OneAPP developed by NewType Infortech has a Hard-coded Credentials vulnerability. Unauthenticated remote attackers can obtain the hard-coded cryptographic key and decrypt login request contents, th |
| CVE-2026-114221 | 7.4 | n/a | NT OneAPP developed by NewType Infortech has a Credential Disclosure vulnerability. Unauthenticated remote attackers can trigger an HTTP Basic Authentication challenge from an unvalidated source in th |
| CVE-2026-114242 | 7.3 | n/a | A vulnerability was identified in dhikshitha29 Insurance-Management-System 91de5edda5baa109ad8e9baf03ce6a3ceda84183/125362cc21dca20d74091a4913a5096bb58dd837. Affected is the function mysqli_query of t |
| CVE-2026-114243 | 7.3 | n/a | A security flaw has been discovered in dhikshitha29 Insurance-Management-System 91de5edda5baa109ad8e9baf03ce6a3ceda84183/125362cc21dca20d74091a4913a5096bb58dd837. Affected by this vulnerability is the |
| CVE-2026-114249 | 7.3 | n/a | A vulnerability was detected in dhikshitha29 Insurance-Management-System 91de5edda5baa109ad8e9baf03ce6a3ceda84183/125362cc21dca20d74091a4913a5096bb58dd837. This vulnerability affects unknown code of t |
| CVE-2026-114254 | 7.3 | n/a | A vulnerability was identified in oretnom23 file-management-system-php up to 2e3c1ebe60f121e8df4fb3f544f0e9591d9a01e4. This affects the function Login of the file admin_class.php. The manipulation of  |
| CVE-2026-114255 | 7.3 | n/a | A security flaw has been discovered in oretnom23 file-management-system-php up to 2e3c1ebe60f121e8df4fb3f544f0e9591d9a01e4. This impacts the function save_user of the file admin_class.php of the compo |
| CVE-2026-114256 | 7.3 | n/a | A weakness has been identified in oretnom23 file-management-system-php up to 2e3c1ebe60f121e8df4fb3f544f0e9591d9a01e4. Affected is the function save_folder/delete_folder/delete_file/file_rename/save_f |
| CVE-2026-114257 | 7.3 | n/a | A security vulnerability has been detected in oretnom23 file-management-system-php up to 2e3c1ebe60f121e8df4fb3f544f0e9591d9a01e4. Affected by this vulnerability is the function readfile of the file d |
| CVE-2026-114258 | 7.3 | n/a | A vulnerability was detected in oretnom23 file-management-system-php up to 2e3c1ebe60f121e8df4fb3f544f0e9591d9a01e4. Affected by this issue is some unknown functionality of the file files.php of the c |
| CVE-2026-114259 | 7.3 | n/a | A flaw has been found in oretnom23 file-management-system-php up to 2e3c1ebe60f121e8df4fb3f544f0e9591d9a01e4. This affects the function save_files of the file admin_class.php. Executing a manipulation |
| CVE-2026-114261 | 7.3 | n/a | A vulnerability was found in MomoTommy file-management-system dc9ce1bf27f94b23d906cb1e86ce374dc94ca5df. This issue affects the function index/store/update/destroy of the file app/Http/Controllers/File |
| CVE-2026-114262 | 7.3 | n/a | A vulnerability was determined in file-management-system dc9ce1bf27f94b23d906cb1e86ce374dc94ca5df. Impacted is the function store of the file app/Http/Controllers/FileController.php. This manipulation |
| CVE-2026-114263 | 7.3 | n/a | A vulnerability was identified in ProjectWorlds Advanced Library Management System 1.0. The affected element is the function mysqli_query of the file individual_report_search.php. Such manipulation of |
| CVE-2026-114267 | 7.3 | n/a | A vulnerability was detected in SourceCodester Food Order Management System 1.0. Affected is an unknown function of the component Admin Endpoint. The manipulation results in missing authorization. The |
| CVE-2026-114439 | 7.3 | n/a | A vulnerability was determined in oretnom23 php-travel-agency-system. Affected by this issue is some unknown functionality of the file admin/session.php of the component Session Handler. Executing a m |
| CVE-2026-114440 | 7.3 | n/a | A vulnerability was identified in oretnom23 php-travel-agency-system. This affects an unknown part of the file admin/delete.php. The manipulation of the argument costomer_id/ticket_id/payment_id/id/do |
| CVE-2026-114441 | 7.3 | n/a | A weakness has been identified in oretnom23 php-travel-agency-system. This issue affects some unknown processing of the file admin/update.php. This manipulation of the argument action/full_name/visa_n |
| CVE-2026-114577 | 7.3 | n/a | A vulnerability was found in oretnom23 php-travel-agency-system. This vulnerability affects unknown code of the file admin/insert.php of the component Insertion Handler. The manipulation of the argume |
| CVE-2026-110744 | 7.2 | n/a | A flaw was found in multicluster-global-hub-operator-bundle. The operator is configured with overly broad role-based access control (RBAC) permissions that grant cluster-wide impersonation of arbitrar |
| CVE-2026-29001 | 7.2 | n/a | TastyIgniter through 4.4.5 contain a PHP object injection vulnerability that allows authenticated administrators to achieve arbitrary code execution by submitting a serialized PHP object as a settings |
| CVE-2026-76293 | 7.2 | n/a | In Splunk Enterprise versions below 10.4.3, 10.2.8, 10.0.11, and 9.4.16, a user that holds a role with the edit_manager_xml capability could execute arbitrary operating-system commands using the permi |
| CVE-2026-76307 | 7.2 | n/a | In Splunk SOAR versions below 8.7.0, a user that holds a role with the Users and Roles view permission could use the Representational State Transfer (REST) API to infer authentication token values for |
| CVE-2026-114077 | 7.1 | 0.2% | Trigger.dev before 4.5.6 contains an authorization bypass vulnerability in createDeploymentBackgroundWorkerV4 that resolves a WorkerDeployment by friendlyId alone, without environment, project, or org |
| CVE-2026-114664 | 7.1 | n/a | Frappe Framework before 16.33.0 contains a blind SQL injection vulnerability in the frappe.desk.doctype.event.event.get_events method, which fails to properly neutralize user-supplied input before inc |
| CVE-2026-76496 | 7.0 | n/a | As part of Cisco's ongoing commitment to proactive security and product quality, the Cisco Expressway Series software engineering team has conducted a comprehensive internal security review. This revi |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-rhhx-6v4c-mf5v | CVE-2026-78392 | unknown | The Link Library WordPress plugin before 7.9.6 does not sanitise and escape a link field before... |
| GHSA-3hr8-rx2p-fg8c | CVE-2026-97328 | unknown | The WebP Express WordPress plugin before 0.25.16 does not escape values that its bundled HTML... |
| GHSA-x2jm-76mq-q2pc | CVE-2026-88849 | unknown | The MasterStudy LMS WordPress Plugin  WordPress plugin before 3.7.55 does not verify that a user... |
| GHSA-v6pr-7m68-qg32 | CVE-2026-114570 | medium | WordPress Core is vulnerable to Stored Cross-Site Scripting via Quick Edit in all versions up to,... |
| GHSA-fqh5-mr22-f9g4 | CVE-2026-109927 | unknown | The HIPAA Forms WordPress plugin before 3.3.2 does not perform a capability check when handling a... |
| GHSA-m595-x4xx-r4vx | CVE-2026-100142 | unknown | The FluentCart A New Era of eCommerce  WordPress plugin before 2.2.0 does not verify that a... |
| GHSA-47v3-4v4g-79h5 | CVE-2026-111972 | unknown | The Photo Engine (Media Organizer & Lightroom) WordPress plugin before 6.5.8 does not verify that... |
| GHSA-9g52-cg59-7f5p | CVE-2026-111971 | unknown | The Photo Engine (Media Organizer & Lightroom) WordPress plugin before 6.5.8 does not sanitise... |
| GHSA-cv43-3m98-pxjc | CVE-2026-109931 | unknown | The Infility Global WordPress plugin before 2.16.25 does not perform any authorisation or nonce... |
| GHSA-r9xx-rhcx-ph2x | CVE-2026-110011 | unknown | The MB Custom Post Types & Custom Taxonomies WordPress plugin before 2.12.3 does not perform a... |
| GHSA-vwmv-9mxc-35hf | CVE-2026-109987 | unknown | The PixelYourSite  WordPress plugin before 11.4.3, PixelYourSite Pro WordPress plugin before 12.6... |
| GHSA-5h77-wc4p-vj34 | CVE-2026-111958 | unknown | The Royal MCP  WordPress plugin before 1.5.7 does not limit a preview-link token to the single... |
| GHSA-95fw-7pmc-68c4 | CVE-2026-110010 | unknown | The MB Custom Post Types & Custom Taxonomies WordPress plugin before 2.12.3 does not perform any... |
| GHSA-mq79-9v7w-xc5w | CVE-2026-103234 | unknown | The WP Ultimate Review WordPress plugin before 2.4.5 does not neutralise shortcodes in all of the... |
| GHSA-3g57-fjv2-jxx4 | CVE-2026-114222 | medium | NT OneAPP developed by NewType Infortech has an Authentication Bypass vulnerability.... |
| GHSA-899f-6cww-cvcv | CVE-2026-114223 | medium | NT OneAPP developed by NewType Infortech has an Exposure of Sensitive Information vulnerability.... |
| GHSA-q6g4-8jxr-rp9c | CVE-2026-114219 | critical | NT OneAPP developed by NewType Infortech has a Hard-coded Credentials vulnerability.... |
| GHSA-j3f5-7crv-v65c | CVE-2026-114220 | critical | NT OneAPP developed by NewType Infortech has an Improper Certificate Validation vulnerability.... |
| GHSA-w9gq-v5qh-882r | CVE-2026-114221 | medium | NT OneAPP developed by NewType Infortech has a Credential Disclosure vulnerability.... |
| GHSA-qc6m-xxcv-cwh2 | CVE-2026-114732 | medium | Roundcube Webmail before 1.6.20 and 1.7.x before 1.7.5 is affected by an improper authentication... |
| GHSA-38c9-3phj-gg36 | CVE-2026-114729 | medium | Roundcube Webmail before 1.6.20 and 1.7.x before 1.7.5 is affected by a remote content blocking... |
| GHSA-mpw2-q5qr-3w4j | CVE-2026-114731 | medium | Roundcube Webmail before 1.6.20 and 1.7.x before 1.7.5 is affected by an uncontrolled resource... |
| GHSA-8f6h-w7cq-8q8h | CVE-2026-114730 | high | Roundcube Webmail 1.6.14 before 1.6.20 and 1.7.0 before 1.7.5 is affected by a server-side... |
| GHSA-vqpp-w68q-p3f5 | CVE-2026-110354 | high | HAProxy 3 before 3.4.6 allows a remote unauthenticated attacker to cause a denial of service ... |
| GHSA-xxh3-46q2-4vrc | CVE-2026-96392 | unknown | Improper Neutralization of Special Elements Used in a Template Engine vulnerability in Drupal AI... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Linebarger Goggan Blair & Sampson | everest | US | 2026-10-22T03:36:22.187070+00:00 |
| K.r.a. ...s | SilentRansomGroup |  | 2026-10-22T01:30:31.743420+00:00 |
| Gräfliches Hofbrauhaus Freising | lamashtu | DE | 2026-10-22T00:45:12.522650+00:00 |
| VERGI Muenster | lamashtu | DE | 2026-10-22T00:44:36.019322+00:00 |
| Heritage Senior Living | N0n | US | 2026-10-21T23:56:37.985836+00:00 |
| FuG-Gruppe | lamashtu | DE | 2026-10-21T23:12:19.257551+00:00 |
| MECA-PRECIS | lamashtu | FR | 2026-10-21T23:11:42.083695+00:00 |
| WEPOS Chemie | lamashtu | DE | 2026-10-21T23:11:03.071755+00:00 |
| bereskinparr.com smartbiggar.ca | incransom | CA | 2026-10-22T02:15:06.971498+00:00 |
| K.r.. ...s | SilentRansomGroup |  | 2026-10-21T21:08:32.977462+00:00 |
| novagroupgbc.com | BrainCipher | GB | 2026-10-21T20:55:59.593611+00:00 |
| oflaherty-law.com | BrainCipher | IE | 2026-10-21T20:55:23.367768+00:00 |
| clinicaromero.com | BrainCipher | AR | 2026-10-21T20:54:47.561918+00:00 |
| sodali.com | BrainCipher | US | 2026-10-21T20:54:08.535201+00:00 |
| srsnodgrass.com | BrainCipher | US | 2026-10-21T20:53:28.795043+00:00 |
| prosomnus.com | BrainCipher | US | 2026-10-21T20:52:52.404024+00:00 |
| olyortho.com | BrainCipher | US | 2026-10-21T20:52:16.151344+00:00 |
| mvjllp.com | BrainCipher |  | 2026-10-21T20:51:40.629098+00:00 |
| Hanjin Information Systems & Telecommunication Co., Ltd. | N0n | KR | 2026-10-21T19:54:47.947489+00:00 |
| Coastal Alabama Community College | interlock | US | 2026-10-21T19:29:49.091231+00:00 |

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
| 58.182.58.128 | 10 |
| 77.90.185.20 | 10 |
| 80.94.95.115 | 10 |
| 152.32.225.117 | 10 |
| 160.250.132.238 | 10 |
| 2.57.122.238 | 9 |
| 45.43.36.172 | 9 |
| 45.148.10.141 | 9 |
| 46.151.178.14 | 9 |
| 66.132.195.104 | 9 |
| 80.94.95.116 | 9 |
| 103.159.2.113 | 9 |
| 107.150.123.48 | 9 |
| 167.94.146.54 | 9 |
| 167.94.146.59 | 9 |
| 169.239.75.138 | 9 |
| 195.178.110.228 | 9 |
| 216.180.246.143 | 9 |

### OpenPhish (live phishing URLs)
- https://www.anz-internetbanking.blogspot.com/
- http://www.authenticateuseridentity.vercel.app/
- https://aminu-gal-expenses.netlify.app/
- http://sp28ct-dureq-biz-qamel-ranek.pages.dev/
- https://sp26ct10-zulvako-biz-taremi.pages.dev/
- https://lfax-y8p8-5gbqr3-l2gc4j-89bu.pages.dev/
- https://sp28ct-garem-biz-zumel-qitek.pages.dev/
- https://murvik-tensha-e4a8d1-gb1504hh-h2406wne.pages.dev/
- http://sp24ct-nelo-biz-kavor-muki.pages.dev/
- http://qavfari-mpt-xelzoro-k6d3pe95.pages.dev/
- http://b00j6-ec8l0f-kv2u-vfpn-tn4.pages.dev/
- http://sp20ct10-korvemo-biz-lunati.pages.dev/
- https://index-catty-neww.vercel.app/
- http://sp28ct-dunav-biz-zorel-qatek.pages.dev/
- http://sp28ct-fanur-biz-qozem-vitek.pages.dev/
- https://sp28ct-vunor-biz-qalem-zirek.pages.dev/
- http://sp26ct10-davmelo-biz-kunati.pages.dev/
- https://sp26ct10-melvemi-biz-dunaro.pages.dev/
- http://sp26ct10-rumrako-biz-lumeni.pages.dev/
- https://sp26ct10-velvako-biz-kumari.pages.dev/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://marviel.cfd/LOGIN/#/index |
| N/A | https://aexshorthood.cactx5.info/2ymmlo/hepe |
| N/A | https://away.vk.ru/away.php?rh=0345a4bb-0023-4208-a6f6-c0bc1a8f19cc |
| N/A | https://vercel.com/login?next=%2Fsso-api%3Furl%3Dhttps%253A%252F%252Finterface-uniswap.vercel.app%252F%26nonce%3D075b953ad0adf80efa4be00066bbf7082182804c41537885a9b5100223ed9f6d |
| N/A | https://away.vk.ru/away.php?rh=6310a8da-5f51-4a72-8dc9-e3ae6a109c60 |
| N/A | https://away.vk.ru/away.php?rh=77a89a3f-e23d-422a-9a49-eccf82355964 |
| N/A | https://pageseuc1.actmkt.com/(S(v3tbshwf3r4az1xxveyzfqpv))/l/c5X8MfZz6j9Y7Fto3LAd |
| N/A | https://41brtx.share-na2.hsforms.com/2BvjHv7K_S5y9Rn6E3_IlcQ |
| N/A | https://away.vk.ru/away.php?rh=b3412063-356e-4ac2-a271-50a38dc65c45 |
| N/A | https://away.vk.ru/away.php?rh=4d86c81e-299c-4e35-90e6-d10bc5a121fc |
| N/A | https://away.vk.ru/away.php?rh=891003d1-cf17-40e4-bb44-b9b09cce7a3d |
| N/A | https://prime-clients-be.com/index.php |
| 4.8 | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AQMjQ7TPKu6R4w93VRXMPKeD3zeOl4EoNrOdcsDBPMv7m30JK47iKcBvHB2Y608BaGxX8bX4kwt6sA&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SQkU12tbFCo9V93QhlLU3bgY-kLS4wLAJoneMhCXVmjvyXhtE0HvuROThN-DcnVnKMQitOOTg&dsh=S369322616%3A1792652412404830 |
| N/A | https://2fjf69.share-eu1.hsforms.com/2A1lEkELGQaCl24Ck9MBMfQ |
| N/A | https://yandex.ru/showcaptcha?cc=1&form-fb-hint=2.1&mt=C2EE0C67D70DF2E344800894603C7440980E91735639110C9DFD4BFC2498CEE123E30496502EF2D18868648888AB1BC34CDA98C3E2E3C835849F35C5614C47DBB025833B11735C1F18C447AFA43B0EF720BB03BA1EA832B8A4985EB16C872A4923A29EBB48AFECAF3015B92EA20FE011C51505CF56D3E00A1CEA5C4DF275F44F1F70563D8F858CCFD8&retpath=aHR0cHM6Ly95YW5kZXgucnUvc2VhcmNoP3RleHQ9MjExNjg3MTc%2C_9e32ea590f1152ceb4677b92f96f1e0c&t=2%252F1792651980%252Fa68fa022c94e12e3023832a8a5ac3507&u=9622373488597846614&s=4cbfeaa2e446595073e915952bea1fd1 |
| N/A | https://apps-uuser433accepts.start.page/ |
| 7.7 | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AaSxoQyQ_ZSuXpSvue0UfKrOXnU6mQAuN0RcLmvWGTqSCzhKlOsPyDT7wQQH6ra2Rhdw1PE87iTB&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SRkQessjzU6jtJlAqvPnQeKUv4-6eOsCLHYfXn-lgsrxqG7gPorXRjTbxzIaFm7r_ftgO7Fyg&dsh=S556430177%3A1792651810300291 |
| N/A | https://away.vk.ru/away.php?rh=bd1efd4c-6551-470d-9f4b-23a04e05caed |
| N/A | https://xml-v4.pushub.net/click?i=kDigrfMKviI_0 |
| N/A | https://away.vk.ru/away.php?rh=c2594cee-266a-47cc-84f6-bcd28ea8caec |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
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
| 5c5c6ce618ac3209dcb239bafd6151d86ca490b4 | OffLoader C&C |
| 107c3b396e9e46f137c02484e2fdcf9b59d99daa | QuasarRAT C&C |
| 498a4921e2950bf327566b8bc94ebe88188ba48e | Meterpreter C&C |
| c0af8a04dbfca38a9c436cac6afe37edf603a2a8 | Malware C&C |
| 891676e8c7f77b79942835d2079e1ea1bcb6a7ae | PureRAT C&C |

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
- 1.10.160.143
- 1.117.72.220
- 1.12.36.175
- 1.12.48.131
- 1.12.55.42
- 1.12.55.80
- 1.14.240.247
- 1.14.94.193
- 1.14.97.120
- 1.15.106.134
- 1.15.14.87
- 1.15.179.199
- 1.15.30.237
- 1.152.109.139
- 1.159.54.33
- 1.162.208.58
- 1.174.232.253
- 1.179.44.7
- 1.212.225.99
- 1.214.214.114

### CINS Army (poorly-rated IPs)
- 1.12.229.231
- 1.145.89.105
- 1.168.172.140
- 1.183.41.171
- 1.188.100.173
- 1.214.29.155
- 1.215.43.201
- 1.221.65.174
- 1.24.16.111
- 1.24.16.134
- 1.24.16.139
- 1.24.16.151
- 1.24.16.182
- 1.24.16.35
- 1.24.16.42
- 1.24.16.59
- 1.24.16.88
- 1.24.16.98
- 1.24.16.99
- 1.24.24.66

## News (last ~36h, across outlets)
### The Hacker News
- [China-Linked Hackers Use ARTEX AI Agents in ConnectWise Supply Chain Attack](https://thehackernews.com/2026/10/china-linked-hackers-use-artex-ai.html)
- [Critical GitLab Flaw (CVSS 10.0) Could Allow Unauthenticated RCE Across 12 Years of Releases](https://thehackernews.com/2026/10/critical-gitlab-flaw-cvss-100-could.html)
- [LiteLLM Compromised in Supply Chain Attack Delivering Credential Stealer and Backdoor](https://thehackernews.com/2026/10/litellm-compromised-in-supply-chain.html)
- [OpenAI's GPT-6 Agent Removed Safety Monitoring, Then Falsely Denied Doing So](https://thehackernews.com/2026/10/openais-gpt-6-agent-removed-safety.html)
- [PHP Issues Emergency Patches for Two Critical PHP2Shell RCE Flaws as Exploit Attempts Emerge](https://thehackernews.com/2026/10/php-issues-emergency-patches-for-two.html)
- [Google Chrome Adds ClickFix Warnings to Stop Users From Running Malicious Commands](https://thehackernews.com/2026/10/google-chrome-adds-clickfix-warnings-to.html)
- [China-Aligned Bronze Sandcastle Abuses Sandboxie DLL Sideloading to Deploy Backdoors](https://thehackernews.com/2026/10/china-aligned-bronze-sandcastle-abuses.html)
- [Generative AI Is Erasing Behavioral Tells, Weakening Behavior-Only Detection, Proofpoint Reports](https://thehackernews.com/2026/10/generative-ai-is-erasing-behavioral.html)
- [PHP2Shell: What Actually Protects You Before the 14:00 UTC PHP RCE Patch, and What Doesn't](https://thehackernews.com/2026/10/php2shell-what-actually-protects-you.html)
- [The Harness Is the Hard Part of Agentic Pentesting](https://thehackernews.com/2026/10/the-harness-is-hard-part-of-agentic.html)
- [Attackers Hijacked Over 300 Tor Exit Relays to Intercept SSH Connections](https://thehackernews.com/2026/10/attackers-hijacked-over-300-tor-exit.html)
- [PHP2Shell: Two Unpatched Critical PHP RCE Flaws (CVSS 9.2) Trigger Emergency Security Alert](https://thehackernews.com/2026/10/php2shell-two-unpatched-critical-php.html)
- [Attackers Abuse UpdraftCentral Keys to Plant Backdoors on WordPress Sites](https://thehackernews.com/2026/10/attackers-abuse-updraftcentral-keys-to.html)
- [U.S. Orders DeepSeek Removed From Federal Civilian Systems, Bans New Purchases](https://thehackernews.com/2026/10/us-orders-deepseek-removed-from-federal.html)
- [State Bank of India Confirms Data Leak After 3,897 Customer Records Found on Dark Web](https://thehackernews.com/2026/10/state-bank-of-india-confirms-data-leak.html)

### BleepingComputer
- [Google Chrome adds Gemini-powered scam detection, warns users of ClickFix attacks](https://www.bleepingcomputer.com/news/google/google-chrome-adds-gemini-powered-scam-detection-warns-users-of-clickfix-attacks/)
- [Japan's Onamae Desktop Cloud hacked, up to 27,000 servers affected](https://www.bleepingcomputer.com/news/security/japans-onamae-desktop-cloud-hacked-up-to-27-000-servers-affected/)
- [Lazarus hackers use post-quantum cryptography for malware delivery](https://www.bleepingcomputer.com/news/security/lazarus-hackers-use-post-quantum-cryptography-for-malware-delivery/)
- [CISA: Hackers chain Plex flaws in Plex2Shell attacks to breach servers](https://www.bleepingcomputer.com/news/security/cisa-hackers-chain-plex-flaws-in-plex2shell-attacks-to-breach-servers/)
- [OpenAI agents disabled safety monitoring, one lied about it](https://www.bleepingcomputer.com/news/security/openai-agents-disabled-safety-monitoring-one-lied-about-it/)
- [PHP ships emergency patches for critical PHP2Shell flaws](https://www.bleepingcomputer.com/news/security/php-ships-emergency-patches-for-critical-php2shell-flaws/)
- [ClickFix has never been bigger, and AI tools are its most convincing lure yet](https://www.bleepingcomputer.com/news/security/clickfix-has-never-been-bigger-and-ai-tools-are-its-most-convincing-lure-yet/)
- [Microsoft PowerToys adds CursorHide, Button Lock mouse tools](https://www.bleepingcomputer.com/news/microsoft/microsoft-powertoys-adds-cursorhide-button-lock-mouse-tools/)
- [Microsoft says October updates didn’t actually fix VPN issues](https://www.bleepingcomputer.com/news/microsoft/microsoft-didnt-actually-fix-vpn-issues-caused-by-windows-updates/)
- [CISA: SafePay ransomware hit over 600 critical infrastructure orgs](https://www.bleepingcomputer.com/news/security/cisa-and-fbi-safepay-ransomware-has-hit-over-600-critical-infrastructure-organizations/)
- [Stolen UpdraftCentral keys used to backdoor WordPress sites](https://www.bleepingcomputer.com/news/security/stolen-updraftcentral-keys-used-to-backdoor-wordpress-sites/)
- [Mozilla, Google, Apple block compromised eMudhra CA certificates](https://www.bleepingcomputer.com/news/security/mozilla-google-apple-block-compromised-emudhra-ca-certificates/)
- [PHP warns admins of two critical flaws, emergency patches coming tomorrow](https://www.bleepingcomputer.com/news/security/php-warns-admins-of-two-critical-flaws-emergency-patches-coming-tomorrow/)

### Krebs on Security
- [Widespread PHP Flaw May Cause Many Site Outages Today](https://krebsonsecurity.com/2026/10/widespread-php-flaw-may-cause-many-site-outages-today/)

### Dark Reading
- [UAE Transitions 50% of Gov't Services to Agentic AI](https://www.darkreading.com/cybersecurity-operations/uae-transitions-50-government-services-agentic-ai)
- [TiDB Breach Exposes Flawed Cloud Security Assumptions](https://www.darkreading.com/cloud-security/tidb-breach-flawed-cloud-security)
- [Marvell, Microsoft &amp; Oracle Work to Standardize Data Center Hardware Security](https://www.darkreading.com/cloud-security/marvell-microsoft-oracle-standardize-data-center-hardware-security)
- [Cloud Security Alliance Survey Finds Data Loss Prevention Often Detects Data Loss Only After It Happens](https://www.darkreading.com/cloud-security/cloud-security-alliance-survey-data-loss-prevention-detects-data-loss)
- ['PHP2Shell' Bugs Signal Red Alert for Security Industry](https://www.darkreading.com/application-security/php2shell-bugs-red-alert-security-industry)
- [OVHcloud GitHub Compromise Tied to GlassWorm Threat Actors](https://www.darkreading.com/cyberattacks-data-breaches/ovhcloud-github-compromise-glassworm-threat-actors)
- [Optiv Launches CyberBOT Cybersecurity Awareness Training Program](https://www.darkreading.com/cybersecurity-operations/optiv-launches-cyberbot-cybersecurity-awareness-training-program)
- [Survey Finds High-Profile Executives Feel Untouchable as Digital Exposure Turns Into Physical Risk](https://www.darkreading.com/cybersecurity-operations/360-privacy-survey-high-profile-executives-feel-untouchable)
- [Decades-Old Windows Utility Powers Modern ClickFix Attack](https://www.darkreading.com/cyberattacks-data-breaches/decades-old-windows-utility-modern-clickfix-attack)
- [Tech Giants Block eMudhra Certificates Tied to 8 Compromised Keys](https://www.darkreading.com/cyber-risk/tech-giants-emudhra-certificates-compromised-keys)

### SecurityWeek
- [Oracle Patches Over 1,200 Vulnerabilities With October 2026 CPU](https://www.securityweek.com/oracle-patches-over-1200-vulnerabilities-with-october-2026-cpu/)
- [Meta Ordered to Pay New Mexico $25 Billion for Deceiving Users About Privacy on Facebook](https://www.securityweek.com/meta-ordered-to-pay-new-mexico-25-billion-for-deceiving-users-about-privacy-on-facebook/)
- [Google Hardens Chrome Against ClickFix Attacks, Insecure HTTP Connections](https://www.securityweek.com/google-hardens-chrome-against-clickfix-attacks-insecure-http-connections/)
- [PHP2Shell Patches Land as First Exploitation Attempts Hit Sensors](https://www.securityweek.com/php2shell-patches-land-as-first-exploitation-attempts-hit-sensors/)
- [‘Context Bombs’ Cut AI Attack Success by Misleading Agents With Fake Targets](https://www.securityweek.com/context-bombs-cut-ai-attack-success-by-misleading-agents-with-fake-targets/)
- [High-Severity Flaws Exploited in Three Days as Ransomware Dominates Q3: Rapid7](https://www.securityweek.com/high-severity-flaws-exploited-in-three-days-as-ransomware-dominates-q3-rapid7/)
- [Asymptote Labs Lands $5.5 Million Seed for AI Agent Runtime Security](https://www.securityweek.com/asymptote-labs-lands-5-5-million-seed-for-ai-agent-runtime-security/)
- [Memory Bugs Account for Most of Chrome’s 353 New Security Fixes](https://www.securityweek.com/memory-bugs-account-for-most-of-chromes-353-new-security-fixes/)
- [OpenAI Agents Silenced Security Team Alerts, Removed Misalignment Monitor](https://www.securityweek.com/openai-agents-silenced-security-team-alerts-removed-misalignment-monitor/)
- [Browsers Block eMudhra Intermediate CAs Over Recoverable Private Keys](https://www.securityweek.com/browsers-block-emudhra-intermediate-cas-over-recoverable-private-keys/)

### The Record
- [Meta on the spot for $25 billion under New Mexico privacy ruling](https://therecord.media/meta-new-mexico-penalty-cambridge-analytica-privacy-case)
- [Tech trio launches $10 million initiative to help under-resourced utilities bolster cybersecurity](https://therecord.media/utilities-cybersecurity-initiative-accenture)
- [Democrat lawmakers say Russia is aiming to undermine party ahead of midterms](https://therecord.media/democrat-lawmakers-say-russia-is-aiming-to-undermine-party)
- [PHP says AI review of critical bugs first sparked alarm in August, but signs surfaced in 2024](https://therecord.media/php-foundation-statement-critical-vulnerabilities)
- [Hundreds of websites taken offline as concern grows over two PHP vulnerabilities](https://therecord.media/php-script-vulnerabilities-warnings)

### Infosecurity Magazine
- [Cloud Security Maturity Lags Despite Widespread Adoption, SANS Warns](https://www.infosecurity-magazine.com/news/cloud-security-maturity-lags-sans/)
- [New PhaaS Platform Uses AI to Craft Phishing Lures and Mask Malicious Activity](https://www.infosecurity-magazine.com/news/new-phaas-uses-ai-phishing-lures/)
- [Symantec Uncovers AI Agent Hijacking Models for Autonomous Cyber-Attacks](https://www.infosecurity-magazine.com/news/symantec-ai-agent-llmjacking/)
- [Ransomware Attacks Rise as Rival Gangs Vie For Market Supremacy](https://www.infosecurity-magazine.com/news/rival-gangs-vie-for-market/)
- [SafePay Has Compromised 600 Critical Infrastructure Victims Worldwide, CISA Warns](https://www.infosecurity-magazine.com/news/safepay-compromised-critical/)
- [Critical PHP Vulnerabilities Leaked Ahead of Scheduled Security Patches](https://www.infosecurity-magazine.com/news/critical-php-vulnerabilities-leaked/)
- [Children’s Data Stolen After Ransomware Attack Compromises ‘Password1’ Account](https://www.infosecurity-magazine.com/news/children-data-stolen-password1/)

### CyberScoop
- [Microsoft pins ConnectWise supply-chain attack to China-state aligned threat group](https://cyberscoop.com/microsoft-attributes-connectwise-supply-chain-attack-china-storm-0940/)
- [PHP releases emergency fixes for 2 critical vulnerabilities](https://cyberscoop.com/php-emergency-patches-php2shell-vulnerabilities/)
- [Philippines-based American pleads guilty to running expansive fraud scheme targeting US servicemembers](https://cyberscoop.com/identity-theft-fraud-military-servicemembers-veterans-guilty-robert-boling/)

### Cisco Talos
- [Compromised eMudhra intermediate certificates](https://blog.talosintelligence.com/compromised-intermediate-certificates/)
- [Two critical RCEs in PHP core](https://blog.talosintelligence.com/two-critical-rces-in-php-core/)
- [Parasitizing trust: How legitimate infrastructure becomes a delivery pipeline for attackers](https://blog.talosintelligence.com/parasitizing-trust-how-legitimate-infrastructure-becomes-a-delivery-pipeline-for-attackers/)

### Unit 42 (Palo Alto)
- [Threat Brief: Critical Vulnerabilities in PHP: CVE-2026-109618, CVE-2026-109619](https://unit42.paloaltonetworks.com/cve-2026-109618-cve-2026-109619/)
- [“Next Exploit Opportunities”: How a Threat Actor Used AI to Help Plan and Execute Multiple Types of Cybercrime Activities](https://unit42.paloaltonetworks.com/ai-assisted-cybercrime-analysis/)
- [Threat Brief: Active Exploitation of PAN-OS CVE-2026-0257 (Updated October 20)](https://unit42.paloaltonetworks.com/active-exploitation-of-pan-os-cve-2026-0257/)

### Microsoft Security Blog
- [AI-driven, large-scale nation-state campaign using ARTEX enables supply chain compromise](https://www.microsoft.com/en-us/security/blog/2026/10/21/storm-0940-uses-artex-agentic-ai-connectwise-supply-chain-compromise/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Thursday, October 22nd, 2026 https://isc.sans.edu/podcastdetail/10146, (Thu, Oct 22nd)](https://isc.sans.edu/diary/rss/33446)
- [Critical PHP Vulnerability (CVE-2026-109618, CVE-2026-109619) &#x5b;infocon yellow&#x5d;, (Wed, Oct 21st)](https://isc.sans.edu/diary/rss/33440)
- [ISC Stormcast For Wednesday, October 21st, 2026 https://isc.sans.edu/podcastdetail/10144, (Wed, Oct 21st)](https://isc.sans.edu/diary/rss/33438)

### Securelist (Kaspersky)
- [How APT41 revived the BlackLotus bootkit to attack diplomatic organizations in Central Asia](https://securelist.com/uefi-bootkit-blackx/121539/)
- [Critical RCE vulnerabilities in PHP (CVE-2026-109618, CVE-2026-109619)](https://securelist.com/tr/php2shell-critical-vulnerabilities-in-php/121596/)
- [Operation FlashHole: Lazarus breaks security, defies control](https://securelist.com/lazarus-operation-flashhole/121541/)

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

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal