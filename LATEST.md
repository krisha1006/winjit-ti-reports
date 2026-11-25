# Winjit Daily TI Digest — 2026-11-25

_Auto-generated. Window: last ~24h. Fetched at 2026-11-25T12:22:39.074759+00:00Z_

**At a glance:** 3 new KEV · 79 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-132224 | Optimizely | Web Experimentation | Optimizely Web Experimentation External Control of Critical State Data Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-131914 | Idunno | AntiCsrf | Idunno AntiCsrf Deserialization of Untrusted Data Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-132165 | Drupal | Core | Drupal Core Remote Code Execution Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-135792 | 10.0 | n/a | A vulnerability has been found in Panabit Smart Application Gateway TANGr7p10. This issue affects the function send_email_authcode of the file user.cgi of the component Email Auth Code Sender. Such ma |
| CVE-2026-135797 | 10.0 | n/a | A vulnerability was identified in Volans NGFW Next-Generation Firewall r5.1. Impacted is the function exec of the file sslvpn/sslvpn_client.php of the component SSLVPN Client. Such manipulation of the |
| CVE-2026-136136 | 10.0 | n/a | A vulnerability was identified in Netis WF2409E up to 20261026. Affected by this issue is some unknown functionality of the file /cgi-bin/skk_set.cgi of the component CGI Interface. The manipulation o |
| CVE-2026-136547 | 10.0 | n/a | A vulnerability was determined in Tenda RX3 16.03.13.11_multi. Impacted is the function R7WebsSecurityHandler of the component httpd. Executing a manipulation can lead to improper authentication. The  |
| CVE-2026-136548 | 10.0 | n/a | A vulnerability was identified in Tenda RX3 16.03.13.11. The affected element is an unknown function of the file /bin/auto_discover of the component GBK-to-UTF-8 Conversion. The manipulation of the ar |
| CVE-2026-136549 | 10.0 | n/a | A security flaw has been discovered in Tenda RX3 16.03.13.11_multi. The impacted element is the function formSetSafeWanWebMan of the file /goform/SetRemoteWebCfg. The manipulation of the argument remo |
| CVE-2026-136553 | 10.0 | n/a | A vulnerability was detected in Tenda RX3 16.03.13.11_multi. Affected is an unknown function of the file /goform/fast_setting_wifi_set. Performing a manipulation of the argument loginPwd results in im |
| CVE-2026-135788 | 9.9 | n/a | A weakness has been identified in D-Link DIR-X1860 4.5.2. Affected by this vulnerability is an unknown functionality of the file /usr/sbin/anweb. Executing a manipulation can lead to os command inject |
| CVE-2026-135790 | 9.9 | n/a | A vulnerability was detected in Panabit Smart Application Gateway TANGr7p10. This affects an unknown part of the file /cgi-bin/dashboard/ajax_chart_dump. The manipulation of the argument isntmeye resu |
| CVE-2026-123342 | 9.9 | n/a | Adobe Campaign Classic (ACC) is affected by an Improper Control of Generation of Code ('Code Injection') vulnerability that could result in arbitrary code execution in the context of the current user. |
| CVE-2026-123723 | 9.9 | n/a | Adobe Campaign Classic (ACC) is affected by an Improper Control of Generation of Code ('Code Injection') vulnerability that could result in arbitrary code execution in the context of the current user. |
| CVE-2026-123986 | 9.9 | n/a | Adobe Campaign Classic (ACC) is affected by an Improper Control of Generation of Code ('Code Injection') vulnerability that could result in arbitrary code execution in the context of the current user. |
| CVE-2026-123987 | 9.9 | n/a | Adobe Campaign Classic (ACC) is affected by an Improper Control of Generation of Code ('Code Injection') vulnerability that could result in arbitrary code execution in the context of the current user. |
| CVE-2026-135791 | 9.9 | n/a | A flaw has been found in Panabit Smart Application Gateway TANGr7p10. This vulnerability affects the function edit_data_pie of the file /cgi-bin/flowcontrol/ajax_data_pie. This manipulation of the arg |
| CVE-2026-135794 | 9.9 | n/a | A vulnerability was determined in Panabit Smart Application Gateway TANGr7p10. The affected element is the function add_crontab of the file admin/cgi-bin/sac/ajax_sac_crontab of the component SAC. Exe |
| CVE-2026-135796 | 9.9 | n/a | A vulnerability was determined in Volans NGFW Next-Generation Firewall r5.1. This issue affects the function exec/system of the file modules/assets/port_serve_scan.mds of the component Web Management  |
| CVE-2026-119582 | 9.8 | n/a | Improper neutralization of special elements used in an SQL command ('SQL injection') vulnerability in ITG Bilgisayar Teknoloji Grubu Tic. Ltd. Şti. VSRM allows SQL Injection.

This issue affects vSRM: |
| CVE-2026-136404 | 9.8 | n/a | ntop n2n supernode 3.0 through 3.1.1 contains a stack-based buffer overflow vulnerability that allows remote unauthenticated attackers to leak memory and execute code by sending an untrusted 16-bit au |
| CVE-2026-136411 | 9.8 | n/a | BusyBox through 1.38.0 contains an absolute path traversal vulnerability in tftpd that allows unauthenticated remote attackers to access files outside any intended directory when started without a DIR |
| CVE-2026-136184 | 9.6 | n/a | compose-farm 0.19.0 before 1.22.0 contains a cross-site WebSocket hijacking and cross-site request forgery vulnerability because its unauthenticated web UI performs no Origin validation. Malicious web |
| CVE-2026-125717 | 9.6 | n/a | Adobe Campaign Classic (ACC) is affected by an Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability that could result in privilege escalation. A low-privi |
| CVE-2026-136522 | 9.6 | n/a | CubeWP Forms before 1.1.13 contains an unauthenticated stored cross-site scripting vulnerability that allows attackers to inject malicious JavaScript by submitting unregistered field names through the |
| CVE-2026-125716 | 9.3 | n/a | Adobe Campaign Classic (ACC) is affected by a reflected Cross-Site Scripting (XSS) vulnerability. An attacker could exploit this vulnerability to inject malicious scripts into a web page, potentially  |
| CVE-2026-117593 | 9.1 | n/a | Weak Password Recovery Mechanism for Forgotten Password vulnerability in ITG Bilgisayar Teknoloji Grubu Tic. Ltd. Şti. VSRM allows Password Recovery Exploitation.

This issue affects vSRM: from v14.08 |
| CVE-2026-135789 | 9.1 | n/a | A security vulnerability has been detected in D-Link R95 101B06. Affected by this issue is the function GetBluetoothAdapterSettings/GetBluetoothBloodPressure/GetBluetoothDeviceList/GetBluetoothScanDev |
| CVE-2026-125718 | 9.1 | n/a | Adobe Campaign Classic (ACC) is affected by an Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability that could result in a Security feature bypass. A low- |
| CVE-2026-136550 | 9.1 | n/a | A weakness has been identified in Tenda RX3 16.03.13.11_multi. This affects the function fromAdvSetMacMtuWan of the file /goform/AdvSetMacMtuWan. This manipulation of the argument mac causes command i |
| CVE-2026-136552 | 9.1 | n/a | A security vulnerability has been detected in Tenda RX3 16.03.13.11_multi. This impacts the function formSetIPv6status of the file /goform/setIPv6Status of the component multiWAN. Such manipulation of |
| CVE-2026-135691 | 8.8 | 0.6% | Open5GS WebUI through 2.8.0 contains an incorrect authorization vulnerability in webui/server/routes/db.js that allows authenticated user-role accounts to modify the Account model. Attackers can send  |
| CVE-2026-135695 | 8.8 | 0.5% | rConfig Core 8.0.0 before 8.2.13 and rConfig Pro before 8.4.0 contain an authorization bypass vulnerability in the users API that allows authenticated users to modify other accounts. Attackers can sen |
| CVE-2026-121016 | 8.8 | 0.6% | The affected products insufficiently restrict runtime-supplied visualization data, allowing local program execution on the engineering workstation, if a user is both logged in to a CODESYS Control run |
| CVE-2026-119543 | 8.8 | n/a | Authorization bypass through User-Controlled key vulnerability in ITG Bilgisayar Teknoloji Grubu Tic. Ltd. Şti. VSRM allows Accessing Functionality Not Properly Constrained by ACLs.

This issue affect |
| CVE-2026-136159 | 8.8 | n/a | TypiCMS Core before 17.0.46 contains an insufficiently protected credentials vulnerability that allows authenticated users with "read users" permission to view plaintext api_token values for all users |
| CVE-2026-136168 | 8.8 | n/a | RedVector before 8.1.0 contains a hard-coded credentials vulnerability that allows unauthenticated attackers to execute commands by supplying the default redvector-dev-token bearer token. Attackers ca |
| CVE-2026-136183 | 8.8 | n/a | Mercur @mercurjs/core before 2.3.2 contains a missing object-level authorization vulnerability that allows authenticated vendors to access other sellers by substituting the :id path parameter. Attacke |
| CVE-2026-136189 | 8.8 | n/a | Schmitech ORBIT before 2.17.15 contains an improper authorization vulnerability in the permission_or_api_key dependency that allows any valid API key to access /admin management routes. Attackers hold |
| CVE-2026-136455 | 8.8 | n/a | borg-ui before 2.4.1 contains a privilege escalation vulnerability that allows a repository-scoped operator to escalate to full administrator by exploiting an unrestricted source_directories field in  |
| CVE-2026-119579 | 8.7 | n/a | Adobe Experience Manager is affected by a stored Cross-Site Scripting (XSS) vulnerability that could be abused by a low-privileged attacker to inject malicious scripts into vulnerable form fields. Mal |
| CVE-2026-123253 | 8.7 | n/a | Adobe Experience Manager is affected by an Improper Neutralization of Special Elements Used in a Template Engine vulnerability that could result in a Security feature bypass. An attacker with high pri |
| CVE-2026-136132 | 8.6 | n/a | Pangolin before 1.21.0 contains an authentication bypass vulnerability in isPathAllowed() in server/lib/pathMatch.ts that splits paths on literal slashes without percent-decoding or resolving dot segm |
| CVE-2026-136632 | 8.3 | n/a | OpenProject 17.2.0 before 17.5.2, 17.6.0 before 17.6.1, 17.7.0 before 17.7.3, 17.8.0 before 17.8.2, and 17.9.0 before 17.9.7 contains an externally controlled method selection vulnerability in Inplace |
| CVE-2026-136626 | 8.2 | n/a | SRS 4.0.0 before 6.0.194, 7.0.0 before 7.0.214, and 8.0.0 before 8.0.73 contains a heap-based buffer overflow in SrsRtcpCommon::decode and SrsRtcpTWCC::decode that lets remote WebRTC peers write past  |
| CVE-2026-136126 | 8.1 | n/a | c-icap-server through 0.5.15 and 0.6.5 contains an out-of-bounds write in process_encapsulated() that allows unauthenticated attackers to corrupt heap memory by sending six Encapsulated entities. Atta |
| CVE-2026-136190 | 8.1 | n/a | RayLabsHQ gitea-mirror before 3.38.1 contains an authorization bypass vulnerability in the /api/sso/providers handlers that allows any authenticated user to access other users' SSO providers without o |
| CVE-2026-136412 | 8.1 | n/a | OpenResty stream-lua-nginx-module before 0.0.20rc4 contains a use-after-free vulnerability that allows remote peers to trigger access to freed memory when a receiveuntil() pattern iterator is garbage- |
| CVE-2026-134639 | 8.1 | n/a | Webmin through 2.670 contains an insecure default configuration in its Windows setup.bat script that provisions an administrator account with the credentials admin/admin and SSL disabled. Unauthentica |
| CVE-2026-87753 | 8.1 | n/a | Authorization bypass through User-Controlled key vulnerability in İdeal Data Finansal Teknolojiler A.Ş. IDeal WEB allows Accessing Functionality Not Properly Constrained by ACLs.

This issue affects i |
| CVE-2026-135736 | 8.1 | 0.7% | FFmpeg 4.4 before 9.1 contains a heap out-of-bounds read and write vulnerability in libavfilter/vf_deband.c that allows attackers to corrupt heap memory by sending a runtime coupling command. Attacker |
| CVE-2026-135722 | 7.8 | 0.2% | FFmpeg before 9.1 contains a heap-based buffer overflow vulnerability in peak_init_writer() and wav_write_packet() in libavformat/wavenc.c that allows attackers to corrupt heap memory by supplying aud |
| CVE-2026-135740 | 7.8 | 0.2% | FFmpeg before 9.1 contains a heap out-of-bounds write vulnerability in libavfilter/vf_readeia608.c because build_histogram() does not clamp high bit depth luma samples to the nominal maximum. Attacker |
| CVE-2026-136328 | 7.8 | n/a | A flaw was found in the file-psd plugin in GIMP. When processing a specially crafted PSD (Photoshop Document) image file in LAB color mode, the plugin does not properly validate that a fourth channel  |
| CVE-2026-136629 | 7.8 | n/a | Nektos act 0.2.92 before 0.2.95 contains an argument injection vulnerability in readProjectArgsFile and projectFlag that allows malicious repositories to bypass the untrusted project .actrc flag allow |
| CVE-2026-129833 | 7.5 | n/a | A flaw was found in rsyslog. A remote, unauthenticated attacker can trigger a stack-based buffer overflow by sending a malformed log message containing an embedded IPv4-in-IPv6 address to an instance  |
| CVE-2026-136181 | 7.5 | n/a | cnpmcore 3.46.0 before 3.84.3 and 4.0.0 before 4.37.3 contains an information disclosure vulnerability that allows unauthenticated attackers to obtain upstream registry authTokens via the GET /-/regis |
| CVE-2026-136627 | 7.5 | n/a | SRS 4.0.0 before 6.0.194, 7.0.0 before 7.0.214, and 8.0.0 before 8.0.73 contains a reachable assertion in RTCP decoding that lets remote WebRTC peers crash the server. Attackers opening an unauthentic |
| CVE-2026-136630 | 7.5 | n/a | Electerm before 5.9.0 contains an origin validation vulnerability in the MCP Server widget that allows remote attackers to execute commands by bypassing Host and Origin checks through DNS rebinding. A |
| CVE-2026-134283 | 7.5 | n/a | Webmin through 2.670 contains an improper certificate validation vulnerability in the http_download function of web-lib-funcs.pl that skips TLS chain and hostname verification. Man-in-the-middle attac |
| CVE-2026-134326 | 7.5 | n/a | Webmin through 2.670 contains a signature verification bypass vulnerability in webmin-lib.pl that allows attackers to install unsigned module updates when GnuPG setup fails. Attackers tampering with u |
| CVE-2026-134438 | 7.5 | n/a | Webmin through 2.670 contains an insecure download vulnerability in webmin/upgrade.cgi, cluster-webmin/upgrade.cgi and cluster-usermin/upgrade.cgi that fetches upgrade packages over plaintext HTTP wit |
| CVE-2026-134630 | 7.5 | n/a | Webmin through 2.670 contains a remote code execution vulnerability in the Perl Modules (cpan) module, which downloads CPAN indexes and module archives over plaintext HTTP without checksum or signatur |
| CVE-2026-134638 | 7.5 | n/a | Webmin through 2.670 contains a missing integrity verification vulnerability in usermin/upgrade.cgi that downloads Usermin upgrade packages over plaintext HTTP without signature or digest checks. On-p |
| CVE-2026-134642 | 7.5 | n/a | Webmin through 2.670 contains a missing authentication vulnerability in fastrpc.cgi that allows unauthenticated network peers to connect to tcpwrite and tcpread file-transfer listeners without session |
| CVE-2026-134647 | 7.5 | n/a | Webmin through 2.670 contains a cleartext transmission vulnerability in web-lib-funcs.pl and fastrpc.cgi that sends cluster RPC traffic over raw TCP despite SSL configuration. Network-positioned attac |
| CVE-2026-135686 | 7.4 | 0.5% | Trilium through 0.107.0 contains an sql injection vulnerability in updateNormalEntity() that allows malicious sync partners to inject SQL by supplying crafted entity names and column keys. Attackers c |
| CVE-2026-135814 | 7.4 | n/a | A vulnerability has been found in zhblue hustoj up to 26.08.19. This impacts an unknown function of the file trunk/core/judged/judged.cc of the component Judge Daemon Sandbox. The manipulation leads t |
| CVE-2026-134644 | 7.4 | n/a | Webmin through 2.670 contains a path traversal vulnerability in minecraft/minecraft-lib.pl that allows unauthenticated game players to overwrite arbitrary files as root via crafted chat messages. Atta |
| CVE-2026-135798 | 7.3 | n/a | A security flaw has been discovered in Volans NGFW Next-Generation Firewall r5.1. The affected element is an unknown function of the file include/sqlite3.inc of the component Web Management Interface. |
| CVE-2026-135800 | 7.3 | n/a | A flaw has been found in hiyouga LLaMA-Factory up to 0.9.5. Affected is the function save_args/load_args of the file src/llamafactory/webui/runner.py of the component WebUI. This manipulation of the a |
| CVE-2026-135810 | 7.3 | n/a | A vulnerability was identified in GongShengyue OnlineBooks up to dfc5eacc08d3b0396c266049548618f6fb9587ea. This vulnerability affects the function insert of the file src/cn/ylcto/book/filter/AdminLogi |
| CVE-2026-136134 | 7.3 | n/a | A flaw has been found in mealie-recipes Mealie up to 3.29.0. Affected is the function get of the file mealie/pkgs/i18n/provider_factory.py of the component I18n Locale Provider. Executing a manipulati |
| CVE-2026-136448 | 7.3 | n/a | A vulnerability was identified in nliautaud pico-content-editor up to 02d5ad6c820c5050c542ab9505819b5e0a0ba1af. Affected by this vulnerability is the function Uploads::saveFile/Auth::init of the file  |
| CVE-2026-136179 | 7.1 | n/a | EpicStaff 1.2.0 before 1.3.1 contains an insecure direct object reference vulnerability in DocumentViewSet download and copy endpoints that allows authenticated users to access other organizations' do |
| CVE-2026-136185 | 7.1 | n/a | Prismor before 1.57.0 contains a wildcard CORS misconfiguration and missing authentication in its local HTTP API that allows remote attackers to overwrite security policies via cross-origin requests.  |
| CVE-2026-123256 | 7.1 | n/a | Adobe Experience Manager is affected by an Incorrect Authorization vulnerability that could result in a Security feature bypass. A low-privileged attacker could leverage this vulnerability to bypass s |
| CVE-2026-136620 | 7.1 | n/a | pain001-mcp 0.0.72 before 0.0.80 contains a path traversal vulnerability in the commit_payment_batch MCP tool that allows attackers to write files outside any output directory via output_file_path. At |
| CVE-2026-136628 | 7.1 | n/a | Wails before 2.17.1 on Linux contains an origin validation error in the sendMessageToBackend WebKitGTK handler that allows child-frame scripts to invoke the privileged IPC channel. Attackers controlli |
| CVE-2026-135723 | 7.0 | 0.2% | FFmpeg before 9.1 contains a double free vulnerability in the fill_marker() function of libavformat/imf_cpl.c that frees a Marker label without clearing the pointer when default scope allocation fails |
| CVE-2026-61512 | 7.0 | n/a | VeraCrypt before 1.26.30 on Linux contains a command injection vulnerability in CoreUnix::CheckFilesystem that allows a local attacker with same-UID access and an active elevated CoreService session t |
| CVE-2026-135739 | 6.5 | 0.5% | FFmpeg 7.1 before 9.1 contains an out-of-bounds read vulnerability in libavfilter/vf_scale.c that allows attackers to read past the filter input array by sending width or height commands using ref var |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-qmhp-mv4v-qrc8 | CVE-2026-80264 | low | Dell Secure Connect Gateway (SCG) Virtual Edition, versions prior to 5.36.00.16, contains a Free... |
| GHSA-gv4c-hhq7-v5fx | CVE-2026-80265 | medium | Dell Secure Connect Gateway (SCG) Virtual Edition, versions prior to 5.36.00.16, contains a... |
| GHSA-f26c-qx7c-fvv2 | CVE-2026-80259 | medium | Dell Secure Connect Gateway (SCG) Virtual Edition, versions prior to 5.36.00.16, contains an... |
| GHSA-38r6-mx7w-mwvf | CVE-2026-135879 | medium | Improper Neutralization of Script-Related HTML Tags in a Web Page (Basic XSS) vulnerability in... |
| GHSA-pw9x-xv5w-r5x4 | CVE-2026-135049 | high | Cross-Site Request Forgery (CSRF) vulnerability in Brainstorm Force Presto Player presto-player... |
| GHSA-6249-f2q2-f7x2 | CVE-2026-135047 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-r3wq-6qr8-pg75 | CVE-2026-135840 | high | Cross-Site Request Forgery (CSRF) vulnerability in Arraytics Timetics timetics allows Cross Site... |
| GHSA-4pgr-xh7w-jrcx | CVE-2026-135033 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-r7jh-48jm-c46w | CVE-2026-80266 | low | Dell Secure Connect Gateway (SCG) Virtual Edition, versions prior to 5.36.00.16, contains an... |
| GHSA-wr43-m6x6-2pmj | CVE-2026-80261 | medium | Dell Secure Connect Gateway (SCG) Virtual Edition, versions prior to 5.36.00.16, contains an... |
| GHSA-66rc-234m-f6c8 | CVE-2026-80260 | medium | Dell Secure Connect Gateway (SCG) Virtual Edition, versions prior to 5.36.00.16, contains a... |
| GHSA-rx84-8f7f-xgcf | CVE-2026-80263 | medium | Dell Secure Connect Gateway (SCG) Virtual Edition, versions prior to 5.36.00.16, contains a Heap... |
| GHSA-5pcq-qr59-2x5j | CVE-2026-80251 | medium | Dell Secure Connect Gateway (SCG) Virtual Edition, versions prior to 5.36.00.16, contains an... |
| GHSA-4pfp-rfrh-67cp | CVE-2026-80262 | medium | Dell Secure Connect Gateway (SCG) Virtual Edition, versions prior to 5.36.00.16, contains a CRLF... |
| GHSA-hj6g-384c-63r6 | CVE-2026-135910 | medium | Improper Neutralization of Script-Related HTML Tags in a Web Page (Basic XSS) vulnerability in... |
| GHSA-wgm2-xx4w-884x | CVE-2026-135040 | high | Cross-Site Request Forgery (CSRF) vulnerability in Themefic Hydra Booking hydra-booking allows... |
| GHSA-3g58-vvhc-m3w7 | CVE-2026-135034 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-xp5x-3jjx-mw7j | CVE-2026-80250 | low | Dell Secure Connect Gateway (SCG) Virtual Edition, versions prior to 5.36.00.16, contains an... |
| GHSA-7q3h-cvw2-f4x5 | CVE-2026-135837 | medium | Missing Authorization vulnerability in weDevs Happy Addons for Elementor happy-elementor-addons... |
| GHSA-xmm8-h36g-wx7p | CVE-2026-135031 | medium | Missing Authorization vulnerability in Magepeople inc. Booking and Rental Manager booking-and... |
| GHSA-q7fh-664m-x6mp | CVE-2026-80252 | medium | Dell Secure Connect Gateway (SCG) Virtual Edition, versions prior to 5.36.00.16, contains a NULL... |
| GHSA-qfg5-h294-95g4 | CVE-2026-135890 | medium | Missing Authorization vulnerability in Qode Interactive Qi Blocks qi-blocks allows Exploiting... |
| GHSA-4f5q-hfgx-mx5q | CVE-2026-135030 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-jrm5-mmrr-5rwm | CVE-2026-135025 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-8f3c-qf59-f3ww | CVE-2026-134999 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Alsanet | spacebears | MK | 2026-11-25T04:44:56.696400+00:00 |
| BIURO RACHUNKOWE RACHEXPERT SPÓŁKA Z OGRANICZONĄ ODPOWIEDZIALNOŚCIĄ | spacebears | PL | 2026-11-25T02:44:43.562091+00:00 |
| Camsons Pty Ltd | spacebears | AU | 2026-11-25T02:44:02.668592+00:00 |
| ADN Energía S. de R.L. de C.V. (also referred to as ADN Energía or ADN Energia) | spacebears | MX | 2026-11-25T02:43:21.943236+00:00 |
| ABL Bio | everest |  | 2026-11-20T22:02:57.555361+00:00 |
| Kegler, Brown, Hill & Ritter | SilentRansomGroup | US | 2026-11-24T23:57:20.182737+00:00 |
| Nonigman LLP | SilentRansomGroup |  | 2026-11-24T23:26:44.109983+00:00 |
| O | medusalocker |  | 2026-11-24T22:53:30.636787+00:00 |
| Islasnatura | medusalocker | ES | 2026-11-24T22:52:57.504183+00:00 |
| Copperstone Clothing Company (Indian garment manufacturer/exporter, SQL Server ERP estate) | PixelLeaks | IN | 2026-11-24T22:34:48.213240+00:00 |
| Smile Designs LLC | rhysida |  | 2026-11-24T21:52:30.654506+00:00 |
| CSG Systems International | Falcon | US | 2026-11-24T21:22:14.809884+00:00 |
| Aimbridge Hospitality | Falcon | US | 2026-11-24T21:21:52.495210+00:00 |
| Greenbaum, Rowe, Smith, & Davis | SilentRansomGroup |  | 2026-11-24T20:43:09.775117+00:00 |
| H... R... | SilentRansomGroup |  | 2026-11-24T20:42:49.706663+00:00 |
| H... | SilentRansomGroup |  | 2026-11-24T20:41:34.308248+00:00 |
| K... B... | SilentRansomGroup |  | 2026-11-24T20:40:19.754402+00:00 |
| Archer & Greiner | SilentRansomGroup | DE | 2026-11-24T20:39:02.991578+00:00 |
| UltraBac Software | play | US | 2026-11-24T19:48:08.828002+00:00 |
| IRL Group | play | CA | 2026-11-24T19:47:34.760323+00:00 |

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
| 167.94.146.48 | 9 |
| 2.57.121.25 | 8 |
| 2.57.121.112 | 8 |
| 18.218.118.203 | 8 |
| 27.102.116.43 | 8 |
| 35.206.178.11 | 8 |
| 62.60.130.148 | 8 |
| 66.132.172.222 | 8 |
| 66.132.195.83 | 8 |
| 92.27.101.99 | 8 |
| 102.220.45.186 | 8 |
| 102.220.161.119 | 8 |
| 113.193.234.210 | 8 |
| 119.204.122.94 | 8 |
| 125.130.102.172 | 8 |
| 141.98.11.11 | 8 |
| 167.94.146.53 | 8 |
| 167.94.146.56 | 8 |
| 193.24.211.206 | 8 |

### OpenPhish (live phishing URLs)
- https://hsbcau.jrni.com/login
- https://hsbcau.jrni.com/
- https://djicameradrones.store/
- http://ladysmithpetsupplies-co-uk-109425-crp.pages.dev/
- http://official-good.mymidasbuy.cc.cd/
- http://mymidasbuys.gamerstored.com/
- http://netflix-clone-nine-beta-20.vercel.app/
- http://ifps62-58hfrz16z-arcadawebapps2.vercel.app/
- https://web.whatsappe.us.cc/
- http://rajafortei.pages.dev/
- https://akukuat.pages.dev/
- https://xjo25-1mg-gw1i-fnru2-28-09-2026-hh.pages.dev/
- http://ifps62-af7a9tq4g-arcadawebapps2.vercel.app/
- https://c1t77f.vercel.app/
- http://ifps62-5bi67kqct-arcadawebapps2.vercel.app/
- http://netflix-clone-chi-pearl.vercel.app/
- http://cock-oliot-f46c1.netlify.app/
- http://capable-caramel-55c524.netlify.app/
- http://ifps62-3ot7lat3p-arcadawebapps2.vercel.app/
- https://facebook-view.slplus.pro/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://member157.metaagencypartner.com/ |
| N/A | https://gtavi.luxe/ |
| N/A | https://128ddd4.pro/?id=V0XPeEq45ZQdv |
| N/A | https://gta6sol.xyz/ |
| N/A | https://h4dq5hv.cn/clickChallenge.php |
| N/A | https://ifps62-458rn4tdu-arcadawebapps2.vercel.app/ |
| N/A | https://ifps62-ag1rcrr19-arcadawebapps2.vercel.app/ |
| N/A | https://vmi3716826.contaboserver.net/gles/oyo/gles/card.php |
| N/A | https://allegrolokalnie.pl-oqloszenie91861419412159235125.sbs |
| N/A | https://vmi3716826.contaboserver.net/gles/oyo/gles/pin.php |
| N/A | https://vmi3716826.contaboserver.net/gles/oyo/gles/msg.php |
| 7.2 | https://allegro.spom38299.casa/ |
| 6.8 | http://1black-bit.exchange/ |
| 4.1 | https://www.brt-wi.eu.cc/it/ |
| 5.7 | https://t.me/BLACKBIT_support_official |
| 6.7 | https://capable-eclair-6d606f.netlify.app/ |
| 4.2 | https://www.brt-vc.eu.cc/it/ |
| 5.6 | https://www.brt-vx.eu.cc/it/ |
| 5.3 | https://www.brt-vn.eu.cc/it/ |
| 4.2 | https://www.brt-vs.eu.cc/it/ |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| d7d6b0e7c29950bee702ea2b0f253d6d4a232bd8 | PureLogsStealer C&C |
| 8ba9366306a3c0801ab5b7a4a52d9a19293cc867 | Vidar C&C |
| 0946c008154ff2809eca3d8c9e28e0ec0b8bacac | SeroRAT C&C |
| 5848fc12988a902dc95fd31897fc72884d332a47 | WeedStealer C&C |
| 85aa46f55739ebba1c0ad050262fdab387ab3db3 | Vidar C&C |
| 853c7cbd33c41f2a4651942d34a733403c89910b | FunStealer C&C |
| cfaeecab0d464737b0c8132f0302b4a2b5bbd149 | FunStealer C&C |
| 4da3273d01b7073f7218b69acadf32b0c57f35de | FunStealer C&C |
| 5d534c73e1fcbaad51fe510e822619d91e173e52 | FunStealer C&C |
| 85fcf32f16ea72d1c6327ab295a9bcbbfd08a644 | DCRat C&C |
| a51757af2edfa00116ada88c46d530474b3eea07 | Malware C&C |
| ccc7b03dc0841123fac4c5a518b74953711d8362 | PureLogsStealer C&C |
| c350ba2b9f3aeeb536476c111de25f3ccb5bb84e | PureLogsStealer C&C |
| 4d53fbd3a15b5220d7b092c0738564e7e6b8d00a | Malware C&C |
| b26fb89c001f599795543e012bb7c9314f2223ae | PureLogsStealer C&C |
| 2e6c34df036674422a595d391f1baedb3fb39027 | OffLoader C&C |
| bf3205fa0b555799dac3790a69a124777b6ef00d | Vidar C&C |
| c3cff7f03d5d7568c2d309491b88e1e8cb357fa6 | Vidar C&C |
| 48b0dec6d012b2281e6a23ea563f86e3bfe9f7ac | RatonRAT C&C |
| 5dbf16080b42e16892a7e78809ee51ce2c488570 | Vidar C&C |

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
- 1.12.55.80
- 1.14.64.225
- 1.141.32.230
- 1.161.133.251
- 1.162.242.67
- 1.183.197.192
- 1.183.25.86
- 1.192.216.175
- 1.194.211.36
- 1.203.149.250
- 1.212.225.99
- 1.214.204.138
- 1.214.214.114
- 1.215.233.74
- 1.220.198.126
- 1.222.42.237
- 1.222.80.212
- 1.226.84.248

### CINS Army (poorly-rated IPs)
- 1.14.3.170
- 1.15.88.48
- 1.168.206.193
- 1.170.200.20
- 1.177.162.2
- 1.189.41.213
- 1.192.129.106
- 1.193.100.138
- 1.20.151.114
- 1.204.35.156
- 1.213.214.233
- 1.224.162.188
- 1.24.16.104
- 1.24.16.125
- 1.24.16.138
- 1.24.16.143
- 1.24.16.144
- 1.24.16.150
- 1.24.16.158
- 1.24.16.161

## News (last ~36h, across outlets)
### The Hacker News
- [Credential Remediation Is Slow When You Don’t Know What Will Break](https://thehackernews.com/2026/11/credential-remediation-is-slow-when-you.html)
- [Drupal Fail2Install Exploit Details Emerge as Critical RCE Flaw Faces Active Exploitation](https://thehackernews.com/2026/11/drupal-fail2install-exploit-details.html)
- [Ex-OpenAI Employee Accused of Bugging Company Offices Granted $1 Million Bail](https://thehackernews.com/2026/11/ex-openai-employee-accused-of-bugging.html)
- [Hackers Exploited CVSS 10.0 Hex.pm RCE Flaw to Compromise 6 Package Registry Servers](https://thehackernews.com/2026/11/hackers-exploited-cvss-100-hexpm-rce.html)
- [Hackers Compromise 24 Check Point Management Servers in Suspected AI-Driven Attack Campaign](https://thehackernews.com/2026/11/hackers-compromise-24-check-point.html)
- [Com-Affiliated Hackers Hijack Cloud Accounts via Vishing for Data Theft and Extortion](https://thehackernews.com/2026/11/com-affiliated-hackers-hijack-cloud.html)
- [WordPress Blocks Six Backdoored WP Connect Plugins Before Malicious Releases Go Live](https://thehackernews.com/2026/11/wordpress-blocks-six-backdoored-wp.html)
- [Iran-Aligned Volant Manticore Uses IPFS-Based KuboShell Backdoor in Espionage Campaigns](https://thehackernews.com/2026/11/iran-aligned-volant-manticore-uses-ipfs.html)
- [VMware vCenter Hit by Another Critical 9.8-Rated Auth Bypass Flaw After Zero-Day Exploitation](https://thehackernews.com/2026/11/vmware-vcenter-hit-by-another-critical.html)
- [Okta Links ShinyHunters-Associated Vishing Group to New INCEPTION Data Leak Site](https://thehackernews.com/2026/11/okta-links-shinyhunters-associated.html)
- [Hackers Found a Way Around GitHub SHA Pinning. This Webinar Explains How to Close the Gap](https://thehackernews.com/2026/11/hackers-found-way-around-github-sha.html)
- [Google Researcher Shows How a Single Bit Change in .NET Files Bypassed Windows Code Integrity](https://thehackernews.com/2026/11/google-researcher-shows-how-single-bit.html)
- [2027 SOC Budget Reset: 5 Priorities to Cut Costs and Reduce Cyber Risk](https://thehackernews.com/2026/11/2027-soc-budget-reset-5-priorities-to.html)
- [Microsoft Fixes Azure API Management Classic Flaw as Actor Targets Customer Secrets](https://thehackernews.com/2026/11/microsoft-fixes-azure-api-management.html)
- [WHMCS SQL Injection Could Expose Customer Data and Admin Password Hashes without Login](https://thehackernews.com/2026/11/whmcs-sql-injection-flaw-could-expose.html)

### BleepingComputer
- [Microsoft fixes Microsoft 365 bug blocking access to Office apps](https://www.bleepingcomputer.com/news/microsoft/microsoft-fixes-blank-dialog-that-made-microsoft-365-office-apps-unusable/)
- [Hackers now exploit critical Drupal RCE flaw to hijack sites](https://www.bleepingcomputer.com/news/security/hackers-now-exploit-critical-drupal-rce-flaw-to-hijack-sites/)
- [Microsoft confirms authentication issues after November updates](https://www.bleepingcomputer.com/news/microsoft/microsoft-confirms-authentication-issues-after-november-updates/)
- [Hackers reportedly breached CIA intelligence analysis system](https://www.bleepingcomputer.com/news/security/hackers-reportedly-breached-cia-intelligence-analysis-system/)
- [Rackspace shuts down Spot cloud platform after security breach](https://www.bleepingcomputer.com/news/security/rackspace-shuts-down-spot-cloud-platform-after-security-breach/)
- [New Inception extortion gang launches large-scale vishing campaign](https://www.bleepingcomputer.com/news/security/new-inception-extortion-gang-launches-large-scale-vishing-campaign/)
- [Turnitin discloses cyberattack affecting customer-facing systems](https://www.bleepingcomputer.com/news/security/turnitin-discloses-cyberattack-affecting-customer-facing-systems/)
- [Radware discloses breach exposing customer cloud access keys](https://www.bleepingcomputer.com/news/security/radware-discloses-breach-exposing-customer-cloud-access-keys/)
- [ShinyHunters claims to return after FBI arrests, uses old PGP keys as proof](https://www.bleepingcomputer.com/news/security/shinyhunters-resurfaces-after-fbi-arrests-uses-old-pgp-keys-as-proof/)
- [European Commission confirms data theft in EU Academy breach](https://www.bleepingcomputer.com/news/security/european-commission-confirms-data-theft-in-eu-academy-breach/)
- [Hackers compromise Check Point Servers in 22 organizations](https://www.bleepingcomputer.com/news/security/hackers-compromise-check-point-servers-in-22-organizations/)
- [Police disrupt 57 illegal streaming services with 7.3 million visits](https://www.bleepingcomputer.com/news/security/police-disrupt-57-illegal-streaming-services-with-73-million-visits/)
- [From Vulnerability Noise to Resilience: Rethinking Security in the AI Era](https://www.bleepingcomputer.com/news/security/from-vulnerability-noise-to-resilience-rethinking-security-in-the-ai-era/)
- [McDonald's Japan data breach exposes customer location information](https://www.bleepingcomputer.com/news/security/mcdonalds-japan-data-breach-exposes-customer-location-information/)
- [New Shirudo tool uses AI to shield unpatched Linux systems from exploits](https://www.bleepingcomputer.com/news/security/new-shirudo-tool-uses-ai-to-shield-unpatched-linux-systems-from-exploits/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [Cyber Insurers See New Divide: AI Defense 'Haves' &amp; 'Have Nots'](https://www.darkreading.com/cybersecurity-operations/cyber-insurers-see-new-ai-divide)
- [Satellites Have a Ground-Level Cybersecurity Problem](https://www.darkreading.com/cyber-risk/satellites-ground-level-cybersecurity-problem)
- [Webworm APT Slithers Into Networks With Customized SoftEther VPN](https://www.darkreading.com/perimeter/webworm-slithers-customized-softether-vpn)
- ['God Mode' Flaws Could Wreak Border-Control Havoc](https://www.darkreading.com/vulnerabilities-threats/god-mode-flaws-wreak-border-control-havoc)

### SecurityWeek
- [Plagiarism Checker Turnitin Investigating Cyberattack](https://www.securityweek.com/plagiarism-checker-turnitin-investigating-cyberattack/)
- [Hackers Exploit Unpatched Flaw in Defunct Idunno AntiCsrf Library](https://www.securityweek.com/hackers-exploit-unpatched-flaw-in-defunct-idunno-anticsrf-library/)
- [Palo Alto Networks Patches Fragnesia Flaw Used to Root Firewalls](https://www.securityweek.com/palo-alto-networks-patches-fragnesia-flaw-used-to-root-firewalls/)
- [Drupal Flaw Found by Anthropic Scanner Exploited in Attacks](https://www.securityweek.com/drupal-flaw-found-by-anthropic-scanner-exploited-in-attacks/)
- [An Unclassified CIA System Was Breached in a Cyberattack, AP Source Says](https://www.securityweek.com/an-unclassified-cia-system-was-breached-in-a-cyberattack-ap-source-says/)
- [VMware Updates Patch Critical ESX, vCenter Vulnerabilities](https://www.securityweek.com/vmware-updates-patch-critical-esx-vcenter-vulnerabilities/)
- [European Commission Uncovers Data Breach in Cyberattack Investigation](https://www.securityweek.com/european-commission-uncovers-data-breach-in-cyberattack-investigation/)
- [Check Point Security Management Servers Hacked in AI-Assisted Campaign](https://www.securityweek.com/check-point-security-management-servers-hacked-in-ai-assisted-campaign/)
- [Anthropic Expands Enterprise Safeguards for Detecting AI Misuse](https://www.securityweek.com/anthropic-expands-enterprise-safeguards-for-detecting-ai-misuse/)
- [OpenAI, Cisco Unveil Open Source Tool to Shield Unpatched Linux Systems](https://www.securityweek.com/openai-cisco-unveil-open-source-tool-to-shield-unpatched-linux-systems/)

### The Record
- [Treasury's FinCEN takes systems offline after cybersecurity incident](https://therecord.media/treasury-fincen-takes-systems-offline-after-cyber-incident)
- [Colorado says cyberattack took down myColorado app, warns 150,000 had data stolen](https://therecord.media/mycolorado-app-down-data-breach)
- [California privacy agency director Kemp to leave after two-year tenure](https://therecord.media/california-privacy-agency-kemp)
- [Lawmakers warn ID verification companies to bolster security after September hack](https://therecord.media/idscan-data-breach-warning-congressional-letter)
- [Carnegie Endowment for International Peace says third-party breach leaked donation info](https://therecord.media/carnegie-endowment-data-breach)

### Infosecurity Magazine
- [US Treasury Investigates Cyber Incident Amid Reported Federal Agency Breaches](https://www.infosecurity-magazine.com/news/us-treasury-cyber-incident/)
- [Ransomware Attacks Surge 23% in October Following Record Quarter](https://www.infosecurity-magazine.com/news/ransomware-surge-october-record/)
- [NCSC Shares Guidance to Tackle Agentic Threat From ARTEX-Like Tools](https://www.infosecurity-magazine.com/news/ncsc-tips-tackle-agentic-threat/)
- [UK Authorized Push Payment Losses Surge 22% as Fraudsters Steal £660m](https://www.infosecurity-magazine.com/news/uk-app-losses-surge-22-fraudsters/)
- [New Inception Extortion Brand Tied to SSO Vishing Campaign](https://www.infosecurity-magazine.com/news/inception-extortion-sso-vishing/)
- [Address AI Agent Risks or Face Action, FCA Warns Financial Firms](https://www.infosecurity-magazine.com/news/ai-agent-risks-face-action-fca/)
- [Chinese Open-Weight AI Models Top Closed Ones at Vulnerability Discovery in New Test](https://www.infosecurity-magazine.com/news/chinese-ai-models-top/)
- [OpenAI and Cisco Release Open-Source Tool to Shield Unpatched Linux Systems](https://www.infosecurity-magazine.com/news/openai-cisco-shirudo-linux-shields/)
- [LaLiga Says Football Fans’ Personal Data Stolen](https://www.infosecurity-magazine.com/news/la-liga-says-football-fans/)
- [Researchers Find a New AI Attack Path: Agent Instructions](https://www.infosecurity-magazine.com/news/researchers-new-ai-attack-path/)

### CyberScoop
- [Unclassified intel system hit by hackers, affecting CIA, ODNI](https://cyberscoop.com/cia-odni-osint-data-breach/)
- [Patel mum on FBI crime info database hack, citing ongoing investigation](https://cyberscoop.com/kash-patel-fbi-ncic-database-hack/)
- [UK cyber agency, threat companies tracking rise in AI-assisted hacks](https://cyberscoop.com/uk-ncsc-ai-assisted-cyberattacks/)
- [Tomorrow’s quantum threat is today’s open door](https://cyberscoop.com/ot-security-post-quantum-cryptography-op-ed/)

### Cisco Talos
- [The Great Escape: Tradecraft insights from an agentic swarm](https://blog.talosintelligence.com/the-great-escape-tradecraft-insights-from-an-agentic-swarm/)
- [Securing Grandma's groceries with Pierre Cadieux](https://blog.talosintelligence.com/securing-grandmas-groceries-with-pierre-cadieux/)

### Unit 42 (Palo Alto)
- [NGINX HTTP/2 Use-After-Free: CVE-2026-123633](https://unit42.paloaltonetworks.com/cve-2026-123633-nginx-http2-vulnerability/)
- [Recent Trends and Tactics of Agentic AI Attacks](https://unit42.paloaltonetworks.com/autonomous-ai-agent-threat-campaigns/)

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Wednesday, November 25th, 2026 https://isc.sans.edu/podcastdetail/10194, (Wed, Nov 25th)](https://isc.sans.edu/diary/rss/33554)
- [Scanning from Subnet 109.160.32.0/24, (Mon, Nov 23rd)](https://isc.sans.edu/diary/rss/33550)
- [ISC Stormcast For Tuesday, November 24th, 2026 https://isc.sans.edu/podcastdetail/10192, (Tue, Nov 24th)](https://isc.sans.edu/diary/rss/33552)

### Securelist (Kaspersky)
- [How to protect against preinstalled Android malware](https://securelist.com/tr/how-to-protect-against-preinstalled-android-malware/122093/)

### CrowdStrike Blog
- [Reprioritizing Automated Leads with CrowdStrike Signal](https://www.crowdstrike.com/en-us/blog/reprioritizing-automated-leads-crowdstrike-signal/)
- [Java4Shell (CVE-2026-114938): CrowdStrike Detects Exposure and Post-Exploitation Activity](https://www.crowdstrike.com/en-us/blog/crowdstrike-helps-protect-against-java4shell-cve-2026-114938/)
- [NGINX2Root: Identify and Protect with the CrowdStrike Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-helps-protect-against-nginx2root-cve-2026-123007/)
- [CrowdStrike Is Building the Engine of the Agentic SOC with Falcon Next-Gen SIEM](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-gartner-mq-siem/)
- [CrowdStrike Brings the Human Advantage to AI Detection and Response](https://www.crowdstrike.com/en-us/blog/crowdstrike-brings-human-advantage-aidr/)
- [Hidden in the Weights: Supply Chain Risk from Backdoored LoRA Models](https://www.crowdstrike.com/en-us/blog/supply-chain-risk-from-backdoored-lora-models/)
- [Inside Falcon AI Gateway: One Control Point for AI Traffic](https://www.crowdstrike.com/en-us/blog/falcon-ai-gateway-one-control-point-for-ai-traffic/)
- [CrowdStrike Named a Leader in the 2026 IDC MarketScape for Worldwide Augmented Identity Security Solutions](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-idc-marketscape-worldwide-augmented-identity-security-solutions/)
- [November 2026 Patch Tuesday: 1,252 CVEs Include One Zero-Day and 68 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-november-2026/)
- [How Adversaries Are Turning the Vulnerability Ecosystem Against Defenders](https://www.crowdstrike.com/en-us/blog/adversaries-turn-vulnerability-ecosystem-against-defenders/)

### FortiGuard Threat Signal
- [BerriAI LiteLLM Guardrail Sandbox Escape RCE](https://fortiguard.fortinet.com/threat-signal-report/6686)
- [Apache Axis RCE in Confluence Data Center & N-able N-central](https://fortiguard.fortinet.com/threat-signal-report/6685)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal