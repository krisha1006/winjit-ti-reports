# Winjit Daily TI Digest — 2026-10-15

_Auto-generated. Window: last ~24h. Fetched at 2026-10-15T08:07:03.155114+00:00Z_

**At a glance:** 4 new KEV · 125 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
| CVE | Vendor | Product | Name | Ransomware use | Required action |
|---|---|---|---|---|---|
| CVE-2026-105134 | Ahsay | AhsayCBS | Ahsay AhsayCBS Command Injection Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-76519 | Cisco | Secure Email Gateway | Cisco Secure Email Gateway Relative Path Traversal Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-105133 | Ahsay | AhsayCBS | Ahsay AhsayCBS Improper Authentication Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |
| CVE-2026-0322 | Palo Alto Networks | PAN-OS | Palo Alto Networks PAN-OS Code Injection Vulnerability | Unknown | Apply mitigations in accordance with vendor instructions, ensuring compliance with CISA’s BOD 26-04 Prioritizing Security Updates Based on Risk (see URL in Notes) guidance and CISA’s “Forensics Triage Requirements” (see URL in Notes). Follow applicable BOD 26-04 guidance for cloud services or discontinue use of the product if mitigations are unavailable. Stakeholders are responsible for evaluating each asset's internet exposure and ensuring adherence to BOD 26-04 patching guidelines. |

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-110536 | 10.0 | n/a | A vulnerability was determined in D-Link DIR-868L 2.01b05. This impacts the function system of the file /htdocs/cgibin of the component HNAP CGI Handler. Executing a manipulation of the argument SOAPA |
| CVE-2026-110002 | 9.8 | 1.0% | The Snazzy Social Media Feed plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 2.5 via the (file scope) function. This is due to missing WordPress boots |
| CVE-2026-97668 | 9.8 | 0.4% | The Abandoned Cart Pro for WooCommerce plugin for WordPress is vulnerable to SQL Injection via the guest cart persistent meta_value in all versions up to, and including, 10.8.0 due to insufficient esc |
| CVE-2026-104800 | 9.8 | 1.0% | The AGE-GATE plugin for WordPress is vulnerable to Remote Code Execution in all versions up to, and including, 1.0 via the 'width (and height)' parameter parameter. This is due to missing authenticati |
| CVE-2026-104748 | 9.8 | 0.6% | The SimpleForm – Form Maker to Chat Apps with Quiz, Poll and Multi Lead Notifications plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 3.10.0 This is du |
| CVE-2020-37282 | 9.8 | n/a | office-converter through 1.0.2 contains an OS command injection vulnerability that allows attackers to execute commands by supplying a crafted fileName to generatePdf() or generateHtml(). Attackers ca |
| CVE-2026-110635 | 9.8 | n/a | webp-converter before 3.0.0 contains an OS command injection vulnerability in src/webpconverter.js helpers that run libwebp binaries via execFile with shell enabled. Attackers controlling file names o |
| CVE-2026-110636 | 9.8 | n/a | pypdftk through 0.5 contains an OS command injection vulnerability in fill_form(), dump_data_fields(), and pdftk_cmd_util() that builds shell commands from caller-supplied paths. Attackers controlling |
| CVE-2026-110638 | 9.8 | n/a | doc-recog through 1.1.6 contains an OS command injection vulnerability that allows attackers to execute commands by supplying crafted document paths to recog() or tag(). Attackers can embed $(...) or  |
| CVE-2026-110640 | 9.8 | n/a | Whisper-node through 1.1.1 contains an OS command injection vulnerability that allows attackers to execute commands by supplying crafted filePath or whisperOptions.language values to whisper(). Attack |
| CVE-2026-110643 | 9.8 | n/a | transcribe2texts through 1.0.6 contains an OS command injection vulnerability that allows attackers to execute commands by supplying crafted audioPath values to transcribeAudio(). Attackers can inject |
| CVE-2026-101950 | 9.8 | n/a | A Heap-based Buffer Overflow vulnerability in the SVR component of Juniper Networks Junos OS on SRX Series allows an unauthenticated network attacker to cause a denial of service and potentially compr |
| CVE-2026-101990 | 9.8 | n/a | A Stack-based Buffer Overflow vulnerability in the routing protocol daemon (rpd) of Juniper Networks Junos OS and Junos OS Evolved allows a remote configured BGP peer to cause an rpd crash, or on Juno |
| CVE-2026-102031 | 9.8 | n/a | An OS Command Injection vulnerability in TACACS of Juniper Networks Junos OS Evolved allows a low-privileged TACACS+-authenticated user to execute commands with root privileges when periodic TACACS+ a |
| CVE-2026-102175 | 9.8 | n/a | A Heap-based Buffer Overflow vulnerability in the sdxd service-deployment daemon of Juniper Networks Junos OS and Junos OS Evolved allows a remote unauthenticated attacker who can control or intercept |
| CVE-2026-102178 | 9.8 | n/a | A Stack-based Buffer Overflow vulnerability in the BGP routing daemon of Juniper Networks Junos OS and Junos OS Evolved allows a configured BGP flowspec peer to cause routing-engine compromise or a ro |
| CVE-2026-109439 | 9.8 | n/a | Lantronix XPress-DR and XPress-DR-I (CoBos-family) firmware through 8.1.0.0 contains a missing authentication vulnerability that allows remote attackers to read and persistently overwrite device confi |
| CVE-2026-101954 | 9.8 | n/a | An Improper Authentication vulnerability in the J-Web management interface and its NETCONF session handling of Juniper Networks Junos OS and Junos OS Evolved allows an unauthenticated network attacker |
| CVE-2026-101982 | 9.8 | n/a | A Stack-based Buffer Overflow vulnerability in the routing protocol daemon (rpd)  of Juniper Networks Junos OS and Junos OS Evolved allows a configured BGP/EVPN peer to cause root code execution on Ju |
| CVE-2026-108587 | 9.8 | n/a | The 10Web Booster – Website speed optimization, Cache & Page Speed optimizer plugin for WordPress is vulnerable to Arbitrary File Upload in all versions up to, and including, 2.34.10 via the compressC |
| CVE-2026-92097 | 9.1 | 0.5% | The Click to Chat for WhatsApp plugin for WordPress is vulnerable to Arbitrary Shortcode Execution in versions up to, and including, 4.44 This is due to the greetings_dialog() function building the {u |
| CVE-2026-110862 | 9.1 | n/a | Better Auth from 1.4.0-beta.18 before 1.7.7 contains an authentication bypass vulnerability that allows unauthenticated attackers to sign in as other users by reusing OAuth state values as Magic Link  |
| CVE-2026-110444 | 8.8 | 0.6% | TeamPlus Messenger developed by Teamplus Technology has a Code Injection vulnerability. Unauthenticated remote attackers can trick users into opening a crafted link to inject and execute arbitrary Jav |
| CVE-2026-110445 | 8.8 | 0.6% | TeamPlus Messenger developed by Teamplus Technology has a Code Injection vulnerability. Unauthenticated remote attackers can trick users into interacting with crafted content to inject and execute arb |
| CVE-2026-110621 | 8.8 | n/a | Swetrix Cloud before 5.1.0 contains a missing authorization vulnerability in ProjectController.addProject that allows authenticated users to hijack arbitrary projects by moving them into their own org |
| CVE-2026-110641 | 8.8 | n/a | @runnerty/executor-decompress through 3.1.1 contains an OS command injection vulnerability that allows attackers to execute commands by supplying crafted archive file names to compress_file. Attackers |
| CVE-2026-102014 | 8.8 | n/a | A Stack-based Buffer Overflow vulnerability in the authd process of Juniper Networks Junos OS allows an attacker able to influence a configured RADIUS server to cause authd to crash or execute code wi |
| CVE-2026-102015 | 8.8 | n/a | A Heap-based Buffer Overflow vulnerability in the secure-dot1xd process of Juniper Networks on Junos OS and Junos OS Evolved allows an unauthenticated adjacent network attacker to execute code as root |
| CVE-2026-102049 | 8.8 | n/a | A Stack-based Buffer Overflow vulnerability in the l2cpd process of Juniper Networks Junos OS and Junos OS Evolved allows an adjacent unauthenticated attacker to cause a denial of service or execute a |
| CVE-2026-102050 | 8.8 | n/a | A Stack-based Buffer Overflow vulnerability in the l2cpd daemon of Juniper Networks Junos OS and Junos OS Evolved allows an unauthenticated adjacent attacker to cause a denial of service in Layer 2 co |
| CVE-2026-102052 | 8.8 | n/a | A Stack-based Buffer Overflow vulnerability in the jdhcpd process of Juniper Networks Junos OS and Junos OS Evolved platforms allows an adjacent unauthenticated attacker to cause denial of service or  |
| CVE-2026-102055 | 8.8 | n/a | A Stack-based Buffer Overflow vulnerability in the cfmd process of Juniper Networks Junos OS on MX Series and Junos OS Evolved on PTX Series platforms allows an unauthenticated adjacent-network attack |
| CVE-2026-102059 | 8.8 | n/a | An Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') vulnerability in the phone-home daemon (phcd) of Juniper Networks Junos OS and Junos OS Evolved on EX Seri |
| CVE-2026-102061 | 8.8 | n/a | A Stack-based Buffer Overflow vulnerability in the phone-home daemon (phcd) of Juniper Networks Junos OS and Junos OS Evolved allows an adjacent unauthenticated attacker to execute arbitrary code as r |
| CVE-2026-102174 | 8.8 | n/a | A Stack-based Buffer Overflow vulnerability in the iked IKE key-management daemon of Juniper Networks Junos OS on the SRX Series allows an authenticated remote-access VPN client to execute code with r |
| CVE-2026-102176 | 8.8 | n/a | A Buffer Copy without Checking Size of Input ('Classic Buffer Overflow') vulnerability in the SDK service process of Juniper Networks Junos OS allows an unauthenticated network attacker to cause a den |
| CVE-2026-101981 | 8.8 | n/a | A Stack-based Buffer Overflow vulnerability in the routing protocol daemon (rpd) of Juniper Networks Junos OS and Junos OS Evolved allows an unauthenticated adjacent LDP peer to cause an rpd crash or  |
| CVE-2026-86461 | 8.8 | n/a | The FV Flowplayer Video Player plugin for WordPress is vulnerable to Limited Arbitrary File Upload in all versions up to, and including, 7.5.54.7212 via the check_mimetype function. This is due to inc |
| CVE-2026-86567 | 8.8 | n/a | A flaw was found in DPDK lib/vhost. The VDUSE handler fails to invalidate vring pointers when the IOTLB is invalidated, leading to use-after-unmap. |
| CVE-2026-77931 | 8.8 | n/a | MoviePilot through 3.1.5 contains a command injection vulnerability that allows attackers to execute arbitrary OS commands by embedding malicious instructions in untrusted content processed through to |
| CVE-2026-81534 | 8.8 | n/a | The Email Customizer for WooCommerce (Pro) plugin for WordPress is vulnerable to Remote Code Execution in versions up to, and including, 3.9.5. This is due to insufficient authorization and input sani |
| CVE-2026-110628 | 8.6 | n/a | Kan 0.5.5 through 0.6.0 contains an unauthenticated server-side request forgery vulnerability in the /api/download/attatchment route due to an incomplete fix for CVE-2026-32255. When S3_ENDPOINT is un |
| CVE-2026-100236 | 8.6 | n/a | A flaw was found in the DPDK GSO library. When software GSO copies packet headers into a new mbuf, it does not check that the header fits in the source first segment or in the destination buffer, and  |
| CVE-2026-110769 | 8.6 | n/a | holaOS through 2026.822.1 contains a missing authorization vulnerability in channel-gateway connectors that allows any messaging-platform user to submit agent tasks because the #isAllowed check accept |
| CVE-2026-110867 | 8.5 | n/a | Renovate before 44.60.1 contains an allowlist bypass vulnerability that allows repositories to set restricted environment variables by placing env inside a shared preset. Attackers controlling an exte |
| CVE-2026-110868 | 8.5 | n/a | Renovate before 44.79.0 contains a server-side request forgery vulnerability that allows users to make the shared HTTP client request arbitrary internal URLs via extends presets or customDatasources.  |
| CVE-2016-15060 | 8.3 | n/a | A vulnerability was found in PCMan FTP Server up to 2.0.7. This affects an unknown function of the component PORT Command Handler. The manipulation results in buffer overflow. The attack can be launch |
| CVE-2026-110616 | 8.1 | n/a | NullHub through 2026.5.29 contains a missing authentication vulnerability that allows unauthenticated attackers to access the /api/* management API because the auth_token field defaults to null and is |
| CVE-2026-110618 | 8.1 | n/a | SmsForwarder through 3.5.0 contains a missing authentication vulnerability in its AndServer HTTP server that allows unauthenticated network attackers to invoke remote-control APIs. Attackers can call  |
| CVE-2026-110646 | 8.1 | n/a | Beganovich snappdf from 1.1.0 before 6.1.0 contains an OS command injection vulnerability on Windows that allows attackers to run commands by influencing the rendered URL. Attackers can supply cmd.exe |
| CVE-2026-101955 | 8.1 | n/a | A Stack-based Buffer Overflow vulnerability in the UTM Anti-Spam SBL of Juniper Networks Junos OS on SRX series allows an unauthenticated remote attacker to cause arbitrary code execution or a denial  |
| CVE-2026-101997 | 8.1 | n/a | An Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in ipfd of Juniper Networks Junos OS on SRX Series allows an unauthenticated network-based attacke |
| CVE-2026-102037 | 8.1 | n/a | An XML Injection vulnerability in the Unified Threat Management daemon (utmd) of Juniper Networks Junos OS on SRX Series devices allows an unauthenticated network attacker to commit arbitrary device c |
| CVE-2026-110770 | 8.1 | n/a | Databasus 3.7.0 through 3.61.0 contains an authentication bypass vulnerability that allows unauthenticated attackers to brute-force password reset codes via POST /api/v1/users/reset-password. Attacker |
| CVE-2026-110858 | 8.1 | n/a | GitPython from 3.1.30 before 3.2.0 contains a remote code execution vulnerability in Remote.pull() whose unsafe-option guard inspects only keyword arguments, not the positional refspec. Attackers cont |
| CVE-2026-110863 | 8.1 | n/a | Better Auth @better-auth/sso from 1.7.0-rc.2 before 1.7.3 contains an authentication bypass vulnerability that allows authenticated users to sign in as other users by registering a personal SSO provid |
| CVE-2026-17031 | 8.1 | n/a | The Checkout Field Manager (Checkout Manager) for WooCommerce plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 7.9.6 This is due to the plugin not prope |
| CVE-2026-90954 | 7.8 | 0.2% | A flaw was found in BusyBox's dpkg-deb archive extraction. The ar archive handler flushes deferred symlinks after each archive member, unlike the tar, cpio, and unzip handlers which flush once after t |
| CVE-2026-110633 | 7.8 | n/a | MyReport Updater through 2.1.1 contains a local privilege escalation vulnerability that allows low-privileged users to make the SYSTEM updater service install attacker-supplied archives into arbitrary |
| CVE-2026-110648 | 7.8 | n/a | @offactory/compress-fonts before 1.1.1 contains an OS command injection vulnerability that allows attackers to execute shell commands by supplying font files with crafted names. Font paths are interpo |
| CVE-2026-101927 | 7.8 | n/a | A Heap-based Buffer Overflow vulnerability in eventd of Juniper Networks Junos OS and Junos OS Evolved on all platforms allows an unprivileged local attacker to cause a denial of service (DoS) or achi |
| CVE-2026-86562 | 7.8 | n/a | A flaw was found in DPDK lib/vhost. A TOCTOU double-fetch of control-queue descriptors allows a heap buffer overflow with attacker-controlled content in the VDUSE control-queue handler. |
| CVE-2026-104767 | 7.5 | 0.3% | The Membership & User Roles for WooCommerce (Automatic Role Changer) plugin for WordPress is vulnerable to Privilege Escalation in versions up to, and including, 20260828. This is due to the `maybe_ad |
| CVE-2026-102251 | 7.5 | 0.4% | The Abandoned Cart Pro for WooCommerce plugin for WordPress is vulnerable to generic SQL Injection via the 'validate' parameter in all versions up to, and including, 10.8.0 due to insufficient escapin |
| CVE-2026-103366 | 7.5 | 0.5% | The Appointment Booking Plugin – LatePoint | Calendar & Scheduling for WordPress plugin for WordPress is vulnerable to Insecure Direct Object Reference in versions up to, and including, 5.7.3 via the  |
| CVE-2026-110284 | 7.5 | 0.7% | The LifterLMS – WP LMS for eLearning, Online Courses, & Quizzes plugin for WordPress is vulnerable to Local File Inclusion in versions up to, and including, 10.3.1 via attacker-controlled attributes o |
| CVE-2026-110690 | 7.5 | n/a | Cloud Commander (cloudcmd) versions 19.20.2 through 19.21.1 contains a path traversal vulnerability in the GET /api/v1/pack endpoint where the onGET handler at server/rest/index.js:130 calls the ungua |
| CVE-2026-104939 | 7.5 | n/a | Description
NGINX Ingress Controller has a vulnerability when implementing an externalAuth policy for ingress. NGINX Ingress Controller may mishandle the HTTP response from an OAuth IdP and allow an a |
| CVE-2026-110623 | 7.5 | n/a | Papermerge Core through 3.5.3 contains a missing authorization vulnerability in the shared nodes API that allows authenticated users to share other users' documents by supplying arbitrary node UUIDs.  |
| CVE-2026-94197 | 7.5 | n/a | An authentication and authorization bypass vulnerability exists in F5 NGINX Kubernetes Ingress Controller (NIC) when configured with the `ExternalAuth` policy or Ingress external authentication. Clien |
| CVE-2026-101939 | 7.5 | n/a | A NULL Pointer Dereference vulnerability in the routing protocol daemon (RPD) of Juniper Networks Junos OS and Junos OS Evolved allows a configured peer sending a BGP UPDATE to cause a denial of servi |
| CVE-2026-101940 | 7.5 | n/a | A NULL Pointer Dereference vulnerability in the rpd routing daemon of Juniper Networks Junos OS and Junos OS Evolved allows an unauthenticated configured BGP peer to cause a denial of service via a BG |
| CVE-2026-101941 | 7.5 | n/a | A NULL Pointer Dereference vulnerability in the routing protocol daemon (rpd) of Juniper Networks Junos OS and Junos OS Evolved allows a configured BGP neighbor to cause a denial of service via a BGP  |
| CVE-2026-101942 | 7.5 | n/a | An Improper Handling of Length Parameter Inconsistency vulnerability in the routing protocol daemon (rpd) process of Juniper Networks Junos OS and Junos OS Evolved allows an unauthenticated network-ba |
| CVE-2026-101943 | 7.5 | n/a | An Improper Input Validation vulnerability in the routing protocol daemon (rpd) of Juniper Networks Junos OS and Junos OS Evolved allows an unauthenticated network-based attacker to cause a denial of  |
| CVE-2026-101944 | 7.5 | n/a | An Integer Overflow or Wraparound vulnerability in the routing protocol daemon (rpd) of Juniper Networks Junos OS and Junos OS Evolved allows an attacker to cause a denial of service via specially cra |
| CVE-2026-101945 | 7.5 | n/a | An Integer Overflow or Wraparound vulnerability in the rpd process of Juniper Networks Junos OS and Junos OS Evolved allows a remote attacker with an established EVPN BGP peering relationship to cause |
| CVE-2026-102012 | 7.5 | n/a | A Reachable Assertion vulnerability in the na-grpcd process of Juniper Networks Junos OS Evolved allows a remote unauthenticated attacker to cause a denial of service via a gRPC telemetry subscription |
| CVE-2026-102016 | 7.5 | n/a | An Improper Validation of Specified Quantity in Input vulnerability in the rpd process of Juniper Networks Junos OS and Junos OS Evolved allows a configured BGP MVPN peer to cause a denial of service  |
| CVE-2026-102020 | 7.5 | n/a | A Reachable Assertion vulnerability in the rpd process of Juniper Networks Junos OS and Junos OS Evolved allows an authenticated network-based attacker to cause a denial of service via BGP-LS routing  |
| CVE-2026-102022 | 7.5 | n/a | A Reachable Assertion vulnerability in the routing protocol daemon (rpd) of Juniper Networks Junos OS and Junos OS Evolved allows an attacker with access to a configured BGP-LS peer to cause an rpd cr |
| CVE-2026-102023 | 7.5 | n/a | A Reachable Assertion vulnerability in fwstatsd of Juniper Networks Junos OS Evolved allows an authenticated network attacker to cause a denial of service via an SNMP firewall-counter MIB query when a |
| CVE-2026-102024 | 7.5 | n/a | An Integer Overflow or Wraparound vulnerability in the routing daemon (rpd) of Juniper Networks Junos OS and Junos OS Evolved allows an authenticated BGP peer to cause a denial of service via BGP rout |
| CVE-2026-102025 | 7.5 | n/a | A Mismatched Memory Management Routines vulnerability in the routing protocol daemon (rpd) process of Juniper Networks Junos OS and Junos OS Evolved allows an authenticated network-based attacker to c |
| CVE-2026-102026 | 7.5 | n/a | An Improper Control of a Resource Through its Lifetime vulnerability in the routing protocol daemon (rpd) of Juniper Networks Junos OS and Junos OS Evolved allows an adjacent eBGP peer to cause a rout |
| CVE-2026-102027 | 7.5 | n/a | An Incorrect Calculation of Buffer Size vulnerability in the routing protocol daemon (rpd) of Juniper Networks Junos OS and Junos OS Evolved allows a configured eBGP neighbor to cause an rpd crash via |
| CVE-2026-102028 | 7.5 | n/a | A NULL Pointer Dereference vulnerability in the routing protocol daemon (rpd) of Juniper Networks Junos OS and Junos OS Evolved allows a remote BGP peer to cause a denial of service when multiple UPDA |
| CVE-2026-102029 | 7.5 | n/a | A NULL Pointer Dereference vulnerability in the routing protocol daemon (rpd) of Juniper Networks Junos OS and Junos OS Evolved allows an unauthenticated configured MSDP peer or adjacent PIM sender to |
| CVE-2026-102030 | 7.5 | n/a | An Incomplete Cleanup vulnerability in the rpd process of Juniper Networks Junos OS and Junos OS Evolved allows a configured MVPN neighbor to cause a denial of service via a BGP MVPN update when an in |
| CVE-2026-102064 | 7.5 | n/a | A Reachable Assertion vulnerability in the routing protocol daemon (rpd) of Juniper Networks Junos OS and Junos OS Evolved allows an attacker to cause rpd crash via malformed BGP MCAST-VPN updates fro |
| CVE-2026-15102 | 7.5 | n/a | ADP Desktop SDK contains a vulnerability where sensitive information is transmitted in clear text. Exploitation of this vulnerability can lead to unauthorized access to Autodesk services. |
| CVE-2026-110767 | 7.5 | n/a | Gitingest through 0.3.1 contains a symlink following vulnerability in ingest_query single-file blob ingestion that allows unauthenticated attackers to read server files by submitting symlink blob URLs |
| CVE-2026-110838 | 7.5 | n/a | FreeRDP shadow server from 3.0.0 before 3.32.0 dispatches input PDUs during the Confirm Active state before authentication, allowing unauthenticated attackers to inject keyboard input. Attackers can n |
| CVE-2026-110856 | 7.5 | n/a | GitPython before 3.2.0 contains a regular expression denial of service vulnerability in the _re_actor_epoch pattern used by parse_actor_and_date on author, committer, and tagger lines. Attackers can s |
| CVE-2026-110857 | 7.5 | n/a | GitPython before 3.2.0 contains a remote code execution vulnerability that allows attackers to run commands because Git.ls_remote forwards URLs without check_unsafe_protocols validation. Attackers can |
| CVE-2026-110859 | 7.5 | n/a | GitPython before 3.2.0 contains an argument injection vulnerability in Head.checkout() that allows remote attackers to read arbitrary files by supplying a branch name parsed as a git option. Attackers |
| CVE-2026-110869 | 7.5 | n/a | Nodemailer 3.0.0 before 10.0.13 has a regular expression denial of service in SMTPConnection._actionEHLO, whose four AUTH mechanism detection regexes contain overlapping whitespace sub-patterns that b |
| CVE-2026-0993 | 7.5 | n/a | SODOLA SL902-SWTGW124AS firmware before 200.2.12 contains a buffer overflow vulnerability that allows unauthenticated remote attackers to cause a denial of service by sending an oversized boundary val |
| CVE-2026-109430 | 7.5 | n/a | Ellucian WebAdvisor 3.2 contains an unauthenticated XML External Entity (XXE) injection vulnerability that allows remote attackers to submit crafted XML POST requests to the /WebAdvisor/WebAdvisor end |
| CVE-2026-76066 | 7.5 | n/a | IntentKit through 2.6.3 contains an authorization bypass vulnerability where the executor validates tool calls against the full tool registry rather than the per-request narrowed tool advertisement en |
| CVE-2026-15090 | 7.5 | n/a | The Link Library plugin for WordPress is vulnerable to time-based SQL Injection via the 'link_url' parameter in all versions up to, and including, 7.9.2 due to insufficient escaping on the user suppli |
| CVE-2026-110864 | 7.4 | n/a | Better Auth from 1.5.0-beta.12 before 1.7.7 contains an authentication bypass vulnerability in the OAuth Proxy plugin that allows unauthenticated attackers to sign in as other users by forging encrypt |
| CVE-2026-110668 | 7.3 | n/a | A weakness has been identified in cemtan sar2html 4.0.0. Affected by this issue is the function index of the file sar2html.py. This manipulation of the argument sort causes sql injection. The attack i |
| CVE-2026-110670 | 7.3 | n/a | A vulnerability was found in cemtan sar2html 4.0.0. The affected element is the function updateDb of the file sar2html.py of the component Archive Processing. The manipulation of the argument s2host r |
| CVE-2026-110679 | 7.3 | n/a | A vulnerability was determined in OpenSIPS up to 3.6.8/4.0.1. The impacted element is the function rtpproxy_offer/rtpproxy_answer of the component rtpproxy. This manipulation causes out-of-bounds read |
| CVE-2026-3712 | 7.3 | n/a | The PhastPress plugin for WordPress is vulnerable to Server-Side Request Forgery in all versions up to, and including, 3.10 This is due to the scripts service endpoint constructing its URL whitelist d |
| CVE-2026-77114 | 7.2 | 0.3% | The Document Gallery plugin for WordPress is vulnerable to Stored Cross-Site Scripting via 'dg_thumber_webhook' Action Request Body in all versions up to, and including, 5.1.1 due to insufficient inpu |
| CVE-2026-83592 | 7.2 | 0.3% | The Contact Form DB for Enfold plugin for WordPress is vulnerable to Stored Cross-Site Scripting via Contact Form Field Values in all versions up to, and including, 2.0.2 due to insufficient input san |
| CVE-2026-93885 | 7.2 | 0.4% | The Cryptocurrency Donation Box – Bitcoin & Crypto Donations plugin for WordPress is vulnerable to Stored Cross-Site Scripting via data_object Parameter in all versions up to, and including, 2.2.13 du |
| CVE-2026-95816 | 7.2 | 0.4% | The Smart Forms – when you need more than just a contact form plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'formString' parameter in all versions up to, and including, 2.6 |
| CVE-2026-104764 | 7.2 | 0.6% | The Post Export Import with Media plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 1.17.1 via deserialization of untrusted input . This makes it possibl |
| CVE-2026-107631 | 7.2 | 0.3% | The Record of Consent Extension for Complianz plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'uid' parameter in all versions up to, and including, 2.5 due to insufficient in |
| CVE-2026-107751 | 7.2 | 0.3% | The Mang Board plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'user_name' parameter in all versions up to, and including, 2.4.3 due to insufficient input sanitization and ou |
| CVE-2026-88829 | 7.2 | 0.3% | A flaw was found in BusyBox httpd's reverse proxy feature. When the proxy is configured to forward requests matching a URL prefix to a backend server, only the first HTTP request on a TCP connection h |
| CVE-2026-110719 | 7.2 | n/a | Portkey AI Gateway 1.14.0 through 1.15.2 contains a server-side request forgery vulnerability that allows unauthenticated attackers to reach loopback and Docker host services because isValidCustomHost |
| CVE-2026-18548 | 7.2 | n/a | The Groundhogg — CRM, Newsletters, and Marketing Automation plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'ref' parameter in all versions up to, and including, 4.5.14 due t |
| CVE-2026-18586 | 7.2 | n/a | The Premium Packages – Sell Digital Products Securely plugin for WordPress is vulnerable to Unauthenticated Stored Cross-Site Scripting via 'order_email' in all versions up to, and including, 7.0.5 du |
| CVE-2026-88043 | 7.2 | n/a | The Mang Board WP plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'data_type' parameter in all versions up to, and including, 2.4.0 due to insufficient input sanitization and |
| CVE-2026-110615 | 7.1 | n/a | jshERP through 3.6 contains a missing authorization vulnerability in the POST /user/batchSetStatus endpoint that allows authenticated low-privilege users to change other users' account status. Attacke |
| CVE-2026-101994 | 7.1 | n/a | An Improper Handling of Length Parameter Inconsistency vulnerability in the 

l2ald 

daemon of Juniper Networks Junos OS and Junos OS Evolved allows an attacker who can control or impersonate a confi |
| CVE-2026-102056 | 7.1 | n/a | An Out-of-bounds Read vulnerability in the cfmd process of Juniper Networks Junos OS and Junos OS Evolved allows an unauthenticated adjacent-network attacker to crash the daemon and disclose limited p |
| CVE-2026-110837 | 7.1 | n/a | FreeRDP 2.0.0 before 3.32.0, when built with WITH_LAME=ON and WITH_DSP_FFMPEG=OFF, has a heap-based buffer overflow in freerdp_dsp_decode_mp3 because the right-channel PCM pointer is offset by a byte  |
| CVE-2026-110839 | 7.1 | n/a | FreeRDP 3.3.0 before 3.32.0, when built with WINPR_UTILS_IMAGE_JPEG=ON, has a heap-based out-of-bounds write in winpr_convert_from_jpeg because grayscale JPEG buffers are sized from one input componen |
| CVE-2026-110865 | 7.1 | n/a | Renovate before 44.60.1 contains an allowlist bypass vulnerability that allows repository users to evade the allowedHeaders restriction by placing hostRules headers inside shared presets. Attackers ca |
| CVE-2026-110873 | 7.1 | n/a | Heym from 0.0.55 before 0.0.121 contains a privilege escalation vulnerability that allows shared collaborators to overwrite a workflow's error_workflow_id because the field is missing from OWNER_ONLY_ |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-mgxx-8mqr-7h76 | CVE-2026-88043 | high | The Mang Board WP plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the ... |
| GHSA-p2wh-5jr9-79p4 | CVE-2026-86803 | medium | The The Ocean Extra plugin for WordPress is vulnerable to arbitrary shortcode execution in all... |
| GHSA-mfhh-qmgc-7465 | CVE-2026-17031 | high | The Checkout Field Manager (Checkout Manager) for WooCommerce plugin for WordPress is vulnerable... |
| GHSA-3jmx-w2jv-78h7 | CVE-2026-18586 | high | The Premium Packages – Sell Digital Products Securely plugin for WordPress is vulnerable to... |
| GHSA-7572-wgx4-m8rc | CVE-2026-15180 | medium | The Tracking Code Manager plugin for WordPress is vulnerable to Reflected Cross-Site Scripting... |
| GHSA-7rgj-wqj9-chr5 | CVE-2026-78001 | medium | The Post and Page Builder by BoldGrid – Visual Drag and Drop Editor plugin for WordPress is... |
| GHSA-5vv9-v5h9-cghv | CVE-2026-78087 | medium | The VK Blocks plugin for WordPress is vulnerable to Stored Cross-Site Scripting via Group Block ... |
| GHSA-4999-fgr2-g9qv | CVE-2026-17001 | medium | The Import and export users and customers plugin for WordPress is vulnerable to Stored Cross-Site... |
| GHSA-x57v-8jrr-596c | CVE-2026-18548 | high | The Groundhogg — CRM, Newsletters, and Marketing Automation plugin for WordPress is vulnerable to... |
| GHSA-gffv-426m-7cc6 | CVE-2026-18557 | medium | The Photo Gallery by 10Web – Mobile-Friendly Image Gallery plugin for WordPress is vulnerable to... |
| GHSA-xg95-mp7q-fp5g | CVE-2026-15090 | high | The Link Library plugin for WordPress is vulnerable to time-based SQL Injection via the 'link_url... |
| GHSA-vwvh-6gpq-r72g | CVE-2026-76667 | medium | A security vulnerability in HPE NonStop EXPAND may result in out-of-bounds memory read. |
| GHSA-3j57-3pc4-v67v | CVE-2026-110926 | medium | A flaw was found in OpenSSH. When compression is negotiated, channels on the same connection... |
| GHSA-h54q-2vm3-97qv | CVE-2026-110925 | medium | A flaw was found in OpenSSH. A username entered on the ssh command line can still contain '$' or... |
| GHSA-cv5v-cq2q-vv46 | CVE-2026-110923 | medium | A flaw was found in OpenSSH. During an sftp copy, a malicious server can supply an empty name, a... |
| GHSA-cf77-p45j-975w | CVE-2026-76666 | medium | A security vulnerability in HPE NonStop EXPAND may result in out-of-bounds memory read. |
| GHSA-gj56-mwgx-mqvf | CVE-2026-3712 | high | The PhastPress plugin for WordPress is vulnerable to Server-Side Request Forgery in all versions... |
| GHSA-mxcg-m44c-38cw | CVE-2026-93484 | high | Znuny through 7.3.6 constructs a ticket-search database query by directly concatenating user... |
| GHSA-38rr-wcwh-jgw6 | CVE-2026-108587 | critical | The 10Web Booster – Website speed optimization, Cache & Page Speed optimizer plugin for WordPress... |
| GHSA-g4fx-r8m5-c6r7 | CVE-2026-93483 | critical | In Znuny through 7.3.6, an attacker can bypass specific standard login procedures and gain... |
| GHSA-qfg8-xghr-gjxw | CVE-2026-76665 | high | A security vulnerability in HPE NonStop EXPAND may cause out-of-bounds memory read resulting in... |
| GHSA-mp7f-3rhr-22p2 | CVE-2026-14572 | medium | The Kirki – Freeform Page Builder, Website Builder & Customizer plugin for WordPress is... |
| GHSA-jw7q-qxhf-mm2p | CVE-2026-76664 | medium | A security vulnerability in HPE NonStop EXPAND may result in out-of-bounds memory read/write... |
| GHSA-r2jj-8gwv-75pj | CVE-2026-110912 | high | In DragonFly BSD through 6.4.2 before 4bb22ff, the ARP input handlers arpintr() and in_arpinput()... |
| GHSA-2wh3-67f4-gxgc | CVE-2026-110911 | critical | Wheels 1.1.8 through 4.1.1 allows SQL injection when caller-supplied quoted values are parsed... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| alera | iah6477 |  | 2026-10-15T03:02:43.047487+00:00 |
| Company #68 | N0n | US | 2026-10-15T02:52:05.376534+00:00 |
| Company #67 | N0n | NL | 2026-10-15T01:51:47.369921+00:00 |
| Company #66 | N0n |  | 2026-10-15T01:22:36.256399+00:00 |
| Interior Technologies | N0n |  | 2026-10-14T22:59:09.912069+00:00 |
| MOA Architecture | qilin | SG | 2026-10-14T15:31:05.498186+00:00 |
| Joliet Public Schools District 86 | qilin | US | 2026-10-14T15:30:28.031156+00:00 |
| Trieschmann Dumala Architectural Group | N0n |  | 2026-10-14T13:54:33.365887+00:00 |
| Green Clinic | Wallstreet | US | 2026-10-14T12:56:56.279165+00:00 |
| E-Z Pack Trucks | Wallstreet | US | 2026-10-14T12:57:15.593725+00:00 |
| poolegroup.com.au | lockbit5 | AU | 2026-10-14T11:31:29.635649+00:00 |
| kordhotels.gr | lockbit5 | GR | 2026-10-14T11:28:33.369306+00:00 |
| MyM ODONTOCLINICA S.A | emperador | BR | 2026-10-14T10:51:31.129638+00:00 |
| FINANCIAMENTO LTDA | incransom | BR | 2026-10-14T16:33:00.031011+00:00 |
| Lane Equipment | dragonforce | US | 2026-10-14T00:30:19.672653+00:00 |
| Taiwan Otsuka Pharmaceutical | Eclipse | TW | 2026-10-14T17:51:57.553763+00:00 |
| japantimes.co.jp | Eclipse | JP | 2026-10-14T17:51:21.668626+00:00 |
| FOODMatch | akira |  | 2026-10-14T16:58:33.669134+00:00 |
| Shediac Lobster Shop | akira | CA | 2026-10-14T16:58:14.191638+00:00 |
| Torns Enterprises | akira |  | 2026-10-14T16:57:54.511558+00:00 |

## IOCs
### ThreatFox (recent, abuse.ch)
| Indicator | Type | Malware |
|---|---|---|
| 49.235.52.47:808 | ip:port | win.cobalt_strike |
| 89.40.105.179:443 | ip:port | win.cobalt_strike |
| 217.182.168.142:7443 | ip:port | unknown |
| https://r.78royal.org/jrs | url | win.vidar |
| https://eq.78royal.org/se | url | win.vidar |
| https://r.78royal.org | url | win.vidar |
| https://eq.78royal.org/m/ | url | win.vidar |
| https://eq.78royal.org/m | url | win.vidar |
| https://eq.78royal.org/po | url | win.vidar |
| 45.87.53.8:443 | ip:port | win.cobalt_strike |
| 45.87.53.9:443 | ip:port | win.cobalt_strike |
| 140.143.239.224:10001 | ip:port | win.cobalt_strike |
| https://eq.78royal.org/tv/ | url | win.vidar |
| https://eq.78royal.org/tv | url | win.vidar |
| https://eq.78royal.org/xjp | url | win.vidar |
| https://eq.78royal.org/x6 | url | win.vidar |
| https://eq.78royal.org/x6/ | url | win.vidar |
| https://eq.78royal.org/l7 | url | win.vidar |
| https://eq.78royal.org/ma | url | win.vidar |
| 2e7db0451353ba2f128333ab512f388cbc172f3d2f81766c3a14c7cf153830a3 | sha256_hash | osx.amos |

### URLhaus (recent malicious URLs, abuse.ch)
| URL | Threat | Status |
|---|---|---|
| http://59.96.138.155:42226/i | malware_download | online |
| http://59.96.138.155:42226/bin.sh | malware_download | online |
| http://42.227.196.224:53694/i | malware_download | online |
| http://42.226.236.209:36563/i | malware_download | online |
| http://115.62.152.23:52843/bin.sh | malware_download | online |
| http://115.62.152.23:52843/i | malware_download | online |
| http://42.230.35.117:53220/i | malware_download | online |
| http://42.226.236.209:36563/bin.sh | malware_download | online |
| http://103.66.176.192:33647/bin.sh | malware_download | online |
| http://115.55.61.246:34455/i | malware_download | online |
| http://60.186.138.183:45320/i | malware_download | online |
| http://210.208.106.68:50663/bin.sh | malware_download | online |
| http://105.184.182.218:55557/bin.sh | malware_download | offline |
| http://175.107.215.35:39492/Mozi.a | malware_download | offline |
| http://119.30.117.179:38895/Mozi.m | malware_download | offline |
| http://95.9.35.137:35818/bin.sh | malware_download | online |
| http://42.225.199.101:33025/bin.sh | malware_download | online |
| http://115.50.104.42:48635/bin.sh | malware_download | online |
| https://download1593.mediafire.com/65fjj9yhlxlgyAmDvohLNPZOz6PDQSXZh38lLkt6VQoL0SihRWoxP0RRbfp5J49NZC3t1IBDJf-K9lsq0p30jcAuNcleWlwfo63HP_IQvgJWjiIXxOtz8pV13Q9dgvUaJCfpjkg88otD8xea9CxgFtsOtiXAF_pld4OyGzEVRIV_Yg/f5or9v58g1hmf84/MalwareRAT.rar | malware_download | online |
| http://115.61.111.244:57147/bin.sh | malware_download | online |

### MalwareBazaar (recent samples, abuse.ch)
| SHA256 | File type | Signature |
|---|---|---|
| 5825ebe05704f9c16b2aff3fb567fcb86dcb6474660793c5e267a6e49b9282f7 | threatcat_ch | n/a |
| 0e1466319663282294106a06bd2234eb2bd7c4cbf89cfbead573a37da711fc2b | Threatray | n/a |
| bf282293d902e1c579d3386117fe82adc6cba6d7e30010d7345f2caf778fa9d8 | Threatray | n/a |
| 63a9dd2ea552fbb84afdec77884f88cc3dc86c26c257a23c465905f218c5d27e | Threatray | n/a |
| 61f41806ab4b660e9c2ee60bd2052c83e7a8ca77d5fb2c763e64e2a8de21b5c5 | Threatray | n/a |
| a31fdd57ba5d2c6e29d5aa431cf2e63f1f23d32e0a77cd99090736b3fb60576a | Threatray | n/a |
| 47a9e572a1062abd16b0a0df256ba0c4b6b4660125844ca8ddbf22714f6beb30 | Threatray | n/a |
| 7bdd7d62f28d859e8dc63a962e56b4fbf72135fde0e92bebf36e2a4fde628f27 | anonymous | n/a |
| 8bf877d9f3cd118941fb745f1b9b5ca47662a7f71b77cdd9e2dd9e8a2b623219 | c2hunter | n/a |
| 21f9def5c5ca5e10c13b3c885349117cebf7a3872702b5dbc78b4cbe5dfd669b | abuse_ch | n/a |
| 4cd3529fc035c278beb7474fd6e78aa6316bc908e105f8e12bb6ab0e79a2bc55 | abuse_ch | RemcosRAT |
| 74eed7f4eb2c03328276103558991ba872db23c73b1dd66a97446c80c9e147d5 | threatcat_ch | XWorm |
| 3504635b77e25e9ed7e8082bb264c4ce8cc4bb3424fbf4bc44277f4946a37db7 | lowmal3 | Formbook |
| 7c1cbb86a7584608ba9c04069ddbbef287b9fb3cf439ec4e7fccafbfb168c428 | lowmal3 | Formbook |
| c513ce735cf7ed9f27bf151601a13d9e8f943c5b6aa20d2a6d7831cb9ce8e4c1 | lowmal3 | n/a |
| 1d9c00c7e9e917b91a1070249c9278ad033d2c834637a081bf66d0e6533504c0 | lowmal3 | DarkTortilla |
| b98db2b56ead04aa27ca8fe4a20d46e546baab613f0a843991512dd4e93a2570 | abuse_ch | ValleyRAT |
| 854a0834a7029c81f91b841116c16fbb196d218d196fe7b63b4f31b8ba17f12e | abuse_ch | RatonRAT |
| 06af7db1507c685154f7a291c862b0bfe5649c989de4e7acbeff23fd3252e4ec | abuse_ch | ValleyRAT |
| 633700324ad7abdf0fcaee0498e4d3bef9093c51ee4d611e02303e0f8f1a58e2 | abuse_ch | ValleyRAT |

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
| 152.32.225.117 | 11 |
| 160.250.132.238 | 10 |
| 45.148.10.141 | 9 |
| 45.148.10.240 | 9 |
| 77.90.185.20 | 9 |
| 92.5.155.195 | 9 |
| 94.154.43.223 | 9 |
| 130.12.180.32 | 9 |
| 167.94.146.48 | 9 |
| 220.80.223.144 | 9 |
| 2.57.122.238 | 8 |
| 18.218.118.203 | 8 |
| 31.184.195.246 | 8 |
| 45.43.60.98 | 8 |
| 45.91.64.7 | 8 |
| 45.148.10.152 | 8 |
| 45.148.10.157 | 8 |
| 45.172.152.74 | 8 |
| 62.60.130.253 | 8 |
| 64.62.156.38 | 8 |

### OpenPhish (live phishing URLs)
- http://help.steampowered.com.im/en/wizard/HelpRequest/HT-E8JJ-I6WP-QJ2C/
- http://humectaseis.com.tr/goodheads/?uid=lanorlab@7766aac2c14dbab8aff1bc5bb92fcb994793.net
- http://start-en-ledger-e-n.typedream.app/
- http://learn-liveledger-eng.typedream.app/
- http://kuucioinlogin.webflow.io/
- http://exoticafood.com.br/nd
- https://s4w.in/roblox-com-share-2753915549-Blox-FruitsprivateServerLinkCode=20050521686964129487128195074939
- https://romantic-salmon-tgjpnemj.edgeone.dev/
- http://homeloans-wellsfargo-com.sbx.pgsdemo.com/
- https://cn.mebetx39.com/home/register/
- https://www.leanl.vercel.app/
- https://www.roblox.com.mu/users/5757654538/profile
- https://https--www--roblox.com/login?returnUrl=1717572407
- http://whimsical-licorice-17cae4.netlify.app/
- http://onl1ne-whatsapp.pages.dev/
- https://consejosempresariales.onrender.com/
- http://cap-learn-livlgr-logn.pages.dev/0x.htm
- https://connexion-auth.toclw.xyz/
- https://app.mimisa.xyz/
- http://www.cutt.ly/ZyWDEv25/

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://pageseuc1.actmkt.com/(S(aprpfow2exkz3ztk0zczczqc))/l/c5X8MfZz6j9Y7Fto3LAd |
| N/A | https://id.superhuman.com/signin?oauth_client_type=MEDIATED_WEB&correlation_id=BG-05yAPveCfyvFurjsY6A&version=v4&client_id=superhumanDocs |
| N/A | https://away.vk.ru/away.php?rh=a19180ca-497d-4bbe-86ea-d48e435c8fe3 |
| N/A | https://bluesoftsdocrks.com/Docusign/page/ |
| N/A | https://yandex.ru/showcaptcha?cc=1&form-fb-hint=2.1&mt=C9A032BB5AB9F6E253F59787F6569EA32B21E40C083E2B6BAC201C25B7FD5651023FA271E3B14B53BA31C8E98C3061BBB39E6B14F56655421E066CF384F8EB3FE382DFAD0D3CFAD2F509C8B3BB3824C3FD4487E6DF8CB7A77B37F52957AC1A3AE9D703F1A6F4B0DD8939CA754371ACB3B88A50CFC7B9510FBCF1FEC2CE060BD2A93409B41EC4F52B26&retpath=aHR0cHM6Ly95YW5kZXgucnUvc2VhcmNoP3RleHQ9MjExNjg3MTc%2C_44f4128833e4ce7a6e47d16fd4eb29db&t=2%252F1792049667%252F100e2d4b06d9f6d34677e07b30acf32b&u=9581953006992896144&s=41cd3da51ec4aced3652d9e28dccfcc4 |
| N/A | https://2fk8mn.share-eu1.hsforms.com/2vkkuLze1TNqmTXt53fc8yw |
| N/A | https://bankofamericalivesupport.com/ |
| N/A | https://ersfilter-my.sharepoint.com/personal/nradonich_ersfilter_com/_layouts/15/doc.aspx?guestaccesstoken=t6T%2FHN1dKbYHlYX%2BeIMbaZufA43rrGZ6%2FaAAewNocDI%3D&docid=1_18168db23429e45f29fdf2e7be120efc4&wdFormId=%7BB9970F62-44C3-4D09-9929-6E1EB652DA57%7D&action=formsubmit&CID=da9e4f6a-0962-471a-bd5d-6d1221ae5b56 |
| N/A | https://away.vk.ru/away.php?rh=1c11b5a5-ecce-4e6a-9896-80e52d996db2 |
| N/A | https://gmail-support.netlify.app/ |
| N/A | https://ledgerdownloads.com/ |
| N/A | https://away.vk.ru/away.php?rh=7b8cf677-bc1d-4bcd-849f-5ac076110e03 |
| N/A | https://away.vk.ru/away.php?rh=77eec061-9b7e-43ae-9c68-a78c8c504395 |
| N/A | https://www.att.com/activearmorapp?_branch_match_id=1639173829281118301&utm_source=AT%26T%20App&_branch_referrer=H4sIAAAAAAAAA8soKSkottLXT0wuySxLTSzKzS%2FSzS%2FKTM%2FM00ssKdFLzs%2FV9wtL8U6KLCzzMUqyrytKTUstKsrMS49PKsovL04tsnXOKMrPTQUAZUf3KkgAAAA%3D |
| 7.8 | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=ASKXGp0_nbFzdHoBsG_d6znGlWE063OUXUJ-liVgQNfJJB3wA_mip4wV6In-9Cchxtm7MSHwtubxoQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06STrdSaNcSRRDLMn9XlgFYHRgoRGfCQGdNSr9X7RW3V6bqoXw-aLRXR7Nkmuz8aLT4FgOD7y&dsh=S1395581743%3A1792047251258761 |
| N/A | https://away.vk.ru/away.php?rh=c1f90100-0c9a-4f11-a5cc-bd7ede25520d |
| N/A | https://chat.juridico-pj.live/ |
| 9.1 | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AQMjQ7TPKu6R4w93VRXMPKeD3zeOl4EoNrOdcsDBPMv7m30JK47iKcBvHB2Y608BaGxX8bX4kwt6sA&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SRKcFvV9HyU353WmHFLyFnxym5jUHlOmIPCOGvYdhntmNg-rRugu0ruhPBVzZc2CIHf1uhb&dsh=S1378833885%3A1792046800158263 |
| N/A | https://vercel.com/login?next=%2Fsso-api%3Furl%3Dhttps%253A%252F%252Finterface-uniswap.vercel.app%252F%26nonce%3Dff8442674e6de0b6ea61bf5fb8c3e857734f26e50253cea6545e0574645e748a |
| N/A | https://away.vk.ru/away.php?rh=343c191d-036c-4379-90ca-cbd8f1bd0cd8 |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| 09545cca9c36c76f4982c4b648041a1606799b53 | Vidar C&C |
| d333c0b7e380afd2f156555b8110c00177b62e5d | Vidar C&C |
| e6c0468f46efe40f3127d33641bfc3df8b2e5c7d | PureLogsStealer C&C |
| 4664c47d412c00bf067a325ffa9790db75efbe75 | PureLogsStealer C&C |
| b3c1e060a727e4db1cf6131f1eb6e9bcca2ffb5d | PureRAT C&C |
| 11cfb1e85c316e9b9785c6778bc077bb04093dfd | PureLogsStealer C&C |
| c389945d4fc75250b291953e0abad0662dd9ce7d | Vidar C&C |
| 24ec954313877b212b522682aef606180ff6f343 | OffLoader C&C |
| 515574d4dc4957fbd0043d3a4269485384e504e7 | Vidar C&C |
| 51f9d6339bfdb9321630392913941e04d921cf7d | Vidar C&C |
| 9d4574e66ed485ca617fe78078a7dba674937bb3 | Vidar C&C |
| 629700c6fb58a48ce5c34e9e830225fad3e62634 | DCAgentRMM C&C |
| 6ae4974b641caa8b6aae8d3392e7fb4f8c7e3577 | DCAgentRMM C&C |
| 245f189a60a8b20a5dc562134b3d55d6539ac186 | Vidar C&C |
| ab1d61a4f4692b105daa345a7185119f0d29cb79 | Vidar C&C |
| 9769dce57ee77a6da94da9c824cd923cb9599892 | Vidar C&C |
| d621cfc19f287afe3b53ee95f4463732d2de342f | Malware C&C |
| 929b3729b42dabeb68077b03b2802e5b53ceade7 | ConnectWise C&C |
| 1c14689e58ebc09098f7c23eec08a314eb17ec76 | OffLoader C&C |
| 4a0c5885230b991333569023a767f7cc3a773baf | PureRAT C&C |

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
- 1.10.247.40
- 1.14.149.30
- 1.14.240.247
- 1.159.54.33
- 1.178.138.99
- 1.20.150.168
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.220.198.126
- 1.222.42.237
- 1.227.228.131
- 1.235.14.41
- 1.235.183.146
- 1.237.155.150
- 1.238.106.229
- 1.247.245.61
- 1.250.67.114
- 1.250.67.190
- 1.27.251.252

### CINS Army (poorly-rated IPs)
- 1.14.149.30
- 1.192.129.106
- 1.192.216.192
- 1.215.138.43
- 1.215.43.201
- 1.236.254.202
- 1.24.16.10
- 1.24.16.102
- 1.24.16.107
- 1.24.16.119
- 1.24.16.12
- 1.24.16.126
- 1.24.16.134
- 1.24.16.139
- 1.24.16.142
- 1.24.16.144
- 1.24.16.146
- 1.24.16.161
- 1.24.16.164
- 1.24.16.166

## News (last ~36h, across outlets)
### The Hacker News
- [Palo Alto Networks Patches PAN-OS Authenticated RCE Flaw Amid Active Exploitation](https://thehackernews.com/2026/10/palo-alto-networks-patches-pan-os.html)
- [Cisco Warns of Active Attacks Exploiting New Critical Secure Email Gateway Vulnerability](https://thehackernews.com/2026/10/cisco-warns-of-active-attacks.html)
- [Hackers Backdoor Nextcloud Servers Through Critical Flaw in Collabora’s Built-in CODE App](https://thehackernews.com/2026/10/hackers-backdoor-nextcloud-servers.html)
- [Microsoft Disrupts 3 Phishing Kits Linked to Over 1 Billion Scam Messages](https://thehackernews.com/2026/10/microsoft-disrupts-3-phishing-kits.html)
- [U.S. Shuts Down Over 40 Laptop Farms, Charges 14 in North Korean IT Worker Fraud](https://thehackernews.com/2026/10/us-shuts-down-over-40-laptop-farms.html)
- [CISA Urges Immediate Ivanti Connect Secure Updates as Honeypots Log 105 Exploit Attempts](https://thehackernews.com/2026/10/cisa-urges-immediate-ivanti-connect.html)
- [curl Patches HTTP/2 Upload Flaw After PoC Demonstrates Client-Side Code Execution](https://thehackernews.com/2026/10/curl-patches-http2-upload-flaw-after.html)
- [How to Run a Deepfake Readiness Drill Before a Cloned Voice Calls Your Team](https://thehackernews.com/2026/10/how-to-run-deepfake-readiness-drill.html)
- [Researchers Used a Public OpenAI Model to Build a $250,000 Chrome Full-Chain Exploit in Six Days](https://thehackernews.com/2026/10/researchers-used-public-openai-model-to.html)
- [Hirudo Android Trojan Uses Patched Banking Apps to Bypass Their Built-In Security Checks](https://thehackernews.com/2026/10/hirudo-android-trojan-uses-patched.html)
- [An AI Agent Found a Critical OTP Bypass in Production. The Attack Was the Easy Part.](https://thehackernews.com/2026/10/an-ai-agent-found-critical-otp-bypass.html)
- [AI-Found Linux Kernel Flaw Gives Local Users Root, and Can Break a Guest Out to the Host](https://thehackernews.com/2026/10/ai-found-linux-kernel-flaw-gives-local.html)
- [Four-Byte Write and Timing Bug Let Researchers Run Code in Windows SmartScreen Enclave](https://thehackernews.com/2026/10/four-byte-write-and-timing-bug-let.html)
- [Microsoft Patches Record 1,413 Flaws, Including Exploited Windows Shell Bug](https://thehackernews.com/2026/10/microsoft-patches-record-1413-flaws.html)
- [OpenAI Employee Arrested for Allegedly Planting Hidden Recorder in Executive Conference Room](https://thehackernews.com/2026/10/openai-employee-arrested-for-allegedly.html)

### BleepingComputer
- [UK Legal Aid Agency: Hackers stole records dating back to 1978](https://www.bleepingcomputer.com/news/security/uk-legal-aid-agency-hackers-stole-records-dating-back-to-1978/)
- [Palo Alto Networks warns of PAN-OS RCE flaw exploited in attacks](https://www.bleepingcomputer.com/news/security/palo-alto-networks-warns-of-pan-os-rce-flaw-exploited-in-attacks/)
- [FBI raids DPRK IT worker laptop farms in Texas, US nationals arrested](https://www.bleepingcomputer.com/news/security/fbi-raids-dprk-it-worker-laptop-farms-in-texas-us-nationals-arrested/)
- [Ledger asks sellers across Asia to halt sales after supply-chain attack](https://www.bleepingcomputer.com/news/security/ledger-asks-sellers-across-asia-to-halt-sales-after-supply-chain-attack/)
- [Cisco patches new Secure Email Gateway zero-day exploited in attacks](https://www.bleepingcomputer.com/news/security/cisco-patches-actively-exploited-secure-email-gateway-zero-day/)
- [Microsoft fixes VPN issues caused by September Windows updates](https://www.bleepingcomputer.com/news/microsoft/microsoft-fixes-vpn-issues-caused-by-september-windows-updates/)
- [The Blind Spots of Agentic Pentesting and How to Close Them](https://www.bleepingcomputer.com/news/security/the-blind-spots-of-agentic-pentesting-and-how-to-close-them/)
- [Global takedown hits network behind 1 billion phishing messages](https://www.bleepingcomputer.com/news/security/global-takedown-hits-network-behind-1-billion-phishing-messages/)
- [CISA warns admins to immediately fix Ivanti flaw exploited as zero-day](https://www.bleepingcomputer.com/news/security/cisa-warns-admins-to-immediately-fix-ivanti-flaw-exploited-as-zero-day/)
- [Hirudo Android malware replaces banking apps to evade security checks](https://www.bleepingcomputer.com/news/security/hirudo-android-malware-replaces-banking-apps-to-evade-security-checks/)
- [Microsoft: Recent Windows updates may trigger Remote Desktop failures](https://www.bleepingcomputer.com/news/security/microsoft-recent-windows-updates-may-trigger-remote-desktop-failures/)
- [OpenAI engineer arrested for allegedly planting spy device in office](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-engineer-arrested-for-allegedly-planting-spy-device-in-office/)
- [Ghostscript flaw lets hackers hijack servers via PDF uploads](https://www.bleepingcomputer.com/news/security/ghostscript-flaw-lets-hackers-hijack-servers-via-pdf-uploads/)
- [Anthropic warns self-replicating AI could spread to your smart devices](https://www.bleepingcomputer.com/news/security/anthropic-warns-self-replicating-ai-could-spread-to-your-smart-devices/)

### Krebs on Security
- [U.K. Sanctions Cryptomus for RU Money Laundering](https://krebsonsecurity.com/2026/10/u-k-sanctions-cryptomus-for-ru-money-laundering/)
- [Microsoft Patches More Than 1,400 Security Flaws](https://krebsonsecurity.com/2026/10/microsoft-patches-more-than-1400-security-flaws/)

### Dark Reading
- [EU Grocers Pay a Steep Price for Unpatched Fridge Firmware](https://www.darkreading.com/ics-ot-security/eu-grocers-unpatched-fridge-firmware)
- [Ivanti ICS Zero-Day Attacks Highlight Vendor Patching Hurdles](https://www.darkreading.com/vulnerabilities-threats/ivanti-ics-zero-day-attacks-vendor-patching)
- [Yam Store: The Phishing Network Behind a Billion Messages](https://www.darkreading.com/cyberattacks-data-breaches/yam-store-phishing-network-behind-billion-messages)
- [Anthropic 'SneakPeek' Flaw Is a Silent Zero-Click Threat](https://www.darkreading.com/threat-intelligence/new-anthropic-sneakpeek-silent-zero-click-threat)
- [Russian Influence Operation Widely Targeting Latin America](https://www.darkreading.com/cyberattacks-data-breaches/russian-influence-operation-targeting-latin-america)
- [Ransomware Gangs Embrace Physical Threats, Family Stalking?](https://www.darkreading.com/cybersecurity-analytics/ransomware-gangs-physical-threats-family-stalking)
- [Zero-Days Lurk in Microsoft's Overgrown October Patch Tuesday](https://www.darkreading.com/vulnerabilities-threats/zero-days-microsoft-october-patch-tuesday)
- [North Korea Phishes Ukrainians for War Intel](https://www.darkreading.com/cyberattacks-data-breaches/north-korea-phishes-ukrainians-war-intel)
- [Anthropic Finds Ingredients for Future AI Worms](https://www.darkreading.com/perimeter/anthropic-ingredients-future-ai-worms)

### SecurityWeek
- [Palo Alto Networks Patches PAN-OS Zero-Day Exploited for Remote Code Execution](https://www.securityweek.com/palo-alto-networks-patches-pan-os-zero-day-exploited-for-remote-code-execution/)
- [Cisco Warns of Exploited Secure Email Gateway Vulnerability](https://www.securityweek.com/cisco-warns-of-exploited-secure-email-gateway-vulnerability/)
- [AI Agents Navigate Unfamiliar OT Systems and Move Equipment in Minutes, Booz Allen Finds](https://www.securityweek.com/ai-agents-navigate-unfamiliar-ot-systems-and-move-equipment-in-minutes-booz-allen-finds/)
- [ICS Patch Tuesday: Siemens Issues 17 Advisories, Rockwell Fixes ArmorBlock Takeover Flaw](https://www.securityweek.com/ics-patch-tuesday-siemens-issues-17-advisories-rockwell-fixes-armorblock-takeover-flaw/)
- [Harmonic Security Raises $50 Million for Workforce AI Protection](https://www.securityweek.com/harmonic-security-raises-50-million-for-workforce-ai-protection/)
- [Virtual Event Today: Zero Trust Strategies Summit](https://www.securityweek.com/virtual-event-today-zero-trust-strategies-summit-2/)
- [Microsoft Disrupts Chinese-Language Phishing Market Behind 1B+ Messages](https://www.securityweek.com/microsoft-disrupts-chinese-language-phishing-market-behind-1b-messages/)
- [US Arrests Two in Crackdown on North Korean IT Worker Laptop Farms](https://www.securityweek.com/us-arrests-two-in-crackdown-on-north-korean-it-worker-laptop-farms/)
- [Chrome, Firefox Updates Patch 114 Flaws as Mozilla Unveils Firefox Enterprise](https://www.securityweek.com/chrome-firefox-updates-patch-114-flaws-as-mozilla-unveils-firefox-enterprise/)
- [Citrix, Fortinet, Ivanti Patch 29 Vulnerabilities Across Their Products](https://www.securityweek.com/citrix-fortinet-ivanti-patch-29-vulnerabilities-across-their-products/)

### The Record
- [North Macedonian police arrest alleged administrator behind OLVX cybercrime market](https://therecord.media/olvx-cybercrime-marketplace-arrest-north-macedonia)
- [Brooklyn DA’s office disrupts crypto scam targeting Russian community](https://therecord.media/brooklyn-da-server-takedowns-crypto-scam-russian-speakers)
- [Spyware manufacturer had access to data harvested by former Polish government, current PM says](https://therecord.media/spyware-manufacturer-had-access-to-data-harvested-by-previous-polish-government)
- [Microsoft takes down 3 major phishing platforms used by Chinese cybercriminals](https://therecord.media/microsoft-takes-down-3-major-chinese-phishing-platforms)
- [Russian travel booking platform suspends reservations after cyberattack](https://therecord.media/russia-anywayanyday-travel-website-cyberattack)

### Infosecurity Magazine
- [ROMULUS Malware Server Leverages ClickFix to Deliver Multiple Payloads](https://www.infosecurity-magazine.com/news/romulus-malware-clickfix-deliver/)
- [Passkey Authentications Double but Adoption Remains Slow](https://www.infosecurity-magazine.com/news/passkey-authentications-double/)
- [French Supermarket Cyber-Attack Impacts More Refrigeration Controllers](https://www.infosecurity-magazine.com/news/french-supermarket-hack-more/)
- [Microsoft Breaks Patch Tuesday Record Again with 1400+ CVEs](https://www.infosecurity-magazine.com/news/microsoft-patch-tuesday-record-1/)
- [Billion-Dollar Companies Twice as Likely to Leave Critical Vulnerabilities Unpatched](https://www.infosecurity-magazine.com/news/companies-leave-critical/)

### CyberScoop
- [Authorities charge alleged OLVX cybercrime marketplace operator in North Macedonia](https://cyberscoop.com/olvx-cybercrime-marketplace-operator-charged-north-macedonia/)
- [Microsoft drops an actively exploited zero-day among record high of 1,413 vulnerabilities](https://cyberscoop.com/microsoft-patch-tuesday-october-2026/)
- [Senators press Trump admin to rally federal government around AI safety, security](https://cyberscoop.com/congress-presses-trump-administration-ai-safety-cybersecurity/)
- [Microsoft and partners disrupt vast Chinese-language phishing kit ecosystem](https://cyberscoop.com/microsoft-disrupts-chinese-language-phishing-kit-ecosystem/)
- [Ivanti misses opportunity to fix vulnerability before attackers got to work and made it a zero-day](https://cyberscoop.com/ivanti-connect-secure-zero-day-actively-exploited/)
- [DOJ charges 14 over a sprawling North Korean remote work scheme](https://cyberscoop.com/doj-north-korea-remote-work-laptop-farms/)

### Cisco Talos
- [Break the silence: Kazakhstan-nexus UAT-6275 targets CIS government organizations](https://blog.talosintelligence.com/break-the-silence-kazakhstan-nexus-uat-6275-targets-cis-government-organizations/)
- [Microsoft Patch Tuesday for October 2026 — Snort rules and prominent vulnerabilities](https://blog.talosintelligence.com/microsoft-patch-tuesday-for-october-2026/)

### Unit 42 (Palo Alto)
- [Unit 42 Uncovers PEERSTITCH, a Stealthy FortiGate Implant](https://unit42.paloaltonetworks.com/fortimanager-cve-2024-47575-peerstitch-malware/)
- [The Noise Inside the Network: How an Unsophisticated Attack Exposed a Third-Party Risk](https://unit42.paloaltonetworks.com/noise-inside-network-third-party-risk/)

### Microsoft Security Blog
- [The hidden network: Inside the phishing infrastructure ecosystem powering global cybercrime](https://www.microsoft.com/en-us/security/blog/2026/10/14/the-hidden-network-inside-the-phishing-infrastructure-ecosystem-powering-global-cybercrime/)

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
- [ISC Stormcast For Thursday, October 15th, 2026 https://isc.sans.edu/podcastdetail/10138, (Thu, Oct 15th)](https://isc.sans.edu/diary/rss/33428)
- [Panchan's Mining Island &#x5b;Guest Diary&#x5d;, (Wed, Oct 14th)](https://isc.sans.edu/diary/rss/33426)
- [Orphaned VBA Projects Inside DWG Files, (Wed, Oct 14th)](https://isc.sans.edu/diary/rss/33420)
- [ISC Stormcast For Wednesday, October 14th, 2026 https://isc.sans.edu/podcastdetail/10136, (Wed, Oct 14th)](https://isc.sans.edu/diary/rss/33424)

### Securelist (Kaspersky)
_No new items / feed unavailable this run._

### CrowdStrike Blog
- [October 2026 Patch Tuesday: 1,413 CVEs Include Three Zero-Days and 75 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-october-2026/)
- [U.S. Government Disrupts FAMOUS CHOLLIMA Operation with CrowdStrike Assistance](https://www.crowdstrike.com/en-us/blog/fbi-disrupts-famous-chollima-operation-with-crowdstrike-assistance/)
- [CrowdStrike and Anthropic Give Critical Infrastructure Defenders the AI Advantage](https://www.crowdstrike.com/en-us/blog/crowdstrike-anthropic-critical-infrastructure-defense-program/)
- [Solving the Continuous Authorization Conundrum](https://www.crowdstrike.com/en-us/blog/solving-the-continuous-authorization-conundrum/)
- [Unknown Threat Actor Uses AI-Driven ARTEX to Target South Korean Finance](https://www.crowdstrike.com/en-us/blog/unknown-threat-actor-uses-artex-to-target-south-korean-finance/)
- [CrowdStrike Named a Leader in the 2026 IDC MarketScape for Worldwide Modern Endpoint Security for Enterprises Vendor Assessment](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-idc-marketscape-worldwide-modern-endpoint-security-for-enterprises/)
- [Request, Aggregate, Bypass: How Attackers Can Evade LLM Safety Classifiers](https://www.crowdstrike.com/en-us/blog/how-attackers-can-bypass-llm-safety-classifiers/)
- [Falcon Data Security for SaaS Secures Sensitive Data in Microsoft 365](https://www.crowdstrike.com/en-us/blog/falcon-data-security-for-saas-secures-sensitive-data/)
- [New in Falcon Cloud Security: Third-Party App Insights and AI-Enhanced Remediation](https://www.crowdstrike.com/en-us/blog/falcon-cloud-security-third-party-app-insights-ai-enhanced-remedation/)
- [CrowdStrike Expands Federal SOC Modernization Through CISA-Funded SIEMaaS](https://www.crowdstrike.com/en-us/blog/crowdstrike-expands-federal-soc-modernization-via-cisa-siemaas/)

### FortiGuard Threat Signal
_No new items / feed unavailable this run._

## Fetch issues this run
_None — all sources responded._

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal