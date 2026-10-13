# Winjit Daily TI Digest — 2026-10-13

_Auto-generated. Window: last ~24h. Fetched at 2026-10-13T06:58:06.681283+00:00Z_

**At a glance:** 0 new KEV · 166 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-108804 | 10.0 | 2.4% | A vulnerability was detected in TRENDnet TEW-751DR, TEW-752DRU and TEW733GR 1.03B01/1.03B03. Affected is the function fwrite of the file pigwidgeon.cgi of the component Web Management Backend. The man |
| CVE-2026-108892 | 10.0 | n/a | A vulnerability was determined in Linksys E1700 1.0.0.4.003. This vulnerability affects the function ssid1MACFilter of the file /goform/ssid1MACFilter of the component Mac Filter. This manipulation of |
| CVE-2026-108907 | 10.0 | n/a | A vulnerability was determined in Netcore NR268 1.7.121109. Affected is the function user_ok of the component CGI Execution. This manipulation causes improper authentication. The attack can be initiat |
| CVE-2026-108917 | 10.0 | n/a | A vulnerability was determined in Edimax BR-6208AC 1.32. This issue affects some unknown processing of the file /goform/formAutoFWupgrade. Executing a manipulation of the argument tftpsIP can lead to  |
| CVE-2026-108918 | 10.0 | n/a | A vulnerability was identified in Edimax BR-6208AC 1.32. Impacted is an unknown function of the file /goform/formWlanMP. The manipulation of the argument readE2P leads to command injection. It is poss |
| CVE-2026-108893 | 9.9 | n/a | A vulnerability was identified in Linksys E1700 up to 1.0.0.4.003. This issue affects the function setVlan of the file /goform/setVlan. Such manipulation of the argument vlan_set leads to stack-based  |
| CVE-2026-108894 | 9.9 | n/a | A security flaw has been discovered in Linksys E1700 1.0.0.4.003. Impacted is the function addStaticRoute of the file /goform/addStaticRoute of the component Static Route Handler. Performing a manipul |
| CVE-2026-108895 | 9.9 | n/a | A weakness has been identified in Linksys E1700 1.0.0.4.003. The affected element is the function setDMZ of the file /goform/setDMZ. Executing a manipulation of the argument MAC_addr can lead to os co |
| CVE-2026-108896 | 9.9 | n/a | A vulnerability was found in Linksys E1700 1.0.0.4.003. This affects the function setLinksysIpv6 of the file /goform/setLinksysIpv6. The manipulation of the argument _6rd_prefix/_6rd_prefix_len result |
| CVE-2026-108914 | 9.9 | n/a | A flaw has been found in Edimax BR-6208AC 1.32. Affected by this issue is some unknown functionality of the file /goform/formWlSiteSurvey. This manipulation of the argument ifname causes buffer overfl |
| CVE-2026-108915 | 9.9 | n/a | A vulnerability has been found in Edimax BR-6208AC 1.32. This affects an unknown part of the file /goform/formWlanMP. Such manipulation of the argument ateBW leads to buffer overflow. The attack can b |
| CVE-2026-108929 | 9.9 | n/a | A flaw has been found in Netcore NR268 1.7.121109. The affected element is the function execvp of the file /router/DDNSset.cgi of the component DDNS. Executing a manipulation of the argument Hostname  |
| CVE-2026-96119 | 9.9 | n/a | IBM i 7.3, 7.4, 7.5, and 7.6 could allow a remote authenticated attacker to obtain sensitive information or execute arbitrary code on the system due to improper data sanitization by the HTTP Server Ad |
| CVE-2026-89107 | 9.9 | n/a | SAP S/4HANA (Manage Substitution/Validation Rules) does not sufficiently validate input processed by rule definition functionality that utilizes a domain-specific scripting language. An authenticated  |
| CVE-2026-89110 | 9.9 | n/a | SAP NetWeaver Visual Composer does not perform sufficient authorization checks in certain portal functionality. An attacker with low privileges could invoke internal operations on a preconfigured remo |
| CVE-2025-71429 | 9.8 | n/a | GPT-SoVITS through 20250606v2pro contains an OS command injection vulnerability in tools/uvr5/vr.py that allows unauthenticated attackers to execute commands via output folder paths. Attackers can ent |
| CVE-2026-109566 | 9.8 | n/a | Rapyd Admin from 9.0.0 before 9.20.0 contains a hard-coded credentials vulnerability that allows remote unauthenticated attackers to gain super-admin access through an AuthSeeder-created admin@laravel |
| CVE-2026-90920 | 9.8 | n/a | IBM Maximo AI Service 9.1.0, and 9.2.0 could allow a remote attacker to execute arbitrary code due to improper control of code generation. |
| CVE-2026-82101 | 9.6 | n/a | IBM DataStage on Cloud Pak for Data 5.4.0.0 could allow a remote authenticated attacker to cause a denial of service due to a path traversal vulnerability. |
| CVE-2026-82103 | 9.6 | n/a | IBM DataStage on Cloud Pak for Data 5.4.0.0 could allow a remote authenticated attacker to obtain sensitive information due to an exposure of sensitive information to an unauthorized actor. |
| CVE-2026-82110 | 9.6 | n/a | IBM DataStage on Cloud Pak for Data 5.4.0.0 could allow a remote authenticated attacker to execute arbitrary code due to improper validation of pathname during a path traversal. |
| CVE-2026-108971 | 9.6 | n/a | A flaw has been found in D-Link DCS-930L B1.08B4. This impacts the function mpfd_decode of the file bootloader_region.bin of the component Emergency HTTP Recovery Server. Executing a manipulation of t |
| CVE-2026-109321 | 9.1 | n/a | Grav Login OAuth plugin (grav-plugin-login-oauth) before 1.4.3 provisions OAuth accounts as ordinary Grav users with a deterministic <provider>.<id> username and an unsalted MD5 hash of the provider i |
| CVE-2026-87744 | 9.1 | n/a | A flaw was found in Quarkus REST Data Panache. This vulnerability allows unauthenticated attackers to bypass security controls on generated endpoints. When a developer customizes a specific operation  |
| CVE-2026-89108 | 9.1 | n/a | SAP Manufacturing Integration and Intelligence does not sufficiently enforce authorization boundaries within certain administrative functionality. An attacker with MII administrator privileges could s |
| CVE-2026-109185 | 8.8 | n/a | jshERP through 3.6 contains a missing authorization vulnerability in the UserController updateUser handler that allows authenticated users to assign arbitrary roles to any user. Low-privilege attacker |
| CVE-2026-109186 | 8.8 | n/a | jshERP through 3.6 contains a mass assignment vulnerability in the UserController update handler that allows authenticated users to overwrite protected fields including tenant_id and password. Attacke |
| CVE-2026-52903 | 8.8 | n/a | A deserialization of untrusted data vulnerability was found in ManageIQ. The YamlLoadAliases module overrides YAML.safe_load to silently fall back to YAML.unsafe_load in production when a Psych::Disal |
| CVE-2026-109199 | 8.8 | n/a | LogicalDOC Community Edition through 9.3 contains a code injection vulnerability that allows authenticated users to execute OS commands by submitting Velocity templates in DocumentService.sendAsEmail  |
| CVE-2026-109305 | 8.8 | n/a | Craft CMS from 5.10.2 before 5.10.14 contains a Twig sandbox bypass that allows non-admin users to invoke PHP callables through the "has some" and "has every" operators. Users with the System Messages |
| CVE-2026-109308 | 8.8 | n/a | Craft CMS 4.0.0 before 4.18.7 and 5.0.0 before 5.10.14 passes the raw 'updates' request parameter in AppController::actionCacheUpdates to UpdatesModel without Component::cleanseConfig(), allowing beha |
| CVE-2026-109318 | 8.8 | n/a | Grav Git Sync 1.0.2 through 3.4.12 contains a command injection vulnerability that allows authenticated content editors to execute OS commands by injecting shell substitutions into profile fields. Whe |
| CVE-2026-109569 | 8.8 | n/a | sandboxed.sh through 1.3.0 contains a container escape vulnerability that allows code in container workspaces to access the host filesystem because nsenter attaches without --root. Agent-run code in a |
| CVE-2024-58390 | 8.8 | n/a | Frappe before 14.81.4 and 15.x before 15.41.0 contains an improper privilege management vulnerability involving a certain document action that permits escalation from the Website User role to System M |
| CVE-2026-102627 | 8.8 | n/a | IBM TRIRIGA Application Platform 5.0.0 through 5.0.8 could allow a remote authenticated attacker to execute arbitrary code due to improper validation of file paths during archive extraction. |
| CVE-2026-109608 | 8.8 | n/a | Frappe ERPNext before 15.121.0 and 16.x before 16.34.0 contains an SQL injection vulnerability in several endpoints that lack input validation. Any authenticated user, including one with no assigned r |
| CVE-2026-109652 | 8.8 | n/a | Frappe ERPNext before 15.119.1 and 16.x before 16.32.0 contains a server-side template injection vulnerability because user-controlled message fields are not validated before template rendering, allow |
| CVE-2026-109667 | 8.8 | n/a | Frappe ERPNext before 15.111.0 and 16.x before 16.22.0 contains a privilege escalation vulnerability in a record-creation endpoint that takes the record type from the request and inserts the record wi |
| CVE-2026-19620 | 8.8 | n/a | IBM Planning Analytics 2.0, and 2.1 could allow a remote attacker to gain unauthorized administrative access due to improper authentication. |
| CVE-2026-19622 | 8.8 | n/a | IBM Planning Analytics 2.0, and 2.1 could allow a remote attacker to bypass authentication and escalate privileges due to improper validation of sub-requests. |
| CVE-2026-82096 | 8.8 | n/a | IBM DataStage on Cloud Pak for Data 5.4.0.0 could allow a remote authenticated attacker to execute arbitrary commands due to improper neutralization of special elements used in an OS command. |
| CVE-2026-82108 | 8.8 | n/a | IBM DataStage on Cloud Pak for Data 5.4.0.0 could allow a remote authenticated attacker to execute arbitrary code due to improper neutralization of special elements used in an OS command. |
| CVE-2026-89113 | 8.8 | n/a | SAP Commerce Cloud does not sufficiently validate certain user-supplied input before it is incorporated into a database query. An authenticated user could send specially crafted requests to affected f |
| CVE-2026-109372 | 8.7 | n/a | ZITADEL 4.x before 4.19.2 and 3.x through 3.4.15 contains an authentication bypass in the SAML identity-provider intent callback, which verifies the assertion signature using the provider named in the |
| CVE-2026-109557 | 8.7 | n/a | EdgeEver through 1.112.0 contains a stored cross-site scripting vulnerability in setMemoDragPreview that allows attackers to inject script through notebook names or memo titles. Attackers can set mali |
| CVE-2026-109558 | 8.7 | n/a | EdgeEver 1.6.0 through 1.112.0 contains a stored cross-site scripting vulnerability in TemplatesPane.tsx that renders template contentMarkdown with raw HTML via dangerouslySetInnerHTML without sanitiz |
| CVE-2026-109559 | 8.7 | n/a | EdgeEver Desktop 1.6.26 through 1.112.0 contains a navigation allowlist bypass that lets attackers load arbitrary origins in the main window via string-prefix URL matching. Attackers can embed a link  |
| CVE-2026-18529 | 8.7 | n/a | IBM Maximo Application Suite - Location Service for Esri Component 9.2, 9.1, and 9.0 is vulnerable to command injection due to improper sanitisation of a user-controlled value passed to a shell comman |
| CVE-2026-18537 | 8.7 | n/a | IBM Maximo Application Suite - Location Service for Esri Component 9.2, 9.1, and 9.0 is vulnerable to improper input validation due to an unsanitised container image reference in a Kubernetes operator |
| CVE-2026-109238 | 8.6 | n/a | Crawl4AI 0.7.0 before 0.9.4 contains a server-side request forgery vulnerability that allows API clients to reach internal addresses by enabling link_preview_config on /crawl requests. Attackers can s |
| CVE-2026-109201 | 8.3 | n/a | LogicalDOC Community Edition through 9.3 contains a missing authorization vulnerability in SoapDocumentService operations that allows authenticated users to access and modify unauthorized documents. A |
| CVE-2026-108916 | 8.3 | n/a | A vulnerability was found in Edimax BR-6208AC 1.32. This vulnerability affects unknown code of the file /goform/formAccept. Performing a manipulation of the argument submit-url results in command inje |
| CVE-2026-93886 | 8.3 | n/a | IBM i 7.3, 7.4, 7.5, and 7.6 could allow a remote authenticated attacker to execute arbitrary script code due to improper validation of user-supplied input. |
| CVE-2026-109371 | 8.2 | n/a | ZITADEL 3.0.0 before 4.18.0 contains a missing authentication vulnerability in the hosted Login V1 UI, where the change-username handler acts on the account bound to a login flow before any factor is  |
| CVE-2021-48012 | 8.2 | n/a | fast-toml through 0.5.4 contains a prototype pollution vulnerability that allows attackers to modify Object.prototype by supplying TOML containing __proto__, constructor or prototype key segments. Att |
| CVE-2026-19627 | 8.2 | n/a | IBM Planning Analytics 2.0, and 2.1 could allow a remote attacker to read arbitrary host files and overwrite certain application files due to improper validation of file paths. |
| CVE-2026-109391 | 8.1 | n/a | Square Squash through commit e73f280 contains an insecure deserialization vulnerability that allows unauthenticated attackers to store crafted YAML via the POST /api/1.0/symbolication endpoint. When o |
| CVE-2026-109399 | 8.1 | n/a | SWUpdate through 2026.05.1 contains an improper certificate validation vulnerability in crypto/swupdate_cms_verify_openssl.c that trusts untrusted X.509 certificates embedded in CMS SignedData for cha |
| CVE-2026-109237 | 8.1 | n/a | Crawl4AI from 0.9.0 before 0.9.4 contains an untrusted-config gate bypass that allows non-admin API clients to construct forbidden config objects by wrapping them in dict-type wrappers. Attackers can  |
| CVE-2026-109286 | 8.1 | n/a | Open WebUI from 0.7.0 before 0.11.4 contains a cross-origin message handling vulnerability in SyncStatsModal that allows any website to steal a signed-in user's session token by posting unvalidated ve |
| CVE-2026-109312 | 8.1 | n/a | Grav Login plugin 2.7.0 before 3.9.9 contains an authentication bypass in processUserProfile(), which checks that the session user exists but not that a pending front-end 2FA session is fully authoriz |
| CVE-2026-109313 | 8.1 | n/a | Grav Login plugin 2.7.0 before 3.9.9 contains an authentication bypass vulnerability that allows attackers with a valid password to skip two-factor authentication through remember-me cookie restoratio |
| CVE-2026-109334 | 8.1 | n/a | SurrealDB before 3.3.0 does not check the caller-selected namespace or database against the level at which a namespace- or database-level system user authenticated, allowing cross-tenant access. An au |
| CVE-2026-109343 | 8.1 | n/a | SurrealDB before 3.3.0 allows cross-tenant access because the SurrealQL USE statement switches a session to any namespace/database without checking that the caller's authenticated level covers it. Aut |
| CVE-2026-109346 | 8.1 | n/a | better-auth from 1.3.8-beta.3 before 1.7.0-rc.3 contains a UI misrepresentation vulnerability in the deviceAuthorization plugin because GET /device omits the requesting client_id and scope. Attackers  |
| CVE-2026-109357 | 8.1 | n/a | LibreNMS before 26.9.0 contains an LDAP filter injection in ldap-authorization and ad-authorization modes because usernames are inserted unescaped into LDAP search filters and authentication only chec |
| CVE-2026-109373 | 8.1 | n/a | ZITADEL 3.0.0 before 4.19.2 contains an authentication bypass vulnerability in the Login V2 UI that allows unauthenticated attackers to obtain other users' session tokens by forging unsigned session c |
| CVE-2026-109422 | 8.1 | n/a | NetEase Cloud Music client for Windows (cloudmusic.exe) versions 3.1.38 and 3.1.39.205426 contains a remote code execution vulnerability in the renderer-process IPC bridge os.navigateExternal, which p |
| CVE-2020-37279 | 8.1 | n/a | easy-pdf-merge 0.1.0 through 0.2.6 contains an OS command injection vulnerability that allows attackers to execute commands by injecting shell metacharacters into source paths, destination path, or ma |
| CVE-2025-71432 | 8.1 | n/a | Frappe ERPNext before 14.92.1 and 15.x before 15.83.0 contains a reflected cross-site scripting vulnerability due to missing input validation on a certain page, allowing arbitrary JavaScript to execut |
| CVE-2026-109573 | 8.1 | n/a | phpMyFAQ before 4.1.9 contains an SQL injection vulnerability in PdoMysql::escape(), which escapes single quotes with backslashes that are treated literally when MySQL or MariaDB runs in NO_BACKSLASH_ |
| CVE-2026-109633 | 8.1 | n/a | Frappe ERPNext before 15.119.1 and 16.x before 16.32.0 contains a stored cross-site scripting vulnerability because content submitted through a public-facing booking page is stored without neutralizat |
| CVE-2026-109640 | 8.1 | n/a | Frappe ERPNext before 16.22.0 contains a missing authorization vulnerability that allows authenticated users to modify records by invoking endpoints lacking proper authorization checks. Attackers can  |
| CVE-2026-85457 | 8.1 | n/a | IBM Planning Analytics 2.0, and 2.1 could allow a remote authenticated attacker to execute arbitrary code due to a stack-based buffer overflow. |
| CVE-2026-93892 | 8.1 | n/a | IBM TRIRIGA Application Platform 5.0.0 through 5.0.8 could allow a remote authenticated attacker to obtain sensitive information due to exposure of session tokens in the HTML response. |
| CVE-2026-109556 | 8.0 | n/a | EdgeEver Desktop 1.92.0 through 1.112.0 contains a remote code execution vulnerability in the desktop:acp-probe IPC handler, which lacks a sender check and spawns a caller-supplied input.path executab |
| CVE-2026-108953 | 7.8 | n/a | mac-shell-mcp before 2.0.0 contains an OS command injection vulnerability that allows MCP clients to bypass the command whitelist by injecting shell metacharacters into execute_command arguments. Atta |
| CVE-2026-108094 | 7.8 | n/a | A use-after-free flaw was found in mutter in the Wayland color-management ICC image-description path. A local attacker who can run a malicious Wayland client can destroy a wp_image_description_v1 reso |
| CVE-2026-109358 | 7.8 | n/a | Edgeless Systems Contrast 1.8.0 before 1.24.1 contains an incorrect permissions vulnerability where the node installer writes the containerd config world-writable (0666). Local unprivileged users on t |
| CVE-2026-75782 | 7.8 | n/a | IBM Aspera Enterprise WebApps 1.0.0 through 1.0.6 could allow a local attacker to gain elevated privileges due to a misconfigured PATH environment variable. |
| CVE-2026-35001 | 7.8 | n/a | OpenS100 through commit daa35b contains an integer overflow vulnerability in the S-102 Bathymetric Surface parser that allows remote attackers to cause a heap-based buffer overflow by opening a crafte |
| CVE-2026-109359 | 7.7 | n/a | Contrast 1.8.0 before 1.24.1 contains an improper verification vulnerability in Coordinator peer recovery that fails to confirm the serving peer uses the same manifest generation. Attackers with write |
| CVE-2026-75888 | 7.7 | n/a | A flaw was found in the OpenShift console. An authenticated console user can exploit a Server-Side Request Forgery (SSRF) vulnerability by providing a specially crafted Helm chart URL without proper v |
| CVE-2026-18517 | 7.7 | n/a | IBM Maximo Application Suite - Location Service for Esri Component 9.2, 9.1, and 9.0 IBM Maximo Application Suite — Location Service for Esri Component is vulnerable to unintended network egress due t |
| CVE-2026-109572 | 7.6 | n/a | Open WebUI from 0.8.6 before 0.11.4 contains a privilege escalation vulnerability in the terminal proxy that allows authenticated users to reach the Terminals administrator API with the shared key att |
| CVE-2026-93891 | 7.6 | n/a | IBM TRIRIGA Application Platform 5.0.0 through 5.0.8 could allow a remote authenticated attacker to obtain sensitive information due to an XML external entity (XXE) injection flaw. |
| CVE-2026-109205 | 7.5 | n/a | LogicalDOC Community Edition through 9.3 contains an unauthenticated file upload vulnerability in the UploadServlet that allows remote attackers to write files to disk without a session. Attackers can |
| CVE-2026-109225 | 7.5 | n/a | SGLang through 0.5.21 contains an unbounded memory allocation vulnerability that allows unauthenticated remote attackers to exhaust memory by uploading oversized files to /v1/audio/transcriptions. Att |
| CVE-2026-109226 | 7.5 | n/a | SGLang through 0.5.21 contains a decompression amplification vulnerability in load_audio that allows remote attackers to exhaust memory by submitting highly compressed audio decoded without duration o |
| CVE-2026-109227 | 7.5 | n/a | SGLang through 0.5.21 contains an unbounded memory allocation vulnerability in preprocess_video in qwen_vl.py that decodes frames at full source resolution before applying max_pixels limits. Remote at |
| CVE-2026-109228 | 7.5 | n/a | SGLang through 0.5.21 contains a resource budget bypass vulnerability that allows remote attackers to override GLM-V video processing limits by supplying fps, max_frames, max_tokens_per_frame and max_ |
| CVE-2026-109229 | 7.5 | n/a | SGLang through 0.5.21 contains a denial of service vulnerability that disables Pillow decompression bomb protection process-wide by setting Image.MAX_IMAGE_PIXELS to None in NanoNemotronVLImageProcess |
| CVE-2026-109398 | 7.5 | n/a | Gumlet php-image-resize before 3.0.1 contains a denial of service vulnerability because the ImageResize constructor in lib/ImageResize.php passes images to GD imagecreatefrom* functions without pixel  |
| CVE-2026-109325 | 7.5 | n/a | Grav from 2.0.22 before 2.1.7 contains an authentication bypass vulnerability in the Clockwork profiler that trusts loopback REMOTE_ADDR values. Unauthenticated attackers behind a same-host HTTP proxy |
| CVE-2026-109326 | 7.5 | n/a | Grav before 2.1.7 contains an information disclosure vulnerability because bundled nginx, lighttpd, IIS, and Caddy 2 configurations block .git only at document root. Unauthenticated attackers can requ |
| CVE-2026-109360 | 7.5 | n/a | MONAI 0.4.0 before 1.6.1 contains a remote code execution vulnerability that allows on-path attackers to execute code by tampering with SENet pretrained weights fetched over plaintext HTTP. Attackers  |
| CVE-2026-109363 | 7.5 | n/a | ZcashFoundation Zebra 6.4.0 before 6.4.2 parses version 6 transactions carrying a pre-NU6.3 consensus branch ID, but the size computation during UnminedTx construction treats re-serialization of the O |
| CVE-2020-37280 | 7.5 | n/a | cbor-sync through 1.0.4 contains a resource exhaustion vulnerability in CBOR.decode that trusts declared array and map lengths without checking remaining input. Remote attackers can supply a tiny craf |
| CVE-2021-48011 | 7.5 | n/a | Servor 1.0.0 through 4.0.2 contains a path traversal vulnerability that allows unauthenticated remote attackers to escape the served root by sending URL-encoded dot segments. Attackers can send %2e%2e |
| CVE-2026-105052 | 7.5 | n/a | IBM Maximo Application Suite 8.10, 8.11, 9.0, 9.1, and 9.2 could allow a remote attacker to traverse directories on the system. An attacker could send a specially crafted URL request containing "dot d |
| CVE-2026-109380 | 7.5 | n/a | modern-tar 0.3.5 through 0.8.5 contains a memory exhaustion vulnerability that allows attackers to produce negative entry sizes via non-octal bytes parsed by readOctal(). Attackers can supply a crafte |
| CVE-2026-109426 | 7.5 | n/a | Telegram-Stremio through 5.1.0 contains an insecure storage vulnerability that allows attackers with access to the MongoDB database, backups, or logs to recover the operator's authenticated Telegram s |
| CVE-2026-109560 | 7.5 | n/a | Continue CLI (@continuedev/cli) through 1.5.47 contains a permission bypass vulnerability that allows attackers to run unapproved commands by chaining them after allowed Bash prefix rules. Attackers c |
| CVE-2026-109563 | 7.5 | n/a | N3.js before 2.11.1 contains a regular expression denial of service vulnerability in the N3Lexer number pattern that backtracks quadratically on long digit runs. Attackers can supply untrusted Turtle  |
| CVE-2026-75881 | 7.5 | n/a | IBM Maximo Application Suite - IoT Component 9.2.0, 9.1.0, and 9.0.0 could allow a remote attacker to cause a denial of service due to an infinite parsing loop when processing certain inputs. |
| CVE-2026-78673 | 7.5 | n/a | IBM Maximo AI Service 9.1.0, and 9.2.0 could allow a remote attacker to cause a denial of service due to improper input validation. |
| CVE-2026-90911 | 7.5 | n/a | IBM Maximo AI Service 9.1.0, and 9.2.0 could allow a remote attacker to cause a denial of service due to uncontrolled resource consumption. |
| CVE-2026-90912 | 7.5 | n/a | IBM Maximo AI Service 9.1.0, and 9.2.0 SaaS could allow a remote attacker to cause a denial of service due to uncontrolled recursion. |
| CVE-2026-90921 | 7.5 | n/a | IBM Maximo AI Service 9.1.0, and 9.2.0 could allow a remote attacker to cause a denial of service due to improper handling of malformed frames, resulting in termination of the host process. |
| CVE-2026-92876 | 7.5 | n/a | IBM Maximo Application Suite - IoT Component 9.2.0, 9.1.0, and 9.0.0 could allow a remote attacker to cause a denial of service due to uncontrolled recursion. |
| CVE-2026-75061 | 7.5 | n/a | IBM Planning Analytics 2.0, and 2.1 could allow a remote attacker to traverse directories on the system. An attacker could send a specially crafted URL request containing "dot dot" sequences (/../) to |
| CVE-2026-75095 | 7.5 | n/a | IBM Aspera Enterprise WebApps 1.0.0 through 1.0.6 could allow a remote attacker to cause a denial of service due to uncontrolled resource consumption. |
| CVE-2026-58249 | 7.5 | n/a | SAP NetWeaver and SAP Web Dispatcher do not properly validate certain fields in specially crafted requests handled by an internal protocol component. An unauthenticated attacker could send a malicious |
| CVE-2026-109394 | 7.4 | n/a | Thirty bees through 1.7.0 contains an authentication bypass vulnerability in PasswordController::resolveCustomer() that allows unauthenticated attackers to reset registered customers' passwords using  |
| CVE-2026-109331 | 7.4 | n/a | Network-AI from 5.14.0 before 5.15.2 contains a security control bypass vulnerability in the ClaudeHookBridge PreToolUse hook, which matches deny patterns only against the first present candidate fiel |
| CVE-2026-83535 | 7.4 | n/a | A flaw was found in openstack-network-exporter. When an operator configures user authentication but omits or misconfigures Transport Layer Security (TLS), the basic authentication mechanism is silentl |
| CVE-2026-109423 | 7.4 | n/a | NetEase Cloud Music client for Windows (cloudmusic.exe) versions 3.1.38 and 3.1.39.205426 contains a TLS certificate validation vulnerability that allows a network-adjacent attacker to intercept and d |
| CVE-2026-53997 | 7.4 | n/a | Netherman Portal del Hermano (portaldelhermano.es) before 2026-10-06 contains a broken authentication vulnerability in its password-recovery flow at the POST /password/create-access and POST /password |
| CVE-2026-84418 | 7.4 | n/a | IBM DataStage on Cloud Pak for Data 5.4.0.0 can allow a man-in-the-middle attacker to present a forged TLS certificate, intercept the connection, and capture the IAM bearer Authorization header automa |
| CVE-2026-108783 | 7.3 | 0.4% | A security vulnerability has been detected in PRVTPRO Amnezia-Web-Panel up to 1.6.2/1.7.2. This affects an unknown part of the file app.py of the component Backup Download. The manipulation leads to u |
| CVE-2026-108798 | 7.3 | 0.3% | A vulnerability was found in ZKTeco BioTime 9.5.6 Build 20260130.3206. This issue affects some unknown processing. The manipulation results in use of hard-coded cryptographic key . The attack may be  |
| CVE-2026-108799 | 7.3 | 0.4% | A vulnerability was determined in jackq XCMS up to 3fab5342cc509945a7ce1b8ec39d19f701b89261. Impacted is the function PublicController::sendFindPwdMail of the file Admin/Home/Controller/PublicControll |
| CVE-2026-108805 | 7.3 | 0.3% | A flaw has been found in krupalshah EmployeeRecruitmentSystem up to 922ff6d208278282e7c8e36d70d9ae356adec9fe. Affected by this vulnerability is the function mysql_query of the file source/loginprocess |
| CVE-2026-108806 | 7.3 | 0.3% | A vulnerability has been found in krupalshah EmployeeRecruitmentSystem up to 922ff6d208278282e7c8e36d70d9ae356adec9fe. Affected by this issue is the function mysql_query of the file source/authprocess |
| CVE-2026-108807 | 7.3 | 0.3% | A vulnerability was found in krupalshah EmployeeRecruitmentSystem up to 922ff6d208278282e7c8e36d70d9ae356adec9fe. This affects the function mysql_query of the file source/adminregister.php of the comp |
| CVE-2026-108818 | 7.3 | 0.5% | A vulnerability was identified in agno-agi agno up to 2.7.3/3.0.6. This affects the function get_authentication_dependency of the file auth.py. Such manipulation of the argument security_key leads to  |
| CVE-2026-108819 | 7.3 | 0.5% | A security flaw has been discovered in agno-agi agno up to 3.0.6/3.1.1. This vulnerability affects the function exec of the component Agent Orchestration Layer. Performing a manipulation of the argume |
| CVE-2026-108826 | 7.3 | n/a | A vulnerability was found in Zen Cart up to 2.2.2. This impacts the function zen_db_perform in the library includes/modules/payment/paypaldp.php of the component PayPal IPN Handler. Performing a manip |
| CVE-2026-108836 | 7.3 | n/a | A vulnerability has been found in Ollama up to 0.34.1. The affected element is the function IsValid of the file types/model/name.go of the component Pull API. The manipulation leads to server-side req |
| CVE-2026-108899 | 7.3 | n/a | A flaw has been found in tobychui zoraxy up to 3.3.4. This impacts the function handleBasicAuth of the file mod/dynamicproxy/authProviders.go of the component Path Exception Matcher. This manipulation |
| CVE-2026-108900 | 7.3 | n/a | A vulnerability has been found in Exponent CMS up to 3.0.2patch2. Affected is the function userLogin of the file xmlrpc.php of the component XML-RPC. Such manipulation leads to sql injection. It is po |
| CVE-2026-109290 | 7.3 | n/a | Open WebUI from 0.11.1 before 0.11.4 contains a stored cross-site scripting vulnerability in DocxPreview.svelte that allows authenticated users to execute script by uploading crafted DOCX attachments. |
| CVE-2026-109291 | 7.3 | n/a | Open WebUI from 0.6.33 before 0.11.4 contains a cross-site scripting vulnerability that allows authenticated users to execute script in victims' sessions by storing javascript: URLs in citation embed_ |
| CVE-2026-109314 | 7.3 | n/a | Grav Login plugin 1.2.0 before 3.9.9 contains an information disclosure vulnerability that allows publishers to obtain password-reset tokens by authoring a page at the reset route. When a victim opens |
| CVE-2026-109361 | 7.3 | n/a | MONAI 1.2.0 before 1.6.1 contains an insecure deserialization vulnerability in nnUNetV2Runner that unpickles the postprocessing_file path read from inference_information.json without confining it to t |
| CVE-2026-108921 | 7.3 | n/a | A vulnerability was detected in KusalkaSilva Learning-Management-System up to ffeb873f8803f1e9664384ff75000c7da45466d2. This impacts the function mysql_query of the file remove_announcements.php of th |
| CVE-2026-109604 | 7.3 | n/a | Frappe ERPNext before 15.112.0 and 16.x before 16.23.0 contains a stored cross-site scripting vulnerability because a tool view interpolates stored record names into markup without escaping. An authen |
| CVE-2026-109612 | 7.3 | n/a | Frappe ERPNext before 15.120.0 and 16.x before 16.33.0 contains a stored cross-site scripting vulnerability in a report view that interpolates stored record names into markup without escaping. Authent |
| CVE-2026-109653 | 7.3 | n/a | Frappe ERPNext before 15.119.0 and 16.x before 16.31.0 contains a stored cross-site scripting vulnerability because record fields are rendered into an HTML attribute context without escaping. A low-pr |
| CVE-2026-109671 | 7.3 | n/a | Frappe ERPNext before 15.113.0 and 16.x before 16.24.0 contains a stored cross-site scripting vulnerability in a profile field that is rendered without escaping into portal pages. Low-privilege attack |
| CVE-2026-109673 | 7.3 | n/a | Frappe ERPNext before 15.103.0 and 16.x before 16.12.0 contains a stored cross-site scripting vulnerability because the names of certain records are not properly neutralized when rendered on some dash |
| CVE-2026-108956 | 7.3 | n/a | A vulnerability was identified in code-projects Online Reviewer System 1.0. The affected element is an unknown function of the file /reviewer/system/system/admins/manage/users/btn_functions.php of the |
| CVE-2026-108964 | 7.3 | n/a | A vulnerability was found in SourceCodester Performance Indicator System 1.0. This affects an unknown part of the file /opils/admin/addproduct.php. Performing a manipulation of the argument prodcatego |
| CVE-2026-108965 | 7.3 | n/a | A vulnerability was determined in SourceCodester Performance Indicator System 1.0. This vulnerability affects unknown code of the file /opils/staff/edit_quantity.php. Executing a manipulation of the a |
| CVE-2026-108966 | 7.3 | n/a | A vulnerability was identified in SourceCodester Performance Indicator System 1.0. This issue affects some unknown processing of the file /opils/staff/product.php. The manipulation of the argument Cat |
| CVE-2026-108967 | 7.3 | n/a | A security flaw has been discovered in SourceCodester Performance Indicator System 1.0. Impacted is an unknown function of the file /opils/staff/edit_credit.php. The manipulation of the argument credi |
| CVE-2026-108968 | 7.3 | n/a | A weakness has been identified in SourceCodester Performance Indicator System 1.0. The affected element is an unknown function of the file /opils/staff/sales_history.php. This manipulation of the argu |
| CVE-2026-108969 | 7.3 | n/a | A security vulnerability has been detected in itsmeravitejak Online-Examination-System up to e6208e630b14657999bbfe4c9912302d2a1e2449. The impacted element is the function Session::checkLogin of the f |
| CVE-2026-108970 | 7.3 | n/a | A vulnerability was detected in itsmeravitejak Online-Examination-System up to e6208e630b14657999bbfe4c9912302d2a1e2449. This affects the function MySQLDB::addNewUser of the file include/database.php  |
| CVE-2026-108972 | 7.3 | n/a | A vulnerability was found in SourceCodester Human Resource Management System 1.0. Affected by this vulnerability is the function session_start of the file controller/employee.php of the component Empl |
| CVE-2026-108906 | 7.2 | n/a | A vulnerability has been found in Netcore NR268 1.7.121109. This affects the function filter_arp_put_file_cgi of the file /router/filter_arp_put_file.cgi. The manipulation of the argument put_file lea |
| CVE-2026-109397 | 7.2 | n/a | Thelia before 3.1.2 and 3.2.x before 3.2.1 contains an unrestricted file upload vulnerability that allows authenticated back-office users to upload PHP files by appending a trailing space to filenames |
| CVE-2026-109317 | 7.2 | n/a | Grav grav-plugin-api before 1.0.36 contains a privilege escalation vulnerability that allows delegated user managers to obtain super-admin access by storing positive scalar admin or api parent grants. |
| CVE-2026-109347 | 7.2 | n/a | Adminer before 6.1.1 contains a remote code execution vulnerability that allows authenticated SQLite users to bypass ATTACH and VACUUM INTO restrictions by prefixing statements with a UTF-8 byte-order |
| CVE-2026-109567 | 7.2 | n/a | Rapyd Admin from 9.0.0 before 9.20.0 contains an improper privilege management vulnerability in the UsersEdit Livewire component that allows users with the edit users permission to assign themselves t |
| CVE-2026-18513 | 7.2 | n/a | IBM Maximo Application Suite - Location Service for Esri Component 9.2, 9.1, and 9.0 is vulnerable to improper access control due to a schema-less Custom Resource Definition. |
| CVE-2026-109164 | 7.1 | n/a | TDuck survey form through 6.0 contains an insecure direct object reference vulnerability that allows authenticated users to delete other users' form submissions by supplying arbitrary submission ids.  |
| CVE-2026-109242 | 7.1 | n/a | FreeRDP before 3.0.0 and 3.6.0 before 3.32.0 renders uninitialized heap memory from un-decoded progressive tiles because the tile->current buffer is allocated without zeroing. A malicious RDP server c |
| CVE-2026-109341 | 7.1 | n/a | SurrealDB before 3.3.0 contains an authorization bypass vulnerability that allows callers with table-level write permission to read SELECT-restricted fields by resolving JSON Patch pointers against th |
| CVE-2026-109353 | 7.1 | n/a | LibreNMS before 26.9.0 contains an SQL injection vulnerability that allows unprivileged users to inject SQL by supplying an array-valued notification_id parameter to notifications.inc.php. Attackers c |
| CVE-2026-109568 | 7.1 | n/a | Shaark 1.2.13 through 1.2.44 contains a missing authorization vulnerability in the Link, Story, Chest and Album API controllers that skips ownership checks. Authenticated non-admin users can send PUT  |
| CVE-2026-109613 | 7.1 | n/a | Frappe ERPNext before 15.121.0 and 16.x before 16.34.0 contains a missing authorization vulnerability in which certain endpoints fail to enforce proper authorization checks on document status modifica |
| CVE-2026-109616 | 7.1 | n/a | Frappe ERPNext before 15.121.3 and 16.x before 16.35.0 contains a missing authorization vulnerability in which certain endpoints fail to enforce proper authorization checks. Authenticated users can se |
| CVE-2026-109617 | 7.1 | n/a | Frappe ERPNext before 15.121.0 and 16.x before 16.34.0 contains a missing authorization vulnerability in certain endpoints that fail to enforce proper authorization checks during document creation. Au |
| CVE-2026-17475 | 7.1 | n/a | IBM Planning Analytics 2.0, and 2.1 could allow a remote authenticated attacker to delete folders and applications belonging to other users due to improper functional level access control. |
| CVE-2026-89120 | 7.1 | n/a | A regression caused by an API change in SAP ABAP Platform reintroduces a previously fixed authorization weakness. The session manager can be opened in single transaction mode, including from FLP. A lo |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-cfgw-wg5v-xf4c | CVE-2026-54870 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-36xp-86g8-82wm | CVE-2026-54868 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-x3xj-rcj9-cf8f | CVE-2026-108972 | medium | A vulnerability was found in SourceCodester Human Resource Management System 1.0. Affected by... |
| GHSA-mr4c-8644-ggh2 | CVE-2026-89271 | unknown | The WP-BusinessDirectory  WordPress plugin through 4.0.2 does not restrict the type or... |
| GHSA-cmm6-9cwj-mxwq | CVE-2026-54867 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-5vhf-mw8w-298v | CVE-2026-108971 | high | A flaw has been found in D-Link DCS-930L B1.08B4. This impacts the function mpfd_decode of the... |
| GHSA-hqhr-xhv5-vmx3 | CVE-2026-54869 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-g282-pvfr-cjqv | CVE-2026-108967 | medium | A security flaw has been discovered in SourceCodester Performance Indicator System 1.0. Impacted... |
| GHSA-vv6q-hqgw-x9v8 | CVE-2026-108966 | medium | A vulnerability was identified in SourceCodester Performance Indicator System 1.0. This issue... |
| GHSA-vc4w-4wqx-vv6m | CVE-2026-89269 | unknown | The WP Testimonials WordPress plugin through 1.4.13 does not properly escape testimonial content... |
| GHSA-pm39-38f7-ghwj | CVE-2026-108968 | medium | A weakness has been identified in SourceCodester Performance Indicator System 1.0. The affected... |
| GHSA-p7f9-5hc2-h654 | CVE-2026-108969 | medium | A security vulnerability has been detected in itsmeravitejak Online-Examination-System up to... |
| GHSA-57h7-65gm-77hx | CVE-2026-108970 | medium | A vulnerability was detected in itsmeravitejak Online-Examination-System up to... |
| GHSA-phpq-mj56-6cg9 | CVE-2026-108964 | medium | A vulnerability was found in SourceCodester Performance Indicator System 1.0. This affects an... |
| GHSA-8m68-j7cp-5rcm | CVE-2026-109758 | critical | Perforce Helix Authentication Service (HAS) deployments that retain the shipped default SCIM... |
| GHSA-qjgm-wp59-vm62 | CVE-2026-108965 | medium | A vulnerability was determined in SourceCodester Performance Indicator System 1.0. This... |
| GHSA-cq2c-fqx9-6r6v | CVE-2026-108961 | medium | A flaw has been found in PaddlePaddle PaddleX up to 3.7.2. Affected by this vulnerability is the... |
| GHSA-3v23-c7fx-q62r | CVE-2026-108962 | medium | A vulnerability has been found in storyicon comfyui_segment_anything up to... |
| GHSA-f65j-g87j-ff2x | CVE-2026-9268 | low | GitLab has remediated an issue in GitLab EE affecting all versions from 13.6 before 19.2.8, 19.3... |
| GHSA-p4fx-7pm7-23jr | CVE-2026-108960 | low | A vulnerability was detected in Tiiny-AI PowerInfer up to... |
| GHSA-5vgp-j37h-7wfx | CVE-2026-96893 | high | GitLab has remediated an issue in GitLab EE affecting all versions from 19.1 before 19.2.8, 19.3... |
| GHSA-ggg2-vpmq-m78f | CVE-2026-92883 | high | GitLab has remediated an issue in GitLab CE/EE affecting all versions from 19.1 before 19.2.8, 19... |
| GHSA-3wqg-xrf4-q3m8 | CVE-2026-92528 | medium | GitLab has remediated an issue in GitLab EE affecting all versions from 16.11 before 19.2.8, 19.3... |
| GHSA-45xr-9jx2-8qgr | CVE-2026-108959 | low | A security vulnerability has been detected in itsourcecode Online Cake Ordering System 1.0. This... |
| GHSA-xw36-3g63-5wfw | CVE-2026-109786 | medium | In fail2ban 0.10.5 through 1.1.1 before ddd879d, the sshd filter (config/filter.d/sshd.conf)... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| The Innovation Group | play | US | 2026-10-13T01:34:32.983032+00:00 |
| DFK Group | play | DE | 2026-10-13T00:37:22.018028+00:00 |
| Saddlers Court MFG | play | GB | 2026-10-13T00:36:48.095988+00:00 |
| Culinary Specialties | play | US | 2026-10-13T00:36:14.053597+00:00 |
| Advanced Imaging Solutions | play | MN | 2026-10-13T00:35:28.363980+00:00 |
| hiqbio.com | safepay | US | 2026-10-12T20:25:24.653800+00:00 |
| Aeroklas Duys / Duys Engineering Group | Deadlock | ZA | 2026-10-12T17:50:45.857578+00:00 |
| RingSide Creative | qilin | US | 2026-10-12T17:23:47.568408+00:00 |
| Claire's Inc. | Dark Project | US | 2026-10-12T16:51:07.130028+00:00 |
| PennEastern Architects LCC | Dark Project | US | 2026-10-12T16:51:51.868233+00:00 |
| Franklin Miller Inc. | Dark Project | US | 2026-10-12T16:52:44.213155+00:00 |
| Pedigo Products, Inc. | interlock | US | 2026-10-12T15:50:37.573403+00:00 |
| Valenti Management | interlock | CL | 2026-10-12T15:50:00.634347+00:00 |
| Concord Eye Center | interlock | US | 2026-10-12T15:49:17.358969+00:00 |
| Greentech Environmental | interlock |  | 2026-10-12T15:48:25.488147+00:00 |
| Engineers Contractors Fabricators Inc. (ECF) | interlock | US | 2026-10-12T15:47:49.993672+00:00 |
| Nu-Quest Distribution Inc | interlock | US | 2026-10-12T15:47:25.093736+00:00 |
| ConAuto | qilin | EC | 2026-10-12T14:50:15.217742+00:00 |
| Prodiel | qilin | ES | 2026-10-12T14:49:34.238836+00:00 |
| MyMichigan Health | metaencryptor | US | 2026-10-12T14:47:55.318406+00:00 |

## IOCs
### ThreatFox (recent, abuse.ch)
| Indicator | Type | Malware |
|---|---|---|
| indigonan.workers.dev | domain | php.shin_webshell |
| https://vr.6r6r6.org/qe | url | win.vidar |
| https://vr.6r6r6.org/kn/ | url | win.vidar |
| https://vr.6r6r6.org/kn | url | win.vidar |
| https://vr.6r6r6.org/q | url | win.vidar |
| https://vr.6r6r6.org/v9/ | url | win.vidar |
| https://vr.6r6r6.org/bn | url | win.vidar |
| https://vr.6r6r6.org/wc | url | win.vidar |
| https://vr.6r6r6.org/pq/ | url | win.vidar |
| https://vr.6r6r6.org/pq | url | win.vidar |
| https://vr.6r6r6.org/nl | url | win.vidar |
| https://65.109.255.31 | url | win.vidar |
| https://vr.6r6r6.org/u/ | url | win.vidar |
| namecheaps.duckdns.org | domain | win.remcos |
| https://vr.6r6r6.org/wm | url | win.vidar |
| https://vr.6r6r6.org/yv | url | win.vidar |
| 4614bb60faf9c9edfac1fa8c90d0c9f939a495cd47bea531142221f6919cabb1 | sha256_hash | osx.amos |
| https://vr.6r6r6.org/qwj/ | url | win.vidar |
| 147.182.144.201:8443 | ip:port | elf.aisuru |
| https://vr.6r6r6.org/rm2 | url | win.vidar |

### URLhaus (recent malicious URLs, abuse.ch)
| URL | Threat | Status |
|---|---|---|
| http://180.188.142.1:24689/i | malware_download | online |
| http://175.153.133.229:44327/Mozi.m | malware_download | online |
| http://45.135.194.96/bins/dbg | malware_download | online |
| http://38.46.31.127:54561/bin.sh | malware_download | online |
| http://104.223.84.34/pkgFkmn.txt | malware_download | online |
| http://104.223.84.34/rkgoaok.txt | malware_download | online |
| http://105.154.111.213:36032/i | malware_download | online |
| http://220.198.115.233:34039/bin.sh | malware_download | online |
| http://105.187.30.24:38917/bin.sh | malware_download | online |
| http://180.188.142.1:24689/bin.sh | malware_download | online |
| https://stat.bestcompliance.net/p | malware_download | online |
| https://stat.bestcompliance.net/s | malware_download | offline |
| http://105.225.40.144:45883/i | malware_download | online |
| https://bvmatqnam.com.vn/js/pp10.bin | malware_download | online |
| http://120.84.214.205:43902/i | malware_download | online |
| http://116.139.221.175:33222/i | malware_download | online |
| https://bvmatqnam.com.vn/js/see3.ps1 | malware_download | offline |
| https://bvmatqnam.com.vn/js/tt3.txt | malware_download | online |
| http://45.137.70.17/armv6l | malware_download | online |
| http://45.137.70.17/powerpc | malware_download | online |

### MalwareBazaar (recent samples, abuse.ch)
| SHA256 | File type | Signature |
|---|---|---|
| 68ce321d9ca45f9f206b03be37395880a124cf7616f65523725e9a6863275505 | abuse_ch | n/a |
| bd809b2f625d640a21fc9418538b686639b719f09e6c2efacffa49a7be3f613a | abuse_ch | n/a |
| b19f095b2d90e78011178060d8d63aff1c285c5be25f2df949dd8ada442889ff | abuse_ch | n/a |
| e4023b4b7a693fb18338f8a1c9c3c2998c6d3150dcf2528dec5025840e44036f | abuse_ch | Mirai |
| ad0d27bee2efabe56d584238d605fafd6ad6edbfae29b8a86f6b0c1bce4e1a2a | abuse_ch | Mirai |
| 34c3c6f2d3920e8643cdbd0bd7e66bba8d2a066ddd9e3eacd8c19b1c7694bce7 | abuse_ch | Mirai |
| 3cc6e26d1ac6aa7e804a51dbebb7edd134e3e48097b0bce49a85d1e1b0671e3a | abuse_ch | Mirai |
| 7322610f54ac41353161f90b35f975125eb65dedb5933c280ed197c8f6638749 | abuse_ch | Mirai |
| dc2adaa551af3e6fa6a76ec4f9c9599e39da33705dc22fe186d52f4b3c57a074 | abuse_ch | Mirai |
| 8323cf5a01e889abcb3bae7a498f4750fd4ad44f44495ca72fd42319cdd5560a | abuse_ch | Gafgyt |
| 3e95e873dedae3cbe5458444b3cca9270a7d8dfcc998eb79adc651a04c518413 | abuse_ch | Mirai |
| 56c3e4dd1d1a7e32c9fb9f43bf14d23bb4d5ece5aff9adf933c3bfde15cd26d5 | abuse_ch | Mirai |
| 8141fb252441eb74264b6adf1d3e2c887620f3e1afcd0506186b936439ccd665 | abuse_ch | Mirai |
| 03d477d4a5e14e77a482ef3b2a4f755ae73c02f167af38471e4f247639554ccf | abuse_ch | Gafgyt |
| 3e68de6f60c7fb5911837df0a5ce6a9aafd4e54a53af4c21bd8472fe16df4c67 | abuse_ch | Mirai |
| 498ac2d84c8ea5730bcb960556734a0e7407faeb33fb859f01602b93aed5d786 | abuse_ch | Mirai |
| d462900f4ea70ad634803710b3360bddabb6f74244e38c6c9854f6deb3cf4c6c | abuse_ch | Mirai |
| fef4ca17e2e6bf135e017fadbfab10bf89086b878139d6d0ac0d1443f97220d8 | abuse_ch | Mirai |
| d5872fe90fe7b76308f57b1d1ab7ebeb8eab06e55a67105774e2aa2a4b746720 | abuse_ch | Mirai |
| 05bdc12486c7b3f60e07653b3411be4beee7a29a6547bacd1b775717dbc4ea31 | Bitsight | NetSupport |

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
| 45.43.60.98 | 11 |
| 2.57.122.238 | 10 |
| 37.120.213.13 | 10 |
| 45.148.10.240 | 10 |
| 66.132.186.166 | 10 |
| 202.155.18.56 | 10 |
| 45.148.10.152 | 9 |
| 66.132.186.200 | 9 |
| 66.132.195.55 | 9 |
| 66.132.195.99 | 9 |
| 66.132.195.123 | 9 |
| 66.132.224.226 | 9 |
| 83.143.112.7 | 9 |
| 85.217.149.57 | 9 |
| 103.159.2.113 | 9 |
| 165.154.1.144 | 9 |
| 167.71.233.141 | 9 |
| 193.47.62.69 | 9 |
| 196.189.236.67 | 9 |

### OpenPhish (live phishing URLs)
- https://bit-mart-hub.zapier.app/
- http://cpcontacts.52-153-141-124.cprapid.com/?koncetlah&shem=aimgspe
- https://rodrigosilvaanalyst.github.io/netflix
- https://ritikbhanot9999.github.io/amazon-clone
- https://rahil-azam.github.io/first-website
- https://renew.badiatennisacademy.com/
- https://authentication.ms/E.6g0V0NJi5xcl?d5a3-42bb-878b-4d4037ebe007&action=block&121020261230&realm=iberdrola.es
- https://daydreamsonpaper.com/Https/
- https://mfacebook.vn/8u04di1oj1c?T6b&mNC
- https://authentication.ms/E.E9ue2_DXhYKDGg?/VGhlIG5leHQgZ2VuZXJhdGlvbiBvZiBzZWN1cml0eSBhd2FyZW5lc3MgaXMgZGVzaWduZWQgZm9yIGVtcGxveWVlcyBhbmQgYnVpbHQgZm9yIGVudGVycHJpc2VzLiBPdXIgaW5kdXN0cnktbGVhZGluZyByZXN1bHRzIGFyZSBwb3dlcmVkIGJ5IGNvZ25pdGl2ZSBhdXRvbWF0aW9uLg
- https://start-io-trezo.b12sites.com/
- https://trezo-enus.b12sites.com/
- https://gov-sp.com/
- http://lmtoken.wchmn.com/
- http://tptp.me/
- https://www.roblox.com.mu/users/6057951819/profile
- https://f006.backblazeb2.com/file/guitxc/index.html
- https://did.li/yAP6q
- https://deutsche-de-germany-immo.info/verschenken/84fyo12cro
- https://deutsche-de-immo.com/jad3bt

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://yandex.ru/showcaptcha?cc=1&form-fb-hint=2.1&mt=C921E95FBCFEECFAAD2E877A17A7EA6B7C448FDF6533DEC42859E758A0E889B817EBFA3A2D1B2829C40377BC7E6A465812F2756D321D6D81CB988EFB848959750DEFEB80C313627882EF45831C755CB19188F94615737B7D9495A65A64B593C18D07EF03D78B15DD0FC245A6ACF7D3A2E6CCBB0004FDC35607F5D6CEC049C41FDD8B5B2870E8BEE39A&retpath=aHR0cHM6Ly95YW5kZXgucnUvc2VhcmNoP3RleHQ9MjExNjg3MTc%2C_9e32ea590f1152ceb4677b92f96f1e0c&t=2%252F1791871191%252F401a7b9678c9e8fda2686a1c26ad6404&u=9569975650480212541&s=27050f50fd6689bfcb90f1ecee680296 |
| N/A | https://away.vk.ru/away.php?rh=b52bff35-9d7b-4eb9-9f92-e73a8e185d0f |
| N/A | https://away.vk.ru/away.php?rh=4277a4df-56a4-448d-8398-a5074b5eb3ca |
| N/A | https://flat-bread-04ca.cloudflareaccess.com/cdn-cgi/access/login/vertiv-command-center.pages.dev?kid=617efb6eb0445e77d08421b7c2075c08ed7302463271c62a28d702c82772462a&meta=eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiIsImtpZCI6IjEyY2U5NjlmMDk3YjUyNjliNjllZjA0N2EwMjBiZGI2NGMwMTc5NjMwNzE3MzJhMWJjODg2NjJiNGUxYzJjY2IifQ.eyJ0eXBlIjoibWV0YSIsImF1ZCI6IjYxN2VmYjZlYjA0NDVlNzdkMDg0MjFiN2MyMDc1YzA4ZWQ3MzAyNDYzMjcxYzYyYTI4ZDcwMmM4Mjc3MjQ2MmEiLCJob3N0bmFtZSI6InZlcnRpdi1jb21tYW5kLWNlbnRlci5wYWdlcy5kZXYiLCJyZWRpcmVjdF91cmwiOiIvIiwic2VydmljZV90b2tlbl9zdGF0dXMiOmZhbHNlLCJpc193YXJwIjpmYWxzZSwiaXNfZ2F0ZXdheSI6ZmFsc2UsImV4cCI6MTc5MTg3MDc2MSwibmJmIjoxNzkxODcwNDYxLCJpYXQiOjE3OTE4NzA0NjEsImF1dGhfc3RhdHVzIjoiTk9ORSIsIm10bHNfYXV0aCI6eyJjZXJ0X2lzc3Vlcl9kbiI6IiIsImNlcnRfc2VyaWFsIjoiIiwiY2VydF9pc3N1ZXJfc2tpIjoiIiwiY2VydF9wcmVzZW50ZWQiOmZhbHNlLCJjb21tb25fbmFtZSI6IiIsImF1dGhfc3RhdHVzIjoiTk9ORSJ9LCJyZWFsX2NvdW50cnkiOiJVUyIsImFwcF9zZXNzaW9uX2hhc2giOiIyYWNhZDM5NWVlM2I2ZjE5YmM1ZWRmYWFmYzM1NWQxZWNkNGRiYzc5ODY5MWRlYWEzNmI4YTA4OWFkYTVkNmQzIn0.Celsif0FlQ7ytmZBfH2D0z2lbebsIdgJsOPyct1ng942jL37n39qUvmRvIPa7z_kNc_lcEmXGGD-PTlwn1ZJthQUrU-Rvrh-UwDBt5QACfu4RyFHPSKq-0EiYeJPAgQc5HXfMtd85Pe9xvSuoIAkB54Os-iw_KnK8FKb9SglwMB8hIHdZsT1rWzNCqi7LdQTofjb-tlEa6eqpEv4xfgg2Nb9OOeayIPLNeiM0BM_8LFGRBdUyS4pK2a4aYPxYf558hmTem3IrOlmgJXNTWfnhBkFsfQ-wZMAl6jogHA4-deiL4voxJNj2s7_mGBTNyW-klh5GlQQNX3oUYrNghIVfQ&redirect_url=%2F |
| N/A | https://away.vk.ru/away.php?rh=770e105e-a1d4-4e9e-b87b-1b03afe2a030 |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=ASKXGp0_nbFzdHoBsG_d6znGlWE063OUXUJ-liVgQNfJJB3wA_mip4wV6In-9Cchxtm7MSHwtubxoQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SSS_BkV1nBq8-KHU_Ba1kZt_Nw84yfd0eZV6GezihZP103DTepI3ynTfk7BkakpJ-Tg0hM1&dsh=S1443256169%3A1791869889131897 |
| N/A | https://zupgn.dtpxkt.com/f2adb8b2-0564-b9e2-d132-2d73cfc0cf41/%E2%93%8A%E2%99%AB%E3%8A%AA%E2%99%AE%E2%99%95%E2%9E%B9%E2%9E%B5=kpqmtn |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AWnogHfrcMjMJOA5-x4JjU2A_H62FL5Ipip8qUn0FfsVqhu1vrUBPxBl4JpnqCjPGKNrTfaShVnNJQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06ST2qS0IUEZUixgYJOV_x5VfkGgS1lKCpji46eNdcgNTZVirok35U7Gdk0DsdU-RDz_jJLoPSw&dsh=S-1207793932%3A1791869733877910 |
| N/A | https://away.vk.ru/away.php?rh=6ad7cfda-5b05-4648-a182-317be214d710 |
| N/A | http://yamagatasilk.com/ |
| N/A | https://petbriteboutique.com/en/wp-includes/IXR/int/left |
| N/A | https://id.superhuman.com/signin?oauth_client_type=MEDIATED_WEB&correlation_id=EvekD7pAdOCtViX_L2whSw&version=v4&client_id=superhumanDocs |
| N/A | https://bancucuscatlan.com/ |
| N/A | https://away.vk.ru/away.php?rh=beec9e78-75a3-473a-82f7-eb9d3ef59ab8 |
| N/A | http://49.51.43.12/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=AWnogHe_pDujLaO-hl3d_3DQFjS6PW6JGM3LRrD13mxmiaQWTJuHz9b6nwmaSIh76M5SMOelnJex7g&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SQx6K0JDkuE9y94YZR0-y8UvA41XRqhKUnRQgMfXLynvAm5wLl4NZHODHx5KSZcfd4dXhhmzQ&dsh=S67281319%3A1791866853684486 |
| N/A | https://pageseuc1.actmkt.com/(S(zktyfvrfgyq41sdphiqah33t))/l/c5X8MfZz6j9Y7Fto3LAd |
| N/A | https://fbetlixgee.eu/get?p=4qGn9Lp5QFErG5X7sLMGQT&nid=5&ext_pub=6401&kw=&pm-click=3f558a490bce4ea3a7fa8f52c69a6b4d |
| N/A | https://pageseuc1.actmkt.com/(S(1pbx3lazorlzewxslrs3q433))/l/c5X8MfZz6j9Y7Fto3LAd |
| N/A | https://petbriteboutique.com/en/wp-includes/assets/eu/sint |
| N/A | http://afromantic.com/ |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| b3c1e060a727e4db1cf6131f1eb6e9bcca2ffb5d | PureRAT C&C |
| 11cfb1e85c316e9b9785c6778bc077bb04093dfd | PureLogsStealer C&C |
| c389945d4fc75250b291953e0abad0662dd9ce7d | Vidar C&C |
| 24ec954313877b212b522682aef606180ff6f343 | OffLoader C&C |
| 515574d4dc4957fbd0043d3a4269485384e504e7 | Vidar C&C |
| 51f9d6339bfdb9321630392913941e04d921cf7d | Vidar C&C |
| 9d4574e66ed485ca617fe78078a7dba674937bb3 | Vidar C&C |
| 629700c6fb58a48ce5c34e9e830225fad3e62634 | DCAgentRMM C&C |
| 6ae4974b641caa8b6aae8d3392e7fb4f8c7e3577 | DCAgentRMM C&C |
| 245f189a60a8b20a5dc562134b3d55d6539ac186 | Vidar C&C |
| ab1d61a4f4692b105daa345a7185119f0d29cb79 | Vidar C&C |
| 9769dce57ee77a6da94da9c824cd923cb9599892 | Vidar C&C |
| d621cfc19f287afe3b53ee95f4463732d2de342f | Malware C&C |
| 929b3729b42dabeb68077b03b2802e5b53ceade7 | ConnectWise C&C |
| 1c14689e58ebc09098f7c23eec08a314eb17ec76 | OffLoader C&C |
| 4a0c5885230b991333569023a767f7cc3a773baf | PureRAT C&C |
| 650f90b14ecb5dc0160ea61d0620402c075c2f3d | QuasarRAT C&C |
| 64d01c8e86e0a3b51c270743879a1fe966af0db4 | QuasarRAT C&C |
| 06fc4c98539ff52b4e4db8c2a69ba0b755d96bf9 | PureRAT C&C |
| 0f0a58e91f1c0f21ec7934e2f5e6b54187ed54be | QuasarRAT C&C |

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
- 1.0.164.165
- 1.14.240.247
- 1.15.221.192
- 1.159.54.33
- 1.188.168.41
- 1.2.225.235
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.220.198.126
- 1.222.42.237
- 1.227.228.131
- 1.235.14.41
- 1.235.183.146
- 1.237.155.150
- 1.238.106.229
- 1.247.245.61
- 1.250.67.114
- 1.250.67.190
- 1.27.251.252

### CINS Army (poorly-rated IPs)
- 1.145.29.140
- 1.15.14.29
- 1.20.173.155
- 1.213.214.233
- 1.215.138.43
- 1.24.16.101
- 1.24.16.106
- 1.24.16.109
- 1.24.16.120
- 1.24.16.139
- 1.24.16.147
- 1.24.16.159
- 1.24.16.161
- 1.24.16.170
- 1.24.16.190
- 1.24.16.191
- 1.24.16.192
- 1.24.16.194
- 1.24.16.196
- 1.24.16.32

## News (last ~36h, across outlets)
### The Hacker News
- [Low-Cost Android Phones Ship With Preinstalled Malware That Turns Them Into Residential Proxies](https://thehackernews.com/2026/10/low-cost-android-phones-ship-with.html)
- [⚡ Weekly Recap: Helpdesk 0-Days, Rogue Certs, ShinyHunters Arrest, AI-Fooling Malware and More](https://thehackernews.com/2026/10/weekly-recap-helpdesk-0-days-rogue.html)
- [Bring Your Own Agent: Your Employees' Assistants Are Already Logged In](https://thehackernews.com/2026/10/bring-your-own-agent-your-employees.html)
- [Ledger Finds Unauthorized Hardware Implant in CryptoBilis-Sold Wallet Amid Fund Theft Reports](https://thehackernews.com/2026/10/ledger-finds-unauthorized-hardware.html)
- [Critical SonicWall SMA 1000 Flaw Targeted in 135 Exploitation Attempts After Patch](https://thehackernews.com/2026/10/critical-sonicwall-sma-1000-flaw.html)
- [Attackers Exploit CVSS 10.0 Bricksforge WordPress Flaw Enabling Unauthenticated RCE](https://thehackernews.com/2026/10/attackers-exploit-cvss-100-bricksforge.html)
- [CyberXero Uses Claude Code in Campaign That Stole Over 628,000 Ukrainian Records](https://thehackernews.com/2026/10/cyberxero-uses-claude-code-in-campaign.html)

### BleepingComputer
- [Norway fines Microsoft ad firm $9.6 million over Grindr data sharing](https://www.bleepingcomputer.com/news/security/norway-fines-microsoft-ad-firm-96-million-over-grindr-data-sharing/)
- [Yandex confirms service outage as users lose access to cloud files](https://www.bleepingcomputer.com/news/security/yandex-confirms-service-outage-as-users-lose-access-to-cloud-files/)
- [Anthropic takes risky AI tests offline after models breach govt sites](https://www.bleepingcomputer.com/news/security/anthropic-takes-risky-ai-tests-offline-after-models-breach-govt-sites/)
- [Ledger confirms spy chip implant behind wallet crypto thefts](https://www.bleepingcomputer.com/news/security/ledger-confirms-hardware-wallet-spy-implant-behind-crypto-thefts/)
- [Cyberattack shuts down refrigerators at French supermarkets](https://www.bleepingcomputer.com/news/security/cyberattack-shuts-down-refrigerators-at-french-supermarkets/)
- [Inside AvisLoader: A Windows Malware Loader Built to Resist Disruption](https://www.bleepingcomputer.com/news/security/inside-avisloader-a-windows-malware-loader-built-to-resist-disruption/)
- [Retail giant Ahold Delhaize takes systems offline after cyberattack](https://www.bleepingcomputer.com/news/security/retail-giant-ahold-delhaize-takes-systems-offline-after-cyberattack/)
- [GitLab warns of max severity code execution vulnerability](https://www.bleepingcomputer.com/news/security/gitlab-warns-of-max-severity-rce-flaw-in-regex-compiler-engine/)
- [Microsoft: Windows 11 23H2 reaches end of support in 30 days](https://www.bleepingcomputer.com/news/microsoft/microsoft-windows-11-23h2-reaches-end-of-support-in-30-days/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [Maximum-Severity SSRF Flaw in SonicWall SMA Devices Under Attack](https://www.darkreading.com/vulnerabilities-threats/max-severity-ssrf-flaw-sonicwall-sma-devices-under-attack)
- [Prominent Ransomware Negotiator Faces Extortion Charges](https://www.darkreading.com/insider-threats/prominent-ransomware-negotiator-extortion-charges)
- [No Identity, No Recovery: Cyber Resilience Starts With IAM](https://www.darkreading.com/cybersecurity-operations/cyber-resilience-starts-with-iam)
- [Passing the Baton: Dark Reading Names New Editor-in-Chief](https://www.darkreading.com/cyber-risk/passing-baton-dark-reading-new-editor-in-chief)

### SecurityWeek
- [IonQ to Acquire Zero Trust Firm Elisity for Up to $1.3 Billion](https://www.securityweek.com/ionq-to-acquire-zero-trust-firm-elisity-for-up-to-1-3-billion/)
- [Bricksforge WordPress Plugin Vulnerability Exploited in the Wild](https://www.securityweek.com/bricksforge-wordpress-plugin-vulnerability-exploited-in-the-wild/)
- [Canonical Websites Disrupted in Second DDoS Attack This Year](https://www.securityweek.com/canonical-websites-disrupted-in-second-ddos-attack-this-year/)
- [Mastermind of 15,000-Mule Cybercrime Laundering Network Pleads Guilty in US](https://www.securityweek.com/mastermind-of-15000-mule-cybercrime-laundering-network-pleads-guilty-in-us/)
- [iRhythm Data Breach Impacts at Least 360,000 People](https://www.securityweek.com/irhythm-data-breach-impacts-over-360000-people/)
- [Ransomware Response Expert Arrested in ShinyHunters FBI Hack Probe](https://www.securityweek.com/ransomware-response-expert-arrested-in-shinyhunters-fbi-hack-probe/)
- [Critical SonicWall Vulnerability Exploited Days After Disclosure](https://www.securityweek.com/critical-sonicwall-vulnerability-exploited-days-after-disclosure/)
- [Let’s Encrypt Cuts Default Certificate Validity to 64 Days Ahead of 45-Day Switch](https://www.securityweek.com/lets-encrypt-cuts-default-certificate-validity-to-64-days-ahead-of-45-day-switch/)

### The Record
- [Ukraine strikes third Yandex data center, disrupting digital services across Russia](https://therecord.media/ukraine-strikes-third-yandex-data-center)
- [Cyberattack disrupts refrigeration at hundreds of French supermarkets](https://therecord.media/cyberattack-disrupts-refridgeration-in-france)

### Infosecurity Magazine
- [Luna Moth Leaks Shed Light on Ransomware Group's Inner Workings](https://www.infosecurity-magazine.com/news/luna-moth-leaks-ransomware-playbook/)
- [Major French Supermarket Chains Hit by Cyber-Attack, Food Stock Impacted](https://www.infosecurity-magazine.com/news/french-supermarket-chains/)
- [Net Closes Around ShinyHunters with Another FBI Arrest](https://www.infosecurity-magazine.com/news/net-closes-shinyhunters-another/)
- [Months-Old Palo Alto VPN Vulnerability Remains a Target for Ransomware Groups](https://www.infosecurity-magazine.com/news/palo-alto-vpn-vulnerability-target/)
- [Karaoke Giant Reveals Data Breach Impacting Eight Million](https://www.infosecurity-magazine.com/news/karaoke-giant-data-breach-eight/)

### CyberScoop
- [Flock can now issue CVEs for its own products. Should we trust it?](https://cyberscoop.com/flock-cve-numbering-authority-cna/)
- [IonQ to buy zero-trust security firm Elisity in deal valued at up to $1.3 billion](https://cyberscoop.com/ionq-acquires-elisity-1-3-billion-quantum-security/)
- [Your AI agent is only as safe as the packages it downloads](https://cyberscoop.com/ai-agent-software-supply-chain-security-op-ed/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Tuesday, October 13th, 2026 https://isc.sans.edu/podcastdetail/10134, (Tue, Oct 13th)](https://isc.sans.edu/diary/rss/33418)
- [ISC Stormcast For Monday, October 12th, 2026 https://isc.sans.edu/podcastdetail/10132, (Mon, Oct 12th)](https://isc.sans.edu/diary/rss/33416)

### Securelist (Kaspersky)
_No new items / feed unavailable this run._

### CrowdStrike Blog
- [Solving the Continuous Authorization Conundrum](https://www.crowdstrike.com/en-us/blog/solving-the-continuous-authorization-conundrum/)
- [CrowdStrike and Anthropic Give Critical Infrastructure Defenders the AI Advantage](https://www.crowdstrike.com/en-us/blog/crowdstrike-anthropic-critical-infrastructure-defense-program/)
- [Unknown Threat Actor Uses AI-Driven ARTEX to Target South Korean Finance](https://www.crowdstrike.com/en-us/blog/unknown-threat-actor-uses-artex-to-target-south-korean-finance/)
- [CrowdStrike Named a Leader in the 2026 IDC MarketScape for Worldwide Modern Endpoint Security for Enterprises Vendor Assessment](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-idc-marketscape-worldwide-modern-endpoint-security-for-enterprises/)
- [Request, Aggregate, Bypass: How Attackers Can Evade LLM Safety Classifiers](https://www.crowdstrike.com/en-us/blog/how-attackers-can-bypass-llm-safety-classifiers/)
- [Falcon Data Security for SaaS Secures Sensitive Data in Microsoft 365](https://www.crowdstrike.com/en-us/blog/falcon-data-security-for-saas-secures-sensitive-data/)
- [New in Falcon Cloud Security: Third-Party App Insights and AI-Enhanced Remediation](https://www.crowdstrike.com/en-us/blog/falcon-cloud-security-third-party-app-insights-ai-enhanced-remedation/)
- [CrowdStrike Expands Federal SOC Modernization Through CISA-Funded SIEMaaS](https://www.crowdstrike.com/en-us/blog/crowdstrike-expands-federal-soc-modernization-via-cisa-siemaas/)
- [Copy, Paste, Compromised: How ClickFix Attacks Work and How CrowdStrike Stops Them](https://www.crowdstrike.com/en-us/blog/how-clickfix-attacks-work-and-how-to-stop-them/)
- [A Win for Defenders: CrowdStrike and NVIDIA Extend Security Across the AI Stack](https://www.crowdstrike.com/en-us/blog/crowdstrike-nvidia-extend-security-across-ai-stack/)

### FortiGuard Threat Signal
_No new items / feed unavailable this run._

## Fetch issues this run
_None — all sources responded._

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal