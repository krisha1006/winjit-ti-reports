# Winjit Daily TI Digest — 2026-11-17

_Auto-generated. Window: last ~24h. Fetched at 2026-11-17T11:37:27.184889+00:00Z_

**At a glance:** 0 new KEV · 36 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-129952 | 9.8 | n/a | NodePress through 8.5.1 contains an authentication bypass vulnerability that allows unauthenticated remote attackers to gain administrator access by forging JWTs with the hardcoded 'nodepress-secret'  |
| CVE-2026-129955 | 9.8 | n/a | NodePress through 8.5.1 contains an authentication bypass vulnerability that allows unauthenticated attackers to gain administrator access by using the hardcoded default password 'root'. Attackers can |
| CVE-2026-130071 | 9.8 | n/a | TridotsTech go1cms master branch through commit 7f68d05 and version-3 branch before commit ead8da3 contains a missing authentication vulnerability in the guest-whitelisted update_doc method that allow |
| CVE-2026-79614 | 9.8 | n/a | An out-of-bounds write vulnerability in “libclinkc.so” in Zyxel DX3301-T0/EX3301-T0 firmware versions through 5.50(ABVY.8.3)C0 could allow an unauthenticated attacker to elevate privileges and potenti |
| CVE-2026-130070 | 9.1 | n/a | Ghost by muneeb141 on the main branch from commit c731cdf through commit 672dfec contains an authentication bypass vulnerability in the whitelisted ghost.api.ghost.convert_to_real_user method that all |
| CVE-2026-130072 | 9.1 | n/a | Cloud Commander (cloudcmd) before 19.21.4 contains an authentication bypass and path traversal vulnerability that allows unauthenticated attackers to rename files by sending PUT /rename requests handl |
| CVE-2026-129545 | 8.8 | n/a | Kalmia through 0.2.0 contains a privilege escalation vulnerability that allows low-privileged authenticated users to modify any account via the /kal-api/auth/user/edit endpoint. Attackers holding only |
| CVE-2026-129948 | 8.8 | n/a | Contentlayer @contentlayer/source-files through 0.3.4 contains a code injection vulnerability that allows attackers who control content files to execute JavaScript by abusing gray-matter's still-enabl |
| CVE-2026-130082 | 8.8 | n/a | django-tenants 3.4.8 before 4.0.1 contains an SQL injection vulnerability in its PostgreSQL backend that allows attackers to inject SQL through unescaped tenant schema names. Attackers who can choose  |
| CVE-2026-130361 | 8.8 | n/a | AdminNeo before 5.9.1 contains a parameter injection vulnerability in its ClickHouse driver that allows attackers to inject ClickHouse HTTP query parameters through an unencoded db GET parameter. Atta |
| CVE-2026-130382 | 8.8 | n/a | AdminNeo before 5.9.1 contains an authentication bypass vulnerability in OtpLoginPlugin that allows attackers knowing the database password to skip TOTP verification by abusing the permanent-login coo |
| CVE-2026-130073 | 8.3 | n/a | CBoard before commit 7bd8180 contains a missing authorization vulnerability that allows any authenticated user to reach admin functions because AdminController and DashboardController methods bypass A |
| CVE-2026-130074 | 8.1 | n/a | free5GC WebConsole through 1.4.6 contains an authorization flaw in the ChangePasswordInfo handler that allows authenticated tenant users to change other members' passwords. Attackers can send POST /ap |
| CVE-2026-130366 | 8.1 | n/a | AdminNeo before 5.9.1 contains an authentication bypass vulnerability in the ClickHouse driver that allows remote attackers to log in to passwordless accounts without the configured defaultPasswordHas |
| CVE-2026-130369 | 8.1 | n/a | phpMyFAQ 4.1.9 before 4.1.12 and 4.2.0-alpha before 4.2.0-RC.2 contains an authorization bypass vulnerability in multisite deployments that allows attackers to overwrite passkeys of accounts on other  |
| CVE-2026-130371 | 8.1 | n/a | phpMyFAQ before 4.1.12 and 4.2.0-alpha before 4.2.0-RC.2 contains an authentication bypass vulnerability because the web installer ignores the legacy config/database.php during 3.x upgrades. Unauthent |
| CVE-2026-130380 | 8.1 | n/a | AdminNeo before 5.9.1 contains an authentication bypass vulnerability in the sqlsrv-based MS SQL driver that allows unauthenticated attackers to log in by submitting an empty username. Attackers can s |
| CVE-2026-121684 | 8.1 | n/a | The Soledad theme for WordPress is vulnerable to unauthenticated Remote Code Execution in versions up to, and including, 8.7.7 The public penci_more_post_ajax AJAX action feeds infeedads[ads_code] (ba |
| CVE-2026-129947 | 8.0 | n/a | Contentlayer @contentlayer/core through 0.3.4 contains a code injection vulnerability that allows attackers to inject JavaScript by embedding single quotes in content file names. Attackers can add a c |
| CVE-2026-129956 | 7.8 | n/a | Sandboxie-Plus before 1.18.6 contains a local privilege escalation vulnerability in SbieSvc that allows standard users to launch UpdUtil.exe as SYSTEM via MSGID_PROCESS_RUN_UPDATER requests. Attackers |
| CVE-2026-124019 | 7.8 | n/a | VB-Audio VB-CABLE virtual audio device kernel streaming driver (vbaudio_cable64_win10.sys 10.0.10011.16384) contains out-of-bounds read and write vulnerabilities in its KSPROPSETID_Audio MUTE, VOLUMEL |
| CVE-2026-130067 | 7.8 | n/a | 7-Zip File Manager before 26.03 fails to detect archive entry names padded with Unicode space characters, allowing attackers to bypass the deceptive file name warning in CPanel::IsVirus_Message. Attac |
| CVE-2026-129880 | 7.7 | n/a | DeepAudit 2.0.0-beta.5 through 3.8.0 contains a server-side request forgery vulnerability that allows registered users to leak server-wide GitLab or Gitea tokens via repository_url. Attackers can crea |
| CVE-2026-129494 | 7.5 | 0.4% | CloudPaste 1.1.0 through 1.9.1 contains an information disclosure vulnerability that allows unauthenticated attackers to obtain WebDAV storage credentials through the unauthenticated /api/proxy/link e |
| CVE-2026-129872 | 7.5 | n/a | REBUILD 2.7.0 through 4.5.4 contains an SQL injection vulnerability that allows low-privileged authenticated users to inject AjQL conditions through the plan parameter of /project/tasks/list. Attacker |
| CVE-2026-127218 | 7.5 | n/a | Axigen Mail Server 10.3.3.67 through 10.3.3.x, 10.4.42 through 10.4.x, 10.5.29 through 10.5.x, 10.6.x before 10.6.41, and 10.7.x before 10.7.3 contains an unauthenticated denial of service vulnerabili |
| CVE-2026-130081 | 7.5 | n/a | B3log Solo through 4.4.0 contains an information disclosure vulnerability that allows unauthenticated attackers to obtain article view passwords by querying the public GET /articles API. The ArticlePr |
| CVE-2026-12487 | 7.5 | n/a | An incorrect authorization vulnerability in the SNMP parameter of Zyxel EE5301-00 customized firmware version 5.63(ACLD.2)b3_D0 could allow an unauthenticated attacker to cause a denial-of-service (Do |
| CVE-2026-130374 | 7.5 | n/a | AdminNeo before 5.9.1 contains an sql injection vulnerability that allows remote attackers to inject SQL by supplying crafted IN and NOT IN search values that process_length() passes unescaped. Attack |
| CVE-2026-118496 | 7.5 | n/a | The affected products process a server-supplied URL without sufficient validation. An unauthenticated remote attacker controlling a malicious Automation Server and tricking a user to trust it or perfo |
| CVE-2026-118498 | 7.5 | n/a | The CODESYS Automation Server Connector uses server-supplied file names without sufficient path traversal checks. An unauthenticated remote attacker controlling a malicious Automation Server and trick |
| CVE-2026-129943 | 7.2 | n/a | Prime CMS (@primecms/core) through 0.4.0-beta.0 contains an OS command injection vulnerability in the updateSystem GraphQL mutation that allows authenticated administrators to execute shell commands v |
| CVE-2026-130351 | 7.2 | n/a | phpMyFAQ from 4.2.0-alpha before 4.2.0-RC.2 contains an authorization bypass vulnerability in the multisite Redis configuration store that is not tenant-scoped. As a result, tenant administrators can  |
| CVE-2026-130375 | 7.2 | n/a | AdminNeo before 5.9.1 contains a remote code execution vulnerability that allows authenticated SQLite users to bypass the check_sqlite_name() extension guard using PDO_SQLite file: URI database names. |
| CVE-2026-86676 | 7.2 | n/a | A post-authentication command injection vulnerability in the “Description” parameter of a CGI program  in Zyxel DX3300-T0 firmware versions through 5.50(ABVY.8.3)C0 could allow an authenticated attack |
| CVE-2026-119643 | 7.2 | n/a | The MembershipWorks - Membership, Events & Directory plugin for WordPress is vulnerable to Stored Cross-Site Scripting in all versions up to, and including, 6.17. This is due to insufficient output es |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-v2xh-2vwr-xq7g | CVE-2026-124709 | unknown | Issue summary: A QUIC server that rejects a stream opened by the peer may
retain that stream's... |
| GHSA-r3mj-hq6x-h82q | CVE-2026-35190 | unknown | Issue summary: A server configured with the Suite B certificate flag through... |
| GHSA-vxv7-5cfm-pc9q | CVE-2026-119643 | high | The MembershipWorks - Membership, Events & Directory plugin for WordPress is vulnerable to Stored... |
| GHSA-jvvm-vvmf-jf3r | CVE-2026-107493 | unknown | Issue summary: When an application passes a stack to
PEM_X509_INFO_read_bio_ex() to add entries... |
| GHSA-rp52-r53q-gv6m | CVE-2026-109151 | high | In
the Matter and Aliro Door Lock Application of the Nordic Semiconductor nRF Door
Lock and... |
| GHSA-c7qq-qq3c-65gx | CVE-2026-109148 | high | In the Aliro access control reference
  applications of the Nordic Semiconductor nRF Door Lock... |
| GHSA-85xr-x9r6-2hqr | CVE-2026-129012 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-hwm6-pp9v-v95x | CVE-2026-109154 | high | In the Matter door lock applications of
  the Nordic Semiconductor nRF Door Lock and Access... |
| GHSA-9cjc-hw4q-x58r | CVE-2026-128038 | medium | The All in One SEO – AI SEO Plugin to Boost SEO Rankings & Traffic (Schema, Local SEO, Sitemap &... |
| GHSA-6j4r-jvx7-7q22 | CVE-2026-129008 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-c28g-pmhp-fmjg | CVE-2026-107904 | unknown | Joomla Extension - valorapps.com - Unauthenticated Remote Code Execution in Easy File Uploader <... |
| GHSA-8qgj-93hh-243h | CVE-2026-129031 | medium | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')... |
| GHSA-pqpq-c5v5-6m96 | CVE-2026-109138 | high | In the Aliro access control reference
  applications of the Nordic Semiconductor nRF Door Lock... |
| GHSA-w2jp-p4hm-xgmr | CVE-2026-85778 | medium | GitLab has remediated an issue in GitLab EE affecting all versions from 19.1 before 19.3.9, 19.4... |
| GHSA-gvx6-3p26-6527 | CVE-2026-18241 | high | GitLab has remediated an issue in GitLab CE/EE affecting all versions from 9.3 before 19.3.9, 19... |
| GHSA-657f-xr79-8gq2 | CVE-2026-111973 | unknown | The RSS Feed Retriever WordPress plugin through 1.6.10 does not validate a user-supplied URL... |
| GHSA-hhw5-pwp3-qhxw | CVE-2026-97639 | medium | The Everest Backup – WordPress Cloud Backup, Migration, Restore & Cloning Plugin plugin for... |
| GHSA-34m6-5973-3qmh | CVE-2026-129253 | medium | GitLab has remediated an issue in GitLab EE affecting all versions from 19.1 before 19.3.9, 19.4... |
| GHSA-88cc-xcj9-p6m5 | CVE-2026-126141 | low | GitLab has remediated an issue in GitLab CE/EE affecting all versions from 11.11 before 19.3.9,... |
| GHSA-4vp5-hwgc-rpm8 | CVE-2026-128849 | medium | GitLab has remediated an issue in GitLab EE affecting all versions from 19.5 before 19.5.6 that... |
| GHSA-x65q-ww88-vfc5 | CVE-2026-129252 | low | GitLab has remediated an issue in GitLab CE/EE affecting all versions before 19.3.9, 19.4 before... |
| GHSA-hgw2-f5fc-3vf5 | CVE-2026-18491 | medium | GitLab has remediated an issue in GitLab CE/EE affecting all versions from 19.2 before 19.3.9, 19... |
| GHSA-j7xh-v8qf-wv2f | CVE-2026-16609 | medium | GitLab has remediated an issue in GitLab CE/EE affecting all versions from 13.2 before 19.3.9, 19... |
| GHSA-4gph-35hq-pq85 | CVE-2026-16545 | medium | GitLab has remediated an issue in GitLab CE/EE affecting all versions from 12.10 before 19.3.9,... |
| GHSA-m568-rhvp-5prc | CVE-2026-125920 | medium | GitLab has remediated an issue in GitLab EE affecting all versions from 17.4 before 19.3.9, 19.4... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| Molex (Koch) - 16,448,279 records | Vortex | US | 2026-11-17T02:32:30.271274+00:00 |
| Mycorpass (Carrington Mortgage Services) | Vortex | US | 2026-11-17T02:31:56.047102+00:00 |
| Apellis Pharmaceuticals | Vortex | US | 2026-11-17T02:31:21.549828+00:00 |
| Castle Biosciences - 2,018,234 records | Vortex | US | 2026-11-17T02:30:47.111740+00:00 |
| Caris Life Sciences - 21,432,021 records | Vortex | US | 2026-11-17T02:30:12.795588+00:00 |
| Owens-Minor - 57,985,343 records | Vortex | US | 2026-11-17T02:29:37.700659+00:00 |
| Instant Access | netrunner | KW | 2026-11-16T23:17:57.671963+00:00 |
| ex********s.com | Curious Worm |  | 2026-11-16T22:51:42.662914+00:00 |
| Anmat Technology for Trading Co. | Aoqin | SA | 2026-11-16T22:50:50.802611+00:00 |
| risingpharma.com | Curious Worm | US | 2026-11-16T21:20:53.219501+00:00 |
| radienzliving.com | chaos | DE | 2026-11-16T21:00:23.135984+00:00 |
| amarok.com | chaos |  | 2026-11-16T20:59:45.796201+00:00 |
| APELLIS | Vortex | US | 2026-11-16T20:57:31.742840+00:00 |
| Johnson Bros. Bakery Supply, Inc. | Global Secret Group | US | 2026-11-16T20:22:36.744745+00:00 |
| t**l**kw*****p.com | Curious Worm |  | 2026-11-16T20:21:01.827129+00:00 |
| Burney Wealth | Shiba | GB | 2026-11-16T19:36:14.075930+00:00 |
| RICK HINDERER KNOVES LLC | Global Secret Group | US | 2026-11-16T19:22:48.648940+00:00 |
| Q... | SilentRansomGroup |  | 2026-11-16T17:39:58.020107+00:00 |
| interdent.com | Curious Worm | DE | 2026-11-16T17:22:03.967794+00:00 |
| Waterman Group | rhysida | GB | 2026-11-16T17:04:04.991303+00:00 |

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
| 45.148.10.151 | 11 |
| 45.148.10.152 | 11 |
| 77.239.124.252 | 11 |
| 138.226.239.233 | 11 |
| 45.148.10.141 | 10 |
| 45.148.10.157 | 10 |
| 138.226.239.234 | 10 |
| 45.156.87.65 | 9 |
| 64.62.197.48 | 9 |
| 66.132.172.111 | 9 |
| 167.94.146.48 | 9 |
| 167.94.146.53 | 9 |
| 193.32.162.15 | 9 |
| 193.187.110.160 | 9 |
| 196.189.236.67 | 9 |
| 18.218.118.203 | 8 |
| 35.210.19.131 | 8 |
| 35.210.65.254 | 8 |
| 35.210.125.227 | 8 |
| 45.14.225.216 | 8 |

### OpenPhish (live phishing URLs)
- http://megashorkxturtle.github.io/Netflix__clone
- https://store.workshopcommunitybrowse.com/sharedfiles/filesdetails/id=3832495514/
- https://eepoint.wtwco.us/ess/bnpp/Login/Index
- http://cryptocomappstillcantlogin.netlify.app/
- http://netflix-abonnement.com/success.php
- https://susannesousadasilva.github.io/Supplies
- http://php-membr.wasmer.app/
- http://conatem.com/adobeStudio.html
- http://hub-open-bxnm.p-xxorevv8.workers.dev/
- http://www.wwrreret264758.weebly.com/
- https://ra-krxu.vercel.app/
- https://kucinonlogen.gitbook.io/us
- https://kucinonlogen.gitbook.io/
- http://verifynownow.webflow.io/
- https://metxmsaklogan.gitbook.io/us
- https://metxmsaklogan.gitbook.io/
- http://plenor-qudrik-f27ab5-thjj-z2406ach.pages.dev/
- http://databaseserver-sigma.vercel.app/
- http://eng-upholld-en.square.site/
- https://roblox.com.gr/users/757568109566/profile

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://www.paleronix.com/0vc0amatamjb.php |
| N/A | https://away.vk.ru/away.php?rh=8430b0b7-1dec-43ab-927a-66bb3fb85056 |
| N/A | https://away.vk.ru/away.php?rh=f2de5cd4-a101-4aed-ab65-b18ca2937008 |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AaSxoQyQEeCdGiNQploah5nAij7vrMqrlVIHby1Q4v_ARx9kttGkmffM4ARVCnkvjXQyGpUqW4kQNA&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBgld9IZH4CIVs2yhKeD7clSl7_EvrI2NKs9GGdA1zP7n0-Q4rbY2LCLqvDYsEoM-boKlKC8g7jg&dsh=S-1910487178%3A1794914823425083 |
| N/A | https://away.vk.ru/away.php?rh=bc872983-639f-489d-ba4c-389d71a9620f |
| N/A | https://away.vk.ru/away.php?rh=58071ac3-6f41-4058-9da2-b90acce6b09e |
| N/A | https://yandex.ru/showcaptcha?cc=1&form-fb-hint=2.1.6478f72a2b8ae650abee94d9f75e236a3b4f6cc75d2cb3912355dbb79377a45c9f48bd3c3e42e964f7717239b45a62a0c563dee1facfed87cbbdb297c315f19aa8b02edb73f42391&mt=88B1A84A4BDC0AE2E26BFD0B54DB19C5876C33A39A24BC9BBDB0945349ACC2897EDD5FD9A671BF08CF53F988DD63162ACCF7D804B36B47B8265E3184E5D4938348F1A69CCB52F5A8FE8500B1AE3A0D342A2AF28B33D53728CBDFAF199DD608E38F3A0890A9E12AE6C0DFDBD1B0419442B30BC0BA4B525EDB09217D87FB08B75E7447E30F45297231C5CD53C1D561B266FCA69799C8521FA42962C5811F2D43272B2547FF31D87F&retpath=aHR0cHM6Ly95YW5kZXgucnUvc2VhcmNoP3RleHQ9MjExNjg3MTc%2C_02b414258f0c5ddfd482bb59523d8ed6&t=2%252F1794914401%252F65f538f79f216597792e993b91c8de81&u=9774202011192061331&s=774151973c25692ea3fe091df5517ba6 |
| N/A | https://away.vk.ru/away.php?rh=5771ddfd-2836-49e6-8002-6f789d2549a1 |
| N/A | http://49.51.43.12/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AQMjQ7QyROPzn0qaqnYvX4_aw7qH8RajahyDV4UI8mo2Mw7SaNi-z6QQG4MH4pDlzJ2gDPTt_nm2&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBglfUOSfh2kC0yC4UWYptFcA9rHJoovHTA-k-opoDOyaIyPs4HafJ4k-aK5tyYSlyRx1geRfX&dsh=S805806016%3A1794913819169712 |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AaSxoQyQ_ZSuXpSvue0UfKrOXnU6mQAuN0RcLmvWGTqSCzhKlOsPyDT7wQQH6ra2Rhdw1PE87iTB&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBglc_CDzajydA-5mZfBFC56RBtYMPUqolRiKYT1YbqU81Svp_wHE-c1_uatBGUVuVP5HslMmbCw&dsh=S856234081%3A1794913824594312 |
| N/A | https://id.superhuman.com/signin?oauth_client_type=MEDIATED_WEB&correlation_id=LxFbyxFZwtWAHxjYvaMiEg&version=v4&client_id=superhumanDocs |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AQMjQ7TPKu6R4w93VRXMPKeD3zeOl4EoNrOdcsDBPMv7m30JK47iKcBvHB2Y608BaGxX8bX4kwt6sA&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBglfqRUPS6WHZeUQKCGBxo3CPP_LkswIf4mLrzoMZEUQmm5pjuv9RbHKGKUxoVOME20Htwv2t&dsh=S-148421622%3A1794913550210654 |
| N/A | https://skinsmonkey.com?referrer=pid%3D1%26af_tranid%3DNzMyNjY1NDA1NDI4NTA5MzY4 |
| N/A | https://global-cn-candy-party.com/98E1p0QT/logininfo |
| N/A | https://away.vk.ru/away.php?rh=07add864-d352-405d-929f-1f5c8d4e8489 |
| N/A | https://www.cdiscount.com?source_id=&sub1=dbu37ae0fgns73ainf30&adv1=&adv2= |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=ASKXGp0_nbFzdHoBsG_d6znGlWE063OUXUJ-liVgQNfJJB3wA_mip4wV6In-9Cchxtm7MSHwtubxoQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBglca-_ErvPC0fMNVkESkcsnRHS0hCW_y7KFYR7ITOwmqeyqLLiKYZoXrpCfN5-dT__3xtv2BzA&dsh=S-13244274%3A1794912915289627 |
| N/A | https://away.vk.ru/away.php?rh=36e4fa3f-d151-4d58-ba1d-fff8d30783cc |
| N/A | https://away.vk.ru/away.php?rh=6368dbde-b956-4135-9e34-67a6d0ae4b48 |
| N/A | http://away.vk.ru/away.php?rh=d2a11b76-a727-4d1e-b204-7b3381761f2b |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
_No data returned this run._

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
- 1.12.55.42
- 1.13.156.111
- 1.13.79.149
- 1.14.140.218
- 1.162.194.101
- 1.163.28.132
- 1.170.208.15
- 1.172.102.101
- 1.2.252.192
- 1.20.184.8
- 1.20.252.234
- 1.203.149.250
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.222.42.237
- 1.234.21.73
- 1.234.27.159

### CINS Army (poorly-rated IPs)
- 1.12.229.231
- 1.14.3.170
- 1.14.75.196
- 1.15.14.29
- 1.158.42.208
- 1.168.168.47
- 1.168.185.245
- 1.179.240.157
- 1.192.129.106
- 1.193.63.143
- 1.220.119.115
- 1.224.163.125
- 1.24.16.103
- 1.24.16.104
- 1.24.16.111
- 1.24.16.12
- 1.24.16.122
- 1.24.16.123
- 1.24.16.126
- 1.24.16.145

## News (last ~36h, across outlets)
### The Hacker News
- [New GitDoor and GraphDoor Backdoors Turn GitHub and SharePoint Into Covert C2 Channels](https://thehackernews.com/2026/11/new-gitdoor-and-graphdoor-backdoors.html)
- [Apple Tightens macOS App Permissions to Limit Data Access Amid AI Agent Security Risks](https://thehackernews.com/2026/11/apple-tightens-macos-app-permissions-to.html)
- [Hijacked Optimizely Scripts Served Card Skimmer and iOS Exploit Kits to CNN, BBC and Zoom Visitors](https://thehackernews.com/2026/11/hijacked-optimizely-scripts-served-card.html)
- [ConnectWise Warns ScreenConnect Attacks Continue as SCKit Targets Unpatched Systems](https://thehackernews.com/2026/11/connectwise-warns-screenconnect-attacks.html)
- [N-able Patches 17 N-central Flaws as Attackers Exploit Earlier Bugs to Deploy Crypto Miners](https://thehackernews.com/2026/11/n-able-patches-17-n-central-flaws-as.html)
- [Google Finds Hackers Using AI Agents to Build and Run Exploits From Software Patches](https://thehackernews.com/2026/11/google-finds-hackers-using-ai-agents-to.html)
- [⚡ Weekly Recap: N-able 0-Days, Windows 0-Days, Chrome 0-Days, Fridge 0-Days, and More Bad Days](https://thehackernews.com/2026/11/weekly-recap-n-able-0-days-windows-0.html)
- [Six Unpatched Danfoss Refrigeration Controller Flaws Could Allow Remote Takeover Without Login](https://thehackernews.com/2026/11/six-unpatched-danfoss-refrigeration.html)
- [Retadup Worm Resurfaces 7 Years After Takedown to Spread CoffeeLoader Malware](https://thehackernews.com/2026/11/retadup-worm-resurfaces-7-years-after.html)
- [SANSAR Linux Cryptomining Malware Uses Modified NVIDIA Library to Hide GPU Activity](https://thehackernews.com/2026/11/sansar-linux-cryptomining-malware-uses.html)
- [Amazon Uncovers AI Agent Campaign Targeting LiteLLM, Dify, and Other Apps for API Keys](https://thehackernews.com/2026/11/amazon-uncovers-ai-agent-campaign.html)
- [BO Team Exploits Log4Shell in VMware vCenter, Compromises Russian Firm's Code-Signing Server](https://thehackernews.com/2026/11/bo-team-exploits-log4shell-in-vmware.html)

### BleepingComputer
- [Microsoft testing Remote Lock for lost or stolen Windows devices](https://www.bleepingcomputer.com/news/microsoft/microsoft-testing-remote-lock-for-lost-or-stolen-windows-devices/)
- [Court clears brothers of $25 million Ethereum crypto heist charges](https://www.bleepingcomputer.com/news/security/court-clears-brothers-of-25-million-ethereum-crypto-heist-charges/)
- [Uber notifies drivers of data breach affecting nearly 150,000 people](https://www.bleepingcomputer.com/news/security/uber-notifies-drivers-of-data-breach-affecting-nearly-150-000-people/)
- [Ransomware affiliate suspect extradited to US, faces 27 years in prison](https://www.bleepingcomputer.com/news/security/alleged-inc-lynx-ransomware-affiliate-extradited-to-us-faces-27-years-in-prison/)
- [Optimizely hack infected CNN, Fox News, BBC, Salesforce sites with malware](https://www.bleepingcomputer.com/news/security/optimizely-supply-chain-attack-delivers-malware-to-cnn-fox-news-bbc-salesforce-sites/)
- [Gemini AI agents repeatedly bypassed safeguards to attack real website](https://www.bleepingcomputer.com/news/security/gemini-ai-agents-repeatedly-bypassed-safeguards-to-attack-real-website/)
- [Google Project Zero cuts bug disclosures to 30 days amid AI threats](https://www.bleepingcomputer.com/news/security/google-project-zero-cuts-bug-disclosure-deadline-to-30-days-amid-ai-threats/)
- [California sues OpenAI over AI agents escaping sandboxes, hacking firms](https://www.bleepingcomputer.com/news/security/california-sues-openai-over-ai-agents-escaping-sandboxes-hacking-firms/)
- [Barracuda links cloud breach to ARTEX AI-powered cyberattack](https://www.bleepingcomputer.com/news/security/barracuda-links-cloud-breach-to-artex-ai-powered-cyberattack/)
- [Microsoft says months-old bug caused global Microsoft 365 outage](https://www.bleepingcomputer.com/news/microsoft/microsoft-says-months-old-bug-caused-global-microsoft-365-outage/)
- [Fandango says hackers stole payment card details from checkout pages](https://www.bleepingcomputer.com/news/security/fandango-says-hackers-stole-payment-card-details-from-checkout-pages/)
- [7 Tips For Complying with CJIS Password and MFA Requirements](https://www.bleepingcomputer.com/news/security/7-tips-for-complying-with-cjis-password-and-mfa-requirements/)
- [Google warns that fully-automated AI attacks are coming soon](https://www.bleepingcomputer.com/news/security/google-warns-that-fully-automated-ai-attacks-are-coming-soon/)
- [Microsoft: Windows Server 2016 reaches end of support in 60 days](https://www.bleepingcomputer.com/news/microsoft/microsoft-windows-server-2016-reaches-end-of-support-in-60-days/)
- [Australian retail giant Coles investigates cybersecurity incident](https://www.bleepingcomputer.com/news/security/australian-retail-giant-coles-investigates-cybersecurity-incident/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [Google Project Zero Slashes Bug Disclosure Deadlines, Splitting Experts](https://www.darkreading.com/vulnerabilities-threats/google-project-zero-bug-disclosure-deadlines)
- [Ransomware Attacks Increase Behind AI, But Payments Decline](https://www.darkreading.com/threat-intelligence/ransomware-attacks-increase-ai-payments-decline)
- ['Sleeper Agent' Tactic Hides Payloads in Open-Weight AI Models](https://www.darkreading.com/vulnerabilities-threats/sleeper-agent-tactic-payloads-open-weight-ai-models)
- [China-Nexus Actors Breach 10 Organizations in AI-Driven Attacks](https://www.darkreading.com/cyberattacks-data-breaches/china-nexus-actors-breach-10-organizations-ai-driven-attacks)

### SecurityWeek
- [Optimizely Vulnerability Exploited to Serve Malware on Major Websites](https://www.securityweek.com/optimizely-vulnerability-exploited-to-serve-malware-on-major-websites/)
- [Trump Administration Moves to Block China From Indirect Access to American AI Technology](https://www.securityweek.com/trump-administration-moves-to-block-china-from-indirect-access-to-american-ai-technology/)
- [Cursor Supply Chain Attack Started at Fireworks AI](https://www.securityweek.com/cursor-supply-chain-attack-started-at-fireworks/)
- [Google Project Zero Sets Course for 30-Day Disclosure Deadline](https://www.securityweek.com/google-project-zero-sets-course-for-30-day-disclosure-deadline/)
- [Barracuda Hacked Amid Surge in Artex-Powered Cyberattacks](https://www.securityweek.com/barracuda-hacked-amid-surge-in-artex-powered-cyberattacks/)
- [Telegram Widgets Hit by RCE Demos, Malware Warning Days After Launch](https://www.securityweek.com/telegram-widgets-hit-by-rce-demos-malware-warning-days-after-launch/)
- [Recent UnrealIRCd Vulnerability Exploited in Attacks](https://www.securityweek.com/recent-unrealircd-vulnerability-exploited-in-attacks/)
- [Hackers Probe Newly Disclosed Flaws in Copeland Refrigeration Controllers](https://www.securityweek.com/hackers-probe-newly-disclosed-flaws-in-copeland-refrigeration-controllers/)
- [Uber Data Breach Impacts 150,000 People](https://www.securityweek.com/uber-data-breach-impacts-150000-people/)
- [Tor Updates DoS Defenses Again as Relay Attacks Continue](https://www.securityweek.com/tor-updates-dos-defenses-again-as-relay-attacks-continue/)

### The Record
- [Uber says nearly 150,000 impacted by third-party breach](https://therecord.media/uber-says-150000-impacted-third-party-breach)
- [California sues OpenAI for Hugging Face and other incidents, alleging deception and recklessness](https://therecord.media/california-sues-openai-hugging-face)
- [Match fined $10 million for alleged Tinder privacy violations](https://therecord.media/ireland-tinder-privacy-fine)
- [Italian regulator fines Meta $886 million for violating data privacy law](https://therecord.media/italian-regulator-fines-meta-886-million-privacy)
- [King Charles opens new HQ for National Cyber Force, UK’s offensive hacking unit](https://therecord.media/uk-national-cyber-force-headquarters-opens)

### Infosecurity Magazine
- [ICO Issues GTA 6 Scam Warning as Release Date Nears](https://www.infosecurity-magazine.com/news/ico-gta-6-scam-warning-release/)
- [Fully Autonomous Agentic Attacks Are Three Months Away, Google Warns](https://www.infosecurity-magazine.com/news/fully-autonomous-agentic-attacks/)
- [Typosquatters Target New Brand Domains Within 24 Hours of Registration](https://www.infosecurity-magazine.com/news/typosquatters-target-new-brand/)
- [La Poste Subsidiary Maileva Breach Exposes 22 Million People](https://www.infosecurity-magazine.com/news/maileva-docaposte-22-million-breach/)
- [Google Project Zero to Cut Disclosure Deadline to 30 Days by 2028](https://www.infosecurity-magazine.com/news/project-zero-disclosure-deadline/)
- [FBI Highlights Growing Abuse of AI-Driven Pentesting Framework ARTEX](https://www.infosecurity-magazine.com/news/fbi-growing-abuse-ai-pentesting/)
- [Information Commissioner’s Office Receives 300+ Reports of Medical Snooping](https://www.infosecurity-magazine.com/news/ico-300-reports-of-medical-snooping/)
- [AI Cuts Vulnerability Discovery from Nine Months to 90 Hours](https://www.infosecurity-magazine.com/news/ai-cut-vulnerability-discover-nine/)

### CyberScoop
- [The Super Intelligence Task Force should open the door to defenders](https://cyberscoop.com/super-intelligence-task-force-cybersecurity-defenders-op-ed/)
- [Google says Russian-speaking hackers ran the first fully automated AI cyberattack](https://cyberscoop.com/google-fully-automated-ai-cyberattack/)
- [California sues OpenAI over AI agents’ summer hacking spree](https://cyberscoop.com/california-ag-rob-bonta-sues-openai/)
- [Commerce moves to place new restrictions on sale of AI chips abroad](https://cyberscoop.com/commerce-ai-chip-export-restrictions/)

### Cisco Talos
_No new items / feed unavailable this run._

### Unit 42 (Palo Alto)
- [QUIC and Covert: Novel HTTP/3-Powered RATs Target Southeast Asian Governments](https://unit42.paloaltonetworks.com/custom-rats-target-southeast-asia-governments/)

### Microsoft Security Blog
- [High volume phishing campaign uses Microsoft 365 outage lures to target multiple industry sectors](https://www.microsoft.com/en-us/security/blog/2026/11/16/high-volume-phishing-campaign-uses-microsoft-365-outage-lures-target-multiple-industry-sectors-2/)

### Google Cloud Threat Intel
- [GTIG AI Threat Tracker: Agentic Threat Activity Crosses a Significant Threshold](https://cloud.google.com/blog/topics/threat-intelligence/agentic-threat-activity-crosses-a-significant-threshold/)

### SANS Internet Storm Center
- [A phishing page interested in MX records, (Tue, Nov 17th)](https://isc.sans.edu/diary/rss/33526)
- [ISC Stormcast For Tuesday, November 17th, 2026 https://isc.sans.edu/podcastdetail/10182, (Tue, Nov 17th)](https://isc.sans.edu/diary/rss/33524)
- [Scans for LiteLLM/Starlette (CVE-2026-42271, CVE-2026-48710), (Mon, Nov 16th)](https://isc.sans.edu/diary/rss/33522)
- [ISC Stormcast For Monday, November 16th, 2026 https://isc.sans.edu/podcastdetail/10180, (Mon, Nov 16th)](https://isc.sans.edu/diary/rss/33520)

### Securelist (Kaspersky)
- [Operation ShadowCloud: cloud service–based backdoors targeting government networks in Asia and Africa. Part 2](https://securelist.com/operation-shadowcloud-graphdoor/122005/)
- [Operation ShadowCloud: cloud service–based backdoors targeting government networks in Asia and Africa. Part 1](https://securelist.com/operation-shadowcloud-gitdoor/122004/)
- [A USB worm’s second life: Retadup spreading CoffeeLoader](https://securelist.com/retadup-delivers-coffeeloader/121908/)

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
_No new items / feed unavailable this run._

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/
- https://sslbl.abuse.ch/blacklist/sslblacklist.csv -> HTTPSConnectionPool(host='sslbl.abuse.ch', port=443): Read timed out. (read timeout=25)

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal