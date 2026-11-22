# Winjit Daily TI Digest — 2026-11-22

_Auto-generated. Window: last ~24h. Fetched at 2026-11-22T10:56:26.432163+00:00Z_

**At a glance:** 0 new KEV · 103 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-133993 | 10.0 | n/a | A security flaw has been discovered in D-Link DIR-600L 2.17b02. This affects the function FUN_0040efb0 of the file gena.cgi of the component GENA Subscription Handler. Performing a manipulation of the |
| CVE-2026-120539 | 9.8 | 2.2% | The Restrictions for BuddyPress plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 1.5.4 This is due to the plugin splicing the attacker-controlled reque |
| CVE-2026-134292 | 9.8 | n/a | SurrealDB 1.0.0 before 4.0.0 contains a capability check bypass in its embedded JavaScript scripting engine, where the surrealdb.functions bridge calls the internal fnc::synchronous() and fnc::asynchr |
| CVE-2026-125294 | 9.8 | n/a | The Nexter Blocks Pro plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 5.0.10 via the `tpgb_ajax_register_user()` function. This is due to a byte-level  |
| CVE-2026-19793 | 8.8 | 0.8% | The WP Import Export Lite plugin for WordPress is vulnerable to Limited Code Injection in all versions up to, and including, 3.9.32 via the 'comment' parameter. This is due to a two-stage shortcode ch |
| CVE-2026-129220 | 8.8 | 0.6% | The Everest Forms – Contact Form, Payment Form, Quiz, Survey & Custom Form Builder with AI plugin for WordPress is vulnerable to Missing Authorization in all versions up to, and including, 3.6.4 This  |
| CVE-2026-133985 | 8.8 | n/a | A flaw has been found in TRENDnet TEW-657BRM 1.00.1. Affected by this issue is some unknown functionality of the file /usr/sbin/restore_config.cgi. Executing a manipulation can lead to out-of-bounds r |
| CVE-2026-134253 | 8.8 | n/a | Grav API plugin from 1.0.0 before 1.1.4 contains a remote code execution vulnerability that allows publishers with media and page write rights to write theme template files through the blueprint-uploa |
| CVE-2026-134295 | 8.8 | n/a | SurrealDB 3.0.0 before 4.0.0 contains a path traversal vulnerability in direct filesystem buckets because BucketController::check_permission evaluates key-based ACLs against the un-normalized object k |
| CVE-2026-134309 | 8.8 | n/a | SurrealDB 1.0.0 before 4.0.0 contains an authorization bypass vulnerability that allows authenticated users to shadow protected $access, $auth, and $token variables by binding them as FOR loop variabl |
| CVE-2026-134337 | 8.8 | n/a | ArcadeDB native-image server builds 26.8.1 before 26.11.1 contain an authorization bypass vulnerability that allows authenticated clients to perform writes through read-only query paths by nesting sta |
| CVE-2026-134338 | 8.8 | n/a | ArcadeDB 25.8.1 before 26.11.1 contains an incorrect authorization vulnerability because per-type ACLs are keyed by type name, renames are not propagated to the permission configuration, and requestAc |
| CVE-2026-134339 | 8.8 | n/a | ArcadeDB from 26.11.1-SNAPSHOT before 26.11.1 contains an authorization bypass vulnerability that allows authenticated users to skip per-type ACL checks when a database is opened on demand. Attackers  |
| CVE-2026-134359 | 8.8 | n/a | AzuraCast before 0.24.1 fails to escape backslashes in Liquidsoap annotation values, allowing media managers to break out of quoted annotation strings. Attackers can set a crafted ID3 title ending in  |
| CVE-2026-134452 | 8.8 | n/a | Dockhand before 1.0.57 merges stack secret environment variables into the environment used to spawn docker compose during stack deploys without filtering reserved keys such as PATH. An authenticated a |
| CVE-2026-134258 | 8.7 | n/a | Admidio 5.0.0 before 5.0.18 contains a path traversal vulnerability in the Documents & Files renameFile() action that allows authenticated users with folder upload rights to move files outside adm_my_ |
| CVE-2026-134389 | 8.5 | n/a | Frappe ERPNext 6.18.0 before 15.124.0 and 16.x before 16.52.0 contains a missing authorization vulnerability in Payment Requests that lets authenticated Accounts User role holders read source document |
| CVE-2026-134429 | 8.5 | n/a | Frappe ERPNext before 15.121.4 and 16.x before 16.36.0 contains a missing authorization vulnerability in a CRM and Support module endpoint that returns Communications of documents without checking whe |
| CVE-2026-134433 | 8.5 | n/a | Frappe ERPNext before 15.124.2 and 16.x before 16.53.0 fails to enforce record-level authorization in several endpoints, reports and forms, allowing authenticated low-privilege users to access data be |
| CVE-2026-134293 | 8.2 | n/a | SurrealDB 3.1.0 before 4.0.0 contains an SQL injection vulnerability in its Model Context Protocol (MCP) server because the identifier validator (consume_backtick_ident and validate_identifier) treats |
| CVE-2026-123086 | 8.1 | 0.6% | The PublishPress Revisions: Duplicate Posts, Submit, Approve and Schedule Content Changes plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 4.3.4 This is |
| CVE-2026-118049 | 8.1 | 1.0% | The Tutor LMS – eLearning and online course solution plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 4.2.0 This is due to the plugin not properly verif |
| CVE-2026-134262 | 8.1 | n/a | Admidio 5.0.0 before 5.0.18 contains a stored cross-site scripting vulnerability that allows role administrators to inject JavaScript by placing quote-breaking payloads in role names rendered unencode |
| CVE-2026-134282 | 8.1 | n/a | Vikunja from 0.14.0 before 2.8.0 contains a mass assignment vulnerability that allows authenticated users to set json-hidden fields by sending XML request bodies to the v1 API. Attackers can set Backg |
| CVE-2026-134300 | 8.1 | n/a | SurrealDB from 2.2.0 before 4.0.0 contains an authorization bypass vulnerability in Document::purge_references that lets authenticated users bypass target table PERMISSIONS by triggering REFERENCE ON  |
| CVE-2026-134316 | 8.1 | n/a | @better-auth/electron 1.5.0-beta.12 before 1.7.16 and 1.8.0-beta.0 before 1.8.0-beta.5 accepts any validly signed value as its transfer cookie and returns the full endpoint context, including the auth |
| CVE-2026-134322 | 8.1 | n/a | better-auth 0.4.12-beta.7 before 1.7.16 and 1.8.0-beta.0 before 1.8.0-beta.5 contains an improper authentication vulnerability in the phone number plugin that lets sign-up and other flows save unverif |
| CVE-2026-134352 | 8.1 | n/a | Rclone from 1.51.0 before 1.76.0 contains an authentication bypass vulnerability in serve sftp --auth-proxy because the generateCacheKey cache key omits the authentication method. Attackers knowing a  |
| CVE-2026-134448 | 8.1 | n/a | Finsys Dockhand 1.0.7 before 1.0.57 contains a path traversal vulnerability that allows low-privileged users to read and write arbitrary files by setting an unvalidated envPath on a stack source. Atta |
| CVE-2026-134451 | 8.1 | n/a | Dockhand before 1.0.57 contains a privilege escalation vulnerability that allows non-admin users with settings:edit permission to modify OIDC provider configuration due to an improper permission check |
| CVE-2026-134654 | 8.1 | n/a | Mailflare before 48957fb contains a host header injection vulnerability in the password-reset request handler that allows unauthenticated attackers to poison reset links when APP_URL is unset. Attacke |
| CVE-2026-134250 | 8.0 | n/a | Grav Form plugin 1.1.0 before 9.1.40 contains a stored cross-site scripting vulnerability in Form::uploadFiles(), which sanitizes SVG only when a file's last extension is .svg and accepts markup under |
| CVE-2026-134303 | 7.9 | n/a | SurrealKV before 1.1.0 contains an out-of-bounds read vulnerability in the safe InternalKeyRef::from_encoded constructor, which only checks key length with a debug-only assertion. Callers passing keys |
| CVE-2026-134694 | 7.8 | n/a | Gammapy through 2.1 contains a code injection vulnerability in WcsGeom.from_header() that passes the WCSSHAPE FITS header card to eval(). Attackers can supply a crafted .fits file with a Python expres |
| CVE-2026-134704 | 7.8 | n/a | OpenShot Video Editor (openshot-qt) through 4.1.1 contains an unsafe deserialization vulnerability in ProjectDataStore.load() and read_legacy_project_file() that passes non-JSON project files to pickl |
| CVE-2026-134248 | 7.7 | n/a | SiYuan 3.6.0 before 3.8.10 contains an information disclosure vulnerability that allows authenticated Readers to read protected documents through block-reference footnote resolution in Markdown export |
| CVE-2026-134287 | 7.7 | n/a | OpenRemote core before 1.34.0 contains an authentication bypass vulnerability in UserAssetProvisioningMQTTHandler that allows unauthenticated attackers to impersonate provisioned devices without proof |
| CVE-2026-134370 | 7.7 | n/a | Frappe Framework before 15.120.1 and 16.x before 16.33.1 contains a path traversal vulnerability in file attachment handling that permits arbitrary file read. Authenticated attackers holding a single  |
| CVE-2026-134372 | 7.7 | n/a | Frappe ERPNext 4.3.0 before 15.121.6 and 16.x before 16.37.0 contains an SQL injection vulnerability in an endpoint of the Selling and Buying modules, where a request value validated early can be over |
| CVE-2026-134393 | 7.7 | n/a | Frappe ERPNext 10.1.41 before 15.122.0 and 16.x before 16.50.0 contains a missing authorization vulnerability in a Manufacturing module endpoint that replaces BOMs without checking whether the caller  |
| CVE-2026-134399 | 7.7 | n/a | Frappe ERPNext 8.11.1 before 15.124.0 and 16.x before 16.52.0 is missing an authorization check in print and portal views, which fail to apply desk users' User Permissions to customer documents. Authe |
| CVE-2026-134404 | 7.7 | n/a | Frappe ERPNext 6.3.0 before 15.124.0 and 16.x before 16.52.0 contains a missing authorization vulnerability in the customer and supplier portal list endpoint, which returns complete selling documents  |
| CVE-2026-134411 | 7.7 | n/a | Frappe ERPNext 11.1.7 before 15.121.4 and 16.x before 16.36.0 contains a missing authorization vulnerability in a Regional module endpoint that returns private e-invoice files after checking only docu |
| CVE-2026-134417 | 7.7 | n/a | Frappe ERPNext 13.0.0 before 15.121.4 and 16.x before 16.36.0 contains a missing authorization vulnerability in an Accounts module endpoint that returns uploaded bank statement file content without ch |
| CVE-2026-134418 | 7.7 | n/a | Frappe ERPNext 4.0.0 before 15.122.0 and 16.x before 16.50.0 contains a missing authorization vulnerability in an Accounts module endpoint that returns the taxes and charges of documents without check |
| CVE-2026-134428 | 7.7 | n/a | Frappe ERPNext 13.0.0 before 15.121.4 and 16.x before 16.36.0 contains a missing authorization vulnerability in a Stock module endpoint that returns Item master records without checking whether the ca |
| CVE-2026-134434 | 7.7 | n/a | Frappe ERPNext 16.0.0 before 16.36.0 contains a missing authorization vulnerability in a Manufacturing module endpoint that allows authenticated users to cancel Stock Reservation Entries without recor |
| CVE-2026-134435 | 7.7 | n/a | Frappe ERPNext before 15.124.2 and 16.x before 16.50.0 contains a missing authorization vulnerability in an Accounts module endpoint that records bank clearance dates, which checks only a broad role p |
| CVE-2026-134436 | 7.7 | n/a | Frappe ERPNext 15.8.0 before 15.121.4 and 16.x before 16.36.0 contains a missing authorization vulnerability in an endpoint shared across modules that returns transaction child table rows without chec |
| CVE-2026-107654 | 7.5 | n/a | The One to one user Chat by WPGuppy plugin for WordPress is vulnerable to generic SQL Injection via the 'userId' parameter in all versions up to, and including, 1.1.6 due to insufficient escaping on t |
| CVE-2026-134245 | 7.5 | n/a | SiYuan 3.8.0 before 3.8.10 contains an incorrect authorization vulnerability in the serveAssets route that allows unauthenticated attackers to read password-protected document assets via name collisio |
| CVE-2026-134246 | 7.5 | n/a | SiYuan 3.6.0 before 3.6.2 and 3.7.3 before 3.8.10 contains a missing authorization vulnerability in the /api/block/getDOMText endpoint, which renders caller-supplied DOM without checking publish acces |
| CVE-2026-134247 | 7.5 | n/a | SiYuan 3.8.0 before 3.8.10 contains an incorrect authorization vulnerability that allows anonymous attackers to read indexed asset text referenced only by publish-disabled attribute-view rows. Attacke |
| CVE-2026-134249 | 7.5 | n/a | SiYuan before 3.8.10 contains an authentication bypass vulnerability that allows unauthenticated attackers to gain Administrator role by spoofing X-Forwarded-For through a loopback-trusted reverse pro |
| CVE-2026-134284 | 7.5 | n/a | Vikunja from 1.0.0 before 2.8.0 contains an account takeover vulnerability that allows attackers to hijack SSO identities by planting local accounts with unverified victim emails. When emailfallback i |
| CVE-2026-134291 | 7.5 | n/a | SurrealDB 3.0.0 before 4.0.0 contains a path traversal vulnerability in its filesystem storage bucket that only canonicalizes the bucket root, not descendant symlinks. Attackers can reference paths th |
| CVE-2026-134294 | 7.5 | n/a | SurrealDB 3.0.0 before 4.0.0 contains a path traversal vulnerability in its bucket storage layer on Windows, where ObjectKey::check_no_traversal splits object keys only on forward slashes while FileSt |
| CVE-2026-134299 | 7.5 | n/a | SurrealDB 3.0.4 before 4.0.0 does not apply operator-configured WebSocket frame, message, and buffer size limits to the GraphQL WebSocket upgrade handler at GET /graphql, falling back to permissive li |
| CVE-2026-134325 | 7.5 | n/a | ArcadeDB before 26.11.1 contains a denial of service vulnerability in the Redis protocol handler, which neither replies to nor closes a pre-authentication connection when it receives an array whose fi |
| CVE-2026-134341 | 7.5 | n/a | actix-http 3.0.0 before 3.20.3 contains a denial of service vulnerability that allows unauthenticated remote attackers to exhaust memory by sending large-window brotli request bodies. Attackers can se |
| CVE-2026-134347 | 7.5 | n/a | actix-files before 0.7.4 contains an information disclosure vulnerability that allows remote unauthenticated attackers to read hidden files by requesting Windows 8.3 short-name aliases. Attackers can  |
| CVE-2026-134364 | 7.5 | n/a | pypdf 3.7.1 before 7.0.0 contains an information disclosure vulnerability that allows attackers to guess placeholders in encrypted templated documents by analyzing file identifiers. Attackers with a d |
| CVE-2026-134366 | 7.5 | n/a | pypdf before 7.0.0 contains a resource exhaustion vulnerability that allows attackers to cause large memory usage by supplying crafted PDF cross-reference streams. Attackers can craft a PDF whose cros |
| CVE-2026-134367 | 7.5 | n/a | pypdf 2.4.2 before 7.0.0 contains a resource exhaustion vulnerability in its handling of XFA forms that allows attackers to cause excessive memory consumption. Attackers can supply a crafted PDF conta |
| CVE-2026-134456 | 7.5 | n/a | Hysteria 2.5.0 before 2.9.2 contains a denial of service vulnerability in the HTTP sniff implementation that fails to limit header size. Attackers can continuously send excessively large HTTP headers  |
| CVE-2026-134461 | 7.5 | n/a | Web-Token jwt-framework and jwt-library before 3.4.10, 4.0.0 before 4.0.7, and 4.1.0 before 4.1.7 contain an uncontrolled resource consumption vulnerability in PBES2AESKW::unwrapKey(), which passes th |
| CVE-2026-134679 | 7.5 | n/a | WeddingShare through 1.8.2 contains a missing authorization vulnerability in the anonymous MediaViewerController.GalleryItem action that allows unauthenticated attackers to retrieve item upload paths  |
| CVE-2026-119114 | 7.4 | 1.0% | The WP Fastest Cache – WordPress Cache Plugin plugin for WordPress is vulnerable to arbitrary directory deletion due to insufficient file path validation in the singleDeleteCache function in all versi |
| CVE-2026-134454 | 7.4 | n/a | Hysteria from 2.0.0 before 2.9.2 contains an ACL bypass vulnerability that allows authenticated clients to reach blocked UDP destinations by reusing an established UDP session. Attackers can open a se |
| CVE-2026-133983 | 7.3 | n/a | A vulnerability was detected in eigent-ai eigent up to 1.0.2. Affected by this vulnerability is an unknown functionality of the file backend/app/controller/chat_controller.py of the component Local Ag |
| CVE-2026-134541 | 7.3 | n/a | A vulnerability was detected in Surya2Developer Online Shopping System 1.0. This impacts an unknown function of the file product.php of the component GET Parameter Handler. Performing a manipulation o |
| CVE-2026-134623 | 7.3 | n/a | A flaw has been found in Microweber up to 2.0.20. This impacts the function UserManager::make_logged of the file src/MicroweberPackages/App/Http/Controllers/ApiController.php of the component Generic  |
| CVE-2026-107713 | 7.2 | 0.5% | The Flutterwave Payments plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'form_id' parameter in all versions up to, and including, 1.0.7 due to insufficient input sanitizatio |
| CVE-2026-116619 | 7.2 | 0.5% | The MetForm – Contact Form, Survey, Quiz, Conditional Forms, Form Templates & Custom Form Builder for Elementor plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'mf-te (the fo |
| CVE-2026-119632 | 7.2 | 0.4% | The Forminator Forms – Contact Form, Payment Form & Custom Form Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'textarea-N (rich-text draft value, saved as Save-and- |
| CVE-2026-120485 | 7.2 | 0.4% | The Admin Columns plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'url' parameter in all versions up to, and including, 7.1.8 due to insufficient input sanitization and outpu |
| CVE-2026-120529 | 7.2 | 0.5% | The Admin Columns plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'HTTP_USER_AGENT' parameter in all versions up to, and including, 7.1.7 due to insufficient input sanitizati |
| CVE-2026-120676 | 7.2 | 0.4% | The Forminator Forms – Contact Form, Payment Form & Custom Form Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'upload-1 (the File Upload field's element_id)' parame |
| CVE-2026-125039 | 7.2 | 0.4% | The EZ SQL Reports Shortcode Widget and DB Backup plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'User-Agent header (stored to comment_agent)' parameter in all versions up t |
| CVE-2026-126011 | 7.2 | 0.4% | The Photo Gallery, Sliders, Proofing and Themes – NextGEN Gallery plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 4. |
| CVE-2026-131822 | 7.2 | 0.5% | The Contact Form to Any API plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'your-message (any CF7 form field)' parameter in all versions up to, and including, 3.0.7 due to i |
| CVE-2026-132620 | 7.2 | 0.4% | The WPBot – AI ChatBot for WordPress & Growth Suite: SEO, AI Writer, Email Marketing, Social Media plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'text' parameter in all ver |
| CVE-2026-133361 | 7.2 | 0.5% | The BlockStrap Page Builder – Bootstrap Blocks plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 0.1.65 due to insuffi |
| CVE-2026-96991 | 7.2 | 0.4% | The SchemaEngine AI – AI Schema Markup, Reviews & Rich Snippets for SEO plugin for WordPress is vulnerable to Stored Cross-Site Scripting via Comment Content via WebPage JSON-LD Description in all ver |
| CVE-2026-125054 | 7.2 | 0.4% | The SiteOrigin CSS plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via the 'class' parameter in all versions up to, and including, 1.6.9 due to insufficient input sanitizat |
| CVE-2026-107632 | 7.2 | 0.7% | The Unbounce Landing Pages plugin for WordPress is vulnerable to Stored Cross-Site Scripting in versions up to, and including, 1.1.6. This is due to insufficient input sanitization and output escaping |
| CVE-2026-118061 | 7.2 | 0.4% | The VikBooking Hotel Booking Engine & PMS plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'inquiry (array keys)' parameter in all versions up to, and including, 1.8.20 due to |
| CVE-2026-119061 | 7.2 | 0.7% | The VikBooking Hotel Booking Engine & PMS plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'vbf<field_id>' parameter in all versions up to, and including, 1.8.20 due to insuff |
| CVE-2026-120526 | 7.2 | 0.5% | The WCFM Membership – WooCommerce Memberships for Multivendor Marketplace plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'wcfm_membership_registration_form[store_name]' para |
| CVE-2026-122230 | 7.2 | 0.4% | The Thim Kit for Elementor – Pre-built Templates & Widgets for Elementor plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via the 'comment' parameter in all versions up to,  |
| CVE-2026-131609 | 7.2 | 0.5% | The Germanized for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'billing_address.first_name (Store API checkout) → stored on parent order; withdrawal get_first |
| CVE-2026-133367 | 7.2 | 0.8% | The WPC Frequently Bought Together for WooCommerce plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'variation' parameter in all versions up to, and including, 8.0.2 due to in |
| CVE-2026-116518 | 7.2 | n/a | The ElasticPress plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'orderby' parameter in all versions up to, and including, 5.3.5 due to insufficient input sanitization and ou |
| CVE-2026-120736 | 7.2 | n/a | The AutomatorWP – No-Code Workflow Automation, Integration & Webhooks Plugin, now with AI plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'your-message (any CF7 form field us |
| CVE-2026-120745 | 7.2 | n/a | The Paid Membership Plugin, Ecommerce, User Registration Form, Login Form, User Profile & Restrict Content – ProfilePress plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'reg |
| CVE-2026-123830 | 7.2 | n/a | The wpForo Forum plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'data[display_name]' parameter in all versions up to, and including, 3.2.4 due to insufficient input sanitiza |
| CVE-2026-124216 | 7.2 | n/a | The Orphans plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 3.4.5 due to insufficient input sanitization and output  |
| CVE-2026-124976 | 7.2 | n/a | The Swift Performance Lite plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the '<attacker-chosen parameter name>' parameter in all versions up to, and including, 2.3.7.5 due to i |
| CVE-2026-130323 | 7.2 | n/a | The Accept Stripe Payments plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via the 'href of any <a> element containing 'asp_action=show_pp&product_id='' parameter in all ve |
| CVE-2026-134254 | 7.1 | n/a | Admidio from 5.0.0 before 5.0.18 contains a path traversal vulnerability in DocumentsService::renameFile() that allows authenticated users to move files outside adm_my_files by supplying an unvalidate |
| CVE-2026-134268 | 7.1 | n/a | Vikunja from 0.21.0 before 2.8.0 contains a resource exhaustion vulnerability that allows authenticated users to trigger instance-wide database writes by setting a project position below 0.1. Attacker |
| CVE-2026-134432 | 7.1 | n/a | Frappe ERPNext 15.0.0 before 15.121.4 and 16.x before 16.36.0 contains a missing authorization vulnerability in a Stock module import endpoint that does not check whether the caller may create inserte |
| CVE-2026-134543 | 7.1 | n/a | A flaw has been found in jprocms up to 1.7.7. Affected is the function StrUtil.format of the component Database Backup Module. Executing a manipulation of the argument host/port/username/password/dbNa |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-88g9-hfp9-hhcx | CVE-2026-123068 | unknown | The Front User Submit  WordPress plugin before 5.1.0 does not validate the content of files... |
| GHSA-vh39-75ff-8h6q | CVE-2026-134651 | medium | A flaw was found in Quay. This vulnerability allows an authenticated remote attacker holding a... |
| GHSA-pfqm-w3pj-43rg | CVE-2026-107592 | unknown | The Mooberry Book Manager WordPress plugin through 4.16.2 does not perform any capability or... |
| GHSA-p794-gcm7-8h8g | CVE-2026-134616 | low | A security vulnerability has been detected in itsourcecode Insurance Management System 1.0. The... |
| GHSA-q4rv-9fc6-2qvq | CVE-2026-105394 | unknown | The Asset CleanUp: Page Speed Booster WordPress plugin before 1.4.0.7 does not restrict which... |
| GHSA-wf3g-c83c-g6cq | CVE-2026-134623 | medium | A flaw has been found in Microweber up to 2.0.20. This impacts the function UserManager:... |
| GHSA-3r7r-r3w3-68c6 | CVE-2026-133362 | unknown | The ThinkRank SEO  WordPress plugin before 2.21.4 does not ensure that the settings section a... |
| GHSA-84q4-r67x-3wfv | CVE-2026-94259 | unknown | The SMS Alert  WordPress plugin before 4.0.4 does not sanitise and escape a parameter before... |
| GHSA-m6vj-v2mr-xvmr | CVE-2026-132814 | unknown | The WPO365 | SEAMLESS WORDPRESS + MICROSOFT INTEGRATION (WPO365 | LOGIN) WordPress plugin before... |
| GHSA-7chf-cpj8-mpv2 | CVE-2026-127024 | unknown | The WordForm  WordPress plugin before 4.1.6 does not properly validate uploaded files, allowing... |
| GHSA-3ccq-3q3j-8m83 | CVE-2026-14233 | unknown | The LifterLMS  WordPress plugin before 10.0.5 does not perform a capability or nonce check in one... |
| GHSA-hj95-42vw-qr86 | CVE-2026-123136 | unknown | The Event Tickets Manager for WooCommerce WordPress plugin before 1.6.2 does not check that the... |
| GHSA-7gv5-qqq4-jvp4 | CVE-2026-107593 | unknown | The Mooberry Book Manager WordPress plugin through 4.16.2 does not perform a capability check on... |
| GHSA-m453-87p4-7j5c | CVE-2026-120413 | unknown | The Yoast SEO  WordPress plugin before 28.9 does not check that content is publicly viewable... |
| GHSA-6p6q-h6px-c62v | CVE-2026-134572 | low | A vulnerability was identified in itsourcecode Insurance Management System 1.0. Affected by this... |
| GHSA-63xw-crcm-qh3r | CVE-2026-134704 | high | OpenShot Video Editor (openshot-qt) through 4.1.1 contains an unsafe deserialization... |
| GHSA-3jc4-fqr5-p6j3 | CVE-2026-134701 | medium | GPAC MP4Box through 26.07.0 contains a heap use-after-free vulnerability in xmt_node_end() that... |
| GHSA-4fgg-82j8-h6pf | CVE-2026-134702 | medium | GPAC MP4Box through 26.07.0 contains a type confusion vulnerability in curve2d_check_changes()... |
| GHSA-38qh-9924-4393 | CVE-2026-134703 | medium | libexpat through 2.10.0 contains an improper Unicode handling vulnerability in... |
| GHSA-rmfw-24qf-w8c3 | CVE-2026-134690 | medium | GPAC MP4Box through 26.07.0 contains a NULL pointer dereference vulnerability that allows... |
| GHSA-697w-g67q-qxwx | CVE-2026-134699 | medium | GPAC MP4Box through 26.07.0 contains a type confusion vulnerability in src/compositor/mpeg4_text... |
| GHSA-pxq4-rfwh-2p3x | CVE-2026-134698 | medium | GPAC MP4Box through 26.07.0 contains a type confusion vulnerability in ctxload_process() in src... |
| GHSA-fg7f-9wwp-mq38 | CVE-2026-134692 | medium | GPAC MP4Box through 26.07.0 contains a use-after-free vulnerability because xmt_find_node() in... |
| GHSA-f639-57pq-9f49 | CVE-2026-134691 | medium | GPAC MP4Box through 26.07.0 contains a heap use-after-free vulnerability in... |
| GHSA-5536-7f78-6gjq | CVE-2026-134695 | medium | GPAC MP4Box through 26.07.0 contains an out-of-bounds read vulnerability in avi_parse_input_file(... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| F5A | medusalocker | MF | 2026-11-21T22:16:49.906231+00:00 |
| tiic.com.ph | safepay | PH | 2026-11-21T18:34:09.356004+00:00 |
| threeroyal.com | safepay | TW | 2026-11-21T18:32:47.204185+00:00 |
| factotal.com | safepay | CL | 2026-11-21T18:31:39.732929+00:00 |
| offshore-ocs.com | safepay | SG | 2026-11-21T18:31:05.559139+00:00 |
| relax.es | safepay | ES | 2026-11-21T18:30:30.654565+00:00 |
| pacifico.com.ar | safepay | AR | 2026-11-21T18:29:55.300437+00:00 |
| qrc-solutions.com | safepay | EC | 2026-11-21T18:29:19.159876+00:00 |
| santak.com.sg | safepay | SG | 2026-11-21T18:28:43.660291+00:00 |
| themedical.co.il | safepay | IL | 2026-11-21T18:28:08.222255+00:00 |
| Regions Behavioral Hospital | incransom | US | 2026-11-21T17:20:46.157162+00:00 |
| County government within a U.S. state | SoulGroup | US | 2026-11-21T15:39:24.003787+00:00 |
| genica.com.ve | lockbit5 | VE | 2026-11-21T11:33:10.619514+00:00 |
| Dallas Fort Worth Fertility Associates | Barracuda | US | 2026-11-21T07:55:50.636176+00:00 |
| Lucid Motors | Inception | US | 2026-11-21T02:51:53.714936+00:00 |
| Kang Chiao International School (Linkou) | osiris | TW | 2026-11-21T17:23:07.745050+00:00 |
| Realta Technologies | Eclipse | IE | 2026-11-21T06:51:14.122301+00:00 |
| MT5 algo-trading farm (OneFunded funded account, WINSERVER) | PixelLeaks |  | 2026-11-20T22:54:54.318905+00:00 |
| bastion.internal domain controller (GCP, GRATEFUL-V1) | PixelLeaks |  | 2026-11-20T22:54:34.550842+00:00 |
| Aixia Group AB (Nasdaq-listed AI/IT, Sweden) | PixelLeaks | SE | 2026-11-20T22:54:13.528875+00:00 |

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
| 45.148.10.61 | 10 |
| 138.226.239.233 | 10 |
| 62.60.130.148 | 9 |
| 64.62.197.17 | 9 |
| 64.62.197.107 | 9 |
| 66.132.195.93 | 9 |
| 66.132.195.112 | 9 |
| 138.226.239.234 | 9 |
| 167.94.146.50 | 9 |
| 167.94.146.56 | 9 |
| 167.94.146.61 | 9 |
| 193.32.162.15 | 9 |
| 3.129.187.38 | 8 |
| 18.116.101.220 | 8 |
| 18.218.118.203 | 8 |
| 35.210.83.117 | 8 |
| 45.148.10.141 | 8 |
| 45.148.10.151 | 8 |
| 64.62.197.2 | 8 |
| 64.62.197.48 | 8 |

### OpenPhish (live phishing URLs)
- https://www.roblox.ly/games/84833567598383/fight-on-a-baseplate?privateServerLinkCode=60606758548615559075198493138760
- http://www.galeri-pemenang99.blogspot.com/
- https://facebooklogin123.blogspot.com/
- https://www.facebooklogin123.blogspot.com/
- https://checkallyournotifications.vercel.app/
- http://www.checkallyournotifications.vercel.app/
- http://app-kleinanzeigen.de/login.php?state=zcbj6I2k31dKKgrAsLVBwIVFufHtbl4d8Sxs0WIfQo
- http://app-kleinanzeigen.de/
- https://www.docaposteinfoar24.abrdns.com/
- https://magazineluiza-blackfriday.vercel.app/
- https://f005.backblazeb2.com/file/jufuhudu/index.html
- https://s.teamrv.homes/p/asb-pfq/jmencser/
- http://jnkf6x-vmgun2sg-yd4t-0lj0wb05-8etrg-eet71d66.pages.dev/
- https://hadiahresmi-jkt648.blogspot.com/
- http://wlwlwlwkonga.pages.dev/
- http://roblox.rw/communities/322769214560/One-Time-YT
- https://118462.xyz/BCP/login.html
- https://www.facebookloginfriends.blogspot.com/
- https://facebookloginfriends.blogspot.com/
- https://alisacruise.com/public/uikits/js/images/transferwe

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://maxis-h.biz.id/max |
| N/A | https://info-facture-prime.com/index.php |
| N/A | https://info-facture-prime.com/ |
| 7.7 | https://xfinitymailogs.weebly.com/ |
| 7.8 | https://boost-coinbase-verify.web.app/ |
| 7.8 | https://gtcontinentalonline.vercel.app/ |
| 8.2 | https://wrtyuuuu.weebly.com/ |
| 6.8 | https://maxis-li.shop/max |
| 8.2 | https://sklsckkslkss.weebly.com/ |
| 7.6 | http://allegrolokalnie.ikupteraz.shop/oferta/id-0ghsbbheyn-konsola-ps5-z-napedem---jak-nowa |
| 7.2 | https://allegrolokalnie.oferta-8261.sbs/ |
| 7.8 | https://coinbasechat.vercel.app/ |
| 6.9 | https://trustwallet.com-2fa.vip/ |
| 9.3 | https://app-kleinanzeigen.de/login.php?state=HV9IXKbkynFZxuZY0vPEhXLkcPkxeaJ4RIjPwGOduT |
| 7.8 | https://system.butudi.com/ar24-infos/ |
| 7.8 | https://doctlib-dossier.bolt.host/index.html |
| 7.8 | https://doctlib-dossier.bolt.host/ |
| 9.2 | https://app-kleinanzeigen.de/login.php |
| 8.1 | https://app-kleinanzeigen.de/login.php?state=0jTFUUVSYRZGkwIO88c3ejQ06coherUlmjtdEIQKRe |
| 7.8 | https://magazineluiza-blackfriday.vercel.app/ |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
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
| c3c9181f153a966d5e57ac0da2caa02ee0268451 | Vidar C&C |
| d07fefbb493d25b4e602bd75a5f847a76ce8817a | Vidar C&C |
| 162ae181924c0382ac8c4d1b59bd2a5ab71d68f2 | Malware distribution |
| 6e5c85d2f880211cfc2b36d1e5140890c1a26399 | PureLogsStealer C&C |
| 09d1e05f957a313204823679e8b23199ddfd85d1 | Vidar C&C |
| 311d90972082954ffd0a2da52a40209f4ded4de8 | RemusStealer C&C |
| d41dff333ce19bcd2d80a26d9df47718e65e421a | RemusStealer C&C |
| 3978f94a567a7ef1f78b59b404b3794a724bd7da | RemusStealer C&C |

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
- 1.10.160.82
- 1.12.252.163
- 1.14.240.247
- 1.146.113.188
- 1.192.216.175
- 1.203.149.250
- 1.209.148.143
- 1.212.225.99
- 1.214.214.114
- 1.222.42.237
- 1.234.53.65
- 1.234.80.94
- 1.235.183.146
- 1.235.192.214
- 1.238.106.229
- 1.247.245.61
- 1.250.67.114
- 1.250.67.190
- 1.255.147.114

### CINS Army (poorly-rated IPs)
- 1.14.3.170
- 1.145.16.243
- 1.15.14.29
- 1.170.200.20
- 1.177.162.2
- 1.180.184.182
- 1.189.41.213
- 1.197.248.101
- 1.20.151.114
- 1.208.108.242
- 1.24.16.10
- 1.24.16.106
- 1.24.16.113
- 1.24.16.114
- 1.24.16.115
- 1.24.16.120
- 1.24.16.13
- 1.24.16.143
- 1.24.16.15
- 1.24.16.150

## News (last ~36h, across outlets)
### The Hacker News
- [OpenRouter Drops 3 Providers After Researchers Catch Months of Prompt Theft at AI Hosting Firms](https://thehackernews.com/2026/11/openrouter-drops-3-providers-after.html)
- [Researchers Demonstrate Ghostscript Sandbox-Escape RCE via Crafted File Uploads in Popular Apps](https://thehackernews.com/2026/11/researchers-demonstrate-ghostscript.html)
- [A Single Malicious Webpage Let Researchers Hijack Meta Muse and Access Private Chats](https://thehackernews.com/2026/11/a-single-malicious-webpage-let.html)
- [GnuPG Warns Critical GPGME Flaw Could Expose App Data via Malicious OpenPGP Keys](https://thehackernews.com/2026/11/gnupg-warns-critical-gpgme-flaw-could.html)
- [Attackers' AI Agents Found a Zero-Day in Medical-Imaging Software and Gained Root Access](https://thehackernews.com/2026/11/attackers-ai-agents-found-zero-day-in.html)
- [Signal Blocks AI Agents From Reading Private Chats via Screenshots on Android and iOS](https://thehackernews.com/2026/11/signal-blocks-ai-agents-from-reading.html)
- [Hackers Exploit Critical VMware, Cisco, and Apache Flaws as Espionage Attacks Emerge](https://thehackernews.com/2026/11/hackers-exploit-critical-vmware-cisco.html)

### BleepingComputer
- [Rackspace Spot breach let hackers access customer Kubernetes secrets](https://www.bleepingcomputer.com/news/security/rackspace-spot-breach-let-hackers-access-customer-kubernetes-secrets/)
- [Microsoft Entra Connect Health flaw exploited to steal tenant data](https://www.bleepingcomputer.com/news/security/microsoft-entra-connect-health-flaw-exploited-to-steal-tenant-data/)
- [BADBOX botnet returns with record-breaking 40 billion daily ad requests](https://www.bleepingcomputer.com/news/security/badbox-30-botnet-returns-with-record-breaking-40-billion-daily-ad-requests/)
- [FBI reportedly hacked again, this time targeting nationwide police database](https://www.bleepingcomputer.com/news/security/fbi-reportedly-hacked-again-this-time-targeting-nationwide-police-database/)

### Krebs on Security
- [CTO of ‘RansomwareHelp’ Indicted for Wire Fraud](https://krebsonsecurity.com/2026/11/cto-of-ransomwarehelp-indicted-for-wire-fraud/)

### Dark Reading
_No new items / feed unavailable this run._

### SecurityWeek
- [FBI Investigating Apparent Hack of Its Key National Criminal Justice Database, AP Source Says](https://www.securityweek.com/fbi-investigating-apparent-hack-of-its-key-national-criminal-justice-database-ap-source-says/)
- [President Trump Taps Kirsten Davies as National Cyber Director](https://www.securityweek.com/president-trump-taps-kirsten-davies-as-national-cyber-director/)
- [Amazon: China-Linked Hackers’ AI Agents Exploited Medical Software Zero-Day](https://www.securityweek.com/amazon-china-linked-hackers-ai-agents-exploited-medical-software-zero-day/)

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
_No new items / feed unavailable this run._

### Securelist (Kaspersky)
_No new items / feed unavailable this run._

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
- [Armory Castle Attack](https://fortiguard.fortinet.com/threat-signal-report/6678)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal