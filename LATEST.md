# Winjit Daily TI Digest — 2026-11-26

_Auto-generated. Window: last ~24h. Fetched at 2026-11-26T12:04:21.718897+00:00Z_

**At a glance:** 10 new KEV · 59 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-103406 | Hewlett Packard Enterprise (HPE) | Juniper Session Smart Conductor and Session Smart Router | Hewlett Packard Enterprise (HPE) Juniper Session Smart Conductor and Session Smart Router OS Command Injection Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-133469 | Vates | Xen Orchestra | Vates Xen Orchestra Improper Validation of Specified Type of Input Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2025-41450 | Danfoss | AK-SM 800A Series | Danfoss AK-SM 800A Series Improper Authentication Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2023-25914 | Danfoss | AK-SM 800A Series | Danfoss AK-SM 800A Series Path Traversal Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2023-25915 | Danfoss | AK-SM 800A Series | Danfoss AK-SM 800A Series Improper Input Validation Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-133324 | Mitel | MiCollab | Mitel MiCollab Not Failing Securely Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-133275 | Mitel | MiCollab | Mitel MiCollab Unrestricted Upload of File with Dangerous Type Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-133311 | Mitel | MiCollab | Mitel MiCollab Weak Authentication Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-133303 | Mitel | MiCollab | Mitel MiCollab XML Injection Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-133323 | Mitel | MiCollab | Mitel MiCollab OS Command Injection Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-136136 | 10.0 | 0.9% | A vulnerability was identified in Netis WF2409E up to 20261026. Affected by this issue is some unknown functionality of the file /cgi-bin/skk_set.cgi of the component CGI Interface. The manipulation o |
| CVE-2026-136548 | 10.0 | 0.9% | A vulnerability was identified in Tenda RX3 16.03.13.11. The affected element is an unknown function of the file /bin/auto_discover of the component GBK-to-UTF-8 Conversion. The manipulation of the ar |
| CVE-2026-136549 | 10.0 | 2.2% | A security flaw has been discovered in Tenda RX3 16.03.13.11_multi. The impacted element is the function formSetSafeWanWebMan of the file /goform/SetRemoteWebCfg. The manipulation of the argument remo |
| CVE-2026-136553 | 10.0 | 1.1% | A vulnerability was detected in Tenda RX3 16.03.13.11_multi. Affected is an unknown function of the file /goform/fast_setting_wifi_set. Performing a manipulation of the argument loginPwd results in im |
| CVE-2026-136823 | 10.0 | n/a | A vulnerability was found in D-Link R32 1.10B02. This affects an unknown function of the file /usr/bin/httpd of the component flupl self Endpoint. Performing a manipulation of the argument fpath resul |
| CVE-2026-137043 | 10.0 | n/a | A security vulnerability has been detected in TOTOLINK N350RT 9.3.5u.6468_B20250827/9.3.5u.6466_B20250825. The affected element is the function setLanguageCfg of the file /cgi-bin/cstecgi.cgi. Such ma |
| CVE-2026-136821 | 9.9 | n/a | A flaw has been found in D-Link R32 1.10B02. The affected element is the function SetTimeSettings of the component DHMAPI Action Handler. This manipulation of the argument TZLocation causes os command |
| CVE-2026-136822 | 9.9 | n/a | A vulnerability has been found in D-Link R32 1.10B02. The impacted element is the function SetDeviceSettings of the file /usr/bin/httpd of the component DHMAPI Action Handler. Such manipulation of the |
| CVE-2026-82489 | 9.8 | n/a | openIMIS before 2026-10 contains an unauthenticated remote code execution vulnerability in the report module (openimis-be-report_py) where the /api/report/reportbro/preview endpoint evaluates printIf  |
| CVE-2026-137090 | 9.8 | n/a | build-git-clone before 1.0.4 contains an OS command injection vulnerability in the clone() function that allows attackers to execute commands by supplying crafted repository URLs. Attackers can embed  |
| CVE-2026-136550 | 9.1 | 3.0% | A weakness has been identified in Tenda RX3 16.03.13.11_multi. This affects the function fromAdvSetMacMtuWan of the file /goform/AdvSetMacMtuWan. This manipulation of the argument mac causes command i |
| CVE-2026-82493 | 8.8 | n/a | openIMIS before 2026-10 contains a remote code execution vulnerability in the report module's overrideReport GraphQL mutation, which stores submitted report definitions without proper validation befor |
| CVE-2026-64845 | 8.8 | n/a | KubeSphere 4.0.0 through 4.1.3 contains a missing authorization vulnerability in the CertificateSigningRequest controller that allows attackers with permission to create CertificateSigningRequest obje |
| CVE-2026-73517 | 8.8 | n/a | KubeSphere 4.0.0 through 4.1.3 contains a command injection vulnerability in the terminal v1alpha2 file download endpoint where the path query parameter is inserted via fmt.Sprintf into sh -c tar comm |
| CVE-2026-137056 | 8.8 | n/a | DeepSeek-Reasonix before 2.53.0 contains a command execution vulnerability that allows attackers to run commands without user approval because the shellsafe classifier treats git blame and git whatcha |
| CVE-2026-66052 | 8.8 | n/a | Comviva Revenue Plus (MobiLytix Customer Value Management) 3.0.0 contains an expression language injection vulnerability in the user administration module, where the POST /rp/manageUser endpoint handl |
| CVE-2026-69695 | 8.8 | n/a | Handesk through 1.5 contains an unrestricted file upload vulnerability in Attachment::storeAttachmentFromRequest() that allows authenticated agents to upload files with arbitrary extensions by attachi |
| CVE-2026-137305 | 8.8 | n/a | Grav Form plugin before 9.2.4 contains a code injection vulnerability that allows page authors to write uploads into Twig template folders by setting an unchecked file field destination in Form::uploa |
| CVE-2026-137389 | 8.8 | n/a | MailGates/MailAudit developed by Openfind has a Command Injection vulnerability.Authenticated remote attackers can inject commands and execute them on the server. |
| CVE-2026-137390 | 8.8 | n/a | Mail2000 developed by Openfind has an OS Command Injection vulnerability.Authenticated remote attackers can inject arbitrary OS commands and execute them on the server. |
| CVE-2026-66784 | 8.7 | n/a | A flaw was found in Submariner. In its default Pre-Shared Key (PSK) mode, all gateways within a broker set utilize the same PSK. An attacker, by knowing this shared PSK, can forge an Endpoint Custom R |
| CVE-2026-136626 | 8.2 | 0.8% | SRS 4.0.0 before 6.0.194, 7.0.0 before 7.0.214, and 8.0.0 before 8.0.73 contains a heap-based buffer overflow in SrsRtcpCommon::decode and SrsRtcpTWCC::decode that lets remote WebRTC peers write past  |
| CVE-2026-136920 | 8.1 | n/a | OneDev before 17.2.4 contains an argument injection vulnerability in commit query handling that allows authenticated attackers to inject git options through branch or tag names. Attackers can push a b |
| CVE-2026-77230 | 8.1 | n/a | Camunda 8.8.0 before 8.8.47, 8.9.0 before 8.9.29, 8.10.0 before 8.10.10, and 8.11.0-alpha1 contain an insecure deserialization vulnerability in the persistent web session feature, which stores session |
| CVE-2026-137086 | 8.1 | n/a | Teracom TCW122B-CM firmware before 4.07 contains a predictable session cookie vulnerability that allows unauthenticated remote attackers to hijack administrator sessions by guessing tick-counter-deriv |
| CVE-2026-130805 | 8.1 | n/a | The Groundhogg plugin for WordPress is vulnerable to Cross-Site Request Forgery in versions up to, and including, 4.11 This is due to the Admin_Page::page() callback dispatching methods named directly |
| CVE-2026-136629 | 7.8 | 0.3% | Nektos act 0.2.92 before 0.2.95 contains an argument injection vulnerability in readProjectArgsFile and projectFlag that allows malicious repositories to bypass the untrusted project .actrc flag allow |
| CVE-2026-136919 | 7.8 | n/a | FCEUX 2.5.0 before 2.8.0 contains an integer overflow in iNESLoad() in src/ines.cpp that allows a crafted NES 2.0 ROM to write past a heap buffer. Attackers can persuade users to open a .nes file usin |
| CVE-2026-136923 | 7.8 | n/a | asar-py before 0.1.4 contains a path traversal vulnerability in AsarArchive.extract() and extract_archive() that allows attackers to write files outside the destination directory via crafted archive h |
| CVE-2026-136329 | 7.8 | n/a | A flaw was found in the file-gif-load plugin in GIMP. When processing a specially crafted JIF image file, a 32-bit integer overflow occurs during the pixel buffer size calculation, while the zlib outp |
| CVE-2026-137060 | 7.8 | n/a | paramz through 0.10.0 contains an insecure deserialization vulnerability that allows attackers to execute code by supplying crafted model files to paramz.load(), which calls pickle.load() without rest |
| CVE-2026-137093 | 7.8 | n/a | Assimp before 6.0.6 contains an out-of-bounds write vulnerability in MD5Importer::LoadMD5MeshFile() that allows attackers to corrupt heap memory via unvalidated weight ranges and bone indices. Attacke |
| CVE-2026-135772 | 7.6 | n/a | RTL8762C MCU developed by Realtek Semiconductor Corporation has an Improper Protection Against Voltage and Clock Glitches vulnerability. Unauthenticated attackers with physical access can use speciali |
| CVE-2026-136630 | 7.5 | 0.4% | Electerm before 5.9.0 contains an origin validation vulnerability in the MCP Server widget that allows remote attackers to execute commands by bypassing Host and Origin checks through DNS rebinding. A |
| CVE-2026-134642 | 7.5 | 0.7% | Webmin through 2.670 contains a missing authentication vulnerability in fastrpc.cgi that allows unauthenticated network peers to connect to tcpwrite and tcpread file-transfer listeners without session |
| CVE-2026-137057 | 7.5 | n/a | llama.cpp from b7118 before b12604 contains an integer underflow vulnerability in llama_grammar_parser::parse_sequence() that allows unauthenticated remote attackers to cause denial of service by supp |
| CVE-2026-137058 | 7.5 | n/a | Cron-parser through 5.10.0 contains an unbounded memory allocation vulnerability in CronExpressionParser.parse() that allows unauthenticated attackers to exhaust memory by supplying oversized cron fie |
| CVE-2026-124211 | 7.5 | n/a | The Ninja Tables – Responsive Table Builder for Data, Pricing & Product Tables plugin for WordPress is vulnerable to SQL Injection via the 'dateFormat' column metadata parameter in versions up to, and |
| CVE-2026-135151 | 7.5 | n/a | The Download Manager plugin for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 3.3.78 via the 'file[page_template]' parameter parameter. This makes it possible f |
| CVE-2026-135266 | 7.5 | n/a | The Music Player for WooCommerce plugin for WordPress is vulnerable to Directory Traversal in all versions up to, and including, 1.9.4 via the '_downloadable_files' parameter parameter. This makes it  |
| CVE-2026-137077 | 7.4 | n/a | FreeRDP before 3.33.0 contains a heap out-of-bounds write in h264_context_reset() in libfreerdp/codec/h264.c, which stores new dimensions before the YUV planes are reallocated. Remote peers can trigge |
| CVE-2026-137308 | 7.4 | n/a | markdownify-mcp before 1.2.0 contains a server-side request forgery vulnerability that allows attackers to bypass URL validation by supplying DNS names, bracketed IPv6 literals, or IPv4-mapped IPv6 ad |
| CVE-2026-136448 | 7.3 | 0.4% | A vulnerability was identified in nliautaud pico-content-editor up to 02d5ad6c820c5050c542ab9505819b5e0a0ba1af. Affected by this vulnerability is the function Uploads::saveFile/Auth::init of the file  |
| CVE-2026-136694 | 7.3 | n/a | A weakness has been identified in eosphoros-ai DB-GPT up to 0.8.2. This impacts the function skill_upload of the file packages/dbgpt-app/src/dbgpt_app/openapi/api_v1/agentic_data_api.py of the compone |
| CVE-2026-136722 | 7.3 | n/a | A vulnerability was identified in Zhengzhou Weiwei Information Technology mayicms up to 5.8E. This vulnerability affects unknown code of the file member.php. Such manipulation of the argument code lea |
| CVE-2026-136733 | 7.3 | n/a | A weakness has been identified in EduardoPires EquinoxProject up to 1.10. This vulnerability affects the function BuildToken of the file src/Equinox.Services.Api/appsettings.Development.json of the co |
| CVE-2026-137087 | 7.3 | n/a | @irrelon/path 6.2.2 before 7.0.3 contains a prototype pollution vulnerability in merge() and mergeImmutable() that allows remote attackers to modify Object.prototype by supplying __proto__ keys. Attac |
| CVE-2026-137088 | 7.3 | n/a | @oleksii-pavlov/deep-merge before 1.2.4 contains a prototype pollution vulnerability in deepMergeTwoAssignable() that allows remote attackers to modify Object.prototype by supplying a __proto__ key. A |
| CVE-2026-137089 | 7.3 | n/a | merge-deep-composed through 0.1.4 contains a prototype pollution vulnerability in _mergeDeepOne() that allows remote attackers to modify Object.prototype by supplying __proto__ keys. Attackers can pas |
| CVE-2026-136946 | 7.3 | n/a | A vulnerability was identified in philipjscott simple-thumbnail up to 1.6.5. This issue affects the function ffmpegExecute of the file index.js. The manipulation of the argument seek leads to os comma |
| CVE-2026-136947 | 7.3 | n/a | A security flaw has been discovered in msaifulcsse Ticket-Travel-Management-System 28b68cea41b3a9eb8d533db992e0b5ba2db68854/15c7bc0b48c263233326bb227fef01efc54c24a7. Impacted is an unknown function of |
| CVE-2026-137046 | 7.3 | n/a | A vulnerability was detected in mahmoudai1 school-management-system up to ecec9faaf2fb1a3c5cd096e063f8ef326d09cdfd. The impacted element is the function userModel::checkUserInDB of the file loginServe |
| CVE-2026-137324 | 7.3 | n/a | A flaw has been found in shemaikuzwe Attendance_Management_system up to b37dbeb5bf4d9eab07480e7b6213db889fc3ebf9. Affected by this issue is some unknown functionality of the file index.php. Executing  |
| CVE-2026-131589 | 7.2 | n/a | The AI Engine – MCP Server & AI Chatbot for WordPress, with Claude, ChatGPT & Gemini plugin for WordPress is vulnerable to Limited Arbitrary File Upload in all versions up to, and including, 3.9.4 via |
| CVE-2026-136620 | 7.1 | 0.2% | pain001-mcp 0.0.72 before 0.0.80 contains a path traversal vulnerability in the commit_payment_batch MCP tool that allows attackers to write files outside any output directory via output_file_path. At |
| CVE-2026-137091 | 7.1 | n/a | EverOS before 1.8.0 contains a cross-origin local file disclosure vulnerability that allows malicious websites to read local files by abusing a wildcard CORS policy with credentials and unrestricted f |
| CVE-2026-67209 | 7.1 | n/a | metasfresh through 5.175 contains a SQL injection vulnerability in the stressTest_massCacheInvalidation handler of DebugRestController, which concatenates the caller-supplied tableName request paramet |
| CVE-2026-137092 | 7.0 | n/a | Assimp before 6.0.6 contains an out-of-bounds write vulnerability in MD5Importer::MakeDataUnique() that allows attackers to corrupt heap memory by supplying unvalidated face indices. Attackers can cra |
| CVE-2026-137326 | 7.0 | n/a | ICU4C through 79.1 contains a use-after-free and double free vulnerability in the x11-compound-text converter because cloning shares the extraInfo block without a safeClone handler. Attackers who cont |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-3gjg-8hh2-vxj3 | CVE-2026-137390 | high | Mail2000 developed by Openfind has an OS Command Injection vulnerability.Authenticated remote... |
| GHSA-8qwh-f6fj-fggr | CVE-2026-137324 | medium | A flaw has been found in shemaikuzwe Attendance_Management_system up to... |
| GHSA-29j6-r64w-wq3h | CVE-2026-137389 | high | MailGates/MailAudit developed by Openfind has a Command Injection vulnerability.Authenticated... |
| GHSA-46cm-wvj6-54g7 | CVE-2026-133340 | medium | Joomla Extension - vi-solutions - Missing data export permission check in administrative form... |
| GHSA-wxgv-rp76-2hfq | CVE-2026-133341 | medium | Joomla Extension - vi-solutions - Missing SQL statement permission check in Maxsubmissions plugin... |
| GHSA-7v34-c5w8-m9m3 | CVE-2026-131916 | medium | GENAI Web provided by Digital Agency contains a server-side request forgery (SSRF) vulnerability.... |
| GHSA-4g9m-rxgf-4f8f | CVE-2026-137316 | low | A flaw has been found in SourceCodester Online Food Ordering System 1.0. Impacted is an unknown... |
| GHSA-c23x-49v4-x7j4 | CVE-2026-133339 | high | Joomla Extension - vi-solutions - SQL injection via form IDs in administrative form export in... |
| GHSA-459x-p27g-jh39 | CVE-2026-137315 | low | A vulnerability was detected in SourceCodester Online Food Ordering System 1.0. This issue... |
| GHSA-9g5c-9qjm-j2ww | CVE-2026-135772 | high | RTL8762C MCU developed by Realtek Semiconductor Corporation has an Improper Protection Against... |
| GHSA-7pvm-5r46-pcrh | CVE-2026-137035 | medium | A flaw was found in bootc. On a sealed composefs boot with a strict composefs digest on the... |
| GHSA-69xg-3f4g-5m85 | CVE-2026-137036 | medium | A flaw was found in bootc. On a sealed composefs boot, a failed bootc-root-setup.service does not... |
| GHSA-f8g4-p7wh-9phv | CVE-2026-133337 | high | Joomla Extension - chronoengine.com - Unauthenticated SQL injection in table sorting in... |
| GHSA-5g2q-w3rp-x7p4 | CVE-2026-133525 | high | Deserialization of Untrusted Data vulnerability in ThemeFusion Fusion Builder fusion-builder... |
| GHSA-q7j3-vqmj-j435 | CVE-2026-133338 | high | Joomla Extension - chronoengine.com - Unauthenticated stored XSS in DB Table cells in ChronoForms... |
| GHSA-wj5g-rh49-4342 | CVE-2026-137314 | low | A security vulnerability has been detected in SourceCodester Online Food Ordering System 1.0.... |
| GHSA-5rhh-fcq6-86qp | CVE-2026-133336 | critical | Joomla Extension - chronoengine.com - Unauthenticated arbitrary file upload in ChronoForms... |
| GHSA-jxjj-rppx-vxqc | CVE-2026-103383 | unknown | In Eclipse MWE <= 2.27.0 if you debug mwe workflows a remote attacker can cause arbitrary classes... |
| GHSA-h5mf-9f7x-72r6 | CVE-2026-137313 | low | A weakness has been identified in SourceCodester Online Food Ordering System 1.0. This affects an... |
| GHSA-jq67-w7xp-55p7 | CVE-2017-20291 | high | An XML External Entity (XXE) injection vulnerability in the Federation Web Services component (... |
| GHSA-cvpj-ggpw-5325 | CVE-2026-137312 | medium | A security flaw has been discovered in SourceCodester Online Food Ordering System 1.0. Affected... |
| GHSA-v9gg-qpr9-xwcj | CVE-2026-137311 | medium | A vulnerability was identified in SourceCodester Online Food Ordering System 1.0. Affected by... |
| GHSA-v8q2-f763-8pc9 | CVE-2026-133209 | low | In Revive Adserver through 6.0.9, deleting an agency, advertiser, or publisher through affected... |
| GHSA-f4mq-jg3f-grw8 | CVE-2026-133211 | medium | In Revive Adserver through 6.0.9, the ct0 request parameter of the delivery scripts is only... |
| GHSA-887w-fq47-3rhx | CVE-2026-133210 | medium | In Revive Adserver through 6.0.9, the zone banner-linking page (zone-include.php) does not cast... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Restaurant Brands International, Inc. | Inception | CA | 2026-11-26T01:52:28.011805+00:00 |
| Koh Young Technology | everest | KR | 2026-11-26T02:06:32.189620+00:00 |
| Nucleon EDR | everest |  | 2026-11-26T02:05:56.634300+00:00 |
| Tessilopera | medusalocker | IT | 2026-11-25T23:03:35.969840+00:00 |
| Reflex Electromechanical & Trade Co. Ltd. (Nablus pumps and elevators engineering house) | PixelLeaks | PS | 2026-11-25T22:46:48.793839+00:00 |
| Signet Pacific Insurance Services | N0n | US | 2026-11-25T22:36:21.718672+00:00 |
| ClearPath Wealth Management | N0n | CA | 2026-11-25T22:25:52.015032+00:00 |
| Atlantis Financial | N0n | CA | 2026-11-25T22:24:37.383288+00:00 |
| pacific-orient.com | BrainCipher |  | 2026-11-25T22:21:01.526123+00:00 |
| Pumptech | Dark Project | US | 2026-11-25T22:21:54.438125+00:00 |
| New Plymouth School District | interlock | US | 2026-11-25T20:45:02.920082+00:00 |
| Norris McLaughlin | SilentRansomGroup | US | 2026-11-25T20:33:22.635996+00:00 |
| York Engineering | rhysida |  | 2026-11-25T19:54:53.463564+00:00 |
| HydroCision | anubis | US | 2026-11-25T18:31:40.176115+00:00 |
| Honigman LLP | SilentRansomGroup | US | 2026-11-25T17:33:49.947790+00:00 |
| Company #286 | N0n | DE | 2026-11-25T17:23:28.259757+00:00 |
| Company #285 | N0n | DE | 2026-11-25T17:22:50.326982+00:00 |
| Company #284 | N0n | DE | 2026-11-25T16:23:15.559683+00:00 |
| Minichi Inc | Dark Project | JP | 2026-11-25T14:51:13.638625+00:00 |
| Company #283 | N0n | US | 2026-11-25T13:56:40.783956+00:00 |

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
| 3.129.187.38 | 9 |
| 27.102.116.43 | 9 |
| 62.60.130.148 | 9 |
| 141.98.11.11 | 9 |
| 2.57.121.112 | 8 |
| 64.62.197.62 | 8 |
| 64.62.197.92 | 8 |
| 64.62.197.152 | 8 |
| 66.132.172.209 | 8 |
| 66.132.195.74 | 8 |
| 66.132.224.242 | 8 |
| 102.220.45.186 | 8 |
| 102.220.161.85 | 8 |
| 104.244.79.113 | 8 |
| 119.204.122.94 | 8 |
| 125.130.102.172 | 8 |
| 164.30.7.153 | 8 |
| 193.47.62.69 | 8 |
| 203.252.10.4 | 8 |
| 1.238.106.229 | 7 |

### OpenPhish (live phishing URLs)
- http://www.metamask173.blogspot.com/
- https://bak-center.com/
- https://loja.bak-center.com/
- https://sistema.acessoprotecnologia.com.br/lvyicoe/
- http://www.66506.cc/
- https://myprofile-microsoft.com/?rid=CgUEQLK
- https://tlktok.vercel.app/
- http://apply-here-nu.vercel.app/
- https://ifps62-178wzziqj-arcadawebapps2.vercel.app/
- https://pvdmcg-r0yfs7ymo-arcadawebapps3.vercel.app/
- http://ifps62-arcadawebapps2.vercel.app/
- http://pvdmcg-arcadawebapps3.vercel.app/
- http://pvdmcg.vercel.app/
- http://instagram-clone-gules.vercel.app/
- https://booking.3825.rest/375102414
- https://ifps62-htolnr64j-arcadawebapps2.vercel.app/
- http://legal-org-docs.d2mqddsv0wxgy0.amplifyapp.com/
- http://netflix-clone-rust-zeta.vercel.app/
- http://projeto-insta.vercel.app/
- https://fi2wx-ftt-ppjl-w9mty-05-10-2026-aa.pages.dev/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://www.brt-yx.eu.cc/it/ |
| N/A | https://allegrolokalnie.pl-oferta-7461-3819-3842.sbs/ |
| N/A | https://www.brt-ys.eu.cc/it/ |
| N/A | https://allegro.pl-oferta-7461-3819-3842.sbs/playstation-5-slim-digital-z-2-p/ciwuyhw |
| N/A | https://itau.granometrics.io/ |
| N/A | https://americanemthulotr.cqhhxx.com/2ymmlo/hepe |
| N/A | https://caixa.cadastropjportal.digital/entrar.php?_vxtok=b1602e9f636640833efcb6358ec10796 |
| N/A | https://www.brt-yc.eu.cc/it/ |
| N/A | https://login-nubank.vercel.app/ |
| N/A | https://nubank-emprestimo.vercel.app/ |
| N/A | https://vendasoboticario.vercel.app/ |
| N/A | https://www.brt-yz.eu.cc/it/ |
| N/A | https://pt-gls.top/ |
| N/A | https://nubankemprestimo.vercel.app/ |
| N/A | https://www.brt-ya.eu.cc/it/ |
| N/A | https://www.brt-ix.eu.cc/it/ |
| 8.7 | https://kontabontang1794263724204.0480074.misitiohostgator.com/Faser5t/home/fi-phone.php?token=TW96aWxsYS81LjAgKFdpbmRvd3MgTlQgMTAuMDsgV2luNjQ7IHg2NCkgQXBwbGVXZWJLaXQvNTM3LjM2IChLSFRNTCwgbGlrZSBHZWNrbykgQ2hyb21lLzEyMi4wLjAuMCBTYWZhcmkvNTM3LjM2MTM4LjE5Ny45MS4yMDYyMDI2Ok5vdjpUaHU= |
| 8.7 | https://kontabontang1794263724204.0480074.misitiohostgator.com/Faser5t/home/fi-phone.php?token=MzQuMTk4LjQ2LjExODIwMjY6Tm92OlRodQ== |
| 5.7 | https://scanned.page/p/1uAlof |
| 7.3 | https://allegro.201298f30.study/ |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
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
| 4da3273d01b7073f7218b69acadf32b0c57f35de | FunStealer C&C |

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
- 1.192.216.175
- 1.194.211.36
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
- 1.234.53.65

### CINS Army (poorly-rated IPs)
- 1.14.110.192
- 1.14.3.170
- 1.145.16.243
- 1.15.14.29
- 1.15.88.48
- 1.168.206.193
- 1.189.41.213
- 1.192.129.106
- 1.193.100.138
- 1.193.63.117
- 1.193.63.118
- 1.204.35.156
- 1.208.108.242
- 1.24.16.131
- 1.24.16.139
- 1.24.16.141
- 1.24.16.146
- 1.24.16.151
- 1.24.16.159
- 1.24.16.161

## News (last ~36h, across outlets)
### The Hacker News
- [Most Wanted: The Phishing Kits and Techniques Getting Past Security Controls](https://thehackernews.com/2026/11/most-wanted-phishing-kits-and.html)
- [1Password Hacked, Customer Data and Source Code Stolen in GitHub Account Breach](https://thehackernews.com/2026/11/1password-hacked-customer-data-and.html)
- [Drupal Warns of New Highly Critical Site Takeover Vulnerability Under Active Exploitation](https://thehackernews.com/2026/11/drupal-warns-of-new-highly-critical.html)
- [Hackers Exploit 10 Vulnerabilities Across Mitel, Juniper, Vates, and Danfoss Products](https://thehackernews.com/2026/11/hackers-exploit-10-vulnerabilities.html)
- [13 Malicious NuGet Packages Turn Fake .NET Job Assessments Into Malware Delivery Traps](https://thehackernews.com/2026/11/13-malicious-nuget-packages-turn-fake.html)
- [Hackers Exploit Two GeoServer Flaws as Researchers Warn of Unauthenticated RCE Chains](https://thehackernews.com/2026/11/hackers-exploit-two-geoserver-flaws-as.html)
- [U.S. Treasury's Financial Crimes Agency Takes Some Systems Offline After Cyber Intrusion](https://thehackernews.com/2026/11/us-treasurys-fincen-takes-some-systems.html)
- [Credential Remediation Is Slow When You Don’t Know What Will Break](https://thehackernews.com/2026/11/credential-remediation-is-slow-when-you.html)
- [Drupal Fail2Install Exploit Details Emerge as Critical RCE Flaw Faces Active Exploitation](https://thehackernews.com/2026/11/drupal-fail2install-exploit-details.html)
- [Ex-OpenAI Employee Accused of Bugging Company Offices Granted $1 Million Bail](https://thehackernews.com/2026/11/ex-openai-employee-accused-of-bugging.html)
- [Hackers Exploited CVSS 10.0 Hex.pm RCE Flaw to Compromise 6 Package Registry Servers](https://thehackernews.com/2026/11/hackers-exploited-cvss-100-hexpm-rce.html)
- [Hackers Compromise 24 Check Point Management Servers in Suspected AI-Driven Attack Campaign](https://thehackernews.com/2026/11/hackers-compromise-24-check-point.html)
- [Com-Affiliated Hackers Hijack Cloud Accounts via Vishing for Data Theft and Extortion](https://thehackernews.com/2026/11/com-affiliated-hackers-hijack-cloud.html)
- [WordPress Blocks Six Backdoored WP Connect Plugins Before Malicious Releases Go Live](https://thehackernews.com/2026/11/wordpress-blocks-six-backdoored-wp.html)

### BleepingComputer
- [SYS010 malware abuses browser management to spy on Gmail, Outlook](https://www.bleepingcomputer.com/news/security/sys010-malware-abuses-browser-management-to-spy-on-gmail-outlook/)
- [Palo Alto Networks warns of Fragnesia flaw exploited in PAN-OS attacks](https://www.bleepingcomputer.com/news/security/palo-alto-networks-warns-of-fragnesia-flaw-exploited-in-pan-os-attacks/)
- [1Password customer data stolen after employee GitHub account breach](https://www.bleepingcomputer.com/news/security/1password-customer-data-stolen-after-employee-github-account-breach/)
- [Italy and Switzerland warn of autonomous AI-driven cyberattacks](https://www.bleepingcomputer.com/news/security/italy-and-switzerland-warn-of-autonomous-ai-driven-cyberattacks/)
- [CISA warns of critical unpatched flaw in Danfoss refrigeration controllers](https://www.bleepingcomputer.com/news/security/cisa-warns-of-critical-unpatched-flaw-in-danfoss-refrigeration-controllers/)
- [More Pentests Without More Pentesters: Where AI Safely Helps](https://www.bleepingcomputer.com/news/security/more-pentests-without-more-pentesters-where-ai-safely-helps/)
- [InfraTrust warns of exploited supply chain flaws in network appliances](https://www.bleepingcomputer.com/news/security/infratrust-warns-of-exploited-supply-chain-flaws-in-network-appliances/)
- [Microsoft fixes Microsoft 365 bug blocking access to Office apps](https://www.bleepingcomputer.com/news/microsoft/microsoft-fixes-blank-dialog-that-made-microsoft-365-office-apps-unusable/)
- [Hackers now exploit critical Drupal RCE flaw to hijack sites](https://www.bleepingcomputer.com/news/security/hackers-now-exploit-critical-drupal-rce-flaw-to-hijack-sites/)
- [Microsoft confirms authentication issues after November updates](https://www.bleepingcomputer.com/news/microsoft/microsoft-confirms-authentication-issues-after-november-updates/)
- [Hackers reportedly breached CIA intelligence analysis system](https://www.bleepingcomputer.com/news/security/hackers-reportedly-breached-cia-intelligence-analysis-system/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [Cyprus Becomes Espionage Target for Iranian Hackers](https://www.darkreading.com/cyberattacks-data-breaches/cyprus-espionage-target-iranian-hackers)
- [Attackers Target .NET Developers With Poisoned Job Assessments](https://www.darkreading.com/threat-intelligence/attackers-net-developers-poisoned-job-assessments)
- [It's a Bot World. We're Just Living in It](https://www.darkreading.com/cyber-risk/bot-world-just-living)
- [Cyber Insurers See New Divide: AI Defense 'Haves' &amp; 'Have Nots'](https://www.darkreading.com/cybersecurity-operations/cyber-insurers-see-new-ai-divide)
- [Latin America Sees Cyberattacks on Ports, Pipelines &amp; Manufacturing](https://www.darkreading.com/cyberattacks-data-breaches/latin-america-cyberattacks-ports-pipelines-manufacturing)

### SecurityWeek
- [Mitel MiCollab Zero-Days Exploited in Suspected AI-Assisted Attacks](https://www.securityweek.com/mitel-micollab-zero-days-exploited-in-suspected-ai-assisted-attacks/)
- [Drupal Installer Patch Left a Gap Attackers Are Already Exploiting](https://www.securityweek.com/drupal-installer-patch-left-a-gap-attackers-are-already-exploiting/)
- [1Password Breach Exposes Customer Data, Internal Source Code](https://www.securityweek.com/1password-breach-exposes-customer-data-internal-source-code/)
- [Two Newly Disclosed GeoServer Vulnerabilities Under Attack](https://www.securityweek.com/two-newly-disclosed-geoserver-vulnerabilities-under-attack/)
- [ShinyHunters Claims Comeback, New Inception Group Rejects Alleged Ties](https://www.securityweek.com/shinyhunters-claims-comeback-new-inception-group-rejects-alleged-ties/)
- [US Treasury’s FinCEN Disconnects Systems Following Cyber Incident](https://www.securityweek.com/us-treasurys-fincen-disconnects-systems-following-cyber-incident/)
- [Ground Truth: CISO Matt Martin on Building a Real Security Program Without an Enterprise Budget](https://www.securityweek.com/ground-truth-ciso-matt-martin-on-building-a-real-security-program-without-an-enterprise-budget/)
- [Plagiarism Checker Turnitin Investigating Cyberattack](https://www.securityweek.com/plagiarism-checker-turnitin-investigating-cyberattack/)
- [Hackers Exploit Unpatched Flaw in Defunct Idunno AntiCsrf Library](https://www.securityweek.com/hackers-exploit-unpatched-flaw-in-defunct-idunno-anticsrf-library/)
- [Palo Alto Networks Patches Fragnesia Flaw Used to Root Firewalls](https://www.securityweek.com/palo-alto-networks-patches-fragnesia-flaw-used-to-root-firewalls/)

### The Record
- [UK’s long-awaited National Cyber Action Plan delayed until December](https://therecord.media/britain-delays-national-cyber-action-plan-again)
- [Microsoft: China’s Salt Typhoon hackers are using Artex](https://therecord.media/microsoft-china-salt-typhoon-using-artex-ai-tool)
- [FIFA says hackers accessed ‘limited set of personal and business information’](https://therecord.media/fifa-data-breach-limited)
- [Florida ransomware recovery CEO indicted for allegedly paying hacker ransoms](https://therecord.media/ransomware-doj-indictment-recovery)
- [Australia passes tough legislation requiring big tech to preempt foreseeable harms](https://therecord.media/australia-passes-online-safety-legislation-preempt-harms)

### Infosecurity Magazine
- [Chinese, North Korean Hackers Adopt ARTEX AI Offensive Framework](https://www.infosecurity-magazine.com/news/chinese-north-korea-artex/)
- [Home Office Reprimanded After GDPR Failure at the Border](https://www.infosecurity-magazine.com/news/home-office-reprimanded-gdpr/)
- [1Password Hit by Backend Breach via Hijacked Employee GitHub Account](https://www.infosecurity-magazine.com/news/1password-github-account-backend/)
- [US Anti-Scam Surge Hits 800 Defendants and 29 Scam Compounds](https://www.infosecurity-magazine.com/news/doj-anti-scam-surge-800-defendants/)
- [Palo Alto Fixes Fragnesia Kernel Bug Chained With PHP2Shell in Firewall Attacks](https://www.infosecurity-magazine.com/news/palo-alto-fragnesia-php2shell-fix/)
- [US Treasury Investigates Cyber Incident Amid Reported Federal Agency Breaches](https://www.infosecurity-magazine.com/news/us-treasury-cyber-incident/)
- [Ransomware Attacks Surge 23% in October Following Record Quarter](https://www.infosecurity-magazine.com/news/ransomware-surge-october-record/)
- [NCSC Shares Guidance to Tackle Agentic Threat From ARTEX-Like Tools](https://www.infosecurity-magazine.com/news/ncsc-tips-tackle-agentic-threat/)
- [UK Authorized Push Payment Losses Surge 22% as Fraudsters Steal £660m](https://www.infosecurity-magazine.com/news/uk-app-losses-surge-22-fraudsters/)

### CyberScoop
- [FinCEN investigates cybersecurity incident, takes systems offline](https://cyberscoop.com/fincen-investigates-cybersecurity-incident-systems-offline/)

### Cisco Talos
- [Oh, is it Thanksgiving? I hadn’t noticed!](https://blog.talosintelligence.com/oh-is-it-thanksgiving-i-hadnt-noticed/)
- [The Great Escape: Tradecraft insights from an agentic swarm](https://blog.talosintelligence.com/the-great-escape-tradecraft-insights-from-an-agentic-swarm/)
- [Securing Grandma's groceries with Pierre Cadieux](https://blog.talosintelligence.com/securing-grandmas-groceries-with-pierre-cadieux/)

### Unit 42 (Palo Alto)
- [The AI Threat Horizon: Why Speed, Edge AI and Baselines Are Our Best Defense](https://unit42.paloaltonetworks.com/ai-threat-horizon/)

### Microsoft Security Blog
- [What defenders need to know about ARTEX, the agentic AI framework threat actors abuse](https://www.microsoft.com/en-us/security/blog/2026/11/25/what-defenders-need-to-know-artex-agentic-ai-framework-threat-actors-abuse/)
- [Microsoft named a Leader in the 2026 Gartner® Magic Quadrant™ for Email Security](https://www.microsoft.com/en-us/security/blog/2026/11/25/microsoft-named-a-leader-in-the-2026-gartner-magic-quadrant-for-email-security/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Wednesday, November 25th, 2026 https://isc.sans.edu/podcastdetail/10194, (Wed, Nov 25th)](https://isc.sans.edu/diary/rss/33554)

### Securelist (Kaspersky)
- [How to protect against preinstalled Android malware](https://securelist.com/tr/how-to-protect-against-preinstalled-android-malware/122093/)

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
- [Apache Axis RCE in Confluence Data Center & N-able N-central](https://fortiguard.fortinet.com/threat-signal-report/6685)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal