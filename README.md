# Valentin Lobstein

**Security Researcher & Exploit Developer @ [VulnCheck](https://vulncheck.com)** ([@vlobstein-vc](https://github.com/vlobstein-vc))

[Blog](https://chocapikk.com) · [Twitter](https://twitter.com/Chocapikk_) · [LinkedIn](https://www.linkedin.com/in/valentin-l1337/) · [Ko-fi](https://ko-fi.com/Chocapikk)

---

### Highlights

- **CVE-2026-53805** - NVIDIA SIL GEN3C: unauthenticated RCE via Python pickle deserialization in the inference API ([VulnCheck](https://www.vulncheck.com/advisories/nvidia-sil-gen3c-unauthenticated-rce-via-pickle-deserialization-in-inference-api))
- **CVE-2026-29514** - NetBox: low-priv RCE via Jinja2 SandboxedEnvironment bypass through ExportTemplate `environment_params` ([writeup](https://chocapikk.com/posts/2026/netbox-export-template-rce/) · [PR](https://github.com/netbox-community/netbox/pull/22078))
- **CVE-2026-29059** - Windfall: unauth RCE in Windmill & Nextcloud Flow via path traversal + credential leak + PostgreSQL heap dump + Nextcloud AppAPI takeover - **Referenced by CERT-FR & BSI** ([writeup](https://chocapikk.com/posts/2026/windfall-nextcloud-flow-windmill-rce/) · [toolkit](https://github.com/Chocapikk/Windfall) · [CERT-FR](https://www.cert.ssi.gouv.fr/avis/CERTFR-2026-AVI-0244/) · [BSI](https://wid.cert-bund.de/portal/wid/securityadvisory?name=WID-SEC-2026-0502))
- **CVE-2026-39912** - Unauth account takeover in Xboard & V2Board via magic link token leak (7000+ instances) ([writeup](https://chocapikk.com/posts/2026/xboard-v2board-account-takeover/) · [exploit](https://github.com/Chocapikk/CVE-2026-39912))
- **CVE-2026-28515 to 28517** - 3 chained vulns in openDCIM: missing auth + SQLi + command injection = unauth RCE - **CVE-2026-28515 & 28517 added to VulnCheck KEV (exploited in the wild)** ([writeup](https://chocapikk.com/posts/2026/opendcim-sqli-to-rce/))
- **CVE-2026-27760** - OpenCATS: unauthenticated RCE via PHP code injection in the installer AJAX endpoint - **Added to VulnCheck KEV (exploited in the wild)** ([writeup](https://chocapikk.com/posts/2026/opencats-installer-rce/) · [VulnCheck](https://www.vulncheck.com/advisories/opencats-php-code-injection-via-installer-ajax-endpoint))
- **CVE-2026-27174 to 27181** - 8 vulns in MajorDoMo: 3 critical RCE, SQLi, 3 XSS ([writeup](https://chocapikk.com/posts/2026/majordomo-revisited/))
- **CVE-2025-2611** - ICTBroadcast unauth RCE via cookie injection - **Added to VulnCheck KEV** ([writeup](https://github.com/Chocapikk/CVE-2025-2611) · [KEV](https://www.vulncheck.com/blog/ictbroadcast-kev))
- **CVE-2025-34147 to 34152** - 6 unauth command injections in Aitemi M300 WiFi Repeater - **Referenced by CERT-FR** ([writeup](https://chocapikk.com/posts/2025/when-a-wifi-name-gives-you-root/) · [CERT-FR](https://www.cert.ssi.gouv.fr/actualite/CERTFR-2025-ACT-052/))
- **CVE-2024-22899 to 22903** - Exploit chain in Vinchin Backup & Recovery ([exploit](https://github.com/Chocapikk/CVE-2024-22899-to-22903-ExploitChain))

<details>
<summary><b>All CVEs</b></summary>

| CVE | Description | Links |
|-----|-------------|-------|
| CVE-2026-28496 | FOSSBilling: SSTI → RCE via getDi() DI container (PDO access) in unsandboxed Twig rendering | [Advisory](https://github.com/FOSSBilling/FOSSBilling/security/advisories/GHSA-57mv-jm88-66jc) |
| CVE-2026-53805 | NVIDIA SIL GEN3C: unauth RCE via pickle.loads() deserialization in inference API | [VulnCheck](https://www.vulncheck.com/advisories/nvidia-sil-gen3c-unauthenticated-rce-via-pickle-deserialization-in-inference-api) |
| CVE-2026-29514 | NetBox: low-priv RCE via Jinja2 SandboxedEnvironment bypass in ExportTemplate | [Blog](https://chocapikk.com/posts/2026/netbox-export-template-rce/) · [PR](https://github.com/netbox-community/netbox/pull/22078) |
| CVE-2026-29059 | Windfall: unauth path traversal + file read in Windmill & Nextcloud Flow - **CERT-FR** | [Blog](https://chocapikk.com/posts/2026/windfall-nextcloud-flow-windmill-rce/) · [Toolkit](https://github.com/Chocapikk/Windfall) · [CERT-FR](https://www.cert.ssi.gouv.fr/avis/CERTFR-2026-AVI-0244/) |
| CVE-2026-23696 | Windmill SQLi in folder management → JWT secret leak → token forge → RCE | [Blog](https://chocapikk.com/posts/2026/windfall-nextcloud-flow-windmill-rce/) |
| CVE-2026-22683 | Windmill operator role bypass: operators can create/execute scripts despite documentation | [Blog](https://chocapikk.com/posts/2026/windfall-nextcloud-flow-windmill-rce/) |
| CVE-2026-39912 | Unauth account takeover in Xboard & V2Board | [Blog](https://chocapikk.com/posts/2026/xboard-v2board-account-takeover/) · [Exploit](https://github.com/Chocapikk/CVE-2026-39912) |
| CVE-2026-28515 to CVE-2026-28517 | 3 chained vulns in openDCIM: unauth RCE on Docker - **28515 & 28517 on VulnCheck KEV** | [Blog](https://chocapikk.com/posts/2026/opendcim-sqli-to-rce/) · [Exploit](https://github.com/Chocapikk/opendcim-exploit) |
| CVE-2026-27760 | PHP code injection in OpenCATS installer AJAX endpoint - **VulnCheck KEV** | [Blog](https://chocapikk.com/posts/2026/opencats-installer-rce/) · [VulnCheck](https://www.vulncheck.com/advisories/opencats-php-code-injection-via-installer-ajax-endpoint) |
| CVE-2026-27743 to CVE-2026-27747 | 5 vulns in SPIP plugins: 2 SQLi, 2 RCE, 1 XSS | [Blog](https://chocapikk.com/posts/2026/spip-plugins-vulnerabilities/) |
| CVE-2026-27174 to CVE-2026-27181 | 8 vulns in MajorDoMo: 3 RCE, SQLi, 3 XSS | [Blog](https://chocapikk.com/posts/2026/majordomo-revisited/) |
| CVE-2026-25874 | Unauth RCE via Pickle in HuggingFace LeRobot (21.5k stars) | [Blog](https://chocapikk.com/posts/2026/lerobot-pickle-rce/) |
| CVE-2026-25873 | Unauth RCE via Pickle in OmniGen2 reward server | [Blog](https://chocapikk.com/posts/2026/omnigen2-pickle-rce/) |
| CVE-2026-29023 | Hard-coded API key in Keygraph Shannon router | [Blog](https://chocapikk.com/posts/2026/gen3c-pickle-rce/) |
| CVE-2026-26210 | Unauth RCE via Pickle in KTransformers (16.5k stars) | [Blog](https://chocapikk.com/posts/2026/ktransformers-pickle-rce/) · [Fix PR](https://github.com/kvcache-ai/ktransformers/pull/1944) |
| CVE-2026-26220 | Unauth RCE via Pickle in LightLLM | [Blog](https://chocapikk.com/posts/2026/lightllm-pickle-rce/) |
| CVE-2026-26215 | Unauth RCE via Pickle in manga-image-translator | [Blog](https://chocapikk.com/posts/2026/manga-image-translator-pickle-rce/) · [VulnCheck](https://www.vulncheck.com/advisories/manga-image-translator-shared-api-unsafe-deserialization-rce) |
| CVE-2025-34433 | Unauth RCE in AVideo via predictable installation salt | [Blog](https://chocapikk.com/posts/2025/avideo-security-vulnerabilities/) · [VulnCheck](https://www.vulncheck.com/advisories/avideo-unauthenticated-rce-via-predictable-installation-salt) |
| CVE-2025-34434 to CVE-2025-34442 | 9 additional vulns in AVideo: IDORs, open redirects, info disclosure | [Blog](https://chocapikk.com/posts/2025/avideo-security-vulnerabilities/) |
| CVE-2025-34452 | Path Traversal + SSRF in Streama | [Blog](https://chocapikk.com/posts/2025/streama-path-traversal-ssrf/) · [VulnCheck](https://www.vulncheck.com/advisories/streama-subtitle-download-path-traversal-and-ssrf-leading-to-arbitrary-file-write) |
| CVE-2025-34147 to CVE-2025-34152 | 6 unauth command injections in Aitemi M300 - **CERT-FR** | [Part 1](https://chocapikk.com/posts/2025/when-a-wifi-name-gives-you-root/) · [Part 2](https://chocapikk.com/posts/2025/when-a-wifi-name-gives-you-root-part-two/) · [CERT-FR](https://www.cert.ssi.gouv.fr/actualite/CERTFR-2025-ACT-052/) |
| CVE-2025-30007 & CVE-2025-30008 | Unauth XSS in Vembu BDRSuite | [Blog](https://chocapikk.com/posts/2025/bdrsuite/) |
| CVE-2025-2611 | ICTBroadcast unauth RCE - **VulnCheck KEV** | [GitHub](https://github.com/Chocapikk/CVE-2025-2611) · [VulnCheck KEV](https://www.vulncheck.com/blog/ictbroadcast-kev) |
| CVE-2025-2609 & CVE-2025-2610 | Stored XSS in MagnusBilling | [Blog](https://chocapikk.com/posts/2025/magnusbilling) · [VulnCheck](https://vulncheck.com/advisories/magnusbilling-logs-xss) |
| CVE-2025-2292, CVE-2025-30004 to CVE-2025-30006 | Auth vulns in Xorcom CompletePBX | [VulnCheck](https://vulncheck.com/advisories/completepbx-file-disclosure) |
| CVE-2024-31819 | Unauth RCE in AVideo | [GitHub](https://github.com/Chocapikk/CVE-2024-31819) |
| CVE-2024-35373 & CVE-2024-35374 | 2 unauth RCE in Mocodo | [Blog](https://chocapikk.com/posts/2024/mocodo-vulnerabilities/) |
| CVE-2024-30920 to CVE-2024-30929, CVE-2024-31818 | Research in DerbyNet | [GitHub](https://github.com/Chocapikk/derbynet-research) |
| CVE-2024-22899 to CVE-2024-22903, CVE-2024-25228 | Exploit chain in Vinchin Backup & Recovery | [GitHub](https://github.com/Chocapikk/CVE-2024-22899-to-22903-ExploitChain) |
| CVE-2024-3032 | Themify Builder Open Redirect | [WPScan](https://wpscan.com/vulnerability/d130a60c-c36b-4994-9b0e-e52f7f99387/) |
| CVE-2023-50917 | RCE in MajorDoMo | [GitHub](https://github.com/Chocapikk/CVE-2023-50917) |

</details>

---

### Tools

- [**cewlai**](https://github.com/Chocapikk/cewlai) - AI-powered wordlist generator (CeWL + CUPP + LLM in one binary)
- [**pgread**](https://github.com/Chocapikk/pgread) - Dump PostgreSQL data from heap files without credentials
- [**wpprobe**](https://github.com/Chocapikk/wpprobe) - Fast WordPress plugin enumeration (800+ stars, in Kali Linux)
- [**LFIHunt**](https://github.com/Chocapikk/LFIHunt) - Scan & exploit Local File Inclusion
- [**msf-exploit-collection**](https://github.com/Chocapikk/msf-exploit-collection) - All my Metasploit modules in one place

---

### Hall of Fame

[Ferrari](https://www.ferrari.com/fr-FR/hall-of-fame-responsible-disclosure-programme) · [Siemens](https://www.siemens.com/global/en/products/services/cert/hall-of-thanks.html) · [Philips](https://www.philips.com/a-w/security/coordinated-vulnerability-disclosure/hall-of-honors.html) · [Wikimedia](https://security.wikimedia.org/hall-of-fame/)
