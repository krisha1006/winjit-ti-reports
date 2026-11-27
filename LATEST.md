# Winjit Daily TI Digest — 2026-11-27

_Auto-generated. Window: last ~24h. Fetched at 2026-11-27T11:55:02.360038+00:00Z_

**At a glance:** 0 new KEV · 155 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-137043 | 10.0 | 0.8% | A security vulnerability has been detected in TOTOLINK N350RT 9.3.5u.6468_B20250827/9.3.5u.6466_B20250825. The affected element is the function setLanguageCfg of the file /cgi-bin/cstecgi.cgi. Such ma |
| CVE-2026-137498 | 10.0 | n/a | Budibase Server from 3.39.18 before 4.0.0 contains a prototype pollution vulnerability that allows unauthenticated attackers to erase MongoDB query filters by supplying __proto__ as a dynamic JSON key |
| CVE-2026-137494 | 9.9 | n/a | Budibase before 4.0.0 contains a broken object-level authorization vulnerability that allows authenticated users with table write access to reference other tenants' files by supplying arbitrary attach |
| CVE-2026-137706 | 9.9 | n/a | Smart Portal developed by Direk Tech has a Missing Authorization vulnerability. Authenticated remote attackers can add a specified account to the Active Directory Domain Admins group, thereby obtainin |
| CVE-2026-137567 | 9.8 | n/a | llama.cpp b11450 before b12658 contains an out-of-bounds write vulnerability in the ggml RPC server that allows unauthenticated attackers to write to arbitrary heap addresses via zero-element destinat |
| CVE-2026-104998 | 9.8 | n/a | The Product Input Fields for WooCommerce plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 2.1.0 via the process_file_input_field function. This is due  |
| CVE-2026-137499 | 9.8 | n/a | Budibase from 3.41.0 before 4.0.0 contains an authentication bypass vulnerability that allows unauthenticated attackers to take over password-less global Builder accounts via unverified-email OIDC/SSO |
| CVE-2026-137536 | 9.8 | n/a | ToolJet before 3.21.94-beta contains an authentication bypass in its server OAuth SSO sign-in module, which resolves Google and Git SSO logins solely by the provider-asserted email without checking em |
| CVE-2026-137550 | 9.8 | n/a | Frappe Framework before 15.122.0 and 16.x before 16.50.0 contains a missing authorization vulnerability in Document.update() that fails to validate whether the caller is permitted to submit or modify  |
| CVE-2026-106125 | 9.8 | n/a | The Sneeit Framework plugin for WordPress is vulnerable to Remote Code Execution in versions up to, and including, 8.7 via the 'callback' parameter of the sneeit_compact_menu_mega_content AJAX action. |
| CVE-2026-115867 | 9.8 | n/a | The Database for Contact Form 7, WPforms, Elementor forms plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 1.5.5 via the copy_files function. This is d |
| CVE-2026-137481 | 9.3 | n/a | Traefik before 2.11.62, 3.x before 3.7.18, and 3.8.0-rc.1 contain an authorization bypass because the sanitizePath entry point option leaves dot-segments carrying path parameters, such as /..;x/, unre |
| CVE-2026-133951 | 9.1 | n/a | The Simple Membership plugin for WordPress is vulnerable to Privilege Escalation in versions up to, and including, 4.8.9 This is due to the site-wide signing secret `swpm_private_key_one` being genera |
| CVE-2026-134173 | 9.1 | n/a | The WordPress File Upload plugin for WordPress is vulnerable to Arbitrary File Deletion in versions up to, and including, 5.3.1 via the 'wfu_ajax_action_handshake' and 'wfu_ajax_action_send_email_noti |
| CVE-2026-135641 | 9.1 | n/a | The WP Job Portal – AI-Powered Recruitment System for Company or Job Board website plugin for WordPress is vulnerable to Authentication Bypass leading to Account Takeover in all versions up to, and in |
| CVE-2026-136240 | 9.1 | n/a | The PDF Invoice for WooCommerce + Drag and Drop Template Builder plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 7.2.0 via deserialization of untrusted |
| CVE-2026-137544 | 9.1 | n/a | LaraDashboard before 1.5.0 contains a path traversal vulnerability in module.json providers and composer.json psr-4 namespace parsing that derives destination folder names without excluding traversal  |
| CVE-2026-137305 | 8.8 | 0.7% | Grav Form plugin before 9.2.4 contains a code injection vulnerability that allows page authors to write uploads into Twig template folders by setting an unchecked file field destination in Form::uploa |
| CVE-2026-137389 | 8.8 | 1.3% | MailGates/MailAudit developed by Openfind has a Command Injection vulnerability.Authenticated remote attackers can inject commands and execute them on the server. |
| CVE-2026-137390 | 8.8 | 1.3% | Mail2000 developed by Openfind has an OS Command Injection vulnerability.Authenticated remote attackers can inject arbitrary OS commands and execute them on the server. |
| CVE-2026-137566 | 8.8 | n/a | Argo Workflows 3.0.0 through 3.7.18, 4.0.0 before 4.0.12, and 4.1.0 before 4.1.4 contains a path traversal vulnerability in the S3, GCS, and Azure Blob artifact drivers. Attackers who can write bucket |
| CVE-2026-137470 | 8.8 | n/a | SiYuan before 3.8.11 contains a stored cross-site scripting vulnerability that allows attackers to inject DOM event handlers by storing handler-named block attributes such as onmouseover. Attackers ca |
| CVE-2026-137490 | 8.8 | n/a | SurrealDB before 4.0.0 contains an authorization bypass vulnerability that allows restricted subjects to execute arbitrary queries by calling the JavaScript surrealdb.query() bridge. Attackers permitt |
| CVE-2026-137492 | 8.8 | n/a | Budibase before 4.0.0 contains an authorization bypass vulnerability that allows workspace-scoped builders to access other workspaces' backups by supplying a foreign backupId. Attackers can substitute |
| CVE-2026-137523 | 8.8 | n/a | ToolJet before 3.21.96-LTS contains an authentication bypass in instance-level Google SSO because the id_token audience is not verified when no Google OAuth client ID is configured, the shipped defaul |
| CVE-2026-137526 | 8.8 | n/a | ToolJet before 3.21.96-LTS contains an authorization bypass in the internal database (TJDB) PostgREST proxy, which grants proxy access to every logged-in user and derives the database role and schema  |
| CVE-2026-137556 | 8.8 | n/a | Dockhand before 1.0.57 contains a path traversal vulnerability in validateStackPath, which omits the isProtectedPath() check and permits writes to protected system directories. Authenticated users wit |
| CVE-2026-76075 | 8.8 | n/a | The Warehouse Cargo theme for WordPress is vulnerable to Arbitrary File Upload in versions up to, and including, 2.7.4 via the warehouse_cargo_install_and_activate_plugin() AJAX handler. The handler i |
| CVE-2026-137539 | 8.8 | n/a | lastversion before 3.6.20 contains a path traversal vulnerability in extract_tar() that allows attackers to write files outside the extraction directory via tar symlink members. Attackers controlling  |
| CVE-2026-113774 | 8.8 | n/a | The Schema & Structured Data for WP & AMP plugin for WordPress is vulnerable to PHP Object Injection in versions up to, and including, 1.68. This is due to deserialization of untrusted input via the a |
| CVE-2026-137704 | 8.8 | n/a | D-Link DWM-222W developed by D-Link Corporation has a Use of Hard-coded Credentials vulnerability. Unauthenticated adjacent network attackers can use the administrator account embedded in the firmware |
| CVE-2026-66784 | 8.7 | 0.5% | A flaw was found in Submariner. In its default Pre-Shared Key (PSK) mode, all gateways within a broker set utilize the same PSK. An attacker, by knowing this shared PSK, can forge an Endpoint Custom R |
| CVE-2026-137478 | 8.7 | n/a | Traefik before 2.11.62, 3.x before 3.7.18, and 3.8.0-rc.1 contain an authentication bypass in the ForwardAuth middleware because connection isolation for NTLM and Negotiate credentials checks only the |
| CVE-2026-137480 | 8.7 | n/a | Traefik 3.7.15 before 3.7.18 and 3.8.0-rc.1 before 3.8.0-rc.2 contains a client certificate authentication bypass in the Kubernetes Ingress NGINX provider because, on hosts shared by multiple Ingresse |
| CVE-2026-137471 | 8.3 | n/a | SiYuan before 3.8.10 contains a cross-site scripting vulnerability where WebDAV sync error formatting skips HTML escaping for certain malformed-response errors, passing raw markup to the Electron noti |
| CVE-2026-93087 | 8.2 | n/a | A maliciously modified field in the locally stored JSON description for an update made available by Autodesk, when processed by Autodesk Access, can cause attacker-controlled HTML content to be execut |
| CVE-2026-137456 | 8.2 | n/a | FreeRDP before 3.33.0 contains an integer overflow in the client GDI handling of accumulated drawing-order bounds: wrapped INT32 coordinates yield a zero-width clip region that causes clipping to be s |
| CVE-2026-133842 | 8.2 | n/a | A flaw was found in Flatpak’s flatpak-system-helper. When a system-wide app, runtime, or extension uses the extra-data mechanism and its apply_extra logic creates a deeply nested directory tree, permi |
| CVE-2026-130805 | 8.1 | n/a | The Groundhogg plugin for WordPress is vulnerable to Cross-Site Request Forgery in versions up to, and including, 4.11 This is due to the Admin_Page::page() callback dispatching methods named directly |
| CVE-2026-131688 | 8.1 | n/a | The Secure MCP Server for Claude, ChatGPT, Gemini, Cursor and other AI Agents plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 1.5.8 This is due to the  |
| CVE-2026-137577 | 8.1 | n/a | Iceburg CRM through 5.0.0 contains an authorization bypass vulnerability that allows authenticated low-privileged users to modify any user record by supplying arbitrary record_id values to POST /data/ |
| CVE-2026-103886 | 8.1 | n/a | The App Builder – Create Native Android & iOS Apps On The Flight plugin for WordPress is vulnerable to Authentication Bypass via Google ID Token Audience Validation Bypass in all versions up to, and i |
| CVE-2026-137491 | 8.1 | n/a | Budibase before 4.0.0 contains a query injection vulnerability that allows low-privilege or anonymous users to inject AQL or SQL by supplying unescaped parameters to ArangoDB and Snowflake queries. At |
| CVE-2026-137493 | 8.1 | n/a | Budibase server from 3.0.0 before 4.0.0 contains an authorization bypass vulnerability that allows view users and anonymous visitors to access entire base tables by passing a view id to the /api/:view |
| CVE-2026-137503 | 8.1 | n/a | Budibase before 4.0.0 contains a JSON injection vulnerability that allows attackers to inject JSON structure into S3 delete and Google Sheets row fields via unescaped template parameters. Attackers ca |
| CVE-2026-137547 | 8.1 | n/a | Coder before 2.29.27, 2.30.0 before 2.34.19, 2.35.0 before 2.37.11, 2.38.0 before 2.38.7, and 2.39.0 before 2.39.1 returns database connection errors containing a temporary AWS IAM database password i |
| CVE-2026-119071 | 8.1 | n/a | The W3 Total Cache plugin for WordPress is vulnerable to unauthorized File Deletion in all versions up to, and including, 2.11.0 via the `ajax_revert()` AJAX handler. The vulnerability exists because  |
| CVE-2026-137506 | 7.8 | n/a | ezdxf through 1.4.5 contains a code injection vulnerability in the dxf2code add-on that allows attackers to inject Python code via unescaped single quotes in DXF table entry names. Attackers can craft |
| CVE-2026-137518 | 7.8 | n/a | pyfda through 0.9.5 contains an insecure deserialization vulnerability in load_filter() that allows attackers to execute code by supplying crafted .npz or .pkl filter files. Attackers can embed a __re |
| CVE-2026-137529 | 7.8 | n/a | JAL (Just Another Ledger) through 2026.11.3 contains an arbitrary file overwrite vulnerability in backup restore that allows attackers to write files by supplying a crafted .tgz backup with a symlink  |
| CVE-2026-137542 | 7.7 | n/a | LaraDashboard before 1.5.2 contains an information disclosure vulnerability in SettingObserver that writes full Setting models, including plaintext secret option_value fields, into the action_logs tab |
| CVE-2026-137543 | 7.7 | n/a | LaraDashboard before 1.5.2 contains a server-side request forgery vulnerability that allows authenticated users to reach internal services by abusing the unvalidated ai_ollama_base_url setting. Once a |
| CVE-2026-135772 | 7.6 | 0.6% | RTL8762C MCU developed by Realtek Semiconductor Corporation has an Improper Protection Against Voltage and Clock Glitches vulnerability. Unauthenticated attackers with physical access can use speciali |
| CVE-2026-137496 | 7.6 | n/a | Budibase before 4.0.0 contains a server-side template injection vulnerability that allows authenticated users with table read permission to execute JavaScript by injecting Handlebars js helpers into r |
| CVE-2026-137511 | 7.6 | n/a | Scriban before 7.6.0 contains a state isolation vulnerability because TemplateContext.Reset() does not clear the Tags dictionary holding array.cycle and math.random state. Attackers supplying template |
| CVE-2026-124211 | 7.5 | n/a | The Ninja Tables – Responsive Table Builder for Data, Pricing & Product Tables plugin for WordPress is vulnerable to SQL Injection via the 'dateFormat' column metadata parameter in versions up to, and |
| CVE-2026-135151 | 7.5 | n/a | The Download Manager plugin for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 3.3.78 via the 'file[page_template]' parameter parameter. This makes it possible f |
| CVE-2026-135266 | 7.5 | n/a | The Music Player for WooCommerce plugin for WordPress is vulnerable to Directory Traversal in all versions up to, and including, 1.9.4 via the '_downloadable_files' parameter parameter. This makes it  |
| CVE-2026-137585 | 7.5 | n/a | Bazarr 1.4.4 before 1.6.1-beta.29 on Windows contains an unauthenticated path traversal vulnerability in the catch_all() handler in bazarr/app/ui.py. Attackers can append percent-encoded '..' segments |
| CVE-2026-137586 | 7.5 | n/a | LibreChat 0.7.3 before 0.8.9 contains an improper input type validation vulnerability in the requireLdapAuth middleware of the /api/auth/login route that allows unauthenticated attackers to crash the  |
| CVE-2026-126089 | 7.5 | n/a | The Drag and Drop Multiple File Upload (Pro) - WooCommerce plugin for WordPress is vulnerable to generic SQL Injection via the 'wc-upload-file (array key)' parameter in all versions up to, and includi |
| CVE-2026-130331 | 7.5 | n/a | The WP Statistics – Simple, privacy-friendly Google Analytics alternative plugin for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 14.16.19 via the 'tab' parame |
| CVE-2026-136488 | 7.5 | n/a | The GeoDirectory – WP Business Directory Plugin and Classified Listings Directory plugin for WordPress is vulnerable to generic SQL Injection via the 'stype' parameter in all versions up to, and inclu |
| CVE-2026-109586 | 7.5 | n/a | The WP STAGING – Backups & Restore, Migration & Clone Plugin – Cloud Backups, Scheduled Backups plugin for WordPress is vulnerable to Authorization Bypass in all versions up to, and including, 4.17.0  |
| CVE-2026-137452 | 7.5 | n/a | FreeRDP before 3.33.0 contains a race condition in asynchronous RDPDR IRP processing that allows malicious RDP servers to leak client memory through non-atomic wStream reference count updates. Attacke |
| CVE-2026-137455 | 7.5 | n/a | The FreeRDP proxy in FreeRDP before 3.33.0 dereferences a NULL backend client context in pf_server_refresh_rect and pf_server_suppress_output, which are guarded only by a debug-only WINPR_ASSERT, when |
| CVE-2026-137457 | 7.5 | n/a | FreeRDP from 3.0.0 before 3.33.0 contains a missing authentication vulnerability in the shadow server's fast-path input handlers in fastpath.c that allows unauthenticated attackers to inject input bef |
| CVE-2026-137459 | 7.5 | n/a | FreeRDP 2.11.2 before 3.33.0 contains unbounded resource consumption in the Progressive codec because progressive_decompress() resets the tile update batch only when frameId changes. A malicious RDP s |
| CVE-2026-137460 | 7.5 | n/a | FreeRDP from 3.10.0 before 3.33.0 contains an invalid free vulnerability in rdg.c because the websocket context pointer shares a union with chunked transfer-encoding decoder state. A malicious RD Gate |
| CVE-2026-137467 | 7.5 | n/a | SiYuan before 3.8.11 uses DejaVu sync code that accepts a non-hexadecimal 40-byte remote index ID from WebDAV responses and joins it into the repository indexes path unchecked, allowing path traversal |
| CVE-2026-137468 | 7.5 | n/a | SiYuan from 3.8.0 before 3.8.11 contains a lockout bypass vulnerability that allows remote attackers to brute-force publish passwords by forging client-computable publish-auth-<ID> cookies. Attackers  |
| CVE-2026-137469 | 7.5 | n/a | SiYuan 3.7.0 before 3.8.11 contains a DOM-based cross-site scripting vulnerability in the AI agent chat panel, which renders final and saved assistant replies into innerHTML without HTML sanitisation. |
| CVE-2026-137479 | 7.5 | n/a | Traefik 3.1.0 before 3.7.18 and 3.8.0-rc.1 contain a memory exhaustion vulnerability in the Compress middleware, which creates zstd encoders with library default options that retain about 18 MiB of st |
| CVE-2026-137497 | 7.5 | n/a | Budibase before 4.0.0 contains an information disclosure vulnerability that allows unauthenticated attackers to retrieve legacy LiteLLM credentials by querying the public settings endpoint. Attackers  |
| CVE-2026-137504 | 7.5 | n/a | actix-multipart (actix-web) before 0.8.7 contains a resource exhaustion vulnerability in the MultipartForm extractor that allows unauthenticated attackers to exhaust memory or file descriptors by send |
| CVE-2026-137508 | 7.5 | n/a | Scriban before 7.6.0 contains a memory exhaustion vulnerability in object.to_json that allows template authors to bypass the LimitToString string length limit by serializing into an unbounded MemorySt |
| CVE-2026-137509 | 7.5 | n/a | Scriban before 7.6.0 contains a resource exhaustion vulnerability that allows template authors to bypass LimitToString by rendering a ScriptObject with many members. Attackers can supply a small templ |
| CVE-2026-137510 | 7.5 | n/a | Scriban and Scriban.Signed before 7.6.0 allow template authors to bypass the LimitToString string length limit because the string.literal, string.base64_encode, html.escape, html.newline_to_br, html.u |
| CVE-2026-137512 | 7.5 | n/a | Scriban before 7.6.0 contains a resource exhaustion vulnerability that allows attackers to bypass LoopLimit by supplying large JSON input to object.from_json. Attackers can pass a flat JSON array or o |
| CVE-2026-137513 | 7.5 | n/a | justhtml before 3.17.0 contains a denial of service vulnerability in decode_entities_in_text that allows unauthenticated attackers to crash parsing via non-ASCII Unicode digits in numeric character re |
| CVE-2026-137549 | 7.5 | n/a | pypdf before 7.0.1 contains a resource exhaustion vulnerability in image loading because data size estimates for some image modes are too low, defeating limits for filters without their own size limit |
| CVE-2026-137552 | 7.5 | n/a | Frappe Framework before 15.121.1 and 16.x before 16.35.0 accepts an undocumented OAuth2 Resource Owner Password Credentials (password) grant at its token endpoint, which does not enforce two-factor au |
| CVE-2026-92251 | 7.5 | n/a | The ZarinPal Payment Gateway for WooCommerce plugin for WordPress is vulnerable to Insecure Direct Object Reference in versions up to, and including, 5.1.1 via the `Return_from_ZarinPal_Gateway()` han |
| CVE-2026-97345 | 7.5 | n/a | The SumUp Payment Gateway For WooCommerce plugin for WordPress is vulnerable to Insecure Direct Object Reference in versions up to, and including, 2.17.1 via the 'sumup-validate-order' query parameter |
| CVE-2026-137657 | 7.5 | n/a | InternLM LMDeploy 0.9.0 through 0.18.0 contains an unbounded resource allocation vulnerability in the DistServe proxy /distserve/connection_warmup endpoint that allows unauthenticated attackers to exh |
| CVE-2026-135616 | 7.5 | n/a | The W3 Total Cache plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 2.11.0 via deserialization of untrusted input that is injected into the Memcached ob |
| CVE-2026-137705 | 7.5 | n/a | Smart Portal developed by Direk Tech has an Arbitrary File Read vulnerability.Unauthenticated remote attackers can exploit Relative Path Traversal to download arbitrary system files. |
| CVE-2026-135626 | 7.5 | n/a | The Simple Membership plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 4.9.0 This is due to the `SwpmLevelForm::role()` function applying only `sanitize |
| CVE-2026-135627 | 7.5 | n/a | The Simple Membership plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 4.9.0 The vulnerability exists because the `bulk_operation_menu()` function accep |
| CVE-2026-137308 | 7.4 | 0.6% | markdownify-mcp before 1.2.0 contains a server-side request forgery vulnerability that allows attackers to bypass URL validation by supplying DNS names, bracketed IPv6 literals, or IPv4-mapped IPv6 ad |
| CVE-2026-137584 | 7.4 | n/a | Twenty through 2.63.0 in multi-workspace mode contains an authentication bypass vulnerability that allows unauthenticated attackers to obtain pending invitation tokens by registering an invitee's emai |
| CVE-2026-137463 | 7.4 | n/a | HKUDS nanobot from 0.1.4 before 0.4.1 contains an improper certificate validation vulnerability in the OpenAI Codex provider that retries authenticated requests without TLS certificate or hostname ver |
| CVE-2026-137465 | 7.4 | n/a | Parse Server 3.10.0 before 8.6.123 and 9.0.0 before 9.11.1-alpha.4 contains an authentication bypass in the Google Play Games authentication adapter, which does not verify that the supplied player ID  |
| CVE-2026-136946 | 7.3 | 1.5% | A vulnerability was identified in philipjscott simple-thumbnail up to 1.6.5. This issue affects the function ffmpegExecute of the file index.js. The manipulation of the argument seek leads to os comma |
| CVE-2026-136947 | 7.3 | 0.4% | A security flaw has been discovered in msaifulcsse Ticket-Travel-Management-System 28b68cea41b3a9eb8d533db992e0b5ba2db68854/15c7bc0b48c263233326bb227fef01efc54c24a7. Impacted is an unknown function of |
| CVE-2026-137046 | 7.3 | 0.5% | A vulnerability was detected in mahmoudai1 school-management-system up to ecec9faaf2fb1a3c5cd096e063f8ef326d09cdfd. The impacted element is the function userModel::checkUserInDB of the file loginServe |
| CVE-2026-137324 | 7.3 | 0.5% | A flaw has been found in shemaikuzwe Attendance_Management_system up to b37dbeb5bf4d9eab07480e7b6213db889fc3ebf9. Affected by this issue is some unknown functionality of the file index.php. Executing  |
| CVE-2026-137403 | 7.3 | n/a | A vulnerability was determined in SourceCodester Online Food Ordering System 1.0. This affects an unknown function of the file /admin/update_food.php. Executing a manipulation of the argument price ca |
| CVE-2026-137538 | 7.3 | n/a | ToolJet before 3.21.96-LTS contains an insufficient session expiration vulnerability that allows attackers to reuse expired JWTs because the passport-jwt strategy sets ignoreExpiration to true. Attack |
| CVE-2026-137409 | 7.3 | n/a | A flaw has been found in chuckfairy node-webcam up to 0.8.2. This vulnerability affects the function generateSh of the file src/webcams/FSWebcam.js of the component FSWebcam. Executing a manipulation  |
| CVE-2026-137411 | 7.3 | n/a | A vulnerability was found in projectworlds Online Jewellery Shopping System 1.0. Impacted is the function searchItem of the file application/models/dashbord_model.php of the component Dashbord Search. |
| CVE-2026-137412 | 7.3 | n/a | A vulnerability was determined in projectworlds Online Jewellery Shopping System 1.0. The affected element is the function Dashbord_model.searchAdvance of the file /jewllary-shop/application/models/da |
| CVE-2026-137414 | 7.3 | n/a | A vulnerability was identified in itsourcecode Event Management System 1.0. The impacted element is an unknown function of the file view_event.php. Such manipulation of the argument ID leads to sql in |
| CVE-2026-137415 | 7.3 | n/a | A security flaw has been discovered in Tencent RapidJSON up to 1.1.0. This affects the function Writer::WriteString in the library include/rapidjson/writer.h. Performing a manipulation of the argument |
| CVE-2026-137436 | 7.3 | n/a | A vulnerability was found in SourceCodester Basic Hotel Online Reservation System 1.0. The affected element is an unknown function of the file add_reserve.php. Performing a manipulation of the argumen |
| CVE-2026-137437 | 7.3 | n/a | A vulnerability was determined in SourceCodester Basic Hotel Online Reservation System 1.0. The impacted element is an unknown function of the file add_reserve.php. Executing a manipulation of the arg |
| CVE-2026-137660 | 7.3 | n/a | A vulnerability has been found in stylefeng Guns up to 2.2. Affected by this issue is the function TokenAndPermissionInterceptor.preHandle of the file TokenAndPermissionInterceptor.java of the compone |
| CVE-2026-137677 | 7.3 | n/a | A vulnerability has been found in code-projects Simple Laundry System 1.0. This affects an unknown function of the file viewdetailforuser.php. The manipulation of the argument serviceId leads to sql i |
| CVE-2026-137678 | 7.3 | n/a | A security vulnerability has been detected in code-projects Online Job Portal 1.0. Affected by this issue is some unknown functionality of the file Admin/InsertUser.php. Such manipulation of the argum |
| CVE-2026-137679 | 7.3 | n/a | A vulnerability was detected in code-projects Online Job Portal 1.0. This affects the function GetSQLValueString of the file JobSeeker/SearchJob.php of the component JobSeeker. Performing a manipulati |
| CVE-2026-133845 | 7.3 | n/a | A flaw was found in Flatpak’s flatpak-portal. When a sandboxed application invokes Spawn() and maps two different file descriptors to the same handle, dup2() can fail. Affected Flatpak versions do not |
| CVE-2026-131589 | 7.2 | n/a | The AI Engine – MCP Server & AI Chatbot for WordPress, with Claude, ChatGPT & Gemini plugin for WordPress is vulnerable to Limited Arbitrary File Upload in all versions up to, and including, 3.9.4 via |
| CVE-2026-128111 | 7.2 | n/a | The Drag and Drop Multiple File Upload for Contact Form 7 plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'upload-file' parameter in all versions up to, and including, 1.4.1  |
| CVE-2026-131613 | 7.2 | n/a | The Classified Listing – AI-Powered Business Directory & Classified Ads plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'formData[description]' parameter in all versions up t |
| CVE-2026-131806 | 7.2 | n/a | The CubeWP Forms plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'cwp_custom_form[form_data_id]' parameter in all versions up to, and including, 1.1.13 due to insufficient in |
| CVE-2026-135655 | 7.2 | n/a | The Easy SwipeBox plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via the 'title attribute of <a> inside an approved comment' parameter in all versions up to, and including |
| CVE-2026-136519 | 7.2 | n/a | The Advanced Product Fields (Product Addons) for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'wapf[field_<id>]' parameter in all versions up to, and including |
| CVE-2026-110702 | 7.2 | n/a | The EWWW Image Optimizer plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 8.9.0 due to insufficient input sanitizatio |
| CVE-2026-127113 | 7.2 | n/a | The GeoDirectory – WP Business Directory Plugin and Classified Listings Directory plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'post_content' parameter in all versions up  |
| CVE-2026-128097 | 7.2 | n/a | The Lazy Loader plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'author' parameter in all versions up to, and including, 8.2.0 due to insufficient input sanitization and outp |
| CVE-2026-129329 | 7.2 | n/a | The Ocean Extra plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'post_title' parameter in all versions up to, and including, 2.6.3 due to insufficient input sanitization and  |
| CVE-2026-131838 | 7.2 | n/a | The MoreConvert Wishlist for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'attribute_<custom_variation_name>' parameter in all versions up to, and including, 2 |
| CVE-2026-133409 | 7.2 | n/a | The Parsigate plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'trackId (Zibal). Equivalent unauthenticated fields for other gateways (e.g. ZarinPal 'Authority', Sep 'RefNum') |
| CVE-2026-135630 | 7.2 | n/a | The Premmerce Brands for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'product_brand' parameter in all versions up to, and including, 1.2.16 due to insufficien |
| CVE-2026-135666 | 7.2 | n/a | The JetFormBuilder — Dynamic Blocks Form Builder plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via the 'f_body (mapped to post_content via fields_map)' parameter in all v |
| CVE-2026-135669 | 7.2 | n/a | The Everest Forms – Contact Form, Payment Form, Quiz, Survey & Custom Form Builder with AI plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'everest_forms[form_fields][<wysiwy |
| CVE-2026-136221 | 7.2 | n/a | The Strong Testimonials plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'custom textarea field name (admin-configured, e.g. 'wfx_note')' parameter in all versions up to, and  |
| CVE-2026-136459 | 7.2 | n/a | The Nexter Extension – Security, Performance, Code Snippets & Site Toolkit plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and incl |
| CVE-2026-137284 | 7.2 | n/a | The JetFormBuilder — Dynamic Blocks Form Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the '<form-field-name> mapped via Insert/Update Post fields_map (e.g. payload → m |
| CVE-2026-123827 | 7.2 | n/a | The Easy Social Share Buttons for WordPress plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'position' parameter in all versions up to, and including, 11.6.1 due to insuffici |
| CVE-2026-125001 | 7.2 | n/a | The NextMove Lite – Thank You Page for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'billing_address.email' parameter in all versions up to, and including, 2.2 |
| CVE-2026-130321 | 7.2 | n/a | The PDF Invoices & Packing Slips for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'billing_address.first_name / company / address_1 / address_2 / city' paramet |
| CVE-2026-135654 | 7.2 | n/a | The Lightbox with PhotoSwipe plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 5.18.0 due to insufficient input saniti |
| CVE-2026-135675 | 7.2 | n/a | The RSS Aggregator by Feedzy – Feed to Post, Autoblogging, News & YouTube Video Feeds Aggregator plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in versio |
| CVE-2026-136610 | 7.2 | n/a | The Pixeline’s Email Protector plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 1.5.0 due to insufficient input sanit |
| CVE-2026-137122 | 7.2 | n/a | The PDF Invoices & Packing Slips for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'billing_address.address_1' parameter in all versions up to, and including, 6 |
| CVE-2026-95810 | 7.2 | n/a | The Easy Form Builder by WhiteStudio – Drag & Drop Form Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via esign 'value' Field via Cross-Type 'r_matrix' Poisoning in all ver |
| CVE-2026-119153 | 7.2 | n/a | The Swift Performance Lite plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'REQUEST_URI (gated by $_GET['force-cache'])' parameter in all versions up to, and including, 2.3.7 |
| CVE-2026-119159 | 7.2 | n/a | The Hide My WP Ghost – Security & Firewall plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 7.0.15 due to insufficien |
| CVE-2026-122039 | 7.2 | n/a | The User Registration & Membership – Free & Paid Memberships, Subscriptions, Content Restriction, User Profile, Custom User Registration & Login Builder plugin for WordPress is vulnerable to Stored Cr |
| CVE-2026-124072 | 7.2 | n/a | The User Frontend – Membership, User Registration, User Profile, User Directory & Content Restriction with Frontend Post Submission plugin for WordPress is vulnerable to Stored Cross-Site Scripting vi |
| CVE-2026-126342 | 7.2 | n/a | The WPForms (Contact Form by WPForms / wpforms-lite) plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the Multiple Choice field's 'Other' option value on payment forms in all vers |
| CVE-2026-131803 | 7.2 | n/a | The Mang Board plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'content' parameter in all versions up to, and including, 2.4.9 due to insufficient input sanitization and outp |
| CVE-2026-137500 | 7.2 | n/a | Budibase before 4.0.0 contains a privilege escalation vulnerability that allows non-admin Creator or app-builder users to read pending invite bearer codes via GET /api/global/users/invites. Attackers  |
| CVE-2026-137551 | 7.2 | n/a | Frappe Framework before 15.121.2 and 16.x before 16.36.0 exposes functions imported into module-path-hooked modules as Jinja globals, making them callable from sandboxed templates. Authenticated users |
| CVE-2026-85412 | 7.2 | n/a | The Easy Form Builder by WhiteStudio – Drag & Drop Form Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'address' parameter in all versions up to, and including, 4.2. |
| CVE-2026-85416 | 7.2 | n/a | The Lenix Leads Collector plugin for WordPress is vulnerable to Stored Cross-Site Scripting via Form Field Name in all versions up to, and including, 2.0.0 due to insufficient input sanitization and o |
| CVE-2026-126717 | 7.2 | n/a | The Translate WordPress with Weglot 2.0 – Multilingual AI Translation plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including |
| CVE-2026-137041 | 7.2 | n/a | The E2Pdf – Export Pdf Tool for WordPress plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'your-name (or any CF7 field referenced in the action's error_message/condition)' pa |
| CVE-2026-136995 | 7.2 | n/a | The Upsell Funnel Builder for WooCommerce – Create Upsells, Cross-Sells, Order Bumps, Frequently Bought, and Popups. plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'form_dat |
| CVE-2026-137587 | 7.1 | n/a | LIVE555 Streaming Media before 2026.08.25 contains a heap out-of-bounds read vulnerability in parseVorbisOrTheoraConfigStr() that trusts attacker-supplied 16-bit header length fields. A malicious RTSP |
| CVE-2026-137474 | 7.1 | n/a | SiYuan 3.8.8 before 3.8.10 contains an incorrect permission assignment vulnerability that creates workspace directories with mode 0755 and conf.json with mode 0644, exposing the cleartext AccessAuthCo |
| CVE-2026-137495 | 7.1 | n/a | Budibase before 4.0.0 contains an insecure direct object reference vulnerability in the bulkDestroy function that allows authenticated users to delete rows from any workspace table by supplying foreig |
| CVE-2026-137537 | 7.1 | n/a | ToolJet before 3.21.96-LTS contains a missing authorization vulnerability that allows authenticated End Users to execute data queries of apps in other organizations via POST /api/data-queries/:id/run. |
| CVE-2026-137326 | 7.0 | 0.2% | ICU4C through 79.1 contains a use-after-free and double free vulnerability in the x11-compound-text converter because cloning shares the extraInfo block without a safeClone handler. Attackers who cont |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-h9vc-j5mx-p392 | CVE-2026-80453 | high | Dell Secure Connect Gateway - Virtual Edition, versions prior to 5.36.00.16, contains a Download... |
| GHSA-964x-v85r-chx9 | CVE-2026-80455 | low | Dell Secure Connect Gateway - Virtual Edition, versions prior to 5.36.00.16, contains a Missing... |
| GHSA-586p-29mw-j3rc | CVE-2026-80454 | low | Dell Secure Connect Gateway - Virtual Edition, versions prior to 5.36.00.16, contains a... |
| GHSA-v5jx-gwm7-jwp7 | CVE-2026-80456 | medium | Dell Secure Connect Gateway - Virtual Edition, versions prior to 5.36.00.16, contains an... |
| GHSA-gxwh-w5fm-9f5r | CVE-2026-80450 | high | Dell Secure Connect Gateway - Virtual Edition, versions prior to 5.36.00.16, contains an Improper... |
| GHSA-jm9r-77jf-92cc | CVE-2026-80451 | high | Dell Secure Connect Gateway - Virtual Edition, versions prior to 5.36.00.16, contains a Use of... |
| GHSA-54mx-87w4-wrhp | CVE-2026-80452 | medium | Dell Secure Connect Gateway - Virtual Edition, versions prior to 5.36.00.16, contains an... |
| GHSA-f592-w69g-48x3 | CVE-2026-80449 | low | Dell Secure Connect Gateway - Virtual Edition, versions prior to 5.36.00.16, contains an Improper... |
| GHSA-j8vm-8q8g-xmv9 | CVE-2026-80448 | high | Dell Secure Connect Gateway - Virtual Edition, versions prior to 5.36.00.16, contains a Server... |
| GHSA-297g-v8jv-pxfm | CVE-2026-80268 | high | Dell Secure Connect Gateway - Virtual Edition, versions prior to 5.36.00.16, contains an Exposure... |
| GHSA-m733-36j3-8fph | CVE-2026-80447 | low | Dell Secure Connect Gateway - Virtual Edition, versions prior to 5.36.00.16, contains an Improper... |
| GHSA-5cmj-q485-xwmj | CVE-2026-80248 | medium | Dell Secure Connect Gateway - Virtual Edition, versions prior to 5.36.00.16, contains a Use of... |
| GHSA-cggc-qc52-r3v6 | CVE-2026-80246 | medium | Dell Secure Connect Gateway - Virtual Edition, versions prior to 5.36.00.16, contains a Stack... |
| GHSA-48fg-wjxv-392p | CVE-2026-80245 | medium | Dell Secure Connect Gateway - Virtual Edition, versions prior to 5.36.00.16, contains a Buffer... |
| GHSA-wxq2-ph2w-2x9x | CVE-2026-137609 | medium | In Eclipse Krazo Extensions up to and including 3.0.0, AsciiDocViewEngine passes MVC model values... |
| GHSA-r2pv-754f-6crw | CVE-2026-133940 | high | The access rules of JTL-Shop (export/.htaccess and export/backup/.htaccess) release files with... |
| GHSA-q7cp-fmgm-4ch2 | CVE-2026-80244 | medium | Dell Secure Connect Gateway - Virtual Edition, versions prior to 5.36.00.16, contains an... |
| GHSA-q922-r648-9p2g | CVE-2026-133938 | high | The backend language switch action (quick_change_language) of the JTL-Shop administration backend... |
| GHSA-44r6-j5xx-pc8x | CVE-2026-59103 | critical | MONEO ERP exposes the Ping method of its _slave JSON-RPC service over WebSocket as @rpc... |
| GHSA-7mrv-33v2-9jwf | CVE-2026-133941 | high | The country manager page of the JTL-Shop administration backend (/admin/countries) writes the... |
| GHSA-66rf-h7fw-hfpj | CVE-2026-133939 | high | The OPC (OnPage Composer) start menu, which JTL-Shop shows to logged-in backend users on... |
| GHSA-74jj-wrpr-v5mg | CVE-2026-115841 | medium | A flaw was found in sequoia-openpgp. DSA signature verification does not reject a public key with... |
| GHSA-q2f4-qp4g-jvjh | CVE-2026-132890 | high | In Eclipse Dataspace Components (EDC) Connector 1.0.0-RC2 through 1.0.0-RC7, the HashiCorp Vault... |
| GHSA-rrh7-9jhw-8vpc | CVE-2026-115834 | low | A flaw was found in sequoia-openpgp. Display and Debug formatting of User IDs and notation data... |
| GHSA-7m2r-2gmw-jrmw | CVE-2026-77679 | unknown | A path traversal (ZIP slip) vulnerability exists in Epiphany when installing WebExtension... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| SternKlinik (medi-z Bremen GmbH) | spacebears | DE | 2026-11-27T03:51:24.060440+00:00 |
| Elektro-Ruppen | bravox | CH | 2026-11-27T00:58:27.884689+00:00 |
| Wolters Kluwer | direwolf | NL | 2026-11-27T01:02:46.848958+00:00 |
| Thomas More University | qilin | BE | 2026-11-27T06:44:27.409518+00:00 |
| Monolithic Power Systems (NASDAQ: MPWR, mps.com) | PixelLeaks | US | 2026-11-26T23:32:02.466288+00:00 |
| Keyes Financial Strategies Inc. | PixelLeaks |  | 2026-11-26T23:31:41.412340+00:00 |
| The Law Firm of Kavesh, Minor & Otis, Inc. | PixelLeaks | CA | 2026-11-26T23:31:21.528910+00:00 |
| MHC Financial Inc | PixelLeaks | US | 2026-11-26T23:31:01.814011+00:00 |
| LockeBridge Capital Partners | PixelLeaks |  | 2026-11-26T23:30:41.950479+00:00 |
| babaiai | medusalocker |  | 2026-11-26T22:54:41.961970+00:00 |
| Eversource | Whitearmor | US | 2026-11-26T23:33:19.069527+00:00 |
| FYE | anubis | US | 2026-11-26T21:22:20.018565+00:00 |
| GoDaddy | Inception | US | 2026-11-26T18:22:01.927878+00:00 |
| Paramount | Inception | US | 2026-11-26T15:24:01.436956+00:00 |
| Verisk | Inception | US | 2026-11-26T15:23:41.682543+00:00 |
| McDonald's | Inception | US | 2026-11-26T15:23:21.912426+00:00 |
| Mattel | Inception | US | 2026-11-26T15:23:02.056648+00:00 |
| Exceptional Healthcare Inc. | metaencryptor | US | 2026-11-26T14:47:48.387729+00:00 |
| Groupe Antilles-Glaces | rhysida | GP | 2026-11-26T12:22:01.752479+00:00 |
| Jackson District Library | rhysida | US | 2026-11-26T12:21:17.956958+00:00 |

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
| 64.62.197.137 | 9 |
| 66.132.172.209 | 9 |
| 66.132.186.180 | 9 |
| 93.123.109.181 | 9 |
| 193.47.62.149 | 9 |
| 193.47.62.152 | 9 |
| 3.129.187.38 | 8 |
| 18.218.118.203 | 8 |
| 27.102.116.43 | 8 |
| 35.206.163.19 | 8 |
| 35.210.24.61 | 8 |
| 64.62.197.17 | 8 |
| 64.62.197.152 | 8 |
| 64.62.197.182 | 8 |
| 66.132.172.139 | 8 |
| 66.132.172.201 | 8 |
| 66.132.186.196 | 8 |
| 66.132.195.67 | 8 |
| 66.132.195.100 | 8 |
| 66.132.224.80 | 8 |

### OpenPhish (live phishing URLs)
- https://sso-auth.com/E.twfJHicKjhI?/facebook_secure_account?id=759347502378427672987349826578129038123807394
- http://orego-six.vercel.app/
- http://bets365.tw/e-sport
- https://zd.lc/gk1YA
- http://app.sync-tangem.com/
- https://www.tekonpcket.pro/
- https://web-nickkoutrelakos-eco-178-unblock-permissioned-f27a9b-uniswap.vercel.app/portfolio/pools
- https://umbrecali.pro/
- https://booking.3825.rest/1317092020
- https://ledger-live-login-access.pages.dev/
- https://is.gd/ZXODyf
- https://sp12ct-frensor-biz-zamdik-holvek.pages.dev/send_appeal_request
- https://sp12ct-frensor-biz-zamdik-holvek.pages.dev/appeals/submit-appeal-form/return/
- https://dataserver-kappa.vercel.app/
- https://www.sso.bumbudapurkita.com/ilmu/hotelmanteo.html
- https://sugosh1.github.io/Netflix_Landing-page_Clone/
- https://f1700qgk-4321.brs.devtunnels.ms/index.html?nombreUsuario=NBMIN
- https://netflis-gpt.netlify.app/
- https://metamask173.blogspot.com/2026/11/?m=1
- https://gerentexgerenciador.online/sala_espera.php?id=b2eed445c7e06da4

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://www.brt-kz.eu.cc/it/ |
| N/A | https://primeproduct.club/accueil |
| N/A | https://www.brt-rz.eu.cc/it/ |
| N/A | https://www.brt-pz.eu.cc/it/ |
| N/A | https://kontabontang1794263724204.0480074.misitiohostgator.com/clinet5a/home/fi-phone.php |
| N/A | https://www.brt-lz.eu.cc/it/ |
| N/A | https://primeproduct.club/ |
| N/A | https://vn-aw88.com/ |
| N/A | https://prime-assistance.com/?campaign=qxz8548 |
| N/A | https://o88-vi.com/ |
| N/A | https://kerino.vip/p/virusbuster |
| N/A | https://bd-sbj66.com/ |
| N/A | https://prime-assistance.com/?campaign=rdr874 |
| 8.2 | https://maillogin-optusnet-com-au.weebly.com/ |
| 7.5 | https://allegrolokalnie.pl-7131228.my/ |
| 7.3 | https://allegro.7846325.lat/ |
| 7.3 | https://allegro.9874235.lat/ |
| 9.3 | https://portal.stp-mex.com/spei/login/code |
| 8.3 | https://oceanicredit.lorealparis.qzz.io/ |
| 7.3 | https://shaywuc.wiki/ |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| ca762af05d70b15789214db60a0f775de37c7b29 | Malware C&C |
| e3f4ba4c9edce49b6cd05a517115f1c555f35d81 | Vidar C&C |
| fc106a1b721f1e8f48d8992745a69506ffbfb0f7 | Vidar C&C |
| 9ca8233118bf720ea5c2e141f0dde31c4cc9c818 | PureLogsStealer C&C |
| 3ec4de7981b35b599489e6131411bfab779a3993 | Vidar C&C |
| 5531f1af029fc7cccf27c690b6e38a11689308e6 | Vidar C&C |
| 07afce465ef29e5bd8b2bf1c86e81cfe37424878 | PureLogsStealer C&C |
| 040ebeff29b5e3f41e6013e783035be7666fcc53 | WeedStealer C&C |
| 9112f43d7b63c2165e9d4f5e0a4b0fbeb2655e23 | PureLogsStealer C&C |
| 7b9d238f14baeab95bdaf3180491bfe280ce44f3 | OffLoader C&C |
| 2e1c386f86155aa8886428c40f01681c692f286f | FunStealer C&C |
| 900cfd996ea2d66b333f8a2408cb4071b2239ff7 | FunStealer C&C |
| 0f2c70bc8079380e50364e46bbe8458606091fe3 | Malware distribution |
| d7d6b0e7c29950bee702ea2b0f253d6d4a232bd8 | PureLogsStealer C&C |
| 8ba9366306a3c0801ab5b7a4a52d9a19293cc867 | Vidar C&C |
| 0946c008154ff2809eca3d8c9e28e0ec0b8bacac | SeroRAT C&C |
| 5848fc12988a902dc95fd31897fc72884d332a47 | WeedStealer C&C |
| 85aa46f55739ebba1c0ad050262fdab387ab3db3 | Vidar C&C |
| 853c7cbd33c41f2a4651942d34a733403c89910b | FunStealer C&C |
| cfaeecab0d464737b0c8132f0302b4a2b5bbd149 | FunStealer C&C |

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
- 1.10.222.204
- 1.12.252.163
- 1.13.169.147
- 1.13.79.149
- 1.141.32.230
- 1.162.242.67
- 1.183.25.86
- 1.192.216.175
- 1.201.146.109
- 1.212.225.99
- 1.214.204.138
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.222.80.212
- 1.226.84.248
- 1.234.21.73
- 1.234.5.148
- 1.234.53.65

### CINS Army (poorly-rated IPs)
- 1.13.17.224
- 1.14.110.192
- 1.168.206.193
- 1.170.243.169
- 1.189.41.213
- 1.192.129.106
- 1.193.63.156
- 1.193.63.196
- 1.193.63.245
- 1.20.187.22
- 1.204.35.156
- 1.208.108.242
- 1.24.16.103
- 1.24.16.104
- 1.24.16.105
- 1.24.16.112
- 1.24.16.119
- 1.24.16.120
- 1.24.16.121
- 1.24.16.13

## News (last ~36h, across outlets)
### The Hacker News
- [How to Keep Your Security Picture Current When Attackers Move at AI Speed](https://thehackernews.com/2026/11/how-to-keep-your-security-picture.html)
- [Hackers Trojanize Official Q-Dir and DesktopOK Downloads to Deliver Remote Access Malware](https://thehackernews.com/2026/11/hackers-trojanize-official-q-dir-and.html)
- [Switzerland Confirms AI-Assisted Cyberattacks Breached Critical Infrastructure Operators](https://thehackernews.com/2026/11/switzerland-confirms-ai-assisted.html)
- [Unpatched Cacti Zero-Day Enables RCE in Just Four HTTP Requests via Guest Access](https://thehackernews.com/2026/11/unpatched-cacti-zero-day-enables-rce-in.html)
- [ThreatsDay: 10M NGINX Services at Risk, 250+ Malicious Extensions, AI Server Hijacking + 17 More Stories](https://thehackernews.com/2026/11/threatsday-250-rogue-extensions-10m.html)
- [North Korea-Linked PolinRider Poisons Over 7,600 GitHub Repositories to Spread Malware](https://thehackernews.com/2026/11/north-korea-linked-polinrider-poisons.html)
- [Most Wanted: The Phishing Kits and Techniques Getting Past Security Controls](https://thehackernews.com/2026/11/most-wanted-phishing-kits-and.html)
- [1Password Hacked, Customer Data and Source Code Stolen in GitHub Account Breach](https://thehackernews.com/2026/11/1password-hacked-customer-data-and.html)
- [Drupal Warns of New Highly Critical Site Takeover Vulnerability Under Active Exploitation](https://thehackernews.com/2026/11/drupal-warns-of-new-highly-critical.html)
- [Hackers Exploit 10 Vulnerabilities Across Mitel, Juniper, Vates, and Danfoss Products](https://thehackernews.com/2026/11/hackers-exploit-10-vulnerabilities.html)
- [13 Malicious NuGet Packages Turn Fake .NET Job Assessments Into Malware Delivery Traps](https://thehackernews.com/2026/11/13-malicious-nuget-packages-turn-fake.html)

### BleepingComputer
- [Microsoft removes WSUS server role in Windows Server 2028](https://www.bleepingcomputer.com/news/microsoft/microsoft-removes-wsus-server-role-in-windows-server-2028/)
- [Drupal warns of new site takeover flaw exploited in attacks](https://www.bleepingcomputer.com/news/security/drupal-warns-of-new-access-bypass-flaw-exploited-in-attacks/)
- [SAP confirms security incident after suspicious GitHub activity](https://www.bleepingcomputer.com/news/security/sap-confirms-security-incident-after-suspicious-github-activity/)
- [Microsoft pushes emergency hotpatch to fix Windows Server crashes](https://www.bleepingcomputer.com/news/microsoft/new-out-of-band-oob-emergency-hotpatch-fixes-windows-server-2025-crashes/)
- [New NFS2ROOT Linux flaw can let attackers gain root privileges](https://www.bleepingcomputer.com/news/security/new-nfs2root-linux-flaw-can-let-attackers-gain-root-privileges/)
- [OpenAI warns GPT-6.2 Astra will hit usage limits 40% faster because it fixed a bug](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-warns-gpt-62-astra-will-hit-usage-limits-40-percent-faster-because-it-fixed-a-bug/)
- [NordVPN Black Friday Deal: Get 78% off VPN plans in 2026](https://www.bleepingcomputer.com/news/security/nordvpn-black-friday-deal-get-78-percent-off-vpn-plans-in-2026/)
- [Fake paid expert interviews impersonate brands to steal Google logins](https://www.bleepingcomputer.com/news/apple/fake-paid-expert-interviews-impersonate-brands-to-steal-google-logins/)
- [Remus malware steals Gmail messages via fake Google Sheets extension](https://www.bleepingcomputer.com/news/security/remus-malware-steals-gmail-messages-via-fake-google-sheets-extension/)
- [SYS010 malware abuses browser management to spy on Gmail, Outlook](https://www.bleepingcomputer.com/news/security/sys010-malware-abuses-browser-management-to-spy-on-gmail-outlook/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [Cyprus Becomes Espionage Target for Iranian Hackers](https://www.darkreading.com/cyberattacks-data-breaches/cyprus-espionage-target-iranian-hackers)

### SecurityWeek
- [In Other News: Tanker Cyberattacks, EU Quantum Act, New VirusTotal Capabilities](https://www.securityweek.com/in-other-news-tanker-cyberattacks-eu-quantum-act-new-virustotal-capabilities/)
- [100,000 Potentially Impacted by Colorado Data Breach](https://www.securityweek.com/100000-potentially-impacted-by-colorado-data-breach/)
- [Hex Package Manager Warns of Potential Data Breach](https://www.securityweek.com/hex-package-manager-warns-of-potential-data-breach/)
- [SAP Confirms Cyberattack, Source Code Reportedly Compromised](https://www.securityweek.com/sap-confirms-cyberattack-source-code-reportedly-compromised/)
- [FIFA Says It Has Been Victim of a Cyberattack Accessing ‘Personal and Business Information’](https://www.securityweek.com/fifa-says-it-has-been-victim-of-a-cyberattack-accessing-personal-and-business-information/)
- [Critical Juniper Session Smart Conductor Flaw Exploited in Attacks](https://www.securityweek.com/critical-juniper-session-smart-conductor-flaw-exploited-in-attacks/)
- [Mitel MiCollab Zero-Days Exploited in Suspected AI-Assisted Attacks](https://www.securityweek.com/mitel-micollab-zero-days-exploited-in-suspected-ai-assisted-attacks/)
- [Drupal Installer Patch Left a Gap Attackers Are Already Exploiting](https://www.securityweek.com/drupal-installer-patch-left-a-gap-attackers-are-already-exploiting/)
- [1Password Breach Exposes Customer Data, Internal Source Code](https://www.securityweek.com/1password-breach-exposes-customer-data-internal-source-code/)

### The Record
- [British government takes services offline following ‘cyber incident’](https://therecord.media/uk-department-work-pensions-cyber-incident)
- [UK’s long-awaited National Cyber Action Plan delayed until December](https://therecord.media/britain-delays-national-cyber-action-plan-again)

### Infosecurity Magazine
- [UK Welfare and Pension Services Taken Offline Following Cyber Incident](https://www.infosecurity-magazine.com/news/uk-welfare-services-offline/)
- [FIFA Confirms Cyber-Attack, Personal and Business Information Compromised](https://www.infosecurity-magazine.com/news/fifa-confirms-cyberattack/)
- [CyberStrikeAI Creator Shuts Down Open-Source AI Offensive Framework](https://www.infosecurity-magazine.com/news/cyberstrikeai-shut-down-threatbook/)
- [CISA Issues Alert After Danfoss Reveals Critical Flaw in Fridge Controllers](https://www.infosecurity-magazine.com/news/cisa-alert-danfoss-critical-flaw/)
- [Google Cloud Requires AI Agents to Access Workspace Through Approved Methods](https://www.infosecurity-magazine.com/news/google-cloud-ai-agents-workspace/)
- [Phishers Abuse Hugging Face's AI Site Builder to Spoof Big Brands](https://www.infosecurity-magazine.com/news/hugging-face-ai-builder-phishing/)
- [Chinese, North Korean Hackers Adopt ARTEX AI Offensive Framework](https://www.infosecurity-magazine.com/news/chinese-north-korea-artex/)
- [Home Office Reprimanded After GDPR Failure at the Border](https://www.infosecurity-magazine.com/news/home-office-reprimanded-gdpr/)
- [1Password Hit by Backend Breach via Hijacked Employee GitHub Account](https://www.infosecurity-magazine.com/news/1password-github-account-backend/)

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
_No new items / feed unavailable this run._

### Securelist (Kaspersky)
_No new items / feed unavailable this run._

### CrowdStrike Blog
- [CrowdStrike Accelerates the Shift to the Agentic SOC](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-gartner-mq-isoc/)
- [Securing Employees&rsquo; AI Use Requires a Unified Architecture](https://www.crowdstrike.com/en-us/blog/securing-employees-ai-use-requires-unified-architecture/)
- [Reprioritizing Automated Leads with CrowdStrike Signal](https://www.crowdstrike.com/en-us/blog/reprioritizing-automated-leads-crowdstrike-signal/)
- [Java4Shell (CVE-2026-114938): CrowdStrike Detects Exposure and Post-Exploitation Activity](https://www.crowdstrike.com/en-us/blog/crowdstrike-helps-protect-against-java4shell-cve-2026-114938/)
- [NGINX2Root: Identify and Protect with the CrowdStrike Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-helps-protect-against-nginx2root-cve-2026-123007/)
- [CrowdStrike Is Building the Engine of the Agentic SOC with Falcon Next-Gen SIEM](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-gartner-mq-siem/)
- [CrowdStrike Brings the Human Advantage to AI Detection and Response](https://www.crowdstrike.com/en-us/blog/crowdstrike-brings-human-advantage-aidr/)
- [Hidden in the Weights: Supply Chain Risk from Backdoored LoRA Models](https://www.crowdstrike.com/en-us/blog/supply-chain-risk-from-backdoored-lora-models/)
- [Inside Falcon AI Gateway: One Control Point for AI Traffic](https://www.crowdstrike.com/en-us/blog/falcon-ai-gateway-one-control-point-for-ai-traffic/)
- [CrowdStrike Named a Leader in the 2026 IDC MarketScape for Worldwide Augmented Identity Security Solutions](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-idc-marketscape-worldwide-augmented-identity-security-solutions/)

### FortiGuard Threat Signal
- [BerriAI LiteLLM Guardrail Sandbox Escape RCE](https://fortiguard.fortinet.com/threat-signal-report/6686)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal