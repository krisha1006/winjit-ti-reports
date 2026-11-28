# Winjit Daily TI Digest — 2026-11-28

_Auto-generated. Window: last ~24h. Fetched at 2026-11-28T11:29:47.719050+00:00Z_

**At a glance:** 3 new KEV · 48 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-120705 | OSGeo | GeoServer | OSGeo GeoServer XML Injection Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-129243 | OSGeo | GeoServer | OSGeo GeoServer Incorrect Authorization Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-136716 | Drupal | Core | Drupal Core Improper Check for Unusual or Exceptional Conditions Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-138004 | 10.0 | n/a | A security vulnerability has been detected in TRENDnet TEW-751DR and TEW-733GR 1.03B01. Affected is the function soapcgi_main of the file /soap.cgi of the component UPnP Igd Control Endpoint. Such man |
| CVE-2026-138005 | 10.0 | n/a | A vulnerability was detected in TRENDnet TEW-751DR 1.03B01. Affected by this vulnerability is the function gena.php::GENA_notify_init of the file htdocs/upnpinc/gena.php of the component UPnP Event Ha |
| CVE-2026-137706 | 9.9 | 0.5% | Smart Portal developed by Direk Tech has a Missing Authorization vulnerability. Authenticated remote attackers can add a specified account to the Active Directory Domain Admins group, thereby obtainin |
| CVE-2026-106125 | 9.8 | 1.2% | The Sneeit Framework plugin for WordPress is vulnerable to Remote Code Execution in versions up to, and including, 8.7 via the 'callback' parameter of the sneeit_compact_menu_mega_content AJAX action. |
| CVE-2026-115867 | 9.8 | 0.9% | The Database for Contact Form 7, WPforms, Elementor forms plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 1.5.5 via the copy_files function. This is d |
| CVE-2026-137964 | 9.8 | n/a | ToolJet before 3.21.96-LTS contains a command injection vulnerability in its GitHub Actions release workflow, which interpolates the pull request title directly into a shell run block. Attackers can s |
| CVE-2026-138003 | 9.0 | n/a | A weakness has been identified in TRENDnet TEW-751DR 1.03B01. This impacts the function FUN_0040ed90 of the file wfadev.cgi of the component UPnP/WFA. This manipulation of the argument SOAPAction caus |
| CVE-2026-113774 | 8.8 | 0.5% | The Schema & Structured Data for WP & AMP plugin for WordPress is vulnerable to PHP Object Injection in versions up to, and including, 1.68. This is due to deserialization of untrusted input via the a |
| CVE-2026-137704 | 8.8 | 0.3% | D-Link DWM-222W developed by D-Link Corporation has a Use of Hard-coded Credentials vulnerability. Unauthenticated adjacent network attackers can use the administrator account embedded in the firmware |
| CVE-2026-138119 | 8.8 | n/a | Kestra before 1.3.36 contains a reflected cross-site scripting vulnerability that allows unauthenticated attackers to execute JavaScript by injecting HTML into the executions page sort parameter. Atta |
| CVE-2026-137953 | 8.6 | n/a | Pydantic Deep 0.2.18 before 0.4.0 contains a missing authentication vulnerability in the bundled DeepResearch FastAPI app that exposes HTTP routes and the /ws/chat WebSocket. Remote attackers reaching |
| CVE-2026-138154 | 8.6 | n/a | POSTAL 2 before build 26810491 contains a sandbox escape vulnerability that allows malicious Steam Workshop mods to execute code by calling ConsoleCommand with a start file URI. Attackers can ship a b |
| CVE-2026-133842 | 8.2 | 0.2% | A flaw was found in Flatpak’s flatpak-system-helper. When a system-wide app, runtime, or extension uses the extra-data mechanism and its apply_extra logic creates a deeply nested directory tree, permi |
| CVE-2026-137957 | 8.2 | n/a | n8n before 1.123.96, 2.47.6, 2.48.3, and 3.2.2 contains a path traversal vulnerability in integration nodes that build API request paths from unencoded record, table, or resource ID parameters. Attack |
| CVE-2026-137959 | 8.2 | n/a | n8n before 1.123.96, 2.x before 2.47.6, 2.48.x before 2.48.3, and 3.x before 3.2.2 does not verify that the user activating a workflow can access the credentials set on its trigger nodes. An authentic |
| CVE-2026-119071 | 8.1 | 0.8% | The W3 Total Cache plugin for WordPress is vulnerable to unauthorized File Deletion in all versions up to, and including, 2.11.0 via the `ajax_revert()` AJAX handler. The vulnerability exists because  |
| CVE-2026-137994 | 7.8 | n/a | Leo through 6.8.10 contains an insecure deserialization vulnerability that allows attackers to execute code by embedding pickled data in unknown XML attributes of .leo outlines. Attackers can place a  |
| CVE-2026-137997 | 7.8 | n/a | HCIPy through 0.7.1 contains an insecure deserialization vulnerability that allows attackers to execute code by supplying crafted .pkl files to read_field, read_grid or read_mode_basis. Because hcipy/ |
| CVE-2026-137998 | 7.8 | n/a | Detoxify 0.5.3 through 0.5.4 contains an insecure deserialization vulnerability in load_checkpoint that allows attackers to execute code by supplying a crafted checkpoint file. Attackers can embed a p |
| CVE-2026-137999 | 7.8 | n/a | JSONSchema2PoPo2 through 3.0.3 contains a code injection vulnerability that allows attackers to inject Python code by supplying JSON Schema default or format values that are written unescaped. Attacke |
| CVE-2026-137941 | 7.8 | n/a | A flaw was found in GIMP. The Levels configuration setter does not validate the channel enum before using it to index fixed-size per-channel arrays. A crafted XCF file with a non-destructive Levels fi |
| CVE-2026-138117 | 7.8 | n/a | HyperSpy from 1.2.0 before 2.6.0 contains a code execution vulnerability that allows attackers to run Python code by embedding malicious expression strings evaluated with sympy.sympify(). Attackers ca |
| CVE-2026-138118 | 7.8 | n/a | HyperSpy from 1.4.0 before 2.6.0 contains an insecure deserialization vulnerability that allows attackers to execute arbitrary Python code by supplying crafted stored-model data in .hspy or .zspy file |
| CVE-2026-138160 | 7.8 | n/a | Gammu before 1.45.2 contains a stack-based buffer overflow vulnerability in ReadBackupTextLen() that allows attackers to overwrite stack memory via crafted backup files. Attackers can supply overlong  |
| CVE-2026-138161 | 7.8 | n/a | Gammu before 1.45.2 contains a buffer overflow vulnerability in LoadBackup() that allows attackers to corrupt memory by supplying an overlong MD5 value in a crafted backup file. Attackers can overwrit |
| CVE-2026-138163 | 7.8 | n/a | Gammu before 1.45.2 contains a heap-based buffer overflow in ReadWAPSettingsEntry() that allows attackers to corrupt heap memory via crafted backup files with excess WAP or MMS settings entries. Attac |
| CVE-2026-132876 | 7.7 | n/a | Dreamweaver Desktop is affected by a Dependency on Vulnerable Third-Party Component vulnerability that could result in arbitrary code execution in the context of the current user. An attacker could ex |
| CVE-2026-135616 | 7.5 | 0.7% | The W3 Total Cache plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 2.11.0 via deserialization of untrusted input that is injected into the Memcached ob |
| CVE-2026-137705 | 7.5 | 0.8% | Smart Portal developed by Direk Tech has an Arbitrary File Read vulnerability.Unauthenticated remote attackers can exploit Relative Path Traversal to download arbitrary system files. |
| CVE-2026-135626 | 7.5 | 0.5% | The Simple Membership plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 4.9.0 This is due to the `SwpmLevelForm::role()` function applying only `sanitize |
| CVE-2026-137952 | 7.5 | n/a | svglib before 2.5.0 contains a denial of service vulnerability in SvgRenderer.renderNode() that recursively renders internal <image> href fragment references without expansion limits or cycle detectio |
| CVE-2026-137977 | 7.5 | n/a | Nmap before 7.992 contains a use-after-free vulnerability in DNS::ResolverImpl::handle_write in libnetutil/massdns.cc that dereferences freed request objects after writes complete. Attackers controlli |
| CVE-2026-137978 | 7.5 | n/a | Nmap before 7.992 contains a use-after-free vulnerability in DNS::ResolverImpl::process_request in libnetutil/massdns.cc that frees still-referenced requests when rescheduling after DNS server disconn |
| CVE-2026-137992 | 7.5 | n/a | libexpat through 2.11.0 contains a denial of service vulnerability in defineAttribute() of lib/xmlparse.c that fails to detect duplicate non-ID #IMPLIED or #REQUIRED attribute declarations. Attackers  |
| CVE-2026-134129 | 7.5 | n/a | smalot/pdfparser before 2.14.0 contains an inefficient algorithmic complexity vulnerability that allows remote attackers to cause a denial of service by submitting a crafted PDF with deeply nested unb |
| CVE-2026-138027 | 7.5 | n/a | Bagel (bagel-mcp) before 2.5.5 exposes unsandboxed DuckDB SQL execution through the read-only annotated query_messages MCP tool, allowing file access and network requests. Attackers who prompt-inject  |
| CVE-2026-138028 | 7.5 | n/a | Bagel (bagel-mcp) before 2.5.5 contains an argument injection vulnerability in RsyncFilesToLocalDirectory that allows attackers to inject rsync options because only --quiet and --log-format values are |
| CVE-2026-138034 | 7.5 | n/a | bigcommerce-api-mcp before 1.0.1 contains a missing authentication vulnerability that allows remote unauthenticated attackers to invoke MCP tools because the /sse and /messages routes skip the authent |
| CVE-2026-138159 | 7.5 | n/a | edbrowse through 3.8.19 contains an integer overflow in stringAndBytes() that allows malicious servers to write past a heap buffer by sending response bodies larger than 2 GB. When a user browses to a |
| CVE-2026-137677 | 7.3 | 0.3% | A vulnerability has been found in code-projects Simple Laundry System 1.0. This affects an unknown function of the file viewdetailforuser.php. The manipulation of the argument serviceId leads to sql i |
| CVE-2026-137678 | 7.3 | 0.4% | A security vulnerability has been detected in code-projects Online Job Portal 1.0. Affected by this issue is some unknown functionality of the file Admin/InsertUser.php. Such manipulation of the argum |
| CVE-2026-133845 | 7.3 | 0.3% | A flaw was found in Flatpak’s flatpak-portal. When a sandboxed application invokes Spawn() and maps two different file descriptors to the same handle, dup2() can fail. Affected Flatpak versions do not |
| CVE-2026-137684 | 7.3 | n/a | A security flaw has been discovered in eosphoros-ai DB-GPT up to 0.8.3. This affects the function editor_sql_run of the file packages/dbgpt-app/src/dbgpt_app/openapi/api_v1/editor/api_editor_v1.py of  |
| CVE-2026-137898 | 7.3 | n/a | A flaw was found in pam. When built with libeconf and an unconfigured vendor directory, the pam_econf configuration handler misinterprets the search path, causing it to look for configuration files in |
| CVE-2026-138026 | 7.3 | n/a | Crypto APIs MCP server packages (@cryptoapis-io/mcp-*) before 0.4.0, mcp-blockchain-events, mcp-blockchain-fees, mcp-broadcast and mcp-prepare-transactions before 0.5.0, and mcp-aml before 0.2.0 conta |
| CVE-2026-136995 | 7.2 | 0.4% | The Upsell Funnel Builder for WooCommerce – Create Upsells, Cross-Sells, Order Bumps, Frequently Bought, and Popups. plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'form_dat |
| CVE-2026-137974 | 7.0 | n/a | A flaw was found in tuned. This vulnerability allows local privilege escalation because the spindown-disk profile script does not properly validate filesystem mount sources before executing remount op |
| CVE-2026-138162 | 7.0 | n/a | Gammu before 1.45.2 contains a stack-based buffer overflow vulnerability in ALCATEL_EncodeString() that allows attackers to overwrite stack memory via oversized encoded phonebook text. Attackers can s |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-9w6h-rf45-6px6 | CVE-2026-123654 | unknown | Themify Base WordPress theme through 1.2.4 does not perform capability checks on its option save... |
| GHSA-wmmj-7mm6-26mg | CVE-2026-112235 | unknown | The Popup Builder  WordPress plugin through 4.4.6 does not properly check authorization before... |
| GHSA-hph8-cfc5-f2m8 | CVE-2026-112234 | unknown | The Popup Builder  WordPress plugin through 4.4.6 does not validate a user-supplied URL before... |
| GHSA-rf22-v3ph-4gc4 | CVE-2026-112233 | unknown | The Popup Builder  WordPress plugin through 4.4.6 does not check the publish status or the... |
| GHSA-gxm7-4f7h-pc43 | CVE-2026-112232 | unknown | The Popup Builder  WordPress plugin through 4.4.6 does not properly sanitize and escape a popup... |
| GHSA-5qxw-r587-h52h | CVE-2026-112231 | unknown | The Popup Builder  WordPress plugin through 4.4.6 does not sanitise or escape a custom styling... |
| GHSA-9gmm-wvwr-7r73 | CVE-2026-138160 | high | Gammu before 1.45.2 contains a stack-based buffer overflow vulnerability in ReadBackupTextLen()... |
| GHSA-x549-h79p-3567 | CVE-2026-138161 | high | Gammu before 1.45.2 contains a buffer overflow vulnerability in LoadBackup() that allows... |
| GHSA-qvrw-322v-v5fc | CVE-2026-138164 | medium | Gammu before 1.45.2 contains a stack-based buffer overflow vulnerability in SaveBackupText() in... |
| GHSA-gr2c-gxjj-cc7v | CVE-2026-138162 | high | Gammu before 1.45.2 contains a stack-based buffer overflow vulnerability in ALCATEL_EncodeString(... |
| GHSA-frvx-qrj8-74hh | CVE-2026-138163 | high | Gammu before 1.45.2 contains a heap-based buffer overflow in ReadWAPSettingsEntry() that allows... |
| GHSA-3x93-mq8m-pp9j | CVE-2026-138159 | high | edbrowse through 3.8.19 contains an integer overflow in stringAndBytes() that allows malicious... |
| GHSA-57qr-c6wx-f722 | CVE-2026-138158 | high | libgphoto2 through 2.5.34 contains a stack buffer overflow in sierra_get_string_register() that... |
| GHSA-8jqc-ggvr-rpj6 | CVE-2026-138154 | critical | POSTAL 2 before build 26810491 contains a sandbox escape vulnerability that allows malicious... |
| GHSA-hq77-9vj4-h457 | CVE-2026-138153 | medium | Otter – Page Builder Blocks & Extensions for Gutenberg before 3.2.12 contains an incorrect... |
| GHSA-92v3-vw2j-4v56 | CVE-2026-138152 | medium | Otter – Page Builder Blocks & Extensions for Gutenberg before 3.2.12 contains a server-side... |
| GHSA-c68x-j5fv-6w36 | CVE-2026-138151 | high | bgpq4 before 1.17 contains an integer overflow vulnerability in expander.c that allows malicious... |
| GHSA-v9jq-rpx4-2cwc | CVE-2026-138122 | low | ClassroomIO through 1.0.0 contains an insecure direct object reference vulnerability that allows... |
| GHSA-xf29-59h2-f9gj | CVE-2026-138148 | medium | picomatch through 4.0.7 contains a glob filter bypass vulnerability because globstar (**)... |
| GHSA-3f8c-9f35-p7hr | CVE-2026-138119 | high | Kestra before 1.3.36 contains a reflected cross-site scripting vulnerability that allows... |
| GHSA-2xjf-686p-8f4f | CVE-2026-138150 | medium | SimGear through 2024.1.7 contains an infinite loop vulnerability in sgSimpleBuffer::resize()... |
| GHSA-9j4c-g9j8-3qhj | CVE-2026-138149 | medium | FeatBit before 6.1.3 contains an authorization bypass vulnerability that allows authenticated... |
| GHSA-3pm5-4cwg-5rmr | CVE-2026-138121 | high | Kestra 1.3.24 before 1.3.41 contains an insufficient credential expiration vulnerability that... |
| GHSA-vcvv-9cv9-c963 | CVE-2026-138120 | medium | Kestra 1.3.24 before 2.0.0 contains a timing side-channel vulnerability in BasicAuthService... |
| GHSA-9qmf-m9r2-5w65 | CVE-2026-138117 | high | HyperSpy from 1.2.0 before 2.6.0 contains a code execution vulnerability that allows attackers to... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Samlut and Company, P.A. | incransom | US | 2026-11-27T23:00:19.875313+00:00 |
| Cinelandia S.p.A | incransom | IT | 2026-11-27T21:46:09.068678+00:00 |
| Brit Ltd / Brit Insurance (britinsurance.com) | incransom | GB | 2026-11-27T16:10:45.427021+00:00 |
| rogers-group | iah6477 | CA | 2026-11-27T15:09:03.482985+00:00 |
| blackstone-consulting | iah6477 | US | 2026-11-27T15:08:36.366456+00:00 |
| supplyone | iah6477 |  | 2026-11-27T15:08:09.423313+00:00 |
| Ferrometalco (FMC) | SoulGroup | CO | 2026-11-27T14:58:55.744068+00:00 |
| US CNC Machine Company | SoulGroup | US | 2026-11-27T14:58:16.770093+00:00 |
| avispl | iah6477 | US | 2026-11-27T14:13:22.305438+00:00 |
| resers | iah6477 |  | 2026-11-27T14:12:55.011868+00:00 |
| RHRS Law Firm | Barracuda |  | 2026-11-27T13:50:52.805478+00:00 |
| VC ERP Consulting Pvt. Ltd. | rhysida | IN | 2026-11-27T11:32:52.949834+00:00 |
| pregis | iah6477 | US | 2026-11-27T08:43:28.332506+00:00 |
| SternKlinik (medi-z Bremen GmbH) | spacebears | DE | 2026-11-27T03:51:24.060440+00:00 |
| Elektro-Ruppen | bravox | CH | 2026-11-27T00:58:27.884689+00:00 |
| Wolters Kluwer | direwolf | NL | 2026-11-27T01:02:46.848958+00:00 |
| Thomas More University of Applied Sciences | qilin | BE | 2026-11-28T03:44:02.468503+00:00 |
| Thomas More University | qilin | BE | 2026-11-27T06:44:27.409518+00:00 |
| Monolithic Power Systems (NASDAQ: MPWR, mps.com) | PixelLeaks | US | 2026-11-26T23:32:02.466288+00:00 |
| Keyes Financial Strategies Inc. | PixelLeaks |  | 2026-11-26T23:31:41.412340+00:00 |

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
| 64.62.197.32 | 9 |
| 86.54.31.34 | 9 |
| 92.207.4.157 | 9 |
| 102.220.161.85 | 9 |
| 103.159.199.43 | 9 |
| 103.248.120.6 | 9 |
| 193.47.62.149 | 9 |
| 193.47.62.152 | 9 |
| 193.47.62.153 | 9 |
| 2.57.121.25 | 8 |
| 2.57.121.112 | 8 |
| 27.102.116.43 | 8 |
| 35.206.150.39 | 8 |
| 35.206.151.191 | 8 |
| 35.206.167.114 | 8 |
| 35.210.24.61 | 8 |
| 35.210.73.217 | 8 |
| 45.148.10.61 | 8 |
| 58.182.58.128 | 8 |
| 58.221.60.25 | 8 |

### OpenPhish (live phishing URLs)
- http://f0undersfirm.com/home
- https://www.hadiah-telkomsel95.blogspot.com/
- https://hadiah-telkomsel95.blogspot.com/
- http://hadiah-ke2telkomsel1.blogspot.com/
- http://www.hadiah-ke2telkomsel1.blogspot.com/
- http://hadiah-telkomsel4343.blogspot.com/
- http://5fbd3-4pl-ih6s-05yzn-20-10-2026-aa.pages.dev/
- https://confirmarlogin365.yzz.me/
- http://c0nf1rmessent3valid65.gt.tc/
- http://icb.lat/wd1/index.php
- http://www.wrtyuuuu.weebly.com/
- http://aditya18633.github.io/First-project_Amazon-clone
- https://na-apple9.xyz/
- http://na-apple11.xyz/
- https://na-apple12.xyz/
- http://na-apple16.xyz/
- http://a-apple7.xyz/
- http://na-apple4.xyz/
- http://na-apple6.xyz/
- http://b-apple11.xyz/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| 7.8 | https://allegrolokalnie.pl-oferta90230982390.cfd/ |
| 8.1 | https://allegro.pl-oferta90230982390.cfd/playstation-5-slim-digital-z-2-p/ciwuyhw |
| 7.1 | https://qr-2dcode.com/ |
| 6.9 | https://registre-eu.org/activation |
| 7.2 | http://getdigicore.com/Docusign/ |
| 8 | http://allegro.allegrolokalnie.top |
| 8 | http://olx.allegrolokalnie.top |
| 7 | https://albumpipe.xyz/MB8SGE200SGMK0938-insights-into-the-future-of-virtual-reality/ |
| 7.6 | https://sucrsalpsnsvrl.netlify.app/ |
| 7.7 | https://dfghjcvbnm.weebly.com/ |
| 4.9 | https://mvm-next.ellectrical.com/ |
| 8.1 | https://myxmaiill.square.site/ |
| 7.2 | https://mvm-next.ellectrical.com/hu20261111/belp342231/ |
| 8.6 | https://sucrsalpsnsvrl.netlify.app/portal/home/login.html |
| 5.7 | https://mvm-next.ellectrical.com/hu20261111/ |
| 7.5 | https://sg5513.craftum.io/ |
| 7.2 | https://mvm-next.ellectrical.com/hu20261111/belp342231/kartya.php |
| 7.1 | https://viaverde-portagenspt.com/ |
| 7.8 | https://serasa-score.vercel.app/ |
| 6 | https://vrhkj.com |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| 611441266f8dfe1b47f0f7e6aa504617e1f4d981 | Vidar C&C |
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
- 1.117.72.220
- 1.12.252.163
- 1.13.156.111
- 1.141.32.230
- 1.183.25.86
- 1.192.216.175
- 1.194.211.36
- 1.196.78.87
- 1.201.146.109
- 1.212.225.99
- 1.214.204.138
- 1.214.214.114
- 1.215.233.74
- 1.220.198.126
- 1.222.42.237
- 1.222.80.212
- 1.226.84.248
- 1.234.21.73
- 1.234.27.159

### CINS Army (poorly-rated IPs)
- 1.117.232.51
- 1.13.17.224
- 1.15.14.29
- 1.168.206.193
- 1.170.195.220
- 1.170.243.169
- 1.189.41.213
- 1.192.129.106
- 1.193.63.117
- 1.193.63.156
- 1.193.63.196
- 1.193.63.91
- 1.198.30.247
- 1.20.187.233
- 1.208.108.242
- 1.214.29.155
- 1.24.16.101
- 1.24.16.108
- 1.24.16.118
- 1.24.16.119

## News (last ~36h, across outlets)
### The Hacker News
- [pCloud Password Manager Hit by Cyber Attack Involving Email Address Exposure and Login Attempts](https://thehackernews.com/2026/11/pcloud-password-manager-hit-by-cyber.html)
- [Suspected Vietnam-Linked Hackers Target Southeast Asia in South China Sea Espionage Campaign](https://thehackernews.com/2026/11/suspected-vietnam-linked-hackers-target.html)
- [Microsoft Store App Found Delivering Vinci RAT Capable of Remote System Control](https://thehackernews.com/2026/11/microsoft-store-app-found-delivering.html)
- [How to Keep Your Security Picture Current When Attackers Move at AI Speed](https://thehackernews.com/2026/11/how-to-keep-your-security-picture.html)
- [Hackers Trojanize Official Q-Dir and DesktopOK Downloads to Deliver Remote Access Malware](https://thehackernews.com/2026/11/hackers-trojanize-official-q-dir-and.html)
- [Switzerland Confirms AI-Assisted Cyberattacks Breached Critical Infrastructure Operators](https://thehackernews.com/2026/11/switzerland-confirms-ai-assisted.html)
- [Unpatched Cacti Zero-Day Enables RCE in Just Four HTTP Requests via Guest Access](https://thehackernews.com/2026/11/unpatched-cacti-zero-day-enables-rce-in.html)

### BleepingComputer
- [pCloud confirms password manager hack after suspicious login alerts](https://www.bleepingcomputer.com/news/security/pcloud-confirms-password-manager-hack-after-suspicious-login-alerts/)
- [New Boston Scientific data breach exposes personal, medical info](https://www.bleepingcomputer.com/news/security/new-boston-scientific-data-breach-exposes-personal-medical-info/)
- [Unpatched Cacti zero-day with public PoC gives remote code execution](https://www.bleepingcomputer.com/news/security/unpatched-cacti-zero-day-with-public-poc-gives-remote-code-execution/)
- [US Air Force cloud platform reportedly hacked in latest federal breach](https://www.bleepingcomputer.com/news/security/us-air-force-cloud-platform-reportedly-hacked-in-latest-federal-breach/)
- [Your Firewall Isn't Enough: The Hidden Risk of Unmanaged VMs](https://www.bleepingcomputer.com/news/security/your-firewall-isnt-enough-the-hidden-risk-of-unmanaged-vms/)
- [Malwarebytes Antivirus: Get 50% off during Black Friday 2026](https://www.bleepingcomputer.com/news/security/malwarebytes-antivirus-get-50-percent-off-during-black-friday-2026/)
- [Microsoft removes WSUS server role in Windows Server 2028](https://www.bleepingcomputer.com/news/microsoft/microsoft-removes-wsus-server-role-in-windows-server-2028/)
- [Drupal warns of new site takeover flaw exploited in attacks](https://www.bleepingcomputer.com/news/security/drupal-warns-of-new-access-bypass-flaw-exploited-in-attacks/)
- [SAP confirms security incident after suspicious GitHub activity](https://www.bleepingcomputer.com/news/security/sap-confirms-security-incident-after-suspicious-github-activity/)
- [Microsoft pushes emergency hotpatch to fix Windows Server crashes](https://www.bleepingcomputer.com/news/microsoft/new-out-of-band-oob-emergency-hotpatch-fixes-windows-server-2025-crashes/)
- [New NFS2ROOT Linux flaw can let attackers gain root privileges](https://www.bleepingcomputer.com/news/security/new-nfs2root-linux-flaw-can-let-attackers-gain-root-privileges/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [Matters.AI Lands India’s Largest Cybersecurity Pre-Series A Round to Fight AI Data Risks](https://www.darkreading.com/cyber-risk/matters-india-cybersecurity-pre-series-ai-data-risks)
- ['God Mode' Flaws Could Wreak Border-Control Havoc](https://www.darkreading.com/vulnerabilities-threats/god-mode-flaws-wreak-border-control-havoc)

### SecurityWeek
- [In Other News: Tanker Cyberattacks, EU Quantum Act, New VirusTotal Capabilities](https://www.securityweek.com/in-other-news-tanker-cyberattacks-eu-quantum-act-new-virustotal-capabilities/)
- [100,000 Potentially Impacted by Colorado Data Breach](https://www.securityweek.com/100000-potentially-impacted-by-colorado-data-breach/)
- [Hex Package Manager Warns of Potential Data Breach](https://www.securityweek.com/hex-package-manager-warns-of-potential-data-breach/)
- [SAP Confirms Cyberattack, Source Code Reportedly Compromised](https://www.securityweek.com/sap-confirms-cyberattack-source-code-reportedly-compromised/)

### The Record
- [Japan’s education ministry discloses breach of government procurement system](https://therecord.media/japan-education-ministry-cyberattack)
- [Software giant SAP confirms cyber incident amid reports of source code breach](https://therecord.media/sap-germany-cyberattack-github)
- [Cyberattack disrupts global news distribution platform at France’s AFP](https://therecord.media/france-afp-hit-by-cyberattack)
- [British government takes services offline following ‘cyber incident’](https://therecord.media/uk-department-work-pensions-cyber-incident)

### Infosecurity Magazine
- [UK Welfare and Pension Services Taken Offline Following Cyber Incident](https://www.infosecurity-magazine.com/news/uk-welfare-services-offline/)
- [FIFA Confirms Cyber-Attack, Personal and Business Information Compromised](https://www.infosecurity-magazine.com/news/fifa-confirms-cyberattack/)
- [CyberStrikeAI Creator Shuts Down Open-Source AI Offensive Framework](https://www.infosecurity-magazine.com/news/cyberstrikeai-shut-down-threatbook/)

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
_No new items / feed unavailable this run._

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal