# Winjit Daily TI Digest — 2026-11-09

_Auto-generated. Window: last ~24h. Fetched at 2026-11-09T11:08:47.980022+00:00Z_

**At a glance:** 0 new KEV · 119 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-123551 | 10.0 | 0.4% | OpenAM from 14.0.0 before 16.1.4 contains an information disclosure vulnerability that allows unauthenticated attackers to read live session tokens from the notification WebSocket. Attackers can bypas |
| CVE-2026-124580 | 10.0 | n/a | A vulnerability was found in Chengdu Feiyuxing Technology VW2100 and VEC10GP 1.0 B-MB3W202-210825-r11775. This impacts the function handle_wechat_cn_wifi of the file var/html/webserver of the componen |
| CVE-2026-124440 | 9.9 | n/a | Kyverno from 1.19.1 before 1.19.2 contains an authorization bypass vulnerability in the apiCall namespace clamp that allows namespace tenants to issue cross-namespace and cluster-scoped API requests b |
| CVE-2026-124450 | 9.9 | n/a | OpenEMR before 8.3.0 contains a broken access control and path traversal vulnerability in the fax/sms module disposeDocument action via an unvalidated file_path parameter. Authenticated low-privilege  |
| CVE-2026-124469 | 9.9 | n/a | OpenEMR before 8.3.0 contains an SQL injection vulnerability in the Fee Sheet drug-inventory lookup (DrugSalesService::sellDrug) that interpolates the prod[N][warehouse] POST field into an ORDER BY cl |
| CVE-2026-107331 | 9.9 | n/a | IBM DataStage on Cloud Pak for Data 5.4.0.0 could allow a remote authenticated attacker to obtain sensitive information due to an absolute-path traversal vulnerability. |
| CVE-2026-124585 | 9.9 | n/a | A vulnerability was found in Chengdu Feiyuxing Technology VW2100 and VEC10GP 1.0 B-MB3W202-210825-r11775. This issue affects the function add_expmac of the file var/html/webserver of the component Web |
| CVE-2026-123549 | 9.8 | 0.4% | OpenAM before 16.1.4 fails to enforce the Valid Creation Attributes list during self-registration, allowing anonymous attackers to set restricted attributes including group membership. Attackers can r |
| CVE-2026-123550 | 9.8 | 0.6% | OpenAM before 16.1.4 contains an authentication bypass vulnerability in its SAML v2.0 service provider that accepts unsigned assertions on the ECP (PAOS) and HTTP-Artifact bindings when WantAssertions |
| CVE-2026-123614 | 9.8 | 0.7% | imgproxy from 4.0.0 before 4.0.16 contains an integer overflow in the ICO loader that allows remote attackers to trigger a heap buffer overflow via a crafted data_size value. Attackers can submit a cr |
| CVE-2026-124427 | 9.8 | n/a | Craft CMS from 5.0.0 before 5.11.2 contains an authorization bypass vulnerability that allows anonymous GraphQL clients to read out-of-scope section entries via prev/next fields. Attackers can chain n |
| CVE-2026-124445 | 9.8 | n/a | OpenEMR from 7.0.1 before 8.4.0 contains a flaw in src/Common/Auth/OneTimeAuth.php that ignores the enforce_onetime_use and max_access_count flags, never revokes consumed service_auth tokens, and chec |
| CVE-2026-15266 | 9.8 | n/a | IBM Concert 1.0 through 3.0.1.1 contains components that allow potentially unsafe command execution, which could be exploited to run arbitrary system commands on the host. |
| CVE-2026-6715 | 9.8 | n/a | IBM Concert 1.0 through 3.0.1.1 allows an attacker can supply crafted input that is incorporated into an operating system command without adequate validation or sanitization. Successful exploitation a |
| CVE-2026-124560 | 9.8 | n/a | A vulnerability was found in D-Link DIR-878 1.20B05. This affects the function GetCAPTCHAsetting of the file bin/prog.cgi of the component HNAP Handler. Performing a manipulation of the argument uid r |
| CVE-2026-124577 | 9.8 | n/a | A weakness has been identified in Intelbras SG 2404 PoE L2+ 1.00.70/1.00.72. The affected element is an unknown function of the file /EXCU_SHELL of the component Web Management Interface. Executing a  |
| CVE-2026-114464 | 9.3 | n/a | IBM Process Mining 2.0.0 through 2.2.1 could allow a remote attacker to obtain sensitive information due to improper access control. |
| CVE-2026-124490 | 9.1 | n/a | OpenEMR before 8.3.0 contains a path traversal vulnerability in the RingCentral RCFaxClient disposeDocument() method of oe-module-faxsms that allows authenticated attackers to read and write arbitrary |
| CVE-2026-101117 | 9.1 | n/a | IBM WebSphere Extreme Scale 8.6.1.0 through 8.6.2.2 could allow a remote attacker to bypass security restrictions due to improper Content Security Policy configuration. |
| CVE-2026-17466 | 9.1 | n/a | IBM Optim 1.0.0, 1.1.0, and 1.2.0 could allow a remote authenticated attacker to obtain sensitive information due to path traversal. |
| CVE-2026-123531 | 8.8 | 0.4% | Vikunja from 1.0.0 before 2.7.1 contains an uncontrolled resource consumption vulnerability that allows authenticated users to bypass service.maxitemsperpage by sending page=0 to /api/v1 list endpoint |
| CVE-2026-123595 | 8.8 | 0.2% | Hickory DNS hickory-proto 0.25 through 0.26.0-alpha.1 and hickory-net 0.26.0-beta.1 before 0.26.2 contain a DNSSEC validation flaw in the validating recursor's NSEC3 handler, which matches the closest |
| CVE-2026-123596 | 8.8 | 0.2% | Hickory DNS hickory-proto through 0.26.0-alpha.1 and hickory-net 0.26.0-beta.1 before 0.26.2 contain a DNSSEC validation flaw in the validating recursor's NSEC handler that accepts parent-side ancesto |
| CVE-2026-123605 | 8.8 | 0.2% | Hickory DNS hickory-proto 0.1 through 0.25.0-alpha.3 and hickory-net before 0.26.2 contain a DNSSEC validation bypass because the validator verifies an RRSIG against the DNSKEY of whatever name appear |
| CVE-2026-124430 | 8.8 | n/a | Craft CMS from 5.10.0 before 5.11.2 contains a remote code execution vulnerability that allows non-administrator control panel users to obtain HMAC-signed Twig templates via the app/render-elements en |
| CVE-2026-124441 | 8.8 | n/a | Kyverno before 1.19.2 contains an authorization bypass vulnerability that allows namespaced tenants to generate any resource kind in any namespace by templating the generate rule's kind and namespace  |
| CVE-2026-124446 | 8.8 | n/a | OpenEMR before 8.3.0 contains a path traversal vulnerability in the FaxSMS module's RCFaxClient and SignalWireClient disposeDocument functions that allows authenticated low-privilege users to read and |
| CVE-2026-124467 | 8.8 | n/a | OpenEMR before 8.4.0 contains a local file inclusion in the ESign router (library/ESign/Router.php), which passes the unsanitized module parameter into a require_once of '<module>/Controller.php', and |
| CVE-2026-124477 | 8.8 | n/a | OpenEMR before 8.3.0 contains a missing authorization vulnerability that allows low-privileged authenticated users to delete arbitrary patient recall records via the delete_Recall action. Attackers ca |
| CVE-2026-124480 | 8.8 | n/a | OpenEMR before 8.4.0 contains an authorization bypass vulnerability that allows low-privileged authenticated users to read cross-patient FHIR QuestionnaireResponse data by sending the APICSRFTOKEN hea |
| CVE-2026-124484 | 8.8 | n/a | OpenEMR before 8.4.0 contains a missing authorization vulnerability in portal onsite-document APIs that allows any authenticated core user to access cross-patient documents. Attackers can omit the pat |
| CVE-2026-124486 | 8.8 | n/a | OpenEMR before 8.3.0 contains a missing authorization vulnerability in the classic document controller that allows low-privilege authenticated users to recategorize other patients' documents. Attacker |
| CVE-2026-117545 | 8.8 | n/a | IBM webMethods Integration Server 12.1 could allow a remote authenticated attacker to bypass security restrictions due to improper authentication. |
| CVE-2026-9764 | 8.8 | n/a | IBM Bob 1.0.4 through 2.0.1 could allow a remote attacker to inject arbitrary code on the system, due to the improper control of user input code. |
| CVE-2026-124463 | 8.7 | n/a | OpenEMR before 8.3.0 contains a stored cross-site scripting vulnerability that allows authenticated users with CAMOS access to inject HTML by saving malicious CAMOS content through ajax_save.php. Atta |
| CVE-2026-124483 | 8.3 | n/a | OpenEMR before 8.4.0 contains an incorrect authorization vulnerability because the prescription REST API routes check the patients.med ACL instead of patients.rx and request no specific permission bit |
| CVE-2026-124447 | 8.1 | n/a | OpenEMR before 8.3.0 contains an insecure direct object reference vulnerability in OnsitePortalActivityController::Update() that checks the request's patientId instead of the stored record's owner. Au |
| CVE-2026-124459 | 8.1 | n/a | OpenEMR before 8.3.0 contains an insecure direct object reference vulnerability in many encounter-form view and save endpoints that lack patient/encounter ownership checks. Authenticated clinical user |
| CVE-2026-124461 | 8.1 | n/a | OpenEMR before 8.3.0 contains a missing authorization vulnerability in library/ajax/upload.php that allows any authenticated user to read and overwrite document data by supplying an arbitrary doc_id.  |
| CVE-2026-124471 | 8.1 | n/a | OpenEMR before 8.3.0 contains a missing authorization vulnerability in interface/billing/sl_eob_invoice.php that allows any authenticated user to read and modify billing data for any encounter. Attack |
| CVE-2026-124472 | 8.1 | n/a | OpenEMR before 8.3.0 contains a missing authorization vulnerability in interface/billing/sl_eob_patient_note.php that allows any authenticated user to read and modify patient billing notes. Attackers  |
| CVE-2026-124488 | 8.1 | n/a | OpenEMR before 8.3.0 contains an authorization bypass vulnerability that allows authenticated clinicians lacking high-sensitivity permission to read and modify encounter-bound forms via load_form.php. |
| CVE-2026-105467 | 8.1 | n/a | IBM QRadar 7.5.0 through 7.5.0 Update Pack 16 Interim Fix 02, and 7.6.0.0 through 7.6.0.5 is vulnerable to Reflected XSS. A victim must open a specifically crafted URL while authenticated to QRadar to |
| CVE-2026-19133 | 8.1 | n/a | IBM Storage TS4500 Library 1.1.1.6 through 1.12.0.3 could allow a remote authenticated attacker to perform unauthorized account takeover due to improper authorization. |
| CVE-2026-97677 | 8.1 | n/a | IBM Langflow OSS 1.0.0 through 1.12.2 An authenticated flow author could write attacker-controlled file content into any directory writable by the service account, bypassing the platform's local file  |
| CVE-2026-118904 | 8.1 | n/a | IBM webMethods Integration Server 12.1 could allow a remote authenticated attacker to bypass security restrictions due to improper authentication. |
| CVE-2026-94249 | 8.1 | n/a | Missing Authorization vulnerability in TÜBİTAK BİLGEM Software Technologies Research Institute Liderahenk allows Privilege Abuse.

This issue affects Liderahenk: before 2.0.3. |
| CVE-2026-124436 | 8.0 | n/a | OpenRemote before 1.32.2 contains an improper authorization vulnerability that allows realm administrators to access and modify global resources by calling admin endpoints lacking super administrator  |
| CVE-2026-107330 | 7.7 | n/a | IBM DataStage on Cloud Pak for Data 5.4.0.0 could allow a remote authenticated attacker to obtain sensitive information due to a Server-Side Request Forgery (SSRF) vulnerability. |
| CVE-2026-124448 | 7.6 | n/a | OpenEMR before 8.3.0 contains a stored cross-site scripting vulnerability in the CCDA/CCD preview stylesheets, where cda.xsl copies event-handler attributes whose values evade a character denylist and |
| CVE-2026-124457 | 7.6 | n/a | OpenEMR before 8.3.0 contains a path traversal vulnerability in interface/billing/sl_eob_process.php that allows authenticated users to write and read files by supplying unsanitized eraname values. At |
| CVE-2026-124492 | 7.6 | n/a | SunEditor before 3.4.0 contains a stored cross-site scripting vulnerability in ModalAnchorEditor's #createBookmarkList, which inserts entity-decoded h1-h6 header textContent into the bookmark list via |
| CVE-2026-123543 | 7.5 | 0.4% | OpenAM before 16.1.4 contains a denial of service vulnerability that allows unauthenticated attackers to exhaust server resources by sending serialized Java data without size or structure limits. Atta |
| CVE-2026-123554 | 7.5 | 0.4% | Zebra zebrad 6.4.0 before 7.0.0 performs quadratic work in the mempool coinbase-maturity check because Transaction::coinbase_spend_restriction() rebuilds the transaction's output list once per spent o |
| CVE-2026-123555 | 7.5 | 0.4% | Zebra from 2.3.0 before 7.0.0 contains a denial of service vulnerability that allows unauthenticated peers to evade misbehavior scoring by sending transactions or blocks with invalid transparent scrip |
| CVE-2026-123558 | 7.5 | 0.3% | Zebra zebrad before 7.0.0 contains a denial of service vulnerability that allows a malicious peer to stall checkpoint sync by cancelling the verifier rewind after a failed commit. Attackers can serve  |
| CVE-2026-123559 | 7.5 | 0.3% | Zebra before 7.0.0 contains an inefficient algorithmic complexity vulnerability that allows unauthenticated peers to exhaust verification threads by submitting transactions with many transparent input |
| CVE-2026-123560 | 7.5 | 0.3% | Zebra before 7.0.0 contains an incomplete cleanup vulnerability that allows unauthenticated peers to stall initial sync by serving a forged checkpoint block body. Attackers can supply a body with forg |
| CVE-2026-123562 | 7.5 | 0.3% | devalue (sveltejs/devalue) 5.8.0 before 5.9.3 contains an unhandled promise rejection in stringifyAsync: when serializing multiple promises, a later promise rejecting before an earlier one settles lea |
| CVE-2026-123563 | 7.5 | 0.4% | Devalue before 5.9.3 contains a validation bypass vulnerability that allows custom ArrayBuffer revivers to skip typed-array allocation checks in the parse function. Attackers can supply very small cra |
| CVE-2026-123564 | 7.5 | 0.3% | Sveltejs devalue from 1.0.0 before 5.9.3 contains a memory exhaustion flaw in uneval, whose generated code for sparse arrays allocates memory proportional to the array's declared length when evaluated |
| CVE-2026-123565 | 7.5 | 0.3% | Sveltejs devalue before 5.9.3 contains a resource exhaustion vulnerability where repeated primitive strings cause quadratic expansion in the uneval function. Attackers can supply a small crafted paylo |
| CVE-2026-123566 | 7.5 | 0.3% | Sveltejs devalue before 5.9.3 contains a denial of service vulnerability that allows attackers to cause CPU amplification by supplying sparse arrays to uneval. Attackers who influence sparse values pa |
| CVE-2026-123569 | 7.5 | 0.3% | The devalue package for npm before 5.6.3 can consume excessive CPU and memory when serializing sparse arrays with uneval or stringify. An attacker who manages to get a sparse array created on the serv |
| CVE-2026-123570 | 7.5 | 0.4% | The DNS wire-format message parser in hickory-proto (Hickory DNS) 0.18 before 0.26.2 preallocates record vectors sized by the untrusted ANCOUNT, NSCOUNT, and ARCOUNT header fields before reading recor |
| CVE-2026-123571 | 7.5 | 0.4% | Hickory DNS from 0.26.0 before 0.26.2 contains an integer underflow vulnerability in TSIG RDATA decoding that allows remote attackers to trigger a panic via malformed records. Attackers can send a cra |
| CVE-2026-123572 | 7.5 | 0.3% | Hickory-dns from 0.20.1 before 0.26.2 contains a denial of service vulnerability in the hickory-proto SVCB and HTTPS record presentation format parser, which panics on malformed alpn values. Attackers |
| CVE-2026-123573 | 7.5 | 0.3% | hickory-dns from 0.20.1 before 0.26.2 contains a denial of service vulnerability in the hickory-proto SVCB and HTTPS record presentation format parser. Attackers can supply untrusted zone files where  |
| CVE-2026-123574 | 7.5 | 0.3% | The zone file parser in the hickory-proto crate of Hickory DNS 0.24.0 before 0.26.2 panics when a single token in a zone file is 4096 bytes or longer. Attackers who can supply untrusted zone files to  |
| CVE-2026-123575 | 7.5 | 0.4% | Hickory DNS before 0.26.2 contains a resource exhaustion vulnerability in its DNS-over-HTTPS HTTP/2 server that lacks sufficient timeouts or limits for incomplete request bodies. Remote attackers can  |
| CVE-2026-123576 | 7.5 | 0.4% | Hickory DNS 0.24.0 through 0.26.1 contains a memory exhaustion vulnerability that allows remote attackers to consume server resources by sending incomplete DNS-over-QUIC request bodies. Attackers can  |
| CVE-2026-123577 | 7.5 | 0.4% | Hickory DNS from 0.24.0 before 0.26.2 contains a resource exhaustion vulnerability that allows remote attackers to consume server memory via unbounded DoH request bodies. Attackers can send large requ |
| CVE-2026-123580 | 7.5 | 0.3% | Hickory DNS hickory-net 0.26.0-beta.1 before 0.26.2 and hickory-proto through 0.26.0-alpha.1 perform insufficient checks on NSEC3 record names during DNSSEC verification, comparing only the hashed lab |
| CVE-2026-123586 | 7.5 | 0.3% | Hickory DNS 0.25.0-alpha.3 through 0.25.2 contains a query amplification vulnerability in its recursive resolver, which mishandles cyclic sibling name server referrals that lack glue records. Attacker |
| CVE-2026-123588 | 7.5 | 0.3% | The recursive resolver in Hickory DNS (all versions of the hickory-recursor crate, and hickory-resolver 0.26.0 before 0.26.2) caches an empty connection pool when it follows a referral with no glue re |
| CVE-2026-123604 | 7.5 | 0.3% | Hickory DNS hickory-resolver 0.26.0-beta.1 before 0.26.2 contains an unbounded retry loop in NameServerPool::try_send, which re-queues truncated (TC) responses without checking the answering transport |
| CVE-2026-123606 | 7.5 | 0.4% | The hickory-dns recursor in hickory-recursor 0.25.0-alpha.3 through 0.25.2 and hickory-resolver 0.26.0-alpha.1 before 0.26.2 iterates every out-of-bailiwick NS target lacking glue in a referral withou |
| CVE-2026-123607 | 7.5 | 0.3% | Hickory DNS hickory-proto 0.25.0-alpha.3 through 0.25.2 and hickory-net before 0.26.1 contain an unbounded loop vulnerability in DnssecDnsHandle NSEC3 closest-encloser proof validation when the SOA ow |
| CVE-2026-123608 | 7.5 | 0.4% | Hickory DNS hickory-proto from 0.3.1 before 0.26.1 contains a denial of service vulnerability in BinEncoder that allows remote attackers to exhaust CPU through quadratic-time name compression. Attacke |
| CVE-2026-123615 | 7.5 | 0.5% | imgproxy 3.3.0 before 4.0.17 contains an out-of-bounds heap read and write in the ICO loader's BMP header reconstruction (vips_foreign_load_ico_header in vips/icoload.c) when an ICO entry declares a t |
| CVE-2026-123616 | 7.5 | 0.5% | imgproxy from 3.3.0 before 4.0.16 contains an unbounded memory allocation vulnerability in the ICO loader that fails to validate the data_size field. Attackers can supply a crafted 23-byte ICO file de |
| CVE-2026-124429 | 7.5 | n/a | Craft CMS from 5.0.0 before 5.11.2 contains a privilege escalation vulnerability that allows unauthenticated public registrants to reclaim deactivated non-admin accounts while retaining their direct p |
| CVE-2026-124437 | 7.5 | n/a | Scriban before 7.5.3 contains a resource exhaustion vulnerability that allows untrusted template authors to exhaust memory and CPU because builtins like math.format, regex.replace and string.escape sk |
| CVE-2026-124439 | 7.5 | n/a | Scriban and Scriban.Signed before 7.5.3 contain uncontrolled recursion flaws in which postfix member, indexer, and call chains bypass ExpressionDepthLimit, array comparison lacks depth and cycle check |
| CVE-2026-124553 | 7.5 | n/a | BabelDOC from 0.3.61 before 0.7.0 contains a resource exhaustion vulnerability that allows remote attackers to exhaust CPU and memory by supplying unbounded bfrange and cidrange spans. Attackers can s |
| CVE-2026-18093 | 7.5 | n/a | IBM App Connect Enterprise 13.0.1.0 through 13.0.8.2 could allow a remote attacker to obtain sensitive information due to broken access control. |
| CVE-2026-93879 | 7.5 | n/a | Hibernate Validator could allow a remote attacker to cause a denial of service due to uncontrolled resource consumption resulting from improper escaping of user-controlled data in Expression Language  |
| CVE-2026-96146 | 7.5 | n/a | IBM SevOne Network Performance Management 7.0.0 through 8.2.2 could allow a remote attacker to cause a denial of service due to uncontrolled resource consumption. |
| CVE-2026-124561 | 7.5 | n/a | A vulnerability was determined in D-Link DIR-878 1.20B05. This impacts the function SetVLANSettings of the file prog.cgi of the component HNAP Handler. Executing a manipulation of the argument VID can |
| CVE-2026-124562 | 7.5 | n/a | A vulnerability was identified in D-Link DIR-878 1.20B05. Affected is the function SetWanSettings of the component HNAP Handler. The manipulation of the argument ConfigDNS/Primary/ConfigDNS/Secondary  |
| CVE-2026-124563 | 7.5 | n/a | A security flaw has been discovered in D-Link DIR-878 1.20B05. Affected by this vulnerability is the function SetWanSettings of the component HNAP Handler. The manipulation of the argument Primary/Sec |
| CVE-2026-124328 | 7.4 | n/a | A vulnerability has been found in FlowCI flow-core-x up to 1.23.49. The affected element is the function ConditionManagerImpl.run of the file core/src/main/java/com/flowci/core/common/manager/Conditio |
| CVE-2026-124438 | 7.4 | n/a | Scriban before 7.5.2 contains an information disclosure and object manipulation vulnerability that allows template authors to access .NET internals of function values through reflection member accesso |
| CVE-2026-124579 | 7.4 | n/a | A vulnerability was determined in aaPanel BillionMail up to 4.9. Affected by this issue is some unknown functionality of the file core/api/relay/v1/relay.go of the component Relay Configuration API. E |
| CVE-2026-124331 | 7.3 | n/a | A vulnerability was identified in Jinher OA C6. This impacts an unknown function of the file /C6/JHSoft.Web.Project/OfficeReadOnly/ProjectAfficheManage.aspx. Such manipulation of the argument ProjID l |
| CVE-2026-124432 | 7.3 | n/a | phpMyFAQ 4.1.9 before 4.1.11 and 4.2.0 pre-releases before 4.2.0-beta.3 contain an account enumeration vulnerability in the unauthenticated POST /api/webauthn/prepare-login endpoint, which returns sta |
| CVE-2026-124501 | 7.3 | n/a | A weakness has been identified in Tidelift moto up to 5.2.4. Affected is an unknown function of the file moto/batch/models.py of the component AWS Batch Emulation. This manipulation of the argument pr |
| CVE-2026-124509 | 7.3 | n/a | A vulnerability was identified in floci-io Floci up to 2.1.0. The affected element is the function S3Destination.bucketName of the file services/firehose/model/DeliveryStreamDescription.java of the co |
| CVE-2026-124554 | 7.3 | n/a | A security flaw has been discovered in JeecgBoot 3.9.5. This affects an unknown part of the file /jeecg-boot/drag/onlDragDatasetHead/getAllChartData of the component JimuBI. Performing a manipulation  |
| CVE-2026-124557 | 7.3 | n/a | A vulnerability was detected in OtterMind Chat2DB up to 5.3.8. Impacted is the function DbMybatisGenerateServiceImpl.generateClass of the file DbMybatisGenerateServiceImpl.java of the component Class  |
| CVE-2026-124558 | 7.3 | n/a | A vulnerability has been found in DataLinkDC Dinky up to 1.2.5. The impacted element is the function SqlGateway.onOpen of the file SqlGateway.java of the component sql-gateway Endpoint. Such manipulat |
| CVE-2026-124573 | 7.3 | n/a | A vulnerability was found in logseq 2.0.1/2.0.2. This affects the function validate-auth-token of the file src/electron/electron/server.cljs of the component Local HTTP API. The manipulation results i |
| CVE-2026-124576 | 7.3 | n/a | A security flaw has been discovered in BeikeShop up to 2.0.0.31. Impacted is the function OrderRepo::getOrderByNumber of the file beike/Repositories/OrderRepo.php of the component Guest Order Lookup.  |
| CVE-2026-124581 | 7.3 | n/a | A vulnerability was determined in itsourcecode Airline Reservation System 1.0. Affected is an unknown function of the file /admin/manage_flight.php. This manipulation of the argument ID causes sql inj |
| CVE-2026-124586 | 7.3 | n/a | A vulnerability was determined in Tencent RapidJSON 1.1.0. Impacted is the function GetCachedPowerByIndex in the library include/rapidjson/internal/diyfp.h. This manipulation of the argument decimalPo |
| CVE-2026-124466 | 7.2 | n/a | OpenEMR before 8.4.0 contains a server-side request forgery vulnerability that allows unauthenticated attackers to make the server send HTTP requests by registering an OAuth2 client with an unvalidate |
| CVE-2026-123520 | 7.1 | 0.3% | Vikunja from 0.18.0 before 2.7.1 contains a privilege escalation vulnerability that allows team owners to gain admin or ownership of read-only shared projects by deleting accounts. Attackers can creat |
| CVE-2026-123522 | 7.1 | 0.3% | Vikunja before 2.7.1 contains an authorization bypass vulnerability that allows authenticated users to read any task by injecting a crafted task object into a no-op Kanban bucket move. Attackers can s |
| CVE-2026-123545 | 7.1 | 0.1% | OpenAM from 14.5.1 before 16.1.4 contains a cross-site request forgery vulnerability in the OAuth 2.0 device authorization flow that allows attackers to approve device codes when consent is skipped fo |
| CVE-2026-124424 | 7.1 | n/a | WWBN AVideo contains a path traversal vulnerability in plugin/AI/receiveAsync.json.php that allows holders of any valid AI token to write arbitrary .vtt files by injecting traversal sequences into the |
| CVE-2026-124434 | 7.1 | n/a | Grav Lightbox Gallery plugin 1.1.0 before 1.3.2 on Grav 2.x calls any medium method named in image, thumb or thumb_options shortcode values without core's allowed media action check. A page editor can |
| CVE-2026-124444 | 7.1 | n/a | OpenEMR before 8.4.0 contains a mass assignment vulnerability in the patient portal OnsiteDocument query API that lets request parameters set bitwise criteria filters whose values are placed unquoted  |
| CVE-2026-124453 | 7.1 | n/a | OpenEMR before 8.3.0 contains an insecure direct object reference vulnerability in portal/lib/persist.php that allows authenticated portal patients to write settings for other patients. Attackers can  |
| CVE-2026-124456 | 7.1 | n/a | OpenEMR before 8.3.0 contains missing authorization and insecure direct object reference vulnerabilities in the oe-module-prior-authorizations module that allow authenticated low-privilege users to ac |
| CVE-2026-124468 | 7.1 | n/a | OpenEMR before 8.3.0 contains an SQL injection vulnerability in the Standard REST API patient insurance and employer search, which concatenates query-string parameter names into SQL as column identifi |
| CVE-2026-124473 | 7.1 | n/a | OpenEMR before 8.3.0 contains a broken object-level authorization vulnerability in the SOAP note update API, which does not verify that the supplied SOAP note ID (sid) belongs to the supplied patient  |
| CVE-2026-124475 | 7.1 | n/a | OpenEMR before 8.3.0 contains an insecure direct object reference vulnerability in portal/lib/persist.php that allows authenticated portal patients to modify other patients' settings by supplying an a |
| CVE-2026-124489 | 7.1 | n/a | OpenEMR before 8.3.0 contains a broken access control vulnerability in portal/portal_payment.php that allows low-privilege authenticated users to bypass billing ACL checks by tampering patient identif |
| CVE-2026-18893 | 7.1 | n/a | IBM CockroachDB PostgreSQL for IBM VPC 26.2.0 through 26.2.3, 25.4.0 through 25.4.12, and 25.2.0 through 25.2.20 is vulnerable to privilege escalation via user-defined function. |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-4frq-3c52-pfc8 | CVE-2026-124580 | critical | A vulnerability was found in Chengdu Feiyuxing Technology VW2100 and VEC10GP 1.0 B-MB3W202-210825... |
| GHSA-vhgw-c286-8gqg | CVE-2026-124584 | medium | A vulnerability has been found in wummel patool 4.1.0. This vulnerability affects the function... |
| GHSA-crmj-h347-23x8 | CVE-2026-124579 | low | A vulnerability was determined in aaPanel BillionMail up to 4.9. Affected by this issue is some... |
| GHSA-q97r-7gmj-rv8g | CVE-2026-124582 | low | A vulnerability was identified in WebTorrent up to 2.8.5/3.0.21. Affected by this vulnerability... |
| GHSA-jgxp-544v-xp58 | CVE-2026-92606 | medium | Time-of-check time-of-use (TOCTOU) race condition vulnerability in TÜBİTAK BİLGEM Software... |
| GHSA-pcqp-9m3v-8mfc | CVE-2026-124581 | medium | A vulnerability was determined in itsourcecode Airline Reservation System 1.0. Affected is an... |
| GHSA-x7mj-p5qg-3rcg | CVE-2026-94249 | high | Missing Authorization vulnerability in TÜBİTAK BİLGEM Software Technologies Research Institute... |
| GHSA-vw5w-mm6p-3m38 | CVE-2026-124585 | high | A vulnerability was found in Chengdu Feiyuxing Technology VW2100 and VEC10GP 1.0 B-MB3W202-210825... |
| GHSA-9vm4-3239-475g | CVE-2026-116337 | low | Uncontrolled resource consumption vulnerability in the Qt Framework HTTP response handling... |
| GHSA-v7j8-qp7g-hgm2 | CVE-2026-124575 | medium | A vulnerability was identified in SiteServer SSCMS up to 7.1.3/7.2.1/7.4.0. This issue affects... |
| GHSA-3p42-pj8h-255g | CVE-2026-124577 | high | A weakness has been identified in Intelbras SG 2404 PoE L2+ 1.00.70/1.00.72. The affected element... |
| GHSA-5g96-mq2h-p82p | CVE-2026-124578 | medium | A security vulnerability has been detected in Pantum BP5100DW 3.A.4.7. The impacted element is an... |
| GHSA-5952-4gv2-m5gj | CVE-2026-124572 | medium | A vulnerability has been found in DataLinkDC dinky up to 1.2.5. Affected by this issue is the... |
| GHSA-956h-hcvx-725f | CVE-2026-113437 | medium | Path Traversal vulnerability exists in SS1/ SS1 Cloud provided by DOS Co., Ltd. and the ODM... |
| GHSA-8xq4-4x26-rxrw | CVE-2026-124574 | low | A vulnerability was determined in chenyme grok2api up to 3.1.6. This vulnerability affects the... |
| GHSA-5655-hp8h-9ffj | CVE-2026-124576 | medium | A security flaw has been discovered in BeikeShop up to 2.0.0.31. Impacted is the function... |
| GHSA-2f7g-3rp5-238m | CVE-2026-109582 | medium | Insecure storage of sensitive information issue exists in SS1 provided by DOS Co., Ltd. Sensitive... |
| GHSA-v9cp-82qp-rrj6 | CVE-2026-123751 | unknown | The WP Duplicate  WordPress plugin through 1.1.11 does not properly verify a request... |
| GHSA-g285-q6c3-f488 | CVE-2026-120386 | medium | Effekseer improperly validates "effect" files. When a crafted effect file is loaded to the... |
| GHSA-frjm-xwcq-24jh | CVE-2026-123131 | unknown | The GemBooking  WordPress plugin before 1.7.1 does not properly verify that a REST request is... |
| GHSA-45wf-gcw8-5mwr | CVE-2026-124573 | medium | A vulnerability was found in logseq 2.0.1/2.0.2. This affects the function validate-auth-token of... |
| GHSA-93w9-c7qv-9m7x | CVE-2026-81422 | unknown | The Advanced Appointment Booking & Scheduling WordPress plugin before 2.7 does not verify the... |
| GHSA-rxc3-24xx-6g22 | CVE-2026-123088 | unknown | The UniPAY Payment Gateway For WooCommerce WordPress plugin before 2.4 does not perform any... |
| GHSA-vh4g-j777-hw5v | CVE-2026-123064 | unknown | The WP BASE Booking of Appointments, Services and Events WordPress plugin before 6.5.1 does not... |
| GHSA-gqcc-52m4-8mqh | CVE-2026-123129 | unknown | The Event Tickets Manager for WooCommerce WordPress plugin before 1.6.0 does not validate the... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Cuomo LLC | anubis |  | 2026-11-09T03:59:31.354287+00:00 |
| Expedia Group, Inc. | N0n | US | 2026-11-09T00:52:31.602271+00:00 |
| Grupa ABS | Panzer | PL | 2026-11-09T00:55:15.649045+00:00 |
| ADG Blatt | Barracuda | DE | 2026-11-08T22:50:42.119031+00:00 |
| Fidex | Deadlock | MX | 2026-11-08T19:51:54.679870+00:00 |
| NoseTea | Deadlock | US | 2026-11-08T19:51:32.761876+00:00 |
| Coopebis | Deadlock | CR | 2026-11-08T18:21:29.011582+00:00 |
| Trinity Custom Homes - USA | Deadlock | US | 2026-11-08T15:21:58.987917+00:00 |
| Chonlatee | Deadlock | TH | 2026-11-08T15:21:38.545972+00:00 |
| Kadick | Deadlock | US | 2026-11-08T15:21:17.135662+00:00 |
| sunclinicallaboratories.com | lockbit5 | US | 2026-11-08T23:28:39.584061+00:00 |
| yatra.com | lockbit5 | IN | 2026-11-08T23:30:44.922271+00:00 |
| grupotelles.com | lockbit5 | BR | 2026-11-08T23:32:52.232773+00:00 |
| starmark.co.th | lockbit5 | TH | 2026-11-08T23:34:54.344818+00:00 |
| Twitter | BYOD | US | 2026-11-08T03:20:51.920702+00:00 |
| www.bogard.com.mx | incransom | MX | 2026-11-08T03:47:21.145552+00:00 |
| bpcm.com | incransom | US | 2026-11-08T03:48:13.488273+00:00 |
| Clínica La Sagrada Familia (Colombia) | Whitearmor | CO | 2026-11-08T03:33:23.256858+00:00 |
| q-technicians.be | incransom | BE | 2026-11-08T03:49:05.694674+00:00 |
| IE & E Industries | Orova | US | 2026-11-09T00:53:07.359272+00:00 |

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
| 18.218.118.203 | 9 |
| 45.148.10.141 | 9 |
| 64.62.197.227 | 9 |
| 66.132.172.194 | 9 |
| 66.132.172.214 | 9 |
| 66.132.195.53 | 9 |
| 167.94.146.50 | 9 |
| 167.94.146.56 | 9 |
| 167.94.146.58 | 9 |
| 193.32.162.15 | 9 |
| 193.47.62.69 | 9 |
| 2.57.121.25 | 8 |
| 2.57.121.112 | 8 |
| 3.130.168.2 | 8 |
| 35.210.191.203 | 8 |
| 45.148.10.151 | 8 |
| 45.148.10.152 | 8 |
| 46.151.178.14 | 8 |
| 64.62.197.32 | 8 |

### OpenPhish (live phishing URLs)
- https://www.r.oblox.com.et/users/893593163/profile
- https://hkdiscord.antsoon.com/blog/iwd-2023-two-women-owned-servers
- https://hkdiscord.antsoon.com/blog/how-we-used-discord-to-build-a-dream-community-for-our-game-descenders
- https://hkdiscord.antsoon.com/blog/how-discord-celebrated-pride-month-2024
- https://hkdiscord.antsoon.com/ads/quests-success-stories
- https://hkdiscord.antsoon.com/company
- https://hkdiscord.antsoon.com/terms
- https://hkdiscord.antsoon.com/category/how-to-discord
- https://hkdiscord.antsoon.com/press-releases/wicked-saints-turns-players-into-irl-superheroes-with-e-l-f-beauty-and-discord
- https://hkdiscord.antsoon.com/press-releases/discord-zach-cregger-resident-evil-missions-quest-activation
- https://hkdiscord.antsoon.com/press-releases/discord-launches-teen-by-default-settings-globally
- https://hkdiscord.antsoon.com/download
- https://hkdiscord.antsoon.com/safety-privacy
- https://hkdiscord.antsoon.com/safety-transparency
- http://sp29ct-zamvi-biz-felun-rakti.pages.dev/
- https://instanoreply11-sudo.github.io/instagramweb
- https://steanmcomnnunituy.ru/id/765678242749728
- https://is.gd/steamcommunity765678242749728
- https://www.roblox.com.ml/users/237525484580/profile/
- https://www.j115f.vip/downapp

### PhishStats (recent phishing/malicious URLs, scored)
_No data returned this run._

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| abc4b076eb276da57cf8a36e7eeca9df713dd83c | PureLogsStealer C&C |
| 19191f7bd7d31b4da986d645a6dfba8fef74fdf9 | OffLoader C&C |
| 4943decccfc5b78cd1d60fab5424bd93d5243aa3 | FunStealer C&C |
| 699efdab8a4d32ffa62dd1a97261e3edd5c5f87a | PureLogsStealer C&C |
| d7f8e6d688805e759b5e9346215212cd246a4b3c | PureLogsStealer C&C |
| 5ccb6f0fb1de883e059a42b51e192eb4fca92373 | PureLogsStealer C&C |
| fb642f9c2a93001eca125a11326d4ff6c0edd834 | PureLogsStealer C&C |
| 0a86f564799b68d6daec13f71654431f5bceba37 | ACRStealer C&C |
| ea53cd87676a1e4bcc32a376166e21c729695daf | Vidar C&C |
| 9b3e876bcc01d08cdcfaf88ee65cdd0a37d19ac9 | RemusStealer C&C |
| 105f909fc4a6d331ae1f63b5b85d5260c9bb5dfd | RemusStealer C&C |
| 54f3060077130ecb0878934a52d37ec9994b2959 | Vidar C&C |
| 3cca61aae64588c6aeb99e549121bd90845df64b | RemusStealer C&C |
| 77c2751f1c3f54478af095b519ee9bda9ae6a893 | RemusStealer C&C |
| 3196a6cb1fa37ee8fccc0ad7e384f3abb7e83116 | RemusStealer C&C |
| 74dbbbef44c355626c83aa8cedcbb86ea6acec58 | Vidar C&C |
| bfbccde2f1ab3e71036fa5b002fb9604a078ac48 | Vidar C&C |
| 2da35ee777136d88d2a5808ab5c9453a40fa8662 | RevStealer C&C |
| 0ee0b095e959aecfb96297890ea5720c00dbfbc9 | Vidar C&C |
| f27ee2327532465a3db66496a09ad92e8d47abdb | Malware C&C |

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
- 1.12.70.212
- 1.13.181.113
- 1.14.140.218
- 1.14.192.95
- 1.14.240.247
- 1.15.227.58
- 1.159.54.33
- 1.161.133.214
- 1.162.217.195
- 1.172.90.41
- 1.175.131.108
- 1.180.246.242
- 1.20.104.16
- 1.203.149.250
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.226.82.243
- 1.234.27.159

### CINS Army (poorly-rated IPs)
- 1.12.229.231
- 1.169.35.122
- 1.183.226.72
- 1.192.129.106
- 1.20.151.114
- 1.24.16.103
- 1.24.16.104
- 1.24.16.108
- 1.24.16.11
- 1.24.16.12
- 1.24.16.122
- 1.24.16.124
- 1.24.16.125
- 1.24.16.131
- 1.24.16.133
- 1.24.16.145
- 1.24.16.146
- 1.24.16.156
- 1.24.16.16
- 1.24.16.17

## News (last ~36h, across outlets)
### The Hacker News
- [LNbits Urges All Operators to Shut Down Their Bitcoin Lightning Wallet Servers Amid Attacks](https://thehackernews.com/2026/11/lnbits-urges-all-operators-to-shut-down.html)
- [Taiwan-Based Hacker Used BOSSAI AI Agents to Steal Taipei Emergency Dispatch Records](https://thehackernews.com/2026/11/taiwan-based-hacker-used-bossai-ai.html)
- [Former OpenAI Engineer Pleads Not Guilty to Planting Covert Device in Executive Meeting Room](https://thehackernews.com/2026/11/former-openai-engineer-pleads-not.html)
- [U.S. Agencies Warn Refrigeration Controller Attacks Could Cause Fires and Inventory Losses](https://thehackernews.com/2026/11/us-agencies-warn-refrigeration.html)
- [CISA Flags SonicWall SonicOS MFA Bypass Flaw Amid Reports of Possible Exploitation](https://thehackernews.com/2026/11/cisa-flags-sonicwall-sonicos-mfa-bypass.html)

### BleepingComputer
- [Iris Ohyama data cloud breach exposes info of 7.7 million customers](https://www.bleepingcomputer.com/news/security/iris-ohyama-data-cloud-breach-exposes-info-of-77-million-customers/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
_No new items / feed unavailable this run._

### SecurityWeek
- [Over 3 Million People Hit by Frontline Education Data Breach](https://www.securityweek.com/3-million-people-hit-by-frontline-education-data-breach/)
- [Google DeepMind’s AI Agents Make 1024-Bit RSA Keys Cheaper to Attack](https://www.securityweek.com/google-deepminds-ai-agents-make-1024-bit-rsa-keys-cheaper-to-attack/)
- [Brava Security Emerges From Stealth With $15 Million in Funding](https://www.securityweek.com/brava-security-emerges-from-stealth-with-15-million-in-funding/)

### The Record
_No new items / feed unavailable this run._

### Infosecurity Magazine
- [Crédit Mutuel Arkéa Targeted in Reported $133m Heist](https://www.infosecurity-magazine.com/news/crdit-mutuel-arka-targeted/)
- [Anti-Money Laundering Watchdog FATF Targets Scam Compounds](https://www.infosecurity-magazine.com/news/aml-watchdog-fatf-scam-compounds/)

### CyberScoop
- [AI doesn’t have to go rogue to break the world](https://cyberscoop.com/ai-hacking-risks-loopholes-bruce-schneier-defcon-keynote-op-ed/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Monday, November 9th, 2026 https://isc.sans.edu/podcastdetail/10170, (Mon, Nov 9th)](https://isc.sans.edu/diary/rss/33500)
- [Scans for Sshole Vulnerability (CVE-2026-123158), (Sun, Nov 8th)](https://isc.sans.edu/diary/rss/33498)

### Securelist (Kaspersky)
_No new items / feed unavailable this run._

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
_No new items / feed unavailable this run._

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/
- https://api.phishstats.info/api/phishing?_sort=-id&_size=30 -> 502 Server Error: Bad Gateway for url: https://api.phishstats.info/api/phishing?_sort=-id&_size=30

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal