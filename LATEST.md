# Winjit Daily TI Digest — 2026-11-13

_Auto-generated. Window: last ~24h. Fetched at 2026-11-13T10:44:31.539351+00:00Z_

**At a glance:** 0 new KEV · 165 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-13672 | 8.8 | 0.7% | An authorization bypass through user-controlled key vulnerability in the SSOAuth in Synology DiskStation Manager (DSM) before 7.3.2-86009-5 and 7.4.1-90080-1 allows remote authenticated users to read  |
| CVE-2026-18792 | 8.8 | 0.9% | An improper limitation of a pathname to a restricted directory vulnerability in the Sharing API in Synology DiskStation Manager (DSM) before 7.3.2-86009-5 and 7.4.1-90080-1 allows remote authenticated |
| CVE-2026-74857 | 8.8 | 0.9% | A missing critical step in authentication vulnerability in the Auth API in Synology DiskStation Manager (DSM) before 7.3.2-86009-5 and 7.4.1-90080-1 allows remote authenticated users to read or write  |
| CVE-2026-15309 | 8.8 | n/a | The CourseCure Courses plugin for WordPress is vulnerable to Privilege Escalation in versions up to, and including, 1.5.1. This is due to a missing capability check in the ajax_save_settings() functio |
| CVE-2026-124013 | 8.8 | n/a | XWEB EVO 5.6.2 through 5.8.8 contains an authenticated OS command injection vulnerability in the api.lua import_preconfiguration and restore actions, where server_url and related server credential fie |
| CVE-2026-127208 | 8.8 | n/a | datamodel-code-generator before 0.84.0 contains a code injection vulnerability that allows attackers to achieve arbitrary code execution by supplying a malicious JSON Schema with a crafted x-python-ty |
| CVE-2026-116615 | 8.8 | n/a | The Widget Options – Advanced Conditional Visibility for Gutenberg Blocks & Classic Widgets plugin for WordPress is vulnerable to Code Injection in all versions up to, and including, 4.2.6.1 via the ` |
| CVE-2026-123769 | 8.8 | n/a | The SureDash – Community, Courses & Member Dashboard plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 1.13.0 This is due to the `save_settings()` REST h |
| CVE-2026-126283 | 8.8 | n/a | NocoDB before 2026.08.0 contains an incorrect authorization vulnerability that lets base-scoped API tokens act as account-wide credentials because the token's base_id is never stored or checked. Attac |
| CVE-2026-126291 | 8.8 | n/a | NocoDB before 2026.06.2 contains an SQL injection vulnerability in base-user.cte.utils.ts, which concatenates base members' email addresses into the SQL text of queries resolving user, created-by or l |
| CVE-2026-126314 | 8.8 | n/a | Frappe HRMS 15.0.0 before 15.64.6 and 16.0.0 before 16.20.1 does not check access to each employee on endpoints that create records in bulk for a list of employees. An authenticated user with create p |
| CVE-2026-126317 | 8.8 | n/a | Frappe HRMS from 16.0.0 before 16.20.1 contains a missing authorization vulnerability that allows authenticated users to read company details outside their permissions due to a missing permission chec |
| CVE-2026-126370 | 8.8 | n/a | Vvveb through 1.0.8.6 contains a remote code execution vulnerability allowing restricted site_admin roles to inject PHP by saving .sql files through the admin code editor. Attackers can bypass extensi |
| CVE-2026-126372 | 8.8 | n/a | Vvveb through 1.0.8.6 contains an incomplete fix for CVE-2026-41934 that allows authenticated editor or site_admin users to write server-side templates by bypassing save restrictions. Attackers can up |
| CVE-2026-126412 | 8.8 | n/a | Frappe HRMS 15.0.0 before 15.64.1 and 16.0.0 before 16.19.0 lacks a write permission check on a bulk record processing action, allowing users with only read access to the related setup record to modif |
| CVE-2026-126414 | 8.8 | n/a | Frappe HRMS 15.0.0 before 15.64.2 and 16.0.0 before 16.20.0 contains a missing authorization vulnerability in certain record update endpoints that lack an ownership check. Authenticated users with the |
| CVE-2026-126458 | 8.8 | n/a | OpenEMR before 8.5.0 contains a missing authorization vulnerability in authorizations_full.php that allows any authenticated staff user to authorize arbitrary patients' clinical records. Attackers can |
| CVE-2026-126466 | 8.8 | n/a | OpenEMR before 8.5.0 contains a missing authorization vulnerability that allows any authenticated user to create patient records and enumerate patients by omitting aclCheckCore() checks. Attackers can |
| CVE-2026-126468 | 8.8 | n/a | OpenEMR before 8.5.0 contains a missing authorization vulnerability that allows any authenticated low-privilege user to access reports, dated reminders, and batch reminder endpoints lacking AclMain::a |
| CVE-2026-126469 | 8.8 | n/a | OpenEMR before 8.5.0 contains a missing authorization vulnerability in several custom/ scripts that rely only on session authentication and never call AclMain::aclCheckCore(). Any authenticated low-pr |
| CVE-2026-126470 | 8.8 | n/a | OpenEMR before 8.5.0 contains an insecure direct object reference vulnerability in the Carecoordination module that allows authenticated users with send_to_hie permission to access any patient's CCDA/ |
| CVE-2026-126472 | 8.8 | n/a | OpenEMR before 8.5.0 contains a missing authorization vulnerability in ccdaservice/ccda_gateway.php that allows any authenticated low-privilege staff user to retrieve other patients' C-CDA documents.  |
| CVE-2026-126482 | 8.8 | n/a | OpenEMR before 8.5.0 contains an SQL injection vulnerability in SLEOB::slInvoiceNumber() in src/Billing/SLEOB.php, which concatenates the CLP01 claim identifier from uploaded X12 835 ERA files into a  |
| CVE-2026-126487 | 8.8 | n/a | OpenEMR before 8.5.0 contains an authorization bypass vulnerability that allows authenticated users to override system-wide global configuration values by storing global-prefixed keys through library/ |
| CVE-2026-126948 | 8.8 | n/a | Zipline before 4.5.0 contains an insecure direct object reference vulnerability caused by missing ownership verification in the PATCH and DELETE handlers for /api/user/folders/:id. Authenticated attac |
| CVE-2026-127090 | 8.8 | n/a | Jadaptive Maverick Synergy Server before 3.0.33 and 3.1.x before 3.1.7, and Maverick Legacy Server before 1.8.1, contain an authentication bypass vulnerability in SSH public key authentication that re |
| CVE-2026-126269 | 8.7 | n/a | NocoDB before 2026.09.0 contains a stored cross-site scripting vulnerability that allows authenticated Editor users to execute scripts by storing crafted attachment MIME types like text/html;image/png |
| CVE-2026-126274 | 8.7 | n/a | NocoDB before 2026.08.0 contains a stored cross-site scripting vulnerability that allows authenticated Creator users to inject script by embedding markup in column or table titles. The Delete.vue conf |
| CVE-2026-126310 | 8.7 | n/a | OpenBao before 2.6.5 and 2.7.2 contains an authentication bypass vulnerability that allows unauthenticated callers to obtain OIDC ID tokens by abusing public clients with client_credentials enabled. A |
| CVE-2026-126945 | 8.7 | n/a | Zipline before 4.5.1 contains a stored cross-site scripting vulnerability in the HighlightCode component that renders unescaped file content before highlight.js finishes loading. Authenticated attacke |
| CVE-2026-85101 | 8.6 | 0.6% | An authentication bypass using an alternate path or channel vulnerability in the rsync in Synology DiskStation Manager (DSM) before 7.2.1-69057-13, 7.2.2-72806-10, 7.3.2-86009-5, and 7.4.1-90080-1 all |
| CVE-2024-58405 | 8.6 | n/a | Zipline through 3.7.9 contains an improper authorization vulnerability in the /api/auth/register endpoint, which enforces invite codes only when user registration is disabled, so registration succeeds |
| CVE-2026-126321 | 8.3 | n/a | Dockhand before 1.0.55 contains a path traversal vulnerability that allows authenticated users with stacks:edit to bypass the file-browser path guard by combining symlinks with '..' sequences. Attacke |
| CVE-2026-124218 | 8.2 | n/a | The Drag and Drop File Upload for Elementor Forms plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation in the remove_files function in all versions up |
| CVE-2026-126383 | 8.2 | n/a | n8n before 1.123.89, 2.x before 2.45.5, 2.46.x before 2.46.1, and 3.x before 3.0.1 contains a NoSQL injection vulnerability in the MongoDB node's Update and Find And Replace operations due to insuffic |
| CVE-2026-18596 | 8.1 | 0.7% | An authentication bypass using an alternate path or channel vulnerability in the OTP in Synology DiskStation Manager (DSM) before 7.3.2-86009-5 and 7.4.1-90080-1 allows remote attackers with valid use |
| CVE-2026-19048 | 8.1 | 0.8% | An improper link resolution before file access vulnerability in the thumb in Synology DiskStation Manager (DSM) before 7.3.2-86009-5 and 7.4.1-90080-1 allows remote authenticated users to write arbitr |
| CVE-2026-81584 | 8.1 | 0.6% | An improper neutralization of special elements used in an SQL command vulnerability in the User API in Synology DiskStation Manager (DSM) before 7.3.2-86009-5 and 7.4.1-90080-1 allows remote attackers |
| CVE-2026-124005 | 8.1 | n/a | XWEB EVO 4.3.0 through 5.8.8 contains a weak password generation vulnerability that allows remote attackers to derive the Administrator code-of-the-day password using only the device MAC address and d |
| CVE-2026-124006 | 8.1 | n/a | XWEB EVO through 5.8.8 contains a predictable credential generation vulnerability that allows attackers to derive the Linux root password by computing a fixed prefix combined with a daily password val |
| CVE-2026-124012 | 8.1 | n/a | XWEB EVO 5.6.2 through 5.8.8 contains a hardcoded credential vulnerability where the Administrator web account is configured to use password_mode daily_password with no stored password, as the Users.a |
| CVE-2025-71459 | 8.1 | n/a | Zipline through 4.3.2 contains a path traversal vulnerability that allows authenticated uploaders to write files outside the upload directory by supplying traversal sequences in the x-zipline-filename |
| CVE-2026-118191 | 8.1 | n/a | The Photo Gallery, Sliders, Proofing and Themes – NextGEN Gallery plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation in the handle_job function in a |
| CVE-2026-126273 | 8.1 | n/a | NocoDB before 2026.09.0 contains a privilege escalation vulnerability in initAdminFromEnv.ts that silently skips super-admin bootstrap when the admin password environment variable is empty. Unauthenti |
| CVE-2026-126286 | 8.1 | n/a | NocoDB before 2026.08.0 contains a reflected cross-site scripting vulnerability in PageLeavingWarning.vue that allows unauthenticated attackers to execute script by embedding an ASCII control characte |
| CVE-2026-126322 | 8.1 | n/a | OpenEMR before 8.3.0 contains an unsanitized deserialization vulnerability that allows authenticated attackers to control patient-matching criteria by supplying a crafted serialized key parameter. Att |
| CVE-2026-126375 | 8.1 | n/a | Vvveb through 1.0.8.6 contains a missing authorization vulnerability that allows low-privilege vendors to rename, delete, or overwrite other vendors' digital-asset files in the shared storage/digital_ |
| CVE-2026-126377 | 8.1 | n/a | Vvveb before 1.0.9.0 contains an authentication bypass vulnerability in generateCookie() in system/user/user.php that uses loose comparison to validate MD5 cookie hashes. Unauthenticated attackers can |
| CVE-2026-126430 | 8.1 | n/a | OpenEMR before 8.5.0 contains an sql injection vulnerability that allows any authenticated core user to inject SQL by supplying crafted patient_data field names to the CCR revandapprove controller. At |
| CVE-2026-126434 | 8.1 | n/a | OpenEMR before 8.5.0 contains a missing authorization vulnerability in interface/forms/procedure_order/common.php that allows authenticated accounts lacking patients/lab permission to read and modify  |
| CVE-2026-126442 | 8.1 | n/a | OpenEMR before 8.5.0 contains a missing authorization vulnerability in create_portallogin.php that allows low-privilege authenticated users to replace patient portal credentials without ACL checks. At |
| CVE-2026-126454 | 8.1 | n/a | OpenEMR before 8.5.0 lacks rate limiting or lockout on TOTP submission, allowing attackers with a valid password to brute-force the 6-digit MFA code. Attackers can script repeated POST requests to mai |
| CVE-2026-126455 | 8.1 | n/a | OpenEMR before 8.5.0 contains multiple missing authorization and SQL injection defects across report, portal, transaction, and immunization components. Low-privileged Front Office clerks can chain the |
| CVE-2026-126480 | 8.1 | n/a | OpenEMR before 8.5.0 contains an sql injection vulnerability in CcrTable::insertApprovedData() that allows authenticated users to inject SQL through request parameter names used as column names. Attac |
| CVE-2026-126481 | 8.1 | n/a | OpenEMR before 8.5.0 contains a path traversal vulnerability in era_payments.php and sl_eob_search.php that allows authenticated billing users to write files outside the ERA directory. Attackers can e |
| CVE-2026-126937 | 8.1 | n/a | Zipline before 4.6.5 contains a TOCTOU race condition in the POST /api/setup endpoint that allows unauthenticated attackers to create multiple SUPERADMIN accounts by racing concurrent requests before  |
| CVE-2026-126952 | 8.1 | n/a | Zipline through 4.4.0 contains an authentication bypass vulnerability in the WebAuthn login endpoint that creates sessions for a supplied registered credential ID without verifying the assertion. Atta |
| CVE-2026-126953 | 8.1 | n/a | Cudy TR3000 before 2.5.42 contains an OS command injection vulnerability that allows a malicious or compromised ACS to execute commands as root by supplying an unvalidated InternetGatewayDevice.User.{ |
| CVE-2026-127088 | 8.1 | n/a | 2FAuth before 9.0.1 contains a weak password recovery vulnerability that allows unauthenticated attackers to poison reset links by forging the HTTP Host header. Attackers can request password or WebAu |
| CVE-2026-128014 | 8.1 | n/a | FrankenPHP standalone static binaries 1.8.0 before 1.13.2 bundle the PHP brotli extension statically linked with Brotli 1.2.0, whose decoder contains an out-of-bounds write (CVE-2026-111497). Unauthen |
| CVE-2026-128046 | 8.1 | n/a | OpenMage magento-lts 20.17.0 before 20.18.2 and 21.0.0-beta1 before 21.0.0-beta3 contains an unrestricted file upload vulnerability because the general/file/protected_extensions blocklist omits phar,  |
| CVE-2026-128047 | 8.1 | n/a | OpenMage magento-lts before 20.18.2 and 21.0.0-beta pre-releases before 21.0.0-beta3 generate customer email-confirmation keys with md5(uniqid()) and customer and administrator password-reset tokens w |
| CVE-2026-75491 | 8.1 | n/a | Cudy TR3000 before 2.5.42 contains an authentication bypass vulnerability in the Mosquitto plugin auth_plugin_jwt.so that accepts unsigned JWTs using alg none. Attackers holding any Cudy-trusted clien |
| CVE-2026-75495 | 8.1 | n/a | Cudy TR3000 before 2.5.42 contains an OS command injection vulnerability that allows a malicious or compromised ACS to execute commands as root by supplying a crafted InternetGatewayDevice.User.{i}.Pa |
| CVE-2026-126282 | 8.0 | n/a | NocoDB from 2026.04.0 before 2026.08.0 contains an improper privilege management vulnerability in org-users.service.ts where updating a user's legacy organization role rewrites their default-workspace |
| CVE-2026-126306 | 8.0 | n/a | EspoCRM before 9.3.11 and 10.x before 10.0.8 contains a stored cross-site scripting vulnerability that allows low-privileged users to upload crafted SVG images that submit authenticated POST requests  |
| CVE-2026-128041 | 8.0 | n/a | OpenMage magento-lts before 20.18.2 and 21.0.0-beta1 before 21.0.0-beta3 serves RSS feeds with a text/html content type and does not escape feed entry data, leading to stored cross-site scripting. An  |
| CVE-2026-121876 | 7.9 | n/a | A flaw was found in the interaction between systemd-gpt-auto-generator and 
confidential computing guest VM images in OpenShift Sandboxed Containers 
(confidential peer pods). systemd-gpt-auto-generat |
| CVE-2026-87772 | 7.8 | 0.1% | Incorrect Authorization vulnerability in TÜBİTAK BİLGEM Software Technologies Research Institute Pardus About allows Privilege Escalation.

This issue affects Pardus About: before 1.2.5. |
| CVE-2026-92083 | 7.8 | n/a | Missing Authorization vulnerability in TÜBİTAK BİLGEM Yazılım Teknolojileri Araştırma Enstitüsü pardus-image-writer allows Privilege Escalation.

This issue affects pardus-image-writer: before 0.9.0. |
| CVE-2024-58404 | 7.7 | n/a | Zipline versions from 3.4.5 before 3.7.10 contain a path traversal vulnerability in the user data export endpoint via the name query parameter. Authenticated attackers can bypass the user id check and |
| CVE-2026-126264 | 7.7 | n/a | SiYuan before 3.8.9 contains an information disclosure vulnerability that allows authenticated Reader users to retrieve credential-named widget files by bypassing the sensitive-path guard in getFile.  |
| CVE-2026-126271 | 7.7 | n/a | NocoDB before 2026.09.0 contains an information disclosure vulnerability that allows authenticated base Viewers to obtain TLS client private keys by reading a base's data source. The source read handl |
| CVE-2026-126285 | 7.7 | n/a | NocoDB before 2026.08.0 contains an sql injection vulnerability that allows authenticated users with read access to run arbitrary read queries via the legacy where parameter on PostgreSQL. Attackers,  |
| CVE-2026-126308 | 7.7 | n/a | The web dashboard in Coder 2.24.0 before 2.29.23, 2.30.0 before 2.34.14, 2.35.0 before 2.36.9, 2.37.0 before 2.37.6, and 2.38.0 before 2.38.2 replaces the $SESSION_TOKEN placeholder in external app UR |
| CVE-2026-126385 | 7.7 | n/a | n8n before 2.45.5, 2.46.x before 2.46.1, and 3.x before 3.0.1 contains a flaw in the OAuth2 credential callback of the dynamic-credential connect flow, which does not verify that the completing browse |
| CVE-2026-126488 | 7.7 | n/a | OpenEMR before 8.5.0 contains an SQL injection vulnerability in the patient portal OnsiteDocument.Query endpoint, where mass-assigned _BitwiseAnd criteria parameters are placed unquoted into SQL with  |
| CVE-2026-127082 | 7.7 | n/a | Huginn before 2026.11.09 contains an information exposure vulnerability in JqAgent that allows authenticated users to read the server process environment because the jq child process inherits it. Atta |
| CVE-2026-128044 | 7.7 | n/a | OpenMage magento-lts before 20.18.2 and 21.x before 21.0.0-beta3 validates OAuth 1.0a oauth_callback URLs with a string-prefix check and falls back to accepting any well-formed URL. Attackers holding  |
| CVE-2026-128329 | 7.7 | n/a | Dokploy 0.28.0 before 0.31.1 contains a path traversal vulnerability that allows authenticated organization members to read arbitrary files by supplying ../ sequences in the filePath of patch.readRepo |
| CVE-2026-126379 | 7.6 | n/a | Vvveb 1.0.8.6 contains an incomplete server-side request forgery fix that allows authenticated admin users to bypass DNS pinning by requesting non-443 URLs. Attackers can supply a rebinding hostname t |
| CVE-2026-126478 | 7.6 | n/a | OpenEMR before 8.5.0 contains an SQL injection vulnerability in the Syndromic Surveillance report because the form_icd_codes[] POST array is concatenated into an unquoted numeric IN() clause without i |
| CVE-2026-126479 | 7.6 | n/a | OpenEMR before 8.5.0 contains a missing authorization vulnerability in five Module Manager InstallerController actions that lack the admin/manage_modules ACL check and CSRF validation. Low-privilege u |
| CVE-2026-126486 | 7.6 | n/a | OpenEMR before 8.5.0 contains a missing authorization vulnerability in portal/import_template.php, where several portal document template modes lack admin/forms ACL and CSRF checks. Any authenticated  |
| CVE-2026-126491 | 7.6 | n/a | OpenEMR before 8.5.0 contains a stored SQL injection vulnerability in getByPatientDemographics() where layout_options field_id values are concatenated into the patient search WHERE clause. Attackers w |
| CVE-2026-127094 | 7.6 | n/a | Pagelayer 2.1.7 before 2.2.1 contains a missing authorization vulnerability in Abilities API abilities registered in main/abilitiesregister.php that only require the edit_posts capability. Contributor |
| CVE-2026-18633 | 7.5 | 0.8% | An access of uninitialized pointer vulnerability in the nfsd in Synology DiskStation Manager (DSM) before 7.3.2-86009-5 and 7.4.1-90080-1 allows remote attackers to conduct denial-of-service attacks. |
| CVE-2026-110951 | 7.5 | n/a | Weak Password Recovery Mechanism for Forgotten Password vulnerability in Hyper Teknoloji Ltd. Şti. Hyper E-Commerce Infrastructure, Hyper Teknoloji Ltd. Şti. Hyper E-Commerce Infrastructure - dealer i |
| CVE-2026-127029 | 7.5 | n/a | A flaw was found in freeradius's Extensible Authentication Protocol Method for Subscriber Identity Module (EAP-SIM) module. When handling authentication requests, the server copies a client-supplied i |
| CVE-2026-127204 | 7.5 | n/a | WooCommerce PayPal Pro Payment Gateway plugin before 4.1.1 contains an unauthenticated payment bypass vulnerability that allows remote attackers to mark unpaid orders as paid by exploiting the pp_capt |
| CVE-2023-54423 | 7.5 | n/a | OpenMage magento-lts before 20.2.0 contains a stored cross-site scripting vulnerability because the TinyMCE WYSIWYG editor fails to filter scripts in specially crafted HTML tags. Attackers can inject  |
| CVE-2026-126266 | 7.5 | n/a | SiYuan from 3.6.0 before 3.8.9 contains an information disclosure vulnerability that allows unauthenticated publish visitors to bypass per-document passwords via regex search in getDoc. Attackers can  |
| CVE-2026-126277 | 7.5 | n/a | NocoDB before 2026.08.1 contains an uncontrolled resource consumption vulnerability that allows unauthenticated attackers to exhaust server resources by sending unbounded filter arrays to shared-view  |
| CVE-2026-126278 | 7.5 | n/a | NocoDB before 2026.08.1 contains a race condition vulnerability in users.service.ts that allows holders of a valid reset token to perform multiple password changes by sending concurrent reset requests |
| CVE-2026-126294 | 7.5 | n/a | Grav Login plugin before 3.11.0 contains an authentication bypass vulnerability that allows attackers with an account password to skip two-factor verification when the global twofa_enabled setting is  |
| CVE-2026-126297 | 7.5 | n/a | NLTK before 3.10.4 contains a quadratic-time denial of service vulnerability in ConllCorpusReader._get_srl_instances that allows remote attackers to exhaust CPU through nested span rescans. Attackers  |
| CVE-2026-126298 | 7.5 | n/a | NLTK before 3.10.4 contains a denial of service vulnerability in Tree.chomsky_normal_form that allows remote attackers to exhaust CPU through quadratic-time right-factor binarization using list.pop(0) |
| CVE-2026-126299 | 7.5 | n/a | NLTK before 3.10.4 contains a denial of service vulnerability in the CCG lexicon parser fromstring that allows remote attackers to exhaust CPU by supplying wide inputs. Attackers can submit lexicon te |
| CVE-2026-126303 | 7.5 | n/a | NLTK before 3.10.4 contains an uncontrolled resource consumption vulnerability in SteppingRecursiveDescentParser.parse() that lacks any max_time deadline or step limit. Attackers influencing the gramm |
| CVE-2026-126304 | 7.5 | n/a | NLTK from 3.10.0 before 3.10.4 contains a symlink escape vulnerability in YCOECorpusReader that allows attackers to read files outside the corpus root by planting psd or pos directory symlinks. Attack |
| CVE-2026-126307 | 7.5 | n/a | Nezha Dashboard before 2.6.0 contains multiple authorization, tenant isolation, and resource exhaustion vulnerabilities that allow members or unauthenticated attackers to abuse NAT, DDNS, OAuth, cron, |
| CVE-2026-126384 | 7.5 | n/a | n8n before 1.123.89, 2.x before 2.45.5, 2.46.x before 2.46.1, and 3.x before 3.0.1 bundles a GraphicsMagick version with known vulnerabilities in its official Docker image, which the Edit Image node u |
| CVE-2026-126391 | 7.5 | n/a | n8n before 1.123.89 contains an insufficient isolation vulnerability in workflow expression evaluation that allows authenticated users to escape the sandbox. Attackers with permission to create or mod |
| CVE-2026-126397 | 7.5 | n/a | vLLM from 0.10.1 before 0.31.0 forwards a request-controlled mm_processor_kwargs.max_patches value to the Hugging Face processor for Cohere2 Vision models without a server-side upper bound, causing qu |
| CVE-2026-126401 | 7.5 | n/a | Fleet before 4.86.2 contains a denial of service vulnerability that allows unauthenticated attackers to exhaust server memory through quadratic XML canonicalization of unsigned SAML responses. Attacke |
| CVE-2026-126428 | 7.5 | n/a | OpenEMR before 8.5.0 contains a remote code execution vulnerability that allows authenticated billing users to store attacker-controlled PHP by uploading a malformed ERA file to era_payments.php. Atta |
| CVE-2026-126436 | 7.5 | n/a | OpenEMR before 8.5.0 contains an authorization bypass vulnerability that allows OAuth2 clients to use unregistered grant types because oauth_clients.grant_types is never enforced. Attackers can reques |
| CVE-2026-128242 | 7.5 | n/a | actix-http before 3.20.1 and actix-web before 4.18.2 contain an unbounded decompression vulnerability in encoding::Decoder that lets remote attackers exhaust memory and CPU via compressed bodies. Atta |
| CVE-2026-128338 | 7.5 | n/a | exceljs through 4.4.0 contains a memory exhaustion vulnerability that allows attackers to crash applications by supplying a worksheet col element with an unbounded max attribute. Attackers can craft a |
| CVE-2026-128339 | 7.5 | n/a | ExcelJS through 4.4.0 contains a memory exhaustion vulnerability in Worksheet._parseMergeCells that allows attackers to crash applications by supplying unbounded mergeCell ranges. Attackers can craft  |
| CVE-2026-128340 | 7.5 | n/a | ExcelJS through 4.4.0 contains a memory exhaustion vulnerability that allows attackers to crash applications by supplying a workbook with an oversized defined-name range. DefinedNames.addEx expands ra |
| CVE-2026-128341 | 7.5 | n/a | ExcelJS through 4.4.0 contains a resource exhaustion vulnerability in data-validations-xform.js that allows attackers to exhaust CPU and memory by supplying unbounded sqref ranges. Attackers can provi |
| CVE-2026-128342 | 7.5 | n/a | ExcelJS through 4.4.0 contains a denial of service vulnerability that allows attackers to block the event loop by supplying an unbounded sheetId in xl/workbook.xml. Attackers can provide a workbook wi |
| CVE-2026-128343 | 7.5 | n/a | exceljs through 4.4.0 contains a denial of service vulnerability that allows attackers to block the event loop by supplying unbounded row r attributes parsed in row-xform.js. Attackers can craft an XL |
| CVE-2026-128344 | 7.5 | n/a | ExcelJS through 4.4.0 contains a memory exhaustion vulnerability that allows attackers to crash applications by supplying a workbook with an unbounded image anchor column in the drawing part. Attacker |
| CVE-2026-128346 | 7.5 | n/a | ExcelJS through 4.4.0 contains a resource leak vulnerability in the streaming WorkbookReader.parse that leaves temporary files and open descriptors when sheet parsing fails or iteration stops early. A |
| CVE-2026-128347 | 7.5 | n/a | ExcelJS through 4.4.0 contains an arbitrary file read vulnerability in the streaming WorkbookWriter that allows attackers to read local files by supplying crafted image filenames to addImage. Attacker |
| CVE-2026-75490 | 7.5 | n/a | Cudy TR3000 before 2.5.42 contains a remote code execution vulnerability that allows unauthenticated adjacent attackers to run root commands by advertising a rogue automesh controller over mDNS. Attac |
| CVE-2026-75492 | 7.5 | n/a | Cudy TR3000 before 2.5.42 contains an unauthenticated stack buffer overflow vulnerability in the stun_client TR-111 UDP Connection Request parser that parses requests before verifying username or HMAC |
| CVE-2026-127111 | 7.4 | n/a | SOGo before 5.12.13 contains an improper restriction of excessive authentication attempts vulnerability that allows unauthenticated attackers to reset account passwords by repeatedly guessing secret-q |
| CVE-2026-127131 | 7.4 | n/a | SOGo before 5.12.13 contains a missing rate limiting vulnerability in its web login TOTP verification that allows attackers who already possess a victim's password to brute-force the second-factor cod |
| CVE-2026-126265 | 7.4 | n/a | SiYuan 2.1.0 before 3.8.9 contains a flaw where the loginAuth CAPTCHA challenge lives in a signed client-side cookie, allowing reuse of a solved challenge. Attackers can replay the original signed siy |
| CVE-2026-126280 | 7.4 | n/a | NocoDB before 2026.08.0 contains a race condition in refresh-token rotation that allows attackers to reuse tokens because UserRefreshToken.ts never checks the affected-row count. Attackers holding a c |
| CVE-2026-127079 | 7.4 | n/a | OpsTree BuildPiper before 2.7.0 lacks rate limiting on password-reset OTP verification, allowing unauthenticated attackers to brute force 6-digit OTPs. Attackers can initiate a reset and submit unthro |
| CVE-2026-128023 | 7.4 | n/a | FrankenPHP before 1.13.0 contains an authentication bypass vulnerability that allows unauthenticated attackers to spoof trusted headers by sending dot-form header names that PHP rewrites to underscore |
| CVE-2026-128332 | 7.4 | n/a | Listmonk 6.0.0 before 7.0.0-beta.2 contains a 2FA bypass vulnerability that allows attackers with a valid password to brute-force TOTP codes because the attempt counter resets on every new password lo |
| CVE-2026-128333 | 7.4 | n/a | listmonk 6.0.0 before 7.0.0-beta.2 contains an authentication bypass vulnerability in doResetPassword that skips TOTP verification after a password reset. Attackers who can complete a reset, such as b |
| CVE-2026-75494 | 7.4 | n/a | Cudy TR3000 before 2.5.42 contains an argument injection vulnerability that allows a malicious or compromised ACS to inject curl options through unfiltered Username and Password values in the easycwmp |
| CVE-2026-126795 | 7.3 | 0.5% | A vulnerability was determined in ToolJet up to 3.20.256-lts/3.21.93-beta. The impacted element is the function activateUserWithPassword of the file server/src/modules/onboarding/util.service.ts of th |
| CVE-2026-126997 | 7.3 | n/a | A vulnerability was identified in JeecgBoot up to 3.9.6. This affects the function RestTemplate.exchange of the file org/jeecg/modules/airag/flow/c/a.class of the component flow-run Endpoint. The mani |
| CVE-2026-127278 | 7.3 | n/a | A weakness has been identified in AIP-PUB ACPs-community up to 2.2.0. The impacted element is the function send_verification_code of the file registry-server/app/account/service_auth.py of the compone |
| CVE-2026-127279 | 7.3 | n/a | A vulnerability was detected in AIP-PUB ACPs-community up to 2.2.0. This impacts an unknown function of the file discovery-server/app/main.py of the component Discovery Server. The manipulation result |
| CVE-2026-127281 | 7.3 | n/a | A vulnerability was found in lanyulei ferry 1.0.0-beta.1/1.0.0. Affected is an unknown function of the file middleware/auth.go of the component JWT Validation. The manipulation results in improper aut |
| CVE-2026-127283 | 7.3 | n/a | A vulnerability was identified in SourceCodester Food Ordering System 1.0. Affected by this issue is some unknown functionality of the file admin/update_food.php of the component Admin Image Handler.  |
| CVE-2026-127284 | 7.3 | n/a | A security flaw has been discovered in SourceCodester Food Ordering System 1.0. This affects an unknown part of the file admin/add_category.php of the component Admin Write Handler. Performing a manip |
| CVE-2026-127286 | 7.3 | n/a | A vulnerability was identified in Zackriya-Solutions Meetily up to 0.4.1. Affected is an unknown function of the file backend/app/main.py. The manipulation leads to missing authentication. The attack  |
| CVE-2026-126305 | 7.3 | n/a | EspoCRM before 9.3.11 and 10.x before 10.0.9 contains a stored cross-site scripting vulnerability in Knowledge Base articles that lets users with Knowledge Base create or edit access attach a JavaScri |
| CVE-2026-126451 | 7.3 | n/a | OpenEMR before 8.5.0 contains a stored cross-site scripting vulnerability that allows portal patients to run JavaScript in staff sessions by injecting javascript: URLs into document template_data. Att |
| CVE-2026-127084 | 7.3 | n/a | Teable before 2026-10-12T12-45-53Z.3331 contains a stored cross-site scripting vulnerability that allows authenticated users to upload SVG or HTML attachments with an attacker-chosen content type. Att |
| CVE-2026-75785 | 7.2 | 0.9% | An improper neutralization of special elements used in an OS command vulnerability in the VPN API in Synology DiskStation Manager (DSM) before 7.3.2-86009-5 and 7.4.1-90080-1 allows remote authenticat |
| CVE-2026-124008 | 7.2 | n/a | XWEB EVO 5.2.3 through 5.8.8 contains an authenticated OS command injection vulnerability in the devices.lua template handling, which allows authenticated attackers to execute arbitrary commands by in |
| CVE-2026-124009 | 7.2 | n/a | XWEB EVO 5.2.3 through 5.8.8 contains an authenticated OS command injection vulnerability that allows authenticated attackers to execute arbitrary commands as root by injecting shell metacharacters in |
| CVE-2026-120688 | 7.2 | n/a | The EZ SQL Reports Shortcode Widget and DB Backup plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'HTTP_USER_AGENT (demonstrated); more generally, any attacker-controllable D |
| CVE-2026-126402 | 7.2 | n/a | Fleet before 4.89.0 contains an incorrect authorization flaw in its user administration API that accepts user creation or modification when the caller administers any one of the assigned teams. Authen |
| CVE-2026-126425 | 7.2 | n/a | OpenEMR before 8.5.0 contains a stored SQL injection vulnerability in which History layout field identifiers saved through edit_layout.php, including HIS fields and LBF source-H fields, are placed unv |
| CVE-2026-126489 | 7.2 | n/a | OpenEMR before 8.5.0 contains a second-order SQL injection vulnerability in the IPPF contraceptive issue feature because issue_ippf_con_save concatenates layout_options field_id values into a REPLACE  |
| CVE-2026-75487 | 7.2 | n/a | Cudy TR3000 before 2.5.42 contains a command injection vulnerability that allows authenticated administrators to execute commands as root via the WireGuard server private_key option. Attackers can sav |
| CVE-2026-75576 | 7.2 | n/a | Cudy TR3000 before 2.5.42 contains a command injection vulnerability that allows authenticated administrators to execute commands as root via an unvalidated multipart filename in the CBI FileUpload ha |
| CVE-2026-75577 | 7.2 | n/a | Cudy TR3000 before 2.5.42 contains a command injection vulnerability that allows authenticated administrators to execute commands as root by storing a malicious WireGuard private key. Attackers can sa |
| CVE-2026-75578 | 7.2 | n/a | Cudy TR3000 before 2.5.42 contains a command injection vulnerability in luci/model/cbi/vpn/openvpn/client.lua, which embeds the shellquote()-quoted remote host token of an uploaded OpenVPN configurati |
| CVE-2026-111552 | 7.1 | n/a | Use of single-factor authentication vulnerability in Hyper Teknoloji Ltd. Şti. Hyper E-Commerce Infrastructure, Hyper Teknoloji Ltd. Şti. Hyper E-Commerce Infrastructure - dealer integration, and Hype |
| CVE-2026-126275 | 7.1 | n/a | NocoDB before 2026.09.0 contains an insecure direct object reference vulnerability that allows authenticated users to read cross-base row comments by supplying only model and row ids. Attackers with a |
| CVE-2026-126309 | 7.1 | n/a | OpenBao before 2.6.5 and 2.7.2 contains a path traversal vulnerability in Transit key import that allows authenticated attackers to bypass name restrictions in ACL policies. Attackers limited by a req |
| CVE-2026-126312 | 7.1 | n/a | OpenBao before 2.6.5 and 2.7.x before 2.7.2, and the openbao-plugins LDAP and RADIUS auth plugins before 0.2.0, contain an ACL bypass in the AppRole, Cert, LDAP, and RADIUS auth methods caused by impl |
| CVE-2026-126416 | 7.1 | n/a | OpenEMR before 8.5.0 contains an improper authorization vulnerability in patient_tracker_status.php that allows low-privilege authenticated users to modify other patients' tracker entries by supplying |
| CVE-2026-126449 | 7.1 | n/a | OpenEMR before 8.5.0 contains a missing authorization vulnerability in immunizations.php, diagnosis_full.php, and billing_process.php that lets low-privileged users bypass ACL checks. Authenticated Fr |
| CVE-2026-126452 | 7.1 | n/a | OpenEMR before 8.5.0 contains a missing authorization vulnerability in diagnosis_full.php that allows authenticated users to delete or clear any billing record by ID. Attackers can supply a target bil |
| CVE-2026-126460 | 7.1 | n/a | OpenEMR before 8.5.0 contains a persistent SQL injection vulnerability in SLEOB::slInvoiceNumber(), where the CLP01 claim control number from uploaded X12 835 ERA files is concatenated unescaped into  |
| CVE-2026-126463 | 7.1 | n/a | OpenEMR before 8.5.0 contains multiple sql injection vulnerabilities that allow authenticated users to inject payloads through ERA CLP01, form_facility, form_icd_codes, and POST key names. Attackers c |
| CVE-2026-126492 | 7.1 | n/a | OpenEMR before 8.5.0 contains a second-order sql injection vulnerability that allows low-privileged authenticated users to store malicious SQL via library/ajax/addlistitem.php. Attackers can persist a |
| CVE-2026-126494 | 7.1 | n/a | OpenEMR before 8.4.0 contains an improper authorization vulnerability in ScopeRepository::finalizeScopes() that allows read-only SMART/OAuth clients to obtain write scopes because ScopeEntity::contain |
| CVE-2026-126938 | 7.1 | n/a | Zipline before 4.6.4 contains a resource allocation vulnerability that allows authenticated users to bypass chunked-upload size and quota checks by forging Content-Range offsets and totals. Attackers  |
| CVE-2026-127077 | 7.1 | n/a | OpsTree BuildPiper before 2.7.0 contains an authorization bypass vulnerability that allows authenticated users to create environments on unassigned Kubernetes clusters by tampering with cluster_id and |
| CVE-2026-127078 | 7.1 | n/a | OpsTree BuildPiper before 2.7.0 contains an authorization bypass vulnerability that allows authenticated users to attach another application's environment to their service by supplying a foreign proje |
| CVE-2026-128337 | 7.0 | n/a | ExcelJS through 4.4.0 contains a prototype pollution vulnerability in mergeConditionalFormattings that allows attackers to modify Object.prototype by supplying an x14:cfRule id of __proto__. Attackers |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-vg7f-4c95-cv88 | CVE-2026-128824 | medium | A flaw was found in Red Hat Quay. The v1 registry API error handler reflects the attacker... |
| GHSA-99cc-4c28-q5f7 | CVE-2026-116430 | medium | Dell PowerScale InsightIQ, Version 6.4.0, contain an Insufficient Verification of Data... |
| GHSA-x64c-625c-5prc | CVE-2026-120866 | high | Memory overflow / improper handling in BGP dynamic routing can lead to unpredictable or erroneous... |
| GHSA-qfg7-vp52-rgx5 | CVE-2026-116438 | medium | Dell PowerScale InsightIQ, Versions 6.3.0 through 6.4.0 , contains a Missing Authorization... |
| GHSA-h4x9-24c3-pjfm | CVE-2026-120865 | high | Memory overflow in HTTP/3 (QUIC) can lead to unpredictable or erroneous behavior or Denial of... |
| GHSA-fx6c-qwpx-wfh7 | CVE-2026-120864 | critical | Memory overflow in ICA proxy can lead to unpredictable or erroneous behavior or Denial of Service... |
| GHSA-48v8-97gp-jm6m | CVE-2026-120867 | high | Memory overflow in SSL/TLS/DTLS can lead to unpredictable or erroneous behavior or Denial of... |
| GHSA-8q4x-px43-5pw8 | CVE-2026-116453 | medium | Dell PowerScale InsightIQ, Versions 6.3.0 through 6.4.0, contains a Missing Authorization... |
| GHSA-65c5-pp56-45wv | CVE-2026-116436 | medium | Dell PowerScale InsightIQ, Versions 6.3.0 through 6.4.0, contains an Insertion of Sensitive... |
| GHSA-3xhh-55c2-2w84 | CVE-2026-116431 | medium | Dell PowerScale InsightIQ, Versions 6.3.0 through 6.4.0, contains a Cleartext Storage of... |
| GHSA-5grf-cxj4-3683 | CVE-2026-116427 | medium | Dell PowerScale InsightIQ, Versions 6.3.0 through 6.4.0, contains a Missing Authorization... |
| GHSA-px29-7vx5-v77j | CVE-2026-116426 | medium | Dell PowerScale InsightIQ, Versions 6.3.0 through 6.4.0, contains an Insertion of Sensitive... |
| GHSA-62qj-qf7p-2wgm | CVE-2026-116425 | medium | Dell PowerScale InsightIQ, Versions 6.3.0 through 6.4.0, contains unauthorized access... |
| GHSA-mg9q-8xmx-6cqq | CVE-2026-116423 | medium | Dell PowerScale InsightIQ, versions 6.3.0 through 6.4.0, contains an Improper Verification of... |
| GHSA-63vx-3r38-6rjr | CVE-2026-116424 | medium | Dell PowerScale InsightIQ, versions 6.3.0 through 6.4.0, contains Unauthorized access... |
| GHSA-39mr-hpmh-g4gx | CVE-2026-116417 | high | Dell PowerScale InsightIQ, versions 6.3.0 through 6.4.0, contains a Weak Password Requirements... |
| GHSA-c448-vjpv-mrhc | CVE-2026-116420 | medium | Dell PowerScale InsightIQ, versions 6.3.0 through 6.4.0, containsan Insertion of Sensitive... |
| GHSA-rrr9-pqfq-6p9g | CVE-2026-116419 | medium | Dell PowerScale InsightIQ, versions 6.3.0 through 6.4.0, containsan Insertion of Sensitive... |
| GHSA-576w-qcwc-9hgf | CVE-2026-59081 | high | Edito CMS deserializes JSON data without further validation. A user (even an administrator)... |
| GHSA-69rv-pv33-j84j | CVE-2026-116421 | medium | Dell PowerScale InsightIQ, Versions 6.3.0 through 6.4.0, contains an Insertion of Sensitive... |
| GHSA-57m9-wwvf-2cc5 | CVE-2026-116422 | medium | Dell PowerScale InsightIQ, versions 6.3.0 through 6.4.0, contains an Insertion of Sensitive... |
| GHSA-f776-3w9r-9mc5 | CVE-2026-59079 | high | Edito CMS restricts the ability to upload files via the UI to specific file types. However, an... |
| GHSA-vx67-947m-hrm5 | CVE-2026-59076 | medium | Edito CMS is vulnerable to Stored Cross-Site Scripting (XSS). Due to improper input validation,... |
| GHSA-xmv6-5m9x-r9m4 | CVE-2026-59074 | high | Edito CMS is vulnerable to improper cryptographic signature verification in the JWT refresh logic... |
| GHSA-39jf-vfwp-382c | CVE-2026-59075 | high | Edito CMS is vulnerable to Dynamic LINQ injection. Due to improper input validation, an... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Company #216 | N0n | BW | 2026-11-13T03:28:24.431546+00:00 |
| toyokiki-thailand.com | safepay | TH | 2026-11-12T22:02:03.406527+00:00 |
| benchmarkseniorliving.com | Curious Worm | US | 2026-11-12T19:55:02.258632+00:00 |
| Airblue | Aoqin | PK | 2026-11-12T19:51:09.760686+00:00 |
| Upper Web | Vexy Ransomware | BR | 2026-11-12T23:18:52.272049+00:00 |
| Osiiminppal | Vexy Ransomware | GL | 2026-11-12T23:19:13.283990+00:00 |
| Franc-Oil | Vexy Ransomware | NG | 2026-11-12T23:19:34.118381+00:00 |
| Ministry of Health Malaysia | Panzer | MY | 2026-11-12T17:58:17.861886+00:00 |
| cey-tech.com | krybit | CY | 2026-11-12T13:56:09.215118+00:00 |
| axiscades.com | incransom | IN | 2026-11-12T21:45:05.518295+00:00 |
| Promantra, Inc. | metaencryptor | US | 2026-11-12T12:18:48.149722+00:00 |
| ProLiant | Barracuda | US | 2026-11-12T07:22:39.834604+00:00 |
| The University of Texas at Arlington | qilin | US | 2026-11-12T06:50:40.355389+00:00 |
| York University | qilin | CA | 2026-11-12T06:49:59.843873+00:00 |
| Dep | medusalocker |  | 2026-11-11T22:01:37.377000+00:00 |
| Minor League Baseball | play | US | 2026-11-11T20:19:30.872886+00:00 |
| EiCOh | thegentlemen | JP | 2026-11-12T09:49:55.201851+00:00 |
| Vinson | thegentlemen | US | 2026-11-12T09:50:16.113409+00:00 |
| Company #213 | N0n | QA | 2026-11-11T18:00:30.349170+00:00 |
| Company #212 | N0n | ET | 2026-11-11T17:59:43.019766+00:00 |

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
| 45.148.10.141 | 10 |
| 45.148.10.152 | 10 |
| 45.148.10.151 | 9 |
| 45.148.10.157 | 9 |
| 125.130.102.172 | 9 |
| 167.94.146.62 | 9 |
| 193.32.162.15 | 9 |
| 193.47.62.69 | 9 |
| 3.129.187.38 | 8 |
| 3.130.168.2 | 8 |
| 35.210.54.75 | 8 |
| 35.210.125.227 | 8 |
| 35.210.166.45 | 8 |
| 64.62.197.92 | 8 |
| 66.132.159.106 | 8 |
| 66.132.172.179 | 8 |
| 66.132.195.74 | 8 |
| 66.132.195.98 | 8 |

### OpenPhish (live phishing URLs)
- http://airbnb.frngrgqb46.workers.dev/help/article/1320
- http://www.shopeemidyer.blogspot.com/
- http://www.layanan-pemenang59.blogspot.com/
- https://www.hadiahshopee3434.blogspot.com/
- https://atendimentopj.vercel.app/
- https://weilsfagosevic.okzk.com/ql34/02kja/signin.php
- http://www.btyytytttttttttttooouuiiuu.weebly.com/
- http://fpagesiterbx0nline.blogspot.com/
- http://shopee7547.blogspot.com/
- http://thrshopee111.blogspot.com/
- https://zarnel-privex-biz-holvik-santor-fdp1912.pages.dev/heartily_welcome?id=130566103479224&page_name=%D7%91%D7%99%D7%9E%D7%AA%20%D7%94%D7%A0%D7%95%D7%A2%D7%A8%20%D7%A8%D7%97%D7%95%D7%91%D7%95%D7%AA%20%D7%94%D7%A8%D7%A9%D7%9E%D7%99appeals%2Fsubmit-appeal-form%2Freturn%2F/
- http://hwcps29vwp-qnkxzqwe-4k7j8d-hwc613-mtvlj85nhr.pages.dev/
- https://bgrfd63mwp-hwcpsfyn-5i9j2g-bgr814-mtvlj85xlo-qnkxz49.pages.dev/
- http://hwcps87mnp-zlkytqwe-5i3j9d-hwc534-qnkxz72vlo.pages.dev/
- https://mtvlj92wkp-qnkxz728-5j8k1g-mtv364-hwcps64nlo-zlkyt38.pages.dev/
- http://mtvlj47vnp-zlkyt728-6i3j2g-mtv859-qnkxz91xdo.pages.dev/
- https://apple-crknjn.pages.dev/en/#/main
- https://bgrfd71nlo-mtvljplx-3k7j5g-bgr926-qnkxz48whr.pages.dev/
- https://sp29ct-tavun-biz-zemri-felko.pages.dev/
- https://sp12ct10-melvani-biz-zulreko.pages.dev/

### PhishStats (recent phishing/malicious URLs, scored)
_No data returned this run._

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| 9d0751a9eab469ff9a399a086ea2531b3c22dc30 | OffLoader C&C |
| 955d88cd421ad19859f6015a6ba3ea81e07b510c | PureLogsStealer C&C |
| 45972ca5b00612d1f51e51325f7662d60cdd7860 | WARDENStealer C&C |
| adc24b6b9445798ed026d417fe423b72aa290ebc | WARDENStealer C&C |
| 041028a7248ce181b5c083d17d31ef9443364b70 | WARDENStealer C&C |
| 0335d3d009c55ea6f49e57aeb54fbdb84e5def8e | FunStealer C&C |
| d313c92a2c0c535a7b60359f758b0032db60b99b | FunStealer C&C |
| 187d60de02b8184158547240aec75f31b8e93a27 | Vidar C&C |
| e637e68e3a9cdbe38b1c1c3ca411596797a0fd66 | Vidar C&C |
| c197cc60215219ca6d3781953e16ed060be8ed9a | ACRStealer C&C |
| 5961621983c7a3175a43032505457983fd0422f5 | ACRStealer C&C |
| 206699fd6ec97741dcdfe7d8ff2a066f1788a3f7 | ConnectWise C&C |
| 0f01c1b3f102f81f42772aed3893c2c9e0f48fb7 | ACRStealer C&C |
| 8850bca458b507876f7d39297d44bdb1634ba915 | PureLogsStealer C&C |
| 2d5618f557611ad38b3addcb60b3e7424006b79b | Vidar C&C |
| 7cf49de496a65869f8cf0c0b6a12c6fa5ab1c70f | Vidar C&C |
| d81ba5307163e9ab6460623840036fff7d856104 | Vidar C&C |
| 3c9cf61da071dea44abcb047a6290104588fb791 | Vidar C&C |
| dc26a2f39a41b1f6341aea0fb4cdbe57ff564917 | Vidar C&C |
| 2c4f45913d2f0f0869145d6eb5399d6e00a303ea | PureLogsStealer C&C |

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
- 1.10.221.161
- 1.13.79.149
- 1.14.140.218
- 1.164.158.192
- 1.175.131.108
- 1.179.172.45
- 1.180.246.242
- 1.183.196.195
- 1.2.226.61
- 1.201.146.109
- 1.203.149.250
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.226.82.243
- 1.234.21.73
- 1.234.27.159
- 1.234.53.65

### CINS Army (poorly-rated IPs)
- 1.12.229.231
- 1.169.41.52
- 1.193.56.135
- 1.193.63.143
- 1.208.108.242
- 1.214.29.155
- 1.224.163.125
- 1.24.16.11
- 1.24.16.117
- 1.24.16.118
- 1.24.16.121
- 1.24.16.124
- 1.24.16.128
- 1.24.16.133
- 1.24.16.140
- 1.24.16.142
- 1.24.16.163
- 1.24.16.164
- 1.24.16.165
- 1.24.16.168

## News (last ~36h, across outlets)
### The Hacker News
- [Hackers Exploit PHP2Shell Flaws in Check Point Gateways to Deploy TSGA Backdoor and Wipe ESXi Files](https://thehackernews.com/2026/11/hackers-exploit-php2shell-flaws-in.html)
- [Hackers Exploit N-central Flaws to Infect 21 Servers, Including 19 Running Hotfix 2](https://thehackernews.com/2026/11/hackers-exploit-n-central-flaws-to.html)
- [Webinar: See How Identity Blind Spots Put Your SOC at Risk and How to Close Them](https://thehackernews.com/2026/11/your-soc-sees-alert-but-does-it-know.html)
- [ThreatsDay: 59 Linux Kernel Bugs, Falcon Spyware, GSocket Backdoors + 17 More Stories](https://thehackernews.com/2026/11/threatsday-59-linux-kernel-bugs-falcon.html)
- [New SignDrop Zero-Day Exploit Turns Windows CLFS Security Feature Into SYSTEM Access](https://thehackernews.com/2026/11/new-signdrop-zero-day-exploit-turns.html)
- [Critical Red Hat Quay Flaw Lets Attackers Read and Overwrite All Private Container Images in a Registry](https://thehackernews.com/2026/11/critical-red-hat-quay-flaw-lets.html)
- [Citrix Patches 12 NetScaler and Secure Access Client Flaws, Including Authentication Bypass](https://thehackernews.com/2026/11/citrix-patches-12-netscaler-and-secure.html)
- [186 Fake AI Domains Redirect Users to ClickFix Lures, Browser Malware, and Search Hijackers](https://thehackernews.com/2026/11/186-fake-ai-domains-redirect-users-to.html)
- [SCKit Malware Turns ScreenConnect Support Sessions Into Potential MSP Attack Paths](https://thehackernews.com/2026/11/sckit-malware-targets-screenconnect.html)
- [Google Cloud Warns Three AMD Turin CPU Flaws Could Leak Data Across Processes in VMs](https://thehackernews.com/2026/11/google-cloud-warns-three-amd-turin-cpu.html)
- [New N-central Exploits Work Against Patched Servers, Enable Root RCE and Windows SYSTEM Access](https://thehackernews.com/2026/11/new-n-central-exploits-work-against.html)
- [Calendar Invites and Live Proxies: Inside a Google Session Hijacking Campaign](https://thehackernews.com/2026/11/calendar-invites-and-live-proxies.html)
- [PTC Patches Critical Windchill and FlexPLM Flaw That Could Enable Remote Code Execution](https://thehackernews.com/2026/11/ptc-patches-critical-windchill-and.html)
- [Critical Pre-Auth MongoDB Flaw (CVE-2026-118383) Can Crash Lagging Servers on Failover](https://thehackernews.com/2026/11/critical-pre-auth-mongodb-flaw-cve-2026.html)
- [Node.js Fixes 16 Flaws, Including HTTP/2 Bugs That Crash Servers and Leak Other Connections' Data](https://thehackernews.com/2026/11/nodejs-fixes-16-flaws-including-http2.html)

### BleepingComputer
- [Microsoft confirms Windows activation failures after November updates](https://www.bleepingcomputer.com/news/microsoft/microsoft-confirms-windows-activation-failures-after-november-updates/)
- [Police arrest 354 suspects in dark web cybercrime crackdown](https://www.bleepingcomputer.com/news/security/police-arrest-354-vendors-buyers-in-global-cybercrime-crackdown/)
- [New worm-like 'SCKit' malware targets MSPs in ScreenConnect attacks](https://www.bleepingcomputer.com/news/security/new-worm-like-sckit-malware-targets-msps-in-screenconnect-attacks/)
- [Hackers compromise 4,800 GitHub accounts to steal cloud credentials](https://www.bleepingcomputer.com/news/security/hackers-compromise-4-800-github-accounts-to-steal-cloud-credentials/)
- [Massive Microsoft 365 outage disrupts Outlook, Teams, Copilot worldwide](https://www.bleepingcomputer.com/news/microsoft/massive-microsoft-365-outage-disrupts-outlook-teams-copilot-worldwide/)
- [New N-able "4EverAble2Shell" zero-day exploited hours after PoC released](https://www.bleepingcomputer.com/news/security/new-n-able-4everable2shell-zero-day-exploited-hours-after-poc-released/)
- [Apache HTTP Server patches critical HTTP/2 remote code execution flaw](https://www.bleepingcomputer.com/news/security/apache-http-server-patches-critical-http-2-remote-code-execution-flaw/)
- [New Windows SignDrop zero-day gives hackers SYSTEM privileges](https://www.bleepingcomputer.com/news/security/new-windows-signdrop-zero-day-gives-hackers-system-privileges/)
- [Police dismantle Gootloader, CastleRAT, StealC malware infrastructure](https://www.bleepingcomputer.com/news/security/police-dismantles-gootloader-castlerat-stealc-malware-infrastructure/)
- [Your Endpoint Management Platform Could Be Your Biggest Security Risk](https://www.bleepingcomputer.com/news/security/your-endpoint-management-platform-could-be-your-biggest-security-risk/)
- [Apify rotates API tokens, prompts 2FA resets after breach](https://www.bleepingcomputer.com/news/security/apify-rotates-api-tokens-prompts-2fa-resets-after-breach/)
- [Microsoft: Recent Windows updates cause SQL Server performance issues](https://www.bleepingcomputer.com/news/microsoft/microsoft-recent-windows-updates-cause-sql-server-performance-issues/)
- [Microsoft confirms Windows security updates installation issues](https://www.bleepingcomputer.com/news/microsoft/microsoft-confirms-kb5132061-installation-issues-0x80070306-0x800f0989-0x800f0993-errors/)
- [Hackers plant GSocket on Linux servers for persistent access](https://www.bleepingcomputer.com/news/security/hackers-plant-gsocket-on-linux-servers-for-persistent-access/)
- [Baker Tilly notifies clients of data breach at third-party provider](https://www.bleepingcomputer.com/news/security/baker-tilly-notifies-clients-of-data-breach-at-third-party-provider/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [Getting Past the Post-Quantum Cryptography Discovery Phase](https://www.darkreading.com/cybersecurity-operations/getting-past-post-quantum-cryptography-discovery)
- [Cyber Experts Weigh In: How to Fight Artex &amp; AntiFox](https://www.darkreading.com/cybersecurity-operations/cyber-experts-fight-artex-antifox)
- [Extortion Group Luna Moth Flits Into Law Firms a Second Time](https://www.darkreading.com/data-privacy/extortion-luna-moth-law-firms-second-time)
- [Inside an AI Attack Against a US Retailer](https://www.darkreading.com/cyberattacks-data-breaches/inside-ai-attack-us-retailer)
- [Chinese AI Project Scouts Spies in Taiwan Chip Industry](https://www.darkreading.com/threat-intelligence/chinese-ai-project-scouts-spies-taiwan-chip-industry)
- [Japan Pushes Emergency Funding for Cybersecurity as AI-Assisted Breaches Rise](https://www.darkreading.com/cybersecurity-operations/japan-emergency-funding-cybersecurity-ai-assisted-breaches)

### SecurityWeek
- [Citrix Patches 10 Critical NetScaler Vulnerabilities](https://www.securityweek.com/citrix-patches-10-critical-netscaler-vulnerabilities/)
- [OpenAI Unveils Daybreak Red Team, Defense Factory Security Tools](https://www.securityweek.com/openai-unveils-daybreak-red-team-defense-factory-security-tools/)
- [Nightmare Eclipse Drops Windows Zero-Day Exploit ‘SignDrop’](https://www.securityweek.com/nightmare-eclipse-drops-windows-zero-day-exploit-signdrop/)
- [PHP2Shell Exploited in Destructive Check Point Gateway Attacks](https://www.securityweek.com/php2shell-exploited-in-destructive-check-point-gateway-attacks/)
- [Hackers Exploit New N-central Zero-Day Hours After PoC Publication](https://www.securityweek.com/hackers-exploit-new-n-central-zero-day-hours-after-poc-publication/)
- [FBI Says US Seized $1.2 Billion Worth of Cryptocurrency Stolen From Binance](https://www.securityweek.com/fbi-says-us-seized-1-2-billion-worth-of-cryptocurrency-stolen-from-binance/)
- [Microsoft 365 Outage Disrupts Outlook, Exchange Online and Teams](https://www.securityweek.com/microsoft-365-outage-disrupts-outlook-exchange-online-and-teams/)
- [Apache Patches Critical HTTP Server RCE Found by Anthropic, Google](https://www.securityweek.com/apache-patches-critical-http-server-rce-found-by-anthropic-google/)
- [Chrome, Firefox Updates Patch Over 180 Vulnerabilities](https://www.securityweek.com/chrome-firefox-updates-patch-180-vulnerabilities/)
- [Attacker Targets 60,000 GitHub Repositories in Credential Theft Campaign](https://www.securityweek.com/attacker-targets-60000-github-repositories-in-credential-theft-campaign/)

### The Record
- [Feds announce seizure of $1.2 billion from Binance theft; also takedown of ‘FaceStealer’ tools](https://therecord.media/stolen-binance-crypto-recovered-doj-facestealer-disrupted)
- [United to block customers from using AI agents, citing cyber threats](https://therecord.media/united-airlines-to-block-customers-using-ai-agents)
- [Shipping giant Maersk says recent cyber incident affected legacy system](https://therecord.media/shipping-giant-maersk-says-recent-incident-affected-legacy-system)
- [European authorities take down SteaIC malware servers for second time this year](https://therecord.media/european-authorities-take-down-stealic-malware-second-time)
- [ConnectWise investigates ScreenConnect breaches after reports of incidents at nearly 50 organizations](https://therecord.media/connectwise-screenconnect-breaches-third-party-tool)

### Infosecurity Magazine
- [Microsoft 365 Outage Set to Ramp up Security Risks to Organizations](https://www.infosecurity-magazine.com/news/microsoft-365-outage-security/)
- [AI Set to Revolutionize Ransomware Following “Stagnant” Few Years](https://www.infosecurity-magazine.com/news/ai-revolutionize-ransomware/)
- [Weak Passwords Expose SQL Servers to Cryptominer and Gh0st RAT](https://www.infosecurity-magazine.com/news/fortinet-sql-server-cryptominer/)
- [Hacked Asian Telcos Used to Intercept Taiwanese Calls and Texts](https://www.infosecurity-magazine.com/news/silentair-liminal-panda-telco/)
- [Lego Takes BrickLink Marketplace Offline After Detecting Unusual Activity](https://www.infosecurity-magazine.com/news/lego-takes-bricklink-marketplace/)
- [Security Teams Must Shift from Patching to Mitigation in the AI Era](https://www.infosecurity-magazine.com/news/shift-patching-mitigation-ai-era/)
- [NCSC Launches Cyber Adversary Testing to Boost Resilience](https://www.infosecurity-magazine.com/news/ncsc-cyber-adversary-testing-boost/)
- [Maersk Reveals Data Breach as Extortion Group Demands $5m](https://www.infosecurity-magazine.com/news/maersk-data-breach-extortion-group/)

### CyberScoop
- [US seizes North Korean hacking infrastructure, $1.2 billion in cryptocurrency stolen from Binance](https://cyberscoop.com/us-seizes-north-korea-hacking-infrastructure-binance/)
- [Rogue remote-access campaign spread through ScreenConnect add-on, researchers say](https://cyberscoop.com/connectwise-screenconnect-sckit-attack/)
- [Don’t put Section 702 spying law renewal in defense bill, groups urge Hill leaders](https://cyberscoop.com/section-702-reauthorization-ndaa-debate/)
- [International operation dismantles malware networks, exposes 6.4 million stolen credentials](https://cyberscoop.com/operation-endgame-malware-takedown-gootloader-stealc-europol/)

### Cisco Talos
- [Never be afraid to ask questions](https://blog.talosintelligence.com/never-be-afraid-to-ask-questions/)

### Unit 42 (Palo Alto)
- [Attackers Use Autonomous AI to Target Semiconductor, Defense and Civil Society Sectors](https://unit42.paloaltonetworks.com/cairn-framework-ai-autonomous-attacks/)
- [ARTEX and AI-Powered Red Teaming Tools: What Defenders Need to Know](https://unit42.paloaltonetworks.com/artex-and-ai-powered-red-teaming-tools/)

### Microsoft Security Blog
- [Trained to betray: How post-training supply chain attacks hijack coding agents](https://www.microsoft.com/en-us/security/blog/2026/11/12/trained-to-betray-how-post-training-supply-chain-attacks-hijack-coding-agents/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [Macfinger ClickFix campaign sends DownTheDRAIN infostealer for macOS, (Fri, Nov 13th)](https://isc.sans.edu/diary/rss/33518)
- [ISC Stormcast For Friday, November 13th, 2026 https://isc.sans.edu/podcastdetail/10178, (Fri, Nov 13th)](https://isc.sans.edu/diary/rss/33516)
- [Exploit Attempts for GPUStack Authentication Bypass (CVE-2026-102895), (Thu, Nov 12th)](https://isc.sans.edu/diary/rss/33514)
- [ISC Stormcast For Thursday, November 12th, 2026 https://isc.sans.edu/podcastdetail/10176, (Thu, Nov 12th)](https://isc.sans.edu/diary/rss/33512)

### Securelist (Kaspersky)
- [Ransomware at the hypervisor layer: how attackers use ESXi and vCenter features for malicious purposes](https://securelist.com/esxi-ransomware/121959/)
- [Transcending the trust boundaries: how a cloud pentest works](https://securelist.com/how-a-cloud-pentest-works/121921/)

### CrowdStrike Blog
- [CrowdStrike Named a Leader in the 2026 IDC MarketScape for Worldwide Augmented Identity Security Solutions](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-idc-marketscape-worldwide-augmented-identity-security-solutions/)
- [November 2026 Patch Tuesday: 1,252 CVEs Include One Zero-Day and 68 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-november-2026/)
- [How Adversaries Are Turning the Vulnerability Ecosystem Against Defenders](https://www.crowdstrike.com/en-us/blog/adversaries-turn-vulnerability-ecosystem-against-defenders/)
- [CrowdStrike Brings Enterprise Browser Security to the Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-brings-enterprise-browser-security-to-falcon-platform/)
- [CrowdStrike Extends the Agentic SOC to Detect and Stop Agent Insider Threats](https://www.crowdstrike.com/en-us/blog/crowdstrike-detects-and-stops-agent-insider-threats/)
- [CrowdStrike Introduces Agentic Adversary Emulation to Counter AI-Enabled Adversaries](https://www.crowdstrike.com/en-us/blog/crowdstrike-agentic-adversary-emulation-counters-ai-enabled-adversaries/)
- [New Falcon Cloud Security Innovations Secure the Cloud AI Runs On](https://www.crowdstrike.com/en-us/blog/falcon-cloud-security-innovations-secure-cloud-ai-runs-on/)
- [CrowdStrike Advances AI Security and Safety from Endpoint to Cloud](https://www.crowdstrike.com/en-us/blog/crowdstrike-advances-ai-security-and-safety-falcon-guardian/)
- [CrowdStrike to Acquire Fiddler to Deliver Falcon Observe for AI Agent Observability](https://www.crowdstrike.com/en-us/blog/crowdstrike-to-acquire-fiddler/)
- [Introducing AI Kill Switch: Taking Control When AI Agents Go Rogue](https://www.crowdstrike.com/en-us/blog/crowdstrike-introduces-ai-kill-switch/)

### FortiGuard Threat Signal
- [Apache HTTP/2 RCE](https://fortiguard.fortinet.com/threat-signal-report/6665)

## Fetch issues this run
- https://services.nvd.nist.gov/rest/json/cves/2.0?pubStartDate=2026-11-12T00:00:00.000&pubEndDate=2026-11-13T10:43:46.000&cvssV3Severity=CRITICAL -> HTTPSConnectionPool(host='services.nvd.nist.gov', port=443): Read timed out. (read timeout=25)
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/
- https://api.phishstats.info/api/phishing?_sort=-id&_size=30 -> 502 Server Error: Bad Gateway for url: https://api.phishstats.info/api/phishing?_sort=-id&_size=30

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal