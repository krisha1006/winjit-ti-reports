# Winjit Daily TI Digest — 2026-11-05

_Auto-generated. Window: last ~24h. Fetched at 2026-11-05T10:34:14.150138+00:00Z_

**At a glance:** 1 new KEV · 78 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2024-27834 | Apple | Multiple Products | Apple Multiple Products Improper Authentication Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-121606 | 10.0 | 0.2% | A vulnerability has been found in Qihoo 360 D621-2, D603-2, D600-2, D619, D606-6 and D706 up to 6.4.9. Affected by this issue is the function verify_sign of the file fs2/bin/iscm of the component Firm |
| CVE-2026-121607 | 10.0 | 2.0% | A vulnerability was found in Qihoo 360 D603-2, D600-2, D606-6 and D706 up to 6.4.9. This affects the function testspeed_command of the file /fs2/bin/iscm. Performing a manipulation of the argument hos |
| CVE-2026-121609 | 10.0 | 0.5% | A vulnerability was identified in Qihoo 360 Whole Home Router M5 4.0.17.1566. This issue affects the function Home of the file /etc/init.d/mpt of the component Boot Script. The manipulation leads to h |
| CVE-2026-121615 | 10.0 | 0.8% | A vulnerability was determined in Linksys E5600 1.1.0.26. Affected is an unknown function of the file /cgi-bin/mesh_login.cgi of the component Login Handler. Executing a manipulation can lead to impro |
| CVE-2026-121932 | 10.0 | n/a | A vulnerability was detected in Linksys E5350 1.0.00.037. This affects the function system of the file /wizard/apply.cgi. Performing a manipulation of the argument ping_ip/traceroute_ip results in os  |
| CVE-2026-121933 | 10.0 | n/a | A flaw has been found in Linksys E5350 1.0.00.037. This impacts the function save_settings of the file /wizard/apply.cgi of the component Setup Wizard. Executing a manipulation of the argument wizard_ |
| CVE-2026-122013 | 10.0 | n/a | A vulnerability was detected in Comfast CF-WR632AX 2.6.0.1. Affected by this vulnerability is an unknown functionality of the file /usr/bin/webmgnt of the component Multipart Parser. Performing a mani |
| CVE-2026-122051 | 10.0 | n/a | A flaw has been found in Edimax BR-6208AC 1.32. Affected by this vulnerability is an unknown functionality of the file /goform/mp. Executing a manipulation can lead to command injection. The attack ma |
| CVE-2026-121597 | 9.9 | 0.6% | A weakness has been identified in TOTOLINK A950RG 4.1.2cu.5268_B20221104. This affects the function setAppEasyWizardConfig of the file /cgi-bin/cstecgi.cgi of the component Easy Setup Wizard Handler.  |
| CVE-2026-121599 | 9.9 | 0.5% | A vulnerability was detected in TOTOLINK A950RG 4.1.2cu.5268_B20221104. Affected is the function setWiFiMultipleConfig/delWiFiMultipleConfig of the file /cgi-bin/cstecgi.cgi of the component Multi-SSI |
| CVE-2026-121600 | 9.9 | 0.5% | A flaw has been found in TOTOLINK A950RG 4.1.2cu.5268_B20221104. Affected by this vulnerability is the function setMacFilterRules of the file /cgi-bin/cstecgi.cgi of the component MAC Filter Handler.  |
| CVE-2026-122303 | 9.9 | n/a | Kyverno from 1.17.0 before 1.19.2 contains an authorization bypass vulnerability that allows namespace tenants to overwrite resources in other namespaces via NamespacedMutatingPolicy mutate-existing t |
| CVE-2026-122304 | 9.9 | n/a | Kyverno from 1.17.0 before 1.19.2 contains an authorization bypass vulnerability that allows namespace admins to escape namespace confinement because the cleanup controller builds its context loader w |
| CVE-2026-122310 | 9.9 | n/a | Kyverno from 1.19.1 before 1.19.2 validates a Policy's context.apiCall urlPath after cleaning it but executes the raw path, whose fragment or query the Kubernetes client discards. A namespace-scoped u |
| CVE-2026-122311 | 9.9 | n/a | Kyverno from 1.16.0 before 1.19.2 fails to validate path segments in the resource argument of resource.get() and resource.post(), allowing namespaced CEL policies to escape their namespace. Tenants wh |
| CVE-2026-122313 | 9.9 | n/a | Kyverno from 1.17.0 before 1.19.2 contains a privilege escalation vulnerability that allows namespace-scoped tenants to modify resources in other namespaces through NamespacedMutatingPolicy targetMatc |
| CVE-2025-71457 | 9.8 | n/a | vtenext 25.02 before 25.02.1 contains an authentication bypass vulnerability that allows unauthenticated attackers to change any account password via hub/rpwd.php without token verification. Attackers |
| CVE-2026-82418 | 9.8 | n/a | IBM Watson Speech Services Cartridge 4.0.0 through 5.4.0 could allow a remote attacker to execute arbitrary code due to a use-after-free vulnerability. |
| CVE-2026-54384 | 9.8 | n/a | VitaFit cloud API before 2026-10-30 contained an authentication bypass vulnerability that allows remote attackers to obtain a full session for a victim's account by submitting a linked Google or Faceb |
| CVE-2026-122302 | 9.8 | n/a | Kyverno before 1.19.2 contains a privilege escalation vulnerability that allows namespace admins to create resources beyond their RBAC because generate-rule admission checks verify the controller's pe |
| CVE-2026-54378 | 9.6 | n/a | VitaFit cloud API before 2026-10-30 contained a broken access control vulnerability that allows any authenticated user to obtain temporary AWS credentials by calling the POST /front/user/s3/token/ end |
| CVE-2026-121930 | 9.1 | n/a | A weakness has been identified in Linksys WRT54GL 4.30.18. The affected element is the function system of the file apply.cgi of the component Ping Diagnostic. This manipulation of the argument ping_ip |
| CVE-2026-121931 | 9.1 | n/a | A security vulnerability has been detected in Linksys WRT54GL 4.30.18. The impacted element is the function system of the file apply.cgi of the component Traceroute Diagnostic Function. Such manipulat |
| CVE-2026-122321 | 9.1 | n/a | Kyverno 1.18.0 before 1.19.2 contains a signature verification bypass in verifyImages because cached verification results are keyed by the image reference string (such as a tag) rather than bound to t |
| CVE-2026-57853 | 8.8 | n/a | DataGerry before 3.3.0 contains a server-side template injection vulnerability that allows authenticated attackers with base.docapi.template.add permission to store arbitrary Jinja2 payloads in the te |
| CVE-2026-11376 | 8.8 | n/a | IBM MQ 9.2.0.0 through 9.2.0.44 LTS, 9.3.0.0 through 9.3.0.42 LTS, 9.4.0.0 through 9.4.0.26 LTS, 9.4.0.0 through 9.4.5.1 CD, and 10.0.0.0 through 10.0.0.5 LTS and CD could allow an authenticated attac |
| CVE-2026-122133 | 8.8 | n/a | Mistral Vibe before 2.25.5 on Windows contains an untrusted search path vulnerability that allows attackers to execute code by placing git.exe in a repository root. Attackers can lure users into openi |
| CVE-2026-122134 | 8.8 | n/a | Mistral Vibe before 2.25.7 contains a remote code execution vulnerability that allows attackers to run commands by configuring malicious Git clean or process filter drivers in a repository. When a use |
| CVE-2026-122135 | 8.8 | n/a | Mistral Vibe before 3.0.3 contains a remote code execution vulnerability that allows attackers to run commands by abusing repository-configured gpg.program during project context collection. A crafted |
| CVE-2026-13292 | 8.8 | n/a | IBM MQ 9.2.0.0 through 9.2.0.44 LTS, 9.3.0.0 through 9.3.0.42 LTS, 9.4.0.0 through 9.4.0.26 LTS, 9.4.0.0 through 9.4.5.1 CD, and 10.0.0.0 through 10.0.0.5 LTS and CD could allow an authenticated attac |
| CVE-2026-54372 | 8.8 | n/a | VitaFit Android application (com.vt.vitafit) before 2.8.1.0 contains an insecure TLS/SSL certificate validation vulnerability that allows network-based attackers to intercept and modify HTTPS traffic  |
| CVE-2026-122299 | 8.8 | n/a | Dulwich before 1.2.20 contains a commit object parsing vulnerability where the read path in _parse_commit resolves a duplicate tree header to the last occurrence instead of the first, diverging from c |
| CVE-2026-118193 | 8.8 | n/a | The GiveWP – Donation Plugin and Fundraising Platform plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 4.19.1 via the `donor_default_user_role` paramete |
| CVE-2026-11724 | 8.5 | n/a | IBM MQ 9.2.0.0 through 9.2.0.44 LTS, 9.3.0.0 through 9.3.0.42 LTS, 9.4.0.0 through 9.4.0.26 LTS, 9.4.0.0 through 9.4.5.1 CD, and 10.0.0.0 through 10.0.0.5 LTS and CD could allow an authenticated attac |
| CVE-2026-122308 | 8.5 | n/a | Kyverno before 1.19.2 contains an authorization bypass vulnerability in the Generation Handler that allows users with create/update permissions to trigger synchronized generate policies by spoofing in |
| CVE-2026-122316 | 8.5 | n/a | Kyverno from 1.17.0 before 1.19.2 contains a missing authorization vulnerability in the mutate-existing background processor that allows namespaced tenants to modify resources outside their namespace. |
| CVE-2026-54375 | 8.4 | n/a | VitaFit Android application (com.vt.vitafit) before 2.8.1.0 contains an insecure session management vulnerability that allows attackers to extract or intercept unencrypted m_session_id tokens stored i |
| CVE-2026-122130 | 8.2 | n/a | CESNET ipfixcol2 2.3.0 before 2.9.0 contains an integer overflow vulnerability in the Forwarder output plugin that allows unauthenticated IPFIX exporters to overflow a heap buffer by wrapping uint16_t |
| CVE-2026-54376 | 8.2 | n/a | VitaFit Android application (com.vt.vitafit) before 2.8.1.0 contains an insecure custom URI scheme vulnerability that allows a malicious application to intercept Fitbit login tokens by registering the |
| CVE-2026-93389 | 8.2 | n/a | The LiteSpeed Cache plugin for WordPress is vulnerable to unauthenticated disclosure of sensitive WooCommerce customer data in all versions up to, and including, 7.9.1 With Cache REST enabled (the shi |
| CVE-2025-71456 | 8.1 | n/a | vtenext before 25.02.2 contains an SQL injection vulnerability that allows authenticated low-privileged users to inject SQL by supplying a crafted fieldname parameter to modules/Fax/EditView.php. Atta |
| CVE-2026-122224 | 8.1 | n/a | WebVirtCloud through commit bb920b0 contains a missing authorization vulnerability that allows low-privileged authenticated users to reach MigrateViewSet and CreateInstanceViewSet because no permissio |
| CVE-2026-13271 | 8.1 | n/a | IBM MQ 9.2.0.0 through 9.2.0.44 LTS, 9.3.0.0 through 9.3.0.42 LTS, 9.4.0.0 through 9.4.0.26 LTS, 9.4.0.0 through 9.4.5.1 CD, and 10.0.0.0 through 10.0.0.5 LTS and CD Managed File Transfer could allow  |
| CVE-2026-116617 | 8.1 | n/a | The Motors – Car Dealership & Classified Listings Plugin plugin for WordPress is vulnerable to File Deletion in all versions up to, and including, 1.4.128 The vulnerability exists because `stm_save_us |
| CVE-2026-59267 | 7.8 | n/a | A crafted DXF document causes a heap buffer overflow in Draw in Apache OpenOffice 4.1.16 and earlier. This could cause a crash or otherwise a corruption of memory areas.
Users are recommended to upgra |
| CVE-2026-54382 | 7.7 | n/a | VitaFit cloud API before 2026-10-30 contained an improper access control vulnerability in its Cognito-issued AWS role that allows authenticated attackers to perform s3:PutObject operations across the  |
| CVE-2026-122305 | 7.7 | n/a | Kyverno before 1.19.2 contains a denial of service vulnerability in substituteVariablesIfAny that allows low-privileged users to hang the admission webhook via self-referential variable templates. Att |
| CVE-2026-122306 | 7.7 | n/a | Kyverno before 1.19.2 contains a denial of service vulnerability that allows namespaced policy authors to exhaust admission controller CPU by submitting pathological wildcard patterns. Attackers can c |
| CVE-2026-122307 | 7.7 | n/a | Kyverno before 1.19.2 contains a policy bypass vulnerability in the admissionpolicygenerator controller, which folds PolicyExceptions into generated ValidatingAdmissionPolicies while ignoring the --en |
| CVE-2026-122312 | 7.7 | n/a | Kyverno from 1.19.1 before 1.19.2 contains a namespace isolation bypass in APICall Fetch() in pkg/engine/apicall/apiCall.go because path.Clean treats '?' as a path character, letting the namespace reg |
| CVE-2026-122318 | 7.7 | n/a | Kyverno before 1.19.2 contains an authentication bypass in matchCertificateData that skips verifyImages subject and subjectRegExp checks when the signing certificate has no Subject Alternative Name. A |
| CVE-2026-122320 | 7.7 | n/a | Kyverno before 1.19.2 contains a missing authorization vulnerability that allows namespaced Policy authors to read resources in other namespaces by templating generate.clone or cloneList namespace val |
| CVE-2026-121617 | 7.5 | 0.5% | A security flaw has been discovered in Linksys E5600 1.1.0.26. Affected by this issue is the function init_multipart of the file /cgi-bin/upload_fw.cgi of the component Header Parser. The manipulation |
| CVE-2026-10859 | 7.5 | n/a | IBM MQ 9.2.0.0 through 9.2.0.44 LTS, 9.3.0.0 through 9.3.0.42 LTS, 9.4.0.0 through 9.4.0.26 LTS, 9.4.0.0 through 9.4.5.1 CD, and 10.0.0.0 through 10.0.0.5 LTS and CD could allow an authenticated attac |
| CVE-2026-122127 | 7.5 | n/a | CESNET ipfixcol2 2.7.1 before 2.9.0 contains a heap-based buffer overflow in Lz4Decoder.cpp that allows unauthenticated network peers to write past heap buffers. Attackers can declare a small ring buf |
| CVE-2026-12356 | 7.5 | n/a | IBM MQ 9.2.0.0 through 9.2.0.44 LTS, 9.3.0.0 through 9.3.0.42 LTS, 9.4.0.0 through 9.4.0.26 LTS, 9.4.0.0 through 9.4.5.1 CD, and 10.0.0.0 through 10.0.0.5 LTS and CD could allow an authenticated user  |
| CVE-2026-17493 | 7.5 | n/a | IBM Watson Speech Services Cartridge 4.0.0 through 5.4.0 could allow a remote attacker to cause a denial of service due to an out-of-bounds read. |
| CVE-2026-54374 | 7.5 | n/a | VitaFit Android application (com.vt.vitafit) before 2.8.1.0 contains a hardcoded credentials vulnerability that allows attackers to extract confidential third-party integration secrets by decompiling  |
| CVE-2026-54381 | 7.5 | n/a | VitaFit cloud API before 2026-10-30 contained a misconfigured cloud storage bucket vulnerability that allows unauthenticated attackers to list and download stored files without authentication. Attacke |
| CVE-2026-122314 | 7.5 | n/a | Kyverno before 1.19.2 contains an unchecked type assertion in its variable-substitution engine that allows users who can submit resources to crash the policy engine. Attackers can submit resources wit |
| CVE-2026-122315 | 7.5 | n/a | Kyverno before 1.19.2 contains an unchecked type assertion in buildStatementMap that allows unauthenticated attackers to crash the policy engine via crafted attestation statements. Attackers can push  |
| CVE-2026-122319 | 7.5 | n/a | Kyverno before 1.19.2 contains a denial-of-service vulnerability in the In and NotIn operators that allows attackers to crash the policy engine via an unchecked type assertion. Attackers can submit re |
| CVE-2026-122322 | 7.5 | n/a | Kyverno from 1.11.0 before 1.19.2 contains an unbounded decompression vulnerability in extractStatement that allows remote attackers to exhaust memory by supplying highly compressed attestation layers |
| CVE-2026-122323 | 7.5 | n/a | Kyverno from 1.11.0 before 1.19.2 contains an unbounded decompression vulnerability in FetchSignatureBlob that allows attackers to exhaust memory by supplying highly compressed notary signature layers |
| CVE-2026-122220 | 7.4 | n/a | WPO365 | LOGIN (wpo365-login) plugin before version 45.2 contains an authentication bypass by capture-replay vulnerability caused by a non-functional anti-replay check in Saml2_Service::check_message_ |
| CVE-2026-121608 | 7.3 | 1.3% | A vulnerability was determined in Qihoo 360 D603-2, D600-2 and D606-6 up to 6.3.2. This vulnerability affects the function on_push_message of the file /fs2/bin/iscm of the component Timezone Push Hand |
| CVE-2026-121610 | 7.3 | 0.3% | A security flaw has been discovered in funadmin 7.1.0. Impacted is the function Curd::selectList of the file /frontend/ajax/index of the component Frontend List Endpoint. The manipulation of the argum |
| CVE-2026-121926 | 7.3 | n/a | A vulnerability was detected in yezhihao jt808-server up to a07f68c466b560b97ef41edb8a4966469abdf83e. Affected is the function WebMvcConfig.addInterceptors of the component Web Management API. The man |
| CVE-2026-122009 | 7.3 | n/a | A flaw has been found in DataLinkDC Dinky up to 1.2.5. This vulnerability affects the function FlinkWebURITemplateProxyServlet.getNewTargetUri of the file dinky-admin/src/main/java/org/dinky/utils/Fli |
| CVE-2026-122019 | 7.3 | n/a | A vulnerability was identified in 6amTech 6valley 16.0. Impacted is the function existingAccountCheck of the file /api/v1/auth/existing-account-check of the component Social Login Flow. Such manipulat |
| CVE-2026-122038 | 7.3 | n/a | A vulnerability was identified in krupalshah EmployeeRecruitmentSystem up to 922ff6d208278282e7c8e36d70d9ae356adec9fe. Affected by this issue is the function mysql_query of the file source/reqformproc |
| CVE-2026-122047 | 7.3 | n/a | A security vulnerability has been detected in Campcodes Complete Advance Loan Management System 1.0. This affects the function move_uploaded_file of the file /loan/application/banner.php. Such manipul |
| CVE-2026-122048 | 7.3 | n/a | A vulnerability was identified in Campcodes Division Regional Athletic Meet Game Result Matrix System up to 2.1. This affects an unknown function of the file /dipam/check-user.php. Such manipulation o |
| CVE-2026-122050 | 7.3 | n/a | A vulnerability was found in Campcodes Complete Sales and Inventory System with Credit Management 1.0. This issue affects some unknown processing of the file /ahira/login.php. Performing a manipulatio |
| CVE-2026-122146 | 7.3 | n/a | A weakness has been identified in 101arrowz fflate up to 0.8.3. This issue affects the function unzipSync of the file esm/index.mjs. This manipulation causes memory corruption. It is possible to initi |
| CVE-2026-13284 | 7.1 | n/a | IBM MQ 9.2.0.0 through 9.2.0.44 LTS, 9.3.0.0 through 9.3.0.42 LTS, 9.4.0.0 through 9.4.0.26 LTS, 9.4.0.0 through 9.4.5.1 CD, and 10.0.0.0 through 10.0.0.5 LTS and CD is vulnerable to an XML external e |
| CVE-2026-13289 | 7.1 | n/a | IBM MQ 9.2.0.0 through 9.2.0.44 LTS, 9.3.0.0 through 9.3.0.42 LTS, 9.4.0.0 through 9.4.0.26 LTS, 9.4.0.0 through 9.4.5.1 CD, and 10.0.0.0 through 10.0.0.5 LTS and CD is vulnerable to an XML external e |
| CVE-2026-18142 | 7.1 | n/a | IBM MQ 9.2.0.0 through 9.2.0.44 LTS, 9.3.0.0 through 9.3.0.42 LTS, 9.4.0.0 through 9.4.0.26 LTS, 9.4.0.0 through 9.4.5.1 CD, and 10.0.0.0 through 10.0.0.5 LTS and CD could allow a remote authenticated |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-jg3r-6p98-c2mp | CVE-2026-107776 | low | The Dokan WordPress plugin before 5.3.3 does not reconcile the amount credited to a vendor's... |
| GHSA-wcgm-r4r4-7xqc | CVE-2026-117679 | medium | A cross-site scripting vulnerability exists in SHIRASAGI, which may allow an authenticated... |
| GHSA-vh3v-vj4j-59pc | CVE-2026-100109 | critical | The Security For WooCommerce WordPress plugin from 1.0.10 to 1.0.16 does not perform capability... |
| GHSA-r2gq-fqfh-5gqm | CVE-2026-123017 | medium | GodotSteam 4.17 through 4.23.2 trusts the peer value of 1 to mean that a player is the server. A... |
| GHSA-pf5w-w956-56pv | CVE-2026-118869 | high | An OS command injection vulnerability exists in SHIRASAGI, which may allow an authenticated... |
| GHSA-4frw-2vwq-957r | CVE-2026-109408 | high | vault-java-driver, a Java client for HashiCorp Vault, silently disables TLS certificate and... |
| GHSA-g3p9-q9ch-26gc | CVE-2026-112072 | medium | vault-java-driver, a Java client for HashiCorp Vault, parses Vault's JSON responses with a... |
| GHSA-m6c5-5946-f5rx | CVE-2026-123033 | high | Authentication bypass in the HA heartbeat origin check in middlewared in TrueNAS SCALE before 25... |
| GHSA-g9hg-38vq-jvh9 | CVE-2026-123025 | critical | An OS Command Injection vulnerability was discovered in the Google Cloud DNS validation module of... |
| GHSA-g54c-2vxv-4cp8 | CVE-2026-123029 | high | Wowza Streaming Engine before 4.12.2 processes XML external entities, which allows remote... |
| GHSA-3ccr-99wp-7ppp | CVE-2026-91049 | unknown | The EWWW Image Optimizer WordPress plugin before 8.9.1 does not properly sanitize and restrict a... |
| GHSA-vg34-wjj2-chfw | CVE-2026-90964 | unknown | The Essential Real Estate WordPress plugin before 5.3.5 does not restrict the recipient of one of... |
| GHSA-rvw5-rgwc-mcpp | CVE-2026-90965 | unknown | The Essential Real Estate WordPress plugin before 5.3.5 does not perform a publication-status or... |
| GHSA-x8r8-2rh2-5h4p | CVE-2026-90967 | unknown | The Essential Real Estate WordPress plugin before 5.3.5 does not verify ownership of an invoice... |
| GHSA-r9cj-c36h-r5w3 | CVE-2026-88814 | unknown | The YITH WooCommerce Gift Cards WordPress plugin before 4.38.1 does not lock or atomically update... |
| GHSA-qm9j-xm9j-x4x3 | CVE-2026-90966 | unknown | The Essential Real Estate WordPress plugin before 5.3.5 does not verify, in one of its AJAX... |
| GHSA-fwc3-9w8p-52wp | CVE-2026-87856 | unknown | The Subscriptions for WooCommerce WordPress plugin before 2.1.1 only enforces its membership... |
| GHSA-c425-pjx7-2qq4 | CVE-2026-86795 | unknown | The Community Events WordPress plugin before 1.6.0 does not have authorisation or nonce checks in... |
| GHSA-h9pq-8fc6-9cqw | CVE-2026-85351 | unknown | The FV Flowplayer Video Player WordPress plugin before 7.5.56.7212 does not validate a user... |
| GHSA-3jgh-hp3g-cxqq | CVE-2026-86442 | unknown | The WP Event Manager  WordPress plugin before 3.4.2 does not verify the ownership or the post... |
| GHSA-qrc4-9pwh-5w2x | CVE-2026-90963 | unknown | The Essential Real Estate WordPress plugin before 5.3.5 does not perform any authorization or... |
| GHSA-6pf6-j276-g8cc | CVE-2026-85570 | unknown | The Tutor LMS  WordPress plugin before 4.2.0 does not prevent the correct answers to quiz... |
| GHSA-8w8j-842q-xx4q | CVE-2026-85347 | unknown | The FV Flowplayer Video Player WordPress plugin before 7.5.56.7212 does not sanitize and escape a... |
| GHSA-j2j9-q63m-9wvj | CVE-2026-19256 | unknown | The All In One Login WordPress plugin before 2.5.0 does not adequately restrict the number of... |
| GHSA-4xwf-gr64-f25h | CVE-2026-85346 | unknown | The FV Flowplayer Video Player WordPress plugin before 7.5.56.7212 does not perform authorization... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Custom Bakehouse | Dark Project | US | 2026-11-05T06:21:31.072294+00:00 |
| Delta Dental of Missouri | N0n | US | 2026-11-05T04:52:28.695264+00:00 |
| The Container Store | N0n | US | 2026-11-05T04:51:57.488255+00:00 |
| Msn | medusalocker | US | 2026-11-04T22:27:24.873996+00:00 |
| baiapai | medusalocker |  | 2026-11-04T22:25:50.790256+00:00 |
| Vinitgloves | medusalocker | IN | 2026-11-04T22:25:19.459966+00:00 |
| Jatl | medusalocker |  | 2026-11-04T22:24:46.845711+00:00 |
| Geetees | medusalocker |  | 2026-11-04T22:24:15.472024+00:00 |
| Ruixiang Jidian | medusalocker |  | 2026-11-04T22:23:43.682060+00:00 |
| Kde | medusalocker |  | 2026-11-04T22:23:12.502234+00:00 |
| Jobmongers | medusalocker | GB | 2026-11-04T22:22:41.115597+00:00 |
| baeaqab | medusalocker |  | 2026-11-04T22:22:08.338014+00:00 |
| Ulaval | medusalocker | CA | 2026-11-04T22:21:35.811959+00:00 |
| On | medusalocker | CH | 2026-11-04T22:21:04.571660+00:00 |
| Hirschinjurylaw | medusalocker | US | 2026-11-04T22:20:33.635900+00:00 |
| BCH | medusalocker |  | 2026-11-04T22:20:02.505131+00:00 |
| Interativa Plasticos (Interplast) | medusalocker | BR | 2026-11-04T22:19:30.447149+00:00 |
| bataaab | medusalocker |  | 2026-11-04T22:18:26.974124+00:00 |
| bamawat | medusalocker |  | 2026-11-04T22:17:55.060144+00:00 |
| K... R... | SilentRansomGroup |  | 2026-11-04T22:01:53.026831+00:00 |

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
| 138.226.239.234 | 11 |
| 138.226.239.233 | 10 |
| 14.34.249.175 | 9 |
| 51.159.4.12 | 9 |
| 66.132.172.214 | 9 |
| 66.132.195.67 | 9 |
| 103.159.2.113 | 9 |
| 167.94.146.53 | 9 |
| 170.231.236.98 | 9 |
| 193.24.211.219 | 9 |
| 196.189.236.67 | 9 |
| 209.99.190.186 | 9 |
| 3.129.187.38 | 8 |
| 3.130.168.2 | 8 |
| 12.156.67.18 | 8 |
| 18.116.101.220 | 8 |
| 18.218.118.203 | 8 |
| 45.148.10.141 | 8 |
| 45.148.10.152 | 8 |
| 64.62.197.48 | 8 |

### OpenPhish (live phishing URLs)
- https://sharemyhtml.com/p/rmDI-OSKFM
- https://fkwz.lpicezo.cn/
- http://2z2z32z.pages.dev/
- https://atomic-en.uncody.site/
- https://s.teamivz.com/p/bjr-wvl/KWPVGTSV
- https://s4w.in/roblox-com-games-8304191830privateServerLinkCode=15920080078090842123854321699
- http://sp10ct10-pavvek-biz-lurevi.pages.dev/
- https://zagrosnova.com/docs/
- https://sp10ct11-kelzuni-biz-mavzaro.pages.dev/
- http://sp10ct11-lavzemi-biz-kavruvo.pages.dev/
- http://sp10ct11-vemzuni-biz-korvilo-ckv.pages.dev/
- http://pzxqn9i38dr-dskrplpw-7t0r8d-ds311a.pages.dev/
- https://sp10ct11-zulnaro-biz-kavmori.pages.dev/
- http://k96ajv-4u0a-gzavvn-cyqk44.pages.dev/
- http://marnita-gld-larqumi-p8t4hk36.pages.dev/
- http://mervani-kxt-qelmora-a8x3hq51.pages.dev/
- http://sp10ct11-vemlako-biz-nulrevo.pages.dev/
- https://mvk62-163sk-lpr47-163lp-0b1c3d-mvk62-163c.pages.dev/
- https://sp10ct11-dorvilo-biz-kavzaro.pages.dev/
- http://dhfgy05lkwg-vnxkppli-6uy75d-dhf66c.pages.dev/

### PhishStats (recent phishing/malicious URLs, scored)
_No data returned this run._

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| 8fa5d5b8ff264dcc0eb6b1d29b5520beeba1e81f | Malware C&C |
| dc7784a75bdb59bd6427e9c2a23384e2094dbba0 | PureRAT C&C |
| 07c4dd65867a3724a96f2525f6ebcf0d2e3dbbf6 | Vidar C&C |
| 69a2602395b7cf2a39cb87cd82a4ce6c5a65b590 | Malware C&C |
| 2d10340053833d2b9662dcde0e36b4fee06991b3 | OffLoader C&C |
| 4ac16d400d5a82f25683361c46f69fbebcbc746a | Vidar C&C |
| 6b16ed3bacf20a5cb798f5aeafddfdf98936ad33 | OffLoader C&C |
| 4006b8b2e5cc903cf34d104d4a9557c9cd72474a | PureRAT C&C |
| f40c3e5760bab5d2d8839c0e55a18f660fbbcd94 | PureLogsStealer C&C |
| c1079d2e32f2c06188ae5eca7e1d65735358b0b8 | doxbin.cy |
| 98cb8edce9e85d99286177ce41e08642663800bb | Malware C&C |
| 2bc2251b18372479069949ab4554d0309d34be18 | PureRAT C&C |
| 345306210bfbe41b06d2222a5a6025a355bd05fa | Vidar C&C |
| 5663d22f630385239855507aac3fbb3b9e775b56 | Vidar C&C |
| cd25fefedddbac11b8cba96ce39f6689968348e0 | Vidar C&C |
| c68ff15755ee7bc3663259b23f74ae0519b2b809 | PureLogsStealer C&C |
| 34caba1bef1d1006199db86c6e2d5bf1d67c884e | PureLogsStealer C&C |
| 277a06bc0dfdd0da5455bdb3d5b92f7cd5fc9520 | PureLogsStealer C&C |
| b04b85ac36b0501fad420e3bc7976c3d31409b4e | PureLogsStealer C&C |
| 70e5be14909fe413ceb33179b521e33253b23b25 | PureLogsStealer C&C |

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
- 1.14.192.95
- 1.159.54.33
- 1.170.61.163
- 1.20.101.33
- 1.20.191.150
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.234.27.159
- 1.234.80.94
- 1.235.183.146
- 1.238.106.229
- 1.247.245.61
- 1.250.67.114
- 1.250.67.190
- 1.27.251.252
- 1.38.64.7
- 1.55.44.10
- 1.80.241.27
- 1.92.114.88

### CINS Army (poorly-rated IPs)
- 1.0.235.78
- 1.12.229.231
- 1.15.14.29
- 1.193.59.243
- 1.20.151.114
- 1.214.98.143
- 1.24.16.126
- 1.24.16.130
- 1.24.16.140
- 1.24.16.147
- 1.24.16.156
- 1.24.16.168
- 1.24.16.195
- 1.24.16.197
- 1.24.16.20
- 1.24.16.21
- 1.24.16.23
- 1.24.16.53
- 1.24.16.70
- 1.24.16.73

## News (last ~36h, across outlets)
### The Hacker News
- [Apple to Start Scanning Publicly Shared iCloud Photos and Files for Harmful Content](https://thehackernews.com/2026/11/apple-to-start-scanning-publicly-shared.html)
- [CERT-In Flags AI-Driven Attacks as Backdoored ARTEX Exposes 62 Consoles to Root Access](https://thehackernews.com/2026/11/backdoored-docker-image-for-artex-ai.html)
- [Zyxel GS1900 Patch Fails to Block Zero-Day Exploit Allowing Root Command Execution](https://thehackernews.com/2026/11/zyxel-gs1900-patch-fails-to-block-zero.html)
- [Hackers Exploit Patched Apple Flaw to Deliver Info-Stealing Malware, CISA Says](https://thehackernews.com/2026/11/hackers-exploit-patched-apple-flaw-to.html)
- [OpenAI AI Pipeline Generates 948 Linux Root Escalation Exploits in 30-Hour Run](https://thehackernews.com/2026/11/openai-ai-pipeline-generates-948-linux.html)
- [Debian and Ubuntu APT Flaw Lets MitM Attackers Swap Verified Packages and Run Code as Root](https://thehackernews.com/2026/11/debian-and-ubuntu-apt-flaw-lets-mitm.html)
- [SonicWall Won't Patch EoL GMS Flaws That Could Expose Files, Alter Database Records](https://thehackernews.com/2026/11/sonicwall-wont-patch-eol-gms-flaws-that.html)
- [Researchers Uncover Prompt Adware Hidden in OpenAI Codex Jailbreak Toolkit](https://thehackernews.com/2026/11/researchers-uncover-prompt-adware.html)
- [APT29-Linked Hackers Hijack Web Analytics Script to Deliver iOS and Android Exploits](https://thehackernews.com/2026/11/apt29-linked-hackers-hijack-web.html)
- [Critical Rails Flaw Lets Attackers Write Server Files via Crafted ImageMagick Uploads](https://thehackernews.com/2026/11/critical-rails-flaw-lets-attackers.html)
- [Xen Hypervisor Flaws Let One Malicious VM Read and Write Any Other VM's Memory](https://thehackernews.com/2026/11/xen-hypervisor-flaws-let-one-malicious.html)
- [Radio With No Radar: Why Agent Runtime Security Fails Without the Layers Beneath It](https://thehackernews.com/2026/11/radio-with-no-radar-why-agent-runtime.html)
- [China-Aligned Hackers Hijack Sogou Input Method DNS Requests to Deploy DarkVigil Backdoor](https://thehackernews.com/2026/11/china-aligned-hackers-hijack-sogou.html)
- [Russian Police Arrest 3 Suspected VasyGrek Hackers, Dismantle Criminal Infrastructure](https://thehackernews.com/2026/11/russian-police-arrest-3-suspected.html)
- [Google Issues Patches for Critical Android Flaw That Could Allow RCE Without User Interaction](https://thehackernews.com/2026/11/google-patches-critical-android-flaw.html)

### BleepingComputer
- [GhostMap Android flaw lets malicious app trigger persistent boot loop](https://www.bleepingcomputer.com/news/security/ghostmap-android-flaw-lets-malicious-app-trigger-persistent-boot-loop/)
- [Vercel rolls out new protection against stolen session cookie attacks](https://www.bleepingcomputer.com/news/security/vercel-rolls-out-new-protection-against-stolen-session-cookie-attacks/)
- [Zyxel fixes zero-day exploited to hack nearly 1,000 network switches](https://www.bleepingcomputer.com/news/security/zyxel-fixes-zero-day-exploited-to-hack-nearly-1-000-network-switches/)
- [DreamHost confirms data breach exposed FTP logins and webmail sessions](https://www.bleepingcomputer.com/news/security/dreamhost-confirms-data-breach-exposed-ftp-logins-and-webmail-sessions/)
- [Cyberattack disrupts blood storage refrigeration systems in France](https://www.bleepingcomputer.com/news/security/cyberattack-disrupts-blood-storage-refrigeration-systems-in-france/)
- [NIKKE PC game launcher hacked to spread remote access, data-stealing malware](https://www.bleepingcomputer.com/news/security/nikke-pc-game-launcher-hacked-to-spread-remote-access-data-stealing-malware/)
- [mSecure password manager hack prompts password reset warnings](https://www.bleepingcomputer.com/news/security/msecure-password-manager-hack-prompts-password-reset-warnings/)
- [Google Calendar phishing campaign hijacks sessions, bypasses MFA](https://www.bleepingcomputer.com/news/security/google-calendar-phishing-campaign-hijacks-sessions-bypasses-mfa/)
- [SonicWall warns of unpatched flaws in end-of-life GMS software](https://www.bleepingcomputer.com/news/security/sonicwall-warns-of-unpatched-flaws-in-end-of-life-gms-software/)
- [US charges two Canadians accused of hacking US universities](https://www.bleepingcomputer.com/news/security/us-charges-two-canadians-accused-of-hacking-us-universities/)
- [CISA flags WordPress RCE flaw as actively exploited in attacks](https://www.bleepingcomputer.com/news/security/cisa-flags-wordpress-rce-flaw-as-actively-exploited-in-attacks/)
- [Hackers use n-day exploits in zero-click attacks on iOS, Android devices](https://www.bleepingcomputer.com/news/security/hackers-use-n-day-exploits-in-zero-click-attacks-on-ios-android-devices/)

### Krebs on Security
- [Want to Rent an Internet Address at the White House?](https://krebsonsecurity.com/2026/11/want-to-rent-an-internet-address-at-the-white-house/)

### Dark Reading
- [Critical Rails Bug Threatens to Derail Vulnerable Servers](https://www.darkreading.com/application-security/critical-rails-bug-derail-vulnerable-servers)
- [Google, Partners Disrupt 1.3 Million-Device-Strong XCPE Botnet](https://www.darkreading.com/endpoint-security/google-13-million-device-strong-xcpe-botnet)
- [Incidents Move Too Fast for Pen &amp; Paper](https://www.darkreading.com/cybersecurity-operations/incidents-move-fast-pen-paper)
- [Philippine Migrant Worker Data Likely Leaked in 69GB Government Breach](https://www.darkreading.com/cyberattacks-data-breaches/philippine-migrant-worker-data-69gb-government-breach)
- [Phishing-Resistant Isn't Enough; Yubico Takes Aim at Identity-Verification Gap](https://www.darkreading.com/identity-access-management-security/beyond-phishing-resistant-yubico-identity-verification-gap)

### SecurityWeek
- [OpenAI Finds GPT-6 Astra Quietly Holding Back on Internal Red-Teaming, Exploit Tasks](https://www.securityweek.com/openai-finds-gpt-6-astra-quietly-holding-back-on-internal-red-teaming-exploit-tasks/)
- [Sysdig Adds Runtime Security and Governance for AI Agents](https://www.securityweek.com/sysdig-adds-runtime-security-and-governance-for-ai-agents/)
- [Barracuda ESG Authentication Bypass Flaw Opens Path to Root](https://www.securityweek.com/barracuda-email-security-gateway-authentication-bypass-opens-path-to-root/)
- [Agentic Data Security Firm Sentra Raises $150 Million](https://www.securityweek.com/agentic-data-security-firm-sentra-raises-150-million/)
- [AI-Linked Breaches Mount as WorkOS, Northflank, Trigger.dev Disclose Hacks](https://www.securityweek.com/ai-linked-breaches-mount-as-workos-northflank-trigger-dev-disclose-hacks/)
- [Canadian Extradited to US Over Cryptomining Hacks on University Supercomputers](https://www.securityweek.com/canadian-extradited-to-us-over-cryptomining-hacks-on-university-supercomputers/)
- [Malicious cPGuard Updates Served in OpsShield Supply Chain Attack](https://www.securityweek.com/malicious-cpguard-updates-served-in-opsshield-supply-chain-attack/)
- [Chrome 157 Rolls Out With 213 Security Fixes, Seven Rated Critical](https://www.securityweek.com/chrome-157-rolls-out-with-213-security-fixes-seven-rated-critical/)
- [Rigged Coding Assignment, Abused AI Tool Opened Path to $6 Billion Binance Heist](https://www.securityweek.com/rigged-coding-assignment-abused-ai-tool-opened-path-to-6-billion-binance-heist/)
- [North Korea Launches Missiles Toward the Sea as Pyongyang Protests Against US Claims on Binance Hack](https://www.securityweek.com/north-korea-launches-missiles-toward-the-sea-as-pyongyang-protests-against-us-claims-on-binance-hack/)

### The Record
- [Chainalysis warns all users hit in cyber breach involving ‘agentic’ techniques](https://therecord.media/chainalysis-all-users-hit-by-agentic-cyberattack)
- [More Asian airlines announce data breaches after attack on Spanish IT provider Amadeus](https://therecord.media/asian-airlines-announce-data-breach-it-provider-incident)
- [Canadian extradited to US for allegedly hacking schools in at least four states](https://therecord.media/canadian-nationals-accused-us-education-hacks-cryptomining)
- [French bank confirms cyber heist, hackers suspected to have stolen an estimated $133 million](https://therecord.media/french-bank-confirms-cyber-heist)
- [Ukrainian news outlet Kyiv Independent hit by suspected Russian cyberattack](https://therecord.media/ukraine-kyiv-independent-cyberattack)

### Infosecurity Magazine
- [GhostMap Bug Leaves Android Phones Stuck in Reboot Loop](https://www.infosecurity-magazine.com/news/ghostmap-bug-android-phones-stuck/)
- [NATS Air Traffic Control Failure Cost UK Economy £33m](https://www.infosecurity-magazine.com/news/nats-air-traffic-control-fail-cost/)
- [China-Aligned Group Abuses Sogou Input Method to Deliver Malware](https://www.infosecurity-magazine.com/news/slippynunchucks-sogou-dns-hijacking/)
- [APT29 Watering Holes Target Unpatched iPhones and Android Devices](https://www.infosecurity-magazine.com/news/apt29-watering-holes-iphones/)
- [France Blood Service Cyber-Attack Sends Blood Storage Temperatures to 110°C](https://www.infosecurity-magazine.com/news/france-blood-service-cyberattack/)
- [3AM Ransomware Used Human-AI Hybrid Tactics in UK School Estate Compromise](https://www.infosecurity-magazine.com/news/3am-ransomware-hybrid-ai-uk-school/)
- [Police Seize 100+ Servers After Four-Year Investment Fraud Probe](https://www.infosecurity-magazine.com/news/police-100-servers-fouryear/)
- [Fake Interview of Software Engineer Led to Binance Mega-Heist](https://www.infosecurity-magazine.com/news/fake-interview-software-engineer/)

### CyberScoop
- [What Democratic control of Congress means for cybersecurity](https://cyberscoop.com/democrats-congress-cybersecurity-cisa-ai-priorities/)
- [Officials extradite Canadian man to US for alleged cryptomining spree](https://cyberscoop.com/canadian-extradited-cryptomining-universities/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [The Classics Return: Vulnerable E-Mail Scripts, (Wed, Nov 4th)](https://isc.sans.edu/diary/rss/33488)
- [ISC Stormcast For Wednesday, November 4th, 2026 https://isc.sans.edu/podcastdetail/10164, (Wed, Nov 4th)](https://isc.sans.edu/diary/rss/33486)

### Securelist (Kaspersky)
- [The SOC Files 5: Ghost in the pipeline, or a fileless SharePoint breach by Storm-2603](https://securelist.com/storm-2603-fileless-toolshell-attack/121467/)

### CrowdStrike Blog
- [CrowdStrike Introduces Agentic Adversary Emulation to Counter AI-Enabled Adversaries](https://www.crowdstrike.com/en-us/blog/crowdstrike-agentic-adversary-emulation-counters-ai-enabled-adversaries/)
- [CrowdStrike Extends the Agentic SOC to Detect and Stop Agent Insider Threats](https://www.crowdstrike.com/en-us/blog/crowdstrike-detects-and-stops-agent-insider-threats/)
- [CrowdStrike Brings Enterprise Browser Security to the Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-brings-enterprise-browser-security-to-falcon-platform/)
- [New Falcon Cloud Security Innovations Secure the Cloud AI Runs On](https://www.crowdstrike.com/en-us/blog/falcon-cloud-security-innovations-secure-cloud-ai-runs-on/)
- [CrowdStrike Advances AI Security and Safety from Endpoint to Cloud](https://www.crowdstrike.com/en-us/blog/crowdstrike-advances-ai-security-and-safety-falcon-guardian/)
- [Introducing AI Kill Switch: Taking Control When AI Agents Go Rogue](https://www.crowdstrike.com/en-us/blog/crowdstrike-introduces-ai-kill-switch/)
- [CrowdStrike Secures AI Agents Inside Claude Cowork](https://www.crowdstrike.com/en-us/blog/crowdstrike-secures-ai-agents-inside-claude-cowork/)
- [CrowdStrike to Acquire Dreadnode to Bring Automated AI Security Testing to the Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-to-acquire-dreadnode/)
- [CrowdStrike to Acquire Fiddler to Deliver Falcon Observe for AI Agent Observability](https://www.crowdstrike.com/en-us/blog/crowdstrike-to-acquire-fiddler/)
- [What Makes a Good Security Agent? 5 Lessons from the AgentWorks Hackathon](https://www.crowdstrike.com/en-us/blog/five-lessons-from-agentworks-hackathon/)

### FortiGuard Threat Signal
- [OT Refrigeration Control Systems Attack](https://fortiguard.fortinet.com/threat-signal-report/6553)
- [Linux Kernel Remote Code Execution](https://fortiguard.fortinet.com/threat-signal-report/6564)
- [Ivanti Connect Secure Zero-Day Exploitation](https://fortiguard.fortinet.com/threat-signal-report/6563)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/
- https://api.phishstats.info/api/phishing?_sort=-id&_size=30 -> 502 Server Error: Bad Gateway for url: https://api.phishstats.info/api/phishing?_sort=-id&_size=30

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal