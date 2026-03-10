# Valentin Lobstein

**Security Researcher & Exploit Developer**

[Blog](https://chocapikk.com) · [Twitter](https://twitter.com/Chocapikk_) · [LinkedIn](https://www.linkedin.com/in/valentin-l1337/) · [Ko-fi](https://ko-fi.com/Chocapikk)

---

### Highlights

- **CVE-2025-2611** - ICTBroadcast unauth RCE via cookie injection - **Added to VulnCheck KEV** ([writeup](https://github.com/Chocapikk/CVE-2025-2611) · [KEV](https://www.vulncheck.com/blog/ictbroadcast-kev))
- **CVE-2025-34147 to 34152** - 6 unauth command injections in Aitemi M300 WiFi Repeater - **Referenced by CERT-FR** ([writeup](https://chocapikk.com/posts/2025/when-a-wifi-name-gives-you-root/) · [CERT-FR](https://www.cert.ssi.gouv.fr/actualite/CERTFR-2025-ACT-052/))
- **CVE-2026-28515 to 28517** - 3 chained vulns in openDCIM: missing auth + SQLi + command injection = unauth RCE ([writeup](https://chocapikk.com/posts/2026/opendcim-sqli-to-rce/))
- **CVE-2026-27174 to 27181** - 8 vulns in MajorDoMo: 3 critical RCE, SQLi, 3 XSS ([writeup](https://chocapikk.com/posts/2026/majordomo-revisited/))
- **CVE-2024-22899 to 22903** - Exploit chain in Vinchin Backup & Recovery ([exploit](https://github.com/Chocapikk/CVE-2024-22899-to-22903-ExploitChain))

<details>
<summary><b>All CVEs</b></summary>

| CVE | Description | Links |
|-----|-------------|-------|
| CVE-2026-28515 to CVE-2026-28517 | 3 chained vulns in openDCIM: unauth RCE on Docker | [Blog](https://chocapikk.com/posts/2026/opendcim-sqli-to-rce/) · [Exploit](https://github.com/Chocapikk/opendcim-exploit) |
| CVE-2026-27743 to CVE-2026-27747 | 5 vulns in SPIP plugins: 2 SQLi, 2 RCE, 1 XSS | [Blog](https://chocapikk.com/posts/2026/spip-plugins-vulnerabilities/) |
| CVE-2026-27174 to CVE-2026-27181 | 8 vulns in MajorDoMo: 3 RCE, SQLi, 3 XSS | [Blog](https://chocapikk.com/posts/2026/majordomo-revisited/) |
| CVE-2026-26220 | Unauth RCE via Pickle in LightLLM | [Blog](https://chocapikk.com/posts/2026/lightllm-pickle-rce/) |
| CVE-2026-26215 | Unauth RCE via Pickle in manga-image-translator | [Blog](https://chocapikk.com/posts/2026/manga-image-translator-pickle-rce/) · [VulnCheck](https://www.vulncheck.com/advisories/manga-image-translator-shared-api-unsafe-deserialization-rce) |
| CVE-2025-34433, CVE-2025-34441, CVE-2025-34442 | Unauth RCE chain in AVideo | [Blog](https://chocapikk.com/posts/2025/avideo-security-vulnerabilities/) · [VulnCheck](https://www.vulncheck.com/advisories/avideo-unauthenticated-rce-via-predictable-installation-salt) |
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

- [**pik**](https://github.com/Chocapikk/pik) - Exploit framework & SDK for Go
- [**wpprobe**](https://github.com/Chocapikk/wpprobe) - Fast WordPress plugin enumeration (800+ stars, in Kali Linux)
- [**LFIHunt**](https://github.com/Chocapikk/LFIHunt) - Scan & exploit Local File Inclusion
- [**msf-exploit-collection**](https://github.com/Chocapikk/msf-exploit-collection) - All my Metasploit modules in one place

---

### Hall of Fame

[Ferrari](https://www.ferrari.com/fr-FR/hall-of-fame-responsible-disclosure-programme) · [Siemens](https://www.siemens.com/global/en/products/services/cert/hall-of-thanks.html) · [Philips](https://www.philips.com/a-w/security/coordinated-vulnerability-disclosure/hall-of-honors.html) · [Wikimedia](https://security.wikimedia.org/hall-of-fame/)
