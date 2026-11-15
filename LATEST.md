# Winjit Daily TI Digest — 2026-11-15

_Auto-generated. Window: last ~24h. Fetched at 2026-11-15T10:34:30.469830+00:00Z_

**At a glance:** 0 new KEV · 27 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-129351 | 10.0 | n/a | A security vulnerability has been detected in TRENDnet TEW-657BRM 1.00.1. This vulnerability affects the function sprintf of the file /setup.cgi of the component mini_httpd. Such manipulation leads to |
| CVE-2026-129353 | 10.0 | n/a | A vulnerability was detected in D-Link DIR-600L 2.17/2.17b02. Affected by this vulnerability is the function authenticationcgi_main of the file authentication.cgi. Performing a manipulation of the arg |
| CVE-2026-129354 | 10.0 | n/a | A flaw has been found in D-Link DIR-600L 2.17b02. Affected by this issue is the function hnap_main of the file htdocs/cgibin of the component HNAP Handler. Executing a manipulation can lead to stack-b |
| CVE-2026-129444 | 10.0 | n/a | A vulnerability was identified in D-Link DSL-6740C 20131126. This affects an unknown function of the file /etc/templates/ftpd/ftpd_conf.php of the component FTP Daemon. Such manipulation leads to hard |
| CVE-2026-129250 | 9.9 | n/a | A security vulnerability has been detected in Edimax BR6478ACV2 1.23. The impacted element is the function formPPTPSetup of the file webs. The manipulation of the argument pptpUserName leads to buffer |
| CVE-2026-129433 | 9.9 | n/a | Dokploy before 0.31.1 contains an OS command injection vulnerability in getComposeContainerCommand() that allows authenticated organization members to execute shell commands via the serviceName parame |
| CVE-2026-126173 | 9.8 | 0.5% | The AutomatorWP Pro plugin for WordPress' webhook addon is vulnerable to authorization bypass in all versions up to, and including, 1.4.4. This is due to the plugin not properly verifying that a user  |
| CVE-2026-120522 | 9.8 | n/a | The Cloud Storage Manager for Fluent Forms – Google Drive, Dropbox, OneDrive, S3 Uploads plugin for WordPress is vulnerable to Arbitrary File Write in all versions up to, and including, 1.2.0. This is |
| CVE-2026-19907 | 9.8 | n/a | The Shipo plugin for WordPress is vulnerable to Authentication Bypass in versions 1.6 through 1.8.0. This is due to the `authenticate_rest_user()` function parsing the `LOGGED_IN_COOKIE` value and aut |
| CVE-2026-129258 | 9.1 | n/a | A vulnerability was identified in Tenda AC18 15.03.05.05_multi/15.03.05.19 Build 6318. Affected by this vulnerability is an unknown functionality of the file /cgi-bin/upgrade of the component Firmware |
| CVE-2026-129352 | 9.1 | n/a | A vulnerability was detected in TRENDnet TEW-657BRM 1.00.1. This issue affects some unknown processing of the file /usr/sbin/upgrade_flash.cgi. Performing a manipulation of the argument boundary resul |
| CVE-2026-129255 | 8.8 | n/a | A vulnerability was identified in CoolerMaster MASTERPLUS+ 1.9.6. This affects the function sub_11504 in the library WinRing0x64.sys of the component Device Driver. The manipulation of the argument Ph |
| CVE-2026-18053 | 8.8 | n/a | The MemberDash plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, 1.8.7. This is due to a mass-assignment vulnerability in the `user_account_manager()` fu |
| CVE-2026-129464 | 8.8 | n/a | Zr.Admin.NET commit 0ee1ab8 through commit eb9228a contains a path traversal vulnerability that allows any logged-in user to read arbitrary server files via the path parameter of /common/DownloadFile. |
| CVE-2026-129465 | 8.8 | n/a | Zr.Admin.NET commit af07ffc through commit eb9228a contains an insecure direct object reference vulnerability in SysProfileController.UpdateProfile that allows any authenticated user to modify other a |
| CVE-2026-129261 | 8.2 | n/a | A vulnerability was found in Kingston FURY CTRL RGB Control Software up to 2.0.66.0. The impacted element is an unknown function in the library NTIOLib_X64.sys of the component IOCTL Handler. Performi |
| CVE-2026-129445 | 8.2 | n/a | A security flaw has been discovered in D-Link DIR-850L FW1.20WWb03. This impacts an unknown function of the file /usr/sbin/consolepwd of the component Console Login. Performing a manipulation results  |
| CVE-2026-82568 | 7.5 | n/a | The Give - Peer-to-Peer plugin for WordPress is vulnerable to time-based SQL Injection via the 'sort' parameter in all versions up to, and including, 2.9.3 due to insufficient escaping on the user sup |
| CVE-2026-82663 | 7.5 | n/a | The Give - Peer-to-Peer plugin for WordPress is vulnerable to authorization bypass in all versions up to, and including, 2.9.5. This is due to the plugin not properly verifying that a user is authoriz |
| CVE-2026-129181 | 7.3 | 0.3% | A vulnerability has been found in projectworlds Visitor Management System 1.0. This issue affects the function mysqli_query of the file /img/user%20page.php of the component Login Endpoint. Such manip |
| CVE-2026-129262 | 7.3 | n/a | A weakness has been identified in Wuxi Wubang Security Software Wubang Five-in-One Safety Production Management Information System up to 3.5. Affected by this vulnerability is the function DiyFileUplo |
| CVE-2026-129359 | 7.3 | n/a | A security flaw has been discovered in Linux Foundation Magma up to 1.9.0. The affected element is an unknown function of the file orc8r/lib/go/registry/interceptors.go. Performing a manipulation resu |
| CVE-2026-129360 | 7.3 | n/a | A weakness has been identified in Linux Foundation Magma up to 1.9.0. The impacted element is an unknown function of the file orc8r/cloud/go/services/obsidian/access/operator.go of the component Obsid |
| CVE-2026-116753 | 7.2 | n/a | The Multi Step for Contact Form 7 plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'multipart field name (array key)' parameter in all versions up to, and including, 2.9.1 due |
| CVE-2026-120687 | 7.2 | n/a | The Lightbox & Modal Popup WordPress Plugin – FooBox plugin for WordPress is vulnerable to Stored DOM-Based Cross-Site Scripting via the 'img alt attribute inside .wp-caption container' parameter in a |
| CVE-2026-124969 | 7.1 | 0.5% | The Optimole – Optimize Images | Convert WebP & AVIF | CDN & Lazy Load | Image Optimization plugin for WordPress is vulnerable to arbitrary file deletion due to insufficient file path validation in th |
| CVE-2026-129429 | 7.1 | n/a | Frappe india-payroll before 16.0.4 contains a missing authorization vulnerability in the get_employee_details, compute_tax_comparison and set_tax_regime methods of tax_regime_selector.py that allows a |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-32m9-2655-w25q | CVE-2026-129444 | critical | A vulnerability was identified in D-Link DSL-6740C 20131126. This affects an unknown function of... |
| GHSA-6hhx-4f46-wj7q | CVE-2026-129443 | low | A vulnerability was determined in itsourcecode Airline Reservation System 1.0. The impacted... |
| GHSA-m4vj-2mv4-rv7p | CVE-2026-127048 | unknown | The Custom Block Builder  WordPress plugin before 3.0.0 does not properly deny unauthorised... |
| GHSA-8pgw-crm2-c68x | CVE-2026-110989 | unknown | The RegistrationMagic  WordPress plugin before 6.1.0.4 does not verify ownership of the submitted... |
| GHSA-594q-h3jv-fr98 | CVE-2026-114451 | unknown | The Membership Plugin  WordPress plugin before 4.0.6 does not perform any authorization or CSRF... |
| GHSA-pmrh-j9jh-j5h7 | CVE-2026-124673 | unknown | The Burst Statistics  WordPress plugin before 3.7.5 does not check that a reported page view... |
| GHSA-8h6p-5wvr-4vr5 | CVE-2026-124671 | unknown | The Burst Statistics  WordPress plugin before 3.7.5 does not enforce a shared report's date range... |
| GHSA-vf5v-xr3h-9x33 | CVE-2026-110987 | unknown | The RegistrationMagic  WordPress plugin before 6.1.0.4 does not properly escape a user-supplied... |
| GHSA-2qcj-76wq-79hr | CVE-2026-103361 | unknown | The Payment Gateway via Valitor for WooCommerce WordPress plugin before 1.9.41 does not properly... |
| GHSA-x3jr-gfj8-g3w8 | CVE-2026-110984 | unknown | The RegistrationMagic  WordPress plugin before 6.1.0.4 does not sanitise and escape a parameter... |
| GHSA-g6c9-6jpv-h859 | CVE-2026-114452 | unknown | The Membership Plugin  WordPress plugin before 4.0.6 does not verify that the membership... |
| GHSA-ggh8-f4wg-vh5g | CVE-2026-116559 | unknown | The A2Reviews WordPress plugin through 1.2.3 does not properly verify authorization on several of... |
| GHSA-vc6r-34rj-x38v | CVE-2026-110960 | unknown | The Auth Armor  WordPress plugin through 1.0.3 does not require authentication on several... |
| GHSA-9hr5-354j-2g3g | CVE-2026-129360 | medium | A weakness has been identified in Linux Foundation Magma up to 1.9.0. The impacted element is an... |
| GHSA-vw3f-m846-9r2c | CVE-2026-129359 | medium | A security flaw has been discovered in Linux Foundation Magma up to 1.9.0. The affected element... |
| GHSA-cw9p-3fjg-gh3r | CVE-2026-129358 | low | A vulnerability was identified in Linux Foundation Magma up to 1.9.0. Impacted is the function... |
| GHSA-6w37-qc84-g44h | CVE-2026-129466 | medium | Zr.Admin.NET commit 1845017 through commit eb9228a contains a missing authorization vulnerability... |
| GHSA-h8cq-rcm7-x963 | CVE-2026-129454 | high | Zr.Admin.NET commit 85cff6a through commit eb9228a contains an insecure direct object reference... |
| GHSA-x62g-47x5-v7vf | CVE-2026-129464 | high | Zr.Admin.NET commit 0ee1ab8 through commit eb9228a contains a path traversal vulnerability that... |
| GHSA-rhw4-mxv2-6w6q | CVE-2026-129455 | medium | Zr.Admin.NET commit e6ceaf4 through commit eb9228a contains an insecure direct object reference... |
| GHSA-jmr5-r26m-3fmv | CVE-2026-129357 | low | A vulnerability was determined in Linux Foundation Magma up to 1.9.0. This issue affects the... |
| GHSA-jwq2-9qvc-8p98 | CVE-2026-129465 | high | Zr.Admin.NET commit af07ffc through commit eb9228a contains an insecure direct object reference... |
| GHSA-3vw8-v548-fw83 | CVE-2026-129355 | medium | A vulnerability has been found in sigoden dufs up to 0.46.0. This affects an unknown part of the... |
| GHSA-fj8v-85jv-jwpv | CVE-2026-129356 | low | A vulnerability was found in vllm-project vllm 0.30.0/0.31.0. This vulnerability affects unknown... |
| GHSA-j69h-pwm6-99pr | CVE-2026-129354 | critical | A flaw has been found in D-Link DIR-600L 2.17b02. Affected by this issue is the function... |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| FINSA | Barracuda | ES | 2026-11-14T17:50:40.941619+00:00 |
| F***** G****** C********** C*** | netrunner | US | 2026-11-14T17:27:01.418558+00:00 |
| Momentum Telecom | EndZone |  | 2026-11-14T12:25:18.758864+00:00 |
| Absolute Bail Bonds | EndZone | US | 2026-11-14T12:24:57.389262+00:00 |
| fittleworth.com | Scarlettgroup | GB | 2026-11-14T18:16:18.167053+00:00 |
| I****** A***** | netrunner | KW | 2026-11-14T01:30:50.924965+00:00 |
| Grundbaulabor Trier GmbH | everest | DE | 2026-11-14T03:32:50.190997+00:00 |
| Kayaku Safety Systems Malaysia Sdn Bhd | qilin | MY | 2026-11-14T21:36:07.809711+00:00 |
| K&A Industries | interlock | US | 2026-11-13T22:46:01.680491+00:00 |
| Final Notice Before Publication | everest |  | 2026-11-13T22:44:12.215915+00:00 |
| i*t*r***t.com | Curious Worm |  | 2026-11-13T20:53:46.961552+00:00 |
| t**a.com | Curious Worm |  | 2026-11-13T20:53:27.907368+00:00 |
| Frey Properties of Highland LLC | play | US | 2026-11-13T20:29:46.224571+00:00 |
| ARRB Group | play | AU | 2026-11-13T20:29:10.769450+00:00 |
| The Tidewater Inn | Aoqin | US | 2026-11-13T18:21:30.277020+00:00 |
| Advantage Archives | incransom | US | 2026-11-13T20:14:47.003693+00:00 |
| Walgreen Co. | Wallstreet | US | 2026-11-13T19:03:11.758241+00:00 |
| RE/MAX Germany | Panzer | DE | 2026-11-13T21:51:51.251717+00:00 |
| sportsmansguide.com | incransom | US | 2026-11-13T20:14:27.769657+00:00 |
| World Wide Fittings | bravox | US | 2026-11-13T14:21:52.700230+00:00 |

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
| 45.148.10.141 | 11 |
| 138.226.239.233 | 11 |
| 45.148.10.151 | 10 |
| 45.148.10.152 | 10 |
| 45.148.10.157 | 10 |
| 138.226.239.234 | 10 |
| 18.218.118.203 | 9 |
| 66.132.172.183 | 9 |
| 125.130.102.172 | 9 |
| 199.165.159.9 | 9 |
| 2.57.122.209 | 8 |
| 3.129.187.38 | 8 |
| 18.116.101.220 | 8 |
| 35.210.19.110 | 8 |
| 35.210.198.246 | 8 |
| 64.62.197.2 | 8 |
| 64.62.197.32 | 8 |
| 66.132.172.45 | 8 |
| 66.132.172.136 | 8 |
| 66.132.172.142 | 8 |

### OpenPhish (live phishing URLs)
- https://kuconlgzn.gitbook.io/us
- https://kuconlogen16.gitbook.io/
- http://akshitofficials.github.io/Spotify-clone
- https://www.jah-delta.vercel.app/
- http://www.shopee-002.blogspot.com/
- http://all4youherebux.blogspot.com/
- https://thr-shopee227.blogspot.com/
- http://shopee-inc2023.blogspot.com/
- https://www.fxvfvbbvff.blogspot.com/
- http://fxvfvbbvff.blogspot.com/
- https://apple.absalomdonald.dpdns.org/
- https://shopee7677.blogspot.com/
- http://www.shopee7677.blogspot.com/
- http://netflixaccount119.blogspot.com/
- https://m.coinbase-svip.com/h5/
- http://bradsaidso.com/wp-includes/indcx.html
- https://ebay-phone-number.blogspot.com/
- https://www.ebay-phone-number.blogspot.com/
- http://xfinifydattabasemeasureuxux.weebly.com/
- https://www.roblox.com.et/users/4925259156/profile

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | https://away.vk.ru/away.php?rh=b6e91902-9bb2-4a0f-8792-b2f1dbcee143 |
| N/A | https://isonic.weebly.com/ |
| N/A | https://www.jardinpourvous.com/ |
| N/A | https://madetomentor.com/ |
| N/A | https://mgxd.weebly.com/ |
| N/A | https://away.vk.ru/away.php?rh=8b6eb21f-7907-46fa-9002-e6525142ff89 |
| N/A | http://43.156.0.130/v3/signin/identifier?amp;continue=https://accounts.google.com/&amp;followup=https://accounts.google.com&passive=1209600&flowName=GlifWebSignIn&flowEntry=ServiceLogin&dsh=S790913859:1794737857708719 |
| N/A | https://zimbramailmyyacccessvoicemail.weebly.com/ |
| N/A | https://tra.com/fresh-start-signup2?_ef_transaction_id=ed520d6f8f524466ba928857cc8cb528&source_id=&affid=5&sub1=8f50da5a0efc4ad9ba06c81e65d00474&sub2=427035&sub3=Taxuy311&sub4=&sub5=&oid=44 |
| N/A | https://3223-664.weebly.com/ |
| N/A | https://yandex.ru/showcaptcha?cc=1&form-fb-hint=2.1.9820a91292fa024952739f43fe8ba54490993d4a97421eea8925d7f0c09812e22274f6bd1d7760e478b7f408a374c9c475b0d55845186c1af74423a696babfb3d5eaa25f5e2c2e84&mt=6308D4B34596D34E7EC984C79B4208887819B0776B44DEECD40A14E568B39506BBBD5FB6DE592DE02A8BFEC6E5B588AC1CAE1DC45F257CADB98E8F89B7ACA08F699EC261588C3166464F6CBB5B5C9ACB0999BDA2C3744D31462F4106BBA5F4113F3565B0DDF03258B51D716A33597AC65C38F9A86AFB34A39543419F6C4476CF8E763BC6EA644691BB947FE0A3F7493328FDF61458C71962259A50AB9E9690444715D5F004B3C7&retpath=aHR0cHM6Ly95YW5kZXgucnUvc2VhcmNoP3RleHQ9MjExNjg3MTc%2C_7b10da088091b864adaf1560824ca7aa&t=2%252F1794737251%252F60a41d47bdbd29f31007b2f3cf99b5a8&u=9762313675598917051&s=346825182a77cd821f3cb6249bb40a4b |
| N/A | https://away.vk.ru/away.php?rh=8a72529e-235b-430e-9265-48262e4efebc |
| N/A | https://away.vk.ru/away.php?rh=79df738e-a1e7-40da-9d9a-27eb27b928db |
| N/A | https://77373734.weebly.com/ |
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AQMjQ7TPKu6R4w93VRXMPKeD3zeOl4EoNrOdcsDBPMv7m30JK47iKcBvHB2Y608BaGxX8bX4kwt6sA&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBgleN2n6QLx1aY9E-M9OY60ZYwV2rbSc_-VtYfTzZEK86EG2ySpqDvtgDbJIJC6up1sLD8Xyk&dsh=S-267233633%3A1794730387082113 |
| N/A | https://away.vk.ru/away.php?rh=06560728-6c0c-4c65-8f80-bf952971d0e2 |
| N/A | https://away.vk.ru/away.php?rh=bc0332ab-64b0-4fdf-a91d-e7cedb351663 |
| N/A | https://away.vk.ru/away.php?rh=47e963b1-569b-4544-a52a-6f63f738c41c |
| N/A | https://id.superhuman.com/signin?oauth_client_type=MEDIATED_WEB&correlation_id=B05g8N5BoWD9ujAybK5fGA&version=v4&client_id=superhumanDocs |
| 5.3 | http://43.156.0.130/v3/signin/identifier?amp%3Bffgf=1&amp%3Bfollowup=https%3A%2F%2Faccounts.google.com&amp%3Bifkv=Af_xneGpinflONH_c3iB5WwVV1C6BSPwAwpudWnjxe8BcKRMcZLFgAnlzpjtHVk0QMFIUm6AcMYv&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AdVBglfprGQbpK2f3i12ypcDUfG3FMsPTs5T0eE-xyEf1H3_tZydvt-lFBvGpWGrP4ytRYUzBsd0ew&dsh=S1829429744%3A1794728819728156 |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| cbe8f557e3190083e91514273c218917ec46534a | Vidar C&C |
| 02d3e8f5f12d2b94432870d2c5a07e819001b6f3 | Vidar C&C |
| e0df07e0a7e6dc641bca1a7f24403a0f2ef6996f | RemusStealer C&C |
| c8e6fc7bb95a5fe2122679cfca61f87c7ce2875a | NativeLoader C&C |
| 0d04a50138c74a1ecfa1a7b4a3afddeb2a4be571 | QuasarRAT C&C |
| d43053e6c4c7f1b6d00e860b690cdf1b964e1afa | WARDENStealer C&C |
| 0038c1179510d131864264eb4a4a6648e8c54425 | Vidar C&C |
| c18c0c3de038ac37fee18f385a8396789ffe7867 | FunStealer C&C |
| 6627379996ae380572b3d2893ff2f2f377def6ec | FunStealer C&C |
| 262c1f81aee686adb3f6fc3a17951096265bf1b0 | FunStealer C&C |
| 9c24fe0ff6b7d2e3cd6fba2446f7ba0e4d18b737 | FunStealer C&C |
| 0799f487e606540102c11948be32f12439eee1ec | FunStealer C&C |
| 9d0751a9eab469ff9a399a086ea2531b3c22dc30 | OffLoader C&C |
| 955d88cd421ad19859f6015a6ba3ea81e07b510c | PureLogsStealer C&C |
| 45972ca5b00612d1f51e51325f7662d60cdd7860 | WARDENStealer C&C |
| adc24b6b9445798ed026d417fe423b72aa290ebc | WARDENStealer C&C |
| 041028a7248ce181b5c083d17d31ef9443364b70 | WARDENStealer C&C |
| 0335d3d009c55ea6f49e57aeb54fbdb84e5def8e | FunStealer C&C |
| d313c92a2c0c535a7b60359f758b0032db60b99b | FunStealer C&C |
| 187d60de02b8184158547240aec75f31b8e93a27 | Vidar C&C |

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
- 1.14.140.218
- 1.162.194.101
- 1.172.102.101
- 1.194.211.36
- 1.2.252.192
- 1.20.178.157
- 1.209.148.143
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.22.175.131
- 1.222.42.237
- 1.234.27.159
- 1.234.53.65
- 1.234.80.94
- 1.235.183.146
- 1.238.106.229
- 1.247.245.61
- 1.250.67.114

### CINS Army (poorly-rated IPs)
- 1.12.229.231
- 1.15.14.29
- 1.168.185.245
- 1.177.162.2
- 1.189.248.116
- 1.189.80.64
- 1.192.129.106
- 1.192.216.192
- 1.193.102.128
- 1.193.63.103
- 1.193.63.13
- 1.193.63.143
- 1.193.63.198
- 1.20.151.114
- 1.213.214.233
- 1.224.163.125
- 1.24.16.101
- 1.24.16.108
- 1.24.16.11
- 1.24.16.111

## News (last ~36h, across outlets)
### The Hacker News
- [Cursor Says Stolen Fireworks AI Key Led to Trojanized Claude Code Extension Incident](https://thehackernews.com/2026/11/stolen-fireworks-ai-key-led-to-cursor.html)
- [Attackers Exploit UnrealIRCd Flaw That Enables Server-Level Command Injection](https://thehackernews.com/2026/11/attackers-exploit-unrealircd-flaw-that.html)

### BleepingComputer
- [Cursor confirms security breach led to malicious Claude Code extension](https://www.bleepingcomputer.com/news/security/cursor-confirms-security-breach-led-to-malicious-claude-code-extension/)
- [US disrupts North Korean campaign behind $400 million crypto theft](https://www.bleepingcomputer.com/news/security/us-disrupts-north-korean-campaign-behind-400-million-crypto-theft/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
_No new items / feed unavailable this run._

### SecurityWeek
- [Is AI Making Us Worse at Cybersecurity?](https://www.securityweek.com/is-ai-making-us-worse-at-cybersecurity/)
- [Apple Reveals How Secure Exclaves Shield Camera and Microphone Data](https://www.securityweek.com/apple-reveals-how-secure-exclaves-shield-camera-and-microphone-data/)
- [No Signs of Hacking in FAA Ground Stop as FBI Reportedly Probes Software Update](https://www.securityweek.com/no-signs-of-hacking-in-faa-ground-stop-as-fbi-reportedly-probes-software-update/)

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
_No new items / feed unavailable this run._

### Google Cloud Threat Intel
_No new items / feed unavailable this run._

### SANS Internet Storm Center
_No new items / feed unavailable this run._

### Securelist (Kaspersky)
_No new items / feed unavailable this run._

### CrowdStrike Blog
- [Inside Falcon AI Gateway: One Control Point for AI Traffic](https://www.crowdstrike.com/en-us/blog/falcon-ai-gateway-one-control-point-for-ai-traffic/)
- [CrowdStrike Named a Leader in the 2026 IDC MarketScape for Worldwide Augmented Identity Security Solutions](https://www.crowdstrike.com/en-us/blog/crowdstrike-named-leader-2026-idc-marketscape-worldwide-augmented-identity-security-solutions/)
- [November 2026 Patch Tuesday: 1,252 CVEs Include One Zero-Day and 68 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-november-2026/)
- [How Adversaries Are Turning the Vulnerability Ecosystem Against Defenders](https://www.crowdstrike.com/en-us/blog/adversaries-turn-vulnerability-ecosystem-against-defenders/)
- [CrowdStrike Extends the Agentic SOC to Detect and Stop Agent Insider Threats](https://www.crowdstrike.com/en-us/blog/crowdstrike-detects-and-stops-agent-insider-threats/)
- [CrowdStrike Introduces Agentic Adversary Emulation to Counter AI-Enabled Adversaries](https://www.crowdstrike.com/en-us/blog/crowdstrike-agentic-adversary-emulation-counters-ai-enabled-adversaries/)
- [New Falcon Cloud Security Innovations Secure the Cloud AI Runs On](https://www.crowdstrike.com/en-us/blog/falcon-cloud-security-innovations-secure-cloud-ai-runs-on/)
- [CrowdStrike Brings Enterprise Browser Security to the Falcon Platform](https://www.crowdstrike.com/en-us/blog/crowdstrike-brings-enterprise-browser-security-to-falcon-platform/)
- [CrowdStrike Advances AI Security and Safety from Endpoint to Cloud](https://www.crowdstrike.com/en-us/blog/crowdstrike-advances-ai-security-and-safety-falcon-guardian/)
- [CrowdStrike to Acquire Fiddler to Deliver Falcon Observe for AI Agent Observability](https://www.crowdstrike.com/en-us/blog/crowdstrike-to-acquire-fiddler/)

### FortiGuard Threat Signal
_No new items / feed unavailable this run._

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal