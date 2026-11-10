# Winjit Daily TI Digest — 2026-11-10

_Auto-generated. Window: last ~24h. Fetched at 2026-11-10T10:53:53.683083+00:00Z_

**At a glance:** 4 new KEV · 132 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-102895 | GPUStack | GPUStack | GPUStack Improper Authentication Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-123158 | OpenBSD | OpenSSH | OpenBSD OpenSSH Unexpected Status Code or Return Value Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-116779 | SignalWire | FreeSwitch | SignalWire FreeSwitch Code Injection Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-123218 | IBM | Aspera Faspex | IBM Aspera Faspex Incorrect Authorization Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-124580 | 10.0 | 2.8% | A vulnerability was found in Chengdu Feiyuxing Technology VW2100 and VEC10GP 1.0 B-MB3W202-210825-r11775. This impacts the function handle_wechat_cn_wifi of the file var/html/webserver of the componen |
| CVE-2026-120017 | 10.0 | n/a | SAP NetWeaver AS ABAP and ABAP Platform does not perform sufficient verification of incoming authentication assertions under certain configurations. An unauthenticated attacker could submit specially  |
| CVE-2026-125086 | 10.0 | n/a | A vulnerability has been found in D-Link M60 1.12.B01. Impacted is the function system of the file /etc/emDaemon/mosquitto.conf of the component emDaemon MQTT Broker. Such manipulation leads to hard-c |
| CVE-2026-76964 | 10.0 | n/a | SAP NetWeaver Application Server ABAP does not sufficiently validate certain network input processed by an internal component. An unauthenticated attacker could send specially crafted network traffic  |
| CVE-2026-89103 | 10.0 | n/a | SAP Gateway activates the default Access Control List with high privileges allowing categorization of external attacker as internal application server. As a result an unauthenticated attacker with net |
| CVE-2026-89126 | 10.0 | n/a | SAP Web Dispatcher does not sufficiently validate certain network input processed by an internal component. An unauthenticated attacker could send specially crafted network traffic to trigger a memory |
| CVE-2026-124585 | 9.9 | 2.2% | A vulnerability was found in Chengdu Feiyuxing Technology VW2100 and VEC10GP 1.0 B-MB3W202-210825-r11775. This issue affects the function add_expmac of the file var/html/webserver of the component Web |
| CVE-2026-109795 | 9.9 | n/a | SAP NetWeaver does not perform necessary authorization checks and lacks sufficient input validation in certain remote-enabled functionality. An attacker with low privileges could send specially crafte |
| CVE-2026-109803 | 9.9 | n/a | SAP NetWeaver Knowledge Management (XML Forms) does not sufficiently restrict the selection of XSL transformations processed by the affected functionality. Under certain conditions, an authenticated u |
| CVE-2026-76965 | 9.9 | n/a | SAP NetWeaver Application Server ABAP and ABAP Platform does not perform necessary authorization checks for certain internal functionality. An attacker with low privileges could invoke affected functi |
| CVE-2026-124560 | 9.8 | 0.7% | A vulnerability was found in D-Link DIR-878 1.20B05. This affects the function GetCAPTCHAsetting of the file bin/prog.cgi of the component HNAP Handler. Performing a manipulation of the argument uid r |
| CVE-2026-124577 | 9.8 | 2.1% | A weakness has been identified in Intelbras SG 2404 PoE L2+ 1.00.70/1.00.72. The affected element is an unknown function of the file /EXCU_SHELL of the component Web Management Interface. Executing a  |
| CVE-2026-124079 | 9.8 | n/a | rConfig Core 8.0.0 before 8.2.19 and rConfig Pro before 8.4.1 contain a deserialization of untrusted data vulnerability that allows unauthenticated network attackers to execute arbitrary code by pushi |
| CVE-2026-125370 | 9.8 | n/a | Kubero 3.0.0 through 3.1.1 contains an authentication bypass vulnerability that allows unauthenticated remote attackers to forge administrative JWTs by using a hardcoded fallback signing secret when J |
| CVE-2026-125383 | 9.8 | n/a | INDOTALENT WHMS (Asp.Net-Core-Inventory-Order-Management-System) before 10.20261109 contains an authentication bypass vulnerability caused by a hard-coded JWT signing key, issuer and audience in appse |
| CVE-2026-125384 | 9.8 | n/a | INDOTALENT WHMS before 10.20261109 contains a default credentials vulnerability that allows unauthenticated attackers to gain administrator access because UserAdminSeeder creates admin@root.com with p |
| CVE-2026-89119 | 9.6 | n/a | SAP Web Dispatcher and SAP NetWeaver Application Server ABAP (Internet Communication Manager) do not perform sufficient request validation in certain administrative functionality. In the context of Ap |
| CVE-2026-60043 | 9.3 | n/a | An unauthenticated remote attacker can perform a XSS attack on a logged in backend user allowing for execution of multiple critical system actions. This could allow an attacker to shutdown the server  |
| CVE-2026-109798 | 9.1 | n/a | SAP BusinessObjects Business Intelligence Platform (Web Intelligence) does not properly restrict external entity resolution when processing OLAP connection requests. An authenticated attacker could ex |
| CVE-2026-76966 | 8.9 | n/a | Due to improper RFC protocol validation in the SAP Kernel used by the Application Server ABAP of SAP NetWeaver and ABAP Platform, an unauthenticated attacker can send a crafted RFC request that exploi |
| CVE-2026-16283 | 8.8 | n/a | Improper neutralization of special elements used in an OS command ('OS command injection') vulnerability in Osbil Technology Ltd.Osbil Technology Ltd. OPanel allows OS Command Injection.

This issue a |
| CVE-2026-12977 | 8.8 | n/a | A flaw was found in the deployment-operation family of WildFly Core. Certain handlers, such as upload-deployment-url, lack proper sensitivity classification, allowing an administrator with the restric |
| CVE-2026-125400 | 8.8 | n/a | Ettercap through 0.8.4.1 contains a use-after-free vulnerability in func_pcre() in src/ec_filter.c that reads the PCRE2 ovector after freeing match data. Network-adjacent attackers can send packets ma |
| CVE-2026-125406 | 8.8 | n/a | Ettercap through 0.8.4.1 contains a stack buffer underwrite vulnerability in the telnet dissector in src/dissectors/ec_telnet.c that decrements the output pointer on backspace without a lower bound ch |
| CVE-2026-56712 | 8.5 | n/a | Replicate Cog through 0.23.1 contains a server-side request forgery vulnerability that allows attackers to cause the Cog process to make server-side HTTP requests by submitting prediction inputs with  |
| CVE-2026-119610 | 8.2 | n/a | A flaw was found in GStreamer's gst-plugins-good, specifically in the H.264 RTP depayloader element. When processing MTAP16 or MTAP24 multi-time aggregation RTP packets, a signed/unsigned integer conv |
| CVE-2026-120008 | 8.2 | n/a | SAP NetWeaver (Internet Graphics Service) does not sufficiently validate certain input values within incoming requests. An unauthenticated user could send a specially crafted request to trigger an out |
| CVE-2026-120513 | 8.2 | n/a | The Everest Forms – Contact Form, Payment Form, Quiz, Survey & Custom Form Builder with AI plugin for WordPress is vulnerable to file deletion due to insufficient file path validation in the remove_cs |
| CVE-2026-95648 | 8.1 | n/a | Improperly controlled modification of Dynamically-Determined object attributes vulnerability in C-Prot Inc. C-Prot AppDefense allows Privilege Escalation.

This issue affects C-Prot AppDefense: before |
| CVE-2026-124001 | 8.1 | n/a | NASA JPL ION-DTN 2.2.1b through 4.2.0 contains an integer overflow vulnerability in the Datagram Retransmission (DGR) convergence layer that allows attackers to corrupt heap memory by sending a malici |
| CVE-2026-119759 | 8.1 | n/a | TrailBase 0.28.2 before 0.35.10 contains an insecure direct object reference vulnerability that allows authenticated attackers to manipulate the object-store id metadata within std.FileUpload columns  |
| CVE-2026-125358 | 8.1 | n/a | Universal-modder before commit e88f6876745427321eb755ebc98276063a962d8a contains a missing WebSocket Origin validation vulnerability in the HostLink class of its passthrough example mods that allows r |
| CVE-2026-125364 | 8.1 | n/a | frab through 0.9.1 contains a privilege escalation vulnerability that allows authenticated crew users to grant themselves orga roles by submitting unchecked nested conference_users_attributes. Attacke |
| CVE-2026-125401 | 8.1 | n/a | Ettercap through 0.8.4.1 contains a heap buffer overflow vulnerability in gg_get_version() in src/dissectors/ec_gg.c that writes up to 44 bytes into a 30-byte allocation. Remote attackers can send Gad |
| CVE-2026-125402 | 8.1 | n/a | Ettercap through 0.8.4.1 contains a heap out-of-bounds read vulnerability in sslw_get_clienthello_sni() in src/ec_sslwrap.c that trusts the unchecked 16-bit SNI length field. Network-adjacent attacker |
| CVE-2026-125403 | 8.1 | n/a | Ettercap through 0.8.4.1 contains an out-of-bounds read and size_t underflow vulnerability in sslw_remove_sts() in src/ec_sslwrap.c, caused by a stale length and an unchecked memmem() result when stri |
| CVE-2026-125405 | 8.1 | n/a | Ettercap through 0.8.4.1 contains an out-of-bounds read vulnerability in Parse_NTLM_Auth() in src/dissectors/ec_http.c due to unvalidated NTLM message offsets. Attackers can send a crafted HTTP Author |
| CVE-2026-76877 | 8.1 | n/a | The WPML Multilingual CMS plugin for WordPress is vulnerable to Authentication Bypass via Race Condition in versions up to, and including, 4.9.7. This is due to the `process_iframe_request` function's |
| CVE-2026-60041 | 8.1 | n/a | An unauthenticated remote attacker can perform a CSRF attack on a logged in backend user allowing for execution of multiple critical system actions. This could allow an attacker to shutdown the server |
| CVE-2026-125399 | 8.0 | n/a | Fluxion before 6.39 contains an OS command injection vulnerability in the fluxion.sh target scanner, which decodes access point ESSIDs with eval after escaping only single quotes. Attackers within Wi- |
| CVE-2026-119474 | 7.8 | n/a | Incorrect Permission Assignment for Critical Resource vulnerability in HAVELSAN Inc. Liman Render Engine allows Privilege Escalation.

This issue affects Liman Render Engine: before 1.2-81. |
| CVE-2026-125203 | 7.8 | n/a | FFmpeg before 8.1.3 and 9.x before 9.0.2 contains a heap buffer overflow vulnerability in the Cook multichannel decoder in libavcodec/cook.c that fails to verify subpacket channel masks are disjoint.  |
| CVE-2026-125209 | 7.8 | n/a | FFmpeg before 8.1.3 and 9.x before 9.0.2 contains a heap buffer overflow vulnerability in the DVD subtitle encoder that underestimates RLE output size for odd-width rectangles. Attackers can supply fi |
| CVE-2026-125229 | 7.8 | n/a | FFmpeg through 9.0.2 contains an out-of-bounds memory access vulnerability in the encode_frame() function of libavcodec/huffyuvenc.c, because encode_init() never validates minimum frame dimensions for |
| CVE-2026-125233 | 7.8 | n/a | FFmpeg through 9.0.2 contains a heap buffer overflow vulnerability in dvbsub_encode() in libavcodec/dvbsubenc.c that undercounts each CLUT segment header by two bytes. Attackers can supply a file with |
| CVE-2026-125244 | 7.8 | n/a | FFmpeg before 8.1.3 and 9.x before 9.0.2 contains an out-of-bounds write vulnerability in the VVC decoder's sh_entry_points() function in libavcodec/vvc/ps.c. Attackers can supply a crafted VVC (H.266 |
| CVE-2026-125250 | 7.8 | n/a | FFmpeg through 9.0.2 contains a heap buffer overflow in the GIF encoder's gif_image_write_image() in libavcodec/gif.c because shrunk_buf is sized from the first frame's linesize. Attackers can supply  |
| CVE-2026-125259 | 7.8 | n/a | FFmpeg through 9.0.2 contains an integer overflow vulnerability in ff_prores_kostya_encode_init() that miscalculates frame_size_upper_bound using 32-bit arithmetic for large frame dimensions. Attacker |
| CVE-2026-125262 | 7.8 | n/a | FFmpeg through 9.0.2 contains a heap buffer overflow vulnerability in libavcodec/lcevcdec.c because LCEVC output picture dimensions are not validated against the allocated frame. Attackers can embed c |
| CVE-2026-125267 | 7.8 | n/a | FFmpeg before 8.1.3 and 9.x before 9.0.2 contains a heap out-of-bounds write vulnerability in the APAC decoder in libavcodec/apac.c caused by an unreset bitstream index. Attackers can supply a crafted |
| CVE-2026-125396 | 7.8 | n/a | Ghostscript before 10.08.0 contains a -dSAFER bypass vulnerability in the .putgstringcopy procedure in gs_fonts.ps, which calls the privileged .forceput operator without checking operand types. Attack |
| CVE-2026-109800 | 7.7 | n/a | SAP Web Dispatcher does not sufficiently validate certain inputs during processing, which could lead to memory corruption. An attacker authenticated as a non-administrative user could exploit this vul |
| CVE-2026-120014 | 7.6 | n/a | SAP HANA XSA Web Dispatcher does not perform sufficient request validation in certain administrative functionality. In the context of SAP HANA XSA Web Dispatcher, an unauthenticated attacker could tri |
| CVE-2026-124561 | 7.5 | 0.5% | A vulnerability was determined in D-Link DIR-878 1.20B05. This impacts the function SetVLANSettings of the file prog.cgi of the component HNAP Handler. Executing a manipulation of the argument VID can |
| CVE-2026-124563 | 7.5 | 0.5% | A security flaw has been discovered in D-Link DIR-878 1.20B05. Affected by this vulnerability is the function SetWanSettings of the component HNAP Handler. The manipulation of the argument Primary/Sec |
| CVE-2026-121629 | 7.5 | n/a | A flaw was found in GStreamer's adaptive streaming demuxers (HLS, DASH, MSS). When processing a media playlist or manifest, URIs referenced in the manifest content are fetched without restricting whic |
| CVE-2026-119755 | 7.5 | n/a | Tasmota through 16.0.0, fixed in commit 1cb7ebc, contains a cross-site request forgery vulnerability that allows unauthenticated attackers to bypass Referer-based CSRF protection in HttpCheckPriviledg |
| CVE-2026-112320 | 7.5 | n/a | The GSS-RPC transport layer in MIT Kerberos 5 (aka krb5) 1.4 and later does not release the previous authentication context when a client switches from an RPCSEC_GSS or AUTH_GSSAPI flavor to a non-GSS |
| CVE-2026-112323 | 7.5 | n/a | The AUTH_GSSAPI handler in lib/rpc/svc_auth_gssapi.c in MIT Kerberos 5 (aka krb5) 1.5.2 and later allows remote attackers to cause a denial of service (memory exhaustion in kadmind) by sending repeate |
| CVE-2026-119079 | 7.5 | n/a | decode_sequence_of() in lib/krb5/asn.1/asn1_encode.c in MIT Kerberos 5 (aka krb5) 1.11 and later grows the decoded element array one entry at a time, which allows remote attackers to cause a denial of |
| CVE-2026-123999 | 7.5 | n/a | NASA JPL ION-DTN 3.6.2 through 4.2.0 contains a heap-based buffer overflow in the Network Management daemon (nm_mgr) string-formatting logic that allows a malicious or misconfigured agent to trigger a |
| CVE-2026-125368 | 7.5 | n/a | OmniAgent through commit 12b98c5 contains an approval bypass vulnerability in ReflexionAgent._is_safe_bash_command that treats any command starting with find as safe without inspecting -execdir argume |
| CVE-2026-125404 | 7.5 | n/a | Ettercap through 0.8.4.1 contains an integer underflow in ccmp_decrypt() in src/ec_encryption_ccmp.c that subtracts the 8-byte CCMP trailer without checking minimum length. Attackers on a network whos |
| CVE-2026-109793 | 7.5 | n/a | SAP NetWeaver Application Server ABAP and SAP Web Dispatcher do not sufficiently validate certain header values processed during inbound request handling. An unauthenticated attacker could send a spec |
| CVE-2026-109794 | 7.5 | n/a | SAP NetWeaver Application Server ABAP, ABAP Platform, and SAP Web Dispatcher do not sufficiently handle resource consumption when processing certain requests. An unauthenticated attacker could send sp |
| CVE-2026-109799 | 7.5 | n/a | The SAP Cloud SDK for Python contains an improper cryptographic signature verification vulnerability (CWE-347) in IASContextProvider, the runtime-context provider registered by default via bootstrap(a |
| CVE-2026-109804 | 7.5 | n/a | SAP Message Server does not properly handle certain malformed requests, which could be leveraged by an unauthenticated attacker to send specially crafted input. Successful exploitation could allow the |
| CVE-2026-109806 | 7.5 | n/a | SAP NetWeaver (Internet Graphics Service) does not sufficiently validate certain input values within incoming requests. An unauthenticated user could send a specially crafted request containing malfor |
| CVE-2026-109807 | 7.5 | n/a | SAP NetWeaver (Internet Graphics Service) does not sufficiently validate certain input values within incoming requests. An unauthenticated user could send a specially crafted request causing the affec |
| CVE-2026-120010 | 7.5 | n/a | SAP NetWeaver Application Server (SAP Message Server) does not properly size memory allocations when handling certain HTTP requests. An unauthenticated attacker could send a specially crafted request  |
| CVE-2026-120015 | 7.5 | n/a | SAP Host Agent does not sufficiently validate certain inputs. Under certain condition, an attacker with low privileges could abuse the affected functionality to influence an internal component into lo |
| CVE-2026-76970 | 7.5 | n/a | Due to a Memory Corruption vulnerability in Application Server ABAP for SAP NetWeaver and ABAP Platform, an unauthenticated attacker could send specially crafted requests to the application. If proces |
| CVE-2026-76973 | 7.5 | n/a | Due to a Memory Corruption vulnerability in Application Server ABAP of SAP NetWeaver and ABAP Platform, an unauthenticated attacker could send specially crafted network requests to the affected servic |
| CVE-2026-89114 | 7.5 | n/a | SAP NetWeaver AS Java EDM Application does not perform an authentication check for certain web service requests. An unauthenticated attacker could send a specially crafted request to retrieve sensitiv |
| CVE-2026-100386 | 7.5 | n/a | The Ultra Addons for Contact Form 7 plugin for WordPress is vulnerable to Directory Traversal in all versions up to, and including, 3.5.54 via the uacf7_wpcf7_mail_components function. This makes it p |
| CVE-2026-120012 | 7.5 | n/a | SAP Cloud SDK for AI (Node.js) could inadvertently include sensitive authentication credentials in error messages generated by certain internal operations under specific failure conditions. An attacke |
| CVE-2026-120013 | 7.5 | n/a | The agent_memory module accepts a caller-supplied tenant parameter in create_client(tenant=...). Prior to version 0.50.0, the tenant parameter was not validated before being used to construct filesyst |
| CVE-2026-60040 | 7.5 | n/a | An unauthenticated remote attacker can perform a DoS in the backends backup creation function. This can result in a total loss of availability. |
| CVE-2026-60044 | 7.5 | n/a | The backups created by the application use a weak static password allowing an unauthenticated remote attacker to access their content. This can result in a total loss of confidentiality. |
| CVE-2026-60046 | 7.5 | n/a | An unauthenticated remote attacker can perform password resets for any user with known username and email without rate limiting. This can result in a total loss of availabilit since the password will  |
| CVE-2026-124579 | 7.4 | 0.2% | A vulnerability was determined in aaPanel BillionMail up to 4.9. Affected by this issue is some unknown functionality of the file core/api/relay/v1/relay.go of the component Relay Configuration API. E |
| CVE-2026-124501 | 7.3 | 0.3% | A weakness has been identified in Tidelift moto up to 5.2.4. Affected is an unknown function of the file moto/batch/models.py of the component AWS Batch Emulation. This manipulation of the argument pr |
| CVE-2026-124554 | 7.3 | 0.3% | A security flaw has been discovered in JeecgBoot 3.9.5. This affects an unknown part of the file /jeecg-boot/drag/onlDragDatasetHead/getAllChartData of the component JimuBI. Performing a manipulation  |
| CVE-2026-124558 | 7.3 | 0.3% | A vulnerability has been found in DataLinkDC Dinky up to 1.2.5. The impacted element is the function SqlGateway.onOpen of the file SqlGateway.java of the component sql-gateway Endpoint. Such manipulat |
| CVE-2026-124573 | 7.3 | 0.4% | A vulnerability was found in logseq 2.0.1/2.0.2. This affects the function validate-auth-token of the file src/electron/electron/server.cljs of the component Local HTTP API. The manipulation results i |
| CVE-2026-124576 | 7.3 | 0.3% | A security flaw has been discovered in BeikeShop up to 2.0.0.31. Impacted is the function OrderRepo::getOrderByNumber of the file beike/Repositories/OrderRepo.php of the component Guest Order Lookup.  |
| CVE-2026-124581 | 7.3 | 0.3% | A vulnerability was determined in itsourcecode Airline Reservation System 1.0. Affected is an unknown function of the file /admin/manage_flight.php. This manipulation of the argument ID causes sql inj |
| CVE-2026-124586 | 7.3 | n/a | A vulnerability was determined in Tencent RapidJSON 1.1.0. Impacted is the function GetCachedPowerByIndex in the library include/rapidjson/internal/diyfp.h. This manipulation of the argument decimalPo |
| CVE-2026-124590 | 7.3 | n/a | A security vulnerability has been detected in zhangbw409 library_manager_system f6c9d9c96bf5d2a32ef741daeaa29d80e6db166b/56514767a5207caf5e04c2cea379dfaa8cb5f00b. This impacts the function BookControl |
| CVE-2026-125074 | 7.3 | n/a | A flaw has been found in SourceCodester Smart Attendance System with QR Code Scanner 1.0. This affects an unknown function of the file reset_password.php of the component Password Reset. This manipula |
| CVE-2026-125075 | 7.3 | n/a | A vulnerability has been found in SourceCodester Smart Attendance System with QR Code Scanner 1.0. This impacts the function getMessage of the file create_admin.php of the component Admin Account Crea |
| CVE-2026-125076 | 7.3 | n/a | A vulnerability was found in SourceCodester Smart Attendance System with QR Code Scanner 1.0. Affected is an unknown function of the file api/attendance_handler.php of the component JSON Endpoint. Per |
| CVE-2026-125087 | 7.3 | n/a | A vulnerability was found in Michael-A-Kuykendall Shimmy up to 2.6.4. The affected element is an unknown function of the file src/server.rs of the component Inference API. Performing a manipulation re |
| CVE-2026-125360 | 7.2 | n/a | Storyden through 1.26.16 contains a privilege escalation vulnerability that allows users holding MANAGE_ROLES to grant the ADMINISTRATOR permission without being administrators. Attackers can call Acc |
| CVE-2026-125382 | 7.2 | n/a | Map-OS 5.0.0 to before 5.2.2 contains a privilege escalation vulnerability in the REST users API that allows non-administrator operators holding the cUsuario permission to bypass permission-delegation |
| CVE-2026-125391 | 7.2 | n/a | Webmin through 2.670 contains an OS command injection vulnerability in samba/save_euser.cgi that allows authenticated Samba user maintainers to inject commands via unvalidated opts parameter. Attacker |
| CVE-2026-120009 | 7.2 | n/a | SAP ABAP Developer Tools (AMDP Data Preview) does not perform sufficient validation and authorization checks within certain affected functionality. An attacker with high privileges could submit specia |
| CVE-2026-84938 | 7.2 | n/a | The Avada (Fusion) Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via Form Notification Dynamic-Data action_hook → Media Upload Chain (ID3 Metadata / html_attributes) in all |
| CVE-2026-93427 | 7.2 | n/a | The ARMember Premium – Membership Plugin, Content Restriction, Member Levels, User Profile & User signup plugin for WordPress is vulnerable to Stored Cross-Site Scripting via Registration Custom Field |
| CVE-2026-60035 | 7.2 | n/a | A high privileged remote attacker can perform a code injection in the backends network auth function leading to code execution. This can result in a total loss of confidentiality, integrity and availa |
| CVE-2026-60036 | 7.2 | n/a | A high privileged remote attacker can perform a code injection in the backends patch activate function leading to code execution. This can result in a total loss of confidentiality, integrity and avai |
| CVE-2026-60037 | 7.2 | n/a | A high privileged remote attacker can perform an OpenSSL code injection in the frontends device importer function leading to code execution. This can result in a total loss of confidentiality, integri |
| CVE-2026-60038 | 7.2 | n/a | A high privileged remote attacker can perform an OpenSSL code injection in the backends ImportPKCS12 function leading to code execution. This can result in a total loss of confidentiality, integrity a |
| CVE-2026-60039 | 7.2 | n/a | A high privileged remote attacker can perform a code injection in the backends backup restore function leading to code execution. This can result in a total loss of confidentiality, integrity and avai |
| CVE-2026-125397 | 7.1 | n/a | NocoBase plugin-ai 2.1.0 through 2.2.41 contains an authorization bypass vulnerability in getAccessibleAIEmployee() that lets authenticated users access unassigned AI employees by overriding the role- |
| CVE-2026-125398 | 7.1 | n/a | Instatic before 0.0.21 contains an authorization bypass vulnerability in handleRowAuthor that allows authenticated users to skip table-level access checks by loading rows with getDataRow() instead of  |
| CVE-2026-109797 | 7.1 | n/a | In SAP/astonish, an authenticated user could potentially identify and operate on another team�s sandbox containers because of improper tenant isolation in the legacy Incus sandbox-management API handl |
| CVE-2026-125181 | 7.0 | n/a | FFmpeg through 9.0.2 contains an out-of-bounds write vulnerability in flic_decode_frame_15_16BPP() in libavcodec/flicvideo.c that allows attackers to corrupt heap memory on big-endian builds. Attacker |
| CVE-2026-125196 | 7.0 | n/a | FFmpeg through 9.0.2 contains a heap buffer overflow vulnerability in liboapve_encode() in libavcodec/liboapvenc.c that allows attackers to corrupt heap memory by supplying frames larger than the conf |
| CVE-2026-125201 | 7.0 | n/a | FFmpeg 7.0 before 8.1.3 and 9.x before 9.0.2 contains a heap out-of-bounds write vulnerability in vk_av1_decode_slice() in libavcodec/vulkan_av1.c because the tile-count limit is checked only on entry |
| CVE-2026-125202 | 7.0 | n/a | FFmpeg through 9.0.2 contains a heap buffer overflow vulnerability in vaapi_hevc_start_frame() in libavcodec/vaapi_hevc.c that copies unbounded PPS tile counts into fixed-size arrays. Attackers can su |
| CVE-2026-125204 | 7.0 | n/a | FFmpeg through 9.0.2 contains a heap buffer overflow in ff_libwebp_get_frame() in libwebpenc_common.c that lets attackers corrupt memory when cr_threshold is set. Attackers can supply crafted media th |
| CVE-2026-125208 | 7.0 | n/a | FFmpeg through 9.0.2 contains an out-of-bounds write vulnerability in v4l2_buffer_swframe_to_buf() in libavcodec/v4l2_buffers.c because cumulative plane offsets are not checked against the V4L2 buffer |
| CVE-2026-125210 | 7.0 | n/a | FFmpeg through 9.0.2 contains a heap buffer overflow vulnerability in aribcaption_trans_text_subtitle() in libavcodec/libaribcaption.c when decoding with sub_type text. Attackers can supply a crafted  |
| CVE-2026-125211 | 7.0 | n/a | FFmpeg through 9.0.2 contains an out-of-bounds read and invalid free vulnerability in aribcaption_trans_ass_subtitle() in libavcodec/libaribcaption.c that frees subtitle rectangles using region_count  |
| CVE-2026-125212 | 7.0 | n/a | FFmpeg through 9.0.2 contains a heap buffer overflow vulnerability in libavcodec/videotoolboxenc.c that copies frames larger than encoder dimensions into undersized CVPixelBuffers. Attackers can suppl |
| CVE-2026-125213 | 7.0 | n/a | FFmpeg through 9.0.2 contains a heap buffer overflow vulnerability in the PSD decoder in libavcodec/psd.c that allows attackers to corrupt heap memory on 32-bit builds by supplying a crafted PSD image |
| CVE-2026-125214 | 7.0 | n/a | FFmpeg through 9.0.2 contains a heap buffer overflow vulnerability in pcm_bluray_decode_frame() in libavcodec/pcm-bluray.c on big-endian hosts. Attackers can supply a crafted Blu-ray (M2TS) LPCM strea |
| CVE-2026-125218 | 7.0 | n/a | FFmpeg through 9.0.2 contains a heap buffer overflow vulnerability in the APNG encoder's encode_apng() function in libavcodec/pngenc.c when frame size changes mid-stream. Attackers can supply crafted  |
| CVE-2026-125219 | 7.0 | n/a | FFmpeg through 9.0.2 contains a heap buffer overflow vulnerability in vdpau_hevc_start_frame() in libavcodec/vdpau_hevc.c that copies unbounded PPS tile counts into fixed-size VDPAU arrays. Attackers  |
| CVE-2026-125222 | 7.0 | n/a | FFmpeg through 9.0.2 contains an integer overflow vulnerability in hap_parse_frame_header() in libavcodec/hapdec.c that allows attackers to trigger a heap buffer overflow on 32-bit builds. Attackers c |
| CVE-2026-125227 | 7.0 | n/a | FFmpeg through 9.0.2 contains an integer overflow in cbs_jpeg_write_scan() in libavcodec/cbs_jpeg.c that causes a heap buffer overflow on 32-bit builds. Attackers can supply a crafted MJPEG/JPEG strea |
| CVE-2026-125235 | 7.0 | n/a | FFmpeg through 9.0.2 contains a heap overflow vulnerability in libavcodec/qsvenc.c that allows attackers to corrupt memory by reusing an undersized pooled QSVFrame buffer when input dimensions increas |
| CVE-2026-125239 | 7.0 | n/a | FFmpeg through 9.0.2 contains a heap buffer overflow vulnerability in ff_dxva2_hevc_fill_picture_parameters() that allows attackers to corrupt memory via unbounded non-uniform tile counts. Attackers c |
| CVE-2026-125241 | 7.0 | n/a | FFmpeg through 9.0.2 contains a heap buffer overflow vulnerability in libavcodec/flicvideo.c that allows attackers to write out of bounds because check_pixel_ptr() checks only one bound with negative- |
| CVE-2026-125248 | 7.0 | n/a | FFmpeg 9.0 through 9.0.2 contains an integer overflow vulnerability in libavcodec/ffv1enc_vulkan.c that undersizes the float remap GPU buffer for large frames. Attackers can supply large GBRPF32 or GB |
| CVE-2026-125249 | 7.0 | n/a | FFmpeg 7.1 through 9.0.2 contains an integer overflow in ff_vk_decode_add_slice() in libavcodec/vulkan_decode.c that miscalculates the Vulkan hwaccel bitstream buffer size. Attackers can supply a craf |
| CVE-2026-125251 | 7.0 | n/a | FFmpeg through 9.0.2 contains an integer overflow vulnerability in the VVC decoder alloc_frame() function in libavcodec/vvc/refs.c that undersizes the reference picture list allocation on 32-bit build |
| CVE-2026-125256 | 7.0 | n/a | FFmpeg through 9.0.2 contains a heap buffer overflow vulnerability in ff_llvidenc_diff_bytes_rvv() that allows attackers to corrupt heap memory by triggering negative length values in the Huffyuv enco |
| CVE-2026-125257 | 7.0 | n/a | FFmpeg through 9.0.2 contains an off-by-one heap overflow vulnerability in get_exponent_dynamic() in libavcodec/nellymoserenc.c that allows writing one element past the opt and path allocations. Attac |
| CVE-2026-125260 | 7.0 | n/a | FFmpeg through 9.0.2 contains a heap buffer overflow vulnerability in libavcodec/exrenc.c that allows attackers to corrupt heap memory when encode_scanline_rle() processes frames taller than the encod |
| CVE-2026-125269 | 7.0 | n/a | FFmpeg through 9.0.2 contains a double free vulnerability in libavcodec/cbs_sei.c where cbs_sei_delete_message() leaves a stale extension_data reference that ff_cbs_sei_add_message() reuses. Attackers |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-xcxm-4wh9-23vp | CVE-2026-60043 | medium | An unauthenticated remote attacker can perform a XSS attack on a logged in backend user allowing... |
| GHSA-r2ff-5fcp-96f6 | CVE-2026-60045 | medium | A high privileged remote attacker can upload arbitrary files to a guessable location. This can... |
| GHSA-hcvq-v3xh-xrrm | CVE-2026-60042 | medium | An unauthenticated remote attacker can perform an authentication bypass on the com_check function... |
| GHSA-hgp2-6gpp-562r | CVE-2026-60039 | high | A high privileged remote attacker can perform a code injection in the backends backup restore... |
| GHSA-98gm-52cv-35p7 | CVE-2026-120513 | high | The Everest Forms – Contact Form, Payment Form, Quiz, Survey & Custom Form Builder with AI plugin... |
| GHSA-3567-fcjg-pc3v | CVE-2026-60046 | high | An unauthenticated remote attacker can perform password resets for any user with known username... |
| GHSA-26g2-hjw8-73rr | CVE-2026-60044 | high | The backups created by the application use a weak static password allowing an unauthenticated... |
| GHSA-rqc3-v8q5-m7g6 | CVE-2026-60038 | high | A high privileged remote attacker can perform an OpenSSL code injection in the backends... |
| GHSA-hpm8-58qv-f78j | CVE-2026-60036 | high | A high privileged remote attacker can perform a code injection in the backends patch activate... |
| GHSA-w7h4-7j86-vprg | CVE-2026-60041 | medium | An unauthenticated remote attacker can perform a CSRF attack on a logged in backend user allowing... |
| GHSA-fcfr-p987-qf2q | CVE-2026-60040 | high | An unauthenticated remote attacker can perform a DoS in the backends backup creation function.... |
| GHSA-77w8-w342-phm6 | CVE-2026-60035 | high | A high privileged remote attacker can perform a code injection in the backends network auth... |
| GHSA-wj7v-jw5v-h8vh | CVE-2026-60037 | high | A high privileged remote attacker can perform an OpenSSL code injection in the frontends device... |
| GHSA-hf6j-pj8j-p44q | CVE-2026-106025 | medium | The Cargo Shipping Location for WooCommerce WordPress plugin before 6.0 does not properly... |
| GHSA-4v54-xc3w-xcgr | CVE-2026-106007 | medium | The FraudLabs Pro SMS Verification WordPress plugin through 1.12.1 does not enforce its SMS-retry... |
| GHSA-rp3r-7x6g-5mw6 | CVE-2026-125652 | medium | A flaw was found in the keycloak-services component of Keycloak, which provides the core... |
| GHSA-p9ff-7qxh-95p9 | CVE-2026-100386 | high | The Ultra Addons for Contact Form 7 plugin for WordPress is vulnerable to Directory Traversal in... |
| GHSA-2mcx-4x33-hmm3 | CVE-2026-76877 | high | The WPML Multilingual CMS plugin for WordPress is vulnerable to Authentication Bypass via Race... |
| GHSA-rr28-rm36-gvjf | CVE-2026-93427 | high | The ARMember Premium – Membership Plugin, Content Restriction, Member Levels, User Profile & User... |
| GHSA-f43f-8f8g-rmhr | CVE-2026-84938 | high | The Avada (Fusion) Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via... |
| GHSA-p43j-wrmf-984c | CVE-2026-8372 | high | A vulnerability that could allow an attacker to gain unauthorized access. |
| GHSA-52m4-8mvq-w68j | CVE-2026-9063 | medium | A locally authenticated user can achieve privilege escalation via an insecure configuration that... |
| GHSA-8fwc-9jq4-4rmv | CVE-2026-119273 | unknown | The BulletProof Security WordPress plugin through 7.2 does not sufficiently protect its security... |
| GHSA-r57p-3w87-4r3m | CVE-2026-63288 | high | A WebSocket request sent to a specific API endpoint allows unauthorized access to a separate API... |
| GHSA-79r3-7f5r-67gf | CVE-2026-4762 | high | A vulnerability to perform a privilege escalation attack on the server as a non-admin user. |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| CRESA | Vortex | US | 2026-11-10T04:50:18.935641+00:00 |
| ALEXION | Vortex | US | 2026-11-10T04:49:46.187076+00:00 |
| PYRAMID HEALTHCARE | Vortex | US | 2026-11-10T04:49:12.202032+00:00 |
| Landmark Group | N0n | AE | 2026-11-10T01:53:03.920029+00:00 |
| Vertex Pharmaceuticals Incorporated | N0n | US | 2026-11-09T23:53:08.209771+00:00 |
| fhiworks | iah6477 |  | 2026-11-09T23:22:45.684888+00:00 |
| Irwin Automotive Group | Aoqin | US | 2026-11-09T22:51:05.015280+00:00 |
| Wilentz, Goldman & Spitzer | SilentRansomGroup |  | 2026-11-09T21:06:01.428547+00:00 |
| B... W... | SilentRansomGroup |  | 2026-11-09T19:06:39.173002+00:00 |
| Published | PixelLeaks |  | 2026-11-09T19:05:21.981778+00:00 |
| Ornico | Global Secret Group | ZA | 2026-11-09T18:54:40.368012+00:00 |
| Heartland Honda | Global Secret Group | US | 2026-11-09T18:53:36.260816+00:00 |
| M.C.S. Steel Public Company Limited | rhysida | TH | 2026-11-09T17:27:39.431342+00:00 |
| DomusVi | Black X | ES | 2026-11-10T04:56:53.842543+00:00 |
| Cameroon government troops leaked | HYFLOCK | CM | 2026-11-09T16:52:56.739848+00:00 |
| Vanderbilt EDU | BYOD | US | 2026-11-09T15:50:50.098302+00:00 |
| carrollins.com | everstake | US | 2026-11-09T15:16:03.614243+00:00 |
| Forus Deporte y Ocio S.L | Black X | ES | 2026-11-10T04:57:36.415215+00:00 |
| Company #211 | N0n | US | 2026-11-09T12:33:23.420544+00:00 |
| Company #210 | N0n | US | 2026-11-09T12:32:39.914572+00:00 |

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
| 45.148.10.141 | 10 |
| 45.148.10.151 | 10 |
| 45.148.10.157 | 10 |
| 18.218.118.203 | 9 |
| 45.148.10.152 | 9 |
| 185.87.121.1 | 9 |
| 193.32.162.15 | 9 |
| 193.47.62.111 | 9 |
| 195.178.110.227 | 9 |
| 2.57.121.25 | 8 |
| 2.57.121.112 | 8 |
| 3.129.187.38 | 8 |
| 3.131.220.121 | 8 |
| 35.206.150.39 | 8 |
| 35.210.125.55 | 8 |
| 35.210.172.21 | 8 |
| 46.151.178.14 | 8 |
| 64.62.197.32 | 8 |
| 64.62.197.77 | 8 |
| 66.132.172.104 | 8 |

### OpenPhish (live phishing URLs)
- https://www.facebook-q.blogspot.com/
- https://facebokksecurity.blogspot.com/
- https://www.facebokksecurity.blogspot.com/
- https://im.nbpublic.com/loading_page/walmart/walmart_cf_36/index.html?lptoken=176d947e255942fc86ca&cep=N4Igdgpg7g%2BgFgSwC4wQExALhARgEwCGAZgMwEBGRAtGngAwAcVALASWlQJxEDG1JDIgDYArCIiMSAdk4gANCABuCAM7JUGbGIZ48QqdR5DmdFp0JcSdIVTp0inKTxGdydThHlLV6pAgC2ECpIBP4ADlgg9HpUODi2nAAqOJyYeAyY1gB0JMwMAFpeympIAPYAThqRzOQiPDxSdCRURBBC8cwiFgwpEC3kPHRo9gZC7l48oWEECADmYFXYQpwMeRDOPCQuUjh2%2BMxoBpwYCmClaBCLIHQweF5nFzBIAJ5hntgAMgRgaAhgs%2FdzpceHAZmAsABta63EAAXQUYXKQQgABt1kgIGgYA93qAXm9Il8fn8AQoQuVZhAUOhIstVuYegw0PhyMM6PspMxGkJAY8adgbndThAAB5ILB417vEAAeSIrXKXnJlOpmhAdLWDEm2nIjXZeB4tQI1l5l350JudAAPjccDBrYL7fdReLMGAAK4olEAX29ChBYJgYVKJQQpXBmFAPHd5SRYCQADkgQBJH6irB0BTkcrfEGp348IKQ2F%2BkCqGBI35IniupDld0QBQARxUEUjpfLkCgWCIBBRKgg3qAA%3D&cpid=69848ec5c3597100124d7f9d
- https://www.i9rhmhd1.ztljm3t.cc/
- https://www.buthichiu2.sbs/
- https://metsmxkelogiioix.gitbook.io/us
- https://metsmxkelogiioix.gitbook.io/
- https://langkepot227.kamunanya.de/
- https://https--www--roblox.com/users/957484851/profile
- https://webtrz.com/
- https://btctrz.com/
- https://realtorbala.ca/soldge/iindex.html
- https://samtjo.com/base.html
- https://s4w.in/www-roblox-com-users-614640892-profile
- https://https--www--roblox.com/users/624640892/profile
- http://arbetsorder.sollander.se/frmLogin.aspx?ReturnUrl=%2f
- http://arbetsorder.sollander.se/
- https://facebook-account-manager.blogspot.com/
- https://sup-robertgaulin359.pages.dev/help/contact/821421682556360

### PhishStats (recent phishing/malicious URLs, scored)
_No data returned this run._

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| 6dabd1e1610022f44a5193e3f613d332b0449119 | PureLogsStealer C&C |
| 4e13fc3de8cecc9a0238827e64ed0a530912dea0 | ACRStealer C&C |
| ae4f978f970ebd6485a1c6993022a9b905f269ba | OffLoader C&C |
| 311e268a12c312f6327c3d7a7d697320793481c8 | ACRStealer C&C |
| f645b552ec56cfc6550b89e3202c53f74c2e980a | OffLoader C&C |
| 96b81644c0b65e34116351415b2bec72bf7fc5be | PureLogsStealer C&C |
| 0de85864ac1b98530883c917890196a0c99fd520 | ACRStealer C&C |
| 0d983264dd1f51176b28d44e1ab03223062c08ff | PureLogsStealer C&C |
| dea6f037aff488a491921f27b37d970d8abd1c62 | OffLoader C&C |
| 855d5d0a4d703037ee1404d889ecb8549eeaaac2 | Vidar C&C |
| 16baeb91ce496edc5c00b62f0d799c5f2ee24d46 | RemusStealer C&C |
| 627456b815281ec00d4c2ab6a4db2b442e00fa4d | RemusStealer C&C |
| 3a03f1046b52bdbfb2fd7df0ad76d1eb648d9f8c | Vidar C&C |
| 35609cd2534c4b828f923e7d81f479d4093d397f | Vidar C&C |
| 103d4b40526cfcb8ae77723be16950b20841fcd3 | Vidar C&C |
| 16c604429ce4dd69a4964d543af87dcce2a81666 | Vidar C&C |
| 12c04c8b919f955d8a3f74eca459dc64f2658674 | Vidar C&C |
| c362d3de5b0a3796b48049d602fa553aa7f33343 | Vidar C&C |
| adf7798c7a783ec41102797a93cb392e583c4061 | Vidar C&C |
| abc4b076eb276da57cf8a36e7eeca9df713dd83c | PureLogsStealer C&C |

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
- 1.13.181.113
- 1.14.140.218
- 1.15.227.58
- 1.161.133.214
- 1.162.217.195
- 1.172.90.41
- 1.175.131.108
- 1.180.246.242
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.220.198.126
- 1.222.42.237
- 1.226.82.243
- 1.234.27.159
- 1.234.53.65
- 1.234.80.94
- 1.235.183.146
- 1.238.106.229

### CINS Army (poorly-rated IPs)
- 1.15.31.90
- 1.160.141.202
- 1.164.152.19
- 1.164.20.118
- 1.169.3.7
- 1.183.226.72
- 1.193.56.135
- 1.193.63.59
- 1.20.151.114
- 1.220.119.115
- 1.223.11.69
- 1.24.16.101
- 1.24.16.103
- 1.24.16.108
- 1.24.16.110
- 1.24.16.122
- 1.24.16.13
- 1.24.16.130
- 1.24.16.132
- 1.24.16.14

## News (last ~36h, across outlets)
### The Hacker News
- [SAP Patches Four CVSS 10.0 Flaws, Including Two Enabling Remote Code Execution](https://thehackernews.com/2026/11/sap-patches-four-cvss-100-flaws.html)
- [France Blames Iran for Sabotage Attack on Refrigeration Controllers at About 700 Retail Sites](https://thehackernews.com/2026/11/france-blames-iran-for-sabotage-attack.html)
- [Anthropic's Claude Fable 5.2 Beats GPT-6 Cyber in Multi-Stage Cyberattack Benchmark](https://thehackernews.com/2026/11/anthropics-claude-fable-52-beats-gpt-6.html)
- [Google Issues Chrome Security Update for Eighth Actively Exploited Zero-Day of 2026](https://thehackernews.com/2026/11/google-issues-chrome-security-update.html)
- [N-able Takes N-central Cloud Offline After Researcher Discloses 33 Zero-Days with PoC Exploits](https://thehackernews.com/2026/11/n-able-takes-hosted-n-central-offline.html)
- [CISA Warns of Active Exploitation of OpenSSH, GPUStack, FreeSWITCH, and IBM Flaws](https://thehackernews.com/2026/11/cisa-warns-of-active-exploitation-of.html)
- [Hackers Exploit Qubole's Trusted AWS Access to Breach Customer Accounts and Steal Data](https://thehackernews.com/2026/11/hackers-exploit-quboles-trusted-aws.html)
- [Hackers Compromise Ethersphere's bee-js and Swarm Desktop to Deliver Wallet-Stealing Malware](https://thehackernews.com/2026/11/hackers-compromise-etherspheres-bee-js.html)
- [Bitter Hackers Deploy New PapRAT Backdoor in Cyberespionage Campaign Targeting South Asia](https://thehackernews.com/2026/11/bitter-hackers-deploy-new-paprat.html)
- [⚡ Weekly Recap: SSHole Exploited, APT Root RCE, Robot Takeovers, 15K Hacked Sites, and More](https://thehackernews.com/2026/11/weekly-recap-sshole-exploited-apt-root.html)
- [Default 'admin:admin' Server Password Helps Researchers Hack Two Automakers, Unlock and Start Cars](https://thehackernews.com/2026/11/default-adminadmin-server-password.html)
- [Web3Auth Flaw Exploited to Steal Keplr Crypto, Provider Empties Other Wallets for Safety](https://thehackernews.com/2026/11/web3auth-flaw-exploited-to-steal-keplr.html)
- [LNbits Urges All Operators to Shut Down Their Bitcoin Lightning Wallet Servers Amid Attacks](https://thehackernews.com/2026/11/lnbits-urges-all-operators-to-shut-down.html)
- [Taiwan-Based Hacker Used BOSSAI AI Agents to Steal Taipei Emergency Dispatch Records](https://thehackernews.com/2026/11/taiwan-based-hacker-used-bossai-ai.html)
- [Former OpenAI Engineer Pleads Not Guilty to Planting Covert Device in Executive Meeting Room](https://thehackernews.com/2026/11/former-openai-engineer-pleads-not.html)

### BleepingComputer
- [Hackers now exploit critical Barracuda ESG flaws to gain root access](https://www.bleepingcomputer.com/news/security/hackers-exploit-barracuda-email-security-gateway-flaws-to-get-root-access/)
- [Turla hackers use new Cereal malware to spy on govt Exchange servers](https://www.bleepingcomputer.com/news/security/turla-hackers-use-new-ceral-malware-to-spy-on-govt-exchange-servers/)
- [Google patches eighth Chrome zero-day exploited in attacks this year](https://www.bleepingcomputer.com/news/security/google-patches-eighth-chrome-zero-day-exploited-in-attacks-this-year/)
- [Fireworks AI discloses new breach after cloud provider hack](https://www.bleepingcomputer.com/news/security/fireworks-ai-discloses-new-breach-after-cloud-provider-hack/)
- [Vanderbilt University hit in BYOD ransomware attack, data theft claimed](https://www.bleepingcomputer.com/news/security/vanderbilt-university-hit-in-byod-ransomware-attack-data-theft-claimed/)
- [SEGA newsletter data breach exposes 2.2 million email addresses](https://www.bleepingcomputer.com/news/security/sega-newsletter-data-breach-exposes-22-million-email-addresses/)
- [N-able takes cloud platform offline after 30+ "zero-days" published](https://www.bleepingcomputer.com/news/security/n-able-takes-cloud-platform-offline-after-30-plus-zero-days-published/)
- [York University breach exposed personal information dating to 2007](https://www.bleepingcomputer.com/news/security/york-university-breach-exposed-personal-information-dating-to-2007/)
- [France blames Iranian hackers for supermarket attacks that sparked fires](https://www.bleepingcomputer.com/news/security/france-blames-iranian-hackers-for-supermarket-attacks-that-sparked-fires/)
- [Russian cloud firm Beget rebuilds from scratch after data wiper attack](https://www.bleepingcomputer.com/news/security/russian-cloud-firm-beget-rebuilds-from-scratch-after-data-wiper-attack/)
- [Binance denies data breach after alleged ShinyHunters claims](https://www.bleepingcomputer.com/news/security/binance-denies-data-breach-after-alleged-shinyhunters-claims/)
- [Hackers exploit SSHole OpenSSH flaw to breach Linux systems](https://www.bleepingcomputer.com/news/security/hackers-exploit-sshole-openssh-flaw-to-breach-linux-systems/)
- [The Biggest Threat to Your GRC Job Isn’t AI. It’s Ignoring AI.](https://www.bleepingcomputer.com/news/security/the-biggest-threat-to-your-grc-job-isnt-ai-its-ignoring-ai/)
- [FBI agent stole $2.5 million in crypto from hackers under investigation](https://www.bleepingcomputer.com/news/security/fbi-agent-stole-25-million-in-crypto-from-hackers-fraud-victims/)
- [US bans MEXC crypto exchange over sanctions evasion, cybercrime links](https://www.bleepingcomputer.com/news/security/us-bans-mexc-crypto-exchange-over-sanctions-evasion-cybercrime-links/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [CISA Announces Enhanced Reporting Form for Cyber Incidents](https://www.darkreading.com/cyberattacks-data-breaches/cisa-announces-enhanced-reporting-form-cyber-incidents)
- [Microsoft Fixes RCE Bug in Windows Paint After Weeks of Confusion](https://www.darkreading.com/application-security/microsoft-rce-bug-windows-paint-confusion)
- [Black Hat India 2026 Makes a Landmark Debut in Bengaluru, Bringing the Global Cybersecurity Community to India](https://www.darkreading.com/cybersecurity-operations/black-hat-india-2026-landmark-debut)
- [Attackers Crash Claude's 'Office Party' Flaw to Run Malicious Code on Linux](https://www.darkreading.com/endpoint-security/attackers-claude-office-party-flaw-malicious-code-linux)
- [PwC's CISO on AI, Robots &amp; What's Next for Security](https://www.darkreading.com/cybersecurity-operations/pwc-ciso-ai-robots-security)
- [NIST: Solo Shouldn't Mean Less Secure](https://www.darkreading.com/cybersecurity-operations/nist-solo-shouldnt-mean-less-secure)

### SecurityWeek
- [N-able Takes N-central Offline as Researcher Drops Over 30 Zero-Days](https://www.securityweek.com/n-able-takes-n-central-offline-as-researcher-drops-over-30-zero-days/)
- [IBM Aspera Faspex, SignalWire FreeSwitch Vulnerabilities Exploited in Attacks](https://www.securityweek.com/ibm-aspera-faspex-signalwire-freeswitch-vulnerabilities-exploited-in-attacks/)
- [France Blames Iran for a Cyberattack That Heated Supermarket Refrigerators](https://www.securityweek.com/france-blames-iran-for-a-cyberattack-that-heated-supermarket-refrigerators/)
- [Chrome Update Patches Exploited XML Zero-Day, Eighth This Year](https://www.securityweek.com/chrome-update-patches-exploited-xml-zero-day-eighth-this-year/)
- [Revolve Puts Data Breach Victim Count at 1.5 Million](https://www.securityweek.com/revolve-puts-data-breach-victim-count-at-1-5-million/)
- [Plex2Shell Exploited Against QNAP NAS Users](https://www.securityweek.com/plex2shell-exploited-against-qnap-nas-users/)
- [Iris Plaza Breach May Have Exposed Data of 7.7 Million Customers](https://www.securityweek.com/iris-plaza-breach-may-have-exposed-data-of-7-7-million-customers/)
- [Italy’s Meloni Blames Pro-Russian Hackers for Leak of Foreign Minister’s Data on the Dark Web](https://www.securityweek.com/italys-meloni-blames-pro-russian-hackers-for-leak-of-foreign-ministers-data-on-the-dark-web/)
- [Hackers Exploiting ‘SSHole’ Authentication Bypass in OpenSSH](https://www.securityweek.com/hackers-exploiting-sshole-authentication-bypass-in-openssh/)
- [Amplifon Americas Data Breach Impacts 1.3 Million](https://www.securityweek.com/amplifon-americas-data-breach-impacts-1-3-million/)

### The Record
- [Data breach at hearing aid giant Amplifon impacts thousands](https://therecord.media/amplifon-hearing-aid-company-data-breach)
- [France blames Iran for fridge cyberattacks, says some caused fires](https://therecord.media/france-blames-iran-for-fridge-cyberattacks)
- [Vanderbilt cybersecurity incident impacting campus devices and systems](https://therecord.media/vanderbilt-cyberattack-ransomware-alert)
- [Ukraine arrests four in $5 million crypto scam targeting Germans](https://therecord.media/ukraine-arrests-scam-call-centers-germany)
- [Alleged AI-aided cyberattack exploits assistant interface to breach German web host](https://therecord.media/cyberattack-germany-ai-mittwald)

### Infosecurity Magazine
- [France Blames Iran for Supermarket Fridge Hack, Requests International Arrest Warrants](https://www.infosecurity-magazine.com/news/france-blames-iran-supermarket/)
- [Binance Investigates ShinyHunters Breach Claims](https://www.infosecurity-magazine.com/news/binance-investigates-shinyhunters/)
- [Jailbroken AI Agent Ran Two-Week Attack on European Telecom](https://www.infosecurity-magazine.com/news/operation-snowball-ai-telecom/)
- [New Supply Chain Attack Compromises Tens of Thousands of GitHub Repositories](https://www.infosecurity-magazine.com/news/supply-chain-attack-thousands/)
- [Email Addresses of 2.2 Million Sega Customers Leaked in Vendor Breach](https://www.infosecurity-magazine.com/news/email-sega-customers-vendor-breach/)
- [Crédit Mutuel Arkéa Targeted in Reported $133m Heist](https://www.infosecurity-magazine.com/news/crdit-mutuel-arka-targeted/)
- [Anti-Money Laundering Watchdog FATF Targets Scam Compounds](https://www.infosecurity-magazine.com/news/aml-watchdog-fatf-scam-compounds/)

### CyberScoop
- [Russian Turla group used new toolset to silently pilfer emails from Kazakhstan, Romanian governments](https://cyberscoop.com/russian-turla-group-used-new-toolset-to-silently-pilfer-emails-from-kazakhstan-romanian-governments/)
- [Trump picks Palantir’s LoSapio to head CISA](https://cyberscoop.com/trump-picks-palantirs-losapio-to-head-cisa/)
- [AI doesn’t have to go rogue to break the world](https://cyberscoop.com/ai-hacking-risks-loopholes-bruce-schneier-defcon-keynote-op-ed/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
- [FORGE Lab uses agentic tools to identify memory safety issues in Rust](https://www.microsoft.com/en-us/security/blog/2026/11/09/forge-lab-uses-agentic-tools-to-identify-memory-safety-issues-in-rust/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Tuesday, November 10th, 2026 https://isc.sans.edu/podcastdetail/10172, (Tue, Nov 10th)](https://isc.sans.edu/diary/rss/33504)
- [Attackers Searching for SAP Netweaver Webshells, (Mon, Nov 9th)](https://isc.sans.edu/diary/rss/33502)
- [ISC Stormcast For Monday, November 9th, 2026 https://isc.sans.edu/podcastdetail/10170, (Mon, Nov 9th)](https://isc.sans.edu/diary/rss/33500)

### Securelist (Kaspersky)
- [IT threat evolution in Q3 2026. Non-mobile statistics](https://securelist.com/malware-report-q3-2026-pc-iot-statistics/121843/)
- [IT threat evolution in Q3 2026. Mobile statistics](https://securelist.com/malware-report-q3-2026-mobile-statistics/121844/)

### CrowdStrike Blog
- [How Adversaries Are Turning the Vulnerability Ecosystem Against Defenders](https://www.crowdstrike.com/en-us/blog/adversaries-turn-vulnerability-ecosystem-against-defenders/)
- [CrowdStrike Introduces Agentic Adversary Emulation to Counter AI-Enabled Adversaries](https://www.crowdstrike.com/en-us/blog/crowdstrike-agentic-adversary-emulation-counters-ai-enabled-adversaries/)
- [CrowdStrike Extends the Agentic SOC to Detect and Stop Agent Insider Threats](https://www.crowdstrike.com/en-us/blog/crowdstrike-detects-and-stops-agent-insider-threats/)
- [CrowdStrike Brings Enterprise Browser Security to the Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-brings-enterprise-browser-security-to-falcon-platform/)
- [New Falcon Cloud Security Innovations Secure the Cloud AI Runs On](https://www.crowdstrike.com/en-us/blog/falcon-cloud-security-innovations-secure-cloud-ai-runs-on/)
- [CrowdStrike Advances AI Security and Safety from Endpoint to Cloud](https://www.crowdstrike.com/en-us/blog/crowdstrike-advances-ai-security-and-safety-falcon-guardian/)
- [Introducing AI Kill Switch: Taking Control When AI Agents Go Rogue](https://www.crowdstrike.com/en-us/blog/crowdstrike-introduces-ai-kill-switch/)
- [CrowdStrike Secures AI Agents Inside Claude Cowork](https://www.crowdstrike.com/en-us/blog/crowdstrike-secures-ai-agents-inside-claude-cowork/)
- [CrowdStrike to Acquire Dreadnode to Bring Automated AI Security Testing to the Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-to-acquire-dreadnode/)
- [CrowdStrike to Acquire Fiddler to Deliver Falcon Observe for AI Agent Observability](https://www.crowdstrike.com/en-us/blog/crowdstrike-to-acquire-fiddler/)

### FortiGuard Threat Signal
- [OT Refrigeration Control Systems Attack](https://fortiguard.fortinet.com/threat-signal-report/6553)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/
- https://api.phishstats.info/api/phishing?_sort=-id&_size=30 -> 502 Server Error: Bad Gateway for url: https://api.phishstats.info/api/phishing?_sort=-id&_size=30

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal