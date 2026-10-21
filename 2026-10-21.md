# Winjit Daily TI Digest — 2026-10-21

_Auto-generated. Window: last ~24h. Fetched at 2026-10-21T08:24:44.990679+00:00Z_

**At a glance:** 6 new KEV · 542 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-106931 | EG Secure Solutions | SiteGuard Server Edition | EG Secure Solutions SiteGuard Server Edition OS Command Injection Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-96656 | Plex | Media Server | Plex Media Server External Control of File Name or Path Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-96655 | Plex | Media Server | Plex Media Server Server-Side Request Forgery (SSRF) Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-96654 | Plex | Media Server | Plex Media Server Improper Neutralization of Encoded URI Schemes in a Web Page Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-96652 | Plex | Media Server | Plex Media Server Server-Side Request Forgery (SSRF) Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-110936 | Siemens | Software Center | Siemens Software Center Uncontrolled Search Path Element Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-101809 | 10.0 | n/a | Vulnerability in the Workflow product of Oracle E-Business Suite (component: Workflow Notification Mailer).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability a |
| CVE-2026-81212 | 10.0 | n/a | IBM DataStage on Cloud Pak for Data 5.4.0.0 allows an unauthenticated user to perform an arbitrary write into shared Redis under any tenant's key. This collapses the platform's credential-encryption b |
| CVE-2026-87337 | 10.0 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploita |
| CVE-2026-91216 | 10.0 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91221 | 10.0 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91231 | 10.0 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Adapters).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerability  |
| CVE-2026-91299 | 10.0 | n/a | Vulnerability in the JD Edwards EnterpriseOne Orchestrator product of Oracle JD Edwards (component: E1 IOT Orchestrator Security).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily ex |
| CVE-2026-113744 | 10.0 | n/a | A security vulnerability has been detected in Tenda AC19 16.03.10.07. The impacted element is the function formSetFirewallCfg of the file /goform/SetFirewallCfg of the component httpd Web Management S |
| CVE-2026-113390 | 9.9 | n/a | A flaw has been found in DrayTek Vigor2960 1.5.1.6 Revision 8218. Affected by this issue is the function sub_182B0 of the file /cgi-bin/mainfunction.cgi of the component CGI Interface. This manipulati |
| CVE-2026-113678 | 9.9 | n/a | Froxlor before 2.3.15 contains a symlink following vulnerability in Statistics::makeChownWithNewStats that allows authenticated customers to take ownership of arbitrary host directories by abusing the |
| CVE-2026-101446 | 9.9 | n/a | Vulnerability in the Siebel CRM Cloud Applications product of Oracle Siebel CRM (component: Siebel Cloud Manager).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability |
| CVE-2026-101501 | 9.9 | n/a | Vulnerability in Oracle Trusted Answer Search (component: PLSQL package).   The supported version that is affected is 26.1. Easily exploitable vulnerability allows low privileged attacker with network |
| CVE-2026-101503 | 9.9 | n/a | Vulnerability in Oracle Trusted Answer Search (component: PLSQL package).   The supported version that is affected is 26.1. Easily exploitable vulnerability allows low privileged attacker with network |
| CVE-2026-101528 | 9.9 | n/a | Vulnerability in the Oracle Enterprise Manager for Oracle Database product of Oracle Enterprise Manager (component: Data Guard Management).  Supported versions that are affected are 13.5 and  24.1. Ea |
| CVE-2026-101529 | 9.9 | n/a | Vulnerability in the Oracle Enterprise Manager for Oracle Database product of Oracle Enterprise Manager (component: Data Guard Management).  Supported versions that are affected are 13.5 and  24.1. Ea |
| CVE-2026-91222 | 9.9 | n/a | Vulnerability in the Oracle Business Process Management Suite product of Oracle Fusion Middleware (component: Human Workflow (11g+)).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0 |
| CVE-2026-91224 | 9.9 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91232 | 9.9 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91250 | 9.9 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Adapters).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerability  |
| CVE-2026-91251 | 9.9 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Adapters).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerability  |
| CVE-2026-91354 | 9.9 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Clean Content SDK).   The supported version that is affected is 8.5.8. Easily exploitable v |
| CVE-2026-91637 | 9.9 | n/a | Vulnerability in Oracle Essbase (component: Security).   The supported version that is affected is 21.8.3.0.0. Easily exploitable vulnerability allows low privileged attacker with network access via H |
| CVE-2026-91638 | 9.9 | n/a | Vulnerability in Oracle Essbase (component: Security).   The supported version that is affected is 21.8.3.0.0. Easily exploitable vulnerability allows low privileged attacker with network access via H |
| CVE-2026-91658 | 9.9 | n/a | Vulnerability in Oracle Essbase (component: Security).   The supported version that is affected is 21.8.3.0.0. Easily exploitable vulnerability allows low privileged attacker with network access via H |
| CVE-2026-91663 | 9.9 | n/a | Vulnerability in Oracle Essbase (component: Security).   The supported version that is affected is 21.8.3.0.0. Easily exploitable vulnerability allows low privileged attacker with network access via T |
| CVE-2026-113802 | 9.8 | n/a | Wavlink WL-WN530BE1-A firmware through M30BE1_V251117 contains an OS command injection vulnerability in the sub_23B54 function of the ioos binary, which passes the unsanitized file_id parameter of /pr |
| CVE-2026-101484 | 9.8 | n/a | Vulnerability in Oracle Secure Backup (component: Backup and Restore).  Supported versions that are affected are 19.1.0.0.0 and   19.1.0.1.0. Easily exploitable vulnerability allows unauthenticated at |
| CVE-2026-101499 | 9.8 | n/a | Vulnerability in the Oracle WebCenter Sites product of Oracle Fusion Middleware (component: WebCenter Sites).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable v |
| CVE-2026-101521 | 9.8 | n/a | Vulnerability in Oracle APEX (component: General).  Supported versions that are affected are 24.1.0-24.1.21, 24.2.0-24.2.20 and  26.1.0-26.1.4. Easily exploitable vulnerability allows unauthenticated  |
| CVE-2026-101537 | 9.8 | n/a | Vulnerability in the Oracle Solaris product of Oracle Systems (component: Utility).   The supported version that is affected is 11.4. Easily exploitable vulnerability allows unauthenticated attacker w |
| CVE-2026-101763 | 9.8 | n/a | Vulnerability in the Oracle Communications BRM - Elastic Charging Engine product of Oracle Communications (component: Cloud native deployment).  Supported versions that are affected are 15.0.0.0.0, 15 |
| CVE-2026-101767 | 9.8 | n/a | Vulnerability in the Oracle Application Object Library product of Oracle E-Business Suite (component: Core).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability  |
| CVE-2026-60432 | 9.8 | n/a | Vulnerability in the Oracle Solaris product of Oracle Systems (component: Image Packaging System).  Supported versions that are affected are 11.3 and  11.4. Easily exploitable vulnerability allows una |
| CVE-2026-83396 | 9.8 | n/a | Vulnerability in the Oracle Data Integrator product of Oracle Fusion Middleware (component: Console / Repository Explorer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily |
| CVE-2026-83397 | 9.8 | n/a | Vulnerability in the Oracle Data Integrator product of Oracle Fusion Middleware (component: Console / Repository Explorer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily |
| CVE-2026-83399 | 9.8 | n/a | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Core).  Supported versions that are affected are 12.2.1.4.0, 14.1.1.0.0, 14.1.2.0.0 and  15.1.1.0.0. Easily  |
| CVE-2026-87251 | 9.8 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploita |
| CVE-2026-91214 | 9.8 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91220 | 9.8 | n/a | Vulnerability in the Oracle Business Process Management Suite product of Oracle Fusion Middleware (component: Human Workflow).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Eas |
| CVE-2026-91233 | 9.8 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Enterprise Scheduling System).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploi |
| CVE-2026-91234 | 9.8 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91235 | 9.8 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91236 | 9.8 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91323 | 9.8 | n/a | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Core).  Supported versions that are affected are 12.2.1.4.0, 14.1.1.0.0, 14.1.2.0.0 and  15.1.1.0.0. Easily  |
| CVE-2026-91408 | 9.8 | n/a | Vulnerability in the Oracle Identity Manager product of Oracle Fusion Middleware (component: End User Self Service).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploi |
| CVE-2026-91491 | 9.8 | n/a | Vulnerability in the Oracle Identity Manager Connector product of Oracle Fusion Middleware (component: LDAP Gateway).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily explo |
| CVE-2026-91495 | 9.8 | n/a | Vulnerability in the Oracle WebCenter Content product of Oracle Fusion Middleware (component: Content Server).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable  |
| CVE-2026-91665 | 9.8 | n/a | Vulnerability in Oracle Essbase (component: Security).   The supported version that is affected is 21.8.3.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via  |
| CVE-2026-92559 | 9.8 | n/a | IBM App Connect Enterprise 13.0.1.0 through 13.0.8.2 could allow a remote attacker to obtain sensitive information due to binding to an unrestricted IP address. |
| CVE-2026-113736 | 9.8 | n/a | A vulnerability has been found in D-Link DHP-W610AV 1.02EUb03. The impacted element is the function login_prepare_hnap of the file etc/defnodes/defaultvalue.xml of the component HNAP Login. The manipu |
| CVE-2026-114108 | 9.8 | n/a | HKUDS Vibe-Trading from 0.1.0 before 0.1.7 contains a missing authentication vulnerability that allows unauthenticated attackers to access the FastAPI surface because require_auth() returns early when |
| CVE-2026-114119 | 9.8 | n/a | Best Practice Software Bp Premier before 1.14.1.1128 uses a hardcoded Microsoft SQL Server administrative password that is shared across all installations and cannot be changed without breaking the ap |
| CVE-2026-101420 | 9.6 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: SQR).  Supported versions that are affected are 8.61-8.63. Easily exploitable vulnerability allows low p |
| CVE-2026-87347 | 9.6 | n/a | Vulnerability in the Oracle HTTP Server product of Oracle Fusion Middleware (component: OSSL Module).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabi |
| CVE-2026-91218 | 9.6 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91243 | 9.6 | n/a | Vulnerability in the Oracle Business Process Management Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easil |
| CVE-2026-91230 | 9.3 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91622 | 9.3 | n/a | Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Product Quality Management).   The supported version that is affected is 6.2.4. Ea |
| CVE-2026-91644 | 9.3 | n/a | Vulnerability in Oracle Essbase (component: Security).   The supported version that is affected is 21.8.3.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via  |
| CVE-2026-10131 | 9.1 | n/a | An OS command injection vulnerability exists in the boa formPasswordSetup functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP request can lead to a |
| CVE-2026-10132 | 9.1 | n/a | A stack-based buffer overflow vulnerability exists in the boa formIpQos mac functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP request can lead to |
| CVE-2026-10133 | 9.1 | n/a | A stack-based buffer overflow vulnerability exists in the batchupg functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP request can lead to arbitrar |
| CVE-2026-10135 | 9.1 | n/a | A OS command injection vulnerability exists in the batchupg functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP request can lead to arbitrary code  |
| CVE-2026-10136 | 9.1 | n/a | A heap-based buffer overflow vulnerability exists in the boa formUpload() functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP request can lead to a |
| CVE-2026-10137 | 9.1 | n/a | A stack-based buffer overflow vulnerability exists in the boa formUpload() functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP request can lead to  |
| CVE-2026-10138 | 9.1 | n/a | A OS command injection vulnerability exists in the boa formUpload() functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP request can lead to arbitra |
| CVE-2026-10139 | 9.1 | n/a | A stack-based buffer overflow vulnerability exists in the Mcli functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP request can lead to arbitrary co |
| CVE-2026-10141 | 9.1 | n/a | A Unsigned Firmware vulnerability exists in the boa Firmware Update functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted firmware binary can lead to arbi |
| CVE-2026-28763 | 9.1 | n/a | A stack-based buffer overflow vulnerability exists in the boa formMapDelDevice hostname functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP request |
| CVE-2026-33568 | 9.1 | n/a | A OS command injection vulnerability exists in the boa formMapDelDevice macstr functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP request can lead |
| CVE-2026-35499 | 9.1 | n/a | An os command injection vulnerability exists in the boa formWsc peerRptPin functionality of Totolink X2000R TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327. A specially crafted HTTP request can lead to arbit |
| CVE-2026-40615 | 9.1 | n/a | A stack-based buffer overflow vulnerability exists in the boa formParentControl deviceName functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP requ |
| CVE-2026-40627 | 9.1 | n/a | An os command injection vulnerability exists in the boa formWsc targetAPSsid functionality of Totolink X2000R TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327. A specially crafted HTTP request can lead to arb |
| CVE-2026-41222 | 9.1 | n/a | A stack-based buffer overflow vulnerability exists in the boa formParentControl url functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP request can |
| CVE-2026-41223 | 9.1 | n/a | A stack-based buffer overflow vulnerability exists in the boa formMapDelDevice macstr functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP request c |
| CVE-2026-42019 | 9.1 | n/a | Multiple stack-based buffer overflow vulnerabilities exist in the boa formIpv6Setup pppoe functionality of Totolink X2000R TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327. A specially crafted HTTP request ca |
| CVE-2026-42020 | 9.1 | n/a | Multiple stack-based buffer overflow vulnerabilities exist in the boa formIpv6Setup pppoe functionality of Totolink X2000R TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327. A specially crafted HTTP request ca |
| CVE-2026-42021 | 9.1 | n/a | Multiple stack-based buffer overflow vulnerabilities exist in the boa formIpv6Setup static network configuration functionality of Totolink X2000R TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327. A specially  |
| CVE-2026-42022 | 9.1 | n/a | Multiple stack-based buffer overflow vulnerabilities exist in the boa formIpv6Setup static network configuration functionality of Totolink X2000R TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327. A specially  |
| CVE-2026-42023 | 9.1 | n/a | Multiple stack-based buffer overflow vulnerabilities exist in the boa formIpv6Setup static network configuration functionality of Totolink X2000R TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327. A specially  |
| CVE-2026-42024 | 9.1 | n/a | Multiple stack-based buffer overflow vulnerabilities exist in the boa formIpv6Setup static network configuration functionality of Totolink X2000R TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327. A specially  |
| CVE-2026-42025 | 9.1 | n/a | Multiple exploitable stack-based buffer overflow vulnerabilities exist in the boa formIpv6Setup dhcp_dns functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially cra |
| CVE-2026-42026 | 9.1 | n/a | Multiple exploitable stack-based buffer overflow vulnerabilities exist in the boa formIpv6Setup dhcp_dns functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially cra |
| CVE-2026-9659 | 9.1 | n/a | Multiple exploitable stack-based buffer overflow vulnerabilities exist in the boa formFilter functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP re |
| CVE-2026-9660 | 9.1 | n/a | Multiple exploitable stack-based buffer overflow vulnerabilities exist in the boa formFilter functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP re |
| CVE-2026-9814 | 9.1 | n/a | An OS command injection vulnerability exists in the boa formWizard newPass functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP request can lead to  |
| CVE-2026-9817 | 9.1 | n/a | A stack-based buffer overflow vulnerability exists in the boa formUploadFile functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP request can lead t |
| CVE-2026-9827 | 9.1 | n/a | A arbitrary file write vulnerability exists in the boa formUploadFile functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP request can lead to arbit |
| CVE-2026-9869 | 9.1 | n/a | A stack-based buffer overflow vulnerability exists in the boa formTR069Config functionality of X2000R (version(s): TOTOLINK-X2000R-Gh-V1.0.0-B20250421.1327). A specially crafted HTTP request can lead  |
| CVE-2026-101590 | 9.1 | n/a | Vulnerability in the Helidon product of Oracle Fusion Middleware (component: helidon-microprofile-security).  Supported versions that are affected are 4.0.0-4.5.5. Easily exploitable vulnerability all |
| CVE-2026-101634 | 9.1 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulne |
| CVE-2026-101765 | 9.1 | n/a | Vulnerability in the Oracle Communications Billing and Revenue Management product of Oracle Communications (component: BRM Server).  Supported versions that are affected are 15.0.0.0.0, 15.0.1.0.0, 15 |
| CVE-2026-101808 | 9.1 | n/a | Vulnerability in the Oracle Product Workbench product of Oracle E-Business Suite (component: WebUI).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows u |
| CVE-2026-87302 | 9.1 | n/a | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Core).  Supported versions that are affected are 12.2.1.4.0, 14.1.1.0.0, 14.1.2.0.0 and  15.1.1.0.0. Easily  |
| CVE-2026-91225 | 9.1 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Adapters).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerability  |
| CVE-2026-91241 | 9.1 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: Analytics Web Administration).  Supported versions that are affected are 8.2.0.0.0, 12.2.1. |
| CVE-2026-91265 | 9.1 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Enterprise Infrastructure SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploita |
| CVE-2026-91305 | 9.1 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Installation Security).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vuln |
| CVE-2026-91341 | 9.1 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Clean Content SDK).   The supported version that is affected is 8.5.8. Easily exploitable v |
| CVE-2026-91490 | 9.1 | n/a | Vulnerability in the Oracle Identity Manager Connector product of Oracle Fusion Middleware (component: LDAP Gateway).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily explo |
| CVE-2026-91624 | 9.1 | n/a | Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Product Quality Management).   The supported version that is affected is 6.2.4. Ea |
| CVE-2026-91655 | 9.1 | n/a | Vulnerability in Oracle Essbase (component: Security).   The supported version that is affected is 21.8.3.0.0. Easily exploitable vulnerability allows low privileged attacker with network access via H |
| CVE-2026-91656 | 9.1 | n/a | Vulnerability in Oracle Essbase (component: Federated Partitions).   The supported version that is affected is 21.8.3.0.0. Easily exploitable vulnerability allows low privileged attacker with network  |
| CVE-2026-105949 | 8.8 | n/a | Cruise Control's Jetty ConstraintSecurityHandler registers security constraints on exact path specs without a catch-all wildcard constraint and without calling setDenyUncoveredHttpMethods(true). The s |
| CVE-2026-100134 | 8.8 | n/a | Acrobat for Edge is affected by an out-of-bounds write vulnerability that could result in arbitrary code execution in the context of the current user. Exploitation of this issue requires user interact |
| CVE-2026-101457 | 8.8 | n/a | Vulnerability in the Siebel Apps - Life Sciences product of Oracle Siebel CRM (component: eDetailing).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows low  |
| CVE-2026-101481 | 8.8 | n/a | Vulnerability in Oracle Secure Backup (component: Device Management and Support).  Supported versions that are affected are 19.1.0.0.0 and   19.1.0.1.0. Easily exploitable vulnerability allows low pri |
| CVE-2026-101495 | 8.8 | n/a | Vulnerability in the Siebel CRM Development product of Oracle Siebel CRM (component: Siebel Approval Manager).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability all |
| CVE-2026-101518 | 8.8 | n/a | Vulnerability in the Oracle Enterprise Manager Base Platform product of Oracle Enterprise Manager (component: Agent Next Gen).  Supported versions that are affected are 13.5 and  24.1. Easily exploita |
| CVE-2026-101525 | 8.8 | n/a | Vulnerability in the Oracle Enterprise Manager for Siebel product of Oracle Enterprise Manager (component: Configuration Management).  Supported versions that are affected are 13.5 and  24.1. Easily e |
| CVE-2026-101526 | 8.8 | n/a | Vulnerability in the Oracle Enterprise Manager for Siebel product of Oracle Enterprise Manager (component: Configuration Management).  Supported versions that are affected are 13.5 and  24.1. Easily e |
| CVE-2026-101542 | 8.8 | n/a | Vulnerability in the Oracle Capacity product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability all |
| CVE-2026-101557 | 8.8 | n/a | Vulnerability in the Oracle Purchasing product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability a |
| CVE-2026-101567 | 8.8 | n/a | Vulnerability in the Oracle Cost Management product of Oracle E-Business Suite (component: Cost Planning).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability al |
| CVE-2026-101594 | 8.8 | n/a | Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Product Quality Management).   The supported version that is affected is 6.2.4. Ea |
| CVE-2026-101596 | 8.8 | n/a | Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Product Quality Management).   The supported version that is affected is 6.2.4. Ea |
| CVE-2026-101635 | 8.8 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulne |
| CVE-2026-101653 | 8.8 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulne |
| CVE-2026-101654 | 8.8 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulne |
| CVE-2026-101655 | 8.8 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulne |
| CVE-2026-101656 | 8.8 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulne |
| CVE-2026-101664 | 8.8 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulne |
| CVE-2026-101685 | 8.8 | n/a | Vulnerability in the Oracle E-Business Suite Integrated SOA Gateway product of Oracle E-Business Suite (component: SOA Provider).  Supported versions that are affected are 12.2.3-12.2.15. Easily explo |
| CVE-2026-101686 | 8.8 | n/a | Vulnerability in the Oracle E-Business Suite Integrated SOA Gateway product of Oracle E-Business Suite (component: SOA Provider).  Supported versions that are affected are 12.2.3-12.2.15. Easily explo |
| CVE-2026-101692 | 8.8 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Admin UI).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability al |
| CVE-2026-101742 | 8.8 | n/a | Vulnerability in the Oracle Applications Manager product of Oracle E-Business Suite (component: Diagnostics).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability |
| CVE-2026-101781 | 8.8 | n/a | Vulnerability in the MySQL Server, MySQL Cluster product of Oracle MySQL (component: Server: Group Replication GCS).  Supported versions that are affected are MySQL Server: 8.4.0-8.4.12, 9.7.0-9.7.3,  |
| CVE-2026-101813 | 8.8 | n/a | Vulnerability in the Oracle Engineering product of Oracle E-Business Suite (component: Change Management).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability al |
| CVE-2026-101842 | 8.8 | n/a | Vulnerability in the Strategic Network Optimization product of Oracle E-Business Suite (component: Installation of SNO).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vu |
| CVE-2026-101852 | 8.8 | n/a | Vulnerability in the Oracle Product Hub product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability  |
| CVE-2026-101853 | 8.8 | n/a | Vulnerability in the Oracle Product Hub product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability  |
| CVE-2026-101854 | 8.8 | n/a | Vulnerability in the Oracle Product Hub product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability  |
| CVE-2026-47025 | 8.8 | n/a | Vulnerability in the Oracle Solaris product of Oracle Systems (component: Utility).  Supported versions that are affected are 11.3 and  11.4. Easily exploitable vulnerability allows low privileged att |
| CVE-2026-76587 | 8.8 | n/a | IBM Planning Analytics 2.0 and 2.1 are vulnerable to a stack-based buffer overflow, caused by improper bounds checking. An attacker could overflow the buffer and execute arbitrary code on the system. |
| CVE-2026-83363 | 8.8 | n/a | Vulnerability in the Oracle Contract Lifecycle Management for Public Sector product of Oracle E-Business Suite (component: Award/PO).  Supported versions that are affected are 12.2.3-12.2.15. Easily e |
| CVE-2026-83402 | 8.8 | n/a | Vulnerability in the Oracle Identity Manager product of Oracle Fusion Middleware (component: OIM Legacy UI).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploitable vu |
| CVE-2026-83403 | 8.8 | n/a | Vulnerability in the Oracle Identity Manager product of Oracle Fusion Middleware (component: OIM Legacy UI).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploitable vu |
| CVE-2026-87263 | 8.8 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: Analytics Server).  Supported versions that are affected are 8.2.0.0.0 and  26.01.0.0.0. Ea |
| CVE-2026-87310 | 8.8 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Database and Comm SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vuln |
| CVE-2026-87313 | 8.8 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Interoperability SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vulne |
| CVE-2026-87351 | 8.8 | n/a | Vulnerability in Oracle GoldenGate (component: Admin Server Executable).  Supported versions that are affected are 19.1.0.0.0-19.32.0.0,   21.3-21.23 and   23.4-23.26.3.0.0. Easily exploitable vulnera |
| CVE-2026-87359 | 8.8 | n/a | Vulnerability in the Oracle Service Bus product of Oracle Fusion Middleware (component: Core).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerability al |
| CVE-2026-87364 | 8.8 | n/a | Vulnerability in the Oracle Service Bus product of Oracle Fusion Middleware (component: Core).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerability al |
| CVE-2026-87397 | 8.8 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Core).   The supported version that is affected is 8.5.8. Easily exploitable vulnerability  |
| CVE-2026-87419 | 8.8 | n/a | Vulnerability in the Oracle Service Bus product of Oracle Fusion Middleware (component: Core).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerability al |
| CVE-2026-87420 | 8.8 | n/a | Vulnerability in the Oracle Service Bus product of Oracle Fusion Middleware (component: Core).   The supported version that is affected is 14.1.2.0.0. Easily exploitable vulnerability allows low privi |
| CVE-2026-91213 | 8.8 | n/a | Vulnerability in the Oracle Business Process Management Suite product of Oracle Fusion Middleware (component: BPM Composer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easil |
| CVE-2026-91215 | 8.8 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91223 | 8.8 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91239 | 8.8 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91259 | 8.8 | n/a | Vulnerability in the Oracle Identity Manager product of Oracle Fusion Middleware (component: OIM Legacy UI).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploitable vu |
| CVE-2026-91268 | 8.8 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Web Runtime SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vulnerabil |
| CVE-2026-91270 | 8.8 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Monitoring and Diagnostics SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploit |
| CVE-2026-91295 | 8.8 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Enterprise Infrastructure SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploita |
| CVE-2026-91296 | 8.8 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Enterprise Infrastructure SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploita |
| CVE-2026-91303 | 8.8 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Installation Security).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vuln |
| CVE-2026-91310 | 8.8 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Installation SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vulnerabi |
| CVE-2026-91326 | 8.8 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Installation Security).  Supported versions that are affected are 9.2.0.0-9.2.26.4. Easily exploitable vuln |
| CVE-2026-91340 | 8.8 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Clean Content SDK).   The supported version that is affected is 8.5.8. Easily exploitable v |
| CVE-2026-91407 | 8.8 | n/a | Vulnerability in the Oracle Identity Manager product of Oracle Fusion Middleware (component: REST WebServices).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploitable |
| CVE-2026-91442 | 8.8 | n/a | Vulnerability in the Siebel CRM Deployment product of Oracle Siebel CRM (component: Server Infrastructure).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows |
| CVE-2026-91478 | 8.8 | n/a | Vulnerability in the PeopleSoft Enterprise SCM Strategic Sourcing product of Oracle PeopleSoft (component: Strategic Sourcing).   The supported version that is affected is 9.2. Easily exploitable vuln |
| CVE-2026-91499 | 8.8 | n/a | Vulnerability in the RDBMS component of Oracle Database Server.  Supported versions that are affected are 23.4.0-23.26.3. Easily exploitable vulnerability allows low privileged attacker having DBMS_VE |
| CVE-2026-91520 | 8.8 | n/a | Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Product Quality Management).   The supported version that is affected is 6.2.4. Ea |
| CVE-2026-91521 | 8.8 | n/a | Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Product Quality Management).   The supported version that is affected is 6.2.4. Ea |
| CVE-2026-91527 | 8.8 | n/a | Vulnerability in the Oracle ZFS Storage Appliance Kit product of Oracle Systems (component: Core).   The supported version that is affected is 8.8. Easily exploitable vulnerability allows low privileg |
| CVE-2026-91532 | 8.8 | n/a | Vulnerability in the Oracle Applications Manager product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulne |
| CVE-2026-91535 | 8.8 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: BI Search).  Supported versions that are affected are 8.2.0.0.0, 12.2.1.4.0 and  26.01.0.0. |
| CVE-2026-91550 | 8.8 | n/a | Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Product Quality Management).   The supported version that is affected is 6.2.4. Ea |
| CVE-2026-91563 | 8.8 | n/a | Vulnerability in the Oracle OLAP component of Oracle Database Server.  Supported versions that are affected are 19.3-19.32, 21.3-21.23 and  23.4.0-23.26.3. Easily exploitable vulnerability allows low  |
| CVE-2026-91579 | 8.8 | n/a | Vulnerability in the Oracle BI Publisher product of Oracle Analytics (component: BI Platform Security).  Supported versions that are affected are 8.2.0.0.0, 12.2.1.4.0 and  26.01.0.0.0. Easily exploit |
| CVE-2026-91610 | 8.8 | n/a | Vulnerability in Oracle REST Data Services (component: General).  Supported versions that are affected are 24.2.0-26.2.2. Easily exploitable vulnerability allows low privileged attacker with network a |
| CVE-2026-91668 | 8.8 | n/a | Vulnerability in the Oracle Data Integrator product of Oracle Fusion Middleware (component: Dictionary Repository).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploit |
| CVE-2026-114045 | 8.8 | n/a | FreeRDP before 3.32.1 contains a heap-based buffer overflow in the server-side rdpsnd channel because an integer wraparound in rdpsnd_server_select_format() DVI_ADPCM block-alignment arithmetic bypass |
| CVE-2026-114089 | 8.8 | n/a | Trigger.dev before 4.5.2 contains a cross-site request forgery vulnerability in the CLI authorization-code flow because loading /account/authorization-code/<code> mints a Personal Access Token without |
| CVE-2026-114094 | 8.8 | n/a | Dulwich before 1.2.9 fails to validate DOS drive letter prefixes in Git tree path elements on Windows, allowing arbitrary file write. Attackers can craft a malicious repository with a tree entry named |
| CVE-2026-114107 | 8.8 | n/a | HKUDS Vibe-Trading from 0.1.0 before 0.1.7 contains an indirect prompt injection vulnerability that allows remote attackers to execute shell commands as root by planting instructions in documents or w |
| CVE-2026-114109 | 8.8 | n/a | uv before 0.11.15 contains a path traversal vulnerability that allows malicious wheels to write files outside the scripts directory via crafted console_scripts or gui_scripts entry point names. Attack |
| CVE-2026-82814 | 8.8 | n/a | The Duplicator and Duplicator Pro plugins for WordPress are vulnerable to PHP Object Injection in all versions up to, and including, 1.5.17 and 4.6.10, respectively, via deserialization of untrusted d |
| CVE-2026-101431 | 8.7 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Test Framework).  Supported versions that are affected are 8.61-8.63. Easily exploitable vulnerability a |
| CVE-2026-101451 | 8.7 | n/a | Vulnerability in the Siebel Life Sciences product of Oracle Siebel CRM (component: Web UI).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows low privileged  |
| CVE-2026-101505 | 8.7 | n/a | Vulnerability in Oracle Trusted Answer Search (component: Application expert UI).   The supported version that is affected is 26.1. Easily exploitable vulnerability allows low privileged attacker with |
| CVE-2026-101824 | 8.7 | n/a | Vulnerability in the Document Management and Collaboration product of Oracle E-Business Suite (component: Attachments).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vul |
| CVE-2026-83379 | 8.7 | n/a | Vulnerability in the Oracle Weblogic Server Proxy Plug-in product of Oracle Fusion Middleware (component: WebLogic Server Proxy Plug-In for Third-Party Web Servers).  Supported versions that are affec |
| CVE-2026-83426 | 8.7 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Difficult to ex |
| CVE-2026-87300 | 8.7 | n/a | Vulnerability in the Oracle Weblogic Server Proxy Plug-in product of Oracle Fusion Middleware (component: WebLogic Server Proxy Plug-In for Third-Party Web Servers).  Supported versions that are affec |
| CVE-2026-87346 | 8.7 | n/a | Vulnerability in the Oracle HTTP Server product of Oracle Fusion Middleware (component: Oracle Weblogic Server Proxy Plug-in for Oracle HTTP Server).  Supported versions that are affected are 12.2.1.4 |
| CVE-2026-87408 | 8.7 | n/a | Vulnerability in the Oracle Applications Framework product of Oracle E-Business Suite (component: Personalization).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnera |
| CVE-2026-91211 | 8.7 | n/a | Vulnerability in the Oracle Identity Manager Connector product of Oracle Fusion Middleware (component: Connectors and Connector Server).  Supported versions that are affected are 12.2.1.4.0 and  14.1. |
| CVE-2026-91437 | 8.7 | n/a | Vulnerability in the Siebel CRM Deployment product of Oracle Siebel CRM (component: Server Infrastructure).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows |
| CVE-2026-91492 | 8.7 | n/a | Vulnerability in the Oracle Identity Manager Connector product of Oracle Fusion Middleware (component: SAP ERP+).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Difficult to exp |
| CVE-2026-101479 | 8.6 | n/a | Vulnerability in Oracle Secure Backup (component: Backup and Restore).  Supported versions that are affected are 19.1.0.0.0 and   19.1.0.1.0. Easily exploitable vulnerability allows unauthenticated at |
| CVE-2026-101688 | 8.6 | n/a | Vulnerability in the Oracle E-Business Suite Integrated SOA Gateway product of Oracle E-Business Suite (component: SOA Provider).  Supported versions that are affected are 12.2.3-12.2.15. Easily explo |
| CVE-2026-83407 | 8.6 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploita |
| CVE-2026-87304 | 8.6 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Core).   The supported version that is affected is 8.5.8. Easily exploitable vulnerability  |
| CVE-2026-91212 | 8.6 | n/a | Vulnerability in the Oracle Identity Manager Connector product of Oracle Fusion Middleware (component: Generic REST).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily explo |
| CVE-2026-91217 | 8.6 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91219 | 8.6 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91267 | 8.6 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Interoperability SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vulne |
| CVE-2026-91273 | 8.6 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Object and Env Tech SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vu |
| CVE-2026-91343 | 8.6 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Clean Content SDK).   The supported version that is affected is 8.5.8. Easily exploitable v |
| CVE-2026-91353 | 8.6 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Clean Content SDK).   The supported version that is affected is 8.5.8. Easily exploitable v |
| CVE-2026-91534 | 8.6 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: Analytics Web General).  Supported versions that are affected are 8.2.0.0.0, 12.2.1.4.0 and |
| CVE-2026-93441 | 8.6 | n/a | IBM QRadar SIEM could allow a remote attacker to cause a denial of service due to uncontrolled resource consumption. |
| CVE-2026-101534 | 8.5 | n/a | Vulnerability in the Oracle EDI Gateway product of Oracle E-Business Suite (component: EDI).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows low privi |
| CVE-2026-83393 | 8.5 | n/a | Vulnerability in the Oracle Product Hub product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerabilit |
| CVE-2026-91347 | 8.5 | n/a | Vulnerability in the iSupport product of Oracle E-Business Suite (component: Service Requests).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows low pr |
| CVE-2026-91651 | 8.5 | n/a | Vulnerability in Oracle Essbase (component: Essbase Web Platform).   The supported version that is affected is 21.8.3.0.0. Difficult to exploit vulnerability allows low privileged attacker with networ |
| CVE-2026-91653 | 8.5 | n/a | Vulnerability in Oracle Essbase (component: Essbase Web Platform).   The supported version that is affected is 21.8.3.0.0. Easily exploitable vulnerability allows low privileged attacker with network  |
| CVE-2026-101648 | 8.4 | n/a | Vulnerability in the Oracle Partner Management product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulne |
| CVE-2026-101744 | 8.4 | n/a | Vulnerability in the Oracle Agile Engineering Data Management product of Oracle Supply Chain (component: Engineering Communication Interface).   The supported version that is affected is 6.2.1. Diffic |
| CVE-2026-87301 | 8.4 | n/a | Vulnerability in the Oracle VM VirtualBox product of Oracle Virtualization (component: Core).   The supported version that is affected is 7.2.16. Easily exploitable vulnerability allows low privileged |
| CVE-2026-87322 | 8.4 | n/a | Vulnerability in the Oracle VM VirtualBox product of Oracle Virtualization (component: Core).   The supported version that is affected is 7.2.20. Easily exploitable vulnerability allows high privilege |
| CVE-2026-91266 | 8.4 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Monitoring and Diagnostics SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploit |
| CVE-2026-91348 | 8.4 | n/a | Vulnerability in the Oracle Solaris product of Oracle Systems (component: Utility).  Supported versions that are affected are 11.3 and  11.4. Easily exploitable vulnerability allows unauthenticated at |
| CVE-2026-91355 | 8.4 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Clean Content SDK).   The supported version that is affected is 8.5.8. Easily exploitable v |
| CVE-2026-101459 | 8.3 | n/a | Vulnerability in the Siebel CRM Deployment product of Oracle Siebel CRM (component: Server Infrastructure).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows |
| CVE-2026-101593 | 8.3 | n/a | Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Product Quality Management).   The supported version that is affected is 6.2.4. Ea |
| CVE-2026-101684 | 8.3 | n/a | Vulnerability in the Oracle E-Business Suite Integrated SOA Gateway product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easil |
| CVE-2026-101785 | 8.3 | n/a | Vulnerability in the MySQL Server, MySQL Cluster product of Oracle MySQL (component: Server: JSON).  Supported versions that are affected are MySQL Server: 8.4.0-8.4.12, 9.7.0-9.7.3, 26.7.0-26.7.1; My |
| CVE-2026-91597 | 8.3 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: Platform Security).  Supported versions that are affected are 8.2.0.0.0 and  26.01.0.0.0. D |
| CVE-2026-114068 | 8.3 | n/a | Trigger.dev before 4.6.0 contains a missing authorization vulnerability in the waitpoint token wait endpoint that allows authenticated attackers to block runs belonging to other organizations. Attacke |
| CVE-2015-20128 | 8.2 | n/a | FooSun DotNetCMS 1.0 and 2.0 contains an SQL injection vulnerability that allows unauthenticated attackers to manipulate MSSQL queries through the CityId parameter. Attackers can send GET requests to  |
| CVE-2026-101458 | 8.2 | n/a | Vulnerability in the Siebel CRM Deployment product of Oracle Siebel CRM (component: Server Infrastructure).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows |
| CVE-2026-101640 | 8.2 | n/a | Vulnerability in the Oracle Marketing product of Oracle E-Business Suite (component: Audience).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows unauth |
| CVE-2026-101690 | 8.2 | n/a | Vulnerability in the Oracle E-Business Suite Integrated SOA Gateway product of Oracle E-Business Suite (component: SOA Provider).  Supported versions that are affected are 12.2.3-12.2.15. Easily explo |
| CVE-2026-101704 | 8.2 | n/a | Vulnerability in the Oracle Concurrent Processing product of Oracle E-Business Suite (component: Other).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allo |
| CVE-2026-101758 | 8.2 | n/a | Vulnerability in the Oracle Communications Billing and Revenue Management product of Oracle Communications (component: BRM Server).  Supported versions that are affected are 15.0.0.0.0, 15.0.1.0.0, 15 |
| CVE-2026-101841 | 8.2 | n/a | Vulnerability in the Global Order Promising product of Oracle E-Business Suite (component: Web Service).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability al |
| CVE-2026-83398 | 8.2 | n/a | Vulnerability in the Oracle Data Integrator product of Oracle Fusion Middleware (component: Data Transforms).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable v |
| CVE-2026-87394 | 8.2 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Core).   The supported version that is affected is 8.5.8. Easily exploitable vulnerability  |
| CVE-2026-91252 | 8.2 | n/a | Vulnerability in the Oracle Solaris product of Oracle Systems (component: Services).   The supported version that is affected is 11.4. Easily exploitable vulnerability allows unauthenticated attacker  |
| CVE-2026-91286 | 8.2 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Monitoring and Diagnostics SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploit |
| CVE-2026-91342 | 8.2 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Clean Content SDK).   The supported version that is affected is 8.5.8. Easily exploitable v |
| CVE-2026-91346 | 8.2 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Clean Content SDK).   The supported version that is affected is 8.5.8. Easily exploitable v |
| CVE-2026-91358 | 8.2 | n/a | Vulnerability in the Oracle Business Process Management Suite product of Oracle Fusion Middleware (component: Case management  Service (11g+)).  Supported versions that are affected are 12.2.1.4.0 and |
| CVE-2026-91445 | 8.2 | n/a | Vulnerability in the Siebel CRM End User product of Oracle Siebel CRM (component: Communications Panel/Dashboard).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability |
| CVE-2026-91573 | 8.2 | n/a | Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Product Quality Management).   The supported version that is affected is 6.2.4. Ea |
| CVE-2026-91625 | 8.2 | n/a | Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Product Quality Management).   The supported version that is affected is 6.2.4. Ea |
| CVE-2026-93442 | 8.2 | n/a | IBM QRadar SIEM 7.6.0.0 through 7.6.0.4, and 7.5.0 through 7.5.0 Update Package 16 Interim Fix 001 could allow a remote attacker to cause a denial of service or obtain sensitive information due to an  |
| CVE-2026-109440 | 8.1 | 0.4% | LangAlpha through 2026.09.07 contains an indirect prompt injection vulnerability that allows remote attackers to execute shell commands or Python by planting instructions in web content retrieved by t |
| CVE-2026-113613 | 8.1 | n/a | FlexGet before 3.20.7 contains a path traversal vulnerability in the decompress plugin that allows remote attackers to write arbitrary files by supplying malicious archive member paths. Attackers can  |
| CVE-2016-20101 | 8.1 | n/a | Issuu Panel plugin for WordPress before 1.6.6 contains a PHP file inclusion vulnerability that allows unauthenticated attackers to include remote or local files through the 'abspath' parameter. Attack |
| CVE-2026-101390 | 8.1 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Business Interlink).  Supported versions that are affected are 8.61-8.63. Difficult to exploit vulnerabi |
| CVE-2026-101411 | 8.1 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Business Interlink).  Supported versions that are affected are 8.61-8.63. Difficult to exploit vulnerabi |
| CVE-2026-101422 | 8.1 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Report Distribution).  Supported versions that are affected are 8.61-8.63. Easily exploitable vulnerabil |
| CVE-2026-101427 | 8.1 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Report Distribution).  Supported versions that are affected are 8.61-8.63. Easily exploitable vulnerabil |
| CVE-2026-101473 | 8.1 | n/a | Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Product Quality Management).   The supported version that is affected is 6.2.4. Di |
| CVE-2026-101498 | 8.1 | n/a | Vulnerability in Oracle Trusted Answer Search (component: PLSQL package).   The supported version that is affected is 26.1. Difficult to exploit vulnerability allows unauthenticated attacker with netw |
| CVE-2026-101665 | 8.1 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Admin UI).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability al |
| CVE-2026-101672 | 8.1 | n/a | Vulnerability in the Oracle Call Center Technology product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit v |
| CVE-2026-101700 | 8.1 | n/a | Vulnerability in the Oracle Application Object Library product of Oracle E-Business Suite (component: Core).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerabilit |
| CVE-2026-101768 | 8.1 | n/a | Vulnerability in the MySQL Connectors product of Oracle MySQL (component: Connector/J).   The supported version that is affected is 26.7.0. Difficult to exploit vulnerability allows unauthenticated at |
| CVE-2026-101770 | 8.1 | n/a | Vulnerability in the MySQL Server, MySQL Cluster product of Oracle MySQL (component: Client programs).  Supported versions that are affected are MySQL Server: 8.4.0-8.4.12, 9.7.0-9.7.3, 26.7.0-26.7.1; |
| CVE-2026-101771 | 8.1 | n/a | Vulnerability in the MySQL Server, MySQL Cluster product of Oracle MySQL (component: Client programs).  Supported versions that are affected are MySQL Server: 8.4.0-8.4.12, 9.7.0-9.7.3, 26.7.0-26.7.1; |
| CVE-2026-101772 | 8.1 | n/a | Vulnerability in the MySQL Server, MySQL Cluster product of Oracle MySQL (component: Client programs).  Supported versions that are affected are MySQL Server: 8.4.0-8.4.12, 9.7.0-9.7.3, 26.7.0-26.7.1; |
| CVE-2026-101791 | 8.1 | n/a | Vulnerability in the Oracle Communications BRM - Elastic Charging Engine product of Oracle Communications (component: Security).   The supported version that is affected is 15.2.0.0.0. Easily exploita |
| CVE-2026-101831 | 8.1 | n/a | Vulnerability in the Oracle Quality product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allo |
| CVE-2026-101834 | 8.1 | n/a | Vulnerability in the Oracle Shipping Execution product of Oracle E-Business Suite (component: Workflow Events).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerabi |
| CVE-2026-82891 | 8.1 | n/a | IBM Guardium Data Protection 12.1, and 12.2 could allow a remote attacker to obtain sensitive information due to use of a hard-coded cryptographic key. |
| CVE-2026-83361 | 8.1 | n/a | Vulnerability in the Oracle Contract Lifecycle Management for Public Sector product of Oracle E-Business Suite (component: Award/PO).  Supported versions that are affected are 12.2.3-12.2.15. Easily e |
| CVE-2026-83409 | 8.1 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Difficult to ex |
| CVE-2026-87305 | 8.1 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Enterprise Infrastructure SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Difficult to ex |
| CVE-2026-87306 | 8.1 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Interoperability SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vulne |
| CVE-2026-87309 | 8.1 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Package Build SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vulnerab |
| CVE-2026-91269 | 8.1 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Enterprise Infrastructure SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploita |
| CVE-2026-91271 | 8.1 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Monitoring and Diagnostics SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploit |
| CVE-2026-91287 | 8.1 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Enterprise Infrastructure SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploita |
| CVE-2026-91313 | 8.1 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Installation Security).  Supported versions that are affected are 9.2.0.0-9.2.26.4. Difficult to exploit vu |
| CVE-2026-91503 | 8.1 | n/a | Vulnerability in the VPD component of Oracle Database Server.  Supported versions that are affected are 19.3-19.32, 21.3-21.23 and  23.4.0-23.26.3. Easily exploitable vulnerability allows low privileg |
| CVE-2026-91506 | 8.1 | n/a | Vulnerability in the Workflow product of Oracle E-Business Suite (component: Workflow Notification Mailer).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability |
| CVE-2026-91546 | 8.1 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: BI Foundation).   The supported version that is affected is 12.2.1.4.0. Difficult to exploi |
| CVE-2026-91635 | 8.1 | n/a | Vulnerability in Oracle Essbase (component: Security).   The supported version that is affected is 21.8.3.0.0. Difficult to exploit vulnerability allows unauthenticated attacker with network access vi |
| CVE-2026-91647 | 8.1 | n/a | Vulnerability in Oracle Essbase (component: Security).   The supported version that is affected is 21.8.3.0.0. Difficult to exploit vulnerability allows unauthenticated attacker with network access vi |
| CVE-2026-114053 | 8.1 | n/a | vLLM from 0.7.3 before 0.31.0 forwards the request-supplied mm_processor_kwargs.code_revision to Transformers AutoProcessor.from_pretrained, letting clients select which revision of a model's dynamic  |
| CVE-2026-114066 | 8.1 | n/a | Trigger.dev before 4.7.0 contains a missing authorization vulnerability that allows holders of unrestricted environment API keys to block runs they do not own by supplying a foreign parentRunId to bat |
| CVE-2026-114069 | 8.1 | n/a | Trigger.dev before 4.6.0 contains an improper authorization vulnerability in the GET /api/v1/projects/:projectRef/envvars endpoint, which returns the environment's root API key as TRIGGER_SECRET_KEY f |
| CVE-2026-114078 | 8.1 | n/a | Trigger.dev before 4.5.6 contains an authorization bypass vulnerability in DeleteTaskScheduleService and SetActiveOnTaskScheduleService that allows authenticated users to delete or disable other organ |
| CVE-2026-114082 | 8.1 | n/a | Trigger.dev before 4.6.2 contains an authorization vulnerability that allows public-token holders with session write access to obtain environment-wide S2 stream credentials via session input initializ |
| CVE-2026-114083 | 8.1 | n/a | Trigger.dev before 4.5.0-rc.3 contains a path traversal vulnerability in the api/v1/packets and api/v2/packets endpoints that allows authenticated tenants to escape their object key prefix through an  |
| CVE-2026-114087 | 8.1 | n/a | Trigger.dev before 4.5.6 self-hosted Docker Compose deployments using the default secrets from hosting/docker/.env.example allow authentication bypass because the hardcoded MAGIC_LINK_SECRET lets anyo |
| CVE-2026-101438 | 8.0 | n/a | Vulnerability in the Siebel CRM Cloud Applications product of Oracle Siebel CRM (component: Siebel Cloud Manager).  Supported versions that are affected are 22.3-26.9. Difficult to exploit vulnerabili |
| CVE-2026-101602 | 8.0 | n/a | Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Product Quality Management).   The supported version that is affected is 6.2.4. Ea |
| CVE-2026-91517 | 8.0 | n/a | Vulnerability in the Oracle Management Pack for Oracle GoldenGate product of Oracle GoldenGate (component: EM Plugin).  Supported versions that are affected are 13.4.1.0.1-13.5.2.0.6. Easily exploitab |
| CVE-2026-114085 | 7.9 | n/a | Trigger.dev through 4.7.6 contains a missing authentication vulnerability in the supervisor workload server that allows workloads to manipulate runs belonging to other deployments without ownership ve |
| CVE-2026-101452 | 7.8 | n/a | Vulnerability in Oracle Autonomous Health Framework (component: AHF Instant Diagnostic Replay).  Supported versions that are affected are 26.3-26.8. Easily exploitable vulnerability allows low privile |
| CVE-2026-101477 | 7.8 | n/a | Vulnerability in Oracle Autonomous Health Framework (component: Trace File Analyzer).  Supported versions that are affected are 26.3-26.8. Easily exploitable vulnerability allows low privileged attack |
| CVE-2026-101478 | 7.8 | n/a | Vulnerability in Oracle Autonomous Health Framework (component: Trace File Analyzer).  Supported versions that are affected are 26.3-26.8. Easily exploitable vulnerability allows low privileged attack |
| CVE-2026-101482 | 7.8 | n/a | Vulnerability in Oracle Secure Backup (component: Device Management and Support).  Supported versions that are affected are 19.1.0.0.0 and   19.1.0.1.0. Easily exploitable vulnerability allows low pri |
| CVE-2026-101527 | 7.8 | n/a | Vulnerability in the Oracle Enterprise Manager Base Platform product of Oracle Enterprise Manager (component: Enterprise Manager Install).  Supported versions that are affected are 13.5 and  24.1. Eas |
| CVE-2026-101549 | 7.8 | n/a | Vulnerability in Oracle Application Testing Suite (component: OpenScript).   The supported version that is affected is 13.3.0.1. Easily exploitable vulnerability allows low privileged attacker with lo |
| CVE-2026-101566 | 7.8 | n/a | Vulnerability in the Oracle Application Object Library product of Oracle E-Business Suite (component: DB Privileges).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulne |
| CVE-2026-101598 | 7.8 | n/a | Vulnerability in the Oracle VM VirtualBox product of Oracle Virtualization (component: Core).   The supported version that is affected is 7.2.20. Easily exploitable vulnerability allows low privileged |
| CVE-2026-101676 | 7.8 | n/a | Vulnerability in the Oracle Concurrent Processing product of Oracle E-Business Suite (component: Other Issues).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerabili |
| CVE-2026-101682 | 7.8 | n/a | Vulnerability in the Applications DBA product of Oracle E-Business Suite (component: AD Utilities).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows un |
| CVE-2026-101757 | 7.8 | n/a | Vulnerability in the Oracle Application Object Library product of Oracle E-Business Suite (component: DB Privileges).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulne |
| CVE-2026-60662 | 7.8 | n/a | Vulnerability in the Oracle Solaris product of Oracle Systems (component: Services).   The supported version that is affected is 11.4. Easily exploitable vulnerability allows low privileged attacker w |
| CVE-2026-87316 | 7.8 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Enterprise Infrastructure SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploita |
| CVE-2026-87356 | 7.8 | n/a | Vulnerability in the Applications Platform Engineering product of Oracle E-Business Suite (component: Valid Session).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulne |
| CVE-2026-91253 | 7.8 | n/a | Vulnerability in the Oracle Solaris product of Oracle Systems (component: Kernel).   The supported version that is affected is 11.4. Easily exploitable vulnerability allows low privileged attacker wit |
| CVE-2026-91304 | 7.8 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Installation Security).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vuln |
| CVE-2026-91306 | 7.8 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Installation Security).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vuln |
| CVE-2026-91311 | 7.8 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Installation Security).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vuln |
| CVE-2026-91314 | 7.8 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Installation Security).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vuln |
| CVE-2026-91315 | 7.8 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Installation Security).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vuln |
| CVE-2026-91328 | 7.8 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Deployment SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vulnerabili |
| CVE-2026-91419 | 7.8 | n/a | Vulnerability in the Oracle HTTP Server product of Oracle Fusion Middleware (component: OSSL Module).   The supported version that is affected is 12.2.1.4.0. Easily exploitable vulnerability allows lo |
| CVE-2026-91457 | 7.8 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Image Export SDK).   The supported version that is affected is 8.5.8. Easily exploitable vu |
| CVE-2026-91458 | 7.8 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Core).   The supported version that is affected is 8.5.8. Easily exploitable vulnerability  |
| CVE-2026-91459 | 7.8 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Image Export SDK).   The supported version that is affected is 8.5.8. Easily exploitable vu |
| CVE-2026-91460 | 7.8 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Image Export SDK).   The supported version that is affected is 8.5.8. Easily exploitable vu |
| CVE-2026-91473 | 7.8 | n/a | Vulnerability in the Oracle HTTP Server product of Oracle Fusion Middleware (component: Web Listener).   The supported version that is affected is 12.2.1.4.0. Easily exploitable vulnerability allows l |
| CVE-2026-91483 | 7.8 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Core).   The supported version that is affected is 8.5.8. Easily exploitable vulnerability  |
| CVE-2026-91537 | 7.8 | n/a | Vulnerability in the Oracle Solaris product of Oracle Systems (component: Utility).   The supported version that is affected is 11.4. Easily exploitable vulnerability allows low privileged attacker wi |
| CVE-2026-91539 | 7.8 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: Presentation Services).   The supported version that is affected is 12.2.1.4.0. Easily expl |
| CVE-2026-91545 | 7.8 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: Platform Security).  Supported versions that are affected are 8.2.0.0.0 and  12.2.1.4.0. Ea |
| CVE-2026-91549 | 7.8 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: Analytics Server).  Supported versions that are affected are 8.2.0.0.0 and  12.2.1.4.0. Eas |
| CVE-2026-91627 | 7.8 | n/a | Vulnerability in the Oracle Communications Billing and Revenue Management product of Oracle Communications (component: Platform).  Supported versions that are affected are 15.0.0.0.0, 15.0.1.0.0, 15.1 |
| CVE-2026-93888 | 7.8 | n/a | IBM Sterling Connect Direct for Unix 6.4.0.0 through 6.4.0.6 and 6.3.0.0 through 6.3.0.7 apnotify utility is vulnerable to a code injection due to insufficient validation of user input. |
| CVE-2026-114096 | 7.8 | n/a | Dulwich from 0.24.0 before 1.2.8 contains a symlink following vulnerability in porcelain.checkout(paths=[...]) that allows attackers to write arbitrary files by abusing raw os.open without O_NOFOLLOW. |
| CVE-2026-114097 | 7.8 | n/a | Dulwich from 0.23.1 before 1.2.8 contains a path traversal vulnerability in CommitFilter._apply_index_filter() that allows attackers to write files outside the working directory via symlinks persistin |
| CVE-2026-114098 | 7.8 | n/a | Dulwich from 0.22.5 before 1.2.8 contains a path traversal vulnerability in stash.py pop() that allows attackers to write arbitrary files outside the worktree through intermediate directory symlinks.  |
| CVE-2026-105311 | 7.7 | n/a | The StreamsHub Console operator acts as a confused deputy: a Kubernetes tenant with permission to create a Console custom resource can set spec.kafkaClusters[].credentials.kafkaUser.namespace to any n |
| CVE-2026-101494 | 7.7 | n/a | Vulnerability in Oracle REST Data Services (component: Core).  Supported versions that are affected are 24.2.0-26.2.2. Easily exploitable vulnerability allows low privileged attacker with network acce |
| CVE-2026-101506 | 7.7 | n/a | Vulnerability in Oracle Trusted Answer Search (component: Application expert UI).   The supported version that is affected is 26.1. Easily exploitable vulnerability allows low privileged attacker with |
| CVE-2026-101540 | 7.7 | n/a | Vulnerability in the Oracle Capacity product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability all |
| CVE-2026-101541 | 7.7 | n/a | Vulnerability in the Oracle Capacity product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability all |
| CVE-2026-101689 | 7.7 | n/a | Vulnerability in the Oracle E-Business Suite Integrated SOA Gateway product of Oracle E-Business Suite (component: SOA Provider).  Supported versions that are affected are 12.2.3-12.2.15. Easily explo |
| CVE-2026-101705 | 7.7 | n/a | Vulnerability in the Oracle Common Applications product of Oracle E-Business Suite (component: Role Summary).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerabili |
| CVE-2026-101818 | 7.7 | n/a | Vulnerability in the Oracle Product Hub product of Oracle E-Business Suite (component: Item Catalog).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability allow |
| CVE-2026-101830 | 7.7 | n/a | Vulnerability in the Oracle Project Contracts product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerab |
| CVE-2026-101837 | 7.7 | n/a | Vulnerability in the Oracle Shipping Execution product of Oracle E-Business Suite (component: Workflow Events).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerabi |
| CVE-2026-91568 | 7.7 | n/a | Vulnerability in the RDBMS component of Oracle Database Server.  Supported versions that are affected are 23.4.0-23.26.3. Easily exploitable vulnerability allows low privileged attacker having Create  |
| CVE-2026-91632 | 7.7 | n/a | Vulnerability in Oracle Essbase (component: Security).   The supported version that is affected is 21.8.3.0.0. Easily exploitable vulnerability allows low privileged attacker with network access via H |
| CVE-2026-91636 | 7.7 | n/a | Vulnerability in Oracle Essbase (component: Security).   The supported version that is affected is 21.8.3.0.0. Easily exploitable vulnerability allows low privileged attacker with network access via H |
| CVE-2026-91639 | 7.7 | n/a | Vulnerability in Oracle Essbase (component: Security).   The supported version that is affected is 21.8.3.0.0. Easily exploitable vulnerability allows low privileged attacker with network access via H |
| CVE-2026-91659 | 7.7 | n/a | Vulnerability in Oracle Essbase (component: Build).   The supported version that is affected is 21.8.3.0.0. Easily exploitable vulnerability allows low privileged attacker with network access via HTTP |
| CVE-2026-91661 | 7.7 | n/a | Vulnerability in Oracle Essbase (component: Security).   The supported version that is affected is 21.8.3.0.0. Easily exploitable vulnerability allows low privileged attacker with network access via H |
| CVE-2026-114081 | 7.7 | n/a | Trigger.dev before 4.5.6 contains an SQL injection vulnerability in the TSQL query compiler, which concatenates window-function names into generated ClickHouse SQL without allowlisting or escaping. Au |
| CVE-2026-114084 | 7.7 | n/a | Trigger.dev before 4.5.6 contains an SQL injection vulnerability in the /realtime/v1/runs endpoint, which concatenates the unescaped tags query parameter into the ElectricSQL shape where clause and de |
| CVE-2026-101387 | 7.6 | n/a | Vulnerability in the Oracle Capacity product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability all |
| CVE-2026-101398 | 7.6 | n/a | Vulnerability in the Oracle Capacity product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability all |
| CVE-2026-101434 | 7.6 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Database Server).  Supported versions that are affected are 8.61-8.63. Easily exploitable vulnerability  |
| CVE-2026-101504 | 7.6 | n/a | Vulnerability in Oracle Trusted Answer Search (component: Application expert UI).   The supported version that is affected is 26.1. Easily exploitable vulnerability allows low privileged attacker with |
| CVE-2026-101641 | 7.6 | n/a | Vulnerability in the Oracle Report Manager product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerabili |
| CVE-2026-101815 | 7.6 | n/a | Vulnerability in the Assets product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows low p |
| CVE-2026-101833 | 7.6 | n/a | Vulnerability in the Oracle Shipping Execution product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnera |
| CVE-2026-101849 | 7.6 | n/a | Vulnerability in the Installed Base product of Oracle E-Business Suite (component: Create Item Instance).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability all |
| CVE-2012-20002 | 7.5 | n/a | TinyMCE Thumbnail Gallery plugin for WordPress before 1.1.0 contains a path traversal vulnerability that allows unauthenticated attackers to read arbitrary files via the href parameter. Attackers can  |
| CVE-2014-125133 | 7.5 | n/a | NativeChurch theme for WordPress before 1.6.2 contains a path traversal vulnerability that allows unauthenticated attackers to download arbitrary files through the file parameter of download.php. Atta |
| CVE-2014-125134 | 7.5 | n/a | ChurcHope theme for WordPress before 2.2 contains a path traversal vulnerability that allows unauthenticated attackers to download arbitrary files through the 'file' parameter of /wp-content/themes/ch |
| CVE-2015-20123 | 7.5 | n/a | Aspose Doc Exporter plugin for WordPress before 2.0 contains a path traversal vulnerability that allows unauthenticated attackers to download arbitrary files by passing unsanitized paths to readfile() |
| CVE-2015-20124 | 7.5 | n/a | Aspose Importer & Exporter plugin for WordPress before 3.0 contains a path traversal vulnerability that allows unauthenticated attackers to download arbitrary files via the unsanitized 'file' paramete |
| CVE-2015-20125 | 7.5 | n/a | Aspose PDF Exporter plugin for WordPress before 2.0 contains a path traversal vulnerability that allows unauthenticated attackers to download files through the unsanitized 'file' parameter passed to r |
| CVE-2016-20100 | 7.5 | n/a | Memphis Documents Library plugin for WordPress before 3.1.6 contains a path traversal vulnerability that allows unauthenticated attackers to read arbitrary files via the mdocs-img-preview parameter. A |
| CVE-2016-20103 | 7.5 | n/a | Cherry Plugin for WordPress before 1.2.7 contains a path traversal vulnerability that allows unauthenticated attackers to download arbitrary files via the 'file' parameter. Attackers can send GET requ |
| CVE-2016-20104 | 7.5 | n/a | EyeLock nano NXT 3.05.1193, 3.04.1108, 3.03.944, and 3.01.646 contain a path traversal vulnerability that allows unauthenticated attackers to read arbitrary files via the 'path' parameter. Attackers c |
| CVE-2026-101409 | 7.5 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Report Distribution).  Supported versions that are affected are 8.61-8.63. Easily exploitable vulnerabil |
| CVE-2026-101410 | 7.5 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Business Interlink).  Supported versions that are affected are 8.61-8.63. Difficult to exploit vulnerabi |
| CVE-2026-101416 | 7.5 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: PsAdmin).  Supported versions that are affected are 8.61-8.63. Difficult to exploit vulnerability allows |
| CVE-2026-101421 | 7.5 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: SQR).  Supported versions that are affected are 8.61-8.63. Easily exploitable vulnerability allows unaut |
| CVE-2026-101428 | 7.5 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: SQR).  Supported versions that are affected are 8.61-8.63. Difficult to exploit vulnerability allows low |
| CVE-2026-101460 | 7.5 | n/a | Vulnerability in the Siebel CRM Deployment product of Oracle Siebel CRM (component: Server Infrastructure).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows |
| CVE-2026-101461 | 7.5 | n/a | Vulnerability in the Siebel CRM Deployment product of Oracle Siebel CRM (component: Server Infrastructure).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows |
| CVE-2026-101463 | 7.5 | n/a | Vulnerability in the Siebel CRM End User product of Oracle Siebel CRM (component: UIF Open UI).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows unauthentic |
| CVE-2026-101468 | 7.5 | n/a | Vulnerability in the Siebel CRM Deployment product of Oracle Siebel CRM (component: Cloud Gateway).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows unauthe |
| CVE-2026-101469 | 7.5 | n/a | Vulnerability in the Oracle Product Lifecycle Analytics product of Oracle Supply Chain (component: Installation Issues).   The supported version that is affected is 3.6.1. Difficult to exploit vulnera |
| CVE-2026-101508 | 7.5 | n/a | Vulnerability in the Siebel CRM Integration product of Oracle Siebel CRM (component: EAI).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows unauthenticated  |
| CVE-2026-101520 | 7.5 | n/a | Vulnerability in the Oracle Global Lifecycle Management NextGen OUI Framework product of Oracle Fusion Middleware (component: NextGen Installer).  Supported versions that are affected are 12.2.1.4.0,  |
| CVE-2026-101531 | 7.5 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: Analytics Server).  Supported versions that are affected are 8.2.0.0.0 and  26.01.0.0.0. Ea |
| CVE-2026-101535 | 7.5 | n/a | Vulnerability in the Oracle Sales Foundation product of Oracle E-Business Suite (component: Security API).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability  |
| CVE-2026-101536 | 7.5 | n/a | Vulnerability in the Oracle Cost Management product of Oracle E-Business Suite (component: Cost Maintenance).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerabili |
| CVE-2026-101543 | 7.5 | n/a | Vulnerability in the Oracle Capacity product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability a |
| CVE-2026-101546 | 7.5 | n/a | Vulnerability in the Oracle Materials Requirement Planning product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to e |
| CVE-2026-101551 | 7.5 | n/a | Vulnerability in the Oracle Applications Manager product of Oracle E-Business Suite (component: Oracle Diagnostics Interfaces).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploit |
| CVE-2026-101552 | 7.5 | n/a | Vulnerability in the Oracle Application Object Library product of Oracle E-Business Suite (component: Flexfields).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulner |
| CVE-2026-101554 | 7.5 | n/a | Vulnerability in the Oracle Payroll product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability al |
| CVE-2026-101555 | 7.5 | n/a | Vulnerability in the Oracle Payroll product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability al |
| CVE-2026-101556 | 7.5 | n/a | Vulnerability in the Oracle Payroll product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability al |
| CVE-2026-101562 | 7.5 | n/a | Vulnerability in the Oracle Agile PLM product of Oracle Supply Chain (component: Acollect).   The supported version that is affected is 2.6. Easily exploitable vulnerability allows unauthenticated att |
| CVE-2026-101572 | 7.5 | n/a | Vulnerability in the Helidon product of Oracle Fusion Middleware (component: helidon-webclient-http2).  Supported versions that are affected are 4.0.0-4.5.5 and 27.0.0. Easily exploitable vulnerabilit |
| CVE-2026-101599 | 7.5 | n/a | Vulnerability in the Oracle VM VirtualBox product of Oracle Virtualization (component: Core).   The supported version that is affected is 7.2.20. Difficult to exploit vulnerability allows low privileg |
| CVE-2026-101603 | 7.5 | n/a | Vulnerability in the Oracle Communications Unified Inventory Management product of Oracle Communications (component: Security).  Supported versions that are affected are 7.5.0, 7.5.1, 7.6.0, 7.7.0, 7. |
| CVE-2026-101604 | 7.5 | n/a | Vulnerability in the Oracle Communications Unified Inventory Management product of Oracle Communications (component: Security).  Supported versions that are affected are 7.5.0, 7.5.1, 7.6.0, 7.7.0, 7. |
| CVE-2026-101645 | 7.5 | n/a | Vulnerability in the Oracle iSetup product of Oracle E-Business Suite (component: General Ledger Update Transform, Reports).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to expl |
| CVE-2026-101647 | 7.5 | n/a | Vulnerability in the Oracle iSetup product of Oracle E-Business Suite (component: General Ledger Update Transform, Reports).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to expl |
| CVE-2026-101660 | 7.5 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Admin UI).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability al |
| CVE-2026-101679 | 7.5 | n/a | Vulnerability in the MySQL Server, MySQL Cluster product of Oracle MySQL (component: Client programs).  Supported versions that are affected are MySQL Server: 8.4.0-8.4.12, 9.7.0-9.7.3, 26.7.0-26.7.1; |
| CVE-2026-101687 | 7.5 | n/a | Vulnerability in the Oracle E-Business Suite Integrated SOA Gateway product of Oracle E-Business Suite (component: SOA Provider).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to |
| CVE-2026-101698 | 7.5 | n/a | Vulnerability in the Oracle One-to-One Fulfillment product of Oracle E-Business Suite (component: Java Server Issues).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vu |
| CVE-2026-101699 | 7.5 | n/a | Vulnerability in the Oracle One-to-One Fulfillment product of Oracle E-Business Suite (component: Documents).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerabili |
| CVE-2026-101703 | 7.5 | n/a | Vulnerability in the Pasta product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability allows low  |
| CVE-2026-101708 | 7.5 | n/a | Vulnerability in the Oracle Payroll product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability al |
| CVE-2026-101712 | 7.5 | n/a | Vulnerability in the Oracle Payroll product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability al |
| CVE-2026-101719 | 7.5 | n/a | Vulnerability in the Oracle Agile PLM product of Oracle Supply Chain (component: Application Server).   The supported version that is affected is 9.3.6. Difficult to exploit vulnerability allows unaut |
| CVE-2026-101759 | 7.5 | n/a | Vulnerability in the Oracle Communications Billing and Revenue Management product of Oracle Communications (component: BRM Server).  Supported versions that are affected are 15.0.0.0.0, 15.0.1.0.0, 15 |
| CVE-2026-101796 | 7.5 | n/a | Vulnerability in the MySQL Server, MySQL Cluster product of Oracle MySQL (component: Server: Replication).  Supported versions that are affected are MySQL Server: 8.4.0-8.4.12, 9.7.0-9.7.3, 26.7.0-26. |
| CVE-2026-101797 | 7.5 | n/a | Vulnerability in the MySQL Server, MySQL Cluster product of Oracle MySQL (component: Client: mysqldump).  Supported versions that are affected are MySQL Server: 8.4.0-8.4.12, 9.7.0-9.7.3, 26.7.0-26.7. |
| CVE-2026-101810 | 7.5 | n/a | Vulnerability in the MySQL Router product of Oracle MySQL (component: Router: General).   The supported version that is affected is 26.7.0. Easily exploitable vulnerability allows unauthenticated atta |
| CVE-2026-101820 | 7.5 | n/a | Vulnerability in the Oracle General Ledger product of Oracle E-Business Suite (component: ADADMIN).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability allows  |
| CVE-2026-101823 | 7.5 | n/a | Vulnerability in the Oracle Bills of Material product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulner |
| CVE-2026-101825 | 7.5 | n/a | Vulnerability in the Oracle HCM Common Architecture product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit  |
| CVE-2026-101826 | 7.5 | n/a | Vulnerability in the Oracle HCM Common Architecture product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit  |
| CVE-2026-101835 | 7.5 | n/a | Vulnerability in the Oracle Shipping Execution product of Oracle E-Business Suite (component: Workflow Events).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerabili |
| CVE-2026-101847 | 7.5 | n/a | Vulnerability in the Oracle Bills of Material product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulner |
| CVE-2026-83370 | 7.5 | n/a | Vulnerability in the Sourcing product of Oracle E-Business Suite (component: Auctions).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability allows low privileg |
| CVE-2026-83404 | 7.5 | n/a | Vulnerability in the MySQL Connectors product of Oracle MySQL (component: Connector/Python).   The supported version that is affected is 26.7.0. Easily exploitable vulnerability allows unauthenticated |
| CVE-2026-87296 | 7.5 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploita |
| CVE-2026-87312 | 7.5 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Enterprise Infrastructure SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Difficult to ex |
| CVE-2026-87315 | 7.5 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Enterprise Infrastructure SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploita |
| CVE-2026-87363 | 7.5 | n/a | Vulnerability in the Oracle Payroll product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability al |
| CVE-2026-87369 | 7.5 | n/a | Vulnerability in the Oracle Service Bus product of Oracle Fusion Middleware (component: Core).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerability al |
| CVE-2026-87395 | 7.5 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Core).   The supported version that is affected is 8.5.8. Easily exploitable vulnerability  |
| CVE-2026-87398 | 7.5 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Core).   The supported version that is affected is 8.5.8. Easily exploitable vulnerability  |
| CVE-2026-87404 | 7.5 | n/a | Vulnerability in the Pasta product of Oracle E-Business Suite (component: Printing Engine).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability allows low priv |
| CVE-2026-87417 | 7.5 | n/a | Vulnerability in the Oracle Solaris product of Oracle Systems (component: Image Packaging System).   The supported version that is affected is 11.4. Easily exploitable vulnerability allows unauthentic |
| CVE-2026-91226 | 7.5 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Difficult to exploit vulnerab |
| CVE-2026-91227 | 7.5 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Difficult to exploit vulnerab |
| CVE-2026-91229 | 7.5 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Difficult to exploit vulnerab |
| CVE-2026-91237 | 7.5 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91254 | 7.5 | n/a | Vulnerability in the Oracle Solaris product of Oracle Systems (component: Kernel).   The supported version that is affected is 11.4. Easily exploitable vulnerability allows unauthenticated attacker wi |
| CVE-2026-91255 | 7.5 | n/a | Vulnerability in the Oracle Solaris product of Oracle Systems (component: Kernel).   The supported version that is affected is 11.4. Easily exploitable vulnerability allows unauthenticated attacker wi |
| CVE-2026-91307 | 7.5 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Installation Security).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vuln |
| CVE-2026-91308 | 7.5 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Installation Security).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vuln |
| CVE-2026-91321 | 7.5 | n/a | Vulnerability in the iProcurement product of Oracle E-Business Suite (component: Requisition Management).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability a |
| CVE-2026-91325 | 7.5 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Installation Security).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vuln |
| CVE-2026-91327 | 7.5 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Installation Security).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Difficult to exploit vu |
| CVE-2026-91344 | 7.5 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Clean Content SDK).   The supported version that is affected is 8.5.8. Easily exploitable v |
| CVE-2026-91345 | 7.5 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Clean Content SDK).   The supported version that is affected is 8.5.8. Easily exploitable v |
| CVE-2026-91349 | 7.5 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Clean Content SDK).   The supported version that is affected is 8.5.8. Easily exploitable v |
| CVE-2026-91350 | 7.5 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In Clean Content SDK).   The supported version that is affected is 8.5.8. Easily exploitable v |
| CVE-2026-91377 | 7.5 | n/a | Vulnerability in the Siebel CRM Integration product of Oracle Siebel CRM (component: Open Integration).  Supported versions that are affected are 25.12-26.9. Easily exploitable vulnerability allows un |
| CVE-2026-91405 | 7.5 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In PDF Export SDK).   The supported version that is affected is 8.5.8. Difficult to exploit vu |
| CVE-2026-91406 | 7.5 | n/a | Vulnerability in the Oracle Outside In Technology product of Oracle Fusion Middleware (component: Outside In PDF Export SDK).   The supported version that is affected is 8.5.8. Difficult to exploit vu |
| CVE-2026-91447 | 7.5 | n/a | Vulnerability in the Siebel CRM Deployment product of Oracle Siebel CRM (component: Server Infrastructure).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows |
| CVE-2026-91448 | 7.5 | n/a | Vulnerability in the Siebel CRM Deployment product of Oracle Siebel CRM (component: Server Infrastructure).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows |
| CVE-2026-91465 | 7.5 | n/a | Vulnerability in the PeopleSoft Enterprise FIN Common Objects Argentina product of Oracle PeopleSoft (component: Integration).   The supported version that is affected is 9.1. Easily exploitable vulne |
| CVE-2026-91484 | 7.5 | n/a | Vulnerability in Oracle Java SE (component: Java plugin).  Supported versions that are affected are Oracle Java SE: 8u503 and  8u503-perf. Difficult to exploit vulnerability allows low privileged atta |
| CVE-2026-91493 | 7.5 | n/a | Vulnerability in the Oracle Identity Manager Connector product of Oracle Fusion Middleware (component: LDAP Gateway).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily explo |
| CVE-2026-91496 | 7.5 | n/a | Vulnerability in the Workflow product of Oracle E-Business Suite (component: Workflow Notification Mailer).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability |
| CVE-2026-91504 | 7.5 | n/a | Vulnerability in the Oracle WebCenter Content product of Oracle Fusion Middleware (component: Content Portal Suite).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Difficult to  |
| CVE-2026-91515 | 7.5 | n/a | Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Product Quality Management).   The supported version that is affected is 6.2.4. Di |
| CVE-2026-91542 | 7.5 | n/a | Vulnerability in the Oracle WebCenter Sites product of Oracle Fusion Middleware (component: WebCenter Sites).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable v |
| CVE-2026-91552 | 7.5 | n/a | Vulnerability in the Oracle WebCenter Sites product of Oracle Fusion Middleware (component: WebCenter Sites).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable v |
| CVE-2026-91604 | 7.5 | n/a | Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Product Quality Management).   The supported version that is affected is 6.2.4. Di |
| CVE-2026-91608 | 7.5 | n/a | Vulnerability in the Oracle BI Publisher product of Oracle Analytics (component: Web Server).  Supported versions that are affected are 8.2.0.0.0, 12.2.1.4.0 and  26.01.0.0.0. Easily exploitable vulne |
| CVE-2026-91664 | 7.5 | n/a | Vulnerability in Oracle Essbase (component: Security).   The supported version that is affected is 21.8.3.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via  |
| CVE-2026-114050 | 7.5 | n/a | vLLM before 0.31.0 uses a client-supplied multimodal uuid verbatim as cache identity with no consistency check on cache hits, allowing engine crashes. Unauthenticated attackers can desynchronize the P |
| CVE-2026-114051 | 7.5 | n/a | vLLM before 0.31.0 skips the min_tokens <= max_tokens check for /inference/v1/generate requests with a null max_tokens, so the EngineCore input thread later dies on an uncaught VLLMValidationError whi |
| CVE-2026-114052 | 7.5 | n/a | vLLM after 0.24.0 and before 0.31.0 contains a memory exhaustion vulnerability in MOSS-Audio model serving that caches a processor for every distinct request-controlled mm_processor_kwargs value in an |
| CVE-2026-114055 | 7.5 | n/a | vLLM from 0.7.3 before 0.31.0 contains an uncontrolled resource consumption vulnerability that allows remote clients to control multimodal processor parameters by supplying per-request mm_processor_kw |
| CVE-2026-114059 | 7.5 | n/a | ArcadeDB before 26.10.1 contains a remote code execution vulnerability that allows authenticated users, including read-only reader role holders, to execute Groovy code because GremlinQueryEngine.comma |
| CVE-2026-114063 | 7.5 | n/a | SvelteKit (@sveltejs/kit) from 2.10.0 before 3.0.0 contains a path traversal vulnerability in the vite preview server on Windows that allows unauthenticated attackers to read files outside the prerend |
| CVE-2026-114102 | 7.5 | n/a | adm-zip before 0.6.1 contains a denial of service vulnerability that allows unauthenticated attackers to crash the Node.js process via a malformed ZIP file, because inflateAsync in methods/inflater.js |
| CVE-2026-114106 | 7.5 | n/a | HKUDS Vibe-Trading from 0.1.0 before 0.1.7 contains a path traversal vulnerability that allows remote attackers to read sensitive server files through LLM agent file-read tools. Attackers can prompt t |
| CVE-2026-113394 | 7.4 | n/a | A vulnerability was identified in DrayTek Vigor2960 1.5.1.6 Revision 8218. Impacted is the function setSWMProfile of the file /cgi-bin/mainfunction.cgi. The manipulation of the argument setSWMProfile  |
| CVE-2026-113682 | 7.4 | n/a | Networknt light-4j from 2.1.5 before 2.4.0 contains an authentication bypass vulnerability in BasicAuthHandler that allows unauthenticated attackers to log in as LDAP/AD-delegated users. Attackers can |
| CVE-2026-101467 | 7.4 | n/a | Vulnerability in the Siebel CRM End User product of Oracle Siebel CRM (component: Portal Framework).  Supported versions that are affected are 17.0-26.9. Difficult to exploit vulnerability allows unau |
| CVE-2026-101636 | 7.4 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Admin UI).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability  |
| CVE-2026-101658 | 7.4 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Admin UI).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability  |
| CVE-2026-101661 | 7.4 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Admin UI).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability  |
| CVE-2026-101680 | 7.4 | n/a | Vulnerability in the Oracle Communications Billing and Revenue Management product of Oracle Communications (component: Platform).  Supported versions that are affected are 15.0.0.0.0, 15.0.1.0.0, 15.1 |
| CVE-2026-101707 | 7.4 | n/a | Vulnerability in the Oracle Concurrent Processing product of Oracle E-Business Suite (component: Other Issues).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerabi |
| CVE-2026-101736 | 7.4 | n/a | Vulnerability in the Primavera Unifier product of Oracle Construction and Engineering (component: Core).  Supported versions that are affected are 21.12.0-21.12.17. Difficult to exploit vulnerability  |
| CVE-2026-101775 | 7.4 | n/a | Vulnerability in the MySQL Server, MySQL Cluster product of Oracle MySQL (component: Server: Replication).  Supported versions that are affected are MySQL Server: 8.4.0-8.4.12, 9.7.0-9.7.3, 26.7.0-26. |
| CVE-2026-101783 | 7.4 | n/a | Vulnerability in the MySQL Router product of Oracle MySQL (component: Router: General).   The supported version that is affected is 26.7.0. Difficult to exploit vulnerability allows unauthenticated at |
| CVE-2026-101829 | 7.4 | n/a | Vulnerability in the Oracle Mobile Application Server product of Oracle E-Business Suite (component: MWA Terminal Server).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploi |
| CVE-2026-83366 | 7.4 | n/a | Vulnerability in the Oracle Shipping Execution product of Oracle E-Business Suite (component: Workflow Events).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerabi |
| CVE-2026-83367 | 7.4 | n/a | Vulnerability in the Oracle Shipping Execution product of Oracle E-Business Suite (component: Workflow Events).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerabi |
| CVE-2026-87314 | 7.4 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Interoperability SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Difficult to exploit vul |
| CVE-2026-91242 | 7.4 | n/a | Vulnerability in the Oracle Solaris product of Oracle Systems (component: Plugins).   The supported version that is affected is 11.4. Easily exploitable vulnerability allows high privileged attacker w |
| CVE-2026-91272 | 7.4 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Interoperability SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Difficult to exploit vul |
| CVE-2026-91288 | 7.4 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Interoperability SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Difficult to exploit vul |
| CVE-2026-91337 | 7.4 | n/a | Vulnerability in the iProcurement product of Oracle E-Business Suite (component: Internal operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability allo |
| CVE-2026-91449 | 7.4 | n/a | Vulnerability in the Siebel CRM Deployment product of Oracle Siebel CRM (component: Server Infrastructure).  Supported versions that are affected are 17.0-26.9. Difficult to exploit vulnerability allo |
| CVE-2026-91450 | 7.4 | n/a | Vulnerability in the Siebel CRM Deployment product of Oracle Siebel CRM (component: Server Infrastructure).  Supported versions that are affected are 17.0-26.9. Difficult to exploit vulnerability allo |
| CVE-2026-91494 | 7.4 | n/a | Vulnerability in the Oracle Identity Manager Connector product of Oracle Fusion Middleware (component: LDAP Gateway).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Difficult to |
| CVE-2026-91623 | 7.4 | n/a | Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Product Quality Management).   The supported version that is affected is 6.2.4. Di |
| CVE-2021-48018 | 7.4 | n/a | Vyper from 0.2.13 before 0.2.15 allocates storage slots for @nonreentrant reentrancy locks at the same locations as contract storage variables. When a function using @nonreentrant is called, setting t |
| CVE-2026-101638 | 7.3 | n/a | Vulnerability in the Applications DBA product of Oracle E-Business Suite (component: AD Utilities).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows lo |
| CVE-2026-101746 | 7.3 | n/a | Vulnerability in the Oracle Agile Engineering Data Management product of Oracle Supply Chain (component: Install).   The supported version that is affected is 6.2.1. Easily exploitable vulnerability a |
| CVE-2026-113704 | 7.3 | n/a | A vulnerability has been found in a2aproject a2a-rs up to 0.4.3. This affects the function HttpPushSender of the file crates/server/src/push_notification_sender.rs of the component Push Notification H |
| CVE-2026-87402 | 7.3 | n/a | Vulnerability in the Applications DBA product of Oracle E-Business Suite (component: AD Utilities).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows lo |
| CVE-2026-91502 | 7.3 | n/a | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Core).  Supported versions that are affected are 12.2.1.4.0, 14.1.1.0.0, 14.1.2.0.0 and  15.1.1.0.0. Easily  |
| CVE-2026-91642 | 7.3 | n/a | Vulnerability in Oracle Essbase (component: Security).   The supported version that is affected is 21.8.3.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via  |
| CVE-2026-101466 | 7.2 | n/a | Vulnerability in the Oracle EDI Gateway product of Oracle E-Business Suite (component: All Miscellaneous EDI Issues).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulne |
| CVE-2026-101519 | 7.2 | n/a | Vulnerability in the Oracle EDI Gateway product of Oracle E-Business Suite (component: All Miscellaneous EDI Issues).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulne |
| CVE-2026-101532 | 7.2 | n/a | Vulnerability in the Oracle EDI Gateway product of Oracle E-Business Suite (component: All Miscellaneous EDI Issues).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulne |
| CVE-2026-101579 | 7.2 | n/a | Vulnerability in the Helidon product of Oracle Fusion Middleware (component: helidon-grpc-server).  Supported versions that are affected are 3.0.0-3.2.21. Easily exploitable vulnerability allows unaut |
| CVE-2026-101585 | 7.2 | n/a | Vulnerability in the Helidon product of Oracle Fusion Middleware (component: helidon-cors).  Supported versions that are affected are 3.0.0-3.2.21. Easily exploitable vulnerability allows unauthentica |
| CVE-2026-101646 | 7.2 | n/a | Vulnerability in the Oracle iSetup product of Oracle E-Business Suite (component: General Ledger Update Transform, Reports).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitabl |
| CVE-2026-101694 | 7.2 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Admin UI).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability al |
| CVE-2026-101786 | 7.2 | n/a | Vulnerability in the MySQL Server, MySQL Cluster product of Oracle MySQL (component: Server: Optimizer).  Supported versions that are affected are MySQL Server: 26.7.0-26.7.1; MySQL Cluster: 26.7.0-26 |
| CVE-2026-101816 | 7.2 | n/a | Vulnerability in the Oracle Product Hub product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability  |
| CVE-2026-101822 | 7.2 | n/a | Vulnerability in the Oracle Bills of Material product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulner |
| CVE-2026-101840 | 7.2 | n/a | Vulnerability in the Oracle Contract Lifecycle Management for Public Sector product of Oracle E-Business Suite (component: Award/PO).  Supported versions that are affected are 12.2.3-12.2.15. Easily e |
| CVE-2026-87357 | 7.2 | n/a | Vulnerability in the Order Capture product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allow |
| CVE-2026-91260 | 7.2 | n/a | Vulnerability in the iProcurement product of Oracle E-Business Suite (component: E-Content Manager Catalog).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability  |
| CVE-2026-91316 | 7.2 | n/a | Vulnerability in the iProcurement product of Oracle E-Business Suite (component: E-Content Manager Catalog).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability  |
| CVE-2026-91433 | 7.2 | n/a | Vulnerability in the Siebel Apps - Field Service product of Oracle Siebel CRM (component: Smart Answer).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows hi |
| CVE-2026-91512 | 7.2 | n/a | Vulnerability in the Oracle Agile Product Lifecycle Management for Process product of Oracle Supply Chain (component: Product Quality Management).   The supported version that is affected is 6.2.4. Ea |
| CVE-2026-113606 | 7.1 | n/a | Stirling-PDF 3.0.0 through 3.2.0 contains an authorization bypass vulnerability that allows authenticated users to access other users' stored files by pointing a processing folder at the server storag |
| CVE-2026-101388 | 7.1 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Portal).  Supported versions that are affected are 8.61-8.63. Easily exploitable vulnerability allows lo |
| CVE-2026-101447 | 7.1 | n/a | Vulnerability in the Siebel CRM Development product of Oracle Siebel CRM (component: Workflow).  Supported versions that are affected are 25.12-26.9. Difficult to exploit vulnerability allows low priv |
| CVE-2026-101450 | 7.1 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Integration Broker).  Supported versions that are affected are 8.61-8.63. Easily exploitable vulnerabili |
| CVE-2026-101464 | 7.1 | n/a | Vulnerability in the Siebel CRM Deployment product of Oracle Siebel CRM (component: Server Infrastructure).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows |
| CVE-2026-101560 | 7.1 | n/a | Vulnerability in the Oracle Commerce Platform product of Oracle Commerce (component: Dynamo Commerce Server).   The supported version that is affected is 11.4.0. Easily exploitable vulnerability allow |
| CVE-2026-101642 | 7.1 | n/a | Vulnerability in the Oracle Report Manager product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerabili |
| CVE-2026-101643 | 7.1 | n/a | Vulnerability in the Oracle Sales Online product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability |
| CVE-2026-101649 | 7.1 | n/a | Vulnerability in the Oracle Partner Management product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnera |
| CVE-2026-101650 | 7.1 | n/a | Vulnerability in the Oracle Partner Management product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnera |
| CVE-2026-101662 | 7.1 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Admin UI).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability al |
| CVE-2026-101735 | 7.1 | n/a | Vulnerability in the Primavera Unifier product of Oracle Construction and Engineering (component: Project Control).  Supported versions that are affected are 23.12.0-23.12.16. Easily exploitable vulne |
| CVE-2026-101773 | 7.1 | n/a | Vulnerability in the MySQL Server, MySQL Cluster product of Oracle MySQL (component: Server: Group Replication Plugin).  Supported versions that are affected are MySQL Server: 8.4.0-8.4.12, 9.7.0-9.7. |
| CVE-2026-101827 | 7.1 | n/a | Vulnerability in the Oracle HCM Common Architecture product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit  |
| CVE-2026-101851 | 7.1 | n/a | Vulnerability in the Installed Base product of Oracle E-Business Suite (component: Data Provider UI).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows  |
| CVE-2026-87307 | 7.1 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Interoperability SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploitable vulne |
| CVE-2026-87308 | 7.1 | n/a | Vulnerability in the JD Edwards EnterpriseOne Tools product of Oracle JD Edwards (component: Enterprise Infrastructure SEC).  Supported versions that are affected are 9.2.0.0-9.2.26.5. Easily exploita |
| CVE-2026-87358 | 7.1 | n/a | Vulnerability in the Oracle General Ledger product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerabi |
| CVE-2026-87403 | 7.1 | n/a | Vulnerability in the Applications DBA product of Oracle E-Business Suite (component: AD Utilities).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows lo |
| CVE-2026-87421 | 7.1 | n/a | Vulnerability in the Oracle Solaris product of Oracle Systems (component: Image Packaging System).   The supported version that is affected is 11.4. Easily exploitable vulnerability allows unauthentic |
| CVE-2026-91228 | 7.1 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91238 | 7.1 | n/a | Vulnerability in the Oracle SOA Suite product of Oracle Fusion Middleware (component: Fabric Layer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91256 | 7.1 | n/a | Vulnerability in the Oracle Solaris product of Oracle Systems (component: Services).   The supported version that is affected is 11.4. Easily exploitable vulnerability allows low privileged attacker w |
| CVE-2026-91338 | 7.1 | n/a | Vulnerability in the iSupport product of Oracle E-Business Suite (component: Internal operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows low |
| CVE-2026-91438 | 7.1 | n/a | Vulnerability in the Siebel CRM Deployment product of Oracle Siebel CRM (component: Server Infrastructure).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows |
| CVE-2026-91488 | 7.1 | n/a | Vulnerability in the Oracle Identity Manager Connector product of Oracle Fusion Middleware (component: Generic REST).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily explo |
| CVE-2026-91489 | 7.1 | n/a | Vulnerability in the Oracle Identity Manager Connector product of Oracle Fusion Middleware (component: LDAP Gateway).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily explo |
| CVE-2026-91511 | 7.1 | n/a | Vulnerability in the Oracle Purchasing product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability |
| CVE-2026-114077 | 7.1 | n/a | Trigger.dev before 4.5.6 contains an authorization bypass vulnerability in createDeploymentBackgroundWorkerV4 that resolves a WorkerDeployment by friendlyId alone, without environment, project, or org |
| CVE-2026-114090 | 7.1 | n/a | Trigger.dev cli-v3 from 3.0.0 before 4.5.4 contains a missing authentication vulnerability in the trigger dev --mcp server, which binds all network interfaces and exposes the /sse and /messages endpoi |
| CVE-2026-101429 | 7.0 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: SQR).  Supported versions that are affected are 8.61-8.63. Difficult to exploit vulnerability allows una |
| CVE-2026-101544 | 7.0 | n/a | Vulnerability in the Oracle Payroll product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability al |
| CVE-2026-101545 | 7.0 | n/a | Vulnerability in the Oracle Inventory Management product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vul |
| CVE-2026-101548 | 7.0 | n/a | Vulnerability in Oracle Application Testing Suite (component: OpenScript).   The supported version that is affected is 13.3.0.1. Difficult to exploit vulnerability allows low privileged attacker with  |
| CVE-2026-101583 | 7.0 | n/a | Vulnerability in the Helidon product of Oracle Fusion Middleware (component: helidon-common-mapper).  Supported versions that are affected are 4.0.0-4.5.5 and 27.0.0. Difficult to exploit vulnerabilit |
| CVE-2026-101681 | 7.0 | n/a | Vulnerability in the Applications DBA product of Oracle E-Business Suite (component: AD Utilities).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability allows  |
| CVE-2026-101683 | 7.0 | n/a | Vulnerability in the Applications DBA product of Oracle E-Business Suite (component: AD Utilities).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability allows  |
| CVE-2026-101739 | 7.0 | n/a | Vulnerability in the Oracle Agile Engineering Data Management product of Oracle Supply Chain (component: Engineering Communication Interface).   The supported version that is affected is 6.2.1. Diffic |
| CVE-2026-101769 | 7.0 | n/a | Vulnerability in the MySQL Cluster product of Oracle MySQL (component: Cluster: General).  Supported versions that are affected are 26.7.0-26.7.1. Difficult to exploit vulnerability allows unauthentic |
| CVE-2026-91415 | 7.0 | n/a | Vulnerability in the Oracle Java SE, Oracle GraalVM for JDK, Oracle GraalVM Enterprise Edition product of Oracle Java SE (component: 2D).  Supported versions that are affected are Oracle Java SE: 8u50 |
| CVE-2026-91557 | 7.0 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: BI Foundation).   The supported version that is affected is 12.2.1.4.0. Difficult to exploi |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-x439-gf26-v2wp | CVE-2026-96901 | unknown | The Cart Abandonment Recovery for WooCommerce  WordPress plugin before 2.2.0 does not verify the... |
| GHSA-rgvg-xc9j-2jxv | CVE-2026-93856 | medium | In OpenStack Cinder through 29.0.0, cross-project information disclosure can occur in the... |
| GHSA-q54c-xpfc-w532 | CVE-2026-92999 | unknown | The Click n Chat (Chat Widget Integration) WordPress plugin before 1.1.3 does not perform any... |
| GHSA-xhvc-grwf-wxq3 | CVE-2026-92998 | unknown | The Click n Chat (Chat Widget Integration) WordPress plugin before 1.1.3 does not sanitise sort... |
| GHSA-v5cq-8fvv-9wcc | CVE-2026-88784 | unknown | The Translate WordPress with Weglot 2.0  WordPress plugin before 6.4.3 does not escape the URLs... |
| GHSA-hqf7-665r-7343 | CVE-2026-87838 | unknown | The Wava Payment Plugin WordPress plugin before 0.3.10 does not perform any authorisation, nonce... |
| GHSA-8mpv-23rw-jfjx | CVE-2026-87837 | unknown | The Wava Payment Plugin WordPress plugin before 0.3.10 does not verify the authenticity of... |
| GHSA-f9pm-pfcr-fr64 | CVE-2026-111956 | unknown | The WholesaleX  WordPress plugin before 3.0.9 does not protect or remove the user-import file it... |
| GHSA-r6r9-jfqh-hrq2 | CVE-2026-111957 | unknown | The SUMIT Payment Gateway for WooCommerce WordPress plugin before 4.0.0 does not bind the payment... |
| GHSA-xm5m-h552-37c3 | CVE-2026-111955 | unknown | The WholesaleX  WordPress plugin before 3.0.9 does not check that a stored account confirmation... |
| GHSA-grh6-fqc7-f8f5 | CVE-2026-81813 | unknown | The Elementor Website Builder  WordPress plugin before 4.3.5 does not sanitize the text content... |
| GHSA-4w7f-p9m2-jxgx | CVE-2026-85642 | unknown | The Formidable Forms  WordPress plugin before 7.0 does not verify the identity of the caller... |
| GHSA-79v7-2xfm-2p77 | CVE-2026-111949 | unknown | The miniOrange 2FA  WordPress plugin before 6.3.1 does not prevent a pending passkey login from... |
| GHSA-2f6h-f6g2-jxwq | CVE-2026-86611 | unknown | The Download Manager WordPress plugin before 3.3.71, Download Manager WordPress plugin before 7.5... |
| GHSA-3846-mpmc-4v59 | CVE-2026-79627 | unknown | The Advanced File Manager  WordPress plugin before 6.0.0 does not correctly determine whether a... |
| GHSA-mr45-fp3c-4768 | CVE-2026-92997 | unknown | The Click n Chat (Chat Widget Integration) WordPress plugin before 1.1.3 does not properly... |
| GHSA-hrxv-m5x6-xfpv | CVE-2026-111596 | unknown | The Kliken: Ads + Pixel for Meta WordPress plugin before 1.2.3 does not verify that a visitor... |
| GHSA-42jx-58g4-6w6f | CVE-2026-111947 | unknown | The Pricing Table WordPress Plugin  WordPress plugin before 4.1.3 does not perform authorisation... |
| GHSA-cwqx-v6j9-jf65 | CVE-2026-81812 | unknown | The Elementor Website Builder  WordPress plugin before 4.3.5 does not sanitize uploaded SVG files... |
| GHSA-7x28-fvqf-5c5h | CVE-2026-111948 | unknown | The User Profile Builder  WordPress plugin before 4.0.1 does not escape the current page URL... |
| GHSA-fm6v-w7hr-3xm4 | CVE-2026-111574 | unknown | The Redirection for Contact Form 7 WordPress plugin before 3.2.12 does not sanitise or escape... |
| GHSA-7phx-x376-59jf | CVE-2026-110982 | unknown | The AI Engine  WordPress plugin before 3.8.6 does not check that the caller is allowed to edit... |
| GHSA-fq22-x2c4-x739 | CVE-2026-110514 | unknown | The WPZOOM Portfolio Lite  WordPress plugin before 1.4.34 does not check that a user is allowed... |
| GHSA-84p5-6x2c-h74j | CVE-2026-15261 | unknown | The TI WooCommerce Wishlist WordPress plugin before 2.13.0 does not enforce the same owner-only... |
| GHSA-cw23-46x9-m6xg | CVE-2026-108073 | unknown | The SureCart  WordPress plugin before 4.9.5 does not restrict which related objects an anonymous... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| GSE-M Technology Sdn. Bhd. | bravox | MY | 2026-10-21T02:12:33.335286+00:00 |
| Bruin Group LLC | emperador | US | 2026-10-21T01:55:09.972426+00:00 |
| M... M... | SilentRansomGroup |  | 2026-10-20T20:05:34.681618+00:00 |
| P... H... | SilentRansomGroup |  | 2026-10-20T20:04:24.366142+00:00 |
| Graves Fireplaces, Inc. | Global Secret Group | US | 2026-10-20T19:53:23.930848+00:00 |
| Asensus Surgical | Dark Project | US | 2026-10-20T17:53:03.802698+00:00 |
| The Excalibur Group | Dark Project | US | 2026-10-20T17:52:21.347217+00:00 |
| P...S...R... | SilentRansomGroup |  | 2026-10-20T16:56:29.357983+00:00 |
| 51Ridge (Newark NJ hosting/IT) | N0n | US | 2026-10-20T13:59:48.673218+00:00 |
| OpenText | Mimori | CA | 2026-10-20T13:45:09.514140+00:00 |
| Aveva | Mimori | GB | 2026-10-20T13:44:30.016847+00:00 |
| City Hall - Everett, MA | Booba Project | US | 2026-10-20T13:55:01.614958+00:00 |
| City of Mt. Angel, Oregon | Booba Project | US | 2026-10-20T13:55:24.974692+00:00 |
| Pearland Pediatrics | Booba Project | US | 2026-10-20T13:55:45.993462+00:00 |
| Chicago Vein Institute | Booba Project | US | 2026-10-20T13:56:07.059848+00:00 |
| Research Foundation of The City University of New York | Booba Project | US | 2026-10-20T13:56:28.213736+00:00 |
| COASTAL CAROLINA NEUROPSYCHIATRIC CENTER, PA | Booba Project | US | 2026-10-20T12:21:07.013508+00:00 |
| centralrogers.com | incransom | US | 2026-10-20T19:23:14.547366+00:00 |
| Company #98 | N0n | ET | 2026-10-20T09:28:30.225343+00:00 |
| Company #97 | N0n | TN | 2026-10-20T05:54:05.013090+00:00 |

## IOCs
### ThreatFox (recent, abuse.ch)
| Indicator | Type | Malware |
|---|---|---|
| 102.220.161.230:425 | ip:port | win.tofsee |
| 46.151.182.129:430 | ip:port | win.tofsee |
| 102.220.161.230:430 | ip:port | win.tofsee |
| 46.151.182.129:420 | ip:port | win.tofsee |
| 102.220.161.230:420 | ip:port | win.tofsee |
| 46.151.182.129:423 | ip:port | win.tofsee |
| 102.220.161.230:423 | ip:port | win.tofsee |
| 46.151.182.129:425 | ip:port | win.tofsee |
| 8d31f0250660fee1e936b8de6fb3d05c059a00cb2e3fcbec475e46f48444d95b | sha256_hash | osx.amos |
| https://ci.abblbet.org/v1/ | url | win.vidar |
| 66c8c5608b33584b77762dfce9954f7282cc5d67836f6f03a78b8d0f5b22aa45 | sha256_hash | osx.amos |
| 91.92.41.120:2026 | ip:port | win.remcos |
| https://ci.abblbet.org/ar/ | url | win.vidar |
| astp.africa.com | domain | win.asyncrat |
| 2c5035d373762bfb96044a1b3fc9fce65f38025b771103d58a8621210e1d6855 | sha256_hash | osx.amos |
| https://ci.abblbet.org/mz/ | url | win.vidar |
| 156.240.41.136:8877 | ip:port | win.vshell |
| 156.240.41.137:8877 | ip:port | win.vshell |
| 156.240.41.133:8877 | ip:port | win.vshell |
| 156.240.41.134:8877 | ip:port | win.vshell |

### URLhaus (recent malicious URLs, abuse.ch)
| URL | Threat | Status |
|---|---|---|
| http://39.88.70.223:33717/i | malware_download | online |
| http://112.242.63.35:36563/i | malware_download | online |
| http://175.172.171.251:37806/bin.sh | malware_download | online |
| http://24.191.64.49:37009/bin.sh | malware_download | online |
| http://39.88.70.223:33717/bin.sh | malware_download | online |
| http://60.19.210.229:58823/bin.sh | malware_download | online |
| http://195.246.231.125:45876/b | malware_download | online |
| http://195.246.231.125:45876/b.gz | malware_download | online |
| http://153.76.163.75:8888/m.sh | malware_download | offline |
| http://123.4.237.186:37220/i | malware_download | online |
| http://195.85.114.192:8080/xmrig.tar.gz | malware_download | offline |
| http://46.16.34.248:24381/bins/payloads/o.xml | malware_download | offline |
| http://159.223.92.101/sysupdate.apk | malware_download | offline |
| http://166.0.100.70/poc.xml | malware_download | offline |
| https://metrics-relay.net/agent.gz | malware_download | online |
| http://58.253.129.91:46735/i | malware_download | online |
| https://github.com/Aakanksha011/Personalised-TODO-with-AI/raw/master/creatrix/Personalised-TOD-with-AI-v1.9.zip | malware_download | online |
| http://195.85.114.192/xmrig.tar.gz | malware_download | online |
| http://94.154.43.37/l_mips.sh | malware_download | offline |
| https://node-status-sync.net/agent.gz | malware_download | online |

### MalwareBazaar (recent samples, abuse.ch)
| SHA256 | File type | Signature |
|---|---|---|
| f2c4b5291a531b411d8b7414ca3bd741304fb72235ee16dfd23c8d8e2bad01c1 | Bitsight | n/a |
| 9bf680e3edfbb245d5abce4d81ccf31f7afaf65a44da82bab73a4dcbc9b7fd3f | Bitsight | n/a |
| b3aeb1895d497230d433d7e9a7e3dba49be39d9b78be7ebd6efa32ef73f9b985 | Bitsight | n/a |
| 405fa135b6bf920b21791936965ceb1d61504869a1c748db7ce7ce838d72e538 | Bitsight | n/a |
| cbf806ad0896c9ee40e9cbbc959630a1b4cb70429de40d08d9010a2da26522ea | lowmal3 | n/a |
| 875f6a62a688be65218a01734a35984772f9f0c613101c97ab7f826cf292d3ec | Bitsight | CoinMiner |
| af97a21425a18a86fe7310e4c96616fb8b6fffb03df0b1c0b4edf235989722b4 | lowmal3 | n/a |
| 266ed3c21bfcf9002396fc9457ce9a35bc5b42e83d2e8ff8ab9526aae0d0df9d | abuse_ch | n/a |
| 8c95c07d55959731bc6649916f1947c5a6d1ffeab2d4a0fe4d7d87d6ffda5dc7 | abuse_ch | Mirai |
| 97ca6a10020c8a44a17f75ffd56cf21867ac70dc3cc11317a8d5b88e5d6109f9 | abuse_ch | Mirai |
| 3e001959d739a0863ee841795a449fc80d8d185374a19b6509a65ae5960e7da1 | abuse_ch | Mirai |
| 754fb80ed6d976d4505b9a405db94326fa0389f5bc9e838163d9b2ca7aea555f | Bitsight | n/a |
| a96995f324d2eaacb92edf3f7337ebabbef17f6032bfab59e9cca922a2f45864 | Bitsight | n/a |
| dc123e0b175af0705b536808884d9365e155f523e6bf1ba7e3a365ae13f387d7 | c4ffeine | n/a |
| 0d0509d786d37000bad5ac3efbf18556e26a5430d00413427ed6f169a0b9baad | abuse_ch | n/a |
| 898a138ef42c7846cd641bd8406a9ec940991b26113389bbc847648a76cf104c | abuse_ch | n/a |
| 4b131b802b89561b8deb26a06cd6d73fc209420c3bb7b6503d8d84649cc2467f | abuse_ch | ConnectWise |
| fb400cd6def8ec282a15fe269f100b71d0bf91c26c714e864430f3103a80d728 | Bitsight | CoinMiner |
| fa2e33c7b781c4491ea42391d015e8c3dc6780de202d0950cf5a8cf73c8b960d | Bitsight | n/a |
| a045b2b66aa63b74141000485105a468629693951dee8de272425e3543fd0cbf | Bitsight | n/a |

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
| 77.90.185.20 | 11 |
| 152.32.225.117 | 10 |
| 160.250.132.238 | 10 |
| 167.94.146.51 | 10 |
| 2.57.122.238 | 9 |
| 45.137.194.154 | 9 |
| 66.132.172.142 | 9 |
| 103.159.2.113 | 9 |
| 103.159.51.70 | 9 |
| 167.94.146.62 | 9 |
| 190.171.189.85 | 9 |
| 193.24.211.219 | 9 |
| 16.5.0.197 | 8 |
| 16.5.0.217 | 8 |
| 36.66.16.233 | 8 |
| 45.148.10.151 | 8 |
| 45.172.152.74 | 8 |
| 46.151.178.14 | 8 |
| 50.221.56.52 | 8 |
| 51.68.226.87 | 8 |

### OpenPhish (live phishing URLs)
- https://nus.nbt.mybluehost.me/website_9f694753/055/Newcorreos%20(1)/cc/login.php?clckid=4e6f526c
- https://www.roblox.com.ml/users/346612762043/profile
- https://sp20ct10-davrelo-biz-kunima.pages.dev/send_appeal_request
- https://sp18ct10-nurlek-biz-zavuno.pages.dev/send_appeal_request
- https://cont17ct-suneri-biz-mavok-telra.pages.dev/send_appeal_request
- https://mavzelo-mpt-firqanu-r6x9pe27.pages.dev/send_appeal_request
- https://sp18ct10-burvak-biz-qazelo.pages.dev/send_appeal_request
- https://sp11ct-renvok-biz8-zelmir-panvek.pages.dev/send_appeal_request
- https://cont17ct-keluna-biz-vemor-tazli.pages.dev/send_appeal_request
- https://marnavi-kxt-belfavi-c5x9dw32.pages.dev/send_appeal_request
- https://sp11ct-melsar-biz8-ronvek-ladrix.pages.dev/send_appeal_request
- https://vormela-kxt-zarveta-r9t6fc13.pages.dev/send_appeal_request
- https://sp11ct-monzar-biz8-frenok-lavtri.pages.dev/send_appeal_request
- https://sp11ct-varsik-biz8-melzor-tranek.pages.dev/send_appeal_request
- https://sp11ct-ronmel-biz8-kastor-velnix.pages.dev/send_appeal_request
- https://sp11ct-vasrel-biz8-cormix-jalven.pages.dev/send_appeal_request
- https://sp11ct-selvik-biz8-tormex-janlor.pages.dev/send_appeal_request
- https://sp26ct-nulvo-biz-kesma-rutik.pages.dev/send_appeal_request
- https://sp18ct10-warnok-biz-lavemi.pages.dev/send_appeal_request
- https://sp26ct-kurva-biz-zemik-lorta.pages.dev/send_appeal_request

### PhishStats (recent phishing/malicious URLs, scored)
_No data returned this run._

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| 498a4921e2950bf327566b8bc94ebe88188ba48e | Meterpreter C&C |
| c0af8a04dbfca38a9c436cac6afe37edf603a2a8 | Malware C&C |
| 891676e8c7f77b79942835d2079e1ea1bcb6a7ae | PureRAT C&C |
| 4c39539092e64bddb231466dd8cce629b0ab53fc | Vidar C&C |
| f142b6f4bf3a29d39c2491bdca1e7f7bf5a06d1b | Vidar C&C |
| 700d7a5261f2ea5f9f4777e37cf2cb68518ae919 | Vidar C&C |
| 1c7f33ad355642475fd0ce679cd224ea3b2709ab | Vidar C&C |
| e10fe9007408391e4c3a808ae4b7c4cb6e7df1a3 | OnyxC2 C&C |
| 9061737b3e3cb6dae0a02abe33346d72ccd27af4 | RatonRAT C&C |
| 59fb8a90649cac57e345fbd3af9f76d6a73fac12 | OffLoader C&C |
| 9a2205a15c886d6278d9e0d60747e8ad287b6c7b | PureLogsStealer C&C |
| 75964711a6e10849d232b5df09f428a4eaa48a68 | PureRAT C&C |
| 9001ac2344ddd1b2e32f5d25b5e56b323e6fc862 | Vidar C&C |
| 38151a6b2438b2b645a27a891e1e15786f11a783 | PureLogsStealer C&C |
| eaefd82da94ee8839666b2a42d24dcc412d7de3c | Malware C&C |
| e2234aa66c80b118b69211f6e8f4efbd578a7587 | PureLogsStealer C&C |
| e2dbc11a546d739d12e547c38cdb4fd6cfacd4c4 | PureLogsStealer C&C |
| b97f1ae860fce04e1aae480e10b884da9826b17b | PureLogsStealer C&C |
| 97001686e56437dda319c71d5b0deeb8647de6e3 | QuasarRAT C&C |
| ad71014e839f794407e155508ce8ba98bf9556f7 | PureRAT C&C |

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
- 1.10.160.143
- 1.117.73.220
- 1.12.36.175
- 1.12.55.80
- 1.12.70.212
- 1.14.110.231
- 1.14.240.247
- 1.14.94.193
- 1.14.97.120
- 1.15.106.134
- 1.15.14.87
- 1.15.179.199
- 1.15.221.192
- 1.15.30.237
- 1.159.54.33
- 1.162.208.58
- 1.174.232.253
- 1.179.44.7
- 1.187.169.38
- 1.20.104.8

### CINS Army (poorly-rated IPs)
- 1.14.149.30
- 1.215.138.43
- 1.24.16.159
- 1.24.16.21
- 1.24.16.28
- 1.24.16.40
- 1.24.16.43
- 1.24.16.8
- 1.24.16.91
- 1.24.24.66
- 1.30.80.145
- 1.34.143.217
- 1.58.108.110
- 1.83.125.105
- 1.83.125.156
- 1.83.125.225
- 1.83.125.227
- 1.83.125.231
- 1.83.125.44
- 1.83.125.79

## News (last ~36h, across outlets)
### The Hacker News
- [State Bank of India Confirms Data Leak After 3,897 Customer Records Found on Dark Web](https://thehackernews.com/2026/10/state-bank-of-india-confirms-data-leak.html)
- [CISA Orders Federal Agencies to Patch Exploited Plex2Shell, Siemens, and SiteGuard Flaws](https://thehackernews.com/2026/10/cisa-orders-federal-agencies-to-patch.html)
- [Hackers Hid Vasilek Backdoor in VMware Tools During 2-Year Russian Healthcare Intrusion](https://thehackernews.com/2026/10/hackers-hid-vasilek-backdoor-in-vmware.html)
- [PHP2Shell: Two Unpatched Critical PHP RCE Flaws (CVSS 9.2) Trigger Emergency Security Alert](https://thehackernews.com/2026/10/php2shell-two-unpatched-critical-php.html)
- [Eight eMudhra CA Keys Compromised, Triggering Emergency Fixes Across Browsers and Software](https://thehackernews.com/2026/10/eight-emudhra-ca-keys-compromised.html)
- [Critical FortiSIEM Flaw Gets Public Exploit PoC for Unauthenticated Remote Code Execution](https://thehackernews.com/2026/10/critical-fortisiem-flaw-gets-public.html)
- [Qilin and INC Ransomware Groups Exploit Palo Alto Networks Flaw to Bypass MFA](https://thehackernews.com/2026/10/qilin-and-inc-ransomware-groups-exploit.html)
- [Hackers Use Autonomous AI Agents to Breach Company Websites, Target Over 1,200 Sites](https://thehackernews.com/2026/10/hackers-use-autonomous-ai-agents-to.html)
- [Pegasus Spyware Infection Confirmed on Serbian University Rector's iPhone Days Before Election](https://thehackernews.com/2026/10/pegasus-spyware-infection-confirmed-on.html)
- [WhatsApp Hid Instructions in Help Pages Telling Its AI Chatbot Not to Recommend Privacy Regulators](https://thehackernews.com/2026/10/whatsapp-hid-instructions-in-help-pages.html)
- [What Security Teams Can Do To Tame Wild Code](https://thehackernews.com/2026/10/what-security-teams-can-do-to-tame-wild.html)
- [Go Issues Emergency Update Blocking Eight CA Keys Over Undisclosed Security Concerns](https://thehackernews.com/2026/10/go-issues-emergency-update-blocking.html)
- [Russian APT28 Breaches NATO Naval Shipbuilder in NATO Country, Deploys New Reflective Loader](https://thehackernews.com/2026/10/russian-apt28-breaches-nato-naval.html)
- [ConnectWise Resets Credentials as Cloud Backup Remains Offline After Security Incident](https://thehackernews.com/2026/10/connectwise-resets-credentials-as-cloud.html)
- [Hackers Hijack Five OVHcloud CLI Releases to Distribute Secret-Stealing Malware](https://thehackernews.com/2026/10/hackers-hijack-five-ovhcloud-cli.html)

### BleepingComputer
- [Stolen UpdraftCentral keys used to backdoor WordPress sites](https://www.bleepingcomputer.com/news/security/stolen-updraftcentral-keys-used-to-backdoor-wordpress-sites/)
- [Mozilla, Google, Apple block compromised eMudhra CA certificates](https://www.bleepingcomputer.com/news/security/mozilla-google-apple-block-compromised-emudhra-ca-certificates/)
- [PHP warns admins of two critical flaws, emergency patches coming tomorrow](https://www.bleepingcomputer.com/news/security/php-warns-admins-of-two-critical-flaws-emergency-patches-coming-tomorrow/)
- [Zeabur shutting down after second security breach in two months](https://www.bleepingcomputer.com/news/security/zeabur-shutting-down-after-second-security-breach-in-two-months/)
- [OpenAI says GPT-6.1 Sol is dramatically better at migrating legacy code](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-says-gpt-61-sol-is-dramatically-better-at-migrating-legacy-code/)
- [DHS bans DeepSeek products across US federal civilian agencies](https://www.bleepingcomputer.com/news/security/dhs-bans-deepseek-products-across-us-federal-civilian-agencies/)
- [CJIS v6.1 Compliance: 5 Practical Priorities for Agencies](https://www.bleepingcomputer.com/news/security/cjis-v61-compliance-5-practical-priorities-for-agencies/)
- [Hacker gets 8 years for stealing $3.3 million from taxpayers](https://www.bleepingcomputer.com/news/security/hacker-gets-8-years-for-stealing-33-million-from-taxpayers/)
- [Windows Server 2025 gets support for quick machine recovery](https://www.bleepingcomputer.com/news/microsoft/windows-server-2025-gets-support-for-quick-machine-recovery/)
- [OVHcloud CLI releases backdoored on GitHub to steal developer secrets](https://www.bleepingcomputer.com/news/security/ovhcloud-cli-releases-backdoored-on-github-to-steal-developer-secrets/)
- [Ahold Delhaize: Cyberattack affects services across US and Europe](https://www.bleepingcomputer.com/news/security/ahold-delhaize-cyberattack-affects-services-across-us-and-europe/)
- [Revolut outage disrupts online banking operations worldwide](https://www.bleepingcomputer.com/news/security/revolut-outage-disrupts-online-banking-operations-worldwide/)
- [Nikkei discloses third data breach in a month, 1.8M records exposed](https://www.bleepingcomputer.com/news/security/nikkei-discloses-third-data-breach-in-a-month-18m-records-exposed/)
- [WordPress SEO plugin Rank Math compromised to backdoor websites](https://www.bleepingcomputer.com/news/security/wordpress-seo-plugin-rank-math-compromised-to-backdoor-websites/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [Tech Giants Block eMudhra Certificates Tied to 8 Compromised Keys](https://www.darkreading.com/cyber-risk/tech-giants-emudhra-certificates-compromised-keys)
- [Ex-OpenAI Engineer Detained After Planting Secret Recorder at HQ](https://www.darkreading.com/insider-threats/ex-openai-engineer-secret-recorder-saudi-ties)
- [Close Identity Gaps in Software Development Before Unleashing AI](https://www.darkreading.com/application-security/close-identity-gaps-sdlc-before-ai)
- [Hackers Abuse AI Pen-Test Tool Cairn to Automate Massive Attack Spree](https://www.darkreading.com/cyberattacks-data-breaches/hackers-abuse-ai-pen-test-tool-cairn)
- [Researchers Infiltrate Microsoft Tech Support Scam Operation](https://www.darkreading.com/threat-intelligence/microsoft-tech-support-scam-operation)

### SecurityWeek
- [PHP2Shell: Mass Exploitation Looms for Leaked Critical PHP Flaws](https://www.securityweek.com/php2shell-mass-exploitation-looms-for-leaked-critical-php-flaws/)
- [Hijacked Developer Account Used to Plant Stealer in OVHcloud CLI](https://www.securityweek.com/hijacked-developer-account-used-to-plant-stealer-in-ovhcloud-cli/)
- [Accenture, Dragos, SANS Launch $10M Initiative to Defend Small US Utilities](https://www.securityweek.com/accenture-dragos-sans-launch-10m-initiative-to-defend-small-us-utilities/)
- [US Agencies Detail Incident Response Practices for Rogue AI Agents](https://www.securityweek.com/us-agencies-detail-incident-response-practices-for-rogue-ai-agents/)
- [AOMEI Backupper Compromised in Short-Burst Supply Chain Campaign](https://www.securityweek.com/aomei-backupper-compromised-in-short-burst-supply-chain-campaign/)
- [The Key to AI Software Security Isn’t Speed, It’s Maturity](https://www.securityweek.com/the-key-to-ai-software-security-isnt-speed-its-maturity/)
- [Ahold Delhaize Restoring Services Disrupted by Cyberattack](https://www.securityweek.com/ahold-delhaize-restoring-services-disrupted-by-cyberattack/)
- [AI Platform Cairn Abused to Hack Over 100 Organizations](https://www.securityweek.com/ai-platform-cairn-abused-to-hack-over-100-organizations/)
- [Ex-OpenAI Worker Accused of Bugging Conference Room Planned to Fly to Saudi Arabia, Prosecutors Say](https://www.securityweek.com/ex-openai-worker-accused-of-bugging-conference-room-planned-to-fly-to-saudi-arabia-prosecutors-say/)
- [Microsoft Targets Rogue AI Agents With Dynamic Permissions, Risk Scoring](https://www.securityweek.com/microsoft-targets-rogue-ai-agents-with-dynamic-permissions-risk-scoring/)

### The Record
- [FBI says SafePay ransomware gang ‘among most active’ with more than 600 victims since 2024](https://therecord.media/fbi-says-safepay-ransomware-gang-among-most-active-600-victims)
- [California warns all public school students of data stolen in contractor breach](https://therecord.media/california-warns-all-public-school-students-of-data-breach)
- [23andMe successor settles with California for $6 million over cybersecurity failings](https://therecord.media/23andme-california-data-breach-settlement)
- [Nigerian national given 8-year sentence for tax business hacks](https://therecord.media/nigerian-given-8-year-sentenc-tax-hacks)
- [EU cyber law won’t force fixes for fridge controllers hit in French attack](https://therecord.media/eu-cyber-law-wont-force-fixes-for-fridges-in-french-attack)

### Infosecurity Magazine
- [Head of AI Security Roles Surge in Large Organizations](https://www.infosecurity-magazine.com/news/head-ai-security-roles/)
- [Researchers Warn OpenCode Quietly Patched Critical RCE Flaw, Leaving Users At Risk](https://www.infosecurity-magazine.com/news/opencode-quietly-patched-critical/)
- [AI Agent Adoption Creates Risk as Oversight Struggles to Keep Pace, Splunk Finds](https://www.infosecurity-magazine.com/news/ai-agent-adoption-oversight/)
- [Siemens Customers Targeted by ClickFix Attackers Exploiting DLL Side-Loading Flaw](https://www.infosecurity-magazine.com/news/siemens-clickfix-exploiting-side/)

### CyberScoop
- [Philippines-based American pleads guilty to running expansive fraud scheme targeting US servicemembers](https://cyberscoop.com/identity-theft-fraud-military-servicemembers-veterans-guilty-robert-boling/)
- [Nigerian sentenced to 8 years for long-running tax business hacking and fraud scheme](https://cyberscoop.com/nigerian-sentenced-hacking-fraud-tax-investment-scheme/)
- [Russian GRU hackers hit NATO shipbuilder, aircraft engine maker, law enforcement agency in espionage campaign](https://cyberscoop.com/russian-hackers-apt28-target-nato-defense-firms/)
- [ConnectWise customers hit by supply-chain attack linked to compromised API secret](https://cyberscoop.com/connectwise-cloud-backup-supply-chain-attack/)
- [DOJ escalates fight for election supremacy with California raids](https://cyberscoop.com/justice-department-california-voter-arrests-noncitizen-claims/)

### Cisco Talos
- [There's only so much code: the rise in vulnerability numbers](https://blog.talosintelligence.com/theres-only-so-much-code-the-rise-in-vulnerability-numbers/)

### Unit 42 (Palo Alto)
- [Threat Brief: Active Exploitation of PAN-OS CVE-2026-0257 (Updated October 20)](https://unit42.paloaltonetworks.com/active-exploitation-of-pan-os-cve-2026-0257/)

### Microsoft Security Blog
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Wednesday, October 21st, 2026 https://isc.sans.edu/podcastdetail/10144, (Wed, Oct 21st)](https://isc.sans.edu/diary/rss/33438)
- [ISC Stormcast For Tuesday, October 20th, 2026 https://isc.sans.edu/podcastdetail/10142, (Tue, Oct 20th)](https://isc.sans.edu/diary/rss/33436)

### Securelist (Kaspersky)
- [Operation FlashHole: Lazarus breaks security, defies control](https://securelist.com/lazarus-operation-flashhole/121541/)
- [The journey of a paper unicorn: adventures inside a modern warehouse](https://securelist.com/paper-unicorn-warehouse-security/121537/)

### CrowdStrike Blog
- [CrowdStrike Achieves NCSC CIR Enhanced Level Assurance](https://www.crowdstrike.com/en-us/blog/crowdstrike-achieves-uk-ncsc-cir-enhanced-level-assurance/)
- [U.S. Government Disrupts FAMOUS CHOLLIMA Operation with CrowdStrike Assistance](https://www.crowdstrike.com/en-us/blog/fbi-disrupts-famous-chollima-operation-with-crowdstrike-assistance/)
- [October 2026 Patch Tuesday: 1,413 CVEs Include Three Zero-Days and 75 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-october-2026/)
- [CrowdStrike and Anthropic Give Critical Infrastructure Defenders the AI Advantage](https://www.crowdstrike.com/en-us/blog/crowdstrike-anthropic-critical-infrastructure-defense-program/)
- [Solving the Continuous Authorization Conundrum](https://www.crowdstrike.com/en-us/blog/solving-the-continuous-authorization-conundrum/)
- [Unknown Threat Actor Uses AI-Driven ARTEX to Target South Korean Finance](https://www.crowdstrike.com/en-us/blog/unknown-threat-actor-uses-artex-to-target-south-korean-finance/)
- [CrowdStrike Named a Leader in the 2026 IDC MarketScape for Worldwide Modern Endpoint Security for Enterprises Vendor Assessment](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-idc-marketscape-worldwide-modern-endpoint-security-for-enterprises/)
- [Request, Aggregate, Bypass: How Attackers Can Evade LLM Safety Classifiers](https://www.crowdstrike.com/en-us/blog/how-attackers-can-bypass-llm-safety-classifiers/)
- [Falcon Data Security for SaaS Secures Sensitive Data in Microsoft 365](https://www.crowdstrike.com/en-us/blog/falcon-data-security-for-saas-secures-sensitive-data/)
- [New in Falcon Cloud Security: Third-Party App Insights and AI-Enhanced Remediation](https://www.crowdstrike.com/en-us/blog/falcon-cloud-security-third-party-app-insights-ai-enhanced-remedation/)

### FortiGuard Threat Signal
- [Atlassian Arbitrary File Access Vulnerability](https://fortiguard.fortinet.com/threat-signal-report/6548)

## Fetch issues this run
- https://api.phishstats.info/api/phishing?_sort=-id&_size=30 -> HTTPSConnectionPool(host='api.phishstats.info', port=443): Read timed out. (read timeout=25)

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal