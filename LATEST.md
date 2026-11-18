# Winjit Daily TI Digest — 2026-11-18

_Auto-generated. Window: last ~24h. Fetched at 2026-11-18T11:22:26.827752+00:00Z_

**At a glance:** 1 new KEV · 266 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-115731 | Perforce | Puppet Enterprise | Perforce Puppet Enterprise Deserialization of Untrusted Data Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-114784 | 10.0 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: Platform Security).  Supported versions that are affected are 8.2.0.0.0 and  26.01.0.0.0. E |
| CVE-2026-114824 | 10.0 | n/a | Vulnerability in the Oracle Platform Security for Java product of Oracle Fusion Middleware (component: Centralized Thirdparty Jars).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0. |
| CVE-2026-114835 | 10.0 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Admin Console).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploitable vuln |
| CVE-2026-91500 | 10.0 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploita |
| CVE-2026-91510 | 10.0 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploita |
| CVE-2026-91569 | 10.0 | n/a | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: TopLink Integration).  Supported versions that are affected are 12.2.1.4.0, 14.1.1.0.0, 14.1.2.0.0 and  15.1 |
| CVE-2026-114819 | 9.9 | n/a | Vulnerability in the Oracle Text component of Oracle Database Server.  Supported versions that are affected are 19.3-19.32, 21.3-21.24 and  23.4.0-23.26.3. Easily exploitable vulnerability allows low  |
| CVE-2026-114822 | 9.9 | n/a | Vulnerability in the RDBMS component of Oracle Database Server.  Supported versions that are affected are 23.4.0-23.26.4. Easily exploitable vulnerability allows low privileged attacker having Create  |
| CVE-2026-114848 | 9.9 | n/a | Vulnerability in the Oracle Text component of Oracle Database Server.  Supported versions that are affected are 19.3-19.33, 21.3-21.24 and  23.4.0-23.26.3. Easily exploitable vulnerability allows low  |
| CVE-2026-114978 | 9.9 | n/a | Vulnerability in the Oracle Hyperion Financial Management product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vulnerability  |
| CVE-2026-114980 | 9.9 | n/a | Vulnerability in the Oracle AutoVue product of Oracle Supply Chain (component: Security Related Issues).   The supported version that is affected is 21.1.0. Easily exploitable vulnerability allows low |
| CVE-2026-130840 | 9.8 | n/a | BISHENG before 3.0.0 contains an authentication bypass vulnerability that allows unauthenticated remote attackers to impersonate administrators by abusing a hard-coded default jwt_secret used by AuthJ |
| CVE-2026-130849 | 9.8 | n/a | BZFlag bzfs before 2.4.32 contains a heap out-of-bounds write vulnerability in NetHandler::tcpReceive() that allows remote unauthenticated attackers to corrupt heap memory by sending a TCP message wit |
| CVE-2026-130856 | 9.8 | n/a | 53AIHub before 0.5.5 contains a missing authentication vulnerability that allows remote unauthenticated attackers to reinitialize installed instances by calling the public POST /api/init endpoint. Att |
| CVE-2026-131852 | 9.8 | n/a | OwnTracks Recorder before 1.0.5 contains a format string vulnerability in json_response() and related output functions that allows unauthenticated attackers to execute code by storing a malicious tid  |
| CVE-2026-114785 | 9.6 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vulnerability allows unaut |
| CVE-2026-114856 | 9.6 | n/a | Vulnerability in Oracle REST Data Services (component: General).  Supported versions that are affected are 24.2.0-26.3.0. Easily exploitable vulnerability allows unauthenticated attacker with network  |
| CVE-2026-91561 | 9.6 | n/a | Vulnerability in the Oracle Service Bus product of Oracle Fusion Middleware (component: Core).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerability al |
| CVE-2026-91469 | 9.4 | n/a | Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Core).  Supported versions that are affected are 12.2.1.4.0, 14.1.1.0.0, 14.1.2.0.0 and  15.1.1.0.0. Easily  |
| CVE-2026-130583 | 9.3 | n/a | Rootways Authorize.net CIM Pro extension for Magento 2 before 4.1.5 contains an unauthenticated server-side request forgery vulnerability in the Apple Pay merchant validation controller. Attackers can |
| CVE-2026-101691 | 9.3 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Admin UI).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability al |
| CVE-2026-114934 | 9.3 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Integration Broker).  Supported versions that are affected are 8.61-8.63. Easily exploitable vulnerabili |
| CVE-2026-114956 | 9.3 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vulnerability allows unaut |
| CVE-2026-115139 | 9.3 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-91507 | 9.3 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploita |
| CVE-2026-114881 | 9.1 | n/a | Vulnerability in the Document Management and Collaboration product of Oracle E-Business Suite (component: Attachments).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vul |
| CVE-2026-130361 | 8.8 | 0.4% | AdminNeo before 5.9.1 contains a parameter injection vulnerability in its ClickHouse driver that allows attackers to inject ClickHouse HTTP query parameters through an unencoded db GET parameter. Atta |
| CVE-2026-130382 | 8.8 | 0.4% | AdminNeo before 5.9.1 contains an authentication bypass vulnerability in OtpLoginPlugin that allows attackers knowing the database password to skip TOTP verification by abusing the permanent-login coo |
| CVE-2026-130848 | 8.8 | n/a | Dolibarr ERP CRM through 24.0.3 contains a code injection vulnerability in Website::importWebSite() that allows website editors without PHP permission to execute code by importing templates. Attackers |
| CVE-2026-130861 | 8.8 | n/a | UrlHub before 1.20.1 contains a missing authorization vulnerability that allows any authenticated user to create accounts via the POST /admin/user/store route because role:admin middleware only covers |
| CVE-2026-101657 | 8.8 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Admin UI).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability al |
| CVE-2026-114814 | 8.8 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: Analytics Actions).  Supported versions that are affected are 8.2.0.0.0 and  26.01.0.0.0. E |
| CVE-2026-114827 | 8.8 | n/a | Vulnerability in the Oracle Managed File Transfer product of Oracle Fusion Middleware (component: MFT Runtime Server).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily expl |
| CVE-2026-114829 | 8.8 | n/a | Vulnerability in the Oracle Enterprise Manager Base Platform product of Oracle Enterprise Manager (component: Job System).  Supported versions that are affected are 13.5 and  24.1. Easily exploitable  |
| CVE-2026-114857 | 8.8 | n/a | Vulnerability in Oracle REST Data Services (component: PL/SQL Gateway).  Supported versions that are affected are 24.2.0-26.3.0. Easily exploitable vulnerability allows low privileged attacker with ne |
| CVE-2026-114859 | 8.8 | n/a | Vulnerability in Oracle Application Testing Suite (component: Test Manager for Web Apps).   The supported version that is affected is 13.3.0.1. Easily exploitable vulnerability allows low privileged a |
| CVE-2026-114896 | 8.8 | n/a | Vulnerability in the Oracle Collaborative Planning product of Oracle E-Business Suite (component: Horizontal View).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnera |
| CVE-2026-114897 | 8.8 | n/a | Vulnerability in the Oracle iProcurement product of Oracle E-Business Suite (component: Redirection).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows  |
| CVE-2026-114917 | 8.8 | n/a | Vulnerability in the Oracle Applications Framework product of Oracle E-Business Suite (component: Personalization).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnera |
| CVE-2026-114928 | 8.8 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Application Server).  Supported versions that are affected are 8.61-8.63. Easily exploitable vulnerabili |
| CVE-2026-114937 | 8.8 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Updates Environment Mgmt).  Supported versions that are affected are 8.61-8.63. Easily exploitable vulne |
| CVE-2026-114979 | 8.8 | n/a | Vulnerability in the Oracle Hyperion Financial Management product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vulnerability  |
| CVE-2026-115035 | 8.8 | n/a | Vulnerability in the Siebel CRM Deployment product of Oracle Siebel CRM (component: Siebel Remote).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows low pri |
| CVE-2026-115044 | 8.8 | n/a | Vulnerability in the Siebel CRM Integration product of Oracle Siebel CRM (component: EAI).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability allows low privileged a |
| CVE-2026-115049 | 8.8 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115054 | 8.8 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115067 | 8.8 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115070 | 8.8 | n/a | Vulnerability in the Oracle Hyperion Financial Close Management product of Oracle Hyperion (component: Reconciliation Manage).   The supported version that is affected is 11.2.26.0.000. Easily exploit |
| CVE-2026-115071 | 8.8 | n/a | Vulnerability in the Oracle Hyperion Financial Close Management product of Oracle Hyperion (component: Reconciliation Manage).   The supported version that is affected is 11.2.26.0.000. Easily exploit |
| CVE-2026-115074 | 8.8 | n/a | Vulnerability in the Oracle Hyperion Financial Close Management product of Oracle Hyperion (component: Reconciliation Manage).   The supported version that is affected is 11.2.26.0.000. Easily exploit |
| CVE-2026-115087 | 8.8 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vulnerability allows low p |
| CVE-2026-115128 | 8.8 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vulnerability allows low p |
| CVE-2026-115131 | 8.8 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Application Development Framework).   The supported version that is affected is 11.2.26.0.000. Easily exploitable v |
| CVE-2026-115133 | 8.8 | n/a | Vulnerability in the Oracle Hyperion Financial Close Management product of Oracle Hyperion (component: Reconciliation Manage).   The supported version that is affected is 11.2.26.0.000. Easily exploit |
| CVE-2026-115142 | 8.8 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-127307 | 8.8 | n/a | Vulnerability in the Oracle AutoVue product of Oracle Supply Chain (component: Security).   The supported version that is affected is 21.1.0. Easily exploitable vulnerability allows low privileged att |
| CVE-2026-127334 | 8.8 | n/a | Vulnerability in the Oracle AutoVue product of Oracle Supply Chain (component: Security).   The supported version that is affected is 21.1.0. Easily exploitable vulnerability allows low privileged att |
| CVE-2026-127335 | 8.8 | n/a | Vulnerability in the Oracle Hyperion Financial Close Management product of Oracle Hyperion (component: Reconciliation Manage).   The supported version that is affected is 11.2.26.0.000. Easily exploit |
| CVE-2026-127371 | 8.8 | n/a | Vulnerability in the Oracle Hyperion Financial Close Management product of Oracle Hyperion (component: Reconciliation Manage).   The supported version that is affected is 11.2.26.0.000. Easily exploit |
| CVE-2026-127418 | 8.8 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Lifecycle Management).   The supported version that is affected is 11.2.26.0.000. Easily exploitab |
| CVE-2026-83362 | 8.8 | n/a | Vulnerability in the Oracle Purchasing product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability a |
| CVE-2026-91556 | 8.8 | n/a | Vulnerability in the Service Delivery Platform product of Oracle Fusion Middleware (component: Messaging Enabler).   The supported version that is affected is 14.1.2.0.0. Easily exploitable vulnerabil |
| CVE-2026-91566 | 8.8 | n/a | Vulnerability in the Oracle Service Bus product of Oracle Fusion Middleware (component: Core).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnerability al |
| CVE-2026-131851 | 8.8 | n/a | ILIAS before 9.25, 10.13, and 11.6 contains an SQL injection vulnerability in ilPRGAssignmentFilter::toConditions() that allows authenticated users to inject SQL through the StudyProgramme members lis |
| CVE-2026-131875 | 8.8 | n/a | fqterm before 0.9.11 contains a heap out-of-bounds write vulnerability in FQTermDecode that allows malicious servers to corrupt memory by sending CSI sequences with unbounded parameter indexes. Attack |
| CVE-2026-5765 | 8.8 | n/a | The Essential Real Estate plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 5.3.3 via deserialization of untrusted input in the 'saved_search_check_resul |
| CVE-2026-113497 | 8.8 | n/a | A low-privileged remote attacker can change the password of arbitrary users using the REST API, including administrative accounts. By changing the administrator password, an attacker can obtain full a |
| CVE-2026-114860 | 8.7 | n/a | Vulnerability in Oracle Application Testing Suite (component: Test Manager for Web Apps).   The supported version that is affected is 13.3.0.1. Difficult to exploit vulnerability allows unauthenticate |
| CVE-2026-114916 | 8.7 | n/a | Vulnerability in the Oracle Applications Framework product of Oracle E-Business Suite (component: Security).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability  |
| CVE-2026-114918 | 8.7 | n/a | Vulnerability in the Oracle Concurrent Processing product of Oracle E-Business Suite (component: BI Publisher Integration).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable |
| CVE-2026-114932 | 8.7 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Test Framework).  Supported versions that are affected are 8.61-8.63. Easily exploitable vulnerability a |
| CVE-2026-115088 | 8.7 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Difficult to exploit vulnerability allows una |
| CVE-2026-115120 | 8.7 | n/a | Vulnerability in the Oracle Hyperion Financial Management product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vulnerability  |
| CVE-2026-115164 | 8.7 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-91509 | 8.7 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Difficult to ex |
| CVE-2026-114783 | 8.6 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: BI Platform Security).  Supported versions that are affected are 8.2.0.0.0, 12.2.1.4.0 and  |
| CVE-2026-114876 | 8.6 | n/a | Vulnerability in the Oracle iStore product of Oracle E-Business Suite (component: Shopping Cart).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows unau |
| CVE-2026-127306 | 8.6 | n/a | Vulnerability in the Oracle AutoVue product of Oracle Supply Chain (component: Security Related Issues).   The supported version that is affected is 21.1.0. Easily exploitable vulnerability allows una |
| CVE-2026-127370 | 8.6 | n/a | Vulnerability in the Oracle Hyperion Financial Close Management product of Oracle Hyperion (component: Reconciliation Manage).   The supported version that is affected is 11.2.26.0.000. Easily exploit |
| CVE-2026-127421 | 8.6 | n/a | Vulnerability in the Oracle VM VirtualBox product of Oracle Virtualization (component: Core).   The supported version that is affected is 7.2.22. Easily exploitable vulnerability allows unauthenticate |
| CVE-2026-91548 | 8.6 | n/a | Vulnerability in the Oracle Platform Security for Java product of Oracle Fusion Middleware (component: Centralized Thirdparty Jars).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0. |
| CVE-2026-91587 | 8.6 | n/a | Vulnerability in the Oracle WebCenter Portal product of Oracle Fusion Middleware (component: Composer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnera |
| CVE-2026-115173 | 8.5 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Common Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vu |
| CVE-2026-91671 | 8.5 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Difficult to ex |
| CVE-2026-115179 | 8.4 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Common Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vu |
| CVE-2026-130584 | 8.3 | n/a | Xibo CMS before 4.5.3 contains an insecure direct object reference vulnerability that allows authenticated users to access other DataSets' RSS feeds by pairing their own DataSet id with a foreign RSS  |
| CVE-2026-130857 | 8.3 | n/a | EveryDocs Core before 1.6.1 contains an authorization bypass vulnerability that allows authenticated users to access other users' records through unscoped Model.find(params[:id]) lookups in multiple c |
| CVE-2026-127357 | 8.3 | n/a | Vulnerability in the Oracle Hyperion Financial Close Management product of Oracle Hyperion (component: Reconciliation Manage).   The supported version that is affected is 11.2.26.0.000. Easily exploit |
| CVE-2026-91558 | 8.3 | n/a | Vulnerability in the Service Delivery Platform product of Oracle Fusion Middleware (component: Messaging Enabler).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Difficult to ex |
| CVE-2026-130796 | 8.2 | n/a | Flowise 3.1.3 through 3.1.4 contains an information disclosure vulnerability that allows unauthenticated attackers to read MCP server bearer tokens via the GET /api/v1/public-chatflows/:id handler. At |
| CVE-2026-130860 | 8.2 | n/a | Flagr before 1.2.5 contains an authentication bypass vulnerability that allows unauthenticated remote attackers to access the flag management write API through an insecure default FLAGR_BASIC_AUTH_WHI |
| CVE-2026-101659 | 8.2 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Admin UI).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability  |
| CVE-2026-114904 | 8.2 | n/a | Vulnerability in the Oracle E-Business Suite Integrated SOA Gateway product of Oracle E-Business Suite (component: SOA Provider).  Supported versions that are affected are 12.2.3-12.2.15. Easily explo |
| CVE-2026-114933 | 8.2 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Security).  Supported versions that are affected are 8.61-8.63. Easily exploitable vulnerability allows  |
| CVE-2026-114958 | 8.2 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115060 | 8.2 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115078 | 8.2 | n/a | Vulnerability in the Oracle Hyperion Financial Management product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vulnerability  |
| CVE-2026-115082 | 8.2 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115092 | 8.2 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Application Development Framework).   The supported version that is affected is 11.2.26.0.000. Difficult to exploit |
| CVE-2026-115166 | 8.2 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-91533 | 8.2 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploita |
| CVE-2026-91543 | 8.2 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploita |
| CVE-2026-130366 | 8.1 | 0.6% | AdminNeo before 5.9.1 contains an authentication bypass vulnerability in the ClickHouse driver that allows remote attackers to log in to passwordless accounts without the configured defaultPasswordHas |
| CVE-2026-130369 | 8.1 | 0.4% | phpMyFAQ 4.1.9 before 4.1.12 and 4.2.0-alpha before 4.2.0-RC.2 contains an authorization bypass vulnerability in multisite deployments that allows attackers to overwrite passkeys of accounts on other  |
| CVE-2026-121684 | 8.1 | 0.4% | The Soledad theme for WordPress is vulnerable to unauthenticated Remote Code Execution in versions up to, and including, 8.7.7 The public penci_more_post_ajax AJAX action feeds infeedads[ads_code] (ba |
| CVE-2026-130589 | 8.1 | n/a | Emitter through 3.1 contains a privilege escalation vulnerability that allows any channel key holder to forge a master key because channel keys use bare XOR Salsa20 encryption without a MAC or signatu |
| CVE-2026-101652 | 8.1 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulne |
| CVE-2026-114788 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Difficult to exploit vulnerability allows una |
| CVE-2026-114813 | 8.1 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: Platform Security).  Supported versions that are affected are 8.2.0.0.0 and  26.01.0.0.0. E |
| CVE-2026-114815 | 8.1 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: BI Foundation).   The supported version that is affected is 12.2.1.4.0. Difficult to exploi |
| CVE-2026-114817 | 8.1 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: BI Platform Security).  Supported versions that are affected are 8.2.0.0.0, 12.2.1.4.0 and  |
| CVE-2026-114825 | 8.1 | n/a | Vulnerability in the Oracle WebCenter Sites product of Oracle Fusion Middleware (component: WebCenter Sites).   The supported version that is affected is 12.2.1.4.0. Difficult to exploit vulnerability |
| CVE-2026-114852 | 8.1 | n/a | Vulnerability in Oracle REST Data Services (component: Core).  Supported versions that are affected are 24.2.0-26.3.0. Easily exploitable vulnerability allows low privileged attacker with network acce |
| CVE-2026-114871 | 8.1 | n/a | Vulnerability in the Oracle Sales Online product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability |
| CVE-2026-114887 | 8.1 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulne |
| CVE-2026-114909 | 8.1 | n/a | Vulnerability in the Oracle iProcurement product of Oracle E-Business Suite (component: Requisition Management).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerabil |
| CVE-2026-114914 | 8.1 | n/a | Vulnerability in the Oracle Purchasing product of Oracle E-Business Suite (component: Endeca).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows low pri |
| CVE-2026-114976 | 8.1 | n/a | Vulnerability in the Siebel CRM Deployment product of Oracle Siebel CRM (component: Cloud Gateway).  Supported versions that are affected are 22.3-26.9. Difficult to exploit vulnerability allows unaut |
| CVE-2026-115046 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115051 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Diffic |
| CVE-2026-115059 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115062 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Financial Management product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vulnerability  |
| CVE-2026-115066 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115081 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115094 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Difficult to exploit vulnerability allows una |
| CVE-2026-115130 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Application Development Framework).   The supported version that is affected is 11.2.26.0.000. Easily exploitable v |
| CVE-2026-115150 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115151 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Diffic |
| CVE-2026-115153 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Common Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vu |
| CVE-2026-115157 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Diffic |
| CVE-2026-115172 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Common Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vu |
| CVE-2026-127308 | 8.1 | n/a | Vulnerability in the Oracle AutoVue product of Oracle Supply Chain (component: Security).   The supported version that is affected is 21.1.0. Easily exploitable vulnerability allows unauthenticated at |
| CVE-2026-127328 | 8.1 | n/a | Vulnerability in the Oracle AutoVue product of Oracle Supply Chain (component: Security).   The supported version that is affected is 21.1.0. Difficult to exploit vulnerability allows unauthenticated  |
| CVE-2026-127329 | 8.1 | n/a | Vulnerability in the Oracle AutoVue product of Oracle Supply Chain (component: Security).   The supported version that is affected is 21.1.0. Difficult to exploit vulnerability allows unauthenticated  |
| CVE-2026-127330 | 8.1 | n/a | Vulnerability in the Oracle AutoVue product of Oracle Supply Chain (component: Security).   The supported version that is affected is 21.1.0. Difficult to exploit vulnerability allows unauthenticated  |
| CVE-2026-127372 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Financial Close Management product of Oracle Hyperion (component: Reconciliation Manage).   The supported version that is affected is 11.2.26.0.000. Easily exploit |
| CVE-2026-127402 | 8.1 | n/a | Vulnerability in the Oracle AutoVue product of Oracle Supply Chain (component: Security).   The supported version that is affected is 21.1.0. Difficult to exploit vulnerability allows unauthenticated  |
| CVE-2026-127415 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Lifecycle Management).   The supported version that is affected is 11.2.26.0.000. Easily exploitab |
| CVE-2026-127416 | 8.1 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Lifecycle Management).   The supported version that is affected is 11.2.26.0.000. Easily exploitab |
| CVE-2026-127425 | 8.1 | n/a | Vulnerability in the Oracle VM VirtualBox product of Oracle Virtualization (component: Core).   The supported version that is affected is 7.2.22. Easily exploitable vulnerability allows high privilege |
| CVE-2026-91522 | 8.1 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Difficult to ex |
| CVE-2026-105929 | 8.1 | n/a | A path traversal vulnerability (CWE-22) was found in ansible-core's ansible-galaxy role installation. An explicit role "name" taken from a role's meta/requirements.yml is used to construct the on-disk |
| CVE-2026-130644 | 8.1 | n/a | A path traversal flaw was found in ansible-core. When installing a collection with ansible-galaxy collection install, the install destination directory is derived from the namespace and name fields de |
| CVE-2025-15716 | 8.1 | n/a | An incorrect implementation of authentication algorithm vulnerability in the SSO API in Synology DiskStation Manager (DSM) before 7.2.2-72806-5 and 7.3.1-86003-1 (7.2.1-69057 is not affected) allows r |
| CVE-2026-127337 | 7.9 | n/a | Vulnerability in the Oracle AutoVue product of Oracle Supply Chain (component: Security).   The supported version that is affected is 21.1.0. Easily exploitable vulnerability allows unauthenticated at |
| CVE-2026-114792 | 7.8 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: Installation).  Supported versions that are affected are 8.2.0.0.0, 12.2.1.4.0 and  26.01.0 |
| CVE-2026-114793 | 7.8 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: Analytics Server).  Supported versions that are affected are 8.2.0.0.0, 12.2.1.4.0 and  26. |
| CVE-2026-114794 | 7.8 | n/a | Vulnerability in the Oracle Business Intelligence Enterprise Edition product of Oracle Analytics (component: Platform Security).  Supported versions that are affected are 8.2.0.0.0 and  26.01.0.0.0. E |
| CVE-2026-114818 | 7.8 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-114828 | 7.8 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-114861 | 7.8 | n/a | Vulnerability in Oracle Application Testing Suite (component: OpenScript).   The supported version that is affected is 13.3.0.1. Easily exploitable vulnerability allows low privileged attacker with lo |
| CVE-2026-114931 | 7.8 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Test Framework).  Supported versions that are affected are 8.61-8.63. Difficult to exploit vulnerability |
| CVE-2026-131871 | 7.8 | n/a | WLA DX 9.7 through 10.7 contains a stack-based buffer overflow vulnerability in parse_data_blocks() in wlalink/analyze.c that copies section namespaces without length checks. Attackers can supply a cr |
| CVE-2026-114809 | 7.7 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vulnerability allows low p |
| CVE-2026-114874 | 7.7 | n/a | Vulnerability in the Oracle iProcurement product of Oracle E-Business Suite (component: Internal operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability |
| CVE-2026-115076 | 7.7 | n/a | Vulnerability in the Oracle Hyperion Financial Close Management product of Oracle Hyperion (component: Reconciliation Manage).   The supported version that is affected is 11.2.26.0.000. Easily exploit |
| CVE-2026-115129 | 7.7 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vulnerability allows low p |
| CVE-2026-115158 | 7.7 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115170 | 7.7 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Common Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vu |
| CVE-2026-127349 | 7.7 | n/a | Vulnerability in the Oracle Hyperion Financial Close Management product of Oracle Hyperion (component: Reconciliation Manage).   The supported version that is affected is 11.2.26.0.000. Easily exploit |
| CVE-2026-127392 | 7.7 | n/a | Vulnerability in the Product Lifecycle Analytics product of Oracle Supply Chain (component: Installation Issues).   The supported version that is affected is 3.6.1. Difficult to exploit vulnerability  |
| CVE-2026-114865 | 7.6 | n/a | Vulnerability in the Oracle Sales Online product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability |
| CVE-2026-114866 | 7.6 | n/a | Vulnerability in the Oracle Sales Online product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability |
| CVE-2026-115058 | 7.6 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Common Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vu |
| CVE-2026-115117 | 7.6 | n/a | Vulnerability in the Oracle Hyperion Financial Management product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vulnerability  |
| CVE-2026-115143 | 7.6 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115176 | 7.6 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-127340 | 7.6 | n/a | Vulnerability in the Oracle Hyperion Financial Close Management product of Oracle Hyperion (component: Reconciliation Manage).   The supported version that is affected is 11.2.26.0.000. Easily exploit |
| CVE-2026-130374 | 7.5 | 0.4% | AdminNeo before 5.9.1 contains an sql injection vulnerability that allows remote attackers to inject SQL by supplying crafted IN and NOT IN search values that process_length() passes unescaped. Attack |
| CVE-2026-77224 | 7.5 | n/a | Camunda 7.24.0 before 7.24.14 and 7.23.0 before 7.23.17 contains an XML External Entity (XXE) injection vulnerability in the camunda-external-task-client's DomXmlDataFormat.defaultDocumentBuilderFacto |
| CVE-2026-130841 | 7.5 | n/a | ioBroker.lovelace before 7.0.0 contains a path traversal vulnerability in the onCards() request handler that allows unauthenticated remote attackers to read arbitrary files via unsanitized dot-dot seg |
| CVE-2026-130874 | 7.5 | n/a | Seerr before 3.5.2 contains an uncontrolled resource consumption vulnerability that allows unauthenticated attackers to exhaust disk space through unnormalized /imageproxy cache keys. Attackers can re |
| CVE-2026-101693 | 7.5 | n/a | Vulnerability in the Oracle Hyperion Financial Data Quality Management, Enterprise Edition product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000.  |
| CVE-2026-114799 | 7.5 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vulnerability allows unaut |
| CVE-2026-114846 | 7.5 | n/a | Vulnerability in the Oracle Financial Services Customer Screening product of Oracle Financial Services Applications (component: User Interface).   The supported version that is affected is 8.1.2.10. E |
| CVE-2026-114864 | 7.5 | n/a | Vulnerability in the Oracle Sales Online product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerabili |
| CVE-2026-114882 | 7.5 | n/a | Vulnerability in the Oracle Product Workbench product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerab |
| CVE-2026-114885 | 7.5 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Admin UI).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability al |
| CVE-2026-114901 | 7.5 | n/a | Vulnerability in the Oracle E-Business Suite Integrated SOA Gateway product of Oracle E-Business Suite (component: SOA Provider).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to |
| CVE-2026-114906 | 7.5 | n/a | Vulnerability in the Oracle Purchasing product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability |
| CVE-2026-114907 | 7.5 | n/a | Vulnerability in the Oracle Purchasing product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability |
| CVE-2026-114911 | 7.5 | n/a | Vulnerability in the Oracle iProcurement product of Oracle E-Business Suite (component: Approval List and Workflow).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulner |
| CVE-2026-114912 | 7.5 | n/a | Vulnerability in the Oracle Purchasing product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability |
| CVE-2026-114929 | 7.5 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Application Server).  Supported versions that are affected are 8.61-8.63. Difficult to exploit vulnerabi |
| CVE-2026-114930 | 7.5 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Application Server).  Supported versions that are affected are 8.61-8.63. Difficult to exploit vulnerabi |
| CVE-2026-114935 | 7.5 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Integration Broker).  Supported versions that are affected are 8.61-8.63. Easily exploitable vulnerabili |
| CVE-2026-114955 | 7.5 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-114977 | 7.5 | n/a | Vulnerability in the Siebel CRM Deployment product of Oracle Siebel CRM (component: Siebel Management Console).  Supported versions that are affected are 17.0-26.9. Easily exploitable vulnerability al |
| CVE-2026-114981 | 7.5 | n/a | Vulnerability in the Oracle AutoVue product of Oracle Supply Chain (component: Security Related Issues).   The supported version that is affected is 21.1.0. Difficult to exploit vulnerability allows l |
| CVE-2026-115065 | 7.5 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Diffic |
| CVE-2026-115101 | 7.5 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Difficult to exploit vulnerability allows low |
| CVE-2026-115146 | 7.5 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115155 | 7.5 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Diffic |
| CVE-2026-127351 | 7.5 | n/a | Vulnerability in the Oracle Hyperion Financial Close Management product of Oracle Hyperion (component: Reconciliation Manage).   The supported version that is affected is 11.2.26.0.000. Easily exploit |
| CVE-2026-127373 | 7.5 | n/a | Vulnerability in the Oracle Hyperion Financial Close Management product of Oracle Hyperion (component: Reconciliation Manage).   The supported version that is affected is 11.2.26.0.000. Easily exploit |
| CVE-2026-83365 | 7.5 | n/a | Vulnerability in the Oracle Purchasing product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability |
| CVE-2026-91551 | 7.5 | n/a | Vulnerability in the Oracle Platform Security for Java product of Oracle Fusion Middleware (component: Centralized Thirdparty Jars).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0. |
| CVE-2026-91564 | 7.5 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploita |
| CVE-2026-131857 | 7.5 | n/a | Supergateway 4.2.0 through 4.2.2 contains a denial of service vulnerability in stdio-to-SSE mode that allows unauthenticated attackers to crash the gateway via prototype-inherited sessionId values. At |
| CVE-2026-130838 | 7.4 | n/a | Radicale 3.3.0 before 3.8.3 contains an authorization bypass vulnerability that allows unauthenticated attackers to inherit group-based rights by reusing group memberships never reset between requests |
| CVE-2026-130868 | 7.4 | n/a | GreaterWMS through 2.1.54 contains a predictable authentication token vulnerability that allows unauthenticated attackers to forge openid tokens by recomputing an unsalted MD5 hash of username and reg |
| CVE-2026-130870 | 7.4 | n/a | ClearFlask before 2.7.3 contains an improper authorization vulnerability that allows any account holding an invitation ID to accept it regardless of invited email. Attackers who obtain a forwarded or  |
| CVE-2026-101663 | 7.4 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Admin UI).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability  |
| CVE-2026-101848 | 7.4 | n/a | Vulnerability in the Oracle Hyperion Financial Data Quality Management, Enterprise Edition product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000.  |
| CVE-2026-114872 | 7.4 | n/a | Vulnerability in the Oracle Sales Online product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability |
| CVE-2026-114877 | 7.4 | n/a | Vulnerability in the Oracle iStore product of Oracle E-Business Suite (component: Shopping Cart).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploit vulnerability allows un |
| CVE-2026-114894 | 7.4 | n/a | Vulnerability in the Oracle Universal Work Queue product of Oracle E-Business Suite (component: Media Integration issues).  Supported versions that are affected are 12.2.3-12.2.15. Difficult to exploi |
| CVE-2026-114903 | 7.4 | n/a | Vulnerability in the Oracle E-Business Suite Integrated SOA Gateway product of Oracle E-Business Suite (component: Web Service Provider).  Supported versions that are affected are 12.2.3-12.2.15. Diff |
| CVE-2026-114939 | 7.4 | n/a | Vulnerability in the Oracle Java SE, Oracle GraalVM for JDK, Oracle GraalVM Enterprise Edition product of Oracle Java SE (component: JGSS).  Supported versions that are affected are Oracle Java SE: 8u |
| CVE-2026-114940 | 7.4 | n/a | Vulnerability in the Oracle Java SE, Oracle GraalVM for JDK, Oracle GraalVM Enterprise Edition product of Oracle Java SE (component: JSSE).  Supported versions that are affected are Oracle Java SE: 8u |
| CVE-2026-115053 | 7.4 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Diffic |
| CVE-2026-115124 | 7.4 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Difficult to exploit vulnerability allows una |
| CVE-2026-115138 | 7.4 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Difficult to exploit vulnerability allows una |
| CVE-2026-115140 | 7.4 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Difficult to exploit vulnerability allows una |
| CVE-2026-115141 | 7.4 | n/a | Vulnerability in the Oracle Hyperion Planning product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Difficult to exploit vulnerability allows una |
| CVE-2026-115160 | 7.4 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Common Security).   The supported version that is affected is 11.2.26.0.000. Difficult to exploit  |
| CVE-2026-115163 | 7.4 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Common Security).   The supported version that is affected is 11.2.26.0.000. Difficult to exploit  |
| CVE-2026-115178 | 7.4 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Diffic |
| CVE-2026-127360 | 7.4 | n/a | Vulnerability in the Oracle Hyperion Financial Close Management product of Oracle Hyperion (component: Reconciliation Manage).   The supported version that is affected is 11.2.26.0.000. Difficult to e |
| CVE-2026-127426 | 7.4 | n/a | Vulnerability in the Oracle VM VirtualBox product of Oracle Virtualization (component: Core).   The supported version that is affected is 7.2.22. Easily exploitable vulnerability allows unauthenticate |
| CVE-2026-91586 | 7.4 | n/a | Vulnerability in the Oracle WebCenter Portal product of Oracle Fusion Middleware (component: Composer).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.0.0. Easily exploitable vulnera |
| CVE-2026-131848 | 7.4 | n/a | Snap7 through 1.4.3 contains an out-of-bounds write vulnerability in TSnap7MicroClient::opReadMultiVars() that allows malicious PLCs to overflow client buffers via unchecked DataLength fields. Attacke |
| CVE-2026-131849 | 7.4 | n/a | Snap7 through 1.4.3 contains a heap-based buffer overflow in TSnap7MicroClient::opReadSZL() that allows malicious PLCs to overwrite client memory by sending oversized multi-slice SZL responses. A rogu |
| CVE-2026-114869 | 7.3 | n/a | Vulnerability in the Applications DBA product of Oracle E-Business Suite (component: AD Utilities).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows lo |
| CVE-2026-114888 | 7.3 | n/a | Vulnerability in the Oracle Mobile Field Service product of Oracle E-Business Suite (component: Admin UI).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability al |
| CVE-2026-91540 | 7.3 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Difficult to ex |
| CVE-2026-82025 | 7.2 | n/a | WP File Manager before 8.0.7 contains a file upload restriction bypass vulnerability that allows authenticated administrators to upload arbitrary PHP files by exploiting a misconfigured elFinder conne |
| CVE-2026-130853 | 7.2 | n/a | Nexterm through 1.2.2-BETA contains a privilege escalation vulnerability that allows users with permissions.manage to gain unauthorized permissions because addGroupMember and setUserGroups lack the gr |
| CVE-2026-101838 | 7.2 | n/a | Vulnerability in the Oracle Contracts product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability al |
| CVE-2026-101839 | 7.2 | n/a | Vulnerability in the Oracle Contracts product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability al |
| CVE-2026-114883 | 7.2 | n/a | Vulnerability in the Oracle Teleservice product of Oracle E-Business Suite (component: Service Request Form).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability |
| CVE-2026-114884 | 7.2 | n/a | Vulnerability in the Oracle Lease and Finance Management product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitab |
| CVE-2026-114902 | 7.2 | n/a | Vulnerability in the Oracle Product Hub product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability  |
| CVE-2026-114927 | 7.2 | n/a | Vulnerability in the PeopleSoft Enterprise PeopleTools product of Oracle PeopleSoft (component: Report Distribution).  Supported versions that are affected are 8.61-8.63. Easily exploitable vulnerabil |
| CVE-2026-114949 | 7.2 | n/a | Vulnerability in the MySQL Server, MySQL Cluster product of Oracle MySQL (component: Server: Replication).  Supported versions that are affected are MySQL Server: 8.4.0-8.4.13, 9.7.0-9.7.4, 26.10; MyS |
| CVE-2026-114950 | 7.2 | n/a | Vulnerability in the MySQL Server, MySQL Cluster product of Oracle MySQL (component: Server: Optimizer).  Supported versions that are affected are MySQL Server: 8.4.0-8.4.13, 9.7.0-9.7.4, 26.10; MySQL |
| CVE-2026-114951 | 7.2 | n/a | Vulnerability in the MySQL Server, MySQL Cluster product of Oracle MySQL (component: Server: Logging).  Supported versions that are affected are MySQL Server: 8.4.0-8.4.13, 9.7.0-9.7.4, 26.10; MySQL C |
| CVE-2026-115072 | 7.2 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-127394 | 7.2 | n/a | Vulnerability in the Product Lifecycle Analytics product of Oracle Supply Chain (component: Installation Issues).   The supported version that is affected is 3.6.1. Difficult to exploit vulnerability  |
| CVE-2026-91498 | 7.2 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploita |
| CVE-2026-91531 | 7.2 | n/a | Vulnerability in the Oracle Access Manager product of Oracle Fusion Middleware (component: Authentication Engine).  Supported versions that are affected are 12.2.1.4.0 and  14.1.2.1.0. Easily exploita |
| CVE-2026-131850 | 7.2 | n/a | ILIAS 11.0 before 11.6 contains an sql injection vulnerability in RegistrationCodeRepository::getCodesData() that concatenates unvalidated sort fields into an ORDER BY clause. Authenticated users with |
| CVE-2026-130121 | 7.2 | n/a | The AI Puffer - MCP Server for Claude & ChatGPT, with AI Chatbot plugin for WordPress is vulnerable to Stored Cross-Site Scripting via AI-generated comment replies in all versions up to, and including |
| CVE-2026-111825 | 7.2 | n/a | The Event Tickets with Ticket Scanner plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'code' parameter in all versions up to, and including, 3.3.1 due to insufficient input s |
| CVE-2026-130615 | 7.1 | n/a | Flowise through 3.1.4 contains a server-side request forgery vulnerability that allows authenticated users to reach internal services by exploiting unpinned DNS validation in checkDenyList(). Attacker |
| CVE-2026-114867 | 7.1 | n/a | Vulnerability in the Oracle Sales Online product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability |
| CVE-2026-114873 | 7.1 | n/a | Vulnerability in the Oracle iProcurement product of Oracle E-Business Suite (component: Internal operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability |
| CVE-2026-114878 | 7.1 | n/a | Vulnerability in the Oracle iStore product of Oracle E-Business Suite (component: Shopping Cart).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows low  |
| CVE-2026-114898 | 7.1 | n/a | Vulnerability in the Applications DBA product of Oracle E-Business Suite (component: AD Utilities).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability allows lo |
| CVE-2026-114913 | 7.1 | n/a | Vulnerability in the Oracle Purchasing product of Oracle E-Business Suite (component: Internal Operations).  Supported versions that are affected are 12.2.3-12.2.15. Easily exploitable vulnerability a |
| CVE-2026-114915 | 7.1 | n/a | Vulnerability in the Oracle E-Business Suite Secure Enterprise Search product of Oracle E-Business Suite (component: Search Integration Engine).  Supported versions that are affected are 12.2.3-12.2.1 |
| CVE-2026-115057 | 7.1 | n/a | Vulnerability in the Oracle Hyperion Financial Management product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vulnerability  |
| CVE-2026-115061 | 7.1 | n/a | Vulnerability in the Oracle Hyperion Financial Management product of Oracle Hyperion (component: Security).   The supported version that is affected is 11.2.26.0.000. Easily exploitable vulnerability  |
| CVE-2026-115063 | 7.1 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115064 | 7.1 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115159 | 7.1 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-115177 | 7.1 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Easily |
| CVE-2026-127319 | 7.1 | n/a | Vulnerability in the Oracle AutoVue product of Oracle Supply Chain (component: Security).   The supported version that is affected is 21.1.0. Easily exploitable vulnerability allows low privileged att |
| CVE-2026-127339 | 7.1 | n/a | Vulnerability in the Oracle AutoVue product of Oracle Supply Chain (component: Security).   The supported version that is affected is 21.1.0. Easily exploitable vulnerability allows unauthenticated at |
| CVE-2026-127414 | 7.1 | n/a | Vulnerability in the Oracle VM VirtualBox product of Oracle Virtualization (component: Core).   The supported version that is affected is 7.2.22. Easily exploitable vulnerability allows unauthenticate |
| CVE-2026-127422 | 7.1 | n/a | Vulnerability in the Oracle VM VirtualBox product of Oracle Virtualization (component: Core).   The supported version that is affected is 7.2.22. Easily exploitable vulnerability allows unauthenticate |
| CVE-2026-127423 | 7.1 | n/a | Vulnerability in the Oracle VM VirtualBox product of Oracle Virtualization (component: Core).   The supported version that is affected is 7.2.22. Easily exploitable vulnerability allows unauthenticate |
| CVE-2026-127428 | 7.1 | n/a | Vulnerability in the MySQL Server, MySQL Cluster product of Oracle MySQL (component: Server: GIS).  Supported versions that are affected are MySQL Server: 8.4.0-8.4.13, 9.7.0-9.7.4, 26.10; MySQL Clust |
| CVE-2026-114941 | 7.0 | n/a | Vulnerability in the Oracle Java SE, Oracle GraalVM for JDK product of Oracle Java SE (component: Compiler).  Supported versions that are affected are Oracle Java SE: 21.0.13.0.3, 25.0.5.0.3 and  27.0 |
| CVE-2026-114942 | 7.0 | n/a | Vulnerability in the Oracle Java SE, Oracle GraalVM for JDK product of Oracle Java SE (component: Libraries).  Supported versions that are affected are Oracle Java SE: 21.0.13.0.3, 25.0.5.0.3 and  27. |
| CVE-2026-115077 | 7.0 | n/a | Vulnerability in the Oracle Hyperion Infrastructure Technology product of Oracle Hyperion (component: Installation and Configuration).   The supported version that is affected is 11.2.26.0.000. Diffic |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-g36v-f88g-q47m | CVE-2026-99319 | unknown | In the Linux kernel, the following vulnerability has been resolved:

ALSA: usx2y: Refuse a... |
| GHSA-rpw6-x7gj-hpxv | CVE-2026-99316 | unknown | In the Linux kernel, the following vulnerability has been resolved:

ALSA: usx2y: Initialize idle... |
| GHSA-5vmm-5wj9-f8xg | CVE-2026-99318 | unknown | In the Linux kernel, the following vulnerability has been resolved:

ALSA: bcd2000: Fix use-after... |
| GHSA-fjcx-325h-xfm2 | CVE-2026-99315 | unknown | In the Linux kernel, the following vulnerability has been resolved:

ALSA: us122l: Fix NULL... |
| GHSA-q89r-8hpp-x2pq | CVE-2026-99317 | unknown | In the Linux kernel, the following vulnerability has been resolved:

ALSA: hwdep: Serialize DSP... |
| GHSA-pr85-mhwv-8mh8 | CVE-2026-99313 | unknown | In the Linux kernel, the following vulnerability has been resolved:

HID: logitech-hidpp: fix... |
| GHSA-66f5-gvww-56pm | CVE-2026-99314 | unknown | In the Linux kernel, the following vulnerability has been resolved:

ALSA: us122l: Add missing... |
| GHSA-8gg9-294g-g2r6 | CVE-2026-99312 | unknown | In the Linux kernel, the following vulnerability has been resolved:

KVM: x86: Unconditionally... |
| GHSA-gwgc-hqh6-hx9r | CVE-2026-95645 | critical | Zohocorp Manageengine DDI Central build below 6500 are affected by a authenticated command... |
| GHSA-gp5r-5mmq-pgr6 | CVE-2026-95643 | critical | Zohocorp Manageengine DDI Central build below 6500 are affected by a authenticated PowerShell... |
| GHSA-3x5q-3r35-5w58 | CVE-2026-1212 | medium | The BuddyPress plugin for WordPress is vulnerable to Insecure Direct Object Reference in all... |
| GHSA-35fq-5c7c-4jhr | CVE-2026-128981 | unknown | ** UNSUPPORTED WHEN ASSIGNED ** 



Improper Authentication in Apache SeaTunnel Web 1.0.2 allows... |
| GHSA-rjfq-5543-h74f | CVE-2026-113497 | high | A low-privileged remote attacker can change the password of arbitrary users using the REST API,... |
| GHSA-6hgh-ffww-cfx5 | CVE-2026-125829 | high | Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal') vulnerability in... |
| GHSA-9r9r-568w-vj4w | CVE-2026-125820 | high | Deserialization of Untrusted Data vulnerability in Rymera Web Co Product Feed PRO for WooCommerce... |
| GHSA-3x8r-v8mp-j7w7 | CVE-2025-15716 | high | An incorrect implementation of authentication algorithm vulnerability in the SSO API in Synology... |
| GHSA-979c-m8xq-mqm2 | CVE-2026-2841 | medium | The Advanced Custom Fields (ACF) plugin for WordPress is vulnerable to incorrect authorization in... |
| GHSA-4ph3-f4w6-p5pw | CVE-2026-1209 | medium | The BuddyPress plugin for WordPress is vulnerable to unauthorized modification of data due to a... |
| GHSA-38r2-fx53-wvrq | CVE-2025-2235 | high | Improper Verification of Cryptographic Signature vulnerability in OpenText™ Connected MX allows... |
| GHSA-98hp-mqh6-77pj | CVE-2026-131922 | medium | In OpenStack keystonemiddleware before 13.0.3, by supplying a malicious regular expression when... |
| GHSA-5hqm-5j9g-jhcr | CVE-2026-131959 | high | GNU Emacs 31.1 contains a code injection vulnerability in its handling of directory-local... |
| GHSA-xrpq-2pv7-g346 | CVE-2026-131920 | medium | In OpenStack Cinder before 29.1.1, by making an os-initialize_connection request with an IQN that... |
| GHSA-fhgr-9vcx-f74c | CVE-2026-97330 | unknown | The Team Members WordPress plugin before 5.4.2 does not properly escape team member social link... |
| GHSA-3frm-cm8h-4v9j | CVE-2026-123662 | unknown | The ProfilePress  WordPress plugin before 4.18.1 does not atomically consume the source... |
| GHSA-mh7c-5mc9-hjhp | CVE-2026-97329 | unknown | The Team Members WordPress plugin before 5.4.2 does not properly escape a team member field when... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| FAIR Health, Inc. (fairhealth.com) | PixelLeaks | US | 2026-11-18T06:34:32.383143+00:00 |
| Wei Tai Leather Viet Nam Co., Ltd (weitai-leather.com) | PixelLeaks | VN | 2026-11-18T05:37:41.792708+00:00 |
| TopGroup | Aoqin | AR | 2026-11-18T05:20:25.862584+00:00 |
| Mnfhs | Helix |  | 2026-11-18T02:51:10.787870+00:00 |
| KDBS Solutions (client hosting) | PixelLeaks |  | 2026-11-18T01:07:38.221316+00:00 |
| Proymoda (proymoda.com.mx) | PixelLeaks | MX | 2026-11-18T01:07:18.469939+00:00 |
| Veritiv | Helix | US | 2026-11-18T00:51:25.437023+00:00 |
| Meridian Capital Group | qilin | US | 2026-11-18T01:23:36.393092+00:00 |
| Drive Medical - 1,442,814 records | Vortex | US | 2026-11-17T23:08:12.087534+00:00 |
| Sonoco | Helix | US | 2026-11-17T19:22:15.183182+00:00 |
| West-Com Nurse Call Systems, Inc | EndZone | US | 2026-11-17T19:21:35.634498+00:00 |
| examinetics.com | Curious Worm | US | 2026-11-17T18:24:03.586279+00:00 |
| intelligentaudit.com | BrainCipher | US | 2026-11-17T18:23:27.116546+00:00 |
| roedentallab.com | BrainCipher | DE | 2026-11-17T18:22:52.722027+00:00 |
| edi-uae.com | BrainCipher | AE | 2026-11-17T18:22:17.400646+00:00 |
| havingbabies.com | BrainCipher | AU | 2026-11-17T18:21:42.363347+00:00 |
| Esco Optics | Aoqin | US | 2026-11-17T18:20:29.660575+00:00 |
| WWGlas | payload | DE | 2026-11-17T17:59:26.888478+00:00 |
| Christine London Ltd | Aoqin | US | 2026-11-17T16:20:32.648156+00:00 |
| Van der Spek Vianen B.V. | rhysida | NL | 2026-11-17T16:09:44.289222+00:00 |

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
| 77.239.124.252 | 10 |
| 138.226.239.233 | 10 |
| 138.226.239.234 | 10 |
| 3.129.187.38 | 9 |
| 35.210.7.114 | 9 |
| 45.148.10.151 | 9 |
| 45.148.10.157 | 9 |
| 66.132.186.187 | 9 |
| 167.94.146.48 | 9 |
| 193.32.162.15 | 9 |
| 18.116.101.220 | 8 |
| 35.206.163.251 | 8 |
| 35.210.13.61 | 8 |
| 35.210.19.131 | 8 |
| 35.210.65.254 | 8 |
| 35.210.150.149 | 8 |
| 45.148.10.152 | 8 |
| 46.151.178.14 | 8 |
| 62.60.130.148 | 8 |

### OpenPhish (live phishing URLs)
- https://mapslocatlphone.help/isignesp.php
- https://spi86.com/
- http://info-resmi325.blogspot.com/
- https://infohadiah-shopee74.blogspot.com/?m=1
- https://bump-sigverify-masterpda.pages.dev/
- https://icloudvsmapalocaliza.click/isignesp.php?correo=-&id=172974
- https://us-start.framer.website/
- http://claimyourrbux24kkofficial.blogspot.com/?m=1
- http://gebyar-shope20.blogspot.com/
- https://pengudiansh0pee.blogspot.com/?m=1
- http://ptshopee-5777.blogspot.com/
- https://irs-gov-report.netlify.app/
- https://krishvermaxd-spec.github.io/netflix-clone
- https://sevenseven712.github.io/xn
- https://im.nbpublic.com/loading_page_cpl/amazon/amazon_cf_2/index.html?lptoken=170859fa7232506226c1&cep=N4Igdgpg7g+gFgSwC4wQExALhAMwKwDseOAjASQLQAcaBEFALAEYCGAzBSwGxcEVNUADHlpcmDKmwCcIADQgAbggDOyVBmwAmQdM0txjYQ0ZMR/QWhYU8XKYIDGJXhEIQ5ilWqQIAthGVILD4ADlgg2pp4FCSCFIJcACqCDJiCgpiaXAB0DASaAFruSqpIAPYATuphJFJoUnhSJJRMBPZRDJoEsVIQOJoU9rYsEI5ogySa7vZBwSwIAOZgVdhcVMMsBGg0JBCCJPZpE1wQEC
- https://mtvlj86vzt-qnkxzlpw-4j9k2g-mtv614.pages.dev/
- https://sp25ct11-rulvaku-biz-vemzaro.pages.dev/
- https://sp25ct11-zorkelo-biz-nuvmari.pages.dev/
- http://sp25ct11-nuvzaro-biz-melruni.pages.dev/
- http://5n0q7x2-m8v1k9p-3z6d4.pages.dev/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://bteemail.durablesites.com/unpublished |
| N/A | https://shell.jsaqwe.asia/kDPYKWmt/ |
| N/A | https://credito-ecuador-amarillo.lovable.app/blocked |
| N/A | https://away.vk.ru/away.php?rh=3ed6f644-bc11-4fb6-91f6-b8f52b0f2c9a |
| N/A | https://mon-espace-client.sofinco.monserviceaconnexion.com/secure/auth/verify?session_token=8PnpSIjDWHmIw8J1y22eNZPI5oWQW9KaDqSKX1LunPdWJOUTQLpEJ5S6jix9u3Qx&src=8PnpSIjDWHmIw8J1 |
| N/A | https://linqapp.com/xdsfaeag?r=link |
| N/A | https://sso.cuban.workers.dev/ |
| N/A | https://jacklouiss1792573888000.1200165.meusitehostgator.com.br/cz/a/dir95796c8e76/ |
| N/A | https://away.vk.ru/away.php?rh=07627779-65c5-4285-bd15-9474bffbd308 |
| N/A | https://www.gtvinerti.com/ |
| N/A | https://flat-bread-04ca.cloudflareaccess.com/cdn-cgi/access/login/vertiv-command-center.pages.dev?kid=617efb6eb0445e77d08421b7c2075c08ed7302463271c62a28d702c82772462a&meta=eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiIsImtpZCI6IjEyY2U5NjlmMDk3YjUyNjliNjllZjA0N2EwMjBiZGI2NGMwMTc5NjMwNzE3MzJhMWJjODg2NjJiNGUxYzJjY2IifQ.eyJ0eXBlIjoibWV0YSIsImF1ZCI6IjYxN2VmYjZlYjA0NDVlNzdkMDg0MjFiN2MyMDc1YzA4ZWQ3MzAyNDYzMjcxYzYyYTI4ZDcwMmM4Mjc3MjQ2MmEiLCJob3N0bmFtZSI6InZlcnRpdi1jb21tYW5kLWNlbnRlci5wYWdlcy5kZXYiLCJyZWRpcmVjdF91cmwiOiIvIiwic2VydmljZV90b2tlbl9zdGF0dXMiOmZhbHNlLCJpc193YXJwIjpmYWxzZSwiaXNfZ2F0ZXdheSI6ZmFsc2UsImV4cCI6MTc5NTAwMDI4OCwibmJmIjoxNzk0OTk5OTg4LCJpYXQiOjE3OTQ5OTk5ODgsImF1dGhfc3RhdHVzIjoiTk9ORSIsIm10bHNfYXV0aCI6eyJjZXJ0X2lzc3Vlcl9kbiI6IiIsImNlcnRfc2VyaWFsIjoiIiwiY2VydF9pc3N1ZXJfc2tpIjoiIiwiY2VydF9wcmVzZW50ZWQiOmZhbHNlLCJjb21tb25fbmFtZSI6IiIsImF1dGhfc3RhdHVzIjoiTk9ORSJ9LCJyZWFsX2NvdW50cnkiOiJVUyIsImFwcF9zZXNzaW9uX2hhc2giOiI3NTM5NmFlNDFmY2YxYzBjN2FlZDI0MmZlMjE3YTI1NjM5YjZkNzJiOGU5NDhlNzMwMzkxZWUyMGI0ZDNlNzJlIn0.LdTCnDcaZQdyFmULlMzlcRhQKqhfHYn2ouGSy3qIe5CvGPwXISY2LURLCeOsrVVGLVY_zTrjkVuJc3moON5e2UwKoxXr54LVyBB0DX5WVqNkRDD5r5KhGGGswnkXDSMU7yrkPejgZjMmKzRVutXNvjfFna0a8fDFDq-ytTOk9Qbol3t44JI-uzuihKEDf0k50uNg6dksSUJGXHaeopnd4bOJB7AKUm9Gxd_XATGCea-ffSGl1zimoBlkbatpXeP2eKHr01YJHRw_I91EKh_ZTSnK2WuLMqUc3cZ_qVYk011yQ4iOMdEIoTcNdIFcwfPYAlJKE19BT2THiLGOqyv4uA&redirect_url=%2F |
| N/A | https://www.att.com/activearmorapp?_branch_match_id=1651555921885719743&utm_source=AT%26T%20App&_branch_referrer=H4sIAAAAAAAAA8soKSkottLXT0wuySxLTSzKzS%2FSzS%2FKTM%2FM00ssKdFLzs%2FV9wtL8U6KLCzzMUqyrytKTUstKsrMS49PKsovL04tsnXOKMrPTQUAZUf3KkgAAAA%3D |
| N/A | http://away.vk.ru/away.php?rh=eff1051f-8c0a-4b67-83f3-e854dce6172c |
| N/A | https://encryptdrive.booogle.net/?state=%7Bids:%5B1zsW2sDoRx1jgl1y1_XDtGIxXpkoMS27F%5D |
| N/A | https://vdbjpmeaqqjzpwxfflbjfmeykyxvcfgmhjbad.blogspot.com/ |
| N/A | https://allegrolokalnie.6710014.cc/ |
| N/A | https://near.tl/sm/J2z8mAaW- |
| N/A | https://away.vk.ru/away.php?rh=f21e542a-84e3-4fb5-8123-57a4af6abc18 |
| N/A | https://pub-4974a8d9bd7347c7a61b9b091e3f09e1.r2.dev/usa/index.html |
| N/A | https://trim.one |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| c2c7c65a60e250f94f78944558c5db7d8086dca4 | PureLogsStealer C&C |
| 5d4337304f628324e97723e352148d9d259ef3c3 | FennecRAT C&C |
| 13b6b2f68e58287e1fbe149b9ae41f5259406f38 | Malware C&C |
| c51052b024b7b8fd7afff4c0912d6c00b3d2eb05 | ACRStealer C&C |
| 203fb6154172879c08291fefb46062b27eb73f55 | ConnectWise C&C |
| 52a71237e3ce64976990f68f176eb8a8c1daa052 | Malware C&C |
| 110dc32c90365e41ccfc8eaf47b89c8f5adc45fc | WARDENStealer C&C |
| d36e7ea8c3bd11f3d64e2a454ca1850566a63df7 | PureRAT C&C |
| dd35950dcdc0d2afeb557ff622375cdafe938fc5 | Vidar C&C |
| 29a612773b379e945229a831f7d69280a2b0fd49 | Vidar C&C |
| 36210d41f78bcf7c4e3dcd32a9c6ea0392c435c2 | xeffStealer C&C |
| 4ab5b2103cc4653d78269daad5fdb8f598705843 | OffLoader C&C |
| 5ce11a4cab0a83a5675d71c4af0804e1c0843c94 | Vidar C&C |
| beb63a581c0b40874ca784c11aaabf1de9dd6a79 | OffLoader C&C |
| 6af7a067b7cb261c98b699435c964976685bfa32 | PureLogsStealer C&C |
| f9e5d2b65403f7a11c01ac424729c955c6b4f177 | ACRStealer C&C |
| 3dbb965b25e91a542ec6259e8aed5b1f1a0b4b32 | PureRAT C&C |
| 2f595bf93f35afe2252bb41c6f98372c9c258222 | PureLogsStealer C&C |
| b21e09ffa024b5a70529a23685341835fe70ee8e | Vidar C&C |
| f2584ca3bfd03dbc915a3d433ffc42f96c78bfb6 | MopsStealer C&C |

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
- 1.0.132.44
- 1.1.220.166
- 1.100.15.8
- 1.13.156.111
- 1.13.22.101
- 1.13.79.149
- 1.14.240.247
- 1.163.28.132
- 1.164.109.132
- 1.192.216.175
- 1.2.252.192
- 1.20.178.157
- 1.20.184.8
- 1.203.149.250
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.220.198.126
- 1.222.42.237
- 1.234.21.73

### CINS Army (poorly-rated IPs)
- 1.14.3.170
- 1.15.14.29
- 1.168.168.47
- 1.177.162.2
- 1.179.240.157
- 1.193.102.128
- 1.20.151.114
- 1.224.163.125
- 1.24.16.102
- 1.24.16.11
- 1.24.16.110
- 1.24.16.111
- 1.24.16.112
- 1.24.16.113
- 1.24.16.115
- 1.24.16.116
- 1.24.16.125
- 1.24.16.129
- 1.24.16.136
- 1.24.16.140

## News (last ~36h, across outlets)
### The Hacker News
- [Hackers Exploiting Critical Puppet RCE Flaw Affecting Enterprise Management Servers](https://thehackernews.com/2026/11/hackers-exploiting-critical-puppet-rce.html)
- [CISA Urges Immediate Patching of Java4Shell Flaw That Could Allow Remote Code Execution](https://thehackernews.com/2026/11/cisa-urges-immediate-patching-of.html)
- [Attackers Compromise Microsoft's Agent Framework PyPI Package to Steal Cloud Credentials](https://thehackernews.com/2026/11/attackers-compromise-microsofts-agent.html)
- [Russian COLD RELIC Hackers Use Stolen Google Workspace Data to Breach Second U.S. Organization](https://thehackernews.com/2026/11/russian-cold-relic-hackers-use-stolen.html)
- [Java4Shell Flaw (CVE-2026-114938) Enables Pre-Auth RCE in Jira, Jenkins, Keycloak and More](https://thehackernews.com/2026/11/java4shell-cve-2026-114938-enables-pre.html)
- [Researchers Claim Two RCE Exploits That Bypass Telegram’s New Android Defenses](https://thehackernews.com/2026/11/researchers-claim-two-rce-exploits-that.html)
- [Oracle to Patch 11 Java Flaws Today as Critical OpenJDK RCE (CVE-2026-114938) Report Emerges](https://thehackernews.com/2026/11/oracle-to-patch-11-java-flaws-today-as.html)
- [Trigram Campaign Impersonates About 50 AI and Blockchain Brands to Target Devs with Infostealers](https://thehackernews.com/2026/11/trigram-campaign-impersonates-about-50.html)
- [Hackers Found a Way Around GitHub SHA Pinning. This Webinar Explains How to Close the Gap](https://thehackernews.com/2026/11/hackers-found-way-around-github-sha.html)
- [Researchers Detail iPhone Flaw That Let Apps Record Audio Despite Denied Microphone Permission](https://thehackernews.com/2026/11/researchers-detail-iphone-flaw-that-let.html)
- [New GitDoor and GraphDoor Backdoors Turn GitHub and SharePoint Into Covert C2 Channels](https://thehackernews.com/2026/11/new-gitdoor-and-graphdoor-backdoors.html)
- [Apple Tightens macOS App Permissions to Limit Data Access Amid AI Agent Security Risks](https://thehackernews.com/2026/11/apple-tightens-macos-app-permissions-to.html)
- [Hijacked Optimizely Scripts Served Card Skimmer and iOS Exploit Kits to CNN, BBC and Zoom Visitors](https://thehackernews.com/2026/11/hijacked-optimizely-scripts-served-card.html)
- [ConnectWise Warns ScreenConnect Attacks Continue as SCKit Targets Unpatched Systems](https://thehackernews.com/2026/11/connectwise-warns-screenconnect-attacks.html)
- [N-able Patches 17 N-central Flaws as Attackers Exploit Earlier Bugs to Deploy Crypto Miners](https://thehackernews.com/2026/11/n-able-patches-17-n-central-flaws-as.html)

### BleepingComputer
- [Apache warns of Roller RCE vulnerability exploited in attacks](https://www.bleepingcomputer.com/news/security/apache-warns-of-roller-rce-vulnerability-exploited-in-attacks/)
- [Microsoft announces Windows Server 2028 with hardened security](https://www.bleepingcomputer.com/news/microsoft/microsoft-announces-windows-server-2028-with-hardened-security/)
- [British Scattered Spider hacker sentenced to 6 years in prison](https://www.bleepingcomputer.com/news/security/british-scattered-spider-hacker-sentenced-to-6-years-in-prison/)
- [Critical Java4Shell flaw allows RCE attacks on major Java applications](https://www.bleepingcomputer.com/news/security/critical-java4shell-flaw-allows-rce-attacks-on-major-java-applications/)
- [Cloud keys leaked in Docker Hub images are stolen within seconds](https://www.bleepingcomputer.com/news/security/cloud-keys-leaked-in-docker-hub-images-are-stolen-within-seconds/)
- [Japan takes Fugaku supercomputer offlline after cyberattack](https://www.bleepingcomputer.com/news/security/japan-takes-fugaku-supercomputer-offlline-after-cyberattack/)
- [Apple reports outages affecting iCloud Mail, AppleCare and more](https://www.bleepingcomputer.com/news/apple/apple-reports-outages-affecting-icloud-mail-applecare-and-more/)
- [Researchers hijack Hugging Face account for popular Kokoro AI model](https://www.bleepingcomputer.com/news/security/researchers-hijack-hugging-face-account-for-popular-kokoro-ai-model/)
- [Tor releases emergency update amid ongoing DDoS attack](https://www.bleepingcomputer.com/news/security/tor-releases-emergency-update-amid-ongoing-ddos-attack/)
- [Flipper Devices launches $399 ‘Flipper One’ Linux-based multi-tool](https://www.bleepingcomputer.com/news/hardware/flipper-devices-launches-399-flipper-one-linux-based-multi-tool/)
- [Inside Modern Phishing Kits Built to Steal Microsoft 365 Sessions](https://www.bleepingcomputer.com/news/security/inside-modern-phishing-kits-built-to-steal-microsoft-365-sessions/)
- [Microsoft testing Remote Lock for lost or stolen Windows devices](https://www.bleepingcomputer.com/news/microsoft/microsoft-testing-remote-lock-for-lost-or-stolen-windows-devices/)
- [Court clears brothers of $25 million Ethereum crypto heist charges](https://www.bleepingcomputer.com/news/security/court-clears-brothers-of-25-million-ethereum-crypto-heist-charges/)
- [Uber notifies drivers of data breach affecting nearly 150,000 people](https://www.bleepingcomputer.com/news/security/uber-notifies-drivers-of-data-breach-affecting-nearly-150-000-people/)
- [Ransomware affiliate suspect extradited to US, faces 27 years in prison](https://www.bleepingcomputer.com/news/security/alleged-inc-lynx-ransomware-affiliate-extradited-to-us-faces-27-years-in-prison/)

### Krebs on Security
- [Attackers Used Optimizely to A/B Test Malware on Top Websites](https://krebsonsecurity.com/2026/11/attackers-used-optimizely-to-a-b-test-malware-on-top-websites/)

### Dark Reading
- [Optimizely Malware Attacks Highlight Third-Party Vendor Risks](https://www.darkreading.com/cyber-risk/optimizely-malware-attacks-third-party-vendor-risks)
- ['TheMailer' Phishing Kit Puts AI in the Driver's Seat](https://www.darkreading.com/perimeter/themailer-phishing-kit-ai-drivers-seat)
- [Cursor Traces Malicious Claude Code Extension to Third-Party Breach](https://www.darkreading.com/application-security/cursor-malicious-claude-code-extension-third-party-breach)
- [Grok Bots Attempt to Access Corporate Data Without User Approval](https://www.darkreading.com/application-security/grok-bots-corporate-data-without-user-approval)

### SecurityWeek
- [Microsoft Agent Framework Releases Poisoned With Credential Stealer](https://www.securityweek.com/microsoft-agent-framework-releases-poisoned-with-credential-stealer/)
- [Critical Perforce Puppet RCE Exploited in Attacks](https://www.securityweek.com/critical-perforce-puppet-rce-exploited-in-attacks/)
- [Oracle Patches 950 Vulnerabilities With November 2026 CSPU](https://www.securityweek.com/oracle-patches-640-vulnerabilities-with-november-2026-cspu/)
- [Java4Shell Vulnerability Puts Many Enterprise Applications at Risk of Takeover](https://www.securityweek.com/java4shell-vulnerability-puts-many-enterprise-applications-at-risk-of-takeover/)
- [Classified Communications Network at the National Security Agency Goes Down, Defense Official Says](https://www.securityweek.com/classified-communications-network-at-the-national-security-agency-goes-down-defense-official-says/)
- [AI Framework Autonomously Weaponized Flaws in Real Attacks, Google Says](https://www.securityweek.com/ai-framework-autonomously-weaponized-flaws-in-real-attacks-google-says/)
- [Market Research Giant Ipsos Investigating Breach of Internal System](https://www.securityweek.com/market-research-giant-ipsos-investigating-breach-of-internal-system/)
- [Fandango Warns Ticket Buyers of Payment Card Data Exposure](https://www.securityweek.com/fandango-warns-ticket-buyers-of-payment-card-data-exposure/)
- [Pretxt Emerges Stealth With $5M Seed and an AI Supervision Tool](https://www.securityweek.com/pretxt-emerges-stealth-with-5m-seed-and-an-ai-supervision-tool/)
- [MSP ScreenConnect Servers Targeted in Month-Long Campaign](https://www.securityweek.com/msp-screenconnect-servers-targeted-in-month-long-campaign/)

### The Record
- [CISA warns of ‘Java4Shell,’ an AI-found Java bug touching most of the Fortune 500](https://therecord.media/cisa-issues-java4shell-alert)
- [Website management platform Optimizely confirms hackers put malicious code into customer sites](https://therecord.media/optimizely-malicious-code-customer-sites)
- [Kazakh ransomware hacking suspect extradited from Italy](https://therecord.media/kazakh-suspected-extradited-charges-8-digits-team-inc-lynx)
- [Chinese state group developing automated attack tool for cyber espionage, Google says](https://therecord.media/chinese-state-group-developing-automated-attack-tool-espionage)
- [California fines Hertz $1.5 million for breaking state data privacy law](https://therecord.media/california-fines-hertz-state-data-privacy-law)

### Infosecurity Magazine
- [Three AI Models Agree on Just One of 121 Potential Code Flaws](https://www.infosecurity-magazine.com/news/ai-models-vulnerability-findings/)
- [Watchdog Warns UK Government Is Falling Short on Risk Management](https://www.infosecurity-magazine.com/news/watchdog-government-risk/)
- [Anthropic Cuts Disclosure Deadline to 30 Days For Serious Bugs](https://www.infosecurity-magazine.com/news/anthropic-disclosure-deadline-30/)
- [Optimizely Flaw Exploited to Serve Malicious Code to Visitors of 178 Organizations](https://www.infosecurity-magazine.com/news/optimizely-hack-malware-178-orgs/)
- [Microsoft Warns of Coordinated Phishing Campaign Leveraging M365 Service Outage](https://www.infosecurity-magazine.com/news/microsoft-phishing-service-outage/)
- [ICO Issues GTA 6 Scam Warning as Release Date Nears](https://www.infosecurity-magazine.com/news/ico-gta-6-scam-warning-release/)
- [Fully Autonomous Agentic Attacks Are Three Months Away, Google Warns](https://www.infosecurity-magazine.com/news/fully-autonomous-agentic-attacks/)

### CyberScoop
- [Government tech debt is a national security risk](https://cyberscoop.com/government-tech-debt-national-security-risk-op-ed/)
- [A vulnpocalypse bug worthy of attention: Researchers disclose critical flaw in Java with help of AI](https://cyberscoop.com/java4shell-critical-java-flaw-openjdk/)
- [GSA says post-quantum work on PIV cards shows new encryption can work on old tech](https://cyberscoop.com/gsa-post-quantum-encryption-piv-cards/)
- [How CISA is prioritizing companies for talks about security improvements](https://cyberscoop.com/cisa-100-critical-infrastructure-companies-fed-talks/)
- [Cyberattack or no, parade of tech outages highlight need for resilient systems, CISA acting director says](https://cyberscoop.com/cisa-nick-andersen-cyber-resilience-outages/)
- [Pakistani hackers are spying on defense workers with fake job sites](https://cyberscoop.com/pakistani-hackers-defense-workers-fake-job-sites/)
- [Alleged ransomware group member extradited from Italy to face US charges in hospital, school extortion case](https://cyberscoop.com/roman-khlynovskiy-ransomware-extradition/)
- [The Super Intelligence Task Force should open the door to defenders](https://cyberscoop.com/super-intelligence-task-force-cybersecurity-defenders-op-ed/)

### Cisco Talos
- [The challenge of defending against bulletproof dead drops on public blockchains](https://blog.talosintelligence.com/the-challenge-of-defending-against-bulletproof-dead-drops-on-public-blockchains/)
- [UAT-12643: Suspected North Korea-aligned actor blends blockchain resilience with targeted infostealing](https://blog.talosintelligence.com/uat-12643-suspected-north-korea-aligned-actor-blends-blockchain-resilience-with-targeted-infostealing/)
- [CVE-2026-114938: Critical vulnerability in OpenJDK JAVA](https://blog.talosintelligence.com/java4shell/)

### Unit 42 (Palo Alto)
- [Borrowed Code, Real Consequences: What OPTIMJACK Teaches Us](https://unit42.paloaltonetworks.com/optimjack-supply-chain-attack/)

### Microsoft Security Blog
- [Security for the agentic era, powered by Microsoft Perception](https://www.microsoft.com/en-us/security/blog/2026/11/17/security-for-the-agentic-era-powered-by-microsoft-perception/)
- [The risks of device code authentication for AI coding agents](https://www.microsoft.com/en-us/security/blog/2026/11/17/the-risks-of-device-code-authentication-for-ai-coding-agents/)
- [High volume phishing campaign uses Microsoft 365 outage lures to target multiple industry sectors](https://www.microsoft.com/en-us/security/blog/2026/11/16/high-volume-phishing-campaign-uses-microsoft-365-outage-lures-target-multiple-industry-sectors-2/)

### Google Cloud Threat Intel
- [COLD RELIC: A Case Study in Impersonation and Compromise](https://cloud.google.com/blog/topics/threat-intelligence/cold-relic-a-case-study-in-impersonation-and-compromise/)

### SANS Internet Storm Center
- [ISC Stormcast For Wednesday, November 18th, 2026 https://isc.sans.edu/podcastdetail/10184, (Wed, Nov 18th)](https://isc.sans.edu/diary/rss/33528)
- [A phishing page interested in MX records, (Tue, Nov 17th)](https://isc.sans.edu/diary/rss/33526)
- [ISC Stormcast For Tuesday, November 17th, 2026 https://isc.sans.edu/podcastdetail/10182, (Tue, Nov 17th)](https://isc.sans.edu/diary/rss/33524)

### Securelist (Kaspersky)
- [The forced audit: how AuditTeam’s OpsAgent framework masks ransomware as consulting](https://securelist.com/auditteam-opsagent-forced-audit/122031/)
- [Operation ShadowCloud: cloud service–based backdoors targeting government networks in Asia and Africa. Part 2](https://securelist.com/operation-shadowcloud-graphdoor/122005/)
- [Operation ShadowCloud: cloud service–based backdoors targeting government networks in Asia and Africa. Part 1](https://securelist.com/operation-shadowcloud-gitdoor/122004/)

### CrowdStrike Blog
- [Hidden in the Weights: Supply Chain Risk from Backdoored LoRA Models](https://www.crowdstrike.com/en-us/blog/supply-chain-risk-from-backdoored-lora-models/)
- [Inside Falcon AI Gateway: One Control Point for AI Traffic](https://www.crowdstrike.com/en-us/blog/falcon-ai-gateway-one-control-point-for-ai-traffic/)
- [CrowdStrike Named a Leader in the 2026 IDC MarketScape for Worldwide Augmented Identity Security Solutions](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-idc-marketscape-worldwide-augmented-identity-security-solutions/)
- [November 2026 Patch Tuesday: 1,252 CVEs Include One Zero-Day and 68 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-november-2026/)
- [How Adversaries Are Turning the Vulnerability Ecosystem Against Defenders](https://www.crowdstrike.com/en-us/blog/adversaries-turn-vulnerability-ecosystem-against-defenders/)
- [CrowdStrike Extends the Agentic SOC to Detect and Stop Agent Insider Threats](https://www.crowdstrike.com/en-us/blog/crowdstrike-detects-and-stops-agent-insider-threats/)
- [CrowdStrike Introduces Agentic Adversary Emulation to Counter AI-Enabled Adversaries](https://www.crowdstrike.com/en-us/blog/crowdstrike-agentic-adversary-emulation-counters-ai-enabled-adversaries/)
- [New Falcon Cloud Security Innovations Secure the Cloud AI Runs On](https://www.crowdstrike.com/en-us/blog/falcon-cloud-security-innovations-secure-cloud-ai-runs-on/)
- [CrowdStrike Brings Enterprise Browser Security to the Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-brings-enterprise-browser-security-to-falcon-platform/)
- [CrowdStrike Advances AI Security and Safety from Endpoint to Cloud](https://www.crowdstrike.com/en-us/blog/crowdstrike-advances-ai-security-and-safety-falcon-guardian/)

### FortiGuard Threat Signal
- [Java4Shell](https://fortiguard.fortinet.com/threat-signal-report/6668)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal