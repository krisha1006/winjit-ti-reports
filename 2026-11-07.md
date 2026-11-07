# Winjit Daily TI Digest — 2026-11-07

_Auto-generated. Window: last ~24h. Fetched at 2026-11-07T09:47:39.631138+00:00Z_

**At a glance:** 1 new KEV · 179 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-19868 | SonicWall | SonicOS SSLVPN | SonicWall SonicOS SSLVPN Use of Single-factor Authentication Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-109469 | 10.0 | n/a | Authorization bypass through user-controlled key in Entra Device Registration allows an unauthorized attacker to elevate privileges over a network. |
| CVE-2026-16884 | 9.9 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information due to an XML external entity (XXE) injection. |
| CVE-2026-16920 | 9.9 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to bypass security restrictions due to a confused deputy vulnerability. |
| CVE-2026-17049 | 9.9 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information and modify arbitrary documents due to authorization bypass through user-controlled |
| CVE-2026-17117 | 9.9 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code due to improperly controlled modification of object attri |
| CVE-2026-17132 | 9.9 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary SQL commands due to improper neutralization of special elements used in an SQL command. |
| CVE-2026-17134 | 9.9 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary SQL commands due to SQL injection. |
| CVE-2026-17146 | 9.9 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary JavaScript and obtain sensitive information due to improper in |
| CVE-2026-17147 | 9.9 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code and perform unauthorized administrative actions due to a  |
| CVE-2026-17150 | 9.9 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code and access sensitive information from other tenants due t |
| CVE-2026-17158 | 9.9 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to gain elevated privileges due to improper authentication. |
| CVE-2026-17239 | 9.9 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code due to a path traversal vulnerability. |
| CVE-2026-17298 | 9.9 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17336 | 9.9 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary SQL commands due to improper neutralization of special elements used in an SQL command. |
| CVE-2026-17342 | 9.9 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code due to improper control of generation of code. |
| CVE-2026-17354 | 9.9 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to perform arbitrary file writes due to path traversal. |
| CVE-2026-17359 | 9.9 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code due to improper control of generation of code. A user-sup |
| CVE-2026-17392 | 9.9 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to gain unauthorized administrative access to other tenants due to LDAP injection.  |
| CVE-2026-17399 | 9.9 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code due to insufficient validation of uploaded content. Conte |
| CVE-2026-17402 | 9.9 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary commands due to OS command injection. User-supplied input is n |
| CVE-2026-17410 | 9.9 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to access and modify other tenants' portal data due to improper neutralization of a |
| CVE-2026-123957 | 9.9 | n/a | A vulnerability was determined in TOTOLINK CA300-PoE 6.2c.884. Impacted is the function setIpQosRules of the file /cgi-bin/cstecgi.cgi. This manipulation of the argument ipStart causes buffer overflow |
| CVE-2026-123958 | 9.9 | n/a | A vulnerability was identified in TOTOLINK CA300-PoE 6.2c.884. The affected element is the function setLanConfig of the file /cgi-bin/cstecgi.cgi. Such manipulation of the argument lanDns/lanSecDns/la |
| CVE-2026-123488 | 9.8 | n/a | Craft CMS 4.0.0 before 4.18.9 and 5.0.0 before 5.11.2 contains an unauthenticated SQL injection vulnerability in the element search endpoint because the attribute parameter is concatenated into the qu |
| CVE-2026-93754 | 9.8 | n/a | The payever – WooCommerce Gateway plugin for WordPress is vulnerable to arbitrary file upload leading to remote code execution in various versions up to, and including, 4.8.0. Three WooCommerce-API ca |
| CVE-2026-123218 | 9.8 | n/a | IBM Aspera Faspex 5.0.0 through 5.0.19 could allow an authorized user to craft a specific message to bypass user authorization and gain full administrative privileges. |
| CVE-2026-19803 | 9.8 | n/a | The Printcart Store – Web to Print Product Designer for WooCommerce plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 2.13.2. This is due to the `nbu_cr |
| CVE-2026-16720 | 9.8 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain valid access tokens for other users due to improper authentication. Authentication agai |
| CVE-2026-17278 | 9.8 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to gain unauthorized access to sensitive API catalog and runtime configuration data due to improper authentication. Information  |
| CVE-2026-17301 | 9.8 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow an unauthenticated attacker to bypass authentication due to improper verification of a cryptographic signature. |
| CVE-2026-17313 | 9.8 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information and take control of gateway configuration due to authentication bypass via an alternate path. |
| CVE-2026-17340 | 9.8 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to execute arbitrary code due to a path traversal vulnerability. |
| CVE-2026-17360 | 9.8 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to gain full administrative control due to the use of hard-coded credentials. |
| CVE-2026-17408 | 9.8 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to execute arbitrary code due to improper neutralization of special elements in an OS command. |
| CVE-2026-17296 | 9.6 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17297 | 9.6 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to perform an account takeover due to an open redirect vulnerability. The redirect address used d |
| CVE-2026-17299 | 9.6 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to perform arbitrary file reads and server-side request forgery due to unrestricted |
| CVE-2026-17353 | 9.6 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information and bypass security restrictions due to server-side request forgery. |
| CVE-2026-17394 | 9.6 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improperly controlled modification of object |
| CVE-2026-17396 | 9.6 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to SQL injection. |
| CVE-2026-18535 | 9.6 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 are vulnerable to a Regular Expression Denial of Service (ReDoS) attack and to improper neutralisation of wildcard query operat |
| CVE-2026-17409 | 9.4 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to execute unauthorized administrative operations and obtain sensitive information due to imprope |
| CVE-2026-18838 | 9.4 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information and modify API configurations due to improper authentication. Identity information supplied in r |
| CVE-2026-16918 | 9.3 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to access internal network resources due to server-side request forgery. |
| CVE-2026-17131 | 9.3 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information due to server-side request forgery. Restrictions on outbound requests can be bypassed, so the se |
| CVE-2026-17329 | 9.3 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information due to improper validation of endpoint URLs. |
| CVE-2026-17344 | 9.3 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information due to server-side request forgery. A service that can be reached without authentication could b |
| CVE-2026-18836 | 9.3 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information due to server-side request forgery. The affected component can be |
| CVE-2026-17066 | 9.1 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information and modify or delete data belonging to other tenants due to missing authorization. |
| CVE-2026-17292 | 9.1 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to take over ownership of other organizations due to broken object-level authorizat |
| CVE-2026-17338 | 9.1 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to broken object-level authorization. |
| CVE-2026-17339 | 9.1 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to access or delete resources belonging to other tenants due to path traversal. |
| CVE-2026-17403 | 9.0 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to gain full administrative control due to the use of hard-coded credentials. |
| CVE-2026-17280 | 8.9 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to perform unauthenticated brute-force attacks to obtain valid credentials due to improper restri |
| CVE-2026-123490 | 8.8 | n/a | Craft CMS from 5.8.17 before 5.11.2 contains a privilege escalation vulnerability because getOwners() applies caller criteria without cleansing the query configuration. Authenticated control panel use |
| CVE-2026-123993 | 8.8 | n/a | Hisense VIDAA Smart TV firmware V0000.01.00a.P0220 contains an unauthenticated access vulnerability where a QA build of the Google Cobalt browser engine exposes the WebDriver automation server on TCP  |
| CVE-2026-50240 | 8.8 | n/a | A flaw was found in OpenShift Pipelines-as-Code (PAC). PAC does not verify whether the creator of a Repository custom resource has permission to create PipelineRuns. A namespace user with only Reposit |
| CVE-2026-104913 | 8.8 | n/a | The Interactive Real Estate – Floor Plan & Building Visualizer plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 2.6.0 via the extract_zip_data function |
| CVE-2026-16716 | 8.8 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to bypass security restrictions to access and modify sensitive information due to i |
| CVE-2026-17335 | 8.8 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code due to path traversal. File paths in uploaded content are not sufficiently validated, wh |
| CVE-2026-17405 | 8.8 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to broken object-level authorization. Access ch |
| CVE-2026-87112 | 8.8 | n/a | The QA Assistants – Driven by data plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 5.3.0 via the 'dlevent_ver' parameter. This is due to unrestricted P |
| CVE-2026-16709 | 8.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary JavaScript in the victim's browser due to cross-site scripting |
| CVE-2026-17190 | 8.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary JavaScript due to cross-site scripting. HTML content supplied  |
| CVE-2026-17291 | 8.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to perform account takeover due to an open redirect vulnerability. The redirect add |
| CVE-2026-17332 | 8.7 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to bypass security restrictions due to improper certificate validation. |
| CVE-2026-17356 | 8.7 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a local attacker to obtain sensitive information due to the use of a hard-coded cryptographic key. |
| CVE-2026-123786 | 8.5 | n/a | Agenta before 0.122.5 contains a server-side request forgery vulnerability that allows workspace members with workflow edit rights to redirect workflow invocations by setting arbitrary revision URLs.  |
| CVE-2026-16880 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to path traversal. |
| CVE-2026-16912 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17108 | 8.5 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17172 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to bypass security restrictions due to improper authentication. Information supplie |
| CVE-2026-17187 | 8.5 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improper validation of user-supplied URLs. |
| CVE-2026-17188 | 8.5 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. When service definitions are imported, referen |
| CVE-2026-17228 | 8.5 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. Destination restrictions on outbound requests  |
| CVE-2026-17287 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. User-supplied a |
| CVE-2026-17288 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17290 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to create unauthorized user accounts due to improper verification of cryptographic  |
| CVE-2026-17293 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to modify user profile information due to broken object-level authorization. Access |
| CVE-2026-17294 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17325 | 8.5 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improper validation of user-supplied URLs. |
| CVE-2026-17327 | 8.5 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17328 | 8.5 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improper input validation. Input checks are incomplete, which could allow t |
| CVE-2026-17330 | 8.5 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17334 | 8.5 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improper authorization via user-controlled keys. |
| CVE-2026-17352 | 8.5 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17365 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17380 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to access sensitive information belonging to other tenants due to improper validati |
| CVE-2026-17381 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improper authorization validation using user |
| CVE-2026-17382 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to a path traversal vulnerability. |
| CVE-2026-17384 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 could allow a remote authenticated attacker to obtain sensitive information due to a server-side request forgery vulnerability. |
| CVE-2026-17385 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17388 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to broken object-level authorization. |
| CVE-2026-17397 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17398 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17404 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17406 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. Address checks  |
| CVE-2026-17407 | 8.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary SQL commands due to SQL injection. Values received during sign |
| CVE-2026-123998 | 8.3 | n/a | Hisense VIDAA Smart TV firmware V0000.01.00a.P0220 contains an authentication bypass vulnerability in its remote-control MQTT broker on TCP port 36669, which accepts publicly documented default creden |
| CVE-2026-17324 | 8.3 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to access sensitive configuration data and perform unauthorized actions due to missing authentication for a critical function. |
| CVE-2026-19121 | 8.3 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow an authenticated attacker to gain unauthorized access due to improper authorization. Tenant context is not sufficiently verified against the authe |
| CVE-2026-17323 | 8.2 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information due to XML external entity (XXE) injection. |
| CVE-2026-17355 | 8.2 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information from internal network resources due to server-side request forgery. Destination ch |
| CVE-2026-17358 | 8.2 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to bypass authentication across tenants due to improper authentication. Authenticat |
| CVE-2026-124040 | 8.1 | n/a | CivetWeb through 1.16, when built with USE_HTTP2 and enable_http2 on, contains a use-after-free vulnerability in handle_http2() that retains freed :method and :path pointers. Unauthenticated remote at |
| CVE-2026-17321 | 8.1 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to delete or overwrite arbitrary control-plane assets due to an insecure direct object reference. |
| CVE-2026-17326 | 8.1 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to bypass security restrictions due to improper authentication. |
| CVE-2026-17343 | 8.1 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to bypass authorization checks to access or modify sensitive information due to improper authorization. |
| CVE-2026-17386 | 8.1 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 could allow a remote attacker to gain full administrative control due to the use of a cryptographically weak pseudo-random number generator. |
| CVE-2026-104738 | 8.1 | n/a | The Advanced Form Integration — Connect Forms to 300+ Apps plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 2.10.2 via deserialization of untrusted inpu |
| CVE-2026-17309 | 8.0 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to obtain sensitive information and tamper with configuration due to improper certificate validation. |
| CVE-2026-17333 | 8.0 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to bypass authentication and inject unauthorized configuration changes due to improper certificat |
| CVE-2026-123784 | 7.8 | n/a | Fluxbox through 1.3.7 contains an OS command injection vulnerability in RootTheme::reconfigTheme() that allows attackers to execute commands via crafted style background values. Attackers can embed sh |
| CVE-2026-16712 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information from other tenants due to improper authorization. I |
| CVE-2026-16715 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information from other tenants due to broken object-level autho |
| CVE-2026-16717 | 7.7 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to broken object-level authorization. |
| CVE-2026-16718 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improper validation of file paths. |
| CVE-2026-16854 | 7.7 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information belonging to other tenants due to an injection vulnerability. Input used to build  |
| CVE-2026-17112 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information belonging to other tenants due to broken object-lev |
| CVE-2026-17279 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to cause a denial of service due to uncontrolled resource consumption. Certain requ |
| CVE-2026-17281 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17282 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to broken object-level authorization. |
| CVE-2026-17283 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to broken object-level authorization. |
| CVE-2026-17285 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improper validation of external references.  |
| CVE-2026-17289 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17295 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to path traversal. |
| CVE-2026-17318 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improper authorization. |
| CVE-2026-17320 | 7.7 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to an insecure direct object reference. |
| CVE-2026-17345 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improper neutralization of special elements  |
| CVE-2026-17361 | 7.7 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to server-side request forgery. |
| CVE-2026-17363 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to SQL injection. |
| CVE-2026-17373 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improper authorization. |
| CVE-2026-17374 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to broken object-level authorization. |
| CVE-2026-17375 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to improper authorization. Authorization decisi |
| CVE-2026-17376 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to broken object-level authorization. |
| CVE-2026-17378 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to broken object-level authorization. |
| CVE-2026-17383 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information from other tenants due to broken object-level autho |
| CVE-2026-17387 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to broken object-level authorization. |
| CVE-2026-17400 | 7.7 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information due to SQL injection. |
| CVE-2026-17129 | 7.6 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to obtain sensitive information and cause a denial of service due to an insecure direct object reference. |
| CVE-2026-17357 | 7.6 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to access internal network services due to server-side request forgery. |
| CVE-2026-17411 | 7.6 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow an authenticated attacker to view, add, modify, or delete information in the back-end database due to SQL injection |
| CVE-2025-71458 | 7.5 | 0.4% | FTS3 Web Monitoring (fts-monitoring) versions 3.12.0 through 3.13.2 and 3.14.0 contain an unauthenticated sql injection vulnerability in the /linkinfo endpoint handled by get_linkinfo. Remote attacker |
| CVE-2026-123620 | 7.5 | n/a | Usermin through 2.570 contains an OS command injection vulnerability in the Read Mail module that allows authenticated users to execute commands through unsanitized IMAP folder names. Attackers can cr |
| CVE-2026-89017 | 7.5 | n/a | Skyline DataMiner BrokerGateway contains an embedded API key vulnerability that allows unauthenticated attackers to retrieve the installation-specific BrokerGateway key even while pairing mode is disa |
| CVE-2026-124027 | 7.5 | n/a | ChatWiki before 2.10.0 contains a missing authentication vulnerability in the GET /manage/getLibRawFileOnePage route that allows unauthenticated attackers to read other tenants' documents. Attackers c |
| CVE-2026-124078 | 7.5 | n/a | plist.js (npm package 'plist') before 5.0.1 contains an uncontrolled resource consumption vulnerability in the binary property-list parser (parseBinary) that allows unauthenticated attackers to crash  |
| CVE-2026-105002 | 7.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow arbitrary code to be executed by the management service in certain non-default configurations due to improper contr |
| CVE-2026-120043 | 7.5 | n/a | The Affiliate Program Suite — SliceWP Affiliates plugin for WordPress is vulnerable to generic SQL Injection via the 'email' parameter in all versions up to, and including, 1.2.14 due to insufficient  |
| CVE-2026-16714 | 7.5 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to overwrite arbitrary files due to a path traversal vulnerability. |
| CVE-2026-17331 | 7.5 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to read arbitrary files on the server due to external control of a file name or path. |
| CVE-2026-19128 | 7.5 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow an authenticated attacker to send unauthorized requests from the system due to server-side request forgery. This could be used to enumerate networ |
| CVE-2026-17244 | 7.4 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to perform unauthorized actions and obtain sensitive information due to missing aut |
| CVE-2026-17337 | 7.4 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to bypass authentication due to improper certificate validation. A certificate check is not performed reliably in  |
| CVE-2026-17379 | 7.4 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote attacker to bypass authentication and assign arbitrary roles due to improper verification of cryptographic |
| CVE-2026-123791 | 7.3 | n/a | A vulnerability was detected in OpenBMB Internet of Agents up to 9d78e88e47160eb42ee1ee8538c05e1c2c47877a. This affects the function _primary_field_query of the file common/utils/milvus_utils.py of th |
| CVE-2026-123881 | 7.3 | n/a | A vulnerability was found in OpenBMB Internet of Agents up to 9d78e88e47160eb42ee1ee8538c05e1c2c47877a. This issue affects the function fetch_chat_record of the file im_server/app.py of the component  |
| CVE-2026-87964 | 7.2 | 1.4% | The Product Feed Manager for WooCommerce – CTX Feed – Support 220+ Shopping, AI & Social Channels plugin for WordPress is vulnerable to PHP Code Injection in all versions up to, and including, 8.0.26. |
| CVE-2026-119070 | 7.2 | n/a | The Optimole – Optimize Images | Convert WebP & AVIF | CDN & Lazy Load | Image Optimization plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all version |
| CVE-2026-119175 | 7.2 | n/a | The Flying Images: Optimize and Lazy Load Images for Faster Page Speed plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and includin |
| CVE-2026-120082 | 7.2 | n/a | The GeoDirectory – WP Business Directory Plugin and Classified Listings Directory plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'post_content' parameter in all versions up  |
| CVE-2026-120512 | 7.2 | n/a | The Form Maker by 10Web – Mobile-Friendly Drag & Drop Contact Form Builder plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'wdform_<n>_element<id> (Hidden Input field, name = |
| CVE-2026-120540 | 7.2 | n/a | The iubenda | All-in-one Compliance for GDPR / CCPA Cookie Consent + more plugin for WordPress is vulnerable to Stored Cross-Site Scripting in versions up to, and including, 3.13.6. This is due to the |
| CVE-2026-119158 | 7.2 | n/a | The Pie Register – User Registration, Profiles & Content Restriction plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'first_name' parameter in all versions up to, and includi |
| CVE-2026-120677 | 7.2 | n/a | The Optimole – Optimize Images | Convert WebP & AVIF | CDN & Lazy Load | Image Optimization plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all version |
| CVE-2026-120739 | 7.2 | n/a | The Optimole – Optimize Images | Convert WebP & AVIF | CDN & Lazy Load | Image Optimization plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 's (missing_srcsets[*][*].s)' para |
| CVE-2026-119167 | 7.2 | n/a | The TranslatePress – Translate Multilingual sites with AI Translation plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment' parameter in all versions up to, and including |
| CVE-2026-17316 | 7.2 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to perform server-side request forgery due to improper validation of user-supplied input. |
| CVE-2026-17341 | 7.2 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to perform server-side request forgery and relay unauthorized email messages due to improper neutralization of user-supplied inp |
| CVE-2026-17401 | 7.2 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to execute arbitrary code due to a stack-based buffer overflow. |
| CVE-2026-75590 | 7.2 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote attacker to access internal network resources and obtain sensitive information due to server-side request forgery. A protection that bloc |
| CVE-2026-115811 | 7.2 | n/a | The Strong Testimonials plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'star_rating' parameter in all versions up to, and including, 3.3.16 due to insufficient input sanitiz |
| CVE-2026-116558 | 7.2 | n/a | The Unlimited Elements for Elementor plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the '<title>/<description> inside the attacker-controlled RSS feed body' parameter in all ver |
| CVE-2026-120537 | 7.2 | n/a | The TranslatePress – Translate Multilingual sites with AI Translation plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'comment (storage); originals / language / original_lang |
| CVE-2026-122037 | 7.2 | n/a | The AgenWebsite Shipping – Plugin Ongkos Kirim & Generate Resi Otomatis Semua Kurir Indonesia plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'zipcode' parameter in all versi |
| CVE-2026-17284 | 7.1 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to perform unauthorized operations in other tenants' environments due to improper v |
| CVE-2026-17311 | 7.1 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to modify application API subscriptions due to broken object-level authorization. |
| CVE-2026-17319 | 7.1 | n/a | IBM API Connect 12.1.0.0 through 12.1.1.2 could allow a remote authenticated attacker to modify tool configuration and cause a denial of service due to improper authorization. Information supplied by  |
| CVE-2026-17322 | 7.1 | n/a | IBM API Connect 10.0.8.0 through 10.0.8.12 and 12.1.0.0 through 12.1.1.2 could allow a local attacker to obtain sensitive credentials and compromise accounts due to insertion of sensitive information  |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-85c5-f7w5-7397 | CVE-2026-39733 | medium | Improper Neutralization of Script-Related HTML Tags in a Web Page (Basic XSS) vulnerability in... |
| GHSA-7wrj-jp98-f9qp | CVE-2026-121778 | medium | Missing Authorization vulnerability in WP Lab WP-Lister Lite for Amazon wp-lister-for-amazon... |
| GHSA-h2j4-jxgc-q6c7 | CVE-2026-52713 | medium | Missing Authorization vulnerability in ThimPress LearnPress learnpress allows Exploiting... |
| GHSA-c4px-fcrj-5258 | CVE-2026-123958 | high | A vulnerability was identified in TOTOLINK CA300-PoE 6.2c.884. The affected element is the... |
| GHSA-v5h9-p8rm-8wmg | CVE-2026-121781 | medium | Missing Authorization vulnerability in WP ManageNinja LLC Fluent Booking fluent-booking allows... |
| GHSA-p324-24fv-h86p | CVE-2026-121779 | medium | Exposure of Sensitive System Information to an Unauthorized Control Sphere vulnerability in YITH... |
| GHSA-wvj4-2674-f7w2 | CVE-2026-120849 | medium | Missing Authorization vulnerability in WC Lovers WCFM Marketplace wc-multivendor-marketplace... |
| GHSA-73qh-px6h-pjq6 | CVE-2026-121768 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-pcxr-2p3v-pf8v | CVE-2026-66669 | high | Cross-Site Request Forgery (CSRF) vulnerability in Suplugins Superb Addons: Blocks, Patterns &amp... |
| GHSA-gvrr-768p-vffx | CVE-2026-119489 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-wxh7-x4wq-j3rp | CVE-2026-123957 | high | A vulnerability was determined in TOTOLINK CA300-PoE 6.2c.884. Impacted is the function... |
| GHSA-4fhm-wfm9-x94p | CVE-2026-124274 | medium | Missing Authorization vulnerability in myCred myCred mycred allows Exploiting Incorrectly... |
| GHSA-j87r-75x7-m939 | CVE-2026-122675 | medium | Cross-Site Request Forgery (CSRF) vulnerability in Wpmet Wp Social wp-social allows Cross Site... |
| GHSA-2838-5w43-fw55 | CVE-2026-121761 | medium | Missing Authorization vulnerability in Infomaniak Network VOD Infomaniak vod-infomaniak allows... |
| GHSA-3rq6-42cq-4f92 | CVE-2026-121767 | medium | Missing Authorization vulnerability in weDevs weDocs wedocs allows Exploiting Incorrectly... |
| GHSA-qhhf-w5r7-gp9v | CVE-2026-120848 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-8h8c-m3hv-wvqp | CVE-2026-119510 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-3775-gmvc-wrxc | CVE-2026-122037 | high | The AgenWebsite Shipping – Plugin Ongkos Kirim & Generate Resi Otomatis Semua Kurir Indonesia... |
| GHSA-xqcq-7gq5-86v8 | CVE-2026-104738 | high | The Advanced Form Integration — Connect Forms to 300+ Apps plugin for WordPress is vulnerable to... |
| GHSA-2jqg-cqmw-45xr | CVE-2026-119467 | medium | Missing Authorization vulnerability in WPVibes AnyWhere Elementor anywhere-elementor allows... |
| GHSA-6gfw-3qvp-fj85 | CVE-2026-87112 | high | The QA Assistants – Driven by data plugin for WordPress is vulnerable to PHP Object Injection in... |
| GHSA-7gvr-jhhp-xg9c | CVE-2026-123881 | medium | A vulnerability was found in OpenBMB Internet of Agents up to... |
| GHSA-h386-5mv5-whv9 | CVE-2026-93370 | medium | The Paystack WooCommerce Payment Gateway plugin for WordPress is vulnerable to Sensitive... |
| GHSA-8pj4-8g3x-p45w | CVE-2026-121536 | medium | The WP Data Access – App Builder for Tables, Forms, Dashboards, Charts & Maps plugin for... |
| GHSA-xw2r-p69h-9jmx | CVE-2026-122265 | medium | The Vanquish Upload Files for WooCommerce plugin for WordPress is vulnerable to Directory... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| maersk | Whitearmor | DK | 2026-11-07T03:48:01.376268+00:00 |
| Kahler Automation | anubis | DE | 2026-11-07T01:08:56.613436+00:00 |
| Benesch Law | SilentRansomGroup | US | 2026-11-07T01:07:11.580830+00:00 |
| 1da9100e55aqf21eb651eNea | incransom | AL | 2026-11-07T00:15:21.235992+00:00 |
| Mutares.com | BrainCipher | DE | 2026-11-06T21:21:28.464004+00:00 |
| Tucker Ellis | SilentRansomGroup | US | 2026-11-06T18:58:03.015515+00:00 |
| Wachtell, Lipton, Rosen & Katz | SilentRansomGroup | US | 2026-11-06T18:57:43.060629+00:00 |
| B... law | SilentRansomGroup |  | 2026-11-06T16:36:19.921755+00:00 |
| Algonomy | direwolf | US | 2026-11-06T13:44:10.199376+00:00 |
| Hudson & Hudson SignProducts | akira | US | 2026-11-06T12:01:13.271975+00:00 |
| Istituto Borgo | Shiba | IT | 2026-11-06T12:00:26.537597+00:00 |
| https://www.sleep-clinic.ca/ | incransom | CA | 2026-11-06T19:09:52.349424+00:00 |
| Boyle, Pecharich, Cline, Whittington andStallings | akira |  | 2026-11-06T11:05:40.077375+00:00 |
| Dompé Farmaceutici S.p.A. | N0n | IT | 2026-11-06T10:54:16.341380+00:00 |
| Cogent Biosciences, Inc. | N0n | US | 2026-11-06T10:53:40.759861+00:00 |
| Chartboost LLC | N0n | US | 2026-11-06T10:53:06.138280+00:00 |
| Centrepoint | N0n | SA | 2026-11-06T10:52:31.590721+00:00 |
| Resource Consultants | N0n | US | 2026-11-06T10:51:56.709132+00:00 |
| Company #6 | OBSOFT |  | 2026-11-06T12:52:45.209965+00:00 |
| Max Fashion | N0n | AE | 2026-11-06T01:24:03.243618+00:00 |

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
| 138.226.239.233 | 10 |
| 138.226.239.234 | 10 |
| 3.129.187.38 | 9 |
| 18.218.118.203 | 9 |
| 64.62.197.77 | 9 |
| 66.132.172.139 | 9 |
| 66.132.172.183 | 9 |
| 66.132.172.214 | 9 |
| 77.239.124.175 | 9 |
| 196.189.236.67 | 9 |
| 199.165.159.209 | 9 |
| 220.80.223.144 | 9 |
| 3.131.220.121 | 8 |
| 31.57.34.150 | 8 |
| 35.202.9.133 | 8 |
| 35.210.83.117 | 8 |
| 35.210.98.27 | 8 |
| 45.148.10.121 | 8 |
| 51.159.4.12 | 8 |
| 58.182.58.128 | 8 |

### OpenPhish (live phishing URLs)
- https://www.roblox.com.ml/users/206830307895/profile
- https://s4w.in/www-roblox-com-users-2068330307895-profile
- http://hometown-herbal-ledger-13.pages.dev/
- https://www.roblox.rw/users/441698548140/profile
- https://g5.lu/52ecz
- https://vaibhavinayak10.github.io/AmazonProject.github.io/
- https://vaibhavinayak10.github.io/AmazonProject.github.io
- https://redysel.com/img/TL-WR840N/47684uyjkhv67954.html
- https://hmilp09kod.flazio.online/
- https://railbuyer.sbb.b-op.com/railbuyer
- https://hispeed-ch70.jimdofree.com/
- http://www.shopee77bombastis.blogspot.com/
- https://roblox.com.gr/games/125538696653169/Showdown-Anime-FPS-Jutsu-Shooter
- https://vaibhavinayak10.github.io/AmazonDarkMode.github.io/
- https://vaibhavinayak10.github.io/AmazonDarkMode.github.io
- https://helpledger.live/login.php
- https://meinhostingfa14r-qqhgpqtwdl.live-website.com/esat/
- https://pncverify.pagekite.me/
- http://fresh-experiences-537560.framer.app/
- http://pichinch-web--juanpila22222.replit.app/

### PhishStats (recent phishing/malicious URLs, scored)
_No data returned this run._

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
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
| f40c3e5760bab5d2d8839c0e55a18f660fbbcd94 | PureLogsStealer C&C |
| c1079d2e32f2c06188ae5eca7e1d65735358b0b8 | doxbin.cy |

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
- 1.14.240.247
- 1.159.54.33
- 1.161.133.214
- 1.162.217.195
- 1.172.90.41
- 1.175.131.108
- 1.179.151.165
- 1.203.149.250
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.220.198.126
- 1.222.42.237
- 1.234.80.94
- 1.235.183.146
- 1.238.106.229
- 1.24.16.182
- 1.247.245.61
- 1.250.67.114

### CINS Army (poorly-rated IPs)
- 1.14.64.144
- 1.145.89.105
- 1.15.14.29
- 1.193.59.243
- 1.20.151.114
- 1.24.16.101
- 1.24.16.118
- 1.24.16.122
- 1.24.16.129
- 1.24.16.131
- 1.24.16.144
- 1.24.16.147
- 1.24.16.153
- 1.24.16.157
- 1.24.16.158
- 1.24.16.16
- 1.24.16.165
- 1.24.16.168
- 1.24.16.20
- 1.24.16.21

## News (last ~36h, across outlets)
### The Hacker News
- [Claude Code's “Don't Ask Again” File Exposes Passwords and Keys in 1,122 Public Copies on GitHub](https://thehackernews.com/2026/11/claude-codes-dont-ask-again-file.html)
- [Installing the Fix for an Exploited WordPress Flaw Can Expose Some Sites One Last Time](https://thehackernews.com/2026/11/installing-fix-for-exploited-wordpress.html)
- [Hackers Target OpenSSH SSHole Flaw Within Hours of Disclosure, Gain Root on Honeypot](https://thehackernews.com/2026/11/hackers-exploited-openssh-sshole-flaw.html)
- [OpenAI Launches GPT-6 Cyber After AI Helps Find 81 Firefox Flaws, 948 Linux Exploits](https://thehackernews.com/2026/11/openai-launches-gpt-6-cyber-after-ai.html)
- [Microsoft Paint RCE Fix Now Available, but Windows Update Won't Deliver It](https://thehackernews.com/2026/11/microsoft-paint-rce-fix-now-available.html)
- [Malicious Browser Extensions Could Use Claude Dispatch to Run Code on Users' Computers](https://thehackernews.com/2026/11/malicious-browser-extensions-could-use.html)
- [The Flood is Coming And The Pipes Were Already Full](https://thehackernews.com/2026/11/the-flood-is-coming-and-pipes-were.html)
- [Chainalysis Breach Exposes All Users' Credentials, Forces Shutdown of Key Services](https://thehackernews.com/2026/11/chainalysis-breach-exposes-all-users.html)
- [Hackers Hide Linux Backdoor in Control Web Panel Server to Execute Commands Without Logs](https://thehackernews.com/2026/11/hackers-hide-linux-backdoor-in-control.html)
- [Experts Demonstrate Barracuda Email Security Gateway Chain Enabling Root Access Without Login](https://thehackernews.com/2026/11/experts-demonstrate-barracuda-email.html)

### BleepingComputer
- [SonicWall warns of new SSL-VPN MFA bypass flaw exploited in attacks](https://www.bleepingcomputer.com/news/security/sonicwall-warns-of-new-ssl-vpn-mfa-bypass-flaw-exploited-in-attacks/)
- [Runaway AI hacking agent behind WorkOS breach after escaping sandbox](https://www.bleepingcomputer.com/news/security/runaway-ai-hacking-agent-behind-workos-breach-after-escaping-sandbox/)
- [OpenAI's new GPT-6 Cyber AI finds 81 Firefox flaws, 948 Linux bugs](https://www.bleepingcomputer.com/news/security/openais-new-gpt-6-cyber-ai-finds-81-firefox-flaws-948-linux-bugs/)
- [Fake security tools on GitHub push backdoors and infostealers](https://www.bleepingcomputer.com/news/security/fake-security-tools-on-github-push-backdoors-and-infostealers/)
- [QNAP says hackers breaching NAS devices in Plex2Shell attacks](https://www.bleepingcomputer.com/news/security/qnap-says-hackers-breaching-nas-devices-in-plex2shell-attacks/)
- [Veeam warns of Software Appliance boot failures on AMD EPYC hosts](https://www.bleepingcomputer.com/news/security/veeam-software-appliance-vms-fail-to-boot-on-amd-epyc-hosts/)
- [IMSI vs IMEI: What Your Phone Broadcasts and Who Can Read It](https://www.bleepingcomputer.com/news/security/imsi-vs-imei-what-your-phone-broadcasts-and-who-can-read-it/)
- [Chainalysis says breach exposed credentials for all customers](https://www.bleepingcomputer.com/news/security/chainalysis-says-breach-exposed-credentials-for-all-customers/)
- [D-Link warns of multiple zero-days in DGS-3130 Series switches](https://www.bleepingcomputer.com/news/security/d-link-warns-of-multiple-zero-days-in-dgs-3130-series-switches/)
- [MetaMask says recent attack didn't affect wallet infrastructure](https://www.bleepingcomputer.com/news/security/metamask-says-recent-attack-didnt-affect-wallet-infrastructure/)
- [FBI, CISA warn of cyberattacks targeting refrigeration systems](https://www.bleepingcomputer.com/news/security/fbi-cisa-warn-of-cyberattacks-targeting-refrigeration-systems/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [UK Wades Into Tech Sovereignty Amid AI Policy Changes](https://www.darkreading.com/cybersecurity-operations/uk-tech-sovereignty-ai-policy)
- [AI Gave Your Incident Archive a Second Job](https://www.darkreading.com/cyber-risk/ai-gave-your-incident-archive-second-job)
- [Why Europe's Freezer Hacks Spread So Far, So Fast](https://www.darkreading.com/ics-ot-security/europes-freezer-hacks-spread-so-far-so-fast)
- [UK Warns Its Critical Infrastructure Faces Grave Risk](https://www.darkreading.com/cybersecurity-operations/uk-warns-critical-infrastructure-grave-risk)
- [Operação de influência russa tem como alvo generalizado a América Latina](https://www.darkreading.com/cyberattacks-data-breaches/opera-o-de-influ-ncia-russa-tem-como-alvo-generalizado-a-am-rica-latina)

### SecurityWeek
- [Japan Announces Emergency Cybersecurity Package Following a Wave of Attacks](https://www.securityweek.com/japan-announces-emergency-cybersecurity-package-following-a-wave-of-attacks/)
- [In Other News: Trezor Implant, LLMJacking Bills Hit $1M, SAP Flaws Weaponized Within Days](https://www.securityweek.com/in-other-news-trezor-implant-llmjacking-bills-hit-1m-sap-flaws-weaponized-within-days/)
- [DigiCert Data Breach Impacts Business Customer Information](https://www.securityweek.com/digicert-data-breach-impacts-business-customer-information/)
- [OpenAI Says New GPT-6 Cyber Model Hunts Flaws Without Crossing the Line](https://www.securityweek.com/openai-says-new-gpt-6-cyber-model-hunts-flaws-without-crossing-the-line/)
- [US Agencies Urge Organizations to Harden Refrigeration Controllers](https://www.securityweek.com/us-agencies-urge-organizations-to-harden-refrigeration-controllers/)
- [Grocery Giant Ahold Delhaize Estimates Financial Toll of October Cyberattack](https://www.securityweek.com/grocery-giant-ahold-delhaize-estimates-financial-toll-of-october-cyberattack/)
- [Researchers Find Residential Proxies on White House Network](https://www.securityweek.com/researchers-find-residential-proxies-on-white-house-network/)
- [OpenSSH Rushes Patches for ‘SSHole’ Authentication Bypass](https://www.securityweek.com/openssh-rushes-patches-for-sshole-authentication-bypass/)
- [OpenAI Model Wrote Its Own Network Code to Get Around Sandbox Restrictions](https://www.securityweek.com/openai-model-wrote-its-own-network-code-to-get-around-sandbox-restrictions/)
- [3 Charged in Scheme to Use AI to Impersonate CEOs and Attorneys to Steal $129 Million](https://www.securityweek.com/3-charged-in-scheme-to-use-ai-to-impersonate-ceos-and-attorneys-to-steal-129-million/)

### The Record
- [Medical services company settles with 4 states over 2023 hack of sensitive patient records](https://therecord.media/medical-services-company-settles-with-4-state-ags)
- [Certificate authority DigiCert reports data breach involving business customer info](https://therecord.media/digicert-certificate-authority-reports-data-breach)
- [FBI agent pleads guilty to stealing $2.4 million in crypto from nation-state hackers](https://therecord.media/fbi-agent-pleads-guilty-to-stealing-from-nation-state-hackers)
- [CEO-spoofing scammers used AI to help steal more than $100 million, feds say](https://therecord.media/ceo-spoofing-scammers-charged)
- [EU accuses TikTok of trapping users in harmful ‘rabbit holes’](https://therecord.media/eu-accuses-tiktok-of-rabbit-hole-DSA-violation)

### Infosecurity Magazine
- [ARTEX Offensive AI Tool Activity Far Exceeds Reported Campaigns, Censys Finds](https://www.infosecurity-magazine.com/news/artex-activity-exceeds-reported/)
- [CISA, FBI Urge Action to Protect Industrial Refrigeration Networks](https://www.infosecurity-magazine.com/news/cisa-protect-refrigeration-networks/)
- [Half of Security Leaders Report Sensitive Data Exposure Through AI Tools](https://www.infosecurity-magazine.com/news/security-data-exposure-ai/)

### CyberScoop
- [Authorities accuse trio of using AI deepfakes to defraud $129M from businesses](https://cyberscoop.com/ai-deepfakes-impersonate-ceo-lawyer-defraud-companies/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
- [Turning Up the Heat: Inside the Attacks on Europe’s Refrigeration System](https://unit42.paloaltonetworks.com/europes-refrigeration-systems-attacks/)

### Microsoft Security Blog
- [ARTEX abuse expands as cybercriminals target financial sector](https://www.microsoft.com/en-us/security/blog/2026/11/06/artex-abuse-expands-as-cybercriminals-target-financial-sector/)
- [Threat actors use agentic AI tooling to find and abuse exposed secrets](https://www.microsoft.com/en-us/security/blog/2026/11/05/threat-actors-use-agentic-ai-tooling-to-find-and-abuse-exposed-secrets/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Friday, November 6th, 2026 https://isc.sans.edu/podcastdetail/10168, (Fri, Nov 6th)](https://isc.sans.edu/diary/rss/33494)

### Securelist (Kaspersky)
- [Virtualization security: attack layers and misconfiguration impact](https://securelist.com/virtualization-security-esxi-and-proxmox-ransomware-cases/121819/)

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