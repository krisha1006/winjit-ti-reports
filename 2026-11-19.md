# Winjit Daily TI Digest — 2026-11-19

_Auto-generated. Window: last ~24h. Fetched at 2026-11-19T11:20:34.560152+00:00Z_

**At a glance:** 4 new KEV · 88 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2024-10441 | Synology | DiskStation Manager (DSM) | Synology DiskStation Manager (DSM) Improper Encoding or Escaping of Output Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-40217 | BerriAI | LiteLLM | BerriAI LiteLLM Unprotected Alternate Channel Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-90817 | Vanderbilt University | Research Electronic Data Capture (REDCap) | Vanderbilt University Research Electronic Data Capture (REDCap) Code Injection Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-90436 | Apache | Axis | Apache Axis Unsafe Reflection Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-130778 | 10.0 | n/a | Incus before 7.6.0 contains an authentication bypass vulnerability that allows remote attackers to authenticate as any trusted certificate by appending its public certificate to their presented TLS cl |
| CVE-2026-130759 | 9.9 | n/a | Fleet from 4.71.0 before 4.88.2 contains an authentication bypass vulnerability in the SAML SSO callback that looks up sessions using unvalidated client-supplied identifiers. Users able to run live qu |
| CVE-2026-130771 | 9.9 | n/a | Incus before 7.6.0 fails to reject special files, hard links, or symlinks in backup or image metadata, allowing restricted project users to read or overwrite host files. Attackers can import crafted b |
| CVE-2026-130780 | 9.9 | n/a | Incus before 7.6.0 contains a path traversal vulnerability that allows malicious migration peers to write outside intended directories by supplying unvalidated dependent volume and snapshot names in t |
| CVE-2026-130784 | 9.9 | n/a | Incus before 7.6.0 contains an authorization bypass vulnerability that allows restricted clients to create and access default project resources by exploiting entitlement checks against the requested p |
| CVE-2026-130786 | 9.9 | n/a | Incus before 7.6.0 contains a configuration injection vulnerability that allows users who can launch instances from controlled images to inject LXC directives by embedding line breaks in OCI config.js |
| CVE-2026-132139 | 9.9 | n/a | A weakness has been identified in DrayTek Vigor2960 up to 1.5.1.6. Affected is the function setSWMProfile of the file /cgi-bin/mainfunction.cgi. Executing a manipulation of the argument filename can l |
| CVE-2026-132141 | 9.9 | n/a | A vulnerability was detected in DrayTek Vigor2960 up to 1.5.1.6. Affected by this issue is the function json_load_lock of the file /cgi-bin/mainfunction.cgi of the component Jsonstatus. The manipulati |
| CVE-2026-132143 | 9.9 | n/a | A vulnerability has been found in DrayTek Vigor2960 up to 1.5.1.6. This vulnerability affects the function doWebBackup of the file /cgi-bin/mainfunction.cgi of the component Backup Handler. Such manip |
| CVE-2026-130675 | 9.8 | n/a | Craft CMS from 5.0.0 before 5.11.4 contains a remote code execution vulnerability in ImageTransforms::normalizeTransform() that allows attackers to instantiate arbitrary classes by supplying class:nul |
| CVE-2026-130733 | 9.8 | n/a | Grav from 2.0.0 before 2.2.18 contains an authorization bypass vulnerability that allows publishers to overwrite pages their per-page permissions deny by abusing FolderStorage key delimiter collisions |
| CVE-2012-20007 | 9.8 | n/a | ThinkPHP 2.0 through 2.2 and 3.0 Lite mode contains an eval injection vulnerability in the Dispatcher PATH_INFO parsing, which uses preg_replace with the /e modifier and a double-quoted replacement. U |
| CVE-2018-25443 | 9.8 | n/a | Baidu UEditor 1.4.0 through 1.4.3.3 contains an unrestricted file upload vulnerability in the catchimage action of /ueditor/net/controller.ashx that only validates the Content-Type header. Unauthentic |
| CVE-2026-130754 | 9.8 | n/a | All versions of LaraDashboard contain an authentication bypass in SocialAuthService::findOrCreateUser(), which links a social login to an existing account by email without checking that the OAuth prov |
| CVE-2026-130756 | 9.8 | n/a | pnpm exe before 10.34.8 embeds an outdated Node.js runtime that still trusts compromised eMudhra intermediate CA certificates during registry TLS connections. Network attackers holding a recovered int |
| CVE-2026-14492 | 9.8 | n/a | The WP Duplicate – WordPress Migration Plugin plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 1.1.11 via the save_single_batch_file function. This is  |
| CVE-2026-130779 | 9.6 | n/a | Incus before 7.6.0 contains a path traversal vulnerability that allows users permitted to import custom volumes to store unvalidated snapshot names from the backup index configuration section. Attacke |
| CVE-2026-130783 | 9.6 | n/a | Incus before 7.6.0 exposes certificate and cluster join token secrets through the default project event stream and skips authorization when cancelling operations without associated permissions. Restri |
| CVE-2026-132142 | 9.1 | n/a | A flaw has been found in DrayTek Vigor2960 up to 1.5.1.6. This affects the function dataflowstatus of the file /cgi-bin/mainfunction.cgi of the component CGI Process. This manipulation of the argument |
| CVE-2026-132622 | 9.1 | n/a | A vulnerability was found in GearUP Hyperev up to 20261020. This impacts the function get_wlan_sitesurvey of the file ld/utils.lua of the component WLAN Site Survey. Performing a manipulation of the a |
| CVE-2026-130679 | 9.0 | n/a | SiYuan before 3.8.10 contains a stored cross-site scripting vulnerability in genAVValueHTML() that allows attackers who can store Attribute View asset values to inject script through an unescaped imag |
| CVE-2026-131851 | 8.8 | 0.6% | ILIAS before 9.25, 10.13, and 11.6 contains an SQL injection vulnerability in ilPRGAssignmentFilter::toConditions() that allows authenticated users to inject SQL through the StudyProgramme members lis |
| CVE-2026-130709 | 8.8 | n/a | NocoDB before 2026.09.0 contains a server-side template injection vulnerability that allows authenticated Creator or Owner users to execute JavaScript by abusing Handlebars webhook helpers. Attackers  |
| CVE-2026-130741 | 8.8 | n/a | Grav from 2.0.0 before 2.2.18 contains a Twig sandbox bypass vulnerability that allows publishers to read any server file by abusing allowlisted array_key_value() and page accessor setters such as fil |
| CVE-2026-130742 | 8.8 | n/a | Grav 2.0.0 before 2.2.18 resolves Flex sort and filter field names by first calling them as public methods, so a field named delete invokes FlexObject::delete() without any permission check. Authentic |
| CVE-2012-20008 | 8.8 | n/a | openSIS 5.1 before 9.0 contains a local file inclusion vulnerability that allows authenticated users to include arbitrary files through the modname parameter of ajax.php. Attackers can prefix a payloa |
| CVE-2026-130774 | 8.8 | n/a | Incus before 7.6.0 contains a privilege escalation vulnerability: rebuilding a never-started unprivileged container makes it boot without a user namespace. Root processes inside the container run as h |
| CVE-2026-130730 | 8.7 | n/a | NocoDB before 2026.10.1 contains an authentication bypass vulnerability that allows OAuth token holders to act as full sessions because OAuth access tokens are signed with the instance JWT secret. Att |
| CVE-2026-130770 | 8.4 | n/a | Incus before 7.6.0 creates the NBD servers used for virtual machine migration and disk export on abstract unix sockets, which have no permission checks and whose names are visible in /proc/net/unix. A |
| CVE-2026-130701 | 8.3 | n/a | NocoDB before 2026.10.1 contains an SQL injection vulnerability because select-field option titles are embedded into MySQL or MariaDB enum/set column definitions with only single-quote doubling, leavi |
| CVE-2018-25442 | 8.3 | n/a | Baidu UEditor 1.4.0 before 1.4.3.1 contains a server-side request forgery vulnerability that allows unauthenticated attackers to make arbitrary requests via the source[] parameter in /ueditor/jsp/cont |
| CVE-2026-130683 | 8.2 | n/a | SiYuan before 3.8.10 uses an incomplete deny-list in IsSensitivePath that omits shell-initialization files such as .zshenv and .bash_profile, as well as ~/.local. Authenticated administrators can call |
| CVE-2019-25784 | 8.2 | n/a | FineCMS versions 5.0.4 before 5.0.11 contain an unauthenticated SQL injection vulnerability in the data2 API action handled by list_tag in libraries/Template.php. Attackers can send GET requests to in |
| CVE-2021-48021 | 8.2 | n/a | Chamilo LMS 1.11.10 before 1.11.16 contains an unauthenticated SQL injection vulnerability in the searchOptionsFromTags function through the options parameter of extra_field.ajax.php. Attackers can se |
| CVE-2022-51028 | 8.2 | n/a | CmsEasy 7.7.5_20210919 contains an unauthenticated SQL injection vulnerability in the execsql_action function at /?case=crossall&act=execsql that executes attacker-supplied queries decrypted with the  |
| CVE-2024-58402 | 8.2 | n/a | Azon Dominator releases through 2024-06-03 contain an SQL injection vulnerability that allows unauthenticated attackers to manipulate database queries through the cid parameter in /fetch_products.php. |
| CVE-2026-130644 | 8.1 | 0.5% | A path traversal flaw was found in ansible-core. When installing a collection with ansible-galaxy collection install, the install destination directory is derived from the namespace and name fields de |
| CVE-2026-130721 | 8.1 | n/a | NocoDB from 2026.06.2 before 2026.08.0 contains an authorization bypass vulnerability that allows authenticated base Editors to write to data-read-only sources by abusing the internal batch endpoint.  |
| CVE-2026-132121 | 8.1 | n/a | Supergateway 2.4.0 through 4.2.2 contains a cross-site WebSocket hijacking vulnerability in stdio-to-WebSocket mode that allows malicious web pages to connect by bypassing missing Origin header valida |
| CVE-2026-130751 | 8.1 | n/a | OpenWrt LuCI luci-app-travelmate on master before 3.0.0-1 and on openwrt-25.12 before 2.4.9-6 grants file exec permissions for state-mutating commands in the read scope of its rpcd ACL, letting authen |
| CVE-2026-130791 | 8.1 | n/a | Finsys Dockhand before 1.0.55 contains a path traversal vulnerability that allows users with stacks:edit permission to move arbitrary server directories by supplying a crafted oldDir parameter. Attack |
| CVE-2026-130766 | 8.0 | n/a | Obot from 0.26.0 before 0.27.0 fails to validate the resource identifier in remote MCP server protected resource metadata, allowing malicious MCP servers to steal access tokens. Attackers can name a d |
| CVE-2026-109555 | 8.0 | n/a | The WP STAGING and WP STAGING Pro plugins for WordPress are vulnerable to PHP Object Injection in all versions up to, and including, 4.17.0 and 6.17.0, respectively, via deserialization of untrusted i |
| CVE-2026-132751 | 7.8 | n/a | yt through 4.4.4 contains a code injection vulnerability that allows attackers to execute Python code by supplying a crafted con_args attribute in a ytdata HDF5 file. SavedDataset._parse_parameter_fil |
| CVE-2026-132756 | 7.8 | n/a | Geany through 2.1.0 contains an OS command injection vulnerability that allows attackers to run shell commands by embedding metacharacters in filenames substituted into build and execute commands. Att |
| CVE-2026-130782 | 7.7 | n/a | Incus before 7.6.0 contains an improper authorization vulnerability that allows restricted and view-only clients to read default project resources by requesting the default project directly. Attackers |
| CVE-2026-130787 | 7.7 | n/a | Frappe ERPNext before 16.35.0 contains a missing authorization vulnerability in financial reporting endpoints that allows low-privilege authenticated users to generate reports outside their permitted  |
| CVE-2026-130764 | 7.6 | n/a | Obot from 0.8.0 before 0.27.0 contains a server-side request forgery vulnerability that allows Power User accounts to reach internal hosts by advertising a malicious OAuth token endpoint in remote MCP |
| CVE-2026-130729 | 7.5 | n/a | NocoDB before 2026.08.0 contains an authorization bypass in its public shared-view relation endpoints, which verify that a parent record exists but not that it passes the view's row filters. Unauthent |
| CVE-2026-130746 | 7.5 | n/a | Grav before 1.7.53.7 and 2.x before 2.2.18 serves page media files, and rendered pages when lazy sessions are enabled, with the visitor's session cookie and a shared-cacheable Cache-Control header. Wh |
| CVE-2026-130749 | 7.5 | n/a | Grav from 2.0.0 before 2.2.18 contains a resource exhaustion vulnerability that allows unauthenticated attackers to fill the disk by varying the HTTP Host header. Attackers can send requests with dist |
| CVE-2019-25785 | 7.5 | n/a | FineReport 8.0 contains a path traversal vulnerability that allows unauthenticated attackers to read arbitrary files through the resourcepath parameter of the /WebReport/ReportServer endpoint. Attacke |
| CVE-2021-48022 | 7.5 | n/a | Rocket.Chat versions 0.61.0 before 3.11.4, 3.12.x before 3.12.4 and 3.13.x before 3.13.2 contain a missing authorization vulnerability allowing unauthenticated attackers to read any room's messages vi |
| CVE-2022-51029 | 7.5 | n/a | Synway SMG Gateway Management Software builds through 2022-03-15 contain a path traversal vulnerability that allows unauthenticated attackers to read arbitrary files via the downfile parameter in /dow |
| CVE-2023-54417 | 7.5 | n/a | Nuxt 3.0.0 before 3.4.2 contains a semi-arbitrary file read vulnerability in the vite-node dev server middleware that allows unauthenticated attackers to read files by supplying an absolute path as th |
| CVE-2023-54420 | 7.5 | n/a | LiveBOS builds through 2023-08-16 contain a path traversal vulnerability that allows unauthenticated attackers to read arbitrary files via the imgName parameter in /feed/ShowImage.do using a ';.js.jsp |
| CVE-2024-58403 | 7.5 | n/a | AnyShare builds through 2024-11 contain a missing authentication vulnerability in the /api/ShareMgnt/Usrm_GetAllUsers endpoint that exposes user records including password fields. Attackers can send u |
| CVE-2026-76411 | 7.5 | n/a | A vulnerability in the phishcheck functionality of ClamAV could allow an unauthenticated, remote attacker to cause a DoS condition on an affected device.
 This vulnerability is due to improper alloc |
| CVE-2026-76414 | 7.5 | n/a | A vulnerability in Microsoft Compiled HTML Help (CHM) file scanning of ClamAV could allow an unauthenticated, remote attacker to cause a DoS condition on an affected device.
 This vulnerability is d |
| CVE-2026-76415 | 7.5 | n/a | A vulnerability in the Yoda'a Crytper (yC) Portable Executable (PE) unpacker of ClamAV could allow an unauthenticated, remote attacker to cause a DoS condition on an affected device. .
 This vulnera |
| CVE-2026-76416 | 7.5 | n/a | A vulnerability in the InstallShield file parser of ClamAV could allow an unauthenticated, remote attacker to cause a DoS condition on an affected device.
 This vulnerability is due to incomplete er |
| CVE-2026-76417 | 7.5 | n/a | A vulnerability in Object Linking and Embedding, 2nd Generation (OLE2) file parser for ClamAV could allow an unauthenticated, remote attacker to cause a DoS condition on an affected device.
 This vu |
| CVE-2026-76421 | 7.5 | n/a | A vulnerability in the LZX data algorithm for Microsoft Compiled HTML Help (CHM) file scanning in ClamAV could allow an unauthenticated, remote attacker to cause a DoS condition on an affected device. |
| CVE-2026-76422 | 7.5 | n/a | A vulnerability in the debug logging functionality of ClamAV could allow an unauthenticated, remote attacker to cause a DoS condition on an affected device.
 This vulnerability is due to improper ha |
| CVE-2026-76430 | 7.5 | n/a | A vulnerability in the Ultimate Packer for eXecutables (UPX) unpacker of ClamAV could allow an unauthenticated, remote attacker to cause a DoS condition on an affected device.   This vulnerability i |
| CVE-2026-76515 | 7.5 | n/a | A vulnerability in the Object Linking and Embedding, 2nd Generation (OLE2) file parser for ClamAV could allow an unauthenticated, remote attacker to exceed the configured MaxScanTime and cause a DoS c |
| CVE-2026-130760 | 7.5 | n/a | Fleet before 4.86.2 contains a denial of service vulnerability that allows unauthenticated attackers to exhaust server memory via unbounded BER recursion in PKCS#7 parsing. Attackers can send deeply n |
| CVE-2026-127222 | 7.5 | n/a | SGLang through 0.5.23, fixed in commit 7b5fb39, contains a missing authorization vulnerability in the POST /load_lora_adapter_from_tensors HTTP endpoint, which lacks the @auth_level(AuthLevel.ADMIN_OP |
| CVE-2026-132140 | 7.5 | n/a | A security vulnerability has been detected in DrayTek Vigor2960 up to 1.5.1.6. Affected by this vulnerability is an unknown functionality of the file mainfunction.cgi of the component Apmcfg Upload. T |
| CVE-2026-14491 | 7.5 | n/a | The WP Duplicate – WordPress Migration Plugin plugin for WordPress is vulnerable to Directory Traversal in all versions up to, and including, 1.1.11 via the 'file_name' parameter. This makes it possib |
| CVE-2026-85776 | 7.5 | n/a | The WP Duplicate – WordPress Migration Plugin plugin for WordPress is vulnerable to Missing Authorization in versions up to, and including, 1.1.11. This is due to a missing capability check and missin |
| CVE-2026-132286 | 7.3 | n/a | A security vulnerability has been detected in yangzongzhuan RuoYi up to 4.8.3. The impacted element is an unknown function of the file ruoyi-admin/src/main/java/com/ruoyi/web/controller/system/SysLogi |
| CVE-2026-132609 | 7.3 | n/a | A vulnerability was identified in SourceCodester Online Food Ordering System 1.0. The affected element is an unknown function of the file /web/admin/add_food.php. Such manipulation leads to unrestrict |
| CVE-2026-132610 | 7.3 | n/a | A security flaw has been discovered in SourceCodester Simple Form Builder Web App 1.0. The impacted element is the function save_form of the file /classes/Forms.php. Performing a manipulation of the a |
| CVE-2026-132611 | 7.3 | n/a | A security vulnerability has been detected in SourceCodester Simple Form Builder Web App 1.0. This impacts the function save_response of the file /classes/Forms.php. The manipulation of the argument q |
| CVE-2026-132625 | 7.3 | n/a | A vulnerability was determined in SourceCodester Student Project Allocation and Management System 1.0. Affected is an unknown function of the file /login.php of the component Login Handler. Executing  |
| CVE-2026-132626 | 7.3 | n/a | A vulnerability was identified in SourceCodester Modern Ticket Reservation System 1.0. Affected by this vulnerability is an unknown functionality of the file /booking/validate.php. The manipulation of |
| CVE-2026-132627 | 7.3 | n/a | A security flaw has been discovered in SourceCodester E-Commerce Shopping Cart Web Application 1.0. Affected by this issue is some unknown functionality of the file action.php. The manipulation of the |
| CVE-2026-130737 | 7.2 | n/a | Grav from 2.0.0 before 2.2.18 contains a privilege escalation vulnerability that allows user managers to grant super-admin rights by nesting access maps under a YAML merge key. Attackers with admin.us |
| CVE-2026-130738 | 7.2 | n/a | Grav from 2.0.0 before 2.2.18 contains a privilege escalation vulnerability that allows user managers with admin.users.update to take over super admin accounts by disabling the super-granting group. A |
| CVE-2026-116758 | 7.2 | n/a | The Advanced Country Blocker plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'REQUEST_URI' parameter in all versions up to, and including, 2.3.2 due to insufficient input san |
| CVE-2026-125053 | 7.2 | n/a | The WEB-Translation – eTranslation Multilingual plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including, 2.0.7 due to insuffi |
| CVE-2026-130758 | 7.2 | n/a | Fleet before 4.92.0 contains an authorization bypass vulnerability in the deprecated POST /api/latest/fleet/mdm/apple/enqueue endpoint that allows team-scoped users to enqueue Apple MDM commands outsi |
| CVE-2026-132748 | 7.2 | n/a | Vtiger CRM through 8.4.0 contains a PHP code injection vulnerability that allows authenticated administrators to inject code via the updatedFields parameter into config.inc.php. Attackers can supply a |
| CVE-2026-84998 | 7.2 | n/a | The NextScripts: Social Networks Auto-Poster plugin for WordPress is vulnerable to Stored Cross-Site Scripting via 'comment_author' and 'comment_agent' Comment Fields in all versions up to, and includ |
| CVE-2026-130776 | 7.1 | n/a | Incus before 7.6.0 contains an information disclosure vulnerability that allows clients with project event-view access to read migration websocket secrets broadcast in operation metadata. Attackers ca |
| CVE-2026-132773 | 7.1 | n/a | Attendize through 2.8.0 contains an authorization bypass vulnerability in EventOrdersController::postCancelOrder() that allows authenticated organisers to cancel attendees belonging to other accounts' |
| CVE-2026-126631 | 7.1 | n/a | A flaw was found in OpenSCAP. This vulnerability allows for information disclosure when performing offline scans of untrusted filesystem images, such as container images or virtual machine (VM) disks. |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-xmgr-hq6h-vqx6 | CVE-2026-99320 | unknown | In the Linux kernel, the following vulnerability has been resolved:

ipv6: raw: fix use-after... |
| GHSA-w4vp-jhx9-25m7 | CVE-2026-132043 | medium | In Eclipse Yasson versions 3.0 to 3.0.5, a race condition (CWE-362) exists in the handling of ... |
| GHSA-rvhf-mrmh-w3hg | CVE-2026-101167 | medium | Missing Authorization vulnerability in Dataprom Bilişim Teknolojileri LTD. ŞTİ. DataPer Access... |
| GHSA-p3qf-w99r-v259 | CVE-2026-128999 | high | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-vr7w-mgpm-j343 | CVE-2026-129048 | critical | Improper Control of Generation of Code ('Code Injection') vulnerability in Jacob N. Breetvelt WP... |
| GHSA-9cgj-8xc4-vcqr | CVE-2026-129001 | high | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-8452-w857-wpmw | CVE-2026-132825 | high | Ruby before 3.3.14, 3.4.13, and 4.0.10 has a heap-based buffer overflow during case conversion.... |
| GHSA-6v2w-685f-h3hc | CVE-2026-110462 | high | The Comelit 1456B Multi-User Gateway, in firmware versions up to and including 2.10.0, allows a... |
| GHSA-rp4c-hw4j-wqpg | CVE-2026-110461 | critical | The Comelit 1456B Multi-User Gateway, in firmware versions up to and including 2.10.0, is... |
| GHSA-6fgf-mf94-qfxg | CVE-2026-129014 | medium | Missing Authorization vulnerability in DynamiApps Frontend Admin by DynamiApps acf-frontend-form... |
| GHSA-6mjw-2gq8-xpjc | CVE-2026-129013 | high | Missing Authorization vulnerability in Deepen Bajracharya Video Conferencing with Zoom video... |
| GHSA-jf78-54vq-jmf2 | CVE-2026-129030 | high | Exposure of Sensitive System Information to an Unauthorized Control Sphere vulnerability in... |
| GHSA-fv8x-rqxf-jgrw | CVE-2026-112163 | medium | Improper neutralization of input during web page generation ('cross-site scripting')... |
| GHSA-q4w5-cx36-345q | CVE-2026-19609 | high | Cross-site scripting in the embedded co-browsing feature in Unblu inc. Unblu Spark 7.0 through 7... |
| GHSA-8q97-pg85-2cjx | CVE-2026-129446 | unknown | The WPO365 | SEAMLESS WORDPRESS + MICROSOFT INTEGRATION (WPO365 | LOGIN) WordPress plugin before... |
| GHSA-5pq6-7wm2-5x62 | CVE-2026-117678 | medium | Inefficient Algorithmic Complexity vulnerability in benoitc idna allows an attacker who controls... |
| GHSA-7fqq-fp6h-crcf | CVE-2026-84998 | high | The NextScripts: Social Networks Auto-Poster plugin for WordPress is vulnerable to Stored Cross... |
| GHSA-4v8m-v3r8-w9q4 | CVE-2026-109555 | high | The WP STAGING and WP STAGING Pro plugins for WordPress are vulnerable to PHP Object Injection in... |
| GHSA-mxpj-h69f-39hr | CVE-2026-121852 | unknown | The AppPresser  WordPress plugin before 5.0.0 does not properly escape the contents of its debug... |
| GHSA-6883-p7cr-883r | CVE-2026-108687 | unknown | The SAML SSO Login  WordPress plugin through 1.5.2 does not verify that the SAML assertion whose... |
| GHSA-7c5c-qrrc-p845 | CVE-2026-132804 | critical | A malicious actor with access to the network and low privileges could exploit a Server-Side... |
| GHSA-q5g9-hj2c-8qfv | CVE-2026-132808 | critical | A malicious actor with access to the network and low privileges could exploit an Incorrect... |
| GHSA-5676-q49r-865f | CVE-2026-132807 | critical | A malicious actor with access to the network and under certain conditions could exploit an... |
| GHSA-rpqv-9vr5-8vqc | CVE-2026-132806 | high | A malicious actor with access to the network and low privileges could exploit an authenticated... |
| GHSA-6m7j-cqmc-p88h | CVE-2026-132805 | high | A malicious actor with access to the network could exploit a Server-Side Request Forgery (SSRF)... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Smith & Green, Attorneys at Law PLLC | rhysida | US | 2026-11-19T06:44:34.639183+00:00 |
| www.sleepboxbymiracle.com | krybit | RU | 2026-11-19T03:51:04.582712+00:00 |
| www.leadersaluminium.ae | krybit | AE | 2026-11-19T01:57:18.197956+00:00 |
| alumil.com | krybit | GR | 2026-11-19T00:50:25.526338+00:00 |
| Terminais | medusalocker | MZ | 2026-11-18T23:01:01.237023+00:00 |
| Company #241 | N0n | US | 2026-11-18T22:14:17.690089+00:00 |
| Company #240 | N0n | PH | 2026-11-18T22:13:41.148098+00:00 |
| Company #239 | N0n | GB | 2026-11-18T22:13:04.286185+00:00 |
| Company #238 | N0n | US | 2026-11-18T22:12:27.968467+00:00 |
| Company #237 | N0n | MX | 2026-11-18T22:11:51.685721+00:00 |
| Company #236 | N0n | US | 2026-11-18T22:11:12.846302+00:00 |
| Company #235 | N0n | US | 2026-11-18T22:10:36.141339+00:00 |
| Company #234 | N0n | GB | 2026-11-18T22:09:59.545128+00:00 |
| Company #233 | N0n | MX | 2026-11-18T22:09:17.924125+00:00 |
| Company #232 | N0n | US | 2026-11-18T22:08:40.493365+00:00 |
| Company #231 | N0n | US | 2026-11-18T22:08:00.252653+00:00 |
| Company #230 | N0n | US | 2026-11-18T22:07:23.536233+00:00 |
| Company #229 | N0n | US | 2026-11-18T22:06:46.914060+00:00 |
| Company #228 | N0n | US | 2026-11-18T22:06:09.536229+00:00 |
| Company #227 | N0n | GB | 2026-11-18T22:05:31.990277+00:00 |

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
| 138.226.239.233 | 11 |
| 138.226.239.234 | 11 |
| 64.62.197.92 | 10 |
| 77.239.124.252 | 10 |
| 18.218.118.203 | 9 |
| 45.148.10.141 | 9 |
| 45.148.10.151 | 9 |
| 45.148.10.152 | 9 |
| 193.32.162.15 | 9 |
| 193.187.110.160 | 9 |
| 2.57.121.25 | 8 |
| 2.57.121.112 | 8 |
| 3.129.187.38 | 8 |
| 35.210.240.68 | 8 |
| 45.148.10.157 | 8 |
| 62.60.130.148 | 8 |
| 64.62.197.2 | 8 |
| 65.49.1.202 | 8 |
| 66.132.195.110 | 8 |
| 80.94.95.115 | 8 |

### OpenPhish (live phishing URLs)
- http://www.talktalkinfo1.weebly.com/
- http://jodals.github.io/SPOTIFY-Clone
- https://www.undian-hadiahshopee33.blogspot.com/
- http://opensea.28372982.com/
- http://small-base-c44c.roberto-kupfer.workers.dev/
- https://vmi3744912.contaboserver.net//amm/rena/msg.php/
- http://armanbin007.github.io/Spotify-Replica-Project
- https://bradescoempresa.urlx.online/
- http://splendorous-sunburst-84749c.netlify.app/
- https://ledger.hk.cn/downloads
- http://kanishkaverma1405.github.io/Netflix-clone
- http://sanganinandini.github.io/Netflix-dashboard
- https://constitute-ontario-jewish-carefully.trycloudflare.com/
- https://upholexdlogin.gitbook.io/
- https://romani.ind.br/sho/upgrade.html#[email%C2%A0protected]
- http://imtooenne.com/en.html
- http://casadosbordados.net/_
- http://splendorous-squirrel-a00c04.netlify.app/
- https://auth.re/E.0zwzVx5eU3tZvXEbyw?/=userid&messageid=YWZhNDM0c2RqZjk4MjNmb2lkc2pmKC9DODk4RnNhOShGLyhBU0ZzdWlhaGRma2FzZDIoLw==
- https://rbx.tg/vYJ-XAmY

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | http://j8882.buzz/ |
| N/A | https://nutmegbelfry.live/ |
| N/A | https://orventa.vu/server/?uid=aaaa@example.jp |
| N/A | https://orventa.vu/9b29b7c73bfa |
| N/A | https://www.cdiscount.com?source_id=&sub1=dbvav860fgns73ajv53g&adv1=&adv2= |
| N/A | https://sunshine-mirror-message.lovable.app/?utm_id=97757_v0_s00_e0_tv2&amp;fbclid=IwY2xjawVrRbRleHRuA2FlbQIxMQBwZG9mAW |
| N/A | https://tra.com/fresh-start-signup2?_ef_transaction_id=aa4738e4807d44678dcb2b8498c214be&source_id=&affid=5&sub1=10cdbde48c6b4abf81232f332c07b711&sub2=427035&sub3=taaax21&sub4=&sub5=&oid=44 |
| N/A | https://vercel.com/login?next=%2Fsso-api%3Furl%3Dhttps%253A%252F%252Finterface-uniswap.vercel.app%252F%26nonce%3D3ad783d544c6403f974a21516c0081e702e0f29ef133a043f1ee0f54dfe65b43 |
| N/A | https://away.vk.ru/away.php?rh=37d16d32-c56b-428a-8025-d0869f04d191 |
| N/A | https://away.vk.ru/away.php?rh=ab9d682c-0a24-4ad9-8029-23cbca64fdeb |
| N/A | https://away.vk.ru/away.php?rh=819c671f-923d-4cdb-aa5a-5e8616c9edf1 |
| N/A | https://b8376mghi5d.jp.larksuite.com/share/base/form/shrjpMwk5KEz3wmsdPQjPPcLjqh?auth_token=U7CK1RF-3e4va3ea-6210-4814-b8c3-6af870qd2bjc-NN5W4 |
| N/A | https://id.superhuman.com/signin?oauth_client_type=MEDIATED_WEB&correlation_id=mbEfN_5D7nunEZXRMdQCJQ&version=v4&client_id=superhumanDocs |
| N/A | https://away.vk.ru/away.php?rh=322b59f6-bda6-40c0-9bf0-104542f22bea |
| N/A | https://away.vk.ru/away.php?rh=0209cba4-2cfb-4b03-8fa4-e71ea83b2673 |
| 5.6 | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AWnogHfrcMjMJOA5-x4JjU2A_H62FL5Ipip8qUn0FfsVqhu1vrUBPxBl4JpnqCjPGKNrTfaShVnNJQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBgle9gf49xdLagHnpUZF1pmdsjvV1cNzWRB9jLUzd1R2hPrBGPUyyRUfnx3bffN2fuhg5jcYJWQ&dsh=S-1442404246%3A1795074542270116 |
| N/A | https://away.vk.ru/away.php?rh=2eb5bdcf-e9fc-4206-a94b-4e5ff1d9350c |
| N/A | https://download.phantom-wallet.to/en?click_id=9c08d196-f479-4648-8f4c-8edf2b314113 |
| N/A | https://vh446.timeweb.ru/parking/?ref=ce56074.tw1.ru |
| N/A | https://flat-bread-04ca.cloudflareaccess.com/cdn-cgi/access/login/vertiv-command-center.pages.dev?kid=617efb6eb0445e77d08421b7c2075c08ed7302463271c62a28d702c82772462a&meta=eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiIsImtpZCI6IjEyY2U5NjlmMDk3YjUyNjliNjllZjA0N2EwMjBiZGI2NGMwMTc5NjMwNzE3MzJhMWJjODg2NjJiNGUxYzJjY2IifQ.eyJ0eXBlIjoibWV0YSIsImF1ZCI6IjYxN2VmYjZlYjA0NDVlNzdkMDg0MjFiN2MyMDc1YzA4ZWQ3MzAyNDYzMjcxYzYyYTI4ZDcwMmM4Mjc3MjQ2MmEiLCJob3N0bmFtZSI6InZlcnRpdi1jb21tYW5kLWNlbnRlci5wYWdlcy5kZXYiLCJyZWRpcmVjdF91cmwiOiIvIiwic2VydmljZV90b2tlbl9zdGF0dXMiOmZhbHNlLCJpc193YXJwIjpmYWxzZSwiaXNfZ2F0ZXdheSI6ZmFsc2UsImV4cCI6MTc5NTA3NDE3NSwibmJmIjoxNzk1MDczODc1LCJpYXQiOjE3OTUwNzM4NzUsImF1dGhfc3RhdHVzIjoiTk9ORSIsIm10bHNfYXV0aCI6eyJjZXJ0X2lzc3Vlcl9kbiI6IiIsImNlcnRfc2VyaWFsIjoiIiwiY2VydF9pc3N1ZXJfc2tpIjoiIiwiY2VydF9wcmVzZW50ZWQiOmZhbHNlLCJjb21tb25fbmFtZSI6IiIsImF1dGhfc3RhdHVzIjoiTk9ORSJ9LCJyZWFsX2NvdW50cnkiOiJVUyIsImFwcF9zZXNzaW9uX2hhc2giOiJmNGY0M2E0YmI5YzQ1N2FmZmMyOTE3YTNkMGQ1MmUzYjZjNTYyMWUyNWY5YTM3MGZkMjM3MGJkYjc1ZDE1NmE0In0.aa7VB389T26PTJaoWJ7qGt3qzfDtpRNcaBWEGzXWvq8IoUL4JLJOhbZkcH9NKbejDTky642virSl7-fPH-ILho154dk3ZIfvvYfFrMsZphc1M2Mly1a57hHBIXTG2kG10PABEYAg_SdayYtVlZycEdBszNlyYHCjH65s1k_oBuqfZAogw0u4K-QuTnpl9DkbuyATsttr6UwNNVcZAgXIUFrgFSMpDwNeQnmirw0M7_GDq_tsmzjWx_ZAyVjQJK4S9X6iQfAuXH7YXo9PJ4vhNYZI7_AQYBnZQ8meKa7GybbDIaDhjUgACd5FHSSgGBV2kMigptenU0CHLw4-1SjUxA&redirect_url=%2F |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| dacd0b341a6ba567988cec40c37f01ef29c68d07 | WARDENStealer C&C |
| 781fbc5f21c8ee7fcf30f9a1418121dba1967a84 | Vidar C&C |
| bbc92da2f65ac8416cfa1cf1796a8c77b7d6702f | WeedStealer C&C |
| 099d0aa13d2c75b25f09bb1315ea83bef301a26c | WeedStealer C&C |
| ef3db89846fa204ef65b0c88ca2b3ced5705ba11 | Vidar C&C |
| 81d9dfcd66de9aa45077d1ab1ecd683e2963a277 | WARDENStealer C&C |
| c2c7c65a60e250f94f78944558c5db7d8086dca4 | PureLogsStealer C&C |
| 5d4337304f628324e97723e352148d9d259ef3c3 | FennecRAT C&C |
| 13b6b2f68e58287e1fbe149b9ae41f5259406f38 | Malware C&C |
| c51052b024b7b8fd7afff4c0912d6c00b3d2eb05 | ACRStealer C&C |
| 203fb6154172879c08291fefb46062b27eb73f55 | ConnectWise C&C |
| 52a71237e3ce64976990f68f176eb8a8c1daa052 | Malware C&C |
| 110dc32c90365e41ccfc8eaf47b89c8f5adc45fc | WARDENStealer C&C |
| d36e7ea8c3bd11f3d64e2a454ca1850566a63df7 | PureRAT C&C |
| dd35950dcdc0d2afeb557ff622375cdafe938fc5 | Vidar C&C |
| 29a612773b379e945229a831f7d69280a2b0fd49 | Vidar C&C |
| 36210d41f78bcf7c4e3dcd32a9c6ea0392c435c2 | xeffStealer C&C |
| 4ab5b2103cc4653d78269daad5fdb8f598705843 | OffLoader C&C |
| 5ce11a4cab0a83a5675d71c4af0804e1c0843c94 | Vidar C&C |
| beb63a581c0b40874ca784c11aaabf1de9dd6a79 | OffLoader C&C |

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
- 1.100.15.8
- 1.12.252.163
- 1.13.22.101
- 1.13.79.149
- 1.14.240.247
- 1.164.109.132
- 1.178.213.254
- 1.192.216.175
- 1.20.178.157
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.220.198.126
- 1.222.42.237
- 1.234.27.159
- 1.234.5.148
- 1.234.53.65
- 1.234.80.94
- 1.235.183.146

### CINS Army (poorly-rated IPs)
- 1.14.3.170
- 1.145.16.243
- 1.15.14.29
- 1.177.162.2
- 1.189.41.213
- 1.192.129.106
- 1.20.151.114
- 1.24.16.101
- 1.24.16.11
- 1.24.16.110
- 1.24.16.111
- 1.24.16.113
- 1.24.16.121
- 1.24.16.130
- 1.24.16.131
- 1.24.16.138
- 1.24.16.142
- 1.24.16.144
- 1.24.16.145
- 1.24.16.149

## News (last ~36h, across outlets)
### The Hacker News
- [Hackers Breach N-able Cloud Server, Disrupting Email Security Management Across 3 Regions](https://thehackernews.com/2026/11/n-able-confirms-hackers-accessed-cloud.html)
- [Ruby Releases Fixes for 7 Regex and String Flaws, Warns 5 Have Proof-of-Concept RCE](https://thehackernews.com/2026/11/ruby-releases-fixes-for-7-regex-and.html)
- [Researcher Demonstrates Database RCE Exploits Affecting PostgreSQL, MySQL and Oracle](https://thehackernews.com/2026/11/researcher-demonstrates-database-rce.html)
- [CISA Warns of 4 Exploited Flaws Linked to Ransomware, Cryptomining, and LLMjacking Attacks](https://thehackernews.com/2026/11/cisa-warns-of-4-exploited-flaws-linked.html)
- [PHP Warns of Critical Security Flaws Affecting All Supported Versions, Fixes Coming November 19](https://thehackernews.com/2026/11/php-warns-of-critical-security-flaws.html)
- [10-Year-Old NGINX HTTP/2 Flaw Lets Unauthenticated Attackers Execute Code on Servers](https://thehackernews.com/2026/11/10-year-old-nginx-http2-flaw-lets.html)
- [F5 Warns 6 Critical BIG-IP Flaws Can Crash Traffic in Specific Setups, May Allow RCE](https://thehackernews.com/2026/11/f5-warns-6-critical-big-ip-flaws-can.html)
- [Critical Apache Roller RCE Flaw Under Active Exploitation, No Authentication Required](https://thehackernews.com/2026/11/critical-apache-roller-rce-flaw-under.html)
- [New EggStreme Malware Variant Goes Silent to Evade Security Tools in Government Attacks](https://thehackernews.com/2026/11/eggstreme-hackers-rebuild-malware-with.html)
- [New Attack Bypasses TPM Lockout to Crack Windows Hello and BitLocker PINs in Days, Not Years](https://thehackernews.com/2026/11/flash-chip-attack-bypasses-tpm-lockout.html)
- [AI Pentesting Checklist for Web Apps: 15 Questions to Ask Before Choosing a Vendor](https://thehackernews.com/2026/11/ai-pentesting-checklist-for-web-apps-15.html)
- [Java4Shell Flaw (CVE-2026-114938) Enables Pre-Auth RCE in Jira, Jenkins, Keycloak and More](https://thehackernews.com/2026/11/java4shell-cve-2026-114938-enables-pre.html)
- [Quality Isn’t The Main Worry About AI Pentesting — Data Privacy and Production Safety Are](https://thehackernews.com/2026/11/quality-isnt-main-worry-about-ai.html)
- [Hackers Exploiting Critical Puppet RCE Flaw Affecting Enterprise Management Servers](https://thehackernews.com/2026/11/hackers-exploiting-critical-puppet-rce.html)
- [CISA Urges Immediate Patching of Java4Shell Flaw That Could Allow Remote Code Execution](https://thehackernews.com/2026/11/cisa-urges-immediate-patching-of.html)

### BleepingComputer
- [Microsoft confirms app installation, launch issues after hotpatch](https://www.bleepingcomputer.com/news/microsoft/microsoft-confirms-app-installation-launch-issues-after-hotpatch/)
- [NVIDIA investigating Gentlemen ransomware breach claims](https://www.bleepingcomputer.com/news/security/nvidia-investigating-gentlemen-ransomware-breach-claims/)
- [Ukraine, FBI arrest ransomware gang members tied to $40M in ransoms](https://www.bleepingcomputer.com/news/security/ukraine-fbi-arrest-ransomware-gang-members-tied-to-40m-in-ransoms/)
- [Coinbase blocks $4.7 million in transfers to Elon Musk deepfake scam](https://www.bleepingcomputer.com/news/security/coinbase-blocks-47-million-in-transfers-to-elon-musk-deepfake-scam/)
- [Data breach impacts 40 Irish credit unions in reported IT provider hack](https://www.bleepingcomputer.com/news/security/data-breach-impacts-40-irish-credit-unions-in-reported-it-provider-hack/)
- [Microsoft’s Agent Framework PyPI package compromised to steal credentials](https://www.bleepingcomputer.com/news/security/microsofts-agent-framework-pypi-package-compromised-to-steal-credentials/)
- [From Deepfakes to Helpdesk Impersonation: Why Stronger Verification Matters](https://www.bleepingcomputer.com/news/security/from-deepfakes-to-helpdesk-impersonation-why-stronger-verification-matters/)
- [Dizigom illegal streaming service with 21M monthly visits shuts down](https://www.bleepingcomputer.com/news/security/dizigom-illegal-streaming-service-with-21m-monthly-visits-shuts-down/)
- [Apache warns of Roller RCE vulnerability exploited in attacks](https://www.bleepingcomputer.com/news/security/apache-warns-of-roller-rce-vulnerability-exploited-in-attacks/)
- [Microsoft announces Windows Server 2028 with hardened security](https://www.bleepingcomputer.com/news/microsoft/microsoft-announces-windows-server-2028-with-hardened-security/)
- [British Scattered Spider hacker sentenced to 6 years in prison](https://www.bleepingcomputer.com/news/security/british-scattered-spider-hacker-sentenced-to-6-years-in-prison/)

### Krebs on Security
- [Attackers Used Optimizely to A/B Test Malware on Top Websites](https://krebsonsecurity.com/2026/11/attackers-used-optimizely-to-a-b-test-malware-on-top-websites/)

### Dark Reading
- [Africa Retakes Top Spot as Most Attacked Region, Led by Nigeria Surge](https://www.darkreading.com/threat-intelligence/africa-top-spot-most-attacked-region-nigeria-surge)
- [Russia's Cold Relic APT Turns One Cloud Breach Into Another](https://www.darkreading.com/cyberattacks-data-breaches/cold-relic-turns-one-cloud-breach-into-another)
- [Strike Graph Launches Integration AI to Automate Continuous Compliance Evidence Using Any Existing Tool](https://www.darkreading.com/cyber-risk/strike-graph-launches-integration-ai-to-automate-continuous-compliance-evidence-using-any-existing-tool)
- [AttackIQ Research Reveals How Iranian Cyber Groups Hand Off Network Access to Enable Destructive Attacks](https://www.darkreading.com/threat-intelligence/attackiq-research-reveals-iranian-cyber-groups)
- [Java4Shell Flaw Threatens Global Enterprises, Java Application Ecosystem](https://www.darkreading.com/vulnerabilities-threats/java4shell-flaw-threatens-global-java-application-ecosystem)
- [Major Brazilian Signature Apps Enable RCE &amp; Fraud](https://www.darkreading.com/vulnerabilities-threats/major-brazilian-signature-app-rce-fraud)

### SecurityWeek
- [Splunk Patches Nearly 140 Flaws Across Three Core Products](https://www.securityweek.com/splunk-patches-nearly-140-flaws-across-three-core-products/)
- [F5 Patches Critical NGINX2Root Flaws as PoC Exploits Go Public](https://www.securityweek.com/f5-patches-critical-nginx2root-flaws-as-poc-exploits-go-public/)
- [Java4Shell Exploitation Attempts Begin as Vendors Rush Out Advisories](https://www.securityweek.com/java4shell-exploitation-attempts-begin-as-vendors-rush-out-advisories/)
- [PHP Readies Critical Security Updates to Patch Another RCE Flaw](https://www.securityweek.com/php-readies-critical-security-updates-to-patch-another-rce-flaw/)
- [Palo Alto Networks to Buy AI Startup Applied Compute for $4.5 Billion](https://www.securityweek.com/palo-alto-networks-to-buy-ai-startup-applied-compute-for-4-5-billion/)
- [Vero Security Raises $11 Million for AI Security Engineering Platform](https://www.securityweek.com/verosecurity-raises-11-million-for-ai-security-engineering-platform/)
- [Russian APT Poses as Employee of Hacked Firm to Breach Another US Organization](https://www.securityweek.com/russian-apt-poses-as-employee-of-hacked-firm-to-breach-another-us-organization/)
- [Last of Five Defendants Sentenced in US Scattered Spider Hacking Case](https://www.securityweek.com/last-of-five-defendants-sentenced-in-us-scattered-spider-hacking-case/)
- [Microsoft Takes Perception Agentic Security Platform Out of Preview](https://www.securityweek.com/microsoft-takes-perception-agentic-security-platform-out-of-preview/)
- [CISO Conversations: Patti Degnan – Part of the Job Is Deciding What Not to Do](https://www.securityweek.com/ciso-conversations-patti-degnan-part-of-the-job-is-deciding-what-not-to-do/)

### The Record
- [Judge signs off on sale of Spirit Airlines’ data to Google](https://therecord.media/judge-signs-off-google-purchase-spirit-airlines-data)
- [Trump administration officials size-up a bad stretch for tech](https://therecord.media/tech-disruptions-house-homeland-committee-testimony)
- [Lawmakers call on White House to develop defensive AI cyber systems](https://therecord.media/ai-cyber-white-house)
- [NSA continues response to interruptions in classified internal network](https://therecord.media/nsa-continues-response-to-nsa-net-problems)
- [Russian cyber-espionage group used stolen cloud data to hack into organizations, Google says](https://therecord.media/russia-cyber-espionage-google)

### Infosecurity Magazine
- [A Fifth of UK Employees Share Passwords with AI](https://www.infosecurity-magazine.com/news/fifth-uk-employees-share-passwords/)
- [Rakuten Securities Breach Could Impact 15 Million Customers](https://www.infosecurity-magazine.com/news/rakuten-securities-breach-15/)
- [Five Critical Vulnerabilities Found in World's Most Widely Used Open-Source Web Server](https://www.infosecurity-magazine.com/news/five-critical-vulnerabilities/)
- [Most SecOps Leaders Are Changing the L1 Role as Agent Use Grows](https://www.infosecurity-magazine.com/news/secops-changing-l1-role-as-agent/)
- [Suspected Chinese APT Rebuilds EggStreme Malware After Exposure](https://www.infosecurity-magazine.com/news/eggstreme-malware-rebuilt-after/)
- [Java4Shell Vulnerability Allows Remote Attacks on Major Java Apps](https://www.infosecurity-magazine.com/news/java4shell-vulnerability-remote/)
- [Russian Espionage Actor Star Blizzard Focuses on Cloud Identities for Mass Data Theft](https://www.infosecurity-magazine.com/news/russian-star-blizzard-cloud-data/)
- [Three AI Models Agree on Just One of 121 Potential Code Flaws](https://www.infosecurity-magazine.com/news/ai-models-vulnerability-findings/)
- [Watchdog Warns UK Government Is Falling Short on Risk Management](https://www.infosecurity-magazine.com/news/watchdog-government-risk/)

### CyberScoop
- [Consensus mounts that tech outages were fueled by patching of AI-discovered vulnerabilities](https://cyberscoop.com/tech-outages-ai-vulnerability-patching/)
- [Senate Republicans advance FCC nominee, slate of cyber bills](https://cyberscoop.com/danielle-thumann-severs-fcc-nomination-tech-bills/)
- [It’s NGINX’s turn to cause vulnpocalypse headaches](https://cyberscoop.com/nginx-critical-vulnerabilities-exploits/)
- [Government tech debt is a national security risk](https://cyberscoop.com/government-tech-debt-national-security-risk-op-ed/)

### Cisco Talos
- [The challenge of defending against bulletproof dead drops on public blockchains](https://blog.talosintelligence.com/the-challenge-of-defending-against-bulletproof-dead-drops-on-public-blockchains/)
- [UAT-12643: Suspected North Korea-aligned actor blends blockchain resilience with targeted infostealing](https://blog.talosintelligence.com/uat-12643-suspected-north-korea-aligned-actor-blends-blockchain-resilience-with-targeted-infostealing/)
- [CVE-2026-114938: Critical vulnerability in OpenJDK Java](https://blog.talosintelligence.com/java4shell/)

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Thursday, November 19th, 2026 https://isc.sans.edu/podcastdetail/10186, (Thu, Nov 19th)](https://isc.sans.edu/diary/rss/33536)
- [Treat Your Honeypot Analysis Like Code: Git, Pull Requests and a Human Gate for AI &#x5b;Guest Diary&#x5d;, (Wed, Nov 18th)](https://isc.sans.edu/diary/rss/33534)
- [Java4Shell, NGINX2Shell and more: Why we are not at "Yellow", (Wed, Nov 18th)](https://isc.sans.edu/diary/rss/33532)
- [ISC Stormcast For Wednesday, November 18th, 2026 https://isc.sans.edu/podcastdetail/10184, (Wed, Nov 18th)](https://isc.sans.edu/diary/rss/33528)

### Securelist (Kaspersky)
- [The forced audit: how AuditTeam’s OpsAgent framework masks ransomware as consulting](https://securelist.com/auditteam-opsagent-forced-audit/122031/)

### CrowdStrike Blog
- [CrowdStrike Is Building the Engine of the Agentic SOC with Falcon Next-Gen SIEM](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-gartner-mq-siem/)
- [CrowdStrike Brings the Human Advantage to AI Detection and Response](https://www.crowdstrike.com/en-us/blog/crowdstrike-brings-human-advantage-aidr/)
- [Hidden in the Weights: Supply Chain Risk from Backdoored LoRA Models](https://www.crowdstrike.com/en-us/blog/supply-chain-risk-from-backdoored-lora-models/)
- [Inside Falcon AI Gateway: One Control Point for AI Traffic](https://www.crowdstrike.com/en-us/blog/falcon-ai-gateway-one-control-point-for-ai-traffic/)
- [CrowdStrike Named a Leader in the 2026 IDC MarketScape for Worldwide Augmented Identity Security Solutions](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-idc-marketscape-worldwide-augmented-identity-security-solutions/)
- [November 2026 Patch Tuesday: 1,252 CVEs Include One Zero-Day and 68 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-november-2026/)
- [How Adversaries Are Turning the Vulnerability Ecosystem Against Defenders](https://www.crowdstrike.com/en-us/blog/adversaries-turn-vulnerability-ecosystem-against-defenders/)
- [CrowdStrike Extends the Agentic SOC to Detect and Stop Agent Insider Threats](https://www.crowdstrike.com/en-us/blog/crowdstrike-detects-and-stops-agent-insider-threats/)
- [CrowdStrike Introduces Agentic Adversary Emulation to Counter AI-Enabled Adversaries](https://www.crowdstrike.com/en-us/blog/crowdstrike-agentic-adversary-emulation-counters-ai-enabled-adversaries/)
- [New Falcon Cloud Security Innovations Secure the Cloud AI Runs On](https://www.crowdstrike.com/en-us/blog/falcon-cloud-security-innovations-secure-cloud-ai-runs-on/)

### FortiGuard Threat Signal
- [Java4Shell](https://fortiguard.fortinet.com/threat-signal-report/6668)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal