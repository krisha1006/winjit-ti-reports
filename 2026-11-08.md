# Winjit Daily TI Digest — 2026-11-08

_Auto-generated. Window: last ~24h. Fetched at 2026-11-08T09:59:52.400512+00:00Z_

**At a glance:** 0 new KEV · 179 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-123966 | 10.0 | n/a | A vulnerability was determined in Tenda AC19 16.03.10.07. Affected by this issue is the function saveParentControlInfo of the file /goform/saveParentControlInfo. This manipulation of the argument devi |
| CVE-2026-123551 | 10.0 | n/a | OpenAM from 14.0.0 before 16.1.4 contains an information disclosure vulnerability that allows unauthenticated attackers to read live session tokens from the notification WebSocket. Attackers can bypas |
| CVE-2026-16884 | 9.9 | 0.5% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information due to an XML external entity (XXE) injection. |
| CVE-2026-16920 | 9.9 | 0.5% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to bypass security restrictions due to a confused deputy vulnerability. |
| CVE-2026-17049 | 9.9 | 0.5% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information and modify arbitrary documents due to authorization bypass through user-controlled |
| CVE-2026-17117 | 9.9 | 0.8% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code due to improperly controlled modification of object attri |
| CVE-2026-17132 | 9.9 | 0.6% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary SQL commands due to improper neutralization of special elements used in an SQL command. |
| CVE-2026-17134 | 9.9 | 0.5% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary SQL commands due to SQL injection. |
| CVE-2026-17146 | 9.9 | 0.7% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary JavaScript and obtain sensitive information due to improper in |
| CVE-2026-17147 | 9.9 | 0.9% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code and perform unauthorized administrative actions due to a  |
| CVE-2026-17150 | 9.9 | 0.8% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code and access sensitive information from other tenants due t |
| CVE-2026-17158 | 9.9 | 0.7% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to gain elevated privileges due to improper authentication. |
| CVE-2026-17239 | 9.9 | 0.8% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code due to a path traversal vulnerability. |
| CVE-2026-17298 | 9.9 | 0.5% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17336 | 9.9 | 0.6% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary SQL commands due to improper neutralization of special elements used in an SQL command. |
| CVE-2026-17342 | 9.9 | 0.9% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code due to improper control of generation of code. |
| CVE-2026-17354 | 9.9 | 0.7% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to perform arbitrary file writes due to path traversal. |
| CVE-2026-17359 | 9.9 | 0.9% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code due to improper control of generation of code. A user-sup |
| CVE-2026-17392 | 9.9 | 0.7% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to gain unauthorized administrative access to other tenants due to LDAP injection.  |
| CVE-2026-17399 | 9.9 | 0.8% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code due to insufficient validation of uploaded content. Conte |
| CVE-2026-17402 | 9.9 | 1.9% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary commands due to OS command injection. User-supplied input is n |
| CVE-2026-17410 | 9.9 | 0.7% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to access and modify other tenants' portal data due to improper neutralization of a |
| CVE-2026-123957 | 9.9 | 0.5% | A vulnerability was determined in TOTOLINK CA300-PoE 6.2c.884. Impacted is the function setIpQosRules of the file /cgi-bin/cstecgi.cgi. This manipulation of the argument ipStart causes buffer overflow |
| CVE-2026-123958 | 9.9 | 0.5% | A vulnerability was identified in TOTOLINK CA300-PoE 6.2c.884. The affected element is the function setLanConfig of the file /cgi-bin/cstecgi.cgi. Such manipulation of the argument lanDns/lanSecDns/la |
| CVE-2026-123960 | 9.9 | 0.8% | A weakness has been identified in TOTOLINK CA300-PoE 6.2c.884. This affects the function setWanConfig of the file /cgi-bin/cstecgi.cgi. Executing a manipulation of the argument pppoeUser/priDns/secDns |
| CVE-2026-123961 | 9.9 | n/a | A security vulnerability has been detected in TOTOLINK CA300-PoE 6.2c.884. This impacts the function setWiFiBasicConfig of the file /cgi-bin/cstecgi.cgi. The manipulation of the argument KeyStr leads  |
| CVE-2026-93754 | 9.8 | 0.9% | The payever – WooCommerce Gateway plugin for WordPress is vulnerable to arbitrary file upload leading to remote code execution in various versions up to, and including, 4.8.0. Three WooCommerce-API ca |
| CVE-2026-123218 | 9.8 | 0.4% | IBM Aspera Faspex 5.0.0 through 5.0.19 could allow an authorized user to craft a specific message to bypass user authorization and gain full administrative privileges. |
| CVE-2026-19803 | 9.8 | 1.0% | The Printcart Store – Web to Print Product Designer for WooCommerce plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 2.13.2. This is due to the `nbu_cr |
| CVE-2026-16720 | 9.8 | 0.8% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain valid access tokens for other users due to improper authentication. Authentication agai |
| CVE-2026-17278 | 9.8 | 0.7% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to gain unauthorized access to sensitive API catalog and runtime configuration data due to improper authentication. Information  |
| CVE-2026-17301 | 9.8 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow an unauthenticated attacker to bypass authentication due to improper verification of a cryptographic signature. |
| CVE-2026-17313 | 9.8 | 0.8% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information and take control of gateway configuration due to authentication bypass via an alternate path. |
| CVE-2026-17340 | 9.8 | 0.9% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to execute arbitrary code due to a path traversal vulnerability. |
| CVE-2026-17360 | 9.8 | 0.6% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to gain full administrative control due to the use of hard-coded credentials. |
| CVE-2026-17408 | 9.8 | 0.9% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to execute arbitrary code due to improper neutralization of special elements in an OS command. |
| CVE-2026-123549 | 9.8 | n/a | OpenAM before 16.1.4 fails to enforce the Valid Creation Attributes list during self-registration, allowing anonymous attackers to set restricted attributes including group membership. Attackers can r |
| CVE-2026-123550 | 9.8 | n/a | OpenAM before 16.1.4 contains an authentication bypass vulnerability in its SAML v2.0 service provider that accepts unsigned assertions on the ECP (PAOS) and HTTP-Artifact bindings when WantAssertions |
| CVE-2026-123614 | 9.8 | n/a | imgproxy from 4.0.0 before 4.0.16 contains an integer overflow in the ICO loader that allows remote attackers to trigger a heap buffer overflow via a crafted data_size value. Attackers can submit a cr |
| CVE-2026-17296 | 9.6 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17297 | 9.6 | 0.6% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to perform an account takeover due to an open redirect vulnerability. The redirect address used d |
| CVE-2026-17299 | 9.6 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to perform arbitrary file reads and server-side request forgery due to unrestricted |
| CVE-2026-17353 | 9.6 | 0.5% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information and bypass security restrictions due to server-side request forgery. |
| CVE-2026-17394 | 9.6 | 0.5% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improperly controlled modification of object |
| CVE-2026-17396 | 9.6 | 0.5% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to SQL injection. |
| CVE-2026-18838 | 9.4 | 0.7% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information and modify API configurations due to improper authentication. Identity information supplied in r |
| CVE-2026-16918 | 9.3 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to access internal network resources due to server-side request forgery. |
| CVE-2026-17131 | 9.3 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information due to server-side request forgery. Restrictions on outbound requests can be bypassed, so the se |
| CVE-2026-17329 | 9.3 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information due to improper validation of endpoint URLs. |
| CVE-2026-17344 | 9.3 | 0.5% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information due to server-side request forgery. A service that can be reached without authentication could b |
| CVE-2026-18836 | 9.3 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information due to server-side request forgery. The affected component can be |
| CVE-2026-17066 | 9.1 | 0.6% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information and modify or delete data belonging to other tenants due to missing authorization. |
| CVE-2026-17292 | 9.1 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to take over ownership of other organizations due to broken object-level authorizat |
| CVE-2026-17338 | 9.1 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to broken object-level authorization. |
| CVE-2026-17339 | 9.1 | 0.5% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to access or delete resources belonging to other tenants due to path traversal. |
| CVE-2026-123959 | 9.1 | 0.8% | A security flaw has been discovered in TOTOLINK CA300-PoE 6.2c.884. The impacted element is the function setLanguageCfg of the file /cgi-bin/cstecgi.cgi. Performing a manipulation of the argument lang |
| CVE-2026-118066 | 9.1 | n/a | The Appointment Booking Plugin – LatePoint | Calendar & Scheduling for WordPress plugin for WordPress is vulnerable to Authentication Bypass via Account Takeover in all versions up to, and including,  |
| CVE-2026-120984 | 9.1 | n/a | A flaw was found in the Keycloak server's client management component. When a client is created or imported with authorization services enabled, the system fails to properly clear an internal session  |
| CVE-2026-124057 | 9.1 | n/a | A security flaw has been discovered in TOTOLINK CA300-PoE 6.2c.884. This impacts the function setWiFiMultipleConfig of the file /cgi-bin/cstecgi.cgi. Performing a manipulation of the argument Key1Str1 |
| CVE-2026-124058 | 9.1 | n/a | A weakness has been identified in TOTOLINK CA300-PoE 6.2c.884. Affected is the function setWiFiRepeaterConfig of the file /cgi-bin/cstecgi.cgi. Executing a manipulation of the argument ApCliKeyStr can |
| CVE-2026-124059 | 9.1 | n/a | A security vulnerability has been detected in TOTOLINK CA300-PoE 6.2c.884. Affected by this vulnerability is the function setWiFiWdsAddConfig of the file /cgi-bin/cstecgi.cgi. The manipulation of the  |
| CVE-2026-124060 | 9.1 | n/a | A vulnerability was detected in TOTOLINK CA300-PoE 6.2c.884. Affected by this issue is the function UploadCustomModule of the file /cgi-bin/cstecgi.cgi. The manipulation of the argument File results i |
| CVE-2026-17403 | 9.0 | 0.5% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to gain full administrative control due to the use of hard-coded credentials. |
| CVE-2026-17280 | 8.9 | 0.5% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to perform unauthenticated brute-force attacks to obtain valid credentials due to improper restri |
| CVE-2026-16716 | 8.8 | 0.6% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to bypass security restrictions to access and modify sensitive information due to i |
| CVE-2026-17335 | 8.8 | 0.8% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code due to path traversal. File paths in uploaded content are not sufficiently validated, wh |
| CVE-2026-17405 | 8.8 | 0.5% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to broken object-level authorization. Access ch |
| CVE-2026-87112 | 8.8 | 0.8% | The QA Assistants – Driven by data plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 5.3.0 via the 'dlevent_ver' parameter. This is due to unrestricted P |
| CVE-2026-123531 | 8.8 | n/a | Vikunja from 1.0.0 before 2.7.1 contains an uncontrolled resource consumption vulnerability that allows authenticated users to bypass service.maxitemsperpage by sending page=0 to /api/v1 list endpoint |
| CVE-2026-123595 | 8.8 | n/a | Hickory DNS hickory-proto 0.25 through 0.26.0-alpha.1 and hickory-net 0.26.0-beta.1 before 0.26.2 contain a DNSSEC validation flaw in the validating recursor's NSEC3 handler, which matches the closest |
| CVE-2026-123596 | 8.8 | n/a | Hickory DNS hickory-proto through 0.26.0-alpha.1 and hickory-net 0.26.0-beta.1 before 0.26.2 contain a DNSSEC validation flaw in the validating recursor's NSEC handler that accepts parent-side ancesto |
| CVE-2026-123605 | 8.8 | n/a | Hickory DNS hickory-proto 0.1 through 0.25.0-alpha.3 and hickory-net before 0.26.2 contain a DNSSEC validation bypass because the validator verifies an RRSIG against the DNSKEY of whatever name appear |
| CVE-2026-16709 | 8.7 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary JavaScript in the victim's browser due to cross-site scripting |
| CVE-2026-17190 | 8.7 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary JavaScript due to cross-site scripting. HTML content supplied  |
| CVE-2026-17291 | 8.7 | 0.5% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to perform account takeover due to an open redirect vulnerability. The redirect add |
| CVE-2026-17332 | 8.7 | 0.3% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to bypass security restrictions due to improper certificate validation. |
| CVE-2026-17356 | 8.7 | 0.3% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a local attacker to obtain sensitive information due to the use of a hard-coded cryptographic key. |
| CVE-2026-16880 | 8.5 | 0.6% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to path traversal. |
| CVE-2026-16912 | 8.5 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17108 | 8.5 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17172 | 8.5 | 0.6% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to bypass security restrictions due to improper authentication. Information supplie |
| CVE-2026-17187 | 8.5 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improper validation of user-supplied URLs. |
| CVE-2026-17188 | 8.5 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. When service definitions are imported, referen |
| CVE-2026-17228 | 8.5 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. Destination restrictions on outbound requests  |
| CVE-2026-17287 | 8.5 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. User-supplied a |
| CVE-2026-17288 | 8.5 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17290 | 8.5 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to create unauthorized user accounts due to improper verification of cryptographic  |
| CVE-2026-17293 | 8.5 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to modify user profile information due to broken object-level authorization. Access |
| CVE-2026-17294 | 8.5 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17325 | 8.5 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improper validation of user-supplied URLs. |
| CVE-2026-17327 | 8.5 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17328 | 8.5 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improper input validation. Input checks are incomplete, which could allow t |
| CVE-2026-17330 | 8.5 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17334 | 8.5 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improper authorization via user-controlled keys. |
| CVE-2026-17352 | 8.5 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17365 | 8.5 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17380 | 8.5 | 0.5% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to access sensitive information belonging to other tenants due to improper validati |
| CVE-2026-17381 | 8.5 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improper authorization validation using user |
| CVE-2026-17382 | 8.5 | 0.6% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to a path traversal vulnerability. |
| CVE-2026-17384 | 8.5 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 could allow a remote authenticated attacker to obtain sensitive information due to a server-side request forgery vulnerability. |
| CVE-2026-17385 | 8.5 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17388 | 8.5 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to broken object-level authorization. |
| CVE-2026-17397 | 8.5 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17398 | 8.5 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17404 | 8.5 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17406 | 8.5 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. Address checks  |
| CVE-2026-17407 | 8.5 | 0.5% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary SQL commands due to SQL injection. Values received during sign |
| CVE-2026-17324 | 8.3 | 0.5% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to access sensitive configuration data and perform unauthorized actions due to missing authentication for a critical function. |
| CVE-2026-19121 | 8.3 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow an authenticated attacker to gain unauthorized access due to improper authorization. Tenant context is not sufficiently verified against the authe |
| CVE-2026-17355 | 8.2 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information from internal network resources due to server-side request forgery. Destination ch |
| CVE-2026-17358 | 8.2 | 0.5% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to bypass authentication across tenants due to improper authentication. Authenticat |
| CVE-2026-17321 | 8.1 | 0.5% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to delete or overwrite arbitrary control-plane assets due to an insecure direct object reference. |
| CVE-2026-17326 | 8.1 | 0.6% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to bypass security restrictions due to improper authentication. |
| CVE-2026-17343 | 8.1 | 0.5% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to bypass authorization checks to access or modify sensitive information due to improper authorization. |
| CVE-2026-17386 | 8.1 | 0.5% | IBM API Connect 10.0.8.0 through 10.0.8.12 could allow a remote attacker to gain full administrative control due to the use of a cryptographically weak pseudo-random number generator. |
| CVE-2026-104738 | 8.1 | 0.4% | The Advanced Form Integration — Connect Forms to 300+ Apps plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 2.10.2 via deserialization of untrusted inpu |
| CVE-2026-103900 | 8.1 | 0.6% | The WPJAM Basic plugin for WordPress is vulnerable to Privilege Escalation in versions up to, and including, 7.1 This is due to the WPJAM_User_Signup::signup() function unpacking attacker-supplied `da |
| CVE-2026-17309 | 8.0 | 0.1% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information and tamper with configuration due to improper certificate validation. |
| CVE-2026-17333 | 8.0 | 0.2% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to bypass authentication and inject unauthorized configuration changes due to improper certificat |
| CVE-2026-17129 | 7.6 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information and cause a denial of service due to an insecure direct object reference. |
| CVE-2026-17357 | 7.6 | 0.4% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to access internal network services due to server-side request forgery. |
| CVE-2026-17411 | 7.6 | 0.3% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow an authenticated attacker to view, add, modify, or delete information in the back-end database due to SQL injection |
| CVE-2026-105002 | 7.5 | 0.3% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow arbitrary code to be executed by the management service in certain non-default configurations due to improper contr |
| CVE-2026-120043 | 7.5 | 0.4% | The Affiliate Program Suite — SliceWP Affiliates plugin for WordPress is vulnerable to generic SQL Injection via the 'email' parameter in all versions up to, and including, 1.2.14 due to insufficient  |
| CVE-2026-16714 | 7.5 | 0.5% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to overwrite arbitrary files due to a path traversal vulnerability. |
| CVE-2026-107616 | 7.5 | 0.5% | The Amelia plugin for WordPress is vulnerable to unauthorized access of attendee data due to a missing authorization check on the GetEventAttendeesCommandHandler::handle() function in versions up to,  |
| CVE-2026-119155 | 7.5 | 0.6% | The wpForo Forum plugin for WordPress is vulnerable to time-based SQL Injection via the 'href[locale]' parameter in all versions up to, and including, 3.2.2 due to insufficient escaping on the user su |
| CVE-2026-119164 | 7.5 | 0.5% | The wpForo Forum plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 3.2.2 via the `data[secondary_groupids]` parameter of the `wpforo_action_profile_updat |
| CVE-2026-95870 | 7.5 | 0.5% | The wpForo Forum plugin for WordPress is vulnerable to generic SQL Injection via the 'data' parameter in all versions up to, and including, 3.2.1 due to insufficient escaping on the user supplied para |
| CVE-2026-116751 | 7.5 | n/a | The Booking for Appointments and Events Calendar – Amelia Pro plugin for WordPress is vulnerable to time-based SQL Injection via the 'tag[] (array KEYS)' parameter in all versions up to, and including |
| CVE-2026-123543 | 7.5 | n/a | OpenAM before 16.1.4 contains a denial of service vulnerability that allows unauthenticated attackers to exhaust server resources by sending serialized Java data without size or structure limits. Atta |
| CVE-2026-123554 | 7.5 | n/a | Zebra zebrad 6.4.0 before 7.0.0 performs quadratic work in the mempool coinbase-maturity check because Transaction::coinbase_spend_restriction() rebuilds the transaction's output list once per spent o |
| CVE-2026-123555 | 7.5 | n/a | Zebra from 2.3.0 before 7.0.0 contains a denial of service vulnerability that allows unauthenticated peers to evade misbehavior scoring by sending transactions or blocks with invalid transparent scrip |
| CVE-2026-123558 | 7.5 | n/a | Zebra zebrad before 7.0.0 contains a denial of service vulnerability that allows a malicious peer to stall checkpoint sync by cancelling the verifier rewind after a failed commit. Attackers can serve  |
| CVE-2026-123559 | 7.5 | n/a | Zebra before 7.0.0 contains an inefficient algorithmic complexity vulnerability that allows unauthenticated peers to exhaust verification threads by submitting transactions with many transparent input |
| CVE-2026-123560 | 7.5 | n/a | Zebra before 7.0.0 contains an incomplete cleanup vulnerability that allows unauthenticated peers to stall initial sync by serving a forged checkpoint block body. Attackers can supply a body with forg |
| CVE-2026-123562 | 7.5 | n/a | devalue (sveltejs/devalue) 5.8.0 before 5.9.3 contains an unhandled promise rejection in stringifyAsync: when serializing multiple promises, a later promise rejecting before an earlier one settles lea |
| CVE-2026-123563 | 7.5 | n/a | Devalue before 5.9.3 contains a validation bypass vulnerability that allows custom ArrayBuffer revivers to skip typed-array allocation checks in the parse function. Attackers can supply very small cra |
| CVE-2026-123564 | 7.5 | n/a | Sveltejs devalue from 1.0.0 before 5.9.3 contains a memory exhaustion flaw in uneval, whose generated code for sparse arrays allocates memory proportional to the array's declared length when evaluated |
| CVE-2026-123565 | 7.5 | n/a | Sveltejs devalue before 5.9.3 contains a resource exhaustion vulnerability where repeated primitive strings cause quadratic expansion in the uneval function. Attackers can supply a small crafted paylo |
| CVE-2026-123566 | 7.5 | n/a | Sveltejs devalue before 5.9.3 contains a denial of service vulnerability that allows attackers to cause CPU amplification by supplying sparse arrays to uneval. Attackers who influence sparse values pa |
| CVE-2026-123569 | 7.5 | n/a | The devalue package for npm before 5.6.3 can consume excessive CPU and memory when serializing sparse arrays with uneval or stringify. An attacker who manages to get a sparse array created on the serv |
| CVE-2026-123570 | 7.5 | n/a | The DNS wire-format message parser in hickory-proto (Hickory DNS) 0.18 before 0.26.2 preallocates record vectors sized by the untrusted ANCOUNT, NSCOUNT, and ARCOUNT header fields before reading recor |
| CVE-2026-123571 | 7.5 | n/a | Hickory DNS from 0.26.0 before 0.26.2 contains an integer underflow vulnerability in TSIG RDATA decoding that allows remote attackers to trigger a panic via malformed records. Attackers can send a cra |
| CVE-2026-123572 | 7.5 | n/a | Hickory-dns from 0.20.1 before 0.26.2 contains a denial of service vulnerability in the hickory-proto SVCB and HTTPS record presentation format parser, which panics on malformed alpn values. Attackers |
| CVE-2026-123573 | 7.5 | n/a | hickory-dns from 0.20.1 before 0.26.2 contains a denial of service vulnerability in the hickory-proto SVCB and HTTPS record presentation format parser. Attackers can supply untrusted zone files where  |
| CVE-2026-123574 | 7.5 | n/a | The zone file parser in the hickory-proto crate of Hickory DNS 0.24.0 before 0.26.2 panics when a single token in a zone file is 4096 bytes or longer. Attackers who can supply untrusted zone files to  |
| CVE-2026-123575 | 7.5 | n/a | Hickory DNS before 0.26.2 contains a resource exhaustion vulnerability in its DNS-over-HTTPS HTTP/2 server that lacks sufficient timeouts or limits for incomplete request bodies. Remote attackers can  |
| CVE-2026-123576 | 7.5 | n/a | Hickory DNS 0.24.0 through 0.26.1 contains a memory exhaustion vulnerability that allows remote attackers to consume server resources by sending incomplete DNS-over-QUIC request bodies. Attackers can  |
| CVE-2026-123577 | 7.5 | n/a | Hickory DNS from 0.24.0 before 0.26.2 contains a resource exhaustion vulnerability that allows remote attackers to consume server memory via unbounded DoH request bodies. Attackers can send large requ |
| CVE-2026-123580 | 7.5 | n/a | Hickory DNS hickory-net 0.26.0-beta.1 before 0.26.2 and hickory-proto through 0.26.0-alpha.1 perform insufficient checks on NSEC3 record names during DNSSEC verification, comparing only the hashed lab |
| CVE-2026-123586 | 7.5 | n/a | Hickory DNS 0.25.0-alpha.3 through 0.25.2 contains a query amplification vulnerability in its recursive resolver, which mishandles cyclic sibling name server referrals that lack glue records. Attacker |
| CVE-2026-123588 | 7.5 | n/a | The recursive resolver in Hickory DNS (all versions of the hickory-recursor crate, and hickory-resolver 0.26.0 before 0.26.2) caches an empty connection pool when it follows a referral with no glue re |
| CVE-2026-123604 | 7.5 | n/a | Hickory DNS hickory-resolver 0.26.0-beta.1 before 0.26.2 contains an unbounded retry loop in NameServerPool::try_send, which re-queues truncated (TC) responses without checking the answering transport |
| CVE-2026-123606 | 7.5 | n/a | The hickory-dns recursor in hickory-recursor 0.25.0-alpha.3 through 0.25.2 and hickory-resolver 0.26.0-alpha.1 before 0.26.2 iterates every out-of-bailiwick NS target lacking glue in a referral withou |
| CVE-2026-123607 | 7.5 | n/a | Hickory DNS hickory-proto 0.25.0-alpha.3 through 0.25.2 and hickory-net before 0.26.1 contain an unbounded loop vulnerability in DnssecDnsHandle NSEC3 closest-encloser proof validation when the SOA ow |
| CVE-2026-123608 | 7.5 | n/a | Hickory DNS hickory-proto from 0.3.1 before 0.26.1 contains a denial of service vulnerability in BinEncoder that allows remote attackers to exhaust CPU through quadratic-time name compression. Attacke |
| CVE-2026-123615 | 7.5 | n/a | imgproxy 3.3.0 before 4.0.17 contains an out-of-bounds heap read and write in the ICO loader's BMP header reconstruction (vips_foreign_load_ico_header in vips/icoload.c) when an ICO entry declares a t |
| CVE-2026-123616 | 7.5 | n/a | imgproxy from 3.3.0 before 4.0.16 contains an unbounded memory allocation vulnerability in the ICO loader that fails to validate the data_size field. Attackers can supply a crafted 23-byte ICO file de |
| CVE-2026-17244 | 7.4 | 0.3% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to perform unauthorized actions and obtain sensitive information due to missing aut |
| CVE-2026-17337 | 7.4 | 0.2% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to bypass authentication due to improper certificate validation. A certificate check is not performed reliably in  |
| CVE-2026-17379 | 7.4 | 0.3% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to bypass authentication and assign arbitrary roles due to improper verification of cryptographic |
| CVE-2026-123881 | 7.3 | 0.3% | A vulnerability was found in OpenBMB Internet of Agents up to 9d78e88e47160eb42ee1ee8538c05e1c2c47877a. This issue affects the function fetch_chat_record of the file im_server/app.py of the component  |
| CVE-2026-123963 | 7.3 | n/a | A security vulnerability has been detected in OpenBMB Internet of Agents up to 9d78e88e47160eb42ee1ee8538c05e1c2c47877a. The impacted element is the function register of the file im_server/app.py of t |
| CVE-2026-123990 | 7.3 | n/a | A security vulnerability has been detected in DataEase up to 2.10.27/3.1.0. Affected is the function ExtWhere2Str.extWhere2sqlOjb of the file engine/trans/ExtWhere2Str.java of the component Chart Data |
| CVE-2026-123991 | 7.3 | n/a | A vulnerability was detected in DataEase up to 2.10.27. Affected by this vulnerability is the function WhitelistUtils.endsWithAny of the file WhitelistUtils.java of the component Authentication Filter |
| CVE-2026-17316 | 7.2 | 0.3% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to perform server-side request forgery due to improper validation of user-supplied input. |
| CVE-2026-17341 | 7.2 | 0.3% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to perform server-side request forgery and relay unauthorized email messages due to improper neutralization of user-supplied inp |
| CVE-2026-17401 | 7.2 | 0.9% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code due to a stack-based buffer overflow. |
| CVE-2026-75590 | 7.2 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to access internal network resources and obtain sensitive information due to server-side request forgery. A protection that bloc |
| CVE-2026-124318 | 7.2 | n/a | Treeio through 2.0 contains an insecure deserialization vulnerability in UpdateRecord.get_format_strings and ModuleSetting.loads that allows staff users to execute code via unverified pickle data. Att |
| CVE-2026-120531 | 7.2 | n/a | The Subscribe2 – Form, Email Subscribers & Newsletters plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the ‘data[ip]’ parameter in all versions up to, and including, 10.47 due to |
| CVE-2026-17284 | 7.1 | 0.3% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to perform unauthorized operations in other tenants' environments due to improper v |
| CVE-2026-17311 | 7.1 | 0.4% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to modify application API subscriptions due to broken object-level authorization. |
| CVE-2026-17319 | 7.1 | 0.2% | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to modify tool configuration and cause a denial of service due to improper authorization. Information supplied by  |
| CVE-2026-17322 | 7.1 | 0.2% | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a local attacker to obtain sensitive credentials and compromise accounts due to insertion of sensitive information  |
| CVE-2026-123520 | 7.1 | n/a | Vikunja from 0.18.0 before 2.7.1 contains a privilege escalation vulnerability that allows team owners to gain admin or ownership of read-only shared projects by deleting accounts. Attackers can creat |
| CVE-2026-123522 | 7.1 | n/a | Vikunja before 2.7.1 contains an authorization bypass vulnerability that allows authenticated users to read any task by injecting a crafted task object into a no-op Kanban bucket move. Attackers can s |
| CVE-2026-123545 | 7.1 | n/a | OpenAM from 14.5.1 before 16.1.4 contains a cross-site request forgery vulnerability in the OAuth 2.0 device authorization flow that allows attackers to approve device codes when consent is skipped fo |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-9f68-g44h-hw2f | CVE-2026-122085 | unknown | The Event Tickets Manager for WooCommerce WordPress plugin before 1.6.0 does not perform... |
| GHSA-2mgp-38q6-99x9 | CVE-2026-96963 | unknown | The Pie Register  WordPress plugin through 3.8.4.15 does not perform an authorisation check in... |
| GHSA-g6hq-r9gh-7r48 | CVE-2026-97194 | unknown | The Secure Custom Fields WordPress plugin before 6.9.8 does not perform a read-permission check... |
| GHSA-2j9h-chv5-8537 | CVE-2026-97193 | unknown | The Secure Custom Fields WordPress plugin before 6.9.8 does not verify that a user is allowed to... |
| GHSA-47pm-jg2m-gx97 | CVE-2026-97195 | unknown | The Secure Custom Fields WordPress plugin before 6.9.8 does not sanitize a persisted field... |
| GHSA-m587-3v6q-xg7x | CVE-2026-96961 | unknown | The Pie Register  WordPress plugin through 3.8.4.15 does not perform any capability, nonce or... |
| GHSA-488p-3q24-423r | CVE-2026-97192 | unknown | The Secure Custom Fields WordPress plugin before 6.9.8 does not re-apply its field-group location... |
| GHSA-m836-p73r-8pm6 | CVE-2026-85344 | unknown | The FV Flowplayer Video Player WordPress plugin before 7.5.57.7212 does not perform any... |
| GHSA-78p4-p67c-wwv7 | CVE-2026-110963 | unknown | The Userplace  WordPress plugin through 1.2.0 does not perform authorization checks on an AJAX... |
| GHSA-xvqw-hjj4-j538 | CVE-2026-105970 | unknown | The Thanh Toán Quét Mã QR Code Tự Động  WordPress plugin through 2.0.1 does not properly verify... |
| GHSA-4435-94rm-8hr8 | CVE-2026-122062 | unknown | The Pronamic Pay WordPress plugin before 11.1.0, Pronamic Pay doneren met Mollie WordPress plugin... |
| GHSA-fq3w-qx64-29mp | CVE-2026-110132 | unknown | The Sync Post With Other Site WordPress plugin before 1.9.4 does not properly authorize a content... |
| GHSA-vj5w-qq84-5r93 | CVE-2026-104639 | unknown | The Razorpay for WooCommerce WordPress plugin before 4.8.9 does not sanitize and escape a value... |
| GHSA-xxh9-x8mr-vqr4 | CVE-2026-106015 | unknown | The Ecommerce Affiliate WordPress plugin through 1.0.0 does not restrict one-time password... |
| GHSA-prj8-x666-xqff | CVE-2026-122060 | unknown | The WP Recipe Maker WordPress plugin before 10.9.2 does not check whether the post a recipe is... |
| GHSA-v95p-x24p-5c2m | CVE-2026-114432 | unknown | The Contact Form 7 WordPress plugin before 6.2.4 does not validate the type or extension of files... |
| GHSA-r5m7-h2q9-5j9j | CVE-2026-109925 | unknown | The Productive Commerce  WordPress plugin before 1.1.54 does not sanitise and escape a parameter... |
| GHSA-6vqr-9fh5-xmwj | CVE-2026-104337 | unknown | The Razorpay for WooCommerce WordPress plugin before 4.8.9 does not verify ownership of an order... |
| GHSA-3g9w-x4v7-974v | CVE-2026-104338 | unknown | The Razorpay for WooCommerce WordPress plugin before 4.8.9 does not perform an authorization... |
| GHSA-vg9h-3m8c-7g2h | CVE-2026-103375 | unknown | The Antom Payments WordPress plugin through 2.0.11 does not perform any ownership or... |
| GHSA-3hhc-3pgw-rhv3 | CVE-2026-103303 | unknown | The Turisbook Booking System WordPress plugin through 1.3.8 does not have authorisation and CSRF... |
| GHSA-q8gp-6fc4-wgxp | CVE-2026-104307 | unknown | The BackUpWordPress plugin before 3.15 does not perform a capability or nonce check on an AJAX... |
| GHSA-fvm2-c629-pcjf | CVE-2026-124422 | medium | SunEditor from 3.0.0 before 3.4.0 contains a stored cross-site scripting vulnerability in html... |
| GHSA-237f-p9h6-wq4r | CVE-2026-114713 | high | The labeled-response module in UnrealIRCd 6.0.0 before 6.2.7.1 does not escape the IRCv3 "label"... |
| GHSA-p65x-p3jr-w89f | CVE-2026-123614 | critical | imgproxy from 4.0.0 before 4.0.16 contains an integer overflow in the ICO loader that allows... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Twitter | BYOD | US | 2026-11-08T03:20:51.920702+00:00 |
| www.bogard.com.mx | incransom | MX | 2026-11-08T03:47:21.145552+00:00 |
| bpcm.com | incransom | US | 2026-11-08T03:48:13.488273+00:00 |
| Clínica La Sagrada Familia (Colombia) | Whitearmor | CO | 2026-11-08T03:33:23.256858+00:00 |
| q-technicians.be | incransom | BE | 2026-11-08T03:49:05.694674+00:00 |
| Company #147 | N0n | US | 2026-11-07T21:30:05.102300+00:00 |
| Company #146 | N0n | US | 2026-11-07T21:29:29.587919+00:00 |
| Company #145 | N0n | US | 2026-11-07T21:28:54.175017+00:00 |
| Company #144 | N0n | US | 2026-11-07T21:28:19.494267+00:00 |
| Company #143 | N0n | US | 2026-11-07T21:27:44.709856+00:00 |
| Company #142 | N0n | KR | 2026-11-07T21:27:09.983250+00:00 |
| Company #141 | N0n | US | 2026-11-07T21:26:34.828856+00:00 |
| Company #140 | N0n | CA | 2026-11-07T21:25:59.003387+00:00 |
| Company #139 | N0n | US | 2026-11-07T21:25:24.510834+00:00 |
| Company #138 | N0n | CA | 2026-11-07T21:24:49.353889+00:00 |
| by.zivor.co.il | safepay | IL | 2026-11-07T19:48:15.476860+00:00 |
| Tribunal de Justica do Estado de Minas Gerais | rhysida | BR | 2026-11-07T13:16:04.118621+00:00 |
| Autohaus Arnold | payload | DE | 2026-11-07T13:15:06.266313+00:00 |
| Brauco | payload |  | 2026-11-07T13:13:44.569461+00:00 |
| Schroers Ingenieure | payload | DE | 2026-11-07T13:12:23.416578+00:00 |

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
| 46.151.178.14 | 9 |
| 64.62.197.77 | 9 |
| 179.43.153.10 | 9 |
| 199.165.159.209 | 9 |
| 2.57.121.112 | 8 |
| 2.57.122.209 | 8 |
| 3.130.168.2 | 8 |
| 5.2.69.86 | 8 |
| 18.116.101.220 | 8 |
| 18.218.118.203 | 8 |
| 35.210.122.25 | 8 |
| 51.68.226.87 | 8 |
| 51.159.4.12 | 8 |
| 58.182.58.128 | 8 |
| 64.62.197.167 | 8 |
| 66.132.159.117 | 8 |
| 66.132.172.206 | 8 |
| 66.132.172.209 | 8 |
| 66.132.172.214 | 8 |

### OpenPhish (live phishing URLs)
- https://www.ucsg365.vercel.app/
- https://www.365973.top/downapp
- https://sprl.me/aZlTSEN
- https://www.roblox.com.ss/users/5757654538/profile
- https://icloud-jp8.xyz/apple-jp-card/jp/login.html
- https://eng-coinsquare.apper.so/
- https://p56e.top/downapp/r/p56e.top/r/p56e.topr/p56e.top
- https://p56e.top/downapp/r/p56e.top/r/p56e.top
- https://p56e.top/downapp/r/p56e.top/
- https://www.roblox.com.ml/users/118673527115/profile
- https://dashboard.phantom-wallet.to/home/import/index.html
- https://systemecuzen--sistemeculo.replit.app/
- https://server-security-page-2--barbnone.replit.app/
- https://neuricardo.click/
- http://promocaoblackdaamazon-h9b5ceb6fghgbtdr.eastus2-01.azurewebsites.net/
- https://store.communitycharts.com/workshop/Brassbounds-Fury/
- https://www.16654422.com/403.html?i=164.92.212.136&c=NL
- https://16654422.com/m/
- https://8r5p6e-qw644c24y-7k1z9p8m2s-2s9m.pages.dev/
- https://088wk-ete-fhrc-8tho6-10-09-2026-hh.pages.dev/

### PhishStats (recent phishing/malicious URLs, scored)
_No data returned this run._

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| 680c5817193fcc2bc6514e111225b43aa56dc231 | Vidar C&C |
| 14d5e3c11ac5c5c5228c1365b20e383cffae0140 | Vidar C&C |
| 9c43558bb0f7fe4afdeb6ed73197abe2365589c3 | Vidar C&C |
| 07e76b646820ea12065b4aa925d2a7e31f2b0841 | RevStealer C&C |
| 662893890b7e8b8f238a39783415f9f744e29175 | RevStealer C&C |
| 0afd01382371c84a699766d7f0b736e9440faee6 | PureLogsStealer C&C |
| 7b10bb2a42505df013247e7fde6b36f4f60ee924 | Vidar C&C |
| de47608bc00bb94984b4e123585b7e8be37bf8b4 | Vidar C&C |
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
- 1.14.192.95
- 1.14.240.247
- 1.159.54.33
- 1.161.133.214
- 1.162.217.195
- 1.20.104.16
- 1.203.149.250
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.220.198.126
- 1.235.183.146
- 1.238.106.229
- 1.24.16.182
- 1.247.245.61
- 1.250.67.114
- 1.250.67.190
- 1.26.90.14

### CINS Army (poorly-rated IPs)
- 1.12.229.231
- 1.15.14.29
- 1.183.226.72
- 1.192.129.106
- 1.20.151.114
- 1.20.93.114
- 1.214.29.155
- 1.214.98.143
- 1.220.119.115
- 1.24.16.108
- 1.24.16.114
- 1.24.16.118
- 1.24.16.126
- 1.24.16.129
- 1.24.16.130
- 1.24.16.136
- 1.24.16.144
- 1.24.16.150
- 1.24.16.151
- 1.24.16.152

## News (last ~36h, across outlets)
### The Hacker News
- [Claude Code's “Don't Ask Again” File Exposes Passwords and Keys in 1,122 Public Copies on GitHub](https://thehackernews.com/2026/11/claude-codes-dont-ask-again-file.html)

### BleepingComputer
- [Hackers pull off $133 million French bank heist via service provider](https://www.bleepingcomputer.com/news/security/hackers-pull-off-133-million-french-bank-heist-via-service-provider/)
- [CTM360 Exposes Fake Gift Card Scams Exploiting Trusted Brands](https://www.bleepingcomputer.com/news/security/ctm360-exposes-fake-gift-card-scams-exploiting-trusted-brands/)
- [SonicWall warns of new SSL-VPN MFA bypass flaw exploited in attacks](https://www.bleepingcomputer.com/news/security/sonicwall-warns-of-new-ssl-vpn-mfa-bypass-flaw-exploited-in-attacks/)
- [Runaway AI hacking agent behind WorkOS breach after escaping sandbox](https://www.bleepingcomputer.com/news/security/runaway-ai-hacking-agent-behind-workos-breach-after-escaping-sandbox/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
_No new items / feed unavailable this run._

### SecurityWeek
- [SonicWall Patches Exploited SonicOS Vulnerability That Weakens VPN Logins](https://www.securityweek.com/sonicwall-patches-exploited-sonicos-bug-that-weakens-vpn-logins/)

### The Record
_No new items / feed unavailable this run._

### Infosecurity Magazine
_No new items / feed unavailable this run._

### CyberScoop
_No new items / feed unavailable this run._

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
_No new items / feed unavailable this run._

### Microsoft Security Blog
- [ARTEX abuse expands as cybercriminals target financial sector](https://www.microsoft.com/en-us/security/blog/2026/11/06/artex-abuse-expands-as-cybercriminals-target-financial-sector/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
_No new items / feed unavailable this run._

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