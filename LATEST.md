# Winjit Daily TI Digest — 2026-10-25

_Auto-generated. Window: last ~24h. Fetched at 2026-10-25T08:14:36.210918+00:00Z_

**At a glance:** 0 new KEV · 15 new HIGH/CRITICAL CVEs · 25 new GitHub advisories · 20 new ransomware victims posted
_Note: CISA KEV, NVD, GitHub Advisories and ransomware.live are genuinely "new since yesterday." The IOC blocklists below (Spamhaus DROP, blocklist.de, CINS Army, IPsum, SSL Blacklist, Feodo Tracker) are current full-list snapshots from each provider, not day-over-day diffs -- expect a lot of overlap with yesterday's report there, that's expected, not a bug._

## CISA KEV — newly added actively-exploited CVEs
_No new KEV entries in this window._

## NVD — new HIGH/CRITICAL CVEs published
_Sorted by CVSS (highest first). EPSS = probability of real-world exploitation in the next 30 days (FIRST.org)._
| CVE | CVSS | EPSS | Description |
|---|---|---|---|
| CVE-2026-115806 | 9.8 | 0.8% | The Prime Mover – Backup and Migration plugin for WordPress is vulnerable to PHP Object Injection in all versions up to, and including, 2.2.1 via deserialization of untrusted input in the migration se |
| CVE-2026-115995 | 9.6 | n/a | A security vulnerability has been detected in Unitree Robotics Unitree Go2 up to 1.1.11.4. The impacted element is the function set_volume of the file gpt_thread.py of the component chat_go. Such mani |
| CVE-2026-110018 | 8.8 | n/a | The aBlocks – Gutenberg Blocks, User Dashboard Builder, Popup Builder, Form Builder & Animation Builder plugin for WordPress is vulnerable to Privilege Escalation in all versions up to, and including, |
| CVE-2026-116009 | 8.8 | n/a | Camaleon CMS before 2.9.3 contains a path traversal vulnerability that allows users with only the media permission to write arbitrary files by supplying ../ sequences in the name parameter. Attackers  |
| CVE-2026-116019 | 8.8 | n/a | Grav 2.0.15 before 2.2.13 contains an allowlist bypass vulnerability that allows page editors to invoke arbitrary public static methods by relocating data-*@ directives with unset-name@ or integer key |
| CVE-2026-116014 | 8.1 | n/a | open62541 1.5.0 before 1.5.7 contains an integer overflow in UA_DataType_fromStructureDescription() that wraps the 16-bit memSize field for large custom structure definitions. A malicious OPC UA serve |
| CVE-2026-116011 | 7.5 | n/a | Crow before 1.3.4 contains an uncontrolled recursion vulnerability in crow::json::load() that allows remote unauthenticated attackers to crash the server by sending deeply nested JSON. Attackers can s |
| CVE-2026-115969 | 7.3 | n/a | A flaw has been found in Travisun Opptrix 0.4.0. This affects an unknown function of the file /api/auth/setup of the component Schedule API. This manipulation causes command injection. It is possible  |
| CVE-2026-115970 | 7.3 | n/a | A vulnerability has been found in Travisun Opptrix 0.4.0. This impacts an unknown function of the file /api/system-update/import of the component Import Endpoint. Such manipulation leads to code injec |
| CVE-2026-115973 | 7.3 | n/a | A vulnerability was identified in FaveoSuite Faveo Helpdesk 2.0.3. Affected by this issue is the function ForgotPasswordController::sendResetLinkEmail/PasswordController::reset of the file app/Http/Co |
| CVE-2026-115999 | 7.3 | n/a | A vulnerability has been found in mansi-k Restaurant_IMS d7ad49f61ab7cc1ec6eb359ac2b5378bdbde0694. Affected is the function mysqli_connect of the file lsmodal.php. The manipulation of the argument log |
| CVE-2026-116000 | 7.3 | n/a | A security flaw has been discovered in Zylon PrivateGPT 1.0.0/1.0.1. This vulnerability affects the function load_file_from_uri of the file private_gpt/server/ingest/uri_loader.py of the component URI |
| CVE-2026-116006 | 7.3 | n/a | A vulnerability was detected in YunaiV/zhijiantianya ruoyi-vue-pro up to 2026.09. The affected element is an unknown function of the file AuthController.java of the component SMS Code Verification. Th |
| CVE-2026-115807 | 7.1 | 0.3% | The User Profile Builder – Beautiful User Registration Forms, User Profiles & User Role Editor plugin for WordPress is vulnerable to Limited Privilege Escalation in all versions up to, and including,  |
| CVE-2026-116016 | 7.1 | n/a | yudao-cloud through 2026.09 contains an authorization bypass vulnerability that allows authenticated users to evade row-level data scope restrictions by sending a data-permission-enable header set to  |

## GitHub Security Advisories — new since yesterday
| GHSA | CVE | Severity | Summary |
|---|---|---|---|
| GHSA-6wpw-wr63-qhp5 | CVE-2026-116044 | low | A security vulnerability has been detected in prasathmani TinyFileManager up to 2.6. Affected by... |
| GHSA-wxfh-552r-23f6 | CVE-2026-94295 | unknown | The Chikkili- Google Pay India for Woocommerce WordPress plugin through 1.0.6 does not verify... |
| GHSA-jgxg-6f9p-7gm5 | CVE-2026-114742 | unknown | The WPVR  WordPress plugin before 9.0.3 does not perform object-level ownership checks when... |
| GHSA-j9mp-rgph-hchj | CVE-2026-115251 | unknown | The Duplicator  WordPress plugin before 5.0.0 does not restrict its one-click upgrade routine to... |
| GHSA-q3pm-872x-6qfr | CVE-2026-115183 | unknown | The Qi Addons For Elementor WordPress plugin before 1.11.2 does not properly sanitise a widget's... |
| GHSA-7v79-ff47-vhhm | CVE-2026-111980 | unknown | The GiveWP  WordPress plugin before 4.19.0.1 does not correctly determine which page a page... |
| GHSA-529h-x3v3-53h3 | CVE-2026-116007 | low | A flaw has been found in YunaiV/zhijiantianya ruoyi-vue-pro up to 2026.09. The impacted element... |
| GHSA-w69v-pr8w-66wj | CVE-2026-114740 | unknown | The WPVR  WordPress plugin before 9.1.3 does not correctly check user capabilities when creating... |
| GHSA-f89g-x83g-732v | CVE-2026-111978 | unknown | The GiveWP  WordPress plugin before 4.19.0.1 does not properly validate a user-supplied filename... |
| GHSA-587v-fw9w-xc4m | CVE-2026-114743 | unknown | The InstaWP Connect  WordPress plugin before 0.1.4.2 does not perform a capability check on its... |
| GHSA-jwvr-26h4-vc23 | CVE-2026-116006 | medium | A vulnerability was detected in YunaiV/zhijiantianya ruoyi-vue-pro up to 2026.09. The affected... |
| GHSA-h3j8-jgx9-4qjv | CVE-2026-115214 | unknown | The Datawiza Proxy Auth Plugin  WordPress plugin before 1.1.1 does not verify that the user... |
| GHSA-vqjh-3q2x-jp9r | CVE-2026-114741 | unknown | The WPVR  WordPress plugin before 9.0.3 does not perform object-level authorization checks when... |
| GHSA-xm8r-m35h-qq8p | CVE-2026-111979 | unknown | The GiveWP  WordPress plugin before 4.19.0.1 does not properly sanitise and escape one of its... |
| GHSA-3f2v-jx9m-xwjg | CVE-2025-15705 | unknown | The Contact Form by Supsystic  WordPress plugin before 1.8.0 does not sanitise and escape a form... |
| GHSA-9x4v-8r28-fx8w | CVE-2026-111976 | unknown | The GiveWP  WordPress plugin before 4.19.0.1 does not perform any status or capability check when... |
| GHSA-vq2h-2cv6-5rpj | CVE-2026-110285 | unknown | The WP Stripe Checkout WordPress plugin before 1.2.2.62 does not verify the Stripe webhook... |
| GHSA-9wv6-rw6f-46c3 | CVE-2026-111981 | unknown | The GiveWP  WordPress plugin before 4.19.0.1 does not perform a capability check when handling... |
| GHSA-f3f8-mxmv-8237 | CVE-2026-116004 | low | A security vulnerability has been detected in onyx-dot-app Onyx up to 5.0.0. Impacted is an... |
| GHSA-5gf5-vm4r-r6j6 | CVE-2026-116000 | medium | A security flaw has been discovered in Zylon PrivateGPT 1.0.0/1.0.1. This vulnerability affects... |
| GHSA-mv73-9vhw-8f9j | CVE-2026-115999 | medium | A vulnerability has been found in mansi-k Restaurant_IMS d7ad49f61ab7cc1ec6eb359ac2b5378bdbde0694... |
| GHSA-76h3-gxx4-8m4v | CVE-2026-115997 | low | A flaw has been found in pig-mesh pig up to 4.1.0. This impacts the function orderItem.getColumn... |
| GHSA-8m4j-fcxh-6rjh | CVE-2026-89284 | unknown | Rejected reason: This CVE ID has been rejected or withdrawn by its CVE Numbering Authority. |
| GHSA-c3qh-x7xm-9m28 | CVE-2026-115996 | medium | A vulnerability was detected in Unitree Robotics Unitree Go2 up to 1.1.13/1.1.14.1/1.1.15.1. This... |
| GHSA-rxr5-3rww-rfv6 | CVE-2026-109111 | unknown | Rejected reason: This CVE ID has been rejected or withdrawn by its CVE Numbering Authority. |

## Ransomware — new leak-site victim postings (ransomware.live)
| Victim | Group | Country | Date |
|---|---|---|---|
| AB InBev | emperador | BE | 2026-10-25T03:22:10.246426+00:00 |
| Newcomer Cremations, Funerals & Receptions | anubis | US | 2026-10-25T00:31:56.643577+00:00 |
| Hisense | Whitearmor | CN | 2026-10-25T01:24:13.562658+00:00 |
| Castle Howard Estate | qilin | GB | 2026-10-24T16:34:49.360176+00:00 |
| Vins Viallet | lamashtu | FR | 2026-10-24T16:30:40.843615+00:00 |
| Frommann Energie GmbH | emperador | DE | 2026-10-24T14:52:41.604608+00:00 |
| Phoenix S&S GmbH | emperador | DE | 2026-10-24T14:53:32.619361+00:00 |
| SLTN Inter Access | qilin | NL | 2026-10-24T13:17:20.097554+00:00 |
| www.choicegoodwill.com | krybit | US | 2026-10-24T11:22:23.052278+00:00 |
| mainplace.com.my | krybit | MY | 2026-10-24T11:21:47.292156+00:00 |
| MODON Developments S.A.E | krybit | EG | 2026-10-24T11:21:10.713443+00:00 |
| www.zhservices.com | krybit |  | 2026-10-24T11:20:35.048020+00:00 |
| grupoeuro.com.mx | krybit | MX | 2026-10-24T11:19:59.229175+00:00 |
| www.optika.ca | krybit | CA | 2026-10-24T11:19:23.017695+00:00 |
| Texcar Inc. | N0n |  | 2026-10-24T09:55:07.404732+00:00 |
| GPIC Projectos Con Instalacoes Lda | N0n | PT | 2026-10-24T09:54:32.982729+00:00 |
| Asisken Asistencia Médica S.A. | N0n | AR | 2026-10-24T09:53:58.710021+00:00 |
| Adirondack Networks, Inc. | N0n | US | 2026-10-24T09:53:23.606425+00:00 |
| Arthritis Center of Riverside | N0n | US | 2026-10-24T09:52:48.628930+00:00 |
| Commonwealth Community Bank | qilin | US | 2026-10-24T03:30:27.396662+00:00 |

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
| 138.226.239.233 | 12 |
| 138.226.239.234 | 12 |
| 77.90.185.20 | 11 |
| 80.94.95.115 | 11 |
| 80.94.95.116 | 11 |
| 2.57.122.238 | 10 |
| 45.148.10.240 | 10 |
| 45.43.36.172 | 9 |
| 45.148.10.151 | 9 |
| 45.156.129.60 | 9 |
| 46.151.178.14 | 9 |
| 50.114.236.142 | 9 |
| 64.62.197.77 | 9 |
| 66.132.172.179 | 9 |
| 152.32.225.117 | 9 |
| 179.43.153.2 | 9 |
| 2.57.122.150 | 8 |
| 2.57.122.168 | 8 |
| 16.5.0.211 | 8 |
| 18.116.101.220 | 8 |

### OpenPhish (live phishing URLs)
- https://www.roblox.ly/users/2112515059/profile
- https://u.gy/QULKD9
- http://tokinix-cdn6-jh.xyz/
- https://checkforcopyrightinfringement.vercel.app/verify.html/
- http://tributosreceita.com/
- https://ukoa0.sunny68.net/
- http://blockbook-btc.sspwallet.io/
- http://www.shopee3989.blogspot.com/
- http://www.tevxorin-lak294816573.vercel.app/
- https://seguridad-2026b65782.netlify.app/
- http://wicksappsoauth.click/
- http://security-server--faifranhondyout.replit.app/
- https://www.caphaibuvoice.vercel.app/
- https://tokinix-cdn6-hk14.xyz/
- https://ilkevtoplu.com/giris.php
- https://hmade40f-del.github.io/ilnstagram/
- https://palmanojit07-cyber.github.io/Ui-clone/
- https://cpg47.ph23-ph.net/
- http://faiceboikonlineshoip.cc/
- https://page-ledger-cdn.typedream.app/en-us

### PhishStats (recent phishing/malicious URLs, scored)
| Score | URL |
|---|---|
| N/A | http://43.156.0.130/v3/signin/identifier?amp%3Bfollowup=https%3A%2F%2Faccounts.google.com%2F&amp%3Bifkv=AWnogHfrcMjMJOA5-x4JjU2A_H62FL5Ipip8qUn0FfsVqhu1vrUBPxBl4JpnqCjPGKNrTfaShVnNJQ&amp%3Bpassive=1209600&continue=https%3A%2F%2Faccounts.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin&ifkv=AWt06SS7uP3u5d4j-PoEuWSCoDLHidEqmIKtCuCxFR7L2AJFAqeqbGau3l4RZInL1to7enFv1cNe&dsh=S-751131183%3A1792915422109515 |
| N/A | https://away.vk.ru/away.php?rh=df6f5ea1-07e4-43e1-83e1-23acc3a139f3 |
| N/A | https://id.superhuman.com/signin?oauth_client_type=MEDIATED_WEB&correlation_id=IanQEkLrEiDlexve5MnHUQ&version=v4&client_id=superhumanDocs |
| N/A | https://skinsmonkey.com?referrer=pid%3D1%26af_tranid%3DMTQ5OTcyMTY5ODU3ODIxMzYzNTM%3D |
| N/A | https://away.vk.ru/away.php?rh=8bec162c-e7c2-447a-872f-3157fcd1bf24 |
| N/A | https://away.vk.ru/away.php?rh=2f8a3f25-61b4-4037-85d7-3427ab84b4ca |
| N/A | https://away.vk.ru/away.php?rh=3f8ccc2a-44c2-4dd2-9a80-adda123bc2e3 |
| N/A | https://away.vk.ru/away.php?rh=5a937666-0eea-4ef7-a95c-f62c513b8c9f |
| N/A | https://xml-v4.pushub.net/click?i=rKOS*LIRC24_0 |
| N/A | https://flat-bread-04ca.cloudflareaccess.com/cdn-cgi/access/login/vertiv-command-center.pages.dev?kid=617efb6eb0445e77d08421b7c2075c08ed7302463271c62a28d702c82772462a&meta=eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiIsImtpZCI6IjEyY2U5NjlmMDk3YjUyNjliNjllZjA0N2EwMjBiZGI2NGMwMTc5NjMwNzE3MzJhMWJjODg2NjJiNGUxYzJjY2IifQ.eyJ0eXBlIjoibWV0YSIsImF1ZCI6IjYxN2VmYjZlYjA0NDVlNzdkMDg0MjFiN2MyMDc1YzA4ZWQ3MzAyNDYzMjcxYzYyYTI4ZDcwMmM4Mjc3MjQ2MmEiLCJob3N0bmFtZSI6InZlcnRpdi1jb21tYW5kLWNlbnRlci5wYWdlcy5kZXYiLCJyZWRpcmVjdF91cmwiOiIvIiwic2VydmljZV90b2tlbl9zdGF0dXMiOmZhbHNlLCJpc193YXJwIjpmYWxzZSwiaXNfZ2F0ZXdheSI6ZmFsc2UsImV4cCI6MTc5MjkxNDM3OSwibmJmIjoxNzkyOTE0MDc5LCJpYXQiOjE3OTI5MTQwNzksImF1dGhfc3RhdHVzIjoiTk9ORSIsIm10bHNfYXV0aCI6eyJjZXJ0X2lzc3Vlcl9kbiI6IiIsImNlcnRfc2VyaWFsIjoiIiwiY2VydF9pc3N1ZXJfc2tpIjoiIiwiY2VydF9wcmVzZW50ZWQiOmZhbHNlLCJjb21tb25fbmFtZSI6IiIsImF1dGhfc3RhdHVzIjoiTk9ORSJ9LCJyZWFsX2NvdW50cnkiOiJVUyIsImFwcF9zZXNzaW9uX2hhc2giOiJmMmYwNzg1MGM2MjRhOTgwYWU4MmRhYjQ0NDkyZDU2M2RiZjJkOGVhMDExMzQxOTRhNTdlZTgwNDBjNzFkNjIzIn0.UeUw2mdVjmSzkKhvOh7WxUOxVYQQqJfqZWRu_qecqE7ZkctoTxfUzEQSvEJoPTYymVGjwBwuJ8yKum6qThUPC8S1KiWbAlHz-zfr6BiSabDMNuW0L7voBn41ckpXVHuKnZcbadTf02myV5d3zws8QyjQydQG6f_vxJUb9artcOzhxKF5pa-Kn_y1uke0FmbjVfsrGoEEir6WUzzHHnlybVoh_ESxknK3hC4HV1JTnK5ikk5NyeKvEWSLH3gHyQpB3WC5EOo8TovO0SkdlBmTbpsRq5wvBg08T6Fb54Fy-UpmJd6FHFBG4BAgGpEKu8AVnD5I5DIBgyssKyqmO79VXg&redirect_url=%2F |
| N/A | https://yandex.ru/showcaptcha?cc=1&form-fb-hint=2.1&mt=A0AA5A8EF8FCB89D8A0B3F38CF2B48FDC85853B8C5E698DA095FC7E0A41D156BC96225C04385B7CD0CD9A1E8309DED3D5BFF14896C1DC33F2EC216D35C492FE41A6E9B5EA5A2B4AFD962F82F78F7C8ECCE07276B346F5B98DAB67C515312F22C1C7F7BD050079CA7BF0B1427ECBFB569C90460F694C546F06018A45FA88F5244EEFB482CCFD7F94C31&retpath=aHR0cHM6Ly95YW5kZXgucnUvc2VhcmNoP3RleHQ9MjExNjg3MTc%2C_9e32ea590f1152ceb4677b92f96f1e0c&t=2%252F1792913580%252Ffb5a682e2e3b8b71e9391ca1363f482d&u=9639929171048935446&s=9b2043c3d9a13780844c20eeb1abd079 |
| 3 | http://away.vk.ru/away.php?rh=3355eb4c-9d59-4749-8af5-fd2cd43e6ca4 |
| 3 | http://allegro-lokalnie.smash860.sbs/ |
| N/A | https://away.vk.ru/away.php?rh=269c0338-3d09-4b86-b88a-1ea1eee25442 |
| N/A | https://away.vk.ru/away.php?rh=dabd8bf4-c145-4b74-aa68-9cf63457d1ea |
| N/A | https://away.vk.ru/away.php?rh=e0e3112b-9bcc-4bcf-97d8-5e73aaf80ab9 |
| N/A | https://xml-v4.pushub.net/click?i=JVSScasrrG4_0 |
| N/A | https://xml-v4.pushub.net/click?i=NaOmEzpB25Q_0 |
| N/A | https://vercel.com/login?next=%2Fsso-api%3Furl%3Dhttps%253A%252F%252Finterface-uniswap.vercel.app%252F%26nonce%3D54f3aed203748a4654e3d0324f23c6ceec016195376c2dc3791dd7f1f28907e6 |
| N/A | https://xml-v4.pushub.net/click?i=5hqwuXgwOy0_0 |

### SSL Blacklist (abuse.ch — certs tied to malware/botnet C2)
| SHA1 | Info |
|---|---|
| e22f91a1cca032454ef45d769cd9b3374283b2a2 | QuasarRAT C&C |
| cfac3216fbbc990e5c606fa5b6b513f2773df7ab | nullRAT C&C |
| 35661619ef7eb0f46354d9b8a6354a1115e338eb | Vidar C&C |
| f74cfb538bdbd89cd3fbfccd91e6530561d87310 | WARDENStealer C&C |
| f1943fdd37320ad09ea8985e9b86ae33aee4525d | RevStealer C&C |
| 842b7c6b2ac561e7155bfdae757689f50ff6c634 | NetSupport RAT malware distribution |
| 84abb61ca68f4b6b4a7f421516b188dae0516d0f | Vidar C&C |
| 49ee355c74a19712c68535feccf60156ff4055f3 | Vidar C&C |
| f8ac3547b3ec163234ebcb90d325eec86069a42f | Vidar C&C |
| 3c99c5d67f2afafad06b3da29af5d1ab97bf5273 | PureLogsStealer C&C |
| 4bba6041d3bd00dd1eb5d436f7d17c7e786eb5ee | PureLogsStealer C&C |
| e8e1ee53a4b01fe4d284f3edf82c0dfd5b6c63cf | CobaltStrike C&C |
| d0cbe76e7158ac0762ebaf34f37e8a357cdfb6b2 | OffLoader C&C |
| 3eba611997b2a74274fd3974dad68bd2d64a936d | Vidar C&C |
| 6f89137efd938f732c38a20125c58d0248016909 | Vidar C&C |
| fe097ea5a213100162ccf6811a78483695f0f8a5 | Vidar C&C |
| b5b9054786b6c3877c16c507e4589388e3f2d08c | Vidar C&C |
| 79928c5b3aaa3ea9d05750ba6b2af2aa6cbea154 | PureRAT C&C |
| 7a5cbff9325f0ca3de3f020b3ba02e51390807cf | Malware C&C |
| 7ed29169b508169575d0d26850aca8a93044067c | QuasarRAT C&C |

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
- 1.10.248.226
- 1.10.248.238
- 1.10.248.240
- 1.117.73.220
- 1.12.55.42
- 1.12.55.80
- 1.14.240.247
- 1.15.106.134
- 1.15.179.199
- 1.159.54.33
- 1.187.174.173
- 1.203.149.250
- 1.203.186.47
- 1.212.225.99
- 1.214.214.114
- 1.215.233.74
- 1.220.198.126
- 1.222.42.237
- 1.227.228.131
- 1.23.80.94

### CINS Army (poorly-rated IPs)
- 1.14.3.170
- 1.15.14.29
- 1.168.172.140
- 1.192.129.106
- 1.193.57.144
- 1.236.254.202
- 1.24.16.12
- 1.24.16.121
- 1.24.16.142
- 1.24.16.143
- 1.24.16.153
- 1.24.16.157
- 1.24.16.167
- 1.24.16.177
- 1.24.16.184
- 1.24.16.197
- 1.24.16.32
- 1.24.16.48
- 1.24.16.49
- 1.24.16.79

## News (last ~36h, across outlets)
### The Hacker News
- [OpenAI AI Agents Demonstrate VM Escapes and Secret Cross-Sandbox Communication](https://thehackernews.com/2026/10/openai-ai-agents-demonstrate-vm-escapes.html)
- [Brotli Decoder Flaw Behind Node.js RCE Also Affects Bun, Python and Other Widely Used Software](https://thehackernews.com/2026/10/brotli-decoder-flaw-behind-nodejs-rce.html)
- [Leaked LiteLLM Master Key Let Attackers Steal GitHub Tokens and Hijack Release Pipeline](https://thehackernews.com/2026/10/leaked-litellm-master-key-let-attackers.html)
- [Google Says Gmail and Photos Data Shared With AI Search Could Be Used for Targeted Ads](https://thehackernews.com/2026/10/google-says-gmail-and-photos-data.html)
- [Researchers Push Over 2 Million Updates to Remotely Disable Popcorn Time Updater That Could Fuel a Botnet](https://thehackernews.com/2026/10/researchers-push-over-2-million-updates.html)
- [CISA Flags Two Actively Exploited Critical Flaws in Collabora Online and Arista VeloCloud](https://thehackernews.com/2026/10/cisa-flags-two-actively-exploited.html)

### BleepingComputer
- [BlackX UEFI bootkit exploits Baton Drop flaw to bypass Secure Boot](https://www.bleepingcomputer.com/news/security/blackx-uefi-bootkit-exploits-baton-drop-flaw-to-bypass-secure-boot/)
- [Abandoned Popcorn Time app exposed millions of devices to RCE attacks](https://www.bleepingcomputer.com/news/security/abandoned-popcorn-time-app-exposed-millions-of-device-to-rce-attacks/)

### Krebs on Security
_No new items / feed unavailable this run._

### Dark Reading
- [Trust Is Not What It Seems — And Fraudsters Are Counting on It](https://www.darkreading.com/cyber-risk/trust-is-not-what-it-seems-and-fraudsters-are-counting-on-it)

### SecurityWeek
_No new items / feed unavailable this run._

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
- [Why Organizations Secure AI Agents with Falcon Guardian](https://www.crowdstrike.com/en-us/blog/why-organizations-secure-ai-agents-with-falcon-guardian/)
- [Obstacles to Weaponizing PHP2Shell Likely Constrain Immediate Widespread Exploitation](https://www.crowdstrike.com/en-us/blog/obstacles-to-weaponizing-php2shell-likely-constrain-exploitation/)
- [CrowdStrike Protects Customers from Threats Delivered via PHP2Shell](https://www.crowdstrike.com/en-us/blog/crowdstrike-protects-customers-from-php-rce-zero-days/)
- [CrowdStrike Uncovers New Agentic AI Campaigns](https://www.crowdstrike.com/en-us/blog/crowdstrike-uncovers-new-agentic-ai-campaigns/)
- [CrowdStrike Achieves NCSC CIR Enhanced Level Assurance](https://www.crowdstrike.com/en-us/blog/crowdstrike-achieves-uk-ncsc-cir-enhanced-level-assurance/)
- [U.S. Government Disrupts FAMOUS CHOLLIMA Operation with CrowdStrike Assistance](https://www.crowdstrike.com/en-us/blog/fbi-disrupts-famous-chollima-operation-with-crowdstrike-assistance/)
- [October 2026 Patch Tuesday: 1,413 CVEs Include Three Zero-Days and 75 Critical Vulnerabilities](https://www.crowdstrike.com/en-us/blog/patch-tuesday-analysis-october-2026/)
- [CrowdStrike and Anthropic Give Critical Infrastructure Defenders the AI Advantage](https://www.crowdstrike.com/en-us/blog/crowdstrike-anthropic-critical-infrastructure-defense-program/)
- [Solving the Continuous Authorization Conundrum](https://www.crowdstrike.com/en-us/blog/solving-the-continuous-authorization-conundrum/)
- [Unknown Threat Actor Uses AI-Driven ARTEX to Target South Korean Finance](https://www.crowdstrike.com/en-us/blog/unknown-threat-actor-uses-artex-to-target-south-korean-finance/)

### FortiGuard Threat Signal
- [OT Refrigeration Control Systems Attack](https://fortiguard.fortinet.com/threat-signal-report/6553)
- [Trimble Cityworks Remote Code Execution Attack](https://fortiguard.fortinet.com/threat-signal-report/5997)

## Fetch issues this run
- https://urlhaus.abuse.ch/downloads/csv_recent/ -> 410 Client Error: Gone for url: https://urlhaus.abuse.ch/downloads/csv_recent/
- https://threatfox.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://threatfox.abuse.ch/export/csv/recent/
- https://bazaar.abuse.ch/export/csv/recent/ -> 410 Client Error: Gone for url: https://bazaar.abuse.ch/export/csv/recent/

---
Sources: CISA KEV · NVD · GitHub Security Advisories · abuse.ch (URLhaus/ThreatFox/MalwareBazaar/Feodo Tracker/SSL Blacklist) · IPsum · Spamhaus DROP · blocklist.de · CINS Army · OpenPhish · PhishStats · ransomware.live · The Hacker News, BleepingComputer, Krebs on Security, Dark Reading, SecurityWeek, The Record, Infosecurity Magazine, CyberScoop, Cisco Talos, Unit 42 (Palo Alto), Microsoft Security Blog, Google Cloud Threat Intel, SANS Internet Storm Center, Securelist (Kaspersky), CrowdStrike Blog, FortiGuard Threat Signal