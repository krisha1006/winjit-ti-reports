# Winjit Daily TI Digest — 2026-10-28

_Auto-generated. Window: last ~24h. Fetched at 2026-10-28T09:27:43.084736+00:00Z_

**At a glance:** 2 new KEV · 87 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-48356 | Adobe | Commerce and Magento | Adobe Commerce and Magento Unrestricted Upload of File with Dangerous Type Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-111497 | Google | Brotli | Google Brotli Unchecked Return Value Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-105781 | 10.0 | n/a | Adobe Campaign Classic (ACC) is affected by an Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability that could result in arbitrary code execution in the c |
| CVE-2026-104351 | 9.9 | n/a | Adobe Campaign Classic (ACC) is affected by an Improper Control of Generation of Code ('Code Injection') vulnerability that could result in arbitrary code execution in the context of the current user. |
| CVE-2026-104353 | 9.9 | n/a | Adobe Campaign Classic (ACC) is affected by an Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability that could result in arbitrary code execution in |
| CVE-2026-105489 | 9.9 | n/a | Adobe Campaign Classic (ACC) is affected by an Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability that could result in arbitrary code execution in the c |
| CVE-2026-105780 | 9.9 | n/a | Adobe Campaign Classic (ACC) is affected by an Incorrect Authorization vulnerability that could result in arbitrary code execution in the context of the current user. A low-privileged attacker could e |
| CVE-2026-117532 | 9.8 | n/a | REDAXO core from 5.3.0 before 5.21.4 contains an authentication bypass vulnerability in the structure/history plugin that allows unauthenticated attackers to forge temporary login tokens. Attackers ca |
| CVE-2026-117564 | 9.8 | n/a | nest-admin before 1.0.1 contains an authentication bypass vulnerability that allows unauthenticated attackers to forge administrator tokens by using a hardcoded JWT_SECRET committed in .env.production |
| CVE-2026-106013 | 9.8 | n/a | The Jupiter X Core plugin for WordPress is vulnerable to Authentication Bypass via the Twitter/X Social Login handler in all versions up to and including 4.61.0. The vulnerability exists within the ve |
| CVE-2026-84999 | 9.8 | n/a | The Pie Register Premium plugin for WordPress is vulnerable to Unrestricted File Type Upload in all versions up to, and including, 3.8.4.0 via the piereg_file_upload function. This is due to the plugi |
| CVE-2026-109218 | 9.8 | n/a | The Contact Manager plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 9.1.2 via the add_message function. This is due to an incomplete extension blackli |
| CVE-2026-48360 | 9.6 | n/a | Adobe Connect is affected by an Improper Control of Generation of Code ('Code Injection') vulnerability that could result in arbitrary code execution in the context of the current user. An attacker co |
| CVE-2026-104350 | 9.3 | n/a | Adobe Campaign Classic (ACC) is affected by a reflected Cross-Site Scripting (XSS) vulnerability. An attacker could exploit this vulnerability to inject malicious scripts into a web page, potentially  |
| CVE-2026-104354 | 9.1 | n/a | Adobe Campaign Classic (ACC) is affected by an Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability that could result in arbitrary code execution in the c |
| CVE-2026-105779 | 9.1 | n/a | Adobe Campaign Classic (ACC) is affected by an Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability that could result in a Security feature bypass. A low- |
| CVE-2026-112352 | 9.1 | n/a | Sunhillo SureLine before 9.1.5 contains an authentication bypass vulnerability that allows an unauthenticated remote attacker to impersonate any user with an active web session by forging a session co |
| CVE-2026-116811 | 8.8 | 0.5% | OpenPanel before 3.0.0 contains a sandbox escape vulnerability in the js-runtime validator that allows a project member to bypass the AST allowlist by aliasing the Function constructor. Attackers with |
| CVE-2026-116843 | 8.8 | 0.4% | Mistral Vibe before 3.0.3 contains a remote code execution vulnerability that allows attackers to run commands by defining git filter drivers in an untrusted repository's .git/config. When started wit |
| CVE-2026-75891 | 8.8 | 0.3% | The Kirki plugin for WordPress is vulnerable to Privilege Escalation via PHP Object Injection in all versions up to, and including, 6.2.5 via deserialization of untrusted input through the 'get-single |
| CVE-2026-117536 | 8.8 | n/a | REDAXO before 5.21.3 contains a cross-site request forgery vulnerability in the backend user administration page (users/users) because the CSRF token check only runs when the save parameter is set, wh |
| CVE-2026-107672 | 8.8 | n/a | A maliciously crafted .stack.json file can trigger a trusted Markdown injection vulnerability in Autodesk Fusion Post Processor Utility Extension. A malicious actor may exploit this vulnerability to e |
| CVE-2026-112351 | 8.8 | n/a | Sunhillo SureLine before 9.1.5 contains an OS command injection vulnerability in the networkDiag.cgi endpoint that allows an authenticated remote attacker with any web account to execute arbitrary com |
| CVE-2026-83831 | 8.8 | n/a | Double free in Microsoft Edge (Chromium-based) allows an unauthorized attacker to execute code over a network. |
| CVE-2026-85898 | 8.8 | n/a | Access of resource using incompatible type ('type confusion') in Microsoft Edge (Chromium-based) allows an unauthorized attacker to execute code over a network. |
| CVE-2014-125138 | 8.8 | n/a | C97net qEngine CMS through 6.0.0, Kemana Directory through 1.5.6, and Cart Engine through 3.0.0 contain an unrestricted file upload vulnerability in administrative image fields. Editor-role users can  |
| CVE-2015-20129 | 8.8 | n/a | CrushFTP before 7.3.0 contains a cross-site request forgery vulnerability that allows attackers to perform administrative actions because CSRF protection is disabled by default. Attackers can lure an  |
| CVE-2026-1928 | 8.8 | n/a | The Rank Math SEO – AI SEO Tools to Dominate SEO Rankings plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 1.0.276 via deserialization of untrusted inpu |
| CVE-2026-109384 | 8.8 | n/a | The The Innovative Form Builder – IvyForms plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 1.5.1 via the filterFiletypeAndExt function. This is due to |
| CVE-2026-111120 | 8.8 | n/a | The VikRentCar Car Rental Management System plugin for WordPress is vulnerable to Cross-Site Request Forgery in all versions up to, and including, 1.4.8. This is due to missing or incorrect nonce vali |
| CVE-2026-92797 | 8.8 | n/a | The MemberPress plugin for WordPress is vulnerable to Cross-Site Request Forgery in versions up to, and including, 1.14.1. This is due to a bypassable nonce verification check in the save_profile_fiel |
| CVE-2026-116819 | 8.5 | 0.3% | OpenPanel before 3.0.0 contains an information disclosure vulnerability that allows read-level project members to obtain plaintext integration secrets because the notification.rules query skips redact |
| CVE-2026-117602 | 8.4 | n/a | Electrum 4.6.0 before 4.7.2 contains an authorization bypass in the external plugin loader, which executes a plugin's __init__.py module when the plugin is marked enabled in the config file, without v |
| CVE-2026-112353 | 8.2 | n/a | GFI KerioConnect (Kerio Connect) before 10.0.8 Patch 2 contains a stored cross-site scripting vulnerability in the Webmail component that allows a remote attacker to run JavaScript in a victim's authe |
| CVE-2026-118375 | 8.1 | n/a | llama.cpp b8841 before b11865 contains an out-of-bounds write vulnerability in the ggml-rpc RDMA transport rdma_recv() function that allows unauthenticated peers to overflow the rpc-server stack. Atta |
| CVE-2026-116816 | 7.8 | 0.1% | llama.cpp b5899 before b10261 contains a heap out-of-bounds write vulnerability in llm_tokenizer_plamo2::build that allows attackers to corrupt heap memory via crafted GGUF models. Attackers can suppl |
| CVE-2026-117558 | 7.8 | n/a | The ai-sdlc plugin MCP server through 0.31.2 contains an OS command injection vulnerability that allows attackers to execute commands by supplying shell metacharacters in the repo argument. The unvali |
| CVE-2026-117559 | 7.8 | n/a | DroidMind through 0.4.0 contains a command injection vulnerability that allows MCP clients to bypass the shell command allowlist by using $(...) or backtick substitution. Attackers, including prompt-i |
| CVE-2026-117560 | 7.8 | n/a | ATXP Gemini CLI extension through 1.0.0 contains an OS command injection vulnerability in runAtxp() that allows attackers to execute shell commands through unsanitized MCP tool parameters. Attackers c |
| CVE-2026-117561 | 7.8 | n/a | Codefriar sf-mcp through 1.3.2 contains an OS command injection vulnerability that allows attackers to execute shell commands by supplying crafted Salesforce CLI tool flag values. Because escapeValue( |
| CVE-2026-117567 | 7.8 | n/a | esp-mcp through commit 28afddf contains an OS command injection vulnerability that allows attackers to run arbitrary commands by supplying shell metacharacters in MCP tool parameters. Attackers influe |
| CVE-2026-117569 | 7.8 | n/a | Kali-GPT through commit a608c74 contains an OS command injection vulnerability in execute_tool() in kali_gpt/tools/mcp_server.py that allows MCP clients to run commands via unsanitized scanner paramet |
| CVE-2026-117573 | 7.8 | n/a | hagent through commit 761eec6 contains an OS command injection vulnerability that allows MCP clients to execute shell commands by injecting metacharacters into the args parameter of the hagent_arduino |
| CVE-2026-113775 | 7.8 | n/a | A maliciously crafted dynamic library, when loaded from an arbitrary path through the TextCommands.LoadDll command exposed by the Autodesk Fusion API, can trigger an Exposed Dangerous Function vulnera |
| CVE-2026-48379 | 7.8 | n/a | Substance3D - Painter is affected by a Stack-based Buffer Overflow vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires u |
| CVE-2026-118378 | 7.8 | n/a | Tabularis before 0.28.0 contains an SQL injection vulnerability in its SQLite driver that allows MCP clients to execute stacked statements by supplying a crafted table_name to the describe_table tool. |
| CVE-2026-116871 | 7.5 | n/a | Semantic MediaWiki 3.0.0 before 7.3.1 contains an uncontrolled recursion vulnerability in LegacyParser::getSubqueryDescription() that processes nested query tokens before depth limits apply. Unauthent |
| CVE-2026-116872 | 7.5 | n/a | Semantic MediaWiki from 3.0.0 before 7.3.1 contains an algorithmic complexity vulnerability in TermParser::normalize_compact_form() that allows unauthenticated attackers to cause quadratic CPU consump |
| CVE-2026-116896 | 7.5 | n/a | REDAXO before 5.21.5 contains a missing authorization vulnerability in the backup addon export that accepts any database table, allowing non-admin users with the backup[export] permission to export re |
| CVE-2026-117540 | 7.5 | n/a | svg-sanitizer from 0.5.3 before 1.1.0 contains a denial of service vulnerability in Sanitizer::sanitize() that repeatedly rescans the whole input while stripping PHP tags. Unauthenticated attackers ca |
| CVE-2026-100164 | 7.5 | n/a | Observable response discrepancy vulnerability in Rolantis Information Technologies Tourism Industry and Trade Co. Ltd. Agentis allows Account Footprinting.

This issue affects Agentis: before 4.8. |
| CVE-2026-92546 | 7.5 | n/a | Authentication bypass by spoofing vulnerability in Keepnet Labs Cybersecurity Inc. Agentic AI / Agentic Ally allows Authentication Bypass.

This issue affects Agentic AI / Agentic Ally: before 0ef61f2 |
| CVE-2026-117553 | 7.5 | n/a | Umbraco CMS before 17.7.2 and 18.2.2 contains an authentication bypass vulnerability that allows unauthenticated attackers to register attacker-controlled OAuth redirect URIs by poisoning the Host hea |
| CVE-2026-117601 | 7.5 | n/a | Electrum before 4.8.3 fails to verify signatures of wallet-owned inputs in unconfirmed mempool transactions, allowing malicious servers to replace a just-broadcast transaction with a conflicting one.  |
| CVE-2026-117604 | 7.5 | n/a | Grav from 1.7.53.3 before 1.7.53.6 contains an authorization bypass in Debugger::isDebuggerRequestAuthorized() that allows unauthenticated visitors to read /__clockwork/ profiler data via a loopback R |
| CVE-2026-112350 | 7.5 | n/a | Sunhillo SureLine before 9.1.5 contains a path traversal vulnerability in the radarUpdater.cgi endpoint that allows unauthenticated remote attackers to read arbitrary files with root privileges due to |
| CVE-2026-112355 | 7.5 | n/a | The MembershipWorks plugin for WordPress before 6.17 contains an information disclosure vulnerability that allows unauthenticated attackers to access member-only content through the WordPress REST API |
| CVE-2026-62765 | 7.5 | n/a | Access of resource using incompatible type ('type confusion') in Microsoft Edge (Chromium-based) allows an unauthorized attacker to execute code over a network. |
| CVE-2026-118377 | 7.5 | n/a | mews/pos through 2.0.0 contains an insufficient verification of data authenticity vulnerability that allows unauthenticated attackers to forge payment results by submitting unverified callbacks. Garan |
| CVE-2026-111255 | 7.5 | n/a | The affiliate-toolkit – Multi-Network Affiliate & Amazon Product Display plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 3.9.2 via the upload_image fu |
| CVE-2026-116613 | 7.5 | n/a | The Animated Text Block plugin for WordPress is vulnerable to Sensitive Information Exposure in versions up to, and including, 1.2.6 via the 'animated-text' shortcode. This is due to the atb_shortcode |
| CVE-2026-15323 | 7.5 | n/a | The Product Designer for WooCommerce WordPress | Lumise plugin for WordPress is vulnerable to Directory Traversal in all versions up to, and including, 2.1.2 via the process_checkout function. This ma |
| CVE-2026-116623 | 7.3 | 0.4% | A vulnerability was detected in code-projects Simple Content Management System 1.0. Impacted is an unknown function of the file /web/admin/welcome.php of the component Admin Interface. The manipulatio |
| CVE-2026-116873 | 7.3 | n/a | Semantic MediaWiki from 7.3.0 before 7.3.1 contains a missing authorization vulnerability in the smwtask API module that allows unauthenticated attackers to run queued jobs and force store updates. At |
| CVE-2026-117511 | 7.3 | n/a | A vulnerability has been found in desmondmorris node-tesseract up to 0.2.7. Affected by this issue is the function process of the file lib/tesseract.js of the component Command Builder. Such manipulat |
| CVE-2026-104349 | 7.3 | n/a | Creative Cloud Desktop is affected by an Uncontrolled Search Path Element vulnerability that could result in arbitrary code execution in the context of the current user. A low-privileged attacker coul |
| CVE-2026-117512 | 7.3 | n/a | A vulnerability was found in oretnom23 php-travel-agency-system. This affects an unknown part of the file admin/employee_insert.php. Performing a manipulation of the argument employee photo results in |
| CVE-2026-117513 | 7.3 | n/a | A vulnerability was determined in oretnom23 php-travel-agency-system. This vulnerability affects unknown code of the file admin/customer_search.php of the component Admin Search Pages. Executing a man |
| CVE-2026-117514 | 7.3 | n/a | A vulnerability was identified in oretnom23 php-travel-agency-system. This issue affects some unknown processing of the file admin/customer_detail.php of the component Admin Record Pages. The manipula |
| CVE-2026-117515 | 7.3 | n/a | A security flaw has been discovered in oretnom23 php-travel-agency-system 4e28b8f84d72420373dd15c3ae32900beb7e0635. Impacted is an unknown function of the file traceapplication.php. The manipulation o |
| CVE-2026-117516 | 7.3 | n/a | A weakness has been identified in oretnom23 php-travel-agency-system. The affected element is an unknown function of the file contact_insert.php of the component Contact Form Handler. This manipulatio |
| CVE-2026-116808 | 7.2 | 0.4% | OpenPanel before 3.0.0 contains an sql injection vulnerability that allows authenticated users to read cross-tenant data by supplying a crafted property parameter to profile.values. Attackers can inje |
| CVE-2026-111820 | 7.2 | 0.2% | The Analytics Insights – Google Analytics Dashboard for WordPress plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the Page Title in all versions up to, and including, 6.3.12 due  |
| CVE-2026-109995 | 7.2 | n/a | The Advanced Views – Display Framework for Gutenberg & Elementor plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 3.9 |
| CVE-2013-20007 | 7.2 | n/a | Linksys WAG200G through 1.01.06 contains an OS command injection vulnerability that allows authenticated attackers to execute commands by injecting backtick-delimited input into the timer_interval par |
| CVE-2026-109999 | 7.2 | n/a | The AI Marketing Expert — AI Email Marketing, AI Content Generator, SEO Analyzer, AI Workflow Automation, Social Media & Ai Chatbot plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Sc |
| CVE-2026-111314 | 7.2 | n/a | The affiliate-toolkit – Multi-Network Affiliate & Amazon Product Display plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'atkp_product_producturl' parameter in all versions u |
| CVE-2026-117607 | 7.2 | n/a | Xerte Online Toolkits through 3.15.5 contains a remote code execution vulnerability that allows authenticated users with system permission to run PHP by importing a crafted language pack. Attackers ca |
| CVE-2026-97019 | 7.2 | n/a | The AMP for WP – Accelerated Mobile Pages plugin for WordPress is vulnerable to Stored Cross-Site Scripting via 'headline-*' Shortcode Attribute in all versions up to, and including, 1.1.17 due to ins |
| CVE-2026-109381 | 7.2 | n/a | The Mage Eventpress plugin for WordPress is vulnerable to privilege escalation in versions up to, and including, 5.7.8 This is due to the mep_grant_shop_manager_access() function hooking user_has_cap  |
| CVE-2026-110662 | 7.2 | n/a | The MxChat – AI Chatbot & Content Generation for WordPress plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via the 'feedback' parameter in all versions up to, and including |
| CVE-2026-111111 | 7.2 | n/a | The Prime Slider – Hero Slider, Carousel, WooCommerce & Post Slider Elementor Addons plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to |
| CVE-2026-116876 | 7.1 | n/a | Semantic MediaWiki from 2.5.0 before 7.3.1 contains an improper authorization vulnerability that allows ordinary editors to permanently protect pages by adding an Is edit protected annotation. When $s |
| CVE-2026-116880 | 7.1 | n/a | Semantic MediaWiki from 3.0.0 before 7.3.1 contains a cross-site request forgery vulnerability in Special:SMWAdmin because it overwrites the wpEditToken with a freshly generated valid token. Attackers |
| CVE-2026-102636 | 7.1 | n/a | A maliciously crafted HTML payload in a design name, when displayed after another user opens the manipulated design, can trigger a Stored Cross-site Scripting (XSS) vulnerability in the Autodesk Fusio |
| CVE-2026-102637 | 7.1 | n/a | A maliciously crafted HTML payload in the documentName parameter of a Fusion protocol URL, when the protocol URL is invoked by a user, can trigger a Reflected Cross-site Scripting (XSS) vulnerability  |
| CVE-2026-102638 | 7.1 | n/a | A maliciously crafted HTML payload in the description of an electronic library (.lbr) file, when displayed in the Library Manager after the library is imported, can trigger a Stored Cross-site Scripti |
| CVE-2026-117609 | 7.1 | n/a | rtl_433 through 25.12 contains a stack-based buffer overflow vulnerability in proflame2_mc() that allows nearby attackers to write past a 7-byte stack buffer by sending more than seven valid Mancheste |
| CVE-2026-117568 | 7.0 | n/a | mcp-ffmpeg through 1.0.5 contains an OS command injection vulnerability that allows attackers to run shell commands by supplying crafted videoPath or outputDir values to the resize-video, extract-audi |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-23m5-26m5-cmpf | CVE-2026-15323 | high | The Product Designer for WooCommerce WordPress | Lumise plugin for WordPress is vulnerable to... |
| GHSA-cr7x-4whh-v74w | CVE-2026-115281 | unknown | The Recipe Card Blocks Lite WordPress plugin before 3.6.4 does not sanitize and cast a block and... |
| GHSA-pp3q-4jh2-gvr2 | CVE-2026-113813 | unknown | The PayPlug for WooCommerce (Official) WordPress plugin before 3.1.1 does not perform any... |
| GHSA-j835-2vx3-j669 | CVE-2026-115255 | unknown | The WP Roster WordPress plugin before 2.35 does not perform any capability or nonce checks on one... |
| GHSA-66pc-wp83-p27g | CVE-2026-115224 | unknown | The Customer Engagement System  WordPress plugin before 2.0.2 does not safely build the SQL... |
| GHSA-4r9j-p4gw-x3hm | CVE-2026-115225 | unknown | The Customer Engagement System  WordPress plugin before 2.0.2 does not restrict access to its... |
| GHSA-x4hx-935f-mhv9 | CVE-2026-111031 | unknown | The Welcart e-Commerce WordPress plugin before 2.12.6 does not validate a user-supplied URL... |
| GHSA-p42q-6x3c-7prr | CVE-2026-110292 | unknown | The PayPlug for WooCommerce (Official) WordPress plugin before 3.1.1 does not verify that the... |
| GHSA-94r9-pgqm-7rh9 | CVE-2026-111961 | unknown | The Royal MCP  WordPress plugin before 1.5.10 does not perform an object-level permission check... |
| GHSA-mc48-45x9-jh54 | CVE-2026-110506 | unknown | The Page Builder by SiteOrigin WordPress plugin before 2.38.0 does not sanitize or escape a... |
| GHSA-8xjg-cmc9-35px | CVE-2026-111577 | unknown | The GoSMTP  WordPress plugin before 1.2.5 does not perform a settings-management authorization... |
| GHSA-cw3q-m3wh-782r | CVE-2026-110509 | unknown | The Essential Addons for Elementor  WordPress plugin before 6.8.7 does not restrict the post type... |
| GHSA-vj27-pxm6-rv65 | CVE-2026-113485 | unknown | The Media Library Assistant WordPress plugin before 3.42 does not consistently validate its CSRF... |
| GHSA-334j-cwwv-qmmh | CVE-2026-111960 | unknown | The Royal MCP  WordPress plugin before 1.5.10 does not perform object-level or post-type... |
| GHSA-v689-9j43-xq5j | CVE-2026-107100 | unknown | The Royal Addons for Elementor  WordPress plugin before 1.7.1070 does not verify that a requested... |
| GHSA-m4h7-mwp4-h59c | CVE-2026-110524 | unknown | The Copy Anything to Clipboard for WordPress  WordPress plugin before 5.5.5 does not sanitize and... |
| GHSA-8x4j-963r-3gx3 | CVE-2026-113488 | unknown | The GeoDirectory  WordPress plugin before 2.8.196 does not properly escape a post badge shortcode... |
| GHSA-w3vc-5h78-6ggp | CVE-2026-107097 | unknown | The Royal Addons for Elementor  WordPress plugin before 1.7.1070 does not perform any... |
| GHSA-r747-x6cp-8vgw | CVE-2026-111027 | unknown | The Welcart e-Commerce WordPress plugin before 2.12.6 does not properly sanitise and escape a... |
| GHSA-gv8j-xg52-fqpf | CVE-2026-106647 | unknown | The Royal Addons for Elementor  WordPress plugin before 1.7.1070 does not scope a contact form's... |
| GHSA-j4v8-4289-whj4 | CVE-2026-111021 | unknown | The افزونه پیامک ووکامرس | Persian WooCommerce SMS WordPress plugin before 7.3.2 does not... |
| GHSA-3rmh-w7g6-4jgh | CVE-2026-111032 | unknown | The Welcart e-Commerce WordPress plugin before 2.12.6 does not properly verify authorization... |
| GHSA-f65r-566x-cp6v | CVE-2026-110691 | unknown | The WPOrLogin  WordPress plugin before 3.1.0 does not perform a capability check or validate a... |
| GHSA-fmvc-698m-vpm5 | CVE-2026-109236 | medium | The Customer Email Verification for WooCommerce plugin for WordPress is vulnerable to... |
| GHSA-2m52-8826-2mqp | CVE-2026-110507 | unknown | The Page Builder by SiteOrigin WordPress plugin before 2.38.0 does not restrict the query... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Echo.com | Whitearmor | DE | 2026-10-28T02:10:02.050465+00:00 |
| wagyu.xyz unfairness | Whitearmor |  | 2026-10-28T02:10:42.771753+00:00 |
| Ryder | Whitearmor | US | 2026-10-28T01:09:16.806823+00:00 |
| Machelen (Belgium) | rhysida | BE | 2026-10-27T22:25:47.522037+00:00 |
| https://t.me/whitearmorxd | Whitearmor |  | 2026-10-27T23:18:42.871402+00:00 |
| TWICE SRL | emperador |  | 2026-10-27T21:22:05.818826+00:00 |
| Tailormade Logistics | play | DK | 2026-10-27T19:51:56.059899+00:00 |
| Coast 2 Coast | play | US | 2026-10-27T19:51:00.885314+00:00 |
| VPC Builders | play | US | 2026-10-27T19:50:08.859781+00:00 |
| Hygiena | play | US | 2026-10-27T18:27:11.459416+00:00 |
| Money Concepts Capital | play | US | 2026-10-27T18:26:34.660553+00:00 |
| MicroSearch | play |  | 2026-10-27T17:30:26.723125+00:00 |
| QLC | play | US | 2026-10-27T17:29:53.098004+00:00 |
| wagyu.xyz | Whitearmor |  | 2026-10-27T15:06:27.903414+00:00 |
| Horizon Eye Specialists & LASIK Center | Booba Project | US | 2026-10-27T13:51:17.574190+00:00 |
| GRUPO PETROIL | direwolf | MX | 2026-10-27T14:11:50.212201+00:00 |
| Hudson River Museum | Booba Project | US | 2026-10-27T13:51:38.611490+00:00 |
| BASS Medical Group | Booba Project | US | 2026-10-27T13:51:59.761206+00:00 |
| Kerckstede vzw | Booba Project | BE | 2026-10-27T13:52:20.590995+00:00 |
| RCOA- Regent Christian Online Academy | Booba Project | CA | 2026-10-27T13:52:40.373871+00:00 |

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
| 152.32.225.117 | 10 |
| 190.171.189.85 | 10 |
| 195.178.110.26 | 10 |
| 196.189.236.67 | 10 |
| 14.34.249.175 | 9 |
| 45.148.10.151 | 9 |
| 46.151.178.14 | 9 |
| 66.132.172.99 | 9 |
| 66.132.172.135 | 9 |
| 80.82.77.139 | 9 |
| 93.152.221.37 | 9 |
| 93.152.221.206 | 9 |
| 94.154.43.63 | 9 |
| 102.220.161.85 | 9 |
| 138.226.239.233 | 9 |
| 138.226.239.234 | 9 |
| 185.136.15.80 | 9 |
| 185.136.15.81 | 9 |
| 209.99.190.186 | 9 |

### OpenPhish (live phishing URLs)
- https://2017-facebook.blogspot.com/
- https://www.2017-facebook.blogspot.com/
- http://microfis-password-recovery.wasmer.app/
- https://account-security-notification.at-us.therelayservice.com/matpwp/#/main?type=LiveEmail&locale=en&token=GcRCorP2TGBfKv2HKw6ye5hKk-AeOhN5hv1a5vOAVJAltw8RwAu1LH_C8hfzhdDAr7PNqAb3gq1ZelCsdwLW_K65BmXwJZqKm3rnThroG684Z1Y0lSA2su8EQuoknGhQMRctAGRpTLi3jGt7aHzwv9fI84P7twmWwX_9g0k1ZkQUqLp-wmQX4DWHiUwK-2eu9NxCMnZAr08qeaTgvkGLGL09prt_sWL_OWh414PkKaYoEIVqWprPCXGCJfhkWF_x3mDRhqCvtcovxqrR0qj87M9D5ccJNFia0Pf7dnRpPDPD0zdB1x7U_3I9ZOZ9_CpF6WpGT8c_DWHAyRJf1mWT56C0kV_xsC8Bdvz7XWPuJI18z_CErG_mrqt4lUsssys8uBh5r8Zz4O_qL62uYTFmorsuJLb1Fph5Q3p0rIxGDvWJppoEg97pJpqk0_slipkNERwtjljswqECcl68-jYP2DFVj8iiubIwQA_ncOvj5OW2IJCWPQ76HHVeGBDMo41e0BbPdrAf6a7Zyh-bBGjJgWsx3s3KS-NKLcVkk8jCmprFgfC4OQHQYWxPyDWObV3xWXd03TKwX2LuCFWBL95ATvX6FXOHYvvLAfSDAhuwI-QZIVZvAyn3qq_gnKkvLJuEeSuiV-JLo67YjCx_g7OTVi4RHBLC_sentRtQulZ7CjCLennMi8g6svaWrSaxnO9t2fdjs3zolqUDYoJ_5-Wauwdfzuapy_xM5fqKYd86YeWO8F5wzaR_Wjpu4ScwX9xLiYnNSp3SCKGskGX3ZHRHkLaakd7rb2WlN4-3-noeUCs
- http://g4gx8.com/
- http://www.flhealthlicense.vercel.app/
- https://vortex-auth-proxy.pages.dev/category/safety
- https://vortex-auth-proxy.pages.dev/category/community
- http://www.robiox.com.tw/login?returnUrl=2076255335
- https://bitmartbit.com/m/
- https://instagrams.com.vn/b00dxs6bnu5?uc
- https://dgfcourier.de/Account/LogOn?ReturnUrl=%2f
- http://jasapickuptiktok.gratisongkir.web.id/k
- https://mining-itself-theaters-hewlett.trycloudflare.com/link/usaa2026/usaa2026D/usaa2026D/web/captcha.php
- https://u.to/nUnhIg?ssxnxx.com
- http://www.edytryyde.com/
- https://facebook-login-redirect.blogspot.com/
- http://www.xfinityy111.weebly.com/
- http://www.loginn-orangnews.vercel.app/
- http://loginn-orangnews.vercel.app/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AaSxoQyQ_ZSuXpSvue0UfKrOXnU6mQAuN0RcLmvWGTqSCzhKlOsPyDT7wQQH6ra2Rhdw1PE87iTB&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SSD97003oP0xYfPa_y2_MmFw6rvJtqmBhHHaZ2tqGrlr5Y899Z7oBdYS9OaZuejbkIS63g2ng&dsh=S1980082563%3A1793177962580611 |
| N/A | https://away.vk.ru/away.php?rh=c7b2d5cf-5734-4486-926b-68beccd1823a |
| N/A | https://away.vk.ru/away.php?rh=589363ea-f726-4f91-9c7f-0b6550ff8f2b |
| N/A | https://secure-xdomain-82343.w-group.shop/ |
| N/A | https://6a6fe68687.nxcli.io/payo/auth/log.php |
| N/A | https://www.ccpcusco.org/archivos |
| N/A | https://www.ccpcusco.org/archivos/ |
| N/A | https://www.troc.com/fr |
| N/A | http://away.vk.ru/away.php?rh=cbb44f27-23a9-4c03-93f3-c9c7740544da |
| N/A | https://away.vk.ru/away.php?rh=5bcb50bb-802c-4d0b-a0bf-c5d3fae780ca |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AWnogHfrcMjMJOA5-x4JjU2A_H62FL5Ipip8qUn0FfsVqhu1vrUBPxBl4JpnqCjPGKNrTfaShVnNJQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SSzyvfXGwvuKCcHO1k7EOClDpiuJ2e73MYdj0AaneDy5gftmMFb2pdwMvWmU0kfoa9W0oRLaw&dsh=S1814340082%3A1793176003819185 |
| N/A | https://away.vk.ru/away.php?rh=ff945ae9-7349-4599-924c-802a9003a528 |
| N/A | https://away.vk.ru/away.php?rh=342e348f-3279-4f98-94ac-acad9a736c30 |
| N/A | https://xml-v4.pushub.net/click?i=mrtZVPHkmTY_0 |
| N/A | http://49.51.43.12/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=ASKXGp36_CB8HzfrpuLLHTVjXxiUGDwO6Tj8yz4QrsaGyc3I4H4G7NxTTQJtpw0j07g9O5T5Tx4uyQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SQz4o_kw4oz0hY3sBp17O67x9nTEdg8uAdjyQzEi-GT1FqukH--DCx4i7Upi93vYDma0tVFkw&dsh=S-818642163%3A1793175744969117 |
| N/A | https://away.vk.ru/away.php?rh=6a5d3f39-df81-4d6f-9cc0-2f480cf2a6ee |
| N/A | https://away.vk.ru/away.php?rh=356c83d3-dbb4-4849-8587-15bb2cb0cd89 |
| N/A | https://ersfilter-my.sharepoint.com/personal/nradonich_ersfilter_com/_layouts/15/doc.aspx?guestaccesstoken=t6T%2FHN1dKbYHlYX%2BeIMbaZufA43rrGZ6%2FaAAewNocDI%3D&docid=1_18168db23429e45f29fdf2e7be120efc4&wdFormId=%7BB9970F62-44C3-4D09-9929-6E1EB652DA57%7D&action=formsubmit&CID=bf196fdf-f2a4-4d77-be42-fcb946a846b3 |
| N/A | https://away.vk.ru/away.php?rh=762dd488-9dfb-4df8-89df-b950463b537e |
| N/A | https://www.eyeearhospital.com/bnd/ |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| b3419f377a0765d386af3f3a61bede653db873f7 | ArvionRAT C&C |
| 891b265025da1fe909b4792dfe0f3df462694bef | ConnectWise C&C |
| d8d068667512bafa6720747c23266764f70638a9 | ConnectWise C&C |
| f7c6d6e9767952571df5b177956e71f6e664711d | ConnectWise C&C |
| 9c1e389a6cea4a7eb32b2e1d89acedfd5b7a52f9 | ConnectWise C&C |
| 8a6380c8c1857ae5e6c215fc9593e152d2350c87 | ConnectWise C&C |
| 33f97c9513d957c407b1fb86aee23c20f9145680 | ConnectWise C&C |
| b850658af6eba65201db37e5e0491bc33b8bba8e | ConnectWise C&C |
| d7ab2ab9aa49099722347f16ecdebd91097d1aa0 | ConnectWise C&C |
| bea642be1361616c46c371216f52414d41ad58d7 | ConnectWise C&C |
| 6ea4447a4cff2bc512fc4d7ccc412111d64f8af8 | ConnectWise C&C |
| 4f77e6691513a2677569524e2331ab29238f07b2 | Malware C&C |
| e5eefcb70e310314c73361c957aa2a1f970fbd65 | PureRAT C&C |
| a54ad395d86f7e564d4c23c150ce28359538d64d | OffLoader C&C |
| 9aa781171a4918d3e4069dd810fb846797806db7 | PureLogsStealer C&C |
| ba95841b4146ce72ee532c53be1651bc97d73388 | OffLoader C&C |
| 109f3ba748ac0f3a080d01039cfd0de392b83b30 | PureRAT C&C |
| 4500afbacb26f57137b330589027e0560957267f | PureLogsStealer C&C |
| 4d319fb9760ff822c5079e3ddbda8304de89f565 | Vidar C&C |
| 4269a895d221ce05070c61672e42fc549739137e | Vidar C&C |

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
- 1.10.242.248
- 1.117.72.220
- 1.12.64.109
- 1.14.105.177
- 1.14.149.30
- 1.14.192.95
- 1.14.240.247
- 1.144.106.82
- 1.147.62.60
- 1.159.54.33
- 1.162.208.86
- 1.179.238.84
- 1.187.165.30
- 1.187.213.56
- 1.187.238.219
- 1.192.80.17
- 1.2.252.192
- 1.20.243.85
- 1.212.225.99
- 1.214.214.114

### CINS Army (poorly-rated IPs)
- 1.12.229.231
- 1.214.29.155
- 1.223.11.69
- 1.236.254.202
- 1.24.16.121
- 1.24.16.134
- 1.24.16.135
- 1.24.16.17
- 1.24.16.191
- 1.24.16.44
- 1.24.16.67
- 1.24.16.98
- 1.24.16.99
- 1.30.28.182
- 1.30.80.145
- 1.31.32.6
- 1.32.57.245
- 1.58.108.110
- 1.64.197.229
- 1.83.125.60

## News (last ~36h, across outlets)
### The Hacker News
- [Anthropic's Unreleased AI Model Chains Flaws Into Working Chrome, Safari, Windows and Linux Exploits](https://thehackernews.com/2026/10/anthropics-unreleased-ai-model-chains.html)
- [FBI Seizes Virtualine Domain Over Alleged Criminal Hosting and Bitcoin Money Laundering](https://thehackernews.com/2026/10/fbi-seizes-virtualine-domain-over.html)
- [Japan's GMO Offers $1 Million Bounty to Catch Hackers Behind FX Trading Cloud Breach](https://thehackernews.com/2026/10/japans-gmo-offers-1-million-bounty-to.html)
- [Tailscale Patches SSH Flaws That Could Let Hacked Devices Gain Root Access on Other Servers](https://thehackernews.com/2026/10/tailscale-patches-ssh-flaws-that-could.html)
- [ShinyHunters-Exploited Oracle PeopleSoft Zero-Day Turns Out to Be Three Chained Flaws](https://thehackernews.com/2026/10/shinyhunters-exploited-oracle.html)
- [Adobe Commerce PolyShell Attacks Breach Hundreds of Stores as Brotli Exploit Traffic Emerges](https://thehackernews.com/2026/10/adobe-commerce-polyshell-attacks-breach.html)
- [CyberStrikeAI Uses 44 AI Agents to Automate Hacking Operations Against Japan Targets](https://thehackernews.com/2026/10/cyberstrikeai-uses-44-ai-agents-to.html)
- [GoAhead TLS Flaws Allow Revoked Client Certificates and Enable Session Decryption](https://thehackernews.com/2026/10/goahead-tls-flaws-allow-revoked-client.html)
- [Apple Backports Fix for Exploited CoreGraphics Flaw to Older iPhones and iPads](https://thehackernews.com/2026/10/apple-backports-fix-for-exploited.html)
- [Microsoft Authenticator Flaw Let Permissionless Android Apps Steal Work Account Tokens](https://thehackernews.com/2026/10/microsoft-authenticator-flaw-let.html)
- [Keystone to Destroy 18,835 Hardware Wallets After Hackers Steal Device Verification Key](https://thehackernews.com/2026/10/keystone-to-destroy-18835-hardware.html)
- [AI-Generated Fake Login Pages Are Making Account Takeovers Easier](https://thehackernews.com/2026/10/ai-generated-fake-login-pages-are.html)
- [Lazarus Abuses South Korean Security Software to Deploy Malware Using Post-Quantum Encryption](https://thehackernews.com/2026/10/lazarus-abuses-south-korean-security.html)
- [Australia Gets Into Amadey Malware Backend, Cuts Off Access to 180,000 Infected Computers](https://thehackernews.com/2026/10/australia-gets-into-amadey-malware.html)
- [OpenAI Compaction Flaw Let Researchers Bypass Hidden Reasoning Protections](https://thehackernews.com/2026/10/openai-compaction-flaw-let-researchers.html)

### BleepingComputer
- [Japan's GMO urges customers to shut down PCs amid ransomware threat](https://www.bleepingcomputer.com/news/security/japans-gmo-urges-customers-to-shut-down-pcs-amid-ransomware-threat/)
- [OpenAI's GPT-6.1 Terra is safer overall, but shows more destructive-action flags in tests](https://www.bleepingcomputer.com/news/artificial-intelligence/openais-gpt-61-terra-is-safer-overall-but-shows-more-destructive-action-flags-in-tests/)
- [UNM Health ransomware attack disrupts patient care, surgeries](https://www.bleepingcomputer.com/news/security/unm-health-ransomware-attack-disrupts-patient-care-surgeries/)
- [Hackers hijack Convertr analytics script to steal payment card data](https://www.bleepingcomputer.com/news/security/hackers-hijack-convertr-analytics-script-to-steal-payment-card-data/)
- [Microsoft releases Windows OOB updates to distrust eMudhra certificates](https://www.bleepingcomputer.com/news/microsoft/microsoft-releases-windows-oob-updates-to-distrust-emudhra-certificates/)
- [Warp discloses breach exposing AI agent logs, user telemetry data](https://www.bleepingcomputer.com/news/security/warp-discloses-breach-exposing-ai-agent-logs-user-telemetry-data/)
- [Tailscale warns of SSH flaws allowing root privilege escalation](https://www.bleepingcomputer.com/news/security/tailscale-warns-of-serious-ssh-flaws-allowing-root-privilege-escalation/)
- [The Huntress Tragic Quadrant: Ranking Threats Hitting Businesses Hardest](https://www.bleepingcomputer.com/news/security/the-huntress-tragic-quadrant-ranking-threats-hitting-businesses-hardest/)
- [Apple backports CoreGraphics zero-day patches to older iPhones](https://www.bleepingcomputer.com/news/apple/apple-backports-coregraphics-zero-day-patches-to-older-iphones/)
- [Energy giant ENGIE discloses data breach affecting customers](https://www.bleepingcomputer.com/news/security/energy-giant-engie-discloses-data-breach-affecting-customers/)
- [CISA confirms PHP2Shell vulnerabilities now exploited in attacks](https://www.bleepingcomputer.com/news/security/cisa-confirms-php2shell-vulnerabilities-now-exploited-in-attacks/)
- [University of Copenhagen data breach exposes data of 525,000 people](https://www.bleepingcomputer.com/news/security/university-of-copenhagen-data-breach-exposes-data-of-525-000-people/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [Third Serengeti Sweep Tops 1,400 Arrests as Investigations Mature](https://www.darkreading.com/cybersecurity-operations/third-serengeti-sweep-1400-arrests-investigations-mature)
- [3 Frameworks to Protect CISOs &amp; Orgs Against AI Liability](https://www.darkreading.com/cyber-risk/3-frameworks-cisos-ai-liability)
- [External Teams Chats Anchor 15-Minute Malware Delivery](https://www.darkreading.com/cloud-security/email-bombing-external-teams-chats-repeatable-access-path)
- [SBOMs Alone Can't Reveal the Scope of a Supply Chain Attack](https://www.darkreading.com/cyber-risk/sboms-alone-scope-supply-chain-attack)
- [Beware the Slasher: AI Could Kill Off Cybersecurity Pros' Skills](https://www.darkreading.com/cybersecurity-operations/ai-kill-off-cybersecurity-pros-skills)
- ['Aokigahara' Stealer Targets 'Developer Keyrings' &amp; AI Assistants](https://www.darkreading.com/endpoint-security/aokigahara-stealer-developer-keyrings-ai-assistants)
- [So Many AI Security Benchmarks, But None Tell the Whole Story](https://www.darkreading.com/cybersecurity-analytics/benchmarking-security-of-ai-models-poses-challenges)
- [Risks &amp; Rewards: How AI Is Redefining the CISO's Role](https://www.darkreading.com/cybersecurity-careers/risks-rewards-ai-redefining-ciso-role)

### SecurityWeek
- [Hackers Start Probing Fresh Oracle EBS Vulnerability](https://www.securityweek.com/hackers-start-probing-fresh-oracle-ebs-vulnerability/)
- [CISA Warns of Node2Shell Exploitation as Honeypots Log Attack Attempts](https://www.securityweek.com/cisa-warns-of-node2shell-exploitation-as-honeypots-log-attack-attempts/)
- [Tailscale Rushes Patches After Uncoordinated Disclosure of ‘Tailworm’ Flaws](https://www.securityweek.com/tailscale-rushes-patches-after-uncoordinated-disclosure-of-tailworm-flaws/)
- [Vendor Key Leak Puts Data of 238,000 Denver Health Plan Members at Risk](https://www.securityweek.com/vendor-key-leak-puts-data-of-238000-denver-health-plan-members-at-risk/)
- [HPE Patches Dozens of Critical Flaws in Networking Products](https://www.securityweek.com/hpe-patches-dozens-of-critical-flaws-in-networking-products/)
- [Unexplained DreamHost Incident Prompts Email, FTP Password Resets](https://www.securityweek.com/unexplained-dreamhost-incident-prompts-email-ftp-password-resets/)
- [iOS, macOS 27.2 Patch 286 Bugs; Fix for Exploited Flaw Backported to iOS 18](https://www.securityweek.com/ios-macos-27-2-patch-286-bugs-fix-for-exploited-flaw-backported-to-ios-18/)
- [Risks Spelled Out for Anthropic Investors Include Possible Harms From Runaway AI](https://www.securityweek.com/risks-spelled-out-for-anthropic-investors-include-possible-harms-from-runaway-ai/)
- [This is Fine: What NetScaler Zero-Days Tell Us About the New Normal](https://www.securityweek.com/this-is-fine-what-netscaler-zero-days-tell-us-about-the-new-normal/)
- [Dead Popcorn Time Updater Put Millions of Computers at Risk of Takeover](https://www.securityweek.com/dead-popcorn-time-updater-put-millions-of-computers-at-risk-of-takeover/)

### The Record
- [Nefilim, Hive ransomware operator given five-year-plus sentence after guilty plea](https://therecord.media/nefilim-hive-ransomware-operator-70-months-prison)
- [US indicts Malaysian national after Madagascar scam operation uncovered](https://therecord.media/malaysian-national-indicted-after-scam-centers-raid-madagascar)
- [Hackers repeatedly breached suppliers holding UK police data, watchdog finds](https://therecord.media/uk-police-data-breached-from-suppliers-watchdog-report)
- [University of New Mexico hospital diverts ambulances after cyberattack](https://therecord.media/university-of-new-mexico-hospital-diverts-cyber-incident)
- [Malicious apps prey on Russians’ anxiety about fuel prices, drone strikes](https://therecord.media/malicious-apps-russian-anxiety-gas-prices-drone-strikes)

### Infosecurity Magazine
_No new items / feed unavailable this run._

### CyberScoop
- [Before you file that AI bug report, OpenAI has some advice](https://cyberscoop.com/openai-ai-generated-bug-reports/)
- [All the security risks Anthropic is worried about before its IPO](https://cyberscoop.com/anthropic-ipo-filing-cybersecurity-risks/)
- [Prolific Hive and Nefilim ransomware affiliate sentenced to 70 months in prison](https://cyberscoop.com/nefilim-hive-ransomware-affiliate-artem-stryzhak-sentenced/)
- [National cyber director rolls out latest pilot in South Carolina, this time for rural hospitals](https://cyberscoop.com/oncd-rural-hospital-cybersecurity-pilot-project-lifeline-250/)
- [What happens when security tools go dark before the ransomware](https://cyberscoop.com/warlock-ransomware-storm-2603-sharepoint-attacks-op-ed/)
- [Experts temper emergency-level alarms over critical Brotli defect](https://cyberscoop.com/brotli-critical-vulnerability-decompression-library-node2shell-broccoli2shell/)

### Cisco Talos
- [From federal SOCs to Talos: Ryan Fetterman on practical security research](https://blog.talosintelligence.com/from-federal-socs-to-talos-ryan-fetterman-on-practical-security-research/)

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Wednesday, October 28th, 2026 https://isc.sans.edu/podcastdetail/10154, (Wed, Oct 28th)](https://isc.sans.edu/diary/rss/33464)
- [ISC Stormcast For Tuesday, October 27th, 2026 https://isc.sans.edu/podcastdetail/10152, (Tue, Oct 27th)](https://isc.sans.edu/diary/rss/33462)
- [Apple Patches for October 2026, (Mon, Oct 26th)](https://isc.sans.edu/diary/rss/33458)

### Securelist (Kaspersky)
- [An insecure neighbor: how a vulnerability chain led to an isolation bypass in cloud infrastructure](https://securelist.com/cloud-infrastructure-isolation-bypass/121609/)

### CrowdStrike Blog
- [Why Organizations Secure AI Agents with Falcon Guardian](https://www.crowdstrike.com/en-us/blog/why-organizations-secure-ai-agents-with-falcon-guardian/)
- [Obstacles to Weaponizing PHP2Shell Likely Constrain Immediate Widespread Exploitation](https://www.crowdstrike.com/en-us/blog/obstacles-to-weaponizing-php2shell-likely-constrain-exploitation/)
- [CrowdStrike Protects Customers from Threats Delivered via PHP2Shell](https://www.crowdstrike.com/en-us/blog/crowdstrike-protects-customers-from-php-rce-zero-days/)
- [CrowdStrike Uncovers New Agentic AI Campaigns](https://www.crowdstrike.com/en-us/blog/crowdstrike-uncovers-new-agentic-ai-campaigns/)
- [CrowdStrike Achieves NCSC CIR Enhanced Level Assurance](https://www.crowdstrike.com/en-us/blog/crowdstrike-achieves-uk-ncsc-cir-enhanced-level-assurance/)
- [U.S. Government Disrupts FAMOUS CHOLLIMA Operation with CrowdStrike Assistance](https://www.crowdstrike.com/en-us/blog/fbi-disrupts-famous-chollima-operation-with-crowdstrike-assistance/)
- [October 2026 Patch Tuesday: 1,413 CVEs Include Three Zero-Days and 75 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-october-2026/)
- [CrowdStrike and Anthropic Give Critical Infrastructure Defenders the AI Advantage](https://www.crowdstrike.com/en-us/blog/crowdstrike-anthropic-critical-infrastructure-defense-program/)
- [Solving the Continuous Authorization Conundrum](https://www.crowdstrike.com/en-us/blog/solving-the-continuous-authorization-conundrum/)
- [Unknown Threat Actor Uses AI-Driven ARTEX to Target South Korean Finance](https://www.crowdstrike.com/en-us/blog/unknown-threat-actor-uses-artex-to-target-south-korean-finance/)

### FortiGuard Threat Signal
- [Node.js Brotli Remote Code Execution (Node2Shell)](https://fortiguard.fortinet.com/threat-signal-report/6556)
- [PHP2Shell Remote Code Execution Vulnerabilities](https://fortiguard.fortinet.com/threat-signal-report/6551)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/
- Infosecurity Magazine RSS -> malformed/unparseable feed (<urlopen error [SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: unable to get local issuer certificate (_ssl.c:1010)>)

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal