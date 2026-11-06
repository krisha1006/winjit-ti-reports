# Winjit Daily TI Digest — 2026-11-06

_Auto-generated. Window: last ~24h. Fetched at 2026-11-06T10:37:10.964309+00:00Z_

**At a glance:** 0 new KEV · 44 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-122303 | 9.9 | 0.3% | Kyverno from 1.17.0 before 1.19.2 contains an authorization bypass vulnerability that allows namespace tenants to overwrite resources in other namespaces via NamespacedMutatingPolicy mutate-existing t |
| CVE-2026-122304 | 9.9 | 0.4% | Kyverno from 1.17.0 before 1.19.2 contains an authorization bypass vulnerability that allows namespace admins to escape namespace confinement because the cleanup controller builds its context loader w |
| CVE-2026-122310 | 9.9 | 0.4% | Kyverno from 1.19.1 before 1.19.2 validates a Policy's context.apiCall urlPath after cleaning it but executes the raw path, whose fragment or query the Kubernetes client discards. A namespace-scoped u |
| CVE-2026-122311 | 9.9 | 0.4% | Kyverno from 1.16.0 before 1.19.2 fails to validate path segments in the resource argument of resource.get() and resource.post(), allowing namespaced CEL policies to escape their namespace. Tenants wh |
| CVE-2026-122313 | 9.9 | 0.3% | Kyverno from 1.17.0 before 1.19.2 contains a privilege escalation vulnerability that allows namespace-scoped tenants to modify resources in other namespaces through NamespacedMutatingPolicy targetMatc |
| CVE-2026-122302 | 9.8 | 0.3% | Kyverno before 1.19.2 contains a privilege escalation vulnerability that allows namespace admins to create resources beyond their RBAC because generate-rule admission checks verify the controller's pe |
| CVE-2026-119757 | 9.8 | n/a | BTCPay Server before 2.4.2, including 2.4.2 release candidates, contains an information disclosure vulnerability that allows unauthenticated remote attackers to retrieve .macaroon credential files for |
| CVE-2026-122321 | 9.1 | 0.2% | Kyverno 1.18.0 before 1.19.2 contains a signature verification bypass in verifyImages because cached verification results are keyed by the image reference string (such as a tag) rather than bound to t |
| CVE-2026-97175 | 8.8 | n/a | A flaw was found in the idp-auto-link authenticator of the keycloak-services component, which handles user identity federation. The issue occurs when Keycloak automatically links an incoming identity  |
| CVE-2026-123208 | 8.8 | n/a | noname Electron desktop build v1.11.2 through v1.11.6.1 contains an unauthenticated local file server with wildcard CORS that allows malicious websites to read, overwrite, or delete installation files |
| CVE-2026-122308 | 8.5 | 0.2% | Kyverno before 1.19.2 contains an authorization bypass vulnerability in the Generation Handler that allows users with create/update permissions to trigger synchronized generate policies by spoofing in |
| CVE-2026-122316 | 8.5 | 0.2% | Kyverno from 1.17.0 before 1.19.2 contains a missing authorization vulnerability in the mutate-existing background processor that allows namespaced tenants to modify resources outside their namespace. |
| CVE-2026-112208 | 8.1 | n/a | A flaw was found in the Organization identity-first login flow of the Keycloak authentication server. Keycloak is an open-source identity and access management solution used to secure modern applicati |
| CVE-2026-92857 | 8.1 | n/a | Keycloak provides a Dynamic Client Registration feature that allows users with specific tokens to register their own applications. A flaw in how Keycloak validates these registration requests allows a |
| CVE-2026-123196 | 8.1 | n/a | Authorizer before 2.4.2 contains a password reset poisoning vulnerability that allows unauthenticated attackers to control emailed link hosts by supplying x-authorizer-url gRPC metadata. Attackers can |
| CVE-2026-96453 | 8.0 | n/a | A flaw was found in the Keycloak Admin CLI kcadm tool, which is used by administrators to manage Keycloak servers from the command line. When a custom truststore is provided to verify the server ident |
| CVE-2026-123271 | 8.0 | n/a | ChatCLI before v1.215.2 contains an improper validation vulnerability in the MCP OAuth login flow that uses server-supplied Protected Resource Metadata as the resource indicator without checking it ma |
| CVE-2026-122328 | 7.8 | n/a | SDL_mixer 3.1.2 through 3.2.4 contains a stack-based buffer overflow vulnerability in FetchXLaw() of src/decoder_wav.c when decoding A-law or mu-law WAV files. Attackers can supply a crafted WAV file  |
| CVE-2026-122329 | 7.8 | n/a | SDL_mixer 3.1.2 through 3.2.4 contains a stack-based buffer overflow in FetchXLaw() in src/decoder_aiff.c due to miscalculated output offsets when expanding A-law or mu-law samples. Attackers can supp |
| CVE-2026-120859 | 7.8 | n/a | PyMoDAQ before 4.4.13, and pymodaq_data, pymodaq_gui, and pymodaq_utils before 5.1.15, 5.2.x before 5.2.14, and 5.3.x before 5.3.10, contain deserialization of untrusted data and eval injection vulner |
| CVE-2026-122305 | 7.7 | 0.3% | Kyverno before 1.19.2 contains a denial of service vulnerability in substituteVariablesIfAny that allows low-privileged users to hang the admission webhook via self-referential variable templates. Att |
| CVE-2026-122306 | 7.7 | 0.3% | Kyverno before 1.19.2 contains a denial of service vulnerability that allows namespaced policy authors to exhaust admission controller CPU by submitting pathological wildcard patterns. Attackers can c |
| CVE-2026-122307 | 7.7 | 0.2% | Kyverno before 1.19.2 contains a policy bypass vulnerability in the admissionpolicygenerator controller, which folds PolicyExceptions into generated ValidatingAdmissionPolicies while ignoring the --en |
| CVE-2026-122312 | 7.7 | 0.3% | Kyverno from 1.19.1 before 1.19.2 contains a namespace isolation bypass in APICall Fetch() in pkg/engine/apicall/apiCall.go because path.Clean treats '?' as a path character, letting the namespace reg |
| CVE-2026-122318 | 7.7 | 0.2% | Kyverno before 1.19.2 contains an authentication bypass in matchCertificateData that skips verifyImages subject and subjectRegExp checks when the signing certificate has no Subject Alternative Name. A |
| CVE-2026-122320 | 7.7 | 0.2% | Kyverno before 1.19.2 contains a missing authorization vulnerability that allows namespaced Policy authors to read resources in other namespaces by templating generate.clone or cloneList namespace val |
| CVE-2026-122314 | 7.5 | 0.3% | Kyverno before 1.19.2 contains an unchecked type assertion in its variable-substitution engine that allows users who can submit resources to crash the policy engine. Attackers can submit resources wit |
| CVE-2026-122315 | 7.5 | 0.4% | Kyverno before 1.19.2 contains an unchecked type assertion in buildStatementMap that allows unauthenticated attackers to crash the policy engine via crafted attestation statements. Attackers can push  |
| CVE-2026-122319 | 7.5 | 0.3% | Kyverno before 1.19.2 contains a denial-of-service vulnerability in the In and NotIn operators that allows attackers to crash the policy engine via an unchecked type assertion. Attackers can submit re |
| CVE-2026-122322 | 7.5 | 0.4% | Kyverno from 1.11.0 before 1.19.2 contains an unbounded decompression vulnerability in extractStatement that allows remote attackers to exhaust memory by supplying highly compressed attestation layers |
| CVE-2026-122323 | 7.5 | 0.3% | Kyverno from 1.11.0 before 1.19.2 contains an unbounded decompression vulnerability in FetchSignatureBlob that allows attackers to exhaust memory by supplying highly compressed notary signature layers |
| CVE-2026-123095 | 7.5 | n/a | mpv 0.29.0 before 0.42.0 contains a playlist injection vulnerability in the bundled ytdl_hook script that allows remote attackers to add unchecked entries by embedding newlines in playlist URLs. Attac |
| CVE-2026-103112 | 7.5 | n/a | A flaw was found in the authentication session handling of the keycloak-services component in Keycloak. The issue occurs because the system fails to verify if an authenticator is valid for the current |
| CVE-2026-107602 | 7.5 | n/a | A flaw was found in the SAML 1.1 XML parsing logic of Keycloak, an open-source identity and access management solution. The issue occurs when the parser encounters unexpected elements within a securit |
| CVE-2026-110931 | 7.5 | n/a | A flaw was found in the SAML 1.1 assertion parser of Keycloak, a tool used for identity and access management. The issue occurs when the parser handles a specific element called AuthorityBinding withi |
| CVE-2026-121995 | 7.5 | n/a | A stack buffer overflow in the GDB client's tracepoint upload handler allows an attacker-controlled debug stub to corrupt stack memory automatically during connection setup. The overflow results from  |
| CVE-2026-123200 | 7.5 | n/a | VRPN through 07.36 contains an out-of-bounds stack write vulnerability in vrpn_Endpoint::handle_sender_message() and handle_type_message() that allows unauthenticated remote peers to write outside a s |
| CVE-2026-123202 | 7.5 | n/a | libnxml before 0.18.6 contains a stack-based buffer overflow vulnerability in src/nxml_parser.c that allows remote attackers to write past a 1024-byte stack buffer via long XML names. Attackers can su |
| CVE-2025-71458 | 7.5 | n/a | FTS3 Web Monitoring (fts-monitoring) versions 3.12.0 through 3.13.2 and 3.14.0 contain an unauthenticated sql injection vulnerability in the /linkinfo endpoint handled by get_linkinfo. Remote attacker |
| CVE-2026-92855 | 7.4 | n/a | A flaw was found in the SAML identity broker component of Keycloak, which is used to delegate authentication to external identity providers. The issue occurs because the broker fails to verify that a  |
| CVE-2026-110291 | 7.2 | n/a | The Graphina – Charts and Graphs For Elementor plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'iq_tree_chart_node_font_family (and any text control serialized into chart_dat |
| CVE-2026-110776 | 7.2 | n/a | The MDTF – Meta Data and Taxonomies Filter plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'vars' parameter in all versions up to, and including, 1.4.1 due to insufficient in |
| CVE-2026-87964 | 7.2 | n/a | The Product Feed Manager for WooCommerce – CTX Feed – Support 220+ Shopping, AI & Social Channels plugin for WordPress is vulnerable to PHP Code Injection in all versions up to, and including, 8.0.26. |
| CVE-2026-97847 | 7.1 | n/a | A flaw was found in the protocol mapper and identity resolution components of Keycloak. The issue occurs when a client manager uses hardcoded-claim mappers to override identity claims in sessionless s |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-6q7q-x7h2-hrfr | CVE-2026-120671 | medium | The UsersWP – Front-end login form, User Registration, User Profile & Members Directory plugin... |
| GHSA-mw63-5fwq-j4r5 | CVE-2026-19877 | high | INFINITT ULite 5.0.2.1_BN48_20260528 and earlier protects image-share links with a low-entropy... |
| GHSA-xxf7-hwxj-cv76 | CVE-2026-19876 | medium | A reflected cross-site scripting (XSS) vulnerability in the login/SSO error page of INFINITT... |
| GHSA-3h33-w3fj-rp34 | CVE-2026-121794 | medium | The Travelly – Tour & Travel Booking Manager for WooCommerce plugin for WordPress is vulnerable... |
| GHSA-fjqr-7p2w-j9wx | CVE-2026-123660 | medium | In Vulnerability-Lookup 5.5.1 up to but not including 6.4.1, a signed-in user could make the... |
| GHSA-5v63-48m3-rm32 | CVE-2026-122222 | medium | The Permalink Manager Lite plugin for WordPress is vulnerable to Stored Cross-Site Scripting via... |
| GHSA-h5w5-gj85-jwc6 | CVE-2026-110291 | high | The Graphina – Charts and Graphs For Elementor plugin for WordPress is vulnerable to Stored Cross... |
| GHSA-p54m-c67r-w58j | CVE-2026-118189 | medium | The Posts Table with Search & Sort plugin for WordPress is vulnerable to Stored Cross-Site... |
| GHSA-3cg9-rmv8-63rq | CVE-2026-103682 | low | Invocation of the Jolokia special agent with the login password in the command line in Checkmk... |
| GHSA-6vww-3h55-pc3j | CVE-2026-103674 | low | Invocation of the NetApp ONTAP special agent with the login password in the command line in... |
| GHSA-jc8j-qq6m-2r53 | CVE-2026-108018 | medium | The BigFix MCM admin portal is directly accessible from the internet without VPN or network... |
| GHSA-26cf-5m8c-2hhh | CVE-2026-65022 | medium | The MDM App Catalog / App Store preview does not properly sanitize or encode user-supplied HTML... |
| GHSA-r545-v5rq-j469 | CVE-2026-88799 | high | The MDJM Event Management and Mobile Events Manager WordPress plugins through 1.7.8.7 do not... |
| GHSA-whrj-2wq8-j622 | CVE-2026-88800 | critical | The MDJM Event Management and Mobile Events Manager WordPress plugins through 1.7.8.7 act on a... |
| GHSA-458f-8h9v-25hw | CVE-2026-88801 | high | The MDJM Event Management and Mobile Events Manager WordPress plugins through 1.7.8.7 do not... |
| GHSA-f4c2-m2fq-wp7w | CVE-2026-121006 | unknown | HTTP::Body versions before 1.24_02 for Perl parse the trailer in quadratic time.

Everything... |
| GHSA-fq8p-wwgm-f3qv | CVE-2026-39744 | high | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-g7w9-6f5v-35q7 | CVE-2026-119516 | critical | Deserialization of Untrusted Data vulnerability in Mamunur Rashid Radius Booking — Booking... |
| GHSA-7mfr-2gjx-xqcx | CVE-2026-120844 | critical | Incorrect Privilege Assignment vulnerability in miniOrange OAuth Single Sign On – SSO (OAuth... |
| GHSA-9jq5-vqj9-9f7c | CVE-2026-121633 | medium | The Order Tracking WordPress plugin before 3.6.0 does not verify that a PayPal payment... |
| GHSA-qm8v-r38g-4hjq | CVE-2026-121636 | medium | The Quick Event Manager WordPress plugin before 9.19 does not verify the authenticity of PayPal... |
| GHSA-g6mh-6qc4-w2p6 | CVE-2026-119499 | high | Insertion of Sensitive Information Into Sent Data vulnerability in BAKKBONE Australia... |
| GHSA-w2x7-pv4h-9c8f | CVE-2026-119488 | high | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-cr8v-hqcv-xjhf | CVE-2026-119472 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-mhrf-qjwq-4j74 | CVE-2026-118423 | critical | The WP Libre Form WordPress plugin 1.5.0.1 does not validate the type of files uploaded through... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Max Fashion | N0n | AE | 2026-11-06T01:24:03.243618+00:00 |
| Hallmark Cards, Inc. | N0n | US | 2026-11-06T01:23:31.053366+00:00 |
| Scry Analytics | N0n | US | 2026-11-06T01:22:59.334278+00:00 |
| Smith, Gambrell & Russell, LLP | SilentRansomGroup | US | 2026-11-05T22:35:25.898328+00:00 |
| W... R... | SilentRansomGroup |  | 2026-11-05T22:35:05.847835+00:00 |
| Company #137 | N0n | CA | 2026-11-05T17:54:23.076846+00:00 |
| Company #136 | N0n | DK | 2026-11-05T17:53:54.647350+00:00 |
| Company #135 | N0n | ID | 2026-11-05T17:53:24.317409+00:00 |
| Company #134 | N0n | US | 2026-11-05T17:52:56.284326+00:00 |
| Company #133 | N0n | US | 2026-11-05T17:52:27.636454+00:00 |
| ZipAI | Vexy Ransomware | VN | 2026-11-05T23:27:37.826356+00:00 |
| Omni Hotels & Resorts | Redact | US | 2026-11-05T16:24:27.883719+00:00 |
| Sistel | Aoqin | BR | 2026-11-05T11:20:37.780181+00:00 |
| ne*****h.com | everstake |  | 2026-11-05T09:09:10.819816+00:00 |
| Disclosed | PixelLeaks |  | 2026-11-05T07:59:30.753699+00:00 |
| Custom Bakehouse | Dark Project | US | 2026-11-05T06:21:31.072294+00:00 |
| Delta Dental of Missouri | N0n | US | 2026-11-05T04:52:28.695264+00:00 |
| The Container Store | N0n | US | 2026-11-05T04:51:57.488255+00:00 |
| Insurance Audit Services | qilin | US | 2026-11-05T20:46:53.207943+00:00 |
| Westboro Partners | akira |  | 2026-11-05T15:20:30.799838+00:00 |

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
| 18.218.118.203 | 10 |
| 167.94.146.53 | 10 |
| 3.129.187.38 | 9 |
| 18.116.101.220 | 9 |
| 51.159.4.12 | 9 |
| 77.90.185.20 | 9 |
| 152.32.236.102 | 9 |
| 167.94.146.56 | 9 |
| 167.94.146.62 | 9 |
| 193.47.62.111 | 9 |
| 199.165.159.129 | 9 |
| 220.80.223.144 | 9 |
| 2.57.121.25 | 8 |
| 2.57.121.112 | 8 |
| 3.130.168.2 | 8 |
| 3.131.220.121 | 8 |
| 12.156.67.18 | 8 |
| 64.62.197.32 | 8 |

### OpenPhish (live phishing URLs)
- https://smcparral.com/Xplrs/?gate=031
- https://2h.ae/eJceI
- https://ios.app-lmaxex.top/
- https://e3x4x3w.pages.dev/
- https://394834binance.com/icloud/signin?client_id=5d914e33-bf66-4f0e-b
- https://icloud-appleinc.com/verify.php
- https://icloud-appleinc.com/Thayna
- http://pmh-ledger.pages.dev/v/mama
- http://pmh-ledger.pages.dev/v/may-may
- http://pmh-ledger.pages.dev/v/papa
- http://pmh-ledger.pages.dev/v/kyi-kyi
- http://pmh-ledger.pages.dev/v/sai-kham
- http://zerobit497-zkku.blogspot.com/
- https://help-docs-metamask.gitbook.io/us
- http://help-docs-metamask.gitbook.io/
- https://shared-documents-access.shared-object-038572.workers.dev/
- http://web-trezor-io-start-trezor-suite-app-cdn.typedream.app/
- https://370941383545690465507436650778.roomcaronmoons.sbs/
- http://www.telstramail-kyc-trial.weebly.com/
- https://higbkr.vercel.app/m0c8mn865q9kmkq9/oewxlj34p722d2cr/kr2vd4700wtzunuk/sroh34oautzjs3gl/danor2@8680dc57d9c3e96f6e7ff97bd8d8fe0bc897.org

### PhishStats (recent phishing/malicious URLs, scored)
_No data returned this run._

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| 043d265d8ee6e5c1c8954108716125c638f33752 | Vidar C&C |
| 063a72d2da624ba373a1afe5323a674af705bd02 | RevStealer C&C |
| e3d64b032db0b875f594b12eb9ad7a624e768383 | Vidar C&C |
| 788de1386a4226d0993c1434a2d820bc1259b88e | PureLogsStealer C&C |
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
- 1.161.133.214
- 1.170.61.163
- 1.172.90.41
- 1.175.131.108
- 1.179.151.165
- 1.20.101.33
- 1.203.149.250
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.220.198.126
- 1.222.42.237
- 1.234.27.159
- 1.234.80.94
- 1.235.183.146
- 1.238.106.229
- 1.247.245.61
- 1.250.67.114

### CINS Army (poorly-rated IPs)
- 1.0.235.78
- 1.12.229.231
- 1.180.184.182
- 1.193.63.198
- 1.20.151.114
- 1.223.11.69
- 1.24.16.103
- 1.24.16.104
- 1.24.16.105
- 1.24.16.108
- 1.24.16.11
- 1.24.16.125
- 1.24.16.129
- 1.24.16.133
- 1.24.16.147
- 1.24.16.149
- 1.24.16.150
- 1.24.16.163
- 1.24.16.165
- 1.24.16.166

## News (last ~36h, across outlets)
### The Hacker News
- [Chainalysis Breach Exposes All Users' Credentials, Forces Shutdown of Key Services](https://thehackernews.com/2026/11/chainalysis-breach-exposes-all-users.html)
- [Hackers Hide Linux Backdoor in Control Web Panel Server to Execute Commands Without Logs](https://thehackernews.com/2026/11/hackers-hide-linux-backdoor-in-control.html)
- [Experts Demonstrate Barracuda Email Security Gateway Chain Enabling Root Access Without Login](https://thehackernews.com/2026/11/experts-demonstrate-barracuda-email.html)
- [OpenSSH Issues Emergency Fix for Flaw Letting Long Passwords Bypass SSH Auth on Alpine Linux](https://thehackernews.com/2026/11/openssh-issues-emergency-fix-for-flaw.html)
- [Researchers Bypass ChatGPT Lockdown Mode to Exfiltrate Chats Without User Interaction](https://thehackernews.com/2026/11/researchers-bypass-chatgpt-lockdown.html)
- [ThreatsDay: Apache OFBiz RCE, DreamHost Breach, DeFi Site Hijacks + 17 More Stories](https://thehackernews.com/2026/11/threatsday-apache-ofbiz-rce-dreamhost.html)
- [Is Your Exposure Management Platform Leaving You Exposed? Five Tests to Find Out](https://thehackernews.com/2026/11/is-your-exposure-management-platform.html)
- [OpenAI AI Pipeline Generates 948 Linux Root Escalation Exploits in 30-Hour Run](https://thehackernews.com/2026/11/openai-ai-pipeline-generates-948-linux.html)
- [5 Active Cyber Threats That Put US Enterprises at Risk in October 2026](https://thehackernews.com/2026/11/5-active-cyber-threats-that-put-us.html)
- [Apple to Start Scanning Publicly Shared iCloud Photos and Files for Harmful Content](https://thehackernews.com/2026/11/apple-to-start-scanning-publicly-shared.html)
- [CERT-In Flags AI-Driven Attacks as Backdoored ARTEX Exposes 62 Consoles to Root Access](https://thehackernews.com/2026/11/backdoored-docker-image-for-artex-ai.html)
- [Zyxel GS1900 Patch Fails to Block Zero-Day Exploit Allowing Root Command Execution](https://thehackernews.com/2026/11/zyxel-gs1900-patch-fails-to-block-zero.html)
- [Hackers Exploit Patched Apple Flaw to Deliver Info-Stealing Malware, CISA Says](https://thehackernews.com/2026/11/hackers-exploit-patched-apple-flaw-to.html)

### BleepingComputer
- [MetaMask says recent attack didn't affect wallet infrastructure](https://www.bleepingcomputer.com/news/security/metamask-says-recent-attack-didnt-affect-wallet-infrastructure/)
- [FBI, CISA warn of cyberattacks targeting refrigeration systems](https://www.bleepingcomputer.com/news/security/fbi-cisa-warn-of-cyberattacks-targeting-refrigeration-systems/)
- [Fake OpenAI, SpaceX events used to steal Microsoft, Google accounts](https://www.bleepingcomputer.com/news/security/fake-openai-spacex-events-used-to-steal-microsoft-google-accounts/)
- [Nearly 1.5 million exposed secrets targeted in new revocation program](https://www.bleepingcomputer.com/news/security/truffle-security-launches-program-to-revoke-14-million-live-secrets/)
- [OpenAI’s GPT-6 Astra silently obstructed safety research tasks](https://www.bleepingcomputer.com/news/security/openais-gpt-6-astra-silently-obstructed-safety-research-tasks/)
- [OpenSSH flaw lets attackers log into password-disabled Linux accounts](https://www.bleepingcomputer.com/news/security/openssh-flaw-lets-attackers-log-into-password-disabled-linux-accounts/)
- [Hackers backdoor Linux servers using trojanized CWP web server](https://www.bleepingcomputer.com/news/security/hackers-backdoor-linux-servers-using-trojanized-cwp-web-server/)
- [DigiCert data breach exposes customer information, identity documents](https://www.bleepingcomputer.com/news/security/digicert-data-breach-exposes-customer-information-identity-documents/)
- [Closing the Identity Gap at the Service Desk](https://www.bleepingcomputer.com/news/security/closing-the-identity-gap-at-the-service-desk/)
- [GhostMap Android flaw lets malicious app trigger persistent boot loop](https://www.bleepingcomputer.com/news/security/ghostmap-android-flaw-lets-malicious-app-trigger-persistent-boot-loop/)

### Krebs on Security
- [Want to Rent an Internet Address at the White House?](https://krebsonsecurity.com/2026/11/want-to-rent-an-internet-address-at-the-white-house/)

### Dark Reading
- [UK Warns Its Critical Infrastructure Faces Grave Risk](https://www.darkreading.com/cybersecurity-operations/uk-warns-critical-infrastructure-grave-risk)
- [US Government Email Systems Open to Abuse Thanks to Typos](https://www.darkreading.com/cybersecurity-operations/us-government-email-systems-abuse-typos)
- [What We Missed: Knicks Phishing Test Goes Out of Bounds](https://www.darkreading.com/cyber-risk/what-we-missed-knicks-phishing-test-out-of-bounds)
- [APT29's Watering Holes Target Thousands of Mobile Users](https://www.darkreading.com/mobile-security/apt29-watering-holes-target-mobile-users)
- [SecurityDataPipeline.com Launches as a New Educational Resource for the AI Era](https://www.darkreading.com/cybersecurity-operations/securitydatapipeline-com-launches-as-a-new-educational-resource-for-the-ai-era)

### SecurityWeek
- [OpenAI Model Wrote Its Own Network Code to Get Around Sandbox Restrictions](https://www.securityweek.com/openai-model-wrote-its-own-network-code-to-get-around-sandbox-restrictions/)
- [3 Charged in Scheme to Use AI to Impersonate CEOs and Attorneys to Steal $129 Million](https://www.securityweek.com/3-charged-in-scheme-to-use-ai-to-impersonate-ceos-and-attorneys-to-steal-129-million/)
- [AI Agents Got Root on Linux via 948 Kernel Flaws in OpenAI Research](https://www.securityweek.com/ai-agents-got-root-on-linux-via-948-kernel-flaws-in-openai-research/)
- [Bank Phishing Sites Show Fake ‘Suspended’ Pages to Evade Takedowns](https://www.securityweek.com/bank-phishing-sites-show-fake-suspended-pages-to-evade-takedowns/)
- [Cyberattack Hits French Blood Bank Site but No Blood Products Are Compromised](https://www.securityweek.com/cyberattack-hits-french-blood-bank-site-but-no-blood-products-are-compromised/)
- [Cisco, WatchGuard Release Patches; SonicWall Won’t Fix GMS Flaws](https://www.securityweek.com/cisco-watchguard-release-patches-sonicwall-wont-fix-gms-flaws/)
- [The Agent Smith Dilemma: Governing Agentic Identities](https://www.securityweek.com/the-agent-smith-dilemma-governing-agentic-identities/)
- [CISO Conversations: Ryan Davis – The Unknown Is Where Security Meets Reality](https://www.securityweek.com/ciso-conversations-ryan-davis-the-unknown-is-where-security-meets-reality/)
- [Zyxel Switch Hacks Blamed on Patched Flaw Actually Exploited a Zero-Day](https://www.securityweek.com/zyxel-switch-hacks-blamed-on-patched-flaw-actually-exploited-a-zero-day/)
- [Russia-Linked Hackers Hit iOS, Android Devices With Exploit Chains via Watering Holes](https://www.securityweek.com/russia-linked-hackers-hit-ios-android-devices-with-exploit-chains-via-watering-holes/)

### The Record
- [Queens Public Library says ransomware attack disrupted Wi-Fi, on-site computers](https://therecord.media/queens-library-ransomware-causes-disruptions)
- [Social media giants sue California to overturn law shielding kids 15 and under from compulsive use](https://therecord.media/social-media-giants-sue-california-over-social-media-law)
- [US issues more sanctions against Prince Group scam center affiliates](https://therecord.media/us-issues-more-sanctions-against-prince-group-scammers)
- [Harden cooling systems now, feds warn critical infrastructure operators amid attacks](https://therecord.media/cyberattacks-refrigeration-cisa-fbi)
- [Russian state-linked hackers target iPhone, Android devices in zero-click espionage campaign](https://therecord.media/russia-hackers-smartphone-cyberattacks)

### Infosecurity Magazine
- [Half of Security Leaders Report Sensitive Data Exposure Through AI Tools](https://www.infosecurity-magazine.com/news/security-data-exposure-ai/)
- [Residential Proxy Traffic Traced to White House Network](https://www.infosecurity-magazine.com/news/white-house-residential-proxy-exits/)
- [Zyxel Switch Patch Missed Flaw Behind Wave of Attacks](https://www.infosecurity-magazine.com/news/zyxel-gs1900-patch-missed-flaw/)
- [India Warns of New AI-Driven Cyber-Attacks Targeting Financial and Crypto Businesses](https://www.infosecurity-magazine.com/news/india-warns-ai-cyberattacks/)
- [Chinese Nation-State Threat Activity Falls Sharply in Q2 and Q3 2026](https://www.infosecurity-magazine.com/news/chinese-nation-activity-falls/)
- [GhostMap Bug Leaves Android Phones Stuck in Reboot Loop](https://www.infosecurity-magazine.com/news/ghostmap-bug-android-phones-stuck/)
- [NATS Air Traffic Control Failure Cost UK Economy £33m](https://www.infosecurity-magazine.com/news/nats-air-traffic-control-fail-cost/)

### CyberScoop
- [Air Force cyber official: need to invest in digital forensics](https://cyberscoop.com/air-force-digital-forensics-cyber-investment/)
- [OpenAI debuts GPT-6 Cyber, touting better performance — and safety guardrails](https://cyberscoop.com/openai-gpt-6-cyber-security-model/)
- [What Democratic control of Congress means for cybersecurity](https://cyberscoop.com/democrats-congress-cybersecurity-cisa-ai-priorities/)

### Cisco Talos
- [Bring a tent, I've got the coffee: Lessons from it-sa](https://blog.talosintelligence.com/bring-a-tent-ive-got-the-coffee-lessons-from-it-sa/)

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
- [Threat actors use agentic AI tooling to find and abuse exposed secrets](https://www.microsoft.com/en-us/security/blog/2026/11/05/threat-actors-use-agentic-ai-tooling-to-find-and-abuse-exposed-secrets/)
- [New investments to reduce on-premises security risk](https://techcommunity.microsoft.com/blog/microsoft-security-blog/new-investments-to-reduce-on-premises-security-risk/4570381)
- [​​​​What’s new in Microsoft Security: November 2026](https://www.microsoft.com/en-us/security/blog/2026/11/05/whats-new-in-microsoft-security-november-2026/)
- [Email threat landscape: Q3 2026 trends and insights](https://www.microsoft.com/en-us/security/blog/2026/11/05/email-threat-landscape-q3-2026-trends-and-insights/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Friday, November 6th, 2026 https://isc.sans.edu/podcastdetail/10168, (Fri, Nov 6th)](https://isc.sans.edu/diary/rss/33494)
- [Vulnerability Scans for Older Cisco IOS Vulnerability / Opt-Out Headers, (Thu, Nov 5th)](https://isc.sans.edu/diary/rss/33492)
- [ISC Stormcast For Thursday, November 5th, 2026 https://isc.sans.edu/podcastdetail/10166, (Thu, Nov 5th)](https://isc.sans.edu/diary/rss/33490)

### Securelist (Kaspersky)
- [Virtualization security: attack layers and misconfiguration impact](https://securelist.com/virtualization-security-esxi-and-proxmox-ransomware-cases/121819/)
- [The SOC Files 5: Ghost in the pipeline, or a fileless SharePoint breach by Storm-2603](https://securelist.com/storm-2603-fileless-toolshell-attack/121467/)

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